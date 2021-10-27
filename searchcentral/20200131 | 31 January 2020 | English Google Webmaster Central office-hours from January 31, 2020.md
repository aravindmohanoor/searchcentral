[![English Google Webmaster Central office-hours from January 31, 2020](https://i.ytimg.com/vi/ylRoKGSSqd8/maxresdefault.jpg)](https://www.youtube.com/watch?v=ylRoKGSSqd8)

## English Google Webmaster Central office-hours from January 31, 2020

This is a recording of the Google Webmaster Central office-hours hangout from January 31, 2020. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Watch out for new sessions, and add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



Feel free to join us - we welcome webmasters of all levels!



Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=0) |  JOHN MUELLER: All right, welcome, everyone, to

today's Webmaster Central Office Hours Hangout. My name is John Mueller. I'm a webmaster trends analysts here at Google in Switzerland. And part of what we do are these office hour Hangouts, where folks can join in and ask their questions around websites and web search. And we try to find answers. A bunch of stuff was submitted, even though it's, like, just a few days. But there's lots of things lined up, but kind of, as always,  

#### [0:00:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=30) |  if any of you want to get

started with the first question, you're welcome to jump in. Hi. AUDIENCE: I have actually two questions. So the first one is about the URL link since we have got a client. So when I checked his website is about [INAUDIBLE].. So the URLs are like this, domain URL slash [INAUDIBLE] slash [INAUDIBLE]  

#### [0:01:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=60) |  slash freestanding [INAUDIBLE]. It's very long, and

he used the keyword a lot of time. So is it bad Istio? What do suggest in this case? JOHN MUELLER: That's fine. I mean, we use URLs to identify the content. So if it's long or short, that's essentially up to you. When we have multiple URLs that have exactly the same content, and we have to pick a canonical, then usually we tend to prefer a shorter one, but usually that's  

#### [0:01:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=90) |  within your own website. So if you

have kind of the short version and the long version, and they both show the same content, then we try to pick the shorter version. But it's not that the shorter version has a ranking advantage or anything like that. AUDIENCE: OK, and the second question is about the backend source. So if an English website gives the backend from another English website and another backend from a non-English website, do you give same importance to both URLs or it  

#### [0:02:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=120) |  varies based on the language? JOHN MUELLER:

That's all the same to us. So it doesn't matter the language of the website. I mean, what happens is we try to understand the anchor text and how that belongs within the context to understand the page they're linking to a little bit better. But it's completely normal for websites to have links from all kinds of other websites from different countries, different languages.  

#### [0:02:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=150) |  AUDIENCE: Thank you. AUDIENCE: John, perhaps I

may chime in before you go with the other comments, if that's OK? JOHN MUELLER: Sure. AUDIENCE: OK. JOHN MUELLER: Sure. AUDIENCE: I just wanted to ask a trivial question, or perhaps not that trivial, regarding interstitial pop-ups. What we are currently having as a discussion between our sales team and the SEO people regarding how we actually  

#### [0:03:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=180) |  get content from our users. [BACKGROUND NOISE]

Sorry, I tried to go on. Just a second. Oh, sounds better. So we are having a discussion with our sales team regarding how we actually get consent from our users, and there is one option, which is this kind of bar at the bottom of the page, and the other one which, like,  

#### [0:03:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=210) |  [INAUDIBLE] more to have an interstitial, which,

actually, is overlaying the content and even trying to gray out the background content. And you said on a recent tweet that content as such is OK if you have the cookie bar at the bottom. However, it becomes a problem if you really have these interstitials, which are overlaying any content. And I wanted to actually to-- perhaps you can elaborate a bit more on what could be possible when it comes to interstitials.  

#### [0:04:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=240) |  Perhaps we don't gray out the background

because it's basically a means of increasing the people to give content to allow us to display advertisement. What's your advice when it comes to this? JOHN MUELLER: So I guess, first of all, I don't know what the legal requirements are that you might need to watch out for. So that's kind of, like, on the side.  

#### [0:04:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=270) |  I don't know if my suggestions would

be compliant with what you're looking for. AUDIENCE: OK. JOHN MUELLER: In general, the kind of the bar on the bottom of the page, that's something that's really useful for us because then we can still see the rest of the page. So, in particular, we can recognize how much of the page is mobile friendly. We can recognize the prominent elements  

#### [0:05:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=300) |  on the page, all of that. That's

really kind of the thing that makes a lot of the normal web search processes just kind of work by default. That's kind the one side. The other, I guess, extreme that we sometimes see is when people redirect to a different URL for kind of confirming that they're allowed to access the content or age interstitial  

#### [0:05:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=330) |  or something like that. And there the

problem is when you redirect to a different URL, Googlebot will follow that redirect, and we will only have that interstitial content to index. So there is no other content on the page. It's not even the right URL. So what usually happens in those cases is we index the interstitial, and we think all of the pages from the website are the interstitial. And , basically, we do eliminate all of the pages towards that  

#### [0:06:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=360) |  interstitial URL, which is kind of the

thing that you really, really want to avoid unless you want to remove your website from search. AUDIENCE: No, we don't. JOHN MUELLER: And I guess the alternative that you're kind of considering is somewhere in between and that you have a full page interstitial that you remain on the same URL. And there it's generally more a matter of how you implement this in a way that Google can still see the normal content.  

#### [0:06:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=390) |  So, in particular, if you're using JavaScript

to display like a div on top of the page, and the rest of the page is still there, then that's something where we can still see the rest of the page, and we can kind of work with that. So those are kind of the different approaches there. One other thing that I think I have seen some sites do is to go into the area of, what is it, flexible sampling  

#### [0:07:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=420) |  almost, where they kind of request that

a user signs a [INAUDIBLE] to see the content. And by signing it, they also have some kind of cookie consent or whatever attached with that. And for us, that's usually less of a problem because we would see that as flexible sampling, like, you're saying, well, my content is here. You just have to take these steps do you actually see the content.  

#### [0:07:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=450) |  So that's perhaps another approach that might

be worth reviewing. AUDIENCE: Perfect. Makes sense. Thanks a lot, John. JOHN MUELLER: Sure. AUDIENCE: Hello, John. JOHN MUELLER: Hi. AUDIENCE: Yeah, [INAUDIBLE] site, actually, I do have a lot of problems, I mean, I wanted to ask you, but I can only ask some things from you. Actually, simply, I have got-- yeah, We're going to reconsider [INAUDIBLE]..  

#### [0:08:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=480) |  I have [INAUDIBLE] for my client. OK,

so, I mean, Google assigned us two sample links, right? I mean, you guys are sending us two sample links as an example of a natural link site. So I found that one of the links carries a nofollow tag, OK? And I don't think-- I mean Google is considering I mean, with nofollow tag links as a-- I mean, as an important link. I mean, you understand my point?  

#### [0:08:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=510) |  JOHN MUELLER: Yeah. AUDIENCE: I don't know

how you guys can send nofollow tag in a sample URL. Can you please explain this thing? JOHN MUELLER: That could be something that went wrong on our side, but, generally speaking, if you did a reconsideration request, especially for link spam, and you got it back saying that it's not good enough, then I would focus on the bigger picture and not kind of worrying too much about that one nofollow link.  

#### [0:09:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=540) |  But, really, think about what kind of

bigger picture things have you been doing with regard to links that you still need to clean up. And sometimes what can happen is that they will flag an issue and say, well, this is the kind of thing that you should be watching out for. It's not, like, these are the two remaining links that you need to fix, but rather here are some ideas of issues that you need to clean up. So I would take it more in that direction  

#### [0:09:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=570) |  and really kind of try to clean

those links out as completely as possible. AUDIENCE: Yeah. OK. JOHN MUELLER: Sometimes the folks on the forum can be helpful for these kind of things, where they can say, oh, you still have, like, all of these millions of links. And they can guide you towards the things that you really need to kind of remove. AUDIENCE: OK. So, John, we also find many of the links are coming from the feed pages, right? I mean, I'm checking all the links that we are getting,  

#### [0:10:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=600) |  the backlinks we are getting in the

master. So a lot of feed pages are generated. Should we do something about them also, or what should we do? Feed pages. JOHN MUELLER: What kind of links did you mean? I didn't understand. AUDIENCE: Feed, feed. I mean, the feed URLs. JOHN MUELLER: Like, how do you mean feed URLs? AUDIENCE: I mean, we are not able to open that kind of URLs. They are just if I open that kind of URL, all that will download, the code downloaded, in our PC,  

#### [0:10:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=630) |  in our system. JOHN MUELLER: OK. AUDIENCE:

I can show you some examples also. Yeah, that's correct, RSS feed. JOHN MUELLER: OK. Usually that's less of a problem, but, usually, the RSS feeds are generated based on the content on a blog, for example. So that's usually where, if there is a link in an RSS feed,  

#### [0:11:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=660) |  then probably that's due to a link

in a blog post somewhere, and cleaning up the blog post fixes the RSS feed automatically too. AUDIENCE: So what do you suggest? I mean, should we consider feed URLs also in our disavow then? I mean, I don't know if-- JOHN MUELLER: No, no, I wouldn't worry about disavowing the feed URLs. It's something where if you've kind of gone out and placed blog posts on other people's sites, and those links also show up in the feed, then maybe it's best to just disavow that whole domain  

#### [0:11:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=690) |  to make sure that you have everything

covered because if you've been placing links on other sites, and they show up in the feed, in addition to the site, then it's not the feed that's the problem. It's kind of a general practice of going out and dropping links on other sites. AUDIENCE: OK, John, one last question, I mean, John. JOHN MUELLER: Sure. AUDIENCE: I mean, if we will place naked URL,  

#### [0:12:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=720) |  I mean, link, naked URL any place

in the website. So it will be considered as unnatural, I mean, if I was missing any naked URLs. JOHN MUELLER: So without a link, or-- AUDIENCE: Without a link, without any anchor text. JOHN MUELLER: Without any-- well, if it's not a link, it's not a link. You should be fine, yeah. AUDIENCE: OK, fine. Thanks a lot, John, for your help. JOHN MUELLER: Sure. Sure. AUDIENCE: Yeah, hey, John. JOHN MUELLER: Let me run through some of the submitted  

#### [0:12:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=750) |  questions. And we can get to more

live questions afterwards just so that we don't completely ignore all the things that people lined up because, a lot of times, people just can't join because of the time zone. So I want to make sure that we can try to get some of their questions through. OK, the first one is about an AMP website. They changed all the internal links to point to Google's cache URLs.  

#### [0:13:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=780) |  "So, basically, even on desktop, it always

goes to the cache. A few months later, I had some negative results in terms of rankings and changed back. So the question is, how should I do it, essentially?" So first of all, I think pointing to the cache URL is generally a bad practice because these URLs can change over time. It's not that those URLs will always remain the same.  

#### [0:13:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=810) |  So, personally, I would link within your

website, link to your own URLs, and if it's loaded on the AMP cache, and they can swap out the URLs against the AMP cache URLs with kind of the cache where it's displayed, that's fine. But I wouldn't kind of generate a website structure by pointing at AMP cache URLs. The other reason why I wouldn't do that is that, as far as I know, a lot of these caches are blocked by robots.txt.  

#### [0:14:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=840) |  So if you're changing all of your

internal navigation to point at URLs that are blocked by robots.txt, then that's going to definitely have a strong effect on your website. So my recommendation there would be to link within your site and keep those links within your site. And if it's loaded on the cache, and it swaps it out for the cache, then that's kind of on the user's side. That's not something you need to worry about. But from crawling and indexing, definitely make it so that we can index your site  

#### [0:14:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=870) |  and not have to kind of worry

about the cache. "I'm seeing random errors of Google Tag Manager verification failures for Search Console for sites." And you link to a thread. I am not aware of anything specific happening there with regards to Tag Manager verifications, but I'll definitely take a look at the thread and see if there's anything more that we need to figure out.  

![](https://i.ytimg.com/vi/ylRoKGSSqd8/maxres1.jpg)



#### [0:15:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=900) |  So try to find something there. "We

often receive DMCA violation notifications. We're not pirates. So disputing complaints and dismissing them [INAUDIBLE],, but it takes time. If it weren't for the fear of Google discontentment, then we wouldn't be doing it. Does the number of DMCA complaints affect the ranking of a site? Is it possible to get rid of a bad reputation?" So I double checked on this because I wasn't sure  

#### [0:15:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=930) |  what we actually announced at the time,

but I think 2012, around, we did a blog post saying that the number of valid DMCA complaints is something that we would take into account for ranking. So if you're dismissing them, if they go away when you kind of flag them as being wrong, then that's perfectly fine. But if your site is collecting them over and over again,  

#### [0:16:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=960) |  then that's something where our systems might

pick up on that. "If we have breadcrumbs only on the desktop site, how will it affect this snippet on Google?" So, in general, when we switch to mobile-first indexing, we only take the content from the mobile site into account. So if you only have some kinds of markup or some kinds of content on the desktop version,  

#### [0:16:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=990) |  and it's not available at all on

the mobile version, then we will not have that available for indexing. So breadcrumbs, if they're only on desktop and not on the mobile, and we switch to mobile-first indexing, we will not have your breadcrumb markup anymore. With regards to putting breadcrumbs on the bottom of the main content on mobile, that's perfectly fine. It's also possible to use kind of responsive design elements  

#### [0:17:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1020) |  where you're saying, well, on desktop, we

have room, and we can display it, and our mobile, maybe we don't have room, or we need to display it in a different way. That's also fine. But the markup needs to be there on mobile if you want us to use that markup. "We migrate to our website on the 13th of December from an old platform that wasn't mobile enabled. It was a major move to a new server, a new platform, new category, new URL structure. All the pages and categories of an index and the URL redirect  

#### [0:17:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1050) |  setup, we had some technical issues with

404s, which have been cleaned up. We're working on speed, which was fine in testing, but now too slow. Taking all of this into account, is it reasonable to assume that the rankings won't have settled down yet or could the site speed be the cause of the low traffic?" So I took a quick look at this before. And I think what is happening is you  

#### [0:18:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1080) |  moved within the same domain two completely

different URLs. And, usually, these kind of moves tend to take more time than when you move to a different domain. And it sounds a bit paradox almost, but when you move to a different domain, we can take everything one to one and just copy it over, essentially. Whereas when you restructure your website, then we really have to relearn your whole website and understand, again, how all of this fits in together,  

#### [0:18:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1110) |  what the context is of individual pages,

how to kind of connect things, what the internal links are like, the internal anchor text. And all of these are things that take a significant amount of time for us to settle down and figure it out again. So I wouldn't assume that the speed is kind of the issue here. We do take speed into account, but that's something that's generally a little bit lower with regards  

#### [0:19:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1140) |  to priority and probably takes a little

bit longer to get picked up. But, rather, on the one hand, the restructuring takes time, and on the other hand, if you change the design of a website significantly, then that can also affect how we see that for ranking. So, for example, if you had a website with a lot of good textual content on the pages and a clear internal navigation, then that's kind of a good thing. And if you redesign into a really minimal version  

#### [0:19:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1170) |  of the website, with the same URLs

maybe, but, like, the internal navigation is a lot less, or there's a lot less content on the pages, then, obviously, we would rank it based on the less information that we have there. One thing kind of that points in the direction of this not being really a speed-related problem is when you look at Search Console-- so what I tend to do in cases like this  

#### [0:20:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1200) |  is take a period of time before

the change and after the change where you're looking at roughly the same kind of days. So I try to pick the same weekdays. I try to skip over holiday seasons because that always skews the numbers a little bit, and I compare the queries where the site was ranking before and after and the URLs that were ranking before and after. By comparing both of those, you can fairly quickly see if there is any problem with the old URLs  

#### [0:20:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1230) |  maybe not being redirected, if, like, the

most important old URLs don't show up at all in the new time period. And that's kind of a sign, and with regards to the queries, you can often understand a little bit better what kind of changes am I seeing. Is this like a change across the board, where maybe all of the queries before and after, like, maybe dropped by 20% or some number. Is it specific to the branded queries,  

#### [0:21:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1260) |  or is it specific to kind of

the long tail, the non-branded queries? And by looking at those differences. One thing I noticed with your website is, essentially, the branded queries are all more or less the same, which, to me, points in the direction of, well, technically your website is kind of OK. Overall, we're seeing it as generally being OK.  

#### [0:21:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1290) |  Probably speed, which would be something that

would apply across the whole website, is less of an issue here. But the non-branded queries are the ones where there's kind of a drop there, and to me on the one hand, that suggests that maybe these are URLs that we haven't recrawled and reindexed that well yet, which could be that kind of from a restructuring, it just takes time. Or, alternately, maybe these are pages that look significantly different before  

#### [0:22:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1320) |  and after where we're kind of ranking

the page on what we have indexed now, and the index version that we have now is significantly less useful for us for whatever reasons. Maybe it doesn't have enough text on it. Maybe it doesn't have a clear headings structure on it. Maybe the images are not that accessible for us, all of these things. So that's kind of the direction I would go there. And kind of look at it--  

#### [0:22:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1350) |  like, I would double check this in

your own Search Console account to kind of see if that matches what you would see as well. And if it's really more the non-branded queries, more the long-tail queries that were going to your site and are less visible for your site, then I would kind of, on one hand, give it more time to settle down, and, on the other hand, really significantly review the pages themselves to see what were they like before, what do they look like now?  

#### [0:23:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1380) |  If you're not sure what they looked

like before, there is archive.org, which is a free service where you can check a lot of URLs to see older versions of those. So you can check kind of the old versions that used to be shown in search and see what they looked like and compare that to the current version that you have yourself. All right, "We have a few thousand sites that show up in Search Console, report indexed and not submitted in sitemap." I think sites probably is pages.  

#### [0:23:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1410) |  I'm not sure, like, so, in German,

we tend to use the same word for websites and web pages, which makes things a bit confusing sometimes, but I think probably they mean pages. So "a few thousand pages that show up in Search Console report index not submitted in sitemaps. Most of them are non-canonical pages which point to their respective canonical version, the rel canonical.  

#### [0:24:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1440) |  When we check one of these with

a site query, it shows up in the search results. When we check them with the URL inspection tool, it says canonical URL provided by the user with the correct canonical and canonical URLs selected by Google with verified URL. Why are these non-canonical pages indexed, although there is a clearer signal with a canonical? The pages are almost 100% identical." So let's see, so I think there might be  

#### [0:24:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1470) |  multiple things happening here. It's kind of

hard to tell without some example pages. But, in general, when it comes to canonicalization, we take multiple factors into account. We do use the rel canonical. That's a fairly strong signal for us. We also use things like redirects.  

#### [0:25:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1500) |  We also use internal linking, external linking.

We use sitemap URLs as well, kind of the internal linking structure with things like hreflang, all of that, plays a role as well. And, essentially, we take these multiple URLs that show the same content, and we try to figure out which one of these URLs is the one that we should pick. And it can happen that we pick your URLs that have a rel canonical on them pointing to a different one. So that's not impossible.  

#### [0:25:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1530) |  If you're seeing this on a large

scale, then I would try to figure out why Google might be doing this. So for a few individual pages, I wouldn't care about this. It's, like, sometimes it goes this way. Sometimes it goes that way. From a ranking point of view, it doesn't change anything. It's purely just which of the URLs is shown. So, again, if you're seeing this on a large scale, I would try to dig into those situations and see  

#### [0:26:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1560) |  what might you be doing that could

be confusing Google. So that could be things internal linking. Are you linking to the exact URLs that you have in the set for rel canonical? If you have something like hreflang, are you using the exact URLs there as well? Sometimes things like upper, lowercase plays a role. If you have a sitemap file, does that match exactly what you have submitted as well?  

#### [0:26:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1590) |  So all of these things kind of,

ideally, would align. If they align, then we'll go with what you suggest essentially. If they don't all align, then Google will try to figure it out and try to come up with a canonical version that works in general. And, again, it doesn't change anything from ranking. It's just purely, like, you have a preference, and, ideally, Google would show that preference, and the other place where this plays a role  

#### [0:27:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1620) |  is, of course, with tracking. If you

use things like analytics, then you want to be able to track the individual URLs that you kind of care about. But that's kind of the direction I would go there and try to figure out what might be happening there. If you have URL parameters in these URLs as well, so something with a question mark and then some, I don't know, words equals something else, then the other place I would also look  

#### [0:27:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1650) |  is the URL parameter handling tool because

it can happen that you have a setting there that you forgot, where it's, like, Googlebot should ignore these parameters, and that's why those URLs are not being picked as canonicals. "I'm looking at log files from the past several months, and about 75% of the 404s we send Google happen when Google requests very old embedded content. So we're talking about old CSS, JavaScript image files that  

#### [0:28:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1680) |  haven't been on site for up to

five years in some cases. I've seen URLs from a site we migrated three years ago in the refer. I verified the request as genuine Googlebot. Did these kinds of requests happen when Google renders old pages? If so, why are you rendering really old versions of our page? It seems like a sign of something going wrong. Is there something we can do about this?" So there's generally nothing you need to do about this.  

#### [0:28:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1710) |  It's essentially just our rendering setup, our

crawling and indexing setup, checking pages again. And when it comes to crawling, it's really common for us to recrawl URLs that are kind of old, where we think probably there's going to be a 404, and if you return a 404 for us, then that's perfectly fine. It's not going to cause any problems there. So I think if you look at your log files in detail,  

#### [0:29:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1740) |  you'll find lots of these weird quirks,

but they generally don't cause any problems. I think it's kind of weird that we would re-render really old pages, but I don't see it as being weird enough that I would contact the rendering team and tell them to stop doing this because usually they have good reasons to try to check things out. Sometimes they're experiments. Sometimes it's just double checking kind of how the old rendering worked versus  

#### [0:29:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1770) |  how the current rendering works, lots of

reasons why that might be happening. But, again, I generally wouldn't worry about this. If the number of requests is causing a too high load on the server, then that's something where you can adjust the crawl rate setting in Search Console to let us know to crawl less. And when we crawl less, it's not that we'll crawl percent-wise less of all of the URLs,  

#### [0:30:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1800) |  but rather that we'll focus more on

the URLs that we actually do care about. So that's kind of an approach you could take if you wanted to go that direction. "Our competitor is now making all external links on their site with help of gasket page with JavaScript redirection. He links from site A to site B, not directly, but through an additional page on the site with some kind of a JavaScript.  

![](https://i.ytimg.com/vi/ylRoKGSSqd8/maxres2.jpg)



#### [0:30:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1830) |  Is something like a link from Facebook.

So the question is, do these JavaScript gasket links convey weight and signals? Does Googlebot perceive them as a real intermediary?" So a lot of times we can crawl through those, and it's absolutely fine. We get to the destination page, and that works for us. So, usually, that's less of a problem. In general, if we can't crawl through them,  

#### [0:31:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1860) |  then it will look to us like

they're just not linking to those pages. But I don't see this as being particularly useful for a website. So if a website just doesn't want to pass any signals through a link, then I will just use a nofollow on that link. Like, all of this extra complexity just means more things can break. So, personally, I would avoid trying to go through kind of all of these extra steps  

#### [0:31:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1890) |  to try to hide links. "If Google

search results page is intermittently ranking two pages for the same keyword, how can we help Google to rank only one of them? We have two pages that keep ultimately ranking for the same term in the search results, and I wonder if the competition is ultimately drawing down ranking. Both pages are important to the site, so we can't just delete or redirect one."  

#### [0:32:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1920) |  So the cases where I have seen

something like this happen is usually when we're unsure what the intent of a query is. So it can happen that this kind of fluctuates over time. For example, we might not be sure if the user is searching for a specific product or a specific kind of product. And depending on how we would judge the intent of those queries, we might say,  

#### [0:32:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1950) |  well, maybe a category page would be

more useful because they're looking for this type of product, or, alternately, we might say, well, they're looking for the exact product, so the product detail page would be more important. And these kind of fluctuations can happen over time. It can happen that, I don't know, from day to day, it changes. It might happen that with queries, like, we're so far on the edge that we might show both of these pages because we're just not  

#### [0:33:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=1980) |  sure what exactly the user wants. And

from our point of view, that's usually normal in that it settles down over time, usually, or maybe it will settle down in the sense of, well, we figured out. We can't tell what the exact intent is. So we have to show both of those pages because one of them will work. But we're not sure which one. So that's something where, from my point of view, I wouldn't worry about it too much.  

#### [0:33:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2010) |  If you have really strong feelings about

those two pages, then I would just make sure one of those pages is really well-targeted for what you're trying to aim for, and maybe the other page is really well-targeted for a different, clearly separate facet that people would be searching for. But for the most part, I don't see this as being problematic. Question about implementing schema markup for the future.  

#### [0:34:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2040) |  OK. Future looking is always tricky. "Can

it be easier to maintain? Can it need less reliance on multiple steps and parties for extensible code? Can we make it easier to instruct developers and designers maybe make Google Tag Manager more efficient?" I don't know. I think it would be nice to have it easier, but to be totally honest, I think in the future, at least  

#### [0:34:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2070) |  in the near-term future, we will have

more types of structured data markup, and it will continue to get more complicated probably in the sense of there are just lots of requirements for different search features and in order to do something really fancy in the search results where we can kind of really highlight your site really well. Or if there is a way to kind of also  

#### [0:35:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2100) |  include information that we can show on

Google Assistant, or, rather, I guess, speak on Google Assistant, then all of these things, they currently rely a lot on structure data markup. So that's something where as these areas expand, I would expect to see some amount of additional markup coming in, and anytime you have more structured data markup, kind of like the interactions get trickier and the requirements getting a little bit harder in the sense  

#### [0:35:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2130) |  that, oh, you have to have-- I'm

just making something up, like, a name with 17 characters, you can't just have a name with 15 characters. Sometimes these things change over time. So I suspect it will get harder, in the near future, at least. Maybe in the really long term, it'll be like, oh, the machine intelligence can figure it out for you. You just write a text file, and everything else  

#### [0:36:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2160) |  will happen automatically. I don't see that

happening in the next couple of years. So if you're, I don't know, on the hill with regards to, like, should I learn more JSON-LD to figure out how to do markup myself? I think that's a good approach. I also think, at the same time, a lot of these things can be made easier by content management systems and plugins, extensions that you have for content management systems.  

#### [0:36:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2190) |  So if you're using something like WordPress,

then maybe there's a plugin that does all of this structured data markup for you automatically. I know there are a bunch of recipe plugins, for example. So instead of creating all of the kind of special markup yourself, if you have a plugin that does it for you, then those plugin developers will continue to kind of stay on top of things ideally as the markup evolves over time and probably make that easier for you.  

#### [0:37:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2220) |  But purely, from a markup point of

view, I don't see this getting any easier, unfortunately. We had two products, so the page structure was obvious, a home page domain that come with links to both products. And now we dropped one product, which is better? Put the main product landing page directly on domain.com or redirect domain.com to the main product  

#### [0:37:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2250) |  landing page. So both of these are

kind of the same thing in that you're folding one product and putting it together with your home page. From my point of view, if you're reducing the scope of the your website and really going to just a one-page website, then I would focus on the home page directly rather than redirect from the home page to a lower-level page. If this is something that is very temporary in the sense that maybe next month you'll have another product to sell,  

#### [0:38:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2280) |  and then you go back to having

multiple products on your site, or maybe next month, you have 100 products to sell, then I would stick to the structure where you have multiple product URLs and the home page separate. But if you're really sure that you want to decrease the scope of your website to just one page, then put it on the home page. I think that just makes everything a lot easier for tracking and for crawling and indexing.  

#### [0:38:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2310) |  "The rich result update in September changed

a lot of search results. I want to understand why, for some home pages, stars are still appearing. In my opinion, it could be the use of misleading markup, or is there an actual issue with understanding markup technically, and will it be solved in the near future?" So not exactly sure which update you mean from September. We've had a lot of things over time, but I think, in general,  

#### [0:39:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2340) |  when it comes to structured data and

the rich results, sometimes we do get tricked by people who are implementing the wrong markup, and then we think, oh, this should be showing review stars because we think it makes sense here, and, actually, when someone manually looks at it, they're like, no, that's, like, implemented incorrectly. Or another common one that we see is recipe markup where maybe you will  

#### [0:39:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2370) |  have a recipe for a fantastic blog

post on your website, and that's not really a recipe. So it's, like, our algorithms might look at that and say, oh, it looks like you have a recipe with multiple steps, but, actually, it's a blog post, and it's definitely not a recipe. So when someone manually looks at it, they'd say, well, this is wrong. And from a manual point of view, we do try to take action on a lot of these. So if there's something where you're seeing sites showing up  

#### [0:40:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2400) |  with rich result types that don't make

sense for that site or those pages, then let us know. Feel free to use the spam report form. If you're seeing this on a larger scale, you can also drop me a note directly. Sometimes what I've also seen is that some plugins, like I said, they make it easier. But plugins can also be wrong sometimes. Sometimes the plugins are just set up incorrectly, which can result in us, on a larger scale, seeing an issue,  

#### [0:40:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2430) |  and that's something where sometimes we'll just

send a note to the plugin maintainer, and, it's, like, hey, like, you have this bug, you can fix it. And then your users won't be upset. So, like, I'd use the webspam report form for most of these. If you're seeing things on a larger scale, feel free to drop me a note. "If some your URLs are blocked by robots.txt, is this still considered a waste of Google's crawl budget?"  

#### [0:41:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2460) |  No. If they're blocked by robots.txt, we're

not going to call them. So it doesn't change anything. In particular, crawl budget is something most sites don't need to worry about. So for the most part, I wouldn't worry too much about that particularly and try to optimize for that unless you're really a website with millions and millions of URLs. And, sometimes, small things on a website like that  

#### [0:41:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2490) |  can lead to us suddenly having, like,

two or three or 10 times as many URLs as you actually have. And with a small website, like, that doesn't really matter. But if you have millions of pages from the start, and, suddenly, you have 10 times as many pages, then that's where we really get bogged down with crawling. "Now that deduplication is in effect, does a web page need to rank in position one to be a featured snippet? Before deduplication, I was under the impression  

#### [0:42:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2520) |  that the results 1 through 10 were

eligible, but mostly 1 through 3 earned the snippet. Is that, or was it ever, the case?" I don't think that was really ever the case. So I'm not sure, like, what all has been changing with the deduplication that you're mentioning. I think this is with regards to the featured snippet and the organic results sometimes appearing on the same page and some of the experiments  

#### [0:42:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2550) |  we've done there to try to simplify

that. But, in general, we can pick up featured snippets from all kinds of URLs. It's not that they have to rank first. And from purely from a practical point of view, it's pretty common that we run across a page where we think, well, this is a really good page for this result. So we'll rank it first, but at the same time, it's hard for us  

#### [0:43:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2580) |  to determine what would be a good

featured snippet for this page because maybe the structure of the page is a little bit tricky, or maybe the query is hard to match with the content on the page. And then it can happen that we say, well, this is a good first result, but we cannot pick any featured snippet from this page because we're just so unsure about that. So we won't, and then maybe we'll pick a featured snippet from one of the other results. Maybe we'll just say, well, we don't  

#### [0:43:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2610) |  have a featured snippet for this query,

and that can also be fine. Then the cookie consent thing, I'll try to see if I can find some more information on what variations would work well for cookie interstitials. So I also know that some folks on Twitter ping me about this. So maybe we can find something there. "How does Google treat timestamps and URLs? For example, if you have slash month, slash year, slash today,  

#### [0:44:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2640) |  would that be the same as slash

month, slash year, slash yesterday?" So when it comes to dates, we use various signals to pick up information about a date that is relevant for a page, but the URL can be a part of that. Sometimes, it's a pretty clear signal that a page was published on a day if it has a URL like that.  

#### [0:44:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2670) |  But we also have-- I think, in

the article markup, you can specify a date on the page to let us know there as well as well as kind of visible dates on a page and all kinds of other signals. And with regards to dates in general, it's, like, the question, I guess is, is something that looks like it's from today better than something that was from yesterday? And the answer is no. It's not the case that something that is fresher  

#### [0:45:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2700) |  will be considered better than something that

is older. And that's kind of obvious when you think about it, like, there are lots of topics where the information has been published, and there's evergreen information out there. And there's really good reference material out there. That doesn't change from day to day because nothing has changed there. And that's really good content. That deserves to rank well in search. On the other hand, it might happen that maybe some recent event takes  

#### [0:45:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2730) |  place where suddenly everyone is looking for

something new on this topic. For example, if you have geographic regions, then maybe like geographic background information for a country is really kind of useful as a reference material. But if something critical happens in that country, then people don't want that reference material. They want the news. They want the newest information. So in those cases, we probably would prefer something fresher rather than kind of the reference material.  

#### [0:46:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2760) |  So it's not so much that fresher

is always better, but it really depends on the situation, and our algorithms change there fairly quickly when we see that something kind of new is happening. "If domain A links to domain B with dofollow links, but domain A later adds a nofollow to the link, does Google discount the linked domain B got in the first place?" So when it comes to links, and when  

#### [0:46:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2790) |  it comes to content in general, we

essentially rank the pages based on the information we have at that time. It's not the case that we would say, well, it used to be better, but now it's bad. Therefore, we'll treat still treat it as something better. But, rather, we base our decision on the current situation. So if a link gets changed to a nofollow, then we treat it as a nofollow. If the link gets changed to have a nofollow removed,  

#### [0:47:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2820) |  we treat it as a link without

a nofollow. If the content on a page changes, then we treat it as that new content. So all of these things are essentially tied to the current state of the web page, of the website, not so much to the previous states. And, usually, that's a good thing because that means that you can improve things. So if you have a website that's not ranking first for all of the queries that you care about, you can improve things. And over time, as we see that the new content,  

#### [0:47:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2850) |  the new website deserves to rank better,

then we'll rank it better. It's not so much that we'll say, oh, this website didn't rank well last year. Therefore, it will never rank well in the future. "We have a site that ever since March, April 2018 we've seen a big drop in traffic that hasn't recovered. So that's a really long time. I don't know if--  

#### [0:48:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2880) |  so AUDIENCE: It think this might be

my question. JOHN MUELLER: Oh, that's your site, OK. AUDIENCE: Yeah, I think so, yeah. I did two sites on the same day. JOHN MUELLER: OK. Go for it. AUDIENCE: OK, so, yeah, back in April, April 3, yeah, both of our sites were doing really well, and then it dropped through the floor by 50%, 60%, down on each site, two separate domains,  

#### [0:48:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2910) |  just overnight. So, yeah, we've had people

in. We've had technical audits. As sort of journalists, we like to pride ourselves on what we do anyway, but, I mean, we've doubled down. We've been cleaning up. I mean, the list, I've got, you know, 25 technical and content-based points. We've improved site structure. You know, we've really been through everything, really,  

#### [0:49:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2940) |  and nothing, you know, no improvement, really.

The are flat, both of them, sort of eerily flat. It was the same traffic every day since April the 2nd. So I don't really know where to turn now. I mean, we're talking about, like, you know, good pieces of content that rank second or third, page 4. No, so it's not all just general distaste, or I don't feel, like, oh, people  

#### [0:49:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=2970) |  are doing everything significantly better than us

so that we went from 3 to page 4. So, yeah, we've lost staff. I don't really know where to turn now. JOHN MUELLER: If you want, you can drop your domain in the chat, and I can take a look at that afterwards. I think-- AUDIENCE: Right, yeah. JOHN MUELLER: In general, if it's been so long since a change, then that sounds like our algorithms are pretty sure that we should be ranking the site like this.  

#### [0:50:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=3000) |  AUDIENCE: Yeah. JOHN MUELLER: And, I mean,

changes can happen in our algorithm. So it's not completely impossible that we would see changes like that. But it's something where, usually, that means we think we're ranking it in the right place. And I can take a quick look after we kind of pause the recording to see if there anything specific that I can point at, like, offhand, but, usually, that means that there's not like a situation where  

#### [0:50:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=3030) |  we're on the edge. We're not sure

how we should rank it, but, rather, it's, like, we're pretty confident that we should rank it like this. If you've had other people look at it, then probably, from a technical point of view, it's OK. AUDIENCE: I know [INAUDIBLE] sent you a note about this because he's been through it and sort of getting to head scratching time. JOHN MUELLER: I don't know.  

#### [0:51:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=3060) |  I can take a quick look after

we pause the recording and see if I find anything offhand. But, usually, it's more a sign that, like, we're kind of OK with the ranking that we figured out there. And these things do change over time so, theoretically, it's possible that something in April happened where we were like, OK, we need to re-evaluate how we rank some of these sites that we have indexed. AUDIENCE: The curious part of it is that the site's rankings  

#### [0:51:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=3090) |  actually returned for exactly one week in

July and then disappear again. JOHN MUELLER: Yeah. I don't know. It's hard to say. So I don't know your sites at all. So it's really hard for me to say it's like, oh, that's a terrible site. It deserves to not be ranked. AUDIENCE: [INAUDIBLE] JOHN MUELLER: It sounds like you're pretty sure that it's not. AUDIENCE: I'd like you to take a look, and, yeah, I see a lot of these sorts of queries on the web,  

#### [0:52:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=3120) |  and there's always something sort of nefarious

in the background or, as you say, you guys know what you're doing. But, you know, things have been run pretty good, and, yeah, I'd like to see if you could take a look, that would be amazing, just [INAUDIBLE] JOHN MUELLER: So I have a bit more time after we end the official Hangout. And if you want to stick around, I can take a quick look. AUDIENCE: Yeah. JOHN MUELLER: I can see. Yeah.  

#### [0:52:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=3150) |  AUDIENCE: Thank you. JOHN MUELLER: Sure. Maybe

we'll just switch to more questions from any of you in the meantime. It looks like there is also some in the chat here. Let's see. "I have a question about sites using heaps of microsites to link back to the main site. A client or competitor has over a hundred of these sites, the sites linking over help prop up the rankings of the main site. Is this business reaching any Google guidelines at all? Anything I can do?"  

#### [0:53:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=3180) |  So that just sounds like a PBN,

which is kind of like the games that people play. If you want, you're welcome to send me, I don't know, the site in question, and I can have someone from the web spam team take a quick look. Sometimes it's OK to have multiple sites, and they link together. Sometimes the multiple sites are essentially just there as a network to prop up the ranking of another site, and sometimes it's useful to kind of dig into those details.  

#### [0:53:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=3210) |  So if you want to drop me

some URLs, then feel free to do that. "Additional to the product question"-- I guess with different domains. I don't know. More questions from you all, maybe something live probably will be easier.  

#### [0:54:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=3240) |  Nothing? Oh, my gosh. OK, then someone

pointed at an hreflang question. Let me see if I can find that. So maybe scrolling down to some of the other questions that were submitted, and like I mentioned, if any of you want to jump in and ask a lot of questions, go for it. AUDIENCE: Yeah, I was just looking for mine here.  

#### [0:54:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=3270) |  JOHN MUELLER: OK, go for it. AUDIENCE:

So after December, I started getting some weird messages that my robots.txt was blocking important URLs, and, in fact, apparently it was because it was never supposed to do that. Those URLs were like our main URLs, which makes me think that probably somewhere in time someone dropped a disallowed slash there or something like that.  

#### [0:55:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=3300) |  But the thing is, I went through

all of the logs, all of our internal systems, and I didn't see anything changing our robots.txt. We also have robots attacks monitoring alerts that we basically ping it, and if it's different than we expect, we get an alert, and we didn't. When I went to Google Search Console old version, it allows me to see the previous version that Google has in cache, something like that, and it did not block any of those.  

#### [0:55:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=3330) |  What I've been doing is, basically, have

been just marking all of them as fixed, but I'm afraid that it might happen again in some [INAUDIBLE],, and I don't know what could have happened here. JOHN MUELLER: It's hard to know without looking at the site. Double checking the old versions in Search Console is a great way to start. I would try to figure out if this was a one-time event  

#### [0:56:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=3360) |  or if this is something that is

ongoing. So, in particular, if you submit those URLs with the Inspect URL tool, does it say that it's still blocked, or is it OK now? AUDIENCE: They're all OK now. JOHN MUELLER: So if it was a one-time event, it could have been something as simple as the robots.txt file returning 403 for a brief period of time or returning a 500 server error for a brief period of time because both of those cases are situations where we say, well,  

#### [0:56:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=3390) |  we can't access the robots.txt file. Therefore,

we won't crawl anything from the website. And, usually, what happens is the next time we check the robots.txt file, which is, I don't know, maybe a couple hours later or the next day, then we can crawl it normally again. And we would get all of the normal content, and we can crawl the website again normally. But during that period of time where we're essentially blocked by the robots.txt file that we can't reach,  

#### [0:57:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=3420) |  then we would assume that all of

the URLs that we would otherwise try to crawl are blocked by robot.txt, and we might flag that in Search Console. So if this is like a one-time thing, it happened once, and it was a fairly short period of time and just a bunch of URLs because, like, we tried to crawl a bunch during that time, then maybe that was just something weird that happened on a server very briefly. If you see this happening more than once, then I would definitely try to determine where  

#### [0:57:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=3450) |  this might be coming from. One place

that I usually go to debug things like this is the server logs and, in particular, the robots.txt request. So filter out all of the robots.txt requests that you got, in particular from Google, and look at things like the response size and the response code that you gave back and try to see if there are differences in the sizes or if the response code has varied over time,  

#### [0:58:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=3480) |  and use that as a way to

kind of narrowing down where things went wrong. Sometimes it's as simple as someone pushed a new version of the website, and the robots.txt file was made inaccessible during that push, and we tried to crawl just during that short window. Then like the next time things go, it'll be better. That might also be a sign that maybe your pushing things to production process could be improved  

#### [0:58:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=3510) |  so that it doesn't block Google when

it tries to access the robots.txt file. AUDIENCE: OK, now I think what might have happened is we allowed Google to index a bunch more URLs in the beginning of December. And it has been hitting us really hard, like six times the usual. And it was overloading our servers, and we started returning 429s to Google.  

#### [0:59:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=3540) |  And after some digging, I figured that

you received that as 503 or something. JOHN MUELLER: Yeah, yeah. AUDIENCE: So maybe that's just the message that was wrong. It's not that the robots.txt was blocking. It's that you could not read it. JOHN MUELLER: Now we would differentiate between 503 and us thinking that a website is blocked. Also, if the robots.txt file returns a 503, and that's a temporary thing for us, then we'll try to get the next version of the robots.txt file first before we stop crawling.  

#### [0:59:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=3570) |  But if you return a 500, then

that would be a sign that the robots.txt file is blocked for us. AUDIENCE: OK, but do you treat 500, I mean, 429s as 500s? JOHN MUELLER: I don't know where we would treat 429s. I don't know for sure. AUDIENCE: Yeah, because I remember the only thing that I found around this was a post because of some Gary  

#### [1:00:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=3600) |  answer on Twitter that it said that

you might treat 429s the same way, meaning it will just slow down crawling. But when I saw here on my logs was that we were not returning any 500s to Google, only 429s, and at the same time, the number of server errors in our Google Search Console properties, they started increasing by 10s, even though we were not returning 500.  

#### [1:00:30](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=3630) |  JOHN MUELLER: OK, I don't know. I'll

double check. That sounds like it might fit. Yeah. But I'll double check on our side to see how we would treat 429s. AUDIENCE: All right, thank you. JOHN MUELLER: Sure. OK, we're a bit over time. So I'll pause the recording here. If any of you want to stick around a little bit longer, you're welcome to do that. But, otherwise, thank you all for joining. It's been great having you all here.  

#### [1:01:00](https://www.youtube.com/watch?v=ylRoKGSSqd8&t=3660) |  It's nice to have so many people

jump in, even on short notice. So thanks for all of that. And I wish you all a great weekend and a good start next week in the meantime. Bye, everyone. AUDIENCE: Thanks, John. Bye.  