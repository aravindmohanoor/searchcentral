[![English Google SEO office-hours from March 12, 2021](https://i.ytimg.com/vi/kzM7fi43cMc/hqdefault.jpg)](https://www.youtube.com/watch?v=kzM7fi43cMc)

## English Google SEO office-hours from March 12, 2021

This is a recording of the Google SEO office-hours hangout from March 12, 2021. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Find out more at https://developers.google.com/search/events/join-office-hours



Feel free to join us - we welcome webmasters of all levels!



#### [0:00:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=0) |  JOHN MUELLER: Hi, everyone. And welcome to

today's Google Search Central SEO Office Hours. My name is John Mueller. I'm a Search Advocate on the Google Search Relations team. And part of what we do are these Office Hour Hangouts where people can join in and ask their questions all around Search and their websites. So many people joining us today. It's fantastic. Cool to see a bunch of new names and faces as well, so that's always neat. And a bunch of things were submitted on YouTube as well.  

#### [0:00:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=30) |  But as always, maybe we can get

started with some first questions. And I think what probably works easiest is if you're live in here, just use the Raise Hand feature. And then I'll try to go through in that order. And wow. OK. Lots of people raising hands already. OK. Praveen, maybe you can get started with your question. PRAVEEN SHARMA: Hey. Hi, John. How are you?  

#### [0:01:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=60) |  So it's a bit weird and long

question, so please don't mind. There's this website we have which is a global website. And they have pages in multiple languages, like English, and like Japanese and Korean. So this website has implemented HREF and tags and all that stuff. And they're doing pretty good in Google in all the local regions. The problem is that, in South Korea, there is a local search engine called Naver. And Naver has problems with these HREF and tags. Like, it doesn't understand them. And this website has this languages.  

#### [0:01:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=90) |  Like they have used a directory system,

folder system for multiple languages. They're not using subdomains or separate domains. And this makes it even harder for Naver to understand that this website is in multiple languages. So the solution-- so what it does is it shows English version to the Korean audience for Korean queries, and that's a problem. The management had decided we should make a separate website for Korean audience in only Korean language. And the concern from Google's point of view  

#### [0:02:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=120) |  is that if we allow that website

to be indexed by Google too, can that new website impact performance of the existing global website? Is there a possibility that-- because Google can figure out that both these websites belong to the same domain, and they are basically targeting the same audience. But that new website won't be just copy paste. It will be a website with new user interface, new fresh content, and everything will be new. The only concern is can the new website impact performance of the existing website? Because that existing website is doing pretty good on Google.  

#### [0:02:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=150) |  JOHN MUELLER: I think if it-- whoops.

A little echo somewhere. I think if it's a completely separate website, then it's a completely separate website. So that's no concern from that point of view. If it's just on a different domain and it's essentially a part of the same set of pages, you can still use hreflang between those different domains. So hreflang doesn't have to be just within one domain.  

#### [0:03:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=180) |  So that might be another option where

you can say, well, they don't understand hreflang but, if it's on a different domain that works for them, and Google understands hreflang and can do it between domains, as well, then you can combine those two options. PRAVEEN SHARMA: We actually don't want to confuse Google with like we have so many pages on [INAUDIBLE] system, and then one is on the subdomain. So we just want to keep things simple. So the only-- new website should not impact the performance of the existing website. I think that's clear.  

#### [0:03:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=210) |  JOHN MUELLER: Yeah. I think what will

happen is you will compete with yourself, with your existing website. PRAVEEN SHARMA: Yeah. That's fine. That's fine. JOHN MUELLER: If you're OK with that, that's fine. But it sometimes makes it a bit harder to rank well for some queries because both of these versions will have some amount of signals and value in Google's eyes. And that means maybe both of them will be kind of mid-range with regards to ranking.  

#### [0:04:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=240) |  But if these are queries where your

site is very visible anyway, then probably it doesn't make a big difference. But essentially, that's up to you. It's not that the [INAUDIBLE] team will look at this and say, oh, two websites is too much. PRAVEEN SHARMA: Sure. Thank you. That's helpful. Thank you. JOHN MUELLER: Sure. Shao Chieh. I cannot pronounce your name. Sorry. SHAO CHIEH LO: Thank you. Thank you. I also typed my question here. So my question is a while ago I was  

#### [0:04:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=270) |  reading one of Google's guides. They say

that do not index internal search results, because you can only not search user intent well. I agree that if it's an informational site, because people won't be landing on the page that directly answers your question. However, I'm not quite sure it's also the same for e-commerce site. For example, when you are searching for, for example, slim computer, and the first result is actually Amazon's internal search result page. And as a customer, I won't be happy seeing that,  

#### [0:05:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=300) |  because it doesn't provide a lot of

options for me to buy. And so my question is just that, for very like transactional intent keyword e-commerce site, it's also not recommended to index internal search page? JOHN MUELLER: So I think that's something where you could argue that these are more like category pages,  

#### [0:05:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=330) |  or where you can say, well, it's

more like a category page and it's indexable. The tricky part with internal search pages is that it's often an infinite space, in that you can enter any random words and it'll create a web page for it. And that's something you kind of want to avoid. But if there are specific topics where you say this is kind of like an important topic, then you can definitely keep that indexed. It's not that the [INAUDIBLE] team is reviewing these and seeing, oh, internal search, it should be spam kind of thing.  

#### [0:06:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=360) |  It's more a best practice for crawling

and indexing that you provide pages that are useful for users. And if these are internal search pages that are more like category pages, that's fine. SHAO CHIEH LO: I see. Thank you so much. So would you recommend only pick some of those internal search pages to index while block the majority of them? JOHN MUELLER: Yeah. I think if you can do that, that's what I would do. Take a list of keywords where you're saying these are OK,  

#### [0:06:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=390) |  and everything else just block those. Just

to avoid the situation that people create random pages for random words. Or also what I've sometimes seen is people create pages for words that you don't want to rank for. Like, I don't know, maybe they're searching for medical terms and your website is about computer products. Then you don't want to rank for that content. SHAO CHIEH LO: I see. Thank you so much. JOHN MUELLER: Sure. David.  

#### [0:07:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=420) |  I think you're muted or your microphone's

not working. DAVID EHRENTREU: Yes. No, I was muted. Sorry. Thank you. OK. I have a few questions, but I think they're quick so I'll try to get through them. Number one is if enhancing core web vitals, let's say, we get rid of a bunch of old scripts and reduces the page size in half, would that correlate with an increase of crawl rate budget?  

#### [0:07:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=450) |  JOHN MUELLER: Maybe. Maybe. So there are

two things there. On the one hand, if we can access your HTML pages faster, we can probably crawl more. So that would go into the crawl budget side of things. The other part is if we can render your pages faster, if there are JavaScript pages, then we can also get through them faster. But it all depends on the demand as well. So for crawl budget, we have kind of the capacity of the website and the demand from our side.  

#### [0:08:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=480) |  DAVID EHRENTREU: Got it. Now the other

question is a little more difficult. Basically, there's the amount of pages that are being indexed by Google in the coverage report. And then if I go to the internal link report in the Link section, I see that all the links that are in the header and footer are the top ones with the same number pretty much. So I know that it's collecting those as internal links  

#### [0:08:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=510) |  to report on, regardless of its effect

or impact. But the number is a tiny fraction of the total indexed pages. And when I do a site search on Google, it's somewhere around the range of the total index pages in the coverage report. But then I go to the Internal Link section and-- I'm talking about index is six million, and in the internal links is 30,000 for all of those header footer pages.  

#### [0:09:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=540) |  And those are on every one of

those pages. So what would that hint to me? JOHN MUELLER: Nothing really useful probably. It's just for these reports, we take a sample of the pages from your site. So they're not meant to be on the same level as the index coverage report. DAVID EHRENTREU: Got it. So it's just to get an idea of which internal links are found more often than others? JOHN MUELLER: Exactly. DAVID EHRENTREU: OK. And then the next thing is, you mentioned  

#### [0:09:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=570) |  that about the URL parameters for search

pages, if you're dealing with a site that the search is set up that it autocorrects and redirects to a proper search that we want that's in our site map that's relevant, is that a redirect that will hurt in terms of crawl budget? Because someone could input anything. Even though it will find the right page, probably the most relevant on the site, is it going to impact anything,  

#### [0:10:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=600) |  and how would be the best way

to implement? JOHN MUELLER: How are you redirecting there? DAVID EHRENTREU: I would have to speak to the dev team but I don't know. They have their own internal link system algorithm. JOHN MUELLER: So usually with redirects, we follow I think a small number of redirects immediately. And it's kind of seen as a part of the same request. And I think the limit is something like five, something like that, where if there are five redirects in a row,  

#### [0:10:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=630) |  we'll just follow that and look at

the final content and treat that as one request. If it takes more than five steps, then we would treat that as separate requests. But usually, for something like this, you would have one step. And you'd be on the category page or something like that. And that's perfectly fine. DAVID EHRENTREU: OK. All right. Thank you. JOHN MUELLER: All right. Evan. EVAN GILGENBACH: Yeah. So I think I was a little faster on the hands up,  

#### [0:11:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=660) |  but my colleague Derek could probably explain

the question more succinctly than I can. Derek, if you want to go ahead. DEREK FITZPATRICK: Sure. Can you hear me? JOHN MUELLER: Yes. DEREK FITZPATRICK: Great. So our question has to do with core web vitals. I'll post it here in the chat. Basically, we want to know how it relates to AMP. So we have enhanced our site for AMP. And 90% of our mobile traffic goes to AMP pages.  

#### [0:11:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=690) |  But now we're addressing core web vitals

stuff. But in our Core Web Vitals dashboard, it looks like only 50% of our pages are hitting good marks there for mobile. So we spent a lot of time doing AMP. Are we going to be penalized for the pages that we have that are not AMP that are performing poorly on the web vitals side? JOHN MUELLER: I don't think you would be penalized for that in that sense. But what happens on our side with regards to the core  

#### [0:12:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=720) |  web vitals is we use the Chrome

User Experience report data as the baseline. And we try to segment the site into parts, what we can recognize there from the Chrome User Experience report, which I think is also reflected in the Search Console report. And based on those sections, when it comes to specific URLs, we will try to find the most appropriate group to fit that into.  

#### [0:12:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=750) |  So if someone is searching, for example,

for AMP pages within your site and you have a separate AMP section, or you have a separate AMP template that we can recognize, then essentially we'll be using those metrics for those pages. It's not so much that if there are some slow pages on your site, then the whole site will be seen as slow. It's really for that group of pages where we can assume that when a user goes to that page, their experience will be kind of similar.  

#### [0:13:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=780) |  We will treat that as one group.

So if those are good, then, essentially, pages that fall into those groups are good. The tricky part I think with the AMP report is that we show the pages there. But we don't really include information on how much traffic goes to each of those parts. So it might be that you have let's say 100 pages that are listed there. And your primary traffic goes to 10 of those pages.  

#### [0:13:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=810) |  Then it could look like you have

all of these-- 90% are slow. Perhaps if those 90 other pages are slow and those 10 that people go to are fast, but actually the majority of your people will be going to those fast pages and we'll take that into account. EVAN GILGENBACH: So two follow up questions there. One, you mentioned that you segment these results into different sections, right? So when I look in the Search Console, you're right. I can see that they're grouped together.  

#### [0:14:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=840) |  But I see the AMP and the

non-AMP pages separately. So will you take into-- if you do a search result and I have maybe a site that's not AMP canonical but you're showing an AMP result for, it will use the results from the AMP section of that page, even if the search result itself is for the non-AMP version, but it has the AMP enhancement? Sorry. Does that question make sense? JOHN MUELLER: I just kind of got confused  

![](https://i.ytimg.com/vi/kzM7fi43cMc/hq1.jpg)



#### [0:14:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=870) |  with that last part is. It's like

it's an AMP page but we're showing the non-AMP page? EVAN GILGENBACH: Well, so there's an AMP and a non-AMP version. And in the search result you're showing the AMP version but it's not AMP canonical is, sorry, is my-- if that makes more sense. JOHN MUELLER: Now I think what-- I have to look at the specifics. My understanding is we would follow the canonical and use it based on that. EVAN GILGENBACH: OK. [INAUDIBLE]  

#### [0:15:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=900) |  JOHN MUELLER: Yeah, I mean, usually what

would happen is we would fold the AMP information, the AMP signals, into the canonical itself. EVAN GILGENBACH: Mm-hmm. Got it. OK. And then I guess the second follow-up question is does the AMP results in the Chrome User Experience report take into account the benefits of the AMP caching? Because I can imagine just going to the AMP page would be much slower than viewing the cached version from that. JOHN MUELLER: We-- I mean, what we do is we take into account what users see. So if it's a valid AMP page and we can serve it from the cache,  

#### [0:15:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=930) |  then we'll use that. Whereas if it's

not a valid AMP page and it's still an AMP page and pretty fast, but we can't serve it from the cache, then obviously we don't use that. EVAN GILGENBACH: Yeah, totally. I was just asking because the Chrome User Experience report, I know, takes from just people browsing the internet from Chrome. So I wasn't sure if it was able to associate the cached AMP pages with those versions. So that was my question. Thanks. JOHN MUELLER: Cool. Fantastic.  

#### [0:16:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=960) |  Max. MAX PETERS: Hi, John. Another AMP-related

question. If we're changing AMP URLs, do we need to redirect from the old one to the new? So the canonical URLs are staying the same. We're just changing the structure of the AMP URLs. JOHN MUELLER: Ideally, yes. In practice, it's not as critical as with normal URLs on a website. Because usually what happens with the AMP URLs is we refresh the cache fairly quickly.  

#### [0:16:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=990) |  And we will notice that the canonical

URL and the cache page and those URLs change fairly quickly. So it's more something where I'd say you have that time period between when we know about the URL, when we show it in a search, and when we've updated it, which might be, I don't know, a couple of days' time. So it's definitely less critical than with the normal pages. But ideally you would still redirect those, as well.  

#### [0:17:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1020) |  MAX PETERS: OK. And I have a

second question, related to AMP again. So I think it's been stated a few times that there isn't a direct ranking boost-- a ranking factor from AMP. However, last year, we removed our AMP pages. We redirected AMP URLs to our canonical pages. And then we saw a decrease in traffic straightaway. And over six days, it was 10% decrease in organic traffic.  

#### [0:17:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1050) |  So we redeployed it. We turned it

back on because we didn't want to keep losing traffic. Is there an obvious reason why that might happen? JOHN MUELLER: I don't know. It kind depends on the site. So on the one hand, I think there might be an effect of things just still pointing at the AMP pages and kind of getting lost, if you just turn it off. So that's something that would be something more of a temporary effect.  

#### [0:18:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1080) |  That's something you can also try to

mitigate by using the AMP Cache API, I think, where you can force a refresh, so that we can see, these pages actually no longer exist kind of thing. I think we have a Help Center article on disabling AMP, actually, that covers all of those steps. The other effect that you might be seeing there, depending on the type of site, is that, for certain search experiences,  

#### [0:18:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1110) |  search features that we show in the

search results, we do use AMP. So I think that's, in particular, the Top Stories section on mobile, where we essentially require AMP pages, at least at the moment. And if it's a news website, for example, that has a lot of content that is shown in a Top Stories section when it's on AMP, then you will see that disappear. That's something where, with the update that we're doing in May around core Web vitals and page experience,  

#### [0:19:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1140) |  we're going to start allowing normal pages

as well, when they reach that appropriate bar, to be visible in the Top Stories section. So that'll be a little bit more mitigated. But it really depends on the kind of site. Like if it's not a news website, if there's no newsy content on there that would have been featured in the Top Stories section, then it would be kind of weird to see a drop in overall organic traffic.  

#### [0:19:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1170) |  MAX PETERS: OK. Yeah, it's not a

direct news website, per se. But it's a medical article website. And we do feature the carousel-- an AMP carousel. So yeah, It might have been that. JOHN MUELLER: Yeah, that could be. Cool. MAX PETERS: OK, thanks. JOHN MUELLER: Mohammad. MOHAMMAD MEDHI ABBAS: Hi, John. JOHN MUELLER: Hi. MOHAMMAD MEDHI ABBAS: I work in an IT company. We put tons and tons of quality content at our website.  

#### [0:20:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1200) |  But recently, we got to know that

there are a few websites that have been copying our content and publishing it on their website. In fact, they are not making an effort to change the images. So I just want to know what kind of action we can take. Or how does Google consider these kind of activities? And how we can protect ourselves in the future regarding these fraudulent activities?  

#### [0:20:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1230) |  JOHN MUELLER: I think the primary action

you could take there, depending on the situation, is to look into the DMCA process. The DMCA process is a legal process. So I can't give you legal advice on when it applies and when it would not apply. But that might be something that you could look into. With the DMCA process, you're basically saying, my content is my content and someone else has copied it. And you're giving Google that information  

#### [0:21:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1260) |  on a per-page basis. And based on

that, our Systems or the Legal team-- I don't know the details-- will review that and take action on that, and also inform the other side about that so that if, for example, they were the original source, they would be able to raise a concern and try to find a different resolution for that. But that's, I think, the primary approach that you could take there.  

#### [0:21:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1290) |  The other thing that I would also

keep in mind is that if you're regularly seeing other people with copied content ranking above your content, then to me that points at a situation where maybe the overall perceived quality of your website is something that our algorithms are having trouble with. That could be something where maybe it makes sense to take a step back and think about your website  

#### [0:22:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1320) |  overall and try to find ways to

significantly improve the quality of that, to make sure that, when our algorithms run across your website with the content on it and some random website that they don't know about with the same content on it, that they say, well, actually, your website is the one that we should trust, and not so much some random website is perhaps just as good or even better than this website that we know about that we know we don't want to trust that well.  

#### [0:22:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1350) |  So that's kind of a different thing

to think about there. But I would definitely look at the DMCA process first. And also, if you're regularly seeing this, I would really think about what you can do to improve the quality overall. MOHAMMAD MEDHI ABBAS: OK. That means that we have loopholes in our own website? JOHN MUELLER: How do you mean? MOHAMMAD MEDHI ABBAS: Like we are not up to their quality. That's why other websites are copying our content?  

#### [0:23:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1380) |  JOHN MUELLER: I don't know why other

people are copying your content. I can't say. But if you're regularly seeing that the copied content is ranking above your content, then, to me, that would point at some kind of quality worries that our algorithms have. MOHAMMAD MEDHI ABBAS: OK, thank you. JOHN MUELLER: Sure. DARCY BURK: John. JOHN MUELLER: Darcy. DARCY BURK: Hi, how are you?  

#### [0:23:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1410) |  Back in I think it was mid-

or late-February, a couple of the tracking tools were reporting some drops in featured snippets and the amount of times that those showed up. Judging by your reaction, I don't know if you are familiar with that at all. Just wondering if that was deliberate by any means, on Google's side, to reduce featured snippets from showing up, or if it was maybe for another reason  

#### [0:24:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1440) |  that that might be happening. It's just

featured snippets, when you get them, are pretty awesome. And to lose them is pretty disastrous. [CHUCKLES] At least if you've been used to riding this wave of traffic that can come with a featured snippet. So to lose it, yeah, just wondering if there's any additional rationale or if you know of any-- maybe it was a side effect of another change. I don't know. JOHN MUELLER: I don't know.  

#### [0:24:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1470) |  I don't know. The featured snippets and

rich results in general, those kind of things can fluctuate over time. And I know the teams are always working on those features and trying to fine-tune the triggering, so when we would show them or when we wouldn't show them. Sometimes the triggering changes over time, that we just reduce the threshold overall or that we change the focus a little bit and say, less here and more here. Sometimes that happens across geographies or languages.  

#### [0:25:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1500) |  But these kind of changes, from our

side, are essentially normal organic changes in Search, how they can always happen. So it's definitely not the case that we say, well, there's some technical requirement that's missing on these pages, therefore we dropped it. It's more, we need to refine which types of results we show over time. DARCY BURK: So yeah, just more of a balancing act, I guess.  

#### [0:25:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1530) |  JOHN MUELLER: Yeah. DARCY BURK: So would

you think that it was a deliberate kind of reduction in featured snippets, or maybe some other change that might have caused that reduction. Any idea? JOHN MUELLER: I don't know. I don't know. Usually we don't think of it as much as we want to reduce the number of times we show a feature, but rather we want to improve the targeting and the relevance of when we show the feature.  

#### [0:26:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1560) |  And sometimes that does mean, overall, it's

fewer. But it might be that there are fewer here and there's a little bit more here kind of thing. And that's something that just happens over time. They're always trying to find a better balance of what to show in Search and improve that. DARCY BURK: Gotcha. Cool. Thank you so much. JOHN MUELLER: Sure. Clint.  

#### [0:26:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1590) |  CLINT BORRILL: Morning, John. My question relates

to the mobile index and specifically responsive design. So if, for example, there is an element on the page which links to-- let's say it's an online catalog, something like that. So that component on the page is essentially linking to the catalog. The catalog itself is not mobile-friendly. So as a result, under the responsive design,  

#### [0:27:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1620) |  we would basically hide that component. But

essentially it's still part of the DOM. So under the new mobile index, will this content still get crawled and indexed? Or because it's not rendered on mobile, it's basically not getting crawled and indexed? JOHN MUELLER: If it's in the DOM, then we would be able to pick that up for indexing. So that would be perfectly fine. CLINT BORRILL: It would only show up, then, on desktop, potentially, not on mobile.  

#### [0:27:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1650) |  JOHN MUELLER: Yeah, yeah. Sometimes what we

try to do is figure out which parts of a page are visible and emphasize those with regards to ranking. But especially on mobile, we see that there's a lot more interactivity on a page in that you activate different tabs and you see different things, and actually it's all a part of the same HTML page. And from that point of view, if it's not visible but it's in the HTML, in the DOM,  

#### [0:28:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1680) |  then that would work for us. CLINT

BORRILL: All right. Thank you. JOHN MUELLER: Sure. All right, SEO Team. AUDIENCE: Hello, everybody. JOHN MUELLER: Hi. AUDIENCE: I am very interested in that I can talk with you, John. I was waiting for this online session because of a particular reason. I have four more important questions for an [? excellent ?] purpose. But the four questions are somehow big. Then I will ask the first two questions.  

#### [0:28:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1710) |  And I wish that I can get

some time during the session to ask the remaining two questions. First of all, for websites that have AMP pages and non-AMP pages, how we can measure the core web vitals to get a general idea about the whole performance of the website. I mean, do we need to measure the performance of AMP pages alone and the non-AMP pages alone? What is the best practice here?  

#### [0:29:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1740) |  JOHN MUELLER: So depending on the way

that you have the AMP and non-AMP pages set up, you may be able to see the difference in Search Console or in the Chrome User Experience report data. Because that could be split out by URL. So I would double-check that. The other thing that you definitely can do is do lab testing. Especially if you're modifying pages, if you're trying things out, then I would do lab testing with Page Speed Insights,  

![](https://i.ytimg.com/vi/kzM7fi43cMc/hq2.jpg)



#### [0:29:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1770) |  with Chrome, directly in the browser, to

test things, especially to compare different versions of the same page. And when it comes to lab testing for AMP pages, if it's a valid AMP page, then definitely also check it on the AMP cache. So to see what users would see when they click on a search result. And that's kind of the approach that I would take there. I also recommend, when it comes to testing,  

#### [0:30:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1800) |  that you set up some kind of

a monitoring system on your side to regularly test the important pages on your website for the Core Web Vitals so that you are able to recognize quickly when something goes wrong. But that's more of the long-term thinking. AUDIENCE: OK. OK, thanks a lot. Another question is that I found a lot of difference between Google Analytics and Google Search Console data. For Google organic traffic, I read a lot about the causes of such a difference.  

#### [0:30:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1830) |  And I know that it should have

its own algorithm in collecting and measuring data. But we are facing a lack in reading about Google organic traffic, in which we have some articles that get thousands of clicks on Search Console, but Google Analytics shows that it only has 10 or 20 Google organic traffic showed for same date range on the same article. More than that, in Search Console sometimes we see articles that have an increasing curve for number of clicks, but Google Analytics  

#### [0:31:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1860) |  show a decreasing curve for Google organic

traffic. So why are we seeing that? And is there any step-by-step guide about how we can solve that big difference in data between Google Analytics and GSC? JOHN MUELLER: I don't know. I would check with the Analytics team and with the Analytics Help Forum to get some input there. The one thing I would kind of suspect,  

#### [0:31:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1890) |  but I don't know how it's implemented

on your site, is since you mentioned AMP pages, it's possible that the AMP pages are being tracked separately in Analytics. So depending on how you have AMP set up, it might be that you have a separate property for the Analytics pages and they're separated out. Whereas in Search Console, we focus on the canonical URL. So we would show all of that traffic together. So that might be one reason.  

#### [0:32:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1920) |  But I would really get some tips

from the AMP Help Forum-- Analytics Help Forum. AUDIENCE: Sure, but sometimes we saw vice versa that. We saw that Google Analytics showed more than the real data on Google Search Console. Not every time Google Search Console showed data more than the number of organic traffic at the Google Analytics. JOHN MUELLER: Yeah. I don't know. The tricky part is Search Console  

#### [0:32:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1950) |  can track what happens in Search, but

doesn't know what happens on your website directly. And people can go to your website directly with a referral from Google. And it can look like someone is coming from Google Search. But in Analytics, you can't tell, is it really from Google Search or is it someone just using the wrong referrer? This kind of weird behavior is pretty common. It just happens on the web. So sometimes you do see some discrepancies.  

#### [0:33:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=1980) |  But especially if you see a lot

more data in Search Console than Analytics, then to me, that feels like something Analytics is tracking wrong. AUDIENCE: OK, OK. Thanks a lot. JOHN MUELLER: Sure. Ritu. I don't know if I'm pronouncing your name right. RITU NAGARKOTI: Hey, John. How are you? JOHN MUELLER: Hi. RITU NAGARKOTI: Actually I have a few questions related to schema.  

#### [0:33:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2010) |  Actually I have implemented schema markup for

knowledge panel graph on my website. But still it is not appearing, knowledge graph. Please let me know which practice we need to consider to implement knowledge panel graph for our brand. Please let me know. JOHN MUELLER: Yeah. I don't think there's any specific markup that you can use to force a knowledge panel to appear for a brand. So what you can do is give some general company information,  

#### [0:34:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2040) |  like the logo, like address, opening hours,

things like that. But just because that's specified in structured data doesn't guarantee that we will show a knowledge panel entry. Sometimes what you can also do is the Google My Business entry, which also appears in the side, similar to a knowledge graph entry. So that's something where you can try different approaches there. But it's not that there's one structured data  

#### [0:34:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2070) |  type that forces the knowledge panel to

appear. RITU NAGARKOTI: OK. Another question is related to site links. Actually I need to appear some desired pages as a site link in Google SERP. But still I'm trying from last six months. And I have [INAUDIBLE] lots of activities. But still my desired pages are not appearing as a site link Google SERP. Please let me know what can I do about this.  

#### [0:35:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2100) |  JOHN MUELLER: So site links are generated

automatically as well, kind of like with the knowledge panel. And there's nothing specific that you can do to force those. We try to pick up the site links based on your site's internal navigation primarily. So if we can understand how people can navigate your website better, then we have more of an opportunity to show site links. But it's not guaranteed that they will be shown. And for most websites, I think we just don't show site links.  

#### [0:35:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2130) |  RITU NAGARKOTI: OK. And what we can

do to appear site link search box, which appear just-- JOHN MUELLER: Yeah. The site link search box is something where you can add structured data to your pages too. But the structured data is only used when we show the site link search box. And it's similar to side links, in that for a lot of sites we just don't show the site link search box. I think it's a confusing feature because of that,  

#### [0:36:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2160) |  because you can add markup, but the

markup only has an effect if we would already show something for your site. RITU NAGARKOTI: OK. We can't depend on the scheme markup for it. JOHN MUELLER: Exactly. RITU NAGARKOTI: OK, OK. Thank you so much for the info, John. JOHN MUELLER: Sure. And then Khiet. I'm probably pronouncing your name wrong. Sorry, I think you're muted.  

#### [0:36:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2190) |  KHIET NGUYEN: How about-- JOHN MUELLER: Yes.

KHIET NGUYEN: OK. Hello, John. JOHN MUELLER: Perfect. Hi. KHIET NGUYEN: Yes. OK, I have a question. My website has reply request redirect [INAUDIBLE].. JOHN MUELLER: It's really hard to-- AUDIENCE: [INAUDIBLE] Yes. My URL, my website, [INAUDIBLE] content on [INAUDIBLE]  

#### [0:37:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2220) |  Ho Chi Minh City and canonical Ho

Chi Minh City. And I have different URL [INAUDIBLE] Ho Chi Minh City. And [INAUDIBLE] district one has some [INAUDIBLE] content, district one. And how does URL [INAUDIBLE] URL canonical go to Ho Chi Minh City, yeah?  

#### [0:37:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2250) |  Yes. A new URL in Ho Chi

Minh City and canonical called [INAUDIBLE] OK, district one, Yes. But when if I redirect, 301 from old URL to new URL. Is that have any problem with my website for Ho Chi Minh City?  

#### [0:38:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2280) |  Is that my-- I have problem from

when I do redirect, 301. OK. JOHN MUELLER: OK. So you're redirecting a part of your website to a different part? Is that-- KHIET NGUYEN: Yes, yes, yes. JOHN MUELLER: OK. KHIET NGUYEN: When-- yes. To a clean URL, to clean URL.  

#### [0:38:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2310) |  JOHN MUELLER: To a clean URL. OK.

KHIET NGUYEN: Yes. Will my URL Ho Chi Minh City will have [INAUDIBLE].. So on Google, any problem? OK. Do you understand? Yes. JOHN MUELLER: A little bit. It's hard. But in general, when you redirect from one URL to another, we try to forward all of those signals.  

#### [0:39:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2340) |  So if you have links to the

old URL and you redirect the old URL to a new URL, a cleaner URL, then we will forward all of those signals and all of those links to the new URL. So I think, if I understand your question correctly, we would pass all of that information to the new URL. KHIET NGUYEN: The old URL have [INAUDIBLE] parameter-- yes, [INAUDIBLE] parameter  

#### [0:39:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2370) |  district one or district two? [? Plus

?] it's canonical to just Ho Chi Minh City. If I [INAUDIBLE] it, it's [INAUDIBLE] redirects Ho Chi Minh City to many URL. Is that right? JOHN MUELLER: I think--  

#### [0:40:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2400) |  so I I'm having trouble understanding exactly

the configuration for your website. But in general, if there are parameters with the old URL, that's perfectly fine. We can also forward that. If you have other URLs on your website that you're not redirecting, then that's also perfectly fine to just keep them. So that should, I think, just work if I understand your question correctly. MIHAI APERGHIS: John, the question is also in the chat.  

#### [0:40:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2430) |  I think it's much more clear with

the structure there. I think it's the case that there are some district-related pages that have canonical to the main city page. But the new structure includes a separate district page as their own pages. So what would happen if those parameter URLs are then  

#### [0:41:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2460) |  redirected to the new district pages, if

they had a canonical until now, to the main city page. JOHN MUELLER: OK, so basically taking a set of city pages and redirecting them to one general page, more general page. MIHAI APERGHIS: No, I think there was a general page in the beginning with a few parameters for each district that had-- all of them had a canonical to the main city page. But now there will be separate pages for each district.  

#### [0:41:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2490) |  So if until now, every parameter URL

had a canonical to the main city page, and now there are separate pages for each district, if the redirect from those parameter pages to the new district pages, if that will affect the main city pages, I think. JOHN MUELLER: Yeah. As I understand it, it's like we would follow these redirects on a per-page basis. And if there are individual redirects there  

#### [0:42:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2520) |  that take place, where you have multiple

pages redirecting to one page, or you have individual this parameter URL redirecting to one clean URL, and you have other pages that stay the same, we would all look at that on a per-page basis. So I think, if you're cleaning things up for a handful of pages for different sections of your website, that's perfectly fine to do like this. KHIET NGUYEN: That's probably right?  

#### [0:42:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2550) |  It's OK, it's not [INAUDIBLE]? Yes, yes.

Thank you. Thank you. I have one question, one more question. My website, it's a classifieds website. It's a 100,000 content. Yes. After two months, this content [INAUDIBLE] This means someone buy a house, someone buy a motorbike,  

#### [0:43:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2580) |  when they [? bounce ?] to my

website, just two weeks or one week, they saw this. My question is, if the content is too old, what should I do with this? Do I leave it on my website, or I keep it on my website? [INAUDIBLE] JOHN MUELLER: Yeah. That's a very common problem. If you have classified content, then it comes and goes fairly quickly.  

#### [0:43:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2610) |  There are two approaches that people take.

And for us, they are very similar. So one is to say the old product that no longer exists, or the page that no longer exists, redirects to the category page. To us, that would be seen as a soft 404, which is something we discourage, but for users maybe it's OK. The other is to just say this page that no longer exists  

#### [0:44:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2640) |  returns a 404 error. And then we

would just drop that page. So in practice, in both of these cases, the old page would drop out of the search results and we will be able to focus on the rest of the website more. So the only thing I would not recommend doing is, for the long run, keeping the old page and just adding a label on top, saying, oh, this is obsolete. It's expired.  

![](https://i.ytimg.com/vi/kzM7fi43cMc/hq3.jpg)



#### [0:44:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2670) |  Because then you have a lot of

pages on your website that Google has to crawl and first recognize, oh, there's content here, but it says it's expired, so I can ignore it. So that's what I would avoid. But redirecting or 404 is fine. KHIET NGUYEN: [INAUDIBLE]. Thank you, thank you, thank you so much. [INAUDIBLE] JOHN MUELLER: Cool. Thank you. KHIET NGUYEN: Thank you. JOHN MUELLER: All right, Mihai. MIHAI APERGHIS: [CHUCKLES] Hey, John.  

#### [0:45:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2700) |  By the way, regarding the question in

the chat, I think, to put it in a more general way is, when you have a lot of URLs doing something, like they all have a canonical to a certain page. And then you change it, and all of those URLs no longer have a canonical, but they do something else. Maybe they're just indexable. Maybe, let's say, you have an e-commerce website. And you have a Category page. And all of the filters or something like that, they all have a canonical back to the main Category page.  

#### [0:45:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2730) |  But then you decide, OK, I need

those filters to be indexed or redirect them somewhere, I don't know. And you break the canonical, and then you use them in whatever other way you want to use them. Does that mean that the main Category page starts to lose some of the signals that were until now aggregated from all of those filters and things like that? Is it kind of a balance-- you kind of gain some, you lose some?  

#### [0:46:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2760) |  JOHN MUELLER: Probably. I mean, it depends

a little bit on what you mean with signals. Because with a canonical URL, when you specify that, we don't take the content itself into account. So if you have a blue car and the canonical is a green car, then we will index the green car. We won't know about the blue car. If someone links to the blue car, then we know there's a link that indirectly goes to the green car. But we don't know it's blue car.  

#### [0:46:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2790) |  MIHAI APERGHIS: Right. But that means that

if you start making the blue car indexable or do whatever else with it, that means that the blue car will start gaining, maybe, in rankings and get traffic, especially if it has links and everything else. But you're no longer canonicalizing to the green car. So the green car kind of loses those ranking signals that came through the canonical until now. So yeah, you lose some, but you might get a lot more traffic by being more specific towards certain queries.  

#### [0:47:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2820) |  JOHN MUELLER: I think that's always a

balance that you have to figure out. There's no absolute answer where you can say you should always split it up or you should always combine it. Sometimes it makes sense to split, sometimes it makes sense to keep it separate. MIHAI APERGHIS: I guess it's a lot based on what your users are really interested in and if they're looking for something more specific and you have a page that could provide a better experience for them, then that might make sense. So I want to ask very quickly about something  

#### [0:47:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2850) |  regarding core web vitals in Search Console.

Because the core web vitals are taken from the Chrome User Experience report. So the data in Search Console is taken from the Chrome User Experience report. Yet for-- let's say you have a CLS issue with a bunch of your pages, you have the option to validate fix. But that doesn't make as much sense as you would validate fix on a coverage report.  

#### [0:48:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2880) |  Because it doesn't matter if Google recrawls

those pages, the data is not from Googlebot, it's from the Chrome User Experience Report. So that's a bit confusing. JOHN MUELLER: Yeah, yeah. We have that there for consistency reasons. But it's based on, like you said, the Chrome User Experience report data. So it wouldn't be the case that we would be able to say, more people should click on this link and then we have more data to look at. We basically have to wait for things to update there. MIHAI APERGHIS: So it's just a display report thing  

#### [0:48:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2910) |  that the validate fix actually helps. You

just kind of see. JOHN MUELLER: Exactly. MIHAI APERGHIS: Yeah, OK. Makes sense. JOHN MUELLER: Cool. We're running low on time. So let me just go through some of the questions that were submitted that we didn't get to yet. And I'll stick around a little bit longer if anyone wants to chat for more as well. The first one I have on top is about AMP. I think we talked about that. Also AMP [INAUDIBLE] ranking factor.  

#### [0:49:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2940) |  Will Google consider the Origins Field core

web vitals data for the whole domain, or will it be ranking on a per-page basis? We talked about that a bit as well, the different groupings that we show. How accurate is "crawled currently not indexed" in Search Console? Despite being a page with sufficient content, without issues, many pages are excluded from the site from being indexed. That's fairly common. So for the most part, we don't index all pages that we know about on a website.  

#### [0:49:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=2970) |  We have to prioritize a little bit.

So that's something where it's less a matter of, this individual page is fantastic, but more that we need to understand that there's a lot of value to be gained from showing your website more visibly in Search. And that's something that's more of a long-term process, and less something on a per-URL basis where you can say, this page is good now. For passage indexing rolling out, does passage indexing relate with core web vitals  

#### [0:50:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=3000) |  for ranking or indexing factors? No, that's

something completely separate. Also, passage indexing is kind of a bad name. I hope the people who decided on calling it indexing don't listen. But it's not based on indexing. So nothing changes with indexing. It's really based on ranking, so understanding what is on a page and how to show that in the search results. Does the URL Parameters tool in the old Search Console still work?  

#### [0:50:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=3030) |  When will the new version go live?

Yes, it continues to work. I don't know of any date with regards to a new version. I think that's one where we're talking with a team to figure out what the right approach is there. And it might be that, at some point, we decide, well, it still works but it's not as valuable for all users to actually migrate to the new version of Search Console. And maybe it'll go away at some point. Maybe it'll be migrated in a different way.  

#### [0:51:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=3060) |  Maybe it'll be taken over one to

one. I don't know. How do the core web vitals interact with AMP site enhancements? I think we talked about this as well. We have two regional sites under different subdomains, one in German for the German region, one in English for the US. We kept the URL handle of our products the same for easier forwarding, but this means that the URLs in our US store are in German. Is this a problem for search ranking in the US?  

#### [0:51:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=3090) |  No, it is definitely not a problem.

We use the words in a URL as a very, very lightweight factor. And from what I recall, this is primarily something that we would take into account when we haven't had access to the content yet. So if this is the absolute first time we see this URL, we don't know how to classify its content, then we might use the words in the URL as something to help rank us better. But as soon as we've crawled and indexed the content there,  

#### [0:52:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=3120) |  then we have a lot more information.

And then that's something where essentially, if the URL is in German or Japanese or in English, it's pretty much the same thing. The only effect where I would kind of worry about this a little bit is that users might be a bit confused if they're copy and pasting your URL, if they're recommending it to other people. Then if the URL is in German and it doesn't make any sense at all to them, then that might be something where they're like, what is this URL actually  

#### [0:52:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=3150) |  about? Usually, if it has product names

in there or descriptions that have very similar words in English and German, then that's less of an issue. But if the URL were in Japanese and the users were in the US, then that could be something where they're like, what am I actually forwarding to my friends here? But that's not an SEO factor. That's more of a marketing issue. I work on a big news site, and some parts of the articles are blocked from the user until they  

#### [0:53:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=3180) |  click the Read More button. For the

Google user, by default-- let's see, it's not blocked behind a login page when we show Googlebot the whole article. So in general, I don't think this is really problematic. But it might be worth thinking about whether or not this should be used with the paywall structured data, where you can kind of clearly specify this part of the page is visible by default and this part isn't.  

#### [0:53:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=3210) |  I think probably paywall would be not

perfectly suited for this. And probably, if this is really something where you just click a link on a page and then the CSS switches over to show more content, then that feels like something where, from Google Search point of view, we wouldn't really care. It might be that your users are a bit annoyed by this. But that's more of a usability issue on your side  

#### [0:54:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=3240) |  and less of an SEO issue. Does

the structured data from YouTube carry through embeds? For example, does the structured data need to be recreated on the page that embeds the video? So if you're using something like an iframe, then we can definitely understand a little bit about what's happening within the iframe and associate that with the page itself, which could be something like the title of the video, for example, on YouTube embed. But I would strongly recommend using  

#### [0:54:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=3270) |  normal video structured data on a page

as well. Because you don't want to rely on this vague "Google might be able to figure it out" thing, but rather you want to really clearly provide that structured data to Google so that Google can show your pages as proper video landing pages, because it has all of the information that it needs there. So we definitely can carry some things over, but for optimal video implementation,  

#### [0:55:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=3300) |  for video optimization in Search, I would

use the normal video structured data. Why, in the Crawl Stats report in Search Console, there are also very old URLs that are sometimes called for discovery and not for refresh? I don't know. I'd have to take a look at some of the examples to see a little bit more about what actually is happening there and chat with the team. But I wouldn't necessarily worry about this difference. It's something where I think splitting those parts out  

#### [0:55:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=3330) |  makes it easier to understand that Googlebot

is actually refreshing a lot of your pages and that it's normal for it to access pages that have been the same for a longer period of time. But I wouldn't worry about individual URLs falling into one bucket or the other bucket. Will the ranking boost from core web vitals be based on the mobile or the desktop numbers? We announced that the core web vitals-- or rather the page experience ranking factor-- would  

#### [0:56:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=3360) |  apply to mobile and not to desktop,

at least initially. I don't know what the long-term plans are, and my guess is at some point we'll figure things out a little bit more fine-grained. But at least the initial announcement that we made is based purely on the mobile side. And that's also where, for the most part I think, the harder barriers are, where users really see things a lot slower than on desktop.  

#### [0:56:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=3390) |  Because on desktop, you tend to have

a really powerful computer, and you often have a wired connection. And on mobile, you have this much-slimmed-down processor with less capabilities and a smaller screen and then a slow connection sometimes. And that's where it's really critical that pages load very fast. Search Console data question-- data on the Search Console UI is slightly different than from what's pulled from the API. And the data in the UI looks more approximated.  

#### [0:57:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=3420) |  Is the data pulled through the API

more accurate? So both of these sources are based on exact same databases internally at Google. It's not that we have one set of data for the API and one set of data for the UI, but rather it's the same data. It's available in different ways. And depending on how you query the API, you might see slightly different numbers. But essentially it's the exact same data.  

#### [0:57:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=3450) |  If a domain organizes its international sites

in subfolders, would Google crawler have an issue with different international sections on a site using different page templates or navigation, since the site navigation template consistency has been mentioned before as a factor in SEO? That's perfectly fine. So we do try to understand the templates of a page and to understand which parts of a page are the primary content and which parts are more boilerplate, like everything around it, the menus, the footer, the titles, things  

#### [0:58:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=3480) |  like that. But we can pick that

up for different parts of a website in different ways. So it's not that the whole website has to have exactly the same template. Most websites don't. The thing I would watch out for, especially since you mentioned international sites, is if you're using hreflang and you have very different infrastructure across the different language versions, then it makes it really hard to link those pages together with hreflang. It's not so much that Google would have trouble with it.  

#### [0:58:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=3510) |  But if you can't specify the hreflang

yourself on those pages, and you want Google to understand the connection between the language versions or the country versions, then that just makes it a little bit harder. But purely from an SEO point of view, if you can create proper hreflang, if these pages are normally crawlable and indexable, then I wouldn't worry about that. OK, wow, so many questions and so much more left.  

#### [0:59:00](https://www.youtube.com/watch?v=kzM7fi43cMc&t=3540) |  But maybe I can take a break

here, pause the recording. And if any of you want to stick around longer, you're welcome to do that as well. Thank you all for listening in, for watching, for asking so many questions. It's like wow, so many hands are still up. So many questions still in. It feels like we could do these for hours and hours. But then I would probably, I don't know, fall into the ground or something afterwards, which would be unfortunate on a Friday  

#### [0:59:30](https://www.youtube.com/watch?v=kzM7fi43cMc&t=3570) |  evening. Cool. OK, let's take a break

here. I'll pause the recording. And like I mentioned, if any of you want to stick around, feel free to do so. Otherwise, have a good weekend, and maybe see you in one of the next sessions. MAX PETERS: Thanks, John. Goodbye. MIHAI APERGHIS: Cheers, John. JOHN MUELLER: Bye.  