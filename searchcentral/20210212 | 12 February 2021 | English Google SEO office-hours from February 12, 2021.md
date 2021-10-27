[![English Google SEO office-hours from February 12, 2021](https://i.ytimg.com/vi/f4z96B0-JYE/hqdefault.jpg)](https://www.youtube.com/watch?v=f4z96B0-JYE)

## English Google SEO office-hours from February 12, 2021

This is a recording of the Google SEO office-hours hangout from February 12, 2021. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Find out more at https://developers.google.com/search/events/join-office-hours



Feel free to join us - we welcome webmasters of all levels!



#### [0:00:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=0) |  JOHN MUELLER: All right. Welcome, everyone, to

today's Google Webmaster SEO Office Hours Hangout. My name is John Mueller. I am a search advocate at Google in Switzerland. And part of what we do are these office hour Hangouts where people can join in and ask their questions around search and their website. As always, a bunch of stuff was submitted directly on YouTube already so we can go through some of that. But if any of you want to get started with a first question, like Barry, feel free to jump on in.  

#### [0:00:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=30) |  AUDIENCE: Sure. Thank you very much. First,

it's no longer the Webmaster Central. It's the Search Central Office Hours Hangout. I know it's hard since you've been saying that for, what, 20 years or maybe 100 years in SEO years. In any event, passage indexing was launched Wednesday night Pacific or Wednesday afternoon Pacific time. And there's a lot of confusion in industry. Just want one clarification. I know Danny Sullivan said it's going to look exactly like any other snippet. It's not going to look like a feature snippet.  

#### [0:01:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=60) |  It's not going to look like a

weird snippet even though you guys had an image of a snippet looking differently in the tweets about it. One, confirm that. And then two, are you going to-- are the [INAUDIBLE] ranking snippets using scroll-to-text that are in some feature snippets and other elements? Those two questions. JOHN MUELLER: I don't know about either of them. So I think like with the first question,  

#### [0:01:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=90) |  I don't really know how that will

be shown. And it's hard for me to tell because I never see it here in Switzerland. Danny might know more there. He's been a bit more involved with that directly. With regards to the scroll to snippet part, I believe that's something that we're just still experimenting with, so not necessarily that it will automatically use that or that it's like always use that or not.  

#### [0:02:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=120) |  But my understanding is that's still something

where we're not 100% sure how that will be embedded in the long run. AUDIENCE: For specifically passage ranking or for any general snippet? JOHN MUELLER: Just in general. Just in general. Yeah. AUDIENCE: Do you know if they're being tested for-- I mean would there be a difference before testing that in passive ranking versus any other snippet? JOHN MUELLER: I don't think there would necessarily be a big difference there. I did see some tweets from people saying,  

#### [0:02:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=150) |  oh, we're starting to see this more

in Search Console since you launched this. I don't know if that's more of a coincidence or if that's directly tied to that or not. AUDIENCE: OK. In summary, you don't know. JOHN MUELLER: I don't know. Yes. AUDIENCE: All right. Thank you. JOHN MUELLER: And not even it depends. Yeah. All right. Other questions? Maybe I'll know some answers along the way.  

#### [0:03:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=180) |  Anything else to get started with? AUDIENCE:

I can ask a quick one if that's OK. Hey, John. JOHN MUELLER: OK. Go for it. AUDIENCE: So this is related to the unavailable after robots value or tag. So we're working with a classified site where that tag would definitely be helpful in order to stop Google from keep trying those 404 expired ad pages.  

#### [0:03:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=210) |  It's just that we're concerned that a

lot of users are able to refresh their ad so in that case it won't expire at the date it's supposed to expire. So they might refresh it for another week or even more. And they might keep refreshing it if they choose to. Is the unavailable after option still a good one? Will updating make Google understand that the data keeps moving forward into the future?  

#### [0:04:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=240) |  JOHN MUELLER: Yeah. I mean, if we

refresh that page for crawling and indexing, then we would see the updated unavailable after meta tag. So that would work. It's not like you can only specify it once and then it's cemented like that. If we recrawl that page and see the new tag, we'll take that into account. So I guess the situation would be kind of tricky if you set the table after meta tag for tomorrow, for instance,  

#### [0:04:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=270) |  and we just recrawl it the day

after tomorrow. Then we would have dropped it potentially in the meantime. AUDIENCE: So is there any way to make sure that doesn't happen? I mean would using the site map and the last modified date help if we use the [INAUDIBLE] after that? JOHN MUELLER: OK. Sure. I mean, it's something where you could change the last modification date and say it changed now. It's not guaranteed that we would recrawl the page right  

#### [0:05:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=300) |  away, but it's one of those signals

you can tell us like this page has changed. Double check to make sure that you're not missing anything. AUDIENCE: But what happens if I said the unavailable tag after tag for tomorrow, let's say, and the crawler knows that from tomorrow going forward it should not crawl the page anymore. And let's say a week from now, the user decides to reactivate their ad.  

#### [0:05:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=330) |  Will the last modification date in the

site map make Google understand, well, maybe I should recrawl that page because it seems it's-- JOHN MUELLER: No. I mean the unavailable after meta tag doesn't say not to recrawl it afterwards. It's more that the site owner is saying this will probably be a no index or 404 afterwards. So it's more that Google can drop it out a little bit faster without needing to recrawl it. It's not a sign that we would stop refreshing that page.  

#### [0:06:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=360) |  AUDIENCE: OK. But it will still help

with the overall crawl budget, making Google kind of slow down on recrawling these guys? OK. JOHN MUELLER: Yeah. Yeah. AUDIENCE: John, regarding this, I just wanted to understand if we are using unavailable after tag in our seasonal pages, like some Christmas day page [? flags, ?] on that case, does Google have the same page indexed even after unavailable after tag or this will drop it  

#### [0:06:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=390) |  from index also? JOHN MUELLER: The idea

is that we would drop it even without needing to recrawl it. So our assumption is that if you have the unavailable after meta tag set to a date, that that page is no longer available afterwards and that it will be no index or 404 afterwards. So our systems-- I think the way that I understood it is our systems are essentially going to treat it as if there is a no index on there after that  

#### [0:07:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=420) |  date, even if we don't recrawl it

by then. AUDIENCE: So it means that it will appear for all the time when it is not season will be no indexed? JOHN MUELLER: Yeah. I mean, it's something where if you have a seasonal page that has a limited lifetime, then you can definitely use that, especially to let us know about things that expire quickly, to let us know about the long tail content  

#### [0:07:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=450) |  that we don't recrawl that often. That's

really useful, like for instance classified sites, for example, I think is a really good example for that. Seasonal content itself, like if you have one Christmas page, usually that's going to be very prominent within your site during that season so we're going to recrawl that quite a bit. And if you add a no index to that page at some point, we'll pick that up fairly quickly. So usually for that kind of seasonal content,  

#### [0:08:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=480) |  the unavailable after meta tag isn't really

critical but really for the content that we don't recall that frequently. AUDIENCE: OK. Thanks. AUDIENCE: Hi, John. JOHN MUELLER: Hi. AUDIENCE: I have a question about robots file. We see that some of our clients that don't have any robots file on their site. Now if a site does not have any robots file, does it effect its ranking, or indexing, or crawling?  

#### [0:08:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=510) |  JOHN MUELLER: No. It's totally optional to

have a robots text file. If there is no robots text file, there are no restrictions for robots text essentially so that's perfectly fine setup. AUDIENCE: And the next question is about a blog post category and blog post tag. The post category and post tag-- does it have any impact on ranking of the blog post? JOHN MUELLER: Not necessarily. So it's not that we would try to recognize tags on a page,  

#### [0:09:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=540) |  but these are links. And potentially they

go to kind of a category page or tag page. And that would be another page that we could index or that we could use to pick up links to your articles. So it's not that there is any inherent kind of magic around tags. It's just it creates more links and more pages within your site. AUDIENCE: Thank you. JOHN MUELLER: OK. Let me run through some of the submitted questions. We'll definitely have more time for your live questions  

#### [0:09:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=570) |  as well. And if you have any

comments or, I don't know, more questions to the questions that we go through, feel free to jump on in. A large site has legacy code that generates parameters on interlinks. These parameters are unique for every session. If the site serves Googlebot these pages with the parameters stripped, would that be considered cloaking? Technically, yes. We would consider that to be cloaking. The search engineering team would say, oh,  

#### [0:10:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=600) |  this is cloaking, like you shouldn't do

it. From a practical point of view, it would not be problematic. So it's not that the web spam team will take manual action on this. It's essentially something where you're kind of providing an optimization for Googlebot that you're not providing for users. And it's more a matter of you're making it kind of hard for yourself to maintain your site because you always have to look at both versions. And if you never see the version that Googlebot sees,  

#### [0:10:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=630) |  it's very easy to run into a

situation where suddenly Googlebot gets error pages or Googlebot gets bad links. And every time you check that with maybe a local crawler, you don't see those broken links. So that's something from kind of a best practices point of view. I try to avoid that. But it's not that you're going to get flagged or get a manual action because of that. If a niche news portal is moved to a subdomain of a larger general news portal, can its visibility  

#### [0:11:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=660) |  be affected by the main domain? So

for example, before the migration, both sites ranked for top positions on a lot of topics. Now many times only the main domain portal is able to reach top positions and the first page while the subdomain has dropped considerably. So any time you do this kind of migration where you're kind of splitting a site into separate parts or you're taking multiple sites and combining them into one main site, I would expect to see fluctuations  

#### [0:11:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=690) |  with regards to ranking in general, temporary

fluctuations, but also long term fluctuations. And it can be that the overall result is something that is much stronger than the individual ones before. It can also be that the overall result is kind of a mixed bag of things and causes problems in the long run. So that's something where it's really hard to determine ahead of time what the actual effect will be when you go into the situation of merging  

#### [0:12:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=720) |  or splitting sites. So from a theoretical

point of view, yes, it can happen like this. It is something where you can put in time and get some help from experts and more experienced folks to see should you expect problems or will this probably be OK. But it is different from the general site move situation where you just move one site to a different domain.  

#### [0:12:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=750) |  You're taking everything from one site and

just passing it on to a new one. As soon as you merge or split things, then we essentially have to reprocess things overall and try to come up with a bigger new picture for that site. Would adding an audio version of a page's content to help with search in any way other than the obvious accessibility improvement? As far as I know, we don't do anything with audio versions of content.  

#### [0:13:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=780) |  We also wouldn't see that as duplicate

content. So it's not that you have to avoid that. I mean duplicate content itself isn't really something you really have to avoid, but even if you wanted to avoid the situation that you're suddenly ranking for the same things with different pieces of content, the audio version is something that we, as far as I know, would not even process separately. So at most, we might see that as a video, a piece of video content, and show that also with a video snippet.  

#### [0:13:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=810) |  But essentially, it wouldn't help or detract

from a page's overall ranking. AUDIENCE: John, wouldn't it show as-- if they've embedded an audio file for example to play on the page, doesn't that do anything? I mean if you've got a page that literally just has text verses a page that has text, pictures, video, audio, and therefore provides more variety and depth, is that not adding anything to the quality of that page  

#### [0:14:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=840) |  to have an audio file? JOHN MUELLER:

I don't think we would look at that and say, oh, there are different kinds of content here. It's a better page because of that. It might be that there are indirect effects. Like if users find this page more useful and they recommend it more, that's something that could have an effect. But it's not the case that we look at the types of content on a page and say, oh, two types versus five types like the one with five types is better.  

![](https://i.ytimg.com/vi/f4z96B0-JYE/hq1.jpg)



#### [0:14:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=870) |  I think it's a bit different with

video and images in that images and video themselves can rank independently. In image search or in video search, you can also have the same piece of content be visible in those other surfaces. But for audio, we don't really have a separate, I don't know, audio search where that page could also rank. I think the closest that could come  

#### [0:15:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=900) |  there is the podcast search that we

have or the podcast kind of one box thing. But that's really tied to kind of the podcast content type where you have a feed of podcast information and we can kind of index it like that. But just having audio on a page by itself, I don't think that would change anything automatically in our systems. AUDIENCE: OK.  

#### [0:15:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=930) |  JOHN MUELLER: OK. The website has a

small [INAUDIBLE].. Sorry. Go ahead. AUDIENCE: Oh. Hi. Sorry. I have a question about mobile first indexing. So I just did a-- I'm working on a site that just went through a site move so I actually spoke to you about it a couple weeks ago. But basically, it's just change of domain name so it didn't change the URLs or site architecture. So the old site was being indexed by mobile Googlebot. But now it's being indexed by desktop. And it hasn't switched over yet so it's only been a week  

#### [0:16:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=960) |  actually since it launched. So I know

it can take a bit of time. But I was wondering if there is maybe a sandbox effect because the domain itself was pre-existing and it was kind of a parked domain, but it was a site that was probably previously indexed by Google. It's currently, according to the crawl stats report in Search Console, it's currently being called 96% of the time by smartphone Googlebot. So I'm wondering like how long I guess  

#### [0:16:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=990) |  might we expect for it to switch

over to mobile first or if there is potentially a sandbox effect because it was previously a site being indexed by a desktop. JOHN MUELLER: So I wouldn't worry about the mobile first part for something like that because we kind of have the timeline set for switching everything over to mobile first anyway. So that will happen in, I don't know  

#### [0:17:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1020) |  what is it, in March or April.

I don't know what timeline we had there. So that'll happen anyway. But with regards to moving to a previously existing domain where there was parked content, you can definitely see some temporary effect there. Not so much in terms of a sandbox effect or something like that but more in terms of if we've always seen a no index page on this site for the longest time, then probably we're going to assume that it's still  

#### [0:17:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1050) |  no index for a while. And you

might see kind of this, I don't know, moment where for-- I don't know. I've seen it happen for maybe a week or two, maybe up to three weeks, where it's just our systems assume that this is still a parked site and essentially treat the new content that is there as being parked as well. And then it either doesn't get indexed at all or its ranks kind of really badly in the beginning.  

#### [0:18:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1080) |  And then at some point, our systems

go, oh, it's no longer parked and essentially it just pops back in. AUDIENCE: OK. Yeah. I think it's starting to-- we are starting to see some recovery with rankings and stuff that had dropped in the last week. But yeah. I was just wondering if there was any sort of negative impact from being indexed by desktop given that we're using a responsive design and it's the same architecture as the previous site. JOHN MUELLER: No.  

#### [0:18:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1110) |  That definitely wouldn't be the case. So

it's not that there is any kind of ranking, I don't know, penalty or anything holding a site back. If it's being called with a mobile or with a desktop crawler, that's really just a technical thing on our side. Are we calling with mobile or desktop? And then essentially the same content goes into the index. AUDIENCE: OK. Yeah. Because I'm seeing something that I'm not sure if it's related which is I'm getting some AMP warnings for domain mismatch.  

#### [0:19:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1140) |  And it seems to be like sometimes

the old version-- the new version of the site has the AMP page indexed but the old page hasn't been recalled yet since the move. So I guess maybe the redirect hasn't been spotted yet. And I was wondering if that is because of primarily the crawling is being done by desktop. JOHN MUELLER: I don't think that should be a problem because if we understand the connection between your kind of legacy pages  

#### [0:19:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1170) |  and the AMP version of the page,

then we would crawl those appropriately. So that's something where I could imagine you might see a temporary effect until all of that settles down a little bit where maybe we have the AMP URL somewhere linked. And we go off and crawl it with a desktop crawler initially. And then we realize, oh, we have to use mobile because it's AMP. Then we would pick that up. But that's something that I would expect should settle down fairly quickly. I don't know order of, I don't know,  

#### [0:20:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1200) |  one two, three weeks, something around that

range. AUDIENCE: OK. And it wouldn't be necessary to, say, like redirect AMP pages from the old to the new? I would redirect those too. I would redirect those. AUDIENCE: Redirect those. OK. JOHN MUELLER: Also images, anything that was essentially hosted on the old domain. AUDIENCE: OK. We've done them for all the other types of pages. I'll add the AMP ones. Thank you very much. JOHN MUELLER: Sure.  

#### [0:20:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1230) |  All right. AUDIENCE: Hi, John. JOHN MUELLER:

Let me just run through some more of the submitted questions first because we always seem to run short of time for them. I'll definitely have more time for live questions as well. The website has a small snippet of client side JavaScript that updates the URL with the History API. For example, the server response shows /page. And the browser address bar shows /page-updated. No resources named page updated is seen in the network resources.  

#### [0:21:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1260) |  Would Google see the updated URL? Which

address would the content be indexed under? So if we see during the loading of a page that the History API changes the URL, then we would try to classify that as a redirect. And we would try to take the destination URL or the new URL that you provide there and try to use that for indexing for the next time. So essentially, what would happen, the first time we would see /page. If it does, the History API swapping with page-updated.  

#### [0:21:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1290) |  The next time, we will try to

crawl /page-updated and use that as the version essentially for indexing. I mean, it's not 100% certain because it's essentially a question of canonicalization. But we would see that as a redirect. And redirects are a pretty strong sign for canonicalization. The important part here is that /page-updated is actually a page that we can crawl so it shouldn't be the case that you  

#### [0:22:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1320) |  swap out the URL for something that

is not existent if you go there directly. So that's kind of the main thing to watch out for. I've written/outsourced about 600 articles in a year. All were made more or less in the same way. Still some rank and show in Google and some are not in Google at all, even those that are more than six years old. Then I manually need to go through all those 600 articles, and make some changes, and update them. And then they start showing up in search.  

#### [0:22:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1350) |  What should I do here, essentially? So

I think the main thing to keep in mind is we don't guarantee indexing of all pages on every website. In fact, for most websites, we index just a small portion of the total website. So if you have 600 articles on your website, it can be completely normal that we go off and index maybe 100, maybe 500, maybe somewhere in between. It would be unexpected, from my point of view,  

#### [0:23:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1380) |  if we would always index all pages

on all websites, because, I don't know, there's a limit to the number of pages that we can index in our system so we have to try to prioritize a little bit. And by changing pages on your website, it's certainly possible that you trigger something where Google starts seeing again that these pages have changed and goes off and crawls them and sees, well, is there something important that we need to index here. And then maybe it'll index it. Maybe it'll be indexed for a while.  

#### [0:23:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1410) |  Maybe it will drop out again after

a couple of weeks or a couple of months. It really depends. It's not something where there is a guarantee that we go off and crawl and index all of the changed pages or that there's a guarantee of having kind of an old evergreen page will rank high, anything like that. So especially if you're talking about a large number of pieces of content on your site, then that's something where it's worthwhile to figure out a system on your own where you can work  

#### [0:24:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1440) |  to determine the quality of these pages

and to work to try to improve those pages over time so that Google also is able to go in there and say, well, these are really fantastic pages. We do need to crawl and index more of these pages. And then over time, that will pick up again. Let's see. Core Web Vitals question. We know that all user interaction pages or URLs are considered. My question is does Core Web Vitals  

#### [0:24:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1470) |  need to meet the 75th percentile across

all devices or mobile only? The doc says segmented across mobile and desktop devices but it's not a clear interpretation, at least not for me. What does that mean? I don't know. Pedro, I think you're here. I don't understand your question. AUDIENCE: Yes, I am. My question is that the word segment across devices, does it mean that the ranking boost or the algorithmic factor is going to be factored only to the segmented device  

#### [0:25:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1500) |  or you have to omit across all

devices to receive the boost? For example, if you meet Core Web Vitals on mobile only, you can only get them mobile only or do you get them desktop too? JOHN MUELLER: I don't know. I don't think we have clearly defined exactly how the ranking boost would happen there. But essentially, we would track these per device. And we'd be able to take them into account per device.  

#### [0:25:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1530) |  So I would assume it would not

be the case that if your desktop pages are really fast and your mobile pages are slow that we would still count that as being fast overall. My assumption is that we would try to separate that out. But I don't know what the final mix will be in terms of do you just have to meet the bar or is there kind of a flexible range that you can reach to see the effects there  

#### [0:26:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1560) |  with regards to ranking. I think for

the badging, it's a little bit easier. And I hope we have some more information on that in the near future. But especially when it comes to ranking, it's something where it's oftentimes not something that is just on or off. AUDIENCE: Yeah. Thank you. JOHN MUELLER: Sure. Let's see. A really long question. I have this website with subdirectories on it for Korean and Japanese.  

#### [0:26:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1590) |  And I think the question goes into

a little bit hreflang. Do you need hreflang, how the links between these versions work, that kind of thing, and whether these different language versions need to be in line. So I'm super simplifying, sorry. But I think, in general, when you have pages in significantly different languages-- so in this case,  

#### [0:27:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1620) |  it sounds like it's Swedish content, Korean

content, and Japanese content-- that's something where we would be able to rank those pages individually. And it's something where if we see someone searching in Japanese, we're not going to show them the Swedish version of your page because it's pretty obvious that they're searching in Japanese and that your Japanese pages would fit that query best. So that's something where, probably to a large extent, in a situation like this,  

#### [0:27:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1650) |  you would not even need hreflang because

it would not be the case that suddenly accidentally your Swedish pages rank for someone searching in Japanese. So I think that makes it a little bit easier in terms of the whole hreflang setup and what exactly you need to do there. But this general situation of if the queries are really split by language, you don't really  

#### [0:28:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1680) |  need to focus on hreflang there. It

would be different, for example, if you had something like a global brand where someone in searching in Japanese would search with exactly the same word as they would search in Swedish. And then it might be hard for our systems to understand this user in Japan who is searching for this one name, do they mean the original Swedish site? Do they mean the local Japanese site? It's hard for us to understand. And in a case like that, we would  

#### [0:28:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1710) |  use hreflang to swap out the appropriate

country language version for that user. AUDIENCE: So I have a follow-up, John. JOHN MUELLER: Sure. AUDIENCE: In the case where you have indicated hreflang appropriately through XML site maps, and specifically related to English speaking countries, what should one do if you see in Search Console that Google is not getting it right? So we've indicated canonicals on both UK and US pages, for example.  

![](https://i.ytimg.com/vi/f4z96B0-JYE/hq2.jpg)



#### [0:29:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1740) |  We've marked our site maps up with

hreflang and we're still seeing Search Console say, hey, we've actually selected the UK version in the context of the US account. JOHN MUELLER: Yeah. So that gets a little bit complicated, because there are other aspects that come into play there. So the first thing I would do there is try to reproduce that and see if that's actually happening  

#### [0:29:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1770) |  like that, because Search Console tries to

do something really smart that really throws things-- I don't know, makes things more complicated in Search Console itself in that it tries to show the canonical version. And with hreflang, in cases where the same content is available for multiple countries, we can still recognize that actually this is duplicate content. We'll index one version. And we'll use hreflang to show the appropriate local URL when  

#### [0:30:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1800) |  someone is searching. So that's something you

might see in English where you have the same content in English. In German, it's really common that this happens. So that's something we see quite a bit here in Europe. And essentially, what happens is in Search Console in the URL inspection tool, if you check the, I don't know, let's say the UK version, if you check that one,  

#### [0:30:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1830) |  you see the canonical shows the US

version. That's kind of what's happening there in that we understand it's the same content. We still see the hreflang there so we can swap the URLs out in the search results. But we will index it as the US version. And the tricky part is, in Search Console, we report on the canonicals themselves. So in the search results, we might show the UK version because we know their equivalent. We can swap out the URLs. But in the performance report, we will track that as the US version in Search Console.  

#### [0:31:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1860) |  So if you just look at the

performance report, it's like, oh, the UK version is never shown. But if you try those search results out yourself, then you see that actually the UK URL is shown. But since the content is exactly the same from an indexing point of view, we're kind of simplifying that. AUDIENCE: So two quick follow-ups to that. One is I think a pretty good indicator for mismatch  

#### [0:31:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1890) |  would be looking at a GS specific

Search Console account looking at the traffic makeup between different GOs. Right. So let's say, for example, I look at Canada. And I see that 50% of their traffic is coming from the UK. That would pretty clearly indicate that there's some mismatch. Is that appropriate? JOHN MUELLER: Yeah. But then you might still be seeing that effect that we're showing the right URLs but we're tracking it with the wrong ones. So that is like super complicated in cases like that,  

#### [0:32:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1920) |  because if we have like Canada and

US versions and we pick one of those as canonical, then we will track even the Canadian URLs when we show them as the American URLs in Search Console. Yeah. It's like you pull out all your hair and you start scratching your head. And it gets really crazy there. From our point of view, it's something where the reporting in Search Console  

#### [0:32:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1950) |  is confusing in cases like that. And

you might say it's wrong because it's reporting on the canonical but not reporting on the one that is actually shown. But from an indexing, from a ranking point of view, it should be working out fine. If you need to have it differently, then essentially what you need to do is make sure that these versions of these pages are unique enough so that we don't run into a situation where we say, oh, we will make it easier for you  

#### [0:33:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=1980) |  and just pick one version to index.

If we clearly understand these are absolutely unique pages, we should index them separately, then we'll show them separately. We'll index them separately. We'll have separate canonicals. AUDIENCE: Cool. Any guidance on enough? JOHN MUELLER: There is no number or anything like that. But yeah. I think it's always tricky in a case like that because, theoretically,  

#### [0:33:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2010) |  from a ranking point of view, it's

OK. It's just everything around tracking is super complicated. AUDIENCE: Hey John. Hi. This is my Mohammad Mehdi Abbas from India. Actually, I have just [INAUDIBLE] industry. And I have two questions to you. First one is regarding domain name-- sorry, domain and subdirectory. Suppose I have a domain called example.com and I have created four subdomain like example.one.com  

#### [0:34:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2040) |  like [INAUDIBLE]. So if I host the

blog for all four subdomains on the name, how will it be from the SEO perspective? JOHN MUELLER: You can do that. I think it's something where some people use subdomains. Some people use subdirectories. If you ask the SEO industry overall, you will get lots of arguments in either direction.  

#### [0:34:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2070) |  So I mean, technically, you can do

that. From Google's point of view, you can use subdomains or subdirectories. That's perfectly fine. I would, first of all, try to think about what possibilities you have available from a technical point of view on your side. So if your hoster makes it really hard to put WordPress into a subdirectory and it has to be on a subdomain, for example, then maybe that's kind of the first way to get  

#### [0:35:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2100) |  started. And then at some point later

on, you can decide, oh, I know enough or I can move to a different hoster and I can set my system up slightly differently. But that's kind of the thing where, from a first step, I would look more at the possibilities that you have available and then really learn from making a website, learn from interacting with search. And over time, you'll see maybe it makes sense  

#### [0:35:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2130) |  to put it into a subdirectory. Maybe

it's fine like this. Maybe I want to move to a whole different domain. Maybe I want to focus on something different with my website. You'll kind of grow into that a little bit more. AUDIENCE: Second question is related to backlinks. I have heard a lot about backlinks that Google consider quality backlinks. When it comes to quality, what exactly does you mean for quality backlings and how Google analyzes between [INAUDIBLE] and backlinks?  

#### [0:36:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2160) |  JOHN MUELLER: So my recommendation, I think

especially if you're getting started, is not to focus on backlinks, because it's very easy to get stuck into the situation of, like you said, Google wants quality backlinks or Google wants natural backlinks. Therefore I will make my backlinks look like quality or I will make my unnatural backlinks look like they're natural. And it's very easy to spend a lot of time focusing on that.  

#### [0:36:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2190) |  So that's something where, from my point

of view, I would focus on your site first and really work to build that up really strongly first. And then over time, you'll see like maybe there are opportunities where you can mention your site with other people with regards to advertising perhaps, with regards to other ways where you can create something really fantastic and point that out to other people and say, look at this cool stuff that I did.  

#### [0:37:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2220) |  And then they link to your page

because they think, oh, this is really neat. And essentially, when it comes to links, Google's point of view is that these should be things that are not organized by you, that are not paid for by you, that are not created by you but rather they should be naturally people who say, well, this is really cool. I really like that. Similar to how if you make a website, you probably have seen lots of other sites where you say this is cool.  

#### [0:37:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2250) |  I will link to that. I will

refer to that because it's something useful for my users. AUDIENCE: Thank you. JOHN MUELLER: Sure. Let me run through some more submitted questions. And we'll definitely have more time for you all as well. Can I prevent a section of my page from being used in the meta description? Google is choosing a component within the product information as a description of a page, which reads really odd in the search results. Yes.  

#### [0:38:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2280) |  You can do something there. Namely, we

have a data no snippet http attribute that you can apply to some HTML elements within your pages. And everything that is within these HTML elements would not be shown in the snippet. So we call the description that you see there the snippet in the search results page. Oftentimes, it's based on the description meta tag. Sometimes it's also based on some of the content on the page itself.  

#### [0:38:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2310) |  The important part is also that the

description that we show as well as the title, they can vary for individual pages depending on what someone is searching for. So if you do a site query for your pages, for example, you might see one title in one description whereas if you search the way that you see in the performance report in Search Console, you might see that users see something slightly different. So before jumping off and trying to block certain parts of your pages from appearing in this snippet,  

#### [0:39:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2340) |  I would double check to make sure

that this is actually something that people are seeing and not just something that only you are seeing while you're trying to diagnose your pages. Will the .gq CCTLV get AdSense approval? I have no idea. I don't know anything about this, Tielly. I don't know about the AdSense approval process. So I have no idea. How to increase organic traffic on new blogs.  

#### [0:39:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2370) |  I don't think I have a one

sentence answer for that. What I would recommend doing maybe is checking out the SEO starter guides. We have one that we've worked on for quite a while. There are some from some of the bigger other companies out there as well that cover a lot of the things that you can think about with regards to CEO. And there's definitely no single meta tag that you can put on your pages and suddenly you  

#### [0:40:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2400) |  get a lot of traffic to your

site but rather you really kind of have to think about this whole thing for a longer period of time. How can a team technically improve SEO when the URL was previously associated with malware? The URL was changed to get away from that but still running into issues with visibility, having our content show on Google News. So I don't know about Google News.  

#### [0:40:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2430) |  But essentially, malware is something that usually

someone who hacked your website added to your pages and provided some bad content for people when they go to your pages that maybe it infects them with a virus or something like that. And when it comes to malware, that's something that is generally flagged by the Safe Browsing-- Safe Browsing? I don't know.  

#### [0:41:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2460) |  Is it Safe Browsing? Safe Browsing team,

I think, and would be shown as a warning in the search results and in the browser as well. And essentially, when that is resolved-- so you can also see that in the Search Console. And you can fix it on your site. And we will automatically recrawl your site every now and then to check if it's fixed. And if it's fixed, then we will remove that warning. And everything will go back to normal. Also in Search Console, you can tell us you fixed that issue.  

#### [0:41:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2490) |  And we'll go off and check that.

And if it's OK, then that malware warning will be removed. And essentially, the site is ranking exactly the same as before. So there is nothing that is for the longer term holding back a site if it was hacked with malware at one point. Usually, that's something that jumps back like completely kind of like on and off switch right away. That said, if a site is hacked and is hacked  

#### [0:42:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2520) |  in ways other than just malware, for

example, if someone adds a lot of content to your site that doesn't belong to your site, or if they add phishing pages to your site, or if they add hidden content on your pages, maybe links to other hacked pages or anything around that, then that's something we also try to catch as hacked content. And we try to ignore that as much as possible. But if that remains on your site for a longer time,  

#### [0:42:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2550) |  then we might assume that this is

actually something that you want to provide on your site. And perhaps you want to change your website into a Canadian pharmaceutical. It's possible. It doesn't have to be the case, but it is possible. And in a case like that, we would start ranking your site with that in mind. And if you fix that, which I hope you do find all of those things and are able to fix that, then,  

#### [0:43:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2580) |  over time, we will see that as

well in the content that we've recrawled and reindexed over time. But that is something that is less like kind of the real malware where it's like a virus on a page kind of a thing where it's on and off but more something where, over time, if that content is on your site for a longer period of time, we'll associate that with your site. And if you remove that, it takes a bit of time for us to kind of de-associate your site from that to recrawl  

![](https://i.ytimg.com/vi/f4z96B0-JYE/hq3.jpg)



#### [0:43:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2610) |  all of these pages and recognize, oh,

it's no longer a pharmaceutical but rather maybe a jewelry store or something else. So that's something where there's no kind of magic thing that you can do to have Google refresh everything for your website. Making sure that all of this hacked content is really gone is critical, the most important step. Making sure that it can't get hacked in the same way  

#### [0:44:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2640) |  again is also critical because a lot

of times these hacks are almost automated in the sense that there is no hacker out to try to hack your specific website but rather they just want to hack any website that they can. So that's something where you need to make sure that you don't just remove the hacked content but rather you also remove the hole where they got through. And for both of those things, I would almost recommend getting help from someone who has experience with hacked sites, which  

#### [0:44:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2670) |  could be an expert that has worked

on these for a longer period of time. There are various people who have done that. It could also be, as a first step, going to the Search Central Help forums where the folks there are very experienced with websites as well who may be able to find some of these issues and help you to clean out any of the remaining hacked content, because it can get really tricky in that if there is a security  

#### [0:45:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2700) |  issue on your website, then multiple hackers

could be involved. And you might have cleaned out some of the hack content but not everything. It might be that there are still some hacked content kind of lingering around that you don't see when you look at it with your browser but that Google would see when it crawls your website. And getting some tips and help on that can be quite helpful and speed things up a little bit. Oh. Wow.  

#### [0:45:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2730) |  OK. Still more people joining. OK. We're

kind of getting into the last 10 minutes. I have a bit more time to hang around if any of you want to stick around longer. But maybe we'll go through some of the local things here. I see some of you are raising your hands. So I'll just go through the list as I have it there. Davor, I think, if I got your name right. AUDIENCE: Hi John. JOHN MUELLER: Hi. AUDIENCE: I just have a couple of questions. Short ones, hopefully.  

#### [0:46:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2760) |  So Core Web Vital said that field

data is more important than lab data. Right. So what happens if we fix our vitals 10 days before the update? How bad will that be or will it be good or how will Google look at it? JOHN MUELLER: Probably we would not notice that. So the field data takes I think around 30 days to be updated. So that's something if you make a short term change,  

#### [0:46:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2790) |  then probably we would not see that

at the first point. But of course, over time, we would see that again. And it's not the case that on that one date, we will take the measurement and apply that forever. So if you need a couple more weeks before everything is propagated and looks good for your users as well, then take that time and get it right. And try to find solutions that work well for that. The tricky part with the lab and the field data  

#### [0:47:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2820) |  is that you can incrementally work on

the lab data, and test things out, and see what works best, but you still need to get that confirmation from users as well with the field data. AUDIENCE: Yeah. Thanks. And second question will be does Google have any preferences when naming pictures? JOHN MUELLER: Not preferences directly, but we do in the image search guidelines recommend  

#### [0:47:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2850) |  that you use useful image names, specifically

for image search. So instead of just using a number, maybe use, I don't know, some words describing the image as the image filename. AUDIENCE: Yeah. We describe what's on the picture actually so that will be fine I guess. Is there [INAUDIBLE] reason why our English article shows up in discovering the United States but our Spanish one doesn't  

#### [0:48:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2880) |  show up in discovering Spain? JOHN MUELLER:

I don't know. I don't know the exact triggering there from a discover point of view. But I could imagine that we might look at things differently depending on the language. But it's all kind of tricky with regards to discover, because it's so much tied to what we see that users prefer to see in discover.  

#### [0:48:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2910) |  AUDIENCE: Yeah. It's tricky. OK. Thanks. And

the last one is if a page is not active for more than two years but they hold pretty good positions, what will happen to them? They're not doing actually anything and we-- JOHN MUELLER: It depends. Some pages remain useful over time even without updates. So just because a page is not being changed  

#### [0:49:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2940) |  doesn't mean that it's lower quality. AUDIENCE:

Yeah. OK. JOHN MUELLER: Cool. All right. Eric. AUDIENCE: Oh yes. Hello. I have a few questions for you. So first of all, we were discussing this two weeks earlier. If Google sees a new or a more recent article for a topic, let's say a review of a product or whatever, does it mean that it prefers the more fresh page over maybe  

#### [0:49:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=2970) |  a higher quality one? JOHN MUELLER: Not

necessarily. So we do try to take the, I don't know, age or the freshness of content into account for some queries, but it's not the case that would always apply. And that's something that can also change over time where if, for example, something happens in the news in one location, then suddenly, I don't know,  

#### [0:50:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=3000) |  the fresher content for that location will

be more relevant for users whereas if nothing has happened there for a while, then maybe the more stable reference content for that location would be relevant. AUDIENCE: That's what I was hoping for. Yes. But we have a few examples of reviews that we think are high quality on our page than there are others that rank higher, a lot higher than ours. And it's frustrating.  

#### [0:50:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=3030) |  JOHN MUELLER: Yeah. I think-- AUDIENCE: Maybe

something like debug this or maybe just solve it somehow, change your content to be on, I don't know, fool Google into thinking it's more fresh or something like that? JOHN MUELLER: I don't think you can really do that. I mean, what you can always do is give us information about these kind of queries where you think the results are bad. But when talking with the ranking team about these kinds of issues, they really need to see that it's really  

#### [0:51:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=3060) |  significantly bad. So not like my page

is just as good at number five as the page at number 4. AUDIENCE: [INAUDIBLE] really [INAUDIBLE].. One paragraph, five lines of some copied text. There's a really big review with photos and everything. So yes. OK. JOHN MUELLER: Yeah. AUDIENCE: We should contact the Google team or how would we do that?  

#### [0:51:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=3090) |  JOHN MUELLER: What you could do is

either post in the help forum. That's one way to do that. The folks in the help forum are able to look at that and give you some tips on that as well. And if there is something that is really weird then, they're able to escalate that to Google as well. AUDIENCE: OK. Perfect. I though it was only a community. OK. And then I had another one. It doesn't matter if we have shared buttons or links through social networks of our site.  

#### [0:52:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=3120) |  Does Google take into account maybe the

like counts or the community on other social networks? JOHN MUELLER: No. No. AUDIENCE: OK. I don't know if you can speak about analytics. JOHN MUELLER: Not really. AUDIENCE: OK. But we noticed that we had some issues with issues with Analytics for like a year. And I was asking that maybe, I mean, do Google Analytics filter inputs like hits and page views  

#### [0:52:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=3150) |  from other domains, like let's say our

code is on someone else's domain. Does this maybe change our statistics somehow? I mean, I would say it should filter. JOHN MUELLER: I don't know. I have actually no idea how that is handled. I vaguely remember that there is some way to set that up. But I have no idea. I would double check in the Analytics help forum. The folks there have definitely heard that and might have a tip for you there.  

#### [0:53:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=3180) |  AUDIENCE: OK. Perfect. Thank you very much.

And have a great day all of you. JOHN MUELLER: Thanks. All right. Darcy. AUDIENCE: Yes. Hey John. Quick one about the home activities schema. Any idea if that is rolled out outside of the US or plans to do so? JOHN MUELLER: I have no idea. No. AUDIENCE: Documentation still just says US  

#### [0:53:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=3210) |  so I'm assuming it is, but we'd

like it in Canada too. JOHN MUELLER: I don't know. Maybe you have to move. I don't know. Usually the folks that are handling the documentation of all of the structured data stuff, they're pretty on top of changes like that. But sometimes the teams also make changes without telling the bigger teams at Google. And then it's suddenly live in other locations  

#### [0:54:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=3240) |  we didn't hear about it yet. But

we try to keep that in sync as much as possible. AUDIENCE: OK. Cool. Thanks. JOHN MUELLER: Cool. Mohammed. I don't know if you asked a question before or that's something separate. OK. Hamid? AUDIENCE: Yeah. Hi. Hi, John. JOHN MUELLER: Hi. AUDIENCE: This is Hamid from India.  

#### [0:54:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=3270) |  I have two questions. So I don't

know whether this platform is the right platform to ask, but it's related to EMP webstories indexing on Google. So we have two or three websites. One is in English obviously and then regional sites. But what we have seen is the English articles get indexed very soon and we get the results as well. But the regional languages don't pick up or don't come on Google Search. And we don't get the [INAUDIBLE].. So is there anything to--  

#### [0:55:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=3300) |  the question is whether there is a

preference in languages compared to English and regional languages. And now we have tried to put English text as well in the regional languages but it's not working. So any preferences of that? JOHN MUELLER: I don't know. So especially around Web Stories, I think there are two aspects that might be playing a role there. On the one hand, we show Web Stories in kind of that unique UI in the search results.  

#### [0:55:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=3330) |  But that's only in certain countries. And

we also show them in Discover. And especially, I mean the first one with Web Stories in the search results with that special UI, that's something that depends on whether or not that UI is shown in your country, for example. I think, for example, in Switzerland it's still not shown. So I would not see that. If someone were to make web stories specifically for Switzerland, that would be kind of awkward  

#### [0:56:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=3360) |  because most people here wouldn't see that.

The other part in Discover is probably where you're seeing similar things as the question a while back with regards to English and Spanish content in Discover where these are essentially just completely different environments or ecosystems essentially in different languages where it's not automatically the case that if something in English  

#### [0:56:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=3390) |  is shown in English Discover for users

in English that any localized version would automatically be shown similarly. So those are essentially completely different things. And it's very likely-- I don't know about the languages in India. But it's very likely that users interact with Discover differently across different languages where maybe in English they look at Discover more, and they see that more often, and your articles have more views, more clicks there, and maybe in some other languages  

#### [0:57:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=3420) |  they just don't use Discover as frequently

and therefore your pagers don't get that many views or clicks there. So what I would recommend doing there is not so much trying to make your non-English pages look like they're English as well because then you'd just be showing them to people who are trying to find English content but rather to continue to kind of build out your non-English content.  

#### [0:57:30](https://www.youtube.com/watch?v=f4z96B0-JYE&t=3450) |  And especially if you know that the

Web Stories are not shown in the regions that you're targeting, then maybe it's worthwhile to say I will focus more on the regions where I know it's shown for the moment and then, at some later point when you know that it is shown more in those regions, then put more energy into those versions as well. AUDIENCE: OK. OK, John. Thank you. Thank you so much. JOHN MUELLER: Sure.  

#### [0:58:00](https://www.youtube.com/watch?v=f4z96B0-JYE&t=3480) |  Let me just pause the recording here.

I'll stick around a little bit longer. It looks like there's still lots of questions left, lots of raised hands. So we can continue on a little bit. But thank you all for your questions so far. I hope you found this useful and insightful and that that was a reasonably good use of your time. And hopefully, I'll see some of you again in one of the future Hangouts as well. All right. So with that, let me pause the recording.  