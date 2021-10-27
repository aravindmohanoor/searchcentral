[![English Google Webmaster Central office-hours from September 4, 2020](https://i.ytimg.com/vi/UKt7sblTapM/hqdefault.jpg)](https://www.youtube.com/watch?v=UKt7sblTapM)

## English Google Webmaster Central office-hours from September 4, 2020

This is a recording of the Google Webmaster Central office-hours hangout from September 4, 2020. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Watch out for new sessions, and add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



Feel free to join us - we welcome webmasters of all levels!



Subscribe to Google Search Central → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=0) |  JOHN MUELLER: All right. Welcome, everyone, to

today's Webmaster Central office-hours hangout. My name is John Mueller. I'm a webmaster trends analyst at Google in Switzerland, and part of what we do are these office-hour hangouts, where people can join in and ask their questions around their websites-- SEO and Search and those kind of things. Bunch of stuff was submitted already on YouTube, which is great, but if any of you want to get started with the first question,  

#### [0:00:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=30) |  you're welcome to jump on in. SAIDUL

HOQUE: Hi, John. JOHN MUELLER: Hi. SAIDUL HOQUE: Hi. I have just gotten a question from one of our client. So the question is about language tech. Now, we know that we can add language tech in the header section of the [INAUDIBLE] or we can build XML site map to show our other version.  

#### [0:01:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=60) |  Which one is better, actually, with the

thing? JOHN MUELLER: So I think you mean the hreflang attribute? SAIDUL HOQUE: Yes. JOHN MUELLER: The hreflang? Yeah. Both of those are equivalent. There's-- like, we treat them exactly the same. SAIDUL HOQUE: Thank you. Well, I believe that he's asking this question because the site is built on WordPress, and if we want to add it to the header section, we need to use some plug-in,  

#### [0:01:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=90) |  and client is afraid that may reduce

the speed, something like this. That is why he is insisting to use XML site map. So do you think is this really a factor? JOHN MUELLER: I don't know if it would really affect speed, but it's certainly an option, just to use a sitemap file. And you don't have to use the same sitemap file that you use for the rest of the site. You can have kind of your normal crawling sitemap file, and you can set up a separate hreflang sitemap file just  

#### [0:02:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=120) |  for those language connections. So that's something

that sometimes it makes it easy to put it in a sitemap file, sometimes it's easier on the page for debugging. It's really up to you. SAIDUL HOQUE: Thank you. MIHAI APERGHIS: I guess there's also the option of HTTP headers, so that wouldn't require changing the HTML code, but it's still a bit more complicated to implement. JOHN MUELLER: Yeah. I guess especially on WordPress, you'd  

#### [0:02:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=150) |  have to do even fancier things. MIHAI

APERGHIS: Yup. JOHN MUELLER: Cool. Let me jump through some of the questions that were submitted, and hopefully we'll have some time towards the end as well for more questions from you all, or if anything comes up in between that fits, we can take a look at that. So the first one that I have here, I don't really know how much I can say here.  

#### [0:03:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=180) |  So it's about a domain migration. We

migrated from one domain to another on August 6 and it's like everything went bad, essentially. And there's a forum thread with a lot more information there. And it's-- from a first glance, looking at the sites there, it seems that it's kind of OK, so I suspect I'd need to look into that a little bit more in depth. So I'll take a look there and also see  

#### [0:03:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=210) |  if there is any escalation from the

forum thread that we can help with. Why exactly websites that have been hit by the core update can't recover before the next core update, even if they make good improvements? Some algorithms are launched one time for a couple of months, or how does that work. So with core updates, we're essentially trying to re-understand how the relevance of the search results are. And it's not something that requires a site  

#### [0:04:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=240) |  to kind of wait for the next

update to have a chance to be seen differently. They can continue working on things and things can improve over time. It's possible that our next core update will make a bigger change in the same direction that you've been working, and you'll see a bigger change in your site's performance as well. But in general, sites don't have to wait for the next bigger update in order to start seeing changes. So from that point of view, I wouldn't just, like,  

#### [0:04:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=270) |  stop working on things once you think

you've done the right thing, but I'd continue working in that direction. You should see at least some incremental improvements over time there. Are there any tricks to check a website or page if it has quality issues like this, for example-- a page doesn't show up in the first position for its own unique content, so something can be bad there.  

#### [0:05:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=300) |  I remember in the past, Google hides

rich snippets for low-quality pages. I don't know if there is any trick to kind of see the way that our algorithms assess the quality of a website overall or the quality of individual pages, because we do look at different things. With rich snippets, I think it's slightly different, because-- just because of the way that these are implemented there.  

#### [0:05:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=330) |  So with rich snippets, if you've implemented

them in a way that is valid with the validators, so valid from a technical point of view, if it's valid from a policy point of view, and if your website just isn't kind of of the quality that we would like to show rich snippets for, you can sometimes do a site query and check to see if the rich snippets would show up there. It's not something from our side that is done by design,  

#### [0:06:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=360) |  so it's not like a feature that

was added from the rich snippets [? team ?] that you could debug things this way, but more of a side effect. And it's also something where it's possible that at some point, this kind of side effect will get cleaned up to make it more consistent. I don't know if that's really important, because not a lot of people just do site queries on their own. But it is one of those things that's  

#### [0:06:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=390) |  kind of more of a side effect

rather than a purposeful decision. And for other kind of quality issues, I don't really think there is a clear way to understand how Google would see that. In general, when you run across quality issues on your website, or when you suspect you have quality issues on your website, then that's something where I'd recommend getting input from external people as much as possible rather than just purely looking at the search results.  

#### [0:07:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=420) |  So that's something where my general recommendation

is to take the questions that we have in the blog posts that we did for our core algorithm updates sometime last year, and look at them with people who are not directly associated with your website to see what do they think about your website-- when they're kind of experiencing it for the first time, when they have to complete a task on your website compared to other websites, maybe--  

#### [0:07:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=450) |  and to really try to get that

objective input from someone who's kind of fresh, who is not skewed from a technical point of view, who's not skewed because they know you and they think you always do fantastic work. So that's usually my recommendation there. We're considering changing our navigation on our e-commerce site, and we have a couple of queries. Can you tell relatively quickly whether a new navigation will have a positive or negative effect on a site's ranking once  

#### [0:08:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=480) |  deployed, or does it take a couple

of months for things to bed in and see? Also, can it affect things from an SEO point of view depending on where the links are displayed in the navigation or not? Do you have any other tips or advice on this and whether one can revert back to the old style of navigation if it has a negative effect? So the last part is definitely the case. If you make a bigger site-wide change on your website  

#### [0:08:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=510) |  and you revert that, you basically have

the previous situation. It's not the case that these kind of things will just flip back and you will have the previous state for your whole website, but rather we kind of have to reprocess that and understand your site again with the new state. In general, when you're making bigger site-wide changes on a website with regards to the internal navigation, that can definitely have an effect on SEO.  

#### [0:09:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=540) |  Usually it does. I mean, it's one

of those things that SEOs sometimes look at when they look at a bigger website. My main recommendation there would be not to change the URL structure unless you absolutely need to. So that's kind of on the side, because changing the URL structure on a website site-wide is something that does take quite a bit of time to be reprocessed. So if you can exclude that and purely focus on the navigation part, that  

#### [0:09:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=570) |  makes it a little bit easier. And

with regards to the navigation, the navigation for us as a search engine, I guess, serves two purposes. On the one hand, we need to be able to discover all of the pages on your website, so to be able to crawl through everything and find all of the content. And on the other hand, we need to be able to understand which pages are relevant or important in which context. So like, which of these pages belong together,  

#### [0:10:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=600) |  which of these pages is the most

important one, that kind of thing. And that's something that you can provide fairly well with a navigation on a website. So one extreme might be you link all pages to each other, and that makes it easy for us to crawl, because we have to look at one page and we find links to all of the other pages. But it makes it hard for us to understand which of these pages belong together and which of these pages are important. So finding a balance between everything really flat  

#### [0:10:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=630) |  and everything really kind of deep, where

you have to follow one link after another to find everything-- that balance is sometimes a bit tricky. But it is something where you need to kind of look for that balance and-- instead of just, like, purely taking an SEO crawling tool and saying, oh, it says my crawl depth is five, I need to change it to four. That's probably not the right approach. But sometimes these tools can give you some input on things  

#### [0:11:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=660) |  that you might have missed. MIHAI APERGHIS:

John-- [INTERPOSING VOICES] MIHAI APERGHIS: The URL parameter tool, since e-commerce sites tend to use it, especially given the parameters and everything-- will that ever be moved to the new search console? Is it planning to be deprecated? Are there any plans with the tool? JOHN MUELLER: The data there has been missing for a really long time, but that's not because we want to deprecate it.  

#### [0:11:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=690) |  It's just because things are weirdly stuck

on our side with kind of the various teams that are involved with creating that data. Internally, we use kind of similar data already. It's not that we don't follow that input at all-- it's just the data that we display in Search Console is kind of stuck just before it reaches Search Console. MIHAI APERGHIS: OK. JOHN MUELLER: And my understanding  

#### [0:12:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=720) |  is that that should get resolved fairly

soon. But I've been hoping that that's fairly soon for a while now. So I've been nudging a little bit more. Hopefully, that'll get better. With regards to moving to the new Search Console, my understanding is that they do want to kind of keep that functionality and move that to the new tool as well. I expect, especially for larger websites, we'll have some really cool stuff coming out  

#### [0:12:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=750) |  as well over time that-- yeah, it'll

be pretty cool. I don't want to pre-announce anything, so I'm not going to go into more details there. But it definitely is something that makes sense to focus on, like you mentioned, for e-commerce sites with a lot of parameters. You can clean up some things there and make it a little bit easier to crawl and index your site. MIHAI APERGHIS: But just out of curiosity, if you're already doing that using canonicals,  

#### [0:13:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=780) |  noindex tags, things like that, do you

also need to try to make sure the URL parameters tool is set so it kind of tells the same story, or-- JOHN MUELLER: No, usually not, usually not, yeah. Usually-- so from what I've seen, there are two situations where the URL parameter tool makes sense. Both are for bigger websites with a lot of parameters, but one is if you really can't set those parameters  

#### [0:13:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=810) |  with canonicals and things on your site

and internal linking and all of that, then it's a way to kind of bridge that. And the other is if you have an extremely large site and you have individual parameters that just blow up the whole crawl space, then that's something where it can make a big difference. So those are kind of the two situations, and it's really in both of those. It's for sites that are a little bit bigger.  

![](https://i.ytimg.com/vi/UKt7sblTapM/hq1.jpg)



#### [0:14:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=840) |  It's not the average kind of, I

don't know, 100,000 page e-commerce site. It feels kind of small in regards to what those tools are kind of meant for. MIHAI APERGHIS: Cool. KERN HOH: Hey John, since we are-- this is Kern here. Since we are on Search Console as well, just I've been facing some issue with the Search Analytics API, so just wondering how we could actually look into that or raise it in a sense that, if I look at my Search Query data  

#### [0:14:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=870) |  on my Search Analytics data, I see

impressions and clicks. But when I'm trying to pull the data via the API, it doesn't return any entries at all. JOHN MUELLER: OK. KERN HOH: And to add some context, half my-- like, on one of my domains, it's working perfectly fine. On the other-- on one of my subdomains, it's not looking. JOHN MUELLER: OK. My guess is that has something to do with the way the site is  

#### [0:15:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=900) |  verified. Maybe you have something like HTTP

verified in the API and HTTPS verified in the UI. Because the backend for both the API and the UI are exactly the same, so it's-- what commonly happens is that the absolute numbers are not exactly the same, because the queries are processed slightly differently. But it shouldn't be the case that you have no results in one and lots of results in the other. That definitely shouldn't be the case.  

#### [0:15:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=930) |  KERN HOH: So basically what I did

was that I used the exact same domain. So imagine if I have www.x.com and that's what I verified. And I took that exact same domain user and I plugged it into the Search Analytics API test query on the browser page. It returns at 200, but without any data. So that's the issue I'm facing. JOHN MUELLER: OK. KERN HOH: So it says it's valid, but there's no data that's coming back.  

#### [0:16:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=960) |  JOHN MUELLER: OK. That seems weird. KERN

HOH: Yeah. JOHN MUELLER: I-- so-- I mean, you're welcome to drop your domain here in the chat and I can take a look at that afterwards. KERN HOH: Yeah. JOHN MUELLER: But one thing you might also want to try in the meantime is to check out some of the other tools that use the Search Console API, just to see if maybe there is something unique in the way that you had that query compiled versus how other tools would  

#### [0:16:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=990) |  pull that. Like Mihai has a nice

plug-in for Google Sheets that lets you also use the API to pull in data, and that way you can kind of double-check is it that Search Console is not giving me any data because my domain name is slightly different than what it expects? I don't know. Or is it because I'm doing something slightly unexpected, where maybe I'm copy-pasting something slightly different? [BEEP] KERN HOH: Sure. Cool. Yeah, thanks, Mihai.  

#### [0:17:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=1020) |  Saw your message. Cool. THOMAS: Hi, John.

Thank you. Thank you for taking your time. So I have a question regarding featured snippets. So we have encountered some occasion in which there has been a featured snippet in place in search results, but afterwards, after some close [INAUDIBLE] analysis of search results, we came across the same term that we looked up on Google and we found out that there's no featured snippet anymore.  

#### [0:17:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=1050) |  So there are two questions for us

now-- is there any way we can actively approach a featured snippet by structuring our data in a certain way on our site, and if there happens to be the case that a featured snippet goes missing, what does that indicate for the term and for the search result as such? So is the featured snippet not attractive anymore? Should we not try to get the featured snippet if Google  

#### [0:18:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=1080) |  removes the featured snippet from search results,

or are there other reasons for the fluctuation in this instance? JOHN MUELLER: Those are good questions, but it's kind of tricky because for us, a featured snippet is just a different way of showing a search result. So it's not something that we would pull out and say, it's something completely different.  

#### [0:18:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=1110) |  So it's something that can appear sometimes

and sometimes it might not appear. For some sites, they see a lot of fluctuations there in the visibility of them, and for others, it's fairly stable. From our point of view, we don't have any explicit guidelines on what you need to do to have content that works well in featured snippets. There are externally some people who have written about kind of ways that you can write your content that works well  

#### [0:19:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=1140) |  with featured snippets. I would definitely check

some of that out. But from our point of view, it's not that there's a technical thing that you have to do to make featured snippets work, or that you have to have, like, one question and an answer and then you will get that in a featured snippet. A lot of these things are things that our algorithms try to figure out automatically and externally, people have written about what they've discovered works well  

#### [0:19:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=1170) |  or doesn't work well. So I would

take a look at some of those external blog posts and presentations that people have done. And I guess the other thing is in Search Console, you can't really track those featured snippets, so it's not something that we would pull out separately, because from our point of view, we think they're kind of a normal search result. What you'd probably see is that the position  

#### [0:20:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=1200) |  of the page for individual queries kind

of goes up and down there, where when it's in the featured snippet, it'll be at position one, and when it's not in a featured snippet, maybe it'll be further down in the search results page. So that's kind of anecdotally, what you might see. THOMAS: All right, thank you. JOHN MUELLER: Sure. OK, let me see what other questions we have submitted, and we'll definitely have more time for more questions  

#### [0:20:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=1230) |  along the way. I'd like to know,

what are the basics to avoid indexing URLs from preproduction or development environment and not have duplicate content issues? I know you're not the only one with this problem. I think pretty much everyone who has kind of a staging environment has run into this issue as well. So basically, the best approach to preventing any of your staging URLs from being indexed in Google  

#### [0:21:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=1260) |  is to put them behind some kind

of a server-side block, which could be server-side authentication, that you have to enter a password, username, or something to get to those pages. It could be by IP address, if you have a specific IP range of your developers, your quality teams, those kind of things. That's essentially the best way to really kind of prevent that content from being indexed.  

#### [0:21:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=1290) |  There are two other approaches that people

sometimes take. One is to use robots.txt to block crawling of those URLs. In general, that's OK, too. For the most part, we wouldn't index those URLs if there are no links to those pages. However, what is a very common mistake is that happens there is that people sometimes push the fully blocking robots.txt file to production as well, and then suddenly your production server  

#### [0:22:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=1320) |  is also blocked. So that's kind of

one of those areas where it's very easy to make mistakes. The other approach is sometimes to use a noindex meta tag on these pages, and that also prevents those pages from being indexed, which is kind of what you're looking for. But again, you also have the same problem that it's easy to take those noindex pages and push those to production. So by using something like server-side authentication,  

#### [0:22:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=1350) |  which generally is not a part of

the full set that you push to production, by doing that, you can kind of sidestep that. You can push something to production and you can be really sure that if you can access your production pages without a password, then that it's actually working well. So that's kind of the three recommendations I'd have there. ROBB YOUNG: How does--  

#### [0:23:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=1380) |  just as an aside, what-- if those

pages aren't linked from anywhere, how do you-- surely then it's fine, or you shouldn't get to them. You're not the deep state. JOHN MUELLER: Yeah, I would-- ROBB YOUNG: How do you get to the pages if they're not linked from anywhere? JOHN MUELLER: If they're really not linked from anywhere, that's perfectly fine. But people leave traces and links in all kinds of weird places. So one of the weird places where we sometimes see our internal links that pop up  

#### [0:23:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=1410) |  are all of these browser plug-ins that

tell you, like, which site is popular with which kind of users, and then suddenly your domain is listed there as, this is one of the, I don't know, least popular websites because of course, only the developers are visiting it, but it's listed somewhere. And then suddenly there is a link. And it's these-- ROBB YOUNG: Right. JOHN MUELLER: --kind of vague traces that are on the web which search engines sometimes just stumble  

#### [0:24:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=1440) |  across and are like, oh, look, a

new website. I will do my best. ROBB YOUNG: All right. So does it usually happen with people using off the shelf CMS stuff, then, if it's plug-ins or things that you install that you forget about? JOHN MUELLER: Yeah, I don't know so much about plug-ins in CMSs, but definitely from a browser side, that's something that we see a lot-- all of those kind of popularity sites  

#### [0:24:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=1470) |  that track, like, what the top websites

are in the UK or top websites-- ROBB YOUNG: Right. JOHN MUELLER: --in different regions. And then it's easy to get somewhere on the bottom of the list there, and then-- ROBB YOUNG: OK. JOHN MUELLER: --it's there. I mean, another thing we sometimes see is when people send URLs by email to other people and the other people end up being public mailing lists.  

#### [0:25:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=1500) |  And then suddenly, some public mailing list

has kind of this URL that you don't actually want to have indexed. And if it's a matter of just having the hostname, then that's something that feels like it can just happen at some point. ROBB YOUNG: And you're saying Google reads email. Is that what you're saying? JOHN MUELLER: If they're on public mailing lists, you know. ROBB YOUNG: Right, right. JOHN MUELLER: Let's see. I have the next mistake.  

#### [0:25:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=1530) |  A page in my web hasn't got

a main entity, and I don't know what to do. In fact, it's an old page which I've tried to delete, but I don't get it. What can I do? So deleting a page is perfectly fine. So that's something where essentially, if you want to delete it and you can work out how to delete it in your CMS, if you're using something like Blogger or WordPress or whatever, then deleting  

#### [0:26:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=1560) |  it should be possible. In general, the

main entity sounds like it's missing some kind of structured data on your page, and from our point of view, structured data is not a requirement for a page for search. So if there's one page on your site that just doesn't have structured data on it or doesn't have that type of structured data on it, then I wouldn't necessarily worry about that.  

#### [0:26:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=1590) |  Does adding year to a post title

help in rankings? For example, "how to start a website" or "how to start a website in 2020"? From our point of view, it doesn't help in ranking. It's not that we have any algorithms that look for the current year and say, oh, this is a recent article. We should show it higher in the search results. Sometimes users look at that. I sometimes find that a bit misleading, because you see websites essentially  

#### [0:27:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=1620) |  update all of their year numbers at

the end of the year, and then suddenly it's like, what is the best cassette recorder from 2021? And then actually, there are no cassette recorders from 2021, but the website is updating their content like that, which feels a bit misleading to me. So I don't think our algorithms would penalize that. They definitely wouldn't favor that, either, though.  

#### [0:27:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=1650) |  Why are news websites getting down day

by day? Is there any update going on? As far as I know, news websites are not going down day by day. It almost seems like news websites are always in the foreground when you look around, because there's always some crazy news happening that pushes their content to be more and more relevant. So there is definitely no kind of anti-news website update  

#### [0:28:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=1680) |  or algorithm happening at the moment. Big

publications artificially refreshing their stories by messing with the timestamp on a very regular basis in the search results and news. Will you ever take action on such sites, or only keep affecting small websites with algorithm updates? We do see this from time to time, and sometimes, it does happen that this has  

![](https://i.ytimg.com/vi/UKt7sblTapM/hq2.jpg)



#### [0:28:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=1710) |  a positive effect on a website. And

that is something that we escalate to the team so that they can take a look at that. On the other hand, we also have fairly robust systems to recognize the more actual date on an article. So if we can find an article on the web and we can recognize when this was really published, and then even if they change the timestamp on their pages, it's not something that will skew our systems.  

#### [0:29:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=1740) |  It does feel like this is a

bit kind of cat-and-mouse thing where we improve our systems, and then they find new, sneaky ways to kind of get around this. But in general, I think where we're kind of reasonably OK there. If you find situations where we're not catching onto this, feel free to let me know. Like, send me some examples on Twitter, ideally screenshots where it's easy for us  

#### [0:29:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=1770) |  to confirm that something like this is

happening, because with a lot of these news things, if you just send us the URLs and we take a look a day later or we pass that on to the team, they take a look a day later, then it might look completely different by then. So with clear screenshots of examples where something is going wrong, that's really helpful. I'd like to know what would be the best technical approach--  

#### [0:30:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=1800) |  follow versus nofollow, index or the noindex,

canonical-- in the following case. We have two domains, A and B. Domain A is linking from the landing page to domain B's landing page, passing a parameter with a URL based on the parameter's landing page at domain B. It's personalized with a different H2 heading copy, et cetera. There's also a default version of the landing page at domain B available at the URL without parameters.  

#### [0:30:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=1830) |  So ultimately, this is up to you.

It's whatever you would like to achieve there. It sounds like the home page of domain B without parameters is kind of one home page, and the home page of domain B with parameters or with those specific parameters is a different version. And from our point of view, you can do that, and you can have two different pages indexed.  

#### [0:31:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=1860) |  It doesn't matter so much that it's

the home page with parameters or without parameters, but essentially, these are two different URLs from our point of view. So if these are two different URLs, then you can kind of decide on your side, do you want them indexed individually, or do you just want one of them indexed? If you just want one indexed, then using the rel=canonical to the version that you prefer to have indexed, that's essentially the right way to do it. But you can also decide to say, well, both of these  

#### [0:31:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=1890) |  are OK to have indexed-- I don't

mind if they're both indexed. It's essentially up to you. Let's see. I think we still have a bit of time, so I'll run through some more of the submitted questions, and we can get through some of the things from you all live as well. If my site is in Search Console verified a long time ago with the www protocol in front, after a site redesign,  

#### [0:32:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=1920) |  I've removed the www. Do you think

this is a problem? Should I add another property in Search Console without it, or should I redirect all my assets and pages to the www version? Just wondering if this is a big issue from an SEO perspective. So it's-- on the one hand, it's not a big issue to switch from one version to the other, but you need to make sure that you have redirects in place. So if you are previously at www your site  

#### [0:32:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=1950) |  whatever, and now it's at the same

version without the www, you need to make sure that there are redirects from the old version to the new one. That's kind of the basic thing thing that you need to watch out for. If you don't do that, we will assume that the old version is kind of broken and we will kind of let that disappear from search, while we recognize your new version and think, oh, this is a new website. We will kind of slowly integrate that into search.  

#### [0:33:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=1980) |  So to prevent us from kind of

losing all of the value that you've built up, make sure that you set up those redirects. That's kind of the basic thing there. With regards to Search Console, it is such that there are two ways that you can verify sites. One is on a domain level and one is on the prefix and protocol level, where you would have to specify the www and not.  

#### [0:33:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=2010) |  So if you have it currently on

the prefix version verified, and you switch to a different prefix, you need to also verify that new prefix in Search Console. Usually, this is pretty straightforward. A nice way around that kind of for the future as well is to switch to domain verification. Then you don't have to worry about that. Search Console is not a requirement for search, so if you forget to do the verification in Search Console,  

#### [0:34:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=2040) |  your site will still work. It's not

that something will break. Also, if you switch to a different Search Console verification, it's not that your data will disappear and you have to start over again. Search Console will recalculate the older data and show that to you there as well. So that's something-- on the one hand, watch out for the redirects that you have those set up properly, and then I'd just recommend making sure that you see your data in Search Console with whatever version  

#### [0:34:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=2070) |  works for your site. If we have

a 404 page today and after a few days, we make it a 200 again and submit it in a site map again and internally link to them again in the site as well, how will Google treat these? Will this create a negative ranking impact, wherein Google re-indexes these pages? Will Google report these URLs and submit it not 404? What bad things can happen if we start using 404 in place of noindex?  

#### [0:35:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=2100) |  So from kind of the early questions

there, if you have a 404 page and you make it 200 and there is content there, then when we reprocess that page, we will take that into account. There is no penalty at all for that page being a 404 in the past. We just have a new page that we can index, and we'll try to index it the best we can. So that's-- on that point of view,  

#### [0:35:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=2130) |  it's not that there's any downside to

doing this. The one thing to kind of keep in mind here, though, is that if a page has been 404 for a longer time, then we tend not to crawl it as frequently, because we think it's-- like, we don't want to bother you with all of these requests for pages that you have always been telling us don't exist, then we probably won't check that page every day or so. It might be that we would check it maybe every other month  

#### [0:36:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=2160) |  or something like that. So if you

have a page that you turn from a 404 to a 200, it can happen that it takes a bit of time for that to get picked up again. So that's one thing to watch out for there. And in particular, if you're changing a page from 404 to 200 and then back to 404 again and back to 200, back and forth a lot, then that's something where, if we get into this state of, oh, this is a 404,  

#### [0:36:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=2190) |  we don't have to crawl it that

often, then it can happen that we miss some of these fluctuations back and forth. So I would try to avoid the situation where you're going back and forth a lot. If you're doing this once, then that's less of an issue. The last question, I think, is what bad things can happen if we start using 404 in place of noindex. I don't see anything bad really happening there.  

#### [0:37:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=2220) |  Essentially, if you're telling us that these

pages should not be shown in search if they don't exist, then both of those options work-- 404 or noindex. My suspicion is that maybe a noindex would be a little bit faster visible, but I think if you're looking at it from a bigger picture point of view, you probably wouldn't notice any difference there.  

#### [0:37:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=2250) |  So from that point of view, if

you have a choice between 404 and noindex, I would just pick whatever works best for you. Can duplicate pages due to uppercase URLs cause side performance downfall? Does keyword cannibalization exist? OK, those are kind of completely different things. On the one hand, the duplicate pages with uppercase URLs-- we do treat URLs as being case sensitive.  

#### [0:38:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=2280) |  So if you have URLs that have

some uppercase characters in them or URLs that have lowercase characters in them, then we would treat those as being unique URLs and we would try to crawl and index those individually. We would probably fairly quickly recognize if they're the same. If your server treats them as the same thing, we would see exactly the same content, and we would fairly quickly realize, oh, we can just focus on one of these. So essentially, what you're doing  

#### [0:38:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=2310) |  is creating duplicate content in a technical

way. I kind of call this technical duplicate content, because it's not that you're duplicating content with the hope of doing something sneaky. It's more that while your server is technically creating multiple URLs for the same pieces of content, usually we can work around that fairly well. So especially if you're a smaller site and you have this kind of duplicate content, then we can work around that.  

#### [0:39:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=2340) |  That's less of an issue. If it's

a very large website where we struggle with crawling even with one version of the content, and you suddenly have multiple versions with upper/lowercase URLs in there, then that's a bit of a different question. So that's something where I would really focus on cleaning up those urls, making sure that you're linking to a consistent version that use the rel=canonical to your consistent version, and really make it so that we can  

#### [0:39:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=2370) |  crawl your website with the preferred URLs

as efficiently as possible. So it feels like that's something that a lot of sites tend not to worry about so much anymore. In the past, it felt like a bigger problem, especially when you were making your own websites. When you're coding your own HTML, then it's very easy to kind of code those links yourself, and then some files are uppercase, lowercase, those kind of things. But if you're using a common CMS like WordPress  

#### [0:40:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=2400) |  or any of the other common CMSs,

then usually that's something that's taken care of you. You link to a specific page and that link automatically has the right upper/lowercase version. Does keyword cannibalization exist? So, keyword cannibalization. People usually call it that when you have multiple pages on your website that are targeting the same keywords--  

#### [0:40:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=2430) |  essentially, when you're making life harder for

yourself than it needs to be. And from that point of view, you could say it exists. I feel that the name makes it sound scarier than it really is. There's nothing mystical around it. It's essentially just you going to people and saying, well, it's like you're searching for this really important term on my website, but it's like here are five options instead of here's one really strong option  

#### [0:41:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=2460) |  that I can give you. And so

it comes across to me more as kind of a marketing question of, how do you present your website, and do you prefer to have one really strong option that you show to people, or do you have kind of a diluted version across multiple variations of the same thing on your website? Sometimes it makes sense to have multiple variations, especially if you know that people are searching for something with a generic term  

#### [0:41:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=2490) |  and they're not quite sure what they

actually mean. Sometimes it makes sense to really have one very strong version, where you really have something that can rank really well because it's like you focus all of your energy into it, you present that within your site as the primary approach there. So those are kind of the things that I would watch out for there. And let me just take one more question, and then we can switch to more questions from you all.  

#### [0:42:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=2520) |  My WordPress blog has Date Published and

Date Modified properties. If I'm using Date Modified, what-- why is my blog posts that are published in 2016, but have spent extensive hours updating in 2020, still showing the date of 2016 in search results? It's misleading to potential visitors and I believe I'm losing clicks because of this. I also don't understand the logic behind the behavior. So I haven't had a chance to take a look at the exact URL  

#### [0:42:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=2550) |  here, but when it comes to dates,

we look at multiple things on a page. I think we have a Help Center article on dates as well. One important thing is that we can confirm the date on the visible part of the text as well. So just updating the metadata in the structured data, if that's something that you're updating, isn't going to sway our algorithms and understand that actually, this  

![](https://i.ytimg.com/vi/UKt7sblTapM/hq3.jpg)



#### [0:43:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=2580) |  is the right date to show. But

we really need to have that confirmed in the visual part of the page. So if at all possible, make sure that that's something that you can confirm in a way that is easy to understand. And by easy to understand, I mean like really listing the date on the page, and not something as like, updated early 2020 kind of thing. It should really have the same date so that we-- when our algorithms look at the page, usually  

#### [0:43:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=2610) |  what happens with regards to dates is

we try to extract all the dates that we can find on the page in the visible part and the structured data, and then we try to judge which of these dates have support within the article, like which of these dates are mentioned multiple times, which of these dates seem to be relevant for the article, and then we try to narrow things down on those dates. So making it as easy as possible for us to confirm that a date is the right one  

#### [0:44:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=2640) |  is kind of what we should be

looking for. OK. Wow, still a bunch of things left, but let's switch over to questions from you all just for a second time. SIVAPRATAP NELLIPUDI: Well, I have a question on Google News, if that's OK. JOHN MUELLER: I don't know everything around Google News, but I'm happy to try. SIVAPRATAP NELLIPUDI: Sure. So there have been several complaints on the Publisher Center forum, as well as Twitter, about sites that have got into the Google News  

#### [0:44:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=2670) |  after December 2019 haven't really been showing

up on the News tab if you search for them, and that includes larger publications like CNN Brazil, IndiaTV.en, and there are several websites like that, and none of them really show up without adding their site operator in the search keyword. If you look at the older websites which got into the News before December 2019,  

#### [0:45:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=2700) |  they does show up on the search

without any site operator keyword. So what is exactly the difference between that initial old one and new one, and why is it that we have to search with the site operator on only those new website? Because ideally, they should show up, even if you search with [INAUDIBLE] because it's been almost like 10, 11 months since the December 2019. So there have been so many complaints on the Publisher  

#### [0:45:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=2730) |  Center about this, and we haven't really

seen satisfactory answers out there. So we just wanted to clarify if this is something that publishers can be helped with. JOHN MUELLER: Yeah. So again, I'm not on the Google News team, but I have seen a lot of these complaints as well. And I spent a bit of time also chatting with Danny Sullivan about this to try to understand this a little bit more.  

#### [0:46:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=2760) |  My understanding is that this is something

that we're working on, so it's not by design that kind of there is this one cutoff date, but rather that things are being processed just a little bit slower than they used to. And the other aspect there, the site query, is-- from my understanding is that even if you're in the News tab and you do a site query for something that's not in Google News directly, and it will default and show the data from Google Search.  

#### [0:46:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=2790) |  So that's kind of-- it feels like,

oh, it should be there, but it's not being shown for normal queries. But actually, what you're seeing is kind of the normal search indexing and not what would actually be shown in Search. So I hope we can kind of clean that up a little bit. I don't know what the timeframe is there, and I don't know exactly what all will change there, but it does feel like something where  

#### [0:47:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=2820) |  things have been going a lot slower

than they should be. SIVAPRATAP NELLIPUDI: There is a bigger problem, actually, because of that. So many publishers, they're switching to domains which were in Google News before December 2019 and then kind of exploiting this thing to show up all those copied articles, scrapping things, and all that. They're appearing very easily, because they got approved before that timeframe, right?  

#### [0:47:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=2850) |  So they just show up without any

effort at all. Like basically, there were a couple of examples given by the product expert in the Publisher Center thread also, saying there are a couple of websites which are really a wireless link. So they're coming up on News, and it is kind of sad that the original publishers has to kind of suffer because of this. It would [INAUDIBLE] you can take a look at that. JOHN MUELLER: Yeah. I mean, I'm not on the Google News team, so I just poke at them and tell them, like,  

#### [0:48:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=2880) |  they should do some more there. But

one thing also to keep in mind is that there's abuse everywhere in Search, and it's something where if you explicitly look for some kinds of abuse, you will find it. So it's-- I don't know, it feels kind of weird to say that, like, we should be showing in Google Search and look, I also found some abuse from existing publishers. Because then it almost distracts, kind of,  

#### [0:48:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=2910) |  the effort that could be put into

your case to kind of improve things on your side by telling them, oh, actually, you should be cleaning things up first. So that's-- I don't know, just from my personal point of view. But we are definitely pushing a little bit on the News folks to see if we can speed all of this up again. SIVAPRATAP NELLIPUDI: Thank you, John. RAJDEEP DAS: Sir, I am here. BRITTANY MCCULLOUGH: Hey. Oh, sorry, can I jump in? JOHN MUELLER: Sure, go for it. BRITTANY MCCULLOUGH: Hi, John.  

#### [0:49:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=2940) |  This is Brittany. I posted the first

question that you read about the domain migration gone very, very wrong. And I have a team of 35 depending on me and depending on this website's traffic, so it's been just such a tough time for us. I have a few theories of what might have gone wrong. I was hoping to run at least one by you, but I know this is a very specific scenario, so if you'd prefer me-- if you'd prefer to just follow up with me after, that's fine, too. I can jump in with one of them, sort  

#### [0:49:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=2970) |  of taking your lead on what's best

in this forum. JOHN MUELLER: So usually what I do on Fridays is also just have a bit of time afterwards where people can ask questions kind of off the record, which makes it a little bit easier to look into some specifics as well. So if you want to hang around a little bit, we can take a look at that then. Would that work? BRITTANY MCCULLOUGH: I will do anything to get any next steps on this situation. So yes. JOHN MUELLER: OK. BRITTANY MCCULLOUGH: Thank you. JOHN MUELLER: Cool. RAJDEEP DAS: Am I clearly here even?  

#### [0:50:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=3000) |  JOHN MUELLER: Yes. RAJDEEP DAS: Sir, I

am asking that some websites which do not have any content, just putting through your two keywords and ad ranking in top stories, where as new publishers, we produce high quality content, but still not able to get on the first page. But they are ranking with this three keywords. I have a video proposal posted in the Google News forum. They are saying that it is computer algorithm and that we cannot do anything, and putting a [INAUDIBLE]..  

#### [0:50:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=3030) |  JOHN MUELLER: What I would recommend doing

there is using a spam report form, if you think that this is really bad content, or using the feedback form to let us know when you see bad results. RAJDEEP DAS: But sir, still the big news publisher sites, like CNN Brazil and India TV, not able to get in the Google News. [INTERPOSING VOICES] JOHN MUELLER: I think we talked about that previously, so I don't really have any updates there.  

#### [0:51:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=3060) |  Our-- no. I mean, one thing that

I'd also just like to point out is that a lot of the sites that I looked at that that were escalated in those threads are things where I'm kind of, I don't know, a little bit reluctant to say that we should treat these as news sites. I'm not on the News publisher team, but there's, like, a lot of, I don't know, weird things there.  

#### [0:51:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=3090) |  So that's another thing to keep in

mind-- that just because things are submitted in the Publisher Center doesn't necessarily mean that we would show them in Google News. But like I mentioned before, we are definitely going to poke the Google News team a little bit to see if we can speed some things up there. RAJDEEP DAS: OK. Thank you, sir. PANDU FURWANI: Hi, John. JOHN MUELLER: Hi. PANDU FURWANI: I want to ask you some question about the AMP  

#### [0:52:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=3120) |  page. This [INAUDIBLE] day my AMP page,

it doesn't show up on [INAUDIBLE].. I don't know what happened and if you have any clue about this, because on the technical side, the AMP page and the HTML, and we have checked into the Search Console. The result is [INAUDIBLE] give the result is [INAUDIBLE] the AMP page. But when I search on the Google Mobile,  

#### [0:52:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=3150) |  then it doesn't show up. Why this

happen, if you any clue? JOHN MUELLER: So you have a setup with a connected AMP page, just to confirm? So one HTML pa-- or, like, I don't know. Are you referring to a legacy HTML page and the AMP version of that page? Is that correct? PANDU FURWANI: Yeah. Yeah, yeah, yeah. We have [? detail. ?] JOHN MUELLER: OK. And you're looking in the mobile search results  

#### [0:53:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=3180) |  and just looking at the normal search

results there, not any specific feature-- PANDU FURWANI: [INAUDIBLE] JOHN MUELLER: --or ranking question? It's really just showing the HTML version and not the AMP version? PANDU FURWANI: Yeah. I think my other question is because of the AMP page, it doesn't show up on the Google Search. I think rank also dropped.  

#### [0:53:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=3210) |  Is that correct? JOHN MUELLER: I don't

know. I mean, usually the switch between the normal HTML version and the AMP version is something that would happen without any ranking change. It's just, we would show one version or the other version. So that wouldn't affect the visibility of the page at all-- it's really just like, which of the URLs is being shown. One thing you could do is make sure that in Search Console,  

#### [0:54:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=3240) |  you also can track those versions. Depending

on how you have AMP set up, if it's like a subdomain or a subdirectory, then make sure that you can also get that data in Search Console to see if there's anything specific that's flagged there. Also in Search Console, there's the AMP report that can give you a little bit of information on issues with AMP pages that we find, which  

#### [0:54:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=3270) |  would result in us not showing the

AMP page, but rather the normal HTML version. But again, all of this wouldn't change the ranking of the page. It's really just which version is being shown. PANDU FURWANI: I see. OK then. JOHN MUELLER: So I think if you're seeing a change in ranking as well, then that wouldn't be related to the AMP version or not. That would be more of a general ranking version or not.  

#### [0:55:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=3300) |  PANDU FURWANI: Mmm. Sorry, in our Google

Analytics, I have seen the slightly drop on the AMP traffic. So I think that also in-- because that doesn't show up under Google Search, I think also the rank is dropping. JOHN MUELLER: OK.  

#### [0:55:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=3330) |  Then that sounds more like a general

ranking question. Then I wouldn't worry so much about the AMP page. I would think about what you could do to improve kind of the ranking of your pages overall. PANDU FURWANI: I see. Still confused a bit, but I don't know. I have checked on the AMP page [INAUDIBLE] on the Google Search Console. They checked-- the AMP page is [INAUDIBLE] by the way, but I don't know. I'm still confused about it. But OK, thanks for the--  

#### [0:56:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=3360) |  JOHN MUELLER: Sure. PANDU FURWANI: --answer. JOHN

MUELLER: Sure. OK. SIVAPRATAP NELLIPUDI: John? JOHN MUELLER: Hey. SIVAPRATAP NELLIPUDI: So again, one thing-- is it possible for you to organize a meet like this for the News team as well, just a request from our side? Because there are a lot of open questions for these News publisher guys, so [INAUDIBLE] at least for a [INAUDIBLE] or something like that? Like what you are doing here? JOHN MUELLER: I-- RAJDEEP DAS: [INAUDIBLE]. JOHN MUELLER: OK.  

#### [0:56:30](https://www.youtube.com/watch?v=UKt7sblTapM&t=3390) |  RAJDEEP DAS: [INAUDIBLE] JOHN MUELLER: OK, we

have some people who are interested in News hangouts. OK, I don't know. I'll ask. Yeah. SIVAPRATAP NELLIPUDI: OK, thank you, John. All the best. JOHN MUELLER: Cool. Let's take a break here. I'll pause the recording. If any of you want to hang around afterwards to ask more questions or chat more, you're welcome to do that. In the meantime, anyone who's watching the recording,  

#### [0:57:00](https://www.youtube.com/watch?v=UKt7sblTapM&t=3420) |  thank you for watching along. I hope

you found this useful, with some of the questions going back and forth. I thought lots of good stuff happening. I wish you all a great weekend, in the meantime, and hope to see you all again in one of the future hangouts. SIVAPRATAP NELLIPUDI: Thank you so much. JOHN MUELLER: Bye everyone. SIVAPRATAP NELLIPUDI: Yeah, take care. Bye. RAJDEEP DAS: Take care. Bye.  