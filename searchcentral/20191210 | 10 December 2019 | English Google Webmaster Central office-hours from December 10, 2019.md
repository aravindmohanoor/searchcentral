[![English Google Webmaster Central office-hours from December 10, 2019](https://i.ytimg.com/vi/FWyFif98YAw/hqdefault.jpg)](https://www.youtube.com/watch?v=FWyFif98YAw)

## English Google Webmaster Central office-hours from December 10, 2019

This is a recording of the Google Webmaster Central office-hours hangout from December 10, 2019. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Watch out for new sessions, and add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



Feel free to join us - we welcome webmasters of all levels.



#### [0:00:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=0) |  JOHN MUELLER: OK, wow, that was recorded.

OK, welcome, everyone, to today's Webmaster Central Office Hours Hangout. We have a bunch of special guests today that have chosen to join us here in Zurich. I don't know, do you want to introduce yourselves? ULRIKA VIBERG: OK, I can start. I'm Ulrika Viberg. I come from Stockholm, Sweden. I do technical SEO and digital marketing and digital strategies. I run my own agency, called Unikorn.  

#### [0:00:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=30) |  JOHN MUELLER: Cool. Interesting. PETER NIKOLOW: My

name is Peter Nikolow. I come here from Ruse, Bulgaria. I build the stuff for my own company, called Mobilio Development. As the name shows, it's mostly for development. But last days, we are working a lot of SEO stuff or things like that, in Tools section mostly. JOHN MUELLER: Cool.  

#### [0:01:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=60) |  Cool. MARTIN SPLITT: Yeah, I mean, most

of you probably know me by now. I'm Martin Splitt. I work with John here in the Zurich office. And as we have a few guests, I thought I'd just pop in again as well. So if you have JavaScript questions, fire away. JOHN MUELLER: Cool. And I'm John. I do these Office Hour Hangouts from time to time. I don't know, since we have a bunch of people here in the room, do any of you want to get started with a question? ULRIKA VIBERG: I think you should  

#### [0:01:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=90) |  start with someone, and then-- AUDIENCE: I

could jump in if that's OK. JOHN MUELLER: All right, someone from the Hangout. Go for it. AUDIENCE: All right. Hey. Hi, John. Hi, everybody. I have kind of like a technical question. So we have a customer who bought a domain name which used to be hacked. So the site used to be hacked. We know that. And the issue is that there are millions of unique URLs that are indexed in Google at the moment on this hacked website.  

#### [0:02:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=120) |  So currently, the site is about 100

pages. It's just a regular site, nothing too fancy, with some regular URLs. But we are having issues on our server because Google Bot is crawling all these old URLs. And you get redirected, or they even give a 200 status code or a 404. But my question is, what is the best approach here too, in the first place, get all these URLs out of Google, and in the second phase,  

#### [0:02:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=150) |  make it so that Google Bot doesn't

overload our server with requests. Because the past 14 days, I think we had about 50 million unique requests from Google Bots trying to get these pages. But they are old hacked pages. So I'm wondering what the best approach is here. PETER NIKOLOW: I can help you. JOHN MUELLER: Go for it. PETER NIKOLOW: If possible. So I have a similar situation like you, years ago or two years ago, with different customers. So probably best way is to make, in htaccess things,  

#### [0:03:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=180) |  an override, so that hacked URL to

return 404 or 410, gone. And this will stop processing the, for example, PHP making calls to the database or stuff like that. This will help, because a patch will see that URL and return direct the status code to the Google Bot.  

#### [0:03:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=210) |  And this will help you with, for

example, when Google Bot go and made the CPU hammer into your website. Another way-- but probably you need to be DevOp [INAUDIBLE],, you can make-- for example, get a virtual machine from someone, for example, like Google Cloud, and make some kind of redirector to the right site. But if URL is infected, that site will return 404 or 410  

#### [0:04:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=240) |  directed to the Google Bot. So it's

not an easy, but if you do that, it actually can take a few hours of work. JOHN MUELLER: I think that kind of makes sense. I mean, essentially, what you want is Google Bot to stop processing these URLs. And it primarily does that when it  

#### [0:04:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=270) |  sees that these are always 404. So

there will be a period of time where we try to crawl all of these like crazy, and then after we see that it really doesn't make sense to crawl these anymore, then we stop crawling them or drastically reduce them. So some kind of a way to bridge that time until that happens, I think, makes sense. And removing them from research is something--  

#### [0:05:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=300) |  so I would first see if it's

actually a real problem, in that, if, for normal queries, these pages even show up. Because if they only show up for site queries where someone actually knows that there is hacked content on this site, then that's probably not so much of a problem. And they'll drop out over time. But if you really need them removed urgently, the URL Removal Tool is what you would need to do. The tricky part there is you need to do that probably  

#### [0:05:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=330) |  on a per-directory level, to say, like,

those hacked directories are things that should not be shown in search. And the Removal Tool does remove it from the index despite the name, it just hides them in search. So it will still crawl. It needs to see the 404s. And then it just won't show them in search. AUDIENCE: OK, thanks. Just a small follow-up question. We are currently rate-limiting all bots  

#### [0:06:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=360) |  that are crawling the server because our

server was going down because of the requests. Do you think that's a good idea? Do we have to turn off the rate limiting? JOHN MUELLER: I think that's fine. So what will happen in practice is Google Bot will crawl less. And we'll try to prioritize better. So we'll try to focus on the URLs that we think are actually important, which should be the normal content. PETER NIKOLOW: May I extend you? JOHN MUELLER: Sure. PETER NIKOLOW: So maybe--  

#### [0:06:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=390) |  I support what John said, but if

you have a budget for that, my idea is to get VPS, to extend that VPS, and to handle everything there to remove that crawling limit. So let Google Bot see and remove them faster. And later-- can be a month or two later-- you can shut down that VPS things to be normal, or even  

#### [0:07:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=420) |  move to the shared hosting again if

possible. JOHN MUELLER: I think that also makes sense. I mean, if you can do that, that cleans it up a little bit faster than if you slow things down. You can ask slow things down in Search Console, if you really need to, with the Crawl Rate setting there. AUDIENCE: OK, maybe one more follow-up question. JOHN MUELLER: Sure. AUDIENCE: Would it be a good idea to-- because as I said, the current site is only a couple hundred URLs-- would it be a good idea to use the URL Removal Tool  

#### [0:07:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=450) |  and just temporarily hide the entire website,

to just use slash at the end, and temporarily hide everything, and start from a fresh index so to speak, so de-index everything? JOHN MUELLER: It doesn't remove it from the index, it just hides it in the search results. So that wouldn't fix anything. AUDIENCE: OK. PETER NIKOLOW: Another way, just to extend it, is if site is very small-- for example, I have a client with 10 pages [INAUDIBLE]  

#### [0:08:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=480) |  a few million pages. So if site

is very small but is built on WordPress or WooCommerce, or things like that, maybe it's a good idea to make a static website, to put it on the server, disable all PHP processing, or Node.js, or whatever it is in background, and let Google Bot access those static files. Because this will make zero CPU usage to the hosting. And you can clean up much faster.  

#### [0:08:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=510) |  But this is for small or medium

site where you have, for example, 1,000 pages. That's OK. But if you have a million pages, that is virtually impossible [INAUDIBLE]. For small and medium sites, it's OK. As workaround. AUDIENCE: Does Google Bot-- at that specific IP of the website for the particular time, saying, OK, this is hacked-- is there any ranking issue with that?  

#### [0:09:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=540) |  JOHN MUELLER: I mean, we try to

recognize when it's hacked content. And we'll flag that in search. But it kind of depends on what you're actually seeing there. If you're seeing that it's flagged as hacked, then you can go through the reconsideration flow, which kind of helps with that too. But it sounds like we just know that there used to be hacked content there, and try to crawl it as much as possible. AUDIENCE: But then the rankings will flow back to where it was,  

#### [0:09:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=570) |  right? JOHN MUELLER: Well, if you're taking

over an existing domain then you would have a new website there. It wouldn't be ranking like before. AUDIENCE: Right. MARTIN SPLITT: It's different content. So you would have different signals, and thus, different rankings. AUDIENCE: No, I mean, if you were in the same industry, for instance, if you were, like, in one specific industry and the site did not change. MARTIN SPLITT: Well, if it literally did not change and the contents did-- because being in the same industry  

#### [0:10:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=600) |  does not mean that the content is

the same. But if literally nothing changes when you take over that website, then sure. Maybe, yeah. I mean, even then, other websites can pop up. And ranking is volatile. Why am I even commenting on this? It's ranking, I know. JOHN MUELLER: [CHUCKLES] AUDIENCE: OK, thanks guys. JOHN MUELLER: Sure. All right, any other live questions before I jump into the submitted ones?  

#### [0:10:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=630) |  AUDIENCE: Hi, John. I have a question.

JOHN MUELLER: OK. AUDIENCE: Hi, my name is Matt. I work for a well-known image and multimedia brand with hundreds of millions of images in our catalog. We also have tens of thousands of contributors to the site that add their own tags for those images. And the site automatically creates a combination of the category of tags, which has unfortunately made for some difficult pairings. In the last year, the site has become much more well-known for not-safe-for-work content, adult terminologies, because of these pairings.  

#### [0:11:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=660) |  And its ranking the top three results

with a pretty good click-through rate. My general question is, does a site's high rankings and relevancy in a category of terminology that's not safe for work preclude it from ranking well for other more innocent or professional terms? JOHN MUELLER: It doesn't prevent it completely. But what could happen is that we would see it as something that would need to be under the SafeSearch filter, which means,  

#### [0:11:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=690) |  if someone has SafeSearch turned on, it

might be that we wouldn't show it. So that's something where usually our recommendation is, if you have adult-oriented content and kind of general content, then separate those out as cleanly as possible by directories or subdomains so that we can kind of clearly identify this part of the site should be under a SafeSearch and this part of the site doesn't need to be under a SafeSearch.  

#### [0:12:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=720) |  And then it's a lot easier for

us to make sure that we're showing it at the right time. Otherwise, if it's a mix of different things on one site, then it could happen that we think the whole site needs to be filtered with SafeSearch. And then it's not so much a ranking issue, it's more that, well, it's not visible to people who have SafeSearch activated. AUDIENCE: All right. Thank you so much. JOHN MUELLER: Sure. All right. AUDIENCE: Can I tap in? JOHN MUELLER: Sure. AUDIENCE: Am I allowed to ask ranking questions?  

#### [0:12:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=750) |  JOHN MUELLER: Sure, we can try. AUDIENCE:

OK. If a site is about books, and then expands to CDs, would it have equal good chances of ranking in the new vertical, given the same quality of content? And would the first category, say, books, suffer from the expansion in verticals? JOHN MUELLER: Not necessarily. I think that that seems like a fine move.  

#### [0:13:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=780) |  And that's kind of like a natural

evolution of a website, anyway. Like you grow, you have more different types of content. That seems completely fine. AUDIENCE: Thank you. JOHN MUELLER: Sure. All right, I'll jump into some of the submitted ones. And if you all have any comments or questions along the way, feel free to jump in.  

![](https://i.ytimg.com/vi/FWyFif98YAw/hq1.jpg)



#### [0:13:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=810) |  The first one is about international sites.

All of our English-market products and recipe pages are being canonicalized to their global English-market equivalents. Regardless of hreflang and search console targeting for our subfolders, local markets Search Console show duplicate. Google chose another URL as canonical pointing to the English global version. We believe this is due to duplicate content. So we ran some tests between the global English and the English  

#### [0:14:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=840) |  UK markets, and only a full copy

change was effective. As there are limited ways to fully rewrite the same product and recipe content, what would you recommend to solve this? How widespread do you see this canonicalization effect on the web? I know, you've probably seen this in the forums a few times, as well. PETER NIKOLOW: That question is asked multiple times. So one of the best solutions is to try  

#### [0:14:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=870) |  to check/recheck the things. Because many times

we have seen very specific, very small issues in implementation, but they totally broke your hreflang issues and make strange, weird things like that. So even if you have seen this, check, recheck, and then check another time. Because most of times, something is burnt into a lot of code, a lot of pieces of things.  

#### [0:15:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=900) |  And something is left, like probably wrong

canonicals, or redirect, or hreflang for Australian language is redirect to South African, or things like that. And this, if Google Bot is seeing this, Google Bot then starts to not trust the hreflang things. And we have seen weird things that can be explained in some easy way.  

#### [0:15:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=930) |  JOHN MUELLER: Yeah. ULRIKA VIBERG: I've experienced

that as well. Keeping stuff in order is the easy answer here. PETER NIKOLOW: Yes. JOHN MUELLER: Yeah, I think, with hreflang, it's really tricky, because it feels like something easy to connect. But in practice, it really gets complicated quickly. PETER NIKOLOW: I'm sorry to interrupt you. One of best answers for us is try  

#### [0:16:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=960) |  to make hreflang things in different domains.

Because if you have the country-specific TLD, Google Bot know that, for example, this is for German people, this is for Switzerland people, this is for Austrian people, and he knows it. But if you put everything into same domain, most of time where things happens in site-- where it is possible. JOHN MUELLER: I think the different domains help, especially for geotargeting. PETER NIKOLOW: Yes.  

#### [0:16:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=990) |  JOHN MUELLER: That makes sense. One of

the tricky things with-- I think, this question is that when we see the same content, like you have English for UK and English for Australia, and it's really the same content. And we think these are duplicates, and we try to help the webmaster by folding them together. And what happens then is, in the reporting, in Search Console, we only show one version. And in the search results, if hreflang is set up properly  

#### [0:17:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=1020) |  like you mentioned, it's sometimes tricky. Then

we will show the different URL in the search results. So we will show the different versions, but we will report on just one version. And that makes it really kind of confusing sometimes. But from our point of view, that's expected and not necessarily a problem. Like you wouldn't rank lower. It's just very confusing in Search Console.  

#### [0:17:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=1050) |  AUDIENCE: [INAUDIBLE] so John, when we've tried

this sort of thing, regardless of speed, backlinks, correct hreflang, incorrect hreflang, it doesn't seem to matter. So when we see this as a business, if you were operating from a supply chain model, and you are being folded up algorithmically from the site from Google Bot, can you imagine the cost of that to a business if-- because Google Bot might not know what we're trying to achieve. So you're saying, OK, maybe try subdomains. But even with search console targeting,  

#### [0:18:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=1080) |  hreflang is designed to bring people to

the right site. So where we're saying-- and plenty of sites around the web have English content for different locales. So how do you know when to roll up that site if it's duplicate content? Because if you're on a supply-chain basis, that would affect the business. And if there's no way out of that other then fully rewriting content, then what do you do? JOHN MUELLER: So it shouldn't affect the search results.  

#### [0:18:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=1110) |  So in the search results, we would

show the different language versions, like the UK and the Australian versions. It's just in the reporting in Search Console, we would only report on the canonical, which would be one of those. So in practice, the traffic you get is still the same. The rankings are the same. It's just the reporting in Search Console is focused just on one of those versions. So like the reporting side is the confusing part.  

#### [0:19:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=1140) |  And at the moment, I don't really

have an answer for how you can separate those things out properly, from a reporting point of view. Because the indexing report will be on the canonical URL, which will be one of those versions. And the performance report is on the canonical URL. In the performance report, you can separate by country, which give you that information again. But it's still on the canonical URL, out not on the individual country URL that are actually  

#### [0:19:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=1170) |  shown in the search results. AUDIENCE: Yeah,

OK. It's very, very hard to get out of that situation. Because I can either say, to the business, OK, you're going to fully rewrite all of the content across the site, but it's the same situation if-- will that work? How much of that works? [INTERPOSING VOICES] MARTIN SPLITT: It's a reporting problem, not a performance problem. AUDIENCE: Right. So we're saying there shouldn't be traffic loss as a result of this duplication, this folding up.  

#### [0:20:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=1200) |  MARTIN SPLITT: Exactly. JOHN MUELLER: Yeah. AUDIENCE:

Right, OK. Thanks. JOHN MUELLER: Sure. But it's tricky. I mean, in English, it's pretty common. In German, it's really common. MARTIN SPLITT: Oh, we have it in German all the time. So we have-- JOHN MUELLER: It's something where we constantly need your feedback and people complaining about these kind of things so that we can bring it back to the team. AUDIENCE: It would be good to see something like that in Search Console, more of a clearer report that  

#### [0:20:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=1230) |  says, yes, we are folding these up

because of this. You know what I mean? It's not too easy, when you go there, just to see a canonical report. I know what that means. But like how do I then explain to the business, this is going to happen because Google sees your content as duplicate? JOHN MUELLER: Yeah. AUDIENCE: Yeah. JOHN MUELLER: Yeah. And explaining the difference between the reporting side and what actually happens in search is really tricky sometimes. People should just have different languages. AUDIENCE: [INAUDIBLE] thanks for what we're hoping  

#### [0:21:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=1260) |  is the magic bullet. OK. JOHN MUELLER:

OK. Another international question. Suppose I have a website, domain.com, which is set to USA using the geotargeting tool. Can I start domain.com/India and set it to India? The short answer is yes. You can definitely do that. That's fine. With a generic top-level domain, you can set subdirectories or subdomains to different countries, however you want.  

#### [0:21:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=1290) |  So that's kind of an easy one.

MARTIN SPLITT: Nice. We don't have that many of those. JOHN MUELLER: No handwaving needed. MARTIN SPLITT: [CHUCKLES] JOHN MUELLER: OK, now we have a complicated one. It's seems as if Google still has major problems with subdomain leasing. So it goes into kind of the different things where basically things like product review or coupon sites  

#### [0:22:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=1320) |  are hosted within an existing domain. And

it's like, why can't Google get its act together and fix this? I don't know, I'm happy to pass this feedback on to our team. I know they've been working on this for a while to try to improve this. In general, the other side that I see here is also that a lot of these more established sites, when you start adding more and more unrelated content to your site,  

#### [0:22:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=1350) |  you're kind of making it hard for

search engines to understand what your site is about. So if you take a news website and you add a big subdomain or subdirectory for coupons or product reviews or whatever, then suddenly it becomes a lot harder for us to understand that this is actually a news website. And then, for your core content, it's a lot harder for us to say, well, this is something that we should show prominently, and rank, and kind of crawl quickly because it's news content, because we have this mix  

#### [0:23:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=1380) |  of different things in there. So it's,

on the one hand, something that I think we need to improve on to better understand the differences within the site, but also where sites kind of are playing with fire a little bit in that it can result in us having trouble understanding their core business, which is something they probably want to avoid. So that's kind of my answer there. The question also went into, well, Bing said they will apply manual actions and penalties  

#### [0:23:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=1410) |  to these sites. And I have no

idea what Bing is actually doing. I know they did this blog post about it. So it's hard for me to compare what other people are doing there. ULRIKA VIBERG: Can I have a follow-up question there? JOHN MUELLER: Sure. ULRIKA VIBERG: So would you recommend instead having, instead of a subdomain with the coupons, creating a new website, totally new domain, totally for that instead? That would be better for everyone, right? JOHN MUELLER: I think that's usually the approach  

#### [0:24:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=1440) |  that we would take. And it's something

where, if you want to host kind of other content on your site for monetization reasons, then I would try to make it as clear as possible that it's really separate. And maybe even consider something as drastic as blocking it from crawling or indexing so that the content is there, you can refer to it if you want, but it's not going to get in the way of your normal search results. ULRIKA VIBERG: Yeah, OK, thank you. JOHN MUELLER: But I suspect people  

#### [0:24:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=1470) |  have different experiences with this. So I'm

sure it will be tricky. But I know that the team is looking into this. And as we get feedback around this these kind of issues, then that's something that we'll definitely review more. ULRIKA VIBERG: You would say that maybe a subdomain isn't really the main domain, and then hence, it would be something different. It would be not seen as, but it is. JOHN MUELLER: Yeah, I think the general idea-- ULRIKA VIBERG: It's intense. I love that. [CHUCKLES] JOHN MUELLER: I think the general idea  

#### [0:25:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=1500) |  is that people try to fold it

into the main site so that they feel like, well, if this is some big website and a part of it is suddenly coupons, then maybe those coupons are really important, too. And you're kind of playing tricks there in that it's harder for us to separate these two. And that means that it'll also be much harder for us to recognize that this is really important content and this is kind of just like used for monetization,  

#### [0:25:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=1530) |  not really what you want to be

known for. Like if you're a big news website, you don't want to be known for your coupons, you want to be known for your news. AUDIENCE: So like a holiday special, whatever, coupons or whatever, if it's a brand, just robots.txt.page? JOHN MUELLER: I mean, that's an option. I mean, that's kind of like an extreme option if you were hoping for search traffic, because search traffic won't happen then. But if you want to host something on your site  

#### [0:26:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=1560) |  that you want to use for monetization

but you don't care for it to be indexed, then that's definitely an approach. AUDIENCE: OK. JOHN MUELLER: But I mean, this is something where, if we get more feedback and hear more from people, then we'll will try to find ways to make that a little bit better on our side as well to really understand these differences. PETER NIKOLOW: Yeah, but this make another problem. For example, if I have site for medical news, for example,  

#### [0:26:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=1590) |  and suddenly some content for car repairs

or things like that, it's stuffing into the main site this is making that problem. For example, Google Bot now-- the bot can't understand what is the main content for that website, and why two are interweaving. And it's tricky.  

#### [0:27:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=1620) |  JOHN MUELLER: I think it will continue

to be tricky. So having specific feedback on issues that you're seeing around this is always useful. Sometimes it's very theoretical in that, well, other sites are doing well like this. Should I do it, as well? It's very hard to kind of use that as an argument with the engineering team internally. But if you're really seeing issues where we're showing things in a wrong way for specific search  

![](https://i.ytimg.com/vi/FWyFif98YAw/hq2.jpg)



#### [0:27:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=1650) |  results, that's always really useful to have.

OK, something completely different. A few weeks ago, we set a large number of pages to 404. Over the last few weeks, the number of pages visible in Search Console has decreased continuously. Currently this number is stagnating at quite a high number with a slightly increasing trend. That doesn't fit together. What could be the reason? Any guesses?  

#### [0:28:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=1680) |  PETER NIKOLOW: For me, probably Google Bot

has seen that 404 arising, and is suddenly start to crawl more and more just to see what part of content is staying there and what kind of content-- what pages, for example-- has been removed. So this is probably tricky if you have done removal of large scale. That's why it probably is good to remove the content in small batch of pieces just  

#### [0:28:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=1710) |  to check how it's going on. But

if you have removed, for example, half of site, suddenly this can went to where it's a situation in the Bot. MARTIN SPLITT: There's also the sheer statistics of it. If you have, I don't know, 1,000 pages, and you have just removed 200 of them, in the first crawl that we're going to do after the removal, we're probably going to hit more of these removed pages.  

#### [0:29:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=1740) |  So they're going to fall out of

the index after a while. And then eventually we're hitting less and less because we are just maybe crawling other parts of the site, depending on your crawl budget. And then, as you said, it depends on, if we think that the structure of the site has fundamentally changed, then we have to crawl it a lot more anyways. And then we might spend more time on pages that are no longer. As in like, on pages that you haven't removed, we might spend our time there as well. And eventually it's just-- we remove a lot in one place, maybe. And then eventually we have less likelihood  

#### [0:29:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=1770) |  of hitting the remaining bits as we

crawl the entire site. And eventually they're going to drop off as well. And if you set them to 404, it doesn't matter that much. They might still show up. But eventually they're just going to drop off. There's not that much that you need to take care of. ULRIKA VIBERG: Can I comment on-- JOHN MUELLER: Sure. [CHUCKLES] ULRIKA VIBERG: So what's the difference between a 404 and a 410, which is the-- PETER NIKOLOW: 410 is like, nuke that page.  

#### [0:30:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=1800) |  It's like throwing a nuclear bomb against

it. Google Bot, when it sees 404, it's regularly return to that page to see maybe that's-- ULRIKA VIBERG: Exactly. So it comes back. PETER NIKOLOW: It's coming back. But if you troll 401, it crawls less and less more that page. And on my tests, after first crawling, that page is gone. It's-- ULRIKA VIBERG: So if you want to remove a full section, is it better to put a 410 on the pages than a 404?  

#### [0:30:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=1830) |  MARTIN SPLITT: In practice, the difference is

relatively small. But basically what you're doing, as Peter explained, you're giving us a different signal. 404 means not found, 410 means gone, which means I made this go away, versus I don't know what you're trying to do here. So you give us a more clear signal. But in practice, unfortunately, a bunch of people are giving us incorrect signals when they do not want to. Like they give us 410 when what they meant was a 404, or the other way around.  

#### [0:31:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=1860) |  So there is-- it's not like we're

literally just going to ban-hammer this. But it is a hint for us to not do that. And you might see better results with 410, but it's not a guarantee. PETER NIKOLOW: There is another problem that Martin probably will explain it better. What if you troll 401, 4010, to some page, and after two months, you change your mind? I want to return content to the same URL.  

#### [0:31:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=1890) |  ULRIKA VIBERG: Bummer. [CHUCKLES] PETER NIKOLOW: It's

banned from the things and it's harder Google Bot to get that crawled and later to get ranking. So 410 is very, very, very specific. MARTIN SPLITT: I mean, you can always submit it for indexing again. So that's not a problem. PETER NIKOLOW: But yes, but if Google Bot doesn't crawl that over and over, just like 410-- MARTIN SPLITT: It wouldn't return itself automatically,  

#### [0:32:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=1920) |  but yeah-- like, you can always-- it's

not that we're marking it as, do not ever do this again, but we're just not automatically crawling much more. So you can always bring it back. It's just more effort with a 410 maybe. JOHN MUELLER: So my opinion is controversial in that I think it's overrated, the difference. MARTIN SPLITT: [HUMMING DRAMATICALLY] Dun dun dun. JOHN MUELLER: I think, in the past-- I mean, theoretically, you're right. We remove it a little bit faster with a 410.  

#### [0:32:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=1950) |  But I think, in practice, it doesn't

really matter. ULRIKA VIBERG: Doesn't matter. JOHN MUELLER: Because we crawl pages on such a different schedule over time that, if we have to crawl it twice, then it's still going to drop out anyway. It's not like you remove a half of the site, and half of the site is gone tomorrow. But it'll still be removed over the next half year. And if you're talking about the next half year, then if something is removed within two weeks  

#### [0:33:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=1980) |  or within three weeks, it doesn't really

matter that much. And from that point of view, I think us kind of focusing on the difference between 410 and 404 is something where it's very easy for folks to get kind of stuck on or hung up on the specifics. Where, theoretically, sure, it's better. But it's not going to break something. So I have sometimes seen SEOs go and complain  

#### [0:33:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=2010) |  that, talking to a developer, it's like,

they use 404 instead of a 410. And it's like, our site is doomed. They're stupid. Why don't they understand things? And in practice, it's easy to spend a lot of time and energy on this small difference, where in practice, the difference is maybe, I don't know, a couple of weeks over the course of a couple of months, whereas it doesn't really change that much. MARTIN SPLITT: There's bigger fish to fry.  

#### [0:34:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=2040) |  ULRIKA VIBERG: I used it more to

sound clever. PETER NIKOLOW: Oh? JOHN MUELLER: I think there are a lot of these things around SEOs, where technically it's like, sure, that's the correct way to do it. But in practice, there's so many other things that play a role that's, like, doing it technically correct, if you can do it with the same amount of work, fine, go for it. But if it's a significant more amount of work involved in doing it technically the correct way and the end result is the same, then you have to kind of make a choice there  

#### [0:34:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=2070) |  and say, well, I can't personally do

it. I have to hire developers to make it a 410 instead of a 404. And that's a lot of work, and a lot of time also that you spend in reviewing their work and making sure it's a 410 that you could be spending focusing on other things within a website. So that's kind of tricky in that sense. I mean, SEO is, to some extent, very much based  

#### [0:35:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=2100) |  on all of these small things adding

up. So I understand that too. OK. Yeah. Do you have a question-- ULRIKA VIBERG: No, thank you. JOHN MUELLER: OK, cool. MARTIN SPLITT: Do we have more submitted questions? Or do we have more live questions? No live questions? JOHN MUELLER: OK, fine. I have more submitted-- AUDIENCE: I've got one potentially, if that's OK. JOHN MUELLER: OK, go for it.  

#### [0:35:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=2130) |  AUDIENCE: It's more JavaScript. I guess how--

what's the easiest way to look at a shadow DOM if you were to review a site, and go, OK, where you've got-- I saw your rendering talk on the Tech Boost. That was really good. Thank you. I just need to know, like, what's the best way to look at a shadow DOM and compare it to a dot-- what Chrome sees or something like that, do you know what I mean? See if there's any differences that could be happening. MARTIN SPLITT: Mm-hmm, yes. So there's two ways of doing that, of inspecting the shadow DOM. The easiest way is, within the developer tools,  

#### [0:36:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=2160) |  if you go Inspect, you see the

elements. So basically shadow DOM is usually used with web components that have their own HTML tag. You find these because they have to have a dash in the name. So a normal HTML tags, like, I don't know, header, footer, H1, P, whatever, they do not have a dash in the name. But if it's like, content-accordion or content-carousel, then that's a very good indicator that this is actually a web component. And then you can right-click, Inspect. And then, within the inspector, you see a hash shadow root.  

#### [0:36:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=2190) |  And you can expand that. And pretty

much whatever is in there is what the shadow DOM contains, which is also what you probably see in Chrome, as in like you see the site. You know what you see there. If you want to inspect it the way that Google Bot sees, then you can use any of the testing tools, as in like the mobile-friendly test, the live test in Search Console, the rich results test, on any of these-- you see the rendered HTML.  

#### [0:37:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=2220) |  And within the rendered HTML, you see

what we would be seeing. So we are flattening whatever it is in the shadow DOM. So if you use techniques that actually copy the content from live DOM into shadow DOM, you would see that. But you would also see the shadow DOM content. But you don't see where the shadow border would be. AUDIENCE: OK. [CHUCKLES] MARTIN SPLITT: Did that make-- that was very technical and very hard to explain without the visual. [INTERPOSING VOICES] MARTIN SPLITT: Does not make sense? AUDIENCE: Yeah. Is there some sort of, I guess-- I know it's kind of hard to say. But if you had to quickly look at a page,  

#### [0:37:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=2250) |  is there a plugin you might recommend

to help break that down easier to see the comparison? Or do you recommend there's nothing that you can't do like that? It's more of a back end. MARTIN SPLITT: What's exactly the goal you're trying to accomplish with this? AUDIENCE: Just to sort of simulate the kind of web rendering view of the page. So where you have got the shadow DOM, and the DOM, you kind of want to say, well, we also need to be mindful of that shadow DOM. So I'm just saying, is there a way to say it? MARTIN SPLITT: Normally it doesn't matter.  

#### [0:38:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=2280) |  And if you want to see that,

again, use the mobile-friendly test or the rich results test, because there you see the rendered DOM, including what was originally in the shadow DOM. So if you see content not showing up in the rendered view, then you can use Inspect in Chrome to see if there might be a shadow DOM involved. AUDIENCE: OK, cool. Thanks. MARTIN SPLITT: You're welcome. Good question. Thank you. JOHN MUELLER: Cool. OK, now we have more controversial questions.  

#### [0:38:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=2310) |  MARTIN SPLITT: Oh no. JOHN MUELLER: If

a page is marked as noindex, but also has a canonical to an indexable page, other than being a mixed and kind of pointless signal, could there be a risk to the noindex being transferred to the target of the canonical? MARTIN SPLITT: That's a Dave question, isn't it? JOHN MUELLER: No. I mean, no is the answer. MARTIN SPLITT: No is the answer, yeah. JOHN MUELLER: No is the answer. But yes, it's a Dave question. MARTIN SPLITT: It's a Dave question. Good question, Dave. JOHN MUELLER: How did you know? MARTIN SPLITT: It sounded like one. JOHN MUELLER: In the reverse logic,  

#### [0:39:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=2340) |  if a page has a canonical link

pointing to a URL-- oh, no, it's cutting it off. [HUMMING] Let me refresh the page. MARTIN SPLITT: Do you have to expand it? Yeah. JOHN MUELLER: Yeah. [HUMMING] I will find it. So if there is a canonical link pointing to a URL that is noindex, would that be considered noindex too? Probably. Probably. We would think that it's kind of like a redirect to a noindex page. And we would drop that page. Thanks.  

#### [0:39:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=2370) |  AUDIENCE: Can I just ask, as well?

I assume, if you've got a 404 page, it doesn't really matter if there's any canonical or anything on that because it'd just be ignored. It just doesn't really see past that 404 header, yeah? JOHN MUELLER: Yeah, yeah. When we see a 404, we ignore the whole content. AUDIENCE: Yeah. Brilliant. Thank you. JOHN MUELLER: So that's something that-- I recently ran into someone who had staging sites get indexed. And the whole staging site would be  

#### [0:40:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=2400) |  returning 404 and actually showing normal content

to users. And if we start to index that staging site instead of their existing site, then suddenly everything would disappear. Does Google consume structured data better if it's coded in a graph V separate snippets of code in JSON-LD? I don't know what a graph V is. MARTIN SPLITT: I'm not sure what that is. I've never heard that before.  

#### [0:40:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=2430) |  JOHN MUELLER: I guess that's a no.

[CHUCKLES] MARTIN SPLITT: Do we have that person in the Hangout? Do you want to clarify the question if you're here? Paul. Maybe not, no. JOHN MUELLER: OK, fine. Maybe you can clarify for the next Hangout, and then we can get to that. I'd like to know if duplicated pages/alternate page with proper canonical tags are marked excluded in the coverage report. I don't know offhand.  

![](https://i.ytimg.com/vi/FWyFif98YAw/hq3.jpg)



#### [0:41:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=2460) |  And at the same time, those pages

still appear in the search results. Oh, OK, like m-dot or AMP pages. Does that mean they're excluded? Or are they not excluded? So what happens here, similar to the hreflang question in the beginning, is we will index the primary version of the page. And we'll use that for indexing. But we will swap out the URL against the alternate version when we show it in the search results.  

#### [0:41:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=2490) |  So it would be excluded for indexing.

Because we index the primary version. But we would know to swap out the URL, as appropriate, in the search results. So it's confusing when you look at the search results. But we try to do the right thing by just indexing the main version. So yeah, I suspect that looks weird in Search Console. In mobile usability, if the content is too small to read  

#### [0:42:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=2520) |  but it isn't the main content of

the page-- for example, terms and conditions-- Google Search Console will throw errors. So will that impact the ranking of the page? I don't know what threshold we would use there. So I imagine, in Search Console, we would flag that because technically these pages are not mobile-friendly. So they'd be flagged on mobile usability report. And it might be something that we would kind of not  

#### [0:42:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=2550) |  show as highly in the search results

because we think the pages themselves are actually not mobile-friendly. So that's something where, usually, I'd recommend, if you have content on a page that you want to use on a page, then make it readable. Or just don't put it on the page if you don't want it readable. OK, I'm just going to continue here until someone stops me. AUDIENCE: Hey. It's me. JOHN MUELLER: Yes. AUDIENCE: [CHUCKLES] OK, so I have this group of websites.  

#### [0:43:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=2580) |  They are all hosted on the same

server-- I mean, not server, but hosting company. And from time to time, I get some warnings of those security warnings saying that my content has been hacked. I tried going really, really deep into those, tried looking at server logs and everything else. And I even tried using the Mobile-friendly Testing Tool to see exactly what Google was seeing on the page. But it's still the same. I copied the source code, divved them,  

#### [0:43:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=2610) |  and besides some minor changes, like variable

names and stuff, they were all the same. So I'm thinking that maybe our anti-bot protection system is maybe flagging the Google Bot or Google security system as a bot, and then it's showing a Captcha page to it. So maybe then the content would be really different to the security program  

#### [0:44:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=2640) |  than for the actual Google Bot. But

I can't debug that. Or I don't have anything-- I don't have a source code that Google is seeing. So I can tell what's happening there. JOHN MUELLER: What exactly is the message that you're seeing? AUDIENCE: Content injection. JOHN MUELLER: Content injection? OK. I don't know. Have you seen that?  

#### [0:44:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=2670) |  PETER NIKOLOW: No. JOHN MUELLER: I have

some ideas. OK. MARTIN SPLITT: Have you audited the JavaScript that you are using? Is there potential third-party content that you don't have control over in the page? AUDIENCE: There are content-- like third-party [INAUDIBLE] stuff, kind of like that. MARTIN SPLITT: Third-party-- excuse me, what was that? Third-party what-- AUDIENCE: Third-party-- I'm missing the name in English. Advertising platforms. MARTIN SPLITT: Ah, OK, ads. OK. AUDIENCE: Not actually platforms, just tracking.  

#### [0:45:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=2700) |  MARTIN SPLITT: Ah, right, OK. AUDIENCE: I

had that happen to one of my Google News websites. And basically it was a plugin issue that-- is it hosted on WordPress? AUDIENCE: No. MARTIN SPLITT: No. OK. AUDIENCE: Most of the time it's something that-- basically it's a code that you need to kind of look for and remove it. AUDIENCE: I would if I knew--  

#### [0:45:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=2730) |  I mean, I divved everything, I divved

the source, I divved DOM. MARTIN SPLITT: Have you tried looking at the source in one of our testing tools? AUDIENCE: Yes, Mobile-friendly Testing Tools [INAUDIBLE].. MARTIN SPLITT: And there's nothing fishy in there either? AUDIENCE: No. JOHN MUELLER: So I think what could be happening-- if you're pretty sure that it's really not hacked, the Captcha page would not be the issue. That's kind of just first off.  

#### [0:46:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=2760) |  So even if you were to show

a Captcha page to Google Bot from time to time, that would not be flagged as hacked or content injection. What could be happening is that we're getting confused by some of the content on your pages. So for example, if you have, I don't know, like an extreme case-- you have an e-commerce site. And suddenly, you have one page with pharmaceuticals on it. Then our systems might think, well, pharmaceuticals is something that is often used by hackers  

#### [0:46:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=2790) |  to inject into websites. And this website

looks like it's not a pharmaceutical site. So maybe someone is injecting pharmaceutical content into these pages. But it could be the case that you're actually displaying this content purposely, that you're saying, well, it's like, we have this special offer in, I don't know, maybe something that isn't even pharmaceuticals. I don't know, you have a t-shirt with, I don't know, Viagra branding or something-- something crazy  

#### [0:47:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=2820) |  where you have those keywords on those

pages. And when we crawl and index the page, we think, oh, all of these pharmaceutical keywords on a t-shirt site. It sounds like it's hacked. And then that might be something that we would flag. And usually what happens there is, as we reprocess those pages, we realize, oh, that's fine. And kind of the warning goes away on its own. So if you're really sure that there's nothing hacked on your site, that the JavaScripts are OK,  

#### [0:47:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=2850) |  nothing is being injected there, and you

have some content that kind of touches upon areas which are sometimes used by spammers or hackers, then I would assume that it's going in that direction. One thing I would do there is maybe bring this up in the Webmaster Help Forums so that people can escalate those specific examples from your site to the team. And we can take a look to see if there's something we need to handle better algorithmically. Because sometimes we flag things incorrectly like this.  

#### [0:48:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=2880) |  It can get a bit confusing. And

it just helps us to improve our algorithms if we have more examples of where we get it wrong. AUDIENCE: OK, I'll do that. Just to clarify, are there any plans on showing us the actual source code or what Google is seeing there? JOHN MUELLER: I think we tried to do that. And in some cases, we can do that. Specifically for malware-- like hacked from malware, we tried to show the snippet of the page where we found that.  

#### [0:48:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=2910) |  But for some kinds of issues where

just "this doesn't feel right" kind of thing, we don't have anything specific to pinpoint. AUDIENCE: OK, thank you. JOHN MUELLER: Sure. Let me just double-check some of the next questions. And we can run through those quickly. So I'm planning to replace my WordPress site with a normal HTML PHP site. So WordPress is PHP. PETER NIKOLOW: Mm-hmm.  

#### [0:49:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=2940) |  JOHN MUELLER: What should we do so

that we don't lose any rankings and visibility? There basically is no answer for this. If you're changing your website, you're changing your website. And we'll reflect that in search. That includes things like the back end and the UI, the internal linking, any of that. That can theoretically affect the crawling and indexing of your site. It can also be a positive thing. So you can also improve your site by replacing it.  

#### [0:49:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=2970) |  There's an undesirable site link showing up

for the Google search for Facebook Support. How can we kind tackle that and get rid of it or fix it. So site links are algorithmically generated. There's no manual way to tweak things up and down and to say, like, I don't want this and I do want that. So there are essentially two things. On the one hand, try to see if this is really something  

#### [0:50:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=3000) |  that the majority of people are seeing,

if it's really a problem or not. Sometimes it's just something that you see with personalized results because you always go there. And the other thing is, if it's really a big problem that this page is being shown at all in the search results, then probably you'd need to noindex that so that the page really drops out completely. Because it's essentially a normal, organic search result. Other approaches you can do are things like changing the title of the page to make it clearer what it should be about.  

#### [0:50:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=3030) |  And then, wow, so many more questions.

We're so short on time. Maybe I can just open up for more questions from you all. Any of you. AUDIENCE: Hey, John. Hi, guys. JOHN MUELLER: Hi. AUDIENCE: So, quick one-- well, I hope so-- so let's assume we have a very big website, like an e-commerce website. Let's say 500,000 products, something like that.  

#### [0:51:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=3060) |  Of course a lot of categories holding

those products. And assuming that most categories-- or assuming every link to a given product has a tracking parameter added to it-- so for example, they want to see, what position what the product within the category when it was clicked. So it has a P equals a number or something like that. And [INAUDIBLE] all of these products URLs do have a canonical tag to the product without those parameters attached.  

#### [0:51:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=3090) |  So they're canonicalized correctly. However, there is

nowhere on the website a way for Google to actually get to those canonical version of URLs directly, only through the sitemap. What would be the like the biggest downside of doing that? And I assume one of that would be the crawl budget, because they're kind of forcing Google Bot to continuously go over those URLs, even if they're canonicalizing elsewhere.  

#### [0:52:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=3120) |  JOHN MUELLER: Yeah, I think crawling is

one thing. The other thing is maybe we will index the other versions anyway. PETER NIKOLOW: And also canonicalization between that pages also can be like an issue. So maybe answer for me, OK, is not showing to the Google Bot that URL parameter for the product URLs.  

#### [0:52:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=3150) |  JOHN MUELLER: It's kind of like cloaking

I guess. [INTERPOSING VOICES] OK. I mean, one thing you could do is use hash URLs for those keys. Maybe that would work. That could kind of make it so that the key is still passed, but it would need to be processed in JavaScript. And from there you can do something with it. The other thing, I guess, is the URL Parameter Handling Tool. You could work with that to just say, ignore these.  

#### [0:53:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=3180) |  The other is kind of like, if

you leave it to canonicalization and you're OK with sometimes a decision going the wrong way, then try it out. But kind of keep in mind that it could happen that we canonical to those keyed URLs instead of your preferred ones. PETER NIKOLOW: [INAUDIBLE] JOHN MUELLER: OK. PETER NIKOLOW: My solution is, for example, if you have categories, you know,  

#### [0:53:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=3210) |  on Google I/O, previous years. There was

excellent video about that, that Google Bot track on URL with anchor. But if you make that anchor is visible, but you make a supersede, like a div that will work on unclick, Google Bot won't see that unclick URL and won't crawl them. JOHN MUELLER: Oh, that's fancy. OK. ULRIKA VIBERG: Yeah. JOHN MUELLER: OK. AUDIENCE: Just out of curiosity, if you  

#### [0:54:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=3240) |  use the URL Parameter Tool to force

Google to ignore-- well, not ignore. I mean, I guess we would choose that the content isn't changed in that option. Is it the same as, like, using a hash symbol for parameters? Is it basically the same thing? Would it achieve the same effect? JOHN MUELLER: Yeah, pretty similar. So we would still occasionally look at those URLs to double-check that it's OK. But probably we would just follow that, yeah.  

#### [0:54:30](https://www.youtube.com/watch?v=FWyFif98YAw&t=3270) |  AUDIENCE: OK, and since that wouldn't involve

any development work, that would be the easiest route to take. OK, awesome. Thanks. JOHN MUELLER: Cool, OK. So I think we have to get out of this room soon. So I'd just like to thank all of you, all of you came here in person, all of you who joined virtually. Thank you all for coming. Thanks for submitting so many questions. And I hope to see you all again in the future sometime. I guess some of you tomorrow, even.  

#### [0:55:00](https://www.youtube.com/watch?v=FWyFif98YAw&t=3300) |  ULRIKA VIBERG: Yeah. JOHN MUELLER: Yeah. Cool.

All right, thanks, everyone. MARTIN SPLITT: Bye. [INTERPOSING VOICES] JOHN MUELLER: I think we have to stop recording. MARTIN SPLITT: Mm-hmm.  