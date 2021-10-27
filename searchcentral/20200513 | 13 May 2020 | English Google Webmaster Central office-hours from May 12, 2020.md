[![English Google Webmaster Central office-hours from May 12, 2020](https://i.ytimg.com/vi/GXFmWVg_QfA/maxresdefault.jpg)](https://www.youtube.com/watch?v=GXFmWVg_QfA)

## English Google Webmaster Central office-hours from May 12, 2020

This is a recording of the Google Webmaster Central office-hours hangout from May 12, 2020. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Watch out for new sessions, and add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



Feel free to join us - we welcome webmasters of all levels!



#### [0:00:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=0) |  JOHN MUELLER: All right. Welcome, everyone, to

today's Webmaster Central Office Hour Hangouts. My name is John Mueller. I am a Webmaster Trends Analyst here at Google in Switzerland-- or, well, still in Switzerland but not in the office, at least. And part of what we do are these office hour Hangouts, where people can join in and ask questions around their website and web search, and we can try to find answers, if that's possible.  

#### [0:00:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=30) |  As always, a bunch of stuff was

submitted already on YouTube. But if any of you want to get started with a first question, you're welcome to jump on in now. LAURA CONDRUT: Hi, John. JOHN MUELLER: Hi. LAURA CONDRUT: We have an issue with the meta description that is being displayed for our home page. So even though we have a meta description that is being implemented on that particular page, somehow in Google, when our website appears,  

#### [0:01:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=60) |  the meta description is completely different. And

in some cases, if we search for our company name plus the word "UK," the meta description makes no sense whatsoever. It's just a bunch of words put together from various parts of the page. I know sometimes Google goes hunting for various things on the page if it cannot find relevant content for that particular region. So I guess my question is--  

#### [0:01:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=90) |  because we have a lot of traffic

that is coming up from branded searches, so it is important for us to have the correct meta description showing up-- what do we do to rectify the situation? JOHN MUELLER: It's hard to say without looking at the search results. So that's kind of the one part. Usually, what happens is, we need to have the description meta tag on the page. So that's kind of the first step.  

#### [0:02:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=120) |  It sounds like you already have that

set up. The other thing there is that we need to be able to, I guess, trust the meta description on the page so that it looks kind of reasonable. In particular, sometimes when we see a bunch of keywords that are just kind of collected in the meta description, then that's something that our systems might look at and say, well, this doesn't look that useful for user. So they'll try to rewrite something else.  

#### [0:02:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=150) |  And most of the time, when it

tries to rewrite something, it's based on the content on the page itself. And the other thing, like you noticed, is the description can vary depending on the query that is used. So the first thing that I would do is just take the normal branded query that you use and double-check that the description that you provide in the meta description is actually pretty useful and not too, kind of, spammy or overdone.  

#### [0:03:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=180) |  And then go from there, essentially, to

figure out, is this something where Google always gets it wrong? Or is it something where sometimes Google's algorithms pick up something else on the page and get it wrong? If you feel that it's something that Google is always picking up incorrectly, then I'd love to have some examples like that. So things like the queries, maybe a screenshot of what you're seeing, if you could send me that or maybe post it here  

#### [0:03:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=210) |  in the chat, that would be really

useful. LAURA CONDRUT: OK, cool. Yeah. Thank you. JOHN MUELLER: Sure. All right. Other questions from anyone before we get started? LAUREN MORRIS: Hi, John. I actually have a question around getting your website verified. We're trying to get our website verified through our analytics tag. We have the tag on the page. We actually use the Google Chrome extension  

#### [0:04:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=240) |  that detects if you have a tag

already on the page, and we're finding it in that. But when you actually go to the verification site and enter the URL for it, it's saying that it can't find the verification tag on the page, even though the user has all the edit access rights to that particular container that it's stored in. Do you have any tips for troubleshooting that? JOHN MUELLER: It's hard to say.  

#### [0:04:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=270) |  So sometimes, this is something where the

folks in the Webmaster help forum can help, because they can take a look to see for-- look at the common issues. One issue that I've seen a few times that has popped up is if the verification-- or if the, kind of, Google Analytics code is not exactly the same as we would provide that within Google Analytics, then that might still work for Analytics, because it's still proper JavaScript. But for Search Console, it would be something  

#### [0:05:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=300) |  that we might not recognize immediately. LAUREN

MORRIS: Got you. JOHN MUELLER: So that's probably what I would watch out for there. Because if you're saying that it's showing it with the Chrome extension, if it's working for Analytics, then it sounds like the JavaScript part is working well. It's working in a way that works well for Analytics, but the Search Console, when it tries to check that page, it just can't recognize that this is really that block of text that's used for verification.  

#### [0:05:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=330) |  LAUREN MORRIS: Sure. All right. Thank you.

JOHN MUELLER: Sure. PRAVEENKUMAR ELANGOVAN: Hey, John. JOHN MUELLER: Hi. PRAVEENKUMAR ELANGOVAN: Hi. John, I am having two questions on hreflang sitemap. The first question is, do we need to submit the same sitemap in all the language part. Like, let's take the example that comes [INAUDIBLE] and the product name. And do we need to submit this the same hreflang sitemap  

#### [0:06:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=360) |  in all the part of the language?

And the second question is, now we are using the Spanish-- sorry, the Brazilian Portuguese in our pages. And what will be the hreflang tag? Either it's PT only or PT BR. We are serving the language across the globe, not only the BR-- not only the Brazil. JOHN MUELLER: OK. So for the first one, in general with regards to hreflang,  

#### [0:06:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=390) |  we need to see both parts. So

we need to see-- kind of, if you have two pages that are connected with hreflang, we need to see the hreflang markup on that first page, and we need to see the same markup on the second page. So if you have, say, an English page and a Spanish page, we need to be able to see the markup for both of them independently. So if that markup is within separate hreflang sitemap files that you're using, then we would need  

#### [0:07:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=420) |  to see all of those versions. Depending

on the way you set up hreflang within the sitemap file, it's possible that you also just have one sitemap file that has all versions. And in that case, that's also fine. But if you split up the language versions into different language sitemaps, then we would need to see all of them. So that's kind of the first one. The other one with regards to Portuguese, with hreflang you can specify either a language alone,  

#### [0:07:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=450) |  or you can specify a language plus

a country if you want to target a specific language within a country. So if you had different Portuguese versions, like Portuguese for Portugal and Portuguese for Brazil, then marking that up appropriately with the country and the language version makes sense. If you just have one Portuguese version, and it's one of these two, then I would just use that language code and not the country code  

#### [0:08:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=480) |  as well. PRAVEENKUMAR ELANGOVAN: OK. Thank you,

John. JOHN MUELLER: Sure. NEYL BENJELLOUN: Hi, John. JOHN MUELLER: Hi. NEYL BENJELLOUN: So we have a website, and we extended it to multiple locations. It's a French website. And we forgot to put the hreflang. So at some point, like, Google de-indexed many pages, because they're similar. They're all in French. But even if they're all in French, every page is for a country.  

#### [0:08:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=510) |  So now we updated the hreflang, and

we asked Google to re-index the page. The crawl happened, but the pages are still de-indexed. I can't get them indexed. JOHN MUELLER: Is it the same content just for different countries? Or what-- NEYL BENJELLOUN: It's the same content, but the title is different and the header one is different. But these are trainings. So, you know, it's just the content of the same training,  

#### [0:09:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=540) |  but we have different headers and titles.

JOHN MUELLER: OK. So practically, what probably is happening here is we are recognizing that these pages are essentially the same, and we're folding them together. So we're seeing them as duplicates of one page, and we'll try to make it easier and just index that one page. And with the hreflang markup, essentially what happens  

#### [0:09:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=570) |  is, we don't change the indexing side,

so we would still index these as one page. But if we recognize that the hreflang markup is correct, then when a user searches in those individual countries, we would try to show the appropriate URL. So if you have a URL, say, I don't know, for-- let's use English-- English UK and a URL for English US, and it's the same content for whatever reasons,  

#### [0:10:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=600) |  and we fold them together as a

duplicate version, then what would happen is we would index just one of those. And if someone is searching in the US, we would show the US URL with the snippet and the title from kind of the one version that we have indexed. And if someone is searching in the UK, we would show the UK URL. So the indexing side wouldn't change, which makes it really complicated to kind of debug. But in the search results, we would use hreflang to swap out those your URLs.  

#### [0:10:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=630) |  And from our point of view, that's

something that kind of makes sense as an optimization for indexing, because we just have to index one version that we have to keep crawling one version, because it's all in that one version. But for the webmaster, it can be really tricky to monitor what is happening there. In particular, the index coverage report in Search Console will just show one of versions as being indexed, even though we show  

#### [0:11:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=660) |  both of those different URLs. And the

search performance report in Search Console will also just report on one of those URLs, the canonical one that we choose. But you can see if you switch to the-- I think the individual countries that you can see in that report-- you can still drill down and see how many users from this country saw that page and how many users from a different country saw the page. So it doesn't really fix the problem in that sense, in that we still just index one version.  

#### [0:11:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=690) |  But theoretically, we should be able to

swap out the individual URLs. If you need to have both versions of these indexed independently, maybe for tracking purposes, or maybe because you have a different rich result type depending on the individual country, for example, then you would need to make sure that the content itself of these pages is significantly different so that we wouldn't assume that these could be considered duplicates.  

#### [0:12:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=720) |  NEYL BENJELLOUN: Yeah. But actually, I mean,

it's the home page-- like, the domain.com/fr. I can't see it on Google, even in France. So even if I'm in France and I'm looking for the home page, I can't find it on Google. JOHN MUELLER: So the page isn't indexed at all? NEYL BENJELLOUN: Isn't indexed at all, yeah. Google dropped it. JOHN MUELLER: That's if you search for the company name, or-- NEYL BENJELLOUN: Yeah, the company name. Like, domain name training--  

#### [0:12:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=750) |  training center in France. And I can't

find it. I can't find it. JOHN MUELLER: OK. But in that case, it wouldn't be a situation where we would pick one version as a canonical. So that wouldn't be a matter of the duplication in the URLs. But it sounds like that's really just something where we're not indexing that page or that site at all, which, from a practical point of view, would usually  

#### [0:13:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=780) |  come from three things. It could be

a severe technical issue on the site from the start, essentially. It could be a manual action from the Web Spam team, which is not something that would happen if this is just duplicate content. That's not something where the Web Spam team would take action on. Or the third one that sometimes happens is that someone used the URL removal tool maybe incorrectly or accidentally and accidentally removed the site from being  

#### [0:13:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=810) |  shown in search results. NEYL BENJELLOUN: Like

Google in Search Console is saying like they picked the canonical URL. They're just indexed in the Canadian one. But they've dropped in all the other countries. JOHN MUELLER: Yeah. But in that case, we would still show the URL. NEYL BENJELLOUN: OK. JOHN MUELLER: So that's something-- if you're seeing that the canonical is chosen as one of these, then that's a situation where we would see  

![](https://i.ytimg.com/vi/GXFmWVg_QfA/maxres1.jpg)



#### [0:14:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=840) |  this as being duplicate content, essentially, and

we would pick one of those versions to index. But if you search for the company name, you should still see that result. It might be the Canadian URL, but essentially, we should still be able to show that. It would be different if it's really-- like, the whole website is not showing at all for users in that country. Then that's more a matter of these detailed technical issues. NEYL BENJELLOUN: So the hreflang isn't giving signals?  

#### [0:14:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=870) |  JOHN MUELLER: The hreflang helps us to

swap things out, but it doesn't change indexing. NEYL BENJELLOUN: OK. JOHN MUELLER: So if it's the same content on those two pages, that wouldn't be affected by hreflang. NEYL BENJELLOUN: Because that would be penalizing for us, because a French guy would see like a Canadian URL in the best case, so he wouldn't click on it. JOHN MUELLER: If you have hreflang set up properly, and we can recognize that across those pages, then we would swap out the URL against the local version.  

#### [0:15:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=900) |  NEYL BENJELLOUN: OK. JOHN MUELLER: Yeah. So--

It should-- NEYL BENJELLOUN: It would take maybe some time. Yeah, it would take some time, maybe. JOHN MUELLER: Yeah. So it should look OK, even though from a technical point of view, the indexing side would still be indexing the other version. NEYL BENJELLOUN: OK. OK, perfect. Thanks. JOHN MUELLER: Sure. Now, this kind of situation, especially with international websites and the same content in the same language, is really complicated sometimes.  

#### [0:15:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=930) |  NEYL BENJELLOUN: OK, thanks. JOHN MUELLER: All

right. Let me run through some of the submitted questions. And we can open things up to more questions from you all later on as well. We have some questions regarding the URL parameters tool in Search Console. In a significant number of cases, we've used the URLs with tracking parameters for interlinking. It's quite an amount of work to completely change this, so we decided to add parameters to the parameter tool. And now if we set the parameter to Representative URL  

#### [0:16:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=960) |  and to know this parameter doesn't affect

page content, does this mean Google will only crawl the URL version without a parameter? Will it still consolidate signals between the parameterized versions, but only crawl the URL without parameters? We don't want to negatively impact our interlinking because of these settings. So yes, this does essentially try to do the right thing, in that it recognizes that we've seen all of these different URLs, and we can fold them together into one  

#### [0:16:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=990) |  kind of representative URL and use that

one for indexing. So it consolidates all of those signals that we've seen and folds them into one version. With regards to crawling, if you choose the option Representative URL, it doesn't mean that we would crawl without a parameter. It might be that we would drop the parameter. It might be that we pick one value with that parameter and just crawl and index that version. But from a practical point of view, both of those  

#### [0:17:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1020) |  are essentially the same thing. And like

I said, from kind of in ranking point of view, from a signal's point of view, everything is folded together. So that would be fine. We noticed that half the parameters added to the URL parameter tools have disappeared. We had about 160 in January and now only 80. Is this problem with the dashboard displaying all the parameters, or should we add back the ones that are missing?  

#### [0:17:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1050) |  It feels like if you have 160

different parameters that you're adding to the parameter handling tool, then that seems like quite a complex website, where probably it would make sense to find ways to significantly reduce that number of parameters that you actually use. So parameter values is obviously something where you might have a lot of them. But individual parameter names feels like something where you should aim for, I don't know, maybe 20 maximum,  

#### [0:18:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1080) |  something like that, different parameter names. Because

otherwise, it's really, really hard to understand how to crawl and index a web site like this. So that's something where I don't quite know exactly what you're seeing with just a drop in parameters that you have listed there. But I'd really try to limit it to something that you can kind of watch over for a website.  

#### [0:18:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1110) |  Since the last core update in June

3, 2019, our news website has disappeared in Top Stories [INAUDIBLE].. We didn't make any technical changes which could explain this. And we analyzed our whole domain. We don't see anything. What do you think could be affecting us in that sense? We review our news articles, and we don't see any issue about that. So the updates from last June are a really long time ago.  

#### [0:19:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1140) |  So it's really hard to say what

specifically might have changed there. But in general, when it comes to core updates, we try to use these to essentially improve the relevance of our search results. And that's something where, oftentimes, that's-- if you're seeing changes from there, it's not because of any specific technical issue on your site or anything specifically that you're doing wrong, but rather where our algorithms have recognized for whatever  

#### [0:19:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1170) |  reason that maybe this website-- this search

result wasn't as relevant to some of the queries that we had shown it for in the past. And we have a long blog post about different things that you can do to kind of take a deep look into your website and see what you could be doing to improve. And so I don't want to kind of rehash the whole blog post. I kind of recommend taking a look at that. And if this is something where you're  

#### [0:20:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1200) |  seeing those changes since last year, then

that feels like something where it's not just kind of this one-off thing, where it's like a little bit that our algorithms are deciding to change things a little bit, but probably things are still in kind of a shape where you might be able to improve them overall. I'm receiving a content injection security message in Search Console for some of my URLs. I checked those pages with every possible aspect, including Google Expert Advice.  

#### [0:20:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1230) |  I even watched the latest video with

regards to security issues and didn't find any issue related. And there are a whole bunch of URLs, so I don't know. I'll pass these URLs onto our team to double-check. Usually, the content injection message is something that we would show if our systems believe that there's content that is hosted on your website or served through your website that might not be something  

#### [0:21:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1260) |  that you created yourself. That might be

something that maybe a spammer created or a hacker created, and they're hosting it on your website for some reason. Usually, this is something where, maybe if your website is about cars, and then suddenly there is pharmaceutical content in there, then our systems might say that, well, this feels like something where we need to be a bit more careful with it. In general, these kind of messages apply to individual URLs.  

#### [0:21:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1290) |  So it's not that your whole website

would be demoted or shown differently in the search results. It's really just those individual URLs. But I'll pass these on to our team to double-check to see if there is something maybe on our side that we're picking up wrong. Or maybe there is something that we can let you know about. Google is showing our old contact number as a featured snippet. Though we updated the new contact number, it's still showing the old one. The steps we've taken so far-- we updated the number and submitted for re-indexing;  

#### [0:22:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1320) |  applied for a Google My Business page,

which is still pending; removed the old number from existing pages and replaced it. So in general, these are the right things to do. If you're seeing things in a featured snippet, that would be due to, essentially, what we would show as a snippet on a page, which is based on the content itself. So updating the number on the page, removing that page from--  

#### [0:22:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1350) |  or removing that number from existing pages,

making sure that you have the new number in, maybe this description meta tag if that's where it was shown, or in any structured data that you have there. Those are kind of the right steps to take. With regards to updating the search results, sometimes this takes a little bit of time, though. So it's not always the case that you click the button for, kind of, submitting to index, and it updates it automatically.  

#### [0:23:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1380) |  Sometimes, this is a process that takes

a little bit longer. So I'd give it a little bit more time there. If it's really critical that this number is not shown in Search-- so for example, if it's a number that doesn't belong to you or a number that doesn't work at all, then what you can also use is the outdated content tool in Search Console, where you can tell us that there is specific content on this one page that has been removed.  

#### [0:23:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1410) |  And you can tell us what that

content is that was removed, the URL of that page. And then our tool will take a look at that and either suppress that snippet for the time being until it's been updated, or wait-- at least, wait until that search result is such that that old information that you used to have there is no longer in there, and then it would show that again. So that might be something that you could do if this is really  

#### [0:24:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1440) |  a critical issue. Recently I requested outdated

URL removal from the Search Console, and I noticed that the site colon domain is still showing the actual number of pages that are live on Google to me after the URL removal, and Search Console indexing status shows more pages even after removals, including previous outdated URLs. So the data doesn't match, even after the removals.  

#### [0:24:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1470) |  This creates confusion. So I think-- I'm

not exactly sure what you're seeing, but probably what you're seeing is kind of a mismatch between the site colon search results and the data in Search Console, specifically for the index coverage report. In general, the site colon number that you see in the search results, where it says, of about so many thousand URLs that we know for this site,  

#### [0:25:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1500) |  that number is optimized for speed and

not for accuracy. So I would not use a site colon request for any kind of diagnostics purposes. Instead, I would use, really, the number that are shown in the index coverage report in Search Console. That's based on what we actually have indexed for the site. So that's kind of the one thing. The other part is specifically with regards to the URL removal  

#### [0:25:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1530) |  tool in Search Console. The URL removal

tool doesn't remove your URLs from indexing. It essentially just hides them from Search. So in practice, what can happen here is that the URL might not be shown at all, or would not be shown at all, in the search results, but would still be counted in the index coverage report for the time being, until we've remove that URL completely from our index. So that's something where you might see a mismatch there as  

#### [0:26:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1560) |  well. In particular, if you remove a

large part of your URLs using the URL removal tool-- maybe a whole subdirectory-full or subdomain-full-- then that's something that could significantly affect the number of URLs shown in Search, but wouldn't necessarily affect the number of URLs that we have indexed in Search. So we might have indexed them, we know about them, but we would not show them. If you want those removed from indexing as well, then you need to make sure that there  

#### [0:26:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1590) |  is a "no index" on those pages,

that there is a 404 status code, all of those usual things that you would do to remove pages from the index. We have multiple location website. The content of the pages is similar, so Google dropped the .com/fr page and said the domain.com/ca page is canonical. I think we talked about this briefly in the beginning, so I'll skip this one. Google currently limits the number of URLs  

#### [0:27:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1620) |  in a sitemap to 50,000 URLs. Does

that include hreflang alternate URLs, videos, and images? No. It specifically specifies kind of the primary URL elements there. I don't know. I think that tag is the loc-- L-O-C-- component tag that we use in the sitemap file. Not 100% sure. But essentially, it's the pages that is limited in a sitemap file. The attributes where you have extra information  

#### [0:27:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1650) |  for those individual pages, like hreflang alternates,

videos, or images, those are not counted in the totals. In practice, they're kind of a part of the totals as well, because there is also a limit on the file size of a sitemap file. So if you have a large number of other URLs that you supply in addition to those pages, then usually the file size would get large enough that it would also be too large and would need to be split into separate sitemap files.  

#### [0:28:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1680) |  But you can create separate sitemap files.

You can submit them individually. You can submit a sitemap index file which points at a number of different sitemap files automatically. So all of that is possible to really exceed those limits by quite a bit. We've seen some websites being targeted by Black Hat SEO. They have consistent bad links pointed at them daily, and they've also seen some big drops. We're constantly having to block links.  

![](https://i.ytimg.com/vi/GXFmWVg_QfA/maxres2.jpg)



#### [0:28:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1710) |  Do you still maintain that bad links

don't matter? So this is certainly something that our systems work really hard on to make sure that any kind of negative SEO, or any kind of irrelevant back links, unnatural back links, that as much as possible we're able to ignore them completely. Usually, the cases where I see that something around negative SEO is happening are kind of the cases where, when you would  

#### [0:29:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1740) |  look at them manually, you would say,

well, this looks like maybe someone has built these links up over the past. And it's not really a competitor but maybe an SEO that's been working for the company. So that's something where our Web Spam team, if they look at that and they see this kind of situation, where it's really kind of improbable that a competitor has built up links for a website over the course of the last decade,  

#### [0:29:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1770) |  then that might be something where the

Web Spam team would say, well, maybe you should clean those links up. Second part is, we've seen some websites that were hit by Google BERT update, and they still have not recovered. Was that update only about intent? Because it seems like it was about more. So BERT is, essentially, a way of better understanding text. It's not a ranking change in that sense. It's not an update--  

#### [0:30:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1800) |  kind of algorithm update, that suddenly we

rank things differently. But it's really about understanding text. So it means that we work hard to understand when people enter queries into the search results. In particular, when these are long queries where we need to understand, what is the context here, what is something that people are actually searching for within this query. And when it comes to pages themselves, we try to figure out what are those pages actually about,  

#### [0:30:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1830) |  and how do those pages map to

those specific queries that we've got. So it's not a ranking change per se. It's really about understanding the text on the page and the text that people enter in the queries. And from that point of view, it's not that websites get hit by this update. It's really that we're trying to understand what these pages are about. And if these pages are such that it's really hard to understand what they're about, then users will have trouble with them  

#### [0:31:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1860) |  and our search engine will have also

trouble with them. Usually, in the cases I've looked at where people say they were hit by this kind of update, it's more that there were just general changes in Search over time that also took place. And we make changes in search all the time, so it's not necessarily the case that, because Google understands the pages better, we suddenly decided to kind of penalize a set of individual pages.  

#### [0:31:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1890) |  Because we're trying to understand these pages

better, not try to understand what people are doing things wrong. Image search results sometimes show images from a related product section on an e-commerce site with the title of the containing page-- another product page. This could lead to results with the title product A and an image of product B, misleading users and creating false information. We saw it also on big sites like Etsy.  

#### [0:32:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1920) |  Is there any way to signal to

Google that these images are not describing the page but are describing the target page, similar to how an anchor text describes target pages? Or is there another way to solve this problem? So in general, we do try to understand where the primary images on a page are and to use those for image search primarily. So if you're embedding the main images  

#### [0:32:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1950) |  in a visible way within a page,

in particular if you're also using the structure data to tell us about those images on a page-- for example, if you have the article markup or something similar, and you can really specify the primary images on a page-- then that's something that makes it easier for us, with regards to Google Images, to understand which images we should be associating with this particular page. Obviously, if you have related images, kind of like thumbnails--  

#### [0:33:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=1980) |  [COUGHS] sorry-- thumbnails leading to other pages,

and those other pages are not indexable, or the primary image on those other pages is not recognizable, then it can still happen that we would show those thumbnail images associated with that particular landing page as well. So that's something where, if we don't have anything better, then we might choose something suboptimal. But if you can specify those images in an optimal way,  

#### [0:33:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2010) |  then it's a lot easier for us

to pick those up and to actually use them. Many times, due to website structure, we have long and weird anchor text-- price, number of reviews, review text, ratings are included in the anchor text. Is it OK for SEO, or should we fix it? Or should we just make sure that important keywords are present in the initial part of the anchor text? So from our point of view, you can leave your anchor text  

#### [0:34:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2040) |  as natural as you want. And if

you're including more information in an anchor text, that's perfectly fine. It's not the case that we, kind of, count the words in an anchor text and only evaluate each word as a fraction of the total number of words in a piece of anchor text. If you're giving us more context about a specific page on your website through the anchor text, then that's fantastic. So for the most part, I wouldn't recommend  

#### [0:34:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2070) |  doing anything particularly artificial for the anchor

text just to make sure that only the keywords that you want to have associated with that page are visible in the anchor text. On one of our mobile domains, I'm seeing that level 3 depth category pages are not crawlable from level 2 category pages. We have breadcrumbs also. Will Google be able to make the relationship of level 3, level 2 by breadcrumbs present on level 3?  

#### [0:35:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2100) |  Or should we make all important subcategory

pages crawlable for bots on the parent page? Currently, they're not ahref-ed, but the user can navigate. So I don't quite understand this question. But in general, if you want to make sure that we can crawl your whole website, then we need to be able to find links across that website, ideally from both directions.  

#### [0:35:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2130) |  So in particular, if you have different

category levels, where you can go down one category-- maybe it's like a submenu or different subcategory section on your website-- then when we really need to be able to find links so that we can go down that path as well. And it's not enough to just find links leading us back up, but we really need to be able to find the way down as well. And ideally, we'd also be able to find some way  

#### [0:36:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2160) |  across those different pages-- so between individual

items and maybe related items, or other items that are within that same category as well. So that's something where I really recommend that you make sure that this kind of structure is crawlable on your website; that it's kind of a reasonable structure; that it's not too deep that you just have lots and lots of categories, but also not too broad that you put everything on the same level.  

#### [0:36:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2190) |  So that's-- kind of, finding that balance

is sometimes a bit tricky. But making sure that we can crawl in, essentially, any starting point and reach the rest of your website from there through clicking on links, that's essentially what you should be aiming for. And there are a bunch of third-party crawlers that you can use to test your website in that regard. If you're unsure about this-- and it sounds like you have some understanding already of what it takes to make  

#### [0:37:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2220) |  a crawlable website-- then I would strongly

recommend using one of those crawlers to kind of start crawling from one URL and see, does it actually reach the other side of my website, and kind of find all of the pages within my website? Or does it get stuck somewhere? Maybe there are individual categories that don't have links to the next parts, where you're using some kind of other, maybe, JavaScript-based navigation that doesn't use links. So that's kind of the direction I would head there.  

#### [0:37:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2250) |  Lately I noticed new pages on my

website are not being indexed. And there are no errors related to crawling or other things. The content is unique. It's been around for three weeks since a new page is indexed. What should I do? Is this normal? I have a new website. In the past, pages were indexed relatively quickly. But the process of indexing is getting slower and slower. So we don't promise to index all pages on the web.  

#### [0:38:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2280) |  That's kind of the first thing there.

It's not a guarantee that, just because you create a page, that Google will go off and crawl and index that page, even if you use the inspect URL tool and submit it to indexing. It's possible that, especially with a newer website-- if there's a lot of content suddenly on a new website-- that our systems might be a bit cautious and say, like, is this really something we should be spending a lot of resources on to crawl and index all of these pages  

#### [0:38:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2310) |  here on this website that we don't

know about yet? Or should we be a little bit more cautious there and wait to see until we have better signals about that website, to understand why that website is so absolutely fantastic that we must absolutely go forth and crawl all of the content on that website? So in particular, if this is a new website, working more on quality rather than quantity is something I would recommend. And working to make sure that your website is well  

#### [0:39:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2340) |  embedded with the rest of the web

also makes sense. So that's something where maybe it makes sense to promote your website a little bit to kind of get things going on your side, kind of how you would do that with a normal business. If you open a business in a new city somewhere, you don't just open your business and hope that people find you and come to your store and buy something. But rather you do something to kind of get things started. And over time, if you do things right, if you have fantastic content, then you'll  

#### [0:39:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2370) |  have that kind of word-of-mouth effect that

people will recommend your content. And over time, that's something that we would pick up for Search as well. I'm looking at a website that's approximately 100,000 pages in size. Approximately two years ago, they made a bunch of fairly significant changes to website all at once. That caused the algorithms a lot of confusion and haven't been-- haven't really recovered since then. They saw a drop in rankings and visibility  

#### [0:40:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2400) |  across search results in general after changing

domain name, framework, platform, content, et cetera. OK, that's a lot of changes. One of the key pages seems to rank OK for some of the commercial terms, but they don't appear for all of the other variation. This page doesn't even appear for the term in the top 250 results. Less relevant pages, like blog posts from the original-- or from their website rank somewhere in for the term.  

#### [0:40:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2430) |  It seems that the page itself is

not a problem, as it ranks for other popular pages. This particular keyword is also used in the footer and makes up 98.9% of the anchor text pointing to that page over the other terms. Have you seen other cases like this, where a page is penalized for a particular keyword because of over-optimization? So I don't know. 98.9% sounds like a lot.  

#### [0:41:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2460) |  But depending on the website, especially if

you're talking about internal links, it's very common that individual pages have a lot of the same internal links. Depending on the CMS that you're using, it's possible, for instance, that you have a product, and that product has a name, and it's always linked by exactly that same name, and then all of the internal links to that product use that product name. And that's perfectly fine. So that's something where it's not necessarily automatically  

#### [0:41:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2490) |  the case that we would, kind of,

algorithmically ignore things just because they're used a lot in the anchor text. It's really hard to say specifically what is happening here. I think you sent me some examples, so I'll double-check those together with the team and see if there is something in particular that I can pull out. But it can certainly happen that individual pages rank well  

#### [0:42:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2520) |  for some popular queries but don't rank

that well for other popular queries. So that's not necessarily something where I'd say there's automatically something broken that needs to be fixed. I experience the following situation. I publish a new blog post. For the past two weeks, the URL was and still is listed under Discovered but not Indexed in the coverage report in Search Console. Inspecting the URL, Search Console says the URL is on Google with the correct self-referencing  

![](https://i.ytimg.com/vi/GXFmWVg_QfA/maxres3.jpg)



#### [0:42:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2550) |  canonical tag. Looking into search performance report,

I discovered that the URL is indexed twice with different UTM parameters from Facebook and Twitter. Is this something that Google will fix by itself because the correct canonical is set up? Or do I have to take any action? I'm using a domain property in Search Console. Should I also add the URL prefix property and use the legacy URL parameter tool?  

#### [0:43:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2580) |  So if you're using a lot of

these parameters on your website, and you want to simplify the tracking, then it's probably worthwhile to use the URL parameter handling tool for this, because with that you can more clearly specify which URLs you would like to have indexed. From a practical point of view, I don't think this page will be ranking differently in the search results. Because if we already have one version indexed, if we have the nonparameter version indexed as well,  

#### [0:43:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2610) |  we would see that as a duplicate

of these parameter versions, and we would essentially just fold those signals into that preferred version. So from a tracking point of view, it's a little bit trickier because you have these UTM parameters. But from a performance point of view, it should be essentially the same. So that's something where I wouldn't see this as a critical issue that you must fix immediately, but rather as something that just  

#### [0:44:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2640) |  makes reporting a lot harder than it

needs to be. So if there is a way that you can tell us that you want those parameter names excluded or ignored, then I would go ahead and do that. Otherwise, what will usually-- I mean, what should happen here is, over time, if we see those URLs with the parameters with the URL canonical pointing to the nonparameter version, we'll take that up as well. And we'll just kind of do that automatically.  

#### [0:44:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2670) |  So if you wanted to give it

more time, that's perfectly fine. That should just settle down. If you want to take things more into your own hands, then using the URL parameter handling tool is an option there. With the parameter handling tool, it's still not the case that this will kind of immediately fold everything over. But in particular with new URLs, as we discover them we'll be able to ignore that parameter, essentially from the start. In our old articles, there are photos  

#### [0:45:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2700) |  that host on HTTP servers. Google Chrome

says that we have mixed content. Is this really a problem for us? I read that Google Chrome automatically changed HTTP to HTTPS. And if the object is no longer available, then it would be ignored by the browser. So in practice, this is something where, when talking with the Chrome team, they obviously don't like to see this. And it is something that is shown in the browser bar  

#### [0:45:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2730) |  that you have mixed content on a

particular page. Kind of the security effect here is that, with mixed content, if the browser is requesting HTTP URLs, then you could be leaking information about that user's session over HTTP, which, theoretically, someone along the way could be picking up or kind of taking advantage of in other ways.  

#### [0:46:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2760) |  So in practice, I'd recommend to try

to clean this up. From a ranking point of view, it doesn't really have any effect. It's more a matter of, for your users it's worthwhile to clean this up. Sometimes there are ways that you can search and replace for things like old host names with HTTP and just replace it with the HTTPS version. So in particular, if your content is already accessible on HTTPS, then it might be an option  

#### [0:46:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2790) |  to do it like that, to pull

together some kind of an SQL query to automatically swap those out-- if that's something that is kind of on a database-based site. If these are all HTML pages that are individual files, then maybe there are different things that you'd need to do there. Let's see. I recently am trying to QC one of my clients' hreflang implementation, a huge e-commerce site with more  

#### [0:47:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2820) |  than 10 million pages. I found it

extremely hard to QC or examine certain pages, because they're using a sitemap hreflang, especially when I try to examine a specific page and I have to go back to the sitemaps to see if there are references. I already found a lot of errors in their hreflang sitemaps, too. Should I recommend them to use HTML-- or HTTP method instead? I heard that HTML hreflang will increase page weight.  

#### [0:47:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2850) |  But those codes are not render blocking,

nor do they have any download or send HTTP requests. They're just plain text, so it shouldn't affect page speed too much. What about HTTP hreflang? How would you deal with a huge e-commerce site's hreflang setup? So we support hreflang through the meta tags on the page, or through HTTP headers, or the sitemap file. And from our point of view, all three of those are equivalent.  

#### [0:48:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2880) |  So if there is a method that

makes it easier for you to maintain, or to kind of track, or implement hreflang, then I would try to use that one. If you're finding it really hard to maintain a particular implementation that you didn't add yourself, then maybe it makes sense to migrate that to an implementation that works better for you. With regards to the HTML version of the hreflang tag--  

#### [0:48:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2910) |  so if you're using it in the

header of a page-- you're correct. This is essentially just static text. It compresses really well. So for the most part, it doesn't change a lot, considering-- assuming this is an e-commerce page with a lot of content on the page, it doesn't affect the payload significantly, depending on, obviously, how many hreflang variations you have. But this kind of content compresses really well, so it shouldn't affect the payload too much.  

#### [0:49:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2940) |  This is something you can double-check, though.

So you can add this kind of hreflang annotations to some test pages, use static testing tools to determine the actual payload size and to determine the effect on theoretical page speed. When it comes to speed, I would recommend taking a look at the new Web Vitals, which we put together, I think, last week or fairly recently,  

#### [0:49:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=2970) |  which include some neat metrics that we

think are fairly relevant for the web. So it might make sense to double-check what those metrics say with these two variations. OK. Kind of running low on time. Maybe we just switch over to live questions if there's anything still left from your all's side.  

#### [0:50:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=3000) |  No more questions? Sure. TICIANO SGARBI: John,

can I? OK. Just double-clicking on the first question about meta description-- during April, we had the updated one meta description from one client adding-- during COVID-19 outbreak we are working, because it's just an online business. And it has nothing to do with health or anything.  

#### [0:50:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=3030) |  So just to emphasize we are working.

And we didn't see it on the Search. So we updated again. We thought maybe it's a red flag for Google exchanged COVID-19 for April. And still, it doesn't show on the Search. Now, with [INAUDIBLE] update, it's not showing still. Is there any something wrong with it? Or what would you say about it? JOHN MUELLER: It's hard to say. But, I mean, with the meta description,  

#### [0:51:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=3060) |  if you're putting it into a meta

description, on the one hand, there are limits to how much we would display from a meta description. So maybe that's-- TICIANO SGARBI: Inside the limit. We considered the limit. JOHN MUELLER: Yeah, OK. The other thing is, if it looks like something that is kind of spammy, where it's more a keyword stuffing related in a meta description, then that might be something where our systems try to determine a meta description to show ourselves.  

#### [0:51:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=3090) |  My guess is that's less the case

if you're adding kind of-- text-- additional textual information. And the other thing is, it's worthwhile to search in the way that users would search-- so not by checking with a site query, but rather by searching for your company name, or kind of the common queries that you would do. Because we do change the description that we show in the search results based on the query.  

#### [0:52:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=3120) |  And if it's a site query that

you're checking, it might be that we're not really sure what we should be showing in the description part. TICIANO SGARBI: Right, we'll work on that. Thanks. JOHN MUELLER: Now, I mean, the other thing is also that sometimes this just takes a while to be updated. But if you're talking about April, then it feels like it's more than a couple of weeks already. So that feels like something where we should have updated that.  

#### [0:52:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=3150) |  TICIANO SGARBI: Thanks. JOHN MUELLER: Sure. HAMMAD

SALEEM: Hi, John. Can you hear me? JOHN MUELLER: Yes. HAMMAD SALEEM: Yeah, this is Hammad. So something I just wanted to share and see if you have any idea or thoughts-- so we have a site where US doctors are answering patients' questions anonymously, just like Quora or Stack Overflow. So we have a million-- we have a 7 million long library. We recently did an infrastructure update where we had to change some of our URL structures.  

#### [0:53:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=3180) |  So we basically did a 301 redirect

for many of our pages, and we submitted a new sitemap. Since then, a majority of our pages have been stuck in Discovered, not Indexed, and pretty much like 90-plus percent of our pages. And it's also resulting in some traffic drop-- some significant traffic drop. So we're just trying to understand if there's something wrong that we did, or we should have  

#### [0:53:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=3210) |  done it in a different way. JOHN

MUELLER: My guess is it's unrelated. Because with a redirect, what you're really telling us is that we should pick a different canonical URL, which means if we haven't processed the redirect yet, we would keep the old URL in Search. If we have processed the redirect, we would use the new URL in Search. It wouldn't be the case that the URL would drop out of the Search results. So it's not that we would show less in Search.  

#### [0:54:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=3240) |  It's really just, do we show this

URL, or do we show that URL. If you're seeing a traffic drop overall, then that feels like something that would be unrelated to this kind of site move. HAMMAD SALEEM: Got it. So the old URLs that are not in the new sitemap are not automatically being removed from the index? JOHN MUELLER: Exactly, yeah. Yeah. So that sounds to me like it's more a matter of, maybe, our quality and algorithms  

#### [0:54:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=3270) |  just not wanting to index as much

from this website as before. It's not something where there's a technical issue with that redirect. HAMMAD SALEEM: Got it. OK. Thanks. JOHN MUELLER: Sure. All right. I think there's someone else that wanted to ask a question in the chat. NICHOLAS HARVEY: Hey, John. This is my first time joining the chat. And I totally feel like the new kid that walked into a very, very advanced class. And I know my question is going to be really stupid,  

#### [0:55:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=3300) |  so please just bear with me. I

don't know SEO. I know the Webmaster guidelines. I've been reading them. But if you had, let's say, for example, a website that sold-- I don't know, let's say baseball hats. And they sold baseball hats for, let's just say, every single team, and there was different colors. This is all hypothetical. What on earth do you put in the meta description besides, like,  

#### [0:55:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=3330) |  "Yankees blue hat," "Yankees red hat"? You

know what I mean? JOHN MUELLER: The meta description is kind of the description of the page. So if it's essentially like a Yankees blue hat, then you might use something to describe that in a more, I don't know, readable way. Which could be, like, buy your Yankees blue hat on our website. Or add something like free shipping, or whatever, kind of, additional information that you might tell someone  

#### [0:56:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=3360) |  if you were to meet them on

the street, and they were like, oh I'd like to buy a hat. Then it's like, what would you say, tell to them? That level of information. So the different things across those different products, that would probably be like the product name or some attribute from the product. But the rest can definitely be the same thing. It can be like, buy your Yankee blue hat here, or buy your Yankee black hat here, depending on what the individual products are.  

#### [0:56:30](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=3390) |  NICHOLAS HARVEY: And you're talking about on

the meta description of the individual products [INAUDIBLE] shop. I don't think that makes a difference, but-- JOHN MUELLER: Yeah. NICHOLAS HARVEY: Awesome. Thank you. Thanks for taking the time. JOHN MUELLER: Sure. All right. I need to jump off to another meeting. But it's been great having you all here. We have the next one lined up, I think, for Friday if you all want to join. Depending on time zone, maybe that works better or less well. And I'll set up the next meetings as well in two weeks  

#### [0:57:00](https://www.youtube.com/watch?v=GXFmWVg_QfA&t=3420) |  again as well. All right. Thanks a

lot for dropping by, and hope to see you all again in one of the next Hangouts. Bye, everyone. MIHAI APERGHIS: Bye, John. MARIA AMELIE: Bye-bye  