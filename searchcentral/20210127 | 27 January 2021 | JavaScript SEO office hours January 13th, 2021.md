[![JavaScript SEO office hours January 13th, 2021](https://i.ytimg.com/vi/Vy7c1NRC7vo/maxresdefault.jpg)](https://www.youtube.com/watch?v=Vy7c1NRC7vo)

## JavaScript SEO office hours January 13th, 2021





#### [0:00:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=0) |  MARTIN SPLITT: Hello. And welcome to the

JavaScript SEO Office Hours in January 2021. Ooh. I hope that you all had a great turn of the years. I think that's what we say in German, but I'm not sure if that's an English thing that you can say as well. I hope you had a good start to the new year, that you're all safe and sound out there. I'm really happy to see that there's a bunch of really good questions on the YouTube post site for this hangout. I'll also, obviously, invite my two guests here  

#### [0:00:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=30) |  in the live meeting to also contribute,

but let's go through the YouTube questions first. So first question came from-- or comes from Jane. Jane asks, how often does Googlebot crawl or render JavaScript for indexing? Is it the same frequency as crawling HTML, or is it less? Really good question because it's a non-simple and non-trivial answer. So the very short couple of words version of it is, yes.  

#### [0:01:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=60) |  Googlebot crawls and renders JavaScript for indexing

as much as of scrolling HTML because pretty much it's like an entire workflow. So it goes in, the crawl happens, and then the rendering happens. And then the indexing happens. Roughly, that. If you want a little more detail, I'll happily provide more detail. But if that's the level of understanding you are looking for, stick to that. It's basically the crawling happens, and then the rendering happens as well.  

#### [0:01:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=90) |  Interestingly enough, there might be reasons for

us to render more often than we crawl. Sounds weird, but hear me out. We might experience situations where we crawl the HTML and then render, and then rendering, for some reason, has some sort of problem not even related to your JavaScript or your website specifically but to our infrastructure. So we might render a second time. That's totally transparent. So it's not something that you need to worry about, or you can influence. It's just it happens automatically. It can also be that if the crawl brought a lot of resources that  

#### [0:02:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=120) |  might change in the meantime, we might

actually then basically crawl the resources as part of the render. So we might render more often than we crawl. But in general, we render as often as we crawl. Sometimes, however, we might crawl more often than we render. If, for instance, another part of Google Search wants to validate something or check something, or if there is crawls going in to see if something has  

#### [0:02:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=150) |  happened on the content, then we might

crawl, decide nothing has changed, and then not render hypothetically. That is a situation that can happen. So we might not render as much as we crawl. It can also be that crawl, we make the request, then something goes wrong before we can render, and then we have to crawl again. In this case, we would also crawl more often than we render. Again, in general, the rule is we crawl and render similar amounts.  

#### [0:03:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=180) |  So whenever we are crawling, we're also

rendering afterwards. So that's not something that you need to worry about or need to take action on. But to answer the question completely, I'll give you a little more background information, which ends up saying, like, generally, yes, the same amount. But there are cases where we might render more often than we crawl, or we might crawl more often than we render. But again, that's not something that you need to take action on, or need to be aware of, or need to worry about. Next question comes from Kevin.  

#### [0:03:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=210) |  Kevin is asking, how they should apply

metadata to 360 degree photos for Google My Business. That's a question for the Google My Business support forums. That's not something that I know or I'm aware of. That's not something that is specific to Search or JavaScript, so that's something that you need to talk to the Google My Business folks about. And then it's like, can businesses get their products into Google Lens? That's a Google Lens question not a Google Search question. Kevin, I'm sorry to not be able to answer  

#### [0:04:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=240) |  these ones a little outside of my

area of expertise. Harris or Harris-- I'm not sure-- is asking, does Google really execute JavaScript? Yes, it does. I mean, whether Google robot reads the source code or it renders the page on the client side and then reads. We do render the page. We actually render the page just like your browser would, so we execute the JavaScript. And whatever gets injected into the DOM by the JavaScript, that can be taken forward.  

#### [0:04:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=270) |  You can see that by looking at

the rendered HTML in the URL inspection tool or the rendered HTML in the mobile-friendly test or in the AMP test. All of that includes content that is generated by JavaScript because we render that properly. And Harris has a second question and actually a third one as well. So how does Google deal with dynamic content by JavaScript which changes with some condition like user clicks, location, browser, or timing? You can find that information in our wonderful documentation  

#### [0:05:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=300) |  at developers.google.com/search. Googlebot does not click, or

scroll, or whatever. So things like location where we reject location requests, so you can't really get location in Googlebot. Or clicks would not work with Googlebot because we don't carry out clicks, and we don't give you the user's location in Google Search in Googlebot rendering places. If it depends on timing, that might actually  

#### [0:05:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=330) |  work, because the way that time works

is different from how time works in the real world when Googlebot accesses your website. You can use the URL inspection tool or any of the other testing tools that we provide from the search side of things to see what's in the rendered HTML. If your content shows up in the rendered HTML, then you'll be fine. How does Google work with pjax? And that's a jQuery library load HTML content without loading and changing address URL.  

#### [0:06:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=360) |  I think what they mean by pjax

is, like, an older technique where you kind of have a single page application where the JavaScript just replaces the content on certain actions. I'm pretty sure we do not see that, because, again, we're not interacting with your content. So if it's only loading, like, different content on a click rather than just on URL, that would not work. You can see that described in the Best Practices Guide  

#### [0:06:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=390) |  that we have for JavaScript. Again, developers.google.com/search,

there, you find more information on how JavaScript is processed. Next question comes from Lorenzo. Lorenzo asks, how can I be really sure that Google is accurately rendering all of the content on the page? Using the screenshot from the URL inspection tool in GSC and from the mobile-friendly test, I see that a lot of JavaScript elements are not loaded. Instead, the rendered HTML code is perfect. Can I be sure the perfect rendering only by checking with the HTML code with these tools?  

#### [0:07:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=420) |  Yes. You can, because that's what we

use for indexing. So we don't actually use any images to look at what the page looks like or anything. We care about the rendered HTML code and some of the layout information. But fundamentally, if it's in the rendered HTML, you will be fine. That's what you should be doing. Could I be sure also viewing and checking the versions of my web page is cached in Google search results? No. The cache is not meant to include JavaScript rendered content. It is an outdated, old feature that we just keep around for convenience, but it might not follow the pipeline as well  

#### [0:07:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=450) |  as other things. The testing tools and

the rendered HTML is what you want to look for. [INAUDIBLE] asked, how are Wix websites doing in terms of rendering? Wix uses a lot of JavaScript for almost everything. And will a lot of JavaScript affect my crawl budget? There's a few things in these questions, so I'll run through these. How does [INAUDIBLE] Wix [INAUDIBLE] page render? Just like any other website, you can check it  

#### [0:08:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=480) |  in the URL inspection tool and all

the other tools that we provide to check and see the rendered HTML. If your content is there, you'll be fine. A lot of JavaScript may have an impact on your crawl budget depending on how it's built and what it does. Generally speaking, if you have less than, like, a million pages or more, crawl budget shouldn't be a problem. So I wouldn't worry too much about it. If you have a smaller website on Wix or smaller websites somewhere else, then crawl budget does not really impact you.  

#### [0:08:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=510) |  If there is a lot of JavaScript

files, all of these have to be fetched to render them. These fetches count towards your crawl budget. The other thing is if the JavaScript then makes additional network requests to fetch the content, like API requests or fetches additional images, all of these count against your crawl budget as well. But again, unless you have a really, really big site, that does not really impact your site too much. Mustafah is asking, regarding partial indexing on the pages,  

#### [0:09:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=540) |  how to quality assure our URLs and

get to know what parts of the page is Google indexing or not. Partial indexing is a tricky one. We are not really partially indexing things. We are having an index where all the information from the page is in there. With partial indexing, people sometimes-- I think this might be my fault because I think, I, at some point, said partial indexing, which is not true. We are indexing the entire page, and then we are looking at the content to find the bits that are more  

#### [0:09:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=570) |  important than the other bits. So if

you have a huge page about making an apple pie, and then on the page, somewhere down there, there's also a story of your cat. And we might decide that this page is really good for apple pie, but the cat part is not as relevant and not as interesting. And so the page might not rank for cat, but it might rank still for apple pie. But then sometimes people are, like, searching for the cat and are like, it's not in the index, or the page was not indexed.  

#### [0:10:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=600) |  It was indexed. It's just the content

isn't ranking because we don't think it's relevant enough to rank. Passage indexing-- sorry. Passage ranking. It's officially called passive indexing, but that's actually really passive ranking-- might change that a little bit where we can then say, like, well, actually, this part about the cat is also really good. So we can rank that for cats as well. But that's not something that you can really check. And I don't think you have to worry about that. As long as your content shows up properly  

#### [0:10:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=630) |  after rendering and the page is indexed,

you'll be fine. And then you can basically try out the different search terms and search queries that you're interested in, and see what happens in them, and also use the Performance Report in Google Search Console to find out for what you're showing up to. And if that is not what you want to show up for, then you have to see how to make the content more relevant for the terms that you care for. Lenore-- lovely, fantastic, ridiculously clever product  

#### [0:11:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=660) |  expert from the webmaster forum is asking

me as well. And he is saying, hello. I'm testing or trying to capture JavaScript errors generated when Google loads and renders JavaScript. I use an event listener to Google Pixel when the error is detected and I add error messages to the URL of the image. After that, I can hopefully analyze my server logs and get the messages and save them. Is there any other way to get error messages? I think there is no other easy way.  

#### [0:11:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=690) |  You might be able to get something

like-- what's it called? Sentry or-- I can't remember what they all are called. Graylog might have a thing. So there's, like, different logging libraries that can send error information out to a separate service that shows you the information. That might be possible, but I think your way of doing this is not bad. That sounds actually like a good plan. Smart, interesting idea.  

![](https://i.ytimg.com/vi/Vy7c1NRC7vo/maxres1.jpg)



#### [0:12:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=720) |  Next question comes from Marco. Marco is

asking, hi, Martin. There's a rumor that Googlebot does not like content in blocks which have SEO combination of classes like div class SEO, and this content is treated less valuable than content in blocks without class SEO. That is a myth. Yes. The question is if that's a myth, and the answer is yes. That is a myth. Interesting though. The next question comes from [INAUDIBLE] 85.  

#### [0:12:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=750) |  Is lazy loading of a news channel

page with a lot of news articles constantly changing subject to SEO? All content is currently communicated to Google site maps and by index API later. If yes, what are the pitfalls? What are the best practices here? We actually do have a best practices guide for lazy loading. But generally speaking, if the news articles independently are submitted to us by site maps, or RSS, or index API, and we can index them, that's not a problem.  

#### [0:13:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=780) |  We might just not rank this one

specific page with lots of things in there, so I wouldn't say it's very relevant to the SEO. If you want to make that page relevant in terms of search results for some reason, then, again, develops.google.com/search. And then under Guides, there is a guide that explains a little bit about lazy loading of content. But you don't really have to worry too much about that, to be honest. Miguel has the next question. We display different main navigations for desktop  

#### [0:13:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=810) |  on mobile. I'm considering the use of

JavaScript to remove hyperlinks from the DOM for links that are only available on desktop for mobile users. Is there a benefit or risk? I think, from the SEO perspective, it doesn't really matter that much. We probably will only index one of the two versions, depending on if you're mobile first or not. We might still crawl and potentially index the desktop version. We might just not highlight it that much in search results. The risk is that if the website's-- like,  

#### [0:14:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=840) |  if you remove links that are nowhere

else, then we might lose the semantic information on how to navigate between the different things there. But if it's like in the site map, and there's lots of other places to reach the content from, I wouldn't worry too much about this. And now, I shall reload the page to see if we have additional-- oh yeah. There is, like, even more comments coming in. Someone is asking for the Google Meet link. That's funny.  

#### [0:14:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=870) |  I know that this happens because the

way that YouTube is ordering comments unfortunately. It is happening, so two more people want to join and can't see the link, it seems. But I'll happily help them, so we might see them join in a moment. But thank you to everyone who submitted their questions to YouTube. This is great. These were great questions today. I'm really, really excited to see  

#### [0:15:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=900) |  the quality of the questions constantly improve,

and I now know that I have four people in the Hangout. If anyone has any audience questions, now is a great time to head into the audience questions. DAVE SMART: I'll get the ball rolling [INAUDIBLE].. MARTIN SPLITT: Excellent. Thanks, Dave. Also, by the way, brilliant product expert  

#### [0:15:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=930) |  from the webmaster forum. Always a little

nervous about your questions. Let's see. DAVE SMART: All right. Yeah. It's a bit back to what you were saying earlier that sometimes you render something more than you'd crawl. How would that impact, say, if I'm making an API call? Say I have a page almost that news thing, and it was [INAUDIBLE] API, [INAUDIBLE] the latest articles. Would that be a point where you're going back and fetching that API and re-rendering from what you've already got?  

#### [0:16:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=960) |  Or would that only ever be triggered

if you went back and crawled the main page? [INAUDIBLE] MARTIN SPLITT: That's a very, very good question. So the way that it works in the pipeline is the crawler basically crawls the resource. Like, the main resource, the HTML fetches that, caches that, and then the rendering happens to use the crawler to fetch all the resources. They also go in the cache. So that being said, if the rendering for some reason has to be restarted or is done at a later time, again for whatever reason, we would  

#### [0:16:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=990) |  go through the cache first, so especially

when it's GET requests. So you said, like, specifically API requests. If that is a get request-- it can be cached, and it happens to be in the cache, and the cache happens to not have expired-- we would just take what we had in the cache. Because the general idea of the rendering process is to produce as consistent renders as possible. So the idea is, like, given the same amount of data that we got from crawling at some point, we want the same output, which is why things like random number generating or time and date  

#### [0:17:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1020) |  work slightly different. You might actually see

us operate with date and timestamps that are coming from when we crawled rather than when we actually render. So to keep this consistency, we use the cache. Fantastic. But what if it is a non-cacheable request, or the cache has expired, or the cache, for some reason, doesn't have this request? Well, in that case, we would send-- the second render, that would run, would send the request to the crawler. The crawler would fetch the data, and then it would go into the cache. Or if it can't be cached, then it would skip the cache.  

#### [0:17:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1050) |  So you would actually see the render

then updating without necessarily seeing the crawl. You can probably see that in the server logs, because you would see the requests coming in from the crawler for one specific source. But again, we would try to reduce that amount of additional fetches, or fresh fetches, because we want the renders to be as consistent as possible and to hopefully only update when we also do the crawl run before. But that might happen, especially with POST requests that we can't. If it's an API request, that is a graphql request, that  

#### [0:18:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1080) |  is using POST, it might actually fetch

fresh. DAVE SMART: So it's not something that you would think, oh well, I've loaded this page, only ever really updates by doing POST requests. We'll just do that, and then [INAUDIBLE].. It's more in the scope of something went a bit wrong last time. Go back and fetch it. MARTIN SPLITT: Exactly. Yeah. That's pretty much what normally happens. DAVE SMART: OK. Thank you. MARTIN SPLITT: You're welcome. Awesome. Any other audience questions now that we broke the ice?  

#### [0:18:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1110) |  I don't want to do the teacher

kind of-- Oh. MIGUEL MARTINEZ: Hi. This is Miguel Martinez. I know this probably isn't. MARTIN SPLITT: Hi, Miguel. MIGUEL MARTINEZ: This probably isn't the most pressing question, but I had asked about considering using a JavaScript to remove hyperlinks from the DOM for links that only appear on our desktop version for mobile users.  

#### [0:19:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1140) |  There's some discussion within my organization about

whether or not it's a good idea versus a bad idea from an SEO standpoint, and if Google would even run the JavaScript as part of the crawl. MARTIN SPLITT: So this is going to be interesting on the recording because we answered this question earlier, but I will very happily answer again because I would like to hear if that's a sufficient answer for you or not. And it's always tricky to get that from here. MIGUEL MARTINEZ: I apologize. I did not see the link. MARTIN SPLITT: All is well.  

#### [0:19:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1170) |  I know that. That's why I'm very

happy to take this live, because it's YouTube's formatting of the-- or sorting of the comments. They have, like, this top comment by default. And usually, when you submit links, they are not rated as top comments, and then people don't see them unless they switch to the-- what's it called-- new comments first ordering. It's a little weird. Anyway, so we do execute the JavaScript. So we'll very likely see whatever comes out of the JavaScript run. So either if you remove the hyperlinks or add hyperlinks with JavaScript,  

#### [0:20:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1200) |  we will see or not see them

depending on if you removed or added them. In general, it shouldn't really matter that much. You can do that change. If you feel that it brings you other benefits than SEO benefits, I would probably do that. If you, for some reason, say, like, oh yeah, but it's better for the users, then that's a decision for you to make. There is no inherent benefit for SEO purposes. There is a potential risk for SEO purposes when the pages that you just remove the links to  

#### [0:20:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1230) |  are actually no longer-- are basically orphaned

pages, and we can't actually get there from somewhere else. Then we might have a hard time to put them back into the rest of the structure of the website even if they are submitted in the sitemap. Sitemaps don't really give us hierarchical information, so that's a thing that is a little tricky. But I don't see navigation links necessarily as being very much superior over a sitemap thing. Because again, if it's in the navigation, it's on every page.  

#### [0:21:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1260) |  And that, again, is kind of non-hierarchical

really. MIGUEL MARTINEZ: Yeah. Unfortunately, it's a flat site architecture very dependent on a legacy platform, and it's to the magnitude of about 1,300 hyperlinks difference between the desktop and mobile versions. MARTIN SPLITT: Wow. So if these pages [? aren't ?] on the sitemap, and you would rather, like, keep the mobile menu lean and remove these 1,300 links, I understand  

#### [0:21:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1290) |  why you want to do that-- I'm

pretty sure this has a performance impact on mobile devices-- then I think this is fine. Just be aware that we might be like, ha, OK. So all of these pages are no longer linked to this other page, so they might not regard them as highly anymore. So it does update the link graph, but just be aware that it does that. And if the SEOs on your team are, like, yes, this is fine,  

#### [0:22:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1320) |  then that's OK. That's not a big

deal. They might think differently. I would understand if they're, like, no, we kind of care about the links being specifically here. MIGUEL MARTINEZ: I do appreciate that feedback. That's very helpful to us. MARTIN SPLITT: Good. That's very, very happy-- or makes me very happy to hear that that was a useful answer. Because these questions, like, I can answer them in a shallow way or in a deep way. And I'm never sure which way to go unless I have  

#### [0:22:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1350) |  the person in the audience. That's fantastic.

Thanks for joining us. Awesome. So we had Dave. We had Miguel. Who else has a question? A few people hanging out just hanging by. All right. I'll check the social networks one more time and see if someone else said something.  

#### [0:23:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1380) |  Oh. A question that came through Twitter

not specifically for the JavaScript SEO Office Hours but good question nonetheless. Someone was wondering-- Ryan, actually, was wondering if there is a different user agent between what we actually do when we crawl, versus when you use the live test, versus when you use the mobile-friendly test. No. They all are using the same user agent. Depending on a little bit on which route it takes to the pipeline, the user agents might differ a little bit, but it's not per tool. It is generally just the way that  

#### [0:23:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1410) |  the crawling infrastructure works. And then they

ask a follow-up question, but why is it that in one tool it looks slightly different than the other? Well, for one, if one tool shows you the desktop version, like the URL inspection tool, if your site isn't mobile-first yet, mobile-first indexing enabled yet, you might see the desktop version where the mobile-friendly test always shows you the mobile version for the obvious reason that it's tailored towards mobile. The other thing is, because of the way that the infrastructure works in the real indexing pipeline,  

#### [0:24:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1440) |  we heavily use caching. But with a

live test, like in the mobile-friendly test or the URL inspection tool live test, you don't want to see the cached version. You want to see what would happen if it would fetch freshly, which also means that we might run into timeouts. That's not because of you. That's because of us. The way that our infrastructure is built, it's not really meant to be doing, like, live fetches, which we are then effectively doing for the tools. So sometimes some resources time out, and then the outcome  

#### [0:24:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1470) |  looks different. So even within the mobile-friendly

test or the URL inspection tool, running the test three times might give you two different results or three different results, depending on how the requests go through. That's not something you need to worry about. That's just something to keep in mind. Sometimes you get false positives as in, like, false things that would get you alarmed about, oh, this part of the content is missing. And then it's just like, oh, actually, the resource wasn't fetched this time. You can always look at what we have in the index  

#### [0:25:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1500) |  using the Search Console, if you use

the URL inspection tool, and look at what we have on the crawled page. You see the rendered HTML from what we actually did when the infrastructure was running, as it was intended, which is the batch processing over a longer time. And then you would see if the content is there or not. That's just something to keep in mind. All right. Anyone else? John. Yes. JOHN CARDINALE: I do have a question,  

#### [0:25:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1530) |  but it's actually not JavaScript related. MARTIN

SPLITT: I'll try. JOHN CARDINALE: OK. And I'll put my camera on to join you. If we have internal links that need to have tracking parameters in them more for political reasons than anything else at this point-- and obviously it's an issue that we've been running into and seeing the tracking parameters appearing even in our Google's index-- is there anything else we can do on our end to kind of help steer Google in the right direction  

#### [0:26:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1560) |  to avoid those pages? MARTIN SPLITT: You

can-- So OK. Are these pages that you definitely want in the index just without the parameters, or is it like you don't want them in the index whatsoever? JOHN CARDINALE: We have our category pages, like top level pages, we want them in the index. We just don't want the actual [INAUDIBLE].. MARTIN SPLITT: Right. You can use the URL Parameter tool in Search Console. That's one thing that you can go. The other thing is you can canonicalize. You can give us a canonical thing  

#### [0:26:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1590) |  like, this, without the weird parameters, is

what we consider canonical. And if that is a strong enough signal, then we would pick that up and actually pick that as the canonical. So that would be what we would show in the search results, rather than the one with parameters. And if you have it in the sitemap and in the canonical that you specify without the parameters, and we see, like, OK, so the parameter one that is linked here is the same content as the non-parameter one, then we would collapse them.  

#### [0:27:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1620) |  And then basically, it's very likely that

we would canonicalize the one without the parameters. No guarantees made, but that's the approach that I would try. JOHN CARDINALE: OK. And that's what we have in place. But I think our issue has been that our top navigation links to pages with tracking. And everything buried in social and everything is always to these tracking pages. MARTIN SPLITT: Yeah. That's unfortunate. And that's a strong signal to use them as a canonical instead. JOHN CARDINALE: All right.  

#### [0:27:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1650) |  Well, thank you. MARTIN SPLITT: You're welcome.

All right. So Miguel, Dave, and John were brave and asked questions. Anyone else having a question? You can also use the chat feature. If you don't feel comfortable voicing your question using voice chat, or if you don't want to turn on your camera, that's fine. There's a chat in this lovely Hangout that you can use to also ask questions.  

#### [0:28:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1680) |  Miguel, another question? IAN CAPULET: I have

a question. MARTIN SPLITT: Oh, awesome. Yes please. IAN CAPULET: So hi, everyone. My name is Ian. So I know this is more centered towards JavaScript. I'm not sure if that's the problem that I'm facing with a particular website, but it very well could be. So let me give you some context.  

#### [0:28:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1710) |  I'm working on a website that we

would consider to be a large website. It's got, like, 25 million pages on it. They have been on Google for quite some time, but they have never been able to get more than, I want to say, about 700,000 pages in the index. So the last thing we did was we compiled all the pages.  

#### [0:29:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1740) |  We made, like, sitemaps. We made a

sitemap index. We submitted that and then waited for a little bit. And then eventually, in the coverage report, it showed up, and it basically said 24 million of those pages were excluded.  

#### [0:29:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1770) |  And then I waited till the coverage

report was updated, which was a couple of days ago. And then I drilled down into it. And it says that these are discovered not currently indexed. So I wanted to see, first of all, if I could get any other information about what that condition tends to mean. And then following that, maybe just talking a little bit  

#### [0:30:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1800) |  about how the site is organized, because

it does use JavaScript in a lot of different places, and maybe it's because of the use of JavaScript that it's sort of got all these pages being excluded. MARTIN SPLITT: Right. First things first, it's not very likely that JavaScript is the reason, but I'll come to what might be the unlikely thing with JavaScript in a moment. Discovered currently not indexed means that we have seen it.  

#### [0:30:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1830) |  We might not have gotten around to

crawling it. That can have various reasons. It can be that we have never actually looked at the page yet because we didn't get around to it. Why we haven't crawled them? Well, there's plenty of reasons for that one in itself. It could just be that your server is responding in a way that makes us believe that we shouldn't be requesting too many pages in one go. It might be that we are predicting based on the pages  

#### [0:31:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1860) |  that we have in the index that

we don't give it as much priority for whatever reason. It turns out the web is really, really big. So we have to start somewhere, and that means that some of the pages might get the attention later. It might also be that we have crawled them. That would usually say, like, crawled but not indexed. So discovered usually just means, like, we are aware that this page exists. We haven't visited it yet. We haven't gotten the content yet. And that's exactly why I don't think JavaScript is your problem, because, if we have never  

#### [0:31:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1890) |  crawled it, that means we have never

even looked at the HTML. So it doesn't really matter if there's JavaScript involved or not if we didn't get around to these pages yet. Could it be that we have-- or should it turn out that we have crawled them but not indexed them, then that is maybe a JavaScript issue in one specific case, which is that the JavaScript somehow does something that prevents us from seeing the content. That can be verified or falsified by putting the URL into the URL Inspection tool  

#### [0:32:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1920) |  and running a live test, where you

get the crawl and the render. And then you see if the content in the rendered HTML looks like what you would expect. If the rendered HTML has all the content that you would expect it, then it's not JavaScript's fault because JavaScript is only involved in the rendering phase. Once we have the content, JavaScript doesn't really matter anymore. If you run into the situation of crawled not indexed, this might also just mean that we have found the content not to be so relevant that we would consider including  

#### [0:32:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1950) |  it in the index, because we don't

include everything in the index. Not every page goes into our index. That's just the reality of it, because it turns out the cloud also has a limited amount of storage. So that's something that you can then only figure out, like, what content do you really care for? And then work on these pages specifically to improve them. IAN CAPULET: OK. Yeah. Because I've sampled pages from the 24 million and just  

#### [0:33:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=1980) |  put them in the inspection tool, and

they came back fine. So yeah. You're probably right. It's not a JavaScript issue. Some of these pages, yes, are thin. It's a website that's devoted to legal documents. Yeah. I mean, like, we have a bunch of pages that list all the companies that are on a case, for instance. And then we have pages for dockets.  

#### [0:33:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2010) |  We have pages that are just, like,

big long lists of PDFs. It's sort of like CourtListener, which is kind of technically-- like, I don't want to say competitor but somebody in the same space. And so it's like-- I guess we're just trying to figure out how CourtListener has, like, millions of its pages already indexed and why it's just taking so long for us to get our stuff indexed. So I mean, like I said, the 24 million  

#### [0:34:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2040) |  just popped up on coverage about, like,

a month ago. And it's slowly going through, like, 10,000 pages every day. It goes up, like, 10,000 into the green. So I'm wondering if it's just, like you said, taking its time. And if that's the case, my only other question is, like I mentioned before, because this website has  

#### [0:34:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2070) |  had pages indexed in Google for quite

some time, is it possible that Google kind of just said, like, this entire website really isn't too important and just started assigning, like, a very small crawl budget to it? And if so, is there a way to tell Google that, no, we're really taking this website seriously. It's mobile friendly now, et cetera. And can you please give it more of a budget?  

#### [0:35:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2100) |  MARTIN SPLITT: That is so-- obviously, we

can't just give everyone the opportunity to say, like, I'm serious about this. Give me more budget. Because then everyone would do that, which is exactly the problem we have with the priority attribute on sitemaps. There used to be a priority attribute of an [? area ?] like, this is the first part-- everything in my page. All these 25 million pages are first priority, which means none of them are. So that's not how that works. But what you can do is, in Search Console,  

#### [0:35:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2130) |  you can have a look at the

crawl statistics. If you go into Settings, Crawl Stats, you see how much we crawled. And you also should see the trend line. And if the page has been lingering for a while, and we have seen, like, oh, there's not that much content here, so we don't have to assign it a large chunk of crawl budget, then you can try to update your sitemap XML file to kind of say, hey, all of these pages have updated. Would you like to come back and have a look?  

#### [0:36:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2160) |  You can try to request indexing on

the pages that you care most for. That's not really a thing that scales well. But that's a way to at least make sure that some of the more important items are getting into it. And then, over time, we'll figure out, oh yeah, this is actually useful and good content. And then the crawling will very likely also increase given that there are no, like, server issues that would suggest to us that we should probably not be crawling this much.  

![](https://i.ytimg.com/vi/Vy7c1NRC7vo/maxres3.jpg)



#### [0:36:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2190) |  Again, the Crawl Stats Report is your

friend here telling you, like, oh, there's issues with, I don't know, 500s, or 504s, or 502s, or 400s, or 401s, or something like that. 404s are not really a problem. That just tells us that the link does not go to where it should go, and that's not an issue per se, unless obviously it's a case where the URL is not a 404, and you want that included. But yeah, you can have a look at, what does the Google Crawler see? What does the Google Crawler try to accomplish?  

#### [0:37:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2220) |  And then you can nudge it with

sitemaps and probably also nudge it with-- yeah. Like, keeping your important content well linked within the pages and request them for indexing to get them crawled again. IAN CAPULET: OK. No. Thank you. I appreciate that. Yeah. I'm looking at the budget right now. It says it doesn't have any problems with responses.  

#### [0:37:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2250) |  Server stat-- the host status is green.

It's interesting, when the 24 million appeared on the excluded report, there is, like, a spike in traffic. Total crawl requests went up to about 57,000 one day, 58,000, and then it just dropped off again. So I guess it's kind of like maybe Google is aware of it and is just processing it slowly.  

#### [0:38:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2280) |  MARTIN SPLITT: Yeah. It takes time to

process the entire web. Also, out of curiosity, as you are already in the process report, what's the average response time? IAN CAPULET: Average response. MARTIN SPLITT: If you go up, you see two, like, [INAUDIBLE] requests, download size and average response time. That's the interesting one. IAN CAPULET: Yeah. It says 888 milliseconds. MARTIN SPLITT: OK. So 0.8 seconds. That's OK, I would say. That's not a bad metric. Good. OK.  

#### [0:38:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2310) |  IAN CAPULET: OK. MARTIN SPLITT: The quicker

the better. IAN CAPULET: Yeah. Thank you. MARTIN SPLITT: You're welcome. Very happy to help. Ian, was it? Right? IAN CAPULET: Yes. MARTIN SPLITT: Awesome. Thank you very much, Ian. All right. And also, actually, Ian, very nice of you to use the Raise Hand feature. I really like when people do that. I should encourage that more often. IAN CAPULET: [INAUDIBLE] MARTIN SPLITT: Yeah. It's really, really cool because that makes it easier. Like, people usually don't talk because they worry about talking about over someone else.  

#### [0:39:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2340) |  And then the Raise Hand feature's a

really nice way to counteract that. And I see that Kevin has raised his hand. KEVIN FROST: Hey, Martin. Thank you very much for getting the Google Meet and doing these weekly. I know it's a lot just to really get this stuff going. Anyways, so to my question, I did post it in the forum. And I'm a Google Street View photographer for a lot of people. And I've been doing it [AUDIO OUT] MARTIN SPLITT: Uh oh.  

#### [0:39:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2370) |  KEVIN FROST: Go ahead. MARTIN SPLITT: OK.

No it was like you were breaking up, but I know that you asked the question about the 360 photos. Right? KEVIN FROST: Yes. So the question was-- because I was rereading what I had read, and it doesn't really clarify it either. But with 360 photos on the Street View especially on Google My Business listings-- and I don't know if you're the exact person to ask, but I know they don't really have a Street View team. But I thought you might have some clairvoyance on kind of what my issue is.  

#### [0:40:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2400) |  I've had people tell me that metadata

on Google Maps is nothing with 360 photos. It is stripped once it goes there. But then the vice versa, if I'm taking a 360 photo in the middle of someone's showroom floor, especially around their tables, or chairs, or something, and I'm creating a virtual tour for their website, would including all of the actual items inside the photo--  

#### [0:40:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2430) |  obviously, the ones that are very easily

seen-- is it worth putting the item description or the item names inside the 360 photo? MARTIN SPLITT: I'm so sorry. Thanks for the very elaborate explanation and question, but I'm the wrong person unfortunately. I really only know about Google Search. I have no idea about Google My Business or Street View for that matter. And to be honest, I have been taking 360 pictures just out of fun and curiosity because I have a 360 degree camera.  

#### [0:41:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2460) |  And so, like, for people that I

know who happen to have a shop, I sometimes wander by and take a picture for them, so that they get a little bit more visibility in Google Maps. But that's, like, a hobby thing. And I don't know who is the right person to address this. I wonder if there is a support forum for Google My Business. I'm pretty sure. KEVIN FROST: It was a part of the local guide community,  

#### [0:41:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2490) |  but unfortunately, they dropped that and are

saying, well, the Street View program is getting completely reworked at least from my understanding. Other than that, they really haven't clarified it. There is Facebook pages, but it's all community brand. I don't think anyone from actual Google or even Maps team is really on there. MARTIN SPLITT: So if you go to the Ask the Community thing, like the forum kind of situation that they have in Google My Business-- in the Google My Business Help--  

#### [0:42:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2520) |  there are-- Yes, it's a community-driven effort.

But there are community managers from Google who look into these questions as well. And community members of the rank of product expert can escalate this to the community members. And then it should get routed in the right direction. The alternative is you can also use the Send Feedback about our Help Center button in the Google My Business help and ask a question. KEVIN FROST: [INAUDIBLE] MARTIN SPLITT: Sorry? KEVIN FROST: I have asked a few questions in the GMB help desk,  

#### [0:42:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2550) |  because that's kind of what my business

is. I usually do 360 photos for people kind of quarterly with the seasons. And I do the Google My Business management for them. And so usually fixing people's mapping addresses or just kind of affiliated-- OK, your map point's not over there. It's over here, all those kinds of things, a lot of what a local guy does, but doing it for a variety of businesses typically. MARTIN SPLITT: I'm very sorry that I'm the wrong person to ask unfortunately.  

#### [0:43:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2580) |  KEVIN FROST: No. It's all right. I

didn't know if you knew anything about the virtual tours on it as well for a website. So if you're implementing the photos inside their website, if that would change anything or even help with their SEO. MARTIN SPLITT: It doesn't really do anything on the search side as far as I'm aware. KEVIN FROST: OK. MARTIN SPLITT: All right. KEVIN FROST: Thank you. I'm sorry. MARTIN SPLITT: I'm trying my best, Kevin. Sorry. Thanks for asking. KEVIN FROST: How dare you? No. You're good. Thank you. MARTIN SPLITT: Awesome. All right. Miguel raised his hand.  

#### [0:43:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2610) |  MIGUEL MARTINEZ: Hi. Yes. My colleague was

really intrigued by your response and wanted to know if you believed that removing the links that are not accessible or visible to users is a good practice. MARTIN SPLITT: I mean, if they're not visible to users, yes. If they're not accessible to users, yes, I would also probably remove them. I wouldn't necessarily say it's a best practice. But, like, I don't think we value these links as  

#### [0:44:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2640) |  much as people think, because, if users

can't reasonably reach them, then I'm not so sure that Google would necessarily value them highly. That gets us into really tricky waters of, like, what does accessible mean and how does Google determine that? And I can't really answer that one. MIGUEL MARTINEZ: That's fine. MARTIN SPLITT: But I think only having links that are meant for users to actually navigate is a good approach. Yeah. MIGUEL MARTINEZ: Thank you.  

#### [0:44:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2670) |  And if I might be so bold--

in relation to the JavaScript, are links loaded only upon user action using JavaScript called, do those count as part of the link quota on the page if they only load after the JavaScript action? MARTIN SPLITT: There's no link quota. MIGUEL MARTINEZ: Not link quota but as part of the crawl? MARTIN SPLITT: Yeah. No, because if they only exist after a user interaction,  

#### [0:45:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2700) |  we can't really see them. Like, we

are not interacting with a page. So let's say you click on something, and then JavaScript generates a bunch of links that haven't been there before. Googlebot would not really see them, unless they happen to already be in the source code, and they're just hidden, and then they're only made visible, because then we would see them in the HTML. And then we would also follow them very likely. MIGUEL MARTINEZ: So like an aria-hidden versus aria-hidden false? MARTIN SPLITT: Yeah. That wouldn't help because then they're still in the source code, and we extract the links before we  

#### [0:45:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2730) |  even render the first time. And then

we extract them again after we render. So we would probably find them before we render because they are in the DOM. MIGUEL MARTINEZ: Great. Thank you. MARTIN SPLITT: You're welcome. We may choose not to follow them, but we will see them at least. OK. Excellent. Anyone else? We have seven more minutes before I need to wrap this up.  

#### [0:46:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2760) |  Feel free to use the chat or

the Raise Hand feature. I see that there's lots of love for the GMB Office Hour's idea. I'll forward that to the team, all I can do. Actually, I'm not sure. But Alan Kent from our team works a lot with the Google My  

#### [0:46:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2790) |  Business folks. So I think it's AJKent

on Twitter-- AJKent99 or something on Twitter if I remember correctly. Let me see if I can find him on Twitter. AJKent99, I think I might be wrong. And I'm like-- oh yeah. No, that's not him. OK. So I nearly threw someone under the bus who has nothing to do with this. AKent99. I'll put it in the chat as well.  

#### [0:47:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2820) |  That gentleman is from my team, and

he works a bit with the GMB team as well. So you can voice the desire for GMB Office Hours in his direction. Or ask him, because he does the E-commerce SEO Office Hours every now and then or used to do them. I'm not sure if he still does them. So you can pop by on his Twitter account and ask him if he still does the E-commerce Office Hours and what he thinks about GMB Office Hours specifically. That's something that I can at least do.  

#### [0:47:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2850) |  KEVIN FROST: Thank you. I will definitely

follow up with that one as well. MARTIN SPLITT: You're welcome. Happy to help. All right. As no one else is raising their hands or using the chat to pose questions, I would say thank you so-- Oh, no, Anastasia. It is not. You can use the Office Hours here right now to ask a question. Even using chat, that is fine. You can use the webmaster forum, or you can use public Twitter  

#### [0:48:00](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2880) |  not direct messages. I cannot provide private

support. It has to go over the public channels for the obvious reasons that we don't want to give preferential support to any one party. Right. So unless Anastasia does have a question for chat, then I'll happily wait for that to arrive.  

#### [0:48:30](https://www.youtube.com/watch?v=Vy7c1NRC7vo&t=2910) |  If that's not the case, then I

would say thank you very, very much for joining the Office Hours. It has been a great pleasure answering all the questions from YouTube and here in person. I hope that you stay safe and healthy and have a great time and hope to see you again in, I think, two weeks. All right. Bye bye. Always the awkward fumbling for stopping the recording. Here we go.  