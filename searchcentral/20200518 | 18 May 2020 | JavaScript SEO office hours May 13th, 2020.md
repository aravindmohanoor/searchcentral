[![JavaScript SEO office hours May 13th, 2020](https://i.ytimg.com/vi/hHNB7PeMpss/maxresdefault.jpg)](https://www.youtube.com/watch?v=hHNB7PeMpss)

## JavaScript SEO office hours May 13th, 2020

This is a recording of the JavaScript SEO office-hours hangout from May 13, 2020. These sessions are open to anything around SEO for JavaScript sites.



Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=0) |  MARTIN SPLITT: Hello, and welcome to another

JavaScript SEO office hours. It's me, Martin Splitt, from the Google search relations team. I'm here to answer your questions on JavaScript SEO. A few questions were already submitted, so I will go to the submitted ones, and then we'll take questions from the audience. If you want to join these live hangouts, you can go to google.com/webmaster/connect. We have a calendar where they are scheduled.  

#### [0:00:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=30) |  Or you go to youtube.com/goog lewebmaster/community. I'll

post the link to these recordings a few minutes before the recordings start so you can join them live. Or you can just use the YouTube post to post your questions and then see the answer later, as the recording goes up. Cool. Let's have a look. The thing is, if you ask questions that are not related to JavaScript, I would ask those in the regular SEO  

#### [0:01:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=60) |  office hours or the webmaster office hours,

because this is specifically aimed towards JavaScript questions and problems. Is it fine that we serve the content pages without any JavaScript for bots? Is that considered cloaking? No. If it is the same content or roughly the same content, it doesn't matter if there is JavaScript or not. And if it's slightly different, that is what we would call dynamic rendering. We have a guide on dynamic rendering as well,  

#### [0:01:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=90) |  and that's perfectly fine. That's not a

problem. Does it have to decrease the time to download and increase the number of pages Googlebot can crawl within the same budget? Maybe, maybe not. That depends on many different factors. Dynamic rendering-- usually, when you render the page without JavaScript, as the request comes in, it usually takes longer, because you have this extra rendering step in the middle of it.  

#### [0:02:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=120) |  That sometimes makes the site a little

slower, but that's normally neglectable and not a big problem. Again, it depends on your setup. You should measure that time. It might save you a few requests in crawl budget if your JavaScript is client-side rendered and does a bunch of API requests to actually fetch resources and then create the content from that. You would save these requests, and that means that when you get a little more requests in your crawl budget. But then again, crawl budget is only relevant  

#### [0:02:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=150) |  if you have a really large site

with, I would say, like a million and up pages. There's other factors that go into crawl budgets, so you might not see an increase in pages being indexed. But you might. It's not impossible. Hi, Martin. Is the client-side JavaScript redirect treated like a 301 and immediately considered permanent, like a 302, temporarily, or something else? It's considered like a redirect.  

#### [0:03:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=180) |  We don't really make that much of

a difference in terms of 301 and 302. It does have a different outcome for the users. 301s-- browsers cache that and immediately jump to the target destination, whereas with 302, it basically jumps to that original URL first and then jumps to the target. Client-side redirects for browsers are pretty much like 302s. If you can avoid them, I would.  

#### [0:03:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=210) |  If you cannot, then that's OK, too.

It doesn't really hurt anything much, so you don't have to worry about that big-time. Someone wants to join the session but doesn't have the link, so I'll just quickly post the link here as well. We rebuilt our website in React and implemented a mobile navigation from one of the component frameworks which is not in the DOM until the user clicks on the hamburger icon. Could that have a negative effect on how Googlebot sees our page?  

#### [0:04:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=240) |  None of the links are visible in

the HTML. You kind of answer your question yourself. If it's not in the HTML, we're not going to see it. That's what's going to happen. If this is your navigation, and your navigation is the only thing that tells us about your page structure, that's not great. I would argue that it's always better to have the links in the HTML, in the DOM. Maybe hide it. Maybe move it out of the screen. Whatever. But don't just remove it entirely. You can totally have something that is invisible in the DOM  

#### [0:04:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=270) |  and only comes in on user interaction.

We wouldn't do the user interaction, but as long as it's in the DOM, we would see the links, whereas if you really just need a user interaction for the links to be injected into the DOM, then that's what we are not seeing. So that's not great. Is there a difference in how Google handles history push state versus history replace state? Good question. I don't know. I think there isn't, but I don't know for sure,  

#### [0:05:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=300) |  and I would have to test. You

can probably test that as well. I'm not 100% sure. I would assume that there isn't a big difference, but I am really, really not sure, and I'm not sure if we would count replace state as a redirect. I would have to check.  

#### [0:05:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=330) |  That's a really good question. I like

hard questions. I'll come back with an answer maybe on Twitter. I'll see. SPEAKER 1: Thanks, Martin. MARTIN SPLITT: Sorry for that. Since the bot should not really care about custom web fonts, is it OK to serve the bot a page that loads fast and does not rely on the custom fonts? Could that have a positive effect? I wouldn't do it. Yes, it could have a potentially positive effect,  

#### [0:06:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=360) |  but it also means that you have

a more complicated setup, because you then have to inherently figure out, "Is this a bot or not?" and then have additional code that deals with this. Additional code usually also means additional bugs. No matter what you do, there will be weird side effects that you might not have foreseen. I just wouldn't do something for such a minuscule improvement. The better way of dealing with this is to either prevent us from loading the web fonts like put the web font somewhere where you can robot them away  

#### [0:06:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=390) |  so that we can't fetch them. If

you really care about this [INAUDIBLE] of performance and set your CSS2 fonts so that they swap in default fonts and don't have the Flash-style text up-front. But honestly, I wouldn't. This sounds like something isn't broken, and you just want to tickle these last few seconds out there. Don't. The complexity that you incur is higher than the benefit that you potentially gain, so I would not do that.  

#### [0:07:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=420) |  As mentioned in the JavaScript SEO basics

article-- yay! Someone's reading my documentation. That's great. Using meaningful HTTP status codes can be impossible for SPAs with client-side routing. Yep. The article goes on to suggest using a redirect to a server render of the URL for this purpose. This solution seems like an overkill for a 404 page. No. No, that's not, because you should be able to configure your server, so you can set it to a 404 status code for some URL,  

#### [0:07:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=450) |  and then you just redirect to that

URL. I don't see why that's hard. I think, in Express.js, that's five lines of code, including the client-side part. Does Google really not recognize a 404 at this day and age? Maybe you can shed some light. We do. We do. If we think that is a soft 404, we do usually flag that, but it's such a bad idea, and it's so easy to prevent. If you don't want to do the overkill, then just no-index the page that is a 404.  

#### [0:08:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=480) |  That's also cool. That's one line. That's

why I have these both examples in there. We do recognize soft 404s normally, but there is a risk, and there will always be a risk, because what we're doing. Our machine has to guess, where there are three mechanisms where we wouldn't have to guess. The 404 as a server-side response, which is not available in the client-side-rendered and client-side-routed application. I understand that.  

#### [0:08:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=510) |  That's one way of not having us

guess and actually having us know that this is a 404. The no-index, where we don't know it's the 404, but we wouldn't put it in the index for sure, so again, no guessing. Or the redirect to a 404 page-- also no guessing. So if you can make something more solid, why wouldn't you, especially if it's a really, really small amount of code that you have to write to make that happen? If you're OK with the risk of potentially ending up with something in search results that is a 404 page, go for it,  

#### [0:09:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=540) |  but then, don't complain to us later.

There are solutions for this that make it clear that the page shouldn't be in the index. You can use them, or you can not use them. That's fine. Most soft 404s are being caught, but I know at least one example in the recent past where that didn't work. And then people were like, why is this showing up in search? It's an error page. I'm like, you're not telling us it's an error page. You're actually not even saying the word "error" anywhere on the page. You're just showing unrelated things.  

![](https://i.ytimg.com/vi/hHNB7PeMpss/maxres1.jpg)



#### [0:09:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=570) |  You can not implement that, but then

you'll live with a little bit of risk. Cool. Those were the YouTube questions. Thank you so much for submitting. I hope the answers were helpful. If not, you can totally ask follow-up questions in next week's edition. I see that we have a bunch of people here in the audience, and I wonder if the audience has questions as well. GAYACHRI SAMPACH: Hi. This is Gayachri.  

#### [0:10:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=600) |  I joined a bit late. My question

was about dynamic rendering. I think I missed that part. Can you just go through that again, please? My name is Gayachri Sampach. MARTIN SPLITT: Did you ask the question on YouTube? GAYACHRI SAMPACH: Yes. MARTIN SPLITT: Why am I not seeing it? Let me see. Ah, yeah. I see you ask how to join the session. I'm not seeing your question.  

#### [0:10:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=630) |  Could you ask your question again? GAYACHRI

SAMPACH: Just give me one minute. MARTIN SPLITT: Why am I not seeing the question? Let me search from the top. GAYACHRI SAMPACH: Actually, the issue was that we're using React JS for our website, and the navigation bar links-- they're not showing up as links in the Google search console.  

#### [0:11:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=660) |  When I do a live [INAUDIBLE] and

when I see the view crawl page, I don't see the live link. It's just dumped as a chunk of text. So we go back to the developers team, and they told us the dynamic rendering is in place and I don't have to worry about this. But I'm just concerned that if the link [INAUDIBLE] the rendering won't be passed on to the navigation bar categories or the content silos and then on to the end-user pages. I wanted to confirm with you if dynamic rendering is  

#### [0:11:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=690) |  in place for our website. How do

I confirm that it has been implemented properly and it doesn't hurt our SEO? MARTIN SPLITT: That's a good question. It depends a little bit on the dynamic rendering solution that you have in place. If it's Rendertron, Rendertron adds an HTTP response header to a page that it rendered. I can actually probably show this. Give me a second. I need a new Chrome tab for this, and then I need a Rendertron instance.  

#### [0:12:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=720) |  If you're using Rendertron, which I don't

know if you do-- and you don't have to. There's other solutions. I'm not saying that this is the right solution. I'm just saying this is one where it's relatively easy to spot what's happening. Let's see. I think this needs to be HTTP. If I render and serialize this page, this is now a dynamically rendered page. I can tell, because if I go into the Network tab--  

#### [0:12:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=750) |  I'll actually make this larger, real quick,

so that people can actually read what's happening in here. If I load this again, I get the headers, and the response headers contain an X-renderer Rendertron header. Rendertron makes it quite easy to see if it has been used or not. If you would see that in the response headers in the search console, then you would know that Rendertron was used. If not, it's relatively easy as well.  

#### [0:13:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=780) |  You can go to, let's say, the

mobile-friendly. Actually, I am just going to go for the mobile-friendly test. If you were going to the mobile-friendly test, and oh, my. My screen is still too large for the actual windows that I put on top of it. You would look into the rendered HTML. What makes me nervous is that you say you don't see the links in the rendered HTML.  

#### [0:13:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=810) |  That isn't great. I just [INAUDIBLE] again.

Ah! Here. Anyone having a question? Silence? Now is your time.  

#### [0:14:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=840) |  GAYACHRI SAMPACH: Actually, I do have one

more follow-up question on that. Don't header bar links have more priority than footer links? Footer links carry low [INAUDIBLE] when it comes to Google just like footer links or things like that? MARTIN SPLITT: It usually doesn't matter that much. The answer is, as usual, it depends, but normally, it doesn't have that much of a--  

#### [0:14:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=870) |  it's not something that I would invest

a lot of time in. GAYACHRI SAMPACH: OK, good. DAVE SMART: Is there any issues with using web workers to process something quite large in the background and then spit that data back? MARTIN SPLITT: Oh, boy. I feared this question would come. Yes. I did a test on web workers, and I notice that we are not perfect when it comes to-- that's an understatement. We are not talking as much about web workers yet,  

#### [0:15:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=900) |  because I think it's a fantastic technique

to offload heavy work to the background, to a separate thread, basically. But I noticed that Googlebot isn't dealing perfectly fine with it yet. We are working on that, but currently, there are certain limitations. I tested what happens if you do an asynchronous communication flow with Web Worker. Basically, I asked the web worker to load something  

#### [0:15:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=930) |  for me, then it asynchronously loads something

and then comes back later. That doesn't seem to work reliably in Googlebot at the time of this meetup or this recording. This will hopefully change in the future soon, but at this point, we don't have guidance on web workers yet. We hope to fix that rather soon, but we'll see. There are other things with higher priority at this point, because web workers are a relatively exotic feature on the web platform still.  

#### [0:16:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=960) |  But we would love it to be

less exotic, because I think it's a great way of offloading work from the main thread. But be very careful and test that very carefully, because there are very clearly limitations, especially when the worker does something asynchronously. DAVE SMART: Right, OK. Thank you. MARTIN SPLITT: That's a really good question. Wow. Holy moly. So many interesting questions. I also saw a question from Reena now that I apparently missed earlier. JavaScript-based site using Angular 10K URLs,  

#### [0:16:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=990) |  which is the most important content on

the site and have good interlinking but still not even a single page is indexed. Looks like these pages don't exist for Googlebot. Even in the log file, I don't find these URLs. However, the URLs can be indexed for live tests and the other tools. The 41 request-- that doesn't say much. But I'm wondering what happens if I throw this into the tools.  

#### [0:17:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1020) |  Is there a status in the search

console, like "discovered but not indexed," or are we waiting for the crawl queue to do things? What's the background on these? Let's see.  

#### [0:17:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1050) |  This is mobile-first indexed. We did crawl

this, but we're saying this is noncanonical. That's interesting. Let's run this through the mobile-friendly test. I'm sorry.  

#### [0:18:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1080) |  What If I run this through here?

Because it is possible that we are not seeing something. It is possible that there is a caching issue. None of these things would necessarily surprise me. Ah! Why can't I just get the link from any of these tools? Every one has some sort of redirecter in here.  

#### [0:18:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1110) |  Well, when I look at it-- let

me share my screen, because I think Reena was in this Hangout, so she no longer is. That's unfortunate. I'll show it anyways, hoping that she sees the recording. If I share this tab-- you should be seeing my screen in the moment.  

![](https://i.ytimg.com/vi/hHNB7PeMpss/maxres2.jpg)



#### [0:19:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1140) |  I think you see my screen now.

I'm not so sure. The layout doesn't help. Let me change the layout, real quick, for a spotlight, and then hopefully my screen is showing up. DAVE SMART: We can see it. I can see that. MARTIN SPLITT: Awesome. Here we see the /watch/movies is the header and the loading spinner. I'm not sure what would I see if I would go to that website directly. Movies/watch.  

#### [0:19:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1170) |  I'm pretty sure I wouldn't see just

a loading spinner. I'm actually seeing just a loading spinner. That isn't great. We see a loading spinner here. If I go to the main page, I see the same.  

#### [0:20:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1200) |  Nope? Now I actually see content. That's

great. This page does load a bunch of content. Was it movies/watch, or did I get that wrong? Watch/movies. Watch/movies. OK, let's see. Interesting. Right. Watch/movies.  

#### [0:20:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1230) |  Uh-huh. Well, OK. We're not seeing that.

But if we look at what we are seeing here, we see the header and the loading spinner. That's what we see in the mobile-friendly test for the URL /watch/movies. And if I test the main domain, I see a header and a spinner. So as far as Googlebot is involved or is concerned,  

#### [0:21:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1260) |  we are seeing two similar pages, which

means we end up eliminating one for the other. If I were to judge this, you're trying to use a service worker. Maybe that's failing somehow. I would definitely debug this with your developers, because that's not something that you would want,  

#### [0:21:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1290) |  I would say. Good. And then there

was a question in the chat, I believe? Yes. One easy question. JavaScript used for accordions-- is that a problem to access the content behind, for instance, the info? Generally, no. As long as it is in the DOM, then we should not have a problem, or inherently have a problem, accessing this. Ah! You're back. Hi. I just had a look at your website.  

#### [0:22:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1320) |  REENA JHA: Very good. [INAUDIBLE] MARTIN SPLITT:

Do you hear us? REENA JHA: [INAUDIBLE]. MARTIN SPLITT: Hello? Reena? Because we hear you. Going back to the question with the Sky URL.  

#### [0:22:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1350) |  Hi! REENA JHA: Hello. MARTIN SPLITT: Aha.

Do you hear us? Reena? Hello? Yes? REENA JHA: Hello. MARTIN SPLITT: We do hear you. Hi. REENA JHA: Hi. MARTIN SPLITT: Yes? REENA JHA: Hello? MARTIN SPLITT: Do you hear us? REENA JHA: Am I audible? MARTIN SPLITT: Yes, you are. We do hear you.  

#### [0:23:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1380) |  REENA JHA: Sorry. I missed the [INAUDIBLE].

MARTIN SPLITT: Not a problem. You're in luck. I still have it open, so I can show you what the problem seems to be. Give me a second. I just need to reorganize my windows and also the layout. I'll present the Chrome tab. I think it's this one. REENA JHA: Our problem is that-- MARTIN SPLITT: Hello? Yes? We still hear you.  

#### [0:23:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1410) |  SPEAKER 2: Hello. MARTIN SPLITT: Hi. Reena,

we could still hear you, initially. I'm not sure. Now we don't hear you anymore. Ah. REENA JHA: I start now. Basically, our problem is, we do have major movies content,  

#### [0:24:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1440) |  but there's still not even a single

URL indexed in Google. However, the things look fine-- the mobile test and all. This is our directory page only. It's a subfolder. Watch movies. There are multiple movies, a dedicated page for the movies. This is not a particular movie page. MARTIN SPLITT: The thing is, this URL, watch movies, is showing us a spinner. No content here. There's only the main navigation,  

#### [0:24:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1470) |  and then there's the spinner here. REENA

JHA: No, no, no. It's not ready. MARTIN SPLITT: But that's what I'm seeing here. That's what Googlebot sees. REENA JHA: Wait. Let me see. Can you open the live site? MARTIN SPLITT: Yes. Like this. Watch/movies. Hmm.  

#### [0:25:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1500) |  Actually, I'm just going to click on

/movies. This is your live site, right? REENA JHA: Yeah. So click on any of the movies-- [AUDIO OUT] --one day.  

#### [0:25:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1530) |  This is our actual movie page. That

was a subfolder only. MARTIN SPLITT: OK. Then let me have a look.  

#### [0:26:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1560) |  Come on. Come on. Load's forever. Sorry

for that. Yeah, that looks good. That looks like we have a bunch of content.  

#### [0:26:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1590) |  That's pretty nice. If we have seen

this URL-- let me check. 17 days ago. Indeed, we are not knowing about this URL yet for some reason.  

#### [0:27:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1620) |  Interesting. REENA JHA: But these URLs are

not indexed. Even in the log [INAUDIBLE],, I don't find any movie URL. MARTIN SPLITT: That's an interesting question. It looks like we have discovered it from the site map, but it doesn't look like we have done the rest of this. Let's see. What is here? Do we see this properly?  

#### [0:27:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1650) |  So /movies is indexed. That one we

know. That one we have in the index. But then, this one, which is clearly linked, we haven't. REENA JHA: And this happens for the entire site. Only, we do have one particular section which is an episode that comes. MARTIN SPLITT: Sorry? REENA JHA: Yeah, but site map is already submitted in the place.  

#### [0:28:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1680) |  And even URLs are not crawled. They

are discovered but not crawled. Not any other error is there. MARTIN SPLITT: Right. I don't know why that is, but I can try to find out why we are not crawling these. I'm pretty sure I can have a look at why this is happening. I don't have an answer to that from the top of my head.  

#### [0:28:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1710) |  Awesome. OK. REENA JHA: /movies, /tv, /music.

The content under the [INAUDIBLE] folder is not. MARTIN SPLITT: So all of these main pages are indexed, but none of the subpages are indexed yet, and I don't know why, either. I'll have to have a look at this, because I don't know from the top of my head. There is definitely a link here.  

![](https://i.ytimg.com/vi/hHNB7PeMpss/maxres3.jpg)



#### [0:29:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1740) |  Copy link address. Do we know about

this URL? Have we discovered the URL would be the real question. And if we have discovered the URL, why have we not-- interesting. We haven't even discovered this URL. I'll have a look at what's going on here. If it's a problem on our side, then we have to fix it. If not, then I would probably respond  

#### [0:29:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1770) |  on Twitter or something. If you ping

me on Twitter, publicly, then I can potentially say something about-- like, well, there is a problem with this and that. But it looks like we should be able to find this. Interesting Coming back to the original question of the Sky accordion, I'll try out the URL that you have given me here in the chat, Ferhat, and I'll see what we see when we go to that page.  

#### [0:30:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1800) |  Theoretically, it's not a problem to have

an accordion. Wait. Where is the accordion to begin with? You said "e.g. Info." Ah, that's like a tab thing. Not really an accordion, is it? Well, it's an accordion. You're right.  

#### [0:30:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1830) |  If I take this into one of

our testing tools, like the mobile-friendly test-- I really need to get rid of this overscan issue. I say that every week, and then I still don't do it, because I'm so busy with other things. I'm too busy to actually fix the overscan problem. For accordions or any UI element, it's not a problem if the content is invisible. It should just be in the DOM.  

#### [0:31:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1860) |  If it's in the DOM, we can

discover it and work with it. If it's only injected upon user gesture-- that was an earlier question. It was like, we have a menu that only is inserted into the DOM when you click on the button. Googlebot doesn't click, so Googlebot didn't see the button. Actually, didn't click the button and didn't see the content that was injected. Now I need to figure out content that was hidden in the accordion.  

#### [0:31:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1890) |  So if I click on "info," [SPEAKING

GERMAN].. I'm getting the German version. Sorry for that. Yeah, it does show up. It's in the DOM, so we can see it, and we can potentially index it as well. That's not an issue. Any other questions while we are here? GAYACHRI SAMPACH: Martin, I do have a question about structured data, but it's off-topic. Can I ask it here?  

#### [0:32:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1920) |  MARTIN SPLITT: Sure. I mean, no one

else is asking questions, so go for it. GAYACHRI SAMPACH: We have a fairly big website which has thousands of pages, and we're looking to implement a structured data markup. I understand that the organizational level of structured data can be implemented in the headers across all divisions of the website. But if we have to do it for individual pages, organic visitors, articles, blog content, news, or contests, do I have to go to each page manually and add  

#### [0:32:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1950) |  the structured data for each of them

in the first leg of implementation, or is there a better way to do it? MARTIN SPLITT: Optimally, CMS does help you with that in some way, because your CMS should know what kind of page each page is. If your CMS does not have any support, then you can maybe talk to your CMS provider or to your developers, because hypothetically, developers should be able to make decisions  

#### [0:33:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=1980) |  based on the type of page and

then programmatically add the structured data markup. That should be the easiest way to do. There is a possibility that you can do it with Google Tag manager if you're really, really careful, but that is more brittle than implementing it into your site through your own developers or through the CMS. So if you really cannot make changes to your own code, then maybe try to figure out a programmatic way of detecting which kind of page it is and then where to pull the data  

#### [0:33:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=2010) |  for the structured data types. But I

would advise against it unless you really, really have to. GAYACHRI SAMPACH: With this implementation, can it be done for the existing pages as well? MARTIN SPLITT: Sure, sure. GAYACHRI SAMPACH: OK, good. And I have one more question. It's about adding review ratings in Google organic search. Recently, in September 2019, Google said that it is no longer going to publish reviews  

#### [0:34:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=2040) |  for organizations and local businesses. With that,

can you still add reviews and give Google the possibility of displaying it when it organically searches for it instead of us prompting for it? And if we do that, do we have to enter the review manually every time it changes, our does it pull automatically from Google My Business account or something like that? MARTIN SPLITT: I don't know. I don't know about Google My Business, and I don't know the policies behind structured data. I don't know.  

#### [0:34:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=2070) |  GAYACHRI SAMPACH: OK, got it. Thank you.

Thank you so much, Martin. MARTIN SPLITT: You're welcome. Sometimes people are still submitting questions via YouTube. Let's check if we have additional comments. No, not today. Any further questions? Audience questions invited.  

#### [0:35:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=2100) |  No one? All right. If there are

no further questions, I would say-- FERHAT OZTURK: Martin, hi. It's me, Ferhat. MARTIN SPLITT: Hi. FERHAT OZTURK: Just one simple question. You told us that when everything is in the DOM,  

#### [0:35:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=2130) |  then this should be not a problem.

But can this have an effect on SEO when content is behind the tabs or accordion at that case? What do you think? MARTIN SPLITT: You shouldn't hide your primary content behind a user interaction. If you consider that content to be central, critical, and important, then I would suggest that you don't hide it behind a user interaction.  

#### [0:36:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=2160) |  But if you have your content behind

a user interaction, it doesn't hurt. It doesn't make a big difference. I don't think we pull such content in for the description snippet. If we decide to rewrite your description, we wouldn't use content that is hidden on the page, but I don't think it hurts big-time. Again, make your primary content visible immediately. That's my biggest suggestion. FERHAT OZTURK: At that case, all content behind the info, right?  

#### [0:36:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=2190) |  MARTIN SPLITT: If that's the content you

really care about, then yes. FERHAT OZTURK: OK. Thank you-- MARTIN SPLITT: You're welcome. FERHAT OZTURK: --Martin. MARTIN SPLITT: You're welcome. More questions? Oh, there is a-- that's a URL. Only these kind of URLs are indexed. Oh, you're facing an internet issue. That's unfortunate. As I said, for your page, I would  

#### [0:37:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=2220) |  have to check what's happening there, why

we are not seeing these things. I can't answer on the spot for these things, as the URL seems to be fine, and I'm not sure why we wouldn't see the linked URLs. That requires me to make sure that it's not something on our end. It might be something on your end, but I can't tell you what without looking at it and seeing the reason as to why we're not seeing something specifically.  

#### [0:37:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=2250) |  Other questions? Wait. Where was-- so many

windows. If there are no further questions,  

#### [0:38:00](https://www.youtube.com/watch?v=hHNB7PeMpss&t=2280) |  then I would like to say thank

you very, very much for joining this week's JavaScript SEO office hours. Check out our YouTube channel to see when the next ones are announced. I'll probably announce them pretty much right now so that people can post their questions there. They will be recorded as well. I'll put up the recording, hopefully, soonish. I guess, maybe, Thursday, maybe Friday. Keep being amazing. Stay healthy.  

#### [0:38:30](https://www.youtube.com/watch?v=hHNB7PeMpss&t=2310) |  Stay safe. Thank you very much for

joining. Have a fantastic time. Bye-bye. GAYACHRI SAMPACH: Thank you so much. You, too, Martin. MARTIN SPLITT: You're welcome. PREM VISHWAKARMA: Bye-bye. GAYACHRI SAMPACH: Goodbye.  