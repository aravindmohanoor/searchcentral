[![English Google SEO office-hours from January 15, 2021](https://i.ytimg.com/vi/puNqYcqyClQ/hqdefault.jpg)](https://www.youtube.com/watch?v=puNqYcqyClQ)

## English Google SEO office-hours from January 15, 2021

This is a recording of the Google SEO office-hours hangout from January 15, 2021. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Find out more at https://developers.google.com/search/events/join-office-hours



Feel free to join us - we welcome webmasters of all levels!



#### [0:00:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=0) |  JOHN MUELLER: All right. Welcome, everyone, to

today's Google SEO Office Hours. My name is John Mueller. I'm a Search Advocate at Google here in Switzerland. And part of what we do are these Office Hour Hangouts where people can join in and ask their questions around their websites, and SEO, and Google Search, and all of that. A bunch of things were already submitted. But as always, if any of you want to get started with a question, you're welcome to hop on in.  

#### [0:00:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=30) |  AUDIENCE: Hey, John. How's it going? JOHN

MUELLER: Hi. AUDIENCE: So my question is pretty quick. There's this website that keeps showing up in search results, in very prominent positions. And the problem is that when you actually click on the links from that website, it actually takes you to something else completely irrelevant for those queries. And obviously it's taking up valuable real estate  

#### [0:01:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=60) |  from other websites that would be more

relevant for those terms. So my question is, first of all, why doesn't Google pick up on these situations and remove those websites from the index? Because in this particular example, I've been seeing this publication for over a year. And if I may send you, in the chat box, perhaps, the URL so you can investigate. JOHN MUELLER: Sure. Sure, yeah.  

#### [0:01:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=90) |  Feel free to drop a link in

the chat. In particular, also, queries where you're seeing this kind of an issue. It kind of depends a bit on what is actually happening there. If it's more that they're returning content which isn't great, then that can happen. If it's a matter of being redirected to malware or to phishing content, then that's a little bit of a different situation. And usually that's something where,  

#### [0:02:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=120) |  if you submit it to the appropriate

forums, then someone from that team will take a look at that. But if it's just like low-quality content, and you don't think it should be ranking like that, then sometimes that's a matter of discussion rather than something where there's like a clear yes-or-no thing that we can do or where the web spam team would jump in and make a manual action. But I'm happy to take a look at the examples and pass that on to whatever team  

#### [0:02:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=150) |  needs to take a look there. AUDIENCE:

Cool. Thank you. AUDIENCE: Hi, John. How are you? JOHN MUELLER: Hi. AUDIENCE: So my question is about [INAUDIBLE] report in Search Console. So we are working on web vitals. And Search Console is [INAUDIBLE] that there are few pages on the website that have a poor CLS score. So when we check those URLs in PageSpeed Insights or other tools like webpagespeed.org,  

#### [0:03:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=180) |  the score is pretty good, like 0.06.

But Search Console is reporting it around 0.60 or more than that. So I'm not sure what we can do here. Because Search Console is saying something else, and PSI, something else. So what do suggest we can do here? JOHN MUELLER: Yeah, I think what you're seeing there is the difference between lab data and field data. So lab data is when you do a theoretical test.  

#### [0:03:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=210) |  And you're kind of theoretically looking at

the website using your connection, using your browser, using a standardized browser, a standardized connection, or what have you. And field data is the data that is actually collected from users when they're using Chrome and accessing the website. And in many cases, the lab data is kind of predictive of the field data that you would see there.  

#### [0:04:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=240) |  But there definitely are situations where what

you see in your kind of theoretical tests doesn't match exactly what your users are actually seeing. And that can happen, for example, if a lot of your users are in locations where they have a bad internet connectivity or where they use devices that tend to be different than what you're testing for. And that's kind of where that difference tends to come from.  

#### [0:04:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=270) |  AUDIENCE: [INAUDIBLE] And in our case, actually,

the Search Console is giving like 0.60 for that URL. But PageSpeed Insights, in field data and lab data, in both these sections, it is showing around 0.04 or 0.06. So the difference is pretty much-- only Search Console is getting some kind of error. But PageSpeed Insights or other tools are not getting. So field data is pretty good, 0.06. Lab data is 0.04.  

#### [0:05:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=300) |  But Search Console is saying that it's

0.6. JOHN MUELLER: Yeah, I mean, the Search Console data is based on the Chrome User Experience Report data, which is the field data. So it's not that Search Console is doing separate tests there. And what might just be happening is that there's kind of a time delay that you're seeing there. But essentially they're based on the same data. The other effect that you might be seeing is that we're grouping things slightly differently  

#### [0:05:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=330) |  in Search Console than when you test

them individually. But that's also something which tends to settle down over time. AUDIENCE: So should we wait? JOHN MUELLER: I would continue to keep an eye on it. But Search Console is not inventing these numbers. It's not making these measurements itself. It's basing them on something that it  

#### [0:06:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=360) |  has seen from the field data. So

I would definitely take the time to investigate a little bit further. Try other parts of your website and try the Chrome User Experience Report field data directly, all of those things. AUDIENCE: OK, sure, thank you. JOHN MUELLER: Sure. AUDIENCE: Hi, John. How are you? AUDIENCE: Hi, John. JOHN MUELLER: I don't know who was first. AUDIENCE: He can go. It's OK. No problem.  

#### [0:06:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=390) |  JOHN MUELLER: OK. AUDIENCE: Is it OK?

OK, thanks. So John, I have a question about international SEO. So we have multiple websites for different countries. And actually they have the similar content in English. We have used, of course, the hreflang for each website. And actually we are facing a major decision-- whether we should keep it like this, with different ccTLDs or just switch to a generic domain with subfolders.  

#### [0:07:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=420) |  So we're not sure yet which one

to choose. JOHN MUELLER: Yeah. From our side, both of those approaches would be valid. So it's not something where we would say there's an inherent SEO advantage of ccTLDs or a generic domain with subdirectories. Both of those would be valid approaches. The only thing I would keep in mind is, if you make a change,  

#### [0:07:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=450) |  try to make a change that you

can live with in the long run. Because every time you restructure your website, you will see some fluctuations. It will take a bit of time for everything to settle down again. So it's not so much that it'll be better automatically or worse automatically. It's just, during that transition time, which might be a month, might be two months, you will see fluctuations. And search will have trouble kind  

#### [0:08:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=480) |  of understanding the full picture of your

website. So if you make a decision, make it based on what you want to have for the long run. And kind of realize that you will see fluctuations. So maybe plan the timing in a way that it doesn't affect your business overall, that you can say, well, people are not searching so much during this time. So I'll do the migration there. AUDIENCE: So [INAUDIBLE] while it's having this kind of structure, having multiple of sites,  

#### [0:08:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=510) |  is fine for ranking factors. So it

doesn't matter whether we switch to subfolders or keep it like this. JOHN MUELLER: Yeah, exactly. For SEO reasons, both of these are valid. Sometimes there are policy reasons to change. Sometimes there are practical reasons that the infrastructure is more expensive or takes more time to maintain. All of those, I think, are valid reasons. For SEO reasons, you can do either way.  

#### [0:09:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=540) |  AUDIENCE: OK, and you've said something interesting

about the change. Actually our URLs for the blog posts, let's say the current path is URL/thePostName. So is it bad, for example, to change the structure to site.com/blog/postName? So is this change could harm our ranking factors? So it's very important to know this.  

#### [0:09:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=570) |  JOHN MUELLER: You will also see fluctuations

when you make that change. But afterwards, it can be the same as before. So it's not that you automatically have an advantage or disadvantage from changing the URLs. But it will just take time to settle down and be understood. AUDIENCE: OK, thank you. You can go, Mike. Sorry. AUDIENCE: All right, thank you. Hey, John, I have a question regarding search intent?  

#### [0:10:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=600) |  How does Google handle search intent? Does

BERT have anything to do with it? And what can I do to optimize my website for better search intent? JOHN MUELLER: I mean, search intent is kind of based on what users are looking for, what they're trying to do. So it's not so much that you would optimize your website for search intent, but rather you would optimize your website for what it is that your users are looking for and how they're searching. So that's something where you could look at the queries that  

#### [0:10:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=630) |  are going to your website. You could

also do user studies for kind of a broader batch of users who maybe are not going to your website already. And based on that, try to figure out what aspects do I need to cover there. AUDIENCE: So, for example, if a user is saying a specific query, a long-tail query, then I should have that exact sentence on my website? Is that what you're saying? JOHN MUELLER: It doesn't have to be the exact sentence. But if you're seeing that as a pattern of something  

#### [0:11:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=660) |  significant with regards to traffic to your

website, then you can kind of assume people have this kind of a question and they're trying to find information on that. So it's less a matter of you have to match that sentence one to one. But if you think this is an important query, then have some content that kind of addresses those questions. So it doesn't have to match exactly. But it would be good if it helps to kind of solve the problem that you think these users are having.  

#### [0:11:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=690) |  AUDIENCE: And BERT has nothing to do

with that, or it does have something to do with it? JOHN MUELLER: I mean, BERT is more about better understanding the queries and better understanding the content. So it's not that you would be optimizing for BERT or anything like that. It's more that we just try to match the content and the queries a little bit better. AUDIENCE: OK, thank you. JOHN MUELLER: Sure. AUDIENCE: Can I also offer a small point of view here? JOHN MUELLER: Sure.  

#### [0:12:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=720) |  AUDIENCE: We generally try to figure out

kind of the same thing, search intent behind certain queries, in order to kind of understand what kind of pages should be created or optimized. And this is specifically for more general queries, where not even knowing the audience, you're not really sure what people are looking for. So for example, somebody searches for something like progressive glasses, you're not sure if they're searching to buy something,  

#### [0:12:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=750) |  you're not sure if they're searching to

understand what they are or are searching for information. So I think a good way to go about it is basically to check the top-down results, kind of figure out-- kind of, so to speak, reverse-engineer what Google kind of thinks that the most relevant results should be. Like maybe more informational results-- because if there are just informational results, and you're trying to improve or optimize the commercial page,  

#### [0:13:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=780) |  that might not have a lot of

chance to rank because it's not really relevant based on the intent that the user is looking for more information about the subject, not necessarily to purchase anything. And that can change. I've noticed, for example, certain holidays like Black Friday and things like that, the search intent might actually change a bit. And the search results might change to be a bit more commercial maybe, rather than informational. Or something that's newsworthy might change that a bit as well.  

#### [0:13:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=810) |  But that's kind of the general idea

of using what else is ranking in the top results to kind of understand what kind of page you should create in order to make sure you're relevant for whatever the users are searching for. AUDIENCE: I also noticed, too, depending on the search query, that the tabs at the top of Google change. So whether it's an image, a video, a map, whatever it is, that order will actually change based upon the query. So does that give me any insight to what information  

#### [0:14:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=840) |  I should have and the hierarchy of

the information I should have on my page? JOHN MUELLER: I think it's useful to take a look at these kind of things and kind of the existing top rankings. But you need to also kind of keep in mind that you're kind of optimizing for the current situation, where, especially with a query like Black Friday, if, in the summer, you're saying, oh, I want to optimize for Black Friday, and you search for it, then you'll find informational content on that.  

#### [0:14:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=870) |  Whereas during the time that you care

about, that informational content is probably not the right thing to kind of focus on with your website. So it's something worth keeping in mind, that the current results are kind of representative of the current state of our understanding of those queries but not necessarily of the long-term understanding. AUDIENCE: Gotcha. AUDIENCE: John, question about a SafeSearch filter,  

![](https://i.ytimg.com/vi/puNqYcqyClQ/hq1.jpg)



#### [0:15:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=900) |  and potentially content that I'm concerned is

getting filtered by the SafeSearch. And I can see why, potentially. But I want to try and understand, is there a way to definitively tell if content is being filtered by a SafeSearch? And if so, and once we can determine that, and I make changes to try and get around that,  

#### [0:15:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=930) |  do I need to wait for just

Google to recrawl that content or those images? Or does it need to pass through another algorithm, and filter, or manual action, or something like this? JOHN MUELLER: The easy way to test if SafeSearch is kind of triggering for that content is to just turn the SafeSearch filter on and off. So doing something like a site query, and then just, in the search URL, on top, you can just add,  

#### [0:16:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=960) |  ampersand, safe equals on, I think, or

safe equals off. And based on that, you'll see if there are different results. And if there are no different results, then SafeSearch is essentially not affecting that site. AUDIENCE: OK, so just [INAUDIBLE] site polling with SafeSearch on or off, and analyzing those results. OK, simple as that. JOHN MUELLER: Yeah, yeah. And with regards to kind of changes that you make on your website, that  

#### [0:16:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=990) |  is something where we have to reprocess

the content and we have to kind of re-understand it a little bit. So it's a little bit longer than just recrawling. But if it's individual pages, usually that's pretty fast. If it's a broader part of your website that we kind of misclassified in that regard, then that can take a bit longer for us to kind of aggregate those signals on a broader level. AUDIENCE: So if it's images we're specifically concerned about, that would affect the entire URL that those images are on?  

#### [0:17:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1020) |  JOHN MUELLER: Yeah. AUDIENCE: Yeah, OK. JOHN

MUELLER: I mean, yeah, because we associate the image with the landing page. And if there's something problematic in the image, then it's very likely that we'll just say, well, kind of this pair of landing page and image is the thing that we have to filter for SafeSearch. AUDIENCE: Got it. And then I think, earlier, at the end of last year, you had mentioned that if the site is being flagged in SafeSearch or has been flagged  

#### [0:17:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1050) |  as having adult content, that it won't

be eligible for rich results. Is that across the board or on those pages specifically? Or did I misinterpret that? JOHN MUELLER: I think that's specific to the pages that are affected. AUDIENCE: OK. JOHN MUELLER: So with regards to a SafeSearch, it's something where we try to do it as granular as possible. But we can't always do that. So sometimes, if we have individual pages across the site that we think we need  

#### [0:18:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1080) |  to fall into the SafeSearch category, it's

possible that our algorithms will just say, we'll take the whole domain, and say, we don't know for sure. So that's something that kind of plays in there as well. It's like the individual pages are essentially what we try to focus on. But if we don't know for sure that these individual pages are OK or not. And I mean, it's not like a quality kind of assessment. It's just SafeSearch or not--  

#### [0:18:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1110) |  then it's possible that we'll filter that

out for those pages. AUDIENCE: John, I think we talked about this in, like, 2014 or so, when all these female celebrities were being hacked. I had an entertainment site. And we were doing legitimate reporting about so-and-so was hacked. So there was "naked photo" or "naked video" were the words. And just by reporting on it, the sheer number of those women who kept being hacked, we were getting bucketed.  

#### [0:19:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1140) |  I think you said that the systems

were sort of accidentally bucketing-- not accidentally, but they were seeing, because it was over two or three days, a ton of that content, that you're writing repeatedly the word and the subject matter, that you could get bucketed. I think that's what happened. It was about six years ago or so. JOHN MUELLER: Yeah, yeah. AUDIENCE: Cool. AUDIENCE: Thank you. AUDIENCE: Hi, John. I might have a short and sweet question. Google, earlier, announced that the rollout of the new page  

#### [0:19:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1170) |  experience ranking signals, like LCP, and FID,

and things like that-- that the rollout was May 2021. I was wondering if this is a global rollout on May 2021, or are there certain countries going to be before that date, after that date. I'm asking specifically for the Belgian market. JOHN MUELLER: My understanding is that this is a global rollout. So it's something that we collect on a global scale. And there is no big reason to not do that on a global level  

#### [0:20:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1200) |  if we can. So my understanding is

it will be global. With regards to kind of experiments before that, I don't know for sure. So in particular, we want to do kind of that badging of the search results when we see that a site is within the good page experience bucket. And usually badging is really hard to do, is really hard to get right. So we have to do a lot of tests before we kind of figure out  

#### [0:20:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1230) |  which way to badge these search results.

And my assumption is that we will have some tests around the badging before that time. And some of those might get seen, some of those might not get seen. But it's something where, when we make visible changes in search like that, we really have to be sure that we do them in a way that the average user can understand them fairly quickly.  

#### [0:21:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1260) |  AUDIENCE: OK, thanks. AUDIENCE: Hi there, John.

Yeah, I work in a camper van rental company. And recently we have been facing a big problem that I've been losing a lot of time to, the last few months. Basically, in specific regions of the UK, we see that, for specific queries, that have kind of the same terms-- the searching tactics are exactly the same, I think. I'm going to give you an example,  

#### [0:21:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1290) |  like "campervan rental" and "camper van rental,"

we see that our competition has consistent results. They basically rank on the first page. And for the two queries, they keep the same position. While our company, for "campervan rental," for example, goes like top five, 10 results, and "camper van rental," we go to 60th or 80th position. And I went deep into this problem,  

#### [0:22:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1320) |  and I checked how many times I

used this word. I hate to go keyword by keyword, but I actually did it this time. And I see they don't use it-- there's no discrepancy here. Like they use it as much as we do. And I'm trying to figure it out. And I'm losing my mind about this. JOHN MUELLER: OK. I suspect what is happening there is that we don't see these words as being 100% synonyms.  

#### [0:22:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1350) |  And that's something that our systems try

to pick up automatically. So it's not that we have-- or at least as far as I know, I don't think we have linguistic models that are there to try to figure out are the possible synonyms for these words. But rather we see these are unique queries. And we try to understand what the entities are behind that and to try to match that as much as possible. But probably we don't see them as 100% synonyms.  

#### [0:23:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1380) |  Otherwise the results would be exactly the

same. And that's something that is-- usually it just works itself out over time, in that when we have enough data to understand that, OK, people searching for the word together mean exactly the same thing as with separate words. Then that's something that we'll take into account and say, OK, this is more of a synonym rather than just like kind of very similar.  

#### [0:23:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1410) |  And with regards to optimizing for something

like this, improving your rankings, I don't really have any super-fancy tips there. It's more a matter of, if you're seeing that a lot of people are searching in one particular way, then maybe use that way on your website as well so that we can find that appropriately across your site.  

#### [0:24:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1440) |  And if you're seeing kind of a

balance between those two ways, and you're seeing that Google isn't matching them as synonyms or as being kind of close together, then maybe it makes sense to mention both of those variations on some pages. It is kind of an awkward shift into kind of the traditional SEO picture of, like, oh, they're just optimizing for all synonyms. And usually we figure that out fairly well.  

#### [0:24:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1470) |  But sometimes it's kind of more practical

to say, well, Google will figure it out at some point. But I need to solve it for myself now, so I just kind of do the awkward thing. AUDIENCE: All right. Thank you very much. JOHN MUELLER: And there was a video, I think, when was it, fall 2019, from Webmaster Conference in Mountain View, from Paul Haahr. So Paul Haahr is one of the top Quality engineers  

#### [0:25:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1500) |  that works at Google on search quality.

And he mentions quite a bit around synonyms and how we pick that up, how we understand which words belong together, which words don't. It's not going to solve your problem, but it'll give you a little bit of background information on what might be happening there. AUDIENCE: All right. Thank you very much. JOHN MUELLER: Sure. AUDIENCE: Hi, John. Our website has about 60,000 products.  

#### [0:25:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1530) |  And we have a rather robust, layered

navigation that uses a number of product attributes. We're preparing to go to a migration to a new system where our search parameters are going to be changing from the current system to the new one. And we were hoping to preserve some of our value for many of those parameters since they do appear in the search results page. What is your suggestion on the best approach to take to preserving SEO value for those legacy URLs  

#### [0:26:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1560) |  once we're on a new system? Should

we preserve those? Should we translate them? How do you see that playing out? JOHN MUELLER: Yeah. I think, any time you do a migration on a URL level, ideally you would redirect the old URLs to the appropriate new ones. So if you're changing parameters or the setup on how you use the parameters within your website, and you care about the old or the URLs,  

#### [0:26:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1590) |  then make sure that you have redirect

set up. And with that, we can pretty much pass all of the value there. And if you have a very complex setup for your website, where you can't just set up redirects for everything automatically, then I would at least take a look at the traffic that you're seeing from search for the URLs on your site. And make sure that the most important URLs or the most important URL patterns are covered with redirects. AUDIENCE: So we shouldn't do anything  

#### [0:27:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1620) |  like noindex the legacy URLs or anything

like that? JOHN MUELLER: No. I would not use-- I mean, if it's something that you care about the traffic to the old URLs, kind of that gets forwarded to the new ones, then I would definitely make sure you have a redirect set up. Or at least, if you can't do a redirect, then set the rel canonical to the appropriate new URL so that we can forward any of the value collected with those old URLs.  

#### [0:27:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1650) |  If you use a no index and

just create the new ones, then essentially all of the value that was collected by the old URLs gets dropped. AUDIENCE: Oh, that's great to know. Thank you very much. JOHN MUELLER: Sure. OK, let me run through some of the submitted questions. And we'll have some more time for other questions from everyone along the way. I think some of them we might already have covered or gone through. So the first one I have here is, our business  

#### [0:28:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1680) |  is going through a rebrand and a

system update. And we're planning on executing quite a hefty migration. And then they list a ton of different things that they're doing, like a domain migration, CMS migration, consolidating pages, updating content, updating the site structure, template redesign, switching hosting providers. And kind of the question is, how should we do this? From my point of view, these are all pretty big changes.  

#### [0:28:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1710) |  So it's something where you will definitely

see fluctuations along the way. And that's something where, if you plan to do so many different changes because you think the end state will be important, then you could theoretically spread that out and do it one after another. But practically speaking, that's probably not going to work. So practically, you're probably going to have to bite the bullet and say, well, I will switch from the old setup to the new setup.  

#### [0:29:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1740) |  And make sure that you have all

of those details from the migration kind of nailed down. In particular, all of the redirects that you need from the individual URLs, any internal linking that you have, structured data that uses URLs, all of that, that it matches the new setup. And usually that means creating tons of spreadsheets and really big lists of URLs, and matching things so that, beforehand, you have a really clear plan of what  

#### [0:29:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1770) |  you need to do. And once you

do the migration, you can do kind of QA of the migration, and really confirm that you have everything lined up. And kind of that confirmation that you have everything lined up is really critical. Because you will see fluctuations, at least the kind of intermittently, while things are being reprocessed. And you need to be sure that you can kind of trust that these fluctuations will settle down.  

![](https://i.ytimg.com/vi/puNqYcqyClQ/hq2.jpg)



#### [0:30:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1800) |  And you can only kind of trust

that if you're sure that you have really done all of the details right. And that's something where you don't want to wait for everything to settle down to figure out, oh, I forgot to redirect my blog, and now everything is gone. And potentially the most dangerous thing with regards to the rankings there, it's important to keep in mind that you will see changes  

#### [0:30:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1830) |  in ranking, at least during the migration.

You will see different rankings afterwards as well. If you have a really clear plan and you have a really nice setup for the final configuration there, maybe you will see positive changes overall. If the final setup is a lot more confusing than the initial setup, maybe you will see lower rankings. So it's not possible to guarantee that the final configuration will be equivalent in terms of SEO to the initial one.  

#### [0:31:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1860) |  And sometimes it's not even reasonably possible

to determine what order of magnitude the final setup will be. In particular, if you have multiple sites that you're combining into a single site, it's not really possible to just add up all of the traffic the individual sites got before and assume that your new site will get it. It's possible that your new site will be so much stronger that you'll get a lot more traffic. It's also possible that the combination  

#### [0:31:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1890) |  that you're doing essentially results in one

site rather than a couple of sites, and that you might lose some visibility in search. So if you're doing this for the first time, I would definitely recommend getting help from someone who's done it before so that you can hear some war stories around migrations, what went wrong, and make sure that you don't do those things. Do you have any information regarding Web Stories, when they might be released in Australia?  

#### [0:32:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1920) |  We want to be early adopters. So

if we can get any estimation. I don't have any information on when the new features will launch, particularly Web Stories in Australia. With Web Stories, it's important to keep in mind they are normal pages too. So you can already adopt and use these Web Stories on your website. And we will crawl and index them like normal pages as well.  

#### [0:32:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1950) |  And when we start to kind of

show them more visibly, you'll see them a little bit differently in the search results. You might see them more prominently in Discover as well. But essentially you can go ahead and implement these already. With regards to us kind of turning on individual features in individual countries, sometimes that's a matter of working out the policies, working out the technical details. Sometimes that's also a matter of us being able to look into the data from the country  

#### [0:33:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=1980) |  and say, oh, lots of people are

already implementing this structured data. Maybe we should just turn it on for them. So in that regard, if you're tempted to try something like this out, I would say go for it, even if you're not seeing all of the advantages yet. Please detail the difference between a doorway page and a landing page, and why doorway pages are frowned upon. So usually-- and I think we have a Help Center article about this-- but usually doorway pages  

#### [0:33:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2010) |  are individual pages where you're just funneling

people to the actual part of your website that you care about. And my assumption is that, for the most part, our systems are able to understand this doorway pages better nowadays anyway, so that when we look at these doorway pages, we see, oh, this is a kind of a low-quality page. It mentions these keywords, but it's kind of a low-quality page. So we will probably not show it as visibly in search anyway.  

#### [0:34:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2040) |  But essentially the idea is that, instead

of setting up a number of different pages for just variations of different keywords, make one really strong page that really kind of covers that topic really well so that our systems can recognize, this is a fantastic page. And appropriately, we can understand, wow, this is a part of this bigger website which is also really fantastic. And that helps us to kind of better rank those pages overall.  

#### [0:34:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2070) |  Will adding History API functionality into infinite-scroll

pages-- is that enough? Or do I need to add physical pagination links on top of this? Yes, if you're using infinite scroll, then having paginated links is very important for us, because then we can crawl and index those paginated links separately. History API is something we can sometimes pick up on. But often it relies on kind of the user doing  

#### [0:35:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2100) |  something specific on a page, like scrolling

to a specific location. And Googlebot, in general, when rendering a page, does not trigger any of these actions, but rather renders a page in kind of a really long viewport. And maybe that will trigger your history API or not. Whereas if you have links to the individual paginated versions of those pages, then for sure we can figure out, these are the different pages. They belong to this one list.  

#### [0:35:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2130) |  And we can index those individually. So

History API alone, without using links on the page, is kind of hit and miss. And depending on how you implement it, it's likely that we won't be able to pick up on those paginated versions. The other thing to keep in mind is sometimes we don't need to trigger infinite scroll on a website. So in particular, if you have something like a blog on a category page, and you use infinite scroll there, if we can already find all of those blog posts,  

#### [0:36:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2160) |  then we don't really need to trigger

infinite scroll. So it's not something where you'd have to say, well, if we use infinite scroll, we must make sure that it's crawlable. But rather it's like, it's a good practice, and if you care about those pages being indexed, then, sure, you should watch out to make sure that they're crawlable. If you don't care, it's like that's totally up to you. Please tell us about Google Sites search.  

#### [0:36:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2190) |  So I don't really have a lot

of information about Google Sites. I think we have a Help forum specifically for Google Sites. And I would recommend going there. So I don't really know what the kind of things to watch out for with regards to Google Sites. John, since you mentioned earlier, regarding pagination, I know there is an old video from [INAUDIBLE] regarding what  

#### [0:37:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2220) |  kind of options you have in terms

of pagination, basically the view-all page or-- it was then run [? next run ?] [? prev. ?] And she mentions in the video that if Google does find the view-all page on the site, it will usually prefer to show that page in the search results. So obviously, if you don't want that, then you can use the normal pagination and Google will kind of figure it out on its own. What I noticed is that, for a couple of our clients where we  

#### [0:37:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2250) |  have a view-all page but it simply

was there because the platform allows you to see kind of all of the results, and there's a parameter like "page equals all" or something like that, Google will actually use that, index that and rank that, despite us not wanting to-- it has a canonical to the nonparameter version. But Google simply seems to be ignoring it. And I wonder whether it is because Google kind of figured  

#### [0:38:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2280) |  out, oh, this is a view-all page.

This is a strong signal for us to kind of use it despite having a canonical to something else. So yeah. And those kind of view-all pages, in some cases, can create a bit of problems. Because it's loads, in some cases, 200, 300 products. So the page kind of starts to load fairly slowly. And other than a redirect, I don't see how else we could kind of push Google to stop using that page and just use  

#### [0:38:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2310) |  the canonical versions of that. JOHN MUELLER:

Yeah. I don't know what we do with the view-all pages at the moment. My guess is that you might be linking to that view-all page from all of the pages within the paginated set. And then we'll say, oh, this must be a really important page. We should focus on it instead of the individual paginated versions. That might be where we're picking that up.  

#### [0:39:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2340) |  But that then kind of depends on,

well, do you want to keep a view-all page or not? And if you don't want to keep a view-all page, then obviously don't link to it. And then we'll kind of work that out. If you do want to link to it, then maybe we will index it. AUDIENCE: Yeah, it looks like we're linking to it. So yeah. I thought it was just a dropdown with, like, no anchor or actually links, like HTML tags.  

#### [0:39:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2370) |  But it looks that they are HTML

tags. So yeah, that seems to make sense. So removing it might lead Google to drop it and use it the-- yeah, OK. JOHN MUELLER: Yeah, yeah. AUDIENCE: Cool. JOHN MUELLER: Then a question about backlink badges. So I don't know, this seems like something that's feels a little bit older. But the question is, a few days ago, I invited members of my website to use an HTML snippet that  

#### [0:40:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2400) |  shows a badge on their websites linking

back to their profile page on my website. Users may edit the HTML snippet to their needs. The default Alt tag is a picture of one of the site's main keywords. Using the badge is entirely voluntary. There are no incentives whatsoever. And using the picture itself without a backlink is also possible. In other words, users will use the badges solely to show their appreciation for the website in question and promote their profiles on their website. Is there anything wrong with that?  

#### [0:40:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2430) |  That sounds essentially OK. I mean, that's

something where, if there is really no kind of value associated with that link in terms of, it's like, you must link to my website with this badge in order to gain access to these features or whatever, then that's perfectly fine. Some sites do this in other ways. For example, that they'll have a link on a page that says, link to this page.  

#### [0:41:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2460) |  And you click on that, it opens

a little text window where there's an HTML snippet that you can use and just copy that to your website. That's also perfectly fine. The important part is really that this is completely voluntary, that people are able to edit this kind of markup if they want to use it or not. That's essentially the important part. Then there is another question about CLS and kind of PageSpeed Insights, and the field data there.  

#### [0:41:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2490) |  I think we talked about that a

little bit beforehand as well. I think also goes into kind of a difference between the field data that you see in PageSpeed Insights and the data in Search Console. So I'll definitely pass this on to the Search Console team to take a look at. If you have any examples, feel free to drop them in the chat or send them my way, maybe on Twitter, for example. Having specific examples makes it a little bit easier.  

#### [0:42:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2520) |  Does it negatively affect SEO for internal

linking if an anchor tag only contains a button tag? Does Googlebot take the text inside the button tag into account as a signal for internal links? Or would it be better to use plain text inside of an anchor tag? So at least as far as I understand it, by default, a button element on a page is essentially tied to a form element.  

#### [0:42:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2550) |  And you can use JavaScript to trigger

kind of a navigation to a specific URL, which makes it kind of like a link. But essentially, Googlebot won't click on these buttons to see what happens. So we would not see that there's a link associated to another URL within your website. So in that regard, if you want to use something that looks like a button for internal navigation, then I would use normal HTML links, and just style it,  

#### [0:43:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2580) |  with CSS, to make it look like

a button, rather than to use button elements in HTML and then add JavaScript that kind of makes them act like a link. Question about internationalization-- we have the same version of the website in English for different countries. And we use hreflang and-- I think this is similar to the question we had in the beginning.  

#### [0:43:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2610) |  So currently we're using different ccTLDs for

the individual countries. And we'd like to move to a generic domain with subdirectories. And yeah, like I mentioned, we support both of those setups with regards to international websites as long as the main domain is really a generic top-level domain. So the question here mentions .io. I believe .io is, theoretically, a country-code top-level  

#### [0:44:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2640) |  domain. It might be that we treat

.io as a generic top-level domain. You can look that up in our Help documentation. But I believe, by default, that's a country-code top-level domain. And for country-code top-level domains, you would not be able to set geotargeting. So that's one thing to kind of watch out for. Sometimes the cute top-level domains are actually country-code top-level domains.  

#### [0:44:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2670) |  And it's worthwhile to double-check that you

can actually set the geotargeting in Search Console before you invest everything to move all of your international versions into that [INAUDIBLE].. AUDIENCE: John, I had a query about international websites. So I just wanted to understand, if there is one page in top-level domain, and we  

#### [0:45:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2700) |  have decided to go with ccTLDs or

we have decided to create separate country pages for the same page, in that case, obviously older pages was having a lot of backlinks. But now new pages won't be having those backlinks. In that case, how does Google deal with backlinks to main page if we have expanded to different country-level pages?  

![](https://i.ytimg.com/vi/puNqYcqyClQ/hq3.jpg)



#### [0:45:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2730) |  So for example, I have, right now,

one page in .com And we have decided to go ahead with three separate countries. Because from them we are getting good number of leads. So we have plan to go ahead with separate country pages for those countries, like .pk for Pakistan, .in for India. But the problem is that older pages ranking in India. And if I am introducing new .in page, that won't be having any backlinks. But hreflang tag would be mapped properly.  

#### [0:46:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2760) |  JOHN MUELLER: Yeah. So if you create

new pages and they're not linked internally, then we would see them as kind of separate pages. With regards to hreflang, what would happen there is, if we understand that these pages are part of a set, and we see a user from a different country kind of doing a search where we would show that page in the search results, then with hreflang, we would swap that out.  

#### [0:46:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2790) |  But by default, if you expand your

website to include more countries, then you're kind of, in a sense, diluting the value of your pages by expanding it across multiple country versions. So you really have to keep in mind that you should also focus on those country versions, that you shouldn't just say, oh, I can make like 50 different country versions of my website now. And you shouldn't assume that copying everything onto 50 different versions will make it more visible rather  

#### [0:47:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2820) |  than maybe even less visible, because you're

kind of like diluting the value across all of those. So if you're adding individual pages, then I would definitely make sure that you have normal HTML links between those existing pages and individual country pages so that we can understand how those new pages kind of map within your website. And hreflang helps us a little bit, but hreflang is not the same as a normal link on a page. AUDIENCE: So in that case, internal linking is fine.  

#### [0:47:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2850) |  We will be doing it. hreflang tag,

also we will be doing. My only concern was that older page was getting the backlinks from India. Now there is new India page targeted for India market. In that case, will hreflang tags swap all external backlinks to new page? JOHN MUELLER: It depends on what you do. Like if you take that existing page and you link to your new India page, then we can forward some of that value. It's not the same as kind of redirecting or posting  

#### [0:48:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2880) |  everything on the existing page. But it

does spread some of that value. So it's not the case that you have to kind of like work to get individual links to all variations of all of your pages. But rather that kind of spreads naturally with the internal linking of your site. AUDIENCE: Thanks. JOHN MUELLER: Sure. All right, let me see. One, I guess, quick question here-- if I do follow backlinks due to paying bloggers  

#### [0:48:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2910) |  to write highly relevant review articles or

paying for high-quality PR news articles, are they paid links that go against Google's guidelines? So I feel like this question is asked a little bit pointed. And I guess the quick and easy answer is, yes, if you're paying people to create content with links, then you're paying people for those links. And if you're paying for links, then that would be something that would be against our webmaster  

#### [0:49:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2940) |  guidelines. So that's kind of the easy

answer there. Of course, if you're kind of-- if these links do not pass page rank, if they have the nofollow attached to it or rel="sponsored" attached to it, then that can be fine. That's essentially a way of advertising your website. It doesn't pass any value to your website. But it still helps users to find your content and kind of indirectly helps to promote  

#### [0:49:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=2970) |  your content and your website. So maybe

that helps a little bit. Then a question-- I think there were two similar ones like this, with regards to structured data types for tourism companies. In the schema.org website, there are different suggestions for travel sector, such as tourist trip, travel agency, or trip. Are the schema types mentioned above supported or relevant for Google indexing and ranking? If not, what would be the most suitable structured data  

#### [0:50:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=3000) |  type for a Trip landing page? So

it's important to differentiate between kind of the broader schema.org ecosystem, where there are lots of different ways that you can add structured data to individual pages, and the Google side of that, in terms of Google Search. So in particular, we support a subset of the functionality, or the different types of markup, from schema.org. And those are the things that we would  

#### [0:50:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=3030) |  show in the search results. And everything

else is essentially kind of, I don't know, more like a nice-to-have, or more like something where you're adding a little bit of extra information to your pages. But I would not expect to see any change in search because of that. And I think that refers to all three of those types in that sense. So what I would recommend doing is going to our Search  

#### [0:51:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=3060) |  Developer documentation, and looking at the rich

results types that we have listed there, and trying to work out which of these types map to the kind of content that you have, and then kind of focusing on those types first so that you kind of have the visible effect kind of nailed down and you kind of know that, if you spend time on that specific kind of markup, you will have a visible effect in search. And then, if you want to go further and provide  

#### [0:51:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=3090) |  additional information through other schema.org types, you're

welcome to do that. I would just assume, by default, that you would not see any effect in search at all. So there is a slight sense of, well, we understand the pages a little bit better with more types of structured data on our page. But I would not assume that that's something that would have a visible effect in terms of ranking or better visibility in search.  

#### [0:52:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=3120) |  So that's kind of the direction I

would go there. OK, we're running low on time. So I'll switch to more questions from you all. And I have a little bit more time afterwards as well if any of you want to hang around a little bit longer, ask more questions, or whatnot. AUDIENCE: John, I saw some tweets this week, with you and Gary, about an old subject. But it's still a favorite--  

#### [0:52:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=3150) |  domain names. You know, an old domain,

name whether you're going to have problems with it down the road because you bought one that had bad content, bad links directly to it. I mean, the only way I know of is to look through Wayback Machine. But that will give you a sense, OK, maybe it was parked or maybe it had content. But could you ever really tell if it had links? Is there a way to do that? And then I guess the next step would be to disavow if one needed to. JOHN MUELLER: Yeah. I mean, to disavow, you'd have to have the site verified  

#### [0:53:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=3180) |  in Search Console. So if you have

it verified, then you'll also see links in Search Console. So that kind of helps a little bit. If you're still at a stage where you're unsure if you should buy that domain name or not, then maybe it makes sense to look at some of the third-party link-checking tools that are out there. I think there are a number of providers that essentially crawl the web, similar to how we do it, and provide some aggregate use of those domains.  

#### [0:53:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=3210) |  And usually you'll see that it matches

a little bit what you would see in the Wayback Machine, where you see, like, OK, this is, I don't know, a small business. And the links that you would find are probably like the links that a small business might have. Or maybe it was a casino or some crazy affiliate site. Then you can kind of assume that, well, probably the links will also be similar in that regard. AUDIENCE: Thank you.  

#### [0:54:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=3240) |  JOHN MUELLER: Cool. AUDIENCE: Hi John, I'll

just jump in. So I do have a question about how Google's treating the date modified for certain articles. So we've tested live blog posting. And we've noticed that Google consistently either ignores or cannot correctly detect our last-modified date. So what we tend to see is, we've updated the post, let's say, five minutes ago, and Google's still  

#### [0:54:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=3270) |  showing in the service that it was

updated or published seven hours ago or four hours ago, something like that. So I think this puts us at a competitive disadvantage. We do have the proper markup in Schema. Our front end does reflect the correct last-updated-date timestamp. And it's also in our sitemap. So I'm curious if you have any insights as to how we can kind of solve that one. JOHN MUELLER: I'd almost need to see some examples where  

#### [0:55:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=3300) |  we get that wrong so that I

could pass that on to the team. So one thing that's important is that we're able to recognize the same date on the page as well. So if you have a date set in the article structured data for the modification date, then that should be something that's also visible on the page as well. So that's one thing to keep in mind. The other thing is to watch out for time zones.  

#### [0:55:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=3330) |  That's something that I've sometimes seen, where

people will specify a date and a time on the site, and we're kind of not sure about which time zone that refers to. And then we can't match that correctly to the structured data on the page. So that's kind of another aspect that sometimes plays in there. And I guess a third thing that I've sometimes seen is sometimes we get it wrong in terms of maybe we'll show the proper date in the normal search results,  

#### [0:56:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=3360) |  and then in the-- what is it,

I think the top stories, or the different news blocks that we have, sometimes we'll show a date that is several hours off. And I believe we fixed that. But if you're still seeing something like that, that kind of like a different timestamp is shown in different places in search, then I'd love to have some screenshots of that happening. AUDIENCE: Yes, so we are seeing that as well.  

#### [0:56:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=3390) |  So I'll definitely send those over. I'll

send you an email if that works. I do have another question on the same topic. So our live version also has the same component, right? But for some reason our AMP cache doesn't update with our current updates. And we've tried purging manually. We've tried it over API. And it should kind of work alongside with the updates  

#### [0:57:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=3420) |  on the non-AMP version. But for some

reason this is not at least being accepted by Google. So I'm curious if you have any thoughts on that as well. JOHN MUELLER: I don't know how that is connected. So my general answer there would be to use the API to request those cache updates. But it sounds like you're already doing that. So I don't know what might need to be done there additionally. Is that specific to pages where you're  

#### [0:57:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=3450) |  updating things on the page, kind of

like the liveblog situation? AUDIENCE: Specifically the liveblog. So for other pages, we can request a purge, and it will update. It may take some time, but it will update. But for this liveblog, for some reason, it doesn't take. It does give us like a 200 response and everything. But we don't see any kind of changes on the operation. JOHN MUELLER: OK, yeah, if you can send me some examples of that too, that would be useful. AUDIENCE: OK. Thanks so much.  

#### [0:58:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=3480) |  AUDIENCE: All right, John, if I may

jump in. JOHN MUELLER: Sure. AUDIENCE: I have a problem with a site and submitting the site map in Google Search Console. When I try to submit the sitemap, Search Console will give me a generic HTP error. And when I have a look at the server log files, then I can see that Googlebot can fetch the sitemap, with a 200 status code.  

#### [0:58:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=3510) |  And I can load the sitemap from

a web browser using all the other tools. The sitemap is structurally correct. I've tested it using various tools. And it's within the limits of 50 megabytes and 50,000 URLs. So do you have any idea what I could try to make Search Console to accept and download the sitemap? JOHN MUELLER: It sounds like you're testing for most of the important things. One aspect that sometimes plays in there  

#### [0:59:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=3540) |  is kind of the topic around crawl

budget. I don't know if that's something that might apply in your site, in the sense that, if we're having trouble crawling enough from your website, then it might be that we would deprioritize something like that sitemap file. But it's hard to say. So what I would do there is either send me the URL so that I can take a look, or post maybe in the Search Help forum  

#### [0:59:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=3570) |  so that some of the other people

can throw an eye on it and give you some initial feedback and escalate it if need be. AUDIENCE: Can I send you the URL in the private chat? JOHN MUELLER: Sure, sure. AUDIENCE: OK, I will do. Thanks. JOHN MUELLER: Sure. OK, let me take a break here and just pause the recording. And you're welcome to kind of hang around a little bit longer as well if you'd like to. But just so that we have kind of a reasonable length  

#### [1:00:00](https://www.youtube.com/watch?v=puNqYcqyClQ&t=3600) |  for the recording. Thank you all for

joining in. Thanks for all of the many questions that were submitted and that were asked here. If there's something on your mind that you still need to find an answer for, I'd recommend going to the Search Central Help forum and asking the folks there. The people there are pretty smart and have a lot of experience with websites. So they can generally help you along. And they can also escalate issues if something pops up that is completely weird or different. So maybe that will help.  

#### [1:00:30](https://www.youtube.com/watch?v=puNqYcqyClQ&t=3630) |  I'll set up more of these Office

Hour Hangouts as well. So if you want to join in one of the future episodes, watch out for the-- I think the YouTube community page is where we list them all. And they're also on the event calendar on the Search Central site. All right, with that, I'll pause the recording. And see you all next time.  