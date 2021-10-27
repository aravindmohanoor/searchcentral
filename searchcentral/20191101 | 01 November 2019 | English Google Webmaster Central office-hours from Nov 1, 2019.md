[![English Google Webmaster Central office-hours from Nov 1, 2019](https://i.ytimg.com/vi/hNXSqRM7Xfs/maxresdefault.jpg)](https://www.youtube.com/watch?v=hNXSqRM7Xfs)

## English Google Webmaster Central office-hours from Nov 1, 2019

This is a recording of the Google Webmaster Central office-hours hangout from Nov 1, 2019. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Watch out for new sessions, and add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



Feel free to join us - we welcome webmasters of all levels!



Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=0) |  JOHN MUELLER: All right. Welcome, everyone, to

today's Webmaster Central office-hours hangout. My name is John Mueller. I'm a webmaster trends analyst here at Google in Switzerland. And part of what we do are these office-hour hangouts where webmasters and publishers can join in. [CLANGING SOUNDS] And there's a bit of a noise. Where webmasters and publishers can join in and ask their questions all around web  

#### [0:00:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=30) |  search and their web sites. There are

a bunch of questions submitted, but I know at least one of you is here at a really late middle of the night time. If you want to get started with your questions, feel free to jump on in now. BRANDON D: Sure, yeah. If I may, I have a couple. So first question is, let's say there's a website where users can rate poems that other users write.  

#### [0:01:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=60) |  Given the update to the ratings and

reviews rich snippets, we're no longer able to support the creative work property with the aggregate rating schema for rich snippets. So what do you suggest, given that our users do rate these poems and we'd like for those to show up in the search? JOHN MUELLER: You'd-- yeah. I mean, from a technical point of view  

#### [0:01:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=90) |  you'd need to use the type of

schema markup that matches the primary object of the page. And if that's a poem and that only works with creative work, then that-- those reviews would have to be based on that. And we might not show that in the search results. So I don't think there's much of a way around that. It wouldn't be that you'd be able to say, well, this poem is suddenly a product,  

#### [0:02:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=120) |  and we'll let people review it based

on that. Kind of is what it is there. So I don't know if there's a real work around to making those available in search. BRANDON D: I see. Yeah, it didn't really seem like there was any property that made sense. I think the closest one was "media object," but even that was a bit of a stretch.  

#### [0:02:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=150) |  JOHN MUELLER: Yeah. BRANDON D: But OK.

The other question is let's say a website-- you search for keyword "x" and a domain that usually ranks for similar keywords doesn't show up on page one, even page two or three. And at the bottom of the search, I believe this would occur on page 1, there is sometimes a Show Omitted Results link.  

#### [0:03:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=180) |  And upon clicking that link the domain

that didn't show up now appears. So what would cause that domain to be originally omitted from the results? JOHN MUELLER: So the Show Omitted Results link in the search results is basically shown when we would have multiple results that would show the same snippet or same preview, essentially. So that's something where we find  

#### [0:03:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=210) |  it doesn't make much sense to show

users the exact same snippet in the search results multiple times for different pages. So we try to pick one of these pages and show that one. And with the omitted results link you can kind of see the others as well. So if a website is only visible when you click on that, usually that's a sign that we found the same content somewhere else and we're currently just ranking that version rather than the version  

#### [0:04:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=240) |  on that particular website. BRANDON D: OK.

That sounds good. Thank you. And I do have one last one. Let's say a website has a lot of URLs. Let's say it's 100 million. And of those that are called daily by Googlebot, maybe a tenth of a percent are 410 status. Now, at some point in time, let's say maybe overnight,  

#### [0:04:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=270) |  that website decides to remove 20 million

URLs simply because they're no value to users. Some of these might be crawled by Google fairly often, some of them might even be indexed. But now that these 20 million URLs are removed, let's say most of them end up getting a 410 status and Google starts crawling-- of the URLs that Google crawls on a daily basis, let's say a large percentage of them now have this 410 status.  

#### [0:05:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=300) |  So instead of it being a tenth

of a percent, maybe it's 5%, maybe it's 7%. What signal might this send to Googlebot despite ultimately improving the quality of the URL that it could crawl? JOHN MUELLER: That's essentially a non-issue for us. So when it comes to ranking, that wouldn't change anything. It's not a bad sign. It's not a good sign. It's essentially just you have fewer URLs.  

#### [0:05:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=330) |  With regards to crawling, in the short

term probably not much would change. We would still try to crawl these URLs, even if they return 404 or 410. And in the long run, we would probably concentrate our crawling more on the URLs that do return 200, where we've seen the other ones that return 404 or 410, we just don't crawl them as frequently. So from a ranking point of view, nothing really would change there. It might be that you would see kind of a subtle effect of kind  

#### [0:06:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=360) |  of the concentration of the value more

on the pages that you have left. But it definitely wouldn't be a negative effect. BRANDON D: I see. So Googlebot wouldn't, let's say, perceive this change negatively despite the significant increase in 410 status URLs? JOHN MUELLER: Yeah. That definitely wouldn't be a negative thing. I mean, 404, 410 is essentially just a sign that these URLs  

#### [0:06:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=390) |  no longer exists. And sometimes a lot

of URLs don't exist anymore. But that's not a sign that the rest of the website is bad, or that anything is kind of broken and we need to be more cautious with crawling. It's just, well, those URLs don't exist. We have the other ones that do exist. We'll focus on those. BRANDON D: OK. All right. I appreciate it. Thank you for the answers. JOHN MUELLER: Cool. Thanks.  

#### [0:07:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=420) |  Anyone else want to get started with

a question before I jump into those that were submitted? No? OK. Maybe along the way. We'll see. All right. Today I got a message from Search Console. "Seems lots of people get messages from Search Console saying that my website has the following issues-- text too small, clickable elements too close,  

#### [0:07:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=450) |  content wider than your screen. However, my

site successfully passed Google's mobile friendly test and no issues were found. Is that a bug? Should I take any action?" So I get this question from time to time. I think it's-- on the one hand, it's a little bit confusing on our side in Search Console. On the other hand, sometimes I think it's also OK to flag these kind of issues. So practically, what is probably happening here,  

#### [0:08:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=480) |  without knowing the actual URLs that you're

looking at, my guess is what's happening is that these pages are mobile friendly. When we look at them in a mobile browser and they load completely, then we can see that they're mobile friendly. We essentially recognize that the text is readable, the elements are appropriately spaced, the content has the right viewport set, all of that. But what might be happening is from time to time when  

#### [0:08:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=510) |  we tried to render these pages to

test them to see if they're mobile friendly, something breaks. So we might have, I don't know, 1,000 pages that we're looking, that we're testing for mobile friendliness, and of those, every now and then something breaks. So we have a handful of pages that essentially don't pass the mobile friendliness test that we do on an automated basis. So in practice what would happen is we would flag those handful of pages to you in Search Console  

#### [0:09:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=540) |  so that you can take a look

to see if this is really something that is broken on those pages, which you can test using the mobile friendly test yourself, or if this is something that's kind of just-- kind of like a flaky test, where sometimes it works, sometimes it doesn't. And often with those kind of flaky tests, if it's not something that's significantly visible across your website, if it's really just a handful of URLs, then that's fine.  

#### [0:09:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=570) |  That can happen. If you're working on

a bigger website, then every now and then, something when we try to test it, it just won't work. The next time we test it, it'll be fine. So that's not anything that I particularly worry about there. I'm try and mute some of you, a little bit of background noise. So it's not necessarily a bug that we  

#### [0:10:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=600) |  would send you these messages. It's essentially,

my guess is we're mostly seeing that things are OK. And just every now and then that the-- the test doesn't work out. So we flag those. "What's the latest position from Google in terms of how much weighting it gives to content hidden behind "read more" dropdown links such as JavaScript functions, especially now that indexing is moving to mobile first and we're encouraged to design best practices for mobile users?"  

#### [0:10:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=630) |  So with mobile first indexing, if content

is loaded in the page, and it's just not visible, it's behind something like a tab or an accordion or something similar, then we will treat that as normal content of the page with the assumption that this is something that users can access if they recognize the accordion function, or the tab, or kind of the "read more" dropdown links, all of those things.  

#### [0:11:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=660) |  So that's kind of the easy part.

However, you dropped an aspect into your question that might be something that we'd see differently. Namely, you're saying this is behind JavaScript functions. So there is a difference from our point of view between functions, or kind of functionality that you have on the page that is loaded by default, and functionality that has to be loaded on interaction.  

#### [0:11:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=690) |  And functionality that is visible in the

page by default, which is in the HTML-- maybe it's not visible by default but it's in the HTML by default-- that's everything that we can pick up and index right away. However, if there's something on your page that needs some kind of interaction to load so that it's even in the HTML, for example, if you use JavaScript to load something from your database or from your APIs  

#### [0:12:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=720) |  and then show that to the user

when they click on something, then that's something that we would not know about. So we would not know where to click on your pages to trigger this kind of interaction with your server to load more content. So that's the aspect that just purely from a technical point of view, we wouldn't know what to do to load that content, so we wouldn't be able to index that content. However, like I mentioned, if it's already in the HTML,  

#### [0:12:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=750) |  if you can do "view source" or

"inspect element" and it's in your HTML by default, it's just not visible by default, then that would be fine. "With the likes of Facebook moving away from "likes" and with many leveraging fake "likes," what will Google do about social ranking signals?" So the good news here is that nothing will change, in particular because we don't use these signals.  

#### [0:13:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=780) |  So that's kind of-- yeah, makes it

a little bit easier, I guess, for you in the sense that we don't use these "likes" anyway as a ranking signal. So if a social network were to change those signals, then that's totally up to them. It's not something that would affect us in any particular way. A lot of the, or some of the reasons, I guess, why we don't use those signals is that purely,  

#### [0:13:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=810) |  it's really hard to even keep up

if we were able to crawl all of those pages. So you can imagine a large social network that it has a lot of content that keeps coming and going. And if we needed to refresh all of that content so quickly that we could pick up all of these social signals then that would be really kind of tricky. So we don't use those. "What scenarios would cause Google Analytics to report  

![](https://i.ytimg.com/vi/hNXSqRM7Xfs/maxres1.jpg)



#### [0:14:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=840) |  organic traffic as direct?" I don't really

know much about Google Analytics. So I can't really say anything particular to that. The only thing I heard over the years is something around redirects, where I believe redirects would lose their refer. But I don't know if that's actually correct or if that's just something I randomly heard. MIHAI APERGHIS: John, we actually  

#### [0:14:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=870) |  had quite a few sites we've worked

with that have had these issues. And sometimes redirects can be interesting. I'm not sure if 302 redirects or JavaScript redirects are the ones that do not pass the referral. 301s should do it well. One of the big issues I've noticed is with tracking issues due to cookie acceptance pop-ups where users might not accept the cookie right away.  

#### [0:15:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=900) |  They move to another page and they

exit the cookie pop-up and then the referral is false, the referral information is false. Or they do get, let's say, from Google to a landing page and they accept the cookie pop-up ad, in order to trigger the analytics count it does a refresh of the page. And that refresh actually uses referral information rather than just push it directly via Google Tag manager  

#### [0:15:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=930) |  or other ways. And this is when

that Google traffic or whatever other source gets treated as direct. JOHN MUELLER: OK. Now, that sounds complicated. So-- MIHAI APERGHIS: Yeah. JOHN MUELLER: Check in with Mihai, I guess. I can imagine now with all of those cookie banners and-- that it actually does the analytics just when you accept everything. That probably makes it a lot harder now.  

#### [0:16:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=960) |  Yeah. MIHAI APERGHIS: This is generally a

big issue, especially in Europe, with the GDPR pop-ups. There are all kinds of plugins or custom implementations that people want to use in order to make sure they are GDPR compliant. And sometimes this breaks the way Google Analytics is loaded and misses out on the referral information. JOHN MUELLER: OK. Good to know. So I guess in future I probably won't  

#### [0:16:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=990) |  be able to answer this question either,

but maybe that helps a little bit to understand what kind of situations you might be seeing that, and probably also why you would see a rise in this kind of traffic over the last couple of years. MIHAI APERGHIS: I highly recommend the Google Analytics forums. JOHN MUELLER: OK. MIHAI APERGHIS: They're-- really knows all about these issues, so yeah. JOHN MUELLER: Cool.  

#### [0:17:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1020) |  All right. So, "Name the top 10

ranking factors that Google is wanting from the publishers." Yeah, I don't really have a list of top 10 ranking factors, so that's going to be kind of awkward. I think in general, what I would recommend doing is on the one hand, making sure that you have a technically valid website that works really well from a technical point of view. And then on the other hand, focusing on making content that is something that people really  

#### [0:17:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1050) |  want to see, and that is unique

and compelling, and that's not just rehashing other people's content. Where you're essentially taking the expertise that you've gained over the years and presenting that to people who are really keen on picking up this kind of content. And that's not something that's easily refined into some magic number where you can say, "Well, I will focus on putting my keyword five times on a page."  

#### [0:18:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1080) |  If you have bad content, you can

put it on there six times or seven times and it still won't change anything. So that's kind of the two pillars that I would look at there. On the one hand, really, technically a valid foundation to work on, and a lot of the common CMSs, a lot of the common systems that are out there are, they do have really good foundations nowadays. Some CMSs have plugins that integrate things  

#### [0:18:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1110) |  like Search Console, Analytics, all of that.

For WordPress, for example, we just launched the Sidekick plug-in from our side, which is something that also automatically integrates Search Console, Analytics, and pretty much all of the various Google tools for publishers. So that might be an option. And then that alone is not something that will make your site relevant to users. So you can have a fantastic from a technical point of view  

#### [0:19:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1140) |  website. But if it's on topics that

people don't care about, if your content is not something that is really on par with the best of the best of that kind of content, then you're probably not going to see a lot of traffic in search. So those two sides, they do need to be [AUDIO OUT].. ITAY: Hi, Don. JOHN MUELLER: Hi.  

#### [0:19:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1170) |  ITAY: So I wanted to ask something.

First of all, happy Halloween. I like what you did with your hair. So my website is in a very spammy industry. And still we work very hard to create high quality content, original content. All of our articles rank very well and share to the community and bring a lot of traffic. We have great [INAUDIBLE],, big institutions, all that. So basically we really try to make  

#### [0:20:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1200) |  sure to follow Google's guidelines or recommendations.

But it doesn't matter what we do and how much effort we put into and how much hard work we do. Our rankings, they don't improve. And they actually, they started dropping lately. And some of our competitors clearly use scammy tactics that you guys always tell us to stay away from. And although it seems like we perform better than them on every single metric we're able to see,  

#### [0:20:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1230) |  they outrank us. And so-- and also

in the past we've had someone spam our website, thousands of spammy links we tried to disavow. But I'm not sure we were able to get all of them. So I kind of wondered, we're wondering if there's something going on that we're not aware of. We have any technical issue or something that you maybe were able to see, if there's anything spammy going on that we're not aware of.  

#### [0:21:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1260) |  JOHN MUELLER: Now that sounds like something

where I probably need to take a bit of time to look into that, or to pass it on to someone to take a look. If you want you can just post a link to in the chat here, and then I can pick that up afterwards. ITAY: Would it be possible to send it to you by email? JOHN MUELLER: Sure. You can also send it to me by email. I just can't promise that I'll be able to respond directly by email.  

#### [0:21:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1290) |  Because a lot of times, these are

things that I pass on to the teams, and they take that feedback and they work on that. But it's not that I'd be able to bring something explicit back to you and say, well, we fixed this, or we changed this, or you need to change this. A lot of times that's really just one way path to the engineering teams. ITAY: OK. I mean, so there won't be any follow up, but you would still have someone take a look at it? JOHN MUELLER: Sure. Yeah. ITAY: That would be great. And also I wanted to say I come very often to the series.  

#### [0:22:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1320) |  I was wondering if you were planning

to do another one of these hangouts where people come join you guys and join you in the hangouts like you've done last year. JOHN MUELLER: We should do that again. Those are always fun. We have the Webmaster Conference lined up in December in Zurich. That might be another opportunity. But think we should do that again. It always fun.  

#### [0:22:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1350) |  ITAY: When is it in December? JOHN

MUELLER: I don't know. It's beginning, maybe first or second week of December. ITAY: OK. That'll be nice. Anyway, thanks. Thanks a lot. JOHN MUELLER: Sure. Thanks. All right. I'll run through some more of the questions here, and then we'll have more time, I guess, for more questions. "If I started link building and built  

#### [0:23:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1380) |  200 links in two days and then

build zero links for two years, will Google see this as blackout and penalize me?" So I think on the one hand, we wouldn't see the building zero links for two years as blackouts and penalize a website. So that's kind of the one thing. On the other hand, if you're building 200 links in two days, it's not so much the number of links that you're building in the short period of time,  

#### [0:23:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1410) |  it's really just a matter that you're

probably building links in a way that would not align with our webmaster guidelines. And that's something where on the one hand, our algorithms might take action on that, or they might ignore those links. On the other hand, our manual web spam team might take action there and apply a manual action. So it's not so much the number of links in the time that you're talking about. It's really just the type of links that you're building,  

#### [0:24:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1440) |  or the type of link building that

you're doing in general. So if you're dropping links on random sites, if you're buying links in various places, if you're exchanging links using some kind of a weird linked network, all of those are things which would be against our webmaster guidelines, which would perhaps result in 200 links being built in two days. And since they are against our webmaster guidelines we do try to catch those algorithmically and ignore them.  

#### [0:24:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1470) |  And we do from time to time

look at these things from a manual point of view and we may take manual action on it. So really it's not the number in the period of time. It's really the type of activity instead. "Do external links pointing to pages with URL parameters set to crawl none in Search Console hold any value? For example, one parameter is only used to track affiliate links. Will setting that one parameter to crawl none effectively  

#### [0:25:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1500) |  block anybody?" So there are a few

things that can happen here. On the one hand, crawl none does not mean we will never crawl it. If you want something never to be crawled, use the robots.txt instead of the parameter handling tool. With the parameter handling tool we will still occasionally crawl these URLs to kind of see if things are set up properly. So that's kind of one part there.  

#### [0:25:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1530) |  The other part is what often happens

with these parameters when they're set in the parameter handling tool is that we try to figure out what the canonical URL is for those URLs. So you might have one URL setup with a parameter where you say, well, ignore this parameter or don't crawl this parameter. But that doesn't mean that we would not try to figure out what the canonical URL for this URL is. So with the canonical URL, we essentially  

#### [0:26:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1560) |  mean the URL that we would try

to index for that piece of content. So for example, if you have an affiliate parameter that you have that you're passing there, and we've seen that this affiliate parameter can be ignored and that we can find the same content without the affiliate parameter, it might be that we have that connection kind of learned in our systems between the URL with the affiliate parameter and the URL without. So if you use Inspect URL in Search Console  

#### [0:26:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1590) |  with the affiliate URL with the parameter,

it's possible, but it's not guaranteed that we would know that the canonical of that URL with the parameter is the one without the parameter, for example. And when that happens, if we have a canonical URL for a link target, then we would change that and say, well, this link technically points to this URL on your website.  

#### [0:27:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1620) |  But we know this URL is equivalent

to that one. So we will kind of route that link to the URL that we have as a canonical. So that would essentially mean that it's the same as having a rel=canonical on these links or redirect, where you're saying, well, from this URL with the parameter we're redirecting through the other one. You could of course also use a rel=canonical, you can also use a redirect. All of those things also make sense. And they help us to figure out what the canonical URL should be.  

#### [0:27:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1650) |  So that might be another option to

do that. The other thing just to mention is that in general, we recommend using "nofollow" or rel="sponsored" for affiliate links because those links are essentially there because of a financial relationship between the affiliate site and the destination site where the links are going. So if you have a rel="nofollow" or the rel="sponsored" there,  

#### [0:28:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1680) |  then in general we wouldn't be passing

any value anyway. So you wouldn't need to worry about this in particular. But those are kind of the different aspects that all play into this. So it seems like a simple question, but lots of things that can play a role here. MIHAI APERGHIS: John, just a quick follow up. So the rel=canonical tag doesn't clash with the URL parameter settings in any way. So it doesn't even make sense to use the URL parameter settings  

![](https://i.ytimg.com/vi/hNXSqRM7Xfs/maxres2.jpg)



#### [0:28:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1710) |  if it's rel=canonical in place. JOHN MUELLER:

So with the parameter handling-- with the parameter setting, we would crawl those URLs much less frequently. So if you're seeing a problem that we're crawling too many of those URLs, finding the rel=canonical and then going and crawling the canonical, then with the parameter handling setting you can kind of simplify that. For most websites, crawling like that is not an issue.  

#### [0:29:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1740) |  It's not that it would break anything.

If we crawl all of those URLs. So I'd try to avoid using those settings, just because it's-- I always find it's a very tricky setting. And if you set it up wrong then suddenly we will not crawl things, and then maybe we'll actually miss something. So with the rel=canonical, at least if something goes wrong we'll still have that one URL that we can still crawl. ITAY: OK.  

#### [0:29:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1770) |  JOHN MUELLER: OK. Let's see. Somehow these

questions are all being cut off a little bit. A question forwarded from the last hangout. "I received a security issue on content injection via Search Console for certain pages. I followed the steps, but I didn't find anything on the pages that's related to spam. Is there a chance to have a"-- and it cuts off. Let me see if I can refresh and get the rest of the question.  

#### [0:30:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1800) |  Oh, here we go. "--To have a

look to see if it's a false positive." What often happens here is-- so I guess there are two aspects here. On the one hand, sometimes we get it wrong and we think that something is hacked when it's actually normal content. So that can happen if you have a bigger website that also includes some content that kind of looks like the type of content that hackers would put on pages, which might be around pharmaceuticals,  

#### [0:30:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1830) |  or I don't know, casino, gambling type

content. If that's mixed in with the rest of your content we might think, well, this seems a little bit odd. And those are kind of issues that we would love to have flagged. And on the other hand, hackers also use a lot of cloaking techniques to hide kind of the hacked content that they put into your site from the webmaster. In particular, they want to get this content indexed in Google, or they want to use it or phishing purposes,  

#### [0:31:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1860) |  or something like that. And to make

sure that it stays around for as long as possible they'll try to find ways to hide it from webmaster. So they might do things that only show it to Googlebot user agents or Googlebot IP addresses. So it's really kind of tricky to find. What I would recommend doing here is maybe checking in with the Webmaster Help forum. The folks there have a lot of experience with these kind of questions. And they can pretty much take a look  

#### [0:31:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1890) |  at that using the tools that are

available to check to see what Googlebot would see, or guiding you to using those, and to find out more if it falls into the category of someone is hiding something on your website or if it falls into the category of well, this is maybe a bug that we should tell Google about. And they can also escalate it if they're issues that Google needs to know about.  

#### [0:32:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1920) |  "One of my websites provides information about

various schools in my country. Each school has its own page with its own unique aggregate rating based on reviews which my visitors submit. However, even though I followed all the guidelines, my aggregate ratings don't show up in the search results. What am I doing wrong?" Good question. I don't know in particular what is showing up on your site. So that's kind of tricky to say. I'd also primarily suggest going to the Webmaster Help forums  

#### [0:32:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1950) |  to double check that with other folks.

But in general, there are few things that can be playing a role here. On the one hand, we've started showing review-rich results only in a certain number of cases. So it might be that the type of content that you have with the reviews that you have doesn't fall into the category of content that we would show in the search results. And if that's the case, there's nothing really  

#### [0:33:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=1980) |  that you can do there. It's essentially

a policy decision on our side that we would not show reviews in the search results for that kind of content. I would not recommend trying to circumvent that by saying, well it's actually not this kind of content. So for example, if people are reviewing schools and you turn that around and say, well, this is a recipe actually. It's not a school. Then that's something that from our side, on the one hand  

#### [0:33:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2010) |  we would try to recognize algorithmically. On

the other hand, the manual web spam team would probably take a manual action on things like that. So I would not recommend doing that. That's kind of the one thing that comes to mind immediately there. The other thing is in general for rich results we have different things that we try to make sure that they apply before we show them in the search results.  

#### [0:34:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2040) |  So independently of reviews or not, in

particular the markup has to be technically correct. So using a testing tool to see that it's correct is important. Then the markup has to be such that it's kind of logically correct as well in the sense that you're marking up things in a proper way, that the item that you're marking is really the primary item of the page, that it's the right type of item. Like I mentioned, if it's a school, don't mark it up as a recipe.  

#### [0:34:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2070) |  That's the other thing. And then finally,

we need to be sure that the website is of a reasonable quality so that we can kind of trust that the information that you're providing with structured data is something that we would like to show in the search results. So those are all kind of the different criteria that come to mind with rich results in general. And especially with the review-rich results that we show in search.  

#### [0:35:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2100) |  The other thing that I mentioned, we

have a blog post specifically about the changes in review markup I think from maybe two months ago, something around that. "On my site there was an issue with an author page. It was redirected on my home page, And there were too many 301 re-directions after the core update, and my site traffic went down. Now I fixed it. How much time will it take to restore?"  

#### [0:35:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2130) |  So I guess the good news is

301 redirect would not negatively affect your site when it comes to changes like the core updates. 301 redirects would only cause a problem if that content were not accessible at all. So if you have kind of a circular amount of 301 redirects where you redirect to one URL and you redirect back, and that redirect goes back again, then we wouldn't be able to load that content.  

#### [0:36:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2160) |  Then that would drop out of search,

and then that would no longer rank. But it's not the case that if you have a redirect from one page to another-- maybe you changed some URLs, maybe you moved a part of your website within the website, that that would be a reason for us to drop a site in search. So in particular, if you're seeing changes after one of these core updates that we've announced, then that's something that from our point of view is not an issue on your website.  

#### [0:36:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2190) |  It's essentially our algorithms thinking, well, maybe

we judge the relevance of this website for those queries incorrectly, and we're trying to improve that. And these things are things that can change over time as well, where we think, well, in the past we thought this was more relevant. And now we've seen that people see something else a little bit more relevant. So we'll trying to adjust our relevance criteria.  

#### [0:37:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2220) |  So it's not so much that you're

fixing something and that it comes back, but rather if your site is no longer as relevant as it used to be, then you can work on making your site more relevant and making your site better in other ways. So it's not you're fixing it and it comes back, but rather you're improving it, and it improves in search over time. We have a blog post about core updates as well from sometime this summer,  

#### [0:37:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2250) |  where I would take a look at

that as well. It has a whole bunch of things that you can look at that we recommend folks kind of ask themselves in a serious way to figure out what they can do to improve their site overall. "Is there any impact if the path of my URL is 404 or even 310?" So if you have like a domain.com/path/path and [INAUDIBLE] and a page name, If one of those path URLs alone  

#### [0:38:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2280) |  is a 301 or a 404, no,

absolutely not. So if we find links to that path directly, then we will see that as a 404. We'll see a link to a 404 page. Like maybe they're out of 404 pages on your website. That's fine. It happens. But it's not the case that we would take a URL and split it into pieces and try the individual pieces out,  

#### [0:38:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2310) |  and if they don't work, then we

would throw away the rest. We understand that these URLs are essentially identifiers. And sometimes the path that you specify in there, they're not actual folders with files on them but rather essentially identifier that is telling us under this long URL we have this content. And what might be if you split that URL up into pieces, that's essentially kind of, well, we didn't  

#### [0:39:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2340) |  tell you to look there, so you

don't need to double check that. So from our point of view, if part of the path does not work, that's perfectly fine. "My client paid for PR in local newspapers and wants to post it on their website. What's the best way to do this to enhance SEO?" So I guess kind of taking a step back in general,  

#### [0:39:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2370) |  if you're paying for PR in a

newspaper, then that's something from my point of view shouldn't necessarily be affecting your SEO. So it shouldn't be the case that you would kind of pay to have more, I don't know, visibility in search. If there are links in these PR articles that are only there because you paid for them, then they should be appropriately marked with a rel="nofollow" or rel="sponsored" to kind of let search engines know that this link is a part  

#### [0:40:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2400) |  of a paid article, for example. That

can still make it useful for users. And that can still mean that you can refer to it on your website. It's just that those particular links, they wouldn't be passing any signals to your website, which in general is fine. So doing this kind of promotion for your website for a business is perfectly fine, is perfectly natural. I think that's something that almost always makes sense,  

#### [0:40:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2430) |  where if you know that there is

an audience out there that might not know about your website or about your business and you want to bring your business kind of in front of them, then finding a way to talk to them-- which might be through a paid article like this-- is perfectly fine and reasonable. It might be that this audience keeps coming back to your website and then they recommend your website to other people, and then those links pass signals. That's perfectly fine.  

#### [0:41:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2460) |  But it shouldn't be the case that

your website ranks higher because you're doing paid articles on other websites. So kind of a direct SEO effect generally shouldn't be there. Indirectly, you can definitely see some effects there, too, where if your content is really good, your website is good, people will be happy to have gone to your website. And that's something that indirectly we might pick up.  

#### [0:41:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2490) |  "Ranking on some sites are related to

their authority, but I see some better content on sites without this authority that rank worse. Can we treat this as a monopoly of information?" So I don't know what a monopoly of information is. So that's kind of one thing. But I think the general complaint that I see in this question is, "We have a really good website.  

#### [0:42:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2520) |  And we think it's just not being

recognized as being a great website in search. And essentially, why are other web sites ranking above mine?" And this is, I think, a pretty basic question when it comes to SEO. It's not limited to authority or trustworthiness or any of the other fancy new buzzwords that are out there. It's really just a matter of, well,  

#### [0:42:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2550) |  some websites we show and we think

they're more relevant to show to users, and some websites we think they're maybe not as relevant to show to users. My general advice here, without knowing your website, without knowing your specific situation, is to make sure that your website is not just as reasonable as the others, as kind of useful as the others, but rather that it's significantly better. So that it's something where if our engineers were  

![](https://i.ytimg.com/vi/hNXSqRM7Xfs/maxres3.jpg)



#### [0:43:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2580) |  to run across this case, maybe the

forums or if you posted about this on Twitter or anywhere, if our engineers were to see, well, for this query, we're showing this website at number nine instead of number one, they would be able to look at that and say, "Well, this website at number nine is clearly, by far, the best of all of the websites in the search results page. We should find a way to rank it number one." And that's something that our engineers do take very seriously, if they see that we're  

#### [0:43:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2610) |  kind of really ranking something much worse

than it absolutely should be objectively looking, then that's something that they'll work to improve. It's not something that happens overnight. It's not something manual where they would say, "Well, we will just change the numbers behind this website at number nine to make it number one." But over time with our algorithms we do try to improve that. But the foundation of that is really that the website that you're looking at  

#### [0:44:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2640) |  is not just, "Well, we have just

as good content," but rather something that is significantly better. So that anyone who objectively looks at the search results page would say, "Well, this is a bug." It's not like, well, it could be this way, or it could be that way, but it's clearly a bug. It's like if you ask Google, "What is 1 plus 1?" and it ranks a website that says the answer is 3 on top and the answer 2 is, like, ranked at number nine.  

#### [0:44:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2670) |  Then objectively we're doing bad search results.

On the other hand, if the number one result says 2 as the answer and the number nine results says 2 as the answer, then those are kind of the same things. And it's not something where our engineers would look at that and say, "We need to fix this." But rather, well, it's the same thing. What difference does it make to users if we showed this one or that one in the first place? So really kind of stepping away from just focusing  

#### [0:45:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2700) |  on individual factors and really thinking about

what could you do to make your website significantly better, objectively better than all of the others that are out there for this particular topic. "An acquired domain that originally redirected to another domain, which currently has thousands of pages indexed"-- oh my gosh. It's a complicated question. "Domain.com redirect our cache and index.  

#### [0:45:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2730) |  I added 410 status and removed URLs

and Search Console, but I'm still seeing 5,000 results in the search results, valid URLs, index not submitted have dropped. Will those 5,000 results in search results drop, or do [INAUDIBLE] need to continue submitting URL removals on Search Console?" So I think--  

#### [0:46:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2760) |  I'm not 100% sure, the question is

a bit complicated. I think what is happening here is you're moving from one domain to another and we're still showing results from the old domain in the search results. In general, that's perfectly normal. That happens all the time. And that's something that our systems try to do, much to the dismay of SEOs who are explicitly trying to move things from one domain to another.  

#### [0:46:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2790) |  In particular, if you're looking for one

domain and we know that content on that one [AUDIO OUT] So if you do a site query for the old domain you will still see results. If you explicitly search for the domain, then we will still show those results. However, if you look at the cache page for those pages, then often you'll see that the cached URL is actually the new URL already.  

#### [0:47:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2820) |  So our systems know that the old

URL is an alternate version of the new one. And if you explicitly search for the old one, we'll show it to you, because we're trying to be helpful. But it doesn't mean that the search results that you would see there are as indicative of any particular problem. So I would not recommend using the URL removal tools for that. On the one hand-- I think there are two reasons for that. On the one hand, you don't need to because probably users  

#### [0:47:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2850) |  wouldn't see these in a normal search

result. On the other hand, the URL removal tool only hides things in search. It doesn't change indexing. So it wouldn't force things to shift over. It just hides them. So that when you do a site query, it's like, well, we would have 5,000 results. But you're hiding them. So we show you 2,000 results. So it doesn't really fix anything. So that's kind of the one thing there.  

#### [0:48:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2880) |  So I would avoid using the removal

tool for something like this. I'd use a removal tool for something that you really don't want to have shown in search, where if someone is searching for something and you removed it from your website because you urgently need to remove it, then you can hide it in the search results. Then it doesn't matter if it's indexed or not as long as nobody sees it. Right? If it's for example, you accidentally leaked some private information about the site owner, and you fix it on your site, and you just  

#### [0:48:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2910) |  want to make sure it's not shown

in search, then of course, go for it. Go for it and hide it. With regards to the other options there, setting 410 status code for these URLs or something similar, I would not do that. If you're moving from one domain to the other, then setup redirects. And in the worst case what can happen if we show your old URLs in search, that redirect will still bring users to the new site.  

#### [0:49:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2940) |  So in those cases, it's not that

you would have any negative effect from having your old URL showing in search, because users still make it to your new site. So those are kind of the things I would do there. In particular, just continue using the redirects. And don't worry so much if you're explicitly looking for a URL that we would show it. Because our systems try to be helpful. And as an SEO, as a webmaster, you're  

#### [0:49:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=2970) |  trying to find the objective answers, and

helpful system sometimes get in the way. All right. Wow. That looks a bunch more questions left, but also a bunch of things happening in here in the chat, which I haven't been able to catch up. Anything from you all that I should be covering next? AMOS GRIMA: Hey, John, it's Amos here. JOHN MUELLER: Hi. AMOS GRIMA: I'm touching on Google for Jobs again.  

#### [0:50:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=3000) |  We still face problems with our visibility

there. So I was wondering if you could point me in any direction, how we could improve our visits through Google for Jobs. I mentioned I think in a couple of hangouts ago that we did a migration and we saw a drop off. And I'm getting lots of pressure internally to give some directions to the team on how we can recover that. JOHN MUELLER: OK. I will prod the team a little bit more on that.  

#### [0:50:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=3030) |  Yeah. AMOS GRIMA: Thank you. AKSHAY MAKADIYA:

Hi, John. JOHN MUELLER: Hi. AKSHAY MAKADIYA: Hi, I'm Akshay, from India. I've got a question. What is the best way to combat plagiarism? For example, my competitor is stealing the design elements from my website that I created. And it is taking advantage of it as it is ranking over me, right?  

#### [0:51:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=3060) |  I have already reported that using the

Google Search Console under the copyright removal. But they say that for each of the following URLs, please identify the [INAUDIBLE] claim infringed upon the competitor. I had already tell this to your team, but they replied that it is unclear to us whether or not you are the authorized copyright agent for the content in question. So my question is that how can I prove my authenticity and ownership that, yes, I created this content and I'm  

#### [0:51:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=3090) |  the owner. And that website owner is

copying from me? So. JOHN MUELLER: I can't really give you legal advice there. So that's kind of the tricky part. In that I am happy to help with the technical side of these kind of things. But I can't give you legal advice with regards to what specifically you should be submitting. So I think the DMCA complaint is generally the right direction,  

#### [0:52:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=3120) |  if it's copyrighted content that someone is

taking. There might be some subtle differences there that you need to watch out for that I don't know about. AKSHAY MAKADIYA: Is it limited to the text part, or did you consider the UX/UI design [INAUDIBLE] as well, that if someone's stealing my image, like changing that hue or saturation, colors and reposting the same image on their website. So is it considered as a plagiarized content?  

#### [0:52:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=3150) |  JOHN MUELLER: I don't know. I mean,

I can't give you advice on that. That's something where you'd need to check maybe with a lawyer locally to make sure that what you're submitting really fits. I know there are sometimes sneaky people that copy things in sneaky ways where it's hard to differentiate if something is kind of just the copy or if it's actually a new work that is based on something else.  

#### [0:53:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=3180) |  But those are the kind of decisions

that I can't make because I'm not a lawyer. So I can't give you advice on that. It's something I see in the forums from time to time. What you might be able to do is double check in the Webmaster Help forums. I know there are some folks there that do have a little bit of a better feeling for the legal aspects there. But if you need legal advice with regards to what you can and can't do, then you really need to make sure that you contact a lawyer yourself.  

#### [0:53:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=3210) |  AKSHAY MAKADIYA: Sure. Thank you. JOHN MUELLER:

Sure. All right. BRANDON D: Hey, John, I have another question regarding flexible sampling this time. JOHN MUELLER: Sure. BRANDON D: So I-- it's about two years since flexible sampling was introduced. I know that there were a couple big publishers  

#### [0:54:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=3240) |  that Google worked closely with for a

few months. Namely, I think, "The New York Times." And we've implemented it on our sites, and we've seen via a couple tests some marginal improvement in organic search rankings. But I believe that given the limited information, and did some analysis of which publishers are currently  

#### [0:54:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=3270) |  using flexible sampling, some aren't even implementing

it correctly. For example Economist.com is not doing it correctly. I don't believe the BostonGlobe.com is doing it correctly, either. And given that we're an Alexa Top 1,000 site, essentially we feel almost as if flexible sampling has been a bit of a kind of neglected program. And given the size of the sites that we have and that Google has historically worked with publishers on this project, essentially I was  

#### [0:55:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=3300) |  wondering if there be a way to

work more closely with Google on this project. Especially given that we have a lot of data around the implementation of it. JOHN MUELLER: You're welcome to send me something, and I can pass that on to a team. But I can't promise that they would have time to look at this with individual sites. So, no.  

#### [0:55:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=3330) |  I think in general with flexible sampling

the one aspect that's always I think a little bit tricky is that you basically have to find that line of how much content you show to users by default and how much content is behind your paywall. You kind of have to figure that out yourself. In the sense that for some sites, for some queries, it might be OK to show minimal amount of information because users really, really, really want  

#### [0:56:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=3360) |  to get to your content. And for

other kinds of sites maybe it's worth showing a little bit more. So giving a few more pages that they can look at automatically, or having a bigger snippet on the kind of preview part that they can look at. So finding that balance, I think, is probably hard. And that's something that more than probably the SEO aspect has also a lot of indirect aspects that flow into that as well.  

#### [0:56:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=3390) |  Where if people always go to your

site and they never get any content, then maybe at some point they just won't go to your site as frequently. On the other hand, if they go to your site and they get all the content they need, then maybe they won't sign up. So finding that balance between those two sides is sometimes tricky. And it's not something that I'd say is a is a technical question, or a question that we can solve for web sites. But it's really something that you almost have to work out together with your users with user studies.  

#### [0:57:00](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=3420) |  But again, if you want to send

me some information that I can pass on to the team, feel free to do that. I can't guarantee that they'll be able to get back to you, but I'm happy to pass that on. BRANDON D: OK I appreciate it. Thanks. JOHN MUELLER: All right. Let me pause the recording here. You're welcome to stay on for a little bit longer if you'd like. But just so that we have a reasonable length  

#### [0:57:30](https://www.youtube.com/watch?v=hNXSqRM7Xfs&t=3450) |  for the YouTube video. Thank you all

for joining in. Thanks for submitting all of these questions so far. And I hope you all have a fantastic weekend. And see you next time. All right.  