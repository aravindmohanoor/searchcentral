[![English Google Webmaster Central office-hours from April 9, 2020](https://i.ytimg.com/vi/Ak7r3oS1g4Q/maxresdefault.jpg)](https://www.youtube.com/watch?v=Ak7r3oS1g4Q)

## English Google Webmaster Central office-hours from April 9, 2020

This is a recording of the Google Webmaster Central office-hours hangout from April 9, 2020. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Watch out for new sessions, and add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



Feel free to join us - we welcome webmasters of all levels!



Subscribe to Google Search Central → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=0) |  JOHN MUELLER: All right. Hi, everyone. Welcome

to this Google Webmaster Central Office Hours Hangout. My name is John Mueller. I am a webmaster trends analyst here at Google in Switzerland. And part of what we do are these Office Hour Hangouts, where people can join in and ask their questions all around web search. There were a bunch of questions that were submitted already-- not a ton, but a few. But if any of you want to get started  

#### [0:00:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=30) |  with a question of your own, you're

welcome to jump in right away. BERNT JOHANSSON: I can actually start off, if that's OK. JOHN MUELLER: Perfect. BERNT JOHANSSON: Yeah. I have a question regarding some weird Googlebot activity that I seem to not be the only one who has experienced this. Sort of late March, some of our sites got 20 to 30 times more bot activity, almost to the extent  

#### [0:01:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=60) |  we had to go in and set

a limit, limit Googlebot for a while, because it was hammering our servers so hard. Any input on what was going on, if it's something that shouldn't have happened, or-- JOHN MUELLER: I don't know. Someone else mentioned this, I think, with regards to early April, so kind of same period, I guess. I took a quick look at their setup,  

#### [0:01:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=90) |  and the general bigger picture view. And

overall, it's not that Googlebot is crawling a lot more. So I think what is happening is just, on some sites, we happen to find a lot of URLs, and we started crawling those more. And on other sites, we're just crawling normally. So as far as I know, I don't think anything really changed in the setup that we use there. So even in the case of the other sites  

#### [0:02:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=120) |  that I looked into a little bit

more, what was happening there is that for some reason, we were running into some, I think some forms on the site, which we were submitting, which Googlebot sometimes does, and that ended up creating a gigantic mess of URL parameters. So we found millions of new URLs, and we thought, well, maybe we should check these URLs out and crawl them to see what comes up.  

#### [0:02:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=150) |  And that led to us kind of

crawling a ton of URLs, because from our point of view, it seemed that the server was able to handle the load. So we just decided to crawl a lot more there. Usually-- BERNT JOHANSSON: We didn't have any problems that it couldn't handle it. But basically, it's an automated setup where more servers are added into the cluster on need. So all of a sudden, the price went up terribly, because my suspicion was that you started  

#### [0:03:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=180) |  following the no-follow links. This is an

e-commerce site with tons of filters that have been no-followed forever and maybe you started following those and finding a lot of new interesting parameter URLs that way. JOHN MUELLER: I don't think that would be that visible. So it feels like, purely from the no-follow point of view, I don't think that would be happening. From the URLs that we're being crawled,  

#### [0:03:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=210) |  would those match the ones that you

tend to link like that? Or was it hard to check in the logs? BERNT JOHANSSON: Yeah, I actually don't have access to the logs, unfortunately. So I can't say for sure. JOHN MUELLER: OK. If you can send me a link to your site, I'm happy to take a look afterwards and see if there is something weird happening with those parameter URLs or if this is just Googlebot being super curious. BERNT JOHANSSON: All right. Thanks.  

#### [0:04:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=240) |  JOHN MUELLER: Sure. NEERAJ PANDEY: Yeah. Tell

me, tell me. I'm listening to you. JOHN MUELLER: All right. Any other questions before we get started? NEERAJ PANDEY: Mm-hmm. Mm. JOHN MUELLER: Sounds like someone's on the phone somewhere else. OK. Otherwise I'll just jump in through some of the questions that were submitted. And you're all welcome to kind of jump  

#### [0:04:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=270) |  in in between if there's something you

want to add, if you have a related question that you'd like to go through. Let's see. "Recently, in January, Google released product features in the US search results and also opened up the merchant account for unpaid users, as well. Is there any advantage for non-US businesses that SEOs can take advantage of?" So I don't know all of the details around the product shopping side.  

#### [0:05:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=300) |  My understanding is that the Merchant Center

is something that you can use regardless of whether you're using kind of the paid part of product search or not. So that might be something to check out. I don't know what the future plans are, in this regard. Usually what happens when we launch something in the US first, it's more to kind of get a feel for how things are working,  

#### [0:05:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=330) |  and then over time we end up

expanding that to other regions, other countries, other languages. I don't know if, particularly with product search, there might be legal or policy reasons involved that make this a little bit trickier or not. With some search features, that's the case. With other search features, it's more of a practical nature that we kind of need to test in a small scale first, before we open things up for everyone. So from just purely from my point of view with regards  

#### [0:06:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=360) |  to search features like this that are

currently US-only or English-only, my recommendation would be to take a look at them and think about how they might make sense for your site, even if you're not in the US. And if you can implement something that takes advantage of features like that, then you'll be ready when things open up a little bit more. I don't think we can ever really promise ahead of time when we open up which features in which regions or which languages.  

#### [0:06:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=390) |  But in general, our plan is to

take features and have them as broadly used as possible. "I was wondering if there's any best practice for URL structure of AMP pages. If you use a subdomain or a folder in upper level, you can have better possibility for analyzing on different tools. But I was wondering if there is any benefit for Google if you put your AMP pages under the root domain instead of a subdomain or parameters."  

#### [0:07:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=420) |  So from Google's point of view, I

think the only criteria that is critical for AMP pages is that it has to be on the same domain. So if you have it in a subdomain or a subdirectory, all of that is perfectly fine. In general, with these kind of related pages, I would recommend doing them in a way that works best for you, so something where it's easy for you to track, it's easy for you  

#### [0:07:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=450) |  to monitor, it's easy for you to

maintain that setup. So if it works well for your CMS, for example, if it works well for your server setup, then that's a good choice. I wouldn't worry about kind of like, is there any kind of Google tweak that makes a big difference with regards to these alternate URLs. The other thing I would watch out for with these alternate URLs is that you don't change the patterns too often.  

#### [0:08:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=480) |  So ideally, if you pick something like

a subdirectory or a subdomain, then try to keep that for as long as you can. It's not quite the same as if you change your primary URLs with regards to search, but anytime you change URLs in general, then we kind of have to re-process that. And if you are changing the alternative rules that are associated with every page on your site, then that means we have to re-process a lot of URLs to kind of understand that new setup.  

#### [0:08:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=510) |  So pick subdomain or subdirectory or parameters

if you want, whatever works best for you, and try to keep that setup, ideally for the long run. "I run a site about smartphone photography. Occasionally-- like once every three months-- I write a guest post on another topically related site. These guest posts are about topics  

#### [0:09:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=540) |  that I don't cover on my own

website. And these guest posts contain a link to my website in the end. At the bottom of the home page of my website, I have a section named "In The Media" where I link back to these guest posts. Currently these are follow links. Does this harm my SEO? What's the best practice for linking back to guest posts in order to not harm SEO?" So in general, with guest posts, you're placing the link, essentially, on another site.  

#### [0:09:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=570) |  So in general, that would be considered

an unnatural link. So I would recommend using no-follow for that. So if you're using a guest post and you're linking back to your site, then use no-follow links for that. I think at the scale where you're doing this at the moment, where it's like, I don't know, once every couple of months, I don't think anyone from the web spam team would look at that and say, oh, this site is maliciously  

#### [0:10:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=600) |  abusing these guest post links and trying

to artificially increase their site's ranking. So I don't think that's something you urgently need to worry about. But in general, for guest posts, you should use no-follow links. With regards to linking back to that site to kind highlight where your content has been shown, you can do that however you want. So you can use no-follow links, if you want. But I think a normal followed link is also  

#### [0:10:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=630) |  perfectly fine for that. Since you're essentially

showing kind of where all of your content is being published in, that's pretty cool. With regards to SEO, I think at the scale where you're doing it, you probably wouldn't see any advantage or disadvantage. With regards to building a bigger audience for your website, that might be a good thing to kind of talk about related topics on other websites and maybe interest some users into visiting your site,  

#### [0:11:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=660) |  as well. So from my point of

view, that sounds kind of cool. But purely from an SEO point of view, I don't think you're doing kind of a lot in positive or negative direction there. "We're running an online shop. Does it make sense to have long descriptions on the product pages? Or is it a problem to have similar content on the product pages? We're selling products in different thicknesses  

#### [0:11:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=690) |  for these, and we're using the canonical

tag. We also have products with similar characteristics. Should we focus on category pages or longer information about our products?" Ultimately, that's kind of up to you. So I think the general approach that you're using here is that you have a canonical to a preferred version of your product. And I think that's a good idea, because that makes that preferred version a little bit more  

#### [0:12:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=720) |  visible for your site overall. And that's

usually a good thing, because then when you look at your site, we understand which are kind of the primary pages to focus on. We can highlight things a little bit better in search. They can rank a little bit better. That's all good stuff. With regards to the descriptions, if the alternate versions of those products have the same or very similar description and a canonical link back to the primary version of the product,  

#### [0:12:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=750) |  then that doesn't matter at all, because

we will try to focus our indexing on the primary version of the product. So if you have an item that's available in different colors or different thicknesses, different sizes, and essentially it's all the same product, it just says different URLs, and you have a canonical to a preferred version there, we will focus our indexing on that preferred version. And essentially what you have on these alternate versions is less critical for us. In many cases, we won't even index that content at all.  

#### [0:13:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=780) |  So it doesn't matter for us if

that's duplicate or not. Even if we were to index those alternate versions of a product and they had a similar description or the same description, that wouldn't be a problem from our side of things. So in particular, it wouldn't be seen as spam, because this is just like the same product. It's just different URLs, different variations. It wouldn't be seen as low quality content.  

#### [0:13:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=810) |  It would just be seen as duplicate

descriptions. We would understand the pages are different, but some of the content on those pages are the same. And when someone searches for something generic that's in that kind of shared piece of content, then we'll try to find the best matching page within your website. That's essentially not something negative for your website. It just means we have all of these pages indexed. We know there's a lot of duplication across these pages.  

#### [0:14:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=840) |  And we'll try to show the right

one in the search results. In general, as a best practice, I think the setup that you have is great. So picking a canonical and saying, this is the version of the product that I really want to have indexed, that's kind of the optimal solution, because then we can focus on that primary version of the product. And with regards to amount of text and descriptions you have on these pages, that's totally up to you. I would make sure that you have things there  

![](https://i.ytimg.com/vi/Ak7r3oS1g4Q/maxres1.jpg)



#### [0:14:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=870) |  that make it easy for users to

find your content. So in particular, if you notice your users are using technical terminology to search for your products, then make sure you use those technical words. If they're using less technical terminology to search, then make sure you're covering that, as well. So kind make sure that your content matches what your users are looking for. And then it doesn't really matter how long  

#### [0:15:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=900) |  or how short that content is. "Can

replacing redirecting internal links by the final URL improve anything? What are the cons if we have a lot of hrefs on our site which are not the final URL?" So our general recommendation is to link to the destination URL. That's on the one hand a matter of speed for users, on the other hand, a little bit of an optimization  

#### [0:15:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=930) |  on our side for ease of crawling

and picking the right URL for indexing. So for users, obviously if you click on a link and it has to redirect, then that's kind of an extra server trip that has to take place. And it slows things down a little bit. And often it's something that's easy to fix. So from a user point of view, I would try to fix that. From a crawling point of view, we also have that redirect. If it's just one redirect when following a link,  

#### [0:16:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=960) |  then that's less of an issue. We

have a lot of time. We just try the next URL that's kind of in that redirect chain, and try that one. If it's a matter of a chain set of redirects, like you linking to one page and then it goes 5, 6, 7 hops until it finally reaches the destination page, then at some point Google will pause crawling and follow the next steps in the redirect chain maybe a day later.  

#### [0:16:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=990) |  So multiple steps I would definitely try

to avoid. A single step is less critical there for crawling. For indexing, what can happen here is that we might get confused with your URL you want to have indexed. It doesn't change anything for ranking, but it's more a matter of which of these URLs that you have on your website is the right one to show. So for example, if you're linking to one version of the URL and that URL redirects to a different URL, then we kind of  

#### [0:17:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1020) |  have two URLs that lead to the

same content. And then our systems have to make a decision and say, should I take the one that the website is pointing out and saying, like, this is the one that they want to have indexed? Or should I take the one that's kind of destination of the redirect chain and index that one? From a ranking point of view, it doesn't change anything. It's really just the URL that's shown in search. And there that's essentially also up to you. If you don't care which URL is shown in search, then that's all fine.  

#### [0:17:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1050) |  If you do care which one is

shown in search, then I would make sure that everything is as clear as possible that this is really the one that you want to have shown. "I launched a new website recently and got five to 10 impressions. However, no query data has been shown yet. I see the number on the graph, the pages, the countries, but no queries. Is this normal? Are queries blocked by the privacy protection policy?"  

#### [0:18:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1080) |  My guess is that it's just not

enough queries yet. So we do filter queries that are below a certain threshold. And I don't think that threshold is exactly defined. It might depend on various factors. It's also mentioned in the Help Center. And if you're talking about five to 10 impressions for a website, then probably that's still below that amount. I'm pretty sure that over time, as the number of impressions  

#### [0:18:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1110) |  for your website grows, then you'll start

to see more data there. So it's also something where once we kind of have a better picture of the website and understand how it fits in with regards to the bigger picture of the web, then we can show it appropriately in the search results. So sometimes it takes a bit of time to kind get the ball rolling. What I would generally recommend, though, is not just to take this as something like,  

#### [0:19:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1140) |  oh, I'll just wait a couple of

months and then it'll be better, but take this as a kind of a situation where it's similar to when you're opening a business in a new location where you need to do something to get the ball rolling yourself. So instead of just waiting for people to randomly search for your website and go to your website, maybe there is a way that you can promote your website amongst people who are interested in this topic already. Maybe it's a matter of doing some ads.  

#### [0:19:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1170) |  Maybe it's a matter of doing some

outreach to related sites that might be able to point at your site, as well. Essentially, like a normal business would do, you need to kind get the ball rolling. You shouldn't just wait for people to come to your website and say, oh, look, I found this new website. So that's kind of my recommendation there. I think with a small number of impressions, it's a good start.  

#### [0:20:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1200) |  But if you just wait for things

to grow, then it's going to take a while for all of that to pick up. "Does a title in a href contribute anything to SEO?" So I took a quick look at some of the things around the title attribute for links. And accessibility is a really big thing here. However, I am not an expert on accessibility. So my recommendation there would be  

#### [0:20:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1230) |  to check with someone who has more

of a background in accessibility to get their input on this. From an SEO point of view, I don't think it's something that's super critical. We pick up information about links from the anchor tags, from the context of the link. So we get a lot of information there already. It's not that you also need to just stuff keywords into title attributes. So my recommendation would be, instead of trying to see this ultimately accessibility feature as an SEO  

#### [0:21:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1260) |  element that you can just fill with

content, try to find ways to use accessibility features in the way that they're meant to be used. And for that, I'd recommend just checking in with the accessibility experts, instead. "In the first phase, we're planning to add a last mod part of our-- to part of our site map.  

#### [0:21:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1290) |  Basically, URLs which are newly added are

marked as indexed again after temporary no index. How will Google treat the remaining 80% of the site map URLs, which have no last mod tag. Can it cause any negative effects? Later we'll implement the last mod on all URLs, but it might take some time. We have over 2 million URLs on our site map." So the last mod date is the last modification date. You can add that to URLs in a sitemap file.  

#### [0:22:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1320) |  It tells us that this is the

date and the time when you last modified a page, which in turn gives us a little bit of a hint and says, well, maybe we should check this page out if we haven't seen it since it was last modified. It doesn't force us to go crawl those pages. But it does help us to figure out which ones we should prioritize as kind of a next step. So in general, if you're using a sitemap file, I'd strongly recommend using the last modification date.  

#### [0:22:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1350) |  If you have the last modification date

for part of your URLs and not all of them, that's perfectly fine, too. We store, essentially, the sitemap's data on a per-URL basis. So it doesn't matter if some URLs have extra metadata and some URLs don't. An example here would also be if you have images that you have in the sitemap file for some URLs and you don't have them in others, or videos and you include them the sitemap file independently.  

#### [0:23:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1380) |  All of those are variations that you

can do. It doesn't make the other URLs on your sitemap file look worse. It does help us to figure out which ones to crawl a little bit faster. So essentially, that's a good thing. "Is it correct that the site will not appear in search console linking site section if the site redirects to the 404 page on our own site?"  

#### [0:23:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1410) |  So I think you're just linking to

the 404 page. So some external site is linking to a URL that returns 404. "Will we see linking sites and search console linking sites report? I suspect we won't, but the verification would be great." So my understanding is, we would drop these links completely. And if we drop them completely, then they would not be listed in Search Console.  

#### [0:24:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1440) |  So from that point of view, from

just purely theoretical situation like this, we would not be listing that in Search Console if an external site is linking to a page that is 404 on our own website. The thing where this sometimes could be visible is if a page goes 404, if it wasn't 404 before, but now it's 404, then it takes a bit  

#### [0:24:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1470) |  of time for all of the linking

systems that track the data in Search Console to update the data there. So it's certainly possible that you see links in Search Console that lead to pages which are currently 404. Over time, those will drop out of the report. But at least in kind of the immediate term, it's very possible that they'll continue to be listed there until they've been reprocessed, until search console is  

#### [0:25:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1500) |  able to figure out, oh, it's time

to remove these and to move on. Since this kind of, I think, situation where someone is linking to your website and then accidentally or for whatever reason you happened to remove a URL on your website-- happens from time to time. I don't know if Search Console would be that useful to kind of track this and to highlight it to you.  

#### [0:25:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1530) |  It's possible that external tools that keep

track of the links on the web would be better suited for that. But it feels like almost a feature request that I should be passing on to the Search Console team to see if we can create a report of people linking to pages that are now 404 on your website where you might be able to either restore those pages or maybe redirect them to a current version of the page, instead, so that those links continue to work.  

#### [0:26:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1560) |  I think for most websites, in the

bigger picture, it doesn't really change that much. But I realize sometimes people like to optimize for small things, as well. "Recently I set up one WordPress fully AMP base URL. Earlier while testing the site with a demo account, with discourage Search Engine from indexing this site?  

#### [0:26:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1590) |  That time Google crawled the URL and

now it's showing as currently not indexed and soft 404 error. It's also 100% AMP-based website, and the 90 page index, but enhancements. Check AMP page is only one." OK. I think these are multiple questions. So let me try to split them out. I think the general--  

#### [0:27:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1620) |  like, the starting point is you have

a test site where you have some URLs that were marked as no-index and Google crawled them and found them to be no-index, and flags on those currently not indexed and their soft 404. In theory, that's the way it should be working. If we find a URL that's no-indexed and we try to index the page but we realize we can't, then we will flag that to you in Search Console. Or we'll try to do that as much as we can.  

#### [0:27:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1650) |  If you change that URL to be

indexable, then the next time we reprocess that page and see the new content, are able to re-index that page, we'll pick that up. And we'll be able to index it again. So generally speaking, there is nothing you need to do here. If these are individual pages, you could use the inspect URL and then submit to indexing tool to get those back into the system a little bit faster. But in general, for any kind of reasonably sized website,  

#### [0:28:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1680) |  that's not something that you'd need to

do. Once we see that the no-index is gone, we'll just re-process that. With regards to the kind of AMP site and in the AMP report you're only seeing a smaller number of URLs than you have actually indexed, that's also normal. The aggregate reports in Search Console, which includes the AMP  

#### [0:28:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1710) |  report, they're based on a sample of

the URLs from your website. So in index coverage, we'll try to show it as comprehensively as possible. But the structured data reports and the AMP report, mobile friendliness and speed reports, I think these are all based on a sample of your website, so not the full set of your URLs. So usually the way you would work with this is to use the index coverage to track what is actually indexed  

![](https://i.ytimg.com/vi/Ak7r3oS1g4Q/maxres2.jpg)



#### [0:29:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1740) |  and to use these aggregate reports as

a way of recognizing if there are any general problems that you need to resolve. And if you're looking at the aggregate reports and they're saying, everything is great and 10 out of your 100 URLs were tested and they're all OK, then usually you can assume that the rest of your URLs are probably in a similar state and also OK. On the other hand, if you go to the aggregate report  

#### [0:29:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1770) |  and see half of your pages are

bad, then that's a sign that maybe a lot of your pages are bad. Or similarly, if you go there and you see a trend in kind of like more pages are being bad or fewer pages are bad, then that's also a sign that either something broke, maybe, or something got fixed. Let's see. Next question there is for the AMP cache. "I use the AMP URL API but didn't give any effect in Search Console.  

#### [0:30:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1800) |  Does that process take time?" So the

AMP cache is something that happens automatically. In particular, with AMP pages, they can be cached because of the way that they're set up. And they can be served from the search results directly. And that's something that happens automatically when someone searches for a page and we see that it's an AMP page and it's a valid AMP page and we can pre-cache it, then we will pre-cache it.  

#### [0:30:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1830) |  There is no need to use the

AMP API for that. The AMP API is probably more for situations where you have a really large website and you need to refresh a lot of URLs in the AMP cache, then that's kind of a useful use of the AMP cache, or AMP. I don't know what it was called. The AMP API. But if you're talking about a small website  

#### [0:31:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1860) |  and you're being shown in search in

a reasonable way, then there is no need to use the AMP API at all. "Years ago you suggested infinite scrolling with pagination. And in previous Hangouts, you told us that Google creates a large viewport when a page has infinite scrolling. So my question is, if we have infinite scrolling with pagination and marked our paginated pages as no-index, how will Google read or index this.  

#### [0:31:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1890) |  Will Google index page 1 on the

basis of page 1 content only, or will it also consider products which come into the giant viewport, or will Google not create a giant viewport for such pages once it understands that these paginated pages are generally no-indexed?" Wow, this is kind of a complicated setup. I think in general, what I would watch out for is that you're not accidentally  

#### [0:32:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1920) |  no-indexing something that you want to have

indexed. So in particular, with kind of this infinite scrolling setup, we would try to render the page in a large viewport. And with the large viewport, we will do that expansion once. We will try to get the content that is shown for that large viewport. And we'll render that page and use that for indexing. So if by using a large viewport, your page adds by JavaScript  

#### [0:32:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1950) |  a no-index tag to that page, then

we would consider that whole page to be no-indexed. It's not that we would say, well, initially it didn't have a no-index and now it does, so we'll take the initial content and index that. It's if, after rendering, your page has a no index on it, we will drop that page from our index. So that's kind of the tricky part to watch out for. On the other hand, if by clicking on a link and kind of following a new URL,  

#### [0:33:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=1980) |  the new URL has no index and

just that new URL will be dropped from your index. But if through rendering a page you add a no index to a page, then that's a no index on the page, regardless of how that came there. BERNT JOHANSSON: Can I chime in with a follow up on that? JOHN MUELLER: Sure. BERNT JOHANSSON: So what you're saying is basically that if I have an infinite scroll page-- let's assume it's a category page on an e-commerce website--  

#### [0:33:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2010) |  maybe I show 20 products. And then

when you scroll at the bottom of that, I load another 20. And then that continues until they're all shown. Are you saying that Googlebot, when crawling or trying to index this, will do that once, will basically scroll down once and say, oh, something more loaded. Load that and then-- but not twice. JOHN MUELLER: Yeah. So I don't think we trigger on scrolling, but rather, we try to load it in a large viewport. So in Chrome, what you can do is with the--  

#### [0:34:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2040) |  what is it?-- what's it called? The

inspect feature-- you can specify a different viewport. So you could specify something like 9,000 pixels high viewport and load the page like that. And essentially, what is loaded for viewport like that would be what we would try to index. I don't know what the exact size is. I think the size also probably changes over time. But essentially, it's a long viewport. And if your page is set up in a way that it loads kind of the next piece of content once,  

#### [0:34:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2070) |  then we would have that next piece

of content. If it's set up in a way that it understands the size of the viewport and loads as many as it needs for that viewport, then we would index that. BERNT JOHANSSON: That's super interesting, because some sites with-- let's say it's not infinite scroll, but what they do is they'll add-- they'll do that-- the first time you scroll, they'll load another 20. But then they'll show a button they  

#### [0:35:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2100) |  have to click to load, which means

that wouldn't load if the viewport was bigger. So thanks. That was super interesting. JOHN MUELLER: OK. "Our page is crawled often by the mobile crawler. How is the importance of the desktop page? The page is crawled by the mobile crawler. Are there main differences in analyzing pages by different crawlers? What are the main factors we should worry about when creating our mobile site?"  

#### [0:35:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2130) |  So by mobile crawler, I assume you

mean that your website is in the mobile-first indexing setup. And what happens with mobile-first indexing is we essentially only index the version that we see with the smartphone Googlebot. We do check the desktop version from time to time. But that's mostly just to make sure that things are linked up properly. If you have alternate URLs set up that we understand, these are linked accordingly.  

#### [0:36:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2160) |  But for indexing, we would only use

the mobile version of the site. In practice, I think this difference is less and less visible, because as people move to responsive web design setups, it is less the case that you have completely different content on desktop and mobile, but more it's just, like, positioned slightly differently? So that's I think less of an issue overall with regards to the amount of content there.  

#### [0:36:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2190) |  But in kind of like with mobile-first

indexing, if there's anything that's only on your desktop pages, then we would not see that at all for the mobile index. And we would not index that. And that would also mean that regardless of users using desktop or mobile to search on Google, we would essentially only show the version that we see with the mobile Googlebot. So if you're just changing the design on these pages,  

#### [0:37:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2220) |  that doesn't change anything for us. If

you're really reducing the amount of content on mobile, then that means we would only index that reduced amount of content. I think overall mobile sites are more and more going in the direction that they're almost providing more functionality nowadays than kind of the old school desktop sites. And with that, the responsive design kind of keeps things together.  

#### [0:37:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2250) |  But I think, at least in the

beginning, it was a bit tricky that sometimes mobile sites were just slimmed down or simplified versions of a desktop site, which would make it harder for mobile-first indexing. With mobile-first indexing, in general, I think we have a significant part of the web moved over to mobile-first indexing already. We plan to shift everything over towards the end of the year. I think we had the date in September.  

#### [0:38:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2280) |  I don't know if that date will

shift with all of the coronavirus stuff happening, as well. But we still see sites kind of preparing for mobile-first indexing. There are not a ton of sites left over. So maybe that'll still make sense. "I have a website and I lost traffic. It's a ringtones download website with 60,000 ringtones on it. On the 17th of December, we lost our ranking. And if I search my site with a site colon query,  

#### [0:38:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2310) |  I only see seven pages available. I

have not received any manual action. Is it an algorithmic penalty in which Google removes web pages? What can I do to recover my traffic." So in general, a site query is not representative of all of the pages that we have indexed. So it's a good way to get a rough view of what we have indexed, but it's not the comprehensive list. It's not meant to be like that.  

#### [0:39:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2340) |  For more information on how or what

we have indexed, I would use Search Console and the Index Coverage Report there. That gives you a better look at the pages that are actually indexed. With regards to losing traffic, I realize that's sometimes hard. What I would do in a case like this is maybe post in the Webmaster Health Forum to get some input from peers who might have seen similar situations on other or kind of related websites.  

#### [0:39:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2370) |  In general, I think with a website

that's focused on ringtones, it'll be a little bit tricky because our algorithms really do try to look out for unique, compelling, high quality content. And if your whole website is built up on essentially providing ringtones that are the same as everywhere else, then I don't know if our algorithms would  

#### [0:40:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2400) |  say this is a really important website

that we need to focus on and highlight more in search. So with that in mind, if you're focused on this small amount of content that is the same as everyone else, then I would try to find ways to significantly differentiate yourselves, to really make it clear that what you have on your website is significantly different than all of those other millions of ringtone websites that have kind of the same content.  

#### [0:40:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2430) |  Maybe there is a way to do

that with regards to the content that you provide. Maybe there is a way to do that with the functionality that you provide. But you really need to make sure that what you have on your site is really significantly different enough that our algorithms will say, well, this is what we need to index instead of all of these others that just have a list of ringtones on the website. So that's probably not going to be that easy to make  

#### [0:41:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2460) |  that kind of a shift. But that's

generally the direction I would head. And that's the same recommendation I would have for any kind of website that offers essentially the same thing as lots of other websites do. You really need to make sure that what you're providing is unique and compelling and high quality so that our systems, and users in general, will say, I want to go to this particular website,  

#### [0:41:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2490) |  because they offer me something that is

unique on the web. And I don't just want to go to any random other website. "Can it help CEO by reducing web pages by marking our product pages no index, which have almost zero impressions in the last 16 months? Currently 10% to 15% pages are like this and they're just dead weight on our site.  

#### [0:42:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2520) |  I was wondering that after no indexing

such pages we will submit fewer pages to Google in the site map and Google could focus on the rest of our site better?" I don't know. It's something that I know some sites do. I think it's not a totally unreasonable approach to say that the pages that nobody cares about I essentially remove from my website.  

#### [0:42:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2550) |  But it's something where I wouldn't just

blindly do this. So if you're just blindly focusing on the number of impressions that you have for individual products and you drop them from search, then it's very easy to drop things that are actually useful, but they're just not that common. It might be that maybe it's an archive version of a product or a page, where people after a certain period of time, they need to go back there to find instructions for repairing this product.  

#### [0:43:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2580) |  Or they want to look up historical

information about a specific item. And that's not something that happens every day. So if you just purely look at the number of impressions, then it's easy to accidentally include a lot of things that are actually still useful. For the web, they're just not that commonly used. On the other hand, looking at the number of impressions and the types of pages that you have on your website, that can give you a little bit of a better  

#### [0:43:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2610) |  understanding which types of pages are more

important for users. And that can either guide you to saying, well, this type of page is something that maybe I don't want to provide anymore. Or perhaps it can guide you into saying, well, this type of page is currently not seen as being that useful. Maybe if I significantly improved it, it would be different. And that's also something where you don't just go and blindly look at the number of impressions, but rather, you have to make a judgment call and look at that  

#### [0:44:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2640) |  and see, does it make sense to

kind of remove this? Does it make sense to improve it? And a lot of times, it does make sense to improve things on the web. With regards to just having fewer pages and those fewer pages then ranking higher, I don't see that happening so much. It can help for a very large website to reduce the number of pages that they provide, just purely from a technical point of view,  

#### [0:44:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2670) |  in that if we can crawl 1/10

of the pages on a website, then it's a lot easier for us to pick up those 1/10 of those pages a lot faster. And that can, in turn, help us to figure out, well, maybe these are the pages that are really important for the website. But if you're just dropping a handful of pages here and there, then I don't think it changes anything for crawling, and probably not much for the website in search  

#### [0:45:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2700) |  overall. Phew, we made it to the

bottom. Wow. That's a change. OK, let's see if there's anything new that got added. Let's see. OK. "Hosting a sitemap file for a domain on a subdomain, is that OK?" Yes. That's OK. "If it's OK, what steps would I need to take?" So essentially, you just need to let  

#### [0:45:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2730) |  us know that the second file is

on a different host. You can point at the sitemap file in the robots text file. That's the easiest way to do it. You can also use Search Console. If you have both of these verified in Search Console, you can submit those sitemap files there, and those would also count. BERNT JOHANSSON: Sorry for bugging in again with a new follow-up. JOHN MUELLER: Sure. BERNT JOHANSSON: I saw that question, so I didn't want to ask mine before you came to it. So basically, subdomains, sitemaps,  

#### [0:46:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2760) |  I got that covered, it seems, before.

But hosting sitemaps on third party domains-- like, a totally different domain-- is supposed to be-- you're supposed to be able to do it. I can see that it works, because I can see when we serve href blank information through those sitemaps, I can see how the international targeting report is saying, you got href links and they're all looking good. But I cannot see any coverage reports for sitemaps in Search Console.  

#### [0:46:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2790) |  Is that supposed to be like that,

or-- JOHN MUELLER: I think that's the case. But it's not that we don't use those sitemaps. It's just, in the UI and Search Console, they don't have a setup that you can combine the coverage report with a sitemap file that's hosted somewhere else. BERNT JOHANSSON: All right. Any plans on kind of adding that, you know? JOHN MUELLER: I don't know. It's the first time I really hear about this. But it's something that makes sense.  

#### [0:47:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2820) |  So maybe we should check with the

Search Console folks to see if there's a way to add that. [INTERPOSING VOICES] JOHN MUELLER: --UI point of view, it's probably tricky. BERNT JOHANSSON: Yeah, I sent you that domain I asked about previously. This is the same domain. So they have that set up. So if you want a sneak peak on that, you can do that, as well. I sent it in the chat here and also on Twitter for you. JOHN MUELLER: Perfect. OK. Sounds great. And the other question is, with regards to the 3D AR program for Google search,  

#### [0:47:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2850) |  I have nearly 1,000 products ready to

upload to our retailers. They can really use some help in this. I don't know what the current status is there. But if you can send me maybe a domain where some of these are hosted now, then I can pass that onto the team that's working on these kind of AR 3D integrations. I think that's really cool, cool stuff that they're doing there. But I understand they're kind of short on time.  

#### [0:48:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2880) |  So I don't know how quickly they'll

be able to do that. OK, cool. You posted it in a chat. Cool. OK. I could take a look at that. Cool. Yeah, I think we got through the questions, more or less. Is there anything else on any of yours minds that you'd like to talk about? BERNT JOHANSSON: I gave someone else a chance for a while,  

#### [0:48:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2910) |  so I'll drop in again. One thing

that we are seeing, at least we're kind of thinking that we're seeing, is that we have a couple of domains that we monitor. And they're improving quite a lot over the last few weeks-- like, tremendously-- both in terms of that search for their industry has increased because of this coronavirus, but also-- so that's one thing, more impressions, you get more pics if you rank. But we also see improvements in rankings.  

#### [0:49:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2940) |  And this is despite no changes going

on at all in terms of technical or content-wise, more or less. So we're kind of sort of thinking the changes in intent with searchers is also impacting how we rank, because we match that intent better than our competitors do. I can understand if you can't really tell me if that's the case, but-- JOHN MUELLER: I mean, it's really hard to say offhand.  

#### [0:49:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=2970) |  I don't think it's as simple as

just matching those two parts. But I do know that people are working on our algorithms to improve them, particularly with regards to queries, where they're seeing a lot more activity on with regard to the coronavirus and the medical situation in general. So my general feeling would be, it's not just purely based on changes in user behavior and intent,  

#### [0:50:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=3000) |  but maybe a mix of various things

kind of coming together. BERNT JOHANSSON: As it almost always is, I guess. JOHN MUELLER: Yeah. I think in particular, in the current situation, it is the case that we have more people working on improving the search results in general. And there are probably side effects from there, as well. BERNT JOHANSSON: All right. Thanks. JOHN MUELLER: Sure. KAIXI LUO: John, hi.  

#### [0:50:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=3030) |  I have a quick question regarding the

negative SEO. For example, we have basically spammers that link to us from hundreds-- I don't know, maybe thousands of domains. They do it slowly over time. And I regularly check and add them to the disavow file, but I don't know if these are having an effect on the site, because it's like--  

#### [0:51:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=3060) |  they spam a lot of links, like--

maybe one domain can link you 10,000 times. And there is, like, hundreds and thousands of domain. So in the end, you look at it and I think you even have more spam incoming links than actual real links. So I'm worried about that. I don't know if I should be worried. JOHN MUELLER: For most of these things,  

#### [0:51:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=3090) |  I think our systems get it right.

And there is nothing you need to do there. So from that point of view, I wouldn't really worry about this situation. If you're already adding them to disavow file, then you're kind of like making sure that Google's systems can't take them into account. But in general, a lot of these spammy domains, they just link to everything. And we've seen them for the longest time. And we're pretty good at recognizing  

#### [0:52:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=3120) |  these kind of spammy domains and just

ignore them. So you'll see them in the link reports in Search Console because we have seen their links there. But just because they're in the link reports in Search Console doesn't mean that they have any effect on your website. So that's something where, I don't know, we occasionally get people to point at things around negative SEO and say, like, Google needs to double check this, because I found this one case where it did have an effect.  

#### [0:52:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=3150) |  Therefore, it might have an effect overall.

But pretty much all of the negative SEO cases that I've sent to the web spam team to manually double check, they're working as intended, where from our side, we're ignoring the things we should be ignoring and treating things appropriately that we're not ignoring. So I would say for most websites out there, you probably don't need to use the disavow tool at all.  

#### [0:53:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=3180) |  And if you're worried about this and

you see some domains linking to you and it looks really spammy, then it's like, you're welcome to use the disavow tool and that has no negative effect. So it's not that if you're using the disavow tool, we think you're a spammer, that kind of thing, either. KAIXI LUO: Well, I started using it because it was the sheer amount of domains and links. And I was like, better to be sure, you know?  

#### [0:53:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=3210) |  JOHN MUELLER: Yeah. I totally understand that.

And it's something where Google has this magical black box where we ignore all of these spammy links. But as a site owner, you just want to be sure that everything is ignored that you don't want to have taken into account. And that's what this disavow links tool is for. KAIXI LUO: OK. Thank you very much. JOHN MUELLER: All right. More questions from any of you? Looks like there's also a bunch of back and forth  

#### [0:54:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=3240) |  in the chat, which I haven't had

a chance to go through. Anything we should cover? BERNT JOHANSSON: I think the page speed question on the extended viewport was particularly interesting in that chat. JOHN MUELLER: OK. Let me see.  

#### [0:54:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=3270) |  The page speed part. So when-- I'm

not quite sure how that going to affect the page speed. But in general, when it comes to speed and ranking, it's not the same as what we use for indexing. So that's sometimes a bit confusing. For indexing and crawling, we need to be able to access the resources as quickly as possible.  

#### [0:55:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=3300) |  And for rendering, we do the long

viewport thing. But when it comes to understanding the speed of a page for ranking purposes, we essentially look at the pages the way that a user would see them when they access them on their device. So for ranking, we use kind of theoretical lab tests where we do things like a page speed insights score and other scores. And we also use field data, which I believe is also shown in page speed insights now with kind of similar to the Chrome User  

#### [0:55:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=3330) |  Experience that are there, which is based

on what people have actually seen. So from a ranking point of view, we would base our speed factors on the normal viewports that people have when they view the pages, which is slightly different on desktop and mobile. But essentially, it is based on the viewport that people have. And for rendering, for indexing, we would use kind of this long, extended viewport  

#### [0:56:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=3360) |  with loading the content and trying to

make sure that everything is in there. So those are sometimes slightly different. BERNT JOHANSSON: That kind of sparks an interesting follow up question, as well, whereas-- so let's say that a website is showing all green lines in a Page Speed Report in Search Console from the Chrome User Experience Report. But in the lab test, they're terrible, which could be because, you know, they target a market where everyone has really modern cell phones on very high internet connections,  

#### [0:56:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=3390) |  so they load quite quickly. But on

the lab test, they load very poorly. Would you say, then, it's still important to try to improve the lab test, even though all our users are getting a great user experience? JOHN MUELLER: I think that's always something you have to kind of judge almost on your own. I think from purely a ranking point of view, probably that's OK. It's also a bit tricky with a lot of these kind of lab tests  

#### [0:57:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=3420) |  in that they test so many different

metrics. And it's hard to know which metrics you should really focus on there. And from our point of view, we try to get the overall picture. And we try to combine multiple of these metrics to understand what the overall view is of a web page. So if the field data is looking fantastic and some lab tests are kind of slow and others are kind of OK, then I wouldn't really worry about it.  

#### [0:57:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=3450) |  BERNT JOHANSSON: All right. Thanks. JOHN MUELLER:

Cool. OK. Lots of good questions today. Cool. Let's take a break here. It's been great having you all here. Thank you all for joining in. Thanks for all of the questions as well that were submitted and live. Always good to see. I think the next batch is lined up for next week on Tuesday and Friday  

#### [0:58:00](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=3480) |  again, so the usual times and dates.

Also another one in German lined up next week. In the meantime, I wish you all, I don't know, good Easter, if you're celebrating Easter, maybe a short break. I don't know if you can really go out and enjoy things, depending on where you are. But hopefully things are well. So wishing you all a great weekend, at least.  

#### [0:58:30](https://www.youtube.com/watch?v=Ak7r3oS1g4Q&t=3510) |  Looking forward to seeing you next time,

then. Bye, everyone. BERNT JOHANSSON: Thanks. Bye bye. KAIXI LUO: Bye, John.  