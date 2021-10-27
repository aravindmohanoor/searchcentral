[![Googlebot: SEO Mythbusting](https://i.ytimg.com/vi/8QeU97wWomQ/maxresdefault.jpg)](https://www.youtube.com/watch?v=8QeU97wWomQ)

## Googlebot: SEO Mythbusting

In the second episode of SEO Mythbusting, Martin Splitt (WebMaster Trends Analyst, Google) and his guest Suz Hinton (Cloud Developer Advocate, Microsoft) discuss the many intricacies of Googlebot such as:

What is - and what is not - Googlebot (crawling, indexing, ranking) (1:02)

Does Googlebot behave like a web browser? (3:33)

How often does Googlebot crawl, how much does it crawl, and how much can a server bear? (4:03)

Crawlers & JavaScript-based websites (9:04)

How do you tell that it’s Googlebot visiting your site? (11:12)

The difference between mobile-first indexing and mobile friendliness (12:28)

Quality indicators for ranking (13:35)



Documentation mentioned in this episode:

What Crawl Budget Means for Googlebot → https://goo.gle/crawl-budget

Google crawlers (user agents) - see which robots Google uses to crawl the web → https://goo.gle/googlebot-useragents

Implement dynamic rendering → https://goo.gle/dynamic-rendering

Prepare for mobile-first indexing → https://goo.gle/mobile-first-indexing



In the future episodes of SEO Mythbusting, look forward to more topics such as SEO & JavaScript, SEO & Web Performance, SEO & Web Frameworks, and SEO & Future of the Web.



Watch more SEO Mythbusting episodes → https://goo.gle/SEO-Mythbusting 

Subscribe to Google Search Central → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=8QeU97wWomQ&t=0) |  SUZ HINTON: A lot of confusion revolves

around SEO because no one understands how the Googlebot actually works. [MUSIC PLAYING] MARTIN SPLITT: Hello and welcome to another episode of "SEO Mythbusting." With me today is Suz Hinton from Microsoft. Suz, what do you do at work, and what is your experience  

#### [0:00:30](https://www.youtube.com/watch?v=8QeU97wWomQ&t=30) |  with front end SEO? SUZ HINTON: Yeah,

so right now, I'm doing less front end these days. I focus more on IoT. MARTIN SPLITT: So in the time you were a front end developer-- SUZ HINTON: Yeah, I was a front end developer for, I think, 12 or 13 years. And so I got to work on lots of different contexts of front end development, different web sites, things like that. MARTIN SPLITT: Cool. SUZ HINTON: Today, I wanted to just address a bunch of stuff about Googlebot specifically, and nerd out about Googlebot, because that was the side of things that I was the most confused about  

#### [0:01:00](https://www.youtube.com/watch?v=8QeU97wWomQ&t=60) |  at the time. MARTIN SPLITT: So Googlebot

is basically a program that we run that does three things. The first thing is it crawls, then it indexes, and then last, but not least, there's another thing that is not really Googlebot anymore. That is the ranking bit. So we have to basically grab the content from the internet, and then we have to figure out what is this content about? What is the stuff that we can put out to users looking for these things? And then last, but not least, is which of the many things that we picked for the index is the best thing for this particular query  

#### [0:01:30](https://www.youtube.com/watch?v=8QeU97wWomQ&t=90) |  in this particular time? SUZ HINTON: Got

it, yeah. MARTIN SPLITT: But the ranking bit, the last bit, where we move things around-- that is informed by Googlebot, but it's not part of Googlebot. SUZ HINTON: Is that because there's this bit in the middle, the indexing? The Googlebot is responsible for the indexing and making sure that content is useful for the ranking engine to-- MARTIN SPLITT: Absolutely, absolutely. You can imagine, someone has to-- in the library, someone has to figure out what the books are about and get the index of the bits in a catalog, the catalog  

#### [0:02:00](https://www.youtube.com/watch?v=8QeU97wWomQ&t=120) |  being our index, really. And then someone

else is using that index to make informed decisions and going, here, this book is what you're looking for. SUZ HINTON: I'm really glad you used that analogy because I worked in a library for four years. MARTIN SPLITT: So you know much better than I how that works. SUZ HINTON: And I was that person. People would be like, I want Italian cookbooks, and I'm like, well, it's 641.5495. And you would just give it to them. MARTIN SPLITT: If I would come to you, as a librarian, and ask a very specific question, like so what is the best book on making apple pies really quick,  

#### [0:02:30](https://www.youtube.com/watch?v=8QeU97wWomQ&t=150) |  would you be able to figure out,

from the index-- you probably have lots of cookbooks. SUZ HINTON: We did, yeah. We had a lot. But given that I also put lots of books back on the shelf, I knew which ones were popular. I've no idea if we can link this back to Googlebot. MARTIN SPLITT: That does. Yeah, it's pretty much-- so you have the index that probably doesn't really change that much, unless you add new books to it. SUZ HINTON: New editions. MARTIN SPLITT: Exactly, yeah. So you have this index, which Googlebot provides you with. But then we have the second-- the librarian second part that basically is,  

#### [0:03:00](https://www.youtube.com/watch?v=8QeU97wWomQ&t=180) |  based on how the interactions with the

index work, figure out which books to recommend to someone asking for it. So that's pretty much the exact same thing. Someone figures out what goes into the catalog, and then someone uses it. SUZ HINTON: I love this. This makes total sense to me. MARTIN SPLITT: But I guess that's still not necessarily all the answers you need. SUZ HINTON: Yeah, I just want to know, what does it actually do? How often does it crawl sites? What does it do when it gets there? What does it-- how is it generally behaving like? Does it behave like a web browser?  

#### [0:03:30](https://www.youtube.com/watch?v=8QeU97wWomQ&t=210) |  MARTIN SPLITT: That's a really good question.

Generally speaking, it behaves a little bit like a browser-- at least, part of it does. So the very first step, the crawling bit, is pretty much a browser coming to your page, either because we found a link somewhere, or you submitted a site map, or there's something else that basically fit that into our systems. You can use Search Console to give us a hint and ask for re-indexing, and that triggers a crawl before-- SUZ HINTON: I've done that before. MARTIN SPLITT: Oh, very good. SUZ HINTON: We asked for it to be done.  

![](https://i.ytimg.com/vi/8QeU97wWomQ/maxres1.jpg)



#### [0:04:00](https://www.youtube.com/watch?v=8QeU97wWomQ&t=240) |  MARTIN SPLITT: And that is perfectly fine,

but the problem then, obviously, is how often do you crawl things, and how much do you have to crawl, and how much can the server bear. If you're on the backend side, you know that you have a bunch of load, and that might not be always the same thing. If it's like a Black Friday, then the load is probably higher than on any other day. So what Googlebot does is it tries to figure out, from what we have in the index already, is that something that looks like we need to check it more often? Does that probably change? Is it like a newspaper or something? SUZ HINTON: Got it, yeah. MARTIN SPLITT: Or is that something  

#### [0:04:30](https://www.youtube.com/watch?v=8QeU97wWomQ&t=270) |  like a retail site that does have

offerings that change every couple of weeks? Or even do not change at all because this is actually the site of a museum that changes very rarely? For the exhibitions maybe, but a few bits and pieces don't change that much. So we try to like segregate our index data into something that we call daily or fresh, and that gets called relatively frequently. And then it becomes less and less frequent as we discover, and if it's something that is super spammy or super broken,  

#### [0:05:00](https://www.youtube.com/watch?v=8QeU97wWomQ&t=300) |  we might not crawl it as often.

Or if you specifically tell us, do not index this, do not put this in the index, this is something that I don't want to show up in the search results, and we don't come back every day and check. So you might want to use the re-index feature if that changes. You might have a page that you go, no, this shouldn't be here, and then once it has to be there, you want to make sure that we are coming back and indexing again. So that's the browser bit. That's the crawler part, but then a whole slew of stuff  

#### [0:05:30](https://www.youtube.com/watch?v=8QeU97wWomQ&t=330) |  happens in between that happening, us fetching

the content from your server, and the index having the data that is then being served and ranked. So the first thing is we have to make sure that we discover if you have any other resources on your page. The crawling cycle is very important. So what we do is, the moment we have some HTML from you, we check if we have any links in there, or images for that matter, or video-- something that we want to crawl as well,  

#### [0:06:00](https://www.youtube.com/watch?v=8QeU97wWomQ&t=360) |  and that feeds right back into the

crawling mechanism. Now, if you have a gigantic retail site, let's say, just hypothetically speaking, we can't just crawl all the pages at once, both for our resource constraints, but also we don't want to overwhelm your service. So we basically try to figure out how much strain we can put on your service and how much resources we've got available as well, and that's called the crawl budget, oftentimes. But it's pretty tricky to determine, so one thing  

#### [0:06:30](https://www.youtube.com/watch?v=8QeU97wWomQ&t=390) |  that we do is we crawl a

little bit, and then basically ramp it up. And when we start seeing errors, we ramp it down a little bit more. So oops, sorry, for that, we are not-- oh, ugh. So whenever your service serves us 500 errors, there are certain tools in Search Console that allow you to say, hey, can you maybe chill out a little bit. But generally, we don't try to get all of it at once and then ramp down. We are trying to carefully ramp up, ramp down again, ramp up again, ramp down again, so it fluctuates a little bit.  

#### [0:07:00](https://www.youtube.com/watch?v=8QeU97wWomQ&t=420) |  SUZ HINTON: There's a lot more detail

in there than I was even expecting. I didn't even know that-- I guess I never considered that a Googlebot crawling event could put strain on somebody's website. That sounds like it's a lot more common than I even thought it would be. MARTIN SPLITT: It does happen, especially if we discover, say, a page that has lots of links to subpages pages. Then all of these go into the crawling queue, and then you might-- let's say you have 30 different categories of stuff,  

#### [0:07:30](https://www.youtube.com/watch?v=8QeU97wWomQ&t=450) |  and each of these have a few

thousand products and then a few thousand pages of products. So we might go, oh, cool, crawl, crawl, crawl, crawl, crawl, crawl, crawl, and then we might crawl a few hundred thousand pages. And if we don't spread that out a little bit-- so it's a weird balance. On one hand, if you add a new product, you want that to be surfaced and searched as quickly as possible. On the other hand, you don't want us to take all the bandwidth that your server offers.  

![](https://i.ytimg.com/vi/8QeU97wWomQ/maxres2.jpg)



#### [0:08:00](https://www.youtube.com/watch?v=8QeU97wWomQ&t=480) |  I mean, cloud computing makes that a

little less scary, I guess, but I remember the days-- I'm not sure if you remember the days where you had to call someone, and they ask you to send a form or fax a form. And then two weeks later, you get the confirmation letter that your server has been started. SUZ HINTON: Yes, I remember the days when we would have to call, and then we would basically pay $200 to have a human go down the aisles and push the physical reset button on the server, so yeah. MARTIN SPLITT: Those times were a lot trickier, yeah.  

#### [0:08:30](https://www.youtube.com/watch?v=8QeU97wWomQ&t=510) |  And then imagine you basically renting five

servers somewhere in a data center, and that taking a week, and then we come and scoop up all your bandwidth. And you're like, great, we're offline today because Google has its crawl day. That's not what we want to have. SUZ HINTON: Yeah, these days, it's more like a happy news kind of moment, when you get hit. MARTIN SPLITT: Exactly. SUZ HINTON: So I feel like you're much more considerate than-- MARTIN SPLITT: Yeah, we try to not overwhelm anyone, and we respect the robots.txt. So that works within the crawl step as well. And once we have the content, we can't  

#### [0:09:00](https://www.youtube.com/watch?v=8QeU97wWomQ&t=540) |  put strain on your infrastructure anymore, so

that's fantastic. But modern web apps being mostly JavaScript driven, we then put that in a queue, and then once we have the resources to render it, we actually use another headless browser kind of thing. We call that the Web Rendering Service. Then there's other crawlers as well that might not have the capacity or the need to run JavaScript. This is like social media bots, for instance. They come and look for metadata. If that meta tag is coming in with JavaScript,  

#### [0:09:30](https://www.youtube.com/watch?v=8QeU97wWomQ&t=570) |  you usually have a bad time, and

they're just like, sorry. SUZ HINTON: Yeah, so that's always been a big mess, and I remember when single page applications, or SPAs, really came into vogue. A lot of people were really concerned. There's a lot of FUD around. Well, if crawlers in general don't execute JavaScript, then they're going to see a blank page, and how do you get around that? So contextually, within Googlebot, it sounds like Googlebot executes JavaScript-- MARTIN SPLITT: They do. SUZ HINTON: Even if it does do it at a later point. MARTIN SPLITT: Yes, correct.  

#### [0:10:00](https://www.youtube.com/watch?v=8QeU97wWomQ&t=600) |  SUZ HINTON: So that's good? MARTIN SPLITT:

That's good. SUZ HINTON: But is there anything that people need to be aware of beyond just, oh, well, it'll just run it, and then it'll see exactly the same thing as a human with a phone or a desktop would see? MARTIN SPLITT: There's a bunch of things that you need to be aware of. So the most important thing is, again, as you said, it's deferred. It happens at a later point. So if you want us to crawl your stuff as quickly as possible, that also means we have to wait to find these links that JavaScript injects. Basically, we crawl, we have to wait until JavaScript  

#### [0:10:30](https://www.youtube.com/watch?v=8QeU97wWomQ&t=630) |  is executed, then we get the rendered

HTML, and then we find the links. So the nice little short loop that finds these links relatively quickly right after crawling will not work. So we will only see the links after we render it, and this rendering can take a while because the web is surprisingly big. SUZ HINTON: Yeah, just a little bit. MARTIN SPLITT: There's 130 trillion docs in 2016, so-- SUZ HINTON: So there's way more now. MARTIN SPLITT: There's way more now. There's way more than that. SUZ HINTON: So robots.txt is very  

#### [0:11:00](https://www.youtube.com/watch?v=8QeU97wWomQ&t=660) |  effective at being able to tell bots

how to do a certain thing. But in this scenario, how do you tell that it's Googlebot visiting your site as opposed to other things? MARTIN SPLITT: So as we are basically using a browser in two steps-- one is the crawling, and one is the actual rendering-- both of these moments, we do give you the user agent header. But basically, there's the string-- literally the string Googlebot in it. SUZ HINTON: That's so straightforward. MARTIN SPLITT: Yes, and you can actually use that to help with your SPA performance as well.  

#### [0:11:30](https://www.youtube.com/watch?v=8QeU97wWomQ&t=690) |  So as you can detect on the

server side, oh, this is Googlebot user agent requesting, you might consider sending us a prerendered static HTML version, and you can do the same thing for the others. All the other search engines and social media bots have a specific string saying that they are a robot. So you can then basically go, oh, in that case, I'm not giving you the real deal, the single page app. I'm giving you this HTML that we prerendered for you. It's called dynamic rendering. We have docs on that as well. SUZ HINTON: The one thing that still doesn't quite  

![](https://i.ytimg.com/vi/8QeU97wWomQ/maxres3.jpg)



#### [0:12:00](https://www.youtube.com/watch?v=8QeU97wWomQ&t=720) |  make sense to me is does the

Googlebot have different contexts? Does it sometimes pretend that it's-- I think of it as this little mythical creature that's pretending to do certain things. So does it pretend to be on a mobile, and then desktop? Are the different, I guess, user agents, even though it still says Googlebot? And can you differentiate between them? MARTIN SPLITT: You're asking great questions, because yes, we have different user agents. So I'm not sure if you heard about mobile first indexing  

#### [0:12:30](https://www.youtube.com/watch?v=8QeU97wWomQ&t=750) |  being rolled out and happening. SUZ HINTON:

I've heard that it's going to affect how you're ranked potentially. MARTIN SPLITT: That as well. SUZ HINTON: I don't know if that's a rumor or not, yeah. MARTIN SPLITT: Ah, that's two different things that get conflated so often. So mobile first indexing is about us discovering your content using a mobile user agent and a mobile viewport. So we are using mobile user agents, and the user agent strings says so. It says something about Android in the name, and then you're like, aha, so this is the mobile Googlebot. We have documentation on that.  

#### [0:13:00](https://www.youtube.com/watch?v=8QeU97wWomQ&t=780) |  There's literally a Help Center article that

lists all these things. So we try to index mobile content to make sure that we have something nice to server for people who are on mobile, but we're not pretending random user agents or anything. We stick to the user agent strings that we have documented as well, and that's mobile first indexing, where we try to get your mobile content into the index rather than the desktop content. Then there's mobile readiness, or mobile friendliness. If your page is mobile friendly, it makes sure that everything is within viewport,  

#### [0:13:30](https://www.youtube.com/watch?v=8QeU97wWomQ&t=810) |  and you have large enough tap targets

and all these lovely things, and that just is a quality indicator. We call these signals. We have over 200 of them. SUZ HINTON: That's a lot. MARTIN SPLITT: Right? So Googlebot collects all these signals and then stuff them, as metadata, into the index. And then when we rank, we're like, so this user's on mobile, so maybe this thing that has a really good mobile friendliness signal attached to it might be a better one than the thing where they have to pinch zoom all the way out  

#### [0:14:00](https://www.youtube.com/watch?v=8QeU97wWomQ&t=840) |  to be able to read anything, and

then can't actually deal with the different links because they're too close to each other. So that's one of the many-- it's not the signal. It's one of the many signals. It's one of the over 200 signals to deal with. SUZ HINTON: I had no idea there were 200. That's making me-- I know that you're not allowed to share what they all are because there has to be a certain mystique around it, because of, I guess, a lot of SEO abuse in the past. MARTIN SPLITT: Yeah, yeah, unfortunately, that is a game that is still being played, and people are doing weird stuff to try to game us.  

#### [0:14:30](https://www.youtube.com/watch?v=8QeU97wWomQ&t=870) |  And the interesting thing with this is,

with the 200 signals, it's really hard to say which one gets you moving in the ranks. SUZ HINTON: The weights of each signal because-- MARTIN SPLITT: And they keep moving, and they keep changing. I love when people are like, no, let's do this, and then, look, my rank changes. Yeah, for this one query, but you lost on all the other queries because you did really weird and funky stuff for that. So just build good content for the users, and then you'll be fine.  

#### [0:15:00](https://www.youtube.com/watch?v=8QeU97wWomQ&t=900) |  SUZ HINTON: I feel like that-- it

feels like less effort as well, than constantly trying to-- MARTIN SPLITT: Yeah, but it's not an easy answer. You pay me to make you more successful on search engines, and I come to you and say, so who are your users, and what do they need, and how could you express that so that they know that it's what they need? That's a hard one because that means I basically bring the ball back to you, and now, you have to think about stuff and figure it out, strategically. Whereas if I'm like, I'm just going to get  

#### [0:15:30](https://www.youtube.com/watch?v=8QeU97wWomQ&t=930) |  you links or do some funky tricks

here, and then you'll be ranking number one. That's an easier answer. It's the wrong answer, but it's the easier answer. So people are like, links are the most important metric ever, and I'm like, no. We have over 200, and it's important, but it's not that important. And chill out, everybody. But this still happens. SUZ HINTON: I'm so glad it's better now. I feel, actually, more at peace in general with SEO, as well,  

#### [0:16:00](https://www.youtube.com/watch?v=8QeU97wWomQ&t=960) |  after speaking to you today. MARTIN SPLITT:

Ah, so good. Suz, thank you so much for being with me here, and has been a great pleasure. SUZ HINTON: Yeah, thanks for answering all of my weird and wonderful questions about the Googlebot. MARTIN SPLITT: Perfect questions. Perfect opportunity. Did we bust some myths? SUZ HINTON: I feel like we did. MARTIN SPLITT: Fantastic. I think that's worth a high five. SUZ HINTON: Awesome. Thanks. MARTIN SPLITT: Thanks. Join us again for the next episode of "SEO Mythbusting," where Jamie Alberico and I will discuss  

#### [0:16:30](https://www.youtube.com/watch?v=8QeU97wWomQ&t=990) |  if JavaScript and SEO can be friends

and how to get there.  