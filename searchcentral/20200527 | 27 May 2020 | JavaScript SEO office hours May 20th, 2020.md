[![JavaScript SEO office hours May 20th, 2020](https://i.ytimg.com/vi/XG4aWpQ844w/maxresdefault.jpg)](https://www.youtube.com/watch?v=XG4aWpQ844w)

## JavaScript SEO office hours May 20th, 2020

This is a recording of the JavaScript SEO office-hours hangout from May 13, 2020. These sessions are open to anything around SEO for JavaScript sites.



Watch out for new sessions, and add your questions at youtube.com/googlewebmasters/community



Subscribe to Google Search Central → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=0) |  MARTIN SPLITT: Hello, and welcome to another

JavaScript SEO Office Hours. My name is Martin Splitt. I work for Google. I am in the Search Relations team, same as John Miller and [? Gary Leish. ?] And yeah, thank you so much for submitting your questions. And thanks to everyone who joined. These office hours are currently done on a weekly basis. There's one in the earlier timeslot for me, and one in the later timeslot. So you can figure out which one works better for you.  

#### [0:00:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=30) |  We announce them at youtube.com/goog lewebmasters/community. So

keep an eye out for these. If you want to join these recordings, I'll post the links in the threads that I create there, where you can also submit your questions. So I'll start with a few of the questions. We have a bunch of really good questions this week. I'll look through them real quick. And we'll pick one that is relatively easy to start with. And then I'll give the audience, the live audience an opportunity to also ask.  

#### [0:01:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=60) |  So is Googlebot still crawling the sites

in the second wave? Or has this been updated to include the first wave? Ah, that's a famous question. And I fear this question every time it comes up, because the first wave/second wave has been a simplification that we use to illustrate how Googlebot processes things. And a lot of stuff happens in parallel inside Googlebot. So it is relatively hard to explain this properly and show this properly. The second wave, as such, wasn't really a thing.  

#### [0:01:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=90) |  It is made-- basically, we process-- we

crawl, which means we make the HTTP request to get your HTML content and the resources. And then we process the HTML that we see. And then while we are processing, at the same time, we are also queuing for rendering, and then render the page, which means executing the JavaScript. And then we process the render HTML again. That means there isn't really a big concern.  

#### [0:02:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=120) |  The concern has been that, oh, the

second wave takes up to a week or longer. But we looked at the data last year. And we found that the median time in queue is five seconds. So between rendering and-- between crawling and rendering, there is-- in the median case, there is five seconds delay. 90th percentile is minutes. So you shouldn't really worry about that. All websites go through rendering anyway. So you don't have to worry about that either. And there is no such thing as rendering budget,  

#### [0:02:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=150) |  just to get all these out. So

the second way It has been a simplification to explain a very, very complex concept and process that we are no longer using-- the metaphor we are no longer using, because it is a little misleading. And we haven't found a better metaphor of saying this. But fundamentally, what we try to say is, if your content is in the server side rendered HTML,  

#### [0:03:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=180) |  that's what we already look at. So

you can, for instance, make sure that we find important links a little quicker. Like, we discover them quicker by having it in the processing right after crawling. But it's not that huge of a difference for us, if it's only in the content after we render. It makes no big difference these days. Cool. Another question that I get a lot of times is, when I view a source on the client's website, I see that content is contained within some sort of JavaScript  

#### [0:03:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=210) |  object. But if I view the page

in developer tools, I see that the function has done something with it and turned it into HTML. Am I right in assuming that that's OK? Yes. Short answer is yes. If you would look into the dev tool-- sorry, the testing tools that we have, like Mobile Friendly Test, your Inspection Tool, Rich Results Test, you see a rendered HTML tab. And if the content is in the Rendered HTML, you're good. That's absolutely not a problem.  

#### [0:04:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=240) |  It's very normal that the view source

is basically what the server sends. So it's normal that, if you use client side rendering that the content isn't in the HTML when you source it. But once the JavaScript executes, it actually injects it into the DOM as proper HTML. And then everything's fine. So that's not an issue. All right. Before I go through more questions from YouTube, any questions from the live audience?  

#### [0:04:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=270) |  OK. If there is no live question,

then another YouTube question. With dynamic rendering-- dynamic rendering means you serve a prerendered, non-JavaScript version to bots, but give the normal client side rendered or whatever version to users. With dynamic rendering, we're looking to serve Googlebot a version of a page with navigation accordions fully  

#### [0:05:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=300) |  expanded with individual href's. But users will

end on a version where it's not. Likewise, we plan to not prerender cookie constant banners for search engine versions and having it for users. Is there a quantifiable threshold guideline, be it in diffs and code or pixels where dynamic rendering could mistakenly be considered cloaking? No. There's no special guideline. Cloaking detection is complicated.  

#### [0:05:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=330) |  And for obvious reasons, we don't want

any of this to be gambled with. So we don't really say much about this. The thing is, as long as you are having a use case like this where just auxiliary content like consent banners or accordions are different from what Googlebot sees and the actual user sees, it's not really an issue. That being said, it shouldn't even be a real big issue to begin with. Even if you wouldn't dynamic render for Googlebot,  

#### [0:06:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=360) |  that should not be a big problem,

because we are seeing things that are invisible as well. We might just consider them slightly differently. But that normally isn't hurting you or isn't causing the problem. So that's a very good question. Generally speaking, just don't mislead the users. And if you are tricking the user to believe something to be-- if you trick the user into clicking on something that they didn't intend to do through Googlebot-- so if you tell you about, hi, my website is about kittens.  

#### [0:06:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=390) |  And then on the website, when the

user lands there, it's about-- I don't know-- boats, that's not great. But generally speaking, making these adjustments for dynamic rendering is not a problem. Would you recommend dynamic and/or service side rendering above using no script tags for showing JavaScript content into Google about? Yes. And actually, looking at dynamic rendering or server side rendering, I would recommend server side rendering, because server side rendering generally tends to produce faster results for faster websites for users.  

#### [0:07:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=420) |  So I would consider that over the

added complexity. Both of these things-- server side rendering and dynamic rendering-- are complex. They are not easy to implement. If you take the effort onto you, then definitely do the thing that also benefits your users, which is server side rendering. So do that instead of dynamic rendering unless you can't for whatever reason.  

#### [0:07:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=450) |  But I would definitely prefer that over

no script, definitely. Can you please expand a bit on the loading spinner from the last Hangout? Oh, I think-- ah, right. If, for example, I see the spinner in the mobile friendly tool, but on the HTML view in the tool, I see the content bot, is that an issue? Ah, last time, there was a website that had a specific question. Like, why is Googlebot not indexing? Or why is Google not indexing this particular page? And why does it think it's the same page as other completely  

#### [0:08:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=480) |  unrelated page? The issue there was that

the HTML content actually, including the spinner, was the same on both pages. And a page with just the spinner isn't fantastically interesting in terms of content. So we thought, hm, all of these pages, because they were all just displaying a spinner, are the same, because they are just containing markup for the spinner-- markup being HTML. And then the page that we ended up picking as the canonical  

![](https://i.ytimg.com/vi/XG4aWpQ844w/maxres1.jpg)



#### [0:08:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=510) |  from the set of pages, it's just

a spinner. So what would we put in search results? Why would we put a page with just a spinner into such results? If you do see your content in the HTML, you are more or less well off. I would still inspect and investigate why we are just seeing a spinner. Why don't we see the actual content? Is there something going wrong? It normally isn't a big issue, especially if we see it in the content, we can index it  

#### [0:09:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=540) |  and understand that these pages are different

from each other. But I would still wonder why is it showing a spinner. There can be legitimately harmless reasons, like-- I don't know-- we can't, for some reason, get to the content quick enough, or one specific thing somehow specifically failed in Googlebot, it doesn't fail off for users. As long as the content is there, we can see it, we can index it. But I would try to understand why you see a spinner in the preview screenshot.  

#### [0:09:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=570) |  Also, the previous screenshot is an approximation.

So don't worry too much if that's not like 100% accurate. Cool. Any questions in the audience in the meantime, while I'm scrolling on YouTube? DAVE SMART: I've got a quick one. It's about server side rendering and AMP, really, because I guess AMP is a client side render thing to some extent. And I believe in server side render. Is there much benefit to that from a Google perspective?  

#### [0:10:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=600) |  Or is that well understood enough as

a framework that it's more of a performance thing that you need to worry about? MARTIN SPLITT: It is pretty much a performance thing, really. So there's not an inherent benefit. AMP is just one way of making sure that you build a fast website. And you can actually-- hilariously enough, you can use AMP in ways that make it not as great and fast as possible. So it is a technology. It is developed by Google. But that doesn't mean that it brings you  

#### [0:10:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=630) |  big benefits, really. The Core Web Vitals

is a project to actually widen the understanding of what makes a fast website. And AMP is trying its best to basically give you the default path to a fast website. But that's pretty much it. So as long as you make your website fast and nice for users and have good content, then AMP or no AMP doesn't make that much of a difference.  

#### [0:11:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=660) |  One more YouTube question-- I have a

new site in which each article comments are enabled by users. Comments are grouped with JSON LD-called comments. I've seen that Google does not cache those comments as part of the HTML of the page. Are you looking into the Google cache? Because that's not a good testing tool. I wouldn't worry about that, to be honest. I would check with the testing tools if it shows up in the HTML. If it doesn't, then it's a little tricky,  

#### [0:11:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=690) |  because the JSON-LD on the page should

augment the page content, which means it should describe what is on the page anyway. If you have JSON-LD that doesn't match anything on the page, it might not give you as much benefit as you wish. So hm, tricky, tricky. What else do we have here? Does Googlebot recognize that select sections of a page content--  

#### [0:12:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=720) |  of a page's content can be hidden

by Show and Hide buttons and therefore decrease the priority or value of that page content based on the fact that it can be hidden? In other words, does Google assume that, because the developer created the content such that it can be hidden by the user, therefore it must not be-- no. We don't even click on things. So if it's visible by default, we wouldn't even know that you can hide it. Also, if you choose to hide it, that doesn't mean that we completely ignore it.  

#### [0:12:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=750) |  It just means that we might think,

OK, so this is apparently not the most important piece of content here, as it is not visible. So we might decide to look at it slightly differently. But generally speaking, that's not an issue really. I have JavaScript links to related products in my web store. Is it convenient? Or should they be in HTML? Well, I asked the clarifying question what they mean by JavaScript links  

#### [0:13:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=780) |  and what they look like in rendered

HTML. And the answer I got is yes. So I'm not 100% sure. But there is documentation for this. If it is a normal href URL, then yes. We can see it. It's fine. If it is anything else, like a button, or diff or a span or something on click, or even an A on click without an href, or an empty href, or something like that, then, no, that's not good. So there's two pieces of documentation  

#### [0:13:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=810) |  that are helpful in this case. One

is the webmaster guidelines on making things crawlable. And the other document is the JavaScript SEO Basics guideline where this is being called out. So as long as the links are proper links, they are fine, even if they are JavaScript-generated links. Anyone else with a question from the audience?  

#### [0:14:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=840) |  TONY CASTILLO: Martin, my agency is building

a lot of PWAs right now. And what resources could we use to make sure that those sites are still crawlable and there's no rendering issues? MARTIN SPLITT: That's a good question. So we do have the JavaScript SEO Basics guide that explains a bunch of stuff that you should probably have a look at. There is even a CodeLab link from that guide that shows you what to look out for in single page applications. And for us, PWAs are basically first and foremost websites.  

#### [0:14:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=870) |  So we don't really care if it's

a PWA or not. If you want to test how Googlebot sees this, you can use the Mobile Friendly Test. You can use the Rich Results Test. If you have it somewhere online where you have a domain authorship verified already, you can use Google Search Console and the URL Inspection Tool to see how we're seeing the content. And Search Console also shows you if there are problems indexing certain pages or views of your progressive web app.  

#### [0:15:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=900) |  So definitely use the testing tools available

from our site to check the rendered HTML. That's the most important bit. Does that help? TONY CASTILLO: Yeah, it does. Thank you. MARTIN SPLITT: Awesome, great. What else do we have here?  

#### [0:15:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=930) |  Then we have a question-- I'm not

100% sure what to say without looking at the site. So there's one question saying, if you're running a single page app and there was set to render the client side and the HTML preview shows a blank page, what would be the best way to fix this? The answer to that question is, it depends. When you say by HTML preview, what you mean is the rendered HTML in any of our testing tools, then look at--  

#### [0:16:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=960) |  potentially there is a problem with us

fetching the JavaScript resources. If they are robotted, for instance-- TOM KOH: [INAUDIBLE] MARTIN SPLITT: There is a-- if there is a robot's issue with one of the APIs that you have to fetch to actually render the page, then that might incur an issue. Generally, check if the HTML content is entirely blank,  

#### [0:16:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=990) |  or if that's just a display issue

if you are looking at the screenshot. But it really depends. There is no general answer. But I would definitely look close at the testing tools. Also, look at that resources loaded. If there is any 500s, or robots issue, or some resources not going through, then that's something that you want to check on. I know that some CDNs apparently sometimes do cause us to either see outdated JavaScript, or to see some sort of warning, because they  

#### [0:17:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1020) |  think we are a bad bot or

something like that. I've heard stories of this. I've never actually seen or experienced that. So it's a tricky one. But definitely use the testing tools to dig deeper into why we are not seeing your HTML. Right. Any questions from the live audience? I'm running low on questions from YouTube.  

![](https://i.ytimg.com/vi/XG4aWpQ844w/maxres2.jpg)



#### [0:17:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1050) |  DAVE SMART: Just a quick clarifying one.

I see a lot people sometimes try and use the Google cache from the web thing-- from web search to diagnose still. My understanding is-- and it's probably a pretty poor measuring rate. But we start the initial HTML. That's not the rendered HTML, is it, that's shown in there? MARTIN SPLITT: Yeah, it often is just the-- so sometimes, it is the rendered HTML. Sometimes-- well, most of the time it is the initial HTML.  

#### [0:18:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1080) |  A bunch of times, it's even an

older version. The Google cache is a convenience feature in case the website goes down. It has been built many, many moons ago. And I don't think it's actually actively being maintained. So as the indexing infrastructure keeps changing, it doesn't really change with it, because there's no one attached to it, as in there's not a Google Cache team that works to keep this feature going, because, as it works, it works reasonably well.  

#### [0:18:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1110) |  And it's meant as a fallback for

a website going down. It's not meant as a way to find out if Google sees your content. And it's not a debug tool. I know that there is a Help Center article that makes it sound like it is. I'm actually working with the team behind that Help Center article to figure out if we can clarify the wording and actually point to the right debugging tools. But don't use it as a debugging tool, yeah.  

#### [0:19:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1140) |  Tom, I got your question on the

recent Core update, but I don't comment on ranking. And I actually don't know about the Core update, because that's not my area of expertise. So I won't say yes or no to this, because I don't know. Good question. I don't know. Then there's a question 11 minutes ago.  

#### [0:19:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1170) |  Nicholas asked, is it normal to see

sometimes the headline tags only visible with JavaScript? Is it a best practice to have headline tags in a JavaScript? I mean, if your content is client side rendering, then you will see all of your content only when you actually run JavaScript rendering and crawling. So that's fine. If you only see-- if your content is there but the headlines are not there,  

#### [0:20:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1200) |  that's weird, I would say. That's a

really weird use case. And I would definitely ask the developers why the headlines are not loading as part of the rest of the content. But if all the content only goes with JavaScript enabled, then that's OK, too. That's not a problem. But it's not a normal thing to just load your headlines with JavaScript and the rest of the content is there. You should not do that. You should always have your HTML in a good shape, be it either coming from JavaScript-- that's fine--  

#### [0:20:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1230) |  or having it static. That's fine, too.

There's a question about a really large React JS website. The site was launched in January. But as of today, it has only 37,000 indexed pages out of 550,000 or more. Every couple of days, 800 pages get indexed. I've tried to speed this up by not limiting Googlebot crawling.  

#### [0:21:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1260) |  So we are now at 512,000 pages,

apparently. But yeah, it apparently takes a long time for us to index. Well, first things first, I don't know how you got to 550,000 good URLs with interesting content for your users. But I would say, I have a feeling that a few of these URLs might not be as relevant. So maybe make sure that we don't spend time  

#### [0:21:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1290) |  on them crawling and indexing. And yeah,

there's no guarantee. That's just the thing. There's neither a guarantee that we will crawl and index all these pages in the URLs. There's no speed guarantee. Sorry. We will have to see and wait. But I think if we already have discovered 500,000 pages since January, that's a relatively good rate.  

#### [0:22:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1320) |  But the other thing is that indexing

doesn't mean that it's showing up. And it doesn't mean that it's useful. So you shouldn't hunt these metrics down without thinking. If I have a page that is indexed but no one ever sees it in search results and no one ever clicks on it, then what have I gained? Not really much. So think about a user's perspective. Or from a user's perspective, try to understand what are the pages that you really, really care  

#### [0:22:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1350) |  about. And I have a hard time

believing that it's half a million pages that you really, truly, definitely care about that are for the masses. Try to get the main vectors into your website index, because they probably have a-- try to get those pages indexed that have a high chance of actually driving traffic. And then the rest is maybe not so important. So indexing and indexing and ranking is not necessarily the same thing.  

#### [0:23:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1380) |  But that's something that I hear a

lot of times. Then there's another question 23 minutes ago from Roshan. My crawl rate is very low. It only crawls 20k to 40k URLs. That's actually not too bad. Could it be why I lost all my discover traffic in September last week? In September last week? It has been on decline since then, 90% drop since September.  

#### [0:23:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1410) |  No, crawl rate has nothing to do

with either indexing or ranking. If not much happens on your page, then a low crawl rate is perfectly fine, right? If we have seen all your content and have put it in the index, then why would we continue to crawl? The other thing is discover is an organic feature. And that can always come and go. More websites come in, interests keep shifting.  

#### [0:24:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1440) |  It happens. And then, for instance, if

you are a travel blogger, you'll probably see less traffic now than you usually see. That just happens. That's how organic traffic works. But there's nothing inherent to, oh, crawl rate is an indicator for-- no, it's not. It's not an indicator for quality. It's not an indicator for demand, or traffic, or whatever. So no need to worry about that.  

#### [0:24:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1470) |  Hello. What is the best way to

clean and use JavaScript code on a website? That's a good question. Generally speaking, I think the Google Developer Tools show you unused code. And that's probably the best for developers, because they can see which part of the code is actually unused when they go to certain websites, as they have the unlimited and unminified sources  

#### [0:25:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1500) |  available to them. I think looking at

where page tests to see where's the biggest amount of code that we have is probably a good starting point to see where you need to dig a little deeper. If you use things like webpack, they usually have a bundle analyzer, where you can see what kind of dependency-- where does the size of my bundle come from, or my JavaScript come from?  

#### [0:25:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1530) |  You can do tree shaking. So your

developers can write code in a way that, if they take in an entire library but only use five functions out of 100, the rest of the code is actually split off automatically. If you want to learn more, there's a bunch of really good stuff around web.dev/fast, for instance, and more resources on web.dev in general. So I would look into those. And it's a whole huge topic on its own.  

![](https://i.ytimg.com/vi/XG4aWpQ844w/maxres3.jpg)



#### [0:26:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1560) |  All right. Any further questions from the

audience? Quiet audience today. Let's see. Maybe I missed a question here.  

#### [0:26:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1590) |  DAVE SMART: I've got another quick one,

if that's OK. A lot of advice around speed and form always used to be about basically stitching all your JavaScript file into one big, giant file. Is that still really the case with things like a HTTP/2 and things like that? MARTIN SPLITT: That's a good question. And it's a tricky one. So HTTP/2 does make that a little less important.  

#### [0:27:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1620) |  But still, I would say, first things

first, Googlebot still uses HTTP/1.1. A bunch of browsers might fall back to it in certain cases. Not every web server is configured to use it. So there is still a bunch of people that are not looking at HTTP/2 and its possibilities. But generally speaking, even the idea-- even if we ignore HTTP/2, the idea of stitching the entire bundle in one  

#### [0:27:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1650) |  is and has become an "it depends"

kind of situation, because, as we build larger applications, a single bundle is definitely greater than a bazillion small JavaScript files, because they have to they get over one by one. I think that even multiplexing have some sort of limit, I guess. Even if it doesn't, then still it means a lot of data needs to be going over the wire that you might not need. If you imagine that you have a huge website with a blog,  

#### [0:28:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1680) |  and a forum, and a shop, and

you have one big bundle, then that's not exactly fantastic, because, if I just come for the shop, why would I need the JavaScript for the blog, and the forum, and all that kind of stuff? So if you can, split your bundles along reasonable boundaries, I would say. So try to get the bundle to bundle up as much as you can. But try to split it as reasonably as you  

#### [0:28:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1710) |  can, because if you really, really care

for the traffic to your blog, then don't make people download the bundle for the rest of the website when they don't need it. You can prefetch these things, so that you can speed things up a little bit. You can use a service worker in the background to fetch these things in the background. That's a much better practice than having everyone download a huge bundle. The other downside with one huge bundle is caching.  

#### [0:29:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1740) |  If you have this huge website that

has a bunch of stuff in one JavaScript file, like the app.js file, the browser caches, great. But then I change something in the blog, and everyone, even those who never visit the blog, need to actually download the entire app.js again. If I have a blog.js, a, let's say, common.js, and I have shop.js, then, if I make a change to the blog, only the app-- sorry, only the blog.js needs to actually be redownloaded.  

#### [0:29:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1770) |  And the rest can stay in the

cache. So the answer is it depends. And it needs a lot of measuring and trying things out. There's no one-size-fits-all. And HTTP/2 makes that even more complicated, because you then have to ask yourself, OK, so how can I make the best use of the multiplexing in the connection? But realistically, even without HTTP in the equation, you have to measure things for yourself and try to make a reasonable call as  

#### [0:30:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1800) |  to where to cut your JavaScript so

that it fits the main avenues of your application or website. DAVE SMART: Just to follow on from that as well, is it-- [INAUDIBLE] a bit torn about is that, obviously, if you say-- if you're serving JavaScript files might be a break in there for allowing things like [? interactive ?] bot. It seems maybe a bit of a fudge, that,  

#### [0:30:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1830) |  because it doesn't seem a predictable way

in many ways. MARTIN SPLITT: It isn't that-- yeah, it isn't really that predictable. And it's tricky. And there is no easy answer at this point, really. And tooling does help with it a lot. And I know that you can configure most bundlers to give you different bundles, and then cache them separately. But yeah, it is tricky. I'm not saying I have easy answers.  

#### [0:31:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1860) |  Unfortunately, sometimes there isn't a nice and

easy answer. Oh, there's a question I haven't seen. I'm using Angular 9 with server side rendering on my website. As I add more features to the website, my overall JavaScript file size increases. Yeah. The following is a Page Speed Insight for one of my features. OK. You can see that the field data for that page in origin is not looking good. I want to know the magnitude of impact it can--  

#### [0:31:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1890) |  I mean, there isn't an easy formula

or something. But seeing a 70% drop in traffic over a two-ish, three-ish weeks, I doubt that that's exclusively because of performance. Also, because you actually have a relatively good performance score, your first [INAUDIBLE] is in 2.3 seconds. Sure, that can be done better.  

#### [0:32:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1920) |  But that's not the worst thing ever.

You have a first input delay of 300 milliseconds. You have a maximum potential first input delay of 290 milliseconds. That's not really a problem. I guess you can improve caching a little bit, according to this audit. But I don't think this is the biggest thing that you need to look at. Traffic drops can happen. That's something that just-- organic traffic is tricky.  

#### [0:32:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1950) |  It's seasonal. It is a little unpredictable,

because other web sites might come up. It might have to do something with the Core update. It might have-- it can be anything, really. Just try to understand what still works, where the traffic is coming from, what traffic you are no longer getting. And then try to find out why you're not getting that traffic anymore. But I don't see performance as the reason for this.  

#### [0:33:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=1980) |  Good. Any more questions from the audience?

DAVE SMART: I'll annoy you again with another one if nobody else wants to. MARTIN SPLITT: Go for it. No yeah, sure. DAVE SMART: Does the web rendering stuff ever take notice of Cache-Control header? Or is that pretty much always ignored? MARTIN SPLITT: We pretty much always ignore the Cache-Control header, because so many resources are under-cached that  

#### [0:33:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=2010) |  it would make our rendering a lot--

would put a lot more load on our crawling and rendering infrastructure. So Cache-Control isn't the best way of telling us to actually redownload something. That's why I am rallying for using versioned URLs, as in app dot some hash dot js, so that when you change the content, you change the file name,  

#### [0:34:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=2040) |  because then we have to download it,

because it's a new file name. But we do look at it sometimes. But it's not a guarantee. We might ignore the Cache-Control header, which is unfortunate sometimes. But generally speaking, it is too unreliable a signal, unfortunately. Right. So last chance for the audience to ask a question.  

#### [0:34:30](https://www.youtube.com/watch?v=XG4aWpQ844w&t=2070) |  If there are no further questions, then

we'll wrap this up. And 3, and 2, and 1. All right. Thank you so much for joining. I hope that this was helpful and a little bit of fun, maybe as well. I was looking at the sheep that the neighbors have are showing up. But unfortunately, there's no sheep to show you. If there were, I would show you the sheep.  

#### [0:35:00](https://www.youtube.com/watch?v=XG4aWpQ844w&t=2100) |  But thank you so much for joining

this. Stay healthy, stay safe. Have a fantastic time. And see you next time. Goodbye. DAVE SMART: Bye.  