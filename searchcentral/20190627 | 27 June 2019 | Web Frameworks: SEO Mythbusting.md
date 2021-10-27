[![Web Frameworks: SEO Mythbusting](https://i.ytimg.com/vi/WU_ZaO35w0U/hqdefault.jpg)](https://www.youtube.com/watch?v=WU_ZaO35w0U)

## Web Frameworks: SEO Mythbusting

In this fifth episode of SEO Mythbusting, Martin Splitt (WebMaster Trends Analyst, Google) and his guest Jason Miller (Sr. Web Developer Programs Engineer, Google) discuss the challenges of web frameworks in the context of SEO, such as:



1:28 Do search engines run JavaScript?

2:39 How to debug your site’s discoverability issues with the new Google Search Console features?

4:17 Which features can one count on being available in the Google crawlers?

5:10 For websites built using web frameworks, does Google Search pick up on push-dates, and under what conditions?

7:30 Is content accessible by onclick event handlers & buttons indexable?

9:45 How can you make your content easily discoverable if you use infinite scrolling?

11:06 SEO troubleshooting for websites driven by web workers

12:39 Is there much of a difference between framework sizes and approaches for how those get crawled?



Documentation mentioned in this episode:

Mobile-friendly test → https://g.co/mobilefriendly

Lazy loading in search → https://goo.gle/lazy-loading-in-search

Crawl budget → https://goo.gle/crawl-budget



Next week, look forward to the last SEO Mythbusting episode - Future of the Web: SEO Mythbusting



Watch more SEO Mythbusting episodes → https://goo.gle/SEO-Mythbusting 

Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=0) |  JASON MILLER: When I was first building

the Preact site, I had it kind of all client side rendered. We weren't doing any pre-rendering or anything. We are now, but at the time I did that, and we weren't super concerned with SEO at the time which immediately vanished. And I was definitely worried when we first pushed it live, like, is this just going to be like a title on Google search with nobody content? MARTIN SPLITT: Right. Yeah. JASON MILLER: So I was kind of confused with that, and there was other weird things. Like, we were doing client side routing,  

#### [0:00:30](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=30) |  and in response to the client side

routing, we would change the meta tags for that description stuff. MARTIN SPLITT: Yeah. JASON MILLER: No idea whether that gets picked up in Google search. [MUSIC PLAYING] MARTIN SPLITT: Hello and welcome to another episode of "SEO Mythbusting." With me today is Jason Miller. I'm really excited to have you here. So Jason, what do you do for work?  

#### [0:01:00](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=60) |  JASON MILLER: I'm a DevRel on the

Chrome team. MARTIN SPLITT: Cool. So what do you work on? JASON MILLER: I work on a bunch of APIs in Chrome and sort of test them out. MARTIN SPLITT: Cool. And you build Preact as well, right? JASON MILLER: I do build Preact on the side. Yes. MARTIN SPLITT: Oh. That's a cool thing. So now that I've got you here, let's talk about SEO and frameworks. JASON MILLER: Sure. MARTIN SPLITT: So I guess there's a bunch of misconceptions about how frameworks and SEO come together, and it would be a perfect opportunity to get them all mythbusted. JASON MILLER: There's definitely a conception that search engines don't run in JavaScript, just  

#### [0:01:30](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=90) |  across the board. MARTIN SPLITT: Wow. OK

JASON MILLER: I'm not 100% sure where that comes from. I think maybe back in the early days of the web, it wasn't a thing. MARTIN SPLITT: Us too. JASON MILLER: I mean, there's still probably cases where some other engines don't. So maybe that's like-- it's pervasive because of that. MARTIN SPLITT: Hmm. That makes sense then. That makes sense. I mean, we do still have crawlers and engines out there that are not executing JavaScript. Is there anything that you wonder or worry  

#### [0:02:00](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=120) |  about in terms of discoverability? JASON MILLER:

Yeah. Definitely. So like if you build an app where the HTML payload is a script tag and a style sheet. [CHUCKLING] You laugh. This is every app. MARTIN SPLITT: Yeah. That is is true. That's what happens. Yeah. Yeah. I mean, besides the user implications that this has, because obviously the browser then has to fetch more content and you look at a blank page for little longer, that also does affect the crawlers a little bit, especially the ones that are not actually executing JavaScript. JASON MILLER: Definitely. MARTIN SPLITT: I can speak for those, but I can say that Google bot does execute JavaScript.  

#### [0:02:30](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=150) |  So we do see your content unless

there's some good reason not to see your content like the JavaScript errors or network arrows happening. JASON MILLER: I did see in the CDS talk you did-- MARTIN SPLITT: Mm-hm. JASON MILLER: There was a new feature in Search Console that you guys were talking about for errors. MARTIN SPLITT: Yes. Yes. So I don't know if you've ever used the [INAUDIBLE] renderer in Search Console beforehand-- JASON MILLER: To get a screenshot. Yes. MARTIN SPLITT: To get a screenshot. So what do you do when you get a blank screenshot? JASON MILLER: Cry. MARTIN SPLITT: Yeah.  

#### [0:03:00](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=180) |  That was-- yeah. I feel you. So

the one we have working around that is to use the mobile friendly test, which is the tool that we brought out. It does what it says it does in the name. Like, It tells you if your page is mobile friendly which is fantastic. But more importantly, it also gives you a list of the resources that we couldn't fetch for whatever reason-- JASON MILLER: Oh cool. MARTIN SPLITT: And it gives you the console logs. JASON MILLER: All of them? MARTIN SPLITT: All of them, including sec traces. JASON MILLER: What? MARTIN SPLITT: Yeah. So you can actually debug.  

![](https://i.ytimg.com/vi/WU_ZaO35w0U/hq1.jpg)



#### [0:03:30](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=210) |  So you get a blank screen shot

and you're like, oh, no. But then you can go to the console and see why. So what we are doing right now is we are working on the new Search Console that also contains a thing that we call the URL inspection tool-- that's part of the Search Console-- and for every page that you have on your site that you verified for because we don't want to serve that data to the public. JASON MILLER: Oh yes. Show me Google search itself. MARTIN SPLITT: Exactly. Show me your Google search data. So we tried to have one stop solution for pretty much everything. Right now, that includes when we last call you, if it's on Google or not,  

#### [0:04:00](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=240) |  if there has been any issues with,

I think, mobile friendliness or AMP, but-- yes. But that's going to be extended to structured data and also to JavaScript errors, I think. JASON MILLER: So we mentioned like the features thing, like what features can I count on being available in the crawler? MARTIN SPLITT: So we do parse HTML. JASON MILLER: Really? MARTIN SPLITT: Yeah, right? That's a mind blowing one. We are stateless. So that means we are basically pretending  

#### [0:04:30](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=270) |  to be incognito browser that opens the

tab for each URL that we are indexing the first time. JASON MILLER: Full of storage, that kind of stuff. MARTIN SPLITT: Local storage. While we do store cookies, but basically when we visit, when we go from one page to another, these cookies are cleared so you can't really rely on cookies to be available on cross. JASON MILLER: Right. MARTIN SPLITT: We're not running WebGL. JASON MILLER: OK. MARTIN SPLITT: Yeah. I don't think we are rendering what's on the canvas. I'm not sure about that. JASON MILLER: You can't really search it anyway, right? MARTIN SPLITT: That's the thing. Exactly. Everything in there is inaccessible to pretty much every user who is using assistive technology,  

#### [0:05:00](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=300) |  and you can think of a crawler

as a user that needs assistive technology to understand the content. JASON MILLER: I'm curious if, let's say, like-- this is a super biased question, but let's say I built a website using a framework that ends in ACT, one of the many. So let's say I built a website using whatever technology client side rendering. MARTIN SPLITT: Right. JASON MILLER: And I'm doing like push state routing using the history API. Does a Google pickup on push dates? MARTIN SPLITT: Yes.  

#### [0:05:30](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=330) |  Yes we do because you give us

a proper URL, right? JASON MILLER: Right. Hopefully. MARTIN SPLITT: You have like example.com/blurb/listing or something like that. So we do pick those up. If you use hash based routing, we don't pick them up. So please do not use push state routing history. API is the way to go. So if you use proper history API URLs. However, don't fall for a thing that I have seen a few people fall for. You might test by basically loading your page from the home page and then clicking through.  

#### [0:06:00](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=360) |  We are not doing that. Remember, we

are stateless. So if I go straight to slash something-- so if you use the URL and use the link to that URL somewhere in your page, that's fantastic, but make sure that people can enter right there. JASON MILLER: Interesting. MARTIN SPLITT: So you may have to make sure that the server understands how to surf this. One way of doing it is using a server that actually serves the index HTML for all routes and then the JavaScript displays the right content. That is perfectly fine. Just don't give us a 404 or 500 or something like that. JASON MILLER: Right. OK. Yeah. So like a bunch of the services-- like, I'm super lazy  

#### [0:06:30](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=390) |  and deploy all my stuff CDNs. MARTIN

SPLITT: Likewise. JASON MILLER: Yeah. So they let you do like a 200.html, and it's just like, it returns that content for any URL that is not a file. MARTIN SPLITT: That is fantastic. I did fall for something once. You might use like a static site thing that you can-- JASON MILLER: On occasion. MARTIN SPLITT: Yeah, like GitHub pages or S3 or whatever, doesn't matter. They also give you the possibility to do a custom 404 page, right? And I have abused that to serve all-- because I didn't  

![](https://i.ytimg.com/vi/WU_ZaO35w0U/hq2.jpg)



#### [0:07:00](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=420) |  know all my routes upfront. So I'm

like, yeah. You know, if it finds a route that it doesn't know, it starts this 404 HTML. JASON MILLER: Is it status quo 404? MARTIN SPLITT: Yes, and that's why it's not being indexed then. JASON MILLER: Oh. MARTIN SPLITT: Yeah. JASON MILLER: So it's an error page that is actually very useful. MARTIN SPLITT: Yeah. But you shouldn't be doing that because if you give that to a crawler and say this is not a page, then we're not picking it up because you told us not to. JASON MILLER: So you said, if I'm using HTML links or whatever link between pages that's fine.  

#### [0:07:30](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=450) |  What if I'm using-- don't judge you

for this-- a button and the button has a click handler, and that click handler calls push state. I'm not saying I'm doing this. I'm not saying I'm not doing. MARTIN SPLITT: Let me guess, a friend of yours does that. JASON MILLER: Right. Yes. What's the name? MARTIN SPLITT: Bob. [LAUGHTER] JASON MILLER: Bob. MARTIN SPLITT: Bob uses buttons on click handlers. JASON MILLER: Poor Bob. MARTIN SPLITT: You clearly do not.  

#### [0:08:00](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=480) |  JASON MILLER: No. I would never do

that. MARTIN SPLITT: And I'm very happy that you're not doing that because your friend really needs to use links for that. JASON MILLER: Right. MARTIN SPLITT: Because links are to go from A to B. Button triggers an action. I think-- you can use buttons on click handles for all the things that are like, I don't know, doing a pop up or something. JASON MILLER: A modal. MARTIN SPLITT: Yeah, modals or even a trigger function, trigger a countdown. Whatever. If it's an action that happens on the page, that's a button, and that's perfectly fine. But if it takes you to another piece of content and you want to make this content accessible via search  

#### [0:08:30](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=510) |  and make it discoverable in search engines,

if it has a URL, it should be a link, right? JASON MILLER: So like if I a modal that had like high-value content in it or whatever, and it right now is just a button with a click handler that shows a thing on a page, if I want that to actually have a representation in the search results, give it a URL. MARTIN SPLITT: Give it a URL. JASON MILLER: Make it a list. MARTIN SPLITT: Yes. But you can always do this. So I like the idea of exposing some of the application state in the URL. So you can basically say like, we support parameters, so you could basically  

#### [0:09:00](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=540) |  go like, I don't know, slash, action,

question mark, model or pop up equals true. And if you use a link to go to that one, and then that means that it displays the thing. Basically, you have to understand that search results work like as if you would take a URL, copy that into your messenger, someone else tapping on the message on whatever device, you don't know. So basically, they start a fresh browser, have never been to your page. Do they see what you are seeing? If that's the case, then that's an indexable URL. JASON MILLER: Right.  

#### [0:09:30](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=570) |  Because otherwise, if I had a modal

and let's say Google somehow crawled it, if you click on a link from Google Search, how does the link open the modal? MARTIN SPLITT: That's the thing. Exactly. It has to make it happen-- JASON MILLER: Interesting. MARTIN SPLITT: --because if that's a mismatch, then what's the point? Another situation like that is infinite scrolls, right? JASON MILLER: Right. MARTIN SPLITT: Don't you hate it when someone sends you a link, and then goes like, did you see like that bird? And then you look at it and it's like, there-- what bird? Oh, yeah, you have to scroll for a while. JASON MILLER: Yeah, if you just scroll  

#### [0:10:00](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=600) |  600 meters down the page, or 400

feet or whatever. MARTIN SPLITT: I use metric system. JASON MILLER: Oh, good. MARTIN SPLITT: Thank you very much for, ah-- I think more people should do that. So yeah, if you scroll down like 600 meters on a page to find the content, that's an issue to surface that. JASON MILLER: If you could link to it, if there's like an anchor on it-- MARTIN SPLITT: Now you've got it. Exactly. If it's an anchor, and specifically if you were using push states to update the URL, and then allow the JavaScript to pick that up.  

![](https://i.ytimg.com/vi/WU_ZaO35w0U/hq3.jpg)



#### [0:10:30](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=630) |  When you come back into the site

and load the right content for it, you're off really well. JASON MILLER: So it's almost like you're doing Virtual Scroll, but the Google Search bot almost sees it as like Next and Back buttons. MARTIN SPLITT: Pretty much. Yeah. That's kind of like the modality that-- exactly. You give it an offset and then we're like, OK, so now our JavaScript starts at like page five. And then you're good. And then Google bot comes and goes like, oh, so there's a link here with page five. All right. So in that case, it surfaces these 25 images,  

#### [0:11:00](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=660) |  the bird being the third one. Off

we go. So that's a good way of doing it. JASON MILLER: So let's say I was like driving a page with a worker. Like I have like a worker that's doing all of my estate management, or even doing DOM rendering or something crazy. And in order to actually get pixels on the screen, I have to round trip through that worker and get all the HTML and DOM manipulation back on the main thread. Is the fact that that might take a little while going  

#### [0:11:30](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=690) |  to be a problem for Google Bot?

MARTIN SPLITT: Generally speaking, no. I'm definitely encouraging to test that carefully using tools that we've got available to make sure that everything works the way you expect. But basically, if you see the content in the-- the mobile from the test also gives you the rendered HTML that we are using for indexing. So you can use that to see if it appears. Normally, if it takes a little bit of time, that doesn't matter that much because we're doing wonky interesting things with time anyways because we have to deal with a bunch of interesting situations--  

#### [0:12:00](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=720) |  JASON MILLER: We can just take a

wild look. MARTIN SPLITT: Exactly. So don't worry too much about the time it takes. If it's a little fragile, you will find out using the tools. JASON MILLER: The HTML that it shows, is that-- like if I've done DOM manipulation, is that after the DOM manipulation? MARTIN SPLITT: Yeah. JASON MILLER: OK. So it's like a snapshot. MARTIN SPLITT: Yeah. And if you're not seeing it, then something has gone sideways. JASON MILLER: OK, so even if I didn't have the error reporting thing-- I mean I want the error reporting thing. But even if I didn't have the error reporting thing-- MARTIN SPLITT: You still have the rendered HTML that you can deduct from what we're indexing. So. JASON MILLER: OK.  

#### [0:12:30](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=750) |  That works. I can live with that.

MARTIN SPLITT: That's pretty cool. All right. Anything else from the top of your head? JASON MILLER: So like, when I'm picking a framework or trying to figure out how I'm going to build my front-end stack, is it much of a difference between framework sizes and approaches for how those might get crawled. MARTIN SPLITT: So when we're talking about crawl budget, which means how often and how quickly we can crawl, the frameworks don't have that much of a difference because we are not like discriminating or preferring any of those. And we are not like looking at, we're  

#### [0:13:00](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=780) |  not looking too much at the size

really. So generally speaking, the more requests you do to get the content together, the more requests we count towards like that. We have done 1,000 requests. And if each page of your content makes 100 requests, that's literally like 10 pages. So, it's also a usability thing, basically, if you think about it, being on a flaky network. Not nice to get half-baked content or get no content at all, and only the empty shell.  

#### [0:13:30](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=810) |  So it makes sense to look into

server side rendering or hybrid rendering to minimize the amount of requests that it takes because that helps you with the crawl budget sometimes. But that being said, crawl budget is a really tricky topic because we cache stuff. So if we have the content already in the cache, that doesn't count towards it. JASON MILLER: Yeah. If your home page loads all the stuff, and then all your product pages or whatever are just hitting the cache, maybe your slipping under the crawl budget. MARTIN SPLITT: That might happen, exactly. And crawl budget adjusts all the time anyways because we want to make sure they're not overwhelming the server. So. JASON MILLER: Interesting. MARTIN SPLITT: Jason, it has been a fantastic conversation.  

#### [0:14:00](https://www.youtube.com/watch?v=WU_ZaO35w0U&t=840) |  Thank you so much for being here.

I'm really looking forward to what you're building next. JASON MILLER: Cool. MARTIN SPLITT: Thanks a lot for being on the show. Thanks. In the next episode of "SEO Mythbusting," Dion Almaer is going to join me to talk about the web platform and SEO, and all the road that lies ahead of us. So do not forget to subscribe to the Webmasters channel.  