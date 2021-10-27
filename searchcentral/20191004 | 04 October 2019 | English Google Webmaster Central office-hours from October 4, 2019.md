[![English Google Webmaster Central office-hours from October 4, 2019](https://i.ytimg.com/vi/Cr3muqj-RKQ/maxresdefault.jpg)](https://www.youtube.com/watch?v=Cr3muqj-RKQ)

## English Google Webmaster Central office-hours from October 4, 2019

This is a recording of the Google Webmaster Central office-hours hangout from October 4, 2019. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Watch out for new sessions, and add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



Feel free to join us - we welcome webmasters of all levels!



#### [0:00:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=0) |  JOHN MUELLER: All right. Welcome, everyone, to

today's Webmaster Central Office Hours Hangout. My name is John Mueller. I'm a webmaster trends analyst here at Google in Switzerland, and part of what we do are these Office Hour Hangouts, where webmasters can jump in and ask us any question that's kind of on their mind with regards to websites and web search. Let's see. A bunch of things were already submitted, so we can go through some of those.  

#### [0:00:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=30) |  But as always, you're welcome to get

started here if you want to ask the first couple of questions. If not, that's also fine. OK, I'll just jump through the questions that came in already, because there's a ton of them this time. I think everyone dropped their questions  

#### [0:01:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=60) |  into this Hangout rather than the other

one last night, but that's fine, too. Let's see. The viewport tag on responsive sites. So this is a fairly complicated question. It took me a couple of times to try to understand what exactly is going on. I think what it comes down to is this is a website that has separate mobile URLs.  

#### [0:01:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=90) |  And at the same time, they're using

the viewport meta tag on some of the pages, and they're kind of wondering, does a viewport tag tell Google this is a mobile page and kind of block the separate mobile URLs from being used? And the viewport tag is essentially something that we use to try to understand the mobile friendliness of a page. So it's a way of scaling things for the viewport, which is usually used on mobile devices,  

#### [0:02:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=120) |  but it's not only for mobile devices.

So just because you have a viewport meta tag doesn't mean that we will see this as the mobile version and we won't look for the other versions that are available. So in particular, if you have separate mobile URLs, what we recommend is on the one hand, having the link between the two versions. So from the desktop version, you have a link rel alternate to the mobile version. From the mobile version, you have the link rel canonical back to your desktop version. That's one thing. And the other thing that I strongly recommend  

#### [0:02:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=150) |  is setting up redirects so that when

desktop users go to the mobile site, they get redirected to the desktop site. And when mobile users go to your desktop site, they get redirected to the mobile site. And with both of those mechanisms, you're really making it clear to us that this is the mobile version, this is the desktop version. And we can connect the two so we can use them properly for indexing, but you're giving us a clear definition, like,  

#### [0:03:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=180) |  what these versions are. And with that

clear definition, it doesn't matter if you have a viewport meta tag or if the desktop version is also kind of usable on mobile or not. So that's kind of the direction I would head there. In general, though, we've stopped recommending using separate mobile URLs, mostly because they just add a lot of complexity and they make things like understanding which one is canonical, which one you should track in Search Console, which one you should focus on--  

#### [0:03:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=210) |  make all of that a lot harder,

and you add more complexity on your side as well with regards to keeping track of all those redirects, making sure that all of those links between those versions are correct, all of that. So if you can, move to a single URL setup, which could be either responsive or dynamic serving, where you're serving a mobile version specifically for mobile users. If you do need to use separate mobile URLs, then the links and the redirects are the way to go.  

#### [0:04:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=240) |  A client's Google My Business listing isn't

showing up. I can't help with Google My Business issues. I don't really have any insight there. So I'd recommend going to their Help Forum. I work with a large health fitness publisher that took a huge hit after the March update. Getting back our results slowly. Is Google experimenting with health-related search terms  

#### [0:04:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=270) |  in preference they receive in rankings? With

some of the health partnerships, we're curious also if more approved terminology is being evaluated or elevated. So I don't think we have any specific algorithms that look out for these kind of sites, but our general ranking algorithms do try to make sure that we treat sites in a way that we think is appropriate in Search,  

#### [0:05:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=300) |  in terms of trying to understand the

intent of the queries that people have, and trying to show relevant search results that we can kind of trust. And some of that is kind of the-- some of the ideas behind that are visible in the Quality Rater Guidelines that we publish regularly. There are various sites that go through these, because these guidelines are quite comprehensive in the meantime. So my recommendation there would be to look through these guidelines and to try to understand how Google tries to evaluate  

#### [0:05:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=330) |  the quality, especially for sites that kind

of go into this health/medical area. The second part is a question with regards to Google News. We're being denied while competitors with less researched content are being included. I also don't have any insight into Google News.  

#### [0:06:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=360) |  I know they have made-- I believe

they've made the application process a little bit more strict, so that's something where I think it's kind of OK to have a high bar for something that's included in a news service like Google News. If you're unsure about why you're not being accepted there when you're applying, I would also make sure to post in the Google News Publisher Help Forum. There are lots of folks there who have experience with these kinds of issues  

#### [0:06:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=390) |  and who can help you to figure

out what you could do to improve there. How to correctly implement pagination on an e-commerce site? The links inside each page will be found and indexed. So that's kind of a short question on a really big topic, so it's kind of hard for me to package that into a really short answer.  

#### [0:07:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=420) |  We do have some guidelines on how

to deal with pagination. They're, I think, in our Help Center as well as a blog post that we did a couple of years back. I am currently trying to look into creating some more specific guidelines for e-commerce sites just to make it a little bit easier for them to implement things like pagination and filtering, category pages, all of that. A customer is closing their business site, but it has a lot of useful articles. Is it safe to use the content on a different domain name?  

#### [0:07:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=450) |  Yes, of course. If this is content

that you're allowed to publish and it's otherwise not published anymore, then I think that's a good way to make this kind of content available. Our website has a growing commerce strategy, and some members of our team believe affiliate links are detrimental to our website ranking for other terms. Do we need to no follow all affiliate links?  

#### [0:08:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=480) |  If we don't, will this hurt our

organic traffic? So this is something that I think comes up every now and then. From our point of view, affiliate links are links that are placed with kind of a commercial background there, in that you're obviously trying to earn some money by having these affiliate links and pointing to a distributor that you trust and where you kind of have some arrangement with them.  

#### [0:08:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=510) |  From our point of view, that's perfectly

fine. Like, that's a way of monetizing your website. You're welcome to do that. We do kind of expect that these kind of links are marked appropriately so that we understand that these are affiliate links. One way to do that is just to use a no follow. A newer way to do that to let us know about this kind of situation is to use the sponsored rel link  

#### [0:09:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=540) |  attribute. That link attribute specifically tells us

that this is something that has to do with an advertising relationship. We treat that essentially the same as a no follow. A lot of the affiliate links out there follow really clear patterns and we can recognize those, so we try to take care of those on our side when we can. But to be safe, usually we recommend just using a no follow or the rel sponsored link--  

#### [0:09:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=570) |  what is it, link attribute, I guess?

But in general, this isn't something that would really harm your website. If you don't do it, it's something that makes it a little bit clearer for us what these links are for. And if we see, for example, that a website is engaging in large scale link selling, then that's something where we might take manual action. But for the most part, if our algorithms just recognize that these are links that we don't want to count, then we just won't count them.  

#### [0:10:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=600) |  Add a new sitemap slowly or all

at once? I have a directory that generates 30 million URLs, and I was advised to submit 10 sitemaps every five to seven days to show these in the Search Console. That means 600 sitemaps to submit. So I guess, first of all, from a more general point of view, if you have a website that generates 30 million URLs,  

#### [0:10:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=630) |  I'd be kind of cautious about the

overall quality that you're creating there. So it's obviously possible for a website to come up and say, well, I have 30 million new URLs, and they're all fantastic. I digitized the archive of my city, and it's a lot of content, and I want to put it all online, and that might be perfectly fine. But on the other hand, we often also see sites that generate 30 million URLs based on a database,  

#### [0:11:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=660) |  or where they enumerate all phone numbers

that are available worldwide and they start putting up pages for each phone number individually. And that's the kind of thing where it's easy to generate a ton of pages, but you're not generating a ton of quality. And that's something when our algorithms look at it, they'll be like, well, we don't really know what to do with this website. We spent a lot of time trying to crawl all of this, but there's no really fantastic content here. Why are we spending so much time on this site when  

#### [0:11:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=690) |  we could be spending time on sites

that do provide really good content? So instead of worrying about whether or not the sitemaps is the problem, I would primarily worry about the quality of your content overall. And if you're sure that the quality of your content is really high, if this is really fantastic content that we've been missing, then just submit it all directly. It's like, let us know as quickly as possible so that we can crawl and index all of this content as quickly as possible.  

#### [0:12:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=720) |  And if you're unsure about the quality

of the content, then maybe double check the quality of the content first and not worry so much about kind of, like, how you can sneak this through with sitemap files. I have one question. I just want to know if it's the right practice to add two authors to one content piece. Sometimes an article requires technical expertise about a subject and the main writer is--  

#### [0:12:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=750) |  there are like-- I guess there are

two people behind the article. Sure, I don't see any problem with that. I mean, we don't have any authorship markup, so how you put information about who wrote your content on your pages is totally up to you. Some people put the names directly. Some people just have it as a part of their normal website. Ultimately, that's totally up to you.  

#### [0:13:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=780) |  There's a little bit background noise somewhere.

Noisy. The news snippet tags that Google has recently added-- is it mandatory for every website to implement these? If I add max snippet number 350 to 400 characters, is Google going to show that? Is it required to news and media sites, where their story appears in the latest post section in mobile? So no, it's definitely not required for every site  

#### [0:13:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=810) |  to use these new meta tags, robots

meta tags that we have available. It's totally up to you. So what you can do with these new meta tags is on the one hand, say this is the number of characters I want you to show at most as a snippet for my website. If you don't care, then just don't specify that. If you do care, then you can specify that. You can specify the size of an image preview, which  

#### [0:14:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=840) |  is something that may make sense if

you have images on your pages that you want to have shown in a large way. Or it may make sense if you don't want to have these images shown as a preview for your web pages. So in particular, they are for AMP pages because the AMP article markup includes an image, a large image, by default. For AMP pages, we would default to large image for you, and for normal HTML pages, we would default to kind of the standard image preview.  

#### [0:14:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=870) |  I think it's called standard or default

or something like that. And then there's something similar for video, where you can also specify the number of seconds that you would like to have a video preview shown. For most websites, these defaults are the same as before. For European press publishers, when their content is shown in France, the default is slightly different. So I would double check a recent blog post we did on that topic  

#### [0:15:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=900) |  to see what the exact defaults are

there for European press publishers when the sites are shown in France. For all other websites, for other locations, for non-press publications, you can use them however you want. The defaults are essentially the same as they've been before. One thing I would kind of shy away from is just going in there and saying, well, I will specify 5 million characters as a maximum snippet and always large  

#### [0:15:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=930) |  and the maximum of everything. I don't

think you'd get any value out of that, and I think it just makes things confusing for you because afterwards, you're like, why did I specify 5 million? Like, I-- what was I thinking of specifically there? It doesn't really make that much sense. So that's something where I'd say unless you have a reason for wanting a change in the way that your pages are shown in the search results as a preview,  

#### [0:16:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=960) |  then I would just leave the defaults

there. What's the correct way to add schema markup to a website, for example, an article schema that also includes breadcrumbs, or a web page that also includes is part of website, and so on complex schemas? If incorrect, does every schema have to be separate? Also, if the schema is being found by schema tests in rich snippets scanner by URL, does it mean that crawlers can find it, too,  

#### [0:16:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=990) |  or is there any other technical aspect

to consider to make them easier to read for crawlers? Wow, that's a lot of questions. Let's see. So I think the-- so in general, we recommend using JSON-LD to add structured data to pages. There are different ways that you can do it. It seems like JSON-LD is the one that's easiest to implement, because it doesn't rely on the actual HTML elements  

#### [0:17:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1020) |  within your page's content, so you don't

have to wrap it around the right pieces of text. You can just include that snippet of markup anywhere on the page, and that can be picked up. And if it can be picked up by the usual testing tools, then it can be picked up by Search as well. If you're doing something fancy, like injecting that structured data with other JavaScript-- for example, if you're using your Google Tag manager to inject a structured data-- then you might need to watch out how  

#### [0:17:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1050) |  you test that to make sure that

you're actually testing the JavaScript side, not just the static HTML version of the page. If you have multiple complex pieces of schema, then there are multiple ways that you can implement that. On the one hand, you can include them separately. On the other hand, you can kind of embed that. How is it called-- like one within the other, depending on the type of structured data that it is.  

#### [0:18:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1080) |  That's something that's essentially up to you.

We should be able to pick that up either way, provided, of course, the testing tools show that information. There are two other things, I guess, to watch out for. Using structured data in a way that matches our guidelines doesn't guarantee that we will show it as rich results in the search results. So it might, on the one hand, take some time. It might be something where algorithms say, well,  

#### [0:18:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1110) |  we don't know if we can actually

show this in Search. That's one thing. And the other thing is that there's a lot of schema types out there that are not used at all by our systems. So that's something where you wouldn't see any visible effect of applying that kind of structured data. So I believe, for example, there are some types for different types of cheese, for example, and we don't have a cheese feature in Search, which is kind of sad, I guess.  

#### [0:19:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1140) |  But it's something where you can specify

these things on your pages, and search engines can look at that. They can understand that this markup is here, but they don't necessarily do anything visible with that. And from our point of view, that means you're providing information. It's nice that you're providing this information, but we don't actually do anything with that information. So if you're time limited or resource limited and can't do everything on your website,  

#### [0:19:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1170) |  then I would concentrate my efforts on

using structured data for the elements that are actually visible in Search or that you have some other kind of direct return from, so that if there's something specific that you want to have shown, like you have events on your page and you also have a lot of cheese on your page, then mark up the events so that you can be shown in the Events feature in Search. And if you're-- like, if you have extra time, or you feel like it's fun, then marking up the cheese elements  

#### [0:20:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1200) |  is also fine. But that's not something

where you would see any direct effect from. Our company is changing our website from CMS to a custom solution, and this change will include design, some content, and some architecture. What are some tips that you can give us to do this while losing as little traffic as possible? So kind of in general, if you make really big changes  

#### [0:20:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1230) |  across your website, then you should expect

some changes in Search. Sometimes those are positive changes, sometimes those are negative changes. So that's something where, if you significantly improve your website, if you improve your site's architecture, if you improve the way that search engines can pull out information from your pages, then that's all fantastic. That's a big change on your website and that's something that likely you'll see some positive effects from.  

#### [0:21:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1260) |  On the other hand, if you change

your website's architecture and it's essentially all the same, but it's all set up in a different way, then probably it'll take a bit of time for us to understand the new setup and to understand that oh, this is actually the same. And you'll see, most likely, kind of a significant drop in visibility over the time where we're confused. We're like, how do these pages belong together? How do they connect together?  

#### [0:21:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1290) |  And over time, that will settle down

again. So I guess, with regards to tips, how to avoid any kind of fluctuations over this time, I would start with the assumption that you will see fluctuations and that they will be in place for a couple of months, even if you improve things overall afterwards. I think going with that assumption prevents you from kind of being, I don't know, surprised by these fluctuations.  

#### [0:22:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1320) |  Because it's very common that if you

make significant changes across your website-- if you change the URL structure, if you change the design, the internal linking-- then you will see changes in Search over the time where it takes search engines to kind of get reconnected with your website and to understand how these pages all belong together. So going with that assumption, it might help you to figure out when would be a good time to make this kind of change. That might be a period where you're saying, well,  

#### [0:22:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1350) |  traditionally people don't search for my business

during this time of the year, so I'll make this change during that time of the year so that the practical effect on my site is minimal. You could also go the other way around and say, well, during this time of the year, we're doing lots of TV advertising or lots of offline advertising anyway, so we don't really need to have the direct traffic from Search during that time, because we're compensating with all of this other sources of traffic, which  

#### [0:23:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1380) |  might be another approach. That's one thing

to watch out for. The other is we generally try to recommend doing these changes incrementally, so that you make one change and then you move to the next so that you're able to determine if something in between goes wrong, what that change was, and to make changes and fix that before you go to your next step.  

#### [0:23:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1410) |  Sometimes that's possible. Sometimes that's not easily

possible. So that's something where it depends a little bit on your site, on the kind of changes that you're making, if you're moving to another domain and changing site architecture or if you're changing the design and changing all of the internal URLs. Sometimes it's possible to decouple those. Sometimes that's not so easily possible. If you can decouple those, I think that generally makes sense, because like I said, it's easier  

#### [0:24:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1440) |  to recognize where problems come from and

to fix them before you move on. But if you can't decouple those, then my main recommendation there would be to really make a absolutely clear map of the starting state and the final state that you're aiming for so that you can monitor everything that's happening over that period of time, so that you can check for things like redirects and make sure that all of the content is correct by crawling your website  

#### [0:24:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1470) |  and checking it like that. It's a

lot harder to try to figure that out afterwards. So if you're coming afterwards and you're seeing, well, I had lost a lot of traffic, but I don't know why, and you don't know what the old URLs exactly were, then you're kind of digging for information at a time when everything is falling apart. Anyway, I hope this move goes well and that it doesn't all fall apart.  

#### [0:25:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1500) |  Let's see, next question we have here.

I know Google ignores rel next and previous annotation, and the best practice, if you have two or more pages, was to canonicalize each page like this, so you have link rel canonical to page equals 2, for example. I worry if Google can't recognize the relevance between page equals 1 and page equals 2. The pages are thought to be duplicate to each other and the value is not unified.  

#### [0:25:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1530) |  So we do recognize URL parameters, and

we can crawl URLs with URL parameters and index them like that. So in general, that's not something you need to worry about, that we wouldn't be able to recognize URL parameters. However, there's a URL handling tool in Search Console where you can specify which URL parameters we should ignore. And if you're seeing that we can't pick up your page  

#### [0:26:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1560) |  equals 2 annotations or URLs, then I

would double check there to make sure that you're not accidentally marking these as URL parameters that we should ignore. Then a question about short-lived pages, like product pages that are sold out within a few days. Is it better to let Googlebot crawl these and index them, or to add product markup or-- what should we do?  

#### [0:26:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1590) |  It's totally up to you. If you

know ahead of time that something will be short-lived, you can make the decision to say, well, I'll just no index it from the start so that Googlebot doesn't have to spend a lot of time on it. There's also the unavailable after robots meta tag, where you can explicitly tell us that the content on this page is only valid for a certain period of time and we can drop it after that date.  

#### [0:27:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1620) |  So with products that you just have

a limited amount from, you probably don't know the date when it's finished, but if it's an auction or if it's some kind of a classified ad that is only available for a couple of weeks or a week or so, then you can use that robots meta tag to tell us about that. So that might be an idea. With regards to product markup, in general, if it's an e-commerce site and you have products on there, I would use product markup. I think that's a good match.  

#### [0:27:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1650) |  I think that's independent of whether or

not this is a page that will be longer term on your site or more short-lived. I found some directory links from a previous SEO pointing to my client's website, but they use branded anchor text or URL. Is it safe to assume that these aren't-- whoops, now I clicked the wrong button. Is it safe to assume that these aren't hurting my website,  

#### [0:28:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1680) |  as you would discount the bad anchor

text rather than demoting? Probably. So if these are just random links that you found to your website, and you feel they're kind of irrelevant, then it's possible that we're ignoring them. In general, if you find a bigger section of links going to your website where when you look at them, you're like, well, someone might assume  

#### [0:28:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1710) |  that if they're looking at this manually,

that these are paid links or that there is some kind of a link scheme happening behind these links then that might be something where you could go to the Disavow tool and say, well, I want to make sure that you don't take these into account. On the other hand, if you just find random links to your website and some of them are a bit spammy and some of them a little bit low quality, I wouldn't lose any sleep over that. That's something that happens to all websites across the web,  

![](https://i.ytimg.com/vi/Cr3muqj-RKQ/maxres2.jpg)



#### [0:29:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1740) |  and we ignore a lot of that--

those kind of crazy links that just happen everywhere. Google did a core update this June and July, and many websites that got hit, my website, too. Can you please tell us some details regarding this core update and what we should do to get our traffic back? So we did a blog post on core updates maybe, I think like two, three months ago.  

#### [0:29:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1770) |  I would definitely check that out. It's

a pretty long blog post. There's a lot of information there. So a little bit of the thought behind these bigger algorithm changes that we make. So I would kind of check that out. And with regards to getting our rankings back, sometimes it's not a matter of getting rankings back, essentially, by fixing a bug or something on your website. Essentially, these core ranking algorithm changes  

#### [0:30:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1800) |  are kind of different ways that we

look at the relevance for search results. So that's not something where we would say a website has done something wrong and therefore if they fix that issue, then they will be ranking normally again. Essentially, we're saying, well, we think relevance should be determined slightly differently for these kinds of queries, and that means we will show slightly different websites. So instead of thinking about it as something that you've been doing wrong, think about it more of like,  

#### [0:30:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1830) |  how can I make sure that my

website is seen as something that is relevant for these queries when you look at it, based on these criteria that Google was looking at here? In a sector I work, a large amount of sites participate in nefarious link schemes to manipulate PageRank. These sites often rank extremely well for high value terms because of this. As recommended by Google and standard SEO practices, I have reported these activities.  

#### [0:31:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1860) |  How often and how seriously does Google

treat these reports? Yeah, there are definitely some areas where we see more issues with regards to links or with regards to other kinds of activities that go against our Webmaster Guidelines. That's definitely the case. However, I wouldn't necessarily assume that these sites are ranking because of those activities. Sometimes what we see is that sites rank fairly well just  

#### [0:31:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1890) |  in general, and it's something that they're

almost ranking despite doing a lot of these crazy things. So that's one thing to keep in mind. What generally doesn't happen is that when we recognize that a site is, for example, participating in links schemes, that we would remove the whole site from Search, because often they're doing other things which are fairly well. And on a balance, that's something where maybe we should still show them in Search based on the other things  

#### [0:32:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1920) |  that they're doing really well. So it's

not that we would remove them completely from Search just because they're doing one thing wrong. One of the big reasons why I think that's important is that a lot of sites do things badly accidentally. They don't know that this is something that they shouldn't be doing. They heard about it, I don't know, in some SEO blog or from some SEO consultant that's working with them, or that used to work with them, and they did all of this crazy stuff, and they  

#### [0:32:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1950) |  didn't realize that this was actually something

that they shouldn't be doing. This is something I see a lot when it comes to smaller businesses in particular. They don't have time to invest to understand all of the details of SEO and all of the details of what you should and shouldn't be doing. They worry about their business primarily. So they'll do weird things, like in the past, they would do a lot of hidden text, or kind of stuff things into the footer of their pages because they heard that that works.  

#### [0:33:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=1980) |  And our algorithms, when they run across

these kinds of issues, one of the things we try to do is to ignore this kind of activity and say, well, we don't know for sure that they did this on purpose, so we will try to ignore it, and we'll try to evaluate the site based on the other factors that we have there. So that might be playing a role there. I know there are probably some niches where people are doing everything to push the boundaries,  

#### [0:33:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2010) |  so that might be something, in particular

where you're active, maybe that's slightly different. If you do find situations where there are really larger schemes, larger level schemes at play where you think that maybe the web spam report isn't a good way to specify that, you can also send that to me directly, and I'll take a look at that with the web spam team to make sure that we're really covering that properly. In general, they do look at the web spam reports and they do try to take appropriate action where  

#### [0:34:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2040) |  they think that's necessary. So kind of

going back to the starting point, if we recognize, or if the web spam team recognizes that our algorithms are already ignoring these, then maybe there is nothing extra that they need to do. On the other hand, if they recognize that our algorithms are picking these up in a way that they shouldn't be picking it up, then maybe they will take manual action to make sure that those kind of links are neutralized.  

#### [0:34:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2070) |  We have a page which downloads certain

content with JavaScript's calls to the server on page load. If the Ajax requests that we do are blocked by robots.txt, will Googlebot be able to see this content on the second wave of indexing? No. We need to be able to access the JavaScript files and the server end points that you're using for these kind of Ajax requests if there's content that you're pulling in that way that you want to have indexed.  

#### [0:35:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2100) |  So we need to be able to

access those things, if that's something that you want to have indexed. When keeping URLs simple, is it OK to have a URL to be longer with the top level page-- for example, slash services categories slash service type name-- or should it be kept short, with just slash service type name? That's totally up to you. You can have longer URLs or shorter URLs.  

#### [0:35:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2130) |  You can have multiple folders with slashes

in between those URLs. That's totally up to you. It's not something that you need to artificially shorten or artificially make longer. The limit that we have, I think, is something like 2,000 characters. So that's something that pretty much no site runs into accidentally when they're just creating URLs manually.  

#### [0:36:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2160) |  Then let's see. There's a fairly long

question about a specific medical site, and also with regards to the algorithm updates that we had there. So I haven't been able to take a look at the site specifically, but I would really take a look at the blog post that we did on the core algorithm updates a while back  

#### [0:36:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2190) |  and look at the kind of things

that we try to keep in mind when it comes to medical sites, or when it comes to sites in general. Also, the Quality Rater Guidelines are a good thing to go through, specifically with regards to medical sites, to kind of understand a little bit better what we're looking at or what we recommend our quality raters look at. So just to clarify, the quality raters don't make the rankings. They help us to improve our algorithms, though.  

#### [0:37:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2220) |  Two niche questions about country-restricted websites due

to legal purposes. When using tools like PageSpeed Insights or Structured Data Testing Tool, both seem to be coming from external country IPs and are restricted from accessing the site. Is there a list of IP addresses that we could whitelist? I'm not aware of any list of IP addresses  

#### [0:37:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2250) |  specifically for those tools. So with Googlebot,

you can confirm the IP address using a reverse DNS lookup, but specifically for those tools I, don't think they would use the same Googlebot IP addresses. So that's kind of tricky. How could you test those? I guess one way to test that is to create separate test pages that are accessible and to see what IP addresses  

#### [0:38:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2280) |  those requests are coming from. There are

hreflang tags that redirect each user to the appropriate TLD website based on their country to avoid restrictions. There is also a single page dot com website. The website is the x-default hreflang of all websites, but only in their home page. Is this the right way, or should we--  

#### [0:38:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2310) |  should this be x-default for all pages?

I would try it out. I think it'll be kind of tricky in general when you're restricting access on a per country basis. On the one hand, for Googlebot it might be tricky, because if you're blocking users from the US, then that would include blocking Googlebot. So it would limit the number of pages or the exact pages  

#### [0:39:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2340) |  that we could actually look at there.

But I would try this out. I think in general, having the hreflang across different country versions, different TLDs is-- that's a perfectly fine, accepted approach. Having the hreflang only on the home page is also perfectly fine, acceptable. Using the x-default to have a default page that is valid for all users that are not within the countries that you're specifically showing individual pages for  

#### [0:39:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2370) |  is also acceptable. We're a news website

and we use news.xml sitemap for discoverability and indexing. But as a news organization, we have to update our stories with more facts and information as the story develops. And I think it kind of goes in a direction of, how do we make sure that these updates are also processed  

#### [0:40:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2400) |  as quickly as possible? So I'm not

aware of anything specific that you could do to make it so that we pick up these updates faster. Essentially, using a second file with the last modification date, that's a great way to do it. Using a RSS Atom feed with the last modification date is really useful. The-- both the new sitemap on the Atom feed are useful because they're just focused  

#### [0:40:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2430) |  on the new URLs for your website,

or the new and changed URLs on your website. We don't have anything like an indexing API, where you can push changes through this. Why does a website's rankings bounce back? I don't know. It really kind of depends on the website. So there are different things that can play a role there. On the one hand, our ranking algorithms can change,  

#### [0:41:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2460) |  so it's something where it's possible that

our algorithms will say that, like, one site we don't really trust that much, or we don't know if we can trust it that much and we'll be a little bit more critical. And the next time around, when our algorithms look at it again, they might say, oh, well, actually, it's a good site. We should trust it a lot more and show it more in Search. And then you might see some fluctuations like that. On the other hand, it might be that within your website,  

#### [0:41:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2490) |  things change, and that could be a

sign for us that oh, there's something different here. We should perhaps reconsider how we were showing it in Search. And of course, there are the situations where something changes in the rest of the web, where suddenly we look at other websites and say, well, actually, they weren't as great as we originally thought. We'll show them a bit lower. And then suddenly, those that were below those start showing up a little bit higher. And all of these things are essentially  

#### [0:42:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2520) |  a normal part of Search. We're constantly

working on our algorithms to try to improve them. We constantly work to try to understand websites better, and because of that, you will almost certainly see fluctuations across different things in Search. Is there any means to request Google crawling from another country other than the US? No. We primarily crawl from the US. There are very few exceptions, and for those exceptions,  

#### [0:42:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2550) |  it's a very small number of countries,

and it's something that would be essentially limited to websites in those countries. So for the most part, we do crawl websites from the US. Please remove YouTube from Google Search. Let YouTubers compete with each other and let websites compete with websites. It's not fair when I write a 4,000-word article covering  

#### [0:43:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2580) |  every aspect of a topic and then

get over-ranked by a 500-word article, just because his website has more authority. So I think first of all, I'm quite happy with having different kinds of search results in Google Search, and that includes sites like YouTube. That includes other video sites. That includes image sites. All of these things bring diversity into the search results.  

![](https://i.ytimg.com/vi/Cr3muqj-RKQ/maxres3.jpg)



#### [0:43:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2610) |  They bring a diverse set of viewpoints

to users in Search, and they're different ways of finding relevant content. So some people like to find content on video. Some people like to find content in text form. Some people don't know what they're looking for for a specific query and then they get surprised by one or the other. I think all of that is essentially fine. The other thing is with regards to the number of words in your article, the number of words on a page  

#### [0:44:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2640) |  are not a factor that we would

use for ranking. So just because you have 4,000 words and someone has 500 words doesn't mean that your page is automatically more relevant than another page. So instead of accounting-- kind of focusing on word count, I would really try to focus on the quality of the content that you're providing and the consistent quality. So if you're working on a website and you're creating one article after another, make sure that you're really hitting the bar that you want to reach and maybe instead of writing one extra article,  

#### [0:44:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2670) |  think about ways that you can make

sure that anything that you create on your website is of the highest quality possible and is, in a way, something that clearly should be ranking number 1 by far for the things that you're targeting. So not just, like, am I kind of doing the same thing as other people, but really making sure that when someone objectively looks at these search results, they say, well, this article is fantastic,  

#### [0:45:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2700) |  and it should clearly rank above all

of the other ones. And that's kind of the level that you should be aiming for. And at that point, that sometimes also means maybe you should be including video content. Maybe you should be including more images. Maybe sometimes articles need fewer words. Sometimes they need more words. That's something where just purely the word count alone is not really the measure that you should be aiming for. I have a website in Angular where previously, I  

#### [0:45:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2730) |  had URLs getting indexed through the escaped

fragment version of the page. However, due to some technical issues, the escaped fragment version was removed, and now the same page is not getting indexed, though I've tried submitting the same using Search Console. What's an alternative to getting my page indexed? So there are a few things going on in this question. And I think what--  

#### [0:46:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2760) |  instead of trying to answer all of

the different things here, I would double check kind of the technical setup that you have there to make sure that things can actually get indexed. So you can use things like the Inspect URL tool to double check and make sure that you have actual URLs on the page and not just hash fragments that you're trying to index. And most of all, especially for JavaScript sites, I would recommend taking a look at our documentation.  

#### [0:46:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2790) |  We have fairly extensive documentation on JavaScript

sites now. We have a set of videos on YouTube for JavaScript sites. So I would kind of make sure that you have all of the technical basics set up there properly. It's easy to say, well, it kind of worked in the past, therefore I just want it to work again. But especially with JavaScript sites, you need to make sure that you're doing things properly so that we can actually render and index the content there  

#### [0:47:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2820) |  accordingly. And if you are doing things

properly, then that's something where the sites can show up in Search normally, too. Whew. Wow, OK. Running out of voice, almost. What kind of questions are on your minds? What am I missing? Oh, wow, lots of stuff happening in the chat.  

#### [0:47:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2850) |  Long questions, at least. We're facing an

issue for one of our clients, where two similar pages were made live and submitted for indexing at the same time. One got crawled and indexed and now is ranking well. The other is still unindexed no matter what we tried. We checked robots.txt, meta robots, no issue. Submitted in sitemaps, submitted feedback in Search Console but in vain. Can you help to understand what might be the issue? So I would double check in the Inspect URL tool  

#### [0:48:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2880) |  to see what the status is there.

Oftentimes, it will tell you what is happening, why a page is not being indexed. So that's something where maybe you can find more information there. It's kind of hard to say, without looking at the URLs, what exactly is going on there. If you have a bit of time afterwards, we can take a quick look. I have a bit more time afterwards.  

#### [0:48:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2910) |  I'll pause the recording at some point.

But we can double check that afterwards if you want. Any other questions from any of you in the meantime? Wow, no more questions. OK. GAL SHALOM: Actually, I do have a question. JOHN MUELLER: OK. GAL SHALOM: So some of the backlinks to our website  

#### [0:49:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2940) |  are not showing up in the Search

Console in the Links section, and I wanted to know if that means that they're not passing any signals if they don't show up in that list. And they're from big, authoritative sites. JOHN MUELLER: Yeah. We try to show a relevant sample in Search Console, but we don't show all of the links that we have there. So if these are normal links that you know exist to your website, then I would assume that we can pick those up.  

#### [0:49:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=2970) |  Similarly, what's also sometimes confusing is if

a link has a no follow or is in a disavow file, we'll still show that in Search Console if we think it's, like, one of these sample links that we should show. GAL SHALOM: OK. Now do links expire after a while? I mean, the signals that they're passing? JOHN MUELLER: No, no. They don't expire. What does happen, though, is that, especially if you're talking about a large website that's  

#### [0:50:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=3000) |  growing regularly, then the pages that links

are on-- over time, they get even deeper and deeper within this website. So for example, if you have a link from CNN and it's in an article that's linked on the home page, then that's something that's really important for us. On the other hand, if this article is maybe a year or two later-- it's somewhere in the archive at CNN-- then that article itself is not something that we would find that important anymore. So it's not that the link expires  

#### [0:50:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=3030) |  after a certain period of time, but

just often that the page where that link is on that becomes less and less relevant over time if it's on a site that is growing fairly regularly. GAL SHALOM: OK. But given that the page doesn't change, or if it's on an important page in a website, then it shouldn't have any different effects over time. JOHN MUELLER: Exactly, yeah. GAL SHALOM: OK. And I have another quick question. So we've been getting some new backlinks recently, and we have seen our ranking increase in search  

#### [0:51:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=3060) |  in the Console. But we haven't seen

any difference in the actual Search, and there hasn't been any change in-- we haven't seen any increase in traffic to the website. We were wondering why is that happening. JOHN MUELLER: That's hard to say offhand, but in general, one thing to keep in mind  

#### [0:51:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=3090) |  is that the ranking is-- that we

show in Search Console is, on the one hand, based on what was actually shown to users. And on the other hand, it's essentially based on that search results page that we would show to users. And sometimes what you'll see is that a site goes maybe from number 10 to number 8 or something like that, and that might be something that's a little bit more visible to users in Search, but it's still not something where you would immediately get a lot more traffic from.  

#### [0:52:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=3120) |  GAL SHALOM: But-- yeah, sorry. JOHN MUELLER:

And the other thing is that sometimes the title and the snippet that we show in the search results doesn't match what the user is exactly looking for. So it might be ranking higher for certain queries, but if users are looking for something different for those queries, then it wouldn't necessarily mean that you'd see more traffic. GAL SHALOM: Mm-hmm, I see. OK, thank you. JOHN MUELLER: Sure. ANDREA MORO: Hey, John. JOHN MUELLER: Hi.  

#### [0:52:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=3150) |  ANDREA MORO: Hi. [INAUDIBLE] to the [INAUDIBLE]

Search Console. So and really would like to understand, I think, more about your take on Google [INAUDIBLE] in general. Because you know, whilst causing the search on [? Linux ?] more often than not by filtering for queries, pages, or whatever, right? You know, if I say I want to include the terms XYZ and then I get some kind of numbers, then if I say, OK, give me all the numbers without the terms ABC  

#### [0:53:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=3180) |  or whatever it was in the previous

example, the numbers never match. So I totally appreciate that you say, OK, we do normalize data, we do certain times exclude X because of whatever reason-- privacy, da-da-da-- but you know, my question in reality is, OK, if you do that kind of discrepancy and i.e. can see discrepancy up to 60%, 70% of the numbers, how would you expect as a [? working ?] industry taking the tool seriously for measurement?  

#### [0:53:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=3210) |  Because we kind of really rely on

such a data if you skew too much. You know, I kind of understand it for privacy. You know, you can say, OK, well, let's take out 2%, 3%, 5%, in terms of certain condition for ourselves. Doesn't really make sense for you to be seeing. Fair enough. You know, 5, 6 is OK. 70-- or 60%, 70%, it's a bit too much. JOHN MUELLER: I guess it all depends on the kind of site and the kind of queries and the level of queries  

#### [0:54:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=3240) |  that you're looking at there. So that's

something for-- for some sites, depending on what you're searching for, you might see bigger changes if you start doing things like including and excluding things. For other sites, you'll see smaller changes. So what I would recommend doing there, instead of using the filters to kind of try to tweak things like this, is just to export the list and work with the list of queries or the list of URLs and the clicks, impressions,  

#### [0:54:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=3270) |  and position that you have there, and

work with those directly. So doing something in a spreadsheet or a database, pulling them out with the API, for example, and focusing on the data there. That's something that makes it a little bit more deterministic, what you're working with, because then you know what the full set is. ANDREA MORO: Yeah, OK. Yeah. It makes sense just using the raw data  

#### [0:55:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=3300) |  at that point in time, which is

something that I have been doing in any case. I was just a bit more concerned about the general average of users, or even when it comes to some stakeholders, that they just don't really have time and patience to wait for you to elaborate on data with a database or whatever other tools you may think about, and they just jump straight on the Google Search Console and say, OK, let's have a look on how we've been [INAUDIBLE] over here. And you know, the numbers didn't really play well.  

#### [0:55:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=3330) |  So then you have a double challenge--

not only finishing the job as [INAUDIBLE] and completion, but also demonstrating there that the Google Search Console is actually wrong, because it's such a [INAUDIBLE] discrepancy, who's going to be then on the right side? You elaborating on the API or Google cutting the tool? You know what I mean? JOHN MUELLER: Well, I guess it all depends on the site and what you're looking at there now. ANDREA MORO: Well, it's not on the site.  

#### [0:56:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=3360) |  Just trying to put-- you know, in

[? saying ?] [? whatever ?] boss choose, right? You know, you are the employee. I'm the boss, and you know, I'm jumping on Google Search Console this morning. I say, OK, give me query x, minus X, traffic X. And you know, you employee, you have been told [INAUDIBLE] for a week or a month that you've been playing against the optimization of a certain page or certain sets of pages to optimize them, right? Great. And you have told me, oh, you know,  

#### [0:56:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=3390) |  boss, I've done such a magnificent job

over here and I've got so great results. And then I jump in on the Search Console and [INAUDIBLE] over here it says that you just brought me, I don't know, 10K traffic, right, irrespective of the websites. And you know and-- JOHN MUELLER: I don't know if that-- I don't know if that's really a reasonable comparison. Because on the one hand, if you're doing all of these kind of crazy comparisons with like plus or minus, then that's a fairly advanced usage.  

#### [0:57:00](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=3420) |  On the other hand, if you're looking

at changes, then those trends would be visible regardless. So that's something where it's like, sure, the absolute number might be different if you're doing this kind of complex query. But if you're looking at it over time, that's something where I totally expect to see reasonable results there. And I don't see this changing at any point in the future. So it's not like we wouldn't be able to show the queries that we're filtering out for privacy reasons. That's not going to happen.  

#### [0:57:30](https://www.youtube.com/watch?v=Cr3muqj-RKQ&t=3450) |  ANDREA MORO: All right. Well, thank you.

JOHN MUELLER: Sure. All right. Let's take a break here. I'll pause the recording. And if any of you want to stick around, and I think that one URL, I'm happy to take a look at that, too. And otherwise, I wish you all a great weekend, and hope to see you all again in one of the future Hangouts. Bye, everyone.  