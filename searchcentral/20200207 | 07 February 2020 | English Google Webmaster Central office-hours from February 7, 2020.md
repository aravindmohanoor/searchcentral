[![English Google Webmaster Central office-hours from February 7, 2020](https://i.ytimg.com/vi/msq9mZgX6ZQ/maxresdefault.jpg)](https://www.youtube.com/watch?v=msq9mZgX6ZQ)

## English Google Webmaster Central office-hours from February 7, 2020

This is a recording of the Google Webmaster Central office-hours hangout from February 7, 2020. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Watch out for new sessions, and add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



Feel free to join us - we welcome webmasters of all levels!



Subscribe to Google Search Central → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=0) |  JOHN MUELLER: All right. Welcome, everyone, to

another Webmaster Central Office Hour Hangouts. My name is John Mueller. I'm a webmaster trends analyst here at Google in Switzerland. And part of what we do are these office hour Hangouts, where people can join in and ask any question related to their website and related to web search, I guess. A bunch of things were already submitted. But if any of you want to get started with the first question, jump on in now.  

#### [0:00:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=30) |  MARTIN: John? JOHN MUELLER: Sure, hi. MARTIN:

Hi, you may remember last German Hangout, where I mentioned the content change of my small website also having added article markup up on about 14 pages. But neither new keywords nor structured data have been noticed by Google until today, neither in Search nor in Search Console.  

#### [0:01:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=60) |  Indexation of the pages is now more

than 10 or 11 weeks ago. And I gave you two URLs to check-- the home page and an article page. Did you check them? Could you find anything? JOHN MUELLER: I don't remember. I need to double-check. I can double-check later on, if you want to stick around afterwards when we have a little bit more time.  

#### [0:01:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=90) |  Yes MARTIN: Yes. OK, I will stay.

JOHN MUELLER: OK. MARTIN: Thank you. JOHN MUELLER: Sure. All right. Any other questions before we jump into the submitted ones? MENASHE AVRAMOV: So you maybe can begin with mine. It's there in the comments. JOHN MUELLER: OK. Let's see.  

#### [0:02:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=120) |  I think yours is the second one

on the list. So I'll just start with the first one, so that I don't lose track where I was. OK. So the first one is a multilingual international website targeting a specific country with URL patterns for the home page like ksa.mywebsite.com/ar, which has the hreflang value of ar-sa. So I guess that would be Arabic for Arabia, I guess?  

#### [0:02:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=150) |  I don't know. I don't know my

country codes. OK. And another /en, which has an hreflang value of en-sa. Knowing that Arabic is the default language for my website, does it help my website to rank higher if I implement URL patterns without ar- prefix in the URL? So just ksa.mywebsite.com without the /ar?  

#### [0:03:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=180) |  No, it doesn't change anything. For hreflang,

we look at the specific URLs. And we essentially rank them as they are. So that's something where I try to keep it as clear as possible in your URL. So if you have different country or language versions, make it so that people can recognize that right away. And in general, I don't see any problem with just keeping it  

#### [0:03:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=210) |  with /ar and /en for the different

language versions. The country version, I think you already have set up as a subdomain, which is good because, for geotargetting, the country level patterns we try to look at clear either domain level, or subdomain level, or clear subdirectory level folders there. So that's something where you're using a subdomain, at least from the example URL there.  

#### [0:04:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=240) |  And that would be perfect. So from

that point of view, I don't think you need to remove the /ar. You can, if you want. But it wouldn't change anything research. Should we provide a list of domains that have been removed in our reconsideration request for the remaining ones? We received a manual penalty for thin content for many of our domains. And we killed a big portion of them. We improved quality on our high value sites. And we believe they meet Google's guidelines.  

#### [0:04:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=270) |  Yes, I think that generally makes sense.

So in particular, if you have a lot of websites that are under manual action and you delete a lot of those, and the process of deletion is your way of cleaning things up, then that's something I would mention. I don't think you need to list them all out individually. But you can say something like, oh, we had-- I don't know-- 100 domains with a manual action for thin content.  

#### [0:05:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=300) |  And we removed 90 of them, kind

of a rough order of magnitude so that the people who are looking at this to see if it was resolved, they recognize, oh, OK, you significantly took steps to clean that up. MENASHE AVRAMOV: And does it matter how we kill the sites-- noindex, server error, DNS error, or removal request? JOHN MUELLER: I would just do it in a way that is as clear as possible. So a server error, a DNS error is  

#### [0:05:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=330) |  something that's like, well, nobody knows if

this is a temporary thing or not. But if you really take down the site, if people when they check the URL they clearly notice, oh, this website is gone, that could be a 404 page, something like that. Just make it as clear as possible that this is not a temporary thing that you just switch it off and see if it goes through. But actually, like this is what you decided to do. MENASHE AVRAMOV: OK, thanks.  

#### [0:06:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=360) |  JOHN MUELLER: OK. The past three days,

we're facing big latency in the indexing API and a lot of 503 errors with the service as currently unavailable. Is the service down? I don't know. So I just this question earlier before the Hangout. And I'm not sure what the current status is. I'm not aware of any bigger issues there. So sometimes, what happens is that things just  

#### [0:06:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=390) |  get stuck for a little bit. But

I'll double-check with the team. And if there is an issue there, then we'll obviously try to get it resolved as quickly as possible. There are lots of schema or types of structured data. But only a few of them are listed in the Google Developers Help. Should we spend time implementing something like image objects? So I think image object is actually one of those that is mentioned in the documentation.  

#### [0:07:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=420) |  In particular, we use images as a

subelement of different other structured data elements. So I think it's, in particular, things like recipes, where you have images that you specify for that. My understanding is we'd use image object height. I'd need to double-check the documentation. But that's my understanding there. But going back to the more general question, should we use types of structured data that are not in the developer documentation?  

#### [0:07:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=450) |  So in practice, what happens here is

we would not use them to do anything visible with your pages. So if you're using a type of structured data that we don't support, then you would not see any visible effect there. I don't know. Maybe you have a car on your page and there is a structured data type for car. Then just using that won't automatically transform your search result into something  

#### [0:08:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=480) |  that looks like a car because, if

we don't have that type of rich result, then we wouldn't be looking at that markup. And if we did have that type of rich result, we would have that documented appropriately in the Developer's Guide. That said, all types of structured data help us to better understand the entities on a page. So in particular, going back to the car example, if you have something that uses a lot of words that could be interpreted as maybe an animal or a type of car,  

#### [0:08:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=510) |  then that's something where if you tell

us, this is actually about a car, then that would give us a little bit more information and would allow us to try to rank your pages more appropriately. So it's not that you would rank higher. But rather, we would try to show you in the queries a little bit more where we better understand your page and where we better understand that your page matches the user's intent. So with that in mind, if you're limited or severely limited  

#### [0:09:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=540) |  by time, then I would focus on

the types of structured data that are really visible. And if you do have a bit more time or if you have a CMS that's flexible, that allows you to expand on things that maybe you're talking about, then that's something where there's definitely no downside to adding more types of structured data. The one thing I would watch out for here is that you can easily get lost in the weeds with all of the different structured data types. So it's very possible that you mark up  

#### [0:09:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=570) |  every other word on a page and

say, well, this is this element and this entity related to this entity. And at some point, you spend more time on the structured data than you actually spend actually on the content. And that's not going to be useful for your website. So trying to find a balance there is something that I'd recommend. And if you're really limited by time and you really need to focus on things that have a clear result, then I would focus on the types that are documented  

#### [0:10:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=600) |  in the Developers' Guide. A few of

my new websites in competitive niches have started to rank without building even a single link, just with pure content. It took a while, though, more than two years. So I guess maybe those aren't new websites, but kind of older ones. Could I have saved precious time by building links from high-end websites to reduce this time period? Or it wouldn't have mattered at all, it would have taken the same amount of time regardless?  

#### [0:10:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=630) |  So we use a ton of different

factors when it comes to crawling, indexing, and ranking. So it's really hard to say, if I did this, how would my site rank compared to when I do this? So those kind of comparisons are kind of futile in general. In practice, though, when you're building a website and you want to get it out there, and you want to have people go to the website and recognize what wonderful work that you've put in there,  

#### [0:11:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=660) |  then promoting that appropriately definitely makes sense.

And you don't have to do that by dropping links in different places. But you can get the word out in different ways. And by getting the word, out you're bringing people to your website. And if they like what they see, then maybe they'll link to your website. And all of these things can add up as signals. And it can help us to better understand where your website fits in with the rest of the web.  

#### [0:11:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=690) |  So from that point of view, I

would not just create a website and put it up, and don't tell anyone about it, and hope that Google finds it, and starts ranking it in competitive areas. Like a normal business, spend time to build that up, and to build an audience, and to understand what people like, respond to feedback that they give you, and really build things up as you  

#### [0:12:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=720) |  would with a normal business, essentially. How

important is speakable and keyword-rich URLs for AMP pages? Our tech guys would like to switch to ID-only pages-- for example, amp.example.com/article/12345. And the canonical would still refer to the speakable and keyword-rich URL. As far as I know, this wouldn't change anything at all.  

#### [0:12:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=750) |  So that's something where, if you want

to switch to more of an ID-based URL system, that's totally up to you. We do use words in URLs as a really, really small factor when it comes to understanding a page. But as soon as we are able to process the content on the page, then those words in URLs are not going to play a significant role anyway. So from that point of view, it's not  

#### [0:13:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=780) |  something where I'd say you're losing out

on a lot of things by not having keywords in your URL, regardless if that's your canonical web page or the AMP version of the page. In general, people see URLs less and less frequently. Especially if you're on a mobile phone, it's really rare that you actually see a URL. So I think that shift has been taking place over time anyway, in that it used to be people would focus on the URL  

#### [0:13:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=810) |  and try to understand what this URL

is before they click on it. But nowadays, you can't really do that. So I kind of see the importance of including a long URL with a description of the article as something that's fading away a little bit, I guess. And that's really regardless of AMP page or web page in general. Is a lastmod necessary for a new site map?  

![](https://i.ytimg.com/vi/msq9mZgX6ZQ/maxres1.jpg)



#### [0:14:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=840) |  Or is this only for normal website

maps? So lastmod is one of those things that we do take into account from a sitemap file. We don't use any of the other attributes-- well, obviously the URL. But any of the other attributes, like priority or change frequency, we don't use those. We do use lastmod, however, to recognize when pages have significantly changed and when pages are essentially new.  

#### [0:14:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=870) |  But for that to work out, we

really need to have a sitemap file that uses the lastmod date in a reasonable way. So don't use today's date for all of your pages' last modification date because if everything changed today, then nothing is really that important for us to pick up first. So what you really want to do is to give us a clear hierarchy of changes that you've made so that if we know that we last crawled maybe yesterday  

#### [0:15:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=900) |  and we see these five pages are

new, then we can focus on those five pages a little bit more. So that's the direction I would head there. Use a proper last modification date. And specify that for all of your URLs. And really, use this for the sitemap file, regardless of the type of sitemap file. So if that's a new sitemap file, then you kind of have that limitation with the 1,000 URLs. For the normal sitemap file, it's essentially the same thing.  

#### [0:15:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=930) |  Does the way searchers use branded terms

in conjunction with non-branded terms effect ranking for non-branded terms? For example, if Google noticed a lot of surfers using the query [INAUDIBLE] company plus widgets, would Google be more likely to rank [INAUDIBLE] company for non-branded queries for widgets? I don't think it would work that way. Essentially, just because people are searching  

#### [0:16:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=960) |  in a particular way for your website

doesn't mean that we can say, well, if they're searching like this, then we should rank them for other things as well. However, if people are explicitly looking for your company, then that's a really clear sign that they really want to go to your company. So that's something which, from my point of view, always makes sense to try to find subtle ways to encourage people to do that because if people understand know your business, they understand your brand,  

#### [0:16:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=990) |  and they explicitly search for your brand,

then suddenly there's no competition in the search results because it's really clear they want to go to your website. And essentially, we call that more of a navigational query. And that shift from people are searching for widgets and going to, well, [INAUDIBLE] company widgets, that's a way of making sure that people go to your website. So it's not so much that branded queries drive more traffic  

#### [0:17:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1020) |  to non-branded queries. But rather, if people

are searching for your brand, suddenly you'd have a lot less competition because Google understands fairly quickly that this is your brand and this is your website. The caveat here is, of course, if your brand is a generic keyword, then that's not really going to work that easily. So if, for example, you named your brand Best Widgets,  

#### [0:17:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1050) |  then if people search for best widgets,

that's really unclear to us that they actually want to go to your website, whereas, if you have some clear company name like-- I don't know-- [INAUDIBLE] company and you also sell widgets, and if they search for company, then suddenly we would understand this query matches your website. And it is more of a navigational query than an informational query. So that's something always worth to keep in mind, especially  

#### [0:18:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1080) |  when you're building up a new website

and a new brand, that you pick something that people can remember and that's kind of unique in the sense that, when people search for it, it's easy to recognize that they really want to go to your website. It's not that they want to get general information for these keywords that they entered. How important is internal linking in general? My client's current HTML sitemap takes five clicks  

#### [0:18:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1110) |  before you reach a page with content.

Outside of using the search bar, the only other way Google can reach these pages is with an XML sitemap. So my guess is, with the current HTML sitemap, you mean the current website in general, not a sitemap page that you would have. So in general, internal linking is really important.  

#### [0:19:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1140) |  And it is almost the best way

to understand the context of individual pages within your website. So it's a lot easier for us to understand this is the hierarchy of your pages, these are the higher level pages, and more important pages, or less important pages. All of that is something that's really important for us to be able to pick up on. And it's something that is reflected in a lot of places in Search. So just for example, something that I saw recently--  

#### [0:19:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1170) |  if you have a really flat hierarchy,

in that you have all of your pages linked from all of your other pages, then we can't really tell which of these pages are more important than others, which can lead to situations like you have a site link on one of your pages that is shown right below the search result that points to a completely unrelated page. And from our point of view, we think, well, all of these pages are equally important.  

#### [0:20:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1200) |  And they're all very related because they're

all linking to each other. So taking any random page and using that as a site link is something that could be reasonable, right? Whereas, if you have a clear hierarchy, then it's a lot easier for us to understand, well, this is a part of the website that belongs together. And this other part belongs together here. And this is the higher level part. All of this is a lot clearer to understand. So with that said, the number of clicks  

#### [0:20:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1230) |  to reach a page from your home

page, for example, is something that helps us to understand how that page fits in. But it's not necessarily something that we say is bad if it's above three, or four, or five. So the important part is really that you have a clear hierarchy. And when you have that hierarchy, the absolute number of clicks is less critical. That said, if there is something that you really  

#### [0:21:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1260) |  want to highlight on your website and

you say, well, this is my favorite product, my best-selling product, the product I make the most profit from, or this is something completely new that I really want to promote, then having that linked more prominently within your website definitely makes sense because then we can understand that you really care about this new thing or this unique thing here. And we can show it appropriately a little bit more visibly  

#### [0:21:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1290) |  in search as well. So if this

is some random product on your website and it takes five, six clicks to get there, perfectly fine. If this is something that is really your best, most important product and it's a very competitive niche, then link to that, [INAUDIBLE] Yeah. And with regards to linking from the XML sitemap,  

#### [0:22:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1320) |  that's something that's almost separate because, from

the XML sitemap, we can pick up which pages are new and changed. But it doesn't give us a lot of context about those pages. OK. After a DMCA notice, my client removed the content and also removed those URLs from Google index. Still, we're receiving a DMCA removal notification. How do I inform the complainant that my client has removed all of the content?  

#### [0:22:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1350) |  My client had the rights to publish

the content. But now, the license has expired. I think someone is accidentally muting me. No problem. So with regards to DMCA complaints, the thing you would need to do is to respond to that DMCA complaint and to saying, well, I cleaned this up. I resolved this issue.  

#### [0:23:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1380) |  So that DMCA complaint goes back to

the person who sent the complaint. And they can take that and say, oh, OK, it's resolved. I will cancel this. So that's kind of the direction that you'd need to take there. In general, if this is a single URL and you've removed it from your website and it's no longer showing in search, then having that DMCA complaint pending or open isn't something that would affect the rest of your website. However, if this is something that  

#### [0:23:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1410) |  happens on a larger scale, in that

you have a lot of DMCA complaints on your website and you removed them individually and it's like you're taking them on step by step, then by having all of those DMCA complaints pending and still active, that's something that we might pick up in our algorithms and say, well, we don't really know how well we can trust this website. So if you get these kind of DMCA complaints on a larger scale, then I would respond to them and make it clear  

#### [0:24:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1440) |  that this is resolved, or make it

clear that this is an incorrect DMCA complaint so that our systems understand that there are no pending DMCA complaints there. I'm going to mute you for a moment. If you're featuring too many ads on your articles, the rankings of your website will get affected.  

#### [0:24:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1470) |  Is that true? It's not so much

the number of ads on your pages as the general experience on the pages themselves. So that's something where we look at things like the above-the-fold content. And if the above-the-fold content is reasonable for your website, if there is information about those pages, then that's fine. If you have ads that are loaded below the fold or if you have small parts of the above-the-fold content  

#### [0:25:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1500) |  with ads, then that's generally OK. And

that's not so much based on the number of ads, but more based on how prominent are these ads. Are they taking up a large part of the above-the-fold content? Or is this something that's like a small bar on top which has five little ads next to each other? That's something that's very different from one very large ad that takes up the whole above-the-fold content. MENASHE AVRAMOV: So John, I have a related question.  

#### [0:25:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1530) |  JOHN MUELLER: Sure. MENASHE AVRAMOV: We have

[INAUDIBLE] links with an affiliate. And we're wondering if we need to add-- if we need to prioritize high adding rel sponsored to our links? Or nofollow is good enough? JOHN MUELLER: In general, nofollow is good enough. If you can add the rel sponsor to that as well, that helps us to better understand a little bit.  

#### [0:26:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1560) |  But it's not something that would be

critical. So in particular, if you have existing links like that, I would just leave them like that. If you're setting up a new website, then I would just use maybe either rel sponsored or rel nofollow sponsored together just to make sure that it's a little bit clearer going forward. MENASHE AVRAMOV: OK, thanks. JOHN MUELLER: Is it problematic to develop with React and implement dynamic rendering on a large site that  

#### [0:26:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1590) |  is essentially static content which doesn't update

rapidly? Our IT department is advocating for this route in our upcoming redesign. We're concerned going the single page application root is going to overcomplicate a lot of things, including SEO. So it will get more complicated. I think that's generally almost always the case when you move from a static HTML setup  

#### [0:27:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1620) |  to a dynamic JavaScript-based framework. So that's

something to keep in mind. It will get more complicated. It's not that it's going to become impossible. But it will definitely become a little bit harder to manage. It'll become a little bit harder to set up properly. It'll become a little bit harder to monitor your setup, to monitor your website that everything is working well because it's a lot harder to use simple command line  

#### [0:27:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1650) |  tools to just fetch the content of

your pages and check that the metatags are the same, all of these things. So that's something definitely worth keeping in mind, in that you might save a lot of time on the development side, or be able to create something really fancy on a developer side. But you will almost certainly have to invest a little bit more on the SEO side to make sure that you're doing everything right. So that's, I think, the baseline situation.  

#### [0:28:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1680) |  It's not that it's going to become

possible to do. And there are different ways of dealing with that, which could be as simple as, well, maybe you just prerender all of the content and you serve the static HTML version either to crawlers or even to all users, depending on how you have that setup. But it is something where you'll have to look a little bit further than just like, oh,  

![](https://i.ytimg.com/vi/msq9mZgX6ZQ/maxres2.jpg)



#### [0:28:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1710) |  I will just switch it on or

switch it over and everything will continue to work the same as before. So that's, I think, definitely worth keeping in mind. I think it's getting a lot easier. It has gotten a lot easier because there's a lot more information out there on what you need to do. There's a ton of documentation on our Developers' Guide on how to deal with JavaScript sites. A lot of the SEO tools, nowadays, they can deal with JavaScript sites. But it is something where you have to spend a little bit more  

#### [0:29:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1740) |  time, especially in the beginning, to make

sure that you're picking a setup that is actually going to work well for your business for Search in general. Let's see. One question about Discover-- my website is in Swedish. However, my articles are not appearing, for me and the rest of the Swedish people, when you're connected to a Swedish Wi-Fi.  

#### [0:29:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1770) |  However, when I connect with Wi-Fi outside

of Sweden, my website articles are appearing as normal. The problem is that my target group lives in Sweden. So it started on a specific date. And it seems more Swedish websites have the same problem. I am not aware of anything specific related to Sweden. But I'll double-check with the team to see what might be happening there.  

#### [0:30:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1800) |  I notice you have a .net domain

name, which is a generic top-level domain, from our point of view. One thing I would make sure is that you also have the geotargetting settings set to Sweden, if that's really your target audience. So that's something you can set in Search Console. It's a little bit hidden at the moment because it's a part of the old Search Console. But that's definitely something I would try to set up. But I'll also check in with the Discover Team  

#### [0:30:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1830) |  to see if they're aware of anything

happening there. Does a broad core algorithm update also affect Google Discover? A couple of weeks after the January 2020 update, we noticed a drop in traffic coming from that source. And Search Console also shows a drop in impressions overall. Yes, I believe we included that in one of the core update  

#### [0:31:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1860) |  tweets series that these kind of core

updates can affect Google Discover visibility as well. Should we have our sites automatically append our company names to the end of the metatitles or leave it off and let Google do it? Right now, our company page automatically appends the company name to the title. And it's annoying because often the titles get too long and end up with ellipses.  

#### [0:31:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1890) |  Yeah, essentially, that's up to you. So

what happens on our side is we try to understand what the website name is, in general. And if that's not included in the title of your pages, we may append that to the end as well. So probably what happens here is we would show them in more or less the same way anyway. In general though, having the website name  

#### [0:32:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1920) |  attached to your titles makes it a

lot easier for us to understand which title to actually use. So that's something where if you give us this information, we'll probably end up using it correctly. If you don't give us the website name at all in the title, then it'll be a lot harder for us to figure out what you would like to have shown there as a website name, company name, in general.  

#### [0:32:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1950) |  To handle our pagination, these are category

pages, actually. And they may contain over 100-plus pages. Do you think this is a good practice if we create page 1 which lists our most important 30 products, and page 2 and a very lightweight View All page which might contain up to 5,000 unique product URLs? And page 2 would be canonicalized to, I guess, the View All page.  

#### [0:33:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=1980) |  So in general, this kind of goes

back to what I mentioned before, in that having a clear hierarchy on your website makes it a lot easier for us to understand your website in general. So if you have a category page with page 1 which is linked here and then page 2 which is actually a View All page with links to all other pages, then we can still understand things from page 1 are probably more important and something higher  

#### [0:33:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2010) |  up in the hierarchy than everything else.

But within this bucket of everything else, everything is kind of equivalent. And from our point of view, that makes it really hard to understand which of these are more critical to you. And it makes a little bit harder to understand how things are related-- so which of these products end up being similar to each other. It's really hard for us to tell. It kind of depends on your website, though.  

#### [0:34:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2040) |  If this is within a set of

different categories and the first page in this category is already really a good sample of the important products that you care about in that category, then we have a lot of hierarchy just from those different categories already. And then the View All page, which links to everything else, is something that essentially is connected further down in the hierarchy of the website. So that's something where maybe it doesn't matter that much.  

#### [0:34:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2070) |  But on the other hand, it might

also just be that if those View All pages aren't that important in general, then you might as well just use a normal pagination setup rather than this complicated one that has the normal pagination and then the View All pagination. You might as well just have linking between the individual pages of pagination directly. MIHAI APERGHIS: Hey, John. JOHN MUELLER: Hey, go ahead.  

#### [0:35:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2100) |  MIHAI APERGHIS: Regarding site hierarchies and overall

architecture, so we're working with a fairly big retailer, in the sense that they have a few hundred thousand products. And there's about 1,000 categories or something like that. And one of the main issues I think they have is that most of those 1,000 categories are in the sitewide menu, like the header menu.  

#### [0:35:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2130) |  So that's quite a lot of links

on every single page. So from my point of view, on one side that makes all of the categories equal, in the sense that there is no hierarchy for Googlebot because everything is sitewide. Everything is linked sitewide. And on the other hand, having 1,000 links on every single page might make it difficult for Googlebot  

#### [0:36:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2160) |  to crawl everything maybe or assess where

the page rank should flow exactly. So what are your thoughts? I mean, I know what is the best practice. But what about the reasons why you shouldn't go with such a flat architecture? JOHN MUELLER: Yeah. So I think, purely from a technical point of view, we'd be able to deal with 1,000 links on a page. I don't see a problem there.  

#### [0:36:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2190) |  So that's something where it used to

be that we would just use, I think, the first 1,000 links on a page. But I think we dropped that 10 years ago or something like that, pretty long time ago. So just from purely a technical point of view, that's not going to cause a lot of issues. But I could imagine, from understanding the context of individual categories, it is something that we might have trouble with. So in particular, you might notice this with site links.  

#### [0:37:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2220) |  That's the place where I ended up

noticing it because people flagged it to me where, if you search for one category and you have different site links below that category page in the Search Results page, and if those other categories that are linked there are totally unrelated and don't make a lot of sense, then that's a sign that we don't really understand how these pages should be connected and which of these categories belong together. So that doesn't necessarily mean that you  

#### [0:37:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2250) |  have to go from 1,000 categories to--

I don't know-- 100 categories and you link to subcategories or something like that. But maybe there are other ways to make it a little bit clearer that these things belong together, these things belong together, these other things belong together. So that's the direction I would go there-- first to figure out, is it really a problem or not? And if it is a problem, then think about ways that you can split that up a little bit clearer.  

#### [0:38:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2280) |  MIHAI APERGHIS: Well, one thing they do--

they already show subcategories in the sidebar. Once you go to a parent category, they show the subcategories in the sidebar. The only thing is that all of these categories are also in the main menu. So the main menu is, again, something like 900 to 1,000 categories. Obviously, that's not very useful for users as well, we're guessing, because we noticed a lot of them are just using the search bar by [INAUDIBLE] search, probably because the menu is so big.  

#### [0:38:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2310) |  I was wondering whether-- I know that

Google splits main content from supplemental content. And the menu pulls in that supplemental content. Does that mean that it's less of a problem to have all of the category links in the menu? Or does it really play a role there? JOHN MUELLER: I don't think you'd see a big difference there, because essentially what would happen is we would recognize the link maybe  

#### [0:39:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2340) |  from one category to another category. We'd

see that in the top menu. And we'd also see it in the sidebar and maybe within the body of content as well. But it's not that we would add up the value of those individual links. It's just like, well, that link is already there. And you're not giving us more information by also including it multiple times. So that's something where just piling on more versions of that link to create a category structure  

#### [0:39:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2370) |  doesn't really work. It's really like we

already see it. And we know that link is there, even if it's in the header somewhere with the main navigation. MIHAI APERGHIS: So because you see those links everywhere, does that mean you can't really-- as you mentioned earlier with the site links, you might not be able to figure it out, OK, so this is a parent category that targets the top eight and these are subcategories that target specific parts of that topic and things like that?  

#### [0:40:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2400) |  Would that create a problem? JOHN MUELLER:

As far as I understand it, yes. So if we already know that link is there, then it's not that we're going to try to figure out like, well, it's also here and also here to try to guess at a hierarchy a little bit more clearly. It's really, give us a clear hierarchy and we'll try to work with that. MIHAI APERGHIS: OK, cool. Thanks.  

#### [0:40:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2430) |  JOHN MUELLER: Another one that sounds kind

of similar-- let's see. If page A1 has 20 outbound links other than a sitemap, these are links through which Google can discover those 20 pages. If we put a canonical tag on A1 pointing to page A, would Google still be able to discover those 20 outlinks on page A1? So with rel canonical, you're essentially telling us that these pages are equivalent.  

#### [0:41:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2460) |  And from our point of view, if

you tell us at these pages are equivalent, then we can just pick one of those and use that for indexing. And it might be that we pick page A1 as a canonical, even though you have a rel canonical pointed somewhere else, because for canonicalization we use a lot of different factors. That includes the rel canonical. It also includes redirects, internal linking, sitemap files. All of these things come together when we pick a canonical. So if we pick page A1 as a canonical,  

#### [0:41:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2490) |  we'll know about those 20 links. If

we pick a page A as a canonical and it doesn't link to those 20 other pages, then we will not use those 20 links on page A1 as a part of A. So with the choice of the canonical, if we understand that these pages belong into a set of pages that could be a canonical, we will only focus on the content and the links of the canonical page. Everything that's on the non-canonical versions, that we end up essentially skipping over for indexing,  

#### [0:42:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2520) |  we would not take into account So

if these are supposed to be equivalent, then make sure that they're really equivalent. If they're supposed to be different, then let them be indexed individually. Googlebot now uses the latest version of Chrome to crawl, render, and index content. When there are discrepancies between the source and the render JavaScript, what factors does it use to determine the authoritative version?  

#### [0:42:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2550) |  So if we render a page, we

will use the rendered content only as a basis for indexing. So if during rendering the content of the page is essentially deleted and replaced with a placeholder text, then we will only use that placeholder text if we index that page after rendering. So anything that was on the page before will be gone. Usually, that's less of an issue because if you have a JavaScript framework, you're adding content to the page.  

![](https://i.ytimg.com/vi/msq9mZgX6ZQ/maxres3.jpg)



#### [0:43:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2580) |  So we would have the existing content

plus the JavaScript content. And that's what we use for indexing. That kind of makes sense. The part where this becomes problematic is if there's a conflict between the content that is on the page before and the content that is on the page afterwards. And one situation that we have seen, for example, is if the content on the page before it gets indexed has a noindex metatag on it.  

#### [0:43:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2610) |  Then regardless of what we place there

with JavaScript afterwards, that noindex is always going to be there. So that's something where if you have a severe conflict between the static version and the JavaScript version, it becomes a lot trickier for us. Another common case is if you have a rel canonical on the static page before and you have a different rel canonical with JavaScript afterwards. Then it's kind of tricky for us to understand, well,  

#### [0:44:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2640) |  which of these ones is actually useful?

And that comes from us, on the one hand, looking at the static version before, and then rendering the version based on that. So that's something where, as much as possible, you want to make sure that those pages align. And if you add additional information with JavaScript, that's fantastic. If you add information that clashes with the existing information, then that's something where it gets a lot trickier.  

#### [0:44:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2670) |  When does Googlebot take the rendered DOM

snapshot used for indexing? We don't have a specific time. So it's not that there's a specific time-out that happens for us to pick up the index version. We try to recognize when a page is ready. Whoops, wait. Menashe, I think you're presenting.  

#### [0:45:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2700) |  Let's see. Maybe I can turn it

off. Yeah, we don't have a specific time with regards to understanding when a page is ready. The main reason we don't have a specific time is that, when it comes to rendering, we do a lot of caching. And we do a lot of steps to try to understand when a page is generally ready.  

#### [0:45:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2730) |  And that can result in things like

the timers on the pages being processed quite differently than when you process a page manually. So that's something where it's really hard to specify a specific time, just because of the way that we render pages. So for example, if you have different JavaScript APIs that you're pulling content in and calling those APIs takes  

#### [0:46:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2760) |  a second each when you run it

in the browser, it might be that we already have those individual elements cached on our side. And when we render the page, we can render this page in a fraction of a second. So we might get the full version in a fraction of a second, whereas you might need to wait maybe 10 seconds to actually render the full page in your browser. And similarly, it can be the other way around in that, when you access a page, you're able to get all of those requests in right away.  

#### [0:46:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2790) |  And you can get that page essentially

right at that time. Whereas, when we try to render the page, it might be that we're limited by the amount of crawling that we can do for individual pages. And then suddenly, it takes us maybe an hour to actually render that page. So those differences are things that come out just because of the different approaches that we take for rendering content for indexing versus what you would do if you were accessing  

#### [0:47:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2820) |  a page with a browser. MATEL NICOLAE:

Hey John, may I ask a question? JOHN MUELLER: Sure, go for it. MATEL NICOLAE: So we have a client that is a retail client. And they have some pages for summer collections 2016, '17, '18. And last year, they decided to make a non-year URL for the summer collection. They did redirect of all of these. But the problem is Google is still seeing these URLs.  

#### [0:47:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2850) |  It's indexing them. If you try to

access, the 301 works. Every tool I tested with sees the 301. In Search Console, when I inspect the URLs, it says that they are indexable, they have a self-canonical. If I test the live URL, it still says they're indexable, but the canonical changes to the new URL that was added last year.  

#### [0:48:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2880) |  Could you help in any way, pointing

in what might be the issue here? JOHN MUELLER: So when do you see the old URLs? Is that something you see in Search? Or is it showing-- MATEL NICOLAE: When I search for the brand and summer collection, I see those old URLs beside the new one. JOHN MUELLER: OK, in addition to the new one? MATEL NICOLAE: Yeah, yeah. So you see like three or four URLs for the same. JOHN MUELLER: OK. Usually, that cleans itself up over time.  

#### [0:48:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2910) |  So that's something where if we see

that there's a redirect, if we see that the rel canonical is pointing to the right version, then that's something where, over time, we will recognize, oh, more and more signals point to this version. So we'll only index that version. The thing I would watch out for is to make sure that your internal links don't refer to the old URLs. That's something that people often forget. Sitemap file, if you have hreflang,  

#### [0:49:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2940) |  annotations, all of those should also point

to the new URLs. Sometimes, you can use third party crawlers to just recrawl your whole website and make sure that there is no reference to the old URLs. And if you're sure that that's the case, then that's something that'll just settle down over time. So for individual pages, it's really hard to force that to happen. It just happens naturally over time. And the thing to also keep in mind is if you explicitly look for the old URLs.  

#### [0:49:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=2970) |  So if you do a site query

or if you do a search which includes maybe words from the old URL, then it might be that we would still show that in Search, even when we switched over to the new one as canonical. So that's really common, for example, if you do a site move from one domain to another. If you search explicitly for the old domain, we'll show it to you because we're trying to be helpful by saying, well, this is the thing that you're looking for.  

#### [0:50:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=3000) |  But in general, if you've made sure

that everything aligns, that everything matches the new version, then I would just let it run. MATEL NICOLAE: OK, thanks. JOHN MUELLER: Sure. MENASHE AVRAMOV: So John, I have a question. I by mistake shared my screen. But I solved for that. So we have a new site. And the site has something that appears like a technical bug. So maybe if it's fine, I will present my screen.  

#### [0:50:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=3030) |  But I'll try to explain it. So

basically-- give me a second. We basically have a page that looks like it's appearing in Google. But when you're checking it, it's a new site. And when you're checking it, even the inspected URL is showing that the site is indexed. And it looks like it has the chance to get a rank.  

#### [0:51:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=3060) |  The results comes out empty. So while

it technically looks like you're inside and it's fine, in any way that we're checking, the page actually doesn't appear indexed. You have by chance any idea why this kind of stuff can happen? We also tried to escalate it to the Community Forum. And we don't really solve it.  

#### [0:51:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=3090) |  JOHN MUELLER: So one place where this

could happen is if there is either a manual action or if you have a URL removal in place. That's something where both of these could be similar in that the inspect URL would say it's indexed, but it wouldn't show in search because, from our point of view, these are basically just filters that happen on top of the search results.  

#### [0:52:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=3120) |  The page can still be indexed. It's

just not showing in search. MENASHE AVRAMOV: Both of them, it doesn't happen. JOHN MUELLER: OK. The other thing is that sometimes a site query, because it's a restrict rather than a comprehensive list of URLs that match from the indexing point of view, it can happen that something is just not shown in the site query. So it might be indexed, but maybe indexed in a way that, from a site query itself, it wouldn't be shown.  

#### [0:52:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=3150) |  And depending on how you search for

that page, it might be the same. So what you could do is double-check in Search Console in the Search Performance section and filter for that specific URL. And then you can see, is it occasionally shown in Search or not at all? MENASHE AVRAMOV: No, it doesn't show in Search. It's kind of, well, de-indexed. But it's technically appearing.  

#### [0:53:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=3180) |  And it's a new site that suddenly

got dropped without any manual action [INAUDIBLE] Search Console. JOHN MUELLER: It might just be that our algorithms are trying to figure out how to show the site properly. That's something that sometimes it takes a bit of time to settle down. It really depends on the website itself. It's also something where, if the topic is something that  

#### [0:53:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=3210) |  is often used for spam, then it

might be a bit trickier for our algorithm to figure out, oh, well actually, it uses similar keywords to maybe other kinds of spammy content. But actually, this one is a good website that we should show in Search. And that's something that can take a bit of time to settle down properly. MENASHE AVRAMOV: OK, thanks. JOHN MUELLER: Sure. All right, any other questions from any of you?  

#### [0:54:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=3240) |  IZIN IZIN: Yeah, John, I had a

question here. JOHN MUELLER: Sure. IZIN IZIN: I assume that you remember the IKEA case which is related to indexing issues with wrong hreflang attributes. Turkish Airlines is one of our main customers. And they complain from the same thing. We wonder when Google can fix this problem. JOHN MUELLER: Which website was that? IZIN IZIN: I remember that IKEA was having some problems  

#### [0:54:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=3270) |  with hreflang indexing status. You remember that?

Google was indexing wrong pages about IKEA from different geographies and from different queries. JOHN MUELLER: Mm-hmm. IZIN IZIN: And we have same problem with Turkish Airlines. And our customer wonders when can this problem be fixed. JOHN MUELLER: That sounds like something different  

#### [0:55:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=3300) |  because I think the issue that we

saw with the IKEA website was unique there. So it would be really helpful to have more specific information about what kind of problem you're seeing. So if you want to stick around afterwards, maybe we can discuss that a little bit more. Or if you want to drop a link in the chat of some sample URL I can look at. IZIN IZIN: I can give you an example.  

#### [0:55:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=3330) |  We see that our pages are getting

indexed in Turkish queries, which may be English pages. But we are using hreflang correctly. There is something wrong about code. And we assume that these will be related to the IKEA case. JOHN MUELLER: But then you have Turkish content and English content? Is that correct? IZIN IZIN: Yes, we have different contents. And we are using hreflang correctly. But Google is indexing them different.  

#### [0:56:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=3360) |  JOHN MUELLER: OK. Now, maybe you can

drop some sample URLs in the chat. And I can pick it up afterwards. IZIN IZIN: OK, thank you. JOHN MUELLER: Because these tend to be kind of unique issues. So the ones that we see more often are cases where it's the same content for different countries. So for example, if you have German language content for Germany and Switzerland, it's exactly the same content.  

#### [0:56:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=3390) |  And that just makes it harder for

everybody. If you're showing Turkish and English content, we should be able to see that it's different. But maybe you can give me some sample URLs and I can check. IZIN IZIN: I will. Thank you for your time. JOHN MUELLER: Sure. All right, looks like we're kind of out of time. I still have a bit of time left. So if any of you want to stick around and chat off  

#### [0:57:00](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=3420) |  the record after the recording stops, feel

free to do so. But otherwise, I'll pause the recording here. Thank you all for joining in. Thanks for all of the questions that were submitted. If there is anything else on your mind that we weren't able to solve here or if any of the answers were confusing, feel free to drop us a note on Twitter or post in the product forums or add a question for one of the future Hangouts. All right, thanks everyone.  

#### [0:57:30](https://www.youtube.com/watch?v=msq9mZgX6ZQ&t=3450) |  And wishing you all a great weekend

in the meantime. MENASHE AVRAMOV: Bye-bye. JOHN MUELLER: Bye.  