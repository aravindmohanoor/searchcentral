[![English Google Webmaster Central office-hours hangout](https://i.ytimg.com/vi/TlocS5b_46o/maxresdefault.jpg)](https://www.youtube.com/watch?v=TlocS5b_46o)

## English Google Webmaster Central office-hours hangout

Join us for a Google Webmaster Central office hours hangout on July 9, 4pm CET 

https://www.timeanddate.com/worldclock/fixedtime.html?iso=20190709T16&p1=268



This session is open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. Add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



To join live, watch out for the link here once the event starts, and use a webcam + headset. Feel free to drop by - we welcome webmasters of all levels!



#### [0:00:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=0) |  JOHN MUELLER: Just a sec. Hi everyone.

Welcome to today's Webmaster Central Office Hours Hangouts. My name is John Mueller. I am a Webmaster Trends Analyst here at Google in Switzerland. And part of what we do are this Office Hour Hangouts for webmasters, SEOs, publishers, anyone who's kind of interested in search, has a website, and seeing some questions there. As always, a bunch of questions were submitted. But if any of you want to get started  

#### [0:00:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=30) |  with the first question, you're welcome to

jump on it now. JOAO: I would love to. JOHN MUELLER: OK. JOAO: So I have this client was asking me about the movie showtime Rich Snippet, the Google shows sometimes for certain branded keywords for the cinema name or a movie. And I was reading about it, trying to find out how to find them. We initially thought schema and a good table set up on the front end, and maybe  

#### [0:01:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=60) |  a new showtime late building date to

complement it. But we heard about this private API or something. That might be what's pulling out the results for the one box that still shows. We found this company called Webedia that actually works with movie database. So wanted to know if we, as webmasters, have the chance to find these rich results by implementing schema plus the tables or some good practices?  

#### [0:01:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=90) |  JOHN MUELLER: So Showtime's is the movie

schedule, right? JOAO: Yes, correct. JOHN MUELLER: I don't know how that's setup. I don't think it's related to specific structured data type. At least, we don't have it documented in the developer center. But rather as far as I know, it's  

#### [0:02:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=120) |  just separate feeds from kind of the

these bigger companies that are active in those-- in those niches. I can double check. But I don't know if I have anything specific I can point you out. So if you want, you can drop your email address. And maybe if you have a link to a help forum post that kind of elaborates on what you're trying to do, feel free to drop that into the comments here in the chat.  

#### [0:02:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=150) |  And then I can try to follow

up on that for you. JOAO: Absolutely, John. OK, thank you. I'll drop the-- we have a webmaster forum thread about it. And I was [INAUDIBLE] by email. JOHN MUELLER: OK, fantastic. JOAO: Thanks. JOHN MUELLER: All right. Any other questions before we jump into the submitted ones? No? OK, fine. Let's see if I can pull it up.  

#### [0:03:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=180) |  Quick question, should we use HREF lang

annotation in non-canonical URLS? Or must we only use it for canonical URLs? So the short answer is you don't need to. And it doesn't cause any problems if you were to use it. The kind of the background there is if a URL is not seen as a canonical URL,  

#### [0:03:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=210) |  then we would not show that in

search. So therefore, any HREF lang annotation that's associated with that URL would not be used. So from that point of view, if we wouldn't show the page in search anyway, then the HREF lang annotation that you add doesn't really change anything. So you can if you have the markup there already. But I wouldn't really spend any time  

#### [0:04:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=240) |  on adding HREF lang annotations to URLs

that are not going to be canonical. We have some links at our site to other internal pages. These links are shown as a pop-up with 5 to 10 lines of good quality explanation to the subject in the link. The link is marked as no follow. I have a feeling that this is not good SEO, both the pop-up the no-follow.  

#### [0:04:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=270) |  I would prefer to show the content

in the pop-up on one normal web page instead of 5 to 10 links with pop-ups. I suspect your suspicions are correct. So I think there are a few aspects there. On the one hand, if these are links are with a real no-follow attached to them, then we would not follow them, and not use them to kind of crawl and pass signals  

#### [0:05:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=300) |  across the rest of your website, which

is probably not something that you want. You'd probably want us to crawl all of these pages and to recognize how important they are and to show them more in search. So in general, for internal links, I would recommend not using the realm of follow unless you have really good reasons to do that. The other thing with regards to the pop-ups,  

#### [0:05:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=330) |  I don't really know exactly how you

mean that. So that's something-- it's kind of hard for me to say, but in general, you're welcome to link to other parts of your website. If you have a pop-up within your website pointing to other parts of your website, usually that's fine, as long as that works for your website, as long as that works for your users. So that's something I'm not really too worried about.  

#### [0:06:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=360) |  It's really more the matter of using

no follow for internal links for things that you do want to have indexed and shown in search. We're working on a page speed initiative to defer images that are outside of the viewport on page load, per the recommendation of Page Speed Insights. Our concern is that the crawler will have trouble finding images that are below the fold as they don't show up in the Dom on the initial page load. How should we balance the recommendations of Page Speed  

#### [0:06:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=390) |  Insights and the ability of the crawlers

to find [INAUDIBLE] this? There's a bit of background noise somewhere. Let me just mute some of you. See if that works. Perfect. OK, so with regards to images, I think there are a few aspects. On the one hand, you kind of need to think about which images you really want to have indexed.  

#### [0:07:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=420) |  So just because you have images on

a page, doesn't necessarily mean that they're useful for your website with regards to image search. So kind of think about how people might search using image search to find your content, and how they might want to search for things, which images they'd like to see, and how that can drive traffic to your website. So that's kind of the first thing is you don't really need every image on your website  

#### [0:07:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=450) |  to be indexed in. Image search a

lot of times images are more decorative and not something that actually drives traffic. On the other hand, there are multiple ways that you can use lazy loading to kind of defer the loading of the images in a way that still works for Google bot. So I double check our guidelines on that. That's something where there are different ways that you can do that and ways that would work  

#### [0:08:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=480) |  for Google bot in particular. And with

regards to the initial Dom of the page, that's less of a worry. It's more a matter of when we render the page do we find the link to the-- do we find the image tag that links to your images. And if we can find the link to your images, then we essentially have everything anyway. But those are kind of the three aspects I'd watch out for. Kind of just avoid just generally  

#### [0:08:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=510) |  indexing all of the images just because

you can. And then double checking the way that you're using deferred loading of images. And then making sure that those images that you do care about are linked in. A way that we can discover. How to affect a site with a DMCA notice. We have two about content that is legal. But we don't have the resources to protest. So we have removed the content, but not the DMCA notice.  

#### [0:09:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=540) |  Is that affecting Google SEO? So I

can't give you legal advice with regards to DMCA process. So that's one thing to keep in mind here. My understanding here is that if there is a DMCA complaint that is active, then we will remove that URL from search and show that notice in the search results appropriately.  

#### [0:09:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=570) |  Within search console, I believe you have

a link to kind of go through the process of claiming that this DMCA complaint was sent erroneously and that you disagree with it. And that step-- once that has happened, it's essentially up to YouTube. So kind of you as a person who published content, and the person who submitted the complaint initially, to figure out what the solution is there.  

#### [0:10:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=600) |  Usually as far as I know, that

goes through the normal legal channels. From search point of view, if you're talking about two DMCA complaints that have been submitted for your website, then generally, that's not a big thing. We will filter out those two URLs from search, and the rest of your content is the rest of your content. So that's not something that is really big problematic.  

#### [0:10:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=630) |  We're only receiving traffic from our brand

keyword from two months ago. But we're new in the top stories, because Google hasn't indexed our news for two years in the carousel. We change our directory from slash notices, and now we have top stories carousel, but only when we search for under the brand name. What can we do? Is there something more wrong?  

#### [0:11:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=660) |  Usually that's-- that can be completely normal.

So these top stories carousel is a normal organic search feature. There is nothing specific tied to things that you need to do on your website in order to be shown there. And in some cases, we show sites for some specific queries. In other cases, it makes sense to kind of broaden that out and show these sites for more broader queries. But this is a normal organic search feature.  

#### [0:11:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=690) |  There is nothing kind of manual about

that where you need to tweak things manually on your website to make it appear there. It's more a matter of we can crawl and index your content, and therefore, theoretically, we could show these pages in the top stories carousel. Sometimes it makes sense for our algorithms to pull in these kind of pages in the top stories carousel, and sometimes it doesn't. There is nothing really special in regards to that.  

#### [0:12:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=720) |  When we search for our brand keyword--

we're a digital newspaper-- we found a search results page with our address. Can we remove it? It's not interesting for readers. We're not a local business. I don't really know how you found an address. So if that's something that's on a specific website, then obviously, you need to contact that website to have that removed. As far as I know, especially for businesses,  

#### [0:12:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=750) |  it's not something where we would say

remove a random web page from the search results because it has an address of a business on it. So that's something where I'd recommend trying to find the source of that address and just having it removed there. If it's something that we're showing in the search results, usually we would pull that information in from the normal web content. So I would again, try to double check where that is coming from  

![](https://i.ytimg.com/vi/TlocS5b_46o/maxres1.jpg)



#### [0:13:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=780) |  and try to remove it from there.

We're about to launch some new brand pages to showcase the various different brands that we sell. They will be sub-categorized in brand and product line. However, we also manufacture and sell items under our own brand name. I'm concerned that our brand-- new brand pages will compete with the main category pages  

#### [0:13:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=810) |  that have all brands listed. I've been

looking at how other retailers do this. And while M&S do seem to manage it, well, there are not many examples out there. I was thinking of setting our own brand pages as no index or with canonical to the main category page to prevent them from competing. These are ultimately to help users to find the products that they want. But it would be counterproductive if the main products all rank as a result--  

#### [0:14:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=840) |  or all tank as a result. Do

you think that's a good idea? I think that's always worth considering. So if you have different pages on your website that are essentially available for ranking for the same keywords, then theoretically, they can compete with each other for those keywords. Theoretically, it can also happen on multiple of these pages show up in the same search results page, which, on the other hand, might be fine.  

#### [0:14:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=870) |  So that's-- I think it's fine to

look into that and to consider does it make sense to combine things into one page? Does it makes sense to just have one of these pages indexable? Or doesn't make sense to have these different pages indexed separately, because maybe they fulfill a different need or a different kind of query. So that's definitely something I would look into.  

#### [0:15:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=900) |  That said, I don't think there's really

a clear kind of perfect answer for this situation. It really depends on the website, on the type of content that you have on these pages. For example, if you're the manufacturer and this is your own brand, then chances are not a lot of other sites are going to be trying to rank for those keywords anyway. So while you might be kind of competing with yourself for those keywords,  

#### [0:15:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=930) |  you're competing at a very high level.

You're kind of competing for position one, two, or three. And these are all pages within your own website. So it's not that your main pages would suddenly disappear when someone is searching for your brand. It's more that well, there are multiple pages now that are showing in the search results when someone is searching for your brand. On the other hand, if you're competing with a lot of other websites out there and they're all trying to rank for these kind of brand name  

#### [0:16:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=960) |  terms as well-- maybe this isn't your

own brand, maybe you just have a lot of resellers that are really strong-- then that's the kind of situation where you might say, well, there's a lot of competition out there. For us, it's a matter of ranking number three, number four versus ranking on page two somewhere if we kind of dilute things into two or three separate pages. In that kind of situation it probably makes sense to concentrate things on one page, which you could do by no indexing the other page,  

#### [0:16:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=990) |  by using a rel canonical, by just

having one page overall. Any of these kind of mechanisms to combine multiple pages for indexing, that might make sense there. So that's again, something where I don't have an absolute answer. But where you can kind of look at the situation yourself and see is there a lot of competition here? Do I have to make sure that I have really, really strong pages?  

#### [0:17:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=1020) |  Or will my pages rank anyway? And

it's more a matter of which of these pages I want to have shown in search. And then maybe it's not so critical that you combine things and make fewer pages that are a bit stronger. Let's say someone wants to launch a new website in a competitive niche where the search results are dominated by 5 to 10 year old-- or 10 to 15-year-old sites with thousands of links.  

#### [0:17:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=1050) |  Let's say the website owner is convinced

he can do a better job than them by providing visitors amazing content with great user experience. Does the webmaster have a chance in a reasonable time? I don't know, maybe, so I mean, there are always these storybook examples out there where someone comes charging in with something really fantastic and it blows everything else away.  

#### [0:18:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=1080) |  And they perform really well in search

and perform really well in business overall. It's possible. It doesn't mean it's going to be easy. So in particular, if you're looking at the search results, and these are companies that have been actively working for those 10 to 15 years on those websites, and they're really strong at competing with each other for these kind of search results, then I suspect that's going to be really, really hard.  

#### [0:18:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=1110) |  On the other hand, if these sites

are out there and they were put up 10 to 15 years ago and kind of left to kind of hang around for a long time, then maybe that's something where you could do something completely novel and kind of turn that upside down. But it's young. I mean, it's not something where there's a clear answer where I'd say it's like it's never possible or it's always going to be possible.  

#### [0:19:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=1140) |  Sometimes it's just very hard, a lot

of hard work. Yeah. It's really hard to say. I wouldn't-- I wouldn't assume that just because other sites are out there longer and have a lot of links, that it's impossible to rank instead of them. Question about flexible sampling.  

#### [0:19:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=1170) |  Let's see. If we use a lead-in

approach rather than metering and we enclose a paywall content with structured data, does this mean we can provide the entire article to Google bot for indexing and not have it considered cloaking? Yes. That's essentially how the flexible sampling approach works. You can provide the content to Google with the appropriate structured data.  

#### [0:20:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=1200) |  And when you feel that it's appropriate,

you can show either the lead-in or you can have kind of the metered setup that you say in this particular case, users are able to see this much content, this much content, or maybe they're only able to see a certain number of pages. That's totally up to you. So that's something that you can do with flexible sampling.  

#### [0:20:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=1230) |  It's always a matter of does it

actually work for a website? Does it work for your business? So that's kind of more the angle that I would worry about there. If users come to your site and they can't read any of your content and they can find just as much good information out there on the rest of the web, then probably they're not going to jump through hoops to kind of get access to that content. But on the other hand, if they've seen that there's something really useful on this website,  

#### [0:21:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=1260) |  and they see either from the lead-in

approach or from kind of the articles that they've been able to access already that this is something that's worthwhile to go through these extra steps of registration or payment or subscription, then that sounds like a good idea. My recommendation there would generally be to experiment with this. So don't just go all in and do it, like in the extreme case  

#### [0:21:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=1290) |  that you only have a line of

text from all of your content. But really kind of double check to see what works well for your users and for your specific content. Nowadays everyone talks about user intent. If a page is blocked by robots text and its ranking, how does Google determine the query relevancy  

#### [0:22:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=1320) |  with page content as it's blocked? If

Google is using other signals, then what happens if the site owner will replace the entire content, for example, if pornographic content is added? So if it's blocked by robots text, obviously we can't look at the content. So we do have to kind of improvise and find ways to compare that URL with other URLS  

#### [0:22:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=1350) |  that are kind of trying to rank

for these queries. And that is a lot harder. And because it's a lot harder, it's also something where if you have really good content that is available for crawling and indexing, then usually that's something where you would try to kind of use instead of a random roboted page. So from that point of view, it's not that trivial.  

#### [0:23:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=1380) |  We do sometimes show roboted pages in

the search results, just because we've seen that they work really well in that when people link to them, for example, we can estimate that this is probably something worthwhile. All of these things. So it's something where as a site owner, I wouldn't recommend using robots.txt to block your content and hope that it works out well.  

#### [0:23:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=1410) |  But if your content does happen to

be blocked by robots text, we will still try to show it somehow in the search results. Um, I asked the question about subdomain leasing in the last Hangout. But there have two more questions. I think your answers would be interesting to the wider webmaster audience, especially as you talked about changing domains recently.  

#### [0:24:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=1440) |  A few months ago the owner operators

of some coupon white label sites that were leased subdomains changed. It seems even though all the content was fully replaced. There was no significant effect on the site's rankings in Google. So my questions are how does Google normally treat cases where the complete content of a website or URL is replaced with similar but completely new content?  

#### [0:24:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=1470) |  This is actually pretty common. So I

mean, probably not that coupon sites are swapped out, but that you replace content on a web page is a pretty common situation. So it's essentially, normal website revamp. Sometimes it's just content that's rewritten. From our point of view, we kind of take the signals that we have associated so far with that particular page and we look at the new content  

#### [0:25:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=1500) |  and we associate whatever new signals that

we can pick up from the new content with that page as well. So if things are just slightly shifting-- so if you take an article on your web page website and you just rewrite it to kind of be more modern to include the modern words, to include more modern information, then we'll take that more modern version into account and use that for indexing. It kind of makes sense, the same thing would happen here.  

#### [0:25:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=1530) |  If one kind of coupon page content

is swapped out against a different coupon page content, it's essentially a way of rewriting a certain page. So that's not something I would see as being particularly unique in that sense. The important part when you're doing a revamp like this with your website is ideally to keep the same URLS as before.  

#### [0:26:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=1560) |  That makes it a lot easier for

us to associate the old signals with the new content. So if you're making significant changes on a website, try to keep the old pages as much as possible. If you can't keep the old pages, then redirect pages that have changed to the appropriate new URL. How does Google normally treat cases where the owner operator of a website changes? So if we're looking at a general business or a general website,  

![](https://i.ytimg.com/vi/TlocS5b_46o/maxres2.jpg)



#### [0:26:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=1590) |  sometimes the ownership situation changes and essentially

the website itself continues to run in the same or pretty much the same way. And that's not really something where Google would get involved in. In that sense, it's kind of like you have one company, it's running a website, and that company gets acquired by a different company. And now theoretically, the owner of that website is that other company, but everything around their website  

#### [0:27:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=1620) |  is essentially still the same. It doesn't

make sense for Google to change anything significantly in their index in the search results just because of some ownership change there. I think it would be different in situations where say, one website expires and someone else picks up that domain name and puts a new website on there. Then that kind of makes sense to treat that differently,  

#### [0:27:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=1650) |  because it's essentially a new website instead

of the old one. But if you're just changing ownership, that's kind of normal thing to happen over time. It's not anything unique that from my point of view, we'd need to treat differently. I also think it would be really hard for Google to try to pick up these kind of things, because we don't really track like, who exactly owns which website or which part of a website  

#### [0:28:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=1680) |  and how does that evolve over time?

I recently started working on a website where pages in one of the languages don't get indexed at all. So the question goes on with a bunch of examples. I looked into this briefly. One of the things that I noticed is every time I try to access the Polish version of a page,  

#### [0:28:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=1710) |  it redirects me to an English version

of the page. And I noticed that this also happens for Google bot as well. So when we tried to render one of these Polish pages, we get a redirect to the English version, which is probably done because you're recognizing that it's maybe an English-based browser or not a Polish-based browser, and it makes sense to show the English version of the page instead. In practice, what happens there is we only see the English version.  

#### [0:29:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=1740) |  We never really have access to the

Polish version. So we can't really index that properly. So what we usually recommend for cases like this is if you have a home page that does this kind of adaptive language switching, then that kind of makes sense. But you should have individual landing pages for the individual languages, so that if someone explicitly goes to the English version, they'll always get the English version.  

#### [0:29:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=1770) |  If someone explicitly goes to the Polish

version, they'll always get the Polish version. And then when you have it setup like that, you can have the home page doing that automatic redirect. And you can use the HREF lang annotations for that. In particular, for the home page, you would have x-default to say this is the default version where I do my fancy redirect. And then you have the English version where you say this is my English version with HREF lang and the Polish version with the Polish version for HREF lang.  

#### [0:30:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=1800) |  And then you look at that set

of pages, we see there is an English version, the Polish version, and the default version, where if we don't know where to send people, we'll send them to the default version. You can do your fancy redirect there. But we need to be able to access the individual language versions individually. Usually, that also means for the individual detail pages on the website, so the individual products or categories that you have.  

#### [0:30:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=1830) |  Usually you wouldn't set that up, because

it's easier to just have one English version and one Polish version of those pages rather than to have a third redirecting version for every product page every category page. So with just like a Polish version and an English version, I would just make sure not to set up a redirect, and instead to use the HREF lang annotations between those two versions so that we can crawl and index both of those versions independently,  

#### [0:31:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=1860) |  and use HREF lang to swap them

out as accordingly. If you see that the wrong version of these pages is shown to users sometimes, what I would recommend doing is showing a banner on top instead of redirecting. With the banner, you're leaving it so that anyone is able to access any of those language versions. But they're still getting that information that actually the version that probably suits them better  

#### [0:31:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=1890) |  is available here. And they can just

click on the link to go maybe to the Polish version or to the English version. So that's generally the recommendation I would have there. So first, remove that automatic redirect on the product page. Maybe setup something similar with a redirecting home page, if you want to do it for the home page alone. And make sure to use HREF lang annotations between these pages. And then finally, if you want to do  

#### [0:32:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=1920) |  something fancy use a banner instead of

a redirect. KUBA: Hi John. Can you hear me? JOHN MUELLER: Yes. KUBA: Great. So that question comes from me. I was just wondering all things considered, I will check all the things that you said. But there's not a thing with the no index error in search console. So I given an example as well for that. Search console shows me that there is a no index meta tag,  

#### [0:32:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=1950) |  but it's neither in the meta tags

nor in the header. So I'm wondering if this is just a fluke or could this be a problem as well with all that? JOHN MUELLER: I don't know. I don't know where you see the no index. So usually what I suspect would be happening here is we would--  

#### [0:33:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=1980) |  I'd have to double check the URL.

But what is probably happening here is we get confused with the canonicalization of that page. So because of the redirect primarily, like, which of these pages should be canonical with what? And we probably or possibly pick a URL  

#### [0:33:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=2010) |  on your website that has a no

index on it as a canonical for whatever reason. And it's not so much the matter that there is a no-index there. It's more that we get confused with the canonicalization, therefore we could be showing things that are not so useful for you in Search Console there. So I'd have to double check that particular URL. Is not the first one that you have in the--  

#### [0:34:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=2040) |  KUBA: Well, there is many of them,

but I've just given one example. Do you mind if I email you like, in a couple days when I check all the things to [INAUDIBLE] on this? JOHN MUELLER: Sure. Ideally, maybe just paying me on Twitter, and then we can do there. KUBA: OK, great. Thank you. JOHN MUELLER: Sure. I think with this kind of redirect thing you could see a lot of weird results because of that essentially go away  

#### [0:34:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=2070) |  wants to redirect as is fixed or

once that's removed. MIHAI: John, can I follow up on this? JOHN MUELLER: Sure. MIHAI: So when you have a homepage that does redirect the user based on an IP address, how does Google handle ranking signals that point towards that home page? Like, links for example. Most links usually go to a website's home page. Does Google forward that to the English version, because Google bot is coming from the US,  

#### [0:35:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=2100) |  and it's likely that the redirect will

go to the English version? Or does Google know how to handle that automatically and spread it out based on HREF lang or anything? JOHN MUELLER: So usually what would happen there is we would pick a canonical for that page, which would possibly be the English version, so depending on how that's set up. You can look up the canonical in Search Console with the inspect URL tool. And that would be the URL that would essentially  

#### [0:35:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=2130) |  collect these links. Because for links, we

link-- we see them as going from one canonical your out to another canonical URL. And essentially, that's how we would track that. What happens there in practice is if say the English version were to rank, and with the HREF lang annotation, we know their home page would be the better fit, then we will just swap out the URL after we put together the search results page. So basically, the ranking stays the same.  

#### [0:36:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=2160) |  We swap out the URL against the

home page and do it like that. MIHAI: Does that happen for somebody who is from a location where a different version [INAUDIBLE]?? JOHN MUELLER: Sure. Yeah. So if you have the English Polish version from before, if you come from Germany, then you like well, we don't have like, a German. But we have an x-default. So we'll show the home page, which is the x-default. MIHAI: And does the x-default tag needs to be placed only  

#### [0:36:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=2190) |  on the initial-- the first page from

each language version? Would that be enough? JOHN MUELLER: Yeah, yeah, yeah. It's kind of weird with the default version, because if you're doing this kind of automatic redirect, then you can't actually put it on the home page. But you can put it on the different language pairs. So if you have English and Polish version, you say this is English, this is Polish, and this is x-default default. And we can't really  

#### [0:37:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=2220) |  compare and kind of control the x-default

default version. But we trust that it's there, because you're linking to it from the different language versions. MIHAI: OK. But do you generally recommend not to have this kind of homepage redirecting setup? Or should it be like-- I noticed, for example, I think IKEA was using just a general home page where you can just choose-- the user can just choose the language version. Is that better for Google bot or--  

#### [0:37:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=2250) |  JOHN MUELLER: That works. MIHAI: OK. JOHN

MUELLER: I think people do it in different ways. I don't know if there are any usability studies out there. Some people have that the map setup kind of like all the different versions linked. Others have a redirect, others just swap out the content dynamically, so that it's like you go to the home page It's automatically in your language, which is also nice. But I don't think from our point of view, we have any preference there.  

#### [0:38:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=2280) |  It's really more usability question. Maybe also

how many different language versions do you have? If you have 50 language versions, then maybe you want to let people pick. If you just have 2, maybe that's something that you can guess better. MIHAI: OK. So generally speaking, just treat Google bot as a normal user, and HREF lang should do the trick as long as it's set up correctly? JOHN MUELLER: Yep. MIHAI: Awesome.  

#### [0:38:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=2310) |  JOHN MUELLER: Cool. OK. DANNY: Can I

ask a question? JOHN MUELLER: Sure. DANNY: OK, great. JOHN MUELLER: Oh, I can't hear you. OLIVER: John, I've got a quick question for you. On the website, [INAUDIBLE]. JOHN MUELLER: Wait a second. I think Danny was trying to ask me question first. OLIVER: All right. JOHN MUELLER: Danny, we can't hear you.  

#### [0:39:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=2340) |  Oh no. Oh, man. We'll have to

get back to you, Danny. Oliver, you want to give it a try? OLIVER: Yeah On the website-- it's nice to meet you John. It's my pleasure. I have a website. I'm not getting any search traffic. But what I'm doing, I'm removing my website on Facebook, and social media, social [INAUDIBLE]..  

#### [0:39:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=2370) |  And basically, people usually steal and copy

my content on the blog. And thankfully, I'm getting links from that, because I usually place entire links on the blog. And people you know, I'm getting links from that. Is there any [INAUDIBLE] because of the user [INAUDIBLE] the same URL are all local Git luck so They're all local.  

![](https://i.ytimg.com/vi/TlocS5b_46o/maxres3.jpg)



#### [0:40:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=2400) |  So is there anything I need to

[INAUDIBLE] I need to be thankful that I'm getting links. JOHN MUELLER: I think in general, if you're getting links from your content, that's kind of OK. The thing I would kind of keep in mind is that if these are say, other blogs that are just copying your content, and that's because you have a link there, then probably that's not a really valuable link.  

#### [0:40:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=2430) |  So it's not going to be something

that will be bad for your website, but I don't think it's something that our algorithms would say, oh, this is a fantastic site, and it's linking to your content, therefore your content must be fantastic. It's more like, oh, this is a pretty bad website and it's linking to your content. It doesn't really tell us that much. It's like, we see the link, but it's not going to be kind of magical SEO power kind of link.  

#### [0:41:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=2460) |  OLIVER: Most of his links and most

of his pages aren't indexed at all. I mean, if I searched the URL, it won't show up at all. JOHN MUELLER: OK. Yeah. That's again, I guess a sign that we don't see them as being that useful. I mean, from my point of view, I think this is fine to get started like this, and to kind of build up and build a user base that if you're creating content that other people find  

#### [0:41:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=2490) |  useful enough to copy, then that's kind

of like a good first step. And then to kind of build up from there, and kind of say well, first they'll have like, random people who kind of link to me because I think it's OK content and they copy it. And then as I grow, more people will recognize that my content is really good. And then I'll start gaining more really stronger, better links as well. OLIVER: Thank you. DANNY: Is that any better?  

#### [0:42:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=2520) |  Can you hear me now? JOHN MUELLER:

Yes. DANNY: Perfect. OK, great. Thanks. I'll keep it brief. So to the extent an image can have a different Alt tag based on whether it's on page A or page B, right I mean, what image can mean different things in different contexts. So to the extent that you can assign it a different Alt tag based on what page it's on, here's my question.  

#### [0:42:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=2550) |  What an image is used as a

link, should the Alt tag of the image be about the page that the image resides on, or should the Alt tag be about the destination page? So, in that page that's wrapped in A tag, right, and the A tags point to some destination page.  

#### [0:43:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=2580) |  So the image resides on page A,

but it's pointing to page B. And page A is about something. And page B is about something a little different. And the Alt tag-- if you asked me to write an Alt tag, I could write different Alt tags for page A versus page B. So does Google base Alt tag-- should it be about page it A or should it be about page B? JOHN MUELLER: It should be about the image. So theoretically, you could see Alt attribute  

#### [0:43:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=2610) |  as something that's associated with the image

in the sense that it should be describing the image. And that's kind of primarily how we use that for image search. If you're talking about an image that's essentially a navigational element on a page, then maybe having an Alt tag or an Alt attribute that matches watch what the image is about-- it's like it's a Next button for example, or it's Add to Cart button-- that kind of thing, then that also makes sense.  

#### [0:44:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=2640) |  We do take the Alt attribute into

account as a part of the anchor for that link. So that does play a little bit of a role there. But I would primarily see this as something that helps with the usability for images like that, if you're using them as navigational elements, and less as something that you're kind of like, passing anchor text value to the next page. If you're worried more about the anchor text,  

#### [0:44:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=2670) |  then I would just use a normal

text anchor text for that, and maybe also have an image next to it or on top of it or something like that. But usually, I will just use the Alt attribute as a description of the image so that those who are using screen readers for example, can still use your website normally. DANNY: OK. Because I mean, what my sense tells me that it should be about the destination page,  

#### [0:45:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=2700) |  because it's wraps and-- the kind of

images I'm talking about are not kind of the boilerplate graphical images. They're more substantial contextual images that tell something about the page and are used to optimize the on-site elements of the page so that if you were to ask what this page is about and you're trying to build a cohesive theme,  

#### [0:45:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=2730) |  you'd want to Alt tag of that

image to match the theme of the entire page so that you're telling the crawler and users what this page is about. But at the same time, my thinking goes well, it's wrapped it in A tag. And in A tag you always write what the destination page is about to explain to the user that this A tag is going to take you here. So should that image that's wrapped in A tag also have the same characteristics in that it should  

#### [0:46:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=2760) |  be about the destination page? JOHN MUELLER:

I think it really depends on what you're trying to do there. I'm not completely sure I understand your particular use case there. So it sounds like it's not like an Add to Cart button, and also it's not like, a giant image that you want to have indexed in image search. It's something in between where-- DANNY: I mean, the simplest thing that comes to mind is maybe lie a product image.  

#### [0:46:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=2790) |  And maybe in the category page, that

product image you'd want to optimize that image to do to be consistent with the category of those products. But that product image is a link that points to the product page. So should that product image on the category page be optimized for the category or should it be optimized for that product that it's pointing to? JOHN MUELLER: I think you could argue both directions.  

#### [0:47:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=2820) |  Because what happens from a technical point

of view, when we see that kind of a setup, essentially, we pull out the Alt attribute and see that as a part of the page that is linking. And so it's kind of like this text is seen as a part of the category page. And we also pull that out as an anchor for the page that it's linking to. So it's seen as both a part of the category page  

#### [0:47:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=2850) |  as well as kind of descriptive around

the product page that it's linking to. So it's not like a clear-- like, it should only be about the product page. And it's also not clear it should only be about the category page where that kind of image is on. DANNY: Right. I mean, my goal is to increase the trust and an authenticity of that page. So I don't want to give conflicting inconsistent  

#### [0:48:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=2880) |  signals to the crawler where the trust

in the website is lost because there is inconsistencies, and the crawlers says well, I can't trust anything that this website is telling me, because here, it's the same image is pointing using this Alt tag but it's not about the page it's sitting on. But OK. Just hearing you say that there's no clear answer, kind of gives me a little piece. JOHN MUELLER: OK, good. DANNY: Thank you. JOHN MUELLER: I wish there were more questions that had clearer answers.  

#### [0:48:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=2910) |  But sometimes they just don't. DANNY: OK,

thanks. JOHN MUELLER: Sure. [INTERPOSING VOICES] CHRIS: Does he want to go first? NIKOLA: Chris, you're first. CHRIS: Oh, fantastic. Thanks. So currently, one of the websites I'm working on is having issues showing up in the Google search index. When I went to Google Search Console, it says that URL is not on Google. The reason for it is it's a page with a redirect.  

#### [0:49:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=2940) |  However, when I went to figure out

where this redirect is or what it's redirecting from, it saying none is detected, and that the URL might be from-- might be known from other sources that are currently not reported. So I'm trying to figure out-- at this point I've asked around a lot what steps I should take to figure out what to do about that. JOHN MUELLER: Probably easiest if you can just  

#### [0:49:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=2970) |  drop the URL in the chat here.

CHRIS: All right. I can do that. JOHN MUELLER: Then-- then I can take a quick look at that. CHRIS: Cool. JOHN MUELLER: Sometimes these are a bit tricky to figure out, especially when there's like, JavaScript elements involved. Then it's really hard to figure out what's happening. So it's-- you're saying it's not being index at all or-- CHRIS: It'll come up if you specifically search for the link.  

#### [0:50:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=3000) |  But it will not come up for

the keyword that I have it registered under, even though when I was doing-- when I reviewed the keyword-- I'm like, number two in my local area for this keyword. JOHN MUELLER: OK, OK. I think that's trickier, because then it is indexed, and it's more a matter of ranking. But I can definitely take a quick look at that. Cool. OK. We have a few minutes left if anyone wants to drop in  

#### [0:50:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=3030) |  with a last question. NIKOLA: Yes, John.

Hi. How are you? JOHN MUELLER: Hi. NIKOLA: So John, I have one related question about redirecting canonicals. Is it a problem for where else with the trailing slash in canonical text or [INAUDIBLE] text but they redirect to the word and we don't [INAUDIBLE]?? JOHN MUELLER: That's usually fine.  

#### [0:51:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=3060) |  I think you have the situation that

it's kind of conflicting information that you're giving us. So it's unclear exactly who will win like, with trailing slash or without. So I would try to be as consistent as possible and pick one or the other. NIKOLA: OK, thanks. It's one more quick question. Is there any difference in the number of search result when we get FAQs result compare with search result without FAQ result? And the most difficult result you  

#### [0:51:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=3090) |  search, we see no more than 5

[INAUDIBLE] results. And total [INAUDIBLE] normally we are seeing 10 results [INAUDIBLE]. JOHN MUELLER: I have no idea. I could imagine maybe they have something, but I don't know. I don't think it's like, defined. NIKOLA: OK, thank you so, John. JOHN MUELLER: Sure. OMAR: Can I ask a quick question before we take off? This is a AMP stories question. We're trying to build a pilot for one of our magazines.  

#### [0:52:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=3120) |  And I'm trying to figure out the

best way for us to place this pages for Google to find them. And I'm having a hard time finding any information on that. Should we be building a site map a landing page for them? I just haven't seen many examples out there other than the big news organizations. JOHN MUELLER: I think in general, you'd want to link these like normal pages within your website.  

#### [0:52:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=3150) |  So we would see them as normal

pages. I think the tricky part is sometimes there is not a lot of content on these pages. So it's hard for us to rank them. But essentially, they're normal HTML pages, so you can put them on the site map, you can link to them internally, anything that you would do with normal HTML pages. OMAR: Yeah, I think the biggest problem that I'm having is that I am having a really hard time finding any examples out there as well. So I don't know if it hasn't been completely ruled out, or it's-- what's going on.  

#### [0:53:00](https://www.youtube.com/watch?v=TlocS5b_46o&t=3180) |  JOHN MUELLER: I think it's just really

new. So it's something where people are experimenting with it. I think the WordPress AMP plug-in has some experimental features around it as well. So I expect over time, more and more people will start using them. Cool. OK, I need to take off. It looks like there's still like, more stuff to be done. If you want, feel free to drop things into the other Hangout in YouTube,  

#### [0:53:30](https://www.youtube.com/watch?v=TlocS5b_46o&t=3210) |  or also feel free to post on

Twitter or post in the Webmaster Help Forum. There are lots of really smart folks there as well. All right. Thank you all for dropping in. And I hope to see you all again one of the next times. NIKOLA: Thanks, John. Bye. JOHN MUELLER: Bye, everyone.  