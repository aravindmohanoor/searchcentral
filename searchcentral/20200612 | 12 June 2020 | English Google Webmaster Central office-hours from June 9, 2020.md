[![English Google Webmaster Central office-hours from June 9, 2020](https://i.ytimg.com/vi/-QMSK3V9iLM/hqdefault.jpg)](https://www.youtube.com/watch?v=-QMSK3V9iLM)

## English Google Webmaster Central office-hours from June 9, 2020

This is a recording of the Google Webmaster Central office-hours hangout from June 9, 2020. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Watch out for new sessions, and add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



Feel free to join us - we welcome webmasters of all levels!



#### [0:00:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=0) |  JOHN MUELLER: All right, welcome, everyone, to

today's Webmaster Central Office Hours Hang Out. My name is John Miller. I am a Webmaster Trends Analyst at Google in Switzerland. And part of what we do are these Office Hour Hangouts, where people can jump in and ask any question around their website and web search. A bunch of things were submitted already. But maybe we can get started with some of you all, if there's anything from your side that you'd like to add.  

#### [0:00:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=30) |  BARRY SCHWARTZ: Could we start with some

indexing? It seems like a lot of people are complaining about indexing issues for the past couple weeks or months. This is a new thing, where Google's like, you know what? We're not going to go ahead and index as many pages as we used to. Because we're going to look at quality and say, all right, if the site's not a certain quality threshold, we're not going to index as many pages. Is anything new with that? JOHN MUELLER: I don't think there's anything really new in that regard. But what has kind of changed over, I guess,  

#### [0:01:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=60) |  maybe the last half year or even

longer is that we show this information a little bit more visibly in Search Console. So it's not so much that is like we're changing how we do indexing, how we select the pages that we use for indexing or crawling. It's more that in Search Console we'll tell you, we've seen these URLs. But we decided not to index them. And then people take that information. They're like, oh, I must be doing something wrong.  

#### [0:01:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=90) |  Therefore, I need to fix something. Or

maybe Google is broken or something like that. Because it's flagging me all of these pages. But it's something that I think, at least as far as I know, has been the case at Google since the beginning in that we just can't index the whole web. There are so many things happening across the whole web that we can't possibly keep up with everything all the time. So we have to make decisions along the way  

#### [0:02:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=120) |  and figure out which pages we really

need to have crawled and indexed and maybe which pages like, well, it's interesting that you wrote this. But at the moment, we don't really know what we should do with this information. So maybe we should just not index it at the moment. And I think that's kind of tricky. Because on the one hand, when I talk to Search Console, the Search Console folks, we tell them that this confuses people  

#### [0:02:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=150) |  and they feel they need to fix

something, because we're flagging it as something not being indexed. But at the same time, it's also the kind of information we want to give people, where we essentially want to tell them, hey, we noticed you put this stuff out. But we decided not to index it. We don't really have a kind of a human readable reason for why we decided not to index it. But we still want to give people the information that we understand your site is this big.  

#### [0:03:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=180) |  But we're just picking up a small

part for indexing at the moment. BARRY SCHWARTZ: OK, so just to be clear, it's a reporting thing possibly that has changed in the past several months, but not anything new with how Google determines what to index in [INAUDIBLE]. JOHN MUELLER: No, no. I mean, it's something that happens with crawling all the time essentially. You see it as an SEO if you're looking at your server logs. You notice it there probably first, where you realize you put out 100,000 pages.  

#### [0:03:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=210) |  And Google is crawling 20,000 of them.

And essentially, we might know about these 100,000 pages. Because they're in the site map file. But we're just crawling a small part of them. So therefore, we can only really index that small part of your site. And as you kind of improve the quality of your website, as you improve things around your website, maybe improve some technical details, then that number of the URLs that we crawl that tends to go up. And from my point of view, that's been the case since--  

#### [0:04:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=240) |  I don't know-- since the beginning. I

think in Gary's Crawl Budget blog post he also touched upon this, kind of the crawl demand, how much we want to crawl from your website. And that also changes over time. And if we don't want to crawl a lot of stuff from your website, then essentially we're not going to be able to index all of that. BARRY SCHWARTZ: Thank you.  

#### [0:04:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=270) |  DARCY BURK: John, I have a question

about the core web vitals-- JOHN MUELLER: Sure. DARCY BURK: --and some of the tools you guys have with them. So I'm looking at some of the sites. And I'm looking at the PageSpeed insights tool. I'm looking at Search Console. And then I'm also using the extension in the browser. And I find that Search Console and PageSpeed Insight seem to line up pretty well. But the extension seems to be way off or at least different. Is that because the extension is using  

#### [0:05:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=300) |  my network and the other tools they're

using a combination of things? And then I guess if that's the case, which would be the source of truth for like ranking at the end of the day? JOHN MUELLER: Yeah. So I don't know offhand how the extension works. But my understanding it is it does use kind of your current data that is kind of like what you're seeing in your browser. And with regards to a lot of the speed metrics, we differentiate between lab data and data  

#### [0:05:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=330) |  that we collect from users through the

Chrome User Experience Report. I think it's like real user metrics or some word that they use for that. And essentially, what we see is that for all kinds of data like this it's more of a prediction of what we expect to see when a new user comes to your site. And that's kind of based on what we've seen in the past, what we would see if we tested it  

#### [0:06:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=360) |  kind of in more of a lab

environment, which could be kind of like on your computer. It could be something maybe it's running on a server at webpagetest.org, if you use their test for example. And essentially, all of these tools are kind of approximations of what the average user might see. I recommend using kind of the lab data in situations where you're testing things, where you're trying things out.  

#### [0:06:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=390) |  Because that's where you see essentially the

immediate effect. You change something on your website. You run the test again in your browser. You see a new score. And over time, if that's something that you publish on your website, if other people can see it as well, then that will affect the field data as well over time. I don't know what the time frame is with regards to the Chrome User Experience Report. I'm just throwing a number out there. I'm guessing maybe it's aggregated over a month  

#### [0:07:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=420) |  or something like that. So that's something

where over the course of this period of time that data needs to be collected. And then you'll see the changes that you see kind of on your side. And sometimes the lab tests don't align completely with what users would see. Like if you have the server right next to you and is like, obviously, the [INAUDIBLE] connection is going to be perfect. But the average user has to go through the internet.  

#### [0:07:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=450) |  And maybe your server is in some

faraway place for the average user. So their network connection will always be slow. So that's something just kind of worth keeping in mind. With regards to what we would use for search, we would essentially align it with the data that we show in Search Console, which is kind of based on the field data that people actually see. DARCY BURK: OK, good. So the field data and Search Console-- so Search Console uses the source of truth for ranking.  

#### [0:08:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=480) |  And Search Console is closely related to

field data that you use. OK. JOHN MUELLER: Yeah. Yeah. DARCY BURK: Thank you. JOHN MUELLER: OK, just one brief note. I need to drop out maybe 10, 12 minutes early to join something else afterwards. But I'll run through some of the questions that were submitted. And if you all have any questions along the way, feel free to jump in. I'll see if I can get through them  

#### [0:08:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=510) |  a little bit faster than usual. Maybe

we can go through. For an e-commerce site, we want to implement a log in area, so either use a new page or embed the log in with an iframe. What option should you use? Do I need to block it in robots.txt? Essentially, search doesn't care. You can do whatever you want there. Blocking it in robots.txt is also fine. Essentially, if someone would be searching for your site, plus login, they might  

![](https://i.ytimg.com/vi/-QMSK3V9iLM/hq1.jpg)



#### [0:09:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=540) |  come to this roboted page in the

search results. But essentially, that would lead to your site anyway. So that's perfectly fine. Then there's a question about discovered currently not indexed. I think we talked about that briefly already. Review web sites could have many low quality pages, thin content, poor site structure. Most reviews won't rank or even get indexed, which isn't a problem. But could this hurt other high quality pages on the same site?  

#### [0:09:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=570) |  Should we use rel UGC to tag

kind of the on page content like this? So in general, you don't need to flag user generated content. But if you're publishing user generated content on your site, that's essentially what we think your site is publishing. So just because it originated from some user, if that's what you publish on your website, we think that's the content that you'd like to have shown, which is kind of the case. So if you think this user generated  

#### [0:10:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=600) |  content is low quality or even bad

content, then it's kind of up to you with regards to whether or not you want to publish it. So that's something where I generally recommend trying to evaluate the quality of the user generated content on your website and making sure that what you publish aligns with what you want to have your site known for. Question about I guess HTML.  

#### [0:10:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=630) |  The lead paragraph of our articles is

inside a div. P is more correct if we're speaking about HTML5. What about Google bot? Does it care about div or Ps? We essentially don't care. Totally up to you. I don't know what the kind of semantically perfect variation would be in this case. But for from Google's side for indexing we treat them the same. We have a news website, 200 articles every day. There are two options.  

#### [0:11:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=660) |  All links for all the time are

stored in a site map, hundreds of thousands of links. Or only the 1,000 of the last links are stored in the site map. So any benefit to using second variant versus the first? So essentially, these kind of map directly to new site maps and general site maps that we have. With general site maps, we recommend including all of your pages in the site map file. With new site maps, it's limited I  

#### [0:11:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=690) |  think to the last 1,000 pages. New

site maps are specifically meant for Google news. But you can use new site maps for essentially any kind of website if you want. Or you can alternately just create an extra site map with just 1,000 links in it and submit that individually. So I think both of these options are fine. In general, I do recommend including all of your URLs in a sitemap file somewhere, just so that you have full coverage in Search  

#### [0:12:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=720) |  Console in the reporting. For websites that

rely heavily on UGC to create millions of pages of Q&A, like Quora, what's the best way to structure them, so that the crawl budget is used efficiently without having to remove pages? I think there's essentially no difference with regards to where your content comes from when it comes to crawl budget or kind of the internal crawling and indexing of a website.  

#### [0:12:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=750) |  Essentially, you want to create a structure

of a website where it's easy for us to crawl and find your most important pages as quickly as possible and where we can somehow reach all of the content on your website, at least all of the content that you want to have indexed. And that's independent of the source of the content. If that's something where you're writing all of these articles yourselves, or if you have a team of writers creating content, if it's created by users, it essentially doesn't matter.  

#### [0:13:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=780) |  I'm doing a 301 redirect from subdirectory

on my site to a subdirectory on a new domain. Once they're redirected, I will be displaying a pop up to inform users that they have been redirected to this new page. Once they read it, they can click continue to move on. Would that affect anything? So usually the way to implement something like this would be to check the HTTP refer that you get when a user clicks on a link and goes to a new site.  

#### [0:13:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=810) |  You can pass that refer along. And

that way you can recognize on the new site that the user came from clicking a link on the old site, for example. For Google, when we crawl and index the web, we don't send the referrer at all. Even if we follow a redirect, even if we follow a link on a page somewhere, we essentially don't forward a refer at all. So we would never see this kind of extra pop up there. So in that regard, this would be essentially something that  

#### [0:14:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=840) |  wouldn't effect search at all. Can image

quality on my content page affect the overall page quality rank. If yes, then what aspect of quality matter, the resolution, camera, sharpness, et cetera? So my understanding is that the quality of the images doesn't affect the ranking in normal web search. But it can affect how these images appear in Google images.  

#### [0:14:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=870) |  So specifically for Google Images, we do

try to recognize high quality images. And we do try to show those appropriately in the search results in Google Images. So that's something where if you care about traffic from image search, if you see that your users are searching in kind of a visual way with Google Images, then obviously you'd want to improve the quality of your images. I mean, that's kind of I'd say the logical conclusion anyway.  

#### [0:15:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=900) |  If you want people to search visually

and you want to present your site in a visual way, then you need to make sure that that presentation is as good as possible. So that people click through to your site. With regards to just pure web search, that's not something that we would directly kind of care about. Indirectly, I don't know. Maybe if users come to a page and they think this is a really bad page because the images on the page are really bad, then maybe they won't recommend it. But that's more of an indirect effect  

#### [0:15:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=930) |  and more something between you and your

users. Why is it that my website ranking keeps decreasing until last March, even though I didn't build any link for the past three years of my site? Now when I build some links, in April, the traffic went up only to crash by 80% in the May update. Why is that? Whether or not I build links I get hit by the update.  

#### [0:16:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=960) |  It's really hard to say without looking

at your website. In general, I suspect the kind of link building that you're doing there doesn't really affect the way that Google shows your website in search. So probably what you're seeing in this case is kind of the natural changes in the algorithms over time. But that said, I really don't know what exactly you've  

#### [0:16:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=990) |  been doing with your website, what your

website is, what it's about, what kind of links you've been building to the website there. It's really hard to say. My general recommendation here would be to get more feedback from peers. And the best way to do that is maybe go to either our Webmaster Help Forum or some other forum for webmasters and explicitly mention your site's URLs and the queries that you're looking at. So that other people can take a look at your site  

#### [0:17:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1020) |  and give you some tips on what

you could be doing differently. ANGIE B: John, if I could just jump in. JOHN MUELLER: Sure. ANGIE B: So I had a follow up for my earlier bananas question. When you said when we're showing which pages are most important on our site, you said it's really more about our internal structure. Did you mean it's more about the way we have internal links going on a site, placement of pages from the home page let's say?  

#### [0:17:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1050) |  Or is it more about this proportion

of the content that's about bananas versus about other topics? Does that also play a factor? JOHN MUELLER: I think there are multiple things that kind of play into that. I guess where usually I start is things around internal linking with regards to the anchor text I use internally, how you refer to your other pieces of content, and with regards to how  

#### [0:18:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1080) |  visibly they're referred to. So for example,

if you have a page about a specific topic and that's only linked way down in your site's architecture, then for us we probably assume this page is not that critical. Whereas, if you have that same page linked with an important anchor text from your home page, then generally, because we assume your home page is probably an important part of your website, then that's going to make that page much more important within the structure of your website.  

![](https://i.ytimg.com/vi/-QMSK3V9iLM/hq2.jpg)



#### [0:18:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1110) |  So that's kind of how you would

structure your website a little bit to make it clear to us which parts of your website you think are particularly important. ANGIE B: OK, and so even if we're writing a lot about like strawberries, and oranges, and stuff, the ratio of that content to the bananas content doesn't really play a factor. It's just more about the linking and the anchor text?  

#### [0:19:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1140) |  JOHN MUELLER: Yeah, I mean, specifically with

regards to things internally within your website. I think it's always tricky with regards to the amount of content that you have and how visible that content is within your website. Because it's very easy to be kind of in a situation where you create a lot of content. But within your website you're positioning it in a way that it's more secondary. So just by absolute counts, you might have-- I don't know-- a lot of terms and conditions pages.  

#### [0:19:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1170) |  But your website is not about legal

topics. But rather you're selling something specific. So just the absolute number of pages on a specific topic that you have, that's kind of secondary to how important you frame them within your website. ANGIE B: OK, perfect. Thank you. JOHN MUELLER: Let's see. I've been working really hard on a particular website with content. And SEO on my website is now return in good position  

#### [0:20:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1200) |  in search engine. Do I now stop

altering the content and the SEO? Or will I have to keep updating it as I may lose rankings? Or do I just leave it as it is kind of as it was built up now? Yeah, I think in general, there is always a temptation to kind of let things be once they work well. But the web is evolving so quickly, so that if you don't stay on top of things, it's very easy to kind of end up in a state  

#### [0:20:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1230) |  where your website has been doing well

for a number of years. But suddenly, the rest of the world moves on. And your website becomes less relevant. And it's not so much that you've been doing something wrong for a number of years. It's just that things have evolved since then. And so with that in mind, I would not just stop when you're in a good position, but kind of keep working at it and keep trying to optimize things, try to recognize trends ahead  

#### [0:21:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1260) |  of time before other people kind of

jump on them, and keep involved in your website to make sure that it remains relevant over time. And that's sometimes easier said than done. But I think the hard work is kind of getting into that position first. So you're probably in a good spot to keep that momentum up. After the May core update, the home page of my website jumped from the seventh position to the first and stayed there up until you announced  

#### [0:21:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1290) |  a new core web vitals. In a

position of a few days afterwards, my website dropped to the fourth position. My home page is poorly optimized for speed. And the top three websites right now have worse content, but better optimization. So I guess the question is, did I get penalized for core web vitals? So the short answer is no. We have not announced the date when we're going to start using the core web  

#### [0:22:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1320) |  vitals as a ranking factor. So this

is not yet in place. We decided to announce it early on, just so that these metrics are out there as early as possible, that people understand which direction we're headed. But we also said that we would, I think, give a heads up time of something like a half a year before we would start using them in search as a ranking factor. So that's something where we announce these. But if you're seeing a change on the date of the announcement,  

#### [0:22:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1350) |  that would not be related to that

announcement at all. That's something where maybe other ranking changes happen. Maybe other things in kind of the web that you're active in have changed. So speed is still important. It's still something you should focus on. But it's probably not the reason why your website dropped. Can you talk a bit about discover? My page suddenly started getting traffic from the source.  

#### [0:23:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1380) |  And just like that, it stopped again

in a few months. I don't have anything really specific to add about discover. I think we have a help center page about discover, which goes into a little bit of what happens in discover. But essentially, it's something where you need to understand your audience well and create content that works well for your audience, that they really appreciate, that makes sense for us  

#### [0:23:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1410) |  to show kind of in this proactive

stream where they get content that might be interesting to them. As far as I know, there are no technical requirements that you need to be in a specific format for being visible in Discover. There's no meta tags you need to use, other than, of course, making sure that you're not blocking crawling and indexing. With regards to the previews in Discover, I believe if you're using AMP by default you can have the bigger  

#### [0:24:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1440) |  image preview. You can also use the

meta tags to select that you would like to have a bigger image preview as well. So there are various ways of getting in there. But there is no kind of simple trick to force your site into being visible there, which is kind of tricky. Because when it comes to search, you can understand what people are searching for and create content that matches those searches. With Discover people are not searching.  

#### [0:24:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1470) |  So there are no queries that we

can show you where we can say, well, people are interested in this topic. You should create some content on this topic. Makes it a bit trickier sometimes. I have a question for my domain. A large number of more than nine years old millions of events pages are still getting crawled and indexed regularly, even though I've removed the site map and everything. And many upcoming events URLs fall  

#### [0:25:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1500) |  into the category of discovered currently not

indexed. And this number is increasing. What should I do? So I think discovered currently not indexed, we talked about that briefly in the beginning. With regards to site maps and crawling, site maps help us to crawl better. But they don't limit what we crawl. VIJAY CHAUHAN: [INAUDIBLE] JOHN MUELLER: Just because pages are not in a site map file doesn't mean we would not crawl them or not index them.  

#### [0:25:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1530) |  We would still crawl the website normally.

VIJAY CHAUHAN: Hello, John. I'm here. How are you? JOHN MUELLER: Good. Good to have you here. VIJAY CHAUHAN: So I have a question. I raise this question. So my [INAUDIBLE] pages are still indexing. And my upcoming events URLs are not indexing. So this might be some Google issue or something else.  

#### [0:26:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1560) |  JOHN MUELLER: I don't think there's any

issue with regards to indexing at the moment. VIJAY CHAUHAN: But my upcoming events are high quality pages and this past year events are already low quality pages. So why Google continuously crawls these old pages.  

#### [0:26:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1590) |  [INAUDIBLE] too many years ago. JOHN MUELLER:

Yeah, my guess is that these are just URLs that we have indexed at sometime in the past. And we tend to keep URLs indexed for a fairly long time once we know about them. So probably we just haven't gotten around to kind of reshuffling things around here. There are things you could do if you wanted to control  

#### [0:27:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1620) |  that more on your side. One thing

is to use the no index meta tag on pages that you don't want to have indexed anymore. Another thing that you can do is use the unavailable after metatag, which lets us know ahead of time when you think that a certain page will no longer be relevant. So for example, if you have events, you could say maybe a month after this event took place you will kind of use the unavailable after metatag  

#### [0:27:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1650) |  and tell us this only makes sense

to keep indexed until a month after the event has taken place. And then afterwards, we'd be able to drop that out a little bit quicker. I don't know if removing pages from the index will make it so that we index newer pages faster on a website though. So it's not the case that you have a limited number of pages in our index and if we have the old ones then we can't add new ones.  

![](https://i.ytimg.com/vi/-QMSK3V9iLM/hq3.jpg)



#### [0:28:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1680) |  VIJAY CHAUHAN: But my question is Google

is still crawling my oldest pages compared to my new pages. So that's why I raise the question. JOHN MUELLER: I think from a crawling point of view, we crawl a lot of things. But that doesn't necessarily mean that we would still index them. So my general recommendation here would be to think about what you want to continue to have indexed and let us know about things that you don't want to have indexed,  

#### [0:28:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1710) |  if you want to make that decision.

But otherwise, to really make sure that the quality of the website overall is as high as it could possibly be. I haven't taken a look at your website specifically. So it's kind of hard to say. But a lot of the pages that I've seen on Twitter that get flagged for these issues where they fall into discovered not indexed or crawl not indexed, it  

#### [0:29:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1740) |  tends to be that the website overall

is kind of in this murky area where we think some parts are pretty good. Some parts are kind of OK, but not fantastic. And then at some point, we just say, well, we're going to wait to see that we get more signals for these particular new URLs before we spend time to actually index them. VIJAY CHAUHAN: And I owe another question because I can [INAUDIBLE]. After I implemented online schema,  

#### [0:29:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1770) |  we lost all our ranking in the

[INAUDIBLE] in [INAUDIBLE].. So [INAUDIBLE]. JOHN MUELLER: That should be unrelated. So the kind of the structured data that you supply on these pages when you additionally add additional structured data types that wouldn't change the ranking of those pages.  

#### [0:30:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1800) |  It would give us more information or

different information about those pages, which could result in other rich results. But it wouldn't change the ranking of the pages. So if you're seeing ranking changes, that would be independent. VIJAY CHAUHAN: No, no, no. I'm not talking about ranking. I'm talking about we lost a lot of [INAUDIBLE] snippet in event schema part, event list, and event [INAUDIBLE]..  

#### [0:30:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1830) |  JOHN MUELLER: I don't know. Yeah, if

you could drop some sample URLs maybe in the chat here, I can pick those up afterwards and double check with the team. VIJAY CHAUHAN: Yeah. So meanwhile, you can continue with another webmasters. Thank you. ANGIE B: On the note of-- oh, sorry. On the note of the crawling or discovered not indexed,  

#### [0:31:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1860) |  sometimes I get AMP pages in there.

And they're freshly published. And when I check them after they get indexed or they have been indexed. So is it just kind of a fluke if I ever see AMP pages in the crawled or discovered not indexed reports? JOHN MUELLER: Yeah, usually what would happen there is we might discover and try to index those pages first. Because maybe we find a link to them or for whatever reason  

#### [0:31:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1890) |  we find them fairly early. And once

we've processed the AMP page and we process canonical HTML page that belongs to it, then we can connect the two and say, oh, we just need to focus on the HTML page. So as a first step, if we see the AMP page first, we'll be like, oh, it's a page. We'll index it. And then, as a second step we'll see oh, it actually belongs to this other page, which we crawled in the meantime as well. So we can kind of fold things together.  

#### [0:32:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1920) |  ANGIE B: OK. It's interesting that you

might be able to see the AMP page first though. Because it's always connected to my canonical. JOHN MUELLER: Yeah, I mean, it can happen that people link to these pages. I see that every now and then that people will take the AMP URL they find in their browser and they link to that directly. And in cases like that we might pick that up a little bit faster than the HTML page. My guess is these would kind of just  

#### [0:32:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1950) |  clean themselves out over time. It's like,

well, kind of a disconnect with the timeline of crawling, where usually we pick up the HTML page first and then understand the AMP connection. This time we picked up the AMP page first and then shifted over to the HTML version. ANGIE B: OK, I see. Thank you. BARRY SCHWARTZ: Is it possible I ask a question about page experience? Or [INAUDIBLE]. JOHN MUELLER: Sure. Go for it. BARRY SCHWARTZ: So could you open up your crystal ball and say-- it seems like the HTTPS the page speed are all relatively historically minor signals  

#### [0:33:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=1980) |  when it comes to ranking. The waits

are minor in general, especially because you let Gary program them and you don't really trust him too much. Joke. In any event, this page experience obviously lumps a bunch of those elements into this overall thing. And each one will be individually, from what I've spoken to Google, each one will be an individual factor. It's just branding purposes calling them page experience. So the core vitals [INAUDIBLE] I suspect also will be relatively minor. Could you tell us if you think that would be true or not?  

#### [0:33:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=2010) |  I know obviously, nothing's been programmed yet.

JOHN MUELLER: I don't know. My feeling is it depends a lot on the search results pages where these pages are shown. So in situations where it's very clear that there is one relevant answer, then we're not going to just pick one that's a little bit faster. So if someone is searching for SEO roundtable, then it's like we're not going to show some random blog that talks about this site just because it's  

#### [0:34:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=2040) |  a little bit faster. We really, really

know that people are looking for this site. On the other hand, if someone is searching for maybe something more generic, like SEO news, and we have a bunch of different sites and they're all kind of in a similar level, then that's something where we can take a lot more of these factors into play and say, well, actually this is like kind of relevant. And it's a really good result. Therefore, maybe we should show it a little bit higher. And finding that balance is really hard.  

#### [0:34:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=2070) |  That's something where the ranking team, they

spend a lot of time on this. And they do a bunch of tests on this to try to figure out what is the right balance between all of the different ranking factors in all of these different kinds of situations. So it is really not possible to say how strong of a signal it will be. Because it really depends on the circumstances. And at the same time, it's not going  

#### [0:35:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=2100) |  to be something where we say, well,

speed has to kind of dominate everything else. Because we really need to also make sure that we're providing relevant results to people. BARRY SCHWARTZ: OK. And if I could add one new factor in the suggestion pool for those overall page experience. The no date for a new site. If a new site doesn't have a dated article, could you please add that as one of the-- type that down [INAUDIBLE]? JOHN MUELLER: OK. OK. Fine.  

#### [0:35:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=2130) |  I hate that as well. That's a

good point. SPEAKER 6: Can I jump in? JOHN MUELLER: Sure. SPEAKER 6: We're making in a new page format for news website, in which stories we'll be told by card. For example, on the page that are online cards for each question. After clicking on the card, it flips over. On the other side of the card there is an answer. It detects about 300 or 500 [INAUDIBLE].. We know that the Google bot does not leak, which means that there may be problems with how Google will understand  

#### [0:36:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=2160) |  such articles. But at the same time,

[INAUDIBLE] repeatedly said that if such content isn't [INAUDIBLE],, then the Google bot will see it and use. So can you give us advice of how to correctly implement a new format with cards from a technical point of view? So that they will be fully indexed. And a link was an example [INAUDIBLE]..  

#### [0:36:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=2190) |  JOHN MUELLER: So if the answer is

in the HTML, then essentially that will just work. On the other hand, if the answer has to be loaded from the server as soon as someone clicks on that card, then probably we would miss that. So that's kind of the different approach there. So that's something where one way you can do it is load the page and then look at the rendered Dom that you have in your browser with inspect element.  

#### [0:37:00](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=2220) |  And if the answer is already in

there, then you're already covered. On the other hand, if the answer is not in there that you need to do an interaction first before it's loaded into the visible page, then that's something we wouldn't see. SPEAKER 6: OK, thank you. JOHN MUELLER: OK, I need to take a break here. Sorry for cutting things short. I'll have a bit more time on Friday in case any of you want to join in then.  

#### [0:37:30](https://www.youtube.com/watch?v=-QMSK3V9iLM&t=2250) |  Thank you all for joining. And thanks

for all of the questions that were submitted. And hope to see you all soon one of the next times. [INTERPOSING VOICES] JOHN MUELLER: I really need to go. VIJAY CHAUHAN: You need to go, OK. JOHN MUELLER: Yeah. VIJAY CHAUHAN: No problem. JOHN MUELLER: Maybe ping me on Twitter. [INTERPOSING VOICES]  