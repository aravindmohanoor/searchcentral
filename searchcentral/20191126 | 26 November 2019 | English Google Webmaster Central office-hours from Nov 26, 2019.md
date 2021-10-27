[![English Google Webmaster Central office-hours from Nov 26, 2019](https://i.ytimg.com/vi/VitQGsyurmw/maxresdefault.jpg)](https://www.youtube.com/watch?v=VitQGsyurmw)

## English Google Webmaster Central office-hours from Nov 26, 2019

This is a recording of the Google Webmaster Central office-hours hangout from November 26, 2019. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Watch out for new sessions, and add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



Feel free to join us - we welcome webmasters of all levels!



Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=0) |  JOHN MUELLER: All right, welcome, everyone, to

today's Webmaster Central office-hours Hangout. My name is John Mueller. I am a webmaster trends analyst here at Google in Switzerland, and part of what we do are these Webmaster office-hours, where people can join in and ask any web search, website-related question that might be on their mind. A bunch of questions were submitted already on YouTube--  

#### [0:00:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=30) |  not as many as sometimes. I guess

the holidays are here. So if any of you want to get started with the first question, you're welcome to jump in. Otherwise, I'll just go down the list and see what we have that was submitted. OK, let's see. I guess a complicated one here. "You explained there are several core algorithm changes released  

#### [0:01:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=60) |  in early November. After those rolled out,

there were many different types of sites impacted, so several updates made sense to me. But as a result of one or several updates, many smaller bloggers in certain niche categories were impacted heavily, like grocery sites. And when checking those specific sites, you could clearly see many unnatural links via recommendation widgets and other link-building tactics.  

#### [0:01:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=90) |  For those sites, is it even worth

disavowing those links? It really looks like Google just simply just devalued those links. And, if so, it seems disavowing would be useless. Thanks for any information." So I didn't take a look into any specific site there. So it's kind of hard to say what exactly is happening there. In general, if you look at your site and the way that it's embedded in the web, and it seems like there's  

#### [0:02:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=120) |  really a clear pattern of unnatural links

associated with your site, that could be because maybe you've been doing link building in some kind of, I don't know, weird way. If you've been using widgets to build links, all of the usual kind of things, then that's generally something I'd recommend trying to clean up, regardless of any updates that happened. And cleaning up link-related issues  

#### [0:02:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=150) |  usually involves either cleaning up those links

so that they're no longer out there. In general, that's the best approach. If these are widget links, for example, then sometimes it's as simple as improving the widget so that it doesn't have these links that are in there. That's really the ideal way. It's like removing those links if you think they're problematic. If you can't remove those links, then using the disavowed file is an option.  

#### [0:03:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=180) |  That's one way for us to kind

of drop those links from being used. And, essentially, a third approach that you could also take, depending on the type of link, is to remove or block the page on your side from being linked. So what generally happens is when we have links to a website, we associate them with individual pages. So we have kind of the source of the link and the destination of the link, and with those two endpoints,  

#### [0:03:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=210) |  we know which way these links go.

So if any of one of those signs is removed from our index, if they no longer exist, then essentially that link loses effectivity. So that could be another approach you could take there. In general, usually though, people try to focus on either removing the links from the source site or using the disavow tool. With regards to kind of this general situation  

#### [0:04:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=240) |  where you assume that an update has

been affecting your site based on links to your site, that's something where I would tend to be a little bit cautious before jumping to conclusions, and really take a look at the links for your site to make sure that there is really kind of a pattern of unnatural links there that is really problematic. It's very easy to look at any website that's been on the web  

#### [0:04:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=270) |  for a longer period of time and

to find a handful of kind of weird and unusual links. So that's something where just because you find something weird doesn't necessarily mean that those links are negatively affecting your site. It might just be that these are kind of the usual kind of crufty links that get collected over the years. But if you do find a pattern of really significant, unnatural links to your site, then that's something I'd recommend cleaning up before maybe someone from the web spam  

#### [0:05:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=300) |  team takes a look at it manually

and then applies a manual action to clean it up for you. AUDIENCE: So a significant amount of links? So if it's, like, only like maybe 10, 20, it doesn't matter, right? JOHN MUELLER: It's hard to give an exact number. It's really something where if you look at the website overall and you see that this is a really significant and clear pattern there that's repeated across most of the links there,  

#### [0:05:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=330) |  then that's something I would take action

on. AUDIENCE: OK. JOHN MUELLER: All right. Then a question about the crawl stats in the old Search Console. "When I compare the URL counts from crawl stats in the old Search Console to my access logs, there are lots of differences."  

#### [0:06:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=360) |  So lots of details there. And, "Why

is that? How are these stats counted? What's typically included? What about rendering? What about other kinds of bots that access pages?" Now, good question. I find it really hard to kind of reproduce those counts because of the way that they're compiled, and I suggest and suspect that's what you're seeing there, too.  

#### [0:06:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=390) |  So that might be something where it's

really tricky to try to understand the kind of exact connection that you're seeing now. In general, what happens there is we include all of the axes that go through the infrastructure that Googlebot uses, which does include Googlebot. It does include rendering. It includes robots.txt access or includes sitemap accesses.  

#### [0:07:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=420) |  It also includes some of the other

bots that are out there, like the ads bot, for example. So it includes a lot of different things. It's not just HTML pages that we request. In general, I find looking at the aggregated logs like this is kind of useful in the sense that it gives you a bigger picture view of your website overall--  

#### [0:07:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=450) |  how many requests are being made, how

fast those requests are being responded to-- which is something that you often don't see as clearly when you look at just the HTML files, for example. So that's something where I find it useful overall to look at these, though it makes it trickier if you're also looking at your log files and trying to compare them. I imagine, in general, if you're looking at the log files  

#### [0:08:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=480) |  and you see what kind of requests

fall into this, then that's something where you'll see the trends are generally the same. Depending on what you're tracking, you might also see the speeds or the file sizes that are involved there, which help you a little bit to understand what all is really happening there. So that's something where it's hard to track that back one to one to specific requests that are made. And for the most part, it's something which probably  

#### [0:08:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=510) |  doesn't make too much sense. Let me

see. All of the things that you mentioned there, JavaScript API calls renderings CSS images. All of that is in there. What is not included in there, you mentioned in one of the questions, is like with different domains. So that would not be included there. So, for example, if you have one HTML page, and it has all of the maybe hundreds of images, but the images are hosted on a different domain,  

#### [0:09:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=540) |  or different hostname, then those would not

be counted there. Those would be counted on the other domain. So, similarly, if you turn it around, if you're the CDN for a number of websites and they include lots of images that are hosted on your CDN, and you don't have any HTML pages at all, then we'll still show those counts as being requests made to your website and show that in the crawl stats data. So that's kind of from that.  

#### [0:09:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=570) |  One thing I thought I would mention,

just because it's the crawl stats, someone put together a really nice bookmarklet that lets you download these stats as CSV files, which makes it a little bit easier to track them over time. It still doesn't make it easy to map one to one to individual requests, but at least you can download the numbers and put them into spreadsheets.  

#### [0:10:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=600) |  AUDIENCE: Hello, John. JOHN MUELLER: Hi. AUDIENCE:

Fine, thank you. Thank you for answers on my question, a lot of information. Thank you very much. I'm not much smarter about this, but thank you for your time. Can you tell me if you plan to, or your team, plan to take growth stats to a new Google Search Console?  

#### [0:10:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=630) |  Or will it be there in some

different, I don't know, report or something? JOHN MUELLER: I don't know. Personally, I'd like to keep everything that's still available in the old Search Console, but I imagine the Search Console team has to make some hard decisions along the way. What might happen is that we could take these reports  

#### [0:11:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=660) |  and integrate them into something a little

bit easier to understand or a little bit clearer and actionable. So one thing that people have been asking about a lot, for example, is crawl budget. Maybe it makes sense to create some kind of a report around crawl budgets. And if we did that, then maybe it makes sense to take these crawl stats and include them in a way that makes them a little bit easier to understand. I don't know if that's something that is lined up  

#### [0:11:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=690) |  or will be happening anytime soon. But

these are always discussions that we have. And part of the directions that we end up going for these kind of features, it really depends on what kind of feedback we get back from you. So if that's something where you see this as really useful, and you can give us information on how you're improving the web overall by using this feature or by using this kind of data, then that makes it  

#### [0:12:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=720) |  a lot easier for us to go

back to the engineering team and say, hey, this is really critical. We need to make sure that we build this out rather than that we build it back. So any kind of feedback or tips or ideas that you have around that is always useful. AUDIENCE: OK, I will definitely email you that information from me. Thank you. One information, just a note-- the bookmarklet, I really love it.  

#### [0:12:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=750) |  And I used it for the data

in my comments. So it's really useful for me too. And can I have one additional question about the topic? JOHN MUELLER: Sure. AUDIENCE: I would love to know how do you or I can tell that the website, or some website, has problems with the crawl budget. Typically, I can see that from--  

#### [0:13:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=780) |  or I can find it out when

the mean of the duration time is something like very high or something or a lot of URLs which aren't useful are downloaded and crawled. And maybe in some report, a discovery report-- I think it's called discovery report-- there is some column with URLs which are discovered, but not  

#### [0:13:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=810) |  crawled, I think. I'm not sure about

it, about the right name. So are there any other possibilities to find out the website has some crawl budget issues? JOHN MUELLER: Now, in general, most websites don't have issues with the crawl budget. So that's always the tricky part, in that everyone is kind of worried about this or at least  

#### [0:14:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=840) |  the people who know about it. And

most websites don't need to worry about this. Let's see. So one way to kind of see what is limited there is essentially if you see that the amount of pages that are being crawled doesn't match the amount of content that you think you've been changing on your website. So, for example, with a news website,  

![](https://i.ytimg.com/vi/VitQGsyurmw/maxres1.jpg)



#### [0:14:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=870) |  if you look at your server logs,

and you see Googlebot is crawling one-third of all of the news articles that are put out on any given day, then that's pretty clearly signed that we're not able to keep up, but that's sometimes really hard to determine. So the two approaches that I usually recommend is, on the one hand, looking at the speed that it takes to download individual pages, like you mentioned. If that seems fairly high, then that's  

#### [0:15:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=900) |  often a sign that where we'd like

to be able to crawl more, but your server is kind of slow. So we're not able to do as much as we could. The threshold there for fairly high is hard to say. So it's something where smaller websites, if they're fairly slow, then that doesn't matter so much because we get as much content as we need anyway. But larger websites, if they're fairly slow,  

#### [0:15:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=930) |  then it does matter quite a bit.

The numbers I see when I look across, like, various web sites, usually the websites where we tend not to have that much trouble with crawling, I see speeds, I don't know, between 100 and 500 milliseconds per request. So that's not per page that is rendered in Chrome, but rather per request made to the website, which includes things like the CSS files, JavaScript files, et cetera.  

#### [0:16:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=960) |  And sites where I see issues with

regards to the crawl speed, usually the time per request is, I don't know, towards two seconds or higher. So those are kind of-- I mean, it's not that we have fixed thresholds there. This is more just anecdotal from what I've seen. So that's kind of the one thing, and the other aspect is server errors.  

#### [0:16:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=990) |  That also plays quite a bit into

when we start to slow down. So if we see a lot of 500 errors or 503 errors, then usually what happens is, over time, we tend to slow down. So that's something you can pretty clearly see in your server logs. In Search Console, it's a bit tricky to see as clearly, but definitely in your server logs, you can track the number of 500 type errors and see if that grows, or if you have spikes there,  

#### [0:17:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=1020) |  or if that's, like, a fairly high

threshold, because, ideally, your server shouldn't be returning 500 errors regularly. That should really be something that's more of an exceptional thing. So those are kind of the two aspects that play into kind of how much we can crawl. And the other aspect with regards to how much we want to crawl, that's something you can also control, which kind of goes into, I think in the coverage  

#### [0:17:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=1050) |  report, what you mentioned, the discovered but

not crawled URLs. And usually looking at those, one way to tell if there's an issue is to kind of look at the pattern of those URLs. If those are all URLs that seem reasonable, that are kind of like clean URLs in the way that you have your canonical shape, then that seems like something where probably we could be crawling a little bit more. If those are all your URLs where it looks from the URL structure  

#### [0:18:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=1080) |  that they're kind of non-canonical URLs-- so

maybe you have parameters attached to them. Maybe you have filtering and sorting parameters or just generally long and complicated URLs that you know are not the ones that you would have specified as canonicals. Then if we don't get to crawl those, that's usually less of a problem. But that could be a sign that you're linking to those somewhere within your website. And yeah, all of that kind of flows  

#### [0:18:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=1110) |  into this complicated topic of crawl budget.

So on the one hand, if we can't crawl everything that you're producing, that's definitely a bad sign. If you're linking to a lot of URLs that don't necessarily need to be crawled, that's something that you can improve, kind of reduce the number of URLs that you push to Google. If you're seeing that the speed is fairly low, that the latency to fetch a single request-- to process a request is fairly high,  

#### [0:19:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=1140) |  that's something you can do. And if

you see a lot of server errors, that's also a sign that we're probably crawling less than we could. So now, lots of complicated things. And like I said, for the most part, kind of, I'd say, small to mid-sized websites, this is not something that you really need to worry about. It's [INAUDIBLE]. AUDIENCE: You were mentioning speeds, the beta speed that's in Search Console right now.  

#### [0:19:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=1170) |  Is that right now on AI and

just kind of understanding what's happening with websites where they are in terms of seconds, milliseconds, and then you're going to take that as the ranking factor? JOHN MUELLER: That's-- AUDIENCE: I mean, it's a-- JOHN MUELLER: That's got to be a different kind of speed. That's the speed to actually view a page. AUDIENCE: Yeah. JOHN MUELLER: And I believe that's just based on the Chrome user experience report data, which is essentially what users have seen in the wild.  

#### [0:20:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=1200) |  So that wouldn't be related to the

crawl budget-type questions. That would be something different. And especially on mobile, we do take speed into account for ranking. So that's something-- if your pages are really slow, and you see that in the speed report, then that might be worth trying to find ways to improve. But the speed and the speed report wouldn't be related to the speed of-- or wouldn't be related to the crawl budget-type questions.  

#### [0:20:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=1230) |  AUDIENCE: I have another question to the

throttling topic. JOHN MUELLER: OK. AUDIENCE: You said about crawl budget. Now, when I see that you're crawling on a page, and we don't get any 500s, does that mean that you crawl as fast and as much as you want, and at some point, you just stop? Is that, like, an indicator we can look in our server logs?  

#### [0:21:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=1260) |  JOHN MUELLER: Not necessarily. So usually what

happens is we make a plan to crawl a collection of URLs from your website per day. And I don't know. These might be, let's say, 10,000 URLs that we'd like to crawl. And we don't try to call them all at once, but, rather, we spread them out over the whole day. So it's not that you would see a pattern of us crawling in the morning and then stopping,  

#### [0:21:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=1290) |  but rather we would crawl kind of

spread out. And the main reason for that is because we don't want to overload your server. So if we were to crawl all of these URLs at once, then that would be a pretty high load on your server. Whereas if we can spread them out more, that makes it a lot easier. And especially if the server is a little bit slow so that we end up having multiple concurrent requests, like, requests that happen at the same time, then that's something we want to avoid.  

#### [0:22:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=1320) |  So we tend to spread things out

if we see that things are just slower than we would have expected. AUDIENCE: Yeah, I'm thinking about it because our service, we are scaling based on our load. So when you would try to crawl us, I guess we would just scale. And so the question would be if you would notice that and stop them or throttle down, or would it still go up?  

#### [0:22:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=1350) |  JOHN MUELLER: So we try to do

this on a per-day basis and look at the whole day, kind of looking back to see how the day went and then, based on that, plan for the next day. So that's something where if you're kind of scaling up in between on the day and some periods are faster, some periods are a bit slower, that's generally OK, as long as the aggregate over the whole day  

#### [0:23:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=1380) |  is kind of within that range where

we'd say, well, this is still reasonable. We can still crawl more. And you'll see, kind of day by day, the speed go up when we think we can crawl more and when we want to crawl more. AUDIENCE: In a 2017 blog, you stated that, basically, increasing the speed will increase the crawl rate. JOHN MUELLER: If we have enough demand for more URLs, then we will try to crawl more, yeah.  

#### [0:23:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=1410) |  AUDIENCE: OK. JOHN MUELLER: So that's kind

of the one thing. The one thing I do want to caution here, though, is that it's very easy to focus on this and to say, the crawl rate is really important. For ranking, it's not necessarily the case that being crawled more often means that you will be ranked better. So I wouldn't see this as a ranking factor, but really mostly as a technical kind of thing where if you're changing your content, and you want that change to be  

#### [0:24:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=1440) |  reflected in the search results, then being

crawled fast enough for that is kind of what you need. Whereas if you're not changing your content, then it really doesn't matter how quickly you're being crawled. So you don't need to kind of push Google to crawl more just because, like, more crawling is better type of thing. It's really not the case that more crawling means higher ranking.  

#### [0:24:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=1470) |  AUDIENCE: OK, thank you for your response.

I saw a few websites which started to use AMP, And this is to think of a crawl budget still. And the stats in crawl budgets looks like the count of AMP typically grew a lot. Like, the crawl budget for AMP is different to the crawl budget of the website.  

#### [0:25:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=1500) |  It looks for me like this. Can

you say something on the topic, like AMP and the crawl budget? JOHN MUELLER: That wouldn't change anything. So those would be normal requests that we would make. I could imagine that maybe AMP pages are smaller files, so they can be transferred faster, which means we could crawl them a little bit better. It could also be the case if you have a separate AMP subdomain,  

#### [0:25:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=1530) |  and you're looking at just the crawl

stats for that subdomain, then those would look better because it's easier to serve maybe static AMP content versus kind of the dynamic, full HTML content. But essentially, when it comes to crawling, we don't special case anything around AMP or normal HTML pages. AUDIENCE: OK. Sounds fair to me. Thank you. Thank you. JOHN MUELLER: Sure.  

#### [0:26:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=1560) |  All right, let's see. Question about Search

Console. "On the one hand, we have for property about 3,500 pages, valid pages, 1,900 indexed and 1,600 sent and indexed. In coverage on the mobile usability, we only have 1,400 valid pages and 55 errors.  

#### [0:26:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=1590) |  As we had until the beginning of

October 2 with desktop and a mobile site, then we switched to dynamic serving. I would expect that this should clear out the difference in counting the valid pages, but it's still there. Can you explain to me where this difference is coming from?" OK, so I think one of the big challenges with the aggregate reports in Search Console,  

#### [0:27:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=1620) |  the mobile usability one, other reports as

well, like, the rich results or the AMP reports that are there, is that they focus on a relevant sample of URLs from your website. So if you look at the coverage report, that includes all of the URLs that we have indexed for your website, so not just kind of an irrelevant sample of them, but rather really everything across the whole index that we have.  

#### [0:27:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=1650) |  And that means that it's hard to

compare the total numbers. So the coverage report might say, like in your case, maybe 4,000 valid indexed pages. And if you look at the mobile usability report, the total might be 2,000 or 1,000 valid pages, and that's not the case that the difference is not mobile friendly or mobile-- kind of matching the mobile usability criteria, but, rather, we took a total of 1,000 pages  

#### [0:28:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=1680) |  from your website, and we reviewed those

specifically for these criteria. So that's something where you might see kind of like the 4,000 that we have indexed, 1,000 we checked for mobile usability issues, and of those 1,000, some of those will be kind of valid with regards to mobile usability. And some of those might have individual errors with regards to mobile usability.  

#### [0:28:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=1710) |  So that's something where adding up those

pages from an aggregate report that generally won't give you the totals of the actual crawl or the actual indexing report. In general, since we take try to take a relevant sample of those pages, if you're seeing minimal amount of errors on the sample that we show on that aggregate report, then that's generally a sign you're OK. So that's not something where I would worry about and say, well, what about those other URLs that are not checked?  

![](https://i.ytimg.com/vi/VitQGsyurmw/maxres2.jpg)



#### [0:29:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=1740) |  Does that mean that maybe they're all

bad? And usually what happens is that that relationship kind of stays the same, and that's most of them, like in your case, they're OK. Maybe a small part are not OK. The other thing that is specific to the mobile usability report is that we determined the mobile usability based on rendering those pages.  

#### [0:29:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=1770) |  We have to render those pages in

a way that matches what a user would see in their device, and sometimes that doesn't work out. So sometimes things like the CSS file we can't fetch properly or the JavaScript file we temporarily can't fetch. And even if that's just a sample of all of your index pages, sometimes that can happen. And with that, you will always see kind of a small amount of issues with regards  

#### [0:30:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=1800) |  to mobile usability in that report, which

are probably mostly based on just kind of temporary fluctuations in our ability to fetch individual pieces of content. And you can double check that by going to the mobile usability report and taking some of the errors that you see there-- do a live test. And if you do a live test, and it says, oh, OK, then that's generally a sign that this was probably just some kind of fluke  

#### [0:30:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=1830) |  with regards to the testing, some kind

of flakey testing that that was happening that isn't really something that is actionable for your side. So in particular, specifically with regards to the mobile usability report, I would not assume that this is something where you can trivially get the number of errors that we showed down to exactly zero, just because some amount of flakiness with regards to requests made to a server, that  

#### [0:31:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=1860) |  is kind of natural. That happens anyway.

That doesn't affect indexing. If it were to affect the HTML pages, we would just refresh those and try to get that again. So it's really only with regards to the mobile usability report there. So that's one thing kind of to keep in mind there, that some of these errors might not be actual errors as much as they could be kind of just fluctuation in the network connections that can sometimes happen.  

#### [0:31:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=1890) |  Let's see. OK. An easy linking question.

"In your opinion, which ultimately is best to use when doing internal linking, absolute or relative URLs?" Ultimately, I mean, your site has correctly implemented canonicals and has a single uniform domain being used and no domain issues. So in that theoretical case where  

#### [0:32:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=1920) |  you have a theoretically perfect website, then

it doesn't matter at all if you use absolute or relative URLs. So from that point of view, use whatever is easier for you. Oftentimes, relative URLs make it easier to test things locally, so maybe that's better. That's not something I would really worry about there. So I really would leave it up to you.  

#### [0:32:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=1950) |  And if I were working on this

website, I would just see which of these ones were easier in the specific case with whatever CMS I'm working on and just kind of use whatever makes sense there. In the case where your website is not this theoretically perfect structure, which probably most websites are not, then working with absolute URLs, if you can make sure that they really point at the canonical versions of all of the URLs  

#### [0:33:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=1980) |  that you have, probably makes a little

bit more sense because then you don't have to worry about things like, what if Google or some user ended up accessing the non-WWW version of your website and it was loaded. With absolute URLs, we always find our way back to your preferred version. In practice, you can also work around this by using the rel canonical, and we can generally figure that out there anyway.  

#### [0:33:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=2010) |  So in the theoretical perfect situation, use

whatever makes sense. In the kind of realistic situation, I'd still say use whatever makes more sense for you. One thing that sometimes comes up is that people try to use absolute URLs as a way to kind of fight against scrapers. And from my point of view, that doesn't really work that well in that most scrapers know  

#### [0:34:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=2040) |  how to deal with URLs. So absolute

or relative, they'll get around that anyway, and probably there are smarter things that you can do to kind of work against scrapers if you're seeing that's happening with your website. Let's see. "How to remove the content of the expired domain from Google. If the user publishes expired domains content on its own site or another one, how would Google treat it?"  

#### [0:34:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=2070) |  So I'm not quite sure which direction

those questions are going. In general, if you take over an expired domain, and you want to kind of start fresh with your new content, then, essentially, you just make sure that the old content returns 404, and over time as we re-crawl those old URLs and see that there is none of the old content left anymore, then that will be reflected in search.  

#### [0:35:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=2100) |  I would not recommend using the URL

removal tool for this. In particular, don't use a URL removal tool for your old domain because it will not reset your domain. It will just hide the old domain from search, which means as you publish new content, that will be hidden as well. So don't use a URL removal tool if you're just taking over an existing domain. So that's kind of the one side there. On the other hand, if your domain expires and you forgot to renew it, and you'd  

#### [0:35:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=2130) |  like to keep publishing the content, then,

ideally, what you would do is-- I mean, in the ideal situation, you would set up redirects to the newly hosted version of that content. If the domain has expired in the meantime, then you can't set up redirects. And in a case like that where you can't set up redirects, then, essentially, your copies of the old content  

#### [0:36:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=2160) |  are essentially new URLs on the web,

and our systems have to discover them first. We have to find links to those pages. We have to crawl them. We have to index them, like any other piece of new content. So there's really no way for you to say, without setting up redirects or without using things like rel canonical, that this new version of the content replaces the old one. Instead, what we will see is, well, there is a version of content here, and the old version is gone.  

#### [0:36:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=2190) |  And we see something new. Something has

gone away. It's not really clear to us that the something new should replace the thing that went away. So that's kind of an unfortunate situation if you let your domain expire and then decide that, actually, you do want to keep the content indexed. AUDIENCE: I have maybe a question related to that. JOHN MUELLER: OK. AUDIENCE: It's now about the whole web page.  

#### [0:37:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=2220) |  When a lot of URLs get indexed,

but they shouldn't, and afterwards the whole folder is blocked by robots.txt, how can you get those URLs indexed without changing the robots.txt? JOHN MUELLER: So you want to get those URLs indexed, or you don't want to get those URLs indexed? AUDIENCE: No, they are indexed, but I don't want them to be indexed. And that's quite a lot of URLs.  

#### [0:37:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=2250) |  JOHN MUELLER: OK. So with the robots.txt,

we would not crawl those pages. So if you have a noindex there, or if you have server side authentication, then we would not see that. So that's kind of one problematic thing there. What generally happens is if these URLs are blocked by robots.txt, then, over time, we will only index the URL, not the content anymore.  

#### [0:38:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=2280) |  So if someone searches for something that

used to be kind of indexable under that URL, then, at most, what might happen is we show the robotic URL in the search results. Usually, this is less of an issue because if these are topics that you actually care about, then you would have a version of content on your website that is indexable with more information. So like, for example, if you have  

#### [0:38:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=2310) |  a page about, I don't know, blue

cars, and you have one version blocked by robots.txt and one version that is still live, if someone searches for blue cars, we might know, based on maybe links to the robotic page, that this is also a blue car page. But we definitely know that the version that you allow us to crawl and index is about blue cars. So that would probably be the one that we would prefer anyway. So if there is a version of content that is crawlable and indexable and one that is blocked by robots.txt, then probably we  

#### [0:39:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=2340) |  would just show the one that is

crawlable and kind of indexed already. If you need to get those old your URLs out completely, so that if someone does like a site query and explicitly looks for those URLs, then you would need to use the URL removal tool. The URL removal tool can be done on a folder level or kind of a prefix of a URL level or on an individual URL level.  

#### [0:39:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=2370) |  For a lot of URLs, if you

have several thousand URLs, then you would try to find a folder or a prefix that would work to remove all of those URLs. If this is a really urgent situation and you have some URLs that are actually indexable within that folder as well, then that's kind of a call that you might have to make where you would say, well, maybe I removed the whole folder, even though I know  

#### [0:40:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=2400) |  there's some content I actually still want,

just to make sure that the critical content that I definitely don't want to have indexed is also removed from search. So that's kind of a, I don't know, rare situation that we don't see that often, but that can happen as well. AUDIENCE: OK, thanks. Another question related to that, would go also on the crawl budget?  

#### [0:40:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=2430) |  JOHN MUELLER: If it's blocked by robots.txt,

no. AUDIENCE: Thanks. JOHN MUELLER: If the URL is blocked by robots.txt, then when we would not count out as something that we tried to crawl. AUDIENCE: Oh, OK, cool. That means over time, let's say half a year or something, those URLs would also be automatically a noindex because you can crawl them? JOHN MUELLER: Not necessarily automatically noindexed, especially if we find links to those pages.  

#### [0:41:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=2460) |  So if we find a lot of

links to those pages, what will happen is we will index just the URL, and we might show kind of as a title in the search results something from an anchor to that page. So that's something that can happen, but like I mentioned, if you have normal content for that topic, then we would probably prefer that over the robotic page. AUDIENCE: All right, thank you. JOHN MUELLER: Sure.  

#### [0:41:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=2490) |  "I noticed that Chrome console is listing

scripts that are not using the same site attribute, that those are blocked and recommending more about it here. So there's a link to Chrome status, I think, blog post. Can you explain what the harms are of not doing anything in this case?" So I had to look at this post as well to kind of see what exactly is changing here.  

#### [0:42:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=2520) |  But it looks like it applies mostly

to cookies. And that's something that generally, from a search point of view, doesn't play a big role. We don't keep cookies for individual pages. So we wouldn't forward those cookies or reuse them. So that's something-- from a crawling and indexing point of view, essentially it doesn't play a role for us. It can affect how users see your pages, of course.  

#### [0:42:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=2550) |  Any change in the common browser can

affect how users see your pages. So it's not something I would completely ignore, but I wouldn't see it as something that is specific to search. One thing also to keep in mind here is that for Google rendering, we're using kind of the evergreen Googlebot now, which means we update the Googlebot Chrome version regularly as well. So similar to you, when you get that warning that there  

#### [0:43:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=2580) |  is a new version of Chrome available,

Googlebot gets updates as well. And if there are changes in Chrome that affect how a page is viewable, then that would affect Googlebot rendering as well. So for example, the kind of-- what is it? One of the changes recently about HTTPS-mixed content, that's something that, generally, I think has been like that in Chrome for a longer period of time.  

![](https://i.ytimg.com/vi/VitQGsyurmw/maxres3.jpg)



#### [0:43:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=2610) |  But if that were to come completely

unexpected from one day to the next that users in Chrome wouldn't be able to see your images, for example, then that would also mean that Googlebot would not be able to see those images and would not be able to render those pages that use kind of that functionality which is now blocked in the browser. That would also be blocked for Googlebot as well. So on the one hand, these things primarily play a role with regard to your users.  

#### [0:44:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=2640) |  On the other hand, if this functionality

is critical for finding content that is indexable for your pages, then that could play a role for rendering as well. I feel that's kind of a confusing answer. Maybe I need to rephrase that at some point. "I am looking to improve the visibility of my product pages. Many of our PDPs include a large number of images, which each include large amounts  

#### [0:44:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=2670) |  of explanatory text with them. So my

concern is that the associated text, while great, might be diluting the identity. In a lot of cases, the h1's are generally too generic, and the text below, in terms of source delivery, provides better clarity about what the product actually is. Do you think moving the images down and the relevant text up would help Google to better interpret the focus of each of these pages?" So just shifting the location of content within an HTML page,  

#### [0:45:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=2700) |  I don't think that plays a big

role at all. Headings are useful in that we can take a heading and see which images and which text kind of applies to that heading. But just shifting around things with HTML or with CSS, I don't see that playing a big role there at all. So in that regard, I wouldn't really worry about this. One thing I did notice when looking at that example page  

#### [0:45:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=2730) |  that you linked to is that when

I load it up, after a certain period of time, it switches to kind of a country picker interstitial. And I don't know how your kind of triggering this and if you trigger this in all locations. But, for example, if you were to trigger this when Googlebot crawls and renders your pages, that might also result in Googlebot not being able to index your pages properly. So that's one thing you might want to double check.  

#### [0:46:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=2760) |  In general, I recommend using kind of

like a banner instead of an interstitial when it comes to things like country or language figures, because if you're using a banner, then even if that does end up being rendered in Google systems, then it wouldn't block the indexing of the rest of your content. Whereas if you have an interstitial that, in the worst case, kind of takes out all of the old content and replaces it with this kind of country or language picker,  

#### [0:46:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=2790) |  then we might not have much content

left on that page for indexing. OK. Let's see, one more question, because it's a source-related one, I guess. "We're fixing a website with a CH domain. We have a well-running clone under a dotcom domain. If we take the CH domain offline for a few weeks and redirect all its traffic to the dotcom domain, what effect does this have on search and ranking?"  

#### [0:47:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=2820) |  So I assume taking it offline and

redirecting happens at the same time. Whereas if you take a domain offline and then, after a certain period of time, then you finally end up redirecting, then that that's a little bit trickier. But, generally speaking, if you just redirect, then we would see that as a domain move and try to move all of the signals that we have for the old domain for the CH domain to the dotcom domain.  

#### [0:47:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=2850) |  And that's something where if you don't

change the structure of your website, then, generally, that's easy for us to process. You can use the site move tool in Search Console to tell us a little bit more about that. But generally we can do that fairly quickly. The one thing I would watch out for here is you're going from a country-level domain to a generic domain. So the CH is specific for Switzerland, which means there is geotargeting happening,  

#### [0:48:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=2880) |  specifically for users in Switzerland when they

search for local content. And with the dotcom, by default, that's kind of generic. So that could be geotargeting any specific country. So what I would recommend doing here-- if you're moving from a country domain to a generic domain, make sure you definitely have the geotargeting settings set in Search Console. And like with all kinds of moves, double check all of the other things that we have listed in the Help Center as well. So there are some things which are kind of obvious that  

#### [0:48:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=2910) |  get forwarded there as well. But things

like the ownership, make sure that you have all of those transferred, all of the settings transferred to the new domain. If you have, like, the parameter handling settings setup, if you have any specific removals that are setup, make sure you have all of that moved over to your new domain as well. So that's kind of what I would watch out for there. With regards to the overall effect on search and ranking,  

#### [0:49:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=2940) |  in general, a kind of one to

one domain migration is pretty easy for us to process and shouldn't have a visible effect. You might see a few days where things are shuffling around, But generally speaking, that should kind of settle down fairly quickly. But it's not guaranteed. So in particular, if the new domain has a really different history associated with it or really different settings associated  

#### [0:49:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=2970) |  with it that take a longer period

of time to kind of settle down again, then you could see effects where we would shift over to your new domain, but your site overall on that new domain is not as visible in search as it used to be. On the other hand, it can also happen the other way that maybe you have a really good domain or your old domain is really bad, and you're moving things over. Then maybe things are a little bit better. OK, so maybe it's time to switch over to questions from you  

#### [0:50:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=3000) |  all as well. It looks like there's

a bit of a back and forth happening in the chat. What can I help with? AUDIENCE: So-- JOHN MUELLER: Go for it. AUDIENCE: So can I still ask the same question regarding that site? Like, if its ranks for its own name, is that still OK? I mean, it ranks for its own name, but it doesn't rank for keywords, so it's obviously very suspicious.  

#### [0:50:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=3030) |  And at the same time, I've also

noticed that Cloudflare has been blocking certain things from the CDN. And I also recall a chat that you had on Twitter with Eric Wu, I think, mentioning that Cloudflare does block Googlebots, and so I've disabled all that stuff. But I'm noticing now that the CDN is blocking particular things, CSS, within the site.  

#### [0:51:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=3060) |  But I'm seeing, like, now the site

ranking for its own name under its own. So I don't know. I mean, what is happening here. Is it going to be also Cloudflare that's blocking. JOHN MUELLER: I say probably not because these kind of technical issues with regards to the access are more specific with regards to indexing the actual content. AUDIENCE: But it's very frustrating, because I'm seeing other major local brands  

#### [0:51:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=3090) |  that I look at ranking fine with

the mobile and desktop. It can't be that this is the only one, John. JOHN MUELLER: Of course not. I mean, it's something-- so I think maybe, just generally, in a case like this where you're seeing the content being indexed, and it's the same content that's used for the mobile and the desktop version-- so you don't have, like, an mdot version of the page--  

#### [0:52:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=3120) |  then I wouldn't worry about those kind

of technical indexing, blocking, type issues because that essentially means we're able to index the content. And we index the content once for desktop and mobile search. So it's not that we have like a desktop version index and a mobile version index. If we can't get one, then suddenly it doesn't rank in that one anymore. If it's indexed, then, essentially, it's indexed. That doesn't mean that maybe we could  

#### [0:52:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=3150) |  crawl better if the hosting environment was

set up differently. That's kind of a different question. For smaller sites, like I said, usually that's not a problem anyway. And what I recall from Cloudflare, I don't know which thread you're referring to, but what I recall from-- AUDIENCE: There was a WAF. There was a WAF. Yeah. JOHN MUELLER: Yeah. What I recall there is that they do block bots that  

#### [0:53:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=3180) |  act like Googlebot that are not actual

Googlebot, and from our point of view, that's fine. So in particular, if you're using some kind of tools to crawl a website, and you're using a fake Googlebot user agent, then if the hosting environment blocks that, then that doesn't really affect us, as long as the real Googlebot is able to get through. So that's kind of that side there. But in general, when it comes to desktop and mobile,  

#### [0:53:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=3210) |  especially for things like local businesses, there

are sometimes significant differences in the way that they're visible in the search results. And sometimes that plays a role with kind of the elements on a page, things like how many maps entries can we show for these queries. That's something that you would also see in Search Console where the ranking would essentially take those elements-- [CRASH] --into account as well.  

#### [0:54:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=3240) |  Something is breaking. AUDIENCE: How is it

OK, though, for their competitors to rank both on mobile and desktop with very even search positions, which is one to one? There's no differences between their competitor's search and mobile and desktop. I've been doing this 17 years. I live this life, right? I do believe it's still technical error. I literally-- JOHN MUELLER: Yeah, I could definitely take a look at that again.  

#### [0:54:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=3270) |  But it's really something where there are

just differences with regards to how people search on desktop and mobile. And that is something that is reflected in the search results. So kind of the elements that are shown, sometimes the ranking, the understanding of the query, it can differ quite a bit. And especially when you're looking at queries that don't have a lot of impressions, then looking at the data in Search Console can be a bit tricky because it's like, when there is an impression, because someone was searching for it,  

#### [0:55:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=3300) |  then suddenly there is that there. When

there is no impression, or people are searching for it, kind of like in a non-local way, then that might be that there is there's a different kind of data there, which makes it really hard to double check. So especially with local businesses, if you're looking at things like local-related queries, then that can be really tricky to check when you're not in that specific location. So take a query like, I don't know,  

#### [0:55:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=3330) |  some kind of business near you. That's

something that people might do on mobile, where they expect things that are really close by. But if you're in a different town, or in a different country, and you try that query, then that's something where you would see drastically different results. And that's kind of normal, and in Search Console, if we see that site mentioned somewhere in the search results, we would still track that as an impression, even though it's not necessarily an impression from a user  

#### [0:56:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=3360) |  that you would care about. AUDIENCE: So

even if you click on a query out of 55,300,000, like "flowers Toronto," and I see the first result on mobile number one and the desktop is also number one, and that's a very competitive query, that query is less than a million search. It's a very small town. But anyhow, I see it as an issue.  

#### [0:56:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=3390) |  And I don't know. It's frustrating when

everything is done correctly, the speed is correct, even though I'm not sure why, but the speed is showing low. The desktop pages are showing low. I mean, that they're not fast. Clearly in Page Insights, you see they are in milliseconds and also in Lighthouse as well. I don't know. I'm just frustrated. This is the first time I've been frustrated in, I think,  

#### [0:57:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=3420) |  literally 10 years. JOHN MUELLER: Yeah, it's

always frustrating to try to chase these differences down. Totally understand that. AUDIENCE: Well, you try to be a good webmaster, right? I mean, like-- and it's just that it's upsetting. That's all. JOHN MUELLER: Yeah. Cool. OK, so we're a bit over time. Let's take a break here. It's been great having you all here.  

#### [0:57:30](https://www.youtube.com/watch?v=VitQGsyurmw&t=3450) |  Those of you in the US, I

wish you all a Happy Thanksgiving and I guess a good Black Friday. I don't know if you wish people that, like just buying stuff. But anyway, a great week. We'll have the next Hangout in English on Friday and one in German on Thursday. And next week, we have a webmaster conference in Tel Aviv, where I will be. So if any of you are there, come and say hi. We also have webmaster conferences  

#### [0:58:00](https://www.youtube.com/watch?v=VitQGsyurmw&t=3480) |  lined up in Japan and Korea the

next couple of weeks. So if you're there, that's also cool. Yeah. AUDIENCE: Also Switzerland on the 11th. JOHN MUELLER: Cool. All right. Yeah, that's the one lined up after that. Yeah. So many things happening next couple of weeks. All right, cool. Then I wish you all a great week, and see you next time. Bye, everyone. AUDIENCE: Thanks. Bye.  