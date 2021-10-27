[![JavaScript SEO office hours April 29th, 2020](https://i.ytimg.com/vi/nZO0OVN37aY/maxresdefault.jpg)](https://www.youtube.com/watch?v=nZO0OVN37aY)

## JavaScript SEO office hours April 29th, 2020

This is a recording of the JavaScript SEO office-hours hangout from April 29, 2020. These sessions are open to anything around SEO for JavaScript sites.



Watch out for new sessions, and add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



Feel free to join us - we welcome webmasters of all levels!



#### [0:00:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=0) |  MARTIN SPLITT: Hello and welcome to another

JavaScript SEO Office Hours hangout. I'm pretty happy to see that there's a few people here. I'm Trying to do these hangouts now weekly with an alternating time zone. Basically like an APEC friendly time zone and more North America friendly time zone-- North and South America, actually. Doesn't matter. So point being, I'm really happy to see a few people in the hangout today as well. And we have a few questions.  

#### [0:00:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=30) |  We have very few questions, so I

think I'll start with the submitted questions and then we'll take questions from those who are with me in the hangout. So the first question that we got is the question that I have is JavaScript single page apps. I think that's what they mean. Do they require hardcoded links? What does that mean, hardcoded links? I mean, OK, we've built a 17,000 page e-commerce website  

#### [0:01:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=60) |  and Google cannot crawl the pages. They

will not index them. The thing here is as far as I can tell, I'm not sure what you mean by the web developers need to know. Web developers do know because it's in our documentation. And as long as you generate links that are proper links, and I mean a tags with an href that has a URL that we can crawl, your discovery will not be impacted.  

#### [0:01:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=90) |  Now again, links are important for discovery

of content and allowing us to understand the structure of your site. With 17,000 pages, as far as we're concerned that's not a huge site. So that should not be a problem. You can also use the site map to submit the URLs to us, but that's an optional additional measure of making sure that we can discover pages. Site maps like the site structure, so having links is very, very important to allow us to understand your site  

#### [0:02:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=120) |  structure. But I would reiterate, if you

use JavaScript to generate the links, if you use client side rendering and that generates all your HTML, that's not a problem. As long as it is proper links, and there's actually on this channel later today, which is April 29, I believe, 28? 28. 28? 29. In April 29, we have this additional video  

#### [0:02:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=150) |  that webmaster conference lightning talks on JavaScript

and links. Very, very basically said as long as you generate proper HTML links, we'll be able to crawl them. The HTML links have to have crawlable URLs, and there should not be any other technical issues that prevent us from indexing or rendering the page. You can test that with a URL inspection tool. You can test that with the mobile-friendly test. You can test that with the rich results test. Wherever you see the rendered HTML,  

#### [0:03:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=180) |  if your links are in the rendered

HTML then we'll see the links. And then we can crawl and potentially index the websites that are linked. And yeah, I mean, you have to make sure that there's no other technical problems like accidental no index, or robots.txt blocking off certain URLs. And if that's not the case, and if you're not preventing us from crawling, rendering, or indexing, then everything will be fine. So that's that.  

#### [0:03:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=210) |  If you want to elaborate on the

question, that's fantastic as well. You can also send that in with more details in the next-- there's like a post on youtube.com/goog lewebmaster/community for the next JavaScript SEO office hours if you want to elaborate on that question. Second question we've got is how to do a client-side 301 redirect. I have a static website, and I want to do a client-side 301 redirect. How to do this in a way that it does not affect SEO? A redirect always affects SEO.  

#### [0:04:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=240) |  Because what it does is it tells

us, especially if it's 301 or a 302, this page no longer has content. Instead you should go there, and then it just takes us somewhere else. So this there's always an effect in terms of SEO because that means that the page that we originally indexed is no longer having content. It is now just taking us somewhere else. A 301 redirect means an HTTP status 301 permanent redirect.  

#### [0:04:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=270) |  You can't do that client side, because

an HTTP status is sent from the server. What you can do client side, though, is, especially if you have a static website and you don't have access or control over your web server. Optionally, if you have access to your web server, configure your web server for a specific URL in htaccess files or in whatever you're using to configure your web server.  

#### [0:05:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=300) |  You select I want a 301 redirect

to this other URL when this URL has been requested. That's how 301 redirects work. If you can't do that, and you do only have access to the client side of things-- meaning JavaScript-- then you can use window.location.href and then give it the new URL, and then that's also a redirect. That's not a 301 redirect. It is a JavaScript redirect. That also works.  

#### [0:05:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=330) |  It has no obvious downsides. It doesn't

really matter to us, but it requires that the crawlers that you care for understand JavaScript. If you have a crawler that does not understand JavaScript then that won't work. You can still use the meta refresh tag in your HTML. That would also probably work for search engines or crawlers that don't understand JavaScript. But for Google search, it doesn't really matter.  

#### [0:06:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=360) |  You can use a JavaScript redirect. You

can also use a server-side redirect if you want to have a 301 redirect. But a 301 client-side redirect is per definition impossible because a 301 is the HTT status code that comes from the server. So if you're not changing your server, you can't really have a 301 redirect on the client side. That is that. And that were the two questions that were submitted on YouTube. As far as I can tell, we don't have more questions submitted by our YouTube.  

#### [0:06:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=390) |  So any questions from the audience? Now's

your time. TONY MCCREATH: Hey, Martin. You can hear me? So I'm using a framework that does bundling. So you got one big JavaScript file, and the core framework part of it is 1 meg, the bundle is 1.7 meg, and what I'm saying is it seems to be hit and miss if Google can actually  

#### [0:07:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=420) |  render that page. It seems to kind

of go, that's just too big. Don't want to bother with that anymore. And it's kind of-- sometimes it works, sometimes it doesn't. Is there any-- oh, and this company who do the framework are working on a way to shrink it down. MARTIN SPLITT: That is amazing. TONY MCCREATH: So are there any other ways to kind of somehow try and get around it?  

#### [0:07:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=450) |  Maybe not bundling-- so it's lots of

smaller files, or-- MARTIN SPLITT: I wouldn't do that. So the thing is I'm guessing when you say like sometimes it works, sometimes it doesn't, you're seeing that in the testing tools, right? TONY MCCREATH: Yeah. So I'm seeing where you get the error thing going, fail to load file, fail to load file. MARTIN SPLITT: Let me guess, it says other error. Is that the reason for it, other error? TONY MCCREATH: Yeah, I think so. MARTIN SPLITT: Yeah, so the good-- so here's  

#### [0:08:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=480) |  the good news and the bad news.

The good news is you don't have to worry too much about that because that comes from the fact that the testing tools are a lot less patient than the actual indexing and the rendering infrastructure. Because we can't really use a cache. We're usually avoiding caching in the testing tools because we want to actually give you the result for the latest version that you actually have on your server. That comes with the downside of as the testing tools use the actual infrastructure that Googlebot would also use,  

#### [0:08:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=510) |  we might get scheduled a little later.

And that is actually relatively independent of the file size, as well. We might just be scheduled for fetching later, and then the tools say like, we can't wait an hour, or half of an hour, or 20 minutes, or 10 minutes. We need the result now. So then they basically just time out and give you this unfortunate other error. That's not great.  

#### [0:09:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=540) |  We are aware of that we are

working on solutions, or we are trying to figure out what we can do to alleviate the issue a little bit. But generally speaking, the indexing infrastructure is a lot more patient. That being said, so while you shouldn't exactly get worried about it, it is annoying and testing. But it wouldn't affect the indexing and rendering performance or anything of that. That being said, 1.0 0 megabyte and 1.7 megabyte, that's 2.7 megabyte, that doesn't fit on a floppy disk.  

#### [0:09:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=570) |  That's obviously-- [LAUGHS] That's always how I

think about these things. It's like, look, if your thing requires me to have 14 megabytes transferred over the wire, that means that you are literally shipping 10 floppy disks to me. I've played entire and fantastic games on 10 floppy disks, so why is your website that large? But besides that, so the bundle size is definitely not fantastic for user experience because you are downloading lot of stuff  

#### [0:10:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=600) |  that you probably might not need. And

that's something that, as you said, your framework provider can help you with. There are ways of doing things-- depending a little bit on what the framework is and what the tooling looks like, you might have options to do what's called tree shaking. So if you are in charge of the application code, you can usually use tools like wet Webpack or rollup to actually analyze what of the dependencies on the framework is actually being used and removing that from the bundle. So that everything that you don't  

#### [0:10:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=630) |  use in the framework on the application

code, you would not have to ship. Which is super helpful. But that really depends on the framework and the tooling setup that you can get to, and how much control you have over the application code that you're using. So tree shaking is a great way of reducing bundle size. I would not unbundle for the simple reason that when you have a lot of network round trips, and the browser has a maximum number of simultaneous network  

#### [0:11:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=660) |  connections that it opens to a single

host. So let's say you have it all on a CDN, maybe cdn.example.com/main.js, app.js, bundle.js, framework A, or like, framework part 1, framework part 2, framework part 3, then they would have to be staggered because at some point it's too many requests due at the same time. So that would also slow things down. So actually, bundling is a good idea. But that being said, most frameworks  

#### [0:11:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=690) |  have an option to do what's called

code splitting. I know that sounds paradox now. Because on one hand, you want to have a bundle so that you don't have too many requests separately. But then again, you don't want to have one gigantic bundle, because then you are basically downloading an entire application code for every single page that you are getting. Even though you can cache that, it's still a lot of code to download for the initial visit for the first visit. So what people tend to do is they tend to split the bundle a little bit, like oh, we have,  

#### [0:12:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=720) |  I don't know, some route-- like our

home page needs-- or our landing page needs this much code, and then there's all the other code. So we are splitting this out and downloading just this bundle when you have your first visit. We download the framework bundle, and then the framework bundle gets cached. We need to have that on every page anyway. So we are getting this one cached, and then we have the bundle only for the home page. And in the background we load all the other bits and pieces.  

#### [0:12:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=750) |  Or if you quit in between and

jump to the next thing, then we would download the next bundle. And then basically you are using the cache the most optimal way, and you're breaking it down into reasonable bundles. But completely unbundling is not the greatest thing to do because of the amount of HTTP requests that you have. HTTP2, or H2, makes that a little better because it can actually multiplex over the same connection. But A, Googlebot does not support HTTP2 yet. And B, not everyone has a HTTP2 compatible browser version  

#### [0:13:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=780) |  probably. Or there might be other issues,

especially on high latency connections which are basically-- and packet loss affected connections which are mobile connections. HTTP2 can also be a little bit of a performance bottleneck. So try to figure out if your application code and/or framework provider support tree shaking. That's the biggest factor that will reduce the size.  

#### [0:13:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=810) |  And maybe also code splitting along the

routes. If you search for tree shaking and code splitting, you will find a bunch of articles on how other frameworks do that. And I'm pretty sure if you have a commercial provider behind the framework that you are using, then they should be interested in actually getting that shipped, as well. TONY MCCREATH: Yeah, they are aware of it. I think pretty much that tree shaking's out the question with their design. MARTIN SPLITT: Oh, OK.  

![](https://i.ytimg.com/vi/nZO0OVN37aY/maxres1.jpg)



#### [0:14:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=840) |  TONY MCCREATH: So yeah. They're looking at

the idea of code splitting. It's a very GUI type. It's like grids and charts. So there's a lot of stuff in there. So I think they've got to kind of give you checkboxes-- do you want charts, do you want this, do you want that? [INTERPOSING VOICES] MARTIN SPLITT: That's the approach that jQuery took, I think. TONY MCCREATH: Yeah. It's actually got jQuery under the hood, as well. MARTIN SPLITT: Oh, OK. [LAUGHTER]  

#### [0:14:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=870) |  TONY MCCREATH: It uses-- you've got A

choice OF something like five different frameworks that IT SITS on top of. Hence this massive thing. Another symptom I saw was so I'm actually creating structured data using the package, AND what I'm seeing in the search console is this [INAUDIBLE] data appears, and then disappears, and comes back, and goes in the enhancements section. Implying that-- this is the intermittent thing  

#### [0:15:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=900) |  that I'm thinking of. Just getting RAM

to it. Sometimes it's not. [INAUDIBLE] debug, because it could be-- MARTIN SPLITT: That is hard to debug. That's an interesting point. I'm not exactly sure where and when we are expecting the information for the enhancements report. This could be potentially that we are putting it or pulling it from the wrong spot in the pipeline. A short-term workaround while your framework provider figures  

#### [0:15:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=930) |  out how to try to get that

solved is potentially considering dynamic rendering. That's an option. Because then you would work around that JavaScript bundle issue. But I'm not sure if that's a good idea because dynamic rendering, A, it's a workaround. B, it's not a non-significant investment, I would say. And C, It is additional complexity. So you have to think very carefully if that's a problem. I would say as long as you're not  

#### [0:16:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=960) |  seeing general issues with like impressions or

performance and such, then I would probably not change much. Because then additional complexity is just risky. You're importing risk for certainty that does not have a visible effect. If you are seeing issues with the performance and such, then maybe it's worthwhile thinking about it while your framework provider figures out how to reduce the bundle size. But generally speaking, the indexing pipeline  

#### [0:16:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=990) |  is quite patient with situations like this.

And 2.7 megabyte is not a size where I would start to cry and scream. If you would have said 10 megabytes I'd be like, well, now we're definitely in hot water. But 2.7 megabytes shouldn't be a problem on our side except for the testing tools. TONY MCCREATH: Yeah. And I'm trying to do as much content. So [INAUDIBLE] on stuff server side  

#### [0:17:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1020) |  so that it's not reliant on the

JavaScript that builds all the fancy tools. The content [INAUDIBLE] straight out. Hopefully the [INAUDIBLE] danger at some point. MARTIN SPLITT: That's also always an option to say like, OK, we're trying to get everything that is content and landing pages, we get that as static as possible. And we only look at the framework for the pages that are really dynamic. That's a solution that a bunch of people have successfully implemented, as well.  

#### [0:17:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1050) |  TONY MCCREATH: Cool, cheers. MARTIN SPLITT: You're

welcome. Next question? Ding, ding, ding. KAIXI LUO: Hi, I had a question. I just checked last week, and even though I think you said that the new evergreen Googlebot is working like 100% since the beginning of this year.  

#### [0:18:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1080) |  I checked my access logs, and 80%

of the requests on Googlebot track quest, I still show the user agent with Chrome 41. Is that something to be expected, or-- MARTIN SPLITT: No, that's not something to be expected. I would check if the IP's coming from Google. Because as far as I'm aware, we are not using the 41 string. We do have different user agent strings, that's for sure.  

#### [0:18:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1110) |  But the Chrome 41 string is unusual.

I would not expect any service from our side to still use that one since April 2019. So that's like a year ago. If you're seeing that, check if the IP range resolves. If you do like a reverse DNS lookup, it should resolve into a workable namespace. If it doesn't, then it's a fake Googlebot. That happens. Some people are like-- or some services that are pretending to be Googlebot, but they're not Googlebot,  

#### [0:19:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1140) |  then they haven't updated their user agent

yet. If you are seeing a Chrome 41 Googlebot coming from Google, then it would be some service. But I'm not aware of any service that would be using that string anymore. I know that we are still having some services like the Read Aloud, for instance, that uses a completely different user agent, but basically I know that we can still  

#### [0:19:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1170) |  crawl without saying that the Chrome version,

there's a few Googlebot strings that we have on our website. And one does not have a version information, and that still happens. But the 41, that would surprise me if we're still using that one. KAIXI LUO: Yeah that surprised me, too. Because we have-- we are medium sized website, but we cover around--  

#### [0:20:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1200) |  we can have around a million requests,

or even more. Up to 10 million from where I work every day. So I check on it. At least three quarters were using this old version. I don't remember it was 41 or 42, but it was not the 70 or 80 something that's the current version. I will check again and let you know.  

#### [0:20:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1230) |  MARTIN SPLITT: Yeah I mean, fundamentally just

make sure that it is an actual Google IP address. If it does come from a Google address, it wouldn't be the regular search part. Then it would be something strange, and I would have to figure out what exactly that would be. But I don't think that we are using this still for anything in search. Not that I'm aware of. I think there's like a few services that  

#### [0:21:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1260) |  used to use that string and weren't

actually rendering, and then it doesn't really matter. If it's not rendering, it doesn't truly matter. But I'm not aware of anyone still using this. I would have to research this a little bit, but generally you can rely on Googlebot to be evergreen. KAIXI LUO: OK, thank you. MARTIN SPLITT: For search, at least. I don't want to comment on other Google products. KAIXI LUO: I check because we were having our first client-side trend or page,  

#### [0:21:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1290) |  and I wanted to make sure that

Google could actually render everything. So yeah. MARTIN SPLITT: I could imagine that maybe like another Google product like Google Ads or something. If you use Google AdSense or AdWords, they might still use the old string. That's possible. KAIXI LUO: Thank you. MARTIN SPLITT: But not Google search. You're welcome. All right. Oh, there it comes through the chat.  

#### [0:22:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1320) |  Hi, Maxine. Infinite scroll in Google-friendly ways.

Yes. Oh, you have a link for me to check. That's nice. So let's have a look. So I'm not looking at the screenshot. I'm basically trying to figure out how the page is supposed to [INAUDIBLE]..  

#### [0:22:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1350) |  So let me actually open the website

first, and then see if I can find something that is content that would be loaded by infinite scroll. Actually, you know what? I can probably share my screen real quick to show you what I'm doing. Because it's probably a little boring to just hear me go like, blah, blah, blah. I want a specific Chrome tab, and I want-- actually no, if I do a specific Chrome tab, then you're not seeing when I switch tabs. That's also not great. OK, in that case, I will share with you--  

#### [0:23:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1380) |  can I share just Chrome? A window.

It says a window. That's good. I think I want this window to be shared, and now you should probably see yourselves, which is odd. But here we go. OK, so here we have the website, and we can see that it's quite long already. And it does seem to be loading additional content as I scroll. Let's see.  

#### [0:23:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1410) |  I try to grab something from as

far down here as possible. OK, now that definitely loaded additional content. So are we seeing NIU [INAUDIBLE]?? I'm not sure what that means. My Russian is not very good, but I'll try my best. OK, now we go to the mobile-friendly test. In the render of HTML, I'm looking for these characters.  

#### [0:24:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1440) |  And it doesn't-- I'm not sure if

that jump meant that it actually saw something or not. So weird not seeing this part here. That's for sure. Are we seeing something else like this, try this one. Nope, wrong window. Actually, wrong tab. So we can definitely see up to here, and it looked like we couldn't see the other string that I was trying.  

#### [0:24:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1470) |  So you get a feeling for what

we are having in the content, and what we are not having in the content. If you are exposing this to other URLs, then that's not a problem. That's generally not an issue. And it looks like some part of the infinite scrolling lazy loading did work, and some of it might not have worked. You can also check here. If you are using JavaScript to load additional content, then you would see--  

#### [0:25:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1500) |  well, this is all not relevant-- you

would also see if we are doing the actual API call to fetch the additional content. I'm not sure that all of this looks like it's not grabbing additional content, but maybe I'm just missing something here. So you want to make sure that we are loading all the content, and that the content is actually visible in the rendered HTML. If it is in the rendered HTML, that's fine. Having multiple H1's is not an indication for a problem,  

#### [0:25:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1530) |  and it's not an issue on our

end either. So that's a question of how you structure your content. If I'm searching for H1 headlines, then we'll see like we have one, two, three, four, five, six, seven, eight, nine, 10 ish. Or actually no, hold on. I think we're at-- no, no, no, no. We are jumping in between the thing. So we have-- no, we have two.  

#### [0:26:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1560) |  These are two independent headlines. [NON-ENGLISH SPEECH]

and [NON-ENGLISH SPEECH] something something, so how the industry something something. So those are the two headlines that we definitely see. Everything else is-- if you are looking for more than these two H1 tags, then we're not seeing them. Oops, no. OK, I'm searching for a random Cyrillic phrase.  

#### [0:26:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1590) |  Let's try this again. And if I'm

going in here, how many H1 tags do I see? Say inspect. Come on, inspection tool. Come with me. Be nice. So if I'm now asking for all the H1 tags, we also get two. So as far as I can tell, that seems to be fine. There's two H1 tags. We're seeing them in the browser. We're seeing them in Google, so we are seeing your H1 tags.  

#### [0:27:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1620) |  And again, having multiple H1 tags is

not a sign for a problem. That's acceptable, as far as we can tell. OK, now stop presenting. So you would have to check if everything from the content that you care for is actually in the rendered HTML. If it is, you have implemented this successfully. You can use the intersection observer to implement infinite scroll and lazy loading.  

#### [0:27:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1650) |  You can make sure that you have

endpoints where your server creates different pages so that you give us a pagination, as well. That's a way of implementing this. You can submit different pages in site maps. That also gives us a hint that, oh, there's more content that we might not have seen on the home page. So there's definitely ways of doing this. And the fact that there's two H1 tags does not mean that there's a problem per se. All right. Hope that answers the question, Maxine.  

![](https://i.ytimg.com/vi/nZO0OVN37aY/maxres2.jpg)



#### [0:28:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1680) |  More questions? TONY MCCREATH: The double [INAUDIBLE]

in the console line there, was that-- MARTIN SPLITT: Oh that's the helper. Yeah, so Chrome DevTools have-- it doesn't always work. It stops working when the website actually has jQuery installed, or like another giant library that overrides this. But by default if you go to any static HTML page,  

#### [0:28:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1710) |  you go to like example.com, then the

DevTools give you a bunch of helpers, which is like super nice actually. I'll show you real quick again. I want to share this window. So if I were to go to example.com, let's say, because that's a really nice and simple website. And I go to inspect, then a few things happen in the console automatically. So I have dollar, which is short for document querySelector. It's just a lot to type. So whenever I do quick debug, I just try this first.  

#### [0:29:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1740) |  And then I can ask for H1

elements. And then you see as I do that, in the page I get the overview of what the page looks like, which is quite cool. Oops, that's not what I wanted. You can also select an element here, and then go to the console. And then you can type $0, which is the element that you'd selected in the Elements tab, which is also quite handy. Because then you can do all sorts of things  

#### [0:29:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1770) |  like text content, hello. So you can

very quickly debug with these helpers in the developer tools, and this is just the shorthand for document querySelectorAll, which also is a lot to type. So this gives you all elements that match a certain selector. So in this case, I think we have two paragraphs, for instance. And then you can inspect what kind of paragraphs you actually have here.  

#### [0:30:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1800) |  And then work with that. So what

I did is I basically just asked document.querySelectorAll H1. so to see how many H1 elements, and which H1 elements we actually have on the page, which is a cool way of quickly debugging that. If you're interested, if you search for, I think it's called DevTool tips or something-- DevTools tips or something like that.  

#### [0:30:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1830) |  DevTips, that's what it's called. There's a

GDE called Umar Hansa who has like an entire course on developer tools tips and tricks. There's also other articles that explain all of these helpers that developer tools and Chrome provide you with. It's quite nice. You have a bunch of stuff that you can do in DevTools if you ever need to debug things. OK, more questions?  

#### [0:31:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1860) |  It does. Yeah, Maxine, it looks two

articles get rendered at once, but it matches what the browser does. When I opened it in the browser, I got the same amount of H1 tags. So to me it looks like Googlebot does exactly what the browser does when it comes to that. Maybe we don't render as many articles because there might be something in the infinite scroll  

#### [0:31:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1890) |  implementation where we don't really follow through

with all the other articles that you get when you scroll in the actual browser. Because Googlebot doesn't scroll, but we definitely load a bunch of content. So as far as I can tell, the content seems to be there. And the fact that you rendered two articles is not a problem for Google. Especially if these articles have links to their own page, then we would probably consider their individual pages as well, and might rank that in search rather than the home page.  

#### [0:32:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1920) |  So that's not per se an issue.

I mean, for instance, e-commerce shops might have an entire category page with lots of products. That's not a problem. You just don't have products, you have articles. That per se is not an issue. OK, more questions?  

#### [0:32:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1950) |  SPEAKER: So if nobody ask, I have

a little question. So we have the problem again with some level things. So the Google search console say to us, one such page is duplicate content, but for another-- like another one, but both page get separated content. But this is loading by JavaScript AJAX.  

#### [0:33:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=1980) |  So I don't know what we do

wrong, or is the problem with the patch is too slow, and the Googlebot read it later? It's not with all pages, it's with some pages. MARTIN SPLITT: Have you tried rendering them through one of our testing tools and looked at the rendered HTML? SPEAKER: Yes. MARTIN SPLITT: And they look completely different in the testing tools? SPEAKER: Yes. I can send you links if you like. MARTIN SPLITT: That would be fantastic to have a look,  

#### [0:33:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2010) |  because that sounds like a-- SPEAKER: So

this is the tool [INAUDIBLE].. MARTIN SPLITT: [NON-ENGLISH SPEECH] OK. SPEAKER: So yeah. MARTIN SPLITT: So if I have a look at this, [INAUDIBLE] OK. Let me go to mobile-friendly text, for instance.  

#### [0:34:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2040) |  So I'm guessing the other search pages

don't have that problem? It's not that everything-- SPEAKER: Not everything. We have, let me not lie, over 500 pages, and only 20 pages have the problem also. But with the same, with stop else canonical, [INAUDIBLE] canonical. MARTIN SPLITT: So what happened is somehow-- and I don't know exactly how-- somehow, we  

#### [0:34:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2070) |  have seen similar content, let's put it

that way, and decided that, like, one thing is a duplication of the other thing. And then we have selected, I think, the stop one. If you said that that's the canonical now, then we have decided that that's the best match for this. That can happen. Especially because you're using JavaScript, that is possible that there was a problem with fetching the JavaScript at some point. And that's why we decided that-- like,  

#### [0:35:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2100) |  imagine that for some reason we couldn't

fetch the JavaScript. We couldn't load the results whatever, or they were empty results for a while. And then we're like, OK, so this is an empty search results page, this is an empty search results page, and this is an empty search results page. They're all the same, so we're just like picking one to keep and the other ones we dedupe. If that was the case, if there was a glitch that led to that, eventually we would probably recover. You can also resubmit them for indexing, and then we might revise the discussion.  

#### [0:35:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2130) |  Actually, we have John in the call.

I've seen you, John. You did not escape my attention. Is there anything else you would have to do to fix this dedupe issue if it's an issue? JOHN MUELLER: I didn't pay attention. Sorry. [LAUGHTER] MARTIN SPLITT: So sorry. I didn't want to call you out on this. I was like, this is a common problem people have, so maybe John has something that I forgot about to mention. Assuming that you have multiple pages loading search without--  

#### [0:36:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2160) |  or not search without, you have a

catalog of different categories. And for different search terms in the category-- sorry, for different categories, basically, in the catalog, you're using JavaScript to load the products. And we have decided that they are all duplicates of each other, and we have selected one as the dup cluster lead. So I think that sounds like we had an issue rendering at some point probably. Maybe we couldn't fetch the JavaScript or something. And now it works, and now it gives you different contents.  

#### [0:36:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2190) |  So I guess eventually we would probably

figure that one out. Or you can request indexing to fix that, right? JOHN MUELLER: Yeah. MARTIN SPLITT: Relatively small number. JOHN MUELLER: I guess it depends on where the issue came from. So what I've sometimes seen is that we learn that particular URL parameters are irrelevant. And if we learn something like that,  

#### [0:37:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2220) |  then it tends to take quite a

long time for that to be unlearned again. So if you think that that's the case, like if you have multiple URLs that all use the same parameter names, and you're noticing that different parameter values all lead to the same canonical, then one thing you could do is to kind of work around Google and change the parameter name. So if you have something like, I don't know,  

#### [0:37:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2250) |  q equals, just take like qu equals,

or s equals, or some other letter. And then essentially we'll look at that and say, oh, it's a new type of URL. We don't know about this parameter, and we will need to analyze to see, is there actually unique content per parameter value here? And if we find that there is, then we will index it normally. Whereas if you keep that parameter and we've kind of learned that the parameter value is  

#### [0:38:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2280) |  irrelevant, then it's going to take a

really long time for us to reconsider that. SPEAKER: OK. MARTIN SPLITT: And I notice that you have a language parameter in the URL, and I'm guessing, like, the language parameter doesn't make that much of a difference. So maybe that's where we fell over. That's a possibility. SPEAKER: We give Google the link without language parameter. So Google get only text search question mark  

#### [0:38:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2310) |  q equals stop, for example. And I

have copied this from my [INAUDIBLE],, and so I'm setting to German so you get the language parameter. But matter of fact, extension question to this. So we want to change something on our server, and at Rendertron. If at Rendertron and some of the [INAUDIBLE] get  

#### [0:39:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2340) |  recrawled, do we have the problem again,

or it's not so important more if we add to the Rendertron server to redirect Google Rendertron rendered version? I hope you know what I mean. MARTIN SPLITT: I know what you mean. So Rendertron, like dynamic rendering in general is a workaround, and I would only incur this additional complexity if I really have to.  

#### [0:39:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2370) |  And I say that as the Rendertron

maintainer. So I would not do it if I don't really have any really good reason to do that, and I don't think that this-- if is the reason why you add Rendertron, I wouldn't. Then I would do what John just said and probably like reconsider maybe renaming the parameters or something. But assuming that you set up Rendertron correctly, and it doesn't fail, and generates static HTML  

#### [0:40:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2400) |  for Googlebot, then that won't incur the

problem again. It might incur different problems depending on what the rendered output from Rendertron looks like, but that specific problem that we can't load your JavaScript would not happen again. Because Rendertron strips the JavaScript from the page. SPEAKER: So the main reason we add Rendertron is for social sharing. MARTIN SPLITT: Yeah, OK. I understand that. 100% understand that. I've been in that position. SPEAKER: So if you use it for social bots, so we can use it for Googlebot.  

#### [0:40:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2430) |  And maybe we have no problem. MARTIN

SPLITT: Sure. That's a possibility. Just make sure to make Rendertron and use a cache, because Rendertron makes things a lot slower if you're not using caching. And [INAUDIBLE] the cache every now and then. OK, cool. SPEAKER: Perfect, nice. Thank you. MARTIN SPLITT: You're welcome. Any other questions? I think, like, that's really weird. I saw a question being submitted on YouTube and now it's gone again, or at least I'm  

#### [0:41:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2460) |  not seeing it anymore. And I'm like--

ah, here, ah ha. So someone submitted something to YouTube, hi, I have noticed a significant drop in the FAQ listings in the two past month. Here's a screenshot. That's why I shouldn't just like read things out as I go along because that's not a JavaScript question. That's a question for the regular office hours. But basically saying, so they added a FAQ markup to their page, and they're seeing  

#### [0:41:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2490) |  a significant drop in the FAQ listings

in the past two months. The fact that you add the markup does not guarantee that you get rich results in search. So it can be that another page has better content for these specific questions. It might be that our algorithms have decided to just show less FAQ markups for the queries that you have markup for. It doesn't affect rankings.  

![](https://i.ytimg.com/vi/nZO0OVN37aY/maxres3.jpg)



#### [0:42:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2520) |  It does affect visibility in the sense

of you don't get the rich result snippets if you're not showing up with rich result snippets. Why am I saying rich result snippets? Rich results. And also, the screenshot that you shared, it doesn't look like a super unusual large drop. It's just dropping-- it went up a little bit. It went down a little bit. That seems to me to be the regular change in algorithms over time. I wouldn't worry too much about that.  

#### [0:42:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2550) |  OK, now coming back to JavaScript questions

anyone? Another like 12 minutes. TONY MCCREATH: Could you explain a bit more about how Rendertron works? Is it a wrapper around Puppeteer type thing? MARTIN SPLITT: Yes. Rendertron is a wrapper around Puppeteer, in fact, and it has two components. It has one component that is universally useful  

#### [0:43:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2580) |  if you want to use Rendertron, and

one that is specifically made for Express.js web service. So the way that Rendertron works is, actually, again I'll just show you. Because we have documentation that has diagrams, which is nicer to explain them than just waving the air in front of me. Because I do that. I notice that I wave my hands quite a bit. Here we go. So in our such documentation, in the guides, in the implement dynamic rendering guide.  

#### [0:43:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2610) |  So basically, it is one way to

implement dynamic rendering. Dynamic rendering means your server looks at the user agent that comes in. If it's a user browser, like Firefox, Edge, Opera, or regular Chrome, then you would just run your JavaScript and produce the JavaScript. That's this part of the diagram here. So the first part here where your server sees a regular user requests that information. So I give it the single page application  

#### [0:44:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2640) |  or whatever JavaScript it needs to actually

fetch the content. The JavaScript to load more content in, or to populate search results on this category page, or whatever. Whereas if it detects a user agent that is from a crawler-- like Googlebot, Twitter, Facebook, any of the social media bots-- then it would-- instead of just sending the response back, it would proxy back to a rendering solution.  

#### [0:44:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2670) |  And then the rendering solution takes that

URL, opens it in a browser, waits until the page has finished rendering, and then makes a snapshot of the HTML and sends the static HTML back to the web server. And the web server then sends that back to the bot or crawler that requested it originally. Rendertron is a thin wrapper around Puppeteer. It basically creates two end points-- one for a screenshot, one for rendering. We have a demo instance, as well,  

#### [0:45:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2700) |  that even is a web interface just

for the fun of it. So I can go to a website that does require JavaScript to do a bunch of stuff, and then I can, for instance, take a screenshot. OK, I can take a screenshot, but then the demo instance does not do screenshots. Wow OK, the demo instance doesn't do anything. I know what's the problem. My certificate went down. But that's OK because it's an experiment page anyways. So here we go. So this uses a bunch of JavaScript  

#### [0:45:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2730) |  to actually do all these tests. But

if I check the page here for any script tags, and we will see that we don't have any JavaScript on this page. So this is just static HTML rendered by a headless Chromium through Puppeteer. And that's the main component of it. So you have a server there which gets a URL out and then produces static HTML that you can send back. The second component is the Express.js middleware. If you are using Express.js as your web server  

#### [0:46:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2760) |  or as your application server, then you

can use Rendertron middleware to actually get a way to integrate Rendertron into your web server. If you are using Apache, or Nginx, or any of the other service IIS, then you would basically configure it like a reverse proxy. That's Rendertron. TONY MCCREATH: Does it only execute script text, or does it execute--  

#### [0:46:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2790) |  for example, would it be a problem

if it did the Google Analytics reference, that sort of thing? MARTIN SPLITT: What do you mean? TONY MCCREATH: So you get a script tag to fire a page view in Google Analytics. So it's got an employee doing that. MARTIN SPLITT: It would-- Rendertron would then execute that JavaScript, generate the page view, but would not-- it strips the JavaScript entirely out of the HTML that it serves on the [INAUDIBLE].. So you would not get Google Analytics on the HTML  

#### [0:47:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2820) |  that Rendertron generates. Which is not great

if that's what you want. A few people asked for an option to keep scripts in, and I'm like, dynamic rendering's entire idea is to remove every bit of JavaScript from a page. So I don't think Rendertron is the right tool for that. What you're saying sounds more like you want server-side rendering. TONY MCCREATH: Right.  

#### [0:47:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2850) |  MARTIN SPLITT: All right, we have time

for two, maybe three more questions. Maybe one if it's one that makes me go talk for a longer time. Oh, there's something coming in by our chat. Last question on that problem with infinite scroll if it's OK. Yeah, sure. We are afraid that when we'll fix it, we should expect serious fluctuations in search results. When we are searching description of an article that goes in infinite scroll, Google says  

#### [0:48:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2880) |  there are seven or more obstacles with

this word. Does that mean that the Googlebot integrated our articles incorrectly all this time? I mean, Googlebot saw twice bigger text when it was in the original. I'm not 100% sure if I understand where you're going with this, but basically if-- where's that link taking me? Let's click on that link. OK wow, that's the--  

#### [0:48:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2910) |  I think what we're seeing here are

different-- yeah, all of these are-- oh wait, 69DC 94E. So we seem to be seeing different pages with this text in it, but I'm not 100% sure if that's a problem or not, to be honest.  

#### [0:49:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2940) |  If you change the way that your

content looks like and the site structure looks like, then yes, that will cause ranking fluctuations. Because we're effectively seeing changes in all the pages that we have in the index. We might see new pages if you change your URL structure in the same time. That will cause fluctuations, yes. If what you are seeing right now in terms of search performance is what you expect to see, then I don't think that's a problem that needs to be fixed. If you see problems with the way that search  

#### [0:49:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=2970) |  works for your site, then that's something

that you want to fix. Don't fix what isn't broken. As far as I can tell-- and correct me if I'm wrong, as far as what you have submitted through the chat so far-- we are seeing all your content. We are ranking your content. Your content shows up in search results. Sounds to me like that's what you want, and I wouldn't fix this if it wasn't a problem. If you are seeing that we are not  

#### [0:50:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=3000) |  seeing some of your content, or if

you notice that your content doesn't perform very well, then you can consider reconfiguring your site. But I wouldn't change anything without being 100% sure that what you are seeing right now in terms of search performance is not what you expect to see. And just the fact that we see the same content on multiple search-- the same words in multiple URLs, that does not mean that that's a problem.  

#### [0:50:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=3030) |  It can only be that reporting is

a little harder because your content might be spread across multiple URLs and multiple different pages. But if it works the way that you would want this to work, and you get the clicks and impressions that you look for, don't fix it because it doesn't seem broken. You're welcome. OK, one more question.  

#### [0:51:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=3060) |  Anyone? I think maybe we have submissions

though YouTube, as well. Let me look. Yeah. Is there some tool that I can use to track the page speed with JavaScript automatically in a dashboard? I believe there's a bunch of tools that do things like performance budgets. You can run Lighthouse in an automated fashion--  

#### [0:51:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=3090) |  automated fashion. In an automatic fashion. That's

what I wanted to say. There's like a Lighthouse CI, I think it's called, is the tool that you can set up to run, I don't know, like twice a day. And then you can snapshot the scores, and then see how the score changes over time. I know that that has been built. I'm pretty sure there's also paid services that do something similar, but I don't have a list of them right now.  

#### [0:52:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=3120) |  I would just search for web performance

budget tracking, or like Lighthouse over time, or something like that. Because I'm pretty sure it has been done before, and it's probably well-documented at this point, as well. So Lighthouse is a good tool to track performance over time. I think you can probably also somehow do that with webpage tests, but I'm not so sure about that. And there's definitely paid solutions out there that do that, as well.  

#### [0:52:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=3150) |  All right, now one last question from

the audience. That was an easy one. TONY MCCREATH: Can I do one that might be-- JavaScript's involved. MARTIN SPLITT: Sure TONY MCCREATH: I'm using Puppeteer to audit clients' websites. So it's rendering the page and things like that. And as I mentioned before, I noticed that it runs Google Analytics scripts, which  

#### [0:53:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=3180) |  I found quite powerful. Because I can

actually find out if a client's got Google Analytics tagged three or four times, things like that. Whereas Googlebot uses robots.txt to stop it doing that. I'm wondering if-- I don't if it's you guys, but should we be using Puppeteer-- because it's a bot really-- should we be blocking triggering things  

#### [0:53:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=3210) |  like Google Analytics and things like that?

MARTIN SPLITT: I think that is up to you. On one end, if the client websites, or if the client's marketing, or analytics, or data science departments complain that they get visits on analytics that look weird, then they can either filter it by filtering-- or if you can probably give them something that they can filter by in Google Analytics.  

#### [0:54:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=3240) |  You don't have to block Google Analytics

because you are a bot. That is your decision in the end. If you don't want to accidentally skew-- I mean, if you are requesting the entire website, like, once for an audit, I don't think that's going to make a big difference unless the website has like five visits anyway per month. Then they're going to be like, we have 10 visits. That's 100% increase. And then they found out that's actually you  

#### [0:54:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=3270) |  botting the website. But normally, it doesn't

really matter that much. And I remember that at least the last time I worked with a data science department, they're like, oh yeah, we're removing everyone who works here from Google Analytics. And we also remove all the bots that look weird. You can maybe set the user agent to something that is easily spottable. TONY MCCREATH: Which, yeah, I do that. MARTIN SPLITT: And then that's an easy filtering question. TONY MCCREATH: Maybe Google Analytics knows about it anyhow.  

#### [0:55:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=3300) |  MARTIN SPLITT: Probably. If you are having

like a really weird user agent, I'm pretty sure that Google Analytics will be like, hmm, interesting. Let's put that here. All right, yeah but in the end, it doesn't-- like it's your decision if you want to run Analytics or if you don't. OK, excellent. In which case, thank you all so much for your questions and for joining.  

#### [0:55:30](https://www.youtube.com/watch?v=nZO0OVN37aY&t=3330) |  Also thanks to everyone who submitted a

question through YouTube, and the next JavaScript SEO Office Hours is in a week's time. It is also already posted on youtube.com/goog lewebmasters/community. If you search for the post that says JavaScript SEO Office Hours May 6, I believe is the next one, then you can submit your questions there. I'll make sure that that one's also recorded, as well as this one. And I wish you all a fantastic time.  

#### [0:56:00](https://www.youtube.com/watch?v=nZO0OVN37aY&t=3360) |  Stay safe, stay healthy, and see you

soon again. Bye. TONY MCCREATH: Cheers. MARTIN SPLITT: Cheers. Stop the recording. s  