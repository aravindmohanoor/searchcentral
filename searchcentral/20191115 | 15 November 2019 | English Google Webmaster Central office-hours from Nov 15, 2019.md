[![English Google Webmaster Central office-hours from Nov 15, 2019](https://i.ytimg.com/vi/WyeHvNvibuY/maxresdefault.jpg)](https://www.youtube.com/watch?v=WyeHvNvibuY)

## English Google Webmaster Central office-hours from Nov 15, 2019

This is a recording of the Google Webmaster Central office-hours hangout from November 15, 2019. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Watch out for new sessions, and add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



Feel free to join us - we welcome webmasters of all levels!



#### [0:00:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=0) |  JOHN MUELLER: All right. Welcome everyone to

today's webmaster central office hours Hangout. My name is John Mueller. I'm a webmaster trends analyst here at Google in Switzerland. And part of what we do are these office hour Hangouts where people can join and ask their questions around their website and around web search, and we can try to help with, hopefully, some answers. Sometimes there are no answers, but we try to at least explain  

#### [0:00:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=30) |  the thoughts behind it. A bunch of

stuff was submitted already on YouTube, which is great. That's always useful. But is there anything on your minds that you need to get an answer to right away? SANJIT CHAKRABORTTY: Yes, John. JOHN MUELLER: Sure. SANJIT CHAKRABORTTY: Yes, John. I'm Sanjit. I'm from Bangalore, India. Yes, I have a question actually. So, I have a website.  

#### [0:01:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=60) |  And part of the website in AMP

and some of the pages, there is [INAUDIBLE] starting to show the content in mobile. And it's a mobile-first indexing from switching mobile-first indexing from May 2018. But now I see in the primary crawler setting, it's showing as desktop. So it's not moved to a smartphone. So could you please help me on that?  

#### [0:01:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=90) |  JOHN MUELLER: Where are you seeing there

the primary crawler? SANJIT CHAKRABORTTY: It's showing desktop in Search Console, in [INAUDIBLE] in Search Console. JOHN MUELLER: OK, so usually when we move aside to mobile-first indexing, then we shift that, too. But what also happens with mobile-first indexing is we will still crawl some pages or some parts of the crawl with the desktop crawler.  

#### [0:02:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=120) |  So it's not that you would shift

completely over to just mobile crawling. It would still have some things there. And in general, it's nothing that you need to worry about. If things are working well on mobile for you, then that's fine. It's not any disadvantage to be crawled with the desktop crawler. SANJIT CHAKRABORTTY: OK, thank you. Thank you so much. JOHN MUELLER: Sure.  

#### [0:02:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=150) |  RISHABH RANJAN: Hey, John. JOHN MUELLER: Hi.

RISHABH RANJAN: So I have a question regarding-- I have a website with a mobile version and a digital version. So I'm wondering how I can use the parameter, [INAUDIBLE] parameter. JOHN MUELLER: The URL parameter handling? OK. So that doesn't really change with regards to desktop or mobile version. If you have parameters within your website that you feel  

#### [0:03:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=180) |  are making it harder to crawl your

website properly, things like sorting or filtering parameters, then you can specify those in the parameter handling tool. If you're not sure and if you think crawling is working fairly well, then I would just skip the parameter handling tool. Then you should be all set. RISHABH RANJAN: Yes, so another way of doing it, maybe we use parameter tag to the main URL, right?  

#### [0:03:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=210) |  So in the mobile version of URL

[INAUDIBLE],, what canonical should I give? Should I give to the desktop version or the mobile version where [INAUDIBLE]? JOHN MUELLER: So with the canonical, you should have the link between the mobile and the desktop version. So the desktop version will have a link rel alternate to the mobile version, and the mobile version will have the link rel canonical to the desktop version.  

#### [0:04:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=240) |  RISHABH RANJAN: Yeah, so sorry to interrupt.

So that part I understood. So actually, the thing that's key, if I have an original version without a parameter one, right? So we'll do the same thing that you told. But in case of parameter-- so I did a canonical. So should, in that case, canonical go to the desktop version or the mobile version of the main URL? JOHN MUELLER: I would just do it to the desktop version of the main URL. I don't think it matters because we fold those URLs together, but the desktop version seems like a good a choice as any.  

#### [0:04:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=270) |  It's maybe also another chance to suggest

that if you can move away from these separate mobile URL set up, it would make things much easier. You don't have to worry about that. But I know moving away is sometimes a lot of work. RISHABH RANJAN: Yes, so I had talked to [INAUDIBLE] regarding that and they're not ready to do that, basically. So I have to walk with them over indexing  

#### [0:05:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=300) |  separately so that's the thing right now

with me. JOHN MUELLER: Yeah. I know it's not easy. BARUCH LABUNSKI: I'm kind of with you, John, way back. And now I'm looking back at it, and I'm like, oh my god. I remember telling you that there's a lot of sites that I knew that were m-dot-whatever and having a website as a whole, yeah.  

#### [0:05:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=330) |  JOHN MUELLER: I think it was a

reasonable choice at the time when making responsive sites was a lot harder, and sometimes you had completely different teams working on a mobile site. But it does make things much, much trickier when you-- BARUCH LABUNSKI: And now it's a dinosaur. RISHABH RANJAN: So to addition to that, John, another point I had. So basically, it's a dynamic site. So a big e-commerce site. So there is a crawling problem happening  

#### [0:06:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=360) |  because we started our mobile site indexing

recently, a month back, basically. So ideally, the sitemap is something like we submit for the desktop and the rel canonical-- rel URL has given to the mobile version, right? So I'm wondering, can we submit a separate sitemap for the mobile version only having the mobile URL in it to make crawling faster?  

#### [0:06:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=390) |  JOHN MUELLER: It wouldn't make crawling faster.

So we need to see the map between the two versions. So I would do the main desktop version with the sitemap file. RISHABH RANJAN: Got it. Thanks for your answers, John. AMAR TADI: Hi, John. I have a question for you. Yeah, we have been implementing a structure data from February last year. But unexpectedly, due to accident, the structure data  

#### [0:07:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=420) |  has been removed on last July. And

we, some of us [INAUDIBLE] and digging in the month of August, we have noticed it and we have added it back. But from that time, we are not able to see the results of the bit snippets. We are able to see the results of AMP and FAQs and videos and everything. But only for the rich results, we are totally vanished right now. So is there a way we can do a re-submission kind of thing for that?  

#### [0:07:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=450) |  JOHN MUELLER: So the way that we

decide when to show rich results is based on three things. So it's not something that you need to do manually. Well, not something that you need to resubmit manually, that someone has to look at it, unless there is a manual action already. Like if the web [INAUDIBLE] says it's not OK, then you need to fix that. But we need to have, technically, the correct structure data. So with the testing tool, that sounds like maybe  

#### [0:08:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=480) |  you're doing correctly. It needs to be

logically correct, so it needs to be the right type of structure data for the right situation. So if it's a product, it shouldn't use the recipe structure data. It should match what you're showing. And the third thing is-- it's kind of tricky-- is that we need to be sure that the website is of high enough quality so that we can really trust the website. We know that the structure data that you're providing  

#### [0:08:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=510) |  is something that is relevant to be

shown in the search results. So that's kind of usually the part where people get stuck in the sense that, technically, implementing things correctly is testable. But determining how high quality your website is something that's very hard to do. So if you're not seeing rich results, one thing you can do is do a site query for your website. So just like, search site, colon, and then  

#### [0:09:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=540) |  your domain name. And if you see

the rich results there, then technically we understand the markup on your pages. And it's usually more a matter of just not being sure about the quality of the website overall. That's something where I would say, if you see it in the site query, then definitely focus on improving the quality of your website significantly, not just like fixing things a little bit, but really get further.  

#### [0:09:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=570) |  AMAR TADI: Sorry to interrupt you. So

we have checked there are no manual action report is not there, and we have been checking all of the structure data as well, the structure data [INAUDIBLE].. For some reason, I'm doing it over the [INAUDIBLE],, I'm able to see the bit snippet, like bit snippet in Google. But the data is not being showing in Google Search Console, that's what we have learned, because we have lost a lot of impressions. Because in July, month, we have seen it,  

#### [0:10:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=600) |  that [INAUDIBLE] rankings. Will there be an

impact of page speed on structure data as well? Because I have checked my site with the Google [INAUDIBLE] tool, and it's showing SEO score as 98. And web performance, it's in 50 or something like that, because [INAUDIBLE]. And I'm not able to increase the speed. That's one more thing that's worrying me. And it's really getting really difficult for me  

#### [0:10:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=630) |  to convince my client that, you know,

the speed is the only matter. It's one of the top three [INAUDIBLE] that's how I am telling. I just want to-- if you could throw some light on it, it would be great. JOHN MUELLER: So whether or not we shall rich results wouldn't affect the rankings. So if you're seeing a drop in rankings, that's completely separate from rich results. That's maybe one thing. The other thing is, with speed, it sounds like you're in a reasonable range.  

#### [0:11:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=660) |  It doesn't sound that terrible. So that's

probably OK. But just from what you're saying, I would really recommend focusing a lot more on the quality of the website overall. AMAR TADI: Thank you. JOHN MUELLER: Sure. OK. Let me run through some of the submitted questions. And we'll have more time for questions from you all towards the end. I have this room a little bit longer, so we can go a little bit longer and maybe go off the record  

#### [0:11:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=690) |  so that the recording doesn't go too

long. Let's see. Regarding the indexing API, I'd like to know if it can be used in e-commerce shopping sites. At the moment, no. So the indexing API is a way of submitting your URLs directly to Google, and it's currently limited to live streaming and jobs content. So any other kind of website content  

#### [0:12:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=720) |  will not be processed with the indexing

API. I don't know about the future plans. Personally, I would much more recommend using sitemap files for any kind of general website where you're making changes. Make sure that you're submitting good sitemap files that are focused on the primary content, and that you specify the last modification date and time of that primary content. So that's kind of what I would recommend  

#### [0:12:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=750) |  doing there instead of trying to go

this work-around through indexing API. And another one that kind of, I guess is similar to e-commerce. Product markup only really works well for a standalone one-off stores like mom and pop t-shirt stores who directly retail. I would argue that's not the case, but OK. When will it be extended to suit the case for global enterprise brands who may have many product pages,  

#### [0:13:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=780) |  but don't directly sell to the public?

For example, a bunch of car dealers or car manufacturers, how do you mark up a page for a specific car model when there is no real price there, probably because of all the variations. It really makes it harder for the enterprise SEOs. So I think this is an interesting question, but I think it's worth looking at it from the other point of view in the sense that what makes sense  

#### [0:13:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=810) |  for a lot of these rich result

sites is that you're aiming for a specific way of that content being shown in search. It's not that you're marking things up and saying, well, I have this magical bonus just because I mark things up. But rather, you're trying to be present in a particular way in the search results so that users better understand what it is that you're offering and how your website is the most relevant one for what they're  

#### [0:14:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=840) |  looking for. So that's kind of the

direction I would look at this from. And when we look at the general products that we show in the search results, it's like you're searching for a specific type of device, or a specific item. And then we can show the different prices and kind of the related items and reviews for those items because it's very much tied to one specific thing. When it comes to different car types, for example,  

#### [0:14:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=870) |  there's so many different variations. And reviews

kind of match different variations. And the prices are all over the place. How would that be suitable to be shown in this kind of generic product display that we have in the search results? I don't know. It feels a little bit stretched to me. So from my point of view, it's not that these kind of sites that are selling cars, or that are manufacturing cars, are in any kind of disadvantage  

![](https://i.ytimg.com/vi/WyeHvNvibuY/maxres1.jpg)



#### [0:15:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=900) |  because, well, you can't fit a car

into kind of this one small thumbnail image with a price and a review and say, well, this is all there is to it for this specific item. So unless there is some other way of showing this kind of content in the search results-- and I really don't know if anything around that is planned-- then that's something where I wouldn't  

#### [0:15:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=930) |  try to shoehorn kind of the generic

product markup and structure data into the use case of something so different, like a car, for example, where you have all of these different variants and variations and reviews and all of these things that are quite different between the different types of models. But that doesn't mean that you can't use structured data on these pages. So we do use structured data to better understand pages  

#### [0:16:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=960) |  and to better understand when a page

is relevant to be shown to users. So I would double-check the schema that Oracle lists that where we have all of the different structured data types. And think about ways that, maybe, there is something on the items that you're selling on the items on your website that is not being picked up properly in the search results, where maybe people are searching for something similar, but they're not really finding your pages.  

#### [0:16:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=990) |  And think about if there's a way

that you can specify that clearer to search engines that your page is actually about this specific type of item. I don't know what exactly would match there for cars, in this particular case, but you don't need to just focus on the car aspect here. Maybe there are other aspects on your website where you already kind of have the situation where it's harder for people to recognize what that page is about. Because I imagine for car models,  

#### [0:17:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1020) |  people search for these models directly. And

we can probably already show those fairly well in the search results. When we add FAQ schema to a page, does that show every time in the search results? No, it doesn't. It's never guaranteed to be shown in the search results. So it wouldn't be the case that we would show it all the time. I think we had that before with the other case  

#### [0:17:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1050) |  with rich results, where there are different

things that we need to look at before we do show it. And even when everything aligns, then we try to limit ourselves to a certain amount of rich result types in the search results page, because otherwise, it just looks too overloaded with all of these different variations. The European Data Protection Regulation requires consent requests for cookies. The form usually overlays the content as a layer,  

#### [0:18:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1080) |  and then there's some examples. How can

Google handle this? Can Google differentiate it from advertising layers? What is to be considered? So I looked at your examples. And at least here, in Switzerland, I don't see those overlays. So that's kind of hard for me to say exactly what is happening there. I generally assume that people put Switzerland into the same bucket as the rest of Europe,  

#### [0:18:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1110) |  despite us being so unique and a

little bit weird. So I don't see those here. I'm not sure exactly what the overlay looks like there. So that kind of leads me to two aspects here. On the one hand, Google generally crawls from the US. So if we don't see those overlays in the US, then we would not see those overlays for search. So that's kind of the first one. The other one is we generally try  

#### [0:19:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1140) |  to recognize these kinds of legal interstitials

and legal banners and differentiate those from advertising banners. So that's something that we have quite a bit of practice with. And in the past, I thought we would need to create a special markup so that you can specify, oh, this is a legal interstitial and not an advertising interstitial. But it turns out that we actually figure that out fairly well. So for the most part, that's not a problem.  

#### [0:19:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1170) |  The one case where it is a

problem-- and it's really, really rare that I run into cases like that-- is when the interstitial replaces the actual content on the page. So when you load that page, instead of the actual content also being loaded at the same time, you either get redirected to an interstitial page or the server only delivers the interstitial without any of the content at all.  

#### [0:20:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1200) |  In a case like that, Googlebot would

not know that it would need to do whatever it needs to do to kind of go through the interstitial and load the actual content. So that's something where, from a technical point of view, we just don't have any capability to actually get to the content itself. Sometimes I see that with age interstitials where you have to enter an age, and then it redirects you back with a cookie to the actual content, and then it actually loads the content.  

#### [0:20:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1230) |  Usually, that's something where people are aware

of that or they notice it fairly well because all of their content would be, essentially, gone from search. We would just only have that interstitial page. So it's usually a pretty obvious thing if you look at the search results for your site and you see that none of my content is indexed, it's not ranking for any of my terms, and the snippet just shows, please click here to confirm.  

#### [0:21:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1260) |  Then that's a pretty obvious sign. Yeah,

those are kind of the things that I would look at there. How does Google treat templated content like on real estate and e-commerce sites where there are hundreds and thousands of pages being generated? So we don't do anything special with this kind of templated content. It's not that we would say, this is a real estate site, they're allowed to do this, and other sites  

#### [0:21:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1290) |  are not allowed to do this. But

rather, we treat this content as we would other content elsewhere. That means if the whole page is duplicated across a website, then maybe we treat that as a duplicate page and say, well, we'll just index one of these. We don't have to index both of them. If just a part of the page is duplicated, we'll try to recognize that as well. We'll generally still index that page and we'll try to show,  

#### [0:22:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1320) |  when someone is searching for that specific

piece of content, we'll know that this piece of content is on multiple pages and we'll try to show the most appropriate one for that user. So that's something where we try to figure out, among all of these copies that we have, which is the best one to show in this particular case. And usually, what we try to do is filter out the duplicates in those search results pages.  

#### [0:22:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1350) |  So you'll often see, if you go

to- I don't know-- page 3 or 4 of the search results page, it'll say there are some pages filtered out. Click here to see them all. And that essentially means that, within the snippet that we would otherwise show, it would essentially show the same thing multiple times, which is not very useful for users. So we would filter those out. So again, it's not that we would treat these kind of sites in any way different. It's essentially just we recognize it, those elements  

#### [0:23:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1380) |  as duplicate content. We try to deal

with that. And there's no penalty for this kind of duplicate content. So it's not that your site would be seen as less valuable just because you have the same product listings as other sites. It's just we know that it's the same thing as on other sites, so when people search, we try to pick the right one to show. Can you talk about Google Discover  

#### [0:23:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1410) |  and put more light on Google Discover

versus Google News? So I don't know what there is, really, to say about Google Discover. It's something where we try to recognize when content is relevant to users and we serve it to them directly in the feed. So from a website point of view, the tricky part is there is no keyword associated with it. There is no ranking associated with it because you're  

#### [0:24:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1440) |  somewhere in this feed. So that makes

it a little bit trickier to kind of focus on, because essentially, you have to create relevant content that is useful for users that makes sense to be shown to users at that time. The one thing I would kind of think about when it comes to Discover is that visual content tends to perform a little bit better, and that it draws people's attention.  

#### [0:24:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1470) |  So things like large images, if you

can mark up a large image on your page, that makes it a little bit more interesting for people. If you use Amp, then it automatically uses the wider image. If you use the max image preview robots meta-tag, you can also specify a larger image to be used in Discover. I think that makes it a little bit interesting for users when they're in their feed. It doesn't mean that we would be more likely to show your pages,  

#### [0:25:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1500) |  but it makes it probably more that

people would click through and say, well, this is actually a pretty interesting topic. You don't need to be in Google News to be in Discover. Discover is based on, essentially, the normal web search content. We do have a set of guidelines and policies for Discover. So if you're really curious about Discover, I would double-check our Help Center on that.  

#### [0:25:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1530) |  Then a few other questions. How can

we use the next back button safely? I'm not quite sure what you mean there, so don't really have an answer. How can we integrate affiliate marketing with news websites? I know Google hates this, but I see big brands doing it. So I don't know. I'm not aware of Google hating affiliate marketing. So that's something maybe just worth saying.  

#### [0:26:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1560) |  The one thing that we do tend

to see with affiliate sites is that there's often a tendency to just put minimal work into them and to just say, well, I have this feed of 100,000 products. I will just create pages for 100,000 products automatically. And if you're creating this kind of low value content, then of course, Google search is going to say this is low value content, because that's what it is. On the other hand, if you're creating really good content  

#### [0:26:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1590) |  and you have affiliate links in there,

then go for it. That's a fantastic way to monetize your pages, a fantastic way to get a reward for the work that you're putting into these things. Go for it. There's nothing on Google's side that would say using affiliate links within your normal content is a bad thing. The thing that we do say is creating low quality content is a bad thing. So it's not the affiliate links, but rather the quality overall that I would focus on.  

#### [0:27:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1620) |  I've been charged by my company with

reviewing our backlinks. Reading through old documents, the company engaged in some unnatural building schemes a decade ago. I also discovered that the company made use of one of those JavaScripts that placed automatic attribution links with fragment links on copy and pasted content. My question concerns the latter practice. Does Google consider these automatic attribution links  

#### [0:27:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1650) |  natural? So I really don't know how

those links look like. I am not aware of the older JavaScript things there. It feels-- offhand, it feels like something that's probably not an issue. But I really don't know how that specifically looks like for your website. In particular, in the past, JavaScript  

#### [0:28:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1680) |  would be one of those things that

we would recommend if you don't want search engines to actually find something on your pages. You can use JavaScript to put the link on this page, for example, and search engines won't use that. In the last couple of years, of course, search engines are capable of accessing JavaScript. So all of that is suddenly visible. So my feeling is, offhand, that if this is something that took place a decade ago, then on the one  

#### [0:28:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1710) |  hand, probably the intent behind those links

is not to manipulate page rank. So it's probably less of a thing. On the other hand, it sounds like maybe it's still worth looking at that to see, how would those JavaScript links be looked at nowadays? Is that something that would have an effect that you maybe should care about and should clean up? Or is that something that continues to essentially not have an effect at all?  

#### [0:29:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1740) |  The amount of not provided data in

my analytics account is steadily increasing. How are we supposed to improve our SEO when Google doesn't deliver the search keywords? So I guess, first of all, I don't see the not provided part going away anytime soon. This has been the case since, I think, before I joined Google, that the refer no longer shows any keyword information.  

#### [0:29:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1770) |  So that's something where I would not

focus on the refer data that you're seeing in analytics, or that you're seeing in general when you're kind of tracking the referred data for keywords. I would really focus on things like Search Console where we do aggregate all of these keyword data and we do show it in a way that makes it kind of easier to use. So that's kind of the direction I would head there.  

![](https://i.ytimg.com/vi/WyeHvNvibuY/maxres2.jpg)



#### [0:30:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1800) |  I honestly do not see that trend

changing back. It's been like this for a really long time. It's something where probably the amount of traffic that you're seeing with a refer is very minimal because we still have some hold back experiments to kind of double-check that things are working as expected. And it might be that some kinds of browsers don't fall into the category where we can kind of strip the refer out.  

#### [0:30:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1830) |  So those are probably the few things

where you would still be seeing that kind of traffic. But I honestly don't think that's something that would be going away, or that I'd recommend kind of focusing on to try to get back. The Google BERT update affected two of my websites and traffic dropped by 40%. The only thing I'm doing is following Google's guidelines. I haven't built a single link and I focused on creating content, user experience.  

#### [0:31:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1860) |  The site ranked in the top three

and traffic was getting better day by day. But after BERT, the site moved to the fourth and fifth page with main keywords and long-tail keywords remaining unchanged. My site is the best user experience and average user stays are five minutes, so a lot bigger than my competitors. What's happening here? So I think, maybe first of all, this would not be from BERT.  

#### [0:31:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1890) |  So the BERT changes are particularly around

understanding queries better and around being able to understand text better, in general. So it's not that we would say that suddenly your page is less relevant. But rather, with BERT we would try to understand, does this question that someone is asking us, does that match this website best? And usually that's far more complicated question. So if someone is searching for, I don't know, cheap smartphone,  

#### [0:32:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1920) |  for example, then that's a pretty obvious

query. We kind of know what to do there. But if someone is asking for, where can I buy a cheap smartphone when I'm not in India? Then suddenly, that becomes a lot trickier because of all of these extra elements within the sentence, within the questions. Well, India is mentioned, but you explicitly don't want pages that mention India.  

#### [0:32:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1950) |  So those are the kind of things

where I would expect a site might see changes in long-tail traffic and of these more longer queries where people are searching for something a little bit more complicated. And there, I would expect to see more relevant results going to those appropriate sites. So some might see a little bit more. So might see a little bit less. But it wouldn't be the case that, overall, your website would drop in rankings or be less visible because  

#### [0:33:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=1980) |  of this kind of change because we're

really just trying to understand things better and to find which of these pages are more relevant. The thing to keep in mind is that we make changes all the time. We've made several core algorithm changes as well over the last month or so, which kind of overlap with the rollout of BERT, as well. So that's something where my guess is  

#### [0:33:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2010) |  that these changes here are totally unrelated

to the BERT change, but more just regards to the general algorithm changes where we try to figure out which pages are more relevant, which of these pages are better, higher quality, how can we show them more relevant pages in the search results. So my recommendation here would be to not focus on BERT, not focused on purely technical aspects. So you mentioned user experience,  

#### [0:34:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2040) |  you mentioned speed. It's something where I

would really focus on the site overall and kind of improving things overall. For the core algorithm updates, we have a blog post that has a lot of details on different things that you could be focusing on. So I recommend checking that out rather than worrying too much about BERT and machine learning and all of these crazy things.  

#### [0:34:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2070) |  Site speed concerns. Let's see. I think

we talked about something similar like this. Search console doesn't show any data in page speed insights. There's different results for desktop and mobile. I understand speed is an important metric. So how can I get the right data to be shown for my site? I feel like I'm simplifying things to run through a little bit.  

#### [0:35:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2100) |  Sorry if I got your question wrong.

So maybe the first thing here is that Search Console, as well as parts of page speed insights, are based on Chrome user experience report data, which is real world data that is aggregated from users as they see your site. And for smaller sites, for sites that don't have a lot of traffic, we might not have enough data to make a meaningful judgment call here. And that's completely normal. That's not a sign that we're ignoring your website.  

#### [0:35:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2130) |  It's just a sign we don't have

enough data to meaningfully make a decision here. So that's maybe the first thing to say here. That's also very visible for larger sites, as well, where if you look in Search Console, it will say you have 10,000 pages indexed, and the speed report says you're 200, which is, well, I have more than 200. Why don't you show me more? And that's mostly just based on, we  

#### [0:36:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2160) |  don't have a lot of data for

those pages. The good part there is that this is based on people who are viewing your website, so it's not an artificial test of speed, but actually of what people have seen on their devices in real world conditions under all of the flakiness of the real world. The kind of lab tests that are available in page speed insights where we test your pages and see how they perform,  

#### [0:36:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2190) |  that's something that is based more on

a theoretical calculation on how the speed would perform in a browser. And that's something that you can test on the one hand in your own browser. In Chrome, you can run the same page speed insights test. You can also run the page speed insights test from our side so that both of those give you some meaningful data, as well. And if you're seeing bad scores there,  

#### [0:37:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2220) |  then I would try to focus on

the low-hanging fruit. Usually, there are small things that you can do that have a fairly big effect on speed. So I would definitely double-check those things. I realize it's sometimes tricky with smaller sites, sometimes tricky if you're focusing on a specific region of the world and you know Google's data center isn't nearby. But there are almost always things that you can do to significantly improve the speed.  

#### [0:37:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2250) |  Related to schema, Google says JSON-LD is

the preferred format, but JSON-LD is JavaScript, and JavaScript is bad, or takes longer to be processed. I'm paraphrasing. Sorry. So yes, JSON-LD is JavaScript, but it's essentially provided directly on the page itself. So that's something that we can process right away, that all scripts can just extract from the HTML directly.  

#### [0:38:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2280) |  So it doesn't need to be rendered

to be viewed. It works right away. So there's definitely no disadvantage to using JSON-LD compared to using micro-data or some of the more HTML-based formats that are out there. We recommend JSON-LD because it's easier to implement because it doesn't have to be interwoven within your HTML. It can be one big chunk that you put on the top or the bottom of your page. And we can extract that and we can use it in one place,  

#### [0:38:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2310) |  rather than having to parse the old

HTML download of a page. Product structure data descriptions and H1 tags. It's my understanding that meta descriptions and product markup descriptions are two things. For a product markup description, is there best practice for number of characters, description? As long as a product markup description matches  

#### [0:39:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2340) |  a product appropriately, is there a need

to worry about the length? I am not aware of any restrictions regarding the length of the description in the product structure data. But I would kind of look at it more from the perspective of, how will this be shown in search? And think about how much text it actually makes sense to show there. So if you have like a two-page article about your product, then maybe that's a bit too long.  

#### [0:39:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2370) |  If you have just like five words,

maybe that's a bit too short. Finding that sweet spot in the middle is something that you kind of need to look at on your own. And I don't think there will be one optimal length that works for all products, so I'd kind of focus in on that. With regards to the description meta-tag, that's similar. We don't have any guidelines regarding the optimal length of description meta-tag. So that can be longer.  

#### [0:40:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2400) |  It can be shorter, depending on your

pages. We don't use a description meta-tag for ranking, so there's no need to stuff keywords in there. It's really something where I would try to describe what your page is about. And like you mentioned, it doesn't need to map one-to-one to the product data, as well. For H1 tags, if a site has over 70% duplicate H1 tags across the site, does that harm SEO? Should H1 tags be diversified across the site?  

#### [0:40:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2430) |  So H1 tags are headings, usually the

primary headings of a piece of content on a page. Usually, I would recommend matching those headings to the actual content. So it's clearer for us this piece of content can be simplified or kind of titled with this specific heading that you have there. We use H1 headings for the content itself,  

#### [0:41:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2460) |  for the text on the pages there.

We also use it for images. So if you have images that are within this chunk of HTML that's below a heading, then it's easier for us to say, well, this heading definitely applies to those images because they're the visible part of this page. So with that in mind, using the same heading across the site and larger parts of a site is kind of wasting signals that you could be using to give search engines more information  

#### [0:41:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2490) |  about the actual content on your pages,

where if you're just using the same thing over and over again, then we say, well, we've seen this heading before. It doesn't help us to differentiate which page on your website is the most suitable for this question that a user is currently having. So it's not so much a matter of harming your SEO, but you're not taking full advantage of all of the signals that you could be sending to search engines. Multi-language websites and URL structure.  

#### [0:42:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2520) |  I took a look at this one

beforehand, so I'll simplify it, as well. Basically, you have some English URLs like /aboutus, and then you have some French URLs, which would be /fr/contactenous, which would be kind of like the French words for about us, or contact us, in this case. Does Google have a harder time figuring that out,  

#### [0:42:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2550) |  or is that OK? So from our

point of view, that's totally fine. If you use hreflang annotations between these URLs, that's perfectly fine. Having a clear language or country code in the URL structure makes it easier for us to understand the language or the country versions if you're not telling us about it with a hreflang. But if you are already telling us about this with hreflang, then we would already figure that out.  

#### [0:43:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2580) |  So that's kind of the main thing

there. With regards to the language itself, usually that's also less of a problem because we try to understand the language of a page based on the content of the page. So if you give us a French URL, a French page, and the URL is just 1, 2, 3, 4, we will still understand that that's a French page. And similarly, if you give us an English page and the URL is 3, 4, 5, 6, we'll still  

#### [0:43:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2610) |  understand that's an English page, even if

the URL doesn't have a clear identifier telling us this is in English, or this is an English keyword associated with that page. So the URL itself is not something that I would use as a critical signal to say this page is in that language. If you're using hreflang, then I would not worry about this at all. If you're not using hreflang, then having a clear like language or country ID in the URL  

#### [0:44:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2640) |  makes it a little bit easier for

us to guess. But probably, we'll figure it out anyway. Wow. Lots of questions left. Let me see. We have 10 minutes left. So maybe I'll just open it up for questions from your side. And if nothing comes in, I'll continue down the line.  

#### [0:44:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2670) |  BARUCH LABUNSKI: Yeah, I wanted to know--

very long URLs, I mean, how long should a URL be, according to your data? JOHN MUELLER: How long should a URL be? So you can pretty much make it as long as you want. I think some of our systems are--  

![](https://i.ytimg.com/vi/WyeHvNvibuY/maxres3.jpg)



#### [0:45:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2700) |  like for web search, I think we

can pretty much deal with everything. I think in Search Console, it's limited to something like 2,000 characters per URL. So that's a pretty long URL. So I don't know. I'd focus on shorter URLs. I think it's easier to diagnose and to troubleshoot and to monitor all of that if you have short URLs with a nice structure on them. But sometimes you have crazy parameters with IDs in them  

#### [0:45:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2730) |  and they get a little bit longer.

But 2000 characters is a lot of room. BARUCH LABUNSKI: So those tools that show, hey, don't exceed 140 or whatever, you can ignore that? JOHN MUELLER: I think those are good practices. But it's not that there is a critical limit. Definitely not 140. It's more like around 2,000. BARUCH LABUNSKI: OK. Thanks.  

#### [0:46:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2760) |  JOHN MUELLER: So quiet today. RODRINGO MACEDO:

Hello, John. JOHN MUELLER: Hi. RODRINGO MACEDO: Hi, how are you? JOHN MUELLER: Pretty good. How are you? RODRINGO MACEDO: Fine, thank you. So I have two questions. We have a 200 e-commerce site and we used to have a category pages and product pages at the same crawl depth. So that left thinking that those URLs might be competing with each other.  

#### [0:46:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2790) |  So we took the 10 category pages

and raised them up a little. Is this something that would take a while to process? JOHN MUELLER: It definitely takes a bit to process, to re-understand that structure. But I think it's a good idea to do that. The main reason why I think it's a good idea is that, in general, with most sites,  

#### [0:47:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2820) |  the closer things are linked from the

home page, the more frequently we crawl them. So especially with the category pages, that's one place where new products, for example, would show up fairly quickly. So it makes sense for us to crawl those category pages a little bit more often so that we don't miss any new product that you put on your site. That doesn't mean that the category pages will have more weight in search, but more that we can find those new products a little bit faster.  

#### [0:47:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2850) |  And if people are searching for those

new products, we can show them a little bit earlier. So that's generally why I would recommend this kind of structure where you have kind of the home page, and then maybe the category pages, or something in between, and then that leading off to the individual product pages. RODRINGO MACEDO: OK. So the other one is, looking at our internal linking report in the Search Console, I see some long ago dropped URLs  

#### [0:48:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2880) |  from index in the part that says

URL pages linking through to this page section in each top link page. So does this mean that Google is still taking this into consideration for ranking purposes? JOHN MUELLER: That means we still have it in our database, essentially. But if it's a really old page, then we  

#### [0:48:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2910) |  would keep that in there until we

can reprocess that old page and drop it out. So if we haven't re-processed that page in a really long time, then there is minimal value in that page, from our point of view, in that link especially. So usually that's a sign that we've seen this. We know it used to exist. Maybe it exists now, maybe it doesn't. We don't really know for sure. But we haven't had a chance to look  

#### [0:49:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2940) |  at this page in a really long

time because we don't think it's that critical to check that frequently. So for the most part, you can ignore that. It's essentially just we found it, we want to tell you about it. It might be something that's older that you don't really need to worry about. RODRINGO MACEDO: OK, thank you. BARUCH LABUNSKI: So I took it a look at in Search Console,  

#### [0:49:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=2970) |  basically when you submit a sitemap, it's

not like the old-school Search Console where you would submit the sitemap, you would see something right away. But now you have to wait. Is that correct with the sitemap stuff? Because there's a delay in sitemap for some reason. Like the last we crawled November 6,  

#### [0:50:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=3000) |  I'm just trying to kind of troubleshoot

the thing as I'm talking to you in Search Console for that particular site. But it's saying last crawl was November 6. And then even though you submit it, you know-- JOHN MUELLER: Yeah. I don't think there is the resubmit button that used to be in the old Search Console. Yeah. So what you could do is do an HTTP ping for that URL.  

#### [0:50:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=3030) |  So there's a special URL that you

can construct, and you just open that URL up in a browser, and it has a text that just says thank you for submission. And that essentially reprocesses the sitemap file. The link for that should be in the Help Center somewhere. Yeah, I would try that.  

#### [0:51:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=3060) |  All right. BARUCH LABUNSKI: [INAUDIBLE],, right? JOHN

MUELLER: Sorry? BARUCH LABUNSKI: You'll take a look at it, I guess, when you get a chance? JOHN MUELLER: Yeah. In the chat, let's see. There's some things around security alerts with injected content. I probably need to have some examples there.  

#### [0:51:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=3090) |  So if you-- ALEJANDRO TORRES: I can

give one about the content injection. JOHN MUELLER: OK, sure. ALEJANDRO TORRES: So we had a security issue for content injections, but it's blocked pages that haven't been re-indexed for three months. So how do we get those pages re-indexed? JOHN MUELLER: Submitting a sitemap file would probably be a good idea. If it's just individual URLs, you can use inspect URL and submit those there.  

#### [0:52:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=3120) |  So if you just want to double-check

that it's actually OK, then I would use inspect URL for that. One thing I've seen on and off is that hackers, when they inject content in your pages, they also add some cloaking to those pages, so that when you look at it in a browser, it looks OK. But when Googlebot looks at it, it still has the hacked content. And with inspect URL you can double-check to see what content Googlebot would actually see, as well.  

#### [0:52:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=3150) |  So that-- ALEJANDRO TORRES: The thing that

we're using is using core command, using different user agents, and then comparing the content. Everything's good. It's just about re-indexing those pages again. JOHN MUELLER: Yeah. If it's just a handful, I would just use inspect URL and do it manually. I believe there is also someone that created a script that does a little bit more automated, but there's some limits with inspect URL. So if you really have a lot of URLs that you need to submit, I would just use a sitemap file.  

#### [0:53:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=3180) |  Let's see. Our reviews on Google Business,

a ranking factor not for web search. I don't know how that's handled within Google My Business. I could imagine that maybe they do use them, but for web search, we don't use them. Will the next Webmaster Conference be in German or English? So we have one in Zurich that's lined up. I think the plan is to have the registrations all sent out  

#### [0:53:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=3210) |  today. We're a little bit behind there,

but we said we would do it by today, so we've managed to get that out today. It'll be in English, so the content will be kind of available to everyone. It's a little bit bigger. We have people from external, as well, who are presenting something. So I think it'll be cool. We also have one lined up in Tel Aviv.  

#### [0:54:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=3240) |  So if you're closer to that, that

might be an option, too. We have some old low-volume pages with mobility issues in Search Console, but they haven't been re-indexed in three months. How can we force re-indexing to get the error to go away? So if it's flagged as a coverage issue in Search Console, then you can request the verification through Search Console, which will speed up crawling a little bit of those pages,  

#### [0:54:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=3270) |  so that we can get through those

a little bit faster. But otherwise, I would focus just on sitemap files, kind of like before. Let's see, there's another question about BERT. How would BERT affect Chinese search queries? I think, at the moment, it doesn't affect it at all. So in the blog post, we explicitly said it was for English content. Some of these kind of natural language understanding models  

#### [0:55:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=3300) |  are very language-dependent, and we need to

figure out how things work well in one language first before we can generalize them to all other languages. So sometimes, that takes a little bit of time. I could imagine, especially with languages like Chinese, where lots of variations, and where it's a lot harder to extract the meaning from a sentence, that might be a little bit harder. But I'm pretty sure there are people working on that, too.  

#### [0:55:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=3330) |  OK, I'll just continue going down the

list until any of you step in with questions from your side. Does Google ever strip off parameter values for manage parameters when crawling URLs? I find I'm seeing empty applied parameter values in my log files, but not in their internal linking.  

#### [0:56:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=3360) |  Could these be legacy URLs that Googlebot

have seen in the past? They could be legacy URLs. They could be things from the parameter handling tool where we're just dropping the parameter values because the parameter handling tools says the value is irrelevant. We do try to figure that out algorithmically, as well. So the parameter handling tool is your way of telling us about this. But a lot of people don't use that tool, which is fine. So we try to figure that out, as well.  

#### [0:56:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=3390) |  A really common use case-- or used

to be really common-- is session IDs in URLs, where every time you access a page, it would use a different session ID as a parameter. And that's something that we also try to understand automatically so that we don't overload your server crawling all of these session IDs. So that's kind of a really simple example, but that applies to a lot of other parameter values, as well. The more we can optimize our crawling for your website  

#### [0:57:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=3420) |  by limiting the parameters that we use,

the more we can crawl more efficiently, which means the more frequently we can crawl your important pages. So that's kind of a win-win for everyone. ALEJANDRO TORRES: I have another question about [INAUDIBLE],, if there's time? JOHN MUELLER: All right. Go for it. Woo-hoo. Live question. ALEJANDRO TORRES: So I know that you talk about picking low-hanging fruits, but I would like to know what Google uses for ranking.  

#### [0:57:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=3450) |  Are they using the score? The performance

score? Are they using the speed index for first content to pane? Which one are they using for the rankings? JOHN MUELLER: Everything. Well, probably not everything. But we use a mix of lab data and real world data. So it's not that we focus on any specific score, or that we would say that we use any specific score,  

#### [0:58:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=3480) |  but we try to use a mix

that matches what we think is representative of speed for that website. So that on the one hand, it makes it a little bit trickier because you can't see exactly what score Google is focusing on. On the other hand, that makes it a little bit easier for us because, over time, when new kinds of metrics come up which we can better understand the speed for, we can use those, rather than being tied to some old school  

#### [0:58:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=3510) |  score or test that's happening. So that's

kind of the mix that we try to apply there. So if you want to kind of do SEO just for speed, then I would focus on speed in general, and focus on the areas where your site is being seen as slow, rather than trying to just take one metric and try to get 100 on that. So we used to see this a lot which page speed  

#### [0:59:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=3540) |  insights, where people would say, I'm going

to optimize my site until it has 100 there. And you can optimize a site to have 100 there without it actually being a fast website. So there are tricks you can use to make it look like it's really fast to a specific testing tool, but it's actually still pretty slow for users. So instead of doing that, I would recommend making sure that, across the board, your site is pretty fast.  

#### [0:59:30](https://www.youtube.com/watch?v=WyeHvNvibuY&t=3570) |  All right, let me take a break

here to parse the recording. If you want, you're welcome to stay on and we can chat a little bit more. But anyway, it's been great having all of you here. Thank you for submitting so many questions and bringing questions into discussion, as well. I hope you found this useful, and maybe we'll see each other again in one of the future Hangouts. Thanks a lot, everyone.  

#### [1:00:00](https://www.youtube.com/watch?v=WyeHvNvibuY&t=3600) |  BARUCH LABUNSKI: Thank you.  

