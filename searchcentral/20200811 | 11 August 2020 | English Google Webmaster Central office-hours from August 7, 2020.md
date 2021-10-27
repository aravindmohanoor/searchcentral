[![English Google Webmaster Central office-hours from August 7, 2020](https://i.ytimg.com/vi/owoXikK9PRU/hqdefault.jpg)](https://www.youtube.com/watch?v=owoXikK9PRU)

## English Google Webmaster Central office-hours from August 7, 2020

This is a recording of the Google Webmaster Central office-hours hangout from August 7, 2020. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Watch out for new sessions, and add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



Feel free to join us - we welcome webmasters of all levels!



#### [0:00:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=0) |  JOHN MUELLER: All right, welcome, everyone, to

today's Webmaster Central Office Hours Hangout. My name is John Mueller. I am a webmaster trends analyst at Google here in Switzerland. And part of what we do are these Office Hour Hangouts, where people can join in and ask their questions around their website and web search. A bunch of stuff was submitted on YouTube already. But if any of you want to get started with a first question, feel free to jump on in.  

#### [0:00:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=30) |  AUDIENCE: Can I just ask a question?

JOHN MUELLER: Sure. AUDIENCE: If you remember, John, I asked some Hangouts ago about a problem of [INAUDIBLE] having disappeared since some months ago. And I was suspecting that the root not [? accessible ?] may be a cause because I moved to a structure for multi-language. And I wrote down the name of the website.  

#### [0:01:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=60) |  I don't if you have time to

have a look. Because nothing changed. [CHUCKLE] JOHN MUELLER: Nothing changed. OK. I passed it on to the team to check out. So I'm a bit surprised that nothing changed. Because it sounded like, from their side, they would take a look. OK, I will push again. Maybe we can get something. AUDIENCE: Thank you very much. JOHN MUELLER: Sure. AUDIENCE: And another short question-- in the same site, I have pages that have specification  

#### [0:01:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=90) |  and reviews of products. And there is

one main page with the list of all the products. And then I have separate pages that do not show all the products, back filter for category. So I have one page [? filled ?] [? in ?] just type A of products, and another listing just type B of products.  

#### [0:02:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=120) |  And each of these pages have a

canonical URL to themselves. Of course, if you put other filters, the canonical points to the basic product page filter at the category. And in Google search, one language is fine. I mean, all these filtered lists are indexed. While in English, almost no pages are indexed.  

#### [0:02:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=150) |  And Google says that these are duplicated

pages. [CHUCKLES] So the same page in another language are considered as duplicated. And I don't know. Is there anything I can look at? JOHN MUELLER: So is it with different languages, the same page? Or is it with the filters, with the categories and kind of-- AUDIENCE: Wait, the main list, the overall list,  

#### [0:03:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=180) |  is fine in both languages. The filtered

pages, so the pages that show the list filtered by category are normally indexed in one language and not indexed in English. And in English, Google search says they are all duplicated pages with wrong canonical because there the canonical points to themself. And instead Google says that it should point to the main list.  

#### [0:03:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=210) |  So they are considered as being duplicated.

I don't know if I am being clear. JOHN MUELLER: OK. I think that can make sense. I mean, it's hard to say without looking at your site. But I think that can make sense. So our systems, when they come across setups like this where there is a possibility for a lot of URLs to be generated and the URLs end up pointing  

#### [0:04:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=240) |  at very similar content-- for example, if

you have a category page, and you can filter by color, and you can filter by size, and all of these things, then the products that you show are essentially kind of just the same things-- different orders, different selection of the same products essentially. And our system is trying to recognize those kind of setups, and to figure out which parameters in the URL are not important for the site.  

#### [0:04:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=270) |  And then they will kind of skip

that and focus on the canonical URLs or the ones that they think are canonicals instead. So my guess is our systems looked at the setup that you have there, and thought that we can save you time by focusing on the canonical URLs. So one thing I would look at there before trying to kind of fix this problem is-- if it's really a problem--  

#### [0:05:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=300) |  so in particular, are these landing pages

that you want to have indexed, are they critical for indexing? Is it something that is very visible or would otherwise be very visible in search? Is it the case that the product pages themselves are still indexable? So usually, from the category page, you link to a product page. And the products are the ones that you usually would focus on. If those products are all indexed normally,  

#### [0:05:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=330) |  and if the pages that we fold

out as canonical are not critical for your website, then I would just leave that and kind of let it be resolved like that. On the other hand, if the products themselves are not being indexed and if the category pages that you're trying to get indexed are really critical for your site, then I would double-check to make sure that the URL structure that you're using  

#### [0:06:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=360) |  is one that does not allow Google

to kind of run into the situation where we start to ignore things. So one example that I sometimes see is that you have parameters in the URL that can be swapped out for any text, and they still link to the same page. For example, you have maybe product name equals a long descriptive name, and then you have the ID as  

#### [0:06:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=390) |  well attached to the end. And as

long as the ID is there, then that page shows a normal page. And that's something where our systems would say, oh, well, probably the product name is irrelevant. And we can just pick one and focus on that. AUDIENCE: Yeah, the URL does contain a variable. Because these pages are filtered by compatibilities. I mean, it's at least of accessories. And the category list is the list  

#### [0:07:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=420) |  of accessories that's compatible with a specific

product. So I would be interesting in having it indexed. Because if you search for accessory compatible to a specific problem, then you have that specific filtered page. And so the idea is that you have to check that if I put a random ID for compatibility, I should return a 404? JOHN MUELLER: Yeah. Yeah. And you can also check, in Search Console, there is the URL Parameter Handling tool--  

#### [0:07:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=450) |  I think it's in the old part

of Search Console-- where we show the URL parameters that we've noticed on your website and the ones that we've started to ignore. And you can change the settings there, and say, well, actually, this is one that I think is important for me. And we'll pick that up. AUDIENCE: OK, thanks. JOHN MUELLER: Sure. All right, any other question before we get started with the submitted ones?  

#### [0:08:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=480) |  AUDIENCE: I've got one if now is

a good time, John. JOHN MUELLER: Go for it. AUDIENCE: Mine's a bit of a conundrum in terms of user experience. So it has to do with Flash. So we run a large digital magazines website. Lots of it's user-generated content. So we've got about 2 million Flash magazines that we're essentially going to retire because, by the end of the year-- most brands don't recognize them all anyway.  

#### [0:08:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=510) |  And so we've got the choice now,

purely through our service setup, we've got the choice of, do we remove all of that content? And essentially we'd love to 404 it. But the way that we've got it set up, because a lot of these are files, is we can 405 it, which is a very ugly access-denied page of death. Or we have the option to directly replace  

#### [0:09:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=540) |  the file, give the user some kind

of information, i.e., "this content is Flash. We've retired it now. Go back to the main page." And then canonicalize that content. But obviously we're talking about scale of 2 million pages that suddenly, overnight, on our website,  

#### [0:09:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=570) |  become identical, with the same message. Just

wondering, from kind of user experience side but then also obviously from a crawling and indexing side, what would be the best kind of route to go down? JOHN MUELLER: So in the long run, from an SEO point of view, both of these would be equivalent. So what would happen is, the 405, we would recognize as an error. We would drop those pages. That's pretty fine.  

#### [0:10:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=600) |  If you serve an HTML page instead

and the HTML page is the same content as other pages, then what would happen is we would pick that up as a soft 404. And then, over time, we would treat it similar to kind of the Page not Found. The difference that you would see, probably, from a practical point of view, is that we would continue crawling the HTML pages longer before we kind of slow down there. Because we're like, well, looks like a normal HTML page. We'll double-check a while.  

#### [0:10:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=630) |  And probably we would just recrawl those

more often. But if you used to have PDF files there, or Flash files, or whatever, then it's probably not the server load that you're worried about. So that's something where, for a longer period of time, we'll be recrawling that. Practically speaking, we'll treat them the same. So my recommendation in a case like that would be to focus more on the user experience side and say, well, I'll put an HTML page here.  

#### [0:11:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=660) |  And Google will treat it as a

soft 404. Soft 404 isn't great, but it's essentially what you want. You want Google to figure out, OK, this page is gone. AUDIENCE: Yeah. And that is essentially it. I guess what we wanted to do, from the user's perspective, is when they land, kind of give them more information. Unfortunately, with our service setup, you can't customize any kind of 405 messaging to explain why this content's been removed.  

#### [0:11:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=690) |  So OK, cool, brilliant, thank you. JOHN

MUELLER: Sure. AUDIENCE: OK, cheers. JOHN MUELLER: All right. I think someone else had a question. AUDIENCE: Yeah. JOHN MUELLER: OK. AUDIENCE: Also sort of an older topic that we've discussed in a previous Hangout. Basically if you remember, we have this weather website. And we have the issue that very weird canonicals are being selected. And we've been going back and forth with the team  

#### [0:12:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=720) |  about it since the end of June.

But still really [INAUDIBLE] couldn't be progressed a lot. We are still in trial and error mode. And so I was wondering if there's anything that we can do to sort of speed this along. Because now is our high season. And business is already pressuring me quite a lot to not get this fixed, but to take some radical measures. We are really talking about relaunching the whole site under different URL. Because it's in such a problem state that we are losing almost all of our relevant search traffic,  

#### [0:12:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=750) |  which is horrible for us. JOHN MUELLER:

Can you drop some sample URLs maybe in the chat here? Then I can pick that up afterwards and double-check with the team. AUDIENCE: I can also post the webmaster's thread. It already has almost 30 replies. So we are back and forth a lot. It seems to be a difficult issue to fix. So I appreciate that there are a lot of people trying to fix it already. But it's really-- business-wise, it's a killer for us. It's really a problem.  

#### [0:13:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=780) |  JOHN MUELLER: OK, sure. I mean, if

you can post maybe a link to a thread or a link to the pages where you're seeing this problem in the chat here, then I can pick that up afterwards. Oh, fantastic. Cool. AUDIENCE: Thanks. JOHN MUELLER: All right, let me run through some of the submitted questions. And we can get-- or do you want to go, Chris? AUDIENCE: Oh yeah, I'd rather ask you, actually. It will probably be easier. We run quite a nice career advice platform. And we've been building this for like 12 years now--  

#### [0:13:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=810) |  OK, sorry, eight to 10 years. It

previously allowed open submission of guest posting. And people would come in, log in, and get paid for actually providing content. And we never really had much editorial moderation in that process. It was very minimal. The last three or four years, we've stepped up the quality. We're trying to follow Google's best practices, the webmaster guidelines. And we seem to have run into a little bit of an issue on the older content and some bad outbound  

#### [0:14:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=840) |  linking in the past. So we have

a manual action now for outbound, unnatural linking. And during the submission process, we tried to follow all the recommendations. But it seems the [? tools ?] we were using didn't uncover all the links on the first audit. And then the second audit, we found issues as well. And we've learned, really painfully, over the last five months now, that maybe we should have taken more time on the initial reconsideration.  

![](https://i.ytimg.com/vi/owoXikK9PRU/hq1.jpg)



#### [0:14:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=870) |  And we are where we are now.

And we're just-- now we have waited three months, I think, from the last response, which was a processed response. And we had no note from the reviewer telling us what to fix. So we're kind of a dead end here, wondering what to do. Do we wait longer, or do we keep following up? Because I've seen advice, "don't follow up," and "do follow up." And we don't want to aggravate you guys and spam you with reconsiderations. But I'm just wondering, what do you  

#### [0:15:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=900) |  recommend in such a long wait, for

five months here. JOHN MUELLER: Yeah. That seems pretty long. So in general, with reconsideration requests, it's not something where you get kind of pushed forward if you do another reconsideration request. So just continuing doing that is probably not going to help. But it sounds like something is stuck.  

#### [0:15:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=930) |  So if you want, maybe post your

URL here in the chat. Then I can take a look at that with the team to see what might be happening there. AUDIENCE: I would really appreciate that, yeah. JOHN MUELLER: And the last response you got was that it was being processed? AUDIENCE: It said it was processed. And the note said, underneath, that is it's either adjusted or revoked. And if it remains in Google Search Console, it means it's just adjusted. So it still applies to the whole site, the manual action. And we've seen all traffic deteriorate with COVID  

#### [0:16:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=960) |  since the spring really. So it's kind

of we're in a desperate state now to get something done. I've even contacted a consultant. And they said to try to reach out to you. So I'll post you the link, anyway, now, in the chat. JOHN MUELLER: Yeah, if you can post it now, I can double-check quickly to see kind of roughly what the status is. It's not always the case that I can see exactly what's happening.  

#### [0:16:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=990) |  But maybe I'll get something. AUDIENCE: Let's

see. [? That's the ?] [? quick ?] link. JOHN MUELLER: [INAUDIBLE] I don't know what the current status there is. So I see we got a lot of duplicate reconsideration  

#### [0:17:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=1020) |  requests from you. But one is still

kind of open. AUDIENCE: OK. I adjusted the message somewhat. But I wanted to give you all the evidence each time. But then I read maybe I should have customized the whole message each time and explained exactly what was done. JOHN MUELLER: Usually what happens is when we get another reconsideration request for the same site and one is still pending, we'll try to process the earlier one first.  

#### [0:17:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=1050) |  But it seems like that's from May.

And it's quite a bit past May now. Yeah. So I'll double-check with the team, see if we can-- AUDIENCE: If you could try to push it along, that would be amazing. Because we're just waiting here. And it's just a bit frustrating. And we're already struggling with COVID and losing a bit of business and traffic as well. So we would really appreciate it. JOHN MUELLER: So usually, with these kinds of manual actions,  

#### [0:18:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=1080) |  what happens is we just devalue the

outbound links on your site. AUDIENCE: Yeah, [INAUDIBLE]. JOHN MUELLER: Because we're not sure-- like if we can't figure out which ones are actually good ones, then we might fall into kind of a safe mode type thing. But that wouldn't affect the ranking of your website. So if you're seeing things around the ranking of your website differently now, then that seems like something worth kind of attacking separately.  

#### [0:18:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=1110) |  I think it's good to get this

resolved, because then your website is really in a clean state again. But if you're seeing significant changes in ranking and visibility in search, that would probably be something different. AUDIENCE: Well, we dropped I think it was about 35% a couple of weeks after the initial notification came. So that was when it was alarming that we'd been hit, penalized, from the manual action itself. I think after we submitted it-- sorry-- the first response we sent, and we got rejected shortly  

#### [0:19:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=1140) |  after because of the issues of our

audit, we saw an immediate drop. I think it was on Friday the 13th of April, I believe, where we saw that dip. But COVID came at the same time as well. So it was quite difficult for us to think, either we've been double-hit by both factors, or it's Google, or it's COVID. We couldn't really differentiate. And now I've got-- the decision was to even follow everything.  

#### [0:19:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=1170) |  Because we feel we've now followed everything

which is of any possibility of being low quality. So we don't really want to do that. Because I wanted to ask actually, a follow-up question if I can. Would you recommend now following all outbound links on a site? Because from my understanding of SEO, this will lower the relevance of the platform. JOHN MUELLER: I don't think it would lower the relevance, but it's unnecessary. I would try to link naturally within the web.  

#### [0:20:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=1200) |  And that's essentially fine. My general feeling

here is really, if you're seeing a significant drop in search, that would be unrelated to the manual action. That would be something that would be separate. So one thing I've sometimes seen-- I suspect that's not the case in your situation-- is that when a site has a lot of unnatural outbound links,  

#### [0:20:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=1230) |  then sometimes it's part of a bigger

network, where it's like everyone has all of these unnatural outbound links. And a lot of support of that website was due to the unnatural outbound links. And if the web spam team takes a look at that network and kind of neutralizes the whole network, then of course those sites will also lose that support. So that's where you might see a drop in visibility. My guess, just from talking with you, is that probably you're not a part of a crazy link network  

#### [0:21:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=1260) |  where the support to your site has

also been neutralized. But what I would kind of focus on here is try to kind of leave the unnatural outbound links/manual action kind of running. I'll see if we can get that resolved on our side. But I wouldn't assume that that will fix the visibility issue of your site. So I'd try to continue looking at other things  

#### [0:21:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=1290) |  and try to find ways to really

significantly take things a step further. AUDIENCE: OK, thanks a lot. Well, it's stabilized for now. So I think it maybe was due to COVID. So yeah, thanks for that. Really helpful. JOHN MUELLER: Sure. OK, let me go through some of the submitted questions. And we'll have more time for other questions along the way. (READING) Do you know how Google determines how and why they show a photo of a product on one website's organic listing versus another website that  

#### [0:22:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=1320) |  doesn't receive it? For example, if you

Google "used Honda Civic," nearly half the organic results have a photo next to the website description, but half don't. When I look at the schema and images of those, and those without they're virtually the same. What am I missing? So we do try to pick up an image for particular pages if we can find one. And we do try to show that in search. However, we also need to make sure  

#### [0:22:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=1350) |  that there is some kind of a

reasonable balance with regards to how many images that we do show in search. So it can certainly happen that, for some pages we show an image, for other pages we don't. Maybe for other queries, we would show an image for those pages too. To kind of make it more obvious to us which image you want to have shown, I would kind of go back to the normal structured data. For example, with the article markup or--  

#### [0:23:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=1380) |  I forget which other variations of the

kind of article or web page markup that you can use there, where there is a primary image on the page that you can specify. And by doing that, you make it a little bit easier for us to pick that up. That said, even without this markup, we can usually figure out what a relevant image for a page might be. And we can usually try to show that where appropriate.  

#### [0:23:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=1410) |  (READING) A 301 redirected 500 article pages

to a new URL structure. The website has about 2,000 pages in total. The pages started to get crawled, and indexed, and recovered. The traffic dropped-- they experienced-- during those days. But a few days later, due to a technical bug, the URL switched back to the previous URL structure, and traffic from those pages is almost gone. Other pages and page types of the site were not hit by this, only the articles. The fix took place the same day.  

#### [0:24:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=1440) |  Plus we modified the canonicals, and back

links, and internal links as well, to the new structure in the following days. Is this mess with the bug and Google indexing the new URLs, and suddenly those are removed and back again after I fixed it, might that trigger a recrawl for the entire website which might mean it might take weeks to recover? It's possible that this will trigger something on our side where we try to recrawl the website overall.  

#### [0:24:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=1470) |  Usually kind of the triggering of a

recrawl on our side essentially just means we try to get an updated picture as quickly as possible. And usually that's due to us recognizing when there are significant changes on a website. So that could be, for example, you changed the whole URL structure or you move from one domain to another. Then we try to get that reprocessed as quickly as possible. It's not the case that the website  

#### [0:25:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=1500) |  will stand still or be dropped out

of search during that time. It's just we're trying to crawl a little bit faster to catch up again. With regards to this situation, where you move URLs and then those new URLs disappear, and then you add them back again, it kind of depends a little bit on what happened during that bug stage on your side. If those new URLs disappeared completely and the redirects were still in place,  

#### [0:25:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=1530) |  then it would have been like you

were redirecting to a 404 page. And in cases like that, we will think, well, you removed these pages, so we will drop them from the index. So in those cases, it probably takes a little bit longer than normal for us to pick that up again and to kind of index all of those pages again. Because we have to kind of get back into-- when we look at your web page, we have to consider again, well, actually these pages might not  

#### [0:26:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=1560) |  be gone completely. We'll double-check them again,

and we'll get back into the normal crawling speed for those individual pages. On the other hand, if the redirect just dropped and essentially it looks like it moved back to the old URL, then those are cases, which we can usually kind of cover fairly well. Because it just looks like, well, you temporarily moved them here, and then you moved them back again,  

#### [0:26:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=1590) |  then you moved them here again. For

our systems, we don't really care. I think it helps to make up your mind which URLs you want. But essentially this "moving back and forth" thing, that's something that we should be able to deal with. So that probably gets resolved fairly quickly. But in either of these cases, even in the worst-case scenario where we thought you removed those pages, and we're crawling those URLs less frequently, with a website  

#### [0:27:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=1620) |  of your size, with like 2,000 pages

in total, we can crawl a lot of content fairly quickly. So that's something where I would suspect, in the worst case, within a week or so, that will settle down again and things will be pretty much. And at any rate, when it does settle down, it's not that Google systems will think your website is bad because you had this technical problem.  

#### [0:27:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=1650) |  It's essentially just, well, we have these

pages indexed now, and we can rank them normally again. There is no kind of bad feelings left behind from a technical glitch like this. So these technical issues happened to every site. So you're not alone with that. And our systems have to deal with that all the time. I need to 301 redirect a page from a subdirectory on a domain to a subdirectory on a new domain.  

#### [0:28:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=1680) |  Do I need to have a new

page indexed by Google before making the redirect to it? No. You can redirect to a completely new URL. That's usually the case how things are done. It's like you take one URL, you redirect it to another one, and then we recognize the new URL and we focus on the new URL. So it doesn't need to be the case that you have to first get that page index and then set up the redirect. It doesn't harm if you do that either, so whatever works.  

#### [0:28:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=1710) |  An article of mine was ranking on

the first page of Google. There was a typo in the URL. I did a 301 redirect to the correct URL and Google was still ranking the old URL. So I requested reindexing of that page and within five minutes of the request, the page disappeared completely and couldn't be found using the site operator. After three days, the page got back in Google search, but now it's no more ranking and can only be found with the site operator.  

#### [0:29:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=1740) |  Can you tell me how long it

will take to get back to the original position? I don't know. Like you mentioned there, I also don't think this is a penalty. It's not like a black hat practice or anything. This kind of thing can happen. Usually, the cases where I have seen something like this, where a page disappears completely, is more  

![](https://i.ytimg.com/vi/owoXikK9PRU/hq2.jpg)



#### [0:29:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=1770) |  do to the site owner using search

console to remove the old URL and then we run into a situation where maybe we make the old URL canonical, but you told us to remove it so we won't show anything. I don't know if that's something that happened here. But in any case, it sometimes happens that things fall out of our index and usually over time they come back in  

#### [0:30:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=1800) |  and they start ranking normally again. So

this is something where I would try to just give it a little bit more time to settle down again. In Russia, we have two powerful search engines, Google and another. Can I separate the site on two domains-- visits from Google sent to the first domain and from the other one through the other domain?  

#### [0:30:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=1830) |  The second domain is closed for Google

and robots.txt but open for other search engines. The idea is to try to recover Google traffic, but not risk losing traffic from the other search engine. Before moving it was 52% from Google and 48% from another. Will it work? Any bans because the two domains with similar content, but one is closed for Google and Google Chrome users will have different behavior on opening one domain.  

#### [0:31:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=1860) |  I don't know if this makes it

any easier for you to do, but at least from our side, if you want to do something like this, that's perfectly fine. If you prefer to block a part of your website or one of your domain's and say, Google should not index this domain, that's perfectly fine. That's your decision to make. The thing to kind of keep in mind is that there's more to your website than just your domain.  

#### [0:31:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=1890) |  So in particular, links on the web

are things that we try to pick up that pretty much all websites-- well, all search engines try to pick up. And if you have two separate domains, then you will have some links going to this domain and some links going through that domain. And if you block one domain for one search engine, then that search engine will only see a part of the picture. And they might assume that actually this website maybe  

#### [0:32:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=1920) |  is not so great after all, because

only like this small part of the links are going there. And that's something where, potentially, you're making it a little bit harder for your website than it needs to be. So that's kind of what I would watch out for there. The other thing is also with regards to having two websites for two search engines, you're just making everything much more complicated from a technical point of view.  

#### [0:32:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=1950) |  How do you deal with users? How

do you deal with users from different locations? All of these things still kind of fall in here if you wanted to do maybe ads at some point, how do you deal with that? Do you run ads separately on the different domains? How do you promote those websites? If you want to publish something really fantastic and you want to spread the word about that, how do you do that? These are all things, which, from my point of view,  

#### [0:33:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=1980) |  make a lot more complicated than it

needs to be. And I don't know which search engine you're referring to-- I can guess-- but my general feeling is that most search engines kind of look at similar things. So it's not that if you have headings on one site that one search engine will say, oh, this is fantastic and the other one was say, oh, this is terrible. But rather, search engines try to look at pages  

#### [0:33:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=2010) |  and they look at it in slightly

different ways and try to understand those pages in different ways. But it's not that they would say, this page that one search engine says is fantastic is now terrible. So they kind of have similar ways of looking at pages. So from that point of view, I kind of worry that you're making it a lot more complicated than it needs to be and you're probably finding a problem where there is none.  

#### [0:34:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=2040) |  When taking a mobile friendly task for

the same page at a different time gap, it shows three variant results like partly loaded, not mobile friendly page, and sometimes showing mobile friendly page with 17 resources unloaded. What is happening behind the crawling process? Is that the JavaScript not loading property? Or are the tracking codes making the page  

#### [0:34:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=2070) |  really slow while rendering? So this can

sometimes happen. What happens with the mobile friendly test in particular is we know users of the test are impatient, and we try to bring back the results as quickly as possible. However, at the same time, we also know that websites have limited capacity, so we try not to overload their servers.  

#### [0:35:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=2100) |  So what can happen is if you

have a very complex page that uses a lot of embedded resources a lot of different things, maybe even from different locations, different servers, then it can happen that we're not able to completely load that page in time to do the full test. So what will then happen is we will load as much as we can, where we're sure that we're not overloading any servers, and we will try to run the test on that part of the page.  

#### [0:35:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=2130) |  So if you run the test and

you see that there's different JavaScript files or images missing, then that's generally a hint that that is happening. And that's generally something where I would say maybe wait again a little bit longer and try that test again at some later point to make sure that you're getting a real picture of how that page is actually crawlable and renderable. And if you're seeing that it never is able to be processed properly,  

#### [0:36:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=2160) |  then I would double-check to see if

there may be things that you can simplify on your pages. Maybe combining different kinds of JavaScript. Maybe removing some of the different tracking setups that you have on the page. Maybe you have other things that significantly slow things down. A good way to look at that is to look at the waterfall diagram that you can see in Google Chrome if you go to the developer tools. I think that it's in the Network Settings in the Developer  

#### [0:36:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=2190) |  Tools. What happens is you reload the

page when you're there, and then it shows how all of the different resources are being loaded and when they're being loaded. And usually, when you look at that and you compare it to other pages that you have or other pages on other people's sites, you can kind of guess where you might be going a little bit too far. It's not that there is any specific limit on our side with the number of resources or the time  

#### [0:37:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=2220) |  that it takes to load, but it

is something where you can look at some pages and maybe they have 100 or so resources and other pages when you load them, they have 10,000 of resources that need to be loaded in order to render the page. And then you can imagine that somewhere in between there is probably a reasonable range to aim for. So if you have thousands of resources that are needed to load a page, then I can imagine that the mobile friendly test at some point was saying, like, we're running out of time.  

#### [0:37:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=2250) |  We have to make a cut off

here. Another tool that you can use, which gives you this waterfall diagram in a more neutral way in the sense that it's not tied to your computer or your settings, your internet, is webpagetest.org. There you can use different device types. You can look at the screenshots. You can see how long it takes to load different parts of your page. So that's kind of the direction that I would go there.  

#### [0:38:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=2280) |  Let's see, second part of the question--

a page without an H1 title, will it still rank for keywords, which is in the H2 title? Of course. Absolutely-- I mean, will it still? I don't know if it will still, but it can. It can, absolutely. So headings on a page help us to better understand the content on the page. Headings on the page are not the only ranking factor that we have. We look at the content on its own as well.  

#### [0:38:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=2310) |  But sometimes having a clear heading on

a page gives us a little bit more information on what that section is about. So in particular, when it comes to images, that's something where headings and the context of that image helps us a lot to understand where we should be showing that image in image search. Because, by design, images are not text-- we don't automatically know what we should be showing it for.  

#### [0:39:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=2340) |  And that combination of the image plus

the landing page is something that depends quite a bit on the text of the page. And when it comes to text on a page, a heading is a really strong signal telling us this part of the page is about this topic. And whether you put that into an H1 tag or an H2 tag or H5 or whatever, that doesn't matter so much, but rather kind of this general signal that you give us that says, well, this part of the page is about this topic  

#### [0:39:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=2370) |  and this other part of the page

is maybe about a different topic. So that's generally what I would think about there. Is it good to have structured data WordPress plugin or rather do it manually? Both approaches work fine. I think from purely a practical point of view, I would personally go with a plugin that does this for you, because then you can focus on the content.  

#### [0:40:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=2400) |  You don't have to focus on the

technical implementation. If you're using something like WordPress, you're already focusing more on the content rather than how do I make an HTML page? Or how do I serve my HTML page from the server? You're already focusing more on kind of the content, not the technical implementation. That said, in the end, if it's valid structured data, we don't care where it comes from. If it comes from a plugin, from your theme, if you added it manually, if you used JavaScript to add it  

#### [0:40:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=2430) |  after the page has loaded-- all of

those different types of structure that are perfectly fine. Is it possible that a website has been penalized and its traffic for less than 20 minutes of 503 service temporarily unavailable and returned to previous levels a week later? No, I don't think that would happen. So usually with 503s, what happens is we  

#### [0:41:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=2460) |  will not index the content that you

serve us when we see 503 response code. And we will assume that this is a temporary issue until we recognize that it's a permanent issue. So if you're talking about 20 minutes or maybe a half a day or a day or so of 503 response codes from your server because it's down because something is blocked or something needs to happen, that's definitely something we can deal with, where we say,  

#### [0:41:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=2490) |  well, we'll try again. And essentially, during

that time, we will not change the indexing of those pages. However, after a couple of days, when we still see a 503 status code, we will assume that this is not a temporary issue, but maybe your server is down. Or maybe these pages were removed and your server is set up in a way that it serves a 503 instead of a 404 response code. And what will happen then is that, kind of page by page,  

#### [0:42:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=2520) |  we will drop those pages from our

index. But if you're talking about a time frame of 20 minutes, that would definitely not happen. And it would definitely not be the case that we would demote that website in ranking during a time when we're seeing 503s, because 503s are a very common thing on the web and it's something that you should be doing if your server is slightly overloaded. Or if it can't deal with the responses,  

#### [0:42:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=2550) |  then 503 is the correct approach there.

And that's not something that we would kind of penalize a website or hold against it in any way. After the 5th of May, our site lost our rich snippets and was also removed from the recipe carousel for three months. We're looking for a reason with no luck. We did tests, different URLs with [? LD ?] plus JSON, schema.org, minimum properties.  

#### [0:43:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=2580) |  Previously, recipes were fully described. And now

we switch to schema micro data only. Here's an example of a recipe. An interesting thing, some of the recipe collections which grouped together, another type of URL, an article marked up only with the necessary schema.org recipe properties, which didn't have them removed from the recipe  

#### [0:43:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=2610) |  gallery. Removed only recipes grouped by URL,

recipes/asterisks. I don't know. This seems like a very specific question. I'll take a look to see if there's something specific happening here. But generally speaking, if you had structured--  

![](https://i.ytimg.com/vi/owoXikK9PRU/hq3.jpg)



#### [0:44:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=2640) |  if you had rich results that were

shown for your website and they disappear from one day to the next, then, unless something specifically changed in the requirements on our side for that type of structured data, which can happen from time to time, but we try to keep it really rare and we try to let you know about it. Then that's more a sign that our algorithms re-evaluated your website and we're not really sure about the quality  

#### [0:44:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=2670) |  of your website. So that's something where

I wouldn't focus so much on the technical implementation of that structure data. If you're sure that it was correct before, if it passes the validators that we have, then that's generally OK. I would focus more on the overall quality of the website. So I don't know this website. It's hard for me to say that this is not a good high quality  

#### [0:45:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=2700) |  website. But that's, from our point of

view, where we see these kind of changes happening. Where it's like, well, we kind of re-evaluated everything around the website. We're like, ah, we're not really sure if it meets the bar for what we would like to show in the rich results. And what can sometimes make this confusing is that sometimes a website might be kind of on the edge there and we will re-evaluate that after some time as well.  

#### [0:45:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=2730) |  And if during that time your kind

of fiddling with the structure data and fiddling with it in a way that kind of breaks the structure data, then suddenly we'll be like, oh, we would like to show rich results from this website. But now the rich results are broken, so we don't have anything to show it anymore. So that's something sometimes to watch out for there. So what I would do here is double-check to see that things are technically OK.  

#### [0:46:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=2760) |  So I would use the rich results

test. Double-check that you have the right rich result types on the pages that you want to have shown. Double-check the policies that we have around those rich results types to make sure that you're doing things in a way that matches what our systems are looking for. And then do maybe a site query for your website to double-check to see if we could theoretically  

#### [0:46:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=2790) |  show those rich result types. Usually, when

you do a site query, we try to show the rich results types, even if we otherwise might not show them in search, so that's kind of a weird workaround to figure out if there's a quality issue or not. And if they're shown in a site query but they're not shown for normal queries leading to your pages, then that's usually a sign that you need to work on the overall quality of the website.  

#### [0:47:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=2820) |  So that's kind of the direction I

would go. Externally, I'll double-check with the team to make sure that things are kind of working as expected here, but that's usually the direction I would head here. Why are some of URLs submitted in a site map, but search console shows indexed not submitted in a site map? It's hard to say without looking at specific examples, but we don't always process everything  

#### [0:47:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=2850) |  in all site map files. So that

might be something where you're kind of running into this kind of an edge case, where we've seen the site map file, but maybe we haven't processed all of the contents in there yet. And then Search Console will say, well, it's indexed, but it's not submitted in site map file because we haven't had time to draw that connection. Due to a bug, many of our web pages are missing meta titles and meta descriptions for three to four months.  

#### [0:48:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=2880) |  Metrics seem to indicate that this had

an impact on traffic from search. And now that the bug is fixed, what's the best way to indicate to crawlers that these pages have been updated? Submitting each URL individually for recrawl would be cumbersome. I was thinking of updating a last updated date for the offending pages in our site map, about 500 pages. Could that make it seem like I'm trying to game the system since the actual body of the content hasn't changed? Will I be penalized? Is it better to leave it be?  

#### [0:48:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=2910) |  So changing the last modified date is

exactly what you should be doing here, because you modified these pages. You put a title on these pages. You added a meta description on these pages. Sometimes, like even when you add structure data to a page, it's not visible at all, but it is a bigger change on a web page. So setting that last modified date in the site map file is exactly the right thing to do here. If you have a kind of a date that you serve with the pages  

#### [0:49:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=2940) |  themselves, then updating that would be great

too. But essentially, using a site map file is what you should be doing here. You can also do that individually in Search Console, but, again, with like 500 pages, it's a lot of work. What I would do, personally, is try to find maybe the top, I don't know, 5%, 10% of the pages that are really important for you and submit those manually.  

#### [0:49:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=2970) |  And just make sure that everything is

otherwise set up properly in the site map file. So that way, the pages that you really care about-- the ones where you think people are really searching for and a missing title or missing description is making it less interesting for people to click through-- then at least those are updated as quickly as possible. And then the rest will be updated naturally. Last time in the German Webmaster Hour,  

#### [0:50:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=3000) |  you've been talking about the rich result

FAQ problem that has been all focused on showing rich and search results, I have additional questions in that. We did not change the way of schema implementation and still the site has the FAQ markup in the source code, but Search Console report is empty. All valid markups are gone. If we test the site, even as a live URL in Search Console or in the rich result test tool, everything shows valid. The markup just doesn't show up in the report.  

#### [0:50:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=3030) |  What could be wrong here? I don't

know. It's hard to say without looking at the site itself to kind of see what we're picking up on here. Usually, the report in Search Console takes a bit of time to be updated and populated. So when you add a site to Search Console for the first time, some of the reports will have data right away and others might take maybe a week or so to be updated. So sometimes you would see a difference there like that.  

#### [0:51:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=3060) |  In general, if the markup is on

the pages and is findable with the rich results test, then that's what you should be aiming for. With regards to the FAQ markup in general, one of the things that I've noticed people talking about online is that we're showing fewer of these in the search results. And that's something from my point of view, that's kind of natural development, where  

#### [0:51:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=3090) |  we try to find the right balance

between showing these everywhere and showing these for pages where it kind of makes more sense. And that's something that generally doesn't have any kind of effect from the markup that you have on the pages themselves. It's really more that suddenly everyone has added FAQ markup to their pages and we can't show every search result with FAQ markup. So we have to kind of fine-tune which of the ones--  

#### [0:52:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=3120) |  which queries, which pages we should be

showing the FAQ rich result types for. Ooh, OK. Still a bunch of questions, but we're running low on time, so I'll switch to anything from you all. It looks like maybe on the Google Meet side something is kind of blocking random people from joining, but I'll pause the recording in a bit  

#### [0:52:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=3150) |  and leave the Hangout running for a

while. So maybe that will let more people join in. We'll see. Anyway, any questions from you all? AUDIENCE: Hi, John. I have one. JOHN MUELLER: OK. AUDIENCE: So, this is happening with our website, basically, where we have multiple, you can say website within one global website. So, again, using older structure to kind of target different countries, let's say US, UK, Japan, Brazil, Mexico.  

#### [0:53:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=3180) |  And so, in that, basically, from the

last two weeks or something, we have noticed a change in the one specific country-- let's say Japan. So we're in Google detecting the duplicate of Brazil, that's something. And now the Japan pages removed from the index and instead ranking the Brazil page. So [INAUDIBLE] inspect URL. Therein it says it's a duplicate and your Google has selected as a different canonical of Brazil.  

#### [0:53:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=3210) |  So I just wondering why is it

happening? So maybe, it might be one of the possibilities happening like, recently, that team has developed or [? changeed ?] one specific change in the [INAUDIBLE],, where they have implemented kind of a default version of the pages in English and the alternate in the Japanese. Similarly, for the canonical vision of the Brazil, where they have marked as the default English and then the alternate as, you can say the Portuguese language  

#### [0:54:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=3240) |  or the Spanish version. So in [INAUDIBLE]

Google might be getting confused like [INAUDIBLE]. Is it the case or maybe something else which is kind of not allowing Google to crawling or indexing the specific page that we actually wanted? JOHN MUELLER: So are the pages in the same language? Or are these different language pages? AUDIENCE: Yeah, they're in different languages. For example, in Japan's case, it is in Japanese, the default one. And the one the Google is referencing is actually the Portuguese.  

#### [0:54:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=3270) |  That's altogether a different language. JOHN MUELLER:

That sounds to me like either the website is trying to automatically serve the content in the user's language or there's some kind of a mismatch with the rel canonicals on the page. So there are situations where we get confused and we think that two pages are the same  

#### [0:55:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=3300) |  and we will fold them together. But

usually that's the case when the pages are the same language. Like, you have one page in English for Japan and one page in English for, I don't know, Hong Kong. And the pages are exactly the same. They're just for different countries. Then that would be something where our systems would say, well, we can simplify this and just keep one as a canonical. But if the pages are in multiple languages,  

#### [0:55:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=3330) |  they're served directly in those languages, then

that wouldn't be something where we would say, these pages are the same because they are translated. Because translated content is, by definition, different content for us. So we shouldn't be kind of confused by that kind of setup and fold things together. That seems more like something where the confusion probably comes from something else, other than kind  

#### [0:56:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=3360) |  of the href lang pages there. But

if you want, maybe you can drop the URLs in the chat here and I can take a look at that with the team afterwards. AUDIENCE: Sure, John. So, let me give you some more context to it. Basically, yes, like you mentioned, apparently it behaves like, depending on the user's browser language, something slows the content accordingly. But I cross-checked the same [INAUDIBLE] mention, like domain or it's OK as far as you're solving the right content with the user [INAUDIBLE],,  

#### [0:56:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=3390) |  So in that particular case, when the

user is coming, they're getting the Japanese. And even when the [? Google ?] is coming, they're getting the content in Japanese as well. So the one conflict is happening over here that the [INAUDIBLE] is that the default version, the tech team is implementing to something in English, but the page is in Japanese. So I feel-- JOHN MUELLER: That's fine. Like, you mean the [? X ?] default href lang? AUDIENCE: It means like I'm at the page, for example, the slash JP is the default page, where  

#### [0:57:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=3420) |  the content present on the pages is

in Japanese. But, by the href lang, the tech team has implemented this page is in English. So that is, you can say, the conflict is happening. The actual thing is saying this page is English, but when you look at the page, it is actually in Japanese. JOHN MUELLER: Oh, OK. Yeah, that sounds like something worth fixing, but that shouldn't be causing an issue with indexing. I think the one thing to watch out  

#### [0:57:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=3450) |  for is that Googlebot almost never crawls

with an accept-language header. So that's something where maybe we'll use English as an accept-language header or maybe we won't use any language as an accept-language header. And if you're serving the English content to users with the English accept-language header, then we would only see the English content. So that's kind of like you're trying to do something  

#### [0:58:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=3480) |  fancy, but instead of automatically serving that

content. What I would do is maybe show a banner on top and say, hey, we have the English or the Japanese version here and you can follow with a link to get to that version, rather than swapping out the content directly. AUDIENCE: So John, we already have those options as well. I mean, we have providing-- there's a language [? feature ?] where you can use it and actually switch to the different languages. It was absolutely was fine before the implementation  

#### [0:58:30](https://www.youtube.com/watch?v=owoXikK9PRU&t=3510) |  by the tech team. And now when

we implement this [INAUDIBLE] change, we have seen a lot of changes in the Japan [? version ?] especially. JOHN MUELLER: I don't know. OK, I'll take a look with the [INAUDIBLE].. AUDIENCE: Sure, thank you, John. JOHN MUELLER: OK, we're out of time. I'll keep the Hangout running. I'll just pause the recording now. Perhaps that makes it easier for other people to join in. Sometimes Google Meet is a little bit  

#### [0:59:00](https://www.youtube.com/watch?v=owoXikK9PRU&t=3540) |  super protective and blocks everyone from joining

in. So let me just find the pause button. Thank you all for joining in, and hopefully we'll see more of you in one of the future Hangouts. All right.  