[![JavaScript SEO office hours May 6th, 2020](https://i.ytimg.com/vi/vC-Bh_c2sQg/maxresdefault.jpg)](https://www.youtube.com/watch?v=vC-Bh_c2sQg)

## JavaScript SEO office hours May 6th, 2020

This is a recording of the JavaScript SEO office-hours hangout from April 29, 2020. These sessions are open to anything around SEO for JavaScript sites.



Watch out for new sessions, and add your questions at https://youtube.com/googlewebmasters/community



Subscribe to Google Search Central → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=0) |  MARTIN SPLITT: All right. Hello and welcome

to this week's JavaScript SEO office hours. My name is Martin Splitt. I work for the search relations team in Google, or at Google in Zurich, right now working from home office, as you can probably tell. And it is my pleasure to answer your JavaScript SEO-related questions. With me today are a few people from the community and people have submitted questions on YouTube. So if you want to be part of this,  

#### [0:00:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=30) |  check out the YouTube channel Community tab

to see when the next Hangout is happening. I'll also post the link to the Hangout there. And then later on, I'll also post the recording, so even if you can't make it for the recording, it's still valuable to submit your questions. Right. Before I go into YouTube, is anyone in the Hangout yearning to shoot a question? BARUCH LABUNSKI: Yeah. I wanted to know is eventually one day will Lighthouse become a ranking factor for website  

#### [0:01:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=60) |  issues and so on? I mean, I

know you have to pay attention a lot to it, but I just wanted to ask you just a generic question in regards to the page speeds addicts, you know. I'm not an addict of page speed insights, but I love the new-- I love the new feel compared to how it changed over time  

#### [0:01:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=90) |  and I've been watching it from day

one. So wanted to know is there any discussions out there? I know there's a lot of things that you can't say, you're not allowed to say, but I mean-- MARTIN SPLITT: It's not that I'm not allowed to say. So there's like three parts to this question in the answer. First things first. Lighthouse and Page Speed Insights are developer tools, or actually tools also for SEOs, as well as developers, to determine how fast the website feels to the user. Now, modeling performance in terms of user experience  

#### [0:02:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=120) |  is very tricky and you have to

find the right proxy metrics. And we're still changing the way that we model. If you look at Lighthouse a year ago, two years ago, and now, you'll see an evolution of the metrics and how we mix them to generate the Lighthouse score. It's not something search specific. It is for you to determine and for developers to determine how fast the website feels to the user and where are the low hanging fruits, where's  

#### [0:02:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=150) |  the potential to improve this. Now, currently

I think like yesterday we announced the Web Vitals, or this morning or something, the European Time Zone, we announced the Web Vitals, which are three already existing metrics that we are thinking as the best way to approximate user experience in terms of loading speed. The Web Vitals are made out of the Largest Contentful Paint, Cumulative Layout Shift and First Input Delay,  

#### [0:03:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=180) |  that's what the third metric is for.

These metrics, again, model user experience. As you know, we are trying our best to give the best results for our users in our search results. I don't really answer ranking questions because A, I'm not working in the ranking part of things; B, I don't really want to talk about ranking because there's so many other things that you can do to make a website good for your users that  

#### [0:03:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=210) |  will reflect in ranking. Ranking is basically

trying to model what is a good answer for this query. So that's the second part. The third part is page speed is already a ranking factor, so that will not change, as far as I can tell. BARUCH LABUNSKI: Right. [INAUDIBLE] if it's embedded into Search Console and there's a delay, there's a delay in the updates in Search Console for page speed, you know, like for moderate [INAUDIBLE].. MARTIN SPLITT: Mhm. Speed report. BARUCH LABUNSKI: Yeah, the speed report, there's  

#### [0:04:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=240) |  a huge delay in that. So that's

why I ask. And of course, user experience is the number one thing that every SEO should just worry about. It's just that I wanted to know. So OK, eventually as Lighthouse will get evolved, it's going to change even more as time goes by. And then I guess other factors will come in and then they'll become a ranking factor eventually. MARTIN SPLITT: Lighthouse itself, again, is a tool for developers and webmasters.  

#### [0:04:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=270) |  It's not any way related to search.

What it does, though, is it shows you-- it tries to emulate a way of determining how fast the website is. and under both lab conditions, as well as if you run it like side by side with a Chrome UX report, then you'll also get real user metrics. These things could become more important for us in the future, not as in search, but like basically as developers  

#### [0:05:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=300) |  and the web ecosystem, we want websites

to become faster. So you don't have to rely entirely on the Search Console Report. Any way of you figuring out how fast the website is, especially in terms of real user metrics, not just lab metrics, is important. BARUCH LABUNSKI: I'd also take to consideration that this is unthrottled all the time. Throttled is much better checking the throttled connection, as opposed to unthrottled. A lot of this kind of shows there's the metric,  

#### [0:05:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=330) |  they change as, I mean, because you

got to keep on refreshing. MARTIN SPLITT: Lighthouse, in general, runs on your computer. So it's not a real user metrics tool. It is only [INAUDIBLE]. BARUCH LABUNSKI: Exactly. Exactly. Right. Right. I just wanted to, yeah. MARTIN SPLITT: So the more real user metrics you can get your hands on, the better. The more lab data you can also correlate with is also helpful. Basically you just build fast websites. That's the goal, really. And Lighthouse is one tool to look into how you're doing.  

#### [0:06:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=360) |  BARUCH LABUNSKI: Right. My second favorite, am

I allowed to say it on this Hangout or no? MARTIN SPLITT: Sure. BARUCH LABUNSKI: G2 metrics is my second best favorite. And that's how I achieve an amazing, amazing results for user experience. So I mean, there's Pingdom. MARTIN SPLITT: Plenty of tools and you can choose whatever you think works best for you. It doesn't really matter because none of these tools shows you the reality.  

#### [0:06:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=390) |  They are all giving you different views

in terms of what we think of as performance and how we are all modeling performance. And when I say, we, I mean the entire world, the entire web community is trying to figure out a way to model speed and performance. BARUCH LABUNSKI: One of the reports within Search Console and seeing which pages suck and why are people not coming there, that's what, you know, I really watch for, as the user experience. So yeah. MARTIN SPLITT: Nice.  

#### [0:07:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=420) |  BARUCH LABUNSKI: Yeah. MARTIN SPLITT: Awesome. Thank

you very much for the question. BARUCH LABUNSKI: Yeah. MARTIN SPLITT: I think I'm going to drag one from YouTube in and then you will get the next chance in the Hangout. Hi Martin. One of the websites that I'm tasked with trying to improve search visibility for is serving the canonical tag via JavaScript. The JavaScript is located in the footer. The canonical appends to the head when rendered. My question, is that acceptable or should the canonical be hardcoded within the head?  

#### [0:07:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=450) |  That is acceptable, especially if you use

the testing tools, like the Mobile Friendly Test, the Rich Results test, or Google Search Console, and see that in the rendered HTML, the canonical tag is A, the one that you expect it to be and is in the head, then you will be fine. It doesn't really matter where the JavaScript runs, as long as it gets inserted into the DOM in the right position, and that would be the head. So as long as it shows up in the head and it's the canonical that you would expect, that's fine. What isn't that great, if there's multiple canonical tags on the page for some reason, or if the canonical doesn't  

#### [0:08:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=480) |  make sense when we are seeing it--

like if you are canonicalizing to something like, I don't know, a 404 page, then we're like, oh, I don't know, we don't think that's the same thing. But generally speaking, using JavaScript to inject the canonical is perfectly fine, as long as it's injected in the head, which according to your question, it is. So that's not a problem. OK, that was a quick one. Another real quick one. Any advice for best practices when implementing tags using Google Tag manager?  

#### [0:08:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=510) |  How does it impact speed optimization? Generally

speaking, there isn't anything inherently wrong with Google Tag Manager and oftentimes it is the best bet you have if you don't have that many front end developer resources, or if you have other needs that can't be done otherwise, then it's a viable solution. It is additional JavaScript, though and it loads additional JavaScript. So it does have some speed impact, obviously,  

#### [0:09:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=540) |  because it's just another piece of JavaScript

that needs to be loaded. So my best practice is if you can implement it directly in the page or with your own JavaScript that you have to ship anyway, then do that. If you do not have access to developers or actually making changes to your site yourself, then Google Tag Manager is the way that you can actually influence things on the site and implement additional text and use that. But don't use it if you can avoid it because it is an additional dependency. It is an extra piece of JavaScript  

#### [0:09:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=570) |  that has to be loaded. So reducing

that is generally a good idea. That being said, there's nothing inherently wrong with using Google Tag Manager. All right. Question from the audience while I'm scrolling YouTube for the next question. JULIUS MOHRING: I think I submitted one on YouTube, but I can't find it at the moment. Maybe we can do it like that. MARTIN SPLITT: Sure. JULIUS MOHRING: So we are currently building, or we want to build a React app and we want to use pre-render to serve dynamically rendered content  

#### [0:10:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=600) |  to Google. And of course whenever you

are entering a URL, it will always return a 200, which is because it's a single page application. MARTIN SPLITT: Yes. JULIUS MOHRING: And there is a way for pre-render to serve to Google Bot a 404 or 301. How does it behave when Google tries to validate if-- or is Google validating if we are serving the same  

#### [0:10:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=630) |  to the user as to Google Bot?

Because it would result in having the 404 page rendered to the user, having a 200 as HTTP status code, but for Google Bot, it would be a 404 in this case. [INTERPOSING VOICES] MARTIN SPLITT: Yeah. So the question aims in the direction of, is it cloaking to do that? JULIUS MOHRING: Exactly. MARTIN SPLITT: Generally not. Unless you do really shady things with that, then it's not cloaking, especially  

#### [0:11:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=660) |  if we are seeing that the page

that is served for the 200 OK is also basically just an error page, then we would highlight that as a soft 404, unless we are seeing it because of dynamic rendering, we are seeing it as a 404 page, then you are in safe waters. So that's not something that you need to worry about, generally speaking. JULIUS MOHRING: OK. Perfect. MARTIN SPLITT: Awesome. BARUCH LABUNSKI: Martin? MARTIN SPLITT: Yes. BARUCH LABUNSKI: Just a quick question, some websites are using--  

#### [0:11:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=690) |  just watching like certain websites out there--

and I do send John some stuff, like for spammy stuff. A lot of this brand is misbehaving with its subdomain. And so it's using its subdomain kind of like for links, and then the webmaster kind of is injecting, you know, like anchor tags and so on. I mean, to what point do you guys say, OK, enough is enough.  

#### [0:12:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=720) |  Like if the system cannot detect it--

MARTIN SPLITT: The system is-- so we are pretty much outside of my depth here because that's definitely for the web quality, so search quality and web spam teams. BARUCH LABUNSKI: But in general, there'd be no follow, right? MARTIN SPLITT: I'm not sure I fully understand the setup, but if it's spammy and if it's doing things that are considered non-organic linking, then that's something that the Web Spam Team is definitely  

![](https://i.ytimg.com/vi/vC-Bh_c2sQg/maxres1.jpg)



#### [0:12:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=750) |  working towards figuring out. And if you

are giving us hints towards where we can see samples of that behavior, then we'll look into them. And definitely if it's something non-organic, then we want to know about these things and we want to catch these things. BARUCH LABUNSKI: Right. So in general, if you have subdomains and you're using your clients for links, that's against your guidelines, right? MARTIN SPLITT: I'm not sure how the subdomain plays in it.  

#### [0:13:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=780) |  Generally speaking, if you are using non-organic

links and don't tell us about that being a sponsored link or something like that, then that's a questionable tactic. BARUCH LABUNSKI: OK. MARTIN SPLITT: I don't understand the subdomain part of this, so this is probably a question for John than for me. BARUCH LABUNSKI: There's like a click, they're using it. They're basically taking these subdomains and pasting it on their clients' websites and then using it for--  

#### [0:13:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=810) |  MARTIN SPLITT: Aha. BARUCH LABUNSKI: Right. MARTIN

SPLITT: Yeah. That sounds like classical link spam to me. BARUCH LABUNSKI: Yeah, but the thing [INAUDIBLE] I even shared it with other of your colleagues. And I just, it's been going on for like years and I've been watching it. It just keeps on going on. It keeps on going on. And I don't know, like every day, there's new links coming in. We all [INAUDIBLE]  

#### [0:14:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=840) |  MARTIN SPLITT: Well, as I said, I'm

the wrong person to talk to. That's a question for, John, then. BARUCH LABUNSKI: OK. But in the end of the day-- MARTIN SPLITT: It has nothing to do with JavaScript either, so I don't know. Out of my depth. BARUCH LABUNSKI: Well, no, it's just being injected internally. MARTIN SPLITT: Yeah. I would have to see the example and it's not really my topics, so I would ask John that question. BARUCH LABUNSKI: OK. MARTIN SPLITT: Right. One more from the YouTube list of things.  

#### [0:14:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=870) |  My website runs the ready-made site builder,

something like Wix, but a local company in Thailand. Since they upgraded their front end from PHP to Angular, where canonical HREF method details are dynamically rendered. For Google Bot, I have noticed a huge drop in ranking. Is it because Google Bot can't process all of the script properly for the both mirror text and content? And isn't GSE excluded URL section? I notice too many URLs being crawled or weird URLs with parameters. Generally speaking, this is unlikely the cause  

#### [0:15:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=900) |  of the rank drop. There are many

factors and hundreds of factors that go into this and I don't really discuss ranking to begin with, but it is not impossible that there is some technical reason for why we are not seeing the data. It can be that the site builder is somehow preventing us from crawling some JavaScript resources. It is possible that the JavaScript is buggy. You would have to use the testing tools to see if we see the content that you put in your pages. If we do see that content, then you  

#### [0:15:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=930) |  are, at least on the technical side,

you are safe. But then you would have to figure out if any of the other things is off, like is the page really slow? Is it doing something weird when Google Bot is indexing it? Is there anything happening that shouldn't be happening? It can also be that their site maps are not helpful because if you say you've seen lots of URLs with parameters that you don't expect to be there, then that's probably a problem on their end where they generate additional URLs,  

#### [0:16:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=960) |  and that is not necessarily helping us.

And then combine that with a technical issue that there might be, then you would have very easily an interesting situation at your hands that you need to clean up. So I would talk to the platform that you were using to figure out what they do, how they do it, and how they can help you resolve these things. Without looking at the URL, it's impossible for me to judge what's happened. I have a React static website hosted on--  

#### [0:16:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=990) |  React static, OK-- on AWS S3 behind

an AWS CloudFront CDN. How can I do a 301 redirect on the client side? There is no such thing as a client-side 301 redirect. 301 is the HTTP status that you're using. The HTTP status comes from the server. I'm not 100% sure I haven't used S3 and CloudFront in a while, but I'm not sure if you can set that up on CloudFront.  

#### [0:17:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1020) |  I guess you could prove potentially route

some URLs through Cloud Functions or something and then actually could generate the 301 response, but once you are in user and client land-- basically once you are in the browser, there's no such thing as a 301 redirect. What you can do, though, is you can use JavaScript to generate a client-side redirect. That is not a 301 redirect. Google Bot does follow those and pretends it to be like a normal redirect.  

#### [0:17:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1050) |  It doesn't really make a difference to

us if it's a 301, 302, or a client-side redirect. So that's a way around this problem, but there's no such thing as a client-side 301 redirect because 301 is a server-side HTTP status. OK. One more and then a question from the audience. We have a website which is built on Angular and has a client-side rendering-- well, yeah-- which means that when you view the source, only you see the Angular tag and the code and no text. The text is dynamically shown after the page loads.  

#### [0:18:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1080) |  When switched to server-side rendering, it shows

the content wrapped around the text. What would you suggest-- client or server-side rendering? I guess according to me, I should go with server-side rendering, as Google will require the text content to be crawled and indexed to understand the context. Yes and no. We don't need the server-side rendering for Google Bot because we are also running JavaScript. So if you are putting your client side rendered version into our testing tools, like Mobile Friendly Test, the Rich Results Test, or Google Search Console, you will see that we are very likely seeing  

#### [0:18:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1110) |  the actual content rendered once JavaScript has

executed and your Angular application is ready in the client side rendering scenario. That being said, if you can enable server-side rendering-- and there is no good reason not to in terms of you know what you're doing and you have that setup tested, or even better you're starting a new project and you get to choose which way to go, I would highly recommend looking into a server-side rendering as an investment because server-side rendering usually is faster for the users and also works  

#### [0:19:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1140) |  for bots that don't understand JavaScript. So

most of the major search engines to understand JavaScript, as far as I know, I can't tell for sure-- for Google, I know that Bing is also rendering, I don't know about the others. But things like social media bots, when you share something on social media, they oftentimes do not run JavaScript or don't understand JavaScript, and those would be left out. So if you use like open graph text for social networks and use them in JavaScript, then you wouldn't see them on these social networks  

#### [0:19:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1170) |  because they don't execute JavaScript. So I

recommend looking into server-side rendering, but it's not necessary for Google search at least. OK. Time for a question from the Hangout. YOAD SNAPIR: Can I ask a question? MARTIN SPLITT: Sure. YOAD SNAPIR: Cool. We're doing a server-side rendering, like the common practice. And clearly as we render the page, we have state built on the server-side, then we serialize it, and push that down,  

#### [0:20:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1200) |  along with the already built HTML to

the client. So my question is, when the bot sees that payload, it's like a duplicate content, everything appears twice, right? Once in a state like this JSON string and once within the actual DOM or the actual HTML. Is that a problem, like this duplication? MARTIN SPLITT: No. Especially if it's just application state in the memory, we don't care. We look at the DOM and we only take what's in the DOM.  

#### [0:20:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1230) |  YOAD SNAPIR: Thank you. MARTIN SPLITT: You're

welcome. Here's an interesting question. Is it OK for SEO to use services such as Cloudflare's Rocket Loader. It helps us reduce ping times speeds, but I'm not sure how Google would read it. I don't know either. I haven't tried Cloudflare's Rocket Loader. I haven't used Cloudfare much. BARUCH LABUNSKI: It's pretty good. MARTIN SPLITT: I'm not doubting that. The thing is, the easiest way for you to test this is point our testing tools to one of your URLs.  

#### [0:21:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1260) |  If your content shows up, you should

be fine. That's all I can tell. I know what Rocket Loader is and what it does, but I don't see why it would inherently be a problem, but I'm never saying something like, oh, yeah, this is fine when I haven't tested it. So as I haven't tested it, I highly recommend you all test this, try this out for yourselves. And if it renders the page fine in Google Bot, then you should be fine.  

#### [0:21:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1290) |  In Search Console, when live testing a

JavaScript rendered page, we sometimes see static resources like JavaScript or CSS files. The requests are failed, but there's no details about why they failed. We're testing the same [INAUDIBLE] again, sometimes work. What is the recommended way to debug such issues? This is unfortunate, but this is a limitation of the testing tools, unfortunately. So the thing is, generally speaking, the way to debug these things is look  

#### [0:22:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1320) |  at the reason in the Mobile Friendly

Test. For instance, there's a reason field or something like that. I may actually see if I can bring this up on the screen real quick. I should be able to. Maybe I'm actually getting an error now. That would be convenient, but maybe I'm not and then I have to deal with the fact that I'm not getting the error. I want to share a Chrome tab. Oh, my screen has gone again. This becomes really annoying that it does that now.  

#### [0:22:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1350) |  OK. Here we go. I think this

has something to do with the screen getting too warm because the sun is shining onto my screen right now. OK. If I go to some-- no, that's actually not-- if I go to some URL-- experiments geekonaut the features. And if I'm lucky, actually, I think features is a bad example because I don't think it loads anything interesting. Interesting.  

#### [0:23:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1380) |  Oh. I know why. My SSL certificate

for this one has expired. And honestly, I don't really care too much for this page. That's new. Right. Fantastic. I can't show this right now, but basically-- is this because my website is somehow broken or something like that? Let's see. Codes. Or is there a fundamental bug in-- no. OK. So at least the testing tools don't  

#### [0:23:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1410) |  seem to be like broken broken, they

just didn't like that URL and I'm not sure why. Maybe I made something weird happen on that URL. No, it's also just, oops, something went wrong. Is this because I'm logged in with that specific account? Maybe I need to use a different account. Can I actually share-- ugh. A good one, I think this is the right window. I think you should be seeing a fresh Chrome window now.  

#### [0:24:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1440) |  Let's try this one more time. This

might work. I don't know. Let's try this. So there is a column that says why the request has failed and oftentimes-- interesting. OK. BARUCH LABUNSKI: Is it because you didn't put the HTTPS?  

#### [0:24:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1470) |  MARTIN SPLITT: I don't think that should

be the problem. It's paired with a different URL as well. I'm not sure. Let's see what happens when I try this again with a completely unrelated URL. How about-- I don't know, this one that's from a previous office hours. Maybe I'm just unlucky right now. Maybe we're over capacity or something. Who knows? Anyway, so you see the reason why it failed and there is the infamous other error.  

#### [0:25:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1500) |  If you're seeing the other error column

status code or reason-- I'm not sure what we call it in the tool, actually, that's why I'm trying to run the tool-- the other error basically just means welcome to the world of limitations. While Google Bot, when we are indexing pages, it's very patient with things and can retry stuff over and over again-- so hypothetically, it can take anything between seconds to hours to I don't know how much because we are retrying  

![](https://i.ytimg.com/vi/vC-Bh_c2sQg/maxres2.jpg)



#### [0:25:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1530) |  something goes wrong-- the test does not.

The test does not have the affordance to actually-- oh, it's status. Thank you very much, Dave. So the status in the Resources tab tells you-- ah! Fantastic. So I have opened a random website that was in the previous office hours, I believe. And I can now share this with you as well because it says actually finally loaded. And I think we are lucky because we actually, yes. So this happened multiple times in this case.  

#### [0:26:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1560) |  Am I sharing the right window? I'm

not sure. Yes. I think I shared the right window. So if I zoom in a little bit, we see like here in the status-- thank you again, Dave-- in the Status field, we have Other Error. If you see this, that usually means that we just didn't have the resources or the time to wait for the resources to load. We have a limited quota of how much we can fetch in one test,  

#### [0:26:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1590) |  so sometimes it just takes you a

few iterations. Also, normally we are caching quite heavily. The test tools are not caching, and that's why sometimes things time out. That isn't a problem. That is not a problem. As I explained, the Google Bot is actually very patient and usually does not have these limitations. So what you can do to figure out if things look fine, as far as you can tell, is you can use Search Console and see if the pages indexed as you would expect.  

#### [0:27:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1620) |  And you can use the URL Inspection

Tool to see the crawled page which shows you what is the HTML that we saw when we rendered the last time. If you would see that the crawled page has issues, then that's something you want to investigate and make sure that it's not like something like robots.txt or something blocking us, but also you would see the error in the testing tools if that is the case. If you see Other Error, that is just the fact that the testing tool both does not use caching and B,  

#### [0:27:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1650) |  is a lot less patient because we

don't want you to sit in front of your computer for an hour until the tool actually shows you any results. That would be unfortunate. So that unfortunately sometimes happens. All right. Before I scroll further down this list, I need further questions from the audience. BARUCH LABUNSKI: What's your favorite framework? MARTIN SPLITT: I don't have a favorite. For me, they are tools. It's like asking what's your favorite tool, and that depends on what's the job that I'm trying to do. I think all the frameworks today are very, very similar.  

#### [0:28:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1680) |  I like to think of it as

for me, a framework is basically a bunch of decisions made for me, and a bunch of tooling around it, and the community around it. So for instance, if I say, OK, I work in a large company environment where we have lots of developers working on the same application together and the teams are distributed and the application is really, really big  

#### [0:28:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1710) |  and there's like a lot of interaction

with the back end and everything, then I might want to choose a tool that facilitates the successful deployment and development in such an environment. One of the things that makes these things a lot easier is TypeScript. TypeScript adds types system information to, more or less, JavaScript, so it gives you a type safe variation of JavaScript or a superset of JavaScript,  

#### [0:29:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1740) |  if you wish to say that And

then one framework has that built in. So I don't have to configure it. I don't have to work out how it works with this framework. It's just built in, and that's Angular. So maybe use that, then. If TypeScript is a big thing for you, then I think Angular is an easy choice to make because it comes as the TypeScript version. Sure, you can use TypeScript with React. Sure, you can use TypeScript with Vue, with Ember, with everything. It's not that you can't do it. It's just more effort. Also, if you are working with a team  

#### [0:29:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1770) |  where Java developers from the back end

now have to work on the front end as well, then Angular feels a little more familiar, I think, or TypeScript feels a little more familiar. So I think that's a good choice. If you are working in an environment where you don't really need a framework framework, but you need a bunch of components that are mostly like vanilla in a way, then maybe Vue or React are the better choices. If you really like the Vue ecosystem, then go with that.  

#### [0:30:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1800) |  If you prefer the React ecosystem, go

with that. I don't think there is a best framework because they just make different decisions in different spots. For instance, React's biggest thing is that they have a DOM abstraction layer. So React has the ability to say, oh, I just want to compile everything that I wrote into a mobile application, or into something that runs on the Oculus Rift VR display,  

#### [0:30:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1830) |  for instance, whereas the others don't really

have that. I mean, there were and are options for this, but what's the point? Yeah. BARUCH LABUNSKI: So you can [INAUDIBLE] with React. You can do a lot of integration with React where Angular-- I mean, Angular is getting there, right? MARTIN SPLITT: And also the other thing is, I don't know how easy these interactions or integrations with React really are. Because I heard a bunch of people who tried React Native and weren't as happy, but then again,  

#### [0:31:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1860) |  other people were super successful with React

Native. So I guess it doesn't really depend on the tool, it depends on you, your resources, your project, what are you trying to accomplish, and what decisions would you make in the process of designing the system. And then you find the framework that has made, more or less, the same decisions. That's how I would do it. So I know in my-- BARUCH LABUNSKI: Thank you. MARTIN SPLITT: You're welcome. In my previous job, I was tasked to figure out which framework we should be going with as we were rewriting  

#### [0:31:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1890) |  our application. And I just sat down

and talked to the developers on the team and figured out what are their preferences, how do they think about systems, how do they approach building web applications, and then I made a decision based on that. And I figured out like, OK, so pretty much all the frameworks are an option for this thing. Which are the decisions that we would like to make and then which framework mirrors that? Cool. Back to SEO.  

#### [0:32:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1920) |  Are there quotas that Google Bot uses

when crawling JavaScript rendered pages or sites? So crawling has not much to do with rendering. That is two different phases. Crawling is just we give a URL to the Bot and then the Bot makes an HTTP request to it. That's where crawl budget comes in. And that is kind of how many requests we can do in parallel. And these requests also include things like API requests and JavaScript file requests  

#### [0:32:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1950) |  and all that kind of stuff. So

it does have a little bit of an impact, but not as much as people might think. Especially because caching is involved, I wouldn't worry about it too much. Unless you have a really, really, really big site with lots and lots of JavaScript files, you might want to consider bundling and also tree-shaking a little bit, and maybe also looking at code splitting at the right spots, but there's no such thing as like a render budget or a JavaScript budget or anything like that. There is crawl budget for crawling specifically though.  

#### [0:33:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=1980) |  But that's also true for non-JavaScript websites.

Does Google Bot still recommend using snapshot tools like Rendertron for serving websites built with modern JavaScript frameworks? No. It's a workaround. You can use these tools. And Rendertron is still actively being maintained, as you can see Tuesday and Thursday when I do the Twitch screams, when I actually do maintenance on Rendertron. But it is not necessary for Google Bot. And we consider it a workaround because if you have JavaScript  

#### [0:33:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2010) |  that causes interesting situations in Google Bot,

it probably also causes interesting situations for users, so you either have to fix that or actually possibly consider a server-side rendering as an alternative. The dynamic rendering was and is a workaround rather than a long-term solution. And I think that's it for the YouTube questions, so more questions from the audience here?  

#### [0:34:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2040) |  MIHAI APERGHIS: Hey Martin. MARTIN SPLITT: Hi

Mihai. MIHAI APERGHIS: Just actually a quick follow-up to what you just mentioned. So just curious if you have, I mean, we work with a website that only part of the content is being generated a synchronicity through JavaScript. So it's an e-commerce website and the product listings on category pages are loaded after the initial page load.  

#### [0:34:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2070) |  It works very fast. It shows up

OK in the URL inspection tool. Should they do anything special if everything seems to work fine? MARTIN SPLITT: No, no. I wouldn't fix what isn't broken. MIHAI APERGHIS: OK. So no server-side rendering or anything special? MARTIN SPLITT: Unless you have a good reason to. I mean, as I said, like server-side rendering,  

#### [0:35:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2100) |  if done right, is fantastic, but it's

also an investment. If you don't want to have that investment made or if it's not a priority and your website is fast already, then you're probably not winning as much. So I would not change something that works. MIHAI APERGHIS: But these being category pages, is there a risk that Google might take a bit longer until it finds the links to the product since the products are loaded after the initial page load? So you have [INAUDIBLE] and discover the links? MARTIN SPLITT: So we can only do the link discovery  

#### [0:35:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2130) |  after rendering, then, but normally that isn't

the problem. For 90% of the pages or URLs, we're actually seeing a render time, well, a render queue time within minutes. So you would only probably shave off a few minutes. And usually the investment into server-side rendering for an existing project is quite substantial. So I'm not-- I don't think you're going to win much, really. MIHAI APERGHIS: Right. Right. OK. Cool. Good to know.  

#### [0:36:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2160) |  MARTIN SPLITT: You're welcome. All right. We

have a bit of time left. That's nice. So more questions? BARUCH LABUNSKI: Would you recommend a shared server or having a dedicated server. MARTIN SPLITT: That depends on many things. It doesn't really-- it doesn't make a difference for us. It can make a difference for you if you notice that your performance isn't great, as in like server-side performance isn't great  

#### [0:36:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2190) |  if things take longer to save into

a database, for instance, that will mean that users may be ordering something from you will take longer until they have the order confirmation. If the hoster doesn't balance things properly, then the server might go down because someone else is having a lot of traffic. So there isn't fundamentally anything wrong with a shared server, especially from our perspective. We're just going to do as many requests as we can reasonably do and want to do. And there isn't--  

#### [0:37:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2220) |  [INTERPOSING VOICES] BARUCH LABUNSKI: --we don't want

to rack up more expenses. It doesn't make sense, you know, that we go from a shared to a dedicated, but then you show them the slow speeds and then you explain to them that it can be a ranking issue. MARTIN SPLITT: With slow speeds, you have to be careful though. What is slow? Time to first byte being slow or is it that their server process takes too long,  

#### [0:37:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2250) |  or is it networking slow? BARUCH LABUNSKI:

The website and the server. MARTIN SPLITT: Right. BARUCH LABUNSKI: The website and the server. And then there's a lot of people on the shared server. There's like-- MARTIN SPLITT: Right. So the server responds very slowly. BARUCH LABUNSKI: Extremely, yeah. MARTIN SPLITT: Right. Because that's the thing, like you want to be very careful that you make sure that it's actually, like if you ping the server, it's really slow and if you make network connections to the server, that's where the time is spent. You can see that in the network timeline where time is spent.  

#### [0:38:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2280) |  If their server is really slow, it's

fine for them to not care about it. Generally speaking, it is one ranking factor, but it's not the most important one and it's also not the only one. So I wouldn't argue that that's necessarily time best spent. Making the website faster, as in the client-side performance of things, that's separate from the server question. If the client-side performance of the website, as in like once  

![](https://i.ytimg.com/vi/vC-Bh_c2sQg/maxres3.jpg)



#### [0:38:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2310) |  things have arrived to the network, it

takes a long time to actually show things to the user, that's something that they probably want to fix because that's something that drives people extremely mad. A slow server can be oftentimes compensated with good caching, so that's something they probably want to look into, but only if really the server gets very, very slow and also unreliable, then that's something that I would bring up with my hosting provider. And maybe they can move you to a different part on their site  

#### [0:39:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2340) |  so that you're still on the plan

of a shared server, but you're on a less busy server, unless it's a physical instance if they don't want to rank up or rack up more expenses. And then they have to figure out like where do they want to spend the money. It's also a possibility to use a CDN in front of their server so that more things get handled by the CDN instead of the actual backend. There's ways of working around slow servers  

#### [0:39:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2370) |  without having to get a separate dedicated

server for more money. BARUCH LABUNSKI: OK. No, no, of course. You've got many options for CDNs out there. OK. Thank you. MARTIN SPLITT: That's something that I would look into before I recommend, strongly recommend switching servers or providers. Awesome. Any other questions? I think there was someone else trying to get a question in. DAVE SMART: Yeah. It's just a quick one. In some ways, I suppose, it follows on from Mihai's.  

#### [0:40:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2400) |  With things like [INAUDIBLE],, you've got this

nice hydrating server-side stuff. Occasionally, there will be components people use that are only client-side or only work client-side because they don't want to fix things, things like [INAUDIBLE]. It's not really a problem as long as you use the testing tools and they show is there any kind of panic where you're sending out something, then hydrating parts for? MARTIN SPLITT: No, I think that's fine. That's fine.  

#### [0:40:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2430) |  Again, especially hydration is a really nice

thing because you get the best of both worlds normally. And if it takes longer to hydrate, that's OK, I guess. There's no inherent issue. It depends on-- I would very carefully use the test tools to see if we are actually seeing what we need to see and also things like Lighthouse will show you if there is things like layout shifting and all that kind of stuff that also is not great for user experience. But unless you see something wrong there, stick with it.  

#### [0:41:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2460) |  It's fine. DAVE SMART: Just to follow

up on [INAUDIBLE],, do you know much about the CLS score, the thing that-- MARTIN SPLITT: I haven't really looked into it yet, I have to admit, but I think it makes perfect sense as that is a factor that is super annoying if you experience it as a user. The amount of things that popped up on my phone just because I clicked or tapped on something and it actually moved while I was tapping,  

#### [0:41:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2490) |  frustrating, I tell you. So I'm really

excited to see more work around these things. And it's also very impressive to look at how the metrics have evolved from years ago. We looked at page load times, like what is a page load. Is it the time when the HTML is completed? Is it the time when JavaScript has completed? But what if? And it's quite interesting. And we will see more in the future, I'm sure, because that's an ongoing challenge  

#### [0:42:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2520) |  to better understand and model what performance

means to a user on the web. Awesome. DAVE SMART: Do you think-- MARTIN SPLITT: Sorry? DAVE SMART: Do you think it's-- do you think it's important, as well, when people are looking at things like performance, they take into consideration what their site is because something that's very interactive, [? FID, ?] might be more important. Something that's just an article, something more like LCP might be more important. [INTERPOSING VOICES] MARTIN SPLITT: And that's a huge challenge. That's true.  

#### [0:42:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2550) |  That's the huge challenge. You want, on

one hand, you want an easy to grasp metric that makes sense if you just look at it in a glimpse, like the Lighthouse score. At the same time, you can't break it down into a single score because you might think, like, actually, fun fact, this is a thing where users only come in once and do the thing once, so I don't really care if we have a service worker because they are not coming  

#### [0:43:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2580) |  back normally to this website. Or well,

actually, we kind of don't care about our first user journey or like first-time visitor because actually the first time visitors come in through these other landing pages which are really fast and then they log in and then they get the service worker. So it is really, really hard to model this and really, really hard to balance both needs, which is why when people ask me about the Lighthouse score, I'm always like see it as a smoke test. If your Lighthouse score is 5, you definitely have work to do  

#### [0:43:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2610) |  and you should get to it as

quickly as possible. If your Lighthouse score is 95, sure, there is a bit of like shaving the yak, as we like to say. There's a little bit of like turning knobs and fine tuning dials there, but I'm not sure if it's going to buy you as much as you think it does. And if you're somewhere in the middle, then it depends on where is the problem. As you say, if you have a highly interactive chat app  

#### [0:44:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2640) |  and every value is fantastic except first

time to interactive, if your FID-- First Input Delay-- if the first input delay is really, really high, then people will get frustrated trying to actually interact with the [INAUDIBLE] and they can't because the website's still loading. It doesn't matter how great the other values are. If that's a blocker on your application, then you have to address that. Whereas a website like Wikipedia,  

#### [0:44:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2670) |  might not care as much about the

interaction delays because they're like, well, we just have to get content for the reader to actually observe and read as quickly as possible, so we care more about the Largest Contentful Paint. So yeah. It's not easy to express all of these differences in a single score. So take your Lighthouse scores with a grain of salt, which doesn't mean that you should rationalize  

#### [0:45:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2700) |  having a Lighthouse score of 5. That's

very likely. It might also be that Lighthouse had an issue understanding your page, which you can then say like it's not a performance problem or is a performance problem, mm-hm-hm. Not easy to break this down. BARUCH LABUNSKI: So is 5G going to make things easy? MARTIN SPLITT: Sorry? BARUCH LABUNSKI: Is 5G going to make things easy for JavaScript or worse? MARTIN SPLITT: Looking at how it has been evolving so far, no, I don't think so because the tendency is if you look  

#### [0:45:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2730) |  at things like we have so much

faster machines these days, yet software hasn't gotten faster. It still takes ages for me to open some websites. It still takes ages for me to open certain applications, even if it's native applications. Where I'm like how does this happen? We used to have this fast and relatively well working, even if the UI didn't look as fancy. This was fine 10 years ago.  

#### [0:46:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2760) |  This is still fine, but not great.

So I think a faster network speed will probably only invite different use cases and use cases that we probably haven't seen today, maybe like more [INAUDIBLE] VR, so that we are all doing our Zoom meetings, instead of in Zoom, we do them in VR in the browser, which is fantastic, but also means that we have to move a lot more data so then that eats up the more  

#### [0:46:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2790) |  bandwidth, more speed that we have. Sorry

for that. So I don't think that more bandwidth and faster mobile speeds will fix these issues inherently because we tend to just use the bandwidth more. BARUCH LABUNSKI: Right. MARTIN SPLITT: Hopefully I'm wrong. That would be fantastic, but I have a feeling that it won't be so easy.  

#### [0:47:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2820) |  All right. Any one else having a

question? I think it's good time for the last question. There's one more in the YouTube submitted questions, but I'm not sure how to answer this one because it's  

#### [0:47:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2850) |  a very vague question. In what aspects

should I be aware of-- or what aspects should I be aware of if I want to change my website by applying single page with Ajax? I'm assuming this question is about building a client-side render same page application, at which point my suggestion would be, consider a high level framework like Nuxt or Next or Angular Universal or any of the other frameworks available  

#### [0:48:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2880) |  that have server-side rendering built in because

server-side rendering usually means a better user experience and it's usually a lot faster. That being said, there are a few things that you want to watch out for. Definitely test your implementation with our testing tools, making sure that we are seeing the content and the rendered HTML. And yeah, there are a few things. Check out our documentation on developers.google.com/search. And in the guides, we have a bunch of guides that give you hints and ideas.  

#### [0:48:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2910) |  Or check out the JavaScript SEO series

on our YouTube channel. Good. BARUCH LABUNSKI: Thank you very much, Martin. MARTIN SPLITT: You are very much welcome. BARUCH LABUNSKI: It's helpful, yeah. MARTIN SPLITT: Awesome. I think we have time for one last question for real this time, if anyone in the audience has a question. VAHAN PETROSYAN: Hi Martin. MARTIN SPLITT: Hi. VAHAN PETROSYAN: This is Vahan from Search Engine Journal. I would like to ask one question about the Service Worker.  

#### [0:49:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2940) |  We had implemented Service Worker to serve

WebP images instead of using the picture tag with the HTML [? load ?] with the source tags in it. So actually, there is an action we do. We check through the service worker if browser does port a WebP, we change that image format  

#### [0:49:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=2970) |  to WebP, we fetch API, and return

WebP image in response to JPEG or PNG. But when the images are opened directly in the browser without HTML web page, those are correct from a web PNG. So there's PNG and JPEG, so JPEG. So actually WebP, our server only when the images are  

#### [0:50:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=3000) |  fetched from HTML web pages. So may

this cause any image ranking issues or crawl issues? MARTIN SPLITT: I don't think this is going to cause any specific issues with the images, but it also means that we're not seeing the WebP fformats. VAHAN PETROSYAN: OK. MARTIN SPLITT: Because we are not running the Service Worker, so we won't see the WebP file format.  

#### [0:50:30](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=3030) |  VAHAN PETROSYAN: But when I check via

[INAUDIBLE] or a [? PHP ?] tool, it does see WebP. MARTIN SPLITT: Because that has nothing to do with Google Bot. VAHAN PETROSYAN: Ah, OK. Google Bot doesn't see it. MARTIN SPLITT: Google Bot doesn't see it, yeah. VAHAN PETROSYAN: Ah, I see. OK, gotcha. Thank you very much, Martin. MARTIN SPLITT: You're welcome. All right, ladies and gentlemen. Thank you so much for joining this week's JavaScript SEO office hours. I hope that this was helpful and entertaining a little bit as  

#### [0:51:00](https://www.youtube.com/watch?v=vC-Bh_c2sQg&t=3060) |  well, especially I like the discussions that

creep in every now and then. We will be back next week. I'll post in the Community tab on our YouTube channel. This recording will be up soon-ish and thanks so much for joining. Have a fantastic time and stay safe and stay well and healthy. Bye bye. DAVE SMART: Thanks Martin. Good bye. BARUCH LABUNSKI: Thank you. Bye-bye. MIHAI APERGHIS: Cheers.  