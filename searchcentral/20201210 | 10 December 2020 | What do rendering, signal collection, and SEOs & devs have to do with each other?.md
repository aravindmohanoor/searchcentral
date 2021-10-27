[![What do rendering, signal collection, and SEOs & devs have to do with each other?](https://i.ytimg.com/vi/pxVFimtzrE0/maxresdefault.jpg)](https://www.youtube.com/watch?v=pxVFimtzrE0)

## What do rendering, signal collection, and SEOs & devs have to do with each other?

In this episode, Gary, Martin, and John draw (un)expected connections between rendering, signal collection in indexing, and SEOs & developers (not) working together. They also reflect back on the Virtual Webmaster Unconference. Have a listen!



Transcript for this episode → https://goo.gle/3ow3DgZ



Watch more Search Off the Record on YouTube → https://goo.gle/2JL3t5Y

Have a favorite way you like to listen to podcasts? Find Search Off the Record on most major podcast platforms → https://goo.gle/search-off-the-record



Google Search developer site → https://goo.gle/35HtREZ 

Search Off the Record on the Google developer Site → https://goo.gle/3qt1XGP



Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



Search Off the Record is a podcast series that takes you behind the scenes of Google Search with John Mueller, Gary Illyes, and Martin Splitt from the Search Relations team.



#SearchOfftheRecord



#### [0:00:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=0) |  [MUSIC PLAYING] JOHN MUELLER: Welcome, everyone to

the next episode of "Search Off the Record" podcast. Our plan is to talk a bit about what's happening at Google Search, how things work behind the scenes, and who knows, maybe have some fun along the way. My name is John Mueller. I am a search advocate on the search relations team here at Google in Switzerland.  

#### [0:00:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=30) |  And I'm joined here today by Martin

and Gary, who are also on the search relations team. How are you two doing? MARTIN SPLITT: All right. Can't complain. Could be worse. GARY ILLYES: I'm going to die. MARTIN SPLITT: We all are, eventually. JOHN MUELLER: But maybe not during this episode, please. Or not any time soon. GARY ILLYES: I'll do my best. MARTIN SPLITT: You're setting the bar quite low. JOHN MUELLER: All right, Gary, before it's too late, can you take us off? GARY ILLYES: Fine. It feels like I'm the only one that has a topic, anyway, all the time.  

#### [0:01:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=60) |  MARTIN SPLITT: How dare you. How dare

you. GARY ILLYES: In the previous episode, we talked about indexing. And I thought that was pretty cool. And other people also thought it's pretty cool. So I am going to continue with that topic. But first, one thing that I forgot, perhaps on purpose, to talk about was rendering. And in my brain, rendering works in a very interesting way. Basically, we have John's workstation that's basically rendering all the documents  

#### [0:01:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=90) |  that we are indexing. So you have

John Mueller standing in front of his computer and visiting random websites. And then his Chrome browser is outputting the dome of those web pages that he visited. And then that's sent to indexing. MARTIN SPLITT: That's accurate. GARY ILLYES: I got that right, right, Martin? MARTIN SPLITT: Yeah. And you forgot a detail. There's like, this entire pipeline where someone  

#### [0:02:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=120) |  gets the request and then puts a

little piece of paper onto, like, a little slide that then goes, like, to John Mueller. And then he basically has, like, these pieces of paper lining up over his computer. GARY ILLYES: No. MARTIN SPLITT: And there's this entire music thing that goes on like, duh, duh, duh, duh, duh, duh, duh, while all this is happening. And then, like, some steam comes out somewhere. Oh, Gary. GARY ILLYES: I feel like you're being sarcastic. MARTIN SPLITT: No! Me? Sarcastic? Never. Of course. JOHN MUELLER: Is this why I always get these weird advertisements in my browser?  

#### [0:02:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=150) |  MARTIN SPLITT: Yes. Exactly, that's why. Because

you click on all the things. GARY ILLYES: All right. Since you are being a jerk to me again, do you want to explain how rendering works? MARTIN SPLITT: Fine. Just because you are so nice and you are the chief of happiness at Google Search, I'll happily explain to you how this works. And actually, this is interesting because I know that last time you went into a little more details into how the crawling part of things works as well. And there's a bunch of moving parts involved here.  

#### [0:03:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=180) |  But eventually, once the crawling is done,

we have the initial HTML. The initial HTML is then passed on. It's part of the Caffeine system, really, that then uses a microservice that is called the web rendering service. And what that thing does is basically orchestrating or herding, if you want to, a bunch of Chrome instances across our cloud. And these Chrome instances get the HTML that comes from crawling and then basically do what your browser does if you visit a website. It uses the HTML to then construct the DOM tree.  

#### [0:03:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=210) |  It downloads the images. It downloads the

JavaScript, the CSS, all these resources, and then executes the JavaScript, just as your browser would do. And to do that we use an evergreen Chrome. So whatever we are updating to the latest stable version of Chrome, that is usually, like, a few weeks after new stable version of Chrome comes out, then we are also updating the web rendering service instances that we use for rendering. And then we have a bunch of systems that make sure that these browsers,  

#### [0:04:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=240) |  if they crash, they retry. If your

rendering fails for some reason, we can also retry. If something else goes wrong, we have error handling in place. We make sure that we get your website as it completes rendering, which sounds simple, but actually isn't because when is a website done rendering? When the HTML is there? Not really, because the JavaScript can influence the content as well. But when is the JavaScript done? Hm. That's also a tricky one to answer. But we are doing our best to actually give you  

#### [0:04:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=270) |  enough time and enough resources to complete

rendering. And then we have the HTML after JavaScript has run. Then that is passed on to other parts of Caffeine and used for indexing. Does that make sense? JOHN MUELLER: Is that something that happens for pretty much every page? MARTIN SPLITT: Yeah. JOHN MUELLER: I mean, that's, like, a lot more than I can load in my browser myself. MARTIN SPLITT: That is true. If you ever tried to, like, run Chrome with lots of tabs, you know that this is not an easy feat. But we are pulling this off with lots of magic and tears. GARY ILLYES: Back in the days when we could still  

#### [0:05:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=300) |  visit each other, and we've seen what

people are doing, and we had those desks that were all organized in an office, I remember that John's browser always looked crazy because he always had, like, 10 million tabs open all the time. And his workstation was always trying to take off and become the new Hubble telescope. So yeah. I'm still uncertain if what you said, Martin, is true,  

#### [0:05:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=330) |  or it's John actually doing the rendering.

Although now that he's working from home, perhaps that would be much harder. So maybe you are right. MARTIN SPLITT: I'm helping him. My laptop is also taking off because I'm also rendering some of the pages. And also, to be fair, in John's defense, you also sometimes have a bazillion tabs open. And there's even a photo that you took on Twitter that shows that you have lots of tabs open. So come on. JOHN MUELLER: Yeah. I mean, this is-- I don't know. Like, I don't want to distract from the awesome work  

#### [0:06:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=360) |  that the rendering people are doing because

if you have tried to open a lot of web pages fairly quickly, then you really see there is a lot of work that needs to be done to make all these pages load and to be able to look at their content. I don't know. I find that really fascinating. On the one hand, like the crawling and indexing side, those numbers are really impressive. GARY ILLYES: Yeah. JOHN MUELLER: But it feels like something that I can't really put into perspective. But thinking about--  

#### [0:06:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=390) |  I don't know-- opening millions of pages

in Chrome, I can kind of feel that pain. MARTIN SPLITT: Mm. And it is not easy because some web pages are built so-- how do I put this-- interestingly, that they are a true challenge to open in a browser. And we somehow still pull it off. And the team has worked not just for our benefit, but if you are using the Chrome DevTools protocol with things like Puppeteer, then that is partially work that the web rendering service team has done in order to be  

#### [0:07:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=420) |  able to use mainline or mainstream Chrome

to actually do this. And they also worked on reducing the memory footprint and the CPU footprint, so that we can run this at scale in the cloud. And anyone who has ever tried to automate rendering websites using a browser at scale knows that this is not a trivial task to accomplish. So like, hat tip to them. JOHN MUELLER: Yeah, that's pretty cool. GARY ILLYES: Can we install browser extensions on the headless Chromes? MARTIN SPLITT: I mean, if you run your own headless  

#### [0:07:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=450) |  Chrome on your own server, then you

can do that. Yeah. But not on the web rendering service. GARY ILLYES: No, the render. MARTIN SPLITT: No! GARY ILLYES: Oh, that's a pity. MARTIN SPLITT: Why? Do you want to bring back Flash? GARY ILLYES: No. I wanted to inject cats in pages that I don't like. MARTIN SPLITT: [CHUCKLE] Also, a fun fact. You can't mine bitcoins on our infrastructure. At least I know that people tried, and we are aware of this. So, no. GARY ILLYES: Really? MARTIN SPLITT: Yeah. That was a problem. That was one of the challenges that people are like, oh! Let's add this malicious JavaScript onto people's website. I mean, it's a fantastic money grab scheme, right?  

![](https://i.ytimg.com/vi/pxVFimtzrE0/maxres1.jpg)



#### [0:08:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=480) |  If you can infect lots of websites

and inject malware, then why don't you inject a JavaScript-based web GL Bitcoin miner? GARY ILLYES: Interesting. JOHN MUELLER: So what happens next after rendering, Gary? GARY ILLYES: Are you trying to steer the discussion away from moneymaking schemes? JOHN MUELLER: Yes, yes, yes. GARY ILLYES: OK. So there was rendering. There was a conversion that we talked about and also collapsing, basically getting rid of soft error pages.  

#### [0:08:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=510) |  Next, we start extracting more data from

the pages. And one of the things that we care about quite deeply is structure data. And there's not that much to say there. Basically what you see in the rich result testing tool is what we see. But we do extract all kinds of structure data. It's not just what the rich result testing tool validates, but pretty much any structure  

#### [0:09:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=540) |  data that you put on the page.

Now, this doesn't mean that you have to put every single kind of structure data on your page. But if you put something relevant, that will be extracted. Why? For entities. Basically, using structure data, we can infer some information about the entities that might appear on pages. And that's why we find that useful. And in this stage I think that's pretty much it.  

#### [0:09:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=570) |  Basically, this service just extracts the structure

data and passes it on to the services that might want to make use of it. So for example, the search result page might need-- I don't know-- recipe markup for presenting pages in the recipe carousel, let's say. And yeah. In this stage, there's nothing that much more that happens. But the next one, actually, the next step is actually  

#### [0:10:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=600) |  quite interesting because that signal extraction-- and

I said the bad word, "signals." And now everyone on Twitter will go nuts about it. And looks like John is also going nuts about it. But I would not overthink this just yet because there are lots of signals that are kind of not so exciting, I would say. In this stage of indexing, many of the signals  

#### [0:10:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=630) |  are just determining which version of the

content is, for example, canonical. Like, is it scraper.com or mysite.com that is the original publisher of a piece of content? And for that, we, for example, use different kinds of hashing algorithms. We hash the content or the centerpiece of the page-- Basically, the centerpiece is where the meaty part of the content is. We talked about this in a previous episode.  

#### [0:11:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=660) |  And we hash that part of the

content, and then we measure the differences between two versions of the potentially same content using these hashes. Why do we hash? It's because it's easier to compare shorter string than, for example, two dozen words. Essentially that's it. But we do have exciting signals here as well. For example, I will say the bad word-- PageRank. MARTIN SPLITT: [GASP] What?  

#### [0:11:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=690) |  GARY ILLYES: I know. JOHN MUELLER: So

you're adding the ranking of a page as a signal? GARY ILLYES: Not that page rank. So page rank is one of our main algorithms. And it's hard to believe it, but after 20 years we are still using it. It was used in the original backdrop version of Google, basically the alpha version, I guess, or beta version of Google in 1996, '97. MARTIN SPLITT: Are we still using the actual PageRank? Or have we replaced it with something similar?  

#### [0:12:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=720) |  Because I thought we are not using

the original one anymore. GARY ILLYES: The original one is still used. MARTIN SPLITT: Oh. GARY ILLYES: But obviously, it's been improved since then. And it's more robust, cheaper to run, et cetera. Basically, it's been improved. But it is still calculated. MARTIN SPLITT: But it's not what was displayed. Basically, if I know what my page rank was according to the Google toolbar back in the day for my page, that's not what we are using today. GARY ILLYES: That's never what we've been using. That's a dumbed down version of the PageRank algorithm.  

#### [0:12:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=750) |  MARTIN SPLITT: Ah. OK. GARY ILLYES: So

one thing. If you read the white paper about PageRank, one thing will be very obvious is that it's not a number from 0 to 10 or from nothing to 10. It's actually an integer. So it goes from 0 to 65,000 something. And then on that scale you land somewhere with your page rank. And then that number is used as a signal somewhere down the line, somewhere downstream.  

#### [0:13:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=780) |  But it does take a lot of

resources to compute this thing. I have a friend who's running their own version of PageRanker. Basically, he built a page ranker based on the white paper that we published. And he's using it for weird things like predictions, like NFL predictions or NBA predictions, and stuff like that. And it's surprisingly accurate. But it's very resource-heavy because you always have to-- it can be used for any link graph or graph-based system,  

#### [0:13:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=810) |  right, or graph-based structure. You don't necessarily

need the web pages to rank. But it is very resource-heavy because you always have to take into account the whole graph. Always. And that takes up lots of resources. You need to store that in memory. Then you traverse every single node. So it can get really hairy, especially if the graph is big. But that's one of the signals that we calculate here  

#### [0:14:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=840) |  based on the links pointing to the

page itself, and also the quality of those links. More links that are low quality will essentially increase your PageRank less than a few high quality links. So don't go buying links from link farms. MARTIN SPLITT: So you're saying we should buy links from high quality link farms? GARY ILLYES: OK. Don't buy links.  

#### [0:14:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=870) |  MARTIN SPLITT: Good boy. GARY ILLYES: I

guess. But this is awkward. So let's just talk more about signals. What other signals do you think we have? MARTIN SPLITT: Uh, Page Speed? GARY ILLYES: No. JOHN MUELLER: Train crossing signs. MARTIN SPLITT: Wait. What? GARY ILLYES: Basically it's not calculated here. MARTIN SPLITT: Ah. OK. It's not calcula-- So signals that we are calculating here. Is that what you're saying? GARY ILLYES: Yeah. In indexing. MARTIN SPLITT: Um. JOHN MUELLER: Keyword density. GARY ILLYES: Uh, what? Why would you even say that? MARTIN SPLITT: To make it awkward. That's what we're here for. Haven't you realized that yet? GARY ILLYES: No.  

#### [0:15:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=900) |  I thought that you are my sunshine

and happiness. But apparently not. MARTIN SPLITT: OK. Content quality of some sort. GARY ILLYES: No. MARTIN SPLITT: What main topic is, maybe. We could figure that one out semantically. GARY ILLYES: Yeah, maybe. That's perhaps not that bad of an idea. OK. I will help. Save search. JOHN MUELLER: Oh. GARY ILLYES: Like, you want to know at this stage whether a page contains porn or not.  

#### [0:15:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=930) |  Because we don't necessarily want to surprise

our users in our search results. So when they search for something like buttercup, for example, then you don't want to serve porn. You want to serve what they actually searched for-- the literal term. Then another signal that we calculate here is where are the pages local to? Which country. Or which metro area in certain countries. MARTIN SPLITT: Which language as well? GARY ILLYES: Yeah, language as well. Thank you for interrupting me.  

![](https://i.ytimg.com/vi/pxVFimtzrE0/maxres2.jpg)



#### [0:16:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=960) |  MARTIN SPLITT: Sorry! GARY ILLYES: But these

are all important signals for serving highly relevant results for people because if I'm in Switzerland and I search for-- I don't know-- kaese, then I don't want German results. Well, I rarely want German results. JOHN MUELLER: But why would you search for cheese in Switzerland and not want Swiss cheeses? GARY ILLYES: What? JOHN MUELLER: Oh, wait. German cheese. Yeah, German cheese. No German cheese. Just Swiss cheese, right? GARY ILLYES: Yes, that's correct. And then because we know that those pages are from  

#### [0:16:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=990) |  Switzerland-- don't make me laugh because then

I can't talk-- because if we know that those pages are Swiss, basically relevant to Switzerland, then we can give them a tiny boost in ranking based on the signal that we extracted during indexing. As you said, language is also important for similar reason. And yeah. I think those are the signals that I'm willing to talk about here. So based on these things so far, essentially,  

#### [0:17:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1020) |  you are a developer, and you build

a good web page, like good HTML, good JavaScript, good whatever. Then you should be able to do well in search. MARTIN SPLITT: Yeah. If only. GARY ILLYES: What? JOHN MUELLER: So just one quick thing. Are these signals a part of those hundreds of signals that we use? GARY ILLYES: Now that's a good point. Some of them will end up being ranking signals. Some of them will not. Some of them will. So for example saved search will definitely  

#### [0:17:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1050) |  become one of those ranking signals. Country

language, both of them will become. But most of the hashes that we use for canonicalization, for example, which we reserve for future episode, those don't end up as ranking signals. JOHN MUELLER: Yeah. OK. Cool. MARTIN SPLITT: [EXAGGERATED SIGH] If only people would just write, like, good stable HTML. And. GARY ILLYES: Yeah, everything would be better. And without JavaScript. MARTIN SPLITT: Whoa! What? JOHN MUELLER: JavaScript is OK. Yeah. No, no, no. We talked about rendering. Like, we heard JavaScript is fine.  

#### [0:18:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1080) |  I just have to refresh the page.

MARTIN SPLITT: Ah. But to be fair, there are developers who are basically, like, using JavaScript as the go-to tool for everything. And then they can paint themselves into corners. And then they're like, oh, what's happening. And lots of them discount SEO as something that they should be aware of or they should be, like, careful about. And that's my daily challenge, basically, to, like, bridge the gap between these two communities. And coming from a developer angle,  

#### [0:18:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1110) |  I'll probably focus a little more on

the developer side of things. But it is a two-way challenge in the sense that sometimes a few people in the SEO circles make very broad blanket statements. That does not exclude us, to be fair. I know that when I am on the go and tweeting, then I tend to say, like, oh, yeah. No worries. JavaScript will be fine, which is a blanket statement that I'd rather not make.  

#### [0:19:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1140) |  But every now and then I'm human.

I make mistakes. And our general perspective on search is that it's our job to make the world's information accessible and useful. So it's our job in search to be able to index and, like, showcase good content websites on the web to people searching for the thing that the websites are about. And so we'd rather have you worry about making good websites and then us worrying about the technical bits and pieces.  

#### [0:19:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1170) |  But I think developers do their part

to this, as well as SEOs working with developers are taking part in this entire equation. And if you say things like, JavaScript is bad or JavaScript is great, then that's very simplistic views of the issue or of the challenges that we are facing. And I'm trying to be as specific about this as possible. But even I fail every now and then by making these blanket statements.  

#### [0:20:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1200) |  But I find it tricky to talk

about these things because on one hand, if I get too technical with SEOs, they sometimes oversimplify it. And then there's, like, this game of telephone going on where I say something. And then an SEO hears part of that and talks to the developers, who hear only part of that. And then, like, some weird miscommunication happens that then is really hard to backtrack out of. But on the other hand, I wish that developers wouldn't  

#### [0:20:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1230) |  discount things such as SEO. But not

only SEO, also use experience, usability, accessibility, design, as like, yeah, whatever. This is, like, simple stuff. Because it really isn't. There are a bunch of things that you need to keep in mind and that are not necessarily easy to get right. I don't know if you observed this with developers as well, especially when you are at a conference, and you're like, hi, I'm talking about SEO. Like, everyone's like, oh. I'll go to another session, I guess. JOHN MUELLER: Yeah. But what kind of things do you find developers skipping over  

#### [0:21:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1260) |  when it comes to SEO? MARTIN SPLITT:

Ah. There's so many different things. One thing is using JavaScript where you don't have to. If you are building a very simple, mostly static website, let's say like, a blog that doesn't have that much interactivity, maybe comments, OK, fair, or maybe like an online shop or something like that, they oftentimes go for the shiniest, newest technology, which usually is somewhat experimental. For instance, most of the clients of JavaScript frameworks of the early days  

#### [0:21:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1290) |  were technically quite experimental ways of making

the browser do stuff that it couldn't do at the time, when they should have just opted for something existing, like a server side technology instead of doing everything in the client side. Because the server is a more controlled environment. We are now seeing the pendulum swing back. So all the bigger frameworks have server side solutions or investigating how they can do things on the server side, which I think is a good thing. Thinking about the architecture of their websites,  

#### [0:22:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1320) |  thinking about how the content should be

presented, how you deal with internationalization, if that's a concern for you. These things seem to be like afterthoughts, oftentimes. JOHN MUELLER: OK. So it sounds like it's more about adding complexity where there doesn't need to be complexity and making things more brittle through that complexity. It's not that it won't work at all. Because it sometimes feels like on the one hand, we're telling people, oh, JavaScript will just work fine for SEO.  

#### [0:22:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1350) |  And on the other hand, we're saying,

well, you should, like, avoid using JavaScript unless you really need to. MARTIN SPLITT: Yeah. JOHN MUELLER: And I can imagine developers are kind of like, just tell me what to do. MARTIN SPLITT: Yeah, that's what I mean. And I think, like, so there are scenarios where it absolutely makes sense to have JavaScript in the client side. If you are building a 3D design app or a product customizer or like, a catalog system with really fancy interactions or something  

#### [0:23:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1380) |  like that, then I understand that. If

you build a web application to design things in the browser, I understand that you are using JavaScript in the client side. But it's not a go-to tool. If you're making a marketing website with a landing page and, like, five different pages that show different products, then why are you using JavaScript in the client side for that? If you are a JavaScript developer, feel free to use the technologies that make sense to you. But try to make it as robust as possible. And yes, if you build a complicated and amazing and fantastic web application that needs all the interactivity,  

#### [0:23:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1410) |  we are here to help you. And

it will work in search unless you're doing something very fundamentally wrong. But that doesn't mean that you should always use JavaScript in the client side. I think that's a very important distinction there. And the other thing is also sometimes just very basic SEO concerns. If you have a link rel canonical on every page pointing to the home page, then why are you doing that? What was the thinking here? How do you deal with routing? Do you use fragments for routing?  

![](https://i.ytimg.com/vi/pxVFimtzrE0/maxres3.jpg)



#### [0:24:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1440) |  That's not a great idea for a

variety of reasons. If you are doing different ways of having different URLs landing on the same thing that then customizes the content, you should look at that. Don't just write a robots.txt because you think it's the trivial thing to do, and then accidentally block all your APIs from being crawled, and then the content doesn't show up. That's not a great thing either. Be careful with no index tags. All these kind of things that developers are just, like, yeah. I know how canonicalization works.  

#### [0:24:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1470) |  And then they don't. JOHN MUELLER: OK.

So basically you're saying, developers should take SEOs more seriously. MARTIN SPLITT: Yeah. JOHN MUELLER: OK. MARTIN SPLITT: But also, SEOs should be aware of their responsibility to not cry wolf whenever there's something that they are not fully sure about. Make it a conversation. Have these conversations. Let your developers explain why they chose JavaScript. Hold them accountable for what they are doing. And also, guide them in when they are making decisions. Don't show up after they made all the decisions and ask them to redo everything from scratch.  

#### [0:25:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1500) |  Then it's too late. JOHN MUELLER: Yeah.

GARY ILLYES: I would just blame them. JOHN MUELLER: No. MARTIN SPLITT: That's a fantastic idea. Mm. The blame game. Lovely. JOHN MUELLER: No! It's like, you have to work together. MARTIN SPLITT: Yes. JOHN MUELLER: I think there's always room for both sides. But it does sometimes come across to when I talk with developers that they're like, oh, SEO is this voodoo magic thing that you don't really need, according to Google. But there are just so many things involved with SEO  

#### [0:25:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1530) |  that, from my point of view, are

critical to making a website accessible online on the web, and especially in search. So it's certainly not something that you can just ignore. And kind of I think your comparison to accessibility, usability, design, that's very apt there. It's not that, it's like, oh, I will just make everything light gray on dark gray. And then I will be a designer. That's not really how it works. But I found a lot of these things  

#### [0:26:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1560) |  also came up in the recent unconference

that you organized, Martin. MARTIN SPLITT: Yeah. JOHN MUELLER: I thought that was really cool. MARTIN SPLITT: Oh. Thank you. How is your impression of the event as a facilitator? Because you facilitated the session. JOHN MUELLER: Yeah. I thought it was really cool. So these were small groups, I think around, like, 20 people. I took part in the one for mobile first indexing and the one for talking about SEO, of course. And in both of these sessions it was a really nice mix of people. So there were people who were fairly fresh who were like,  

#### [0:26:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1590) |  oh, I just started with SEO this

year and is like, I have no idea what you all are complaining about, or kind of like all these inside jokes. I don't get them. So that was really cool. From my point of view, I find it a really nice sign that there are more and more kind of new people joining the SEO side as well because that kind of confirms that maybe SEO is not a fad that is just going away. Maybe that will stick around, which is, I think, good for the community in general and the whole ecosystem.  

#### [0:27:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1620) |  There are also people there who are

working with really large sites. There are people there who mostly work with small businesses. And kind of getting that mix of feedback was really interesting. Like, especially the ones working with small businesses are like, we don't have to get everything perfect as long as we're a little bit better than our competitors. That's good enough. And it's like, that's a perfect approach. MARTIN SPLITT: That's true. JOHN MUELLER: You kind of have to focus your work on things that matter.  

#### [0:27:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1650) |  And you don't have to be absolutely

perfect when it comes to SEO. But. MARTIN SPLITT: We also try to balance our attendees a little bit across the world. So I hope that that also came through. JOHN MUELLER: Yeah. No. Different people from different locations was really cool. Time zones, of course, is tricky. MARTIN SPLITT: Yeah. JOHN MUELLER: I think we had one or two people from India in our sessions. And for them, it must have been middle of the night somewhere. But otherwise, that was really nice. Also a really nice mix of genders. It was fairly balanced.  

#### [0:28:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1680) |  That was really useful. And I think

it's something that sometimes goes missing with a lot of the online events where you have the same people speaking over and over again. You just hear their opinions. And it's like, I work for this really large company and work with these giant clients. And that's one part of SEO. But there are so many people who are working on kind of normal websites, normal businesses. And that was-- I found that really cool. So do you think we should be doing more of these?  

#### [0:28:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1710) |  MARTIN SPLITT: Definitely. So this was, like,

our pilot event. And we have been receiving very overwhelmingly positive feedback. And I know that I broke a lot of hearts with sending lots of people emails that they didn't make it, they didn't get in. And I know that that is not optimal. But as you say, like, these discussions unfolded in smaller groups. And I doubt that they would have unfolded in larger groups. There are only so many people facilitating sessions. We got the conclusions from every facilitator. That was great. So we will be publishing a blog post about this.  

#### [0:29:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1740) |  Or by the time this episode comes

out, maybe there is already a blog post. So check out the Google Webmaster blog. And yeah. We think with all the positive feedback and also with the time zone challenge, we will definitely run more localized events across different time zones so that people can jump into the one that makes sense for their time zone. And by having more of these and maybe even doing them more regularly, like, once a quarter or at least, like, twice a year or something, there will be more chances of getting a spot even though we will have  

#### [0:29:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1770) |  to continue to probably limit the amount

of people, because whenever we are putting out an event, whatever kind of event it is, this for participants fill up very, very quickly. JOHN MUELLER: Yeah. No. I think it's really cool. I mean, it's also kind of this big gap that we have because we don't have physical events at the moment. It's like, it would be really nice to do some kind of real physical event type thing. Maybe we can start doing those early next year. Probably not, I guess.  

#### [0:30:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1800) |  MARTIN SPLITT: We'll see. We'll have to

see. GARY ILLYES: You are very optimistic there. JOHN MUELLER: Yes. Everything will get better. Like, after Christmas, it's just, like, one uphill stretch. GARY ILLYES: Oh. MARTIN SPLITT: Uphill stretch. In infections? Or-- JOHN MUELLER: No. No, no. It'll just get better. Everything will be better. GARY ILLYES: OK. JOHN MUELLER: I'm sure. MARTIN SPLITT: OK. GARY ILLYES: That's what you asked for from Santa? Or-- JOHN MUELLER: Yeah. Exactly. GARY ILLYES: How does that work? JOHN MUELLER: We should just all send a note to the North Pole saying, make everything awesome again, and let us have real conferences.  

#### [0:30:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1830) |  GARY (SINGING): Everything is awesome. MARTIN SPLITT:

We'll also probably do another virtual event where we don't have to limit the amount of participants later this year. So at least we have that. But yeah. The physical events would be amazing. That would be great. I miss it. JOHN MUELLER: I mean, as many people as possible can also listen to our podcast. So it's not-- GARY ILLYES: That's true. JOHN MUELLER: --like we're limiting things there. Or they can watch all of our videos. It's like, you can binge watch the webmaster  

#### [0:31:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1860) |  channel on YouTube if you really miss

hearing us, seeing us. So that's an option. MARTIN SPLITT: There's also no limits on the seats for the office hours. That's also a thing that we're doing if you want to join these. JOHN MUELLER: Cool. All right. MARTIN SPLITT: Fun times. JOHN MUELLER: Sounds like lots of stuff is lined up. Cool. OK. So maybe we can take a break here. Thank you for all of the cool insights from rendering and indexing and talking with developers. I thought that was pretty cool.  

#### [0:31:30](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1890) |  To everyone listening in, thank you for

listening to the podcast. I hope you found it insightful and kind of fun. I certainly found it that. And feel free to like and subscribe and follow us for more information as things move along. MARTIN SPLITT: Send us follow links. JOHN MUELLER: Follow links. Yeah. Yeah. GARY ILLYES: No follow links. I only want no follow links. MARTIN SPLITT: Sponsored. JOHN MUELLER: But what about subscribe? Subscribe links. GARY ILLYES: Subscribe-- what? What are you ta-- what? That's not a thing. JOHN MUELLER: OK. MARTIN SPLITT: Great.  

#### [0:32:00](https://www.youtube.com/watch?v=pxVFimtzrE0&t=1920) |  Maybe we should make it a thing.

JOHN MUELLER: OK. See y'all later. Bye. MARTIN SPLITT: Bye bye. GARY ILLYES: [NON-ENGLISH] [MUSIC PLAYING]  