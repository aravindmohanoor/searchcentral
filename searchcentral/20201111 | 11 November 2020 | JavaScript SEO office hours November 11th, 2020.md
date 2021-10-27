[![JavaScript SEO office hours November 11th, 2020](https://i.ytimg.com/vi/bAE3L1E1Fmk/maxresdefault.jpg)](https://www.youtube.com/watch?v=bAE3L1E1Fmk)

## JavaScript SEO office hours November 11th, 2020

In the JavaScript SEO office hours, you can ask your questions about Google Search and JavaScript. You can either join the recordings live or post questions in the relevant thread on youtube.com/c/GoogleSearchCentral/community



#### [0:00:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=0) |  MARTIN SPLITT: He made it himself, that's

even better. All right. Hello, and welcome to the JavaScript SEO office hours. The first office hours from Google Search Central, our new rebranded identity. I'm super glad to be here. My name is Martin Splitt. I am from the Google Search Relations Team, and I am happy to answer all questions. We'll go through the YouTube submitted questions, and then I'll open the floor to audience questions. I'm really happy to see a bunch of people here today in the audience and look forward to the questions.  

#### [0:00:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=30) |  OK. So let's go through the questions.

Florian Mihai is asking they have an old website made with C# in web forms from ASP.NET, and they want to build a new one with .NET Core and render the HTML using JavaScript and AJAX and extract information to be populated on the web pages from APIs in the back end. It sounds a bit like a mixture of certain kinds of rendering  

#### [0:01:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=60) |  for me, but I don't know .NET

Core and the Views system, so I'm not sure how exactly that would work. The question is, will this affect our rankings and will Googlebot be able to read the content of the website, even if it's rendered after the page load event? That's a good question. Generally, it should not break. In Googlebot, we should be able to render it even if it uses JavaScript, but that is something that you can and should test before you launch.  

#### [0:01:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=90) |  You can test this with a mobile

friendly test. You can test this if you have a URL domain that is verified in Search Console. You want to look at the rendered HTML and make sure that the content in the rendered HTML is the content you would expect. Now, if the structure of your website and the content has changed, that will affect the rankings. If it is a one-to-one copy, it will net not necessarily affect the rankings because if it's really a one-to-one copy of everything, the URLs are not changing, then there is no need for us to gather signals again.  

#### [0:02:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=120) |  If URLs change or the structure changes

or the content changes or the way that your page works fundamentally changes in the way that we need to recollect the signals, then that would have a ranking impact. But that's not necessarily something that you should worry about unless there's a technical problem that we can't see some of your content, that's what you want to test for before we go live again. Test with mobile friendly test, look at the rendered HTML, and see if the content is there that you would expect.  

#### [0:02:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=150) |  Maria Stella is asking two questions. They

are using Gatsby and JavaScript and have a lot of locale adaptive content on the page. What we do is we check the cookies and the browser language and then the IP in that order to, one, redirect users to the appropriate localized versions, and, two, like, for instance, basically, they check,  

#### [0:03:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=180) |  oh, this is DE DE, so German

in Germany or this is French in France and so on and so forth, and then they redirect you to that content. They also populate the content on the page using JavaScript to show super localized content for a specific city. And they were wondering how Googlebot perceives this since they gave Googlebot's location through the IP address, which is probably not going to be different or not going to vary that much across the world.  

#### [0:03:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=210) |  Googlebot won't see all versions of the

page that users see because Googlebot doesn't crawl from every city in the world. Is this a problem? Is there an alternative solution you would recommend? Yes to both of these. It is a bit of a problem because if we don't see the content, then frankly, we wouldn't know it exists. What you should be doing is for the locale content, you should set up hreflang and, basically, say like this content is also available under EN US and UK, FR FR and DE DE and so on and so forth.  

#### [0:04:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=240) |  Basically, give us a list of the

versions in the different languages so that we understand and cluster them together as one piece of content. And then know that there is language variations of each of these. For the different cities and the hyper locale stuff, make sure that you have URLs and that your URLs are discoverable either by putting them in the sitemap or, even better, somehow creating a structure where we can use the structure and links in the menu, for instance, to understand where in the structure  

#### [0:04:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=270) |  the different pieces of content belong and

how the different cities relate to each other, for instance. So that's two things that you should look into. And make sure that we have URLs that we can use and that we find these URLs, as well. So discovery will be a challenge as well as giving us hints as to how the information structure looks like. Second question is regarding JavaScript and pre-rendered content. Is it OK to pre-render content for Googlebot but do some personalization for users using cookies?  

#### [0:05:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=300) |  Users might see different content than Google

based on the previously selected preferences? Is it cloaking? Again, that is not a super easy answer to that question. But fundamentally, if it's just personalization, and if I'm on a page for products that say, I don't know, it's a page for restaurants and I see slightly different restaurants or I see them in a different order, that is fine. If you'd show me my top uses restaurants or something instead of just a generic list of restaurants nearby,  

#### [0:05:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=330) |  that is absolutely fine. That's not cloaking.

Because if I click on the list of restaurants, for instance, in the search result pages and I get to a list of restaurants that are around me, including my top restaurants, that's not surprising, that's not disruptive, and that's not bad intentioned. I wouldn't call this cloaking. But it's a little blurry. You want to be careful not to give content that completely mismatches from what they might expect from such result pages. So that's something you want to be careful about.  

#### [0:06:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=360) |  But generally speaking, this would not be

considered cloaking. So Danielle says, I know you've talked about dynamic rendering and how that's OK. For many, though, bots are only ever shown an non-interactive site that is not rehydrated. How does or will that impact Core Web Vitals. Not at all. Core Web Vitals are coming from real user data, so they would come from people actually browsing your page.  

#### [0:06:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=390) |  And that way, we wouldn't hopefully not

get the dynamically rendered version for bots, and then that's not an issue. For that, data measurements, this might be a challenge, but we are not using that data in the Core Web Vitals for now, which might change in the future. Who knows. But you don't have to worry about this as of today. Then, we have a question from Patrick.  

#### [0:07:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=420) |  Not really a JavaScript question, but all

right. Several websites that are ranking in Africa, and I really want to get the event schema up and running. I've tried JSON with multiple entries. I tried combining the code and using IDs, and I also tried switching the data to microdata. Satisfied all requirements over the [INAUDIBLE] did not show up and be the case. I want to confirm whether the Event Schema Rich Snippet is available in Africa. Actually, I don't know. Unless we are saying it's not available in Africa in the documentation, there's no reason to assume that it's not available in Africa.  

![](https://i.ytimg.com/vi/bAE3L1E1Fmk/maxres1.jpg)



#### [0:07:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=450) |  But it's important to understand that implementing

the markup and satisfying all the requirements makes you eligible for potential rich results showing up. That doesn't mean that we guarantee you that you're showing up as a rich result snippet, so it might just be that the algorithm doesn't decide to go with a rich snippet for the query that you're ranking for.  

#### [0:08:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=480) |  And that means that the event schema,

even if implemented correctly, would not lead to rich results. So again, it's eligibility, it's not a guarantee that you get the snippets. Then Ankor asked the question here, not sure if this is something you can answer. We'll find out in a second. We have our website in Vue.js and we also a SSR version for Google. So effectively, dynamic rendering. How do we measure Core Web Vitals?  

#### [0:08:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=510) |  Does Google measure results from SSR version

as PageSpeed Insights Tool will measure it from the CSR version? Again, the answer is similar to the answer I gave previously with regard to the dynamic rendering question. The Core Web Vitals are being measured by real user metrics. So basically, coming from the Chrome UX report. That means that the results come from real users using your website. They get the client side rendered version,  

#### [0:09:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=540) |  which means that's where the data comes

from, that's where the measurements come from. So that's that. Lab data using a bot user agent, yes. But I had to clarify with the team that what I thought was rolled out is actually kind of an internal experiment. The lab data is only used as an experiment internally. It's not actually ready and might actually never happen, so I wouldn't worry about lab data too much. I would focus on the real user metrics for the moment  

#### [0:09:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=570) |  because that's what we'll roll out in

May rather than the lab data measurement. Lab data is mostly useful for testing, really. So you shouldn't worry too much about it. But yeah, if lab data comes in and we do measure that from a bot agent, then that would impact the metrics based on dynamic rendering. Which is probably exactly why it's an experimental stage and not an actual thing because we need to figure that one out. Because I don't think it makes sense  

#### [0:10:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=600) |  to give users expectations based on something

that comes from the rendered bot version of the page rather than what they would see. So we'll see about that. In general, again, dynamic rendering is considered a workaround. So if you want to make some mid-term long-term bets and investments, I would not go down the dynamic rendering route. I would figure out the way to basically do SSR plus hydration  

#### [0:10:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=630) |  because that pretty much gives you the

best of both worlds. Even there, would be still a discrepancy in the metrics. But again, that's not your problem. That's our problem. We wouldn't use lab data before we figure that one out. Excellent. With that, I think we have exhausted the pre-submitted questions. That means that we are opening up to the floor. Does anyone have questions for me here?  

#### [0:11:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=660) |  Quiet, peace and quiet. Any tips for

the best use of hydration and rehydration? Good question. Basically, whatever is implemented in your framework of choice. As long as the rendered HTML has the content, it doesn't really matter that much. Try to build it in a way that it doesn't basically  

#### [0:11:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=690) |  reload the entire content, but it really

just hydrates the interactivity layer on top of it. Because if you have a lot of things going on the main thread, that might mean that interactivity is hindered and the page starts to feel jaggy and weird. So try to offload as much work as possible from the main thread. Some dumb work has to happen on the main thread, unfortunately. But minimize the main thread time that your JavaScript spends as much as you can.  

#### [0:12:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=720) |  That's generally true for JavaScript, which is

an interesting position because we haven't fully tested web workers that much. I know of some limitations of our rendering implementation when it comes to web workers, so that's something that we'll have to work on this year and next year. Any other questions? More questions? The questions are great today. I love this.  

#### [0:12:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=750) |  Everyone fell quiet. Oh, everyone's submitting questions,

you can also ask questions aloud in the video, but it's fine to also use the chat. I respect that, too. Christian's asking, what happens SEO-wise when there are inconsistencies between rendered and non-rendered HTML of a page, specifically  

#### [0:13:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=780) |  with canonical tags, no index tags, title

tags. Does one of the HTML versions-- that's undefined behavior, actually. Which means you shouldn't be running into the situation in the first place. If you do, that's not great. Simply from the standpoint of what is it that you really want, and some people would say, we want what we sent you in the initial HTML and other people would say, oh, we actually meant what we have in the rendered HTML. So it is guesswork. Whenever there's guesswork involved, you can't rely on either of the two to be picked.  

#### [0:13:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=810) |  It might flop between the two or

flip-flop between the two or it might always prefer one or the other, but I can't say which one of it will prefer. Even if you would measure it today, this might change next week. Because again, this is undefined behavior, and this is not something that we would encourage. So I would recommend keeping your versions aligned or leaving out information when you know it to be inconsistent or incorrect. Generally, I would expect the rendered HTML to prevail  

#### [0:14:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=840) |  in most cases, but that's not necessarily

the case, especially with canonicalization, it is possible that we might also look at the pre-rendered version and this might influence the way that the rest of the pipeline works. It might be that you run into really strange behavior because this might rely on microservice timing the way that, basically, the indexing pipeline is not one program that just keeps running from A to Z, but it's basically a piece of program that branches out  

#### [0:14:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=870) |  in different services. And then they process

information in parallel. And depending on what results the indexing pipeline gets back from the individual services and when and in which order gets them back, you might see different behavior whenever there's undefined behavior. Right? So for instance, indexing generally would wait for rendering to happen. But when we get the initial HTML, we start a few processes at the same time. We, for instance, start to elimination,  

#### [0:15:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=900) |  which is fundamentally what kind of localization

is part of. So we would try to identify, is this page a duplicate of something else that we have in the index already? We can't make a final judgment call because the rendering might change the content. And then it might no longer be a duplicate. But we already get preliminary results. And if it then says I canonicalize this to this other page, then we might, depending on if rendering has finished at that point or still is in progress, we might see a different behavior on what's in the pipeline, then if that isn't the case.  

![](https://i.ytimg.com/vi/bAE3L1E1Fmk/maxres2.jpg)



#### [0:15:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=930) |  So that's tricky, and you should avoid

that situation in the first place. Then Ankor asks, in the SSR version, we have an Add to Cart button which basically does not do anything at this stage. Does Google take this in a negative way? No. We don't click on buttons, at least Google search doesn't click on buttons. For shopping, I don't know. You would have to ask the shopping folks. But from Google Search, we don't click on buttons  

#### [0:16:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=960) |  so it doesn't matter. Then what will

be the case if the website isn't JavaScript for Christian's question? I mean, I don't know exactly what that means? If it has nothing in there, and then the JavaScript generates the stuff, then that's fine. Then we don't have mixed signals. That's OK. If the JavaScript generates a different canonical, as I said, that's undefined behavior. And then you might get [INAUDIBLE] of the responses or results.  

#### [0:16:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=990) |  All right. AUDIENCE: Just to clarify the

clicking on Adding to Shopping Cart button, you did clarify, yeah, Google Search doesn't directly do that, but like you said say, Google Merchant Center Shopping might do that in limited cases just to make sure the price is what it is from the shopping page versus the cart page. And there was a whole big controversy about that when it was written about, I think,  

#### [0:17:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1020) |  in the Wall Street Journal. But it's

just for validation purposes, I believe. MARTIN SPLITT: Yeah. But again, if you want to learn more about that part, you would have to ask the Shopping and Merchant Center folks because that's a little outside of my area of expertise. It's quite interesting to see that this kind of thing happens. And then people get confused about, so is Googlebot doing this? Then the question becomes, what do you understand as what is Googlebot? Because Googlebot really is a piece of shared infrastructure that different teams at Google may use.  

#### [0:17:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1050) |  For instance, I'm not sure if you

ever saw a bot with a user agent Speakr, and I think now it's called Read-Aloud or something. That's also Googlebot, it's just a completely different team. So they are using the same crawling and fetching infrastructure, but they're not using any of the rest of the bits. And it's not really the Googlebot that you know for Search. AUDIENCE: Right. I mean, the biggest speculation came out when Google started AdWords or Ads, now Google Ads, and they have their own Googlebot Ads stuff.  

#### [0:18:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1080) |  So, yeah. They're separate, I think. MARTIN

SPLITT: It's wild. It's kind of interesting. I could write my own version of Googlebot that clicks on all the links if I wanted to. I would have to have the budget for that, and I would have to run through a bunch of approval processes. But if I ever say, oh, I want a Googlebot that actually clicks on all your links to see what happens, I could implement that. It still wouldn't be the regular Googlebot, but the infrastructure would allow me to do that.  

#### [0:18:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1110) |  AUDIENCE: Can you guys open source some

of that? MARTIN SPLITT: We do have the robots.txt parser that is open source, which is one of the microservices that we run. So Puppeteer is using the Chrome DevTools protocol which internally used to be called Lightrider, and that's kind of a way to programmatically control Chrome instances. And that's used in a very customized and interesting way  

#### [0:19:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1140) |  in the web rendering service. So fewer

bits and pieces are at least partially open source, and I am hoping that we would see more stuff moving towards open source because I think a bunch of our components are quite useful for other purposes, as well. Ah, there's a clarification on the previous question from Ankor. I mean if the website is built in JavaScript, then if the tags are different from this-- yeah, that's exactly what I answered for.  

#### [0:19:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1170) |  If the SSR version and the JavaScript

versions are disagreeing on things like canonical tag, it's undefined behavior. You might get either us treating the initial version as the real thing or the rendered version. You can't rely on that. You should avoid that situation. AUDIENCE: A little bit of an add, a check question. So machine learning is used throughout Google Search.  

#### [0:20:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1200) |  We know for ranking and purposes, I

know you end the Search Off the Record podcast with Gary spoke a little bit about dedupe duplication process and figure out the canonical and then put in the things from machine learning for assigning weights to what the canonical page is. In terms of rendering and crawling, is there a lot of machine learning used there as far as you're aware of? MARTIN SPLITT: For crawling? Yes. We do have a bit of machine learning in there, as well. As far as I remember, I'm not sure if this is actually live  

#### [0:20:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1230) |  or if this is experimental. I know

that we are using machine learning to identify or to predict the result of a crawl in terms of what will we get in terms of quality content. Can we predict or it's definitely interesting to try to find out if we can predict what kind of quality we will get from a given crawl before it happened. Because that would allow us to schedule  

#### [0:21:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1260) |  crawling more intelligently. The same goes for

if we can try to find out if we can predict freshness, as in like do we know that we have to schedule this website daily? Or can we gather signals that tell us not to do this daily and then use machine learning when predicting that for sites that we haven't had as much data for? But again, I'm not sure if we're using this in production or if this is experimental so far. AUDIENCE: All right. So to clarify, you may be using machine learning for crawling  

#### [0:21:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1290) |  purposes for, one, should I bother crawling

this page is enough quality for us to use our resources to actually try to even bother crawling the page? And two, for how fast we should crawl a specific site because of is it a new publisher and so forth. And generally, I guess, in the past, you may not use machine learning to find those things, but now you might be or you may decide to do so in the future. MARTIN SPLITT: We have been, in the past, gathering signals on this and making decisions holistically  

#### [0:22:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1320) |  on the signals. And we might now

use machine learning for that to predict this even better and more precisely. AUDIENCE: But nothing on the rendering side. MARTIN SPLITT: Not as far as I'm aware, we're not having any machine learning on the rendering side. No. AUDIENCE: OK. Thank you. MARTIN SPLITT: Welcome. All right. Any other questions? AUDIENCE: Hi, Martin. I have a question about the web rendering service.  

#### [0:22:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1350) |  So from what we know, the web

rendering service is very resilient. So if a rendering failed, it may will try later. So can you specify a bit more about when it's retried if there is like a percentage of fetch that have to fail to retry the render? Or are there any other things that fire these retry laters.  

![](https://i.ytimg.com/vi/bAE3L1E1Fmk/maxres3.jpg)



#### [0:23:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1380) |  So just to the box problem. MARTIN

SPLITT: Yeah. In general, this is something that you shouldn't need to worry about. That's something that we need to worry about. Very basically, like, this is out of your hands, this is our problem if rendering fails. We are pretty good at detecting rendering failures either on the network level when there's a crawling issue with actually fetching sources, for instance.  

#### [0:23:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1410) |  We might fall back to the cache.

If the cache gives us a version that looks OK, then we should be fine. We also try to, basically, render multiple times and see if the rendering result changes too much because, basically, the rendering tries to be as deterministic as possible. So we shouldn't see too big of a change except for maybe content. But like even that, should not change super much when we render multiple passes in one go. And if we see things like we have signals from a page that  

#### [0:24:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1440) |  has been high quality, and now comes

out with very few bits and pieces of content, then that would be considered low quality. And then we would assume that this probably is a failure on our rendering side, and then we would retry. We often use the cache to bypass most of the failures because most of the failures are actually network failures. Sometimes, we do have an non-responding Chrome that's taken care of by the internals of the web rendering service so that you basically then get immediately rescheduled  

#### [0:24:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1470) |  on a new fresh Chrome instance. But

all of that is something that, A, you don't see, B, you don't really have to deal with. That's our job to make sure that that's just working. As far as the indexing pipeline is concerned, it says render me this page and then it gets a rendering back. All the failure management is handled inside the WRS. AUDIENCE: OK. Thank you very much. MARTIN SPLITT: You're welcome. Good questions. That's really lovely today. Thank you so much, everyone.  

#### [0:25:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1500) |  Bring on more. AUDIENCE: OK. So if

I have another one. MARTIN SPLITT: Sure. AUDIENCE: About the CPU usage. So we can use like tools that we have, Chrome DevTools, so stuff like that, to have an idea of the max amount of CPU  

#### [0:25:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1530) |  we can use without the rendering. If

the render the rendering might stop us quit, that it is loading too much, that it's using too much CPU. There is a way we can say, OK, my JavaScript is using 80% of my CPU when I'm loading on my Chrome browser in my DevTools, stuff like that. Obviously, this depends on computer. So on my MacBook, it's probably different from the Chrome  

#### [0:26:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1560) |  instance machine because they're using different CPU,

different RAM. But there is something that we can do, like, OK, we can remove the JavaScript memory leak, and that's OK. We can have a profile limit so we can say, OK, this is the limit. I can't do much more of this so I have to debug stuff and optimize the JavaScript file.  

#### [0:26:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1590) |  MARTIN SPLITT: Again, a really good question,

and there is no easy hard and fast rule for this either. Again, it's holistically done. And generally speaking, you should not really worry about the CPU consumption. If your JavaScript ends up in an infinite loop, we will cut that off. If you are taking ages, and I mean ages. And I'm very specifically saying ages and not a specific number here, because there is no specific number thanks to the way that we are actually rendering, which is interesting and complicated and, unfortunately, internal  

#### [0:27:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1620) |  only. You don't really have to worry

about that. But like if your JavaScript takes ridiculous amounts of time on a reasonable machine, and that could be your MacBook, that could be your phone, you should assume that you definitely want to do something, not specifically for Google, but for your users. So it becomes a problem for your users and your real world performance before it becomes a problem for rendering. AUDIENCE: OK. So if the JavaScript file is working  

#### [0:27:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1650) |  on a smartphone or a computer, then

the render should be-- MARTIN SPLITT: It should be fine. AUDIENCE: OK. This is something interesting. Thank you. MARTIN SPLITT: You're welcome. Happy to help, happy to answer all questions. And again, I know that you probably want to hear, oh, yeah, if it's this many instructions or this much CPU usage on this machine, that's not how it actually works. AUDIENCE: Yeah, yeah, I know. I'm a bit interested in how the web rendering service is built,  

#### [0:28:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1680) |  but this is something-- MARTIN SPLITT: I'm

just waiting for ability to let out more details, but I have been asked for holding some bits and pieces back. I'm really excited about that, as well, because I think our engineering team did a great job there. AUDIENCE: And one more question about this CPU using web worker would work, because I have really tested it, but would also these be useful in the rendering machine? Because yeah, just to know.  

#### [0:28:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1710) |  MARTIN SPLITT: Generally, yes, I mean parallelizing

work that can be put in parallel is always great. That's great for your users. That's easier for rendering. Just be careful to test this very, very carefully because especially with web workers, there's so many edge cases that I tested with. I tested a few very simple things, and they failed in rendering. Partially because very few people do this and very few people do this in a way that it matters for the content. So I am a little cautious when recommending to put things  

#### [0:29:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1740) |  into web workers because, in theory, it's

great, in practice, it needs very careful testing. AUDIENCE: Yeah, I test a bit something that is connected to the timing on the page. And, yeah, it is not really working very well because, obviously, you have a different time inside the rendering machine, and it's probably it's fake, though, stuff like that. So yeah, It's not working really well there.  

#### [0:29:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1770) |  MARTIN SPLITT: Exactly. There's lots of bits

and pieces. It's also a measure of the way that we detect how the website rendering is progressing Is not working super well when there's thread threads involved. So it's fascinating, and there is still a lot of work for us to do in the web rendering service. It's not all done and dusted and perfect yet. AUDIENCE: Yeah, thank you very much, thank you very much. MARTIN SPLITT: You're welcome. Thank you very much, Giacomo.  

#### [0:30:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1800) |  More questions? All right. If there's no

further questions, I'll give you five, four, three, two, one. Last call for questions. No? All right. In that case, thank you all so much for joining the live recording. Thanks everyone who submitted questions  

#### [0:30:30](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1830) |  in the YouTube thread. I'll just post

the thread for the next one in two weeks, which means that's the, oh, my, I can't remember when the next one is. I think that would be on the 25th of November. That will be the one on 10 AM CET. So I'm trying to surf all time zones as much as I can. Thank you very much. I'll post the recording later. If you're watching the recording, thanks for watching the recording.  

#### [0:31:00](https://www.youtube.com/watch?v=bAE3L1E1Fmk&t=1860) |  And have a great time, stay safe,

stay healthy, and bye bye. AUDIENCE: See ya.  