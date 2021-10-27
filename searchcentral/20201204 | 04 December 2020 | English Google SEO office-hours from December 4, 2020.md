[![English Google SEO office-hours from December 4, 2020](https://i.ytimg.com/vi/C9dNFj0APvg/hqdefault.jpg)](https://www.youtube.com/watch?v=C9dNFj0APvg)

## English Google SEO office-hours from December 4, 2020

This is a recording of the Google SEO office-hours hangout from December 4, 2020. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Find out more at https://developers.google.com/search/events/join-office-hours



Feel free to join us - we welcome webmasters of all levels!



#### [0:00:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=0) |  JOHN MUELLER: All right, welcome, everyone, to

today's Google Search Central SEO Office Hours Hangout. My name is John Mueller. I am a search advocate at Google in Switzerland. And part of what we do are these office hours Hangouts where people can join in and ask their questions around search and their website. A bunch of things were submitted already on YouTube. So we can go through some of those. But if any of you want to get started with a question of your own, feel free to jump in now.  

#### [0:00:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=30) |  AUDIENCE: If I can start-- if I

can be first, it would be nice. JOHN MUELLER: Sure. AUDIENCE: Thank you, John. So earlier this week, actually, like, two or three days ago, I noticed that one of my client's websites, some pages got deindexed, and it says that the user-declared canonical is just a different page. But then I checked the pages, the HTML code shows that it's a self-referencing canonical. So it's actually pointing to the correct one,  

#### [0:01:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=60) |  and then when I use the live--

how do you call it, the Live Tool, to check the live URL, it actually shows that it is the correct canonical. But it's still reported there, and some of those pages are still deindexed. So I'm not really sure how that happened. I checked the website. Nothing really changed. So I don't really know how to tackle the problem, because we lost some keywords and ranking, some traffic, because of that. JOHN MUELLER: Yeah, like, on my side, what I need to do  

#### [0:01:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=90) |  is look into those specific details. So

what I would usually recommend for a case like this is to post those details in the Help Forum first and get some input from other people. And the product experts in the Help Forum, they can escalate threads when they see that things aren't kind of working out. So that's kind of the direction I would head there. I have seen some cases like this, not specifically like this week or last week,  

#### [0:02:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=120) |  but, in general, it happens every now

and then that something on the website is configured in a way that makes it really hard for us to crawl and index the pages. So I've seen that, for example, with a site that uses some ad blocker scripts, or anti ad blocker scripts, I guess. And then in cases like that, those scripts sometimes redirect to a central page, and that has a rel canonical on it,  

#### [0:02:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=150) |  or we pick up the redirect, and

we use that kind of as a canonical signal, those kind of things. And that can sometimes trigger, depending on the way that we crawl. So maybe, like, for the normal crawls, it doesn't trigger, and then every now and then, it does trigger, and it triggers right at that moment when we pick up something that we want to use for indexing. But that's something that sometimes is noticeable when you look at the specifics of the site,  

#### [0:03:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=180) |  like, if you look at the other

URLs, then you can see, oh, they have similar issues sometimes, which kind of points to this kind of sporadic type of an issue. And sometimes it's just like, I don't know, some one-off quirk that might have happened, maybe from a CDN that's involved in the middle, maybe from the hosting site, something like that, that just happened to kind of step in in between. AUDIENCE: OK, interesting. And I also wanted to ask, I noticed  

#### [0:03:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=210) |  that there is many older pages that

are not indexed because of the trailing slash-- I don't know. This is the first time, like, most of the other pages you don't see-- you don't see that, you know-- sorry, many other websites, I've seen that there is nothing in the report, even though, you know, the pages have the trailing slash, of if it doesn't have it, it's still considered the same page. But for this particular website, it  

#### [0:04:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=240) |  seems like many pages without the trailing

slash were deindexed. I don't know if that gives us a hint of something going on. JOHN MUELLER: I don't know. It's hard to say. So by default, we wouldn't see the trailing slash and not trailing slash as the same URL. It is something that, technically, we would consider one to be kind of the root of a folder and the other a file name within the higher-level folder. So we wouldn't, by default, try to equate those.  

#### [0:04:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=270) |  If we crawl them, and we see

the same content, then we pick them up, and we try to use them for canonicalization. So that's something that then kind of happens as a second step, and depending on the way that you have the site verified in Search Console, if you just have like that subdirectory verified and the URL is the one without the trailing slash, then we would assume that URL is no longer a part of that site if you kind of focus on the subdirectory.  

#### [0:05:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=300) |  And we have that same problem right

at the moment with our kind of new search documentation, which is also hosted on developersgoogle.com/search without a trailing slash. And we have the URL with the trailing slash verified in our Search Console account. So we kind of have the similar situation that sometimes we just don't see that traffic or the clicks and impressions there.  

#### [0:05:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=330) |  AUDIENCE: Awesome. Thank you. JOHN MUELLER: Sure.

All right, any other questions before we get started? Uh oh, Barry. AUDIENCE: I got one. So, quickly, on the core update that was released yesterday, one is that I have some understanding on the rationale behind the timing of that if you at all were involved or saw some emails around why you timed it for right after Cyber Monday, but before the holidays.  

#### [0:06:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=360) |  What's the rationale there? JOHN MUELLER: I

don't know. know I mean, I don't know. From my side, it feels like a reasonable time. Like, I wasn't involved in the decisions there, but it's, like, not really in the holiday season and kind of after the whole Thanksgiving rush. So it felt, like, I don't-- at least from my point of view, it wasn't something that I would have flagged and said, oh, you need to watch out for this.  

#### [0:06:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=390) |  AUDIENCE: OK, thank you, and two, people

are asking me with the core update, this doesn't mean passage indexing or ranking is out? That has not gone out with this? It's not live yet in terms of the passage indexing? I know because you said at the end of the year, passage indexing will be live by then, but it's not out yet, right, as far as you know? JOHN MUELLER: I don't know if it's out yet, but, usually, the core update wouldn't be something that we would bundle with other kinds of changes like that.  

#### [0:07:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=420) |  So it's something that maybe it is

coming out at the same time. But it wouldn't be because of the core update. It would be kind of, like, more of a coincidence. I don't know what the timing plans are for that. AUDIENCE: OK, thank you very much. Appreciate it. JOHN MUELLER: Sure. AUDIENCE: Hello? JOHN MUELLER: Hi, yeah? AUDIENCE: Hi, John, how are you? I left you one of the comments on the post, but I just wanted to ask you because I thought that I could not make that clear, and I thought it was easier  

#### [0:07:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=450) |  to tell you by voice. So, basically,

the problem that we're facing and what I wanted to ask you is if you guys still have reports on any canonical bugs for USA content and for USA country because what we do is we're a sport's international media company, and we've been having a lot of problems with our live blogs, which usually has recurring themes because, you know, they play two times during the season  

#### [0:08:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=480) |  and only in US selected as language

and selected as, I mean, English as the language and USA as a country. We don't show up, even though Google Search Console, it's reporting that it's indexed, but the funny thing is if you go to UK with English language setup, we show up as the first SERP in most of the searches. So it's something that is happening specifically just for US, and it only happens for our live blogs, which  

#### [0:08:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=510) |  we assume has to do with something

that, you know, it's recurrent themes that we're mentioning because we're not really having the canonical bugs for any, like, news that is happening, which we only report once. So I was wondering if you guys have any reports on the canonical bugs, that it still happens because these just started happening maybe two months ago. Before that, it was, you know, perfectly normal, showing up as usual. JOHN MUELLER: Yeah, I'm not aware of any issues around kind of the canonicalization  

#### [0:09:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=540) |  and indexing at the moment. And, also,

from how you describe it, it sounds like it's less an issue of indexing and more an issue of around kind of like internationalization for the site. So just to double check, do you have separate URLs for the UK, or do you have the same URL that is just visible in the UK but not visible in the US? AUDIENCE: It is the same URL, and we just place ref links.  

#### [0:09:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=570) |  But our source, it's as a publisher

for US. So everything's working supposedly the way it should. It just stopped working two months ago, and it only stops working for live blogs, which we use recurrent themes. If we, you know, make a live blog of, I don't know, a game that hasn't been happening much or from a team that is not that common, it shows up perfectly, which it makes it really, really tough to understand why this is happening. JOHN MUELLER: Yeah.  

#### [0:10:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=600) |  I don't know. To me, that doesn't

sound like an indexing bug. That really sounds like something around internationalization. And the hreflang side there might also be something that's playing a role there. How do you have the hreflang set up? Is that, like, one English URL and then like a Spanish URL or a French URL, or how do you link those? AUDIENCE: Yeah, we just have one URL, and we just then place if it's for NUS or N only  

#### [0:10:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=630) |  or NMX, depending on which countries we're

trying to attack through the reflang. JOHN MUELLER: OK. I don't know. I'd have to look at the specific details. But offhand, it feels like something where maybe with the hreflang set up, something is not quite the way that it should work. And that's something that sometimes causes more problems,  

#### [0:11:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=660) |  sometimes causes less problems. But probably that's

something that you'd be able to resolve there. What you could do is maybe post some of the details here in the chat, and I can pick up the chat afterwards or post the details in the Help Forum as well so that kind of, like, some other people can throw some eyes at it. AUDIENCE: OK, all right, John. JOHN MUELLER: Sure. AUDIENCE: So I will post on the forum, and then I will let you know where it is so you can check it. Thank you so much. JOHN MUELLER: Sure. Thanks.  

#### [0:11:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=690) |  All right, I think someone else is

trying to jump in and ask a question as well. Go for it. AUDIENCE: Yes, hello, John, do you hear me? JOHN MUELLER: Hi, yes. AUDIENCE: Yes, right, so as you maybe know on the Twitter right now, so we have the problem with the discover feed in Sweden. We have had that since, I think, like in the middle of December last year, and it's fairly amount of sites  

#### [0:12:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=720) |  that have this issue. And so, yeah,

these sites are not showing up in the Swedish discovery feed when you are in Sweden, but if you, like, turn on a VPN, then it's turned on, and, yeah, of course, if you're outside of Sweden, and if you're outside of Sweden and go into the discover feed, it's also showing up.  

#### [0:12:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=750) |  JOHN MUELLER: OK. I don't know offhand

about that because I believe that's something that we already passed on a while ago, and you're still seeing this happening with no changes at all? AUDIENCE: Yeah, exactly. I can show you if you want. JOHN MUELLER: Or maybe you can post a link in the chat here. Then I can pick that up afterwards. AUDIENCE: Yeah, of course, of course. JOHN MUELLER: Cool. AUDIENCE: Pretty great. Thank you. JOHN MUELLER: OK, great.  

#### [0:13:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=780) |  Thanks. AUDIENCE: Cool. OK, let me run

through some of the questions that were submitted. And we'll definitely have more time for your direct questions as well along the way. JOHN MUELLER: Let's see. I'll try to run through these fairly quickly since it seems like lots of questions are here. "When it comes to anchor text from external links pointing to my website, do you check the anchor text only on a page-by-page basis, or do you also look at site-wide anchor text?" We look at both, so we do look at it on a per-page basis  

#### [0:13:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=810) |  to understand kind of the context of

individual pages. You notice this in particular if a page is blocked by robots.txt and is still indexed, then you'll see kind of the anchor text as something that we might use as a title in the search results for that page. But we also look at the anchor text for sites overall because it does give us a little bit of a kind of a broader understanding of how that site is embedded in the way. So that's something that we try to take into account where  

#### [0:14:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=840) |  we can. "We're experiencing huge ranking fluctuations

where a specific page drops for most relevant keywords from the top places to pages 3 to 5 and comes back a few days later, and this keeps repeating. We're quite sure it's not just normal fluctuations since there's a repeating, exact-same pattern. These are high-volume, high-competition keywords. Any idea what might be the cause of this?"  

#### [0:14:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=870) |  I don't know. I occasionally see that

from people. It's not something that I would say is completely out of the question that this kind of thing happens. Oftentimes, it settles down because our algorithms figure out, oh, this is kind of a stable place how we should be ranking this site. If your site used to be ranking much lower, then this could be a sign that our algorithms are kind of wondering, should we be ranking a lot better? If your site used to be ranking better for this  

#### [0:15:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=900) |  and sometimes gets dropped down like that,

than it could be a sign that our algorithm is a little bit cautious more maybe. So that's something which I would kind of take as a sign to significantly improve the quality of the website overall so that our algorithms are less on the fence and have kind of a clear understanding that this is actually a really good website that we should be showing more. Then, "My website is losing indexing. For some weeks, my website has been  

![](https://i.ytimg.com/vi/C9dNFj0APvg/hq1.jpg)



#### [0:15:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=930) |  losing indexing for no apparent reason, and

no significant changes have been made except for the usual ones that are adding and removing vehicles." So the website was mentioned there, and I took a brief look beforehand, and one of the things that I noticed specifically with regards to the indexing of the content on the website is that it's really hard to crawl and index the content from your site. So, for example, if I do a site query for the website,  

#### [0:16:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=960) |  then a lot of the pages that

I find are kind of weird, listing pages, where I suspect maybe a vehicle or product used to be available and is no longer available, and it's kind of, like, with an ID of very high number. And my general feeling is there that we're just having a lot of trouble crawling and indexing the website. So that's something where what I would do  

#### [0:16:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=990) |  is try to figure out which URLs

you really care about, and, first of all, put those in a sitemap file, if you haven't done so already. And then, secondly, try to figure out, like, are these URLs actually being indexed properly, and, additionally, look at the other URLs that are being indexed for the website at the moment. If you look at a site query, that's kind of a rough idea to do that. And think about how those URLs were discovered. So the URLs that you don't care about,  

#### [0:17:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1020) |  like, why is Google spending so much

time on them, with the end goal essentially being kind of making it really clear for search engines which URLs you want to have indexed, being absolutely certain that Google can crawl your website normally and find those URLs and can focus on just those URLs that you care about. So that's kind of my recommendation there. Sometimes it also helps to use something like a third-party crawler tool to kind of crawl  

#### [0:17:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1050) |  your website if you're not sure where

these URLs are being picked up on. There are a bunch of different tools out there. Some of them are really good. So that might be an option to kind of try out while you're figuring out why our search engine is kind of getting lost within my website. "Mobile searches related to glasses, or prescription glasses, are resulting in duplicate content on the same page. In the first search results page,  

#### [0:18:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1080) |  it's due to the Interesting Find section,

which seems odd. Are you aware of this behavior? Does Google consider this to be an issue?" So I don't know exactly what you're seeing there. So it's really hard to say. In particular, a lot of the different sections in the search results page trigger in individual countries or trigger differently in individual countries. So when I search in English, I tend to get Swiss sites in English.  

#### [0:18:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1110) |  I don't tend to see exactly the

same thing as users in the US would see. So that kind of makes it hard for me to figure out what exactly you were seeing there. If you can send me some screenshots or maybe post them on Twitter or add them here to the YouTube comments, then I'm happy to take those and also send those to the teams here that work on the search results page. I think, in general, when it comes to different elements on a search results page,  

#### [0:19:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1140) |  it's always kind of tricky to find

that balance between providing lots of usefulness for users, lots of value for users, and, ultimately, providing too much clutter essentially in the search results, where if you look at the search results page, there are just so many different items there. And they're all kind of competing for your attention. And sometimes it can happen that you have different sections that show the same content, which, from my point of view, is kind of just, I don't know,  

#### [0:19:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1170) |  unnecessary clutter. It's not something I would

consider to be a serious bug or anything like that, or it's definitely not something we would do on purpose. But, sometimes, it just kind of evolves in that direction over time. And having examples where this is kind of annoying, that's really useful to pass on to your team so that they can understand, oh, if these different elements in the search results page are triggering and showing, we should make sure to not show the other thing here  

#### [0:20:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1200) |  because that's essentially showing the same thing

are not as useful for the user. "I'd like to know how Google indexes its sites with new extensions, like, .club or .tools. Is there any preference for indexing dotcom domains over these?" So we treat all of the new top-level domains like any other generic top-level domain. So there is no additional value to having keywords in the top-level domain.  

#### [0:20:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1230) |  There is no additional value in having

city names or country names in the top-level domain. We treat them all like any other generic top-level domain like a dotcom, essentially. So from that point of view, if you find a domain name that works well for your site that you want to keep for the long run, and it's a new top-level domain, then definitely go for it. I think that's perfectly fine. But, also, keep in mind that there is no bonus for using a particularly well-matching,  

#### [0:21:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1260) |  top-level domain. It's not that we would,

from an SEO point of view, treat those as anything better than other generic top-level domains. "What happens to visitors if we post duplicate content regularly?" I don't know. I mean, visitors are kind of out of our control. But from my point of view, like, if you regularly post duplicate content that is already on your website  

#### [0:21:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1290) |  or that's findable on other sites, my

assumption is, a lot of times, visitors will just end up going somewhere else because why should they go to your site if they've already seen that content somewhere else? So that's kind of one of the reasons also why we discourage people from just copying content because it's something our algorithms can pick up on, and we know users don't like it when we show the same content multiple times, kind of like the previous question there. So that's something where if you want to provide something  

#### [0:22:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1320) |  on the web, you want to make

sure that's visible in Search, make sure it's unique, compelling, high-quality, all of the usual attributes. "If our business has good ratings on some authentic websites, can showing those ratings on our site influence algorithms or rankings, not considering user behavior?" I don't think that changes anything. So if you have, like, a five-star rating  

#### [0:22:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1350) |  from some other service, and you put

that on your website, I don't think our ranking algorithms will look at that and say, oh, this sounds like a good thing. So from that point of view, from just purely an SEO standpoint, I don't think that changes anything. Obviously, users might care if you show users that your website is trustworthy, that it's regularly kind of audited and kind of reviewed, then that's something  

#### [0:23:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1380) |  that they might care about. But at

least from an SEO point of view, there is no immediate ranking change. "With this new passage indexing rolling out soon, will this help a site, for example, a blog, to get better rankings for more opportunities, for more search terms per article that is published?" So the passage ranking, or passage indexing update that we talked about there, like I mentioned in the beginning, I don't know the timing of this, when it will be visible where.  

#### [0:23:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1410) |  But, essentially, the idea is to take

particularly long pages and understand the relevant parts within that page a little bit better so that we can show those appropriately in the search results. So that's something if you have really long articles, then it might be that we pick up something useful in the middle, and we send users to that directly. If you have been doing SEO for a while now,  

#### [0:24:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1440) |  if you've been focusing on your website

for a bit, then probably you've already split those exceptionally long articles into shorter ones anyway so that it's easier to focus on specific aspects of what people are searching for. And in those cases, like, there is nothing really that you need to do there. So that's something where I like to see it more as if, like, you have really long pages on your site, and you've never really bothered to kind of watch out  

#### [0:24:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1470) |  for what users actually want and realize

that, oh, users are looking for a part of the page, not the full page, then that's something where I assume passage ranking will help out a bit. But it's not the case that we'll just take any article on the web and say, oh, there's, like, a good word on-- way, way down on the bottom of the page. Therefore, we will rank this page higher. It's not a general ranking improvement. It's more a better understanding of the content. AUDIENCE: John, can I follow up on that?  

#### [0:25:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1500) |  Yeah, so I had a question that

was very similar. You answered part of it in there where you had said, you know, if you're a good and savvy SEO, you may have already taken a long page and split it out into multiple pages. So I guess what I'm wondering-- so that is still the recommendation, I guess. And so I had an example of-- let's say you have a business that offers four or five services.  

#### [0:25:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1530) |  Previously, I would have always taken that

and done and created five separate pages, one for each service, so Google would understand the topic of that page. But with passage indexing, I was wondering perhaps does it make more sense to have one single page that lists all five services, potentially hoping that passage indexing, or passage ranking as you've said a couple of times now, passage ranking understands each chunk.  

#### [0:26:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1560) |  And the reason why I think that

could be advantageous perhaps is consolidation of link authority and link building. So you have one URL now that has multiple links, and that page could be very authoritative. Do you think that strategy makes any sense, or would you still kind of go to one separate page for each service? JOHN MUELLER: I don't know. So from my point of view, I would test it. I would see how it works. I don't think, by design, that's necessarily a bad way to do it.  

#### [0:26:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1590) |  I also don't think it's necessarily kind

of, like, always going to be the right approach because when users are looking for something that's kind of on the bottom of the page, and they land on the top of the page, then maybe they'll be lost, and your conversions will suffer a bit. I don't know. But I would definitely try it out and see what happens. I could imagine that maybe you find  

#### [0:27:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1620) |  a balance that works well and is

kind of positive, under-the-line for you. AUDIENCE: So, theoretically, that's how passage ranking or passage indexing could work, where, now, previously they had this one page with 10 different services. It'd be hard to understand the topics of all of them, but now passage ranking might better understand, well, this is about service A, this one's about service B, and then rank those sections, or passages, appropriately for queries. So this theoretically could work. Could it be better?  

#### [0:27:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1650) |  I guess that's to be tested. JOHN

MUELLER: Yeah, I don't know. I mean, it's kind of tricky because we could still understand that part of the page is appropriate for that query, but would there perhaps be a factor of saying, well, the other parts are kind of contrary to that part of the page is understanding, like, if you have completely independent services, then it might look like, oh, you're offering consulting, and you're selling products, and if someone  

#### [0:28:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1680) |  is trying to buy a product, then

it's, like, well, how do we weigh these? AUDIENCE: Yeah, that makes sense, and if it's way off, yeah, that probably-- but, like, maybe an electrician that offers, you know, outdoor lighting, interior lighting, all these different services. They're all electrical services. Yeah, OK, that's cool. I might give it a shot. JOHN MUELLER: I would try it out. I mean, all of these new things I think are just always interesting also to see how they kind of react  

#### [0:28:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1710) |  to something like that, where you kind

of have an understanding of what you would expect, and you can see if you would see changes like that. AUDIENCE: Wonderful. I'll wait for you to tell us when it goes live. JOHN MUELLER: I mean, you could also-- you could also do something like that now and see what the effect is currently because some effect will also be there because it's always this balance of taking multiple pages that kind of have to rank on their own. You're diluting the value, or you're concentrating  

#### [0:29:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1740) |  that value on a single page. So

some effect you might see already, and when we switch that on, you might see, oh, well, overall, there's an even stronger effect now. But I honestly don't know. And I think it's something that probably depends quite a bit on the type of site that it is, so just taking any random 10 pages and putting them together on one page, that's probably a bad idea,  

#### [0:29:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1770) |  but maybe there are certain configurations, like

you mentioned, where it could make sense, yeah. AUDIENCE: Awesome. Thanks so much. JOHN MUELLER: Sure. And I have your question next. Is there anything else that you'd like to add there with regards to passage indexing? AUDIENCE: No, you covered it very thoroughly. Thank you. JOHN MUELLER: OK. Cool. "Are you still planning on dropping support for the webmasters discovery document end of the year?  

#### [0:30:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1800) |  There haven't been any updates since the

original blog post in August, and I urgently need to plan changes if this is still true." I just double checked with the team. I haven't heard back. So I'll double check to see what is happening there and maybe post an update in the YouTube comments to your question. From looking at the old blog post from August, it seemed like it was pretty clear that we're going to drop that discovery document.  

#### [0:30:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1830) |  But maybe there is a new discovery

document that you can switch to. I don't know. "Feels a bit like I'm following you, but I could really use your help. We have a website, which is a Finnish site that got penalized in January for thin content. Since then, we basically rebuilt it from scratch, addressing every possible issue related to thin content. Affiliation on the site is minimal and with value to users.  

![](https://i.ytimg.com/vi/C9dNFj0APvg/hq2.jpg)



#### [0:31:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1860) |  We're trying our best to make the

site as good as possible for them, but we keep getting rejected from the reconsideration request. And I'm not sure what to do now, and, in general, how does the site owner get more clarity when dealing with such issues such as manual actions? So kind of to the last part with regards to getting a bit more clarity, what I would recommend doing there is posting in the Help Forum,  

#### [0:31:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1890) |  in the Search Central Help Forums, because,

like I mentioned, the product experts have seen a ton of websites, and they can give you advice in lots of different directions, especially with regards to manual action. So a lot of those cases also end up in the help forums. And they can escalate issues, where appropriate, when it looks like someone from the web spam team might need to take a better look at that. So that's essentially the place that I would go there.  

#### [0:32:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1920) |  I briefly looked at your site and

the manual actions that were associated there, and I didn't double check with the web spam team with regards to what you should be doing or what you could be doing differently there. But one of the things I noticed is that you have a lot of different sites that are essentially focusing on very similar topics. And I know the web spam team sometimes uses this kind of manual action as well to help clean up these issues where  

#### [0:32:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1950) |  you have a ton of different sites

that are essentially targeting the same keywords, where it tends to look more like a collection of doorway sites. So that's something where if that's the case, if you have a lot of different sites that are essentially all the same content, then that's something I would try to resolve in addition to just fixing things on this one particular site because one of the things the web spam team kind of worries about is you fix this one site,  

#### [0:33:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=1980) |  and your manual action is resolved there,

and then you take that, and you use that across a big network of sites. So that's something at least to address in a reconsideration request when you submit that and probably something the product experts would also pick up on, where when they look at your thread and look at your site, they're like, oh, but what about this network of sites  

#### [0:33:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2010) |  that you have here? What is the

relationship here? Yeah. And if you end up not getting anything useful from the help forum, feel free to escalate it here in one of these office hours again, and I can pass that on to the web spam team directly to see if I can get something more specific that I can point you at. "When considering multi-language and multiregional sites and hreflang implementations, is there any problem with  

#### [0:34:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2040) |  combining usage of subdomains, country code, top-level

domains, generic top-level domains in subfolders, for example, example.com/UK or fi.domain.com or domain.se?" You can definitely combine all of these. For hreflang, it doesn't matter at all which URL patterns that you use. For geotargeting, we need to be able to understand a clear section of your site.  

#### [0:34:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2070) |  And, in particular, for geotargeting, what we

look at is either the country code top-level domain, or if you have a generic top level domain, the setting that you have in Search Console, which you can apply on a subdomain or subdirectory level as well. So something like domain.com/UK would be perfectly fine. You can set geotargeting for that. However, something like domain.se/UK, that would not work for geotargeting,  

#### [0:35:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2100) |  because we would see that as being

part of a country code top-level domain, and we would not let you set the UK geotargeting for that subdirectory. But for hreflang, if you just have the same content on different pages, and you don't care about geotargeting, then that's perfectly fine. In general, with hreflang, I would use hreflang when you're seeing issues with the wrong country version being shown in the search results.  

#### [0:35:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2130) |  A really common use case is if

you have an international brand where someone searches for a brand name, and just from the brand name alone, we don't know which language version that we should show the user. Then their hreflang helps us to pick out which version we should show. Whereas if someone is already searching in a specific language for, like, a generic term for a product or for your services or something like that, then the hreflang annotation  

#### [0:36:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2160) |  is not really that helpful because we

already understand this user is searching in that language. Therefore, we should show that user that content. So that's something kind of to keep in mind ahead of time when you're planning the implementations there. With hreflang, it's very easy to set up very complex implementations. And a lot of times, you don't need to have complex hreflang implementations. You might just need it on a handful  

#### [0:36:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2190) |  of pages across your website. "When determining

search ranking or where to position websites apart from organic traffic, does Google consider traffic from other sources like YouTube or Facebook or Pinterest? So if a user enters a page via social media platform, finds the information useful and relevant, does it have any effect on search rankings?" No. At least as far as I know, none of that applies. It's not the case that we would track that for search.  

#### [0:37:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2220) |  It's not the case that we would

use that for any kind of search ranking. So if you're using social media, and you're driving traffic to your website, that's fantastic. But I would see that as something that you do for social media and not as something that you're doing for SEO reasons. Of course, you can kind of combine that in looking at the longer view. So if you drive traffic to your site using social media, and you encourage them, for example, to link to your site  

#### [0:37:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2250) |  or to recommend it so that we

can pick it up for search, then, indirectly, we could pick that up for search. But it's definitely not the case that just because someone comes from social media we would rank the site higher. "We have a relatively high volume of URLs in discovered, currently not indexed in Search Console. What can we do to get googlebot to crawl those URLs? Is having a CSR," so I guess Client Side Rendering," "a contributing factor for this issue?"  

#### [0:38:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2280) |  I don't think client-side rendering would be

associated with this because we would still be able to crawl those pages regardless. And client-side rendering-- so kind of like if you have a JavaScript-based website, and we have to do JavaScript to pick up the content, that's something that usually is less problematic with regards to indexing. We can do that fairly easily. Usually, if you have a lot of URLs in this discovered,  

#### [0:38:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2310) |  currently not indexed, section, that means we've

crawled your website. We've seen a lot of these URLs, but we currently are not convinced that indexing them will be valuable to our users. So that's something where it's less a matter of something technical that you need to change on your website, but more a matter of making it clear to us or to the search engines in general that actually all of this content  

#### [0:39:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2340) |  is very important and useful to have

indexed. So that's kind of the direction I would head there and focus a little bit more on kind of quality rather than just purely quantity. In general, it's extremely common for websites to be partially indexed. That's kind of-- essentially, that's normal. And the indexing rate of any website will fluctuate over time. So kind of that number of discovered, but currently  

#### [0:39:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2370) |  not indexed, that number will always fluctuate,

I think, regardless of the type of website that you have. "We had mdot URLs for a mobile site, which were used as alternate versions for the desktop version. We now have just the desktop version, so www, and the mdot URLs are redirected. Should we use the Change of Address Tool in Search Console? Will it change anything with SEO or crawl budget?"  

#### [0:40:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2400) |  You don't need to use the Change

of Address Tool. That's something that we would just pick up the versions automatically. So if you're redirecting, then we will pick that up. There's no need to use the Change of Address Tool. The Change of Address Tool is more if you're actually moving between different websites. In this case, you're essentially going from mdot to www, and that's kind of within the same website. So there is nothing special that we need to do there. With regards to crawl budget or SEO, this has no effect.  

#### [0:40:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2430) |  So what will happen there over time

is we will primarily crawl the www version of the URLs. We will occasionally look at the mdot versions because we might still find links to those pages, or we just want to make sure that we're not missing anything. But for the most part, we will concentrate on the www version. And from a crawling point of view, that shouldn't be any change overall.  

#### [0:41:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2460) |  "Can additional properties and schema which are

not mentioned in the Google documentation give any benefits to Google, especially in the case of AMP, non-AMP articles schema? If we add AMP articles, properties, on non-AMP pages, is there any harm or benefit?" So there is probably no benefit at all and probably also no harm there. In general, we recommend using structured data for elements that you want to have visible in the search results,  

#### [0:41:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2490) |  and the ones that we have visible

are based on the properties that we have documented. So if you add structured data for things that we don't use for visible rich results, then we can crawl those pages still normally. We just don't use that kind of extra information. It's fairly rare that you would be able to provide some structured data on a page, which gives us unique information that we don't see from the page itself that helps us to understand that page better.  

#### [0:42:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2520) |  And I think, in particular, the AMP

article markup, that's not something that tells us something different about the page. It's just a different way of providing metadata for the page in general. So it definitely wouldn't cause any problems, but I don't think you would see any advantage of doing that. "The mobile friendly test is showing our page as mobile friendly, but when I generate the report through Lighthouse and Chrome Inspection, it's showing me some issues like top targets are not  

#### [0:42:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2550) |  sized properly. Can that influence our rankings?"

So if the mobile friendly test is saying things are OK, if the Search Console mobile friendliness report is saying things are OK, then you should be all set. The tricky part with mobile friendliness is there's no objective measure to say this is mobile friendly or not. In particular, the top targets that you mentioned you could argue with people that there's a certain size top  

#### [0:43:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2580) |  target that needs to be there by

minimum. But that's not something that necessarily will be the case across all different sites or all different devices or all different people. So that exact size that kind of is valid for a large enough tap target, that's something that could vary across the different testing tools. So if you purely care about how Google Search sees  

#### [0:43:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2610) |  your site for mobile friendliness, then I

would use those tools. If you kind of want to get a better view of how other tools might see your site or give recommendations with regards to mobile friendliness, then I would definitely take those other tools into account as well. OK. AUDIENCE: Hello? JOHN MUELLER: Hi. AUDIENCE: I think that was my question. It's OK if I have follow-up? JOHN MUELLER: OK. AUDIENCE: [INAUDIBLE].  

#### [0:44:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2640) |  And since that GSC is reporting mobile-friendly

issues. But when we do a line inspection within GSC, it shows that the URL is mobile friendly. Should we consider that as an issue or not? JOHN MUELLER: It's hard to say. When you say you've revamped your site, my general assumption is if the mobile-friendly test says it's OK, then I would not worry about it.  

#### [0:44:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2670) |  I assume that those issues in Search

Console are mostly with regards to kind of rendering your site. And because we cache some of the embedded elements on a page, also like a JavaScript in CSS, it can happen that we have kind of a mixed view of a site that has just been revamped completely. So my assumption is, without looking at those specific examples, that probably this is just  

#### [0:45:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2700) |  a temporary phase, and things will settle

down over time, like over a couple of months, then our kind of understanding of the site overall with regard to mobile friendliness, that settles down again. Cool. Yeah, I think the only new question that came was with regards to the update timing, which  

#### [0:45:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2730) |  I think we chatted about with Barry

already in the beginning. What else is on your mind? What else can I help with? AUDIENCE: Hi, John. AUDIENCE: Oh. AUDIENCE: OK, you can start. AUDIENCE: OK, OK, John, I have the question about duplicated content because you replied to this question that it depends on the situation. And if you are talking about moving service,  

#### [0:46:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2760) |  for example, if we need to move

stuff from Toronto to Vancouver or from A to B, and I found that many pages on the top 10, they have two pages separate. For example, if we want to move from Toronto to Vancouver, this page usually submits some information  

#### [0:46:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2790) |  that are related to Vancouver why you

need to live there, better school, better shops, and something like this. And if we create two pages from Vancouver to Toronto and from Toronto to Vancouver, is it OK? Or because we have similar titles, Google will understand that these pages have different content? JOHN MUELLER: Yeah.  

![](https://i.ytimg.com/vi/C9dNFj0APvg/hq3.jpg)



#### [0:47:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2820) |  I think it's hard to say comprehensively

there. So for just the situation where you have two cities like that, I don't see a problem. That's kind of, like, you have a handful of pages, and you kind of add the alternate versions of those pages. I don't see a problem. If you take all of the cities in Canada, and you say all of the combinations, then that's essentially a giant network of unnecessary content on a site.  

#### [0:47:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2850) |  That we would probably see as doorway

pages. So that's something where finding the balance between providing value to users and just filling it out with a database because you have a database of cities, for example, and you have some information from Wikipedia on every city, just because you have that doesn't mean that those are going to be good pages. AUDIENCE: But users have different intent, you know, when they are searching for service to move stuff  

#### [0:48:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2880) |  from Toronto to Vancouver, and they want

to know about Vancouver, and when I check out to the top-10 results, I see they submit this information. It's not only about some Wikipedia page about Vancouver. They reply to some questions that people might ask their intent, the distance from these cities and something similar, you know? And we don't know, do we need to create two separate pages  

#### [0:48:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2910) |  or just to create one page? JOHN

MUELLER: I would just create one page. Especially if you're talking about a large amount of pages, then that's something where I would try to limit it on the number of pages. I think it's sometimes misleading when you look at the search results, and you see, oh, other people are creating this kind of thin content, automatic content, in different variations. Therefore, we also need to do it. I think that's sometimes misleading.  

#### [0:49:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2940) |  But especially when you're starting out, I

would focus on a lot fewer pages and make those a lot stronger. So especially in competition with other websites, having fewer pages that are just significantly stronger makes those a lot more valuable, and it's also something where you need to watch out for kind of like misleading yourself with regards to the user intent. So kind of the question that you had there, like, well, users  

#### [0:49:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=2970) |  might want to find out more about

the city. I really doubt that someone who is looking for transport services from one city to the other wants to have background information about neighborhoods in the city or something like that. That's something where it's very easy to get this kind of information and just put it on a web page because you can. It's like their APIs, and the data is there. You can rewrite it automatically. But I don't think it provides value. And more and more, our systems are  

#### [0:50:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=3000) |  such that we understand when pages are

being compiled automatically, and then we will say, oh, maybe the whole website is just automatic content. We should demote the whole website. So that's kind of the long-term view. I would focus more on having fewer pages and making them a lot stronger. AUDIENCE: OK, understand. Can I ask in more details? For example, when people are searching  

#### [0:50:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=3030) |  moving from Toronto to Vancouver, they are

living in Toronto. They know about the city. And if I submit all of the information about Vancouver, If someone wants to move from Vancouver to Toronto, they will read information. They don't need it, you know, they don't need to know more about Vancouver. They want to know about Toronto. And, you know, at that point, we can confuse some people to submit information  

#### [0:51:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=3060) |  they don't need at all. JOHN MUELLER:

I would argue they probably don't need the information the other way around either. Like, if you're trying-- like imagine you're in this situation. You need to move to a different city for work, do you need background information on what the weather is like there? You're looking for a transport company. You're not looking for kind of like city information. Whereas if you're looking for city information, then you explicitly look for city information. You don't kind of say, well, oh, look on this transport company  

#### [0:51:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=3090) |  page, there is now a weather report

from the other city. How useful. Like, that's something where it's very easy to provide this kind of information. But I don't think it's something that search engines would say, oh, this is so useful to have this extra information here. They really try to focus on that individual query. AUDIENCE: [INAUDIBLE]. Thank you. JOHN MUELLER: Dave, I think you had a question?  

#### [0:52:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=3120) |  AUDIENCE: Yes, [INAUDIBLE]. I was quite interested

to see that the Core Web Vitals will count for noindex pages and things about robots.txt and stuff. It's quite interesting because, obviously, in Search Console, these are aggregators you get a group of pages. How do you understand that this is a group? If these are noindexed, then you've not got the contacts and stuff? Or is it just based on the URL path-- or, you know, and I know it's not even a ranking factor yet.  

#### [0:52:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=3150) |  So in the future, we don't really

know exactly how it's going to apply. But That's quite worrying. If you've got something in the members area, some kind of tool that takes a while. You've got bad vitals, but it's not really bad because it's expected. It's what it is. If that's going to leak out into your other site, that's probably going to be quite worrying for some people, but-- JOHN MUELLER: I don't know. I mean, my general feeling is there  

#### [0:53:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=3180) |  that that's something that's also part of

your website. So if, like, you use some extra functionality, and that's noindex, then kind of, like, people see that as a part of your website and say, well, this website is slow, or this website is fast kind of thing. I don't know how a Search Console reports on that particularly. I think within the Chrome User Experience report data in the Chrome developer site, they have some information on how the grouping is made,  

#### [0:53:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=3210) |  but I don't know how detailed that

is there. AUDIENCE: Right, yeah, sounds like [INAUDIBLE].. Thanks, John. JOHN MUELLER: I mean, one of the tricky parts is also-- it's very hard for us to understand when a page is something that is not meant to be indexed because like all of the canonical decisions and all of that, like, just looking at an individual page on its own, it's sometimes not absolutely clear is this something that can be accessed directly, or does that cookie that was set  

#### [0:54:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=3240) |  in the beginning need to be set

to access the page or, like, what all is involved there. So I imagine that's always kind of tricky to balance out. AUDIENCE: Yeah, a lot of moving parts. AUDIENCE: John, I had one follow up on that. It is actually very interesting. I was also thinking the same. So from SEO side, how SEO team should be worried about it, because there are a lot of pages that are noindexed, a lot of pages, especially in travel websites,  

#### [0:54:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=3270) |  there are so many search pages. On

that case, then how to ensure that pages are not at least decreasing the mobile ranking? It is very tricky for us. JOHN MUELLER: I don't have any great answers for you at the moment. AUDIENCE: So should we expect that [INAUDIBLE] there should be some document update. JOHN MUELLER: Maybe. Maybe. I don't know what the information out there is on the grouping at the moment. So it is really hard for me to say exactly,  

#### [0:55:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=3300) |  like, what you need to watch out

for or what you can kind of ignore. In general, when it comes to grouping across websites, when we try to do grouping, we try to do that, on the one hand, by URL pattern and on the other hand also by the kind of content on the site. And those are, I think, the way that we do the groupings in Search Console, for example. So if you have parts of your website  

#### [0:55:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=3330) |  that you want to be seen as

belonging together, then I would definitely make sure that from a URL pattern point of view, it's clear that these belong together. So if you're specifically worried about search pages, for example, then putting those in a folder with /search makes it a little bit easier for us to understand all of these search pages belong together, all of these product pages belong together, all of these blog posts belong together. We might be able to treat them individually when  

#### [0:56:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=3360) |  it comes to Core Web Vitals. The

other thing to keep in mind is we don't have a ton of aggregated data for every website. It might be that, for some sites, we just have few data points. So we just have kind of for the website overall information on the Core Web Vitals. And in that case, even if you use URL structures to split things up cleanly, we might not be able to use kind of that grouping because we just don't have enough data  

#### [0:56:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=3390) |  for those individual groups. So that's something

where I suspect, over time, probably we'll be able to have a little bit more information, but it'll still be something that is not 100% such that you can just say, oh, ignore this page, and do count that page kind of thing on a website. AUDIENCE: OK, thank you. JOHN MUELLER: You see something similar,  

#### [0:57:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=3420) |  like, it is totally unrelated to this,

but more related to grouping, when it comes to adult content, where if we can clearly understand the adult content belongs to this part of a website, then we can use Safe Search and say, well, this subdirectory or the subdomain must be filtered by Safe Search. Whereas if we can't tell that that belongs in just one part of the site, then we might say, well, the whole website needs to be filtered with regard to Safe Search. So that's also something where sometimes we  

#### [0:57:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=3450) |  have more data points. We can do

that clearer. Sometimes we just don't have enough data points, and we can't kind of do it that fine-grained. AUDIENCE: Mhm. OK, all right. JOHN MUELLER: All right, I think we're kind of at time. Maybe if there's one last question from anyone, happy to take that. Otherwise, we'll call it a week. AUDIENCE: Oh, can I ask about the content because you mentioned it?  

#### [0:58:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=3480) |  You know, some SEO specialists think that

we should use white-hat techniques for white niches, if you are talking adult content or some specific language use, including the Russian language. Now it's better to use black-hat techniques. Can you reply to this and how we can create links or provide some link building if you start from scratch, have no authority, adjust, and you  

#### [0:58:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=3510) |  want to give some links to earn

them. But with adult content, it's tough, and you do have some suggestions what to do? JOHN MUELLER: I mean, I can't suggest that you should use black-hat techniques. So from that point of view, I can really only point at our guidelines with regards to what we do recommend. So I understand that some people might say, oh, well, like, everyone else in my nation is doing it the wrong way.  

#### [0:59:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=3540) |  Therefore, I also need to do it

that way. And I don't know. Like, it might be that there are individual, special niches where our systems just aren't picking up kind of the abusive or problematic techniques well enough. But, I mean, from my point of view, if you want to look at the long, long run and not just focus on something that might work for a couple of weeks or a couple of months, then I would tend to focus more on that what we have documented.  

#### [0:59:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=3570) |  But, I mean, like, everyone tries out

different things. And, sometimes, the best advice doesn't work for you, so, like, I don't know. I can't physically hold you back from doing kind of black-hat-- AUDIENCE: It's only my opinion, you know? I just thought that you can find on Reddit or many forums where people shared this thought that we should use black-hat techniques for adult niches  

#### [1:00:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=3600) |  because you can't get results with white

hat. I just want to know your thoughts about [INAUDIBLE].. JOHN MUELLER: I mean, there is a lot of talk on online forums in general, and it's hard to understand, like, who really knows what they're talking about. And so I don't know. It's always worth taking that with a grain of salt. AUDIENCE: OK, thank you. JOHN MUELLER: Dwayne, I think you just raised your hand as well.  

#### [1:00:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=3630) |  Hi. AUDIENCE: Hi, John. Yes. So I

have a situation where I've seen AMP articles being served on desktop, even though we have the proper canonical setup, and we don't have self-referring AMP canonicals. Is there something that we should worry about there? JOHN MUELLER: I don't know. If you just occasionally see that, my guess is it's  

#### [1:01:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=3660) |  more a matter of kind of a

skew from crawling and indexing that we maybe picked up the AMP version first, and we didn't pick up the desktop version yet. So we might show the AMP version temporarily in the search results as well. But if you see that regularly, especially for the same URLs for the long run, then that feels like something where either we can't understand that connection properly, or there's something going wrong on our side.  

#### [1:01:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=3690) |  So what I might do there is

maybe post the Search Help Forum, or the Webmaster Help Forum and include some of the details that you have there, especially if it's something that you see happening regularly, and it's always the same URLs, then that's something where the folks there can take a look with their tools and kind of their understanding of how things work and, otherwise, escalate that to googlers, if needed.  

#### [1:02:00](https://www.youtube.com/watch?v=C9dNFj0APvg&t=3720) |  AUDIENCE: Thank you. JOHN MUELLER: All right,

so let's take a break here. It's been great having you all here. I'm glad this time kind of worked out. I guess I'll set these up a little bit more regularly, and on Fridays as well, to try to cover that US time zone because it feels like during the week when I usually have these planned on Tuesdays, there's always so much other things happening  

#### [1:02:30](https://www.youtube.com/watch?v=C9dNFj0APvg&t=3750) |  trying to get my time. So maybe

on Friday, it'll be a little bit easier. Thank you all for joining here. I hope you all have a great weekend, and stay safe, and, hopefully, see you in one of the future Hangouts. AUDIENCE: Thank you. Bye, bye. JOHN MUELLER: Bye, everyone. AUDIENCE: Thank you. Bye, bye. AUDIENCE: All right, John, thank you.  