[![JavaScript SEO office hours November 25th, 2020](https://i.ytimg.com/vi/6hFm34j9Zk0/maxresdefault.jpg)](https://www.youtube.com/watch?v=6hFm34j9Zk0)

## JavaScript SEO office hours November 25th, 2020

In the JavaScript SEO office hours, you can ask your questions about Google Search and JavaScript. You can either join the recordings live or post questions in the relevant thread on youtube.com/c/GoogleSearchCentral/community



#### [0:00:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=0) |  MARTIN SPLITT: Hello, and welcome to the

JavaScript SEO Office Hours here at Google Search Central. If you hadn't seen them beforehand, we have office hours for general SEO questions as well as JavaScript SEO questions, as well as Japanese Office Hours. And then we have e-commerce office hours. So if you have questions, drop over to our YouTube channel, youtube.com/c/go oglesearchcentral and check the Community tab for upcoming office hours. I'm super happy to see that a few people have joined today  

#### [0:00:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=30) |  and a few people have submitted questions

on the YouTube thread. So we'll go through the YouTube questions first, and then I'll open the floor for questions from the audience here. Excellent. So Jeff James asked, "If part of a pages render server side initially, then uses client side rendering, does that influence Google's decision to render the JavaScript component of the page? We can see crawlers where only about 20% of the server side requests from Googlebot on a certain page show up for client side versions or assets."  

#### [0:01:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=60) |  Generally speaking, that should not make a

decision-- or it should not influence our decision to render pages. We are pretty much rendering all the pages. But sometimes your JavaScript might time out, or there might be a caching issue, which might mean that we are not seeing all your content. Unless you have an indexing issue, I wouldn't really think about this. As long as your content is showing up in searches, then you should be fine. It's not really something that you need to actively monitor. Oh, hold on. The question is actually longer. "Is this in contrast to a page where rendering is done  

#### [0:01:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=90) |  exclusively for JavaScript?" No. There is a

heuristic that tries to understand this, but this heuristic is very rarely used, only for certain legacy domains. So it is not really a problem that you need to work with. Just make sure that you version your assets properly, and it should be fine. Also, the amount of crawling does not really mean much. This might just be a crawl-- what's it called-- a crawl rate-related thing that you might be seeing in Search and server logs.  

#### [0:02:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=120) |  Also, be aware that some fake bots

pretend to be Googlebot, so server logs need to be taken with a grain of salt. You need to verify that it's a Google IP address that the crawl came from, because anyone can say, yeah, I'm Googlebot. And we see lots of fake Googlebots out there. So I wouldn't worry about that, unless you see specific issues with content not showing up in Search. Phillip asked, "How do you prefer to measure CPU and RAM consumption when the browser loads the URL or website?  

#### [0:02:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=150) |  And what are acceptable ranges? This may

be more general, but in most cases, the problem is on the JavaScript side. And high CPU or RAM consumption could lead to a partial indexing because Googlebot will not process all content on the URL." That is true. We do limit CPU consumption. Mostly it's CPU time, actually, that we are limiting, but mostly to catch things such as infinite loops and other issues. So I wouldn't be worried too much specifically about this.  

#### [0:03:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=180) |  I have personally seen very few cases

where this was a problem. In all of the cases I've seen, that was incorrect code or basically broken code that ran into infinite loops and then wasn't indexing the rest of the content because the code never actually reached it. The general thing is, I'd rather not give a specific time or range, or whatever kind of measures, because, a, these are implementation details that can change at any point in time. B, we are also using heuristics, so it's not really  

#### [0:03:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=210) |  a clear-cut number or range that I

can give you. The general recommendation is, make it as fast as you can with as few CPU resources as you can. If it takes a MacBook two minutes of spinning the CPI at 100%, that may be not great for users, either. So think about it from a user's perspective. If you are consuming CPU resources on end for lots of time, your users will probably be unhappy.  

#### [0:04:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=240) |  Especially on mobile phones, that is really

a killer. So try to optimize as much as you can, but be reasonable about it. Because in the end, if users are seeing your content and everyone is happy and it's also showing up in Search, you shouldn't worry about this. Again, this is something that you can go into and profile and debug when you are seeing an issue. I wouldn't proactively look too much, unless you really hear your fans spinning up at 100% after a couple of minutes of trying to load a website. That's usually a really bad sign.  

#### [0:04:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=270) |  And those are the two questions we

have from YouTube, which means we can now open up the floor for questions. And I've seen various people here on the call today, so that's pretty cool. If you have any questions, feel free to just ask them. You can also use the chat function on the right-hand side of this Google Meet recording if you don't want to ask a question by voice. Any questions? AUDIENCE: Hi, Martin. MARTIN SPLITT: Hi, Dave.  

#### [0:05:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=300) |  AUDIENCE: Just a quick one. Content visibility--

the new CSS property that starts running around [INAUDIBLE] until it hits [INAUDIBLE]. Is there any implications from Google's bots of using this at all? MARTIN SPLITT: I don't think there is any problem with it. I haven't tested it yet. That's a really good question. I love it when you're in these Hangouts because you always ask questions where I'm like, oh, I should actually definitely test this. I expect this to work out of the box as we are upgrading the Chromium renderer,  

#### [0:05:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=330) |  and it should fall back reasonably. But

I definitely recommend testing this out and making your own conclusions until I have had a look. And probably we have some guidance on this. If you don't see any guidance coming up in the next couple of months, that just means it works out of the box and doesn't need any specific things. And to be honest, if it doesn't work, then that's a problem on our side that we will need to fix sooner rather than later. Very good question. Thank you. AUDIENCE: All right. Thank you. Thank you for having the answer.  

#### [0:06:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=360) |  MARTIN SPLITT: Very happy. I know that

"I haven't tested it" is not the greatest answer ever, but there's so many things that I need to test. AUDIENCE: More hours in the day. That's what we need. MARTIN SPLITT: Yeah, definitely. All right. Anyone else have any question? Now is your opportunity. You can, again, also use the chat if you'd rather not pipe up. Let me refresh the YouTube set, because sometimes people are posting to YouTube a little late.  

#### [0:06:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=390) |  No, it doesn't look like it. Newest

first. Yeah, this is a really unfortunate thing that you have to actually say sort by newest first to actually see all the comments. Any questions? AUDIENCE: Yes. Hi, Martin. MARTIN SPLITT: Hi. Awesome. AUDIENCE: I have a question about [INAUDIBLE] vitals, particularly the fact that the APIs, as far as we know,  

#### [0:07:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=420) |  are currently not supported on Firefox and

Safari. They're only supported by the Blink-based browsers. So my question is, do you have any recommendations if you're looking to test the optimized websites, particularly for those browsers? Are there any particular metrics that you would use to replace Largest Contentful Paint? Like, what are the ones-- if you had to come up with a, let's say, workflow,  

#### [0:07:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=450) |  are there any particular metrics that you'd

use? And how would you go over this problem? MARTIN SPLITT: I'm not sure about Safari's dev tools, but I know that the Firefox has great developer tools. But they don't really have anything that allows you to gather real user metrics, so you would have to fall back to gathering field data-- not field data-- lab data, sorry. So if you don't get any field data, then lab data is not perfect, but it is better than  

#### [0:08:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=480) |  having no data whatsoever. So I would

definitely just dive into the developer tools and do the performance audits with the developer tools that you have there, and probably also try to find some users or someone in your team who happens to have devices that are not top-of-the-line devices to actually run the performance profiling there as well. But that's the best you can do. I do hope that the proposed APIs are running in other browsers as well, because I think having more field data is just  

#### [0:08:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=510) |  generally useful. But if you can't, then

at least use some lab data. AUDIENCE: Got it. Thanks. MARTIN SPLITT: Sorry for not having a good answer. This is like-- every browser is figuring out this performance thing so far. So it takes a while for everyone to come up with ways of gathering information. Also, I think Firefox might have a philosophical stance on the point of gathering field data.  

#### [0:09:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=540) |  Can't speak for Mozilla, though. All right.

More questions? Five comments. AUDIENCE: If there's no one, maybe just a follow-up question, then. What would be-- I'm not sure if you're the right person to ask because I don't know how much invested you are in web performance, actually. But let's say you cannot use Largest Contentful Paint. What would be your other, let's say,  

#### [0:09:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=570) |  favorite-- or maybe not favorite, but most

useful metrics for measuring renderer performance? Do you have any thoughts on that? MARTIN SPLITT: Yeah, I do. Actually, I am relatively invested in web performance, and I used to be very, very invested, having worked for a startup that does VR on the web for architectural applications. If I can't do that, I would look into frame timings. I would try my best to see if we can basically hit 60 frames per second as quickly as possible,  

#### [0:10:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=600) |  because that's a good approximation for, a,

does something hog up the GPU. And, b, something hog up the main thread? Because if something is blocking the main thread, that usually results in frame drops quite quickly. AUDIENCE: OK, cool. Thanks. MARTIN SPLITT: You're welcome. Also, frame timings are relatively-- well, relatively easy to measure. I'm saying "relatively" to other things. Like, Largest Contentful Paint is really tricky to measure yourself unless you have the APIs that  

#### [0:10:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=630) |  give you this information. Whereas frame timings,

you can measure that within a request animation frame loop and then measuring at times. It's still not easy. It's not easy to get accurate frame timings, but it's easier than the other options, I think. All right. Ah, OK. Here's a question from Muhammad in the chat. "How long a bot can wait for rendering a JavaScript code?"  

#### [0:11:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=660) |  I'm guessing "JV code" is JavaScript. Well,

I don't like that this question gets asked because it's telling me someone is gaming with a bot, and that's a bad idea. As quickly as possible. Do it as quickly as possible. We do wait quite a bit, but users don't. So even if for the bot it is OK, users might not be so happy. So try to get your JavaScript over the wire as quickly as possible and get the content on the screen  

![](https://i.ytimg.com/vi/6hFm34j9Zk0/maxres1.jpg)



#### [0:11:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=690) |  as quickly as possible. If you're talking

tens of seconds then, you're already having a problem. I know that some websites take minutes and they are still indexing fine, but they're definitely not making users happy. All right. Any more questions? Seeing that we have nine people here.  

#### [0:12:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=720) |  Well, it's eight and then me. Now

is your opportunity. Don't be shy. And again, if you are shy, that's perfectly fine. You can also use the chat. Asking questions in the chat is perfectly acceptable. Quiet.  

#### [0:12:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=750) |  In that case, let me ask a

question. If you are here in these JavaScript SEO Office Hours, what brought you here? What is a thing that you are concerned about? What is a thing that you have experienced that didn't go so well? What kind of JavaScript frameworks have you been working with? Feel free to put it in the chat or just talk. That's also perfectly fine.  

#### [0:13:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=780) |  Quiet group today, huh? Also, I'm trying

not to butcher names, but I'm really not sure how to pronounce-- is it a Polish name? AUDIENCE: It is. It's a Polish name. MARTIN SPLITT: Is it "Jee-mo-wit"?  

#### [0:13:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=810) |  AUDIENCE: "Jee-mo-vit." MARTIN SPLITT: "Jee-mo-vit." Ha. I

wasn't too bad. I was super afraid to answer your question and start with a name that is pronounced incorrectly. And I'm very sorry that I was a little scared about screwing it up. So "Jee-mo-vit." AUDIENCE: That's correct. And I completely understand. It's rare even for Poland, so I'm used to it. MARTIN SPLITT: Interesting. I'm super sorry again. I'm super happy that you're here, and I'm very happy to learn. You know what? I'll see if I can pronounce people's name.  

#### [0:14:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=840) |  So Carolyn is probably correct. Dave Henning.

Henning. You from Germany or Austria or Switzerland? Sounds like a very German name. AUDIENCE: Yes, from Germany, Hamburg. MARTIN SPLITT: Hamburg. Ah. AUDIENCE: Yeah, but I live in Barcelona. MARTIN SPLITT: Oh, wow. OK. That's really nice. That's lovely. AUDIENCE: Yes. Yes. MARTIN SPLITT: I mean, Hamburg is nice, too. It's just a little more cold, I guess. AUDIENCE: Yes.  

#### [0:14:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=870) |  Gray. MARTIN SPLITT: Gray as well. Gray

is probably also a problem. That's true. AUDIENCE: Exactly. MARTIN SPLITT: Cool. Barcelona. Coming from Hamburg to Barcelona. That must have been an interesting change of pace and scenery. AUDIENCE: My wife come from here. And over the years, we spent so much time here before we change. So nothing new for me. MARTIN SPLITT: Right. It wasn't like a drastic change. OK. I get it.  

#### [0:15:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=900) |  AUDIENCE: No, not [INAUDIBLE]. MARTIN SPLITT: Then

I think we have Muhammad. "Moo-ha-mod." I'm never sure which way to pronounce these. "Se-veh-lay"? "Ta-mash"? "Toh-mush." "Toh-muck." Come on. [INAUDIBLE] AUDIENCE: "Toh-muck." MARTIN SPLITT: And "Tah-mash" is right? AUDIENCE: Yeah. From Hungary. AUDIENCE: That's the official name, but everybody calls me "Thomas." MARTIN SPLITT: I see. Let's see. So we have Tomasz from Poland, and then we have Tamás from  

#### [0:15:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=930) |  Hungary. Nice. AUDIENCE: Exactly. MARTIN SPLITT: That's

pretty cool. Unknown, I think, is Symon, but I'm not sure. And then we have Ziemowit. OK. And then we actually have a comment from Carolyn in the chat. "I used to work for a company who used AJAX JavaScript to create product pages. It is commonly discussed in the SEO world that AJAX is not ideal for SEO. But also have seen the pages got not indexed properly. But what do you think? And is AJAX really not ideal for SEO?"  

#### [0:16:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=960) |  Well, that's a really good question, Carolyn.

Thank you very much for sharing this with us. So what AJAX really means is-- it's actually a bit of an anachronismus. Or anachronism, I think, is the English word. "Anachronismus" is a very German way of thinking about it. Anyways, it's like-- so when we used to build websites in the olden days, what would happen is you have-- you make a request to the server, you get the website,  

#### [0:16:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=990) |  and then that's it. That's the entire

interaction that happens. And then at some point, we're like, but it would be cool to kind of get data back to the server, like if I want a contact form or guestbook or comments. So the way that works is basically you go to the website. The server responds with the HTML and then some form in the HTML. And then you would fill that in, click Submit. That would submit it to the server. The server would submit-- would send back a new website pretty much. That's how that worked, which means you have this page  

#### [0:17:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1020) |  refresh in the middle. So you have

this flash of white in the middle when the server gets the data from you and before it has given you the response back, like, thanks for your contact request, or here's the new website, the new article with the new guestbook-- not guestbook-- guestbook comment that you just wrote in it. And then we came up with this idea of, hey, hold on, couldn't we-- instead of basically refreshing the entire website, couldn't we just use JavaScript to send-- so you have this form where  

#### [0:17:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1050) |  you can type in your comment under

a blog post, for instance. And you hit Submit, and instead of actually refreshing the entire website, JavaScript makes the request in the background. And then the server responds back, and then we can reload the page. Or even better, we can basically just change the page because we have all the page, so we can add new stuff using JavaScript. And that's where AJAX comes from. AJAX stands for Asynchronous JavaScript and XML. So originally, you would make asynchronous, which means  

#### [0:18:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1080) |  in the background, kind of. Asynchronous means

a little different, but for the sake of this explanation, in the background is good enough. So in the background, JavaScript makes a request and gets XML back. And then from that XML, you would create the HTML that you need. And then there were variations of it. So AJAH, as in A-J-A-H, would be basically Asynchronous JavaScript and HTML. So the response back to that JavaScript request would be HTML, and then you can just plug that HTML  

#### [0:18:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1110) |  straight into the page. And then there

was "AJAJ," I guess you would pronounce it-- A-J-A-J-- which is Asynchronous JavaScript and JSON, JSON just being a different representation. So XML, HTML, and JSON are just structured ways of sending data. If you look at an HTML document, it's structured information. It's like, this is the body, this is the title, this is the headline, this is the subheadline, this is the link, this is a button, and so on and so forth. It's just structured information.  

#### [0:19:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1140) |  You can use other things. Like XML

is a more flexible way of structuring information. And JavaScript Object Notation, or JSON in short, is another way of structuring data. And is this bad for SEO? Yes and no. It made life harder for search engines because no longer we can just make a request to the server and get the website, because now some content might be loaded with JavaScript. So you make a request, get pretty much an empty website back, and then JavaScript does these AJAX  

#### [0:19:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1170) |  requests to actually fetch more data and

put it into the website. But since a couple-- over the years, Google has been at least very capable in terms of running JavaScript. So the AJAX requests themselves are not really a problem. But they are additional complexity, and complexity is usually a thing that you want to minimize as much as you can. You cannot really avoid it, but you can minimize it. And the reason why I'm saying is that there are more ways of things going wrong--  

#### [0:20:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1200) |  more ways for things to go wrong.

For instance, what if this JavaScript request that fetches data to show on the website is roboted, if for some reason your JavaScript makes a request to /api/cats to get a list of cats to show on the website and then robots.txt says, /api/ is disallowed. It works in the browser because the browser doesn't really care for a robots.txt. But it doesn't work in Google Search because we do care for the robots.txt. And then we are basically seeing this empty website.  

#### [0:20:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1230) |  We are running the JavaScript. The JavaScript's

like, can you fetch me /api/cats. And then the robots.txt says, no, you cannot. And then we're like, whoops. It's harder to test these things. It's harder to fix these things. So it isn't fantastic for SEO, but it's not really a problem, either, because once you implement it properly, it's fine. It's not a problem. Yet I would say it's additional complexity that you don't necessarily need, unless you have a good reason.  

#### [0:21:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1260) |  AUDIENCE: Thank you very much for explaining

it that well. That was really good. Thank you. MARTIN SPLITT: You're welcome. Trying my best here. [INAUDIBLE] is asking, "Does it affect the rest of the content if some JavaScript code is blocking rendering some part of the content on the page?" Yeah. So let's say you have a piece of JavaScript that doesn't finish forever. It basically is stuck. We would run through the page, we would run that JavaScript, and then get stuck. And eventually it would stop rendering because it's like, OK, this gets stuck,  

#### [0:21:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1290) |  so we have to try again later.

And in that case, we don't see the content that this JavaScript would fetch. We don't see the content that would be in the HTML after the blocking JavaScript, either, because the processing would be stuck at that point. So that is the potential problem in terms of indexing. All right. Do we have more questions now that we all got to know each other a little bit and got the ball rolling? Again, feel free to use the chat if you don't want to speak up.  

#### [0:22:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1320) |  Oh, Henning is asking, "I saw a

problem with prerendered pages for the Googlebot with prerender.io. Sometimes these pages are not up to date anymore, and therefore the resources, so like JavaScript and CSS, are no longer accessible because the hash in the file name has changed. Can this influence the indexing, or does it only influence rendering?" Well, so what prerender.io does is basically dynamic rendering.  

#### [0:22:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1350) |  And it is tricky. So the reason

why prerendering is a tricky thing-- and when I say prerendering, I don't mean the actual prerendering. Let me run back. So there's a bunch of different ways of doing things. One way is-- let's say you have blog. This blog only ever changes if you update a blog post or create a new one or remove an old one. So you know exactly when it changes.  

![](https://i.ytimg.com/vi/6hFm34j9Zk0/maxres2.jpg)



#### [0:23:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1380) |  If you are using some JavaScript, you

could basically run this on your machine and make it generate all the HTML and then only upload the HTML, because this HTML only changes when you make a change. That actually is prerendering, or what's usually named prerendering in developer circles. Then there is client side rendering, where you have a bunch of templates in HTML, and then you have some JavaScript that fetches data from the APIs or back-ends or CMSes or whatever. It doesn't really matter.  

#### [0:23:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1410) |  The JavaScript in the browser grabs the

additional content and puts it in the HTML. That's client side rendering. And then you could do server side rendering, which you can do with JavaScript, with Python, with Perl, with PHP, with Java, with ASP.NET, with Golang, with REST. I don't know. Basically, that works by sending some request. Then some program runs, and that could be a JavaScript program, generating the HTML. And then you send the HTML back. That also works. And then there's what we call dynamic rendering  

#### [0:24:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1440) |  that you normally only do for bots

with things like Rendertron or prerender.io or any of the other providers out there. And what that does is that basically a request comes to the prerendering service-- from Googlebot or from users, if you configure it that way-- comes to one of the prerendering services. The prerendering services open a browser on the server that then makes a request to the actual server that then gets the response back, runs all the JavaScript, waits until there's HTML in the browser,  

#### [0:24:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1470) |  and takes that HTML snapshot and sends

it over. Do you see a problem here? You should, because opening a browser on the server, opening the page in that browser, waiting for that page to load, that takes time. So these requests are usually a lot slower. And I don't know. Have you ever seen a browser crash? I did. Just this morning, a browser crashed on me on my phone. A few days ago, my browser crashed on my laptop. Browsers can crash.  

#### [0:25:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1500) |  So what happens then? Well, then we

have to catch that crash. Then we have to re-open the browser. It takes even longer. If our code here in the prerender solution isn't great, then maybe it doesn't notice that the browser crash sends back empty HTML. So it invites a whole new load of problems, and it takes a long time. So because it taking so long, oftentimes you would instead basically cache these things. So you would say, oh, we don't always open it in a browser. We open it once and then catch the HTML that we'd get for a day, for an hour, for five minutes,  

#### [0:25:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1530) |  because that's usually good enough. Sometimes these

caching decisions are not great because you might cache too long, or you might not cache long enough and then things get slow again. So prerendering isn't the silver bullet that magically makes all the problems disappear. If this happens, when it tries to access resources that it doesn't have anymore, with the CSS it's probably fine, because that's-- the web will succeed nonetheless.  

#### [0:26:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1560) |  Like, it should be fine. The content

should still be there. It might look weird, but that doesn't really matter that much. If the JavaScript resources fail-- and the JavaScript is what actually fetches the content-- then the rendered HTML by the prerender solution might miss the content. And if it misses the content, then the indexing won't see it. So it's not just a render issue. If content is missing in rendering, or after rendering, then indexing can't index it either. So that can immediately become or escalate  

#### [0:26:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1590) |  into an indexing issue for you, which

is why I would keep the old assets around for a while to make sure that you're not running into these problems. I don't know how long prerender.io caches things, but yeah, I would keep the old versions around. Also, I see that Tomasz has raised his hand. Tomasz, what can I do for you? AUDIENCE: Hi, Martin. Hello, everyone. I have a question for you, Martin. What kind of analysis you run on initial HTML?  

#### [0:27:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1620) |  MARTIN SPLITT: What kind of analysis do

we run on initial HTML? Pretty much anything that we also run on-- well, that's not true. We run a few things on the initial HTML. One thing is it's early link extraction. So once we have HTML, we can immediately have a look if this looks like a link-- or if it has something in it that looks like links, because then we can immediately queue them for the scheduler. We obviously do that, again, once we have rendered, because usually that produces  

#### [0:27:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1650) |  more links that we need to queue

for crawling. But that's something that we do on the initial HTML. We also, I think, try to understand if this is an error or not. So if it comes back with a 404, that's not really the HTML. But if the initial crawler comes back with a 404, then we treat it as such. So you can't really use a 404 page to run JavaScript to load some content. I've tried that in the past and got everything de-indexed-- not a good strategy, really not a good strategy.  

#### [0:28:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1680) |  We also look for meta tags. So

if there are canonicals in there, if there is a meta description in there, or if there is a meta robots in there, we definitely do look at those. Which also means that if you say noindex in the meta robots in the initial HTML and then the JavaScript runs, you have a problem, because when the initial HTML contains a meta noindex, we're like, oh, this page doesn't want to be indexed, so we don't need to render this.  

#### [0:28:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1710) |  Because you already told us you don't

want this to be indexed. So be very really careful with that. I think we also try to do canonicalization at this point, at least dedup management, which sometimes does not give us clear signals. And in that case, we might ignore the initial canonical tag. We might ignore the initial-- basically content hashing that we do on the initial HTML, if the content hash differs in the rendered HTML.  

#### [0:29:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1740) |  So canonicalization being a longer running process

starts in the initial HTML but also takes into account what happens in rendering. What else do we do in the initial HTML? Nothing that I can think of right now. Let me actually see if I can-- do I have the slide? [INAUDIBLE] a copy of the slides, but that works as well. Let me see if I forgot something.  

#### [0:29:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1770) |  Oh, I wish we would make this

public. I keep pushing Gary to give a specific presentation that he gives for new Search Googlers because it has a lot of useful information in it. But we don't really have everything in this shared yet. We have everything in here, roughly, but we don't have it in this specific format, which I think is awesome. I hope that he makes a video one day. What else do we do?  

#### [0:30:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1800) |  Content parsing. I know that we don't

do that for the HTML, but if it's like a PDF or something, we would parse that. Yeah, we gather some signals already, but we also then mix them with what we get from the rendering. So most of it happens also after rendering, again. Does that help? AUDIENCE: What about duplicate content detection, regardless of canonicalization, et cetera? MARTIN SPLITT: Well, canonicalization and/or  

#### [0:30:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1830) |  deduping are related, right? So basically, when

we say canonicalization, it really is deduplication. We first see all the papers that are similar enough, and then we elect which of these is the canonical. So it's kind of like it's related to each other. As I said, we do that on the initial HTML, but we also do it in the rendered HTML. So I don't think there is a chance that we would kick out the page without having  

#### [0:31:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1860) |  it rendered first. So we do get

the hashes immediately, but we compare them to what we get after rendering. And usually in rendering we get different hashes, and then that's what we use continuously-- unless we get the same hashes. Then we're like, yeah, no, this is actually an empty page, or this is actually a page that we already have an index. AUDIENCE: Mm-hmm. OK, thank you. MARTIN SPLITT: You're welcome. Any more questions? And again, feel free to both use the chat or to speak up. Or actually, the Raise Hand feature is kind of-- oh,  

#### [0:31:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1890) |  Dave is raising his hand. AUDIENCE: Hi.

Yeah. Well, when you're fetching stuff from an API, et cetera, if you do get one, does Google cache that the same as it would another resource? MARTIN SPLITT: It does. AUDIENCE: Yeah. But if you did a post, would it not cache that? MARTIN SPLITT: Then we would not cache it. Yes, that's correct. AUDIENCE: OK. Just to move on starting with calls and stuff, I mean, it could be logging on my side, logging an error,  

#### [0:32:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1920) |  but I never see pre-flight requests and

option requests from Googlebot. Or it doesn't seem that way. And yet you kind of expect that. Does Google handle it in a different way, or is it just my login's not great? MARTIN SPLITT: That's an excellent question. I think we do not follow the course protocol because we are going through the-- we are kind of not really a user acting upon things.  

#### [0:32:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1950) |  But I'm not 100% sure. That's a

really good-- ah, Dave, every time you ask a question, you create work for me, and I love that. That's fantastic. I would love more questions like this, because I did a course test once. But I can't remember what the outcome of it was. I need to think find out. Thank you. That's a really good question. Anyone else raising their hands?  

#### [0:33:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=1980) |  No. Anyone else have any questions in

the chat? No. Feel free to drop more questions. Definitely do that. Also really happy to see a good mixed bunch of people here. And I think we have lots of different locations. So we have Hungary. We've seen Poland. We have seen Germany. No, hold on. We don't have anyone from Germany. Well, we have Switzerland. That's me.  

#### [0:33:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=2010) |  I think Symon is in the call

as unknown, and I think he's based in Germany. What other countries do we have? Barcelona, so we have Spain involved as well. AUDIENCE: UK. MARTIN SPLITT: UK. AUDIENCE: But I'm from Germany, so [INAUDIBLE].. MARTIN SPLITT: Interesting. Oh, where from Germany? AUDIENCE: Stuttgart. MARTIN SPLITT: Stuttgart. Not too far away. Interesting. So we have-- well, UK, yeah, sure. Dave is also from the UK. Pakistan. Wow.  

#### [0:34:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=2040) |  Global Office Hours today. That's awesome. Do

we have more questions on YouTube? No. All right. AUDIENCE: Hi, Martin. MARTIN SPLITT: Hi. AUDIENCE: So I had one question regarding this fetching and finding the content as duplicate. In [INAUDIBLE] web indexing system, in initial HTML, does it happen that in an initial  

![](https://i.ytimg.com/vi/6hFm34j9Zk0/maxres3.jpg)



#### [0:34:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=2070) |  HTML Google could not find duplicate content,

hence it indexed the page? Then after a final rendering and indexing, it figures out that the page is duplicate, therefore removes the page from indexing. MARTIN SPLITT: OK, that's a very good question. "Neer-aj," is it? AUDIENCE: Yeah. MARTIN SPLITT: Yay. Neeraj, thanks for the question. Good question. It's one of the questions that haunts me the most. Not this specific question, but the two ways of indexing  

#### [0:35:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=2100) |  has been a metaphor that has slightly

gone wrong, I think, because there's not really two ways of indexing. We are pretty much processing the initial HTML and then decide to render and then index. So pretty much anything that gets indexed has been rendered in the middle of it. That's why I'm always a little conservative when people are like, oh, this has been indexed without rendering. Most pages, actually pretty much nearly 100% of the pages, get rendered before they get indexed. Hypothetically, what you are describing  

#### [0:35:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=2130) |  is possible if rendering continuously failed for

some reason, if there is some JavaScript that got stuck, if there is some fundamental error. And then it might be that the page starts flip-flopping. It is also just possible that what you are seeing-- especially if you think that it's dropping off the index and coming back into the index, sometimes what happens is that there is a change in the canonicalization. So as I said, we put all the pages that we think are roughly duplicated into a cluster, and then we choose which one we think should be the canonical.  

#### [0:36:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=2160) |  And sometimes the only thing that happens

is we understand that this is a duplicate page, and it's just like different canonicals are being chosen, thanks to the signals fluctuating. That is normally not related to rendering. That's normally related to other things, because we are combining a bunch of signals into the reader or canonical selection within these duplication clusters. But normally, no, there is very few opportunities for a page to be indexed without rendering. So it's very, very unlikely that the page gets not  

#### [0:36:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=2190) |  seen as duplicate before rendering and then

seen as duplicate after rendering, unless there's something really funky going on. AUDIENCE: OK. And what happens if the content is coming from the API and the API gets failed and Google retries, and then only the content is appearing? Then only it will be able to-- MARTIN SPLITT: Yeah, that is a problem because then we might be seeing-- depending on how it failed, we might just not see the content that comes from the API and then basically cluster up URLs that are not technically  

#### [0:37:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=2220) |  the same just because multiple URLs have

failures with the API. That's why it's very important to make sure that you have mechanisms in place to make sure that your API doesn't fail. And if your API is flaky, then that's something that I'd investigate, yeah. AUDIENCE: OK, thank you. MARTIN SPLITT: You're welcome. Tomasz has raised his hand. AUDIENCE: So when there is noindex on our page,  

#### [0:37:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=2250) |  do you take structured data into consideration

or not? MARTIN SPLITT: I don't think we do, because if you think about it, structured data is then used for rich results mostly and some other additional semantic enrichment. But it's basically-- if the information we have on the page says, do not put me in the index, then I guess we stop processing before we would look at structured data as well. AUDIENCE: What about extraction in that case? Because that was-- long story.  

#### [0:38:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=2280) |  MARTIN SPLITT: That is a good question.

I don't know, because these processes should be running in parallel. So I could imagine us to actually doing extraction on a page that tells us noindex and then only find out that it's noindexed after we already started scheduling the URLs for crawling. And especially if the crawling has already happened, then we can't un-crawl something. If a request has been made, it has been made.  

#### [0:38:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=2310) |  But I guess you might see mixed

signals here. Sometimes we might discover the links. Sometimes we might not. And really, it's a case of, if you don't want something in the index, put a noindex on it. And if we discover the other links, that's not a problem, unless you also don't want these things to be indexed. If you don't want these things to be noindexed put a noindex on them as well. The clearer you can make the signals,  

#### [0:39:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=2340) |  the easier it is for us not

do something that you don't expect. Makes sense? AUDIENCE: Makes sense. MARTIN SPLITT: Awesome. Let's check the chat. Yeah, Henning, I said Catalonia. I said Spain, or actually Catalonia. So I am aware that there is sensitivity in that area.  

#### [0:39:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=2370) |  Anyone else with questions? Yeah, I mean,

may have overheard it because I said Spain. And I was like, no, actually, it's Catalonia. Someone asks for this link on Twitter. So I'll be so nice to share the link on Twitter as well. Because why wouldn't I? There we go. Maybe someone else joins us today.  

#### [0:40:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=2400) |  If not, feel free to ask your

questions, either in the chat or by speaking up-- or raising your hand. That's actually a-- I keep forgetting that we have this feature now. It's really nice. I like that feature. Ooh. Holy moly. I'm not sure if these are-- so I'm enrolled for experiments in Hangouts. And now I need to find out if certain features are actually available to everyone or just basically out in testing.  

#### [0:40:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=2430) |  And let me see, because I don't

want to use a cool new feature if I'm not sure that feature is actually public yet. I don't want to accidentally leak things. That would be awkward. That would be so awkward. Let me see. Do I have these features here as well? No. Well, then again, I also don't have the Raise Hand feature  

#### [0:41:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=2460) |  here. Oh, God. If only I knew

if this is public or not. Dang it. Because I just saw a few nice features. Actually, I can probably try to read-- ah, OK. Ha, ha. It's actually public. I can start a poll. "Which JavaScript framework do you mainly work with,"  

#### [0:41:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=2490) |  question mark. And then there's, like, Angular,

React, View, other. Let's see if I can launch this. I don't know how it shows up for you, but we now actually do have a poll, a vote that you can go and--  

#### [0:42:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=2520) |  oh, yeah. So people are already-- oh.

Oh. Oh, wow. OK. Angular and react taking the lead. React taking the lead. That's what I expected, to be honest. For those of you selected other, what are you working with?  

#### [0:42:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=2550) |  AUDIENCE: I selected view, but I do

use the property a bit more now. I use Svelte and [? zappa ?] a lot, particularly Svelte a lot. MARTIN SPLITT: Yeah, someone just said Svelte in the chat as well. So Svelte seems to be-- should I do a livestream with Svelte? Probably should. AUDIENCE: Definitely. MARTIN SPLITT: Yeah, might be interesting. JavaScript new-- that's fine. Every one of us started at some point. And if you watch the Twitch streams that I do every now and then, you'll see that even I struggle with syntax and stuff.  

#### [0:43:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=2580) |  Like, no shame in that. It's cool.

Awesome that you are getting into Svelte, Ziemowit. So that's pretty cool. Hold on. What happens in the poll? Angular and React leading. Cool. That's more or less what I expected. Just quick question for the Angular people-- would you consider your projects or companies more enterprise-y or more startup-y? Because I have a feeling--  

#### [0:43:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=2610) |  I have a suspicion in which environments

Angular is used more and in which environments React is used more, but maybe I'm wrong. Maybe I'm just biased. I could run a separate poll for this. But then again, eh. How does this work? Ah. Uh-uh. That doesn't seem so useful. But the polls feature is quite interesting. That's nice. So we ran a poll. I wonder how that comes up in the recording.  

#### [0:44:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=2640) |  In case it doesn't come out in

the recording, I asked which JavaScript framework people mainly work with. I got eight responses, and three people use Angular. Three people use React. One person uses View, and one person uses Svelte, as we just found out. Awesome. In case anyone has a question, I think we are running out of time, but I will take one more question. Yes, [? Asaf, ?] I did cut my hair. Thank you very much. It is more useful when diving.  

#### [0:44:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=2670) |  Long hair and cold air don't go

well together. So I'm pretty happy that I don't have to deal with long hair and cold weather after diving anymore, even though I do miss the long hair a little bit. It feels weird as well. I can still color it, but eh, might as well not. Like, I think colors come out nicer when you have a transition. And for transition, you need a certain length. I also still have some blue and blonde bits in my hair,  

#### [0:45:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=2700) |  and it looks a bit weird, I

think. But it'll disappear eventually. It's fine. All right. Final countdown. 5, 4-- questions? 3, 2, 1. Ladies and gents, it has been a huge pleasure hosting the Office Hours. The next Office Hours will be-- actually, I think next week.  

#### [0:45:30](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=2730) |  Is it next week or is it

in two weeks? I confuse myself with how I schedule these these days. No, it's in two weeks. It will be in the later time zone as well. It will be at 5:00 PM CDT, so it will be seven hours later than this one. And then in four weeks, we'll be in this time slot again. Has been a huge pleasure. I'll upload the YouTube video as soon as I get the recording, and I wish you all a fantastic day. And for those of you who are watching  

#### [0:46:00](https://www.youtube.com/watch?v=6hFm34j9Zk0&t=2760) |  this as the YouTube recording, feel free

to drop in your questions. Go to our channel. Go to the Community tab and watch for the next announcement post for the SEO Office Hours. Has been a huge pleasure having you all here, answering all of your questions. See you soon, and I hope to see you all in the next upcoming Hangouts as well. Bye. AUDIENCE: Bye, Martin. AUDIENCE: Bye. AUDIENCE: Bye.  