[![JavaScript SEO office hours October 14th, 2020](https://i.ytimg.com/vi/24TZiDVBwSY/maxresdefault.jpg)](https://www.youtube.com/watch?v=24TZiDVBwSY)

## JavaScript SEO office hours October 14th, 2020

In the JavaScript SEO office hours, you can ask your questions about Google Search and JavaScript. You can either join the recordings live or post questions in the relevant thread on youtube.com/googlewebmasters/community



#### [0:00:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=0) |  MARTIN SPLITT: All right. Hello, and welcome,

everybody, to the JavaScript SEO office hours. After a bit of a break, I'm back. And I hope to do these now on a bi-weekly basis, or fortnightly basis, as the British would probably say. So every 14 days, there will be an opportunity. And I'll try to switch the different time zones so that we have both APAC-friendly hours as well as EMEA-, Americas-friendly hours too. Sweet. So let's go through the questions that  

#### [0:00:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=30) |  were submitted on YouTube. Black Cat Go

asks, "How does Google's web rendering service handle CORS--" so Cross-Origin Resource Sharing. "Does it inherit the policies of the Chromium version in use?" Yes, it is also bound by the CORS principles, and APIs, and headers. So that means that if you have CORS requests, or cross-origin requests-- so requests to another subdomain or another origin-- you want to make sure that these are allowed as per the specification as well. Then we have Monsef asking two questions, actually.  

#### [0:01:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=60) |  The first one-- "Is it safe from

an SEO perspective that [? next ?] view store the duplicated data in a script tag?" Yeah, that's fine. That's not an issue. And the same question about view server side rendering hydration and SEO-- "Is it better to do lazy hydration--" which means hydrate the content, or refill the content that you send from the service-- "just before the user reach the components to decrease time to interactive?"  

#### [0:01:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=90) |  It's also a user experience question. And

I think it would be good to lazy hydrate. But if that causes problems or if you notice in the testing tools that your content doesn't show up in the rendered HTML, then that means that lazy hydration does not work with Googlebot very well. I haven't really tested that. Try it out. And if it does not work, then I would not hydrate lazily. But hypothetically, the content should be there-- from the server side rendered version, anyway. So you should be fine. But definitely test everything.  

#### [0:02:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=120) |  And also things can change over time.

So testing is always the best possible strategy here. Also, if there is a popular-- sorry, Kyo asks, "if there is a popular resource, like a popular JavaScript library from a WordPress plugin or something. from Node.js, can Google cache it in a single place to render pages from different domains?" So in the WordPress plugin example, let's say you have a local thing from my JavaScript resource, and that's broken. Can Google still render the web page because it's a popular resource and therefore cached  

#### [0:02:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=150) |  from other pages? No, we cannot do

that for the simple reason that that would allow cache poisoning. And that's a very, very risky vulnerability. So what you can do is you can include them from CDNs if you trust these CDNs, or public places where these might be hosted. Then you can use those versions instead of your version. And we might be able to use them from the cache. On the other hand, you don't really have to worry about it. Because popular or not, our cache is very aggressive.  

#### [0:03:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=180) |  So we are generally over-caching than under-caching.

So if something is broken momentarily, that normally isn't a problem. Because we are not fetching it in every render anyways in the first place. But there is no such thing as, oh yeah, jQuery is broken on your side, so we'll just fetch it from somewhere else. The only situation where I could see that as potentially feasible is if you have a subsurf-- sub-resource ref-- what's it called--  

#### [0:03:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=210) |  a sub-resource integrity token in your code.

And even then, it is tricky, because there are so many different versions. So we are not implementing that really. But again, don't worry about it. Normally, we are over-caching rather than under-caching. So even if you have a momentarily broken link to a resource from your site, then that's not necessarily a problem. Also, we retry renders if that is necessary. So don't worry too much about-- CAIO BARROS: Well, Martin--  

#### [0:04:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=240) |  MARTIN SPLITT: --that. CAIO BARROS: --so the

follow-up question is-- from what I understand, the caching is more or less domain-based. MARTIN SPLITT: Mm-hmm, origin-based, yeah. CAIO BARROS: Yeah, will cache everything my domain needs even if I request the resource from a CDN or from other-- MARTIN SPLITT: Well, no, because then we would potentially be able to cache that on that domain as well. CAIO BARROS: OK, yeah, makes sense. MARTIN SPLITT: So that makes-- yeah, that makes that possible.  

#### [0:04:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=270) |  CAIO BARROS: And I believe the follow-up

question that will come with that is, how does that affect crowd budget and everything? So let's say I fetch the resource from a different source, from a different crowd CDN. Does that impact my crowd budgets or their crowd budget? MARTIN SPLITT: I'm not 100% sure, to be honest, because I haven't really thought about this. But I think it does not affect your crowd budget. Or at least, it doesn't do so directly. But then again, it might do indirectly.  

#### [0:05:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=300) |  I wouldn't worry about it too much.

Because I assume that you're not having thousands of resources that you need to download. I hope you don't. CAIO BARROS: I hope so, too. Thanks. MARTIN SPLITT: You're welcome. JAMIE ALBERICO: Hey, Martin, follow-up question about that resource availability, right? MARTIN SPLITT: Yes. JAMIE ALBERICO: So I see in a lot of URL inspector tests a high level of the resources not being available. That leads me to ask, does Google  

#### [0:05:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=330) |  do a fresh fetch for each resource

when you do a URL inspection test? Or is that really representative of the availability rate? MARTIN SPLITT: You're probably mostly riffing off of the other error that you might see in the testing tools, right? Is that what you're getting? Or is that-- does that look differently in the testing tools? JAMIE ALBERICO: What I'm referring to is when you go into the more Info and you look at resource availability. You know, if a page calls 150, I've  

#### [0:06:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=360) |  got some rather complex folks I've worked

with who have 104 of those missing, unavailable. And some of them I've seen from being dependencies. So their jQuery resource didn't respond. That was unavailable. And then the five scripts executed off of that also were listed as unavailable, because domino effect. So I'm curious if those tests are actually representative of what Googlebot is seeing or just an isolated, individual, we tried to fetch everything fresh. MARTIN SPLITT: Right. So OK, the general answer to that  

![](https://i.ytimg.com/vi/24TZiDVBwSY/maxres1.jpg)



#### [0:06:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=390) |  is, unlike the actual indexing runs, the

test, for the obvious reasons, actually does run a fresh fetch. Because we want to give you the opportunity to test the latest version of everything that you've got, which means that we are definitely bypassing the cache. So the testing tools do bypass cache, which is not something that happens in the actual crawls and the actual indexing runs. I know that that sometimes causes a few confusion  

#### [0:07:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=420) |  or confusing moments. But when you say

resource available, to you mean, basically, you go in the URL inspection tool? For instance, you go to page resources, and then you see some resources can't be loaded, right? JAMIE ALBERICO: Yes, so there is the screenshot, the rendered HTML, the More Info tab. It says x out of x resources unavailable. And you look through those. So that's [INAUDIBLE] I'm hearing about. If Google has a proper copy of that resource at any given  

#### [0:07:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=450) |  point, it sounds like that will behave

differently than the test [INAUDIBLE]. MARTIN SPLITT: You can-- exactly. You can double-check this. If you look at the crawled page instead of the live test that you do, you would see how that looks like in terms of the page resource. And not everything that is in there is necessarily a problem. Sometimes other error just means that we didn't deem this resource to be very important. That happens specifically with images that are usually skipped in fetching. Because we don't really have to fetch the images  

#### [0:08:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=480) |  for some of the stuff and-- or

most of the stuff, actually. JAMIE ALBERICO: The idea being image is static? So once you have it, you're not going to worry about grabbing it again? MARTIN SPLITT: Yeah, kind of. JAMIE ALBERICO: [INAUDIBLE]? MARTIN SPLITT: We are updating the images. It's just that for the indexing run, that doesn't necessarily report well. Because the image index is a separate entity anyway. JAMIE ALBERICO: OK. MARTIN SPLITT: So generally speaking, you shouldn't need to worry too much about a resource not showing up in the live tests because we are skipping it  

#### [0:08:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=510) |  in the cache. But you still want

to make sure that you have a look at the crawl page to make sure that all the content that you expect shows up there. If that doesn't show up and you see a related resource issue-- let's say, some content is drawn from an API endpoint that is fetched by your app.js file. And then that app.js file shows up as fails to load in the crawled page report-- so again, you basically click-- you crawl page. And then you get the more Info page resources.  

#### [0:09:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=540) |  If something shows up there as an

error and you see the matching missing content in the rendered HTML, you see the content that should be loaded by this resource missing, then that's a strong hint for something going wrong in terms of us not being able to cache it. Or maybe we cached it in the past, and we couldn't refresh the cache. Or the cache has expired. But generally speaking, yes, the live test tools, all of them-- so that's the AMP test, the rich results test,  

#### [0:09:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=570) |  the mobile-friendly test, and the live test

in Google Search Console-- they skip the cache. That's correct. JAMIE ALBERICO: Thank you. MARTIN SPLITT: You're welcome. All right, I see that we are through with the YouTube questions. And that means that I'm opening up the questions to the live audience. CAIO BARROS: All right, Martin, I have another question, then. MARTIN SPLITT: Sure. CAIO BARROS: This is based on something I've been seeing on the forums. So let's say I have a lighter version  

#### [0:10:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=600) |  of my website for mobile. And I

don't want to show all the resources on the mobile page. I don't know, maybe I don't want to show a carousel, because it takes too much space. One way to do that is to use CSS display none. But that will just-- the resource will be fetched anyway, right? MARTIN SPLITT: Mm-hmm, I think so. CAIO BARROS: What do you-- yeah, I think so as well, but I'm not sure. So do you have any suggestions on--  

#### [0:10:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=630) |  what do you suggest? Server side rendering?

What would be the best thing to do to-- MARTIN SPLITT: There is a bunch of different ways of going about having a mobile-friendly version of your site and not loading resources. One way is that, if it's a component that is dynamically inserted, like-- it sounds like that, if you say additional resources are being fetched. CAIO BARROS: Yeah. Yeah, sure. MARTIN SPLITT: Then what you could do  

#### [0:11:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=660) |  is you could do conditional fetching based

on the media selector. So you can say, oh, this is a small screen. And I think, on small screens, this carousel does not make sense. That's one way of doing it. That is possible. You can also just server side render. I mean, you would also always have to find a way to adapt to things. But if you server side render, then you should not necessarily have to fetch much in terms of resources. Because these resources will be inlined into the page.  

#### [0:11:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=690) |  At least the HTML will be there.

It will still load the images, of course. What you can do is, especially if it's an image carousel specifically, you can lazy load the images. And then display none would mean that the images aren't being loaded, because they are never in the viewport. That is an option for this as well. So you have different options to make your design responsive to the different screen sizes. And you have to try them out to see what works best for your approach.  

#### [0:12:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=720) |  Because they have-- from a search perspective,

it doesn't really matter which one you go with. But I think from a user experience point of view as well as from an implementation point of view, that will very likely be the bigger bits to understand what works best or what doesn't work so great. Because some might be easier. For instance, the CSS display none, that's really easy to implement, I guess. Whereas a dynamic switch, depending on the media query,  

#### [0:12:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=750) |  might not be as easy to implement

depending on the solutions being used. But it might be more effective, as it would take out the content entirely if the screen size doesn't warrant for displaying it, yeah. CAIO BARROS: And of course, you are suggesting that this should be dynamic based on the screen size, not on user agent or any other way? MARTIN SPLITT: Don't base it on user agent. CAIO BARROS: Yeah.  

![](https://i.ytimg.com/vi/24TZiDVBwSY/maxres2.jpg)



#### [0:13:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=780) |  Yeah. I don't think I saw anyone--

much later, people using this with user agent. But then I was-- I was thinking how, for the core web vitals scores, when they are testing for-- at least, say, in Lighthouse, if they are testing for mobile and for desktop, the only thing that is changing there is the screen size when they are [INAUDIBLE].. MARTIN SPLITT: Screen size, yeah. CAIO BARROS: Yeah, OK, makes sense. Thanks. MARTIN SPLITT: You're welcome. Good to have so many questions in the first one  

#### [0:13:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=810) |  after the longer break. More questions? Anyone

else have any question? DAVE SMART: Hi, is there any difference between the mobile-friendly testing tool, and the rich results test, and the URL inspection test-- big question. I know there is. But in terms of the [INAUDIBLE] that they use-- specifically, we had someone come in the forum where it was a very weird case of the site that would render the HTML in the mobile-friendly testing tool,  

#### [0:14:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=840) |  but would not in the rich results

test. And from what they were reporting to us, it wouldn't in the URL inspection either. And apparently that seemed to reflect more what they were actually getting. But was there anything around that? The only thing that I could think why the mobile-friendly test was possibly working is if there was something about viewport thing. Because that attempts to paint. But I couldn't really see anything. But there's nothing kind of too different about those other  

#### [0:14:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=870) |  than that, I suppose. MARTIN SPLITT: No.

So internally-- that's a very good question. Actually, I think I saw the thread. It's like a React page that has the-- I suspected that it's React, and I don't think it's React. DAVE SMART: Yeah, no, I think it was a different one. Yeah, I did see some guy the other day in React thread. But I think that was basically it was just incredibly slow. And he was just timing out. And that was that. [INAUDIBLE] it was legitimately-- MARTIN SPLITT: Right-- DAVE SMART: I think that he might have treated-- MARTIN SPLITT: --so these things do pop up multiple times,  

#### [0:15:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=900) |  I see. Interesting. So internally, all of

these are called the "Single URL Inspection Tools," or SUITE, or SUIT, depending on, yeah, I think "suit" is how you properly pronounce that then. SUIT is the internal acronym. It all goes through the same pipeline. Obviously, then there are a few changes. For instance, the rich results tests allows you to specify if you want mobile or not, whereas the mobile-friendly test always opts for the mobile route.  

#### [0:15:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=930) |  The URL inspection tool goes for if

the page is mobile-first indexed. Then it goes for the mobile route. If it is not, then it goes for the desktop route. But you can switch that. So there might be small issues, or small differences, especially if it's a non-MFI-- so not Mobile-First Indexed page. It might go through the desktop route. And then you can get different results in the rich results test and in the mobile-friendly test. Because those go the mobile route instead.  

#### [0:16:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=960) |  So there's a few small different code

paths that could be triggered hypothetically. But it is the same infrastructure. And so far, as you say, most of the times, I've seen this either with intermittent errors on which resources are fetched, because we are bypassing the cache. Then different resources might time out or might fail to complete their requests in time. And then you might get different results in one-- even in the same too-- I think, the thread that I looked at, at least, they used the same tools multiple times.  

#### [0:16:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=990) |  And they got like, yeah, the URL

inspection tool doesn't work, but the mobile-friendly test does. And the rich results test also doesn't work. And then the next time they posted, it was like, the URL inspection tool doesn't work, but the mobile-first indexing tool doesn't, and the rich results test does. And it's basically like it was different combinations of the three, where it worked and where it didn't. And I'm like, well, if you're running it through the same three tools different, multiple times, and you get different results, then that tells you that there's something intermittently wrong and not necessarily a fundamental issue.  

#### [0:17:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=1020) |  Really hard to [INTERPOSING VOICES] DAVE SMART:

So I found out about this one little case. It must be a very edge case that it was consistent to. It was consistent with no page results loading errors at all. [INAUDIBLE] consistently failed and rich results [INAUDIBLE].. MARTIN SPLITT: Is that the one that you escalated recently? DAVE SMART: Yes, I think I might have escalated it to you. MARTIN SPLITT: Sweet, because that is an issue on my desk to find out. I just didn't have the time yet.  

#### [0:17:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=1050) |  But it looked like it might happen

either tomorrow or on Friday that I can look into it. So that's fun. That's timely. DAVE SMART: Excellent. MARTIN SPLITT: So yeah, just for the general population and public out there, if you are seeing a fundamental issue that can't be solved in the webmaster forum, then sometimes these issues get escalated through Googlers who work on the forum. And then these are being investigated. I can't give you-- please don't send me direct messages or something.  

#### [0:18:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=1080) |  Because I can't investigate every page out

there. But if it looks like this might be something where the public channels failed to support your case and give you support, then we might look into it as a potential general larger issue. And if that is true, then we will fix that larger issue. But if it's just your site, then we'll find a way to give you more public feedback so that the next person running into the exact same situation sees that forum thread and can use that as a reference point.  

#### [0:18:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=1110) |  So that's what I'll be doing later

this week as well. It's an interesting case. It's a curious case. When I saw-- when I saw that, I was like, hmm, interesting, it goes through the same pipeline. How is this different? We'll find out. Thanks for the question. That's a really good question. More questions? OK, so I'll give it a 5, 4--  

#### [0:19:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=1140) |  for your questions-- 3-- [INTERPOSING VOICES] All

right, there we go. Oh, multiple people jump on, all right. JAMIE ALBERICO: So in thinking about how to approach understanding rendering and resource availability better, aside from knowing the manual breakdown of that rendered HTML, associating it with the script that creates it, is there another way to figure out if a resource has been persistently  

#### [0:19:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=1170) |  unavailable to Google on the script which

generates content is problematic? MARTIN SPLITT: That's not really easy to do that, especially over time, as the crowd page is basically just a snapshot. I mean, in the end, if you see your page, for instance, dropping out of the index every now and then and dropping back in, that's something that you probably want to investigate in general if that  

![](https://i.ytimg.com/vi/24TZiDVBwSY/maxres3.jpg)



#### [0:20:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=1200) |  is an issue with intermittent resources. Just

generally, these issues are really, really rare. Because as I said, we have a cache. We have a very aggressive cache. So even if your server gives us the script once and then doesn't give it out for the next month, you should not see intermittent resource issues. This is more a problem with the live tests than a real issue. JAMIE ALBERICO: Is there an index coverage type that we should look for moving from indexed  

#### [0:20:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=1230) |  and submitted or whatever, to-- MARTIN SPLITT:

Not really. Not really. As long as it is indexed and you want it indexed, then I think that's fine. I don't think you can monitor for anything specific there, except for it landing in the error category or in the excluded category. If a page that you really care for lands in the excluded category every now and then, then that's probably something where you want to look into. It doesn't mean that it's a rendering problem though.  

#### [0:21:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=1260) |  JAMIE ALBERICO: Would crawl anomaly be the

closest rejection-- or excluded type to indicate that? MARTIN SPLITT: Not really either, because crawl anomaly normally is not a rendering issue, but an issue in crawling already. It also can be pretty much anything. That's a really broad category. I wouldn't say there is a clear category or that there are candidates where you would need to worry about rendering more than others.  

#### [0:21:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=1290) |  Couldn't think of any. Because rendering is

more or less a transparent part of indexing. So it's not that we report a very specific error back, because we are retrying errors. So again, normally you should never run into this problem in real life, where a resource is temporarily not available to us, unless, of course, you 404 a resource.  

#### [0:22:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=1320) |  And then the page drops out, because

it's now basically empty, or barren of content. But I wouldn't know how you would spot this in Search Console patterns. JAMIE ALBERICO: Thank you. MARTIN SPLITT: You're welcome. I'm sorry that I don't have a better answer for this.  

#### [0:22:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=1350) |  Probably crawled, currently not indexed might point

at that problem if it is something with the-- sometimes it might affect the canonical. If the canonical on the HTML looks different than from what is in the rendered version, then that might come out as, like, alternate page with proper canonical tag, or duplicate without user selected canonical. But I wouldn't say that these are inherently signals that that's a rendering problem.  

#### [0:23:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=1380) |  They might be, but they don't have

to be. That's as good as I can do at this point. Damn. CAIO BARROS: Martin, the live tests and the URL inspection tool use the same pipeline as the testing tools, the rich results tests? MARTIN SPLITT: Yep. CAIO BARROS: Yeah, and it doesn't take up caching when you do the live tests, right? MARTIN SPLITT: Correct, yeah.  

#### [0:23:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=1410) |  CAIO BARROS: Yeah, OK. But I have

another question related to lazy loading, native lazy loading as an attribute of image. I was looking here in can I use. And I noticed that it doesn't run on Safari yet. It's an experimental feature on Safari. So maybe if I implement that on our web page, it could cause some slowness in real-time measurements, right? MARTIN SPLITT: Mm-hmm. CAIO BARROS: I know that Googlebot uses Evergreen Chrome.  

#### [0:24:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=1440) |  But if I'm looking at the field

measurements in Search Console for speed and things like that, maybe the-- using native lazy loading, we will slow down. We would expect to slow down for iOS users or Mac OS users, something like that. MARTIN SPLITT: I mean, it wouldn't-- [INTERPOSiNG VOICES] Yeah, exactly, if you have a fallback, then that's the best you can do.  

#### [0:24:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=1470) |  If you don't have a fallback, then

it wouldn't slow it down. But it would be slower than in Chrome, where native lazy loading is implemented. Yeah, that's true. CAIO BARROS: Yeah. So it should appear on the field testing results on Search Console? What do you think? MARTIN SPLITT: I think we are mostly sourcing them from the Chrome usability report. So I don't think they show up unless iOS Safari does play into this.  

#### [0:25:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=1500) |  Because when you're running a Chrome on

iOS, you are effectively running Safari. But I'm not sure if that is the case. I'm not sure if we can somehow-- I don't know. It might be. CAIO BARROS: Mm-hmm. All right. In any case, test on the real thing, right? MARTIN SPLITT: Definitely test. CAIO BARROS: OK. MARTIN SPLITT: All right, more questions?  

#### [0:25:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=1530) |  All right, 5, 4, 3, 2, 1--

awesome. That was fantastic. Thank you so much, everyone, for submitting your questions on YouTube as well as everyone who joined tonight, or this morning, or this evening, or this afternoon, depending on where you all are based. It has been huge fun. And again, as I said at the beginning, we will do these every two weeks.  

#### [0:26:00](https://www.youtube.com/watch?v=24TZiDVBwSY&t=1560) |  So definitely keep your eyes peeled for

the post for the next episode's question time where you can post your questions and the link to the Hangouts if you want to join next-- the next edition. I was saying, like, next week's Hangout, but it's not in a week. It's the next-- the week after next week's Hangout. Wow, OK-- it's quite late here. I'm sorry. In that case, thank you very much, everyone who was watching.  

#### [0:26:30](https://www.youtube.com/watch?v=24TZiDVBwSY&t=1590) |  Have a great time. Stay safe. Stay

healthy. And bye-bye. CAIO BARROS: Bye-bye. DAVE SMART: Bye, Martin. MARIA AMELIE: Bye-bye, Martin. Thank you. MARTIN SPLITT: Thank you very much for joining.  