[![JavaScript SEO office hours April 22nd 2020](https://i.ytimg.com/vi/r8EEW6wMamc/maxresdefault.jpg)](https://www.youtube.com/watch?v=r8EEW6wMamc)

## JavaScript SEO office hours April 22nd 2020





#### [0:00:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=0) |  MARTIN SPLITT: All right. Hi, everybody, and

welcome to the JavaScript SEO office hours for this week. I see that we have a few people in the hangout with me as well. And we have a bunch of questions that were submitted, so I'm thinking that we have quite a bit to go through. Is there anyone in the hangout who wants to already ask a question before I dive into the YouTube-submitted questions? SPEAKER 1: So I have a question for the beginning stuff.  

#### [0:00:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=30) |  It's OK. We have one problem since

two months. We have add two index XMLs to our Search Console. MARTIN SPLITT: So you have two sitemaps. SPEAKER 1: Two index sitemaps. MARTIN SPLITT: A-ha, OK. SPEAKER 1: With sub-sitemaps. MARTIN SPLITT: OK. SPEAKER 1: And we have look in our programmers,  

#### [0:01:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=60) |  and we can't see any difficult with

this. And the point is how we can maybe check from Google if the sitemap is not really good or something else. Then the Google Search Console show us no trouble information but only read two sitemaps from the second index sitemaps from round about 600 sitemaps.  

#### [0:01:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=90) |  MARTIN SPLITT: You mean URLs from the

sitemaps? You don't have 600 sitemaps, right? SPEAKER 1: No, no. We have 600 sitemaps. MARTIN SPLITT: How many pages does your website have? SPEAKER 1: Roundabout, let me not lie-- over 1 million. We have 3D parts with configurations. MARTIN SPLITT: Right. But why do you have 600 sitemaps? SPEAKER 1: This is catalogs, catalog sitemaps  

#### [0:02:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=120) |  with parts from the catalogs. For example,

we have parts from MRN. And they make something like screws, and engines, and something else. And you can go to us and download 3D files from this to use it for your CAD models and so. MARTIN SPLITT: Right. But why is there a separate sitemap for just that? Why is that not a part of the general sitemap?  

#### [0:02:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=150) |  I mean, I get the point that

some websites are nesting their sitemaps, but for that many URLs. That doesn't sound like-- SPEAKER 1: I'm afraid we need to split by 50,000 sitemaps, links. MARTIN SPLITT: And URLs in there. OK. SPEAKER 1: Yeah, we need to split. And then we need to make a new sitemap.  

#### [0:03:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=180) |  MARTIN SPLITT: I [INAUDIBLE] know where the

maximum number of URL is, actually. But let me double-check if we can-- sitemaps is a little outside of what I'm normally dealing with. But-- OK. So with the sitemap question, I'm not 100% sure because that's a little outside of my area of main expertise. But generally speaking, if I understand correctly, the problem was that we are not seeing all of your nested sitemaps, or we are not indexing  

#### [0:03:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=210) |  all the URLs from the sitemap. SPEAKER

1: So the problem is the second index sitemap. Let me explain. The second index sitemap have over 600 sitemaps. Index sitemaps have over-- MARTIN SPLITT: Right. Hold on, hold on. So you have a sitemap XML, and then in the sitemap XML, you are specifying other sitemaps, right? SPEAKER 1: Yes. MARTIN SPLITT: And now we're talking about one that is specified in there, like you have some-- SPEAKER 1: No, no, no. We have two of these.  

#### [0:04:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=240) |  We have one sitemap with specified sitemaps,

one index sitemaps. And the second index sitemaps have the problem that only the second and the five elements, the second and the five sitemap in this index sitemap has only got read. Anything else is ignored. And I don't understand why the look for the second and the five element-- MARTIN SPLITT: Interesting. SPEAKER 1: --not for the first and so. [INAUDIBLE] MARTIN SPLITT: That should not happen, generally speaking.  

#### [0:04:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=270) |  I would bring that up either in

the Webmaster forum or in the general SEO office hours with John because he might know something that I don't know about this kind of thing. SPEAKER 1: OK. OK. Good. MARTIN SPLITT: Awesome. Sorry that I wasn't the right person to answer this one. SPEAKER 1: No problem. Thank you. MARTIN SPLITT: You're welcome. Now I think I'll take one from YouTube. We are in the process of replacing the HTML text content of our pages with JavaScript  

#### [0:05:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=300) |  fill text commands on the HTML5 candidates.

That's not a good idea. Are there any plans to index text and images canvases in the near future? I can't predict the future. I can't make announcements of that sort. I don't know. We don't have any plans ready for public highlight that we are planning on indexing texts and images  

#### [0:05:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=330) |  or in canvases. What are the recommendations

to exposing this text content in the way the indexer can actually read it without violating cloaking guidelines? Honestly, for accessibility reasons to begin with, you should not do this. I know a bunch of projects that tried to do this successfully, and nicely, and fancily. They all are not around anymore because it turns out to be quite hard to do this, what your browser does  

#### [0:06:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=360) |  for you for free. You can't use

CSS. You can't use any of the browser-given resize or responsive paradigms. You have to basically calculate everything yourself. That is a pain for both people using screen readers as well as bots. And it also is not very performant usually, unless you are really using something like WebGL acceleration for this. But I would just refrain from doing it, unless you have a very, very important use case where  

#### [0:06:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=390) |  you 100% have to do this, and

then you just bite the pill that you are not getting indexed. But honestly, I would not do that. To avoid impacting page load times, we would like to populate this HTML strictly after the visual text is painted to the canvas. What signals can we send/receive to ensure the text is ready before the indexer snapshots the page? There is no such thing. Just build a normal HTML page. Trust me. You will be better off. That's that. Canvas and image rendering things, I would not do that.  

#### [0:07:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=420) |  Now. More people joining. That's lovely. You

advised on April 8-- that's a good one. On April 8, you advised against noscript in favor of native lazy-loading or-- something like, for instance, the Intersection Observer, what they say is the Google-suggested way. But the former have browser compatibility issues  

#### [0:07:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=450) |  so then later you will not show

images for users without JavaScript. Well, first things first, I didn't say I advise strictly against using noscript. That was something that was blogged about, but it's not what I said. I said I would not recommend relying on it 100% and for the future because you don't know if we actually at some point might deprecate that. We are not having plans to deprecate that either, but I just say it's a fallback solution that I would not exactly suggest.  

#### [0:08:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=480) |  The native lazy-loading, yes. That is not

compatible with all the browsers. A bunch of browsers don't support it. But I think it is a nice, progressive enhancement for those people who are using a browser that supports it. And more browser support will follow in the future, I am pretty sure, because it's kind of like an obvious thing to do. And those who are on an older browser might not get it. But they're not losing something. They don't have the best experience, sure. But you have to draw a line somewhere.  

#### [0:08:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=510) |  If you understand your user base well

enough to say, oh, most of our users are actually on a browser that don't support it-- which I think I would argue today is actually the case for most websites, to be honest-- you can do both the noscript fallback on top of the JavaScript way that we can index it, because that doesn't hurt you either, especially because the noscript fallback is for those users who are not using JavaScript. And they would get the images nonetheless. And then the crawlers who understand JavaScript  

#### [0:09:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=540) |  get the lazy-loading that works, using, for

instance, an Intersection Observer, whereas the crawlers that don't support JavaScript also get the noscript version. I think that's fine to do. I'm just saying you want to re-evaluate that in the future. It's not a bullet-proof thing forever, unless you are using the way that works for Chromium-based browsers. Because that's I think what Bing uses  

#### [0:09:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=570) |  as well because they use Edge, and

Edge is now a Chrome-based browser. As well as we are using Chromium to render, so we are seeing the content. I'm pretty sure Bing will see the content. You would have to test with their tools to make sure that they see the content. And that's not going away, whereas the noscript fallback, if that's your only strategy, it might go away at some point in the future. Might being the keyword here. I'm not saying we are about to deprecate it. What I'm saying is it's not a future-proof thing  

#### [0:10:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=600) |  for SEO purposes. It is still future-proof

for your users. So go with that. But anyway, you would have to more or less evaluate what works for your user base and for your use case as well. SHAO CHIEH LO: So, Martin, that is my question. I have a follow-up question on that. I also have it here. MARTIN SPLITT: OK. SHAO CHIEH LO: Compared to the method that you just said using JavaScript and fall back to noscript,  

#### [0:10:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=630) |  there is another method that also progresses

enhancement, recommended by Lighthouse. I paste the link here. What they do is that they say that you actually can do one thing they said. You use native lazy-loading first. But you don't put RC first. You put data as RC in the native lazy-loading. And then you use JavaScript to detect if the browser's supported.  

#### [0:11:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=660) |  If not, they [INAUDIBLE] fill the JavaScript

to do [INAUDIBLE] basically lazy-load a native-- [INTERPOSING VOICES] SHAO CHIEH LO: --pull back to JavaScript-- [INTERPOSING VOICES] SHAO CHIEH LO: --load. So my question here is that-- SPEAKER 2: Let me set up my screen. SHAO CHIEH LO: So my question here is that, first, how do we specify the placeholder in this kind of fallback case? It's like if you use JS lazy-load first directly, you know the placeholder is IMC source.  

#### [0:11:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=690) |  But if we do this kind of

progressive enhancement, how do we specify placeholder? And another issue is that, compared to this and use direct JavaScript lazy-load directly and fall back to noscript, which one is more safe? Yeah. MARTIN SPLITT: There is no simple answer to this, is the thing. You would have to make up your mind.  

#### [0:12:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=720) |  And basically you would have to look

at the different approaches, and you would have to decide what works for our use case. If you know that pretty much everyone is on a browser that supports JavaScript and the no JavaScript case is something that you can reasonably ignore, or you are already ignoring in the rest of your development, then I would say using either the JavaScript approach with the Intersection Observer, or maybe using this hybrid approach that web.dev documented here is a very fine way to go about it.  

#### [0:12:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=750) |  You can always also specify the noscript

version. That never hurts. It won't hurt you. You should not rely on the noscript version to fix all your SEO problems in the next hundred years. But for now, it works even for Google Search. It would just mean you have multiple ways of actually giving us the image. We don't really worry about that. It's not a problem to have a noscript fallback. So if you want to be super foolproof and make sure that it always displays images,  

#### [0:13:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=780) |  you can use one of the lazy-load

link strategies plus the noscript fallback, for instance. You can use the approach that web.dev took. I'm guessing, as a placeholder, you can just specify the image source here on top of the data source. I guess that's fine. I'm not sure about that. You would have to ask whoever wrote this article, which is not clear from the page itself. Yes, it is. The authors were Hussien, Addy, or Matthias  

#### [0:13:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=810) |  would be the persons to ask for

the specific approach that they documented here. But, yeah. So noscript will be foolproof and is a way of making sure that it also works when JavaScript does fail. SHAO CHIEH LO: OK. Thank you so much. MARTIN SPLITT: You're welcome. SHAO CHIEH LO: I just have a follow-up question. Not really related. A lot of the developers worry about browser don't support JavaScript. But actually, how many browser actually don't  

![](https://i.ytimg.com/vi/r8EEW6wMamc/maxres1.jpg)



#### [0:14:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=840) |  support JavaScript nowadays? MARTIN SPLITT: That's a

good question. And the answer is that's the wrong question. Because the thing is, yes, pretty much every browser supports JavaScript. But there are privacy extensions that some people use that are very, very clearly disabling pretty much everything unless the user specifically opts in. So they might not see the content immediately. There can always be transmission issues if you're on the mobile phone. The HTML, as the HTML arrives over the wire,  

#### [0:14:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=870) |  can already start rendering. With the JavaScript,

I have to wait until everything comes down. And if my JavaScript is half a megabyte, and then in the middle of it the connection is cut, the JavaScript won't execute, and I won't see anything on my phone. So that's the case that you might want to prepare yourself for, but only if you have data that you need to prepare for that. So if you have, for instance, telemetry on the errors that you are getting, and there's errors that support the hypothesis that JavaScript  

#### [0:15:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=900) |  loading failed for a bunch of your

users, you might want to consider that a case for noscript. But, generally speaking, pretty much every browser has JavaScript, and it normally works. There are cases where it might not work. SHAO CHIEH LO: OK. Thank you so much. MARTIN SPLITT: You're welcome. When static HTML and the rendered JavaScript title in the metadata differ, will Google always use the rendered JavaScript metadata? Fun fact-- usually yes, but we might also just consider it a bad title if the title does not  

#### [0:15:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=930) |  seem to be relevant to the actual

page content, and then we just might rewrite it. The same goes if the query suggests that we might want to rewrite the title, we might rewrite the title. But generally speaking, the rendered JavaScript title should take precedence, unless there is something going wrong in rendering, which is unlikely. Do we have questions from the Hangout before I continue with the submitted questions? SHAO CHIEH LO: I have another one.  

#### [0:16:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=960) |  MARTIN SPLITT: Sure. SHAO CHIEH LO: So

my question here is that HTTP/2 is supported by most of the browser nowadays, and most of the websites are using them. Is that still important to limit HTTP requests for external JavaScript in CSS? Because they are download parallel anyway. For example, if I have 100 external JavaScript and they are deferred, so async, would it still be a problem for page speed?  

#### [0:16:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=990) |  MARTIN SPLITT: That's a good question. I

think there is still a maximum of multiplexing that can happen in HTTP/2. I'm not sure what that would be like. But I'm not sure if you can just say, OK, I'll just get everything over HTTP/2 in parallel. Some browsers and some connections might still fall back, for whatever reason, to HTTP/1. So, hmm. I would be a little careful with that.  

#### [0:17:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1020) |  I would still try to minimize the

amount of resources that you are loading specifically, which is like this weird thing. You have to find the balance between minimizing the amount of resources and also making sure that you're not forcing the entire application bundle down on every request. It's a dance between splitting the bundles reasonably and minimizing the amount of external resources. SHAO CHIEH LO: OK. So from what I've heard is that it's still safer to try to not request too much request [INAUDIBLE]..  

#### [0:17:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1050) |  MARTIN SPLITT: It definitely is safer until

we are very, very surely in HTTP/2 land. Also, for instance, Googlebot will still fetch from HTTP/1, at least for now. So, hmm. SHAO CHIEH LO: OK. Thank you. MARTIN SPLITT: You're welcome. I run site audits for clients, and one point is to check JavaScript navigation. But I thought Google can follow JavaScript navigation.  

#### [0:18:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1080) |  Are there any cases where it can't?

What's the proper way to execute this so it's not a problem? Is the person who asked this question in this Hangout, maybe? No. OK. Generally speaking, if you use JavaScript to generate your navigation, that should be fine. If you are generating proper links-- and proper links are links that have a proper URL, and an HREF, and are an anchor tag, and all that-- then that should be fine.  

#### [0:18:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1110) |  If your navigation, for some reason, is

a dropdown, we are not going to interact with that. And when I say dropdown, I specifically mean like an HTML select element or something like that. If your navigation is a bunch of span elements, or LI elements with an onclick handler, we're not going to see that. But that's not specific to JavaScript navigation. That's just generally specific to links. So just make sure that we see the content rendered  

#### [0:19:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1140) |  in our testing tools. So you can

use Google Search Console or the rich results test, or the mobile-friendly test to make sure that the content is in the DOM. And then with that, you should be fine. That's pretty much it. Oh, there's another good question that I saw earlier. Many sites we review enjoy using full-page hero images that require a scroll to see the rest of the content. All data is in DOM without scrolling. So Google Render look poor, like the screenshot  

#### [0:19:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1170) |  that you get looks poor. Can this

be an indexing handicap to the content you need to scroll to, some of that hidden content? No. No, that's not a problem. If it's in the DOM, that's fine. That's it. Don't worry about it. Just make sure that it's in the DOM. That's really important. Do we have questions from the live audience? SPEAKER 1: Sure, I have a question. MARTIN SPLITT: Sure. SPEAKER 1: Maybe a little bit a crawling problem  

#### [0:20:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1200) |  with Googlebot and JavaScript. So we have

around about five months changed our URL schema. So from URL ?q= blah, blah, blah, blah, blah to /folder stuff.  

#### [0:20:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1230) |  And we have, from time to time,

the problem that Google crawled new URLs with the wrong URL schema, with the old one. MARTIN SPLITT: Right. SPEAKER 1: About the last one is from one week. And the question is is this the problem from Google,  

#### [0:21:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1260) |  that they catch the JavaScript too long?

And when yes, how long catch the Googlebot the JavaScript? MARTIN SPLITT: That is one possibility. It is possible that we are seeing the old URLs because your JavaScript wasn't updated. That is definitely a possibility. We are trying to cache as long as possible. We might cache longer than you specify in the cache header. The best thing that you can do is version your JavaScript assets.  

#### [0:21:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1290) |  There's different ways of doing that. SPEAKER

1: We do this. And we can see an effect-- yeah. Sorry. MARTIN SPLITT: Then that shouldn't be a problem. There are certain situations where we might hit the old version, but it's very unlikely. What can also happen is that we're just seeing somewhere else linking to the old URLs. SPEAKER 1: OK. And the second question is, if I look at this link, he say to me the canonical is like the link he get.  

#### [0:22:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1320) |  And this is totally wrong. He can't

get this canonical. We have write something that we changed the canonical to the new one. Safe. MARTIN SPLITT: That is great. However, that's not how that works. The canonical that you give us is a hint to us. SPEAKER 1: Oh. MARTIN SPLITT: There are situations where we might decide that that's a nice hint that you gave us, but we think the other thing has a good reason to become the canonical lead in this case.  

#### [0:22:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1350) |  So we basically cluster the URLs, and

then we choose the leader from that cluster. We say, OK, so all of these URLs point to the same thing. And then we look at signals. And one of the signals is the canonical that you pick. But very often webmasters pick the canonical incorrectly. So we can't just use that and then be merry with it because we would break half of the internet that way in Google Search. So what we do is then we look at other things,  

#### [0:23:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1380) |  like how many inbound links do we

have on this, and how often do we call these, and what kind of content do we see at these. The canonical can change over time. So if these old URLs are dying out, then I wouldn't worry too much about that, especially if your server setup is anyway redirecting to the right URL, then whatever. I wouldn't worry too much about it. It can be a little bit of a pain to actually track reports in Search Console then, because they are using the canonical. I'm aware of that, but unfortunately I  

#### [0:23:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1410) |  don't have an easy answer for this.

If you have a sample URL, and you post it on the Webmaster forum and you point me to the thread, or you post it here in the chat, or in the YouTube thread for further questions, I can take a look at it. But I can't do much about it. I can only maybe at least explain why this happens. But there's not that much action that can be taken by me, or anyone else really.  

#### [0:24:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1440) |  If the old URLs are disappearing from

the internet, and you are also submitting the new URLs via a sitemap, and you're making sure that pretty much everything redirects to that new URL to be the target, then eventually we'll see that, OK, the old URL that we picked as a canonical is no longer a good candidate for this. And then we might switch over to the canonical that you're giving us. Shouldn't cause a problem, but is a little inconvenient, especially in reporting. I'm aware.  

#### [0:24:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1470) |  SPEAKER 1: OK. Thank you again. MARTIN

SPLITT: You're welcome. So let's pick another question from here. Bunch of them aren't actually JavaScript-related, but that's fine. Hi, Martin. How does Googlebot handle the spoiler boxes? What's a spoiler box? There's a link, and then there's an HREF to some ID,  

#### [0:25:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1500) |  and then there's a onclick handler that

does a bunch of stuff with jQuery. Oh! That's an easy question. We don't click on links. It looks like you're not loading different content. You're just moving things around and making them visible or invisible. So if the content is in the DOM, how it looks like to me, this will be mostly fine.  

#### [0:25:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1530) |  If it's hidden content, we might think

it's not that important. If this is your main content, the spoiler box is your main content, you do not want to hide this, neither from the user nor from the bot. I think if it's hidden, we will consider it. We might not highlight it in the snippet, but we will see the content in the DOM, if it's in the DOM. If it's just in the DOM and hidden, we will see the content. But we won't click on the thing, so we won't ever see the spoiler box opened, I think.  

#### [0:26:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1560) |  Which should not be a problem. Right.

More questions from the audience? DAVE SMART: Yeah, I've got one. MARTIN SPLITT: All right. DAVE SMART: Little bit more performance and speed-related, really. Particularly when you've got something like an SPA, initial load might be much slower than obviously navigating through the roots or something to hide rates. But I assume that maybe Google would  

#### [0:26:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1590) |  consider maybe that first load because that's

what's important from Google's perspective rather than speed. It might be slow when someone's using the app. Would that be a roughly right assumption? MARTIN SPLITT: That sounds pretty much right, in the sense of yes, sure, the moment a new user comes in the website will be slow, and then it will be faster on subsequent navigations. That's the same kind of situation that you run into, especially if you  

#### [0:27:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1620) |  use a service worker, right? If you

use a service worker, and your service worker caches everything on the first load, and then everything else is fast, that's fantastic for the user. Except that you still need to worry about the initial load time because that's what a first-time user sees. And the first-time users are normally the ones that are from a user experience point of view. If I'm doing a user study, the first visits are what I most worry about because those are the people who are most volatile.  

#### [0:27:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1650) |  They come to your website the first

time, and they're like, argh, this is not loading! And then they are gone. So all the things that your service worker, or your single page application, did in the background are lost. So I would say for page speed, you definitely want to have a close look at the first load experience. DAVE SMART: Thank you. MARTIN SPLITT: Awesome. Also, that reminds me. Someone recently somewhere asked me to explain a service worker  

#### [0:28:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1680) |  in layman's terms. And I'll try. If

the person who asked that is in here or sees this recording, you'll be happy. A service worker, very fundamentally said, is basically an intermediary between your application and the network. So you can imagine if you have a normal website without a service worker, the website, whatever it does, whenever it sees, oh, there's an image that I need to load, it goes to the network and fetches the image from the network. Right? That's what it does. There is also a cache that the browser controls,  

![](https://i.ytimg.com/vi/r8EEW6wMamc/maxres2.jpg)



#### [0:28:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1710) |  but that might or might not happen.

So the website goes, oh, there's an image I need to load. And then the browser might go like, you don't have to go to the internet! I happen to have it here. It's like, oh, cool. Cool, nice. But you don't really have control over that cache as much because you only control that via your server headers. And if there's a proxy in between it might strip the headers. And there's a bunch of things that can go wrong with the caching. Now, a service worker is basically a little program. It's literally a JavaScript program that you can specify for your site. I can say, OK, I'm owning example.com,  

#### [0:29:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1740) |  and I want to install this little

service worker which is a little JavaScript program where whenever the network is somehow involved, this little program gets woken up and gets to decide what to do with that situation. So basically, if I'm the service worker now, and there's the website over there, and the website goes, oh, I have an image to fetch, that will basically ring a little bell. I will wake up and be like, oh, you need to fetch an image. All right. And now it's the decision and the job of the service worker  

#### [0:29:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1770) |  to figure out what to do. It

can do a bunch of things. It can just be like, oh, you need an image. OK, cool. You need that something something header.png. Sure. And then goes off to the network and fetches it. That's the dumbest service worker possible because it does what the browser would do. But it also has options to, for instance, have its own little cache, which is basically a storage room. So the service worker gets woken up. Get me that image. And it goes like, oh, all right. OK, cool. In that case, I'll get it. And I'll make a copy, and I'll put that copy in my storage room.  

#### [0:30:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1800) |  Here you have it. And then, the

next time the website asks for the image, it has, again, more choice. Because now I have it in my storage room, so I can either go like, this might be old, and there might be a new version of this image, but this is fine. This is just the logo of the company, for instance. Here you go. Right away without even considering the network. Then I can optionally ask the network if I want to update my copied version of that image, or maybe I only do that once a week, or whatever. I have the full flexibility as the service worker.  

#### [0:30:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1830) |  So you program how your application behaves.

The biggest advantage of that is that now, without making any changes to the website, if my service worker stores everything it sees in a cache-- and maybe even when I install the service worker, I give it a list of things to put in its cache beforehand so that basically the first time I visit the website, sure, the thing has to go to the network and fetch the image. But my service worker also fetches everything on the site and puts that into the cache. And then the next time I'm asking I can get it out  

#### [0:31:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1860) |  of the cache right away. That's a

lot faster than actually going to the network. And the biggest advantage is if I'm offline and my service worker is programmed in a way to check its cache before it even tries to go online, if I'm offline it doesn't matter that I'm offline because my service worker has all the things that it needs already in the cache. So we can actually function independent of the network. We can also say, OK, the website asks for this image. I get it from the thing, and I try to update it from the network.  

#### [0:31:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1890) |  Oh, I'm offline! OK, in that case,

I don't update it from the network. So you get a middleman that you control. And you control it by writing a little JavaScript, which is your service worker. So that's roughly it in layman's terms. I hope that made sense. So that's done. And service workers are really, really flexible because I get to program the service worker to whatever I need it to be. I once built a service worker where I ran into the situation  

#### [0:32:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1920) |  that the API was done using POST

requests only. POST requests can't be cached, which is bad. So what I did instead is I basically rewrote the front-end side of things to actually make GET requests. And the service worker that was in the middle would take the GET requests and turn them into the actual POST requests and then cache the results because we can cache for GET requests. Or actually, no. Hold on. We made the POST request, but I basically knew that if it's an API POST request,  

#### [0:32:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1950) |  I decided I wanted to cache it

anyways, even though for some API calls I couldn't cache it. So I got to program a service worker that very specifically cached things from an API that was, by default, uncachable, which is quite cool. If you don't have a service worker installed, or if the service worker fails for some reason, you would still make a request straight to the back end and get the data back. It would just take longer. So service workers are a really cool, progressive enhancement way of adding niceness to users where the service  

#### [0:33:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=1980) |  worker successfully installs. And that's kind of

nice. Right. Any further questions from you all in the call? Oh, yes. Actually, there's one in the chat. Is that a question that we've seen? All right. We've seen JavaScript play a major role in how websites are built and how JavaScript frameworks adopt it and take advantage of it. Most of the concerns now run around HTML and JavaScript  

#### [0:33:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2010) |  rendering. What do you foresee will be

the next challenges for the upcoming years regarding the use of JavaScript on websites? Honestly, making things faster. JavaScript still has this really not great property of inviting you to build a bunch of stuff that it will not perform fantastically well, for two reasons. One reason is that it can't be parsed progressively.  

#### [0:34:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2040) |  You just cannot. You can start rendering

HTML as it arrives. You don't have to wait until the entire HTML has arrived on your end. The same with CSS. You can progressively build the CSS tree from the data that you get from the network. You don't really have to deal with that, whereas with JavaScript, you have to wait until the entire blob is over. And we are still not having easy to deploy and easy to build ways of doing server-side rendering, so that will be a thing where you would  

#### [0:34:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2070) |  be able to build the web applications

with all the flexibility that JavaScript provides you with, but still have a fast experience with the users. So that'll be something that is not easy to achieve right now, that will hopefully get easier in the future. Then the entire how do I split my bundles. That still requires a bunch of manual work from developers that hopefully we can somehow make easier, and the default thing to work. So performance is going to continue  

#### [0:35:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2100) |  to be a big avenue of change,

or playground for change, I hope. PEDRO DIAS: So do you think there will be attempts to make JavaScript render progressively, or attempts to technically make it possible? MARTIN SPLITT: I don't think that there is a technical possibility for that. An imperative language, as JavaScript is one, is not really-- it's not possible.  

#### [0:35:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2130) |  It's one of the downsides of-- it

gives you a lot of flexibility, which is fantastic. But it also gives you the downside of not being able to start rendering as things happen because you need the entire context to actually be able to parse and execute JavaScript. So I'm not sure that we're going to see progressive rendering JavaScript. I'm not sure where WebAssembly goes. But as far as I'm aware, WebAssembly has the same problem that you can only execute instructions  

#### [0:36:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2160) |  once you have the bundle compiled. But

maybe we have a way of actually getting that working. That would be surprising and really cool. And we are in future territory, so I'm like, I don't know. Maybe none of what I've just said makes sense, or tomorrow someone finds a way to actually do the thing that I found to be impossible. But definitely also tooling is a big thing. A lot of websites, I would argue, that are built with JavaScript these days  

#### [0:36:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2190) |  don't really have to be built with

JavaScript. It's just the tool that-- PEDRO DIAS: Just a novelty, yeah? MARTIN SPLITT: Not even. No, no. I'm not saying that it's just a novelty and people like to play with it. It is just a way that allows you to build a lot of things very flexibly. And then you might be tempted to either use that for everything, like a novelty, or you might have reasons for it. I remember when I was building a very dynamic web application, where there was no way around it. We did VR in the browser.  

#### [0:37:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2220) |  There's no way in heaven that we

can do that reasonably without JavaScript. We would have to run JavaScript. So it was a dynamic web application, but it also had an e-commerce kind of system attached to it, so that also needed to be built and actually maintained somehow. We were a very small team, so the only reasonable way of doing this was to say, OK, we can't afford having to run with two completely different systems.  

#### [0:37:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2250) |  We can't afford to maintain a CMS

and this application. The only way forward for us reasonably is to somehow integrate this into our existing system, which is a JavaScript web application. And so we ended up having a Vue.js-powered blog. But, because I was aware of the situation, I was like, OK, as soon as possible, we need to figure out how to at least server-side render the static bits and figure out a way to keep the static bits static without having to drag in CMS or a completely  

#### [0:38:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2280) |  different set of tools that people have

to deal with to publish something on the blog. So that's where our server-side rendering then came in. And I remember that was 2016 or 2017. Server-side rendering of Vue.js applications wasn't the obvious thing. It wasn't easy. And that's the same for every other framework back in the days. And that's just how you end up with situations where like, eh,  

#### [0:38:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2310) |  we know it's not great, but that's

the only thing that we can reasonably do at this point. So I would hope that the tooling ecosystem explores more way of giving you a well-lit path to success where that kind of thing is considered from the get-go. Because most of the frameworks that came out around 2014 until maybe 2016 or something in that area of time were pretty much client-side rendering, and then everything else was an afterthought. So I would like to see us steering  

#### [0:39:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2340) |  into clearer waters where it's easier for

developers to just build things that are progressively rendering by default, no matter how. And that would fundamentally have to break down to server-side rendering at this point. Server-side rendering and hydration is a great thing, but it's not the default for most frameworks. What I'd like to see is that-- or what makes me hopeful for the future is that both higher-level frameworks like Next.js or Nuxt.js or Angular Universal  

#### [0:39:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2370) |  are getting a lot of traction recently,

as well as that more and more people are jumping on what they call the JAMstack or jumping onto static site generators like Gatsby or Eleventy, or these kind of things where you can build things with the technology that you have at hand, and you can use the same technology to build something much more dynamic. But you can also compile or pre-render it into HTML. PEDRO DIAS: I always like to think  

#### [0:40:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2400) |  we are dealing with this now. What's

going to come ahead? And I know the web technology that we use for websites has gone from like-- JavaScript always existed. It's as old as almost as HTML. And then we had stuff like ActionScript and Flash, and all of the things that came in and disappeared. So I've been just thinking what's potentially going to come afterwards? Is JavaScript here to stay?  

#### [0:40:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2430) |  Is it just something that we are

going to deal with it more natively going forward, more in the back end, more in the front end? I mean, this is just things that I try to anticipate, just to think the problem ahead of the time. MARTIN SPLITT: I think this is not a fad or whatever. I think this is a fundamental shift that has been going on for at least 15 years at this point.  

#### [0:41:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2460) |  When we started with Ajax, around 2005-ish,

it became clear that the web is a fantastic application platform. It used to be a document platform. That's how it was built and designed originally, to exchange documents and make them linkable to each other. Since, I would say, 2012, 2013, 2014, 2015 have not-- no. 2004, 2005-ish it became clear that we can build applications  

#### [0:41:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2490) |  on this. And if I look at

my daily work, I notice that a lot of this happens. Like Google Meet that we are using right now is in the browser. That's not a website. Google Meet is not a website. Maybe the landing page, yes. But what we are using right now is not a website. That's an application. Google Mail is not a website. That's an application, and I do things that I would do in an application. Google Spreadsheets, Google Docs, so many different things.  

#### [0:42:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2520) |  There's video editing tools. I don't know.

There's so much going on in Facebook, Twitter, all these things. Social media is actually an interesting thing because you could argue it's a website, but it's also more than a website. So I think the paradigm shift from a documentation platform to an application platform is powered and driven by JavaScript. This has been at least happening for the last 15 years,  

#### [0:42:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2550) |  maybe even longer. I don't think that's

going to go away anytime soon. And I don't think that we will fully replace JavaScript with something else anytime soon either. So I would say prepare yourself for JavaScript to stay around. It's just that we are learning where the limitations are, and we are learning where the real world hits the hopefulness of JavaScript developers in the way of like, oh, I can do this with JavaScript.  

![](https://i.ytimg.com/vi/r8EEW6wMamc/maxres3.jpg)



#### [0:43:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2580) |  I don't have to deal with servers

at this point. And then it's like, oh, yeah, but if I deal with a server, I get a lot of benefits from that. I do also hope that we continue to work to bring things into a more declarative state of things. For instance, I know that we are working on things like HTML modules. We are working on things like declarative shadow DOM. And hopefully, eventually, we might get declarative web components where we can then hopefully  

#### [0:43:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2610) |  build things with a little less reliance

on JavaScript and have more of the web platform take care of it, web platform meaning that the browser does the thing for you. But I don't know. This can go either way. Either we find out, OK, this really needs to be done in the web platform and needs to happen in the browsers, or no, this should not be done in the browsers. We definitely need to make sure that we are doing this in JavaScript-land because that's easier to deal with. But JavaScript itself is not a fad.  

#### [0:44:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2640) |  And using JavaScript to build web applications

is not a short-time fad. This will stay with us for a longer time, for sure. PEDRO DIAS: Yeah. Thanks for that. I didn't want to monopolize so much of the conversation. MARTIN SPLITT: No. No worries. No worries. LUKA ZUBOVIC: Can I ask just one question before you finish? MARTIN SPLITT: Sure. LUKA ZUBOVIC: Actually, I put my question in the comments, but you didn't take it. MARTIN SPLITT: Ah, let me see. LUKA ZUBOVIC: It was possible five minutes before the meeting should have started.  

#### [0:44:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2670) |  I'm not really sure whether it's JavaScript-related,

but I'm trying to get some kind of answer from anyone from Google for some time now, and I'm getting desperate. In the company where I work, one of the main web portals recently had front page dropped from Google Index. It's actually not dropped from Index, but it doesn't show in Search results.  

#### [0:45:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2700) |  And I'm not sure what could have

been the reason of this because when I check it in Webmaster Tools, it says that the page is indexed. And I don't know. When you try to see the search results for this page, it shows it's from 23 days ago. It doesn't have any appearances in Search results.  

#### [0:45:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2730) |  MARTIN SPLITT: The problem with that question

is-- and I see the question in front of me right now. And the reason why I didn't pick it, and why I would guess no one would pick this in an office hour is that I don't know. From the question itself, it can be anything. It can be a manual action. It can be that this is a display issue and we are actually seeing it in Search results, or it can be everything. Without a URL, I don't know.  

#### [0:46:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2760) |  I can't do much. LUKA ZUBOVIC: Maybe

I can send you a URL and you can check. MARTIN SPLITT: We only take information through public channels. But I think if you're using the Webmaster forum, there will be ways of getting the URL to us to double-check if it's a problem on our side, or if it's something-- because the problem here really is I can't help you. Because if I would, that would be unfair to everyone else that I can't help.  

#### [0:46:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2790) |  And if I would have to help

everyone who had similar problems, I would not get anything else done. That's the reason why we're not offering private support. What I can do if you give me your URL, is I can look if it's a problem on our end that affects other sites as well. And if it's a problem with our end that affects other sites as well because it's a bug, then we would fix it. But I cannot answer what you need to do to fix this problem, unfortunately. The best place for placing this question really is the Webmaster forum because the other users  

#### [0:47:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2820) |  might have an idea. And you can

send these other users private message, or basically like-- I'm not sure how exactly the new system works, but basically you can get messages to what we call product experts, who are very fantastic users who help and dedicate their time for other users struggling with things like this. And you can get the URL to them privately. You can also feel free to send me the URL separately. Or you can share it now and I can have a look maybe.  

#### [0:47:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2850) |  LUKA ZUBOVIC: OK. MARTIN SPLITT: That would

definitely work, and then maybe I can-- all right. OK. Maybe I can have a look at this and see. And it's only the landing page, the homepage. LUKA ZUBOVIC: No, it's only the homepage. The other pages aren't affected. MARTIN SPLITT: OK. That's an interesting one. HTTPS www. Just making sure that I copy and paste it correctly because there's like this weird-- Hangouts changes the links.  

#### [0:48:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2880) |  As far as I can tell, it

has impressions. Plenty. So if your Search Console somehow shows you that this page does not have any impressions from search results, then that would let me wonder if there is a bug in Search Console. LUKA ZUBOVIC: Yes, well, when I and anybody from the company, or even the country, types in [INAUDIBLE],, which is the keyword that  

#### [0:48:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2910) |  was most indexed for this page, you

don't see this page as first search result. It's actually in the section on the site which is [INAUDIBLE], which is news. MARTIN SPLITT: So if I go to-- LUKA ZUBOVIC: If you try to search-- [INTERPOSING VOICES] LUKA ZUBOVIC: --it won't be the first results in Google results.  

#### [0:49:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2940) |  MARTIN SPLITT: I mean, it's not the

landing page that is the highest-ranking result. But that's a ranking question now. This is no longer an indexing issue or some JavaScript issue. We have the content. It does show up. Your site shows up multiple times, just like subsites of it, not the front page, which might mean that we think the front page is not a good hit for this specific thing, this specific query. LUKA ZUBOVIC: Well, that started happening,  

#### [0:49:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=2970) |  like I said, 23 days ago. And

this was a page that was best ranked in Google Index. And in two days it went from, I don't know, 300,000 results per day fell to zero. So I think-- MARTIN SPLITT: That is possible. I mean, the first thing is you say zero. And that's not something that I can see. I see you have impressions. So people are clicking on it in search results.  

#### [0:50:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=3000) |  People are seeing it in search results.

It can't be zero. So it must be-- what tool are you using that says this does not have any impressions? LUKA ZUBOVIC: I'm using Google Webmasters tools. I can send you-- MARTIN SPLITT: Interesting. Because that sounds like there is a problem with the reporting on this page rather than the actual page, because you do have impressions on this.  

#### [0:50:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=3030) |  LUKA ZUBOVIC: I don't think I have

impressions for the home page exactly. MARTIN SPLITT: You do. LUKA ZUBOVIC: I do. MARTIN SPLITT: Yes. This might be a reporting issue, if any. LUKA ZUBOVIC: Is it possible to send-- MARTIN SPLITT: I don't think you can send screenshots. So again, let me reiterate the best place for this is the Webmaster forum. LUKA ZUBOVIC: OK.  

#### [0:51:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=3060) |  MARTIN SPLITT: And if it turns out

to be-- sorry? LUKA ZUBOVIC: I'm happy that you gave me some answers, and I'll try to-- MARTIN SPLITT: Sure. Not a problem. That's what I'm here for. And even though this isn't JavaScript-related, it seems to be fine from what I can see in our tools. It does have impressions. It does have clicks from Search.  

#### [0:51:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=3090) |  So there is nothing that prevents it

inherently. JAMIE ALBERICO: Could I ask a JavaScript-related question? MARTIN SPLITT: Sure! JAMIE ALBERICO: Hi. You look wonderful. It's good to see you. MARTIN SPLITT: Thank you. JAMIE ALBERICO: We have a site that is executing a third-party script via JavaScript. The bit of a problem is that they seem to-- you fire in this bit of JavaScript and it's inviting a lot of friends to the party. And it appears to be causing the layout thrashing. Question-- what would be the best way  

#### [0:52:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=3120) |  to execute these third-party scripts in a

way that they're not interrupting the time to interactive? Perhaps limit the amount of resources Googlebot then has to exert to this third-party script that calls a friend that calls a friend that calls a friend. It's got a crazy map. MARTIN SPLITT: So the best way to-- if the third-party script work with that, is to give them the defer attributes so that they are only loaded very well  

#### [0:52:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=3150) |  at the end of everything, so that

they can't interfere with the rest. Also move them as far down as possible on the site so that they get discovered as late as possible. And that should be doing it. The thing is that, with defer, it might be that if your application code somehow uses something from the third-party script, then that can get gnarly. JAMIE ALBERICO: It wouldn't be right to catch the metrics. I think that's the thing impeding it right now is that it needs that loopback for tracking. Would it be effective, then, to figure out  

#### [0:53:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=3180) |  if we could split that main bundle

into perhaps the analytics needed and the actual request for resources? MARTIN SPLITT: Yeah, that could be an option. JAMIE ALBERICO: Thank you. MARTIN SPLITT: You're welcome, Jamie. Thanks for popping by. All right. Time for one last question. SHAO CHIEH LO: I have another question. MARTIN SPLITT: Yes. SHAO CHIEH LO: It's a question about native lazy-loading. Is there any specific condition to met to make native lazy-loading work?  

#### [0:53:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=3210) |  I see a lot of example is

that there is a lot of web page that use native lazy-loading. And when I tested using a desktop, it doesn't work. But when I use mobile simulator, they work. I have an example here, like this one. When I use desktop, I see the network tab, and you see that they start loading before down construct, even before down construct. But if you use mobile simulator in the dev tool,  

#### [0:54:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=3240) |  you will see that it actually only

load when the view port is close approaching. Do you have any idea of is there anything that will happen to prevent late loading to happen on desktop site? MARTIN SPLITT: I'm guessing either this is a browser bug, or they do something like somehow specify that they want this to be preloaded. Or maybe there's a service worker involved that preloads it that doesn't do that on mobile.  

#### [0:54:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=3270) |  I'm not sure. I'm not familiar with

the website. But generally, it should work on desktop. Or should it? Let me actually see. I have a very simple test page. Actually, no, I don't. Not for native lazy-loading. I need to try that still. I would ask either the Google Chrome Dev's account, or maybe submit a bug in the Chromium Bug Tracker  

#### [0:55:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=3300) |  to just get a feeling for it.

But for that, I would highly recommend building a very minimal reproduction test case, where you're basically just loading a bunch of images that are large enough to be out of the viewport as well, with the latest native lazy-loading. And if that doesn't work on desktop, that sounds to me like that's a Chromium bug. SHAO CHIEH LO: I see. So if that is a Chromium bug, it's not just-- MARTIN SPLITT: Might be! Might be. SHAO CHIEH LO: So I mean if! If that is the case, then every native lazy-loading  

#### [0:55:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=3330) |  will behave like that, not just the

website that I saw. MARTIN SPLITT: Pretty much. Well, I mean, it depends. It depends on the bug. If there is something that needs to happen to trigger that bug, then, no. Not every website will have that happen. If you can't reproduce it, then it's less likely that it's a Chrome bug. Then it's more likely-- the harder it becomes to reproduce, the likelier it is to actually be a problem of that specific website and maybe others that are having similar problems.  

#### [0:56:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=3360) |  And that's a whole investigation. SHAO CHIEH

LO: I never did that in a lab environment. But I saw several web pages behave like that, so you can. MARTIN SPLITT: I mean, yeah. So I would try that with a reproduction case. And if you can reproduce it on pretty much every website, then it's definitely a browser bug. SHAO CHIEH LO: Thank you. MARTIN SPLITT: You're welcome. You're welcome. So I am looking for university3png.jpeg. This is a weird website-- png.jpeg.  

#### [0:56:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=3390) |  Hmm. Anyway. [LAUGHS] So, yeah. Right. In

which case, I would think that I have exhausted the YouTube questions, mostly. And I would think that we are over time a little bit, but that's fine. It's not that I have to be anywhere. It's locked down anyway.  

#### [0:57:00](https://www.youtube.com/watch?v=r8EEW6wMamc&t=3420) |  So in that case, thank you very

much, everyone, for joining. The next version in this time slot and time zone will happen in two weeks, on the Wednesday again. And next week on Wednesday, I'll do a little more APAC-friendly one in a different time zone, basically. So if you are getting up very, very early or staying up very, very late for these office hours, there will be a better-suited version for you next week  

#### [0:57:30](https://www.youtube.com/watch?v=r8EEW6wMamc&t=3450) |  as well. Thank you so much. Keep

submitting questions on the YouTube things for the upcoming office hours. And thanks for hanging out with me. And have a fantastic day. Stay safe, and stay healthy. Bye-bye. MARIA AMELIE: Bye-bye. SPEAKER 1: Bye.  