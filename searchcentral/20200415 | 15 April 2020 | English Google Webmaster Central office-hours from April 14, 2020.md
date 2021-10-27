[![English Google Webmaster Central office-hours from April 14, 2020](https://i.ytimg.com/vi/AoZbAinDg0E/maxresdefault.jpg)](https://www.youtube.com/watch?v=AoZbAinDg0E)

## English Google Webmaster Central office-hours from April 14, 2020

This is a recording of the Google Webmaster Central office-hours hangout from April 14, 2020. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Watch out for new sessions, and add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



Feel free to join us - we welcome webmasters of all levels!



#### [0:00:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=0) |  JOHN MUELLER: --not to jump out. OK.

All right. Welcome, everyone, to today's Webmaster Central Office Hours Hangout. My name is John Mueller. I am a Webmaster Trends Analyst here at Google in Switzerland, and part of what we do are these office hour hangouts-- which I guess are not in the office anymore but, rather, at home at the moment. But whatever-- we'll improvise. I hope you're all doing well and are safe wherever you are, whichever place at home--  

#### [0:00:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=30) |  I guess pretty much everyone is at

home nowadays, where you're at. We have a bunch of questions submitted, but if any of you want to get started with the first question, feel free to jump on in. AUDIENCE: Hi, John. JOHN MUELLER: Hi. AUDIENCE: [INAUDIBLE] So John, I want to ask a question about the crawl depth of a website. So what happened is, I was working on a website, and it has approximately 200 blogs.  

#### [0:01:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=60) |  So when I initiated the crawl on

it, I used Screaming Frog, and what I found is, the blogs are dug deep in the AI. That is, the most profound blog was on eighth, crawled up. So how could I cope it, and what is the best practice for it? What would you suggest? JOHN MUELLER: In general, with crawl depth, you need to find a balance between having a flat architecture and a really kind of narrow and deep  

#### [0:01:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=90) |  architecture. And that's something where there is

no hard rule, where you can kind of say, for technical reasons, it should be like this or like this. But rather, we generally try to crawl things that are closer to the home page, because usually, the home page is the most important page. We tend to crawl things that are linked from there a little bit more frequently, and that kind  

#### [0:02:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=120) |  of bubbles down. So depending on the

website, whatever page happens to be the most important page for that website, from there is kind of where we start looking at the crawling. And that essentially happens through the links on the page. And if we find pages that you think are really important-- just very far away from the pages that Google or your users think are important-- then, for us, it's hard to understand that this is actually an important page. So when it comes to crawl depth in a situation like this,  

#### [0:02:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=150) |  if this is something that you find

is really important for your website-- which might be because there is important information on there, it might be because you're doing a special offer at the moment, it might be because you make the most money from a certain product-- then I would just make sure that it's really visibly important on your website. So link to it from kind of higher level places within your website's architecture. It could be from the home page.  

#### [0:03:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=180) |  It could be from category pages-- things

like that. So that's something where you kind of have to use your judgment and say, well, this is an important page for me. Therefore, I want to make sure that everyone-- users and search engine crawlers-- understand that it's important. AUDIENCE: OK, so just to follow up-- I just want to ask one thing. What would be the back work of that? Should I categorize those blogs into certain categories, or should I use breadcrumb implementations for that?  

#### [0:03:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=210) |  Or just simply categorize into them? JOHN

MUELLER: That's totally up to you. Sometimes, it's enough to just categorize the blog post that you have-- kind of higher level category pages which are easier to crawl and find. Sometimes, you can take individual posts and just highlight them on, like, the home page of the site and say, these are my most important posts or my most popular posts-- something like that-- and link to them a little bit more  

#### [0:04:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=240) |  prominently within the website. But how you

do that is up to you. And it might also be that this kind of eighth level, in that particular site, is also OK. It's not necessarily a sign that eight is bad or anything like that. AUDIENCE: John, I have a follow-up-- AUDIENCE: Thanks, John. AUDIENCE: --on that. JOHN MUELLER: Sure. AUDIENCE: You said, now I think-- let me try to interpret your tweets. Basically, you said something about your way to visibly see-- according to Google-- if Google thinks  

#### [0:04:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=270) |  you have a flat architecture is, if

you don't have site links to show off for your website. Could you clarify that a little bit? If I missed something about it. JOHN MUELLER: It's not so much that they don't show up, but with site links, we try to figure out what the context is of other content on your website. And if we can really tell that, like, a handful of pages are really associated with this one page that's showing visibly in search, then we might show that as a site link. Whereas if everything is really flat--  

#### [0:05:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=300) |  if it's like everything is equally important

and there is no hierarchy at all-- then it's really hard for us to say, these pages belong together with that other page that we're showing in the search results. So not seeing site links-- it's kind of hard to say that that's just because of a flat architecture. We don't show site links for lots of pages, but showing irrelevant side links-- that's a really clear sign that we don't understand the architecture of the website. And your hierarchy is kind of maybe too flat for us  

#### [0:05:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=330) |  to understand which pages belong together. AUDIENCE:

Cool. Thank you. JOHN MUELLER: Cool. OK. Any other questions before we get started? AUDIENCE: John, with Movie Schema, is that intended for movie theaters or-- well, I should say, is it appropriate  

#### [0:06:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=360) |  for a site that just has information

about a movie? Like does a review have information on the actors, and directors, and that type of thing? Is Movie Schema appropriate for that? JOHN MUELLER: I think so. So I just like peeking at the documentation, and it feels like that's one of the big use cases. Like you write about movies, you review the movies-- those kind of things. AUDIENCE: OK, great. Thank you. JOHN MUELLER: Yeah.  

#### [0:06:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=390) |  All right. Anything else before I jump

into the submitted questions? AUDIENCE: I've got another question about a tweet you recently posted. JOHN MUELLER: OK, go for it. AUDIENCE: About manual actions-- you basically said it could happen where you don't include sample URLs. What scenarios would you guys not include sample URLs in a manual action?  

#### [0:07:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=420) |  JOHN MUELLER: I don't know, and-- AUDIENCE:

I gave some assumptions. I can tell you what I think, but-- JOHN MUELLER: OK. I mean, I'd have to totally guess, because I don't know. I don't know that part of the system that well just from kind of day-to-day interaction with the teams. My guess is, if it's something where it's purely site level, then it probably doesn't make sense to show individual URLs.  

#### [0:07:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=450) |  Whereas if there's something really specific on

individual pages, then we probably should show URLs. But I haven't looked into that in a while. AUDIENCE: OK, thank you. AUDIENCE: But if they never add anything to the email and you reply back, they send you an email saying-- like, I had one recently where they would reply back and then  

#### [0:08:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=480) |  show what the issue was, so-- JOHN

MUELLER: Yeah, we try to do that. Yeah. AUDIENCE: So that tells me-- OK, there was a human interaction there. It wasn't-- I mean, it's good to see that nowadays. JOHN MUELLER: We're not all robots. Yeah. AUDIENCE: Exactly. Yeah. JOHN MUELLER: Yeah, like we try to do that, where we can tell that there is a good faith effort by the site owner, that they're trying to fix something and maybe they just need a little bit more information. Then we try to do that.  

#### [0:08:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=510) |  I assume-- just for time reasons-- it's

not possible to do that with every manual action and reconsideration request that comes in. AUDIENCE: Exactly. JOHN MUELLER: All right. Let me run through some of the submitted questions, and you're welcome to jump in in between if you have any related questions or need any more clarifications. OK. For a multilingual website, if we have different language versions with one domain under different directories-- so /en,  

#### [0:09:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=540) |  /fr, et cetera-- if we have interf

Link set up in place, does it matter if the domain is a ccTLD-- like .de-- would it be better to move the website to a gTLD-- like .com? For just purely multilingual content, if it's different language versions, it doesn't matter if there is a ccTLD or a gTLD. On the other hand, if you have content that is specific to individual countries-- so for geo-targeting--  

#### [0:09:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=570) |  then that would be something where hosting

it on a ccTLD makes it a lot harder, because you can't specify the geo-targeting for other countries. So using a gTLD, a generic top-level domain like .com, would be a lot better there. But like I said, if it's purely just different language content-- if it's not specific to individual countries-- post it wherever you want.  

#### [0:10:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=600) |  Is it true that Google uses font

size to detect headers? For example, if my h2 is 35 pixels and my h1 is 25 pixels, then is Google going to say, 'well, the bigger phrase is more important' and use the h2? Second-- do you use this technology only when there is no h1 to h6 tags on a page, like if there are divs and spans? I think we do a combination of all of these things. So on the one hand, we do try to understand the headings  

#### [0:10:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=630) |  on a page, and headings are, ideally,

flagged with the h1, h2, h3 tags where you can semantically tell us what the heading of individual pieces of content on a page is. And that's really useful for us. On the other hand, we also render the pages, so we can see which text is actually visible, which text is not as visible. We see the overall layout of the page as well to better understand how things kind of work together  

#### [0:11:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=660) |  there. So from that point of view,

if you're trying to optimize at this level, which probably does not have a giant effect on your website-- but if you're trying to optimize on this level-- then I would make sure to use proper headings. And I would make sure to display those headings in a way that is relevant for the user as well. So that's kind of the direction I would go there. If we don't have any headings on a page at all,  

#### [0:11:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=690) |  then obviously, we have to guess. And

sometimes we guess right, and sometimes it's pretty hard. For what it's worth, especially with headings, that's one area where we found some trouble with switching to mobile first indexing on sites, because for whatever reason, some sites don't like to use headings as much on the mobile version of their pages. And in those cases, we do lose a little bit of information there. So that's something where-- especially  

#### [0:12:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=720) |  for images, if we don't understand which

heading this image belongs to, then it can be a bit tricky for us to show it appropriately in the image search results. AUDIENCE: Also has accessibility implications. You want to make sure that people on screen readers get a structural run down, and that doesn't work with font sizes. It doesn't matter for SEO models, but for accessibility, it does. JOHN MUELLER: Yeah. That's definitely another thing to keep in mind. I always forget to explicitly call that out, but it is something where it's good to watch out  

#### [0:12:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=750) |  for these kind of things. A web

page schema natively has breadcrumb schema field built into it. A web page-- not the schema, f but the rendered one-- possibly includes a header with a menu, and a footer, and a menu, and so on. Does it make sense to add these header-footer elements to be nested within the web page schema or separately as their own schema, since it's not natively included in the web page schema?  

#### [0:13:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=780) |  Wow, that's a confusing question with lots

of web pages, and headings, and navigation elements. So I think, just first off-- probably, this makes absolutely no difference for us at all. But when it comes to search, that's something where if there is a specific use case you have in mind with regards to the schema markup on those pages, and that use case works  

#### [0:13:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=810) |  with this kind of a setup, then

obviously go for it. On the other hand, if you're mostly worried about how Google would interpret this and use it for SEO reasons, then I would spend my time somewhere else, because this kind of level of structured data-- nesting and integration within a page-- is not something that we would show in the search result. So it's very easy to spend a lot of time on something like this and to focus on lots of theoretical variations of how this could or should be nested.  

#### [0:14:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=840) |  But if it doesn't have any effect

at all on search and what you're really trying to do is achieve something for a search, then probably it's better to spend your time somewhere else. With regards to how it theoretically would be done-- if you care about the schema.org variations-- I honestly don't know. You probably need to ask someone on the schema.org site. I believe they have a Google Group, where you can probably ask this kind of a question, but again, for SEO reasons,  

#### [0:14:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=870) |  I don't think that changes anything at

all. When a bot is scanning a page and find schema markup, does it validate the schema accuracy through schema.org-- which means sending a bot to validate for every schema-- or does it validate via Google's own database? We validate the structure data with our own systems, so I believe we regularly sync those with the schema.org  

#### [0:15:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=900) |  setup. I don't know what the technical

implementation is there, with regards to syncing the schema specifications, but that's something where we think with the schema.org setup, and we have our own set of rules as well with regards to which fields and values are required or optional, or what kind of restrictions apply to individual fields. So that's something where that essentially happens  

#### [0:15:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=930) |  on our side in the background and

is not something that is done one by one when crawling and indexing to web. So that's another reason, also, why using HTTP or HTTPS when it comes to the JSON-LD markup that you have there, it doesn't matter so much for us. Because we understand http://schema.org is the same as https://schema.org, and it just tells us we should use our validator for structured data.  

#### [0:16:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=960) |  It doesn't mean that we need to

double check if this HTTP or HTTPS URL is the right one. So that makes it a little bit easier and allows us to crawl and index a lot faster. Does Google, which remains very strict with webmasters with regards to correct information for users, do the same with new sites in some manner? It is often noticed that many new sites nowadays publish fake news regularly and move to next page news  

#### [0:16:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=990) |  when the truth comes out frequently without

clearly declaring the said news came out false with relevant apologies. That's a complicated sentence. Does Google downgrade their rankings based on some trust site's logic? So I am not aware of us explicitly looking for this kind of information within webpages to see if, like, is this the correct information or not? But I am pretty sure you would see a lot of indirect effects  

#### [0:17:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1020) |  there where, if a website regularly posts

information that is not correct and users end up not trusting that website, then that's something that would probably be reflected in our search results over time. And so that's not that Google's algorithm goes out and kind of fact checks the math on all of these pages, and if it's not correct math, then we will demote them in search, but it's more that we see that there are lots of good signals for this page  

#### [0:17:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1050) |  and not a lot of good signals

for another page. So we'll try to rank the good page a little bit better. If we have critic reviews with user reviews, how should we implement schema? One schema for user reviews and one schema for critic reviews? Which ratings will Google display in the search results? What's the best practice when we have both kind of reviews? So my understanding is that both of these types of structured data would be shown slightly differently  

#### [0:18:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1080) |  in the search results. So my general

recommendation here, when you're faced with a situation where you have, essentially, different types of structured data on a single page-- where only one of them is shown in the search result-- is to try to make a decision yourself. So instead of implementing all of this markup on a single page and saying, well, I hope Google chooses the right one and you don't really know which one is the right one, then I would make a decision and say, well, I  

#### [0:18:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1110) |  want Google to show my critic reviews.

Or I want Google to show my user reviews. Therefore, I will explicitly mark those up and maybe not mark up the other parts. So when you're seeing this kind of situation where multiple kinds of search results are possible but you can't combine them, then pick what you would like to have shown and be as clear and direct as possible with regards to that so that our systems can pick it up and say, oh, these are clearly user reviews.  

#### [0:19:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1140) |  They're marked up properly. We should show

them in search. A question about adding no index tag to 404 pages. In my understanding, if the page was removed and has a 404 status on it, it's already telling crawlers all they need to know. So adding a no index tag isn't really adding any value, apart from the speed of removal from the index. But if my clients already included no index tags on their 404 pages, are there any negative consequences of that site?  

#### [0:19:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1170) |  So the easy answer is, when we

see that a page returns 404, we ignore all of its content. So whether or not it has a no index on there, whether there's-- I don't know-- a really fancy picture on there or not, whether the 404 page is essentially just the text 404, if it's a really fancy 404 page-- we don't see any of that at all when it comes to search. We see the status code 404 and it's like, that's OK. That's enough for us.  

#### [0:20:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1200) |  So adding a no index tag there

wouldn't change anything at all, neither positively or negatively, nor would it speed up the removal from the index. As soon as we see the 404, we understand, well, this is probably something we don't need to index. So with that in mind, if they already have a no index on the 404 pages, that's fine. If they don't have it there, you definitely don't need to add anything. If a web page has millions of URLs  

#### [0:20:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1230) |  with parameters that don't change the content--

only slightly-- do you recommend to configure, in Search Console, this parameter? Is it strongly recommended? I think it really depends on the website itself a little bit. To a large part, we try to learn these parameters automatically. And so often, if you go into Search Console, into the tool, you'll see Google has already determined that these parameters are less important or more important,  

#### [0:21:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1260) |  for example. And in a lot of

cases when we have worked with a website for a while, then we'll figure out which parameters are important, which ones are not important, and kind of treat that appropriately automatically. If you're starting out new with a new website or you're adding new parameters to an existing website and you really have kind of millions of URLs that use these parameters and maybe thousands of URLs that don't use any parameters which  

#### [0:21:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1290) |  are kind of the normal content that

you would like to have indexed, then using the URL parameters tool is a great way to let us know about that. So that's something where I would use it-- especially if you're starting out, especially if you're making bigger changes on your website-- but if it's been running like this for a number of years, probably we already figured that out. On a price comparison website, we also have shop and seller who sell products  

#### [0:22:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1320) |  on their site related pages. On the

shop pages, we have shop info, and ratings, and reviews, so we've implemented organization markup, with reviews and ratings, in February. But still, we have not gotten any impression rich results yet for those pages in the search results. I'm seeing our competitors are displaying rich results, though. What can we improve here? Should I implement rating and reviews in separate schema, because that's the only thing I want to see with our shop pages  

#### [0:22:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1350) |  in search. So I hope the review

stars are not the only thing that you want to see in search but, rather, kind of your content should be visibly indexed anyway. That's kind of the most important part. So looking at the review markup, one of the things that has changed recently-- I don't know if that was in February or sometime before-- like everything is a blur, that's more than a couple  

#### [0:23:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1380) |  of days back. One of the things

that has changed there is that we only show the review markup for a limited number of objects. So that's something where maybe you're marking something up with a review that is not one of the supported types, and that might be a reason why we might not show that in the search results. The other thing to keep in mind is that, especially with review markup, reviews should be specific to the primary object of the page.  

#### [0:23:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1410) |  So if you have a shopping comparison

site and you have one page with lots of products on it, and it's just from this one company for example, then that wouldn't be relevant to mark that up with the review markup, because you don't really have one primary item on the page. You have lots of different items, whereas if you have one product that you're selling which happens to be from one manufacturer  

#### [0:24:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1440) |  and the reviews are all specific for

that one product, then that would be a good use of the review markup on the page. So structured data should be as specific as possible to the primary object of the page and not something general for a page. Being a newbie blogger, how much time will my site take to rank in the Google search results after implementing both on-page and off-page SEO techniques? So I don't think there's any specific amount of time  

#### [0:24:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1470) |  for a site to rank in the

Google search results. It's really kind of a tricky question in itself, because often, we just index websites as quickly as we can, but that doesn't mean that we show them as visibly as possible. So everything around ranking depends a little bit on what else is happening in those search results. We might be indexing a page within a couple of hours,  

#### [0:25:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1500) |  a couple of minutes, depending on the

website. But if you're targeting a topic that is very competitive in nature, where other people have spent a decade or longer working on their website to improve it-- to make it as fantastic for that one question as possible-- then it's not going to be something where you can just implement a little bit of markup and do some off-page SEO techniques to suddenly rank above these other people who  

#### [0:25:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1530) |  have worked so much and done so

much good stuff to appear in the search results. So that's something where there is no fixed amount of time. It doesn't mean that you'll never be able to show above other people in the search results, but it does mean that when we look at the search results, we need to figure out what is relevant for the user. And if we have a lot of information that's telling us these existing pages are really relevant because they've been doing really well for such a long time,  

#### [0:26:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1560) |  then that's a strong signal for them.

On the other hand, if we see these existing pages haven't been updated in a long time and they're outdated, they're obsolete information, and there's a new website out here that's providing fantastic information talking about those themes in a way that others haven't before, then we might choose the new website instead. So these kind of things are really impossible to say, and it's impossible to give a time  

#### [0:26:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1590) |  until the website will rank in the

Google search results. I'm wondering if the current COVID-19 crisis will push back Google's plans for mobile first indexing for all sites from September to later this year or early next year? Good question. I'd love to have your all's input on that as well. So I've been in touch with a mobile first indexing team,  

#### [0:27:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1620) |  and for the most part, they're still

seeing sites preparing and getting ready for mobile first indexing. So it feels like people are still working on the website, even if they're maybe not working in the office anymore. On the other hand, the whole situation is really hard to take and really throws a lot of companies off. Throws a lot of websites off, and people working on websites-- it's very challenging. So that's something that might say,  

#### [0:27:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1650) |  well, we're seeing people are struggling with

this, and we don't want to create an extra burden of saying, well, you have to do all of this extra work until September. Maybe we should push it back. But it would be really useful for me to get some feedback from any of you, on Twitter or where else, to kind of let us know, is this something you're seeing people struggle with? Or do you think this is something that people are planning to do, regardless?  

![](https://i.ytimg.com/vi/AoZbAinDg0E/maxres2.jpg)



#### [0:28:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1680) |  Let me know. I'm happy to pass

that on to the team and to figure something else out. My guess is, we will make a decision on this maybe sometime in the next month and then either update-- a blog post or tweet something with the official account-- with regards to the actual date. I feel like Google sold me a bad domain and is doing nothing about it. I bought a domain from Google in March a few days  

#### [0:28:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1710) |  after having my old site without penalties.

Being redirected to a new domain is when I found out about a pure spam manual action. Two reconsideration requests have been denied. My site has completely new content and is free of spam. What are my options besides asking the community? Because even they don't know. So that's really hard to say. I mean from our point of view, the whole search ranking side  

#### [0:29:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1740) |  of things is not something that the

Google domains team works on, so they would not know which domains had a manual action or not. In general, whenever you're buying a new domain name and you want to move from one domain to another, it's worthwhile to do some research and to figure out what happened with the domain name that you're considering and to really look into the details of what was hosted there in the past.  

#### [0:29:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1770) |  Is this something that I can deal

with? Do I have to deal with anything or not? Is it something where maybe there are a whole bunch of crazy links pointing at the domain name and it was used by-- I don't know-- spammers hosting all kinds of crazy content? That's something where you, if you move to that domain, then you kind of have to live with that and work on ways to improve that situation. So that's something where you really need to do some research ahead of time  

#### [0:30:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1800) |  before moving a website to another domain,

especially if it's something that was used in the past. With regards to this specific case, it's impossible for me to say, because I don't know the websites involved. But generally speaking, a pure spam manual action is based on the content. It's not based on a domain. It's not something that would be transferred from one owner to the next owner. It's really based on the content that you host there. So if you're seeing a pure spam manual action, then that's  

#### [0:30:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1830) |  really something where you need to think

about your content really hard and think about, why would my content, perhaps, trigger this? And it's really hard to say, because I don't know what the site is here. It's certainly possible that the web spam team gets one of these things wrong, and with a reconsideration request, that's a great way to get it in front of another person on the web spam team.  

#### [0:31:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1860) |  But it feels kind of unlikely that

you would have two reconsideration requests and the initial manual action happen. If there's really nothing with regards to the actual content here, that's problematic. So I mean, it's certainly possible that you have really bad luck. If you really feel like it's one of these cases where you really have fantastic content and the web spam team just  

#### [0:31:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1890) |  doesn't realize it, then feel free to

ping me on Twitter so I can take a look and pass that on to the web spam team to double check. But it really feels kind of iffy, just based on the question itself. I hope you're doing well despite all of this coronavirus crisis. The question I have is the following-- we recently transferred our website example  

#### [0:32:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1920) |  account to a multilingual one. So for

most language versions, we have the ordinary setup, such as example.fr, example.nl, example.es. But for the Swedish extension, our International Sales Director requested to keep the original domain of the acquired company. So instead of having the ordinary example.se, we have random.se. I was totally against this setup, because I didn't believe Google will see this domain  

#### [0:32:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1950) |  extension as the primary domain Swedish extension

but will treat it as a separate domain. Please clarify from Google's perspective how this is going to be seen by Google. OK. So in general, these are all separate domains. We would not infer from just the example part in the beginning that these domains belong, somehow, together. Essentially, these are completely separate websites from our point of view.  

#### [0:33:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=1980) |  However, for most kind of multilingual setups

or international setups, you would use something like the hreflang annotations between maybe the home page, maybe between other pages on the website. And for hreflang, it doesn't matter which domains you use. So if you have example.fr and random.se, you can have the hreflang annotation between those two, and that tells us all we need to know. That this page on random.se has an equivalent  

#### [0:33:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2010) |  in French on example.fr. So from that

point of view, it doesn't really matter with regards to which of these domain names you use for which country version. For the country versions, it sounds like you're using country code top level domains, which is great. It means geo-targeting is already automatically handled. If you just want international language versions, then you don't really need to use country code top level  

#### [0:34:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2040) |  domains. But if you want to, that's

also fine. So from my point of view, I wouldn't see this as any kind of a deal breaker or any critical issue, if you don't have example.se and instead have random.se Question about a multilingual website, if we have a proxy buying website that helps users from different countries buy clothes from a Chinese auction website.  

#### [0:34:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2070) |  We use an API to get the

product information, present in our website in English, and German, et cetera. While we manually translate information about the product categories and provide UIs in each language, there is no realistic way for us to manually translate the product names and descriptions. If we leave them in Chinese, that's not a good user experience and also does nothing for our English SEO. Providing automatic translations would greatly help our users. However, it looks like automatically  

#### [0:35:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2100) |  translated content is against the webmaster guidelines.

Do we have to leave the product in Chinese to avoid a penalty? So that's an interesting question. I think there are probably lots of things that could apply here as well. But in general, I would see the automatic translation as something where, in many cases, it's just the quality of the translation is really bad, and that's one of the primary reasons why  

#### [0:35:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2130) |  we say this is not something that

you should be doing. It might be something that changes over time where, over time, if we see that these automatic translation setups are able to create content that's of really high quality and really easily understandable, then maybe you can do that. Maybe that's something that would make sense there. But overall, we often see that these automatic translations are just kind of borderline gibberish,  

#### [0:36:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2160) |  even, where it's really hard to tell

what those products, in this case, would actually be about. So that's kind of the primary consideration I would have here is, if you're taking content and you're just automatically translating it into a number of different languages, and the content that you get out of this is of such low quality, then keep in mind that we will look at those pages and say, well, this is low quality English content. It's low quality German content.  

#### [0:36:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2190) |  Why should we show it at all

in our search results? So it's not so much about whether or not you use automatic translations or human translations. It's just, well, the content is really bad and hard to understand. Another thing that sometimes plays a role-- I don't think, if you have this many products, so much-- is that a lot of times, it's not just a matter of translating a product name or product description.  

#### [0:37:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2220) |  But actually, you kind of have to

localize it, and write in the way that users would expect, and categorize and group your content in a way that users would expect for those languages. And that can sometimes be subtly different across different languages, different cultures, those kind of things. So just going back to your question here-- should you post it in Chinese or post it in English? I think the general configuration is something  

#### [0:37:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2250) |  you might want to reconsider. I don't

think it's something where, like, the manual web spam team will take a look at this and say, oh, this is terrible. We should remove the whole website. But more kind of, from a quality point of view, our teams might look at it and say, well, we should not be ranking this website, because it's really not that useful of content. For the new image license metadata for Google Images which can result in a badge in Google  

#### [0:38:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2280) |  Images, I know some large photo sites

are adding necessary structure data and license pages, but some are adding license pages per image. And that's resulting in the addition of tens of millions of new URLs to the site, basically doubling the number of pages. For example, a site with 30 million images might be adding 30 million license pages. For some of those sites, their URLs were both crawlable and indexable, so those sites are adding double the amount of URLs that  

#### [0:38:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2310) |  can be indexed. Is Google's recommendation to

disallow the licensed URLs and robots' text? Do the licensed URLs need to be crawled by Google in order for the license badge and Google Images to show up? I can see potential problems with letting Google crawl and index tens of millions of additional new URLs. So the additional URL here-- I had to look this up.  

#### [0:39:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2340) |  I think the same question was submitted

last week as well. The additional URL is that, on a per image basis, you can specify metadata for license of all images. And per image, you can specify where the user can buy or license this image. So essentially, it's a link to a checkout page, if you will. From that point of view, like other checkout pages, you don't necessarily need to have those indexed. So if you use a no index on those pages,  

#### [0:39:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2370) |  if you disallow crawling of those checkout

pages, then that's perfectly fine. That's totally up to you. So from that point of view, you can definitely block those from being indexed. It might make sense to find other ways to deal with that. For example, if you have the image landing page, you could just have a checkout button there, and then people will go to the same image landing page and kind of be able to do the checkout flow there.  

#### [0:40:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2400) |  But ultimately, you have to work with

whatever restrictions you have in your CMS, and sometimes just creating a separate page for the checkout is the easiest approach. So that's totally up to you. In Search Console, it indicates there are no security issues, so it's not possible to request a review. But if you search for our company name, the 'this site may be hacked' message still comes up. How can it be removed if Google Search Console believes  

#### [0:40:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2430) |  everything is OK? I guess. So I

did a quick search for this company name, and the search results it shows for your home page is all about pharmaceuticals. So my guess is, your website is still hacked. Looking at the website directly, I see it shows normal content, so this seems like a traditional kind of a hack where, essentially,  

#### [0:41:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2460) |  the webmaster-- not the webmaster-- the hacker

is cloaking to Google and probably sending users to a different page when they click on your search result. So that's something where you probably still need to resolve that issue to make sure that we can understand that your page is about-- I don't know-- I think it was like silverware or something like that-- and not about pharmaceuticals.  

#### [0:41:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2490) |  So the best way to do that

is probably to double check in our Help Center. We have a whole section on dealing with hacked websites. Not sure if it's in Help Center or the Developer Documentation, but one of those two places. And it lists, essentially, the same kind of hack that you're seeing there, where when you go to the page yourself, you see the normal content in the search results and you see the hacked content. And it has kind of a step-by-step guide  

![](https://i.ytimg.com/vi/AoZbAinDg0E/maxres3.jpg)



#### [0:42:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2520) |  on how to deal with that. What

you can do, once you've resolved that issue and if you still don't see any kind of the security issues being flagged in Search Console, you can just use the Inspect URL tool and resubmit the home page for crawling and re-indexing. And we'll pick that up usually within an hour or so. So that's kind of the direction I would head there. The tricky part with this kind of hack is, it essentially means that the hacker has access  

#### [0:42:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2550) |  to your server or had access to

your server, which means that you also need to double check all of the verification settings in Search Console. So on the one hand, your verification tokens. On the other hand, any other verification tokens that might be on that website. Because we've frequently seen that hackers will take over a website. They'll verify the site in Search Console or kind of, like, re-verify it with their own account,  

#### [0:43:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2580) |  and then they'll use their own account

and say, oh, my website got hacked. Google, can you get rid of this warning, because I fixed the hack. And hope that someone from the web spam team removes the 'this site is hacked' label, even though it's still the hacker who's asking for this to be done. So that's something where you really need to double check all of the verifications on your website. Make sure that only you are the one who's  

#### [0:43:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2610) |  actually a verified owner. And then, of

course, by following the guidelines or the guide in the Help Center, make sure that your server is locked down appropriately so that the existing hacker or any other hacker won't be able to get in again. I think it's sometimes a really frustrating process, but it's really important to follow through with those steps. And if you have difficulties along the way with that process, I would strongly  

#### [0:44:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2640) |  recommend getting help from someone who has

a little bit more experience in this, because they'll be able to see those places where hackers traditionally hide their code, and help you to really clean things out completely, and to get it resolved as quickly as possible. [EXHALES] OK. AUDIENCE: --to have the two-step authentication. JOHN MUELLER: Two-step authentication. Yeah, I think that always makes sense for your accounts. But if someone is hacking your server,  

#### [0:44:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2670) |  then the authentication on your own account

is kind of, yeah, not that useful. But it is something where it's-- I don't know, the first time you get your site hacked like that, it's so frustrating and is really hard to understand what you should be doing. So it's definitely worthwhile getting help. Maybe go to the Webmaster Help Forum, if you're really unsure about things. There are people that are active in the Webmaster Help Forum  

#### [0:45:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2700) |  who have seen a ton of hacks

and who can help you to find some things. But probably, if this is a company website, you probably want someone that you can interact with one-to-one and just get it resolved as quickly as possible and understand exactly what happened so that you can make sure to avoid that in the future. All right. Let's see if anything else popped in.  

#### [0:45:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2730) |  Otherwise-- yeah, I think-- oops. Someone was

waiting for that link. Let me just copy that. That was 30 minutes ago. Oops, sorry. Yeah. AUDIENCE: Hey, I have a quick question. JOHN MUELLER: Sure. Go for it. AUDIENCE: Is that special announcement COVID schema live yet? JOHN MUELLER: I don't know if it's live yet.  

#### [0:46:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2760) |  I think it's-- as far as I

know, it's still in the rollout phase. I don't think it's live in general yet. AUDIENCE: OK, thank you. AUDIENCE: John, I have two questions. I haven't been here in almost half a year. I don't know how long it's been, but somewhere around there. A quick question-- the hashtag [INAUDIBLE] adding it before their actual-- like in the title tag.  

#### [0:46:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2790) |  Would that affect the home page? The

actual title-- like if adding a hashtag prior to the first word, does that affect the main keyword for the actual home page? So for instance, if I'm selling toys, and I have the hashtag, and then type the actual word, and then so on and so on.  

#### [0:47:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2820) |  Because I'm still having issues with that,

because I'm having an argument with someone on that. JOHN MUELLER: I honestly don't know. My feeling is, we would probably understand to ignore the hashtag symbol and just focus on the word, which is probably what you're trying to do. But I don't know if we would use that combination of symbol plus word as something unique.  

#### [0:47:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2850) |  AUDIENCE: So you ignore it? JOHN MUELLER:

My guess is, we would just ignore the hashtag symbol and focus on the word itself. AUDIENCE: OK. JOHN MUELLER: But that's something that you can probably test by including some random word with a hashtag and seeing if you can search for it with just the random word without the hashtag symbol. AUDIENCE: It's hard when someone believes that the hashtag-- you know how it is. JOHN MUELLER: Yeah. I mean, it's not going to make your site rank for that  

#### [0:48:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2880) |  keyword anyway automatically. So just using, like,

#toys or-- I don't know-- like #cheapcreditcards in a title, I don't see that making any difference. It just looks kind of weird in the search results. AUDIENCE: OK, and then also, you said something a while back on Twitter. And I know a lot of people quoted that, also, here in the hangout. But you said that guest posts placing a link back to your site from a guest post is unnatural.  

#### [0:48:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2910) |  But what if a person does that

on a massive basis? Like do you just ignore that? Because I think Gary said, in this other-- JOHN MUELLER: Yeah. Yeah. AUDIENCE: --tweet. JOHN MUELLER: Usually, we would just ignore that. AUDIENCE: OK. JOHN MUELLER: So that's the kind of thing where, if we can tell that this is clearly an unnatural link, we would essentially just try to ignore that. AUDIENCE: So what if the guy has, like, 40,000 or 50,000? You would just ignore that?  

#### [0:49:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2940) |  JOHN MUELLER: Yeah. It sounds like they've

been busy, but it's easier to ignore a lot of links than to ignore the individual ones. Because if our algorithms are kind of with that mindset of like, we don't know if we can trust this link-- and if we can see that there are lots of these links out there that are essentially following the same pattern-- it's a lot easier for us to just say, oh, all of these are the same bucket. We should just ignore it those. AUDIENCE: OK.  

#### [0:49:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=2970) |  Thanks. Appreciate it. JOHN MUELLER: Sure. AUDIENCE:

Can I ask you a quick question? JOHN MUELLER: Sure. AUDIENCE: About the-- in Search Console international targeting and the geo-location there for country and the hreflang you can specify reach-- do they do basically the same job? Are they [INAUDIBLE] to each other or are there a lot of differences in scope? JOHN MUELLER: Geo-targeting and hreflang are, essentially, different things,  

#### [0:50:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=3000) |  but people tend to use them for

related things. So hreflang essentially helps us to swap out the URL if we rank one of the URLs of that site. And geo-targeting helps us to understand that this is probably a local page, so if someone is looking for something local, we would try to show that. So the end result can look kind of similar, but they are technically different things. I think it's pretty confusing to have kind  

#### [0:50:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=3030) |  of this slight overlap there. I'd love

to have some easier setup for all of the international things, but all of the proposals I've put together ended up being much more complicated than what we have now. So I don't know. If someone has a really good idea for how to let search engines know about international versions of a website,  

#### [0:51:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=3060) |  that would be fantastic. But it's been

challenging. AUDIENCE: Got you. OK. Fair. JOHN MUELLER: All right. More questions from any of you? AUDIENCE: Hi, Mr. Mueller. JOHN MUELLER: Hi. AUDIENCE: This is me, Mohammed, from Search Engine Journal. I'm kind of chasing you with this scholar question of [INAUDIBLE].  

#### [0:51:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=3090) |  On the last call, you said you

will look into the issue why [INAUDIBLE] pages pool small images. We'd like to kindly check if you did get the chance to look. JOHN MUELLER: We have been looking for that, and there's some work being done from the team to make, I think, the information a little bit clearer and to be a little bit more consistent, internally, with how we deal with those kind of issues.  

#### [0:52:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=3120) |  So I don't have a complete update

for you yet, but people are working on it. So hopefully-- AUDIENCE: Thank you very much. JOHN MUELLER: --we'll have something soon. AUDIENCE: Thank you. JOHN MUELLER: Sure. Wow, we're running out of questions. I can't believe it. Let me see-- there's one in the chat. We have separate pages for our shop where there are only two things in that page. One is the shop info, and two--  

#### [0:52:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=3150) |  ratings and reviews. And our users usually

come for the ratings and reviews. So I want to display the ratings in the search results prominently. Yeah, so I think, if on the product pages you have reviews and ratings, then that's a great use of the structure data for those individual reviews and ratings. I would just make sure that you're following all of the guidelines there, because lots of people like to use the review structure data.  

#### [0:53:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=3180) |  And that's something where our systems and

our engineers are kind of more and more picky with regards to what we actually show in the search results. So make sure you're following the guidelines as completely as possible so that it's clear that what you're providing on your page is actually what makes sense to show in the search results. Does a date in front of a meta description affect the ranking if the blog post is from previous years?  

#### [0:53:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=3210) |  No, not necessarily. So a lot of

times, when we recognize a date on a page, we can show it in the search results directly, and that's not because it's in the meta description. But we show it next to a snippet, which is usually what we take from the meta description, and we display it there. But that's not necessarily a ranking factor, because it's not always clear what a user is looking for.  

#### [0:54:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=3240) |  Are they looking for kind of the

newest information on this topic? Or are they looking for research information on this topic, which might be a little bit older? So just because there's a date being shown there, that doesn't necessarily mean that that's kind of a positive or negative ranking factor in any way. Are you seeing any potential shift impact of COVID-19 on the proportion of mobile tablet desktop searches? I have not seen anything there.  

#### [0:54:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=3270) |  I don't know if we would have

any data on those changes at the moment. I have no idea. It seems like an interesting question. If you have a website that gets a lot of impressions, you can probably double check that yourself in Search Console and see if there are any changes there. It'd be interesting to look at across a number of different web sites, but I don't know if that would be something that we would publish or if it's easier for you to kind of work  

#### [0:55:00](https://www.youtube.com/watch?v=AoZbAinDg0E&t=3300) |  together with a bunch of other publishers

and combine that data and look at it from your site. All right. Any last questions before we head out? Martin! No? AUDIENCE: I just-- I just have to leave. Bye bye! JOHN MUELLER: Just waving. OK. AUDIENCE: Just waving. JOHN MUELLER: All right. Fine. So the next hangout is lined up on Friday.  

#### [0:55:30](https://www.youtube.com/watch?v=AoZbAinDg0E&t=3330) |  There's a German one lined up on

Thursday, if you want to practice your German. So if there's anything that we missed, feel free to jump into one of those hangouts. Thank you all for dropping by, and I hope you all stay safe and healthy and are at home, I guess, as much as possible. See you next time! Bye, everyone. AUDIENCE: Thank you. AUDIENCE: Thank you, John. AUDIENCE: Bye.  