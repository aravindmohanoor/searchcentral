[![JavaScript SEO office hours March 25th 2020](https://i.ytimg.com/vi/DK1rJhvTAdM/maxresdefault.jpg)](https://www.youtube.com/watch?v=DK1rJhvTAdM)

## JavaScript SEO office hours March 25th 2020





#### [0:00:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=0) |  MARTIN SPLITT: Instant. Interesting. The more you

learn. All right. Hi everyone, and welcome to the first official JavaScript SEO Office Hours. I'm Martin Splitt. I am working in the search relations team in Zurich, currently working from home, as you can probably tell. Which is probably what most of you are also doing, I'm guessing. COVID has pretty much reached a global working from home peak at this point. And this is our opportunity to discuss JavaScript SEO-specific  

#### [0:00:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=30) |  questions. If you have questions that are

not related to JavaScript-- I've seen a few people who were already asking questions on YouTube that were not really fitting this format. Also the regular office hours that you can use to ask the non-JavaScript questions. So don't worry about it if you don't have anything specific to JavaScript. You might still learn something today. Cool. In that case, anyone of you wants to ask a question already?  

#### [0:01:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=60) |  [INAUDIBLE] see 20 people [INAUDIBLE] up. That's

really cool. SPEAKER 1: I have a question. MARTIN SPLITT: Sure. SPEAKER 1: So, let me see if I can also type it here. Oh here. So, my question is, if you use robots.txt to block JS or CSS on external JS files DSS file in other domain,  

#### [0:01:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=90) |  or it's in other domain that blocked

them. So user will see different things in Google Bot, right? So, would Google distrust this kind of page and downrank them? MARTIN SPLITT: That's a very good question. Thank you very much. No. We won't downrank anything. It's not cloaking. Cloaking very specifically means misleading the user. Just because we can't see content doesn't necessarily mean that you're misleading the user. It is still potentially problematic  

#### [0:02:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=120) |  if your content only shows up when

we can fetch these resources, and we don't see the content in the rendered HTML because it's blocked by robots.txt. Then we can't index it. If there is content missing, we can't [INAUDIBLE] content. So it's definitely worthwhile trying out our testing tools to see if the content that you want us to see on the page is actually visible on the page, even though some JavaScript or CSS resources might be robotic. But generally speaking, robotting JavaScript or CSS resources isn't per se a problem.  

#### [0:02:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=150) |  It can be a problem if we

can't see the content. But it is fine from the standpoint of cloaking. It's not cloaking. SPEAKER 1: I see. So from what I heard [INAUDIBLE] said, if the JavaScript only do enhancement like make it [INAUDIBLE] for [INAUDIBLE] there won't be a problem. But if JavaScript lets you insert some text or something, there will be a problem? MARTIN SPLITT: Yes. Correct. If the content is loaded by JavaScript, and we can't load that JavaScript because it's robotted, we're not going to see it.  

#### [0:03:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=180) |  That is potentially problematic. But if it's

like, an enhancement, let's say like a chat box, or a comment widget that allows users to add something to the page that is invisible immediately anyway, then that isn't an issue. SPEAKER 1: So in this case, it's like, in this case, if we load something in, is that a penalty for doing that? Or it's just that the thing that we load won't be ranked? MARTIN SPLITT: It's just that we don't see the thing that you load if you robot it away. SPEAKER 1: I see. Thank you. Thank you. MARTIN SPLITT: You're welcome.  

#### [0:03:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=210) |  Very good question. I'm also trying to

keep notes on the questions. But actually, I have the recording. But if you hear me type, then that's because I'm trying to keep tabs on the questions being asked. Awesome. Anyone else having a question? SPEAKER 2: Hello, Martin. MARTIN SPLITT: Hi. SPEAKER 2: Hey, I'm [INAUDIBLE],, link developer at Search Engine Journal. So, today we have implemented the infinte scroll on mobile.  

#### [0:04:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=240) |  And in the past, we had it

on the desktop. And my concern is, what good will index the infinite scroll articles as a part of the main article, which is open first? The [INAUDIBLE] URL which the page queries has a no index applied. But is there any guarantee that the appended content will not  

#### [0:04:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=270) |  be indexed as a part of the

main web page? MARTIN SPLITT: Very good question. The answer is, it depends on how it's implemented and how we see it in the rendered HTML. I would highly recommend checking out the testing tools to see the rendered HTML. Because it depends a lot on how you build your infinite scroll and how we can discover additional content. But if it's like, for instance, using some sort of link  

#### [0:05:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=300) |  that tells us to go to another

URL, and then that URL is no index, then we would not see that content. SPEAKER 2: Like, the picture is implemented the following day. Like, when you scroll down, it loads to article through [INAUDIBLE] at some point, like when you are about to end reading the article. But the [INAUDIBLE] URL which sends the content of the next article has no index ahead of  

#### [0:05:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=330) |  [INAUDIBLE]. So that makes me like somehow

confident that the appended content will not be indexed. But I would like to know like, how I can make sure that indexed scrolled articles will not be indexed as a main part of the article. MARTIN SPLITT: Test. SPEAKER 2: Is there a certain trick-- MARTIN SPLITT: Test. SPEAKER 2: Test? MARTIN SPLITT: It really depends on the exact--  

#### [0:06:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=360) |  so the way that you describe it,

it can go either way. I don't know. I am not fully sure how we see the rendered HTML. Use the testing tools. Specifically, the URL inspection tool can help you figure out how the rendered HTML looks like. If the rendered HTML somehow still contains the additional content because the viewport has changed or something like that, then we would index it as part of the main page, as in like, the page that you have seen. And then no indexing that doesn't really help that much. It can also be that you accidentally no index  

#### [0:06:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=390) |  the content that was previously on the

page so that you might end up in no indexing too much. I would always test these things and look at the rendered HTML. The rendered HTML tells you what we are seeing. You can use the life-- sorry, the URL inspection tool to see what we have crawled. So you see it in the crawled rendered HTML. Or you can also use the live test to see what we see if we would do it again. So, it depends really is the answer in that case.  

#### [0:07:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=420) |  You're welcome. SPEAKER 2: Thank you. MARTIN

SPLITT: Today is March 25. Is that correct? SPEAKER 3: Yes. MARTIN SPLITT: Woo-hoo. I got it right. Very good question as well. And I see that we have one question in the chat that I would like to take at this point. As a JavaScript developer, what are the top five things that we should consider to have or not to have for web security? Web security is a vast and huge field, not really related to JavaScript SEO, though.  

#### [0:07:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=450) |  But I would say definitely make sure

that you will test for cross-site scripting and cross-site resource forgery. Those are two very important things. Make sure that you implement the content security policy headers. That's what they're there for. They prevent a lot of problems. You can set the content security policy to report only so that you basically get feedback on potentially problematic settings before you switch them off.  

#### [0:08:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=480) |  Yeah. What else? [INAUDIBLE] Update your dependencies.

Reduce dependencies to begin with, is a big one. Like, don't include modules for one functionality that you can build in five lines yourself. What else? Security is not exactly my strong side. So I'm not quite sure what else I would do for security. But definitely look at your dependencies, reduce your dependencies, keep them up to date. Use content security policy headers, and make sure that you are not accidentally  

#### [0:08:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=510) |  allowing some sort of cross site scripting

on your site. Anyone else having a question in the hangout? Or should I go to the questions that were submitted? SPEAKER 1: Hi, I have another question.  

#### [0:09:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=540) |  So, so what is it the-- I

recently noticed that Google font in third party font can affect web performance a lot. And I wonder what is the best way to prevent third party font to affect your site performance? Is it worth to, like, query third party font in CSS? Because CSS itself is render blocking and then you query again. And you just send another request. MARTIN SPLITT: So, you're saying you're  

#### [0:09:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=570) |  worried about the performance of third party

fonts. SPEAKER 1: Yeah. MARTIN SPLITT: Yes. I wouldn't worry too much about that. You can hypothetically cache it on your end. So make sure that you're not downloading it over and over again. But I think one way-- I'm not sure what it was called. I think it's font display or something, is the CSS property that you can use to specifically say that it should already start rendering with the system font, or with a fallback font. And then swap in as it has the new font that might reduce  

#### [0:10:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=600) |  the performance impact there. But I would

consider other things as well. It's like you can subset a font to make sure that you only download the subset of the font that you actually need. Reduce on the weights in the font file. So maybe it is definitely worthwhile looking into in-lining, or basically just not necessarily in-lining. But like, hosting your own version of the font. But if you can't, for licensing reasons or whatever, definitely at least use font display swapping. SPEAKER 1: OK thank you.  

#### [0:10:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=630) |  MARTIN SPLITT: Awesome. SPEAKER 1: Oh another--

MARTIN SPLITT: Yeah? SPEAKER 1: Another question. What is the best way to lazy loading? Like, what I do is I use develop tool, and I just record it without scrolling. And to see that if that any image loaded before content download. Is there a right away or is there a other way that there is the more easily quality assurance lazy load? MARTIN SPLITT: Hmm. That is the tricky one that I never really thought about.  

#### [0:11:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=660) |  I just-- yeah. I think I also

just use the developer tools and then resize the window or scroll in the window and see if it actually loads the actual sources. I wouldn't know for sure. That's a good question. SPEAKER 1: Yeah. Because if that is the best way that if you have one million pages, you have to do one million times. MARTIN SPLITT: Yeah, I'm not sure that's a great one. I think you might be able to script something  

#### [0:11:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=690) |  with Puppeteer, maybe. But even then, it

would probably be really, really hard to do that at scale with all the pages, if you have so many pages. That's-- yeah. That's probably something you should do on the page level as the pages get created [INAUDIBLE].. I don't know. If you use the native lazy loading implementation in Chrome, then don't really have that problem then. Because then you can make it a problem of the browser to do that. But not every browser supports it. So I see that, at this point, where you have a bunch of custom implementations,  

![](https://i.ytimg.com/vi/DK1rJhvTAdM/maxres1.jpg)



#### [0:12:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=720) |  this might be pretty hard to test

at scale. SPEAKER 1: I see. Thank you. MARTIN SPLITT: You're welcome. All right. Now I think I'm going to take a question from the list. What are some of the best practices to follow while optimizing speed on JavaScript websites? What's the best CNS for JavaScript website? I don't know about CSSes. Because I'm pretty sure that you can probably make it work with pretty much all of them. But for performance in JavaScript,  

#### [0:12:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=750) |  I would suggest, A, to defer as

much JavaScript as you can. And also if can, if you reasonably can not rely entirely on the client site rendering for your most critical content. Because the quicker you deliver HTML to the browser, the better it is. And the more you rely on JavaScript to do that, the slower it will be, especially for landing pages and static pages. You want to consider a server-side rendering  

#### [0:13:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=780) |  or server-side rendering and hydration. If you

are to start a new project, I would look into a higher level framework, such as NextJS, NextJS or [INAUDIBLE] universal to do that. But if you really have to stick with client-side rendering, then at least try to make your JavaScript as fast as possible by basically tree-shaking your dependencies so that you only have the absolutely crucial and necessary piece of code from your dependencies, and not just drag dead code around.  

#### [0:13:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=810) |  Consider splitting, actually bundling up as much

code as possible, but also splitting your code along the packages where it makes sense. So for a specific page, I might not need all the bundle for all the application. So you could split those and then preload the-- or actually not preload, but prefetch the other bundle so that it is faster as the browser does that in the background. But yeah, the less JavaScript you ship, the better it is. Just that's a general rule of thumb.  

#### [0:14:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=840) |  OK. And then we have a few

more questions in the chat. For caching stack assets such as fonts, using service worker would be recommended? Yes and no. Yes, generally, for your users, that is fantastic to use a service worker to reduce the network activity, especially in the sense of reducing the latency. Because it's always going to be faster to fetch from a local cache then from the network.  

#### [0:14:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=870) |  But search engines also usually are heavily

and aggressively caching, which is why we would suggest to generally use long-lived catching and fingerprinting or some sort of content hash or versioning of your assets. There's an article on the web.dev which is called "HDP Cache-- Your First Line Of Defense," if I remember correctly. I can post that in the chat real quick. If I find it. Yes, I do find it here. It's fantastic. Where's the chat? Here's the chat.  

#### [0:15:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=900) |  So, definitely try to make it easier

for the browser by having long-lived cache. For e-commerce collection category pages that display product ratings, is a [INAUDIBLE].. That's a structured data question. I would take that to the office hours real quick. Last call, I asked about JavaScript files that were being requested by Googlebot after four years after they were embedded on our site. That is really weird.  

#### [0:15:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=930) |  I would be very surprised if that

isn't some sort of glitch in the way that the indexing runs. I wouldn't worry too much about that, normally. Especially if your content gets indexed anyways. But, if you share that problem with either this fantastic mailing list-- [INAUDIBLE] I can't type anymore. That mailing list called the JavaScript Sites Working Group,  

#### [0:16:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=960) |  where you can ask this with a

sample URL. Because this needs to be investigated. And I can't do private support. So you can't send that to me privately. But the Webmaster Forum or that mailing list is a fantastic place to get some feedback from others who might be able to help you with this problem, Trevor. And, for client-side [INAUDIBLE],, does having a site map speed up the second wave of crawling? Or does it stay the same with or without the site map? This is for a site with two million pages.  

#### [0:16:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=990) |  It depends, is the answer to that

question. First things first. There's no such thing as a second wave of crawling. Ish. The second wave is a oversimplification that is coming back to us with interesting implications every now and then. Basically, a site map just helps us discover things that we can't discover as quickly otherwise. Which means, if a site map helps you with discovery,  

#### [0:17:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1020) |  generally it's depending on your site structure

and on your crawl frequency, which has nothing to do with if you have a site map or not. If you have a very well linked structure between different pages anyways, then the site map is probably not going to be a big speed-up. But the site map definitely helps us discover new content, generally speaking, quicker. Two million pages, it might give you some advantage. It might not give you some advantage. Try that out. It definitely doesn't hurt. But it doesn't replace linking in the clean menu  

#### [0:17:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1050) |  structure and a clean linking structure between

your pages anyway. It's just a different way for us to consume content and discover links on your site. Awesome. Now, there was a question submitted on YouTube, which is from Dave. When fingerprinting resource files, is it better to change the name, like vendor  

#### [0:18:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1080) |  dot some version string dot JS? Or

can parameters work? For example, vendor js question mark version equals something. Parameters work for us. And that's perfectly fine. It might be tricky depending on your setup. If you have a cache in between or like a reverse proxy that somehow kills create parameters, I know that some CDNs do. Then it might not work. And it is sometimes harder to debug because you might not  

#### [0:18:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1110) |  have the level of logging that you

need to actually troubleshoot issues throughout multiple hosters and pieces of infrastructure. I would say generally it doesn't make a huge difference. But having it in the file name is probably a little more robust across different environments. So I would balance that. But generally speaking, it's fine to use parameters. SPEAKER 4: Yeah. MARTIN SPLITT: OK. SPEAKER 4: Sorry. [INAUDIBLE] so fast because if you do with a parameter,  

#### [0:19:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1140) |  and it changes, then it would potentially

still load, wouldn't it, if Googlebot or something is taking-- MARTIN SPLITT: That's true. SPEAKER 4: So you would get a fresher version, which I suppose could be both a blessing and a curse. But that would seem like the reason behind the question. MARTIN SPLITT: Then you make your life with debugging even harder. Because then you're like, I think we loaded version 5. But then it turns out that it was version 6. So it's like, huh. It really depends on your use case and on your environment.  

#### [0:19:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1170) |  I would say from experience that putting

it in the file name is slightly more robust. But either way works. It's not that one way wouldn't generally work. It's just if it doesn't, then debugging parameters is usually a little harder, depending on how your systems are configured, it might be a lot harder, in fact. SPEAKER 4: Yes. MARTIN SPLITT: Thank you very much for the question. Anyone else here having a question before I go back to the written questions?  

#### [0:20:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1200) |  Silence. OK. SPEAKER 5: So sorry, mate.

I just typed one out because it's a bit of a long-winded one. So probably better to write than trying to verbalize it. MARTIN SPLITT: Right. A client's currently building a new front end in Gatsby. Nice choice. And is setting up their own A/V-- oh. A/V testing. Yeah. Fun times.  

#### [0:20:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1230) |  Development is against URL changes and guidelines

how to separate URLs and canonicals are desired if we move to parameter injection, dependent on the version in canonical. [INAUDIBLE] JavaScript. I'm not sure I fully understand the question. SPEAKER 5: So a little bit [INAUDIBLE] contact, so obviously. Removing-- we're building a custom front end. [INAUDIBLE] our own custom A/B solution. Obviously, if we're going to build an A/B,  

#### [0:21:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1260) |  I want to append URLs with versions

or some sort of control, I mean, cross canonical back. They've said that will require a lot more engineering. So I'm trying to find a compromise where I can get parameter potentially injected. Obviously, because it's all being done in JavaScript, there's no CMS, because it's all being done headlessly as well. Then, do you perceive that if we inject, say, a parameter onto version B, and then you inject a canonical that way, that would still  

#### [0:21:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1290) |  meet the requirements for basically canonicalizing B

to A, C to A, et cetera, from a Google perspective? MARTIN SPLITT: I think that would. If you have parameters in your canonicals, even if they are JavaScript injected, that should be fine. SPEAKER 5: OK. That could be a good compromise. And thank you, Martin. MARTIN SPLITT: You're welcome. All right. I'm going to copy this over, then.  

#### [0:22:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1320) |  Oh. More people still joining us. Amazing.

Anyone else having a question for me at this point? Now is your chance. SPEAKER 1: I have another question. MARTIN SPLITT: Sure. SPEAKER 1: So, I'm not sure it's a JavaScript question or not, cause I'm not sure closed caption is created by JavaScript on most of the page. So my question is, if you have multiple languages closed  

#### [0:22:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1350) |  caption on the video, and I know

they are not in the source code. So they might be later inserted in JavaScript or something like that, [INAUDIBLE] closed caption? Or do they know that they have different language if I have multiple language? And is there a way to make sure that Google know that [INAUDIBLE]? MARTIN SPLITT: Video indexing is so far away from what I work on that I have no idea how we're indexing videos and how we're dealing with closed captions.  

#### [0:23:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1380) |  So I can't really answer the question.

But I would assume that whatever mechanism there is to provide closed captions, if you provide those, even if it's with JavaScript, it should be fine. I don't know how exactly this entire mechanism work. I've never worked with a video that much. But, I guess maybe the Webmaster Forum people might know about this. Or definitely, it is something that I can then hopefully send  

#### [0:23:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1410) |  onto other teams to discuss. But that's

not something that I can answer that easily. SPEAKER 1: OK. Thank you. MARTIN SPLITT: You're welcome. All right. In that case, do we have more questions in the-- I'm using JavaScript to set my title and description. It was stated that Googlebot respects it. But I noticed that sometimes it uses those titles and descriptions, but other times treats the website as if it had-- no-- sorry?  

#### [0:24:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1440) |  Oh OK. --as if it had no

title and description. How to prevent that and be sure that the Googlebot actually waits for JavaScript to kick in? Notices that the page is not empty because it looks as though it is like that. It's not a problem of us thinking that it's empty. Because if it would be an empty page, we wouldn't index it. Because there is nothing to index then. So we'd definitely be seeing the content if we indexed the page.  

![](https://i.ytimg.com/vi/DK1rJhvTAdM/maxres2.jpg)



#### [0:24:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1470) |  This effect seems to be random. My

website sometimes has a description and title and service and sometimes does not. I'm not sure what's going on there. I would definitely post this in the Webmaster Forums or in the JavaScript sites, WG. Generally speaking, whatever we see when we are done rendering, we put into the index and then move forward. We might rewrite the title anyway. I'm not sure if you're aware, but basically, when you give us a title and description and we figure out that it's not relevant to the query  

#### [0:25:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1500) |  or not relevant to the content on

your page, we might consider alternatives anyways. There is an entire system that deals with that. And sometimes, the system picks a title that you don't think is right, or sometimes it might not find a title that is worthwhile picking. But I don't think that we usually end up with empty titles. That is a really, really weird situation. I would definitely have a look at the URL inspection tool  

#### [0:25:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1530) |  and look at what kind of rendered

HTML we have in the crawl page. Probably also run a life test. Especially if it's an on-off thing, that suggests that there is some sort of issue on your end with the way that you are generating your HTML and JavaScript. It can be that your service sometimes times out, sometimes gives us a 404 or 500 of something like that. I would check the server logs to find out what's going on there. Especially because it sounds like your website is  

#### [0:26:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1560) |  client-side rendering, or at least, like, uses

JavaScript to change the content, because it does change the description and title. So I would check that your server definitely does not return any weird errors to us. And I would consider posting a URL into the JavaScript Sites WG, or into the Webmaster Forum so that we can take a look at this. Awesome. Anyone else here having a question?  

#### [0:26:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1590) |  SPEAKER 2: Yeah. Martin, I just went

tested few URLs and since [INAUDIBLE] index infinite scroll the articles. So that is very good. But I'm going to research a little bit more and find out what is the like, edit case when it does index, when it doesn't. But I believe that, [INAUDIBLE] John Mahler say that when you have an [INAUDIBLE],, you are [INAUDIBLE] indexed. Googlebot did not crawl that content.  

#### [0:27:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1620) |  That's why I asked again to get

some sort of confirmation. MARTIN SPLITT: Generally, that is true. It does depend on your implementation, though. SPEAKER 2: OK. MARTIN SPLITT: But good to hear that your implementation apparently seems to work the way that you expect it to work. So then that should generally be fine. SPEAKER 2: Thank you. MARTIN SPLITT: You're welcome. How big of a problem is it when a part of the website has client site rendering and Google can't render  

#### [0:27:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1650) |  any image of the website? Hold on.

Sorry I needed to admit someone to the hangout. And Google Bot cannot render any image of the website. I know it's not an optimal situation. But I have to convince the development team that this might be a problem. All textual content can be rendered. For example, and then we have a sample URL. I would have to look at the sample URL to see what is happening there.  

#### [0:28:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1680) |  Actually, let's do that real quick. Generally

speaking, if there is an image URL and we can't render it, that shouldn't necessarily be a problem, unless you want that image indexed. If you care for your images, which you probably should, then you might want to know why we are not rendering it. And then you can use various tools to see why the thing is happening. So I'm not sure. Oh shit. I used the wrong tool for this.  

#### [0:28:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1710) |  Let me quickly run this through mobile-friendly

test. This is really annoying because it's like a weird redirect thing going on. And I don't want the YouTube redirect. I want the URL itself. Real quick. I can probably share this with you all on my screen, if I figure out where [INAUDIBLE] my entire screen. And I want this screen.  

#### [0:29:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1740) |  This is going to be funky. So

I threw this into the mobile-friendly test. We can see that there are no images being rendered, which is because there's nothing specifically preventing us from seeing them, except that there's like, some CSS and some JavaScript not running. But that should not be a problem. Let's have a look at the HTML. If I scroll down here, can I search for the image tag,  

#### [0:29:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1770) |  maybe? Well, that's the image for the--

that's a bunch of images for all sorts of things in the menu. Now someone wants to join, so I'll let them in real quick. All of these are present, basically like menu images or something. And none of this is actually an image image.  

#### [0:30:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1800) |  So I'm not sure what kind of

image he is missing here. But I can't find them in the HTML. If they are not in the HTML, we're not going to even like, discover them. I'm not sure. Let's actually try this URL in the regular browser tab and have a look again. So there are a bunch of images that we are supposed to see, I would say. Yeah, and they are definitely present here.  

#### [0:30:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1830) |  They are not present for whatever reason

in the rendered HTML because I couldn't find any of this previously. Also really interesting. So there's an ALT tag here. And an ALT tag, an ALT attribute here. And we can maybe search for this in the-- come on. Don't do this to me. There we go. Oops. So we do find this in the text.  

#### [0:31:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1860) |  But I am not seeing this in

an ALT attribute. So that tells me that whatever they're doing, we are not seeing it in the rendered HTML. If we're not seeing it in the rendered HTML, you know what that means? That means that we are not able to index this. If you care for these images being indexed, definitely you need to figure this out. Because that means that we are not seeing them right now.  

#### [0:31:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1890) |  Good. Any more questions from you all

before I go back to the list of questions? SPEAKER 6: I had a-- SPEAKER 7: I had a quick question. MARTIN SPLITT: Oh, multiple. Multiple people. Oh oh oh. OK. One after the other. SPEAKER 7: Yeah, go ahead. Go ahead. SPEAKER 6: OK, great. So we have clients whose website is awfully, awfully outdated  

#### [0:32:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1920) |  and they are about part of a

big corporate system. So an upgrade is a bit out in the future. And currently, they can't add any sort of editorial content. MARTIN SPLITT: Mm-hmm. SPEAKER 6: How would-- how would Google look at it if we made a sort of a workaround  

#### [0:32:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1950) |  where we added content using JavaScript? Like,

we, at the front page, we might add a parameter, add a URL with a parameter through JavaScript to a sort of a fake page by overriding another, or adding and another, like fictitious parameter with custom content.  

#### [0:33:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=1980) |  MARTIN SPLITT: So, you can totally do

that. Especially if the content is basically an update of the previous content at the same page, then that's not a problem. Googlebot would see that rendered content, unless your implementation has some flaw or problem. You can test that with the testing tools. Creating fake pages through history API is a little bit of a tricky one,  

#### [0:33:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2010) |  because then, you can't necessarily assume that

it will always return the right content if you're getting on the page and the JavaScript breaks. But fundamentally, it works. It is a brittle solution. But it is better than probably like, dealing with like, we can't do anything on our website at all. I would definitely very, very carefully test the implementation, whatever you're building. But if you use JavaScript to inject content, we see it as normal content. SPEAKER 6: OK great. Thanks.  

#### [0:34:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2040) |  MARTIN SPLITT: You're welcome. SPEAKER 7: I

just wanted to ask if now with the JavaScript where Googlebot still doesn't scroll through the pages nor click the buttons or-- MARTIN SPLITT: Correct. SPEAKER 7: Correct? MARTIN SPLITT: Yeah. SPEAKER 7: OK. OK. So, any like, JavaScript buttons that opens, for example, drop-downs and stuff  

#### [0:34:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2070) |  like that with content inside, they won't

see it? MARTIN SPLITT: Depends on the implementation, the way-- if you only load the content into the DOM or only make it part of the active HTML document after user interaction, then we won't see it. But if it is rendered into the HTML beforehand, and only becomes visible through user interface, then we might still index it. SPEAKER 7: OK. MARTIN SPLITT: We just won't click on anything.  

#### [0:35:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2100) |  So if you have a button that

takes you to a different page, we won't click on it. We won't see that. SPEAKER 7: OK. The only thing you do click on, quote, unquote, is anchor tags, right? MARTIN SPLITT: Yes. Yeah. SPEAKER 7: OK. MARTIN SPLITT: We don't click on those either. We use the H ref URLs. SPEAKER 7: OK. OK. Thanks. MARTIN SPLITT: You're welcome. There's a follow-up question. We can't index an image if it's not in the HTML.  

#### [0:35:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2130) |  Since this is the case, how do

we make sure lazy loaded images are indexable? Lazy loaded images. There's two options here. So one is, if there is an image tag that has the loading equals lazy, we will see it because it has a source attribute. If you do not use the source attribute in lazy load and basically update the image, then it depends on your implementation. For instance, if you are using an IntersectionObserver, that would not become a problem because we are doing something  

#### [0:36:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2160) |  to make the viewport large enough for

your website. And then the lazy loading would kick in and would create the image source attribute that we need. And then in the rendered HTML, you would see the actual image source. And I can show you an example of that. Let me real quickly show you something. Oh OK. Someone wanted to be in this. SPEAKER 1: So based on what you just say, it indicated Googlebot do scroll down.  

![](https://i.ytimg.com/vi/DK1rJhvTAdM/maxres3.jpg)



#### [0:36:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2190) |  MARTIN SPLITT: No. It does not scroll

down. There's other ways of changing the viewport so that things become visible. SPEAKER 1: I see. MARTIN SPLITT: I don't want to discuss this too much, because it's an implementation detail that I don't want people to like, cling on. But-- actually, this is the wrong website. Where did I have this? I think it was here somewhere. Lazy loading experiments.  

#### [0:37:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2220) |  I guess? Yes. No? Oh, god. OK,

let me see if I can find this back. And I think someone wanted to join the hangout. Yes. OK. So I can actually make this larger. So I built a bunch of test cases for lazy loading. Let's use lazy sizes, for instance. The way that these pages work is they-- oops. I'm not in front of the protocol yet. The way that this works is we have a bunch of HTML, very, very boring text.  

#### [0:37:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2250) |  And then we have an image tag

that does not have a source. Well it has a source, but it's only like a 1 x 1 pixel source. And then the data source is what's used to actually lazy load this content. And, I can show you that this works by actually seeing like 100 x 100, 200 x 200, 300 x 300, 400 x 400, and 500 x 500. So these images lazy loaded as they became visible. And if I'm lucky, and this thing doesn't break on me while  

#### [0:38:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2280) |  I'm doing this, because every now and

then we run it into interesting resource situations here, where it's-- the problem is the testing tools are very impatient. So sometimes if things take too long, then the testing tools bail out where they shouldn't have bailed out. We can see all resources. And here you see, it loaded 100 x 100. It loaded 200 x 200, 300 x 300, 400 x 400, and 500 x 500. So all these images have been successfully loaded  

#### [0:38:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2310) |  and will be indexed. And that's actually

what really matters when it comes to lazy loading. So this implementation actually works. You can also see that in the rendered HTML. If I scroll down to, let's say, here, then we see that the source has been replaced by the 200 x 200 image source as lazy loading would do. So this is how you can test your implementations. And that way, you know if you're lazy loading works or doesn't. It is not very easy to say, yeah,  

#### [0:39:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2340) |  that totally works and this other thing

doesn't. You have to test these things, unfortunately. SPEAKER 1: So not just reloading. Anything that is JavaScript inserted, if they show up in a ref result, they can potentially be indexed too? MARTIN SPLITT: Mm-hmm. SPEAKER 1: OK. MARTIN SPLITT: Yeah. SPEAKER 1: Thank you, sir. MARTIN SPLITT: You're welcome. Do we have more questions in the-- no, there's not more questions on YouTube. So if you have any further questions, now is a good time for those.  

#### [0:39:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2370) |  SPEAKER 7: Yeah, can I ask another

one? I just remember. For example, we use Google Maps API. And since now Google Bots executes JavaScript, does that mean it will consume the quota? MARTIN SPLITT: That's a really good question. There is a potential that this might actually happen. But I think, if I remember correctly, because Google Maps does not normally generate--  

#### [0:40:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2400) |  I'm not sure. You would have to

check if Google Maps gets robotted away or not. But generally speaking, we are very aggressively caching things. So I wouldn't worry too much about this. But definitely test that. Because I don't know if we are skipping Google Maps or not. That's a very good question. SPEAKER 7: OK, thank you. MARTIN SPLITT: You're welcome. Thank you very much for asking all these good questions.  

#### [0:40:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2430) |  I'm really happy with the questions being

asked today. SPEAKER 2: Martin, just one thought that came to my mind. Like, I have implemented the infinite scroll also in AMP [INAUDIBLE] next page new feature. So I'm guessing the way it's implemented the next page feature of AMP does guarantee somehow like,  

#### [0:41:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2460) |  next articles even not the index is

a part of the content, right? Because the way you thought and planned and implemented the next page of AMP should supposed also avoid that issue. Can I [INAUDIBLE] MARTIN SPLITT: Yeah. I'm not sure about AMP. SPEAKER 2: OK. MARTIN SPLITT: All right.  

#### [0:41:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2490) |  Cool. Any further questions? Let me check

the chat. No. No questions in the chat. All right. Any further questions? SPEAKER 7: So is Googlebot doing the two-pass thing? Like before it reads the HTML, and then  

#### [0:42:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2520) |  after a while, the renders the JavaScript

and gets rendered source or something like that? Or is now faster. Because I remember that it used to be like there were experiments of people like, creating different versions of their pages and saying, hey, after a week, disappeared on Google. And after a couple of days, disappear on Google.  

#### [0:42:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2550) |  MARTIN SPLITT: So generally speaking, we are

still somehow like, looking-- so we are running some analysis on the initial HTML, specifically to discover links or linked discovery is fastest if you server site render still. But fundamentally, you can assume that every page gets rendered, and you can assume that between initial crawling and rendering, on median, there's a delay of five seconds in the queue. And then plus the time that it takes  

#### [0:43:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2580) |  to actually render your page. If your

page renders in 10 seconds, then you wait 15 seconds at median. If your page renders an hour-- actually, no page renders an hour. That's bullshit. But like a minute, then that extra minute comes on top of that. But yeah. Generally speaking, JavaScript rendering got a lot faster these days. SPEAKER 7: And do you cut off the rendering at some point? Like, if you have a very long page? Or-- MARTIN SPLITT: We do. It is very hard to specifically say something  

#### [0:43:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2610) |  because it depends on a bunch of

heuristics and signals. So I would not worry about it too much. If it's fast for your user, then you should not have a problem. If you have to bind your user for two minutes to actually get any content, then you might run into problems to begin with. It's not an SEO-specific problem. So you shouldn't worry too much about that specifically for SEO. SPEAKER 7: OK. OK. Thank you very much. SPEAKER 4: I've got a question, if that's OK. If on an SPA that you're routing locally,  

#### [0:44:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2640) |  I notice kind of two options for

a 404. You can either no index, or you can redirect up to an actual 404 outside. Is there any benefits between the two? Or is there both just as good a solution as another, just depends on what's easiest? [INAUDIBLE] MARTIN SPLITT: Yeah. Both of them are as good as a solution. It really depends on what's easier for you and there's not that much of a difference between the two.  

#### [0:44:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2670) |  SPEAKER 4: Thank you. MARTIN SPLITT: You're

welcome. There is, however, this one note that I would like to give if, like, I've seen it happen. And I've done that mistake myself many years ago. If you think that it's a smart solution to have a robots no index in your rendered HTML-- in the HTML that you sent initially, and then switch that back with JavaScript, don't. Because what happens is, we see the initial HTML. We see no index and we stop. And we don't execute the JavaScript.  

#### [0:45:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2700) |  So like the robot thing has a

risk attached to it if someone, somehow decides to put no index in the HTML, and then switch that with JavaScript, which redirects don't have. But I could see people screwing up either solution. So, both of that is risky to a certain degree. SPEAKER 4: Thank you.  

#### [0:45:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2730) |  MARTIN SPLITT: All right. SPEAKER 6: Just

to be clear, you just said that, if the HTML contains no index, that would prevent you from executing the rest of the page basically, right? MARTIN SPLITT: Pretty much. And when I say no index, I specifically mean like a meta robots content no index. If you have no index in the robots tag, we basically do not render the page.  

#### [0:46:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2760) |  That's what happens. We also mentioned that

in the documentation, if I remember correctly. I can see if I can find the documentation link real quick. And, whoa. OK. That has changed. Let's see. I believe this might be here, or is it in the other one? I'm not sure. No index.  

#### [0:46:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2790) |  We don't explain it here. I think

it's explained here. Yeah. This one. So we explain this in the documentation. You can swap-- you can basically dynamically add a new index. You cannot dynamically remove a new index from the page with JavaScript.  

#### [0:47:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2820) |  OK. One last question? Or maybe two

more. I don't know yet. All right. So if there are no further questions, I would like to take this opportunity to say thank you so much for coming to the first official JavaScript SEO Office Hours.  

#### [0:47:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2850) |  I hope this was useful and that

you got the answers you were looking for. If you have any further questions, remember, we do have the Webmaster Forum. We do have the JavaScript site working group that you can post questions to. It's usually a good idea to send us also URLs, as in like, send either the Webmaster Forum or the sites working group to send a URL there. We can see the problem action, or even  

#### [0:48:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2880) |  try to build like a tiny little

prototype that exhibits the behavior you're wondering about so that it's easier to debug these things. Please continue watching out the my Twitter feed as well as the YouTube channels community page for the next Office Hours to happen. I expect them to be approximately every two weeks. And yeah, I'll upload the video to YouTube later on. And thank you so much for being fantastic people and asking great questions. And have a great day.  

#### [0:48:30](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2910) |  SPEAKER 8: Thank you, Martin. SPEAKER 7:

Thank you. Thank you. MARTIN SPLITT: Thanks, everyone for, coming. Bye-bye. SPEAKER 9: Thank you, Martin [INAUDIBLE].. SPEAKER 5: Goodbye. MARTIN SPLITT: Bye. SPEAKER 2: [INAUDIBLE]  

#### [0:49:00](https://www.youtube.com/watch?v=DK1rJhvTAdM&t=2940) |  MARTIN SPLITT: Oh, I need to stop

the recording somehow. Stop recording. Oof.  