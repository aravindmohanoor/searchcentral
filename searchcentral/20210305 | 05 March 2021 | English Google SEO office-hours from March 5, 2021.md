[![English Google SEO office-hours from March 5, 2021](https://i.ytimg.com/vi/8UBSEiO87GM/hqdefault.jpg)](https://www.youtube.com/watch?v=8UBSEiO87GM)

## English Google SEO office-hours from March 5, 2021

This is a recording of the Google SEO office-hours hangout from March 5, 2021. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Find out more at https://developers.google.com/search/events/join-office-hours



Feel free to join us - we welcome webmasters of all levels!



#### [0:00:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=0) |  JOHN MUELLER: All right. Welcome, everyone, to

today's Google Search Central SEO Office Hours. My name is John Mueller. I'm a Search Advocate on the Search Relations team here at Google. And part of what we do are these Office Hour Hangouts where people can jump in, ask their questions around search, and we can try to find some answers. A bunch of stuff was submitted already on YouTube. So we can go through some of that. But like always, I think it's always neat to start with live questions.  

#### [0:00:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=30) |  Anything from your side, anyone who wants

to get started? VAHAN PETROSYAN: Yeah. I would like to ask the first question. JOHN MUELLER: OK. Go for it. VAHAN PETROSYAN: I am a Vahan. I'm an IT director of Search Engine Journal. And one question I have about Core Web Vitals is, is there a possibility that Google can start revise that score in the master quicker? Like, I did updates on the website  

#### [0:01:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=60) |  and have found that Core Web Vitals

are broken after 20 days because it's updating in the weeks, in a long period. So I have fixed that. But it will take another couple of weeks to have that fixed. Is there a possibility that Google can review and make those updates more quicker? Like, not like 28 days, but a couple of days?  

#### [0:01:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=90) |  JOHN MUELLER: Yeah, I don't know. I

doubt it, because the data that we show in Search Console is based on the Chrome User Experience Report data, which is aggregated over those 28 days. So that's the primary reason for the delay there. It's not that Search Console is slow in processing that data or anything like that.  

#### [0:02:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=120) |  It's just the way that the data

is collected and aggregated, it just takes time. So usually what I recommend when people ask about this kind of thing where it's like, I want to know early when something breaks, is to make sure that you run your own tests on your side, kind of in parallel for your important pages. And there are a bunch of third party tools that do that for you automatically. You can also use the Page Speed Insights API directly  

#### [0:02:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=150) |  and pick-- I don't know-- a small

sample of your important pages and just test them every day. And that way you can kind of tell if there are any regressions in any of the setups you made fairly quickly. Obviously a lab test is not the same as the field data. So there is a bit of a difference there. But if you see that the data lab test  

#### [0:03:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=180) |  results are stable for a period of

time and then suddenly they go really weird, then that's a strong indicator that something broke in your layout, in your pages somewhere. VAHAN PETROSYAN: Thank you. SPEAKER 1: Quick follow up. JOHN MUELLER: Sure. SPEAKER 1: So does that mean that if I-- say that I have really bad core web vitals and manage to fix most of those issues in one day.  

#### [0:03:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=210) |  The next day, that would be-- or

rather, two days later-- that would be part of these 28 days because that would-- would it be a rolling update or is it every 28 days that it happens? So-- JOHN MUELLER: I don't know for sure. I think the Chrome User Experience Report site has that documented. I'm not sure if it's, like, a matched update that is just done every 28 days, or if it's more of a rolling thing. I know in Search Console we have kind of the overtime data.  

#### [0:04:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=240) |  And it's not that it jumps every

28 days. So my guess is it's probably more rolling. SPEAKER 1: All right. I will check that. Thank you. ROBB YOUNG: So it could still take 28 days to fully-- so after one day, you're 128th of the way there to seeing what the results are, which is why you suggest doing your own test manually? JOHN MUELLER: Yeah, exactly. VAHAN PETROSYAN: But that makes web development very expensive,  

#### [0:04:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=270) |  as well. JOHN MUELLER: It makes things

harder, yes. I mean, it's not that we're trying to make things harder. It's just the way that this data is collected in Chrome, it just takes time to be aggregated. VAHAN PETROSYAN: So just to know everybody what the broad Core Web Vitals score, since something was updated on the Core Web Vitals calculations, since it seems better.  

#### [0:05:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=300) |  So we were hiding the modification menus

when you scrolled down. And it showed when you scroll up. And used tests like the position to animate it, like hide it. And seems that position animations did spoil the Core Web Vitals. So even though it's a sticky menu and it's not causing layout to shift,  

#### [0:05:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=330) |  but it's calculated as a layout shift

because you are animating the position of the element. So we did change that animation from position to opacity. Like, we are just feeding out it instead of moving away from the screen by position animation. JOHN MUELLER: Yeah. The cumulative layout shift is sometimes, I think, tricky to interpret and figure out what exactly  

#### [0:06:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=360) |  is causing issues there. Yeah. VAHAN PETROSYAN:

Yeah, because in the past, it wasn't causing-- our Web Vitals were all green. In one day I found everything is in red. What could cause that? And I have found that just [INAUDIBLE] position animations, which even though it cause the layout shifts are contributing into layout shift calculations. JOHN MUELLER: Yeah. I think for things where you feel that the calculations are  

#### [0:06:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=390) |  being done in a way that doesn't

make much sense, I would also get in touch with the Chrome team. I think especially Annie Sullivan is working on improving the cumulative layout shift side of things. And just make sure that they see these kind of examples. And if you run across something where you say, oh, it doesn't make any sense at all, then make sure that they know about it.  

#### [0:07:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=420) |  It's not so much that from Google's

search side we would try to dig in and figure out exactly why this is happening with that score, but we kind of need to rely on the score from the Chrome side. And our goal with the Core Web Vitals and page experience in general is to update them over time. So I think we announced that we wanted to update them maybe once a year and let people know ahead of time what is happening.  

#### [0:07:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=450) |  So I would expect that to be

improved over time. But it's also important to get your feedback in and make sure that they're aware of these weird cases. VAHAN PETROSYAN: Thank you. JOHN MUELLER: Sure. All right. MOHAK NAHTA: Hi, John. JOHN MUELLER: Yes. You raised your hand. Perfect. Exactly. MOHAK NAHTA: Great. Yeah. So our website consists of a lot of-- thousands of guides that we made to help people  

#### [0:08:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=480) |  understand visa requirements based on their location.

And the way we've designed these guides are that they're meant to be a one-stop destination. But that said, some of the content is overlapping and there's a risk that Google might interpret these pages as doorway pages, even though that's not our intention. For example, we have a guide for France visa in Los Angeles and then France visa in Detroit. And it's personalized to the city. But a lot of the content is also similar.  

#### [0:08:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=510) |  And so what is your advice to

make sure it's not interpreted as [INAUDIBLE] or canonicalized by Google, given that we have so many of these? JOHN MUELLER: I don't know. It is hard to say. So offhand, just hearing that you have city-level pages for visa advice feels a lot like you're headed into the direction of doorway pages. So that's something where I would  

#### [0:09:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=540) |  be really cautious about expanding too much

in that direction, because obviously you're going to have things like, well, all of the country information is exactly the same. And essentially, the difference is the address and maybe a telephone number or opening hours. And that's something where I suspect our systems, on the one hand, could be getting confused from the content side, and where probably if someone from  

#### [0:09:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=570) |  the web spam team were to look

at that, they would say, this is potentially too much, especially if you really have, like, on a city level, country wide information that feels like you could easily expand that to 10,000s of cities and claim that it's all unique content because it's for every city individually. And I have some kind of basic information about each city, as well, on those pages.  

#### [0:10:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=600) |  But in the end, it's all about

one country and the visas for the other country, right? So that's something where I would try to take a strong look at what you can do to try to concentrate those pages so that you don't end up in a situation where you're just taking a giant list of cities, giant list of countries, and then crossing them in a database and generating pages. MOHAK NAHTA: Mm-hmm. Got it. And then just a follow up question. So we'll definitely look into it.  

#### [0:10:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=630) |  So across all the pages that we

have, Google's indexed only about 100 of them. And the primary reason, when I look at the crawl stats report, is that Google only crawls about 60 pages. And all the other pages are excluded, like discovered but not crawled, which means that they didn't want to overload our website. But we have full success rate and really low response times. How would you suggest we go about getting the crawl  

#### [0:11:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=660) |  budget up? JOHN MUELLER: Yeah, so there

are two aspects there with the crawl budget-- on the one hand, kind of the technical limitations of the server, and on the other hand, the demand from Google with regards to what we think is important to index. And it sounds like the technical limitations on your server are less of an issue. If you're saying it's a fast server, everybody responds quickly, then primarily what you're probably seeing is that Google is running into a situation  

#### [0:11:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=690) |  where it's saying, well, I don't know

how useful these pages actually are. And that's something that Google can learn over time. But it's not something that you can force. And even if you can force it for like a temporary situation where Google goes off and indexes tens of thousands of pages from your site, if then it still determines, well, actually, this site is not as useful as I thought it was, then it will just drop those pages from the index over time.  

#### [0:12:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=720) |  So assuming this is still the visa-level

site, then that's something where I would strongly recommend starting off with a much smaller set of pages, a much smaller set of content, so that it's something that Google can index, Google can learn over time that, actually, this is really good content. And based on that, it can expand and say, well, actually, OK, instead of just 100 pages, I'll go and crawl 1,000 pages or go and crawl 10,000 pages  

#### [0:12:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=750) |  and try to get those indexed, as

well. But kind of especially when you're starting off with a site that has a lot of content, potentially, I would try to find a way to decrease the size so that you can grow and become strong first and then expand to showing more content. MOHAK NAHTA: Awesome. Thank you so much. JOHN MUELLER: Sure. RAMINDER KAUR: Hi, John. JOHN MUELLER: Hi. RAMINDER KAUR: Hi. So this is Raminder.  

#### [0:13:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=780) |  I have a question regarding site maps,

which is similar to the previous discussion. So we have a news site. And we have older site maps, like ranging from 2009 to 2015, say. And we're facing some of the site maps do have certain issues, like images. Image URLs have migrated. And because of that, we're getting issues in the older site map. So just wanted to check with you. How important are the older site maps  

![](https://i.ytimg.com/vi/8UBSEiO87GM/hq1.jpg)



#### [0:13:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=810) |  for the [INAUDIBLE],, since we feel it's

already archived in that case. And secondly, does it help the crawl budget by removing the older sitemaps? JOHN MUELLER: Yeah. Good question. So with regards to site maps, we use that to better understand which pages we need to crawl and update. And if you know that you have sitemap files that point to pages that don't exist anymore, or that you don't care about anymore, then essentially,  

#### [0:14:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=840) |  I would try to remove those pages.

So if this is a site map file that was useful, I don't know, a couple of years ago, and your website has migrated in the meantime, you have a different URL structure, then telling us about those old URLs doesn't give us any useful information. So I would consider regenerating the site map files and really making sure that they contain the current set of URLs from your website that you care about. And that's less a matter of crawl budget,  

#### [0:14:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=870) |  I think, but more just kind of

like general website hygene in that you're making sure that Google understands what you care about and is able to process that as easily as possible. RAMINDER KAUR: OK. [INAUDIBLE] Thank you. JOHN MUELLER: Mohak, I think. MOHAK NAHTA: You already answered my question. JOHN MUELLER: Oh, OK. Emre? - Emre. Hey. JOHN MUELLER: Perfect  

#### [0:15:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=900) |  EMRE SANLI: OK. So recently we implemented

structured data for voice search, speakable structured data. And we would like to understand what will be the impact. And is there any way that we can somehow understand what percentage of the traffic comes from the voice search or is there any trick that we can use to extract this information from the Search Console?  

#### [0:15:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=930) |  JOHN MUELLER: I don't think you can

see anything with regards to Voice Search there at the moment. So that's something people have asked about on and off. Not for a long time now, but every now and then. But I don't think there is anything in Search Console that gives information about how the speakable markup is used or when that's shown. So it's almost something that you'd probably have to try out for yourself and see,  

#### [0:16:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=960) |  is it doing what you think it's

doing? Or is it not that useful? EMRE SANLI: OK. Thank you. And I have another question. JOHN MUELLER: Sure. EMRE SANLI: It's about how we can force Google to refresh the resources-- I mean, the cache, resources cache? For example, if we change something with our JavaScript file or, I don't know, CSS or something like this, how we can force Google to refresh this file?  

#### [0:16:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=990) |  JOHN MUELLER: So you mean with regards

to rendering the page or with regards to-- [INTERPOSING VOICES] EMRE SANLI: Because we had an issue and the page was returning that empty page because of this caching issue. So we, let's say, redeployed the site. And we saw that Google continued to use the old JavaScript file. So what we can do about this? I mean, to force Google to refresh?  

#### [0:17:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1020) |  JOHN MUELLER: I don't think you can

easily force it to refresh that. But there are two things you can do. One is to serve the files with the appropriate caching headers so that Google knows approximately how long it could be cached. It's a bit tricky there, because the caching that we do for rendering is very different from the caching that our browser usually does for users. So it's helpful, but it's not the perfect solution.  

#### [0:17:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1050) |  The other thing that I've seen people

do is to update the URLs when they make significant changes within the content. So I have seen some that use something like a content hash in the URL for the JavaScript files, for the CSS files. And in general, when we try to render an HTML page and we see a link to a new JavaScript file, which would be based on the content hash, for example,  

#### [0:18:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1080) |  then we would know that, oh, this

is a new JavaScript file. We need to take a look at it, whereas if you keep the same file names for JavaScript and CSS, then we might be tempted to just reuse our cache. EMRE SANLI: OK. Thank you. JOHN MUELLER: Sure. Esther, I think you're next. MOHAMMAH MEHDI ABBAS: Hi, John. JOHN MUELLER: Oh, wait. ESTHER ASHMORE: Hi. JOHN MUELLER: Hi. ESTHER ASHMORE: Hi. We're currently conducting a large site migration  

#### [0:18:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1110) |  after our company was acquired by another

company. So we're basically lifting and shifting some pages over to our website amongst our existing content and changing the domain. Are there any top five tips on what I should look out for whilst I'm doing this? JOHN MUELLER: Yeah. I think the most important part is really  

#### [0:19:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1140) |  to track the individual URLs so that

you have a clear map of what previously was and what it should be in the future. And based on that, on the one hand, to make sure that you have all of the redirects set up properly, so the various tools that you can use to kind of submit the list of the old URLs and check to see that they redirect to the right new ones. The other thing I would watch out for  

#### [0:19:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1170) |  is all of the internal linking so

that you really make sure that all of the internal signals that you have, as well, that they're forwarded to whatever new URLs, because what sometimes happens, or what I've sometimes seen with these kind of restructurings, is that you redirect the URLs. You move them over. But you forget to set the rel canonical. You forget to set the links in the navigation or in the footer somewhere. And all of those other signals there,  

#### [0:20:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1200) |  they wouldn't necessarily break the navigation. But

they make it a lot harder for us to pick the new URLs as canonicals. So that's kind of the effect that you would see there. It's not so much that it would stop ranking. But it's more that, oh, we just keep the old URLs for much longer than we actually need to. ESTHER ASHMORE: OK. Brilliant. Thank you. JOHN MUELLER: Yeah, sure. MOHAMMAH MEHDI ABBAS: Hi John. JOHN MUELLER: Hi. Let me just grab the next one in the list  

#### [0:20:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1230) |  and I can get back to you.

Dwayne? MOHAMMAH MEHDI ABBAS: No, I just-- DAYNE RICHARDS: Hi, John. Thank you. So we're rethinking how we display our publication dates on site, on the front end. And I want to know what the official stance is, whether we need to have both the published date and update date, our last modified date to comply with structured data?  

#### [0:21:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1260) |  I know that most of structured data

requires that you have some physical element that's marked up. So that's kind of-- want to see what you think is best there. JOHN MUELLER: We have a Help Center page on dates. I would double check that. I don't think it's necessary to specify any date in structured data. So if you give us some date information, that helps us to better understand it. Usually what happens with regards to dates is we try to pick a date that is relevant for the page.  

#### [0:21:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1290) |  And we do that based on the

structured data that you have on the page, but also based on things like, what is on the page itself? So as much as possible, like a lot of SEO signals, I think, it's important to make sure that all of these things align, that if you're giving us a date in one place, that it's actually a date that's visible on the page, that the time zone is correct that you specify there,  

#### [0:22:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1320) |  all of these kind of small details

as well, just that it matches the other information that we find. DAYNE RICHARDS: OK, yeah. The reason we're thinking is because we're seeing that sometimes we aren't seeing the proper modification page show up in search. So we want to be able to have that work properly. So thank you. JOHN MUELLER: Yeah. Our systems kind of work in a way that we pick up all of the dates that we can find for this piece of content.  

#### [0:22:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1350) |  And then we try to figure out

which ones kind of match up the best. And based on that, we try to pick the right date. And sometimes if you have-- I don't know, a news site, then you'll have related articles or things like that where you also have dates kind of mentioned in the text. And if we don't find clear information in the structured data for the date, then we might pick one of these other random dates on the page,  

#### [0:23:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1380) |  as well. DAYNE RICHARDS: Can I just

follow up one more time on that? So how does Google decide to show the last modification date? Does it need to reflect a significant change on the page? Or is there something else I need to think about? JOHN MUELLER: I don't think we have any specific guidelines on when you should change the dates. But for practical reasons, I would  

#### [0:23:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1410) |  try to do it then when you

have significant changes on the page. So it's not like I just swapped an ad out in the sidebar kind of thing. But really, if it's in the primary content and you made some significant changes, then that feels like something that you'd want to flag there for users, as well. DAYNE RICHARDS: Not necessarily me changing the publication date, but will Google then pick up the modification date if I made the substantial change versus just showing me the publication date?  

#### [0:24:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1440) |  Sorry. JOHN MUELLER: Yeah. I don't know

how we decide between publication date and last modification date. Not really sure how you'd be able to easily influence that. I could imagine that we try to see when significant changes happen on a site. But we're on a page. But I don't think we have any explicit guidelines on that. DAYNE RICHARDS: OK. Thank you so much. JOHN MUELLER: Sure.  

#### [0:24:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1470) |  MOHAMMAH MEHDI ABBAS: Hi, John. JOHN MUELLER:

Hi. MOHAMMAD MEHDI ABBAS: This is Mehdi Abbas. Again, I am here with a very simple, basic question as I started learning SEO. So this time my question is related to headings, heading structure, basically. Is it mandatory that we should structure our headings in ascending order, or we can leverage the structure as [INAUDIBLE]? JOHN MUELLER: It's not necessary to have kind of this theoretically correct order of the headings.  

#### [0:25:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1500) |  And the number of H1 headings that

you have is also something that is kind of open. I think for a large part, it makes sense to try to have a semantically correct heading structure, because there are things like screen readers that also rely on headings to kind of navigate to the right part of the page. So it certainly makes sense to try to get that. But I wouldn't see it as something where you would see significant changes in SEO if you change  

#### [0:25:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1530) |  the order of your headings. MOHAMMAD MEHDI

ABBAS: Another question is related to H1 tags. What is the optimal or ideal numbers of H1 tags we can have in a page? Because I have read so many articles of industry expert that there should be only one H1 tag from the perspective of SEO. So what do you recommend? JOHN MUELLER: You can have as many as you want. So I think in many cases, you have one primary heading.  

#### [0:26:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1560) |  But if you have multiple, that's fine.

With HTML5, it's also the case that by design in HTML you have multiple H1 tags. So it's something where there's definitely not a hard limit with regards to the number of primary heading tags. I think from a kind of a focus point of view that you have a clear focus on your page, it makes sense to have one primary topic.  

#### [0:26:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1590) |  But that can be something that you

highlight in other ways. It could be-- like, it doesn't necessarily need to be the H1 tag. It could be something that you have with a big title, or if this is your home page, then maybe you have other ways of structuring what you think is the primary topic of the page. MOHAMMAD MEHDI ABBAS: So can I say Google gives the importance on the basis of structures of headings to the content?  

![](https://i.ytimg.com/vi/8UBSEiO87GM/hq2.jpg)



#### [0:27:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1620) |  JOHN MUELLER: To some extent. It's not

only that, but it does help us to understand what you think is important for the page. And if you say, well, this is the primary heading for my page and what this page is about and we see it matches what you have in your content, then that's always useful for us to know. MOHAMMAD MEHDI ABBAS: Thank you. JOHN MUELLER: Sure. And Rob, you're so patient. ROBB YOUNG: Am I, though?  

#### [0:27:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1650) |  So you give us your current take

on the supported image types for the Core Web Vitals and page speed? Because you guys still seem to be recommending file types that you don't actually support, or are not really the optimal image types to use. And I say that because when I look at our page speed insight  

#### [0:28:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1680) |  scores, they seem to be fine. We

can save 0.15 seconds on JavaScript, 0.9 seconds on deferring off screen images. But we can save 12 seconds by changing the file types to image types like JPEG XP or JPEG 9,000 ABC that you don't even support. So can you clarify that?  

#### [0:28:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1710) |  JOHN MUELLER: I haven't seen that, so

it's hard for me to say. ROBB YOUNG: I can share my screen. JOHN MUELLER: Maybe not. No, I mean, just because-- since we're talking about images and things, I don't want it to suddenly be like, oh, it's like you're showing copyrighted images on your YouTube thing. So that's a primary thing I'm a little bit worried about.  

#### [0:29:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1740) |  But if you want to drop your

URL in the chat-- like, the one that you're looking at-- then I can take a look at that afterwards. ROBB YOUNG: It's just our UK home page, which I'm sure you know. JOHN MUELLER: OK. The homepage. OK. ROBB YOUNG: But in particular, the time-- because, we have no problem updating the image to a file type that you like. But why is that still the recommended file type when you don't-- you guys don't really support JPEG 2000?  

#### [0:29:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1770) |  JOHN MUELLER: I don't know. It feels

like we should support that. ROBB YOUNG: It does, doesn't it? JOHN MUELLER: You're saying that we don't support it in image search, or-- ROBB YOUNG: Well, for as far as I know, and a developer and whenever you search it, Chrome doesn't support JPEG 2000, but recommends it as the recommended file type to speed up your pages. JOHN MUELLER: That seems kind of an awkward mix. ROBB YOUNG: Seems to be conflicting information. JOHN MUELLER: Yeah. I don't know. But it might be also a sign that there are other image  

#### [0:30:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1800) |  optimisations that you could do to decrease

to file size. ROBB YOUNG: But it never mentions file size, just type. They're all PNG, which is JPG. JOHN MUELLER: Yeah. JPEG 2000. That seems like forever ago. OK, I'll take a look at that. Interesting. Cool. OK, let me run through some of the submitted questions. And then we'll have more time for questions from you  

#### [0:30:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1830) |  all along the way, as well. I'm

managing one of the biggest news sites in our country. I want to improve internal linking for news and I'm thinking about including the latest news section in the sidebar so that the latest articles are linked not only from the home page, but also from most pages on the site, as well. Is this a good approach or is only linking from the home page enough that these-- whoops. Enough and those sidebar links won't necessarily  

#### [0:31:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1860) |  move the needle or pass additional value?

Usually this is a good approach. If they're new or important pages on your website and you link to them from across the rest of your website, then that helps us to better understand that you care about those pages and you want them to be crawled and indexed as quickly as possible. Usually when it comes to news sites, we focus a lot of our crawling on the new site map that you have and on so-called hubs, which  

#### [0:31:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1890) |  are usually the home page, the category

pages, pages that we can refresh very quickly where you link to the individual news articles. So probably for a reasonably-sized news site, we should be able to pick up all of the new content that way already. So it's more a matter of giving us a signal for the importance of those other pages.  

#### [0:32:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1920) |  So that's something where, if you think

that these new articles are not performing as well in search as they could be, then linking to them like this probably makes sense. If you have other articles that you care about that you want to be more visible in Search-- and that could be something that is older, could be something that maybe is a cause that your site cares about. Maybe it's important information that you need to share for the long run. Then I would definitely also include that in something like a sidebar or footer links.  

#### [0:32:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1950) |  So I think overall it's a reasonable

strategy. I think especially for non-news websites, it definitely makes sense. So if it's an e-commerce site, for example, and if you have new products or related products, you could link to those in the sidebar. That's a fantastic way for us to get that information. For a news site, we probably can already find those pages in other ways. And it's more about giving a subtle hint of importance.  

#### [0:33:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=1980) |  What's the best practice for anchor text

wording on internal links as well as external links-- for example, using the website name, the blog post title, exact match, or LSI keywords? So first of all, we have no concept of LSI keywords. So that's something you can completely ignore. I think it's interesting to look at LSI when you're thinking  

#### [0:33:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2010) |  about understanding information retrieval as a theoretical

or computer science topic. But as an SEO, you probably don't need to worry about that. With regards to internal links, you're giving us a signal of context. So basically, you're saying, in this part of my website, you'll find information about this topic. And that's what you would use as the anchor text for those internal links. So that's something where, on the one hand, usually that's something that you  

#### [0:34:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2040) |  want to kind of give that context

to users, as well, so the kind of internal links-- whoops. The kind of internal links that you would use for users usually match what you would use for SEO. As well. So that's something where luckily there is a nice overlap there. With regards to external links, if you're linking out to other people's websites, the same things, like supply some context why people should go and click  

#### [0:34:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2070) |  on this link, what kind of extra

information it gives. With regards to links to your website from other people's websites, usually that's something you wouldn't have control over anyway, so I'd be kind of cautious about what you need to have there. Second part of the question-- is it true that the more links you have on a page the more page authority gets divided amongst the links? If so, is there a range to be within?  

#### [0:35:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2100) |  So we do use page rank. We

don't use page authority in our systems. We do use page rank as a way of understanding the internal structure of a website a little bit better. And it does take into account the links on a page. And we kind of forward the signals across these pages. But it's not the case that there's any optimal number of links that you need to have on a page to make that work well.  

#### [0:35:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2130) |  Essentially, if you're creating a website that

has a reasonable structure for users where they can navigate around your website in a reasonable way, then that would work for search, as well. And especially if you were getting started, then that's something where I wouldn't necessarily focus on the number of links on the page and use that as a metric to try to figure out how to keep your pages running. I think at some point if you have a very large website and Google has trouble understanding the structure  

#### [0:36:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2160) |  or has trouble crawling it properly, then

the internal linking structure is certainly something to look into. But especially with smaller, newer sites, that's something you probably don't need to worry about too much. GAGANDEEP SINGH: John, can I ask a follow-up to your last question? JOHN MUELLER: Sure. GAGANDEEP SINGH: Yeah. Actually, I just want to know if I have links to other pages on my website from my article, does Google try to understand the other articles which  

#### [0:36:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2190) |  I'm linking to by looking at [INAUDIBLE]??

This is like 500 word [INAUDIBLE]?? From there you are going to this page. So we will try to understand from 500 words-- like, get some information about title page, which I am linking to internally. Does Google do that? JOHN MUELLER: A little bit, but not so much in that random words on a page will impact how linked pages are handled.  

#### [0:37:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2220) |  So we take that into account with

regards to understanding the context of the pages that you have there. Usually the anchor text is the most important part there. With images, it's something where we do take into account kind of the content around that image. So that's kind of in the direction that you're saying there. And it's less so in a case like that that's  

#### [0:37:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2250) |  like, any random text on a page

will count towards that, but more really around this image or around the link there, what kind of information is available? GAGANDEEP SINGH: So just for better understanding the page which you link? JOHN MUELLER: Yeah, exactly. And you can kind of guess some of this if the destination page is blocked by robots.txt. Then there are still some situations where we would show it in Search, even if it's blocked by robots.txt.  

#### [0:38:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2280) |  And we would only be able to

show it in Search based on the links that we have to that page. So that's one way to kind of see, well, what kind of information is Google picking up from those internal links? GAGANDEEP SINGH: [INAUDIBLE] thank you. JOHN MUELLER: Sure. My blog has been completed since two months. I posted content in January and in starting it was an index. But now it's not in Google anymore. What is the reason for the de-indexing of the post  

#### [0:38:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2310) |  and how can I get it back

into Google? I don't know. It is really hard to say without any additional information there. So the one thing I would recommend in a case like this is go to the Search Central Help Forums. Post your URL, some keywords that you were targeting there, and try to get some advice from the community. Sometimes there are technical things that are wrong on a site that you need to fix to make it so that we  

#### [0:39:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2340) |  can index it properly again. Sometimes it's

more a matter of quality of individual pages or of the website overall. And that's something where the feedback is sometimes hard to take, but it's sometimes really useful to get that feedback anyway. So I would make sure to just provide all of the information that you can give there with regards to the pages, the rest of your site, what all has been happening there. If there's a web spam manual action that took place  

#### [0:39:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2370) |  with regards to that page or the

site in general, you would see that in Search Console. So probably you've seen that. For the most part, if you're using a common CMS system, then probably the technical details are kind of OK. And it's really more a matter of the quality side of things. Our log files show that Googlebot finds a lot of JSON files, even more than normal pages.  

#### [0:40:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2400) |  Might these kind of pages exhaust our

crawl budget? Does Google crawl API routes or is this somehow internally prevented? If we disallow our API and robots.txt, how does that affect the XHR requests? Would they still be able to deliver content? So super good question. Yes, all of these requests do count towards the crawl budget. So that's something where essentially every request  

#### [0:40:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2430) |  we make to the server that goes

through the Googlebot infrastructure is something that we would count as a request that we make. I mean, it is a request. And we would try to limit that based on the technical limitations that we feel apply to your server. And based on that, we might say, well, we can get more or we can get less content here. So in a case like this, you're probably more looking at the technical limitations when it comes to crawl budget and less the crawl demand  

![](https://i.ytimg.com/vi/8UBSEiO87GM/hq3.jpg)



#### [0:41:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2460) |  side of things. And it's something where

if you just look at the server logs and you see a lot of JSON files that are being requested, it's not necessarily a sign that something is broken. It's not necessarily a sign that the crawling is limited due to these JSON requests that are made. It's just, well, we happen to make a lot of these. And it could be the case that we make a lot of these requests but we can still crawl enough of the normal content  

#### [0:41:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2490) |  and it doesn't really affect the normal

crawling and indexing of the site. So that's something I would try to figure out ahead of time. There's no simple way to see that. There's no information in Search Console directly that says, oh, you've exhausted the technical limitations that we think apply to your server. So that's something where you almost need a little bit of experience and a little bit of guessing when looking at the graphs and looking at your servers  

#### [0:42:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2520) |  and kind of testing individual URLs to

figure out, is it possible that Google is running into limitations with regards to what it can crawl? Or is it possible that Google is crawling as much as it wants and it's OK with that? So that's kind of the first step there. With regards to blocking these JSON files, if you do find out that these requests are causing problems, one approach is to kind of speed things up so that the technical limitations are  

#### [0:42:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2550) |  less of an issue, which could be

to move some content into a static CDN somewhere so that those requests are easier cachable, that they go a little bit faster than the rest of the requests to your site. That might be an option. If you decide that you do need to block the crawling of these JSON files, then you just need to keep in mind that this does include rendering of pages that kind of try  

#### [0:43:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2580) |  to embed these JSON files or that

request these JSON files. So if there is content on your site that is only visible after rendering pages that request these JSON files, then that content will no longer be indexable because we can't get to those JSON files anymore. So that's kind of the downside of blocking things there. It's similar if other people on other websites  

#### [0:43:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2610) |  are using your APIs and kind of

using your APIs to generate content for their pages. If you block those JSON files from being crawled then those pages on their site won't be able to get that content indexed. It might be that you don't really care about that and that's fine for you. But it's kind of something to keep in mind there. Yeah. I think-- VIJAY CHAUHAN: Hi, John. JOHN MUELLER: Pretty much it with the--  

#### [0:44:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2640) |  yeah, go for it. VIJAY CHAUHAN: Yes,

John. [INAUDIBLE] platform [INAUDIBLE].. And we are facing some issue related duplicate canonical thing. So the issue is Google is picking the wrong pages instead of choosing original pages. [INAUDIBLE]? JOHN MUELLER: OK.  

#### [0:44:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2670) |  RUCHIT PATEL: OK, so let me add

in from the same team. JOHN MUELLER: OK. RUCHIT PATEL: So basically, we have 9,000 cities, and each city has a different event on them, basically listing the events. So since a few months you are seeing Google is bringing up wrong city instead of other cities. If you search about events in Washington, it will show a result of the San Francisco. And when we check canonical, it has picked up the wrong canonical. And the whole page and the content, everything  

#### [0:45:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2700) |  is different. Still is picking up a

whole different city for around 2,000-3,000 pages are affected like this. JOHN MUELLER: OK. There are two possible things that I've seen that could be playing a role here. The first one depends a little bit on the way that you have your site set up. I didn't check in this case.  

#### [0:45:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2730) |  But if you're using JavaScript to generate

some of this city-level content and for whatever reason we can't process the JavaScript properly, then it's possible that we see more of a generic page for some cities. And then we could say, well, this generic page is the same as that other generic page. And then we treat them as duplicates and we pick one of them as canonicals. That's something where you could probably recognize that fairly quickly if you use view source on the page  

#### [0:46:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2760) |  and you see opposing JavaScript that doesn't

have in the HTML the actual content from the individual cities. You can double check some of that with the Inspect URL tool, as well, in Search Console to see what is the content that Google picks up after rendering. The tricky part there is if it's really with JavaScript, sometimes there are weird, flaky issues, depending on the server, depending on the setup that  

#### [0:46:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2790) |  happened, where sometimes we can render it

properly, sometimes we can't. And that's something that's sometimes a bit hard to judge if that's happening or not. The other thing is if it's not a JavaScript-based site where you're pulling in the content with JavaScript, this kind of duplicate detection can still happen, even if the HTML content is different. So what tends to happen on our side  

#### [0:47:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2820) |  is we have multiple levels of trying

to understand when there is duplicate content on a site. And one is when we look at the page's content directly and we kind of see, well, this page has this content. This page has different content. We should treat them as separate pages. The other thing is kind of a broader predictive approach that we have where we look at the URL structure of a website where we see, well, in the past, when we've looked at URLs that look like this, we've seen they have the same content as URLs  

#### [0:47:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2850) |  like this. And then we'll essentially learn

that pattern and say, URLs that look like this are the same as URLs that look like this. Even without looking at the individual URLs, we can then sometimes say, well, we'll save ourselves some crawling and indexing and just focus on these assumed or very likely duplication cases. And I have seen that happen with things like cities.  

#### [0:48:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2880) |  I have seen that happen with things

like, I don't know, automobiles is another one where we saw that happen, where essentially our systems recognized that what you specify as a city name is something that is not so relevant for the actual URLs. And usually we learn that kind of pattern when a site provides a lot of the same content with alternate names. So with an event site--  

#### [0:48:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2910) |  I don't know if this is the

case for your website. With an event site, it could happen that you take one city and you take the city that is maybe, I don't know, one kilometer away. And the events pages that you show there are exactly the same because the same events are relevant for both of those places. And you take a city maybe five kilometers away and you show exactly the same events again. And from our side, that could easily end up in a situation  

#### [0:49:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2940) |  where we say, well, we checked 10

event URLs and this parameter that looks like a city name is actually irrelevant because we checked 10 of them and it showed the same content. And that's something where our systems can then say, well, maybe the city name overall is irrelevant. We can just ignore it. So what I would try to do in a case like this is to see if you have this kind of situation where you have  

#### [0:49:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=2970) |  strong overlaps of content and to try

to find ways to limit that as much as possible. And that could be by using something like a rel canonical on the page and saying, well, this small city that is right outside the big city outside the canonical near the bigger city, because it shows exactly the same content. So that really every URL that we crawl on your website and index, we can see, well, this URL and its content  

#### [0:50:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=3000) |  are unique. And it's important for us

to keep all of these URLs indexed or we see clear information that this URL you know is supposed to be the same as this other one. You have maybe set up a redirect or you have a rel canonical set up there. And we can just focus on those main URLs and still understand that this city aspect there is critical for your individual pages. So that's kind of the approach I would take here.  

#### [0:50:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=3030) |  I'll also pass this on to the

team internally so that they have an example of something where we're picking it up wrong and we could be doing a better job there. But I'd still try to see if there is something that you can do on your site, as well, to try to limit this kind of overlap with multiple URLs. ROBB YOUNG: John, can I just say-- or offer-- if you want to stick the URL into the chat, I have quite a lot of experience with a geographic event sites,  

#### [0:51:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=3060) |  as you know. So we can have

a look at it, as well. JOHN MUELLER: Of course. Yeah. ROBB YOUNG: Ruchit, if you want to just paste it in. RUCHIT PATEL: I just dropped the URL in the chat. And one more thing that I have noticed that there is some pattern that the smaller number of cities like, I mean, in length, like four or five character length  

#### [0:51:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=3090) |  cities are affected the most instead of

the larger name cities. JOHN MUELLER: Yeah. That's something that could also be happening there in that-- I mean, our systems, when they try to understand the duplication across URL patterns, it sometimes picks up weird things there. So especially if you mentioned shorter city names and longer  

#### [0:52:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=3120) |  city names, I could imagine a case

where you have abbreviations, as well, for the same city. And then we might learn, well, this shorter version is the same as this longer version, therefore we can do that more likely with shorter URLs. But I don't know. Maybe some examples, if you could post them in the chat, then I can pick those up as well and forward them on to your team, or Robb has some tips.  

#### [0:52:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=3150) |  He's been working with event sites since

forever. RUCHIT PATEL: Sure. I will drop some things. JOHN MUELLER: Cool. Let me just see what else we have. So I have a bit more time. We can hang around after the recording stops, as well. Let's see. One question here is someone has a bunch of XML sitemap files. And two of them have a status of can't fetch. Sitemap couldn't be read. The files are valid and why don't they work?  

#### [0:53:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=3180) |  It's hard to say. That's something where

it would be useful to have specific example URLs. And one way you can give us that information is maybe in the Help forum, so to post some of the sitemap URLs that are working and some that are not working. The folks in the Help forums can escalate individual issues, as well, so that Googlers can take a look and see if there's something on our side  

#### [0:53:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=3210) |  that's maybe blocking that, as well. I

have occasionally seen these kind of cases where you have a bunch of sitemap files and some of them work and some of them don't. Sometimes they're just technical quirks on the server side that are happening. Sometimes they're weird things on our side that are happening. So it's sometimes useful to look at the specifics. One thing I have seen is sometimes just changing the URL of the sitemap file kind of resets Google's  

#### [0:54:00](https://www.youtube.com/watch?v=8UBSEiO87GM&t=3240) |  opinion of that URL and gives us

a chance to take a look at the kind of new site map URL. So that might be kind of a tricky workaround. Cool. OK. Let me take a break here with the recording and I'll stick around for more, as well. So if any of you want to hang out a little bit longer or chat off the record, you're welcome to stay. If you're watching this on YouTube, thank you for watching. And if you'd like to join one of these events in the future,  

#### [0:54:30](https://www.youtube.com/watch?v=8UBSEiO87GM&t=3270) |  make sure to watch out for the

event listing on our YouTube page or subscribe to the calendar that we have on the Search Developer site. All right. With that, I wish you all a great weekend. And see you all maybe next time.  