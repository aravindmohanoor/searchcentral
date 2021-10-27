[![English Google SEO office-hours from February 19, 2021](https://i.ytimg.com/vi/zCV6tEt3w0k/hqdefault.jpg)](https://www.youtube.com/watch?v=zCV6tEt3w0k)

## English Google SEO office-hours from February 19, 2021

This is a recording of the Google SEO office-hours hangout from February 19, 2021. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Find out more at https://developers.google.com/search/events/join-office-hours



Feel free to join us - we welcome webmasters of all levels!



#### [0:00:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=0) |  JOHN MUELLER: All right, welcome everyone to

today's Google Search Central SEO office hours. My name is John Mueller. I'm a Search Advocate on the Search Relations team at Google. And part of what we do are these office hour Hangouts where people can join in and ask their questions around Google Search. And hopefully we can find some answers along the way. Lots of stuff was submitted already on YouTube. So we can go through some of that. But as always, if any of you want  

#### [0:00:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=30) |  to get started with the first question,

you're welcome to jump in. PRAVEEN SHARMA: Hey, John. Can I start? JOHN MUELLER: Sure. PRAVEEN SHARMA: OK, so you might have answered this question in one of the previous meetings, but somehow I missed it. This is related to code [INAUDIBLE].. I just wanted to ask [INAUDIBLE] is going to impact a website on the domain level or the page level? Like, for example, there is a website with 20 pages with good [INAUDIBLE] score and then there are other 20 pages of average to poor score.  

#### [0:01:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=60) |  So these [INAUDIBLE] can impact ranking for

these good pages, also? JOHN MUELLER: Good question. So the Chrome User Experience report data is available on different levels. So that's something where, depending on the website, the amount of data that we have available to work with, then we might be able to be more fine grained or we might just have one score that we need to use across the whole site. And you can see some of that in Search Console  

#### [0:01:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=90) |  directly, where you see kind of how

many pages are grouped together in this one data point that you have? PRAVEEN SHARMA: So this domain, does it include subdomains also, or subdomain is separate thing? JOHN MUELLER: As far as I recall, the CrUX data is kept on an origin level. So for Chrome, the origin is the hostname, which would be kind of on a subdomain and protocol level.  

#### [0:02:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=120) |  So if you have different subdomains, those

would be treated separately. PRAVEEN SHARMA: OK. Thank you. JOHN MUELLER: Sure. All right, Lee, I think you raised your hand. LEE ELLIOTT: Yeah. And this might be a silly question, and maybe one that you've covered beforehand. But I work with a company that has a very large footprint on the internet. We have over 100 million pages that we're  

#### [0:02:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=150) |  trying to have indexed. And obviously, that's

a struggle. But in Google Search Console, we have submitted a site map index with over 1,000 different site maps contained therein. Currently, in Google Search Console, it is saying that we have submitted and indexed three million pages. However, when I look at the site map coverage, under that site  

#### [0:03:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=180) |  map index, it is only saying that

it has indexed 40,000 pages. And it's only recognizing one file out of the 1,000 site maps in that site map index. So there's some discrepancy there because that one site map that it's recognizing only contains 40,000 files. My question is, we have some issues with Google crawling our site and returning server errors, like 500  

#### [0:03:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=210) |  errors and some soft 404s. Would that

contribute to Google stopping crawling or not recognizing our site maps because it's getting stalled up somewhere? Like, I guess I'm just a little bit confused as to where to go from here as far as next steps. JOHN MUELLER: Yeah. I am not 100% sure. But I suspect in Search Console maybe  

#### [0:04:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=240) |  you're just seeing a part of the

picture because of the way that the site map files within the site map index files are treated there. So that's something where maybe you're just seeing one of those site map files in Search Console. But actually, if you added the site map files individually, you could probably see data for the other ones. LEE ELLIOTT: Got it. OK. JOHN MUELLER: And that's more of a reporting thing rather than an indexing thing. So it's more that you just don't see the details there.  

#### [0:04:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=270) |  LEE ELLIOTT: Sure. OK. JOHN MUELLER: With

regards to crawling in general, with a really large website-- it sounds like that's the case there-- it is kind of helpful for us to be able to crawl as much as possible. And that kind of flows into the general topic of crawl budget. So there was a blog post, I think, now maybe three years back from Gary about crawl budget  

#### [0:05:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=300) |  kind of going into the different aspects

that we take into account there. And on the one hand, we have kind of the crawl demand from our systems, where we think, oh, this is a fantastic site. We need to crawl as much as possible from it. And with a really large website, sometimes we have mixed signals there. Sometimes it's like, oh, there's a lot of content here. But actually, we've found it's not as useful. So maybe we don't crawl as much. I don't know if that plays a role there. And the other side--  

#### [0:05:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=330) |  OK. The other side is kind of

the technical aspect that we don't want to cause problems on the server. And that's kind of something where things like server errors flow in where kind of the delay on the responses from the server flows in, where if we see-- when we crawl a certain amount of pages per day that the number of server error goes up, then we'll back off and we'll kind of assume, oh, maybe we're crawling too hard  

#### [0:06:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=360) |  and causing these problems. And we want

to leave capacity for users, too. So we will back off a little bit. And similar with server response time. So the rendering side-- kind of the speed aspect that most people focus on-- is usually less critical when it comes to crawling. But the response time, like how quickly does a server respond to requests, that's something  

#### [0:06:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=390) |  that, kind of on a technical level,

slows us down from crawling. LEE ELLIOTT: Got it. OK. Well, thank you for the insight on that. I do appreciate it. JOHN MUELLER: All right. Michael, I think you have your hand raised, too. MICHAEL LEWITTES: Yeah, so I often notice that an established outlet will republish a wire story's article, such as Reuters, and then they'll leap frog in Search the original wire service, whether it's Reuters or Associated Press.  

#### [0:07:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=420) |  All those services aren't spammy. They're very

trustworthy. What factors would contribute to that happening? JOHN MUELLER: I don't know. It's hard to say. I think in most cases, we try to recognize situations where exactly the same article is just being republished and then to kind of treat that accordingly in Search by showing maybe the original or the one that we  

#### [0:07:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=450) |  think where it might have come from.

But there are lots of cases where we can't really recognize that completely. And then it's sometimes a matter of, well, this content is here, but someone also wrote about the same topic somewhere else. And then we kind of have those two viewpoints. So that's something where it's not-- I don't think there's anything technical or anything specific  

#### [0:08:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=480) |  that is happening there where it's like,

well, if it gets republished here, then we just take that one. But any time you have content that is syndicated, it can happen that our systems don't recognize that it's-- like, we should be showing this version instead of the other version. ROBB YOUNG: Is there any difference between a press release and any other type of content publishing? It's just content, isn't it? JOHN MUELLER: Yeah.  

#### [0:08:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=510) |  Usually it's just content. I think, to

some extent, we probably try to recognize press releases and understand that these are pieces of content that are just republished in lots of places and to try to act accordingly for that. But otherwise, it's just content. It's kind of like, if I write a blog post or a news article, it's essentially a piece of content for us.  

#### [0:09:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=540) |  ROBB YOUNG: The nature of press releases

is that you want it to be somewhere else. I mean, the whole point of releasing a press release is that it goes out into the world where people actually read it. No one goes to Reuters to read the news. If there's a new iPhone released, for example, which is always the most popular example, you go to all of the bloggers and tech reviewers and Apple itself to read that. So it's the very nature of a press release that you send it out into the wild,  

#### [0:09:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=570) |  hoping that people will read it elsewhere.

JOHN MUELLER: Yeah. I don't know if Google News does something slightly different than the web search in that regard, though. So that might be something that also kind of plays in there. I know from-- I don't know-- some book about Google a long time back where, in the early days of Google News, they definitely tried to recognize a situation where people were writing about the same topic  

#### [0:10:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=600) |  or writing with the same content and

trying to understand, does that make this topic or this article more important than other topics? But within Web Search, it is really mostly a matter of-- these are different HTML pages, essentially, and we find content there and we try to index it. RICHARD HEARNE: John, quick question. Just jumping in first to say hello, long time no see. Just while you're talking about syndication, how might geolocation come into that if people are syndicating,  

#### [0:10:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=630) |  let's say, in an English article across

different locales-- Australia, US, Great Britain-- could there be an impact there with geolocation also on that? JOHN MUELLER: I suspect that could be the case, yeah. I mean, when there are situations where we recognize that people are searching for a piece of text that's included in a lot of other articles, then we try to pick which one is the most relevant one for the user. And if we recognize that there are some pages or sites that  

#### [0:11:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=660) |  are particularly relevant for users in some

locations, then that's something that we might highlight there. So that could also be playing a role there a little bit. I don't know. If something is originally released in the US and a UK news site picks it up and you're also located in the UK, then maybe you would see the UK news site. All right.  

#### [0:11:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=690) |  Robin? ROBIN FREDMAN: Yes, hello. So we

have a bit of a conundrum here. I just posted a question in the comments, but I don't think you have responded yet. I joined seven minutes late. Sorry. So we have a big site with a global footprint and a lot of different English variant language sites which are located in different subdirectories on our domain. And we are using self-referencing canonicals  

#### [0:12:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=720) |  and the correct href link tags for

each of the countries. So we are specifying that the Australian site, for example, is using Australian English. It is the fact that we do have a bit-- since the sites are virtually copies of each other, we are using one English language [INAUDIBLE] and then allowing each country to localize the country as they see fit. But in most cases, they don't do that,  

#### [0:12:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=750) |  because we have, for example, product pages

which are identical in all countries. So we can see in Google Search Console that there are a lot of exceptions due to Google either choosing another canonical than the one that we have specified-- so initially, we thought this would be a huge problem because we would not have any visibility, any local visibility. But I have done some tests where I either  

#### [0:13:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=780) |  tried to use an Australian IP to

Google on-- Google.com.au. And the same for the American site. And I still get the US sites for pages which shouldn't be indexed. So the pages in the index are indexed according to Search Console. But it still is the URL in Google Search, which is a bit strange. So my question is basically twofold.  

![](https://i.ytimg.com/vi/zCV6tEt3w0k/hq1.jpg)



#### [0:13:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=810) |  Is there any way we can get

around-- so we could have our pages indexed without Google Search Console complaining too much, even though the sites are technically duplicates? And if we can't do that, how is Google evaluating the ranking? Because I think that-- I mean, some domains will have more links, for example, external links. The American site is much bigger than the Philippines site,  

#### [0:14:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=840) |  for example. And so the American site

would have much more links to it. If that page is not indexed but the Philippines page is the one that is indexed, my theory is that the Philippine version would have a lower level Google rank, even though-- but it's the one that's the template for our rank on the Search Results page, even though it displays the America page. JOHN MUELLER: Yeah.  

#### [0:14:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=870) |  I think this is a super complicated

topic. And we make it extra complicated, I think, in Search Console, unfortunately. So it makes it-- I don't know, super confusing. So basically, what is happening is we're recognizing that-- I don't know your site, so I don't know 100% sure if this is actually the case. But usually, this is what happens. We recognize that the content is the same.  

#### [0:15:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=900) |  So you have the same English language

content, maybe for, I don't know, Australia, New Zealand, or something like that. And our systems will then understand that these are duplicates, put them into one cluster. And then we will pick one canonical URL to use for indexing for that. We do pick up the href lang annotations on these pages. So we understand the connections between the URLs. But we still index them as one canonical URL.  

#### [0:15:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=930) |  And in the Search Results, when you

search, if we understand the href langs properly, then we will show the appropriate local URL in the search results. But we will base it on the canonical indexed version. So in the snippet, you might see kind of signs that, oh, this is that canonical version. But the URL should be the right one. And the ranking should be based on whatever for that local URL  

#### [0:16:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=960) |  should be relevant. So it's not the

case that we would pick-- like, if we had the Philippine version as canonical and all the links go to the US version, then when we put them into a cluster for canonicalization, and then essentially whoever is shown gets those links. So it's not that those get lost. But the tricky part is, in Search Console, we report on the canonical URLs, for the most part.  

#### [0:16:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=990) |  So in both the Index Coverage Report

and in the Performance Report, we will simplify things for you and show the canonical URL. So if, in Australia, like-- well, take, for example, the situation where you have the Philippine and the US site and we pick the Philippine version as canonical for whatever reason. In the US, you would probably still see the US URL if we understand href lang properly. But in Search Console, we would report that  

#### [0:17:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1020) |  as being the Philippine URL. So in

the performance report, it'll say, like, oh, the Philippine URL is very popular. And you look at the details in Search Console, going to say, it's popular in all of these countries where it's kind of the same content that's being shown just with the local country versions. And similar in the index coverage report, we'll focus on the canonical URL. So if you have, say, a separate subdirectory for US,  

#### [0:17:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1050) |  then it would look like maybe the

US version is not getting indexed at all, but the Philippine version is getting indexed. And that can be very confusing. But essentially, from a ranking point of view, that should be working out. So if we understand the href lang, we'll show the right version. It'll rank accordingly in Search. Everything with Search Console with the tracking there is super complicated.  

#### [0:18:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1080) |  We see this a lot more in

Europe with German language content, where the German language countries are right next to each other. And in Switzerland, we have different currencies and we can't kind of import things from Europe, all of those weird extra situations. And still, we kind of have that canonical issue there, as well. So it's not just specific to English things there.  

#### [0:18:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1110) |  I don't see this changing in Search

Console in the near future. So that's kind of something where you have to keep that in mind and understand that for your content, one version is being chosen as canonical and the reports that you see in Search Console, you kind of have to pick them apart and try to understand them on your own. To avoid that, the only thing you can really do is make sure that these pages are not recognized as duplicates, which would be to make sure  

#### [0:19:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1140) |  that they're really significantly localized, which, if

it's an e-commerce site and you have the same product across all of these different country versions, that's probably not that feasible. If it's mostly content that you have there and it's not a lot of pages, then maybe that is something that you could be doing. So those are kind of the options there. ROBIN FREDMAN: OK. Thank you very much. I think our worst worry was that our ranking was  

#### [0:19:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1170) |  negatively impacted. But I did find that

one of my UK colleagues sent me a couple of URLs for changing. And I think he Googled it, because he did not send the UK versions. He sent me the Philippine versions. That's why I use that as an example. Is there any way to help Google even more beyond the href lang tag to understand that these are really localized pages? JOHN MUELLER: Not really. Not really.  

#### [0:20:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1200) |  I think also with href lang-- especially

if you have a lot of different country versions-- then it is something that sometimes we pick it up properly. And sometimes we struggle with it. So that's something where anyone who has, I don't know, worked on bigger international sites, you'll see that lots of href lang gets picked up and used. And then some parts, just, like, Google gets confused and shows the wrong version. ROBIN FREDMAN: Yeah, I think we have, like, 30 English versions and 10 or so Spanish. No, even more Spanish.  

#### [0:20:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1230) |  15 versions or something like that Spanish.

JOHN MUELLER: I mean, one thing that I usually recommend is to assume that users might be going to the wrong version on your site and to try to catch them on your site, as well. So show something like a banner on top and it's like, hey, it looks like you're from the UK. Do you want the UK version? And make it so that they can get there fairly quickly. ROBIN FREDMAN: OK. Yeah, thank you. Yeah, we've thought of that, but we wanted to know if our ranking, foremost, was negatively  

#### [0:21:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1260) |  impacted before we did that type of

action. Thank you very much. JOHN MUELLER: Sure. Let me run through some of the submitted questions. And I'll get back to everyone who is raising hands, as well, later on. Don't worry. Let's see. I'm working on the biggest mom advice site in our country, which was demoted with a core update. They have a great brand, search, and a community of loyal returning users. So my approach is going through the content that  

#### [0:21:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1290) |  is deemed the most relevant in Google

for queries from Search Console and making sure that when users come, the content is the highest quality content, solves the need behind the query, and is trustworthy. Is that the right approach? I think, in general, that's a great approach. And that's, especially when you have a larger website, you can't do everything at the same time, but focusing on the parts that are seen as the most relevant for your website, that are kind of the most important gateways to your content,  

#### [0:22:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1320) |  I think that always makes sense. So

that seems like a good approach. There are various people within the SEO community who have kind of focused on the whole topic of EAT, Expertise Authority Trustworthiness. And they've written lots of really interesting blog posts and case studies. So I would also go through a lot of that just to make sure that you're not missing anything obvious that might be relevant for your site, as well.  

#### [0:22:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1350) |  Core Web Vitals and subdomains, I think

we've talked about that briefly. The Chrome User Experience report data is based on kind of the browser origin, which is the hostname. So it would be separate for a subdomain. How long does it usually take to show a Web Story in Discover after creating it? The answer is, it depends, unfortunately. So it's something where sometimes we  

#### [0:23:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1380) |  can pick up content very quickly after

it was created and crawl it very quickly, index it very quickly. Sometimes all of that takes a lot longer. And Discover, in particular, is yet another level on top of that, because for Discover, we want to make sure that we're actually recommending something that is really appropriate for users, because users are not searching for something specifically. So we have to be kind of almost extra  

#### [0:23:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1410) |  careful with regards to the content that

we show in Discover. So there, in particular, it can happen that it takes a little bit longer for it to start showing up in Discover. It can also happen that it is never shown in Discover. So it's not the case that all Web Stories are shown in Discover. What would be the difference between the new passage ranking algorithm and the current featured snippet?  

#### [0:24:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1440) |  From my understanding, is kind of the

UI part of this is completely separate from the ranking aspect there. When it comes to passage ranking, it's more a matter of us going into the content and recognizing that this page is relevant for something that is kind of hidden away on the bottom of the page. And then how we display it in the search results is a completely different question. So it's not that the featured snippet or longer snippet  

#### [0:24:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1470) |  or anything like that would be tied

to the way that we do ranking for those pages. What's the best practice of guest posting, and is it recommended by Google? Oh my gosh. OK. So from our point of view, it's fine to go off and promote your content on other people's sites. So if you're creating content and you're publishing it on other sites to kind of draw awareness to your website, to what you're working on, that's perfectly fine.  

#### [0:25:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1500) |  It's just the links within these guest

posts should be nofollowed because essentially you're placing those links on other people's sites. So from our point of view, that's something where you're putting these links on other people's sites so those links should not be passing a new page rank. And that's essentially the main aspect there. So going off and creating something to draw awareness for what you're working on, that's perfectly fine.  

#### [0:25:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1530) |  Just make sure that the links don't

pass any page rank. If we get links from a subdomain, will they count as PBN backlinks? No, not necessarily. So PBNs are Private Blog Networks, which is kind of a technique that, I don't know, some people-- usually spammers-- use to try to create a network of sites that looks natural that all tend to link to something that you care about, with the hope that when Google runs across this  

#### [0:26:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1560) |  it thinks, oh, so many people are

recommending this page. We should show it higher in the search results. And obviously, if you're creating these sites and you're just putting links there, we would see that as web spam, or at least as links that are unnatural, and try to discount those. So from our point of view, links from subdomains are perfectly fine. It's not that we would see subdomains  

#### [0:26:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1590) |  as a private blog network. Sometimes sites

use subdomains. www is a subdomain, technically. And PBN backlinks are essentially something completely separate, where if we understand that this is a part of a private blog network, then we will just discount that by default. And it doesn't matter if it's on a subdomain or on a main domain or anything like that. So those are kind of completely separate things. Just to make it clear, I would not recommend using private blog networks  

#### [0:27:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1620) |  to promote your website, because that's essentially

against our webmaster guidelines. What matters the most, the number of unique referral backlink domains or the total number of blacklinks? So I don't think we differentiate like that in our system. So from my point of view, I would tend not to focus on kind of the total number of links to your site or the total number of domain links  

![](https://i.ytimg.com/vi/zCV6tEt3w0k/hq2.jpg)



#### [0:27:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1650) |  to your website, because we look at

links in a very different way. And we try to understand what is relevant for our website, how much should we weigh these individual links. And the total number doesn't matter at all, because you can go off and create millions of links across millions of websites if you wanted to. And we could just ignore them all. Or there could be one really good link from one website out there that is, for us, a really important sign that we should treat  

#### [0:28:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1680) |  this website as something that is relevant,

because it has that one link-- I don't know, maybe from a big news site's home page, for example. So the total number essentially is completely irrelevant. Do you ever consider content published across various websites sourced from the same press release as duplicate content across those sites? We talked a bit about that in the beginning. Technically, if you're duplicating content,  

#### [0:28:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1710) |  then that is duplicated content. We don't

penalize duplicate content in our algorithms. It's just that we would try to pick one version and show that appropriately. And the other things that we talk about with syndicated content are kind of in the beginning, if you want to watch that on the recording. My home page outranks my internal pages. How can I fix it? It's not necessarily something that you need to fix.  

#### [0:29:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1740) |  So this is something that just happens

sometimes. Sometimes internal pages rank higher than the home pages and people complain about that. But essentially, for individual queries, we try to recognize what is the most relevant result from within your website or across the web? And we try to show that appropriately in the search results. And sometimes that's your home page. Sometimes that's a product page, might be a category page, might be a blog post on your site about a specific product.  

#### [0:29:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1770) |  From our point of view, that's not

something that we would consider something wrong. The thing that you can do a little bit, though, within your website is to help us understand which parts of your website you consider to be the most important. And the best way to do that is with internal linking. So the clearer you can make it to us that this is something that is really important within your website by showing it to users more  

#### [0:30:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1800) |  frequently, having kind of visible links to

that content within your website, the clearer we can understand that this is probably something that you care about and that you want to treat with a little bit more weight. So for example, if you have a lot of products on your website and there's one product that you really care about because maybe it's the product that you're most proud of, or it's the product where you earn the most money from, or whatever reasons, if you have all of your products linked  

#### [0:30:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1830) |  in the same way within your website

that you have different categories and subcategories and then have links to the products, then from our point of view, we can't really tell that this is a really important product, because it's just one out of a thousand other ones that you have on your site. Whereas if you were to go for the forward and specifically link to that product from your home page, for example, from other important pages within your website, then it's a lot easier for us  

#### [0:31:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1860) |  to recognize that, oh, this one particular

product is so much more important for this website than all of these thousands of other products that are on the website. And that way you can kind guide Google to understanding your website and what you consider to be relevant a little bit better. We have a website that we found many spammy sites pointing to in the links section.  

#### [0:31:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1890) |  Is it worth disavowing those domains? We

don't have any manual actions in Search Console. And we think those bad sites are dragging down our traffic. So in general, in cases like this, you don't need to disavow those links. Our systems are really good at understanding which links are relevant and which links we can completely ignore. And there are lots of levels in between, but essentially, random, spammy links pointing to a website  

#### [0:32:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1920) |  is super common. It's something that happens

to pretty much every website out there. And our systems have, I don't know, tens of years of experience with dealing with that and ignoring a lot of that. So offhand, I would not worry about this. If you're seriously worried that these might not be getting picked up properly by Google's systems and you really, really want to make sure that they don't cause any problems, then go ahead and drop them in the disavow file.  

#### [0:32:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1950) |  The disavow file is something we see

more as a technical thing. It's something we look at and we say, oh, you don't want these links? Then fine. We will take them out. It's not something that we would count against your website. It's not something where we would say, oh, this person must have been a spammer because they're trying to disavow all of these links now. It is really just a clean sign for us, like, you don't want those links counted. And so we won't count those.  

#### [0:33:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=1980) |  So if you're really, really worried about

these links and you're losing sleep and you're kind of wondering, is it affecting our rankings? Then just drop those domains in a disavow file and move on. Then you're really, really sure that our systems are ignoring it. For the most part, I think sites don't need to do anything there. If you've had a site on the internet for a while, then you see all of these weird links to your site. And you can assume that Google is pretty good at seeing that, too.  

#### [0:33:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2010) |  During the December update we had a

ranking drop to our game site. This is very surprising, as in my opinion, we have one of the best and most complete experiences for this type of site. While other sites offer mainly questions for the game, we do that, as well as show votes for [INAUDIBLE].. And we even have country-specific data. My question is, was this drop due to something technical such as site speed or hosting, or are we somehow not  

#### [0:34:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2040) |  satisfying users as well as other sites,

or was it a mistake? I don't know. Like, the last part, was it a mistake, I tend to assume that these kind of changes are not mistakes, but they can happen. So if you're really kind of super sure that you've checked everything and you think you've kind of gone through everything with regards to your website, then  

#### [0:34:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2070) |  what I would recommend doing first off

is posting in the Webmaster Help Forum and getting some input from other people there. And the folks in the forums can also escalate that to Googlers, as well. So if there is something really, really weird happening then it's theoretically possible that there's a mistake on our site. I think it's super, super rare. It's extremely rare that I run across something where, when I send it off to the engineering team,  

#### [0:35:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2100) |  they're like, oh, something weird is happening

that we have to fix. But it's theoretically possible. That said, my assumption would be that it's really more tied to other parts of your content, other parts of your website, and trying to understand how we should be showing those-- that content more. So site speed, I suspect, is less of an issue. In particular, the Core Web Vitals are something that we'll start using in May.  

#### [0:35:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2130) |  So that wouldn't be affecting your site

now. It might be that there's some crawling issues if you have a really large website with regards to speed. But it sounds like, if your site has been around for a longer time, then probably we have indexed the appropriate content for your site already. So that's less of an issue. So my assumption would be more in the direction of the content and the way you're providing that content for users. I took a look at a handful of pages from your website  

#### [0:36:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2160) |  and I could see how our algorithms

might be a little bit confused with regards to how we should be showing this site in Search, in particular because on a lot of these pages, there isn't a lot of content there. So that's something where, if I go to random pages on your site, I'll have kind of that card in the center. And essentially, everything else will be ads. And I could imagine that our systems struggle a little bit  

#### [0:36:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2190) |  with understanding, what should this page be

relevant for? So that's something where maybe it's worthwhile to kind of rethink a little bit how you want to be found in Search and how you can put your best foot forward when it comes to being found in Search. One thing might be to think about, like, do you actually need all of these individual pages indexed? Or should you have something more about the content overall  

#### [0:37:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2220) |  itself as an index thing? So maybe

less focusing on individual pages, which just have one or two questions on them, and focusing more on, I don't know, category of items where you have more actual content on a page. How does Google judge to show more images in the Search results in a single blog post?  

#### [0:37:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2250) |  I don't think we have anything specific

in that regard. Sometimes we can pick up images through structured data and we can show those in the search results. But essentially, the algorithms that we have for showing kind of the thumbnails within the individual search results entries are things that are more, I don't know, broader algorithms in terms of us recognizing there are multiple images on a page and kind of making the assumption that maybe  

#### [0:38:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2280) |  these multiple images on a page are

particularly useful or relevant for users to understand why your pages are relevant for the user now and the search results. So that's kind of the direction I would head there. I think there are two or three types of structured data that are slightly different in that regard in that you can provide a carousel of images or carousel of pieces of content. I think something like the "how to" structured data  

#### [0:38:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2310) |  falls into that category, and maybe something

around recipes. I'm not quite sure. But all of that should be documented in our Developer's Guide. And you can kind of look at that to see, is there something specific that you could be doing? My recommendation would be to look into the search results of what your site is focusing on, and then based on that, to try to work backwards. Like, is there a specific type of structured data  

#### [0:39:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2340) |  that these people are using? Or is

this just Google's algorithms trying to be helpful and just show more images? Cool. OK. I think maybe we'll just switch back a little bit to questions from you all, since there seem to be more and more hands being raised. Not quite sure where we were. Rob, were you next? ROBB YOUNG: It says Lee was, but I don't know if it's already been. But I just want to ask about 404 errors in Search Console,  

#### [0:39:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2370) |  or 400 errors in general. Are they

still a thing, because I only see 500 and no 400s, despite having lots of 404s. Are they still reported, or are they moved to some other section? JOHN MUELLER: Good question. I don't know offhand. Yeah. We used to have the Crawl Errors report,  

#### [0:40:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2400) |  but I think some of that was

moved. ROBIN FREDMAN: It's in the excluded, I think. You can find them in the excluded. So they're not errors anymore. They're excluded instead. JOHN MUELLER: Oh, OK. They're in the Index Coverage report, in that case. Yeah. OK. ROBB YOUNG: But could you then drill down and see them? ROBIN FREDMAN: Yeah, if I-- yeah. I'm actually in that report right now because I had to pick out one before.  

#### [0:40:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2430) |  So you can click on the photo

for post in the-- it's like Coverage, then Excluded-- [INTERPOSING VOICES] ROBIN FREDMAN: --click on the 404 and then you can click on Exported. [INTERPOSING VOICES] ROBB YOUNG: Yeah. OK. Thanks, John slash Robin. JOHN MUELLER: Cool. Thanks. ROBB YOUNG: Dude, you always start with an "I don't know" anyway as a disclaimer. JOHN MUELLER: I think-- yeah. I don't know. ROBB YOUNG: See? JOHN MUELLER: Like, these changes in Search Console, it's sometimes hard to keep up.  

#### [0:41:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2460) |  That's why we have Daniel on the

team working directly with Search Console, like-- ROBB YOUNG: OK. That's all from me. JOHN MUELLER: Cool. ROBB YOUNG: Thanks. JOHN MUELLER: Reza? REZA AKBARI: Hi. I have two questions. First, I have a question about these pages that don't have actual content on them. And it doesn't make sense to put--  

![](https://i.ytimg.com/vi/zCV6tEt3w0k/hq3.jpg)



#### [0:41:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2490) |  directly put content on them, like online

tools, online calculators, online translator. They don't actually have content. How can we optimize those pages for Google? I don't know if you should write a blog post and link to them or-- JOHN MUELLER: Sure, yeah. I mean, from our point of view, we don't have a kind of a system that uses online tools  

#### [0:42:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2520) |  and tries to see what they're useful

for. So if you have a calculator on your site, our systems will go and just see, oh, the number of zero through nine and some symbols are on this website. We don't necessarily know that it's a calculator. So anything that you can do to make it easier for us to understand what this page is for, that helps us. So that's something like using clean titles and headings on the page. Having some informational text on the page itself is really useful.  

#### [0:42:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2550) |  If you have a blog where you

can write about these tools, that's obviously also useful, because then we understand a little bit the context of those tools a little bit better. So essentially, anything that you can do to bring more textual information to those tools, that helps us. In particular, if these are tools where you have some functionality that we just don't see because Googlebot doesn't interact with the tool,  

#### [0:43:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2580) |  so if you have something like a

map and you can click on different locations, you can see opening hours for different businesses that you're working with, Googlebot is not going to click on the map and see what happens, but rather, we need to be able to find that information in some textual format in another way. So either having more general information on a page in a case like that would help. Like, these are the opening hours of our different branches.  

#### [0:43:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2610) |  Or even listing that information directly on

the page itself, that also helps us. So if it's like a look up of the opening hours, then maybe just list the addresses along with the map on the page so that users can click on the map if they feel more comfortable with the map, or they can scroll through the list to find that information. So essentially, when you have these kind of online tools, anything that makes it easier for us to understand what we should be showing  

#### [0:44:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2640) |  this page for, that's useful. REZA AKBARI:

Thank you. And the second question is, we had the big news websites and on December update we lost like 50% of the traffic. And mostly that Discover part, it completely suddenly gone away. And we couldn't find out the issue. Can you please explain more about that?  

#### [0:44:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2670) |  JOHN MUELLER: Yeah, I don't know. That's

kind of tricky. So I guess tricky on multiple levels there, because I suspect you're talking about the core update that happened in December. REZA AKBARI: Yes, yes. JOHN MUELLER: So with the core update, it's not so much that we're flagging problems  

#### [0:45:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2700) |  within a website and saying we think

this website is bad or has a problem, but more that we're trying to understand the relevance of these pages a little bit better. And the relevance is something that is tied to so many different factors. And that's essentially what we try to pick up with the core update. And the information from the core update is also used in other parts of Search-- in particular, in Discover, as well.  

#### [0:45:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2730) |  And because of that, it can also

happen that maybe a change is kind of subtle in Search in general, but has a stronger effect in Discover, just because we're a little bit more critical on the Discover side. With regards to kind of improving the situation there, we have a blog post about core updates that has a little bit more background information on the kind of things we look for when we try to understand relevance. I would definitely go through that.  

#### [0:46:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2760) |  It also has a little bit of

information on how things work with regards to recovering after making changes within your website, because from our point of view, it's not the case that a website is doing something wrong that it has to fix when it comes to core updates. But obviously, you want to have similar traffic as before. So improving your website overall, that will help us to better understand how the relevance is kind of better than before  

#### [0:46:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2790) |  for your website. So unfortunately, there is

no one simple thing to focus on there. There are lots of small things that kind of add up. And a lot of that is listed in the blog post, as well. REZA AKBARI: OK. Thank you. JOHN MUELLER: Sure. And Feroz-- I don't know if I'm pronouncing your name properly. FEROZ BUX: Yeah, hi John. JOHN MUELLER: Hi.  

#### [0:47:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2820) |  FEROZ BUX: Actually, I have a question.

One of our client, we are working for him. And I apologize for my English. It is very weak, so please don't mind. So the issue is that a few of the competitors, they have laid some kind of reviews on other websites. So the problem that we are facing right now is that our ORM is not maintained as it was before. So what we did is we asked the websites that were showing up  

#### [0:47:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2850) |  the reviews in Google. But ultimately, the

result is that they are asking for $2,000 to remove those reviews. So I'm not sure that what exactly should we do. JOHN MUELLER: Yeah. I don't know what the best approach is there. I mean, that's something we sometimes hear about, as well.  

#### [0:48:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2880) |  I think the most straightforward approach is

either to find some kind of a solution there in regards to having that content removed if that's something where you think, for legal reasons, they're publishing things that are not correct, then that might be an approach that you could take there. The other approach, in general, with regards to reputation  

#### [0:48:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2910) |  online is to make sure that the

more relevant content is also visible in the search results, which could be something, from your side, that you provide there. So that might be an option there. If this is something where it looks like there's a really big scheme in play with regards to this kind of content, then that might be something that we can pass on to your team here to take a look at  

#### [0:49:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2940) |  and to understand a little bit better.

But I would see that more as kind of a long term approach. So for things like that, I would recommend also maybe posting in the Webmaster Help Forum so that other people can take a look and give you some tips there. I don't think there is one simple answer that you can use in these kind of cases. And it's similar with other situations where maybe there is a legitimate negative review  

#### [0:49:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=2970) |  out there where you can't just force

people to remove negative reviews. But in the Webmaster Help Forum, you'll probably get some input on some options that you can do there. Maybe you'll also get some, I don't know, more straightforward feedback on how, well, maybe you should just be providing a better service, or whatever. But I think this kind of direct and, I don't know,  

#### [0:50:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=3000) |  more or less honest feedback is sometimes

very useful to understand, well, what is the general perception externally with regards to this type of issue? And is it something that I can resolve on my own? Or is it something I need help with from other people? Or do I need to rethink what I am doing with regards to how you're active online? That might be something that also comes into play there. And as I mentioned in the other questions before,  

#### [0:50:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=3030) |  the folks active in the help forums

can also escalate these issues to Googlers. So if they see something that comes up again and again in the forums, from the same sites that are doing similar schemes kind of thing, then they do pass that on to the team here. And we do try to take a look at that. It's sometimes tricky with regards to what we can do in cases like that. In particular, if the website is not spammy, if it's a normal website that we wouldn't remove for web spam,  

#### [0:51:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=3060) |  then there's no kind of web spam

policy reason for us to remove it. There might not be other policy reasons for us to remove it, either. Sometimes it is really quite complicated. But yeah, I think taking the step and getting more input from other people might be a good first step. FEROZ BUX: Thank you so much, John. I have one more question that is-- can I please?  

#### [0:51:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=3090) |  JOHN MUELLER: Sure. FEROZ BUX: Yeah, so

basically, one of our page was not indexing. I don't know the exact reason what it was. So what we did is we started Google Ads for that page. And besides this, we started social sharing. We started to share this on Facebook and other platforms. Now I'm not sure what was the exact reason, but first that page was on third page of Google results.  

#### [0:52:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=3120) |  And now it is under 10. So

I'm a bit confused at what was the exact reason. Was it traffic that matters? Or was it-- JOHN MUELLER: Yeah. So both of those things-- ads and social sharing-- are not things that we take into account for search. So my guess is it's either something-- an indirect side effect of that, or it's  

#### [0:52:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=3150) |  just that our systems decided at some

point that, oh, we should also index this page there. But both the ads and the social sharing side are things that we don't take into account. Traffic in general also not. It's something where various SEOs externally have made tests with regards to traffic to see if traffic can get a page indexed, and that's not the case. So from my point of view, probably it's  

#### [0:53:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=3180) |  just like it was almost indexed and

at some point our system said, OK, we will actually index this page and show it in Search. FEROZ BUX: OK. So it was the hard work of our team. Thanks a lot. JOHN MUELLER: Yeah. All right. Sure. Lene? LENA HEGLAND: Yeah. I'm happy that we got some time. So we have a news website that, in addition to articles, publish a bunch of URLs with short updates,  

#### [0:53:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=3210) |  so not much content. So I'm wondering

if there's a best practice for news websites to avoid thin content and if you would recommend to just noindex all of these URLs to just the short stories. JOHN MUELLER: I mean, if you don't want them showing up in Search, you can use noindex. But I don't think you would need to noindex something just because it's a short news article. Sometimes short articles are completely fine.  

#### [0:54:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=3240) |  So I wouldn't focus so much on

the length of the article, but rather, do you want it indexed or not? LENA HEGLAND: Yeah, we would. But I was just afraid that it will be viewed as short stories because it's just a paragraph, nothing else. JOHN MUELLER: So for Web Search, we don't care about the length of the articles. I don't know if there's any kind of policy thing around Google News. So especially if you mentioned that this is on a news website,  

#### [0:54:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=3270) |  I vaguely recall some errors that we

had in Search Console way in the beginning, where we would show this content, this news article is too long or too short. Maybe that's something that plays a role there with regards to news content. But if that is the case, you can also use the Google News-- Google.news-- meta tag to specifically block it from Google News so that you can keep it shown in search and just block it for Google News.  

#### [0:55:00](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=3300) |  LENA HEGLAND: OK. Thank you. JOHN MUELLER:

Sure. OK. Let me just pause the recording here. I'll stick around a little bit longer for all of the questions that are still pending and if anyone has anything else they want to share. But thanks for joining and watching so long, if you're watching this as a recording. And thanks again for all of the questions that were submitted. And hopefully I'll see you all again in one of the future Hangouts.  

#### [0:55:30](https://www.youtube.com/watch?v=zCV6tEt3w0k&t=3330) |  Bye, everyone. LEE ELLIOTT: Thanks, John. 

