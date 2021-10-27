[![English Google Webmaster Central office-hours hangout from August 9, 2019](https://i.ytimg.com/vi/zm7mn2sGuyw/hqdefault.jpg)](https://www.youtube.com/watch?v=zm7mn2sGuyw)

## English Google Webmaster Central office-hours hangout from August 9, 2019

This is a recording of the Google Webmaster Central office-hours hangout from August 9, 2019. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Watch out for new sessions, and add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



Feel free to join us - we welcome webmasters of all levels!



Subscribe to Google Search Central → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=0) |  JOHN MUELLER: All right. Welcome, everyone, to

today's Webmaster Central Office Hours Hangouts. My name is John Mueller. I am a webmaster trends analyst at Google here in Switzerland. And part of what we do are these Office Hour Hangouts, where webmasters and publishers can join in and ask questions around Web Search and their website. As always, looks like a bunch of questions were submitted. But if any of you want to get started with the first question, you're welcome to jump in now.  

#### [0:00:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=30) |  AUDIENCE: I would like to ask a

question. JOHN MUELLER: All right. AUDIENCE: Yeah. It is about the geoblocking, because we have a web page which has a lot of media and programs which we are only allowed to show in our country. So we have geoblock, so if people come outside, they're actually redirected to a page where it says that they can't watch this program.  

#### [0:01:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=60) |  And also, if you enter the front

page, you can only see content which, yeah, you're able to watch. So my question is whether we can whitelist Google crawlers, or that is a no-go? Or how we can fix that. JOHN MUELLER: So in general, you should treat Googlebot the same as any other user from the same region. So since we mostly crawl from the US,  

#### [0:01:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=90) |  you would need to treat Googlebot like

another user from the US. That's a bit, I don't know, problematic in some cases, because the other way around would be no problem. If you have a website in the US and you say, I want to block users in Europe, then that would be no problem. But if you're a website in Europe and you want to block users in the US, then you would be blocking Googlebot as well. So that's not really something that you  

#### [0:02:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=120) |  can get around there, or at least

according to our guidelines. What you can do for video content, specifically, is specify which countries the content is available for. So what you could do, theoretically, is make it so that the HTML pages are accessible by users everywhere and that the videos only play in the appropriate countries. And the video files, those are things  

#### [0:02:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=150) |  that you can show to Googlebot, even

though users in the US would not be able to see it, because you can specify the limitations with the markup. AUDIENCE: Yeah. OK. But it is a no-go to actually whitelist-- JOHN MUELLER: Yeah. AUDIENCE: Yeah. OK, cool. I wanted to make sure, because that was the easiest workaround. But yeah. JOHN MUELLER: Yeah. I think from a web spam point of view, the web spam team would probably not take action on that.  

#### [0:03:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=180) |  But according to our guidelines, that would

not be appropriate, yeah. AUDIENCE: Yeah. OK, thank you. JOHN MUELLER: Sure. All right. Any other questions before we jump into the submitted ones? AUDIENCE: Hey, John. I have a question. The thing is, we have a main domain redirect. So will it affect my data in Search Console? JOHN MUELLER: How do you mean main domain redirect?  

#### [0:03:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=210) |  AUDIENCE: Say, example.com/, it is redirected to

the example.com/en. So should I have to change my main domain in the Search Console? JOHN MUELLER: Oh, no. That's perfectly fine. If you're redirecting to a lower level page on your domain and you can keep the whole domain in Search Console, you can, if you want, just verify the subdomain or subdirectory, but you don't need to.  

#### [0:04:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=240) |  AUDIENCE: OK. So if verifying two domains,

will my data will be available in both the domains? JOHN MUELLER: Yes. AUDIENCE: OK. Thanks. JOHN MUELLER: All right. Let's jump into some of the submitted questions. As always, if-- AUDIENCE: Sorry, John, hello? Hello? JOHN MUELLER: Yeah, OK. One more before we go. AUDIENCE: OK, thanks. So I asked the question on the webmasters help community.  

#### [0:04:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=270) |  The question is about the Google Search

Console. In the old version of Google Search Console, we had a great way to discover blocked resources. Now, as I understand, in the new one we have the URL inspection tool. Help center suggests use these tool if you want to discover blocked resources. So when I use test my site tool, I see blocked resources. But I can't find the same data in URL inspection  

#### [0:05:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=300) |  tool in Search Console. Well, I wonder

why. And also, wasn't it better to provide information about blocked resources of all site, not on the single URL basis? Thank you. JOHN MUELLER: Yeah, that's a good request. So I think we dropped that feature because we noticed that most sites were no longer running into problems with that.  

#### [0:05:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=330) |  Because with the shift to mobile friendliness,

that was a big problem. If a resource was blocked from crawling with robots.txt, then sometimes we can't tell if a page is mobile friendly. But that has improved significantly across the web, so we decided to drop that feature. But it's good to hear feedback that it was actually useful. So I'll definitely pass that on to the team.  

#### [0:06:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=360) |  AUDIENCE: OK. JOHN MUELLER: Yeah, I don't

have any workaround at the moment to get a broader list of all of the blocked resources. AUDIENCE: OK, thanks. JOHN MUELLER: Sure. AUDIENCE: Hello, John. How are you? JOHN MUELLER: Hi. AUDIENCE: Yeah, John, I have a question regarding the Webmaster Office Hours which was streamed live on November 2018. JOHN MUELLER: Oh, gosh. AUDIENCE: Yeah. It was weird also.  

#### [0:06:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=390) |  Yeah, so in that session you mentioned

that the discovered but not index thing, which will not happen because the pages are duplicate. Or maybe the pages have the same thing, but they are having different content. But once the Google will crawl a thousand pages, then Google will get to know, right now this website has the same design, same way of content showing on the website.  

#### [0:07:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=420) |  So, I mean, in this way, you

mentioned this. If we're using the script-based title and meta description automation-- if we are putting the title and meta description using the scripts-- we are using the-- for example, right now we have two large pages. 200,000 pages right now we have on our website. And we're using script automation by putting the Google metadata, alt text and everything-- metadata, everything. We're using this script-based automation.  

#### [0:07:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=450) |  So you mentioned that it is not

a good practice. And my question is, in the Magento, when people are uploading Excel sheets, so that is also a kind of automation, because they're updating their metadata by using Excel. So how Google is reacting towards the Magento websites, and how Google is reacting to the custom-based websites which  

#### [0:08:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=480) |  are using the script-based automation? JOHN MUELLER:

OK. I think those are two quite different things. So I think what you're referring to is the Google Tag-- using Google Tag Manager to edit titles and-- AUDIENCE: No, no. We're actually not using Google Tag Manager. We're just using GTM only for the schema-based variable creation thing. So we are just using the script-based automation for our metadata.  

#### [0:08:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=510) |  In this way, we are doing is

we are just putting-- in the Excel we do concatenation, right? So the concatenation process, we are just using the script for that on our website. So every time when we upload, for example, 50,000 more pages for our website, so we have a template. We upload that template again. Then every page has its own meta tag, alt tag, and everything. So because right now we have-- you know, products we have different. We have different content.  

#### [0:09:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=540) |  We have different fact pages on our

different pages. But still, our indexing is not improving. I mean, my main question is, is it because of the design? Is it because of the automation? Is it because of the script? I mean, what could be the reason? Because right now we are doing everything-- I mean, at our end we are trying to keep unique content on our website, we are doing everything, I mean, a best way, but still we are facing this problem in the indexing way.  

#### [0:09:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=570) |  So we have like 28,000 pages indexed

only now. So that's why. Yeah. JOHN MUELLER: OK. So I think there are a few aspects that might be confusing and being mixed up. So in general, when you say you're using a script-based approach there, it sounds like you have these scripts running on the server. It's not JavaScript. AUDIENCE: It's not on the server. Yeah. It's not on the server. Sorry to interrupt you, but it's not on the server.  

#### [0:10:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=600) |  But once we-- before uploading the website

live, what we do is we have the developer version of our website. What we do is we upload our data on the developer version. And then the developer, what they do is they upload that version live, live server. So we are not actually creating the script-based thing on live website. So we are doing on our-- you know, the full version, you can say the first version, of the website. So yeah. JOHN MUELLER: OK.  

#### [0:10:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=630) |  So I think in general you wouldn't

need to worry about the script part, because it sounds like-- I don't remember that particular Hangout. So it's been quite awhile. But one of the things we have talked about is using JavaScript to update titles and descriptions. And that would be something very different from what you're doing. So it sounds like you're uploading things, and then you have a script that processes them. And then you upload that to the server. And that results in normal HTML pages  

#### [0:11:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=660) |  being uploaded to your website, which we

can process completely normally. So that's very different from using JavaScript that runs in a browser to update the titles and descriptions. So from that point of view, I think you're fine. I think the general problem that you're seeing is just that you have a lot of pages and only a part of them are being indexed. AUDIENCE: Yeah. JOHN MUELLER: And that's something that can be quite normal.  

#### [0:11:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=690) |  It can also be a sign that

maybe there's some technical issues there. What I would recommend doing is posting that maybe in the webmaster help forum and having some other people double-check your site and just kind of give you some general advice. It could be that, for example, that we're just not convinced about the quality of the website. It could be that there is a technical issue that's blocking us from crawling these pages completely.  

#### [0:12:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=720) |  But it's very hard to say just

off the hand. I think, in general, the approach that you have with uploading your content with an Excel file, and your server generates pages out of that, that's perfectly legitimate. That's something that a lot of sites do. AUDIENCE: Yeah. Because, I mean, when I took the Magento processing, when we check our websites-- so we're using PHP. Magento is also on PHP. So Magento is right now moved to React JS in 2.3 version.  

#### [0:12:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=750) |  So they have some different things. But

right now I was just confused. Like, if we are doing the automation process in Magento, then, I mean, how could it harm to our website in the custom way? So that is my concern. JOHN MUELLER: No. I think from the automation that you're doing with uploading the information with a sheet, that's perfectly fine. That's not an issue. And Magento is a fairly big platform in that a lot of sites use it. So if there were a general problem with Magento,  

#### [0:13:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=780) |  I think that would be very visible,

and it would be something that they would fix very quickly. AUDIENCE: Yeah, they would. Yeah. JOHN MUELLER: Yeah. So I would just try to get advice from other people, specifically for your website, and see if there's something small that maybe you can change or maybe you have to kind of find other approaches to make the website work better. AUDIENCE: OK, sure. I'll get it done on Google Webmaster Forum. Thank you. JOHN MUELLER: Cool. AUDIENCE: Yeah, thank you.  

#### [0:13:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=810) |  AUDIENCE: Hi, John. JOHN MUELLER: All right.

AUDIENCE: Do you mind if I ask a question? JOHN MUELLER: Sure, go for it. AUDIENCE: So I'm working with a site at the moment. They have actually posted this on the forum. So what's happening is, we've got a bunch of pages, and they're indexed. They then get-- their noindex gets removed, gets introduced to the sitemap. They then throw a load of errors in Search Console that they're in the sitemap and they're indexed.  

#### [0:14:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=840) |  If you hit the Revalidate button, it

just says-- it checks a few and then says that they're indexed still. It seems to me that the Revalidate button doesn't work or-- because we can go through them, and there's definitely no x-robots header or tag in the head of the page. But it still just keeps throwing this error. We wondered if-- JOHN MUELLER: So the pages are not noindexed, or they are?  

#### [0:14:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=870) |  AUDIENCE: They previously weren't indexed. It's a

user-generated site. So the noindex gets removed when the content reaches a certain threshold, i.e., it's had enough engagement. They then get put in the sitemap. And at that point, the error in Search Console's saying that then they're noindexed but in the XML sitemap. So then-- there's like 2,000 of them at the moment-- but you can click Revalidate button, and it just says, no, they're still noindexed,  

#### [0:15:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=900) |  even though they're definitely not. JOHN MUELLER:

OK. I suspect what's happening there is that Search Console is a little bit faster than the rest of indexing, which is surprising sometimes. But what's probably happening is we're seeing that these pages are noindexed, and Search Console recognizes that they're in the sitemap file, because that's where they are now. And then Search Console will throw an error.  

#### [0:15:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=930) |  So basically, we're taking the old status

of the noindex pages and seeing that they're now on a sitemap file and thinking, oh, you added noindex pages to the sitemap file, and we haven't actually re-processed the individual pages since you've added to them to the sitemap. AUDIENCE: Right. Does the Revalidate button not actually go off and re-crawl all of these pages? JOHN MUELLER: Revalidate. Is that in the index status, or is that the sitemap?  

#### [0:16:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=960) |  AUDIENCE: No. It's like a-- so you

can go into Search Console. You pick the section of errors that you've got, in this case in sitemap and noindex. And there's just a button that says Revalidate. And from what I understood, it goes off and rechecks all these pages, but, yeah, it doesn't seem to do that from what I can tell. JOHN MUELLER: It should. It should. The idea there is that it checks a sample of the pages first, I think maybe like 5 or 10 pages, and double-checks  

#### [0:16:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=990) |  that the error is resolved. And then

it'll trigger the re-processing of the rest of the pages there. I'm not 100% certain how it would handle the situation where you have the sitemap file in between, if it just revalidates that these URLs are in the sitemap file or not, or it actually re-crawls the URLs themselves. But I can double-check with the team on that, yeah.  

#### [0:17:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1020) |  AUDIENCE: All right, cool. Thank you. JOHN

MUELLER: Yeah. Cool. All right. Let me run through some of the questions that were submitted, because people spent a lot of time pushing them in there. So we should get through some of those. "What could be a reason that a huge listing, very popular site not being switched to mobile-first indexing?" Essentially, we have multiple classifiers that try to understand when a site is  

#### [0:17:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1050) |  ready for mobile-first indexing. And usually, what

we've seen with larger sites is not so much that we'd say, this is an important site, we'll switch it over quickly, but rather, we'll switch it over when we think it's ready. And with larger sites, what often happens is there are multiple sections of the site that use slightly different setups. So that's something that happens quite a bit, where you have, maybe, multiple CMSes involved or multiple back ends or front ends involved within the same domain.  

#### [0:18:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1080) |  And it can happen that maybe some

of those systems are not ready for mobile-first indexing, according to our classifiers, and others are. And in a case like that, we'll hold off and wait a little bit to kind of make sure that everything is really ready. Also, with really large sites, what we've started doing is shifting a handful of URLs over to mobile-first indexing, maybe 1%, maybe a few percent, and seeing how  

![](https://i.ytimg.com/vi/zm7mn2sGuyw/hq1.jpg)



#### [0:18:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1110) |  the site generally performs. Are they seeing

that indexing is working well with mobile-first indexing for that site? And if so, we'll ramp that up slightly. So all of those things are aspects that you might be seeing there with mobile-first indexing. I wouldn't see it as a sign that anything is broken or wrong if your site has not switched to mobile-first indexing yet. It might just be that our classifiers are still a bit cautious and try to stay on the safe side.  

#### [0:19:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1140) |  "The meta tags keywords and news keywords

aren't used anymore, I believe. However, I see a lot of publishers are still using it. Is it just redundant? Should we use them, essentially?" We don't use them at all for Search. So you don't need to use them. But at the same time, they also don't cause any problems. I've used the keywords meta tags for my own sites,  

#### [0:19:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1170) |  just as a way to help me

kind of focus on a specific topic so that I know what I want to write about on a specific page. And that's more for myself and not something that search engines would really care about. So maybe others are doing that, too. But again, this is something that essentially is not something that you'd need to fix or change. It's just, we ignore them.  

#### [0:20:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1200) |  If you want to provide them, if

your systems provide them automatically, no problem. "I recently uncovered a big canonicalization issue on a large-scale site, where many pages were incorrectly being canonicalized to other pages with non-equivalent content. Google was simply ignoring the rel canonical, which makes sense. Now I'm surfacing more examples across the site of Google ignoring rel canonical, also where it makes sense.  

#### [0:20:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1230) |  This got me wondering that if Google

sees the wrong canonical tags on a site often, if it then starts to not trust the user-selected canonical URLs across the whole site. And if it does lose trust, then maybe Google systems think it's better to select canonical URLs across the site on its own versus using the canonical tag. Do you know if that's the case?" So, it's theoretically possible that we ignore the canonical tag across the whole site.  

#### [0:21:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1260) |  But I think that would be extremely

rare, because that would generally be something that our engineers would have to do pretty much manually. What usually happens is, with the canonical-- rel canonical tag, is that we do this on a per-page basis. And on a per-page basis, we use a number of factors that come into canonicalization, including the rel canonical, including information about the URL, about the content, about other URLs that  

#### [0:21:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1290) |  have the same content, and we try

to pick a canonical based on all of those factors. And the rel canonical alone isn't enough of a signal for us to say, we will always be able to trust it. If we see other signals that come into play, then we might ignore the rel canonical on a page like this. And that's something that happens on a per-page basis, so not something where, at least as far as I know, we would do this on a per-site basis and say,  

#### [0:22:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1320) |  well, the canonical links on this website

overall are wrong. Therefore, we'll ignore them completely. It's more that on a per-page basis we'll try to pick the canonical URLs that we think make sense. I have a lot of excluded pages in my Search Console. My valid pages are about 1/10 the number of the excluded pages. And it's a big site with 170,000 valid pages. I'm wondering if excluded pages count towards our crawl budget.  

#### [0:22:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1350) |  Once Google decides a page should be

excluded from the index, does it still crawl the page periodically? Should I be concerned that the high ratio of valid to excluded pages is eating up our crawl budget? That's a good question and a complicated one, I think, in the sense that, yes, the excluded pages are counted in the crawl budget in the sense that when we try to call them  

#### [0:23:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1380) |  and we end up not including them

in the index, then we've tried to crawl them. And they count as an attempted crawl and essentially count in that bucket of crawl budget. However, what usually happens is, when we exclude a page for any particular reason-- that could be because maybe it has a noindex tag on it; it could be maybe we have a duplicate URL; we've picked a different canonical--  

#### [0:23:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1410) |  then what generally happens there is we

crawl these pages a lot less frequently. So while you might have a lot of pages that are excluded, and we might be re-crawling them from time to time, we'll be re-crawling them a lot less frequently compared to the URLs that we think are important for your website. So on the one hand, they do count in the crawl budget. On the other hand, the effect within your site's crawl budget is generally minimal.  

#### [0:24:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1440) |  Also, when we have a number of

URLs that we want to crawl for a website-- and we also include a number of maybe excluded URLs or URLs that we're not sure about-- and we run into a situation where we're limited by your site with regards to crawl budget, then we will try to prioritize the URLs that we think are more important over the ones that are less important. So let's say in an extreme case, we can crawl a thousand URLs a day from your website, and we know about 900 URLs that are good  

#### [0:24:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1470) |  and about maybe 10,000 URLs that are

from this excluded bucket. We'll try to get those 900 good URLs in first. And then the rest that we kind of have available there we'll pick from the excluded bucket, just to make sure that we're not missing anything, that pages from the excluded bucket did not end up suddenly becoming includable and that maybe a noindex is gone now, and we can pick that up again.  

#### [0:25:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1500) |  So, yes, they're included in the crawl

budget. But generally, it's not something that you need to worry about there. OK. Two really big questions. Let's see. "I am working for a travel agency. We have our main platform and some that revolve around the main one. The revolving ones are all linked to the main one, but they're not linked between each other and all have a different domain. The revolving one spoke about the same thing  

#### [0:25:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1530) |  but ranks with different keywords and content.

So the subjects in these are identical. It's all about travel. The content is different, but there can be similarities. My websites are all divided into continents, and we're speaking about a lot of countries and cities in those. So it can look like the same. We're talking about the same cities and locations in each of those but worded differently, like if it was a different opinion on an identical site."  

#### [0:26:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1560) |  Let's see. So maybe before I get

into the questions, this sounds a lot like something that you might want to watch out for, in that you're creating a ton of content that can look a lot like doorway pages, in that you're just kind of switching different keywords across all of these pages here. So that's something where I would  

#### [0:26:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1590) |  tend to be pretty cautious about just

running a system like this with so many different domains and sites that essentially cover the same content. A lot of times what you'll find is that if you have fewer pages or fewer sites, you can perform a lot better in Search, because we can see that these are really important pages, versus you're kind of diluting things across a lot of pages. So let's look at the questions. "My issue is that I'm using a premade theme,  

#### [0:27:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1620) |  and I wanted to know if those

would have an impact on the ranking of my websites." Not necessarily. So whether or not you use a premade theme or a custom theme, that's essentially up to you. From a user's point of view, that might be something that users recognize, and maybe that's something where users will say, well, I don't know if I can trust this website if they're just using a theme that kind of came with WordPress by default. But that's essentially up to you.  

#### [0:27:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1650) |  Let's see. The second question-- this is

also about having multiple websites. "Would applying a nofollow rule suffice?" So I think it's basically between the different websites. "Or should I do some kind of Jedi mind trick like transforming those links into spans and using JavaScript to redirect to my domain?" So I think in general, the links between these sites and pages  

#### [0:28:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1680) |  is less of a problem than just

the plain existence of so many variations. So I wouldn't worry about trying to hide any of the links between those sites. I would instead try to find ways to combine a lot of these sites and pages so that you don't have to have that many separate ones. Usually, having fewer sites means you can make those a lot stronger. You can concentrate your energy on those sites.  

#### [0:28:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1710) |  A question about JavaScript. "If I can

see my text in Google's mobile-friendly text, can I ensure that Google doesn't have a problem with reading and indexing my content and my pages?" For the most part, yes, that's correct. There can be subtle issues with regards to JavaScript. But in general, the mobile-friendly test is something that uses the new Chromium setup  

#### [0:29:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1740) |  that we use for Googlebot. So if

it works in the mobile-friendly test, it should work for indexing as well. One of the things to watch out for here is that the mobile-friendly test, as far as I know, doesn't follow the robots.txt rule. So that's something where you might want to use the inspect URL tool in Search Console to make sure that actually your JavaScript files and your server responses and all of that  

#### [0:29:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1770) |  are working well from that point of

view. "I changed normal images to Instagram embeds on one of my articles and saw a decrease in rankings, clicks, et cetera, for Image Search. It was a 43% decrease in Image Search clicks overnight on a very reliable article. Can you talk a bit about the difference between normal images versus Instagram embeds from Google's perspective?"  

#### [0:30:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1800) |  So I thought that was an interesting

question. And I created a test page to see how this actually works, because it really depends a lot on how Instagram sets this up, because you're essentially just taking code from Instagram and putting it on your website. And depending on how they set up that code on there, it can have an effect on your website. So in general, what kind of the bigger picture change is,  

#### [0:30:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1830) |  you're going from a situation where the

images are embedded in the HTML directly on your website, where they're really easy for us to discover and really easy for us to crawl and index, to a situation where we have to process some JavaScript and do some fancy processing to get to those images. So that means it's a lot more work for us to actually get to those images. We can recognize those images, and we can crawl those images. Using the mobile-friendly test shows those embeds as well.  

#### [0:31:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1860) |  So it kind of looks OK. However,

what I notice is, specifically with the way that Instagram embeds these images-- they use an iframe to embed kind of the post from Instagram, which kind of makes sense. But with an iframe, you're basically adding another layer of indirection between your page and the images. So it goes from your page to this iframe,  

#### [0:31:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1890) |  and then from the iframe content to

your images. So that makes it a little bit harder for us to pick up those images. But what really kind of breaks the story for us is that, within the content that is embedded from Instagram within the iframe, they use a no-image-index robots meta tag. And this meta tag tells us that you don't want those images indexed together with the page itself.  

#### [0:32:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1920) |  So if we just look at that

iframe content, we can recognize that there is an image there. We can crawl that image. But with that meta tag, you're basically telling us that you don't want this image indexed together with that landing page. So essentially, by switching from a direct embed of an image on your website to using Instagram embeds,  

#### [0:32:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1950) |  you're kind of telling us that you

don't want these images indexed for your website. And with that, I think it would be normal to see a significant drop in your search traffic to those pages, because you're essentially telling us you don't want these pages to be indexed like that. So from my point of view, it essentially kind of comes back to you and kind of your preferences there. I can understand that sometimes it  

#### [0:33:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=1980) |  makes sense to embed Instagram posts directly,

or social media posts in general, because you get a lot of added value from just kind of the whole everything around that, with regards to comments, and maybe the likes and the shares, and all of that information that is available within the embed. On the other hand it makes it a lot harder for us to actually index those images. So that's something that you almost need to balance on your side. Do you need to have all of this extra detail around the images?  

#### [0:33:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2010) |  Or do you really need to make

sure that those images are well indexed for your website? And depending on the website, you might have preferences one way or the other. If you want to have both kind of the Instagram embed and to have your page ranking for those images, then that will probably be tricky and might involve weird situations like having to put it in there twice.  

#### [0:34:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2040) |  "Since a few months, we're seeing a

new strategy where big news websites lease a whole subfolder or subdomain to a media company." I think we've looked at this a few times here as well. So kind of the question is, like, this is spammy and I don't like it, and does the search team know about this?  

#### [0:34:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2070) |  We do talk about this with the

search quality team from time to time. And we do try to find examples where we think that things are kind of worse for users and maybe also a situation where we think that things are actually pretty good for users. In general, I think these kind of changes happen from time to time, in that people will find something that works really well for them. And it happens to work really well in Search, and then suddenly everyone does it. And then at some point, it becomes so,  

#### [0:35:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2100) |  I don't know, problematic in the sense

that it results in a lot more low-quality content, and then the websites themselves get seen as low-quality content. And things kind of settle down into a more reasonable place. I haven't looked at this situation for a while now. But I feel it's something where things will be settling down into a more reasonable place. And in general, when it comes to changes like these,  

#### [0:35:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2130) |  we try to avoid going down the

route of manually adjusting the rankings of individual websites because of these issues. Specifically, when it comes to topics where it's more about quality rather than pure spam, then we wouldn't have the web spam team go in there and say, we need to manually adjust the ranking of these websites. But rather, what we would try to do is algorithmically try to recognize the situation overall  

#### [0:36:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2160) |  and kind of work out where the

high-quality, the useful content is within setups like this, and to promote that appropriately in the search results, and to find places where our algorithms can automatically recognize that this is not so useful for users overall, and to make those less visible in the search results. And sometimes this takes a little bit of time.  

#### [0:36:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2190) |  "If a site has a fairly large

volume of internal links which generate 301 redirects to reach the final destination pages, will this impact crawl budget? I see Google regularly visiting the 301 redirect URLs, and I am assuming that placing the correct links to the destination pages would be better utilization of crawler resources and would speed up page load time significantly for users. This is a fairly large e-commerce site, where these kind of links are regularly and repeatedly  

#### [0:37:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2220) |  available 10,000-plus times." In general, if we

recognize that a page just bounces from one URL to another, in the sense that we find a link to one URL and it redirects directly to the next one, then that's something that wouldn't negatively affect the crawl budget in the sense that, like, we can process it right away.  

![](https://i.ytimg.com/vi/zm7mn2sGuyw/hq2.jpg)



#### [0:37:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2250) |  It can mean that we spend a

little bit more time on a per-URL basis to crawl this website. And that can in turn still affect the crawl budget. So in particular, if we recognize that we need, I don't know, so many seconds to actually get to the content, then we'll try to limit the number of simultaneous requests to that website just to avoid causing any issues. And if each request takes longer, then that in turn  

#### [0:38:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2280) |  does mean that we're not able to

crawl that much. So theoretically, that could play a role. In practice, it seems pretty rare. And especially if you're talking about something like 10,000 pages, then for most websites, being able to crawl 10,000 pages-- especially if it's a fairly large e-commerce site-- that's not something that would cause any issues there. So I think you'd probably see a small incremental change  

#### [0:38:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2310) |  with regards to our crawling if you

were to kind of link directly to the target pages. But you probably wouldn't see anything significant when you're talking about 10,000 pages. If you're talking about all pages within the e-commerce site-- so maybe you're like always linking to a tagged URL and from that tagged URL you're redirecting back to a clean URL, and you have that millions of times across the whole website-- then that is something where I'd say you probably would see a significant change  

#### [0:39:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2340) |  in how much content we can crawl

from that website by fixing that setup. But if you're talking about 10,000 pages within an e-commerce site that has millions of pages, then that seems fairly insignificant overall. "To increase the EAT of a medical page, should I use article schema for example, or for example, web page or medical web page as the latter two  

#### [0:39:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2370) |  have as an option for reviewed-by property?

Or maybe Google can find that the article was reviewed from the context if I provide such details and schema? Property reviewed-by is not necessary." I think that's kind of up to you. We do try to recognize kind of these additional details about information about the author, information  

#### [0:40:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2400) |  about the reviewers, about the website overall

through a number of ways, partially through the content directly. So kind of similar to how users would see it. If they go to the page and they see kind of information about who has reviewed this content or who has provided it, that's really useful. If it's just hidden away in structured data, then that's not very useful for users, because users tend not to use View Source when looking at a page to determine whether or not  

#### [0:40:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2430) |  they should trust it. So I would

try to find an approach that works well primarily for users and focus on that. With regards to article or web page, that's something where I'm not exactly sure what the difference there would be. It seems that there-- from a semantic point of view, they're slightly different. There is a bit of an overlap there, though.  

#### [0:41:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2460) |  So depending on the page that you

have, I would try to pick the appropriate one there. So if you have an article, then maybe the article schema is the right one. If you have something more like a tool or lookup or a forum or something, then maybe article is not the right approach there. "Google has a penchant for adding branding to title tags in search results where there are none written on the site.  

#### [0:41:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2490) |  For example, HubSpot has a guide to

cryptocurrency without the brand name in the title, and Google added HubSpot to the headline in the search results. Is this purely aesthetic? Or is there possibly more to it, for example, a signal that Google likes to see sites add branding to titles themselves?" So for the most part, we do this automatically because we find that it helps users to better understand  

#### [0:42:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2520) |  the context of the individual pages that

we show in the search results. And a lot of times, I think we do a fairly good job of that. Sometimes we pick the wrong ones. And for those that we pick wrong, it's useful to get feedback on that. So if you see something weird happening with the title tag, then feel free to let us know about that. But it's not something where I would say you have any kind of a ranking advantage  

#### [0:42:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2550) |  if you add a site title to

your title tags or any other kind of advantage there. It's essentially purely something that we end up doing for users. Sometimes we also rewrite the titles. Sometimes we have to shorten them if they're on a mobile device, for example. The same thing happens with the descriptions. Sometimes we adjust them subtly based on the query that was made. So all of these things are aspects  

#### [0:43:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2580) |  that we try to do to make

it easier for users to understand how your page is relevant for them in their specific situation. And it's not a sign that you have to copy that and do the same thing on your pages directly. "I have a question about Google Analytics. For one of my clients under GA organic keywords, I see something like NP dash or NP dash user/register.  

#### [0:43:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2610) |  What could possibly be that I'm doing

wrong in terms of tracking?" I don't know anything about Google Analytics, so I can't really help you with that. My guess is maybe you're providing URLs to track on your own. But I really don't know how those things end up in Google Analytics.  

#### [0:44:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2640) |  "We have a website with 50 million

monthly page views. And when people search for our brand directly, they don't see sitelinks nor the sitelinks search box below our home page result. Search Console detects the sitelinks search box markup correctly, but it just won't show up in the search results. Does this mean that Google considers our site to be low quality? 60% of our traffic comes from organic search, and the average session time is over four minutes."  

#### [0:44:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2670) |  So, no, it doesn't mean that we

think your website is low quality. Just first of all, that's something that I really wouldn't worry about specifically with regards to the sitelinks or the sitelinks search box. We show sitelinks and the sitelinks search box when we think that it makes sense for a site and for the queries that are going to the site. And it's not necessarily something that is tied to the quality of the website.  

#### [0:45:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2700) |  Obviously, the website could still be low

quality. So it's not that I'm saying your website is high quality. But just because we're not showing sitelinks or sitelinks search box is not a sign that we think the website is low quality. Specifically to the markup of the sitelinks search box, that's something where, if we were to show a search box below the listing,  

#### [0:45:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2730) |  then we would use the markup to

show the version that you prefer to have shown. But it's not the case that just because you have the markup we would be more likely to show that box. So it's still-- kind of as a first step, if we were to show a sitelinks search box, then we would use a markup. It's not that, if you have the markup then we would show the sitelinks search box. "My question is regarding multiple countries targeting  

#### [0:46:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2760) |  for multiple products. If I have product

one which is in demand in the US and product two which is in demand in Canada, and there are other products for both countries--" oh, this is complicated. "If I target product one, product three, and product four in the US, will make it complex for Google to understand in which country I'm targeting my entire website?"  

#### [0:46:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2790) |  Usually, this is not an issue. So

in general, when it comes to geotargeting you can specify that in multiple ways, but it needs to be a clear section of the website. So for example, you could say your whole site is targeting one specific country. Or you can say, I have multiple subdomains or multiple subdirectories, and if you list those separately in Search Console, you can specify the geotargeting for those parts individually.  

#### [0:47:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2820) |  What you can't do is specify geotargeting

for individual pages within your website. So kind of with that out of the way, that means if you have a shop with multiple products on it, then you would use geotargeting to specify the primary geotargeting of the website overall. Or you can use geotargeting to say, I don't want to have any geotargeting for my website, I just want to rank normally.  

#### [0:47:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2850) |  And probably that would be the right

approach here in that you're essentially a global website, and some products are more popular in individual countries. And that's perfectly fine. We'll try to rank them appropriately, but there's nothing special that you need to do there. So there's no special markup that you need to put on these pages to say, this product is specifically for the US, and the other product is specifically for Canada, and maybe a third product is global. We'll treat all of these products as being global  

#### [0:48:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2880) |  and still try to rank them appropriately

within the individual countries. And a Google My Business listing question, which I don't really have any insight on. "In a recent webmasters meetup, it was said that the ccTLD is still a strong ranking factor. So does it mean that a .com website with a separate folder is not a correct practice?"  

#### [0:48:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2910) |  No. Essentially, when it comes to geotargeting,

we use two main factors, or two main ways, to try to figure out the country. On the one hand, if you're using a country code top-level domain, then that's a pretty clear sign that you want to target that country. On the other hand, if you use a generic top-level domain, then you can specify that in Search Console. And both of these ways are equivalent.  

#### [0:49:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2940) |  So if you have a generic top-level

domain, you can specify the geotargeting for the whole website. You can verify just a subsection of that site and set the geotargeting for just that subsection in Search Console. And all of that is essentially equivalent. In practice, that means you can use the layout, the kind of the setup that you think works best for your website. But there might be some, maybe, market-specific approaches  

#### [0:49:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=2970) |  that you want to look at as

well, in the sense that an SEO point of view, you can do all of these things. But from a practical point of view, maybe users in one country really prefer to see their own top-level domain in the search results, and they're really kind of cautious about the more generic ones. And then that's something where it's more a matter of marketing which setup that you use. Sometimes it's also a matter of policy in that,  

#### [0:50:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3000) |  maybe if you're-- for example, if you're

targeting users in China, maybe there are some policy reasons why you'd have to say, well, I need to use a Chinese top-level domain, because that's kind of what's required there. I don't know if that's the case, but I could imagine that there are situations that end up like that. AUDIENCE: John. Can I follow up on that question? JOHN MUELLER: OK. AUDIENCE: In current Search Console-- I haven't looked, but--  

#### [0:50:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3030) |  so can you set up /us and

target US, and then /uk and target UK? Can you do all that in the new Search Console? Or do you have to pick one country? JOHN MUELLER: I think geotargeting is not yet in the new Search Console. So you'd have to do that in the old one. But you can-- AUDIENCE: Oh, but you can-- JOHN MUELLER: Yeah, you can kind of mix and match. The thing that you can't do is-- if you use domain verification, then that's  

#### [0:51:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3060) |  only in the new Search Console. But

if you have the subfolder verified, then that would be available in both of them. AUDIENCE: Hi, John. JOHN MUELLER: Hi. AUDIENCE: So, John, actually, this was my question regarding geolocation. So a little different, another conclusion was like, "best coffee shop in New York." One website is in New York or in the USA, which is targeting US, and one website is in India, which is set up  

#### [0:51:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3090) |  not country targeting India. Then how geolocation

works, basically? Like, somebody searching from India will see India site first? JOHN MUELLER: Possibly. Possibly. So what happens with geotargeting is, when we recognize that a user is in one country, and they're looking for something that seems to be specific to their country, then we will use geotargeting to promote the local sites.  

#### [0:52:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3120) |  So there are a lot of situations

where, if you search, you're basically trying to search globally. If you're searching for an instruction manual on one product, then you don't really care which country that's from, and then geotargeting is not really a primary factor. On the other hand, if it looks like you're searching for something to buy, then maybe geotargeting should be a stronger factor. So that's something where, if you're  

#### [0:52:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3150) |  doing a query that is kind of

artificial, like "best coffee shop in New York," while located in India, then I could imagine that our systems get a little bit confused because they don't really know exactly what you're trying to do. But if you're searching for "best coffee shop," and you're located in one country, then we'll try to bring results from that region. So that's kind of-- I think with that specific query example that you had and the location that you had there, then  

#### [0:53:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3180) |  that's not really something that would map

well to the general kind of user side of how users use geotargeting. AUDIENCE: Hey, John. I have a question about the Google Search Console API. JOHN MUELLER: Sure. AUDIENCE: So we're a site that's in the Alexa global top 1k. And around the 1st of April, we've noticed that hundreds out of the many thousands of sitemaps  

#### [0:53:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3210) |  that we have have since then been

reporting incorrect indexed data via the API. So in some cases, ever since early April, the index count is the same, and we know for sure that can't be the case. The index count in some cases is reported as 0. Or in other cases, the index count just seems wildly inaccurate. Meanwhile, the submitted count does seem accurate.  

#### [0:54:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3240) |  And so, essentially, we posted on the

webmaster forums asking for some insights into the issue and to see if others were facing a similar problem. But we weren't able to gain much ground there. So I was just kind of wondering what you think the next steps should be for us, and perhaps maybe we could escalate this issue. Because it seems like if there is some indexation bug or something around the API that maybe  

#### [0:54:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3270) |  was resolved for most sites, our site

still seems to be affected. JOHN MUELLER: That's unfortunately something in the API itself. So that's something where, at some point when we switched over to the new UI for sitemaps reporting, I think they stopped updating that data in the API. So that's probably why you're seeing some stale data for some sitemaps and some zero data for some sites within the indexing count  

#### [0:55:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3300) |  there. I need to talk with the

team about kind of what the next steps there are. I know they've been looking into it and trying to find a way to resolve that. But I think it's been long enough that we need to at least document the state to make it clearer for people who are seeing this problem that this is not something that they're doing wrong, but rather we just aren't updating that at the moment.  

#### [0:55:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3330) |  AUDIENCE: I see. Is there any interim

solution that we can employ-- perhaps submitting those sitemaps as new sitemaps, or do anything else differently that could enable us to get this data? Because this data is pretty critical for us, and not having it for a large portion of the sitemaps that we submit is pretty unfortunate. JOHN MUELLER: I don't think so. I think at the moment it's not being updated at all. So for the sitemaps where you are seeing a number there,  

![](https://i.ytimg.com/vi/zm7mn2sGuyw/hq3.jpg)



#### [0:56:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3360) |  I suspect it's just the number that

was there since April. And for the ones where you're not seeing anything, basically, we haven't added anything there. But I totally get your point. I know that this is something that others are using as well. So we should definitely find a way to get that data back in. I just don't have any ETA on that, so. I think what will probably happen is we'll try to get it updated at least in the documentation  

#### [0:56:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3390) |  so that it's clear that this data

is not available. And then in the next step with the API, where I know the teams are working on improving some things there, that we'll get that back in. AUDIENCE: I see. And so despite some of the sitemap index counts seeming accurate and seeming like they're being updated, it's the case that, entirely for that sitemap API, the index counts should be considered invalid entirely?  

#### [0:57:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3420) |  JOHN MUELLER: Yeah. I would consider them

invalid. AUDIENCE: OK. JOHN MUELLER: Yeah, sorry. AUDIENCE: OK. No problem. Thanks for the insight. JOHN MUELLER: Sure. We still have a bit of time left. Well, actually, we don't have much time left. But I have this room for a little bit longer, so we can continue a little bit longer if you like. If there are any other questions that are on your side,  

#### [0:57:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3450) |  feel free to jump on in. AUDIENCE:

Hey, John, we run a e-commerce business. So we have two listing pages. One listing page will consider all the brands. The other listing page is only a specific brand. The specific brand page is considered as duplicate. So how to eliminate that? And I want it to be indexed. JOHN MUELLER: If we consider them to be duplicate, then that's probably because of the content on those pages.  

#### [0:58:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3480) |  If they're about the same brand, then

I could imagine that we might run in that situation. So if you need to have them indexed individually, then I would make sure that the content is really significantly different. If you don't need to have them indexed individually, then I would pick one of those on your side and use a rel canonical to tell us which one of these versions that you want to have indexed. AUDIENCE: OK. Then one more question also-- is there any necessity to specify the domain name  

#### [0:58:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3510) |  in the meta title and description? If

there is no ranking advantage, so is it necessary? JOHN MUELLER: No, it's not necessary. Some sites use the domain name as a brand name for the site. And putting that in the title is fine, but there's no ranking advantage of using a domain name in the title or description. AUDIENCE: OK. Then one thing also-- like, Google reads the image or text. So suppose that I am hovering over an image,  

#### [0:59:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3540) |  and I display the text. So is

that Google reads it or-- JOHN MUELLER: Yeah. We do use the alt attribute for images. We use it as a part of the page for assessing the web page and for better understanding the image itself. AUDIENCE: OK, thanks. JOHN MUELLER: Wow, 20 people in here. Crazy.  

#### [0:59:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3570) |  I guess this is one advantage of

the new setup. More people can join in at the same time. Any other questions from any of you? AUDIENCE: Hey, John. JOHN MUELLER: Hi. AUDIENCE: Yeah, so this is related to the domain diversity update, which was released in, I think, July or July. So was not Top Stories part of this diversity update? Because what we see is most of the time  

#### [1:00:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3600) |  the same news source is repeated two

or three times within the Top Stories carousel. JOHN MUELLER: I don't know for sure if Top Stories would be included in that specifically. Because a lot of times when we have oneboxes or kind of carousel elements there, then we see those as separate parts of the organic search results page, not the same thing as the normal listings there.  

#### [1:00:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3630) |  So it's quite possible that Top Stories

has its own setup for determining how the diversity should be set up across the pages that we show there. AUDIENCE: Yeah, because it's not like other sources are not covering that same topic. They are covering it, but still, I mean, the same source appears two or three times. So that's my problem, yeah. JOHN MUELLER: I don't know how Top Stories would deal with that.  

#### [1:01:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3660) |  I do hear this from time to

time. So if you have any specific examples or screenshots or something that you can post on Twitter and send my way, that would be useful to pass on to the team. It's sometimes a bit tricky with Top Stories, because it's so specific to the location and the exact time when you do that query. So screenshots are really helpful for that. AUDIENCE: Sure, I will do that. I'll do that. JOHN MUELLER: Cool. AUDIENCE: Thank you. AUDIENCE: John, the same applies still to PAA also?  

#### [1:01:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3690) |  Is that a part of that domain

diversity update? JOHN MUELLER: So-- AUDIENCE: People Also Ask. JOHN MUELLER: People Also Ask. I don't know. Probably. I don't know how those results are created. But that's also essentially a separate block. So generally speaking, they would have their own kind of internal ranking within that block.  

#### [1:02:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3720) |  OK. Let me double-check the-- AUDIENCE: Oh,

sorry. Go on, please. JOHN MUELLER: Let me double check the submitted questions to see if there's anything new that we can add. I think for the most part we have things covered.  

#### [1:02:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3750) |  What else is on your mind? AUDIENCE:

Well, I had one query in my mind. JOHN MUELLER: OK. AUDIENCE: So, John, nowadays I am saying that people have some [INAUDIBLE] like, if we want to shift to other domain, let us just redirect it for one year and we will leave it. In webmaster forum, I am also seeing a lot of people discussing the same thing that you-- please tell me for how long we should have this redirect 301, and we will leave it. How does Google really see if we have shifted  

#### [1:03:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3780) |  this domain to all-- in the market,

or we have sold this domain? And now links are still pointing to x domain, which was redirecting to y domain. How Google determines later on that, yeah, this link equivalent to this link. Why? Because six months back it was redirecting, so now it is also the link to-- link value should be passed to this. JOHN MUELLER: Unfortunately, if you re-use a domain for something else,  

#### [1:03:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3810) |  which could be either on your side

or it could be that someone else has bought that domain, and we discover links to that domain, even if these are older links, then we will count those links as applying to the new domain. So it's not that we would say, well, this is an old link that was there when that redirect took place, therefore we'll ignore that link or pass it to the website that has moved on. It's really the case-- if you remove those redirects and we discover links to those old URLs,  

#### [1:04:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3840) |  then we will probably try to apply

them to the new website there. So it's not something that you would get to keep if you move to a new domain and you let the old one expire. Because of that, that's something where I really recommend on the one hand going through and updating the links, kind of how we have it listed in the help center, and also trying to keep that old domain for as long as possible.  

#### [1:04:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3870) |  Even if you're not using redirects anymore,

just at least keep it within your own control so that you don't run into a situation that suddenly a competitor is taking your old domain and using it to try to write their content. So if you're moving from one domain to another and set up permanent redirects, I'd try to keep them as permanent as possible. And in any case, I'd try to keep the old domain name so that it doesn't expire and end up being something  

#### [1:05:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3900) |  completely unrelated. AUDIENCE: Yeah, thank you. JOHN

MUELLER: John, can I ask a quick question about image links versus regular links? JOHN MUELLER: Sure. AUDIENCE: OK. Because I want us to link to the other websites that we have but showing the logo so it's more user-friendly and that people can see it, and not only have a text linked to that domain name. Would it still be OK to have the link in the image?  

#### [1:05:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3930) |  JOHN MUELLER: Sure, sure. What I think

is useful there is either that you have the text link as well, or at least that you use the alt attribute for the image to kind of give us the anchor text that you want associated with that link. AUDIENCE: So that alt text can be the full domain name? JOHN MUELLER: Sure. Yeah. AUDIENCE: OK. But you will also have a text under it. So it will be linking the image and then the text under. OK.  

#### [1:06:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3960) |  JOHN MUELLER: Yeah, that sounds good. Yeah.

AUDIENCE: Perfect, thanks. AUDIENCE: Hi, John. JOHN MUELLER: Hi. AUDIENCE: My question is, Google solving queries on its own, such as, "what is the capital of UK?" It is possible that Google got to know about this from such websites as Wikipedia and others. If Google will keep answering these questions without mentioning the website source, it is possible that in the future  

#### [1:06:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=3990) |  Google is going to kill all the

traffic to the webmasters who is providing such information about the persons and places. Is Google thinking about the criteria of these kind of webmasters right now? JOHN MUELLER: Sure, absolutely. I think that's something that pretty much everyone on the search team thinks about and tries to take into account. So trying to find the balance between giving people information and making sure that the whole web ecosystem has  

#### [1:07:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=4020) |  a reason to remain kind of a

thriving ecosystem, that's something that we definitely think about a lot. I think there are some kind of queries where it makes sense to show information directly in the search results and maybe others where it doesn't make that much sense. So for example, if someone is looking for the opening hours of a business, then showing those opening hours doesn't cause any problems for that website in the sense  

#### [1:07:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=4050) |  that users aren't going to the website

and clicking on that page anymore to find opening hours. But they find the opening hours, and they use these opening hours to go and visit the business in person. So for the business itself, clicks to that page are not really the critical aspect there, but rather kind of being visible in search and being findable and having their information available for users at the right time, so that they can then kind of make it-- have it a little bit easier to actually convert  

#### [1:08:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=4080) |  with that business and become actual customers.

And that's one aspect there. The other aspect is, of course, if you have content that is very limited in the sense that-- like, you ask, "what is the capital of India?" and the answer is one word. Then if your whole web page is essentially just to answer that question, then of course that will be tricky. Because on the one hand, there's a lot more competition for those kind of pages out there now.  

#### [1:08:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=4110) |  And on the other hand, a lot

of this information is general information that we can just show in search. So if the whole reason for being of your website is to answer these one-word questions, then I do imagine that's something that you will have to figure out on your side, kind of migrating the change in how search works, how the web works overall. But that's something that, from my point of view, is normal,  

#### [1:09:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=4140) |  is a normal part of the web,

in the sense that things evolve over time. The user needs evolve over time, the expectations change over time, and therefore websites themselves also need to find ways to stay with the times and find ways to be unique and compelling so that users want to go to your web page and don't just want a one-word answer. AUDIENCE: Actually, in recent article of [INAUDIBLE],, he is saying that Google is providing--  

#### [1:09:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=4170) |  answering the queries 40% without mentioning the

source. Isn't it alarming to the webmasters? JOHN MUELLER: I did not read that article, so it's really hard for me to comment on that. AUDIENCE: OK. Thank you. AUDIENCE: John, do you have a number of-- or do a rough percentage of what queries you answer on the page rather than not? JOHN MUELLER: I don't know. I don't think we have a public number. I think it's also tricky to say, because some things are  

#### [1:10:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=4200) |  answered directly in a snippet on a

page. And it's kind of hard to say that this is something that Google is doing differently versus maybe the answer is just in the meta description of the page. AUDIENCE: All right. I just wonder. I suspect it's not a big issue. People just notice it. [INAUDIBLE] JOHN MUELLER: Yeah, I imagine it's something that changes over time as well, depending on how people search, what kind of questions people  

#### [1:10:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=4230) |  use to search. It's one of those

things where, I think, user needs and user expectations change quite a bit over time. AUDIENCE: I think business expectations have changed as well. I think people now think you can monetize "what's the capital of India," where 20 years ago you'd look at it in a book or you ask someone else. There's no money to be made from that query. So people have got lucky for 20 years and maybe have made some money out of it, but things change. You can't make money out of everything.  

#### [1:11:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=4260) |  JOHN MUELLER: That's probably the case, too,

yeah. I mean, like, capital of India, I could imagine that for a long time you could make kind of ads-- make for ads landing pages that worked really well in search for that. And like you said, for a while you could probably make a decent living just answering these basic questions. But things change. And especially when it comes to, I think, bigger websites, that's something  

#### [1:11:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=4290) |  that has changed significantly as well, where

in the beginning you could make a landing page on specific book topics or specific things, just because there is no kind of general source of information on the web, and you could rank for those and perform really well. And nowadays, there are lots of different sites that are trying to compete with all of these queries. Yeah. I think, Axel, you're raising your hand. AUDIENCE: Yeah. JOHN MUELLER: Go for it. AUDIENCE: This is Axel from Germany.  

#### [1:12:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=4320) |  I'm managing a really old site where

we have special chars in the URL. So some editor has created URLs with copyright names and French accents, like Avene or Elmex Gelée. And I noticed that the GSC, the check URL tool is not accepting the URL at the moment, because it says it won't encode it. Could you investigate on that?  

#### [1:12:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=4350) |  JOHN MUELLER: Do you have some example

URLs? Like, maybe you can copy it to chat? AUDIENCE: Yeah. I'll give you one in a minute. So we have here one URL where the editor, the person, basically put in the product in-- this one, it's a German site. And there's a product, and there's a percentage AE, which is the copyright sign.  

#### [1:13:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=4380) |  This one I would say is not

so legit. But there's another one where the brand name is called "French Avene." There's also a famous toothpaste in Germany called Elmex Gelée, which has an É. And so the content editor just types in the name of the brand, and the CMS is like converting the URL. And if you paste that into check URL, it's, like, not-- JOHN MUELLER: Yeah.  

#### [1:13:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=4410) |  Trying those in the browser also doesn't

show the character. But it should at least load. So I'll double-check with the team on that. In general, what we recommend for kind of non-- I don't know, non-standard? I mean, these are standard characters, but kind of the non-ASCII characters-- AUDIENCE: [INAUDIBLE] JOHN MUELLER: Yeah. The kind of special characters is that you use Unicode if you include them a URL.  

#### [1:14:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=4440) |  That way we can always pick that

up. But we should-- I mean, if you can load this page in a browser, we should be able to test it with the testing tools as well. So that seems like a bug on our side. AUDIENCE: The tool says at the moment URL is not in the correct format, and we are trying to switch our system from a ISO Latin-1 one to UTF-8 page, so it's going to be probably sorted. So if you could pass that to the devs.  

#### [1:14:30](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=4470) |  JOHN MUELLER: Yeah, I'll definitely pass that

on. Thanks. Cool. Any last questions before we close out for the week? Everything good? OK. That's good. I think the indexing issue that we had yesterday should be mostly resolved now as well. So maybe we can go into the weekend with a little bit less stress.  

#### [1:15:00](https://www.youtube.com/watch?v=zm7mn2sGuyw&t=4500) |  I hope the week has been good

for you all. And I wish you all a great weekend. Thanks, everyone, and see you next time. Bye. AUDIENCE: Bye.  