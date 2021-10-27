[![JavaScript SEO office hours October 28th, 2020](https://i.ytimg.com/vi/R3SQnt_B7go/maxresdefault.jpg)](https://www.youtube.com/watch?v=R3SQnt_B7go)

## JavaScript SEO office hours October 28th, 2020

In the JavaScript SEO office hours, you can ask your questions about Google Search and JavaScript. You can either join the recordings live or post questions in the relevant thread on youtube.com/googlewebmasters/community



#### [0:00:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=0) |  MARTIN SPLITT: All right. Hello, and welcome

to the JavaScript SEO office hours on October 28, if I remember correctly, or if I can read my numbers on the watch correctly. In these, you have the opportunity to post questions onto YouTube. If you go to youtube.com/goog lewebmasters/community, you'll find different threads for the questions for the different office hours. There's the general office hours that John Miller runs, and then there's the JavaScript SEO office hours  

#### [0:00:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=30) |  that you're watching today. You also have

the opportunity to join the recording live and ask your questions live. I'm really happy to see that I have three guests in this office hours today. Hello. How's it going? And we have a bunch of questions submitted through YouTube. So I'll go quickly through those who have submitted questions on YouTube. All right, is it bad to use JavaScript for pagination? Oh, that's a lovely question, because the answer is no, it's fine. Test it.  

#### [0:01:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=60) |  Make sure that you're not breaking it,

that you're not doing something that doesn't work or that we can't pick up. But generally, JavaScript pagination is not an issue. Ludvig Larsson is asking a longer question. "About page links to products. in the raw HTML, the a link tags are formatted as href and then double curly braces URL. With JavaScript enabled, that placeholder, that double curly braces URL, gets replaced with a real link and correctly rendered as href-- for instance, slash category one slash product 123.  

#### [0:01:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=90) |  These links are followed and indexed by

Google." Good. "However, in Search Console, the 404 error report contains many links, such as category one slash double curly braces URL, which obviously originate from the raw HTML. Since Google can index the JavaScript rendered links correctly, would it somehow be a bad practice to add disallow slash double curly braces URL in robots.txt to quickly solve this issue?" Well, first things first, if the links get indexed,  

#### [0:02:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=120) |  it's not really an issue. So the

error report, the 404 error report, is just to highlight that there is something that is a 404. That can always happen. It is definitely possible that someone links to a page that doesn't exist, we crawl it, and then you see a 404 error report for that. It doesn't mean that you need to worry about it. It's not an issue that you need to address. It's just something-- if it annoys you, then you can totally look into your robots.txt and disallow URLs with that placeholder. But it's not a problem that you need to address.  

#### [0:02:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=150) |  It's more like an inconvenience. Eric asks

a very broad question, which is, "SEO and Create React App, can you talk about that?" Yes. Generally speaking, Create React App is mostly fine out of the box. You do want to add React Helmet to get some metadata in, as well. But if you want to learn more about that, conveniently I did talk about that in the past. If you go to our YouTube channel and search for the JavaScript SEO video series, there is an episode of React that I highly  

#### [0:03:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=180) |  recommend you check out. Then Ricardo asks

a question about something that is actually not JavaScript, so I think I'll skip that. Sorry for that. I should have marked that beforehand. Then we have Manoju is asking, "JavaScript error in amp?" I'm sorry, that's too broad to answer. If you have details, maybe take that question to the webmaster forum, as well, because that is not  

#### [0:03:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=210) |  a question that makes sense to answer,

because I don't have any context here. Joseph is asking about the benefits of using Jamstack for a website. He specifically asks about Nuxt or Next.js or Gatsby, if there's any pitfalls in these approaches or if I would recommend it. So generally speaking, Jamstack websites are great for websites that have some dynamic data  

#### [0:04:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=240) |  but are not super dynamic. Next.js, Nuxt.js,

both of these allow you to use server-side rendering plus hydration, which is generally a very robust and stable approach, if done right. The big pitfall is that people are not testing things. They're like, ah, it's server-side rendering. It'll be fine. If your server side rendering output is garbage, or if the hydration makes it garbage, it's not going to help you. So definitely test this with the testing tools, be it Search Console, be it mobile-friendly test, be it  

#### [0:04:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=270) |  rich results test. Just make sure that

it works from our perspective, that the rendered HTML model looks like something that you would want to see. But generally, we do recommend server-side rendering just as a way of having a more robust setup. But server side rendering can have interesting consequences. If it goes wrong, it might require a more complicated server-side configuration. It might require a little bit of care in terms of how you are dealing with data sources.  

#### [0:05:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=300) |  But there's nothing specific for SEO or

Google Search that you need to be aware of. "Hi, Martin. How can we add JavaScript powered graphs," asks Andrei, "to a large website so that it will not affect core web vitals?" Well. "Will not waste our crawl budget and will not make Googlebot treat this content as duplicate. Can you point to some typical pitfalls?" One typical-- I mean, if you add graphs to the existing page, that's not duplicate content.  

#### [0:05:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=330) |  That's not an issue. If the only

thing that is on the page is a JavaScript powered graph, then that's probably not really that useful in terms of content and we might ignore that. But if you embed the graph into a page that has content and is indexed, that's not a problem. You want to be careful with cumulative layout shift. If the graph container basically just pops in eventually, shifting everything on the page once it does, that might impact your core web vitals. You also want to make sure that you're not loading a bazillion different JavaScript files just  

#### [0:06:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=360) |  to have a graph, because that wastes

crawl budget. Try to have one bundle for the graphs, or integrate the graph libraries into your bundle so that you have one API call, maybe, plus the JavaScript source that needs to be loaded. And then also use CSS so that the containers have fixed dimensions so that they don't magically appear, shifting everything on the site. That should help a lot. Also, minimizing the amount of JavaScript is generally a good idea.  

#### [0:06:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=390) |  If you can pre-render the graph somehow,

do it. If that is not feasible or is too costly, then don't. Then JavaScript graphs is just fine. And then Dave asked the question, "I have a client that is planning a range of internationalization features, a clothing retailer. The first step is to change the price and currency, shipping and sizing info, to match the user's location." That's very nice. And they make it swappable. That's good. I like to hear that, because I hate it with a passion if I'm in the US and everything is, like, 7 inches,  

#### [0:07:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=420) |  and I'm like, I don't know what

that means. You might as well say, like, 20 caterpillars. That's not helping me. I want centimeters. I'm living in the metric world. So they want to do this on the client side during hydration, which will differ from the server side content that Googlebot might see. "Besides seeing the US version, because Googlebot usually crawls from the US, would this be an issue?" Generally-- oh, read more. OK, and then there's the second step  

#### [0:07:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=450) |  that we will get into in a

moment, as well. Generally, I would say if these two pieces of content differ, that's not much of an issue. Just be careful that if the rendering for some reason fails-- like, we can fetch something, some resource or something-- then we might end up seeing the server side rendered content. And then you might get weird movements or even canonicalization changes, depending on if the content looks different enough for us to say, OK, so this is a canonical version of this one.  

#### [0:08:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=480) |  And then there's-- this other canonical piece

is different enough. Second step is they plan to go for a fuller translation during hydration, also update the URL to an international one. Yeah, generally that is fine. I don't see a potential problem right away. Again, testing is key here. And I know that we have Dave here. Do we have follow-up questions on that? DAVE SMART: Yeah, it was more on the second one, because the planning, if I arrive from France,  

#### [0:08:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=510) |  they plan on updating the URL to

a French one, and obviously doing all the full translation. But they also want to use href lang, et cetera. My concern was if Googlebot-- it almost like you advise against on something where you 301 redirect or 302 redirect people, which they generally say no. I kind of worry that basically it'll wipe out everything, because ultimately you're updating the URL.  

![](https://i.ytimg.com/vi/R3SQnt_B7go/maxres1.jpg)



#### [0:09:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=540) |  I wasn't sure whether Google would definitely

treat that as a redirect to the French one, and they'd never ever see anything other than the US version, if that's where they're mostly crawling from. I mean, they're adamant that they really want to do it. And I could see, it's a nice experience. Once again, they've got a little switchable thing. But that relies on cookies, which obviously aren't going to work on-- MARTIN SPLITT: Mmm, yeah. DAVE SMART: --Googlebot. So it is a nice-- from a user experience, I could definitely see their arguments.  

#### [0:09:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=570) |  You know, it's a nice experience. It's

kind of not having to, are you from the USA? From here in a big banner. It kind of takes you there. It does still give you the opportunity to go where you want to. But I do worry that for Googlebot, it's going to be no different, so if you just force redirect to them all to the US version. So the only sort of solution I could come up with was trying to prevent that happening for Googlebot, which seems a bit fragile and a bit [INAUDIBLE].. I never really liked doing that kind of thing. But would, ultimately, that cause an issue  

#### [0:10:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=600) |  if that was the only solution? MARTIN

SPLITT: I'm not sure how big of a problem this might be. I would expect-- try it out, if you can. Try to see what happens when we run into situations like that. And if that is what you expect, then don't build additional brittle bits and pieces in. I think a forced redirect for Googlebot  

#### [0:10:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=630) |  would not be too brittle, depending on

how it's implemented. Yeah, good question. No, I can't foresee any obvious problems with this, to be honest. But then again-- DAVE SMART: What I'm trying to get them to do is just launch the UK version and then maybe just roll out a country or two and maybe see where we go from there.  

#### [0:11:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=660) |  As ever, they'd love to know it

all up fronthand. But I guess we don't really know it fronthand. So OK, thank you. MARTIN SPLITT: All right. Yeah, and I mean, staged rollouts are generally a good idea. These all or nothing things are-- or have a tendency to break in interesting ways. Now, I've got three questions from Asaf to finish up the YouTube backlog, so to say. First question is, "A JavaScript site with client-side rendering set up using dynamic JavaScript to change the title  

#### [0:11:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=690) |  and uses the React Helmet component for

description and other social tags. Sometimes in search results you see the default title--" which is what is in the initial HTML, I'm guessing-- "and the description looks corrupt, as well." Well, I'm not sure what that means. The question is, "Does taking the Helmet tags higher in the head section will make it more stable? How can I improve the stability for showing the correct title?" First things first, depending on where you see these-- as in, like, if you're seeing these for actual search queries,  

#### [0:12:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=720) |  or if you just see them in

the site list of things, you should be more or less worried. If it's for actual queries, that's something that I would be a little worried about. If you're seeing it in the site query operator, then that's not really an issue, because we usually don't use, by default, "bad" titles and descriptions when the actual queries are being used. So I wouldn't worry too much about that. If you move it up, I don't think it makes that much of a difference. I don't think that we go by that.  

#### [0:12:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=750) |  It might just be that we are

sometimes picking up things without rendering first. And then rendering takes a little moment until that actually kicks in. And then we are updating the index. And index updates take a bit-- I'm talking minutes here, not hours or something. So moving it up doesn't really make that much of a difference, I think. If you can server-side render the metadata, that's definitely a way to avoid the situation there. If you can't, then again, I wouldn't worry too much  

#### [0:13:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=780) |  about it. Another related question to pagination,

they use an infinite scroll. They want to add classic pagination at the bottom of the page with push state setup. We don't really have a tutorial on this. But basically, again, it doesn't really matter if you have a classic pagination with pages 1, 2, 3, 4, 5, 6, 7, and so on and so forth, to 10, or just Next and Previous links,  

#### [0:13:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=810) |  because one, the pagination with more links

to different pages just allows us to discover these a little quicker, the different pages. Whereas without that, we would have to do multiple cycles of crawl. But it doesn't really make that much of a difference. I know that for e-commerce, we are working on guidance on this. But I can't give an ETA on when that documentation will be available.  

#### [0:14:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=840) |  All right. I think those were the

questions from YouTube. Let me refresh, because sometimes some questions trickle in after they start the-- no, OK. Fantastic. In that case, let's open the floor to questions. Do you folks have questions for me? TONY MCCREATH: I'll have a go at one. I'm not a super expert at JavaScript.  

#### [0:14:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=870) |  I've been recently playing with CDNs. And

something I realized was things like static resources, they're great for that. You get the resource closer. But if you're looking at dynamic stuff like JavaScript doing APIs, I get the feeling that the CDN actually slows things down there. So there's a compromise, because you have to go via the CDN network.  

#### [0:15:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=900) |  Is there any kind of best practices?

Do you do API calls on a different domain or something? MARTIN SPLITT: So my general guidance for these kind of things is, CDNs for me are strictly for static assets. So your JavaScript files, your CSS files, your images, your videos, your fonts, this kind of stuff, goes onto a CDN. Also because you can cache it, these things tend to have a tendency to cachable longer.  

#### [0:15:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=930) |  With JavaScript bundles, that's debatable. But let's

say, like, CSS doesn't change that often, probably. Fonts do not change that often. Images do not change that often. Sure, there's more images probably. But I rarely see an existing image being updated every week. So these are really, really handy, because they speed up things. For API calls, I would put them on a separate domain. I would have something like api.example.com instead of just putting it on example.com,  

#### [0:16:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=960) |  simply because browsers have a connection limit.

And actually Googlebot, the same thing, has a connection limit. So I think for Chrome it's 12 connections, 6 connections? So say you would load lots of images or make lots of parallel API calls. You could do, like, six of them. And then afterwards, they would have to stall until the first one is finished. And then it basically rolls over. You can avoid that by splitting it out to a separate domain.  

#### [0:16:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=990) |  To be fair, it's pretty much the

only thing you fetch from the main domain is the static HTML. And then all of the assets come from the CDN. Then you should also be fine with doing your API calls from the main domain. That depends a little bit on what your setup looks like. But in general, I would suggest you try to design an API in a way that minimizes the amount of network calls that go from the browser to whatever server infrastructure you've got.  

#### [0:17:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1020) |  That sometimes collides with clean API design,

especially if it's a REST API. You want these different resources. But you might need the bundle of resources. One way to ship around this is a GraphQL API where you basically send one request and say, I want all these things. And then you get one response back with all these things. The other way would be to build what I call an API proxy or an API facade, where you say, get data for this screen. And then it makes the actual internal API calls that it needs to make to fetch all the different bits and pieces.  

#### [0:17:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1050) |  And then it gives back one response.

Yeah. But unless you have lots of API calls, that isn't really a problem. But then again, a CDN surely slows things down, because you shoot to the CDN, and then the CDN basically becomes a proxy. And I don't see the value of that proxy. Especially if it's API calls that you can't cache. If it's something that you can cache, then maybe. Like, I don't know, stock prices you can probably cache, because every user would more or less  

![](https://i.ytimg.com/vi/R3SQnt_B7go/maxres2.jpg)



#### [0:18:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1080) |  get the same result within a certain

time window. TONY MCCREATH: Well, yeah. I've seen-- or common practice is to put a version number on static resources so you can have them-- you don't have to worry about timeout. MARTIN SPLITT: Exactly. You can cache them infinitely, because if they change, the file name changes. Yeah. That's a very good practice. TONY MCCREATH: I also found, I think by default, CDNs will not cache HTML resources, because they vary.  

#### [0:18:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1110) |  They might have users [INAUDIBLE] fix different

things. So I was thinking the same with that, that that should be on a different domain to your static stuff. And probably I'm seeing this because Australia's the wrong side of the world. And I've got servers in the US, CDN here. And so I've found HTML going via the CDN  

#### [0:19:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1140) |  would add half a second to the

basic request. And just going-- tossing it up. Faster images, slower HTML. So I'm thinking about this idea of split-- like you were saying, use subdomains and things like that. MARTIN SPLITT: Yeah. That's a really good, common practice. And as you say, it can differ quite a bit if you are pushing non-cachable things to those CDNs.  

#### [0:19:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1170) |  That's a good observation. And I know

how you feel. I used to work for a company that had a few customers from Australia. And we ended up actually basically spinning up a few instances on Amazon in Australia, just because that's the only way to make it reasonably fast without much change to our code or our infrastructure. Fun times. I think Natalia had a question, as well? NATALIA VITI: Yes, I have a quick question.  

#### [0:20:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1200) |  Or maybe not a quick question, we'll

see. I'm wondering, because very often when doing page speed reports, JavaScript from third parties is flagged. And particularly, I'm referring to a case that I've seen many times in international ICO where we use, for example, Google Analytics and also Yandex.Metrica or different third party scripts we cannot really change and optimize. And I wonder if there's any best practice to kind of solve this issue of the speed, because typically it's  

#### [0:20:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1230) |  making the results terrible. And it's always

a battle to convince the developers to keep the codes like that, that Yandex.Metrica, for example. It's typically a 20 second difference in the page speed results. So I wonder if you have any advice on that or any concept how to maybe execute it so it doesn't harm the result. MARTIN SPLITT: Oh, that's a really good question, and definitely not a quick one, because it comes down to a very subtle, very delicate balance.  

#### [0:21:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1260) |  On one hand, you want to load

these things as early as possible so that you have a good chance of catching everything that happens on the page. On the other hand, it makes things slower. That's just by the nature of these scripts. Doesn't matter if it's Google Analytics, if it's the Yandex.Metrics, if it's HubSpot, if it's Hotjar. It doesn't really matter which one it is. They are working really hard on making these things as fast as possible. But any JavaScript interaction, any JavaScript request, or any JavaScript resource that needs to be attached  

#### [0:21:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1290) |  does make things a little slower, and

sometimes a lot slower. So you want to load them as late as possible in the process. Which contradicts what I just said, that you want to load them as early in the process as possible to catch as much. So you have to be a little on the fence about, hmm, am I more OK with losing some data in terms of analytics and tracking, versus how OK am I with losing some of my performance? And in my opinion, I would load them as late as possible.  

#### [0:22:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1320) |  And I would load them as deferred,

so that basically the entire HTML gets parsed and displayed and the vital JavaScript, the bits that actually serve the content-- if you're using a client-side rendered application-- basically get to work and fire first so that they actually display the application, rather than basically loading the tracker first, but then starting with the application. What this balance is and what it looks like for you,  

#### [0:22:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1350) |  that depends. That's a really tricky one.

There is a brilliant talk by Harry Roberts, who talks about third party JavaScript. Let me see if I can find it real quick. Third party scripts, I think. That should give me a reasonable-- so actually, there's also an article OK, that's nice. The article is from 2018. I'll post it in the chat real quick.  

#### [0:23:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1380) |  And I'll put it in the video

notes for those who are watching the recording. That article talked about identifying these, auditing these, and then discussing with people about the value of these. And what I found that surprised me a little bit is that sometimes you run into-- oh, and here's the talk video, as well. You run into third party scripts in large sites like this.  

#### [0:23:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1410) |  Five, six different analytics trackers in there.

And then when I worked in a company that had that situation, I just "accidentally" removed two. And no one ever complained. So I removed the third one and the fourth one. And no one ever complained. And then we ended up-- NATALIA VITI: I wasn't working there, because I would be the one to complain usually. MARTIN SPLITT: Perfect. So that's the situation that you might find elsewhere, but then  

#### [0:24:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1440) |  not you. If you are on top

of your trackers, then that's not really a valuable alley to go down. But it's tricky. And what we found for-- well, when I say we, at the company I worked for beforehand, before I joined Google, we actually used the Google Analytics-- I would call it API-- to basically fire our events when we needed.  

#### [0:24:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1470) |  Because we basically just wanted to see

basically conversion tracking, what happens when-- how do people navigate through the site? And when do certain events happen, and how often do they happen, and which locations do they usually happen from? And then we basically built our own analytics tracker based on the Google Analytics tracking API. And then we shot these requests ourselves. It is a little tricky. It is heavily under documented, if you ask me. But it might be worthwhile, if that's what you were using.  

#### [0:25:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1500) |  Maybe Yandex has something similar. I'm not

very familiar with their product. But besides that, just load your trackers as late as possible. And when I say as late as possible, as late as is reasonable for what you need the data to look like. Because to be fair, you always have gaps in analytics and trackers. Right? I think I read numbers somewhere between 10% and 30% these numbers will be off. So then the question, knowing that there is such a gap  

#### [0:25:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1530) |  in the data already, is it worthwhile

making everyone wait for these trackers to actually load and fire? That's a question that you would have to answer for your specific case. NATALIA VITI: Thank you. Yeah, that's a good answer. A lot to think about. Many decisions to make. MARTIN SPLITT: I know. It would be great if it would have been a quick answer like, yes, no, maybe. But I mean, the short answer would have been, "it depends."  

#### [0:26:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1560) |  But that's not helpful. Awesome. Do we

have other questions in the audience? Why is it always the leaf blower people? I'm not sure if you hear it on the recording or if you hear it in the live-- like, someone literally five minutes before we started recording decided to start blowing leaves. DAVID SMART: Important update, how are the sheep? MARTIN SPLITT: Oh, sad news.  

#### [0:26:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1590) |  The sheep are gone. They were taken

away on Monday. And it was particularly sad, because it was also raining-- like, torrential rain. And the sheep are standing there looking a little sad, like, baaa. And then they were taken away. And I was like, no! Don't take them away! Leave them be. But I mean, on the other hand, they did a great job. The grass is really short now. So I understand that they have to move on to greener meadows,  

#### [0:27:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1620) |  to greener pastures, I think is the

term that you use in that case, which is sad. But it's good for the sheep, I think. So I have to take one for the sheep. Sad. But yeah, the sheep were fantastic. If you are not aware of what happened with the sheep, check out my Twitter feed. Go back a little while and you'll see what I mean, because there were sheep here in the neighborhood. And I could see them from my home office desk. And now they're gone.  

![](https://i.ytimg.com/vi/R3SQnt_B7go/maxres3.jpg)



#### [0:27:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1650) |  All right. Excellent. In that case, thank

you very, very much. The next JavaScript SEO office hours will be in two weeks. That'll be the-- me and my calendar. Hold on. Hold on. Hold on. Hold on. That'll be Wednesday the 11th. Yeah, press F to pay respect to the sheep.  

#### [0:28:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1680) |  So Wednesday the 11th at 6:00 PM

central European time, we will have the next JavaScript SEO office hours. I will post into the YouTube community thread so that you can drop your questions or join the live recording next time. DEBORAH NORTON: Hey, Martin. MARTIN SPLITT: Hi, Deborah. DEBORAH NORTON: Good morning, Martin. How are you? MARTIN SPLITT: Great, how are you doing? DEBORAH NORTON: Good, thank you. MARTIN SPLITT: Do you have a question? DEBORAH NORTON: I do have a question.  

#### [0:28:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1710) |  And I'm like-- MARTIN SPLITT: Excellent. DEBORAH

NORTON: Is it JavaScript only? Can I only ask JavaScript questions? MARTIN SPLITT: These JavaScript SEO office hours are JavaScript-only questions, yes. DEBORAH NORTON: Oh, JavaScript-only questions. OK. Well, then, I really have to condense my thought to being, I'm thinking about programmers. And I'm thinking about programming. And my conundrum is that when it comes to-- for programmers to start understanding your code--  

#### [0:29:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1740) |  excuse me, understanding SEO. That's my big

concern right now, is having programmers understand SEO concepts. And that's where my question is, is that, when you're talking to programmers, coders, front end people, back end people, and you're trying to explain SEO to them, I mean, they're not getting it. And what I mean by that is that they don't understand  

#### [0:29:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1770) |  the Google guidelines. They don't understand why

we do these things. They don't understand pagination and what it means. And my question is, how can we better explain to them as SEOs? You're a programmer. How can we better communicate between one another so that I can get my thoughts over to a programmer who said, this makes sense. It's come up a lot lately, so I was thinking of your thoughts on that. MARTIN SPLITT: That's a very good question. Thank you very much. That's actually kind of my mission.  

#### [0:30:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1800) |  That's the mission I am on as

a developer and working in the SEO space here. My big mission is to bridge this gap in communication and also teamwork. I've done a bunch of presentations about it, but I don't think we have found the silver bullet to solve these problems. The way that I usually approach it is, depending on your developers, they might already have certain awarenesses about accessibility, or performance, or usability.  

#### [0:30:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1830) |  And then I tie into these things.

Because if they are accessibility-aware, so they are aware that they should build things that do not for default exclude people with different abilities, then I say, consider this like that, that Googlebot or any other crawler is basically a user with assistive technology needs. Because the crawlers are not human.  

#### [0:31:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1860) |  They can't really see. They can't really

understand the text, necessarily. At first, they just need to be able to consume as semantically rich as possible data and then work from there. If they are performance-aware, which most developers at this point are, because we have been talking about this to them for the last couple of years, that performance is a really important factor. And you can say, look, performance-wise, you want to make sure that your website is fast, because that  

#### [0:31:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1890) |  makes users happy, right? And then they

say, yes. And then you say, OK. So then consider that to make users happy, you not only have to be fast-- fast is one aspect of SEO. That's one thing that I'm looking at as an SEO, as well. But also we need to make sure that it shows up in the first place. Because in the end, good developers want to build things for people to use. But if no one finds your thing on the internet, there is no one using the thing. It doesn't matter how fast you make your website.  

#### [0:32:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1920) |  It doesn't matter how accessible you make

your website. It doesn't matter which JavaScript framework you use for your website if no one's ever going there. So what I usually tell them is, like, if I were to ask you a question, like, where can you rent sheep to mow your lawn? What do you do? And then they will probably say, I'll Google it. Or I'll use a search engine to find it. And then you say, aha. So if you were the person to build a website for sheep rental, what do you need to make sure in order for people  

#### [0:32:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1950) |  to actually find your website? Well, that

it shows up in search engines. Yes. That. And that's exactly what I am doing. And that's what I'm really good at. And that's what I'm helping you with. You can focus on the technical side of things. But please, please, please talk to me so that I can test the things you build and show you what you need to be addressing if there's something going wrong in terms of us not showing up in search engines. And then if they are understanding that, if they get the point that, ah,  

#### [0:33:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=1980) |  this is one more requirement-- because developers

work with requirements. DEBORAH NORTON: Yes, they do. MARTIN SPLITT: Right? They get a requirement like, this website has to load in 1.5 seconds on this specific connection. It has to be-- our editors have to be able to upload products in the background. It has to do this, it has to do that, it has to be mobile-friendly, whatever. One more requirement should be, it has to be visible in Google Search, or in search engines in general. I'm just coming from the Google Search perspective. But it should be visible and standing out  

#### [0:33:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=2010) |  enough in search engines. And then they're

like, ah, OK, so that's a requirement. I don't know how to make sure that we fulfill this requirement. And you're like, well, conveniently, that's exactly what I can do. Let's work together on making sure that we show up. DEBORAH NORTON: Oh, I love that approach. That is amazing. MARTIN SPLITT: That usually works. DEBORAH NORTON: That's a great one. And that's for the conscious developer who is on the high end spectrum.  

#### [0:34:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=2040) |  What I'm seeing in the industry right

now is that the clients that I'm working with are working with people to just get a website up. And so a lot of them are on do-it-yourself platforms, or they're on customized CMS systems that have only been evolved for half a year. And they're buying into it. And that's the stumbling block. And so I think it's a two-fold piece. We're making developers aware of this.  

#### [0:34:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=2070) |  We also are needing to make clients

aware of this on the small side. Because they're not sure. They're building on systems and they're putting all of this effort and money into it. And all of a sudden, it's blocked. Or it's not even visible at all. So these are the hurdles we're trying to get around. MARTIN SPLITT: Yep. DEBORAH NORTON: I'm so super-psyched that you're doing this. And it's 5:30 in the morning if I sound a little jittery. MARTIN SPLITT: Oh, wow. DEBORAH NORTON: Eastern coast time. But thank you for this.  

#### [0:35:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=2100) |  And I appreciate this. I will always

listen in, because that was the best answer. MARTIN SPLITT: Thank you, Deborah. Thank you a lot for the question. Thanks for being up so early, as well. See, this is exactly why I swap the times, so in two weeks it will be a lot later, actually. I think it will be like eight hours later. So that then is a little friendlier time for you. So every second week you don't have to get up this early to get your questions in. DEBORAH NORTON: Fantastic. And I'll sound more awake. Are you going to be posting this on Twitter, your Twitter feed--  

#### [0:35:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=2130) |  that's how I found it-- to notify

us when this [INAUDIBLE]?? Super. MARTIN SPLITT: Yes. You can also hop into youtube.com/goog lewebmaster/community. And there's all the office hours, so the ones that John does. There's basically a posting, drop your questions here. And then you can drop the question. And also we post the link to this recording in these threads. DEBORAH NORTON: Thank you so very much. Have a beautiful day. MARTIN SPLITT: Thank you very much. Likewise. Have a wonderful morning. Wow. So we are spanning pretty much the entire world now.  

#### [0:36:00](https://www.youtube.com/watch?v=R3SQnt_B7go&t=2160) |  We have Australia on the one end.

And we have the US on the other. Wow. That's amazing. Sweet. Any further questions? 5, 4, 3, 2, 1. All right, ladies and gentlemen, it has been a fantastic time. Thank you so much for joining the live recording. Thanks everyone who dropped questions into the YouTube  

#### [0:36:30](https://www.youtube.com/watch?v=R3SQnt_B7go&t=2190) |  thread of questions. We'll see each other

again in two weeks. Stay safe. Stay healthy. Have a great time. Bye bye. DEBORAH NORTON: Thank you. MARIA AMELLE: Bye, Martin. MARTIN SPLITT: Bye, Maria. DEBORAH NORTON: See you. MARTIN SPLITT: Stop recording. Bye, Deborah.  