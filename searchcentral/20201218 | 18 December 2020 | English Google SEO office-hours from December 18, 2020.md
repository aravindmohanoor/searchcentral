[![English Google SEO office-hours from December 18, 2020](https://i.ytimg.com/vi/udW8Pc1tpl8/hqdefault.jpg)](https://www.youtube.com/watch?v=udW8Pc1tpl8)

## English Google SEO office-hours from December 18, 2020

This is a recording of the Google SEO office-hours hangout from December 18, 2020. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Find out more at https://developers.google.com/search/events/join-office-hours



Feel free to join us - we welcome webmasters of all levels!



#### [0:00:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=0) |  JOHN MUELLER: All right. Welcome, everyone, to

today's Google SEO Office Hours Hangout. My name is John Mueller. I am a Search Advocate at Google in Switzerland. And part of what we do are these Hangouts where people can join in and ask their questions about their website and web search, and we can try to find some answers for you. Bunch of things were submitted on YouTube already, so we can go through some of those, but we can also go through some of your questions first, if any of you want to step up and mention something  

#### [0:00:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=30) |  that's been on your mind. ROBB YOUNG:

Can I ask a Web Stories question, then? JOHN MUELLER: All right. ROBB YOUNG: The Web Stories follow the same sort of rules in the domain set up. So if we have that content living at forward slash UK, and then a bunch of Web Stories, and then forward slash US, a bunch of Web Stories,  

#### [0:01:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=60) |  is that the best way to handle

that, or can you just have forward slash WebStories, and Google will work out what the best audience is? If we're creating AMP pages specifically for those? JOHN MUELLER: So far geotargeting in particular, or-- ROBB YOUNG: Yeah, yeah, because we'll have-- it'll be on a global site where we'll have US, UK, South Africa, Australia, et cetera. Would you have a central pool of those Web Stories, or would you do them at the domain, country domain level?  

#### [0:01:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=90) |  JOHN MUELLER: I don't know. ROBB YOUNG:

[LAUGHS] OK. JOHN MUELLER: I don't know. So I think Web Stories are only shown as kind of this unique UI thing in certain countries. I don't know if that's in the UK, but it might be UK and the US, something like that. ROBB YOUNG: The "Telegraph" has it, so I assume-- in fact, well, I think the "Telegraph" is one of the examples that they use within the--  

#### [0:02:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=120) |  JOHN MUELLER: OK. ROBB YOUNG: So-- unless

I'm going mad. JOHN MUELLER: OK. Well, then, maybe you're seeing them. Because we don't have them in Switzerland, so I'm just assuming what they will look like. But essentially, for all other countries, we show them as normal web pages. So they're normal AMP pages, and we will index them like normal web pages. So that means any geotargeting that you have there for those pages, depending on where they're located, that would apply there as well.  

#### [0:02:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=150) |  ROBB YOUNG: Right. JOHN MUELLER: But I

don't know how that would apply for the situation when we show them as kind of that Web Story UI in Discover and in the search results. ROBB YOUNG: OK. But it couldn't hurt to follow a country level role, presumably? Because if the country doesn't exist in Web Stories-- let's say it's Australia or whatever-- they're just not going to find it anyway, so it doesn't matter.  

#### [0:03:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=180) |  JOHN MUELLER: Yeah, yeah. ROBB YOUNG: OK.

JOHN MUELLER: Yeah. I don't know. It's also one of those things where, since it's a bit of a new UI, I could imagine that they're kind of watching out for how these Web Stories are used and how they perform. And if you have the same story for multiple countries, then it could be that it comes across as oh, you're just republishing the same content multiple times.  

#### [0:03:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=210) |  So that's kind of the unknown from

my side. If it comes across as you're, like, republishing things, or if it's purely tied to geotargeting. ROBB YOUNG: All right. Yeah, I mean, luckily for us, we can do geotargeting and unique content per country. But OK. Cool. MIHAI APERGHIS: As far as I know, I think some of the product experts experimented with this a bit. And I know somebody with, I think,  

#### [0:04:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=240) |  a UK site created Web Stories that

got displayed in the US Discover results, because most of the traffic seemed to have come from US users despite that being a UK website. So my guessing, I guess, is that perhaps we should just treat them like a normal blog post. Like, if you have blog posts that are just in English  

#### [0:04:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=270) |  and are not targeting a specific audience,

you wouldn't necessarily make duplicates for each kind of country version-- you just have that blog post and that's it. Or maybe your commercial site has different country or language versions, but you have one single blog and you keep that separate and just in one language or whatever it's easier, and Google kind of picks it up and shows how it makes sense for Google, basically. ROBB YOUNG: Right.  

#### [0:05:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=300) |  I mean, ours is country-specific subfolders with

country-specific con-- this is for Experience Gifts, not the other site. So it would be specifically for that country. It's interesting, the "Telegraph"-- [INTERPOSING VOICES] MIHAI APERGHIS: --the UI, not the actual-- the-- because as far as I know, Web Stories do work. They're just not being shown in the-- the UI's not being shown-- ROBB YOUNG: Right. MIHAI APERGHIS: --in specific countries.  

#### [0:05:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=330) |  But they themselves are still being indexed

by Google, as far as I know. ROBB YOUNG: Right, OK. JOHN MUELLER: Yeah, I'll double check with the Web Stories folks when they're back. ROBB YOUNG: OK. DARCY BURK: I got a Core Web Vitals question for you, John. I think-- JOHN MUELLER: OK. DARCY BURK: --it makes sense. I just want to understand the rationale behind it a little bit more. So metrics like LCP, which is measured in time-- so like, 3, 2 and 1/2 seconds for good--  

#### [0:06:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=360) |  that is dependent on internet connection, right?

Like, that weighs heavily into that metric, right? So better developed countries with faster internet are going to more likely have a better LCP than the same website, perhaps, where the audience is in a country with underdeveloped internet connection. That is accurate? JOHN MUELLER: That can happen, yeah. I mean, for speed, the internet connection is one thing.  

#### [0:06:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=390) |  But the way that the pages are

built up is not purely tied to the internet connection speed. So that's something where-- [INTERPOSING VOICES] JOHN MUELLER: Whoop. Okey-doke. OK. Let's hope this doesn't go too crazy. Sometimes we have, I don't know, these kind of like Zoom bombers  

#### [0:07:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=420) |  drop in and do crazy stuff. So

we'll see. KAREN NELSON: Hey, hey man, very basic question, please. JOHN MUELLER: Sure. KAREN NELSON: I am just so stuck. I am not as technical as all of you. I am using Google Sites, not Suites, and I made a website and I cannot get-- I've enabled Google Analytics to track the property, and I simply cannot get--  

#### [0:07:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=450) |  I can't get Google to crawl the

site. And when I get into Google's Google Search Console, I've auto-verified the property. When I do a URL inspection, I get a message that the URL is not in property, I have to wait a couple of days. But that's been stuck for two weeks. I just wonder what to do. JOHN MUELLER: My recommendation there would be maybe to post in the Webmaster Help forum.  

#### [0:08:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=480) |  So Mihai is one of the experts

there. But sometimes, this depends a little bit on the specifics of your case. So in particular with Google Sites, there is a kind of a weird situation with the way that the URLs are structured in the sense that it can be that you're testing a URL which is one of those URLs that we don't actually crawl, but which is something that you might see in the UI.  

#### [0:08:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=510) |  So that's sometimes a bit, I don't

know, quirky with Google Sites in particular. And kind of going to the Help forum, posting your URL there, usually people will be able to take a look and say, oh, you should have been checking the other URL instead of that one, for example. KAREN NELSON: Oh good. Which site is that? Which webmaster did you recommend? JOHN MUELLER: It's the-- what is it? Google Search Central Help forum. I can drop a link into the chat as well. KAREN NELSON: That'd be terrific.  

#### [0:09:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=540) |  Thank you so much. JOHN MUELLER: Sure.

SPEAKER: Hi John. JOHN MUELLER: Hi. SPEAKER: This is [INAUDIBLE]. How are you? JOHN MUELLER: Hi. How are you doing? SPEAKER: Yeah, I'm good. John, the thing is actually, I found a fault in Google Webmaster algorithm bias for the software category. Is it possible to discuss about that personally? Already I've spoken with your representative site  

#### [0:09:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=570) |  for India plus [INAUDIBLE] country manager. Regarding

on this, this is what he said is not satisfied with me. Actually, Google is a company to provide a solution for that for my category and the following. This is what they said to me-- is not satisfied with that business. Can we discuss about this personally, not in this chatroom? Because I lost your-- JOHN MUELLER: We-- SPEAKER: Yearly, for example, $250 million,  

#### [0:10:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=600) |  I lost in my company due to

the-- I think you can understand. Can we discuss personally about this? Is it possible? JOHN MUELLER: Usually we don't set up one to one meetings, so that's something which usually we don't do. If there's something where you're running into situations with regards to maybe the monetized side of Google,  

#### [0:10:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=630) |  usually you can reach out to a--

what are they called? Account manager-- to kind of discuss out there. But especially when it comes to Search, it's not that we would set up a one to one meeting with any company. SPEAKER: It's OK. How to contact the account manager in India, John? JOHN MUELLER: I don't know. That's something where you'd have to go through whatever montized channel that you're working with. If you're working with Google Ads,  

#### [0:11:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=660) |  then through that, for example, you'd have

to go. Or if you're using AdSense, for example, you'd have to go through that. SPEAKER: Right, right, OK. Then we can discuss right now [INAUDIBLE] regarding this. For e-commerce platform business category people, the following search results are very good, right? So that is not just for the e-commerce business or news angles or in blog sports, OK? Bloggers for bloggers like that. For software category, software publisher companies,  

#### [0:11:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=690) |  like an [INAUDIBLE] like a Cnet. For

that kind of category company, actually I launched a company called filecoffee.com that was in '14, OK? I started-- and I started building within a large enterprise to publish the software for my country, India. So there is no representative in India to publish a software in India, because the software publishing is not the easiest task.  

#### [0:12:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=720) |  It's a very highly challenging-- oh, what

is it? Challenging field, right? Right. Before that, I started. But due to Google bias engine, how the Google is seeing for the sort of category site, told me about that Google is seeing the category for worldwide, because anyone can be downloading that throughout the world. Like, if I published the software in my domain [INAUDIBLE] even the Japan people also able to download the file, or the United States of people  

#### [0:12:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=750) |  can download the file, right? Right, John?

Right, fine. But the thing is actually in my country. It's the second largest country downloading the software. So I started the company from India, but I am not getting nothing the revenue from here. So how you are going to deal John, about this? JOHN MUELLER: OK, so you're not seeing your site visible in the search results in India?  

#### [0:13:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=780) |  Is-- SPEAKER: Yes, you are right. JOHN

MUELLER: Yeah, OK. My recommendation there might also be to go to the Webmaster Help forum and post some specifics, in particular, some searches that you see when you're looking from India to kind of highlight the issue that you're seeing there. And the folks in the Search Central forum, they can escalate these if there's something on Google's side that needs to be done. They can also give you tips with regards  

#### [0:13:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=810) |  to what you might be doing-- what

you might do differently with regards to geotargeting, with regards to kind of mapping the content to what the queries are looking for, those kind of things. SPEAKER: OK, yeah, actually they've given us some of the tips and to do that. Actually, they are recommending foreign AdWords. How much-- because I am a startup company, how much millions of dollars I can spend for the AdWords? So it's-- JOHN MUELLER: I have no idea. SPEAKER: --Google--  

#### [0:14:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=840) |  JOHN MUELLER: I have no idea how

AdWords works, so that's also something where it's like-- sometimes when you're a new business, you do various things to get popularity and to kind of grow a little bit more well known first, and that can include ads. But ads is not something that we do from the organic search side. So that's something you'd have to kind of figure out separately. SPEAKER: OK, OK. OK, John. OK, thank you. DARCY BURK: John, can we just touch back on my Core Web Vitals question again quickly?  

#### [0:14:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=870) |  Thanks. JOHN MUELLER: OK. DARCY BURK: So

yeah, just about the internet connection affecting the speed. So basically, what I'm trying to understand-- so I have a multinational site where the majority of the customer-- or some portion of the customers are in North America, where there's better internet connection, and then a portion of the customers are in an underdeveloped-- a more underdeveloped countries with a slower internet connection. It's essentially the same architecture, different content.  

#### [0:15:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=900) |  But the speed scores might be the

same, but then because the internet connection is poorer for maybe South America, I have a worse LCP score there. So what can I do about that, or what's the methodology behind that, I guess? JOHN MUELLER: The-- in general, our idea with this score is to map where your users are actually using your site from.  

#### [0:15:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=930) |  So if users are primarily in one

location where they have bad internet connectivity, you're kind of competing with other sites who are also kind of focusing on those users. So it's not that you have kind of a disadvantage just because you happen to have users with a slow internet connection. It's more, well, for those users, those are the sites that are available, and maybe they will come to you as well. Maybe they'll go to other sites. DARCY BURK: So it's a level playing field, basically, is what you're saying there.  

#### [0:16:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=960) |  JOHN MUELLER: That's kind of the idea,

yeah. So it's not just like, well, this site focuses on users in the US and they have really fast connections, therefore they have good scores and we will rank them higher. It's more that, well, like, depending on where your users are coming from, we will try to rank you like that. DARCY BURK: So would you look at the ranking on a per country basis, or like-- so like if it's a multinational site like that, the US section, would that have a different kind of benchmark,  

#### [0:16:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=990) |  or I guess be against a different

audience than, I guess, the other sections? JOHN MUELLER: Could be. So I-- so there are a few things that kind of play into that. On the one hand, we have to have enough data from the Core Web Vitals side to understand these segments, and if we have data for those segments, then we can apply that. Whereas if we don't have a lot of data for your website, then maybe we'll just say, oh, the whole website has this one data point. And then it's kind of like all bundled together in that one  

#### [0:17:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1020) |  aggregated data point. But if, when you

have more data-- and you'll see that in the Search Console. If there are multiple sections there with number of URLs, you can see a little bit more like, well, there's data for the US part, there's data for the South American part, for the European part, all of those things. DARCY BURK: And I section those different properties, or those different subfolders out into different properties anyway, so I can use that data that way then, I guess. JOHN MUELLER: Sure.  

#### [0:17:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1050) |  Yeah. DARCY BURK: OK. And then just

to further your point with one more thing, what if a site has no-- is not in the CrUX data set at all? How then does it get ranked, or-- yeah? JOHN MUELLER: Yeah. I mean we run into this problem with all kinds of metrics, so that's something where we kind of have to figure out, how do we start this side off? And that's something which you see not specific to the speed  

#### [0:18:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1080) |  side, but what you also see with

regards to, I don't know, lots of other factors, like, around the quality of the site overall. Whereas some people will say, oh, there's this Google honeymoon period until Google has enough data for my site, or I'm in the Google sandbox because Google is ranking my site lower than it should be in the beginning until we have enough data. And that's kind of reflected in there. It's not so much that we treat it in a bad way  

#### [0:18:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1110) |  or in a good way, but we

have to make some assumptions, and over time, we should be able to collect data on that. DARCY BURK: OK, cool. That makes sense. Thanks so much. JOHN MUELLER: Sure. DEEPAK: Hi John. JOHN MUELLER: Hi. DEEPAK: Hi John. It's Deepak here. I'm from India. JOHN MUELLER: Cool. Hi. DEEPAK: Yeah, I'm doing Java and MTC company. Actually, my question regarding a basic and technical website  

#### [0:19:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1140) |  structure. Actually, I'm facing some issues with

my website there, regarding a crawling and indexing. It's bigliving.co.uk website. I have changed the website structure many times. But still, I'm not able to index my website in search engine.  

#### [0:19:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1170) |  There are basically some categories which are

indexed, but other pages, like filter pages and internal subpages, are not indexed properly. So that's why I'm not able to get good results. And this site is, you can call it an enterprise website. JOHN MUELLER: OK. DEEPAK: So can you please suggest to me what I have to do with this website or structure, where  

#### [0:20:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1200) |  I can-- JOHN MUELLER: Yeah. So it's

hard to say without looking at the website in detail, and so that's something where I might also suggest going to the forum to get some tips there. But in general, changing the website structure makes it a lot harder for us. So if you've changed the structure a few times already, then every time you change the structure, we have to understand the new structure. And that takes time.  

#### [0:20:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1230) |  So finding a way to focus on

one structure that you can keep for the long run, that's, I think, is really important. So fewer changes and more focus on one clear structure. The other thing that I think is important is focusing on fewer pages as much as possible. So you mentioned, like, filter pages, for example. And if you can avoid having all of these filter pages  

#### [0:21:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1260) |  indexed by setting them as noindex, for

example, then we can focus a lot more on the actual detail pages. So that's something where, when you look at your website, maybe-- it's like, if you're seeing that Google is struggling with crawling and indexing, then think about which pages do you really, really care about, which ones are really important for your business, and make it so that search engines can really focus on those pages. So kind of limit the links to the other pages,  

#### [0:21:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1290) |  limit the indexability of the other pages

so that we can really focus on the smaller set of pages that you find important. DEEPAK: OK, sir. One more question, please. JOHN MUELLER: Sure. DEEPAK: It's regarding URL structure. Obviously, we are talking about is essentially website structure, but what do you think about URL structure [? meaning ?] to root domain category, then subcategory,  

#### [0:22:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1320) |  after that, product page? So is it

right URL stru-- JOHN MUELLER: Yeah, I think that's perfectly fine. Like, URL structure, I don't have super strong opinions on that, because different sites make it in different ways. And usually, if you have unique URLs, it just works. But that's a reasonable structure. That's also, like I said, something I wouldn't just change.  

#### [0:22:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1350) |  So if you get advice from some

other SEO and they say, oh, you should put dashes instead of subdirectories, for example, I wouldn't change that kind of thing, because it makes it much harder for us to understand your site. So instead, pick one structure that you're kind of OK with, and keep that for the long run. DEEPAK: OK, sir. All right. And-- all right, sir. Thank you very much. I think I'm satisfied with your answer.  

#### [0:23:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1380) |  JOHN MUELLER: Sure. MARTIN RAU: I have

a follow-up question to that. RAJA GOPAL GADDE: Hi John. JOHN MUELLER: OK. [INTERPOSING VOICES] RAJA GOPAL GADDE: Yeah. So today I would like to-- so today I would like to know that actually, our website is an e-learning website. And it's ranking well, and we're getting the good profit and actually, we want to apply the story branding  

#### [0:23:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1410) |  thing to our website. So for that,

like, we want to cut down our content in our service pages and in the home page, and we want to put more graphics in it. And let's say maybe we cut down the content up to 75%. What kind of impact it will show in the ranking, and as well as the [INAUDIBLE]? JOHN MUELLER: I don't know. It really depends.  

#### [0:24:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1440) |  So if you're removing content, then obviously,

we can't rank you for that content. If you're removing things that are not important for your site, then that's perfectly fine. If you're removing something that is critical for those pages, then of course, those pages won't be visible for those queries. So yeah. So it's-- RAJA GOPAL GADDE: I would like to add that so-- we'll, I mean, take the consideration of the keywords  

#### [0:24:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1470) |  and we will put those keywords in

the content. And I mean, we want to write in terms of customer prospect, too, so because of that, we want to trim down the content and make it very crispy for the users. So-- JOHN MUELLER: So my recommendation there, if you're looking at trying to make a bigger change, like removing 75% of the content seems like a big change,  

#### [0:25:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1500) |  I would take a handful of pages

and test it and make the changes there and see how they perform. If they perform OK, then maybe do the same work on the other pages. If they don't perform as good as you expect, then maybe try different things out and test that. RAJA GOPAL GADDE: OK, if they're not working well, if I restore the page again with the same content which I have deleted, so will it rank again?  

#### [0:25:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1530) |  JOHN MUELLER: Sure, yeah. I mean, it

obviously takes a little bit of time for indexing to catch up, but it will be like before. RAJA GOPAL GADDE: OK, great. And one more question, last question. And actually, in our blog, we upload the one article each day. I mean, we publish one article each day. So what do you suggest the best-- thing-- I mean to say, like, in terms of content members,  

#### [0:26:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1560) |  how many articles are we supposed to

upload in a week or a month? JOHN MUELLER: It depends. Up to you. Some sites make very few changes and few articles, others make lots of articles. It really depends on how much content you have available that you can create and what people are looking for. RAJA GOPAL GADDE: OK, great. And thank you so much. And I appreciate Google for conducting these kind of [INAUDIBLE] and Merry Christmas.  

#### [0:26:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1590) |  JOHN MUELLER: Thanks. You too. Martin, I

think you had a question. MARTIN RAU: Yeah, I had a follow-up question to the change of the internal structure of the domain. Let's say you really change a big thing, like the main navigation, for example. What kind of timeframe would you recommend until all the signals have been reprocessed, so to say? JOHN MUELLER: I would assume you would see the large part of the reprocessing taking place  

#### [0:27:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1620) |  within maybe two or three weeks. In

general, we try to recrawl all pages within six months. So the long tail will take a bit of time to be updated, but kind of the pages that we crawl the most, that we think are the most important for your site, they should be updated within a couple of weeks. So my guess is at least after a month,  

#### [0:27:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1650) |  you should see kind of the effects

of a change like that. MARTIN RAU: All right, that's great. Thank you. JOHN MUELLER: Sure. NIKOLA MINKOV: Hi John. JOHN MUELLER: Hi. NIKOLA MINKOV: So which [INAUDIBLE] to choose if we have a category with products for a few months. They're indexing very well, they run very well. But in one shiny day, the owner delete them or remove them from categories.  

#### [0:28:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1680) |  And what method will be better for

us to choose, the noindex canonical or something to leave them like a blank page? JOHN MUELLER: So it's a product that you're removing from your site? Is that correct? NIKOLA MINKOV: Yeah. Yeah, but the question is for the category, because the categories rank in the list or in the category are very much products, but they finish one day. JOHN MUELLER: Oh, so you removed the whole category?  

#### [0:28:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1710) |  NIKOLA MINKOV: Yeah, all products from category.

JOHN MUELLER: OK. I-- NIKOLA MINKOV: Other category, same thing. For a few months. But after a few months, we will be come back. JOHN MUELLER: I would just make it 404. NIKOLA MINKOV: 404. JOHN MUELLER: Yeah, I wouldn't try to do anything too tricky there. I think if you set it noindex, the same thing will happen. If you try to set it canonical to a different category, we'll treat it as a soft 404.  

#### [0:29:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1740) |  So from that point of view, I

think, like, 404 is kind of the easiest approach that has the same effect. NIKOLA MINKOV: OK. And if we get the products few months after that, we should create new categories. JOHN MUELLER: Sure, yeah. And if you have new internal linking pointing to those category pages, then we will pick it up. NIKOLA MINKOV: Yeah, of course. And thank you so much. And one more question about the last update.  

#### [0:29:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1770) |  I was wondering something after the date,

do you think it's reasonable to immediately take some action, or should we wait until it's over? Because sometimes webmaster's trying to change something when the update is rolled out, but I don't know it's very smart decision. What is your advice here? JOHN MUELLER: I mean, if-- so I think the core update, I think  

#### [0:30:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1800) |  that's finished rolling out. So from that

point of view, it's like, it's finished anyway. But in general, if you have things that you can improve on your website, why would you wait? I-- especially if there's something bigger that you want to improve on your website, then I-- there's always some update happening at some point, so I would just make those fixes and improvements. And keep track of them, of course,  

#### [0:30:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1830) |  so that you know a little bit

when what happened, but I would just make those changes. NIKOLA MINKOV: Mm-hmm. Yeah. Thanks. And do you think that a website can lose its visibility to recover without this SEO specialist intervention in the period between two updates? JOHN MUELLER: Sure. NIKOLA MINKOV: It's possible. Without the-- JOHN MUELLER: Yeah, I mean, it's like, SEO specialist. You can't, like, pick up a magic wand  

#### [0:31:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1860) |  and kind of make a website magically

appear. It's something where-- especially when it comes to the core updates, we're looking at the relevance of the website overall. And that's something that anyone can take a website and say, oh, I will rewrite the content and I will recreate the website. It doesn't need to be an SEO. I think there's a little bit of an effect there that SEOs often know a little bit more  

#### [0:31:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1890) |  of what's happening and what Google might

be watching out for, but anyone can update a website and make it better. NIKOLA MINKOV: Yeah. Thank you so much, John. JOHN MUELLER: Sure. Let me run through some of the submitted questions. And we'll definitely have a bit more time to chat as well afterwards, but just so that we kind of run through those quickly. We experienced a severe ranking drop. Our domain is only visible for brand searches. All other rankings have nearly completely vanished for now  

#### [0:32:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1920) |  since three weeks. On the other hand,

we do not experience any alert in Search Console. Is it possible that the Search Console has a bug so that there are no alerts shown, even if the domain is punished via penalty? So it's always possible that there's a bug in Search Console. I mean, that's-- it's kind of like computer software. It's always possible there. However, I would be very surprised if there were a bug in particular with regards  

#### [0:32:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1950) |  to the manual actions. So we call

them manual actions. People externally tend to call them penalties, because manual actions are something that-- they just happen all the time and lots of sites see them, lots of sites try to fix them, and that's something where, if there were a general bug with regards to how we show manual actions, I think lots of people would notice it and complain about that. CHRISTIAN SCHWINDEN: May I ask a question? Are we running? JOHN MUELLER: Sure. CHRISTIAN SCHWINDEN: So you already know the situation,  

#### [0:33:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=1980) |  but can you imagine a situation where

the rankings are vanished and the reason for that. So if it's not a penalty. JOHN MUELLER: Yeah. So I don't know exactly the number of weeks, but we recently had a core algorithm update, and that might map into that timeframe that you're looking at there. And with the core algorithm updates,  

#### [0:33:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2010) |  we try to improve the way that

we understand relevance in the search results. And with that, it can happen that a website becomes suddenly less visible and significantly less visible in some cases, even, than it was before. And it's not that there's a kind of something that you're explicitly doing wrong, or an error or something on your website. It's more our systems feel that this is the way that we should show websites in search now. CHRISTIAN SCHWINDEN: OK.  

#### [0:34:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2040) |  JOHN MUELLER: And we have a blog

post about the core algorithm updates, so I would go through that. CHRISTIAN SCHWINDEN: Oh, sorry. We already checked this. It was our first thoughts, so it happened around the 24th, 25th of November. So we are pretty sure it's not the core update. JOHN MUELLER: OK. I mean, there are also lots of other changes that can happen in search, so it can certainly  

#### [0:34:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2070) |  happen that our algorithms are picking something

up on your site and reacting to that. If it's not-- [INTERPOSING VOICES] CHRISTIAN SCHWINDEN: It can provide another information. So there was an incident, so a linked network, a link building networks on [INAUDIBLE] a fraud network, was pointing on 300 domains which were in my company's portfolio. So they were hosted on our own servers. And by linking from the linked network to our domains,  

#### [0:35:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2100) |  those domains got indexed, and they all

had a redirect to our main company page. So that [INAUDIBLE] as well, which can help to clarify it. JOHN MUELLER: Usually, something like that wouldn't be a problem for us, because if it were a problem, we would flag that as a manual action and you would see that in Search Console. And yeah. CHRISTIAN SCHWINDEN: It's the servers. So the servers of-- so it's a huge company, and the servers  

#### [0:35:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2130) |  from my company that's something like a

daughter of the big company, they are hosted on the same servers. So the traffic from the indexed URLs pointing on our domain are on the same server. So that's why I mentioned, it's not taken into respect as spam-- or it is taken into respect as spam because they are hosted on our own servers. So if they're a foreign-- or servers which are not under our control, the spam attack  

#### [0:36:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2160) |  wouldn't be that-- would not have those

consequences. JOHN MUELLER: Yeah. I don't know. My general feeling is we would still be able to deal with that normally. But it sounds like you have a very unique situation. So that's something where I would also maybe point at the Help forum. Maybe post there.  

#### [0:36:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2190) |  You can also drop your URL here

in the chat, and I can take a quick look afterwards. I can't make any promises with regards to what we can do there. But I'm happy to take a quick look to see that things are kind of working as expected. CHRISTIAN SCHWINDEN: Just get to-- I need to ask someone if I can put our web [INAUDIBLE].. JOHN MUELLER: Sure, sure, no problem. CHRISTIAN SCHWINDEN: Thank you. JOHN MUELLER: OK. All right. Let me run through some of the other submitted questions so that we get a few of those covered.  

#### [0:37:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2220) |  During the core update rollout, is it

like the quality of the website is calculated from the overall site signals, and then this site quality score is propagated to every page gradually, page by page? Is it possible that some pages drop and some pages surge, and the overall traffic to the domain remains the same? It's-- like, when we try to understand the relevance of a website, on the one hand, we try to look at the bigger picture of the website. But we do also look at smaller parts of a website.  

#### [0:37:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2250) |  So it can certainly happen that some

things go up, some things go down. And on average, across a domain, you will see some change, or maybe it'll even out even in kind of weird coincidental cases. So that's certainly possible, the way that you're seeing things there. And it's also that there are always a lot of different things that come out with regards to search, and some are a little bit more  

#### [0:38:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2280) |  focused on the domain or on a

bigger picture of the website. Some are focused more on smaller parts of a website. So even outside of a core update, you might see these shifts across some parts of your site, and other parts going up, some parts going down. When do you bring back the request indexing tool? I don't know. So we will see. I know that lots of people want it, and the Search Console team is pretty close to kind  

#### [0:38:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2310) |  of getting that back lined up. I

don't know what the timing there will be. It's like there is some chance that we might still get it this year, though it's getting really tight. From a ranking standpoint, if Core Web Vitals us real user data-- I think we talked about this briefly before-- in March, your big mobile update will come. If we are ranking well at the moment on mobile,  

#### [0:39:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2340) |  can that change with the mobile update?

For example, our internal linking is basically nonexistent on mobile. Our mobile navigation menu is blocked for the crawler currently. How much is our desktop page actually influencing the rankings on mobile? So I didn't take a look at your specific site, but if your site is already shifted over to mobile first indexing, then you will not see any changes in March when we shift the rest of the web  

#### [0:39:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2370) |  over, because we're already using the mobile

version of your site for indexing there. And for the largest part, we have shifted over most websites. So that's something where if we've shifted it over, you're not going to see any changes. If we haven't shifted your site over to mobile first indexing, then that does mean that on the one hand, our systems are not sure if your site will work well with mobile first indexing.  

#### [0:40:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2400) |  And if your site still doesn't work

well with mobile first indexing in March, then we will pick whatever mobile content you have and index that, which might be worse than your site is now with regards to indexing. So that's something where depending on your case, you might see changes or you might not see changes. Page speed Core Web Vitals question-- does the origin summary include only index pages or the domain  

#### [0:40:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2430) |  experience? So I don't know offhand how

the Core-- or how the CrUX, the Chrome User Experience Report data is collected with regards to kind of like what goes into the origin summary or not, but there is fairly detailed documentation on the Chrome User Experience Report data. So I would double check that there.  

#### [0:41:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2460) |  I still get alerts from an old

subdomain that I moved away many years in Search Console. I'm concerned that it's affecting my ranking with a current and active domain. Should I fix these errors? Probably not. So search and Search Console, they keep track of things for a really, really long time. And it can happen that you move to a different domain and the old domain still exists. Maybe there's no hosting there anymore in the meantime. And if anything happens where we try to crawl a page  

#### [0:41:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2490) |  and find errors, then we will flag

that in Search Console, but that doesn't mean that there's any effect on your current site with regards to search. So for the most part, if you've moved away many years ago and something gets flagged on the old domain, then you can just ignore that. I want to split a website into two websites. I want to keep some pages and posts on a current domain, but the pages and posts I want to move to a separate website  

#### [0:42:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2520) |  will keep the same branding, structure, basically

everything. I just want to separate visitors and make two websites easier for them. Except for 301 redirection for the moved pages, is there anything else I should keep in mind to do in order to maintain the website reputation and not lose ranking of those migrating pages? So I think the redirects are really the primary thing that you should focus on,  

#### [0:42:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2550) |  but any time that you split or

you merge websites, the end result is really hard to determine ahead of time. And it can be that things are better. It can also be that things are worse overall. So in particular, if you're taking a website and you're splitting it up into lots of small pieces, like lots of pieces, not just two, then it can happen that all of those pieces individually are just kind of like OK from a quality point of view, but not good enough  

#### [0:43:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2580) |  to compete in a competitive environment. So

in particular, if you're active in a very competitive area and you split things off into smaller pieces, then it might be harder for us to rank those. Whereas if you combined them, it might be easier for us to rank those. On the other hand, if it's a less competitive area, then it's very possible that we'll just index all of those versions and show those appropriately in the search results. So that's something where it's really hard to determine ahead  

#### [0:43:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2610) |  of time what the SEO effect will

be. And because of that, I would recommend doing this kind of a split or merging primarily then when you have really, really strong business reasons to actually do that. If you really know your users are annoyed if you have both of these things on the same website, and maybe they convert first because of that, then that's something where I'd say, well, maybe it makes sense to split these off. But if you're just trying to tweak things slightly,  

#### [0:44:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2640) |  and you don't expect a big effect

from your user side, then by doing this kind of splitting off, my suspicion is that overall, you will be a little bit worse situation than before. When will Search Console allow disavow files submitted to domain verified sites and allow all four versions to apply at the same time? We don't want to do it four times. I don't know.  

#### [0:44:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2670) |  I think that's on the Search Console

list of things to do. In particular, when they rolled out the new disavow feature, we did bring them their feedback because it also came from folks like you. So I don't know what the timing there will be. The good part, I guess, here is that it's-- for the most part, it's really rare that you have to do a disavow file submission. So if you do this in an extreme case once a month,  

#### [0:45:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2700) |  and you have to do it four

times rather than one time, it's not a ton of times [INAUDIBLE].. On the other hand, if you're doing this daily, then probably you're focusing on things that don't have as strong effect as you'd expect. I'm starting my new website, and I'm making it accessible for people with disabilities. My question is, how can we include animation and videos and infographics if I want to make it accessible? Second, does accessibility make for trouble  

#### [0:45:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2730) |  when it comes to indexing? So I

don't have a lot of expert advice with regards to accessibility. I don't have a lot of background knowledge there, so it's hard for me to say what you should really focus on there. But there are definitely experts out there who can help you to figure that out. With regards to indexing, usually I find that if you make a website more accessible,  

#### [0:46:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2760) |  that it actually becomes better for search

because usually that means you don't just have one image and Google has to figure out what this image means, but rather, you have the image and you have an alt attribute for the image, and you give more details about the image. And all of that makes it easier for us to understand what your site is about. So that's something where usually, with regards to crawling and indexing, making things more accessible is more of a positive effect  

#### [0:46:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2790) |  rather than a negative one. Should I

separate my e-commerce from my main website? What's the guideline, if any? Would it be better for SEO? You can do it either way. So some sites have a blog and an e-commerce site on the same domain. Some split that off into multiple domains. It's essentially possible for you to do that in any particular set-up.  

#### [0:47:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2820) |  So that's something where I would focus

more on what works well for you, what works well for tracking for Analytics purposes, and then go from there. I'm very novice, but have managed my website this past year. I'm really having difficulty understanding Search Console with regards to my accounts. Looks like everyone here is more expert. Is there more appropriate Google forum? I would probably go to the Search Central Help forum.  

#### [0:47:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2850) |  I keep saying that today. I don't

know. It seems like it's usually a good place to go with regards to these general questions, like how do I verify my site, how do I get things started and get set up with regards to search. There are lots of really smart and friendly people there, so I would tend to go there and post your details there, like the URLs that you have for your website, so that someone can take a look and say, oh, it's  

#### [0:48:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2880) |  like, you need to put your meta

tag here or you need to do this in your WordPress or whatever you're using. How many articles are needed for Google Discover to find our site suitable? I don't think there's any limit with regards to Discover. However, the Discover content policies are a little bit different than web search, and what we focus on for Discover is a little bit different than just general web search. So I would check out the content guidelines for Discover  

#### [0:48:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2910) |  and see how you can perhaps tweak

your content to make it more suitable for Discover, and then keep working on that. I think Discover is a really fascinating thing because it shows your website to people that are not actively looking for it. But on the other hand, that also means it's really hard to create content specifically for Discover, because you don't know what people are not searching for where your site could be shown.  

#### [0:49:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2940) |  So it's a bit kind of like--

it's a tricky, tricky place. But I think it's really cool. Oof, OK. More and more questions. Maybe I'll just switch back to questions from you all to kind of close things out. CHRISTIAN SCHWINDEN: So I've dropped you the URL in the chat. JOHN MUELLER: OK, cool. I'll copy that out and take a look at that later on.  

#### [0:49:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=2970) |  Yeah. CHRISTIAN SCHWINDEN: Great, thank you. JOHN

MUELLER: Sure. MIHAI APERGHIS: John, regarding-- so regarding Discover, does it-- first of all, is there anything new that the Discover team is likely to come up with, come out with anytime soon in terms of more recommendations or maybe more insights of what people-- especially people who had traffic from Discover, now they don't--  

#### [0:50:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=3000) |  maybe some insights into what they can

do to improve? JOHN MUELLER: Yeah. I don't have any idea of timing. So that's always tricky to come and say, like, what will happen in the future. It's like, I really don't know what the timings are there. I do know the Discover team cares a lot about people who are trying to get content visible in Discover, and they'd like to make it a little bit easier to understand  

#### [0:50:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=3030) |  what is happening there. So it's certainly

possible that some things will come out that have a little bit more information or some more tips on it on what you could be doing differently. But I don't know what the specific plans are there or timelines would be. MIHAI APERGHIS: Sorry, you mentioned in one of the previous Hangouts that-- as I mentioned, we've been working with a publisher that has been removed from Discovery in May and we kept making sure that the new content that they publish  

#### [0:51:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=3060) |  is according to Discover policies. And they

improved the content and overall user experience as well. And you mentioned that Google, kind of including Discover, requires quite a bit of time to kind of process all of these changes. Even if the content is indexed, there might still-- we might still need some time until Google understands  

#### [0:51:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=3090) |  that OK, so this is a good

enough quality website to be included in Discover again. And you mentioned a month is, especially for large websites, a month is kind of a small amount of time. What would you think, like, is an appropriate amount of time to wait? JOHN MUELLER: I don't know. I mean, it's tricky, on the one hand, with regards to bigger quality changes on a website.  

#### [0:52:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=3120) |  So that's-- it's really hard to say

there. And on top of that, I don't know, in particular, how Discover pulls all of that information together. MIHAI APERGHIS: Right. You-- JOHN MUELLER: So for search, I would guess, like, a large site, a couple of months should give us time to understand a little bit better. I don't know if Discover would do anything past that or would take longer. MIHAI APERGHIS: OK.  

#### [0:52:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=3150) |  But so definitely a month is too

little to kind of see a significant impact. So I'm guessing two, three, four months and beyond-- JOHN MUELLER: Yeah. MIHAI APERGHIS: --is a more appropriate time to-- oh, OK. And I know you mentioned that with Discover, the new content, the fresh content, is-- has a heavier weight in terms of how Discover calculates everything. So just to confirm that it's not really required to kind of go back months  

#### [0:53:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=3180) |  or years to kind of update that

old content and, you know, update it? JOHN MUELLER: Yeah. I see it as something that's not particular to Discover itself, but more with regards to how we understand websites. And the kind of website that you're kind of talking about sounds like something where you're generally creating new content all the time, right? That means within your website, when we understand your site  

#### [0:53:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=3210) |  structure, we focus essentially on the newer

content and on the main category sections, for example, of a website. Which means that overall, we would automatically for indexing kind of focus more on that newer content, because it's just very prominently linked within your website. You're giving it a lot of weight. So regardless of Discover or just search in general, if you're constantly creating new content, then that's kind of where we will shift our focus over time.  

#### [0:54:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=3240) |  MIHAI APERGHIS: So it's not the case

that the old content might pull everything, you know, especially if the site has been online for, like, five years or something like that. It's not like these four and 1/2 years are pulling down the last six months of new content. JOHN MUELLER: I mean, it really depends on your website, and that's something where if you look at the traffic from search and the Analytics traffic,  

#### [0:54:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=3270) |  you can probably make guesses on which

parts of your site are critical for your site. So I could, for example, imagine a situation where you have a news type website where we focus on news, but you also have a reference section somewhere. And the reference section is really important because it's like, you're the only reference site for that kind of content. Then we would say, well, this reference part is really important. But there's also a news part.  

#### [0:55:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=3300) |  And we try to find kind of

like a balance between those two parts. On the other hand, if it's purely a news website and we can purely focus on the new content and that's really clear when we crawl and index your site, that's clear from all of the signals that we get, then obviously, we'll focus on the news part. MIHAI APERGHIS: OK, for search. I'm guessing for Discover, these reference sections, they might not be as relevant when calculating things.  

#### [0:55:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=3330) |  JOHN MUELLER: I mean, it kind of

depends on what kind of things you're focusing on. So if you're looking at an overall quality issue with regards to your website, and you have kind of this reference part that's really important for your website but is really low quality, then we will still balance that low quality part with your newer quality news content and try to find some middle ground there with regards to how we understand the quality of your website overall.  

#### [0:56:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=3360) |  But it really kind of depends on

your website. And it's not so trivial to just say, oh, we will take a look at all the Search Console traffic and impressions kind of thing. It's like we try to figure out what is important for the site overall. MIHAI APERGHIS: Right, right. OK, OK, good. JOHN MUELLER: Sure. All right. Any more questions from anyone?  

#### [0:56:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=3390) |  No questions? DEEPAK: Hey John. I have

a question. JOHN MUELLER: Sure. DEEPAK: Actually, it's regarding website schemas. [INAUDIBLE] for website-- is it really useful for increased website visibility in a search engine, or help to rank higher? JOHN MUELLER: It doesn't change the ranking. It changes how we show the pages in the search results.  

#### [0:57:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=3420) |  So it's not that you will rank

higher if you add structured data. But if you do have structured data that we can use for rich results types, then we will perhaps show that in the search results. So for example, if you add FAQ markup to your pages and we understand we can show that for your site, then we will show that in the search results. And maybe that will be more visible for your website,  

#### [0:57:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=3450) |  and maybe it will attract more users

to your site overall, but it doesn't change the ranking of those pages. DEEPAK: OK, OK. Actually, I have implemented a schema over all websites and they all are visible in search engines. JOHN MUELLER: Cool. DEEPAK: OK. And yeah. One more question-- sometime website, overall website perform-- right? All keywords are in the top 10.  

#### [0:58:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=3480) |  And after two weeks, overall website drop.

Pure ranking drop. Then what we can-- what issue-- I have no words for this. I hope you understand? JOHN MUELLER: Yeah. It's really hard to say. So we have a document in the Help Center specifically for,  

#### [0:58:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=3510) |  I think, my site's ranking dropped or

my page's visibility dropped, something like that. And it goes through a number of the issues that could be playing a role there with regards to maybe technical issues that you can double check, and also some tips with regards to the overall quality. But in general, even if you have all of the technical things set up correctly, it can happen, and it's very normal  

#### [0:59:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=3540) |  that things will go up in ranking

and things will go down in ranking over time. So just because a page is no longer ranking as well as it was before doesn't necessarily mean that there's something wrong with the page. It might just be it's like, maybe there are other pages that we should show in search. Maybe we just have trouble understanding the relevance of the page. Focusing the page more on the kind of content that you want to have it visible for. All of these things can play a bit of a role.  

#### [0:59:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=3570) |  DEEPAK: Oh, OK, OK sir. Actually, according

to all Google guidelines, I have made a document and recently, last month, I have launched a new website. It's regarding a hoverboard. And can you imagine, after one and 1/2 months, overall website are ranked higher  

#### [1:00:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=3600) |  and the [INAUDIBLE] are in top 10.

Fresh new website. JOHN MUELLER: That's good. DEEPAK: Yeah. And I got good traffic, daily around 2,000 to 2,500. Yeah. JOHN MUELLER: That sounds good. Yeah. I mean-- DEEPAK: It's [INAUDIBLE]. JOHN MUELLER: Sometimes if you get everything-- DEEPAK: [INAUDIBLE] overall website optimizer, all are Google guidelines, Google guidelines.  

#### [1:00:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=3630) |  JOHN MUELLER: Cool. DEEPAK: Excellent, excellent, really.

JOHN MUELLER: Cool. I mean, it's-- on the one hand, the technical things are certainly things to watch out for. But it's also-- it's not guaranteed that you will be successful just because you follow the technical guidelines. So sometimes, you also have to kind of like have a sense of what will be important or what areas are maybe not covered so well at the moment  

#### [1:01:00](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=3660) |  that we can help cover. So it's

like yeah, cool. All right, let me just pause the recording here. We can stick around a little bit longer, if any of you want, and yeah. I don't know. I think this is the last Office Hours Hangout out for this year. So thank you all for joining all of these Hangouts. Thanks for all of these questions along the way. I hope you found these useful. We'll certainly be doing more of these next year as well.  

#### [1:01:30](https://www.youtube.com/watch?v=udW8Pc1tpl8&t=3690) |  I think Martin is doing one for

JavaScript next week, so it's not completely closed. I don't know how he does it, like, over-- almost over the holidays. We'll see. But we'll definitely have more of these lined up next year. So wish you all happy holidays and see you next year, in that case. DEEPAK: Merry Christmas! MARTIN RAU: Merry Christmas! DIDO GRIGOROV: Merry Christmas. DEEPAK: See ya. MARTIN RAU: Bye.  