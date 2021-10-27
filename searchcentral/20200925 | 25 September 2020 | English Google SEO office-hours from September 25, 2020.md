[![English Google SEO office-hours from September 25, 2020](https://i.ytimg.com/vi/aEE8wfC-7gA/hqdefault.jpg)](https://www.youtube.com/watch?v=aEE8wfC-7gA)

## English Google SEO office-hours from September 25, 2020

This is a recording of the Google SEO office-hours hangout from September 25, 2020. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Watch out for new sessions, and add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



Feel free to join us - we welcome webmasters of all levels!



Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=0) |  JOHN MUELLER: All right. Welcome everyone to

today's Webmaster Central office hours Hangout. My name is John Mueller. I'm a Search Advocate at Google. And part of what we do is these kind of office hours and events where people can come to us and ask us questions around the website, around search, and we try to find answers or figure out what's happening, to some extent. A bunch of things were submitted already on the YouTube listing for the event.  

#### [0:00:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=30) |  But if any of you want to

get started with your first question, you're welcome to jump on in. JEMMY K: Hi, John. JOHN MUELLER: Hi. JEMMY K: Hey. I've got a question regarding rankings. So I've written an article that ranked number one the day after it was posted, and it was with a feature snippet. But then, it dropped to, like, page six within about 24 or more hours and a decent amount of search volume for the keyword. And then I verified the SERP on Google  

#### [0:01:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=60) |  search console third-party SEO tools, and then

asked several people to verify the position. And does the ranking or the feature snippet mean anything, or is it just Google indexing doing this work? And can I assume that, at least, a post is eligible for the feature snippet position or the top ranking eventually, providing everything remains the same? Thank you. JOHN MUELLER: It's hard to say.  

#### [0:01:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=90) |  So it can happen that a piece

of content appears very visibly in search in the beginning, and then it settles down into a lower state. It can also happen that a piece of content starts off kind of low and, over time, gets a higher ranking. And both of those situations are, from our point of view, essentially normal. So that's something where I wouldn't necessarily say there is a technical issue on your website, or there is something problematic with those pages.  

#### [0:02:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=120) |  It's essentially just how ranking works. And

it can happen that it goes back up-- that, over time, we see, actually, this is a fantastic article, we should be showing it more. It can happen that we show it as a featured snippet. It can also be that we show it as a featured snippet even if it's not ranking first. So all of these things are possibilities. One thing that I would generally recommend  

#### [0:02:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=150) |  if you care about the visibility of

this article, don't just kind of take it and say, oh, I'll leave it as it is and hope that something changes in the future. But rather, if you care about it, then continue working on it, and continue trying to make it better, so that when we look at it again, we see, well, there's a lot of new information here-- there is something really useful here that we do need to show more visibly. JEMMY K: Thank you so much.  

#### [0:03:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=180) |  CHRISTIAN KUNZ: John, good morning. JOHN MUELLER:

Hi. CHRISTIAN KUNZ: Yeah, I've submitted a question regarding a website with a separate mobile version and three language versions. The problem is that, in the desktop search, Google shows mobile URLs for the most important keywords and, despite alternate and canonical set correctly in the Google search console, no impressions for the mobile URLs  

#### [0:03:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=210) |  are shown. In addition to this, for

some German searches, English URLs show up in the search and href lang is implemented for every language. So I'm wondering, what could be the problem here? JOHN MUELLER: OK. I cheated. I looked at your issue beforehand, just so that the people who are watching this don't think I have a crystal ball.  

#### [0:04:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=240) |  And essentially, what is happening in your

situation-- you have the mobile version with separate mobile URLs and the different language versions. And you have different language versions for both desktop and for mobile. And what is happening is, your site is switched over to mobile-first indexing. So the primary version that we index for your pages is the mobile version, so kind of the m dot version of the pages--  

#### [0:04:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=270) |  I think you called them mobile in

the subdirectory or something-- it doesn't matter, m dot or something else in between. So this is the primary version that we index. In general, when we recognize there is a desktop and a mobile version, we will swap out URLs in the search results appropriately. However, also, when we recognize there are different language versions-- so using href lang, for example--  

#### [0:05:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=300) |  then that's something where we would also

swap out the URL. So what is happening here is, we swap out the URLs for the different language version in your case, and we don't swap out the URLs for the desktop, mobile version. So what is happening there is basically, in Search Console, we count it as an impression for the primary version of the page, and we swap out the language version and we show that to the user. And that's the mobile German version,  

#### [0:05:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=330) |  or the mobile English version. And that's

essentially what is happening there. From talking with the mobile-first indexing and the internationalization team, they don't feel this is critical enough to kind of really work on and say, oh, we need to change our algorithms to figure this out better. But rather what they recommend is that, if you have a separate mobile version  

#### [0:06:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=360) |  and a separate desktop version, that you

redirect on both of those. So if a mobile version goes to the desktop page, redirect to the mobile version. I think you're doing that. But also if a desktop user goes to mobile page, then redirect to the desktop version. So if you add that redirect, then even if we show the mobile version in the search results, people will go to the appropriate version of the site. CHRISTIAN KUNZ: OK. Thank you. And regarding the language version--  

#### [0:06:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=390) |  so showing the English version for German

searches-- can we do something about that? JOHN MUELLER: I think that's really tricky. I didn't see that, in particular, for your site. But I think, I suspect, that's for the brand name, or the city name, that you have there. Now, I think that's really tricky there because it's hard for us to recognize that this query is in German or in English because you're searching for that specific name, and it's the same name  

#### [0:07:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=420) |  in English and in German. So we

probably primarily think, oh, the user settings are in German, we'll try to show the German page. But it could also be that the user is searching in English. We can't completely tell just based on a query. CHRISTIAN KUNZ: OK. Thanks a lot, John. JOHN MUELLER: Sure. MAYANK PARMAR: Hey, John. JOHN MUELLER: Hi. MAYANK PARMAR: Starting September 22, our new articles have stopped indexing  

#### [0:07:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=450) |  and all articles are disappearing. When I

check on inspection tool, it says, duplicate [INAUDIBLE] error and Google has [INAUDIBLE].. So we are-- our traffic has [INAUDIBLE].. JOHN MUELLER: Now, I don't know where specifically that would be coming from. So that's something where it would be useful to maybe have a forum thread with the details.  

#### [0:08:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=480) |  MAYANK PARMAR: Yeah, I [INAUDIBLE] to you.

JOHN MUELLER: OK, cool. If you can drop the link to the forum thread in the comments here, I can take a look afterwards as well. MAYANK PARMAR: Yeah, thanks. JOHN MUELLER: Sure. PRAVEEN SHARMA: Hey. Hi John. JOHN MUELLER: Hi. PRAVEEN SHARMA: Hi. I need your advice on something, digital images. So we got a lot of images on our website. And our pages load quite quickly than normal networks or faster networks. But if the user is coming from a slower network, say 3G network.  

#### [0:08:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=510) |  So the page takes a lot of

time to fully load something, somewhere around five to six seconds. So we're trying to fix this issue. And one of the solutions the tech team suggested that what if we just don't show those images to the people who are coming from slower network. So I need your advice. Can this impact our SEO? JOHN MUELLER: Not-- probably not directly. Because Google Bot will probably be crawling with something  

#### [0:09:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=540) |  that you recognize as a kind of

higher bandwidth connection. But what you can do in a case like this, instead of trying to recognize the user as coming from different locations, use something like, oh-- I forgot what the name is. When you have different image files for the same image. I think a source set is how you implement it. That might be something that you could implement there. So that instead of not showing the image at all,  

#### [0:09:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=570) |  you just have a very low resolution

version of that image. I'm not completely sure how you would implement that just on the kind of the speed of the connection. But that might be something to look into there. PRAVEEN SHARMA: Sure. I'll try. JOHN MUELLER: Yeah. But also, if you really recognize that these users can't use the full content of your pages, then showing them a limited version is fine.  

#### [0:10:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=600) |  Yeah. Maybe that. PRAVEEN SHARMA: Yeah. Images

are just part of the content, just to show like-- the text part is there. Just to show that the content is rich and, because we go to games website and we just have part of them. JOHN MUELLER: Yeah I-- I think if the images are critical for your pages, then I would find a way to show them in any case. Even if you have to show like, lower resolution or do something fancy that people click to get the full version.  

#### [0:10:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=630) |  If images are just decorative on your

website, then that's something I wouldn't worry about. But, in particular, if people go to your pages and they go there because of the screenshots that you show, or because of the images that you show, then it shouldn't be that those images are just not shown. PRAVEEN SHARMA: Sure. Thank you. JOHN MUELLER: Sure. I think Dejan, you had a question. Oh, we can't hear you.  

#### [0:11:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=660) |  I don't know if your microphone is

off. I can't hear you. OK. Maybe you can type it into the chat or we can try again later. OK. ROBB YOUNG: John, can I just follow up on that page speed image question? Is it still the case that in Insights, one of the things it suggests for images is using the next gen format.  

#### [0:11:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=690) |  And yet, until recently-- I haven't looked

recently-- but they weren't really supported by a lot of the browsers. It seemed to be that you were suggesting one thing, but browser said, no, we don't like those. Is that still the case? Or has that been updated? JOHN MUELLER: I don't know which formats are currently listed there. So I think one of the newer formats was WebP. And I believe that's supported everywhere.  

#### [0:12:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=720) |  But if you use-- oh, I forgot

what the name was. I think it's the source set for images. If you specify different image files there with different formats, then the browser can pick the format that works for them. So even if you have like, one version with WebP, and the other version as a GIF or JPEG or something, then the browser will pick which one works best for them. So that means for things like modern browsers,  

#### [0:12:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=750) |  like Chrome, where we would pick up

the speed, we'd be able to use the fast images. And if the browser has to use one of the fallback versions, then that still works. ROBB YOUNG: OK. JOHN MUELLER: But it also means that you have to kind of generate your images in different formats inside, so it's a little bit extra work. Some CMS's probably make that a little bit easier. ROBB YOUNG: OK. JOHN MUELLER: Cool. OK let me run through some of the submitted questions.  

#### [0:13:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=780) |  And we'll definitely have more time afterwards

if people want to hang around, ask more questions. Let's see. Let's say we have a good article that we want to publish on several high traffic websites. So we send the article to the owners of those sites asking them to publish it. Afterwards, 10 out of 30 websites publish our articles. But we also noticed some unwanted websites have taken over the article and published it as well. So how does Google treat the back link  

#### [0:13:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=810) |  from the unwanted websites? Can this back

link harm us? Should we disavow it? Or is it considered a natural behavior in the eyes of Google and we should just keep the link and the article there too? So, in general, we recommend not doing guest posting for link building. So that's something where if you're really only kind of sending this article out and trying to get it to other sites to get a link from that, that's something that, if done on a high scale,  

#### [0:14:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=840) |  is something that the Webspam team would

look at and say that, this is not a collection of natural links. And maybe algorithmically or manually, we have to take action there. So that's kind of the first thing there. In general, though, if you do have one article on multiple websites, then we will see that article on those multiple websites. And we will see those links there. And if these are on websites that you don't kind of want  

![](https://i.ytimg.com/vi/aEE8wfC-7gA/hq1.jpg)



#### [0:14:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=870) |  that to be published on, then it's

kind of up to you to take action there. And that can be using the disavow tool if you want. That might be contacting the site owner and asking them to take it down or using the DMCA process. That's essentially up to you. The second part of the question is, how does Google treat the 10 out of 30 webmasters that decided to publish the same article? Is it considered duplicate content? Yes. Of course it is duplicate content, because it's the same article.  

#### [0:15:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=900) |  So, essentially, what would happen in the

search results is, we would recognize that it's the same article being published multiple times. And we would try to pick one of them to show in the search results. And it can be that we show a version on one other person's website. It can be that we show the version from your website. It's not guaranteed that we would always show the version from your website. So if you syndicate your content, then you kind of have to live with the kind of aspect  

#### [0:15:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=930) |  of, well, maybe Google will show a

syndicated version instead of your version. And, essentially, the way to prevent that from happening is not to syndicate your content. When auditing links for my client's websites, I see some naked URLs that are pointing to valuable resources on the site. How does Google treat such links when there's no anchor text? So I think by naked URL, it's basically just someone is linking with the URL as the anchor text.  

#### [0:16:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=960) |  So, in that situation, we see that

URL as the anchor text. From what I understand, our systems do try to recognize this and say, well, this is just a URL that is linked. It's not that there is a valuable anchor here. So we can take this into account as a link, but we can't really use that anchor text for anything in particular. So, from that point of view, it's a normal link.  

#### [0:16:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=990) |  But we don't have any context there.

Yes? MIHAI APERGHIS: Can Google kind of get context for like, the text the round at the link maybe if it doesn't have any? JOHN MUELLER: Sure. But that's more kind of secondary. Like, that really strong piece of context from the anchor text that's missing in that case. And then, like small things around the side, that does help us a little bit. But really, the kind of the primary aspect of that link  

#### [0:17:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1020) |  is kind of gone. And, I mean,

usually that doesn't matter. It's not that it counts against your website in any way. It's just, well, for this particular link, we don't really know what the context is. MIHAI APERGHIS: All right. I'm asking since the majority of organic links, so to speak, usually use either branded anchor text, like the brand name of that website. Or something like the URL or nothing--  

#### [0:17:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1050) |  specific no keyword, specific keywords being used.

So, since that is the case, since the majority of the links that point to a website aren't really specific around the keywords that are related to the website, does Google use the content around or the topic of the article where that link is or things like that? JOHN MUELLER: Yeah. I mean, that's something we do definitely take into account.  

#### [0:18:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1080) |  But it's very secondary. So, it's not--

I mean, there's no kind of like, value of strength for the context there. But I'd say it's like, that anchor text is really obvious and we can collect that. And we can look at that overall. And kind of the context of the linking pages is something, well, it's like, we also need to think about at some point. But the anchor text is really kind of the primary thing. MIHAI APERGHIS: Right. But, it's also the anchor text that kind of also points you  

#### [0:18:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1110) |  in cases where that link is doesn't

seem to be very organic. Because it's very like, that-- JOHN MUELLER: Sometimes. Yeah. Sometimes. Yeah. MIHAI APERGHIS: OK. JOHN MUELLER: I recently changed the layout, look, and feel of my blog and moved away from WordPress and now using Hugo's static sites and generator for publishing my post. Does the change in layout impact my ranking and search results  

#### [0:19:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1140) |  on this. Side note, there's no change

in content and the URL structure. It's still the same as before. So, changing like the layout of your pages can affect your search results. So, this is something that some people work on actively as well with regards to on page SEO. So things like figuring out how to use titles properly on a page, how to do internal linking properly, how to provide more context for the article itself--  

#### [0:19:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1170) |  all of this can definitely affect SEO.

So just because the kind of the primary content, like the blog post that you have, and the URLs themselves don't change, doesn't mean that there's nothing else around all of that that search engines won't be able to pick up on. So, it can definitely affect SEO. And it can be a good thing. It can be a bad thing. So it's not that you need to avoid making these changes. But rather, when you make these changes, make sure to double-check that you're kind of doing everything  

#### [0:20:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1200) |  really well. My blog traffic is 99%

from desktop, and I get very rare traffic from mobile and tablet. But sometimes I see the mobile usability issues like clickable elements too close. Should I be concerned more about that? Will it put a negative impact on my site's ranking or search results for desktop? I optimized my website for mobile and it's responsive as well. So, I think this is one of those aspects where sometimes  

#### [0:20:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1230) |  our systems see fluctuations in how we

process the pages. And that can result in things like a mobile usability report in Search Console saying, oh, I found a number of pages that are not really mobile-friendly. And, if you check those pages manually and you see that they are actually mobile-friendly, then I would just leave it at that. That's basically our systems, for whatever reason, at one point, were not able to render your pages properly.  

#### [0:21:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1260) |  So we wanted to let you know

about that ahead of time. If you see that the majority of your pages are recognized as not being mobile-friendly, then I would definitely take a look at that. If it's just individual pages every now and then, that's perfectly fine. With regards to mobile-friendliness in general, with regards to a site that is mostly visible on the desktop search results, the mobile-friendliness is a factor that we use in mobile search results, particularly. It's not something that we currently use  

#### [0:21:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1290) |  for the desktop search result. So if,

for example, your site were actively not mobile-friendly, if like, you never worked on mobile-friendliness and it's a table based layout and you have to zoom in and everything is really hard to use on mobile, but nobody is searching for your site on mobile, then that's also kind of fine. The thing to watch out for there, though, is, it might just be that nobody is using your site on mobile because it's not mobile-friendly.  

#### [0:22:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1320) |  So, that's one of the things, especially

in the beginning, as everything around mobile came up, even on the search console side, the search console team was like, well, we don't have to make our site mobile-friendly because nobody's using search console on their mobile phone. And of course, if you can't use it on your mobile phone, then nobody will use it. So, you kind of have to avoid running into that situation. I've been a webmaster and SEO professional since 2001.  

#### [0:22:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1350) |  I have a hypothesis that I am

hoping you can confirm or deny. Uh-oh. I'm wondering if referral traffic from organic back links and referring domains play a part in the legitimacy, trust, and authority when it comes to the PageRank algorithm. It seems to me that a back link that has never clicked on would be less useful than one that does. Therefore, a back link that is actually used by visitors may be counted or regarded with higher trust or authority.  

#### [0:23:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1380) |  And since the purpose of the back

link is to drive traffic, if some back links never drive traffic by way of referrals, why would they matter? Yeah. I think this is an interesting question. It comes up every now and then. Essentially, in our algorithms, we don't look at that. So it's not that we kind of monitor what people actively click on and see how the traffic goes back and forth.  

#### [0:23:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1410) |  There are lots of reasons for traffic

to go to a website that is completely unrelated to SEO. So from that point of view, it's something where, I think, as a site owner, it's useful to think about where your traffic is coming from. And if you see a lot of your traffic is coming from some particular sites, then that might be a sign that maybe there's something you can do together with that website to make it work even better. Maybe that's a sign you could work with other websites to make it better there. Maybe it's a sign that there's a large overlap of audience  

#### [0:24:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1440) |  between those two websites. But just because

there is traffic coming, or there's no traffic coming from individual links, doesn't play a role in our algorithms. In particular, with regards to PageRank, PageRank is really kind of a simple algorithm that is just complicated because of the scale of the internet. But that's something where we try to essentially just focus on the link. So it's not that there's anything special also  

#### [0:24:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1470) |  kind of flowing into that. So, from

that point of view, if you have links to your site that nobody's clicking on, that can be perfectly fine. It can also be something where you might say, well, like, why do I have these links from these sites if nobody's actually using them? Then maybe like, that link is just hard to find. Or maybe there's kind of a mismatch with the audiences there. But essentially, that doesn't play into the SEO side of things.  

#### [0:25:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1500) |  If my original site is faster than

the AMP version, do you still recommend having an AMP version? That's an interesting question. So, I think if you have a site that is faster than the AMP version, then to me, that would point at the AMP version being kind of a suboptimal version. Because in general, AMP is really optimized for really fast delivery, especially  

#### [0:25:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1530) |  if you're using the AMP cache. If

something is being served from the cache directly, then, from my point of view, unless you're doing something really weird with those AMP pages, that should be really fast. That said, there are multiple reasons to use AMP. Speed is definitely one of them. If speed is the only reason that you're using AMP pages, then of course, feel free to just use your own version. That's something where it's really up to you.  

#### [0:26:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1560) |  Other people, some might decide to just

say, well, I will just use the AMP version and make my AMP version the fastest one possible so that you don't have to work on both of them. That's also a way to kind of deal with that. But, in general, like, if you really are only doing AMP for speed, and your normal responsive pages are just as fast or faster than your AMP versions, then that seems like one place where you could optimize.  

#### [0:26:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1590) |  With regards to some of the features

where we do show AMP pages, that's something where we recently announced with, I think the page experience ranking factor, that we would start taking into account pages that are not AMP as well, provided they kind of reach that same threshold with regards to the core web vitals. So, at some point in the future-- it's not the case at the moment for things like the top stories  

#### [0:27:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1620) |  feature-- if your pages are really fast

and they kind of reach the core web vital factors, then we would also show them there, even if they're not AMP versions. What is Google's vision of the future of its search engine? There have been a few changes in recent times with all the extra boxes in the search results page that make me wonder what they're driving towards. They seem to me to be aiming at or preparing something new  

#### [0:27:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1650) |  for the future. Wow. I don't know

what the big future vision is with regards to Search. It feels like we could probably have a long session just speculating on different topics. I don't really know what I can tell you here. I think the important part to keep in mind is that we make changes all the time. And we try a lot of things out, as I think pretty much every website should do.  

#### [0:28:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1680) |  And that's something where if you try

a lot of things out, if you try some risky things along the way as well, then you'll see which things work out and which things don't work out so well. So for example, for last year, I think-- I don't know. We did over 100,000 tests and experiments with different things over the course of a year. And it led to something like, I don't know, 3,500 changes in the search results. So, that's something where, it's like,  

#### [0:28:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1710) |  you say you've seen a few changes

in recent times. There's lots of changes happening all the time. Some of those changes are very small that just like, small pixels shift around or the colors slightly change. Some of them are fairly visible. And we have to keep testing. We have to keep improving things, because people online, they expect even better things all the time. It's not the case that you can just keep one thing stable and it'll be relevant forever.  

#### [0:29:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1740) |  How does Google treat blogs that are

built on expired domains? Is it a recommended practice? So in general, I wouldn't recommend using expired domains as a kind of an SEO strategy. That seems very risky. Sometimes these domains, on the one hand, can be quite expensive. And sometimes you might be getting a lot of extra cruft with that expired domain. So we do try to recognize when a new site is being built on an expired domain and we try to ignore as much of the past  

![](https://i.ytimg.com/vi/aEE8wfC-7gA/hq2.jpg)



#### [0:29:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1770) |  as possible. However, if the old version

of the site that used to be there on the previous owner was something that was really problematic, for example, they built a lot of links in ways that were against our webmaster guidelines, then that's something that can still be associated with your website. And that's something that you'd probably need to clean up before you can really be sure that you're starting with a clean slate.  

#### [0:30:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1800) |  So my recommendation there would be, as

much as possible, if you really want to dive all in on a domain name, then investigate its past so that you kind of know what you're getting involved in. And if you're doing this just to kind of try something risky and you don't need to rely on it for your business, then feel free to try things out. But if your business really relies on it, then investigate the past. And make sure that you understand  

#### [0:30:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1830) |  what it is that you will need

to clean up at some point to get back to a clean slate and whether that's worth it for you overall. ROBB YOUNG: John, do you differentiate between domains that have actually expired, though, and just someone taking over another domain? Like, it has to have expired at the registrar. JOHN MUELLER: That's sometimes really hard to tell because of the way that the registrars work  

#### [0:31:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1860) |  and what information they provide publicly. So

that's-- I mean, what we try to recognize is, there's essentially a new site here. And we also try to recognize situations where people take an expired domain, they go to archive that org, and they download the old version of the site and they put it back up and they add five new links along the way and try to make it look like, oh, this is just, like, you know, I forgot to renew my domain  

#### [0:31:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1890) |  and it's all the same now. That's--

I don't know. It's been in practice since forever. But these are things that we try to recognize from a webspam point of view, and also just generally from kind of a general ranking point of view to make sure that, as much as possible, people can reuse domain names. But also that kind of the cruft and the extra value that was associated with the old domain is kind of neutralized as much as possible.  

#### [0:32:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1920) |  Sometimes we can't do that completely. Like,

if there are really lots of problematic links there, then sometimes that's just kind of like the last-- ROBB YOUNG: But you're trying to neutralize problems or neutralize benefits? Because in the real world, if you own, I don't know, a restaurant chain and you buy another restaurant chain, and you then have more sites. You might want to close some and just merge them, fire half the staff, and get economy to scale.  

#### [0:32:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1950) |  Is that not-- why is that not

the case in the online world where you still have all of those links coming in which are now pointing to your new business, and offer the same value if there's a genuine takeover? You're diminishing the value in the business you've just purchased for no reason. JOHN MUELLER: It's-- it's hard. It's hard. I mean, a lot of these--  

#### [0:33:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=1980) |  so what we do try to recognize

is when things are essentially kind of just being taken over and the business continues to run normally, where, essentially, it's just kind of like a change of ownership situation, but it's essentially the same business. That's something we do try to say, well, that seems like a reasonable change. That can happen. But, a lot of times, the reuse of expired domains  

#### [0:33:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2010) |  is essentially one business goes bankrupt and

the business stands still for a while. And then someone else goes there and says, oh, actually, I'm Robb's business and I'm just the new owner kind of thing, treat me as if I were still a legitimate business. ROBB YOUNG: But you were to-- but isn't that right, though? If you do that in the real world, the roads going into your business and the signs that used to be there and the previous PR you had,  

#### [0:34:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2040) |  you can take over the bankrupt businesses.

That happens all the time to utilize their assets. JOHN MUELLER: I don't know. I don't know. Yeah. It's-- ROBB YOUNG: Otherwise, every bankrupt business is worthless. And there'd be no-- there would be no benefit in buying bankrupt assets. JOHN MUELLER: It's tricky. ROBB YOUNG: I wasn't planning on doing this, by the way.  

#### [0:34:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2070) |  It just feels like a real world

situation is usually the best way to judge an online situation. Would you do it in the real world? No, then probably don't do it. JOHN MUELLER: Yeah. Yeah. I think it's also something that we just see at scale a lot of times, that people go off and it's like, oh, I can buy 1,000 expired domain names. And I'll look up the links to those domain names ahead of time and I'll just buy them all and redirect them to my site.  

#### [0:35:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2100) |  That's something where, from our point of

view, it's not that your site has gained any value, any more relevance because of that. It's really just, well you're taking a lot of expired domains and then redirecting them to your site. And that's something we shouldn't really kind of treat as being a part of your site. ROBB YOUNG: OK. JOHN MUELLER: Yeah.  

#### [0:35:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2130) |  I can see both sides. But it's

something where the legitimate side, where this matches what would happen in the offline world and your business should be able to do this, that's something that is significantly rarer than the other side where people just take expired domain names and try to reuse them. ROBB YOUNG: Right because the barriers to entry in the online world are almost zero, where it takes some effort to go buy a bankrupt business.  

#### [0:36:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2160) |  JOHN MUELLER: Yeah. Yeah. Probably. ROBB YOUNG:

--business in the real world. JOHN MUELLER: Yeah. Yeah. And this is something that sometimes has really weird effects in that people will buy expired domain names from conferences where it's like, I don't know, some scientific conference 2014, and you go to the website and they're selling, I don't know, fitness equipment now. And you're like, OK.  

#### [0:36:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2190) |  Why? Why did you essentially act like

you're at a conference, but you're selling something completely different now? ROBB YOUNG: Yeah but that would be the same in the real world if I bought a restaurant chain and turned it into a gym, I wouldn't expect to still serve restaurant customers. JOHN MUELLER: Yeah. But I mean, in that case, you would be like, well, actually it's a gym now. And you can't kind of build off of the reputation you have as a restaurant. I mean, I'm sure there are ways you could twist that and say like, well,  

#### [0:37:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2220) |  actually this is the gym for the

old restaurant. I don't know. OK. Wow. Yeah. I think with expired domain names, it feels like one of those topics that there so many different aspects there. But you know. OK. Let's see. In my search console, I am noticing a continuous decrement in mobile-friendly pages. When I inspect the pages in mobile-friendly testing tool,  

#### [0:37:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2250) |  all of my pages were mobile-friendly. I

haven't changed anything on my site. What's the reason behind the continuous decline in mobile-friendly pages on my website? What should I do to overcome that? So one of the things to keep in mind is that the Aggregate Reports in Search Console, like the Mobile-Friendly Report, the Structured Data Report, I think the Speed Report as well, they're based on a part of your website. So it's not that these are all of the index  

#### [0:38:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2280) |  pages from your website or that it's

your whole website that's listed there, it's just a sample of the pages from your website. And it can happen that that sample becomes smaller. And that doesn't mean that you have fewer pages that are mobile-friendly. It's just in that report, we're just showing fewer pages in that report. And what I would recommend doing there is continue to double check your pages individually so that you're sure that things are OK.  

#### [0:38:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2310) |  But if you don't see a rise

in errors in that report, then I would just assume that, well, for this sample, we've determined that these are all mobile-friendly. And we might be showing you a smaller sample of pages there, but that's perfectly fine. So in short, this is not something that you need to fix in any particular way. Just make sure that like, that sample is all OK. That things are OK there. How deep is the bond between Top Stories and Google News'  

#### [0:39:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2340) |  old algorithm? I see Top Story being

tested in the News tab on Search. I don't know what you mean with how deep is the bond between these different elements. We do have different elements that we show in the Search results. And I could imagine that we would show some of these across the News and Search and maybe also in Google News as well. So from that point of view, it's not  

#### [0:39:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2370) |  that there's a deep connection between all

of these things or anything that can be quantified. It's just for practical reasons, if we recognize that one UI element works really well for users, maybe we'll use it in other places. So that's something that can happen. Our website was affected by a hack and we've been dealing with it on and off for two weeks. Things got cleared out and when they pop back up, we're in the clear now from the hack.  

#### [0:40:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2400) |  But I've noticed our ranking has dropped

for some of our strongest keywords during all of this. What are some best practices I should be following to get our site to be viewed as reputable by Google again quickly? Do I need to resubmit the site map since one of the hacks messed with ours? I repaired with it, but I'm not sure if I should resubmit. I would definitely resubmit the site map, because that's just generally something that helps us to understand your site better. And if you're using a common CMS to generate that site map file,  

#### [0:40:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2430) |  then probably it's already been resubmitted automatically.

So probably that's already OK. In general, if you're faced with an situation where someone is actively hacking your website for a longer period of time, and I think two to three weeks or so, is something I would quantify as a longer period of time, then it would be normal for our algorithms to be a little bit confused about what it is that you're trying to host on your website  

#### [0:41:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2460) |  and what you want to rank for.

So that's something where I can definitely see our algorithm saying, well, we don't really know what we should be showing this website for. And probably during that time, the ranking for the keywords that you do care about goes down. It's possible that maybe ranking for keywords that you don't care about goes up. In particular, if people add things to your website. So, if a hacker is using your site to not redirect to other people's sites, but rather to host kind of hacked content,  

#### [0:41:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2490) |  then that's possible that our systems will

be like, on the one hand, maybe we'll show you for, I don't know, athletic shoes because that's what the hacker placed there. And then when we recognize that it's actually hacked content, we'll show you for less fewer of these searches overall. In general, the important thing that you really, really need to do is make sure that you've cleaned up the whole hack completely, that you've done things  

#### [0:42:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2520) |  like remove any owners that the hacker

has added to Search Console or to Analytics, so that you're really making sure that you're starting with a really clean slate. Make sure that the security issues that were used to get in are really cleaned up. And then clean out all of the hacked content. And that includes checking things like the server control files, where sometimes there are redirects that are placed there that are only visible to search engines.  

#### [0:42:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2550) |  Also double checking all of the index

pages, of course, so that you're sure that all of those are cleaned up. And I would also double check your server logs to make sure that there's really no traffic going to pages that you don't want to have indexed. For example, one thing we sometimes see with hacked sites is that they're used for phishing attacks. And phishing content is often not indexed by Google, because maybe it has a no index on there.  

#### [0:43:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2580) |  But if people are using your site

to host phishing content that they use for Gmail, for example, then that's something you might not be seeing directly in your search results. So all of these things, I would definitely clean out. And once it's all cleaned out, once you resubmitted your site map file, that's something where I would say it's probably a matter of a few weeks or so for things to settle down again. And it's frustrating to be hacked like this.  

#### [0:43:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2610) |  It's something that kind of really pulls

things down and is annoying and it's hard to clean up sometimes, but it just takes a bit of time for things to settle back down again. But, with all of these things, if you do clean up the hack content on your site, it will settle back down. It's not something where Google will hold a grudge and say, oh, you were hacked once. Therefore, we can not trust your website ever again.  

![](https://i.ytimg.com/vi/aEE8wfC-7gA/hq3.jpg)



#### [0:44:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2640) |  Lots of websites get hacked. That's something

that unfortunately happens. BILL ALLEN: John, I've got a question about site colon searches. JOHN MUELLER: OK. BILL ALLEN: So we're trying to look at the performance of a particular product category-- a set of product category pages-- that would include pagination, would include some facets.  

#### [0:44:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2670) |  So maybe along with the category, you

have a selection for brands. And you have a lot of those indexed. Dozens, maybe hundreds. And if you were to choose to place a no index on those pages, would you be sending Google the signal to then not index the products that exist on those pages? Well, what would happen to the products that would be listed on those pages?  

#### [0:45:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2700) |  JOHN MUELLER: So you have a category

page and for your product-- BILL ALLEN: You've got a category page, you're got pagination. Google's indexing all of those pages. Pagination, some facets. But somebody's concerned that you have too many of these category pages indexed, knowing that these category pages have the products listed. And if you were to no index those pages, what would be the end result of those products being indexed?  

#### [0:45:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2730) |  JOHN MUELLER: Yeah. OK. So what would

usually happen, if you have category pages and pagination on those category pages, and you, for example, no index everything from page two onwards, what would usually happen is we would start to drop those pages from our index. And when we drop those pages from our index, we would essentially drop those links as well.  

#### [0:46:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2760) |  So probably if you put a no

index on page two, then it will be less likely that we would even go to page three to figure out what is even shown there. So that's kind of one aspect there. It's possible that we'd still notice some of the links on page two. But kind of everything linked further back would be a lot harder to find. With regards to e-commerce sites, sometimes that doesn't matter so much because a lot of times,  

#### [0:46:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2790) |  products are in different categories or you

have products that are cross-linked with kind of related product links. So, what I would recommend doing there is, first, double checking to see that we can still find all of your products. But if we ignore the no index pages. Often you can do that with a local crawler, something like Screaming Frog, or some online crawler to kind of test your site. And just make sure that with the no index in place,  

#### [0:47:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2820) |  we can still find all of your

products. If we can't find your products with the no index in place, then that's definitely something to watch out for. BILL ALLEN: Perfect. Thank you. JOHN MUELLER: In general, our recommendation, though, is to allow the indexing of the paginated category pages and only disallow the indexing of things like facets. So if you have different sort filters or kind of different filters for sizes or kind of sub-attributes of those products,  

#### [0:47:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2850) |  that's something I would no index. But

the main category pages, I would allow indexing of those. BILL ALLEN: So you wouldn't see value in, again, simplified-- I'm not throwing out all of our facets for Google to crawl, but just a select few. So for example, the category in brand combinations, would you recommend not allowing Google to go to those? JOHN MUELLER: So it can be really tricky with e-commerce  

#### [0:48:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2880) |  because, on the one hand, it's about

crawling to find those pages. On the other hand, these can also be valuable landing pages. So if, in any case, you're saying, this is a valuable landing page for me-- it's like, someone is searching for men's athletic through shoes in blu and this is a really popular query for your site, then keeping that facet available for indexing makes a lot of sense. People are searching for it explicitly, you have a good landing page for it, definitely keep that.  

#### [0:48:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2910) |  On the other hand, if this is

just really just for usability. If like, nobody is searching for this particular facet, and you just have it for usability there, then that's something I would disallow indexing of. BILL ALLEN: OK. Thank you. HASIT RUPAREL: In addition to that, John, we can also do a rel canonical tag, right? Instead of just no indexing basically? JOHN MUELLER: Yeah. I think you can do-- you can do pretty much both of those.  

#### [0:49:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2940) |  From my point of view, I think

it makes more sense to use no index for those kind of things because that gives you a clearer mental model. What we often see is people use rel canonical on the pages that they don't want to have indexed. And from our point of view, we will look at that and say, oh, you're saying these pages are equivalent. And you can probably pick one or the other to show in the index. And that's not really what you're saying. You're kind of saying, well, just don't index this page.  

#### [0:49:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=2970) |  So for content that's not really identical,

I would just use a no index and not the rel canonical. And I'm sure this will lead to lots of long discussions online now. BILL ALLEN: All right. Thanks. JOHN MUELLER: Sure. DEJAN TOTEFF: John, can I try? Can you hear me? JOHN MUELLER: Sure. Yes. DEJAN TOTEFF: Sorry for the previous problems. I have a question that maybe has been asked many times.  

#### [0:50:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=3000) |  It's about cloaking. We have a dynamic

website, which is not indexed at all. And the cache text version is completely empty, which means that-- I think that maybe I can take the HTML with [INAUDIBLE] or something like that, and just see if Google Bot or any other bot is coming, I can serve this page.  

#### [0:50:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=3030) |  And for any other, if it's not

Google Bot, I can just give the dynamic and actual version of the website. How bad is that? JOHN MUELLER: That's perfectly fine. So we call that either server side rendering, or dynamic serving, I think we call that, depending on how you have that set up. And that's perfectly acceptable as an approach. One thing I would just caution against is, just because the cache page is empty  

#### [0:51:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=3060) |  doesn't mean that Google is not able

to index the content. So sometimes what usually happens with JavaScript based sites is, the cached page shows the HTML version of the page that we have. And if the JavaScript can't run on the URLs that we use for the cache page, then it doesn't show any content. But you can double check that by taking some of the content and just explicitly searching for that in Google.  

#### [0:51:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=3090) |  And if you see those pages showing

up, then that's a sign we can find the content. And I wouldn't worry about the cached page in that situation. DEJAN TOTEFF: No. It was just like, like indicated what is happening. Because it's obvious something is wrong. I was just curious, can we apply this. And I just want to safeguard that we are not cloaking, like accused of cloaking.  

#### [0:52:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=3120) |  Because if we do that, we will

do it with [INAUDIBLE] like every 24 hours and it won't be fully dynamic and every manual check on the web page will see, OK, this is not what is the life. Thank you very much, John. JOHN MUELLER: We have that documented. So if you need to point something-- for whoever makes decisions on your website, we have documentation on that in the Search Developer documentation on how you can set that up with JavaScript.  

#### [0:52:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=3150) |  So we would definitely not see that

as cloaking because the content that's shown in the end is the same. It's just the delivery method is slightly different. What we would consider cloaking is if the content is very different. When you go to the page and show shoes and Google Bot sees, I don't know, something completely different, like vacation photos or something. That would be considered cloaking. DEJAN TOTEFF: OK. What about if there's some--  

#### [0:53:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=3180) |  the content depends on the app request,

that's the bot waits-- how long it waits for-- is it wait for network idle? JOHN MUELLER: We don't have a specific time that we wait there. We essentially try to see until nothing more changes on a page. And that's-- on the one hand, we have some hard timeouts. On the other hand, we try to figure out when things stop changing. The difficulty with waiting is that we use  

#### [0:53:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=3210) |  a lot of caching on our side.

And we don't run Chrome with kind of the same speed set up as a normal user would. So you can't really compare how Google Bot would wait for that page to how a user would see it. The inspect URL tool in Search Console gives you kind of an idea of what Google would show. DEJAN TOTEFF: Thanks very much, John, for your answer. JOHN MUELLER: Sure. DEJAN TOTEFF: I will leave because I'm technically  

#### [0:54:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=3240) |  at work. So bye all. JOHN MUELLER:

Yeah. DEJAN TOTEFF: Thank you. JOHN MUELLER: Thanks. DEJAN TOTEFF: Bye. JOHN MUELLER: All right. Any more questions before we pause the recording? ROBB YOUNG: I have a question. JOHN MUELLER: OK. ROBB YOUNG: With our new site, we have the ability now to have dates booked. So there's live inventory of dates. So in our meta information, that's  

#### [0:54:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=3270) |  now sometimes pulling through saying, next available

on the 1st of October. And that looks nice in the search results because people can probably improve click through for people that are interested. But, the problem is, obviously, of course, if that stays there until the 2nd of October, and Google doesn't index it again in the meantime, then it looks like an expired search result and it's probably worse. Have you seen this sort of thing before?  

#### [0:55:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=3300) |  And how any other people deal with

that problem, where there's dynamic content and therefore might be dynamic meta information. And so how do people deal with that? Or can we just ask you to index it every 20 minutes? JOHN MUELLER: Every 20 minutes. I don't know. Yeah. I think that's easy to do on a small website, and really challenging on a large website. So we see that a lot--  

#### [0:55:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=3330) |  or I don't know, a lot. We

sometimes see that with e-commerce websites, for example, if they go through and they change your prices significantly in a short term. Like, I don't know, for Black Friday, suddenly all the prices are 10% lower, then that's something where we would need to essentially recrawl all of the products to see those changes. And for that, we don't have any special method available there. It's really in the site map file, you have to tell us, this page has changed.  

#### [0:56:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=3360) |  And then we may go off and

recrawl that page. And sometimes we recrawl it fairly quickly after you tell us about it. Sometimes we recrawl it a month later. So, that's something where on the one hand, you can help us by optimizing what you allow us to crawl. So, having a really clean URL structure where we don't end up kind of getting lost in variations of URLs helps a lot. Having a fast server so that we can crawl a lot helps a lot.  

#### [0:56:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=3390) |  But it doesn't guarantee that we will

pick up all changes immediately. If you're seeing that this happens regularly, or you make these changes fairly quickly, like, you have something that's not happening next month, but rather it's like, always a couple of days ahead of things, then you could also use the data no snippet attribute in HTML where you say, well, actually, this particular thing is something that is very dynamic. I don't want you to show it in the snippet.  

#### [0:57:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=3420) |  And then, you kind of don't have

the advantage of being there with kind of a date in the near future. But you also don't have the disadvantage if it's still indexed at some point later on. And you can use that for dates, for anything on the page. You can use that for prices, for something that's shown in the structure date. For anything that you don't want to have shown in the snippet, you can let us know about it like that. ROBB YOUNG: And it is the markup for dates that would help if we really wanted it to be?  

#### [0:57:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=3450) |  JOHN MUELLER: There is some markup for

dates, but it's mostly based on kind of what you want to provide as the article date. So if you're writing a blog post or an article and you have like, today's date as a change on there-- ROBB YOUNG: Or event dates or ticket sellers. JOHN MUELLER: Yeah. So for events, you could probably use the event markup. Maybe that would work, if you have specific dates where you say, this is taking place on this date at that time.  

#### [0:58:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=3480) |  ROBB YOUNG: We're pulling the dates through

via an API for live ticketing feeds. So it is accurate. So we can do that. JOHN MUELLER: Yeah. That sounds a good thing. Yeah. ROBB YOUNG: OK. JOHN MUELLER: And with the event markup, if we recognize that, then we can show that kind of as a rich result under the result. Sometimes we also show it in the sidebar, where if you're searching for a specific event, then in the sidebar, it'll be like, this is happening at that date, and then it links to your pages.  

#### [0:58:30](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=3510) |  ROBB YOUNG: [INAUDIBLE] events because they happen

every week. There's a cooking class every week or a skydive every week. And yet, they kind of are specific because they're always happening on a certain date. JOHN MUELLER: Yeah. ROBB YOUNG: All right. JOHN MUELLER: Sure. ROBB YOUNG: Thanks. JOHN MUELLER: OK. All right. Maybe we can take a break here. I'll pause the recording. If any of you want to stick around, you're welcome to stay a bit longer. Thank you all for joining.  

#### [0:59:00](https://www.youtube.com/watch?v=aEE8wfC-7gA&t=3540) |  I hope you all found this useful.

Lots of good questions here. So thanks for asking all of that. And hopefully, I'll see you again in one of the future Office Hours Hangouts. Bye everyone. SEBASTIAN SCHOENER: Bye bye. Thank you.  