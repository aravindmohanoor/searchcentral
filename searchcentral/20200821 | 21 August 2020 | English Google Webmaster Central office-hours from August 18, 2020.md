[![English Google Webmaster Central office-hours from August 18, 2020](https://i.ytimg.com/vi/7bAHUrvFECs/hqdefault.jpg)](https://www.youtube.com/watch?v=7bAHUrvFECs)

## English Google Webmaster Central office-hours from August 18, 2020

This is a recording of the Google Webmaster Central office-hours hangout from August 18, 2020. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Watch out for new sessions, and add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



Feel free to join us - we welcome webmasters of all levels!



#### [0:00:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=0) |  JOHN MUELLER: All right welcome everyone to

today's Webmaster Central Office-hours Hangout. My name is John Mueller. I'm a webmaster trends analyst at Google in Switzerland. And part of what we do are these office-hour Hangouts, where people can jump in and ask their questions around their website and web search. And we'll try to come up with an answer. A bunch of stuff was already submitted on YouTube, but if any of you want to get started with our first question you're welcome to jump on in.  

#### [0:00:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=30) |  MIHAI APERGHIS: John, I have a couple

of questions regarding internal linking. JOHN MUELLER: OK. MIHAI APERGHIS: So one would be whether-- well, let's say you have an architecture of categories that use your main navigation, and it's one way on the desktop side-- so for example, you might have some dropdowns, some bigger menus, things like that, that you can hover with your mouse, the dropdown shows,  

#### [0:01:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=60) |  but you can also click on the

link and go to that top category if you'd like. However, on the mobile, since you're kind of limited both in terms of space and functionality, maybe that top category is still there with a HTML link, but when you tap on it, it just lowers a dropdown or something like that. So my question is if Google treats the fact that, well, that's a link there in the navigation, but when users tap on it, it doesn't actually  

#### [0:01:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=90) |  go to that page, it just launches

a dropdown or something like that, even though there is an HTML link. So the behavior of the link is not actually acting like a link, it just shows you a dropdown or things like that. Does Google treat those in any way differently? JOHN MUELLER: I guess it depends on how that is modified on mobile, because if we render that page and essentially that HTML link is swapped out with a JavaScript event,  

#### [0:02:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=120) |  and that HTML link is no longer

there on the rendered page, then we might not see that internal link. MIHAI APERGHIS: But it's still there? JOHN MUELLER: If the HTML-- if the link element is still there, if it's just something like a span on top of the link element, and that captures the click and does the JavaScript fanciness, that's perfectly fine. MIHAI APERGHIS: OK. So there is no worry that, oh, it's not taken into account, or, I don't know, like that in terms of crawling  

#### [0:02:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=150) |  JOHN MUELLER: Yeah. Yeah. MIHAI APERGHIS: OK?

OK. Second question is kind of related to how-- there's been this information that when Google sees multiple links going to the same page on a given page, it only takes into account the anchor text for the first link that it sees on the page and kind of ignores the rest. I'm not sure if that's exactly true.  

#### [0:03:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=180) |  And whether, you know-- so for example,

if you have a link in the menu, but then you write an article about it, then you might reference the same page with a different anchor text. Does Google understand that and see both it's in the main content, so even if you have it in the menu, I'll take a look at that anchor text in the main content, because it seems more important. Does that play into it at all? JOHN MUELLER: I don't think we have that defined, that behavior. So it can go either way.  

#### [0:03:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=210) |  And it can be that we take,

kind of, the multiple links that we find, and we combine the signals from that. So that's something where-- the kind of misconception that if you have multiple links to the same page on one page, then you need to make sure that the most keyword-rich anchor text is the first one on the page-- that is not the case. MIHAI APERGHIS: Sure. JOHN MUELLER: That's not the case. So from that point of view, it's not that you need to artificially tweak  

#### [0:04:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=240) |  the order of the links on the

page. But it's also not the case that we have, kind of, this one defined way that we always treat things when we find multiple links on a page. MIHAI APERGHIS: OK. I was mainly asking for, like, e-commerce websites-- they usually have a big menu with categories and things like that. They don't have a lot of space to use very keyword-rich anchors in the menus. They did kind of-- you just have women, or men, or anything like that. But in the content, let's say you  

#### [0:04:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=270) |  have a blog, and then in those

articles you kind of reference those pages with a more relevant anchor text. So I was wondering if Google could also take those anchors into account. JOHN MUELLER: No. Yeah. From my point of view, we could take those into account. It's just not clearly defined that we will do exactly one to one. I think for the most part, with normal web sites, there are so many different links going to every page with internal linking  

#### [0:05:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=300) |  that it's not critical which anchor text

you use from this one page to this one other page, because we have so much other information from the rest of the site. MIHAI APERGHIS: OK. Last one. So let's assume that certain pages are linked from multiple sections that are site-wide, like you have one in the main navigation, but you also have one in the footer, like, let's say, to the Contact page, or to the FAQ page,  

#### [0:05:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=330) |  or anything like that. And since PageRank

usually works by also counting, you know-- the number of links on the page matter, and the time you mentioned-- you linked to a certain page also matter. Is that something, like, webmaster should take that into account? Like maybe don't have all links to the privacy policy page on every page on your site, because that kind of takes away  

#### [0:06:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=360) |  from the rest of the links you

might have in your navigation. Or is that too little of a factor to bother about? JOHN MUELLER: Yeah. I don't think that would play a role. So-- I mean, I'm kind of tempted to see if I can play with something like that, maybe on our blog or something, where we put links to, I don't know, maybe a privacy policy 10 times instead of one time. But my feeling is that wouldn't change anything at all. MIHAI APERGHIS: I'm only asking since certain tools,  

#### [0:06:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=390) |  like Screaming Frog, for example, that calculate

the link score in a very basic way, similar to how PageRank works. JOHN MUELLER: Yeah. MIHAI APERGHIS: But you might see, like, a link of the FAQ page, or the privacy policy page. I mean, a very, very high link score over some of the pages that you might want that are internally linked. So I was just wondering if Google-- I know it's a very basic calculation that they do, versus what Google does. But I was just wondering if it's something that you could try to tweak, maybe, here and there,  

#### [0:07:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=420) |  or not really bother because Google doesn't

really care about that. JOHN MUELLER: Yeah. I think for the most part it's wasted time to do that. I think it's important that these tools show this kind of score internally, because sometimes you do kind of lose track of pages, and you think this one thing is really important but actually you only link to it once on your whole website. And then getting that highlighted is really useful.  

#### [0:07:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=450) |  But for the most part I wouldn't

really worry about those details. Also the follow-up question from there is sometimes, should I nofollow the links to my privacy policy page because I don't want it to rank? And we have a lot of practice with privacy policy pages and similar pages, where we understand they're linked from everywhere within the website, but they're not the most important piece of content on the website. So we kind of understand these kind of relationships. But I think having some kind of score,  

#### [0:08:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=480) |  having a way to look at how

a crawler would look at a website in a naive way, I think is really useful. So I wouldn't discount those tools just because they don't map one-to-one to what Google does. MIHAI APERGHIS: Gotcha. OK. Thanks. I'm done. JOHN MUELLER: Cool. Anyone else before we get started? RAMESH SINGH: Hi, John. I have one. JOHN MUELLER: OK. One of you guys. RAMESH SINGH: So we have--  

#### [0:08:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=510) |  yeah, that's me. So I asked in

the last Hangout question about that one of our websites kind of duplicating our homepage and it's why are they coming from one [? Japan, ?] [INAUDIBLE],, but they're kind of forwarding together, and Google thinks they are duplicated. So just wanted to follow in that part. Is there something that we can do from our end that can make it Google for [INAUDIBLE] do you think it's reasonable advice to have the different pages, or how we should go about that part.  

#### [0:09:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=540) |  JOHN MUELLER: I don't remember the details

there. But was that something, like you have the same English content on the page for Japan as well as on a page for another country? RAMESH SINGH: No. They are different. Both web pages have different content. JOHN MUELLER: OK. I don't know. I'd probably need to take a look at the examples again. If you want to drop the links into the chat, I can pick that up afterwards. RAMESH SINGH: Sure. Thank you so much.  

#### [0:09:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=570) |  JOHN MUELLER: Maybe add a comment, as

well. Then I know exactly what I want to watch out for. RAMESH SINGH: All right. Cool. Thanks. JOHN MUELLER: And links in the chat don't pass any PageRank. RAMESH SINGH: [LAUGHS] All right. JOHN MUELLER: OK. Someone else had another question as well. PRAVEEN SHARMA: Hey, John. How are you? JOHN MUELLER: Hi. PRAVEEN SHARMA: OK. I have two very, very small questions for you. One is regarding the search consultant site that Google recently launched, Google Search Console. It seems the data that Google shows is based on Google Search  

#### [0:10:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=600) |  Console plus Google Analytics. So just wanted

to confirm if a website doesn't have Google Analytics account, so will that-- insights will still be there, or you need to have Google Analytics to count for that? JOHN MUELLER: My understanding is you need to have it tied in with Google Analytics, because the-- from-- so I haven't been following all of the details with Search Console Insights. But my understanding is that the idea  

#### [0:10:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=630) |  is to kind of provide a mix

of the data from Analytics and Search Console in a way that it's a little bit easier to understand for people who don't spend their whole life in Google Analytics or in Search Console. So that's something where we really kind of need to have both of those data sources so that we can show that kind of simplified data. PRAVEEN SHARMA: OK. The second question is regarding nofollow.  

#### [0:11:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=660) |  It is believed that Google doesn't pass

PageRank to a nofollow link, but recently, Google decided to crawl if the link is even tagged as nofollow. So if this Google decides to crawl that URL, will it pass PageRank to that URL particularly, or if Google decides-- thinks that this URL is good enough to be crawled and indexed, though, we should pass the PageRank or not?  

#### [0:11:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=690) |  JOHN MUELLER: I don't think you can

simplify it that much. There are multiple aspects with regard to nofollow there. On the one hand, like you mentioned, we decided to start trying to treat it as a hint rather than a clear directive, and that can result in us following links that have a nofollow to discover new URLs. So essentially if there is something that we haven't seen before, and we see there is a nofollow link there,  

#### [0:12:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=720) |  then we might go off and try

to crawl that page. And if we think it's worthwhile, maybe we will index that page. So that's kind of the one aspect. But the aspect with regards to passing PageRank and passing signals-- that's something that's totally independent of that. That's something where we also need to take into account a lot more, rather than just, is this a new page or not? So just because something got crawled that has a nofollow link doesn't mean that we're going to start passing all kinds of ranking signals  

#### [0:12:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=750) |  to that page. It can, but it's

not necessarily required. BARRY SCHWARTZ: John, to follow up on that, last I heard from Gary was that it's just currently a policy change around the nofollow, but nothing really has changed practically yet. Has that changed? JOHN MUELLER: It's possible. I don't know. Gary would be following up there more. But this is essentially the direction  

#### [0:13:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=780) |  that we could be heading, where we

have those nofollow links. We could theoretically use those to pass signals. I believe we are using them for discovery already, though. But I don't know. Gary would know more. BARRY SCHWARTZ: All right. Thank you. JOHN MUELLER: Maybe I should drop him a tweet and find out. OK. Let's jump into the questions.  

![](https://i.ytimg.com/vi/7bAHUrvFECs/hq1.jpg)



#### [0:13:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=810) |  We have the top question, from Barry,

can you comment more on the August 10th indexing system failure, and maybe what happened this past Saturday? See your favorite SEO blog for more details. How do you know what my favorite SEO blog is, Barry? That's-- it's like, are you reading my email? BARRY SCHWARTZ: I have a little malware installed on your computer. JOHN MUELLER: OK. OK. Well, if it's just that, bye. I don't have any more information.  

#### [0:14:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=840) |  So my feeling is with the August

10 issue, that's something where it got resolved reasonably quickly and I don't know if the team would have more information to share on that publicly. And with regards to the one on the 15th, I don't know the details of what happened there. But that also seemed like something where even you, kind of, didn't really see what exactly was changing, just  

#### [0:14:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=870) |  like-- everyone was complaining, and then suddenly

it was gone. So maybe that was just something really short. BARRY SCHWARTZ: Because I think technically it wasn't short-- it was only short because I didn't get back online until Saturday night. But I think it happened Saturday morning. JOHN MUELLER: Ah, OK. BARRY SCHWARTZ: And then-- and there were some screenshots from, like, Glenn Gabe and other people, where it showed some pretty significant changes. And then things went back sometime around, I don't know, at night, at least, Eastern time. Are you aware of anything that went wrong? Not specifically tell me what went wrong,  

#### [0:15:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=900) |  but did something go wrong? JOHN MUELLER:

I don't know. There are lots of systems with Google. BARRY SCHWARTZ: Is this just "I don't know" like "no comment," or "I don't know?" JOHN MUELLER: I don't know. I really don't have any additional information on that. So-- BARRY SCHWARTZ: OK. JOHN MUELLER: I mean, there are lots of systems at Google. And sometimes when something kind of quirky happens for a really short period of time, they just go off and fix it without letting everyone know. I think the earlier issue seemed to have been a bigger one.  

#### [0:15:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=930) |  And that's kind of also why it

took a little bit longer to get everything redone, and we ended up tweeting about it briefly. BARRY SCHWARTZ: OK. Thank you very much. JOHN MUELLER: Now, sometimes we don't have a lot of internal details to share. OK. Now a question about pagination-- or five questions. What's the importance of pagination?  

#### [0:16:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=960) |  Are there issues with pagination? What about

infinite scroll? Should paginated pages be indexed? What is the best practice of pagination? So, lots of questions. I don't know. Let me see if I can run through them briefly. So, essentially when we talk about pagination, we mean you have one thing that is really large, and it doesn't fit on one page, so you split it across multiple pages. And that could be maybe one long article where you say,  

#### [0:16:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=990) |  well, it's worthwhile splitting this. It could

be a list of individual products, maybe in a category, where you say, well, I have 5,000 products, I can't put them all on one page. I will put them on five pages, or 1,000 pages, or whatever. So that's kind of where pagination comes in. And from our point of view, it's important that we can recognize this kind of pagination and essentially index those individual pages, so that we can pick up all the content or all the links  

#### [0:17:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1020) |  to individual items that you have on

the paginated pages. Usually with pagination, one of the questions that comes up is, well, this creates a lot of new URLs, because you have to go through all of these pages to get all of the content. And yes, it does generate a lot of URLs, and we have to index a lot of different pages. But if we want that content in our index, if we want to understand those internal links to your other pieces of content, we kind of have to do that.  

#### [0:17:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1050) |  Infinite scroll is a way of doing

pagination without the user having to click Next. The important part there is that you do infinite scroll in a way that makes-- that works for Search, with regards to crawling and rendering in particular. And we have some guidelines on how to do that. So in particular, one recommendation is to have separate URLs for each page so that you can still go to the individual pages,  

#### [0:18:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1080) |  to have links to those individual pages.

And for the user if they scroll down to the bottom then it's fine to load the next page kind of thing. Should all paginated pages be indexed? Yes. Kind of like I mentioned before, if there is something on there that you want to have known by Google-- which could be a link to a different product, which could be a part of a longer piece of content-- then it has to be indexed. And the best practices--  

#### [0:18:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1110) |  kind of following up on the other

steps there. We have to know about these paginated pages, so you have to link to them, usually with a next and previous link. And with normal HTML links, we can pick that up fairly easily. You don't have to do anything special for this kind of pagination. So just link from one page to the next, and link through to the previous page as well. Then we can crawl through all of those paginated pages.  

#### [0:19:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1140) |  I kind of ran through this, and

I know there is a lot more, depending on what kind of setup you might have. So this is something where we will probably have a bit more information, in particular for e-commerce sites, to make it a little bit easier to understand what exactly should be indexed with pagination. In general, we find that most sites implement pagination in a way that just works, so we've stepped back  

#### [0:19:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1170) |  from saying, like, we need to define

exactly what people need to do for pagination, but rather, if you understand these pages need to be indexable, then you understand they need to be linked. You can test them with a local crawler and usually that just works out. Google is indexing pages with parameters. Is this considered duplicate content? Should I use the URL Parameter tool in Search Console to fix it as a best method?  

#### [0:20:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1200) |  So, in general, pages with parameters aren't

necessarily bad. It's something where in the past, maybe going back, I don't know, 15, 20 years, like a really long time, search engines were kind of reluctant to index URLs with question marks in them because it's easy to create a lot of URLs that way. But that has since changed, since a long time, and URLs with parameters in them are perfectly fine. Sometimes they can lead to duplicate content,  

#### [0:20:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1230) |  and in most cases we figure that

out ourselves. We recognize this URL with this parameter is the same content as the different URL with a different parameter. And from our point of view that essentially just works out. If you find that within your website you have a significant amount of duplicate content, and a significant amount of pages, so that you can assume that crawling is really hard within your website--  

#### [0:21:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1260) |  so say, for example, you have, I

don't know, 100 million pages. And you recognize with the parameters that you're linking within your website, you're creating 10 times as many URLs as you have pages. Then those numbers are really, really big. And that's something where it definitely makes sense to go off into the parameter handling tool to resolve that. Also to think about your internal navigation, where these parameters are being picked up on, and to improve that.  

#### [0:21:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1290) |  So that's kind of, I guess, the

extreme situation. Most sites are somewhere in between. Some have just a few pages with parameters, and at that scale, I really wouldn't worry about those. Any comments on Google blocking new publishers since December 2019? So, I saw a bunch of your tweets as well. I don't have any insight on that. It's definitely not the case that we're  

#### [0:22:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1320) |  blocking any new websites from appearing in

Search. There have been lots of new websites since then, and they do appear normally in Search. But it is something where-- you mentioned a bunch of examples where you thought things weren't working as well as they should, specifically for Google News, and I forwarded that on to the Google News team to double-check to see if there's anything that we could be doing better there. One of our websites--  

#### [0:22:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1350) |  BARRY SCHWARTZ: John. JOHN MUELLER: Yes. BARRY

SCHWARTZ: I think that was related to like the News Publisher Center. Like, if you submit it through there it's not getting-- I'm not even sure. But it sounds like it's something around the new Google News Publisher Center. JOHN MUELLER: Yeah. BARRY SCHWARTZ: Because I don't know if that provides more of something for you to look into. JOHN MUELLER: I don't know. I don't really have any insight into the News side. But since crawling and indexing kind of is combined when it comes to News, if we can pick it up for Search, then we should be able to pick it up  

#### [0:23:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1380) |  for News as well. I think most

sites don't do anything special to be picked up in News. BARRY SCHWARTZ: Right. Yeah. No. I'm just-- yeah, I don't know if there's anything specifically buggy with the News Publisher Center. It's like the Google Search files open News Publisher. I'm not sure. JOHN MUELLER: It's always possible that there is something buggy. But it would surprise me if it were completely broken since December 2019. That seems like a pretty long time. BARRY SCHWARTZ: I agree. Yes. JOHN MUELLER: One of my websites got backlinks  

#### [0:23:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1410) |  from a domain that embedded my Twitter

page feed, and the backlinks are coming from a tweet link. I don't think embedded feed content links are followed by Google, but please enlighten me. I don't know how these tweets are embedded, but in general, when we see things that are embedded with JavaScript or with an iframe on a website, it is possible for us to say that this part of the content could be seen as a part of that page.  

#### [0:24:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1440) |  And it is possible that we will

pick up links in tweets like that. That said, my understanding is that Twitter pretty much uses nofollow links everywhere. So essentially those would be nofollow links pointing to your website there, where, for the most part, we wouldn't be passing any particular signals there. So from that point of view, I don't see anything particularly positive or negative  

#### [0:24:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1470) |  with regards to SEO if you get

a link from one of your tweets that was embedded on another person's website. I-- usually it's a good sign that people like the tweets that you're writing and maybe are OK with the content that you're providing on your website-- assuming they're writing about it in a positive way. But essentially that's independent of any kind of SEO effect from those individual links.  

#### [0:25:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1500) |  The thing to also keep in mind

is that, in particular in Search Console, the links that we show there are just all links, or a sample of all of the links that we know, from the web for your website so it's not that we would only be showing you links there that pass any signals or that have any special weight. It's very possible to show things there that are maybe even disavowed, maybe that have a nofollow, anything like that, too.  

#### [0:25:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1530) |  How does Google know about the category

of a new URL being added later? So the URL wasn't mentioned in the sitemap. I don't know how you mean the category of a new URL. But assuming it's just generally, how does Google know about this new URL that I added to my website, and I didn't put it in my sitemap file? We use lots of things to pick up new URLs. But we don't make them up.  

#### [0:26:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1560) |  So essentially somewhere there must have been

a link to this page within your website-- that could be within your own content, that could be within a sitemap file, within an RSS feed, maybe someone else, maybe a tweet-- anywhere, essentially. And if we spot a URL and we think, oh, this might be something that's useful, we might go off and look at that page and see if we can index it. And if we can index it and we think it's something useful then maybe we will index it.  

#### [0:26:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1590) |  So that's essentially the story of where

the URLs come from. It's not that we have any kind of magic back door to your server and can look at what you're doing on your server, or anything like that. We really kind of have to follow those links. And sometimes the links that we find are a bit surprising to people, and that they don't realize that maybe a link is included in their RSS feed even if they don't manually include it in the sitemap file,  

#### [0:27:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1620) |  or maybe they don't realize that someone

else has tweeted a link, or maybe you shared a link by email, and the email address you shared it to is actually a public mailing list and suddenly that link is in a public mailing list where we could also pick that up. Our website and our blog have an English and a Spanish version. In Search Console, we have a property for each language where we upload the sitemap separately. While the pages related to our service are translation,  

![](https://i.ytimg.com/vi/7bAHUrvFECs/hq2.jpg)



#### [0:27:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1650) |  and therefore through hreflang we indicate it

clearly, the English blog and the Spanish blog are not linked, as they have different contents, and we try to attract traffic by offering different contents and different experience for each language in the blogs we implemented and versions for the articles. Here are some questions. Is it necessary to define the articles as canonical URL, since I comment there, the AMP version?  

#### [0:28:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1680) |  Yes. So for connected AMP pages-- I

assume this is the case that you have one traditional page, and the AMP page, and you link to them. With that kind of a setup you need to use the rel canonical. That's kind of the definition of these pages. Even if you have standalone AMP pages, where you just have AMP pages and no traditional content, you need to have a rel canonical on that page pointing to itself then.  

#### [0:28:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1710) |  So that's independent of any translations, independent

of any hreflang, for the AMP setup you need to have the rel canonical. Is this configuration correct? It's essentially fine to have it set up like that. So if you have some pages that are localized and you have the hreflang links between them, and other pages that are just in different languages but not localized versions of each other, then you don't have the hreflang there, that's perfectly fine.  

#### [0:29:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1740) |  Hreflang is a per-page annotation. You don't

have to do it on all pages. You can do it just on the home page, do it just on an about us page. You can pick and choose however you want. We have some concern that URLs that don't have an AMP page can't be fast enough. Can this generate problems for the ranking of the blog articles? So, we do use speed as a ranking factor,  

#### [0:29:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1770) |  but it's a fairly small factor. And

you can make really fast pages that are not AMP. And you can also make slow pages that are using AMP. So just because one part of your site uses AMP, and another part doesn't, doesn't necessarily mean that the part without AMP is slower or in any way treated less favorably compared to the rest of your content. So I wouldn't primarily worry about this difference, AMP  

#### [0:30:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1800) |  or not AMP, but rather think about

speed overall. And you can test speed on your side as well using the various speed-testing tools that are out there. So instead of just purely AMP or not AMP, I would look at the speed overall. Are the AMP versions used to measure and rate the URL speed performance of our articles? So, in particular with the new Core Web Vitals that is coming to Search-- we don't have a date for that yet,  

#### [0:30:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1830) |  when that will be used as a

ranking factor. We'll let you know at least six months ahead of time. But with that, we look at the page that users actually see. So if users see the AMP version of a page, and that's essentially the main version they see, maybe on mobile, then we will use that when it comes to our speed calculations. On the other hand, if people see the traditional HTML version, they have to click a link to go to the AMP version, or something crazy like that, then we would use that page we showed the users, which in that case  

#### [0:31:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1860) |  would be the traditional HTML version. We

used to have pagination on our main blog, but we realized that they were indexed in Search Console by mistake, the same pages with different URLs for pagination. We removed the pagination and it looks like the issue is solved. Do we need to de-index those mistaken URLs? So, well, more pagination questions. No, you generally don't need to do that. Usually what happens when you have pagination activated  

#### [0:31:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1890) |  like that on kind of a blog

setup, then it's just paginating through different previews of articles on your site. And it's just a parameter that's added to the page. And if you disable that, then essentially going to those URLs just shows the home page again. So if we re-crawl and reprocess those URLs over time, we will see the home page, and everything will be fine. If, on the other hand, it results in those URLs returning  

#### [0:32:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1920) |  404, then we will re-crawl and reprocess

them and drop those URLs out of the index as well, which is also fine. So either way it's not that you necessarily need to do anything to remove those URLs from the index. Can monetizing your website with an ad partner potentially hurt your rankings in Google? Because after signing up with these partners what I realize is they like to show more ads on your website.  

#### [0:32:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1950) |  So I'm just worried if it will

cause a drop in my ranking. Well, I guess, in general, if you add monetization to your web pages, then that monetization has to be visible somehow, which can result in ads being shown on your pages. So that's, on the one hand, kind of to be expected. On the other hand, with regards to Google rankings we do have some things that we watch out for.  

#### [0:33:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=1980) |  So in particular the above-the-fold content is

something where we want to see some actual content, not just an ad. Depending on the way that you have monetization setup, you might need to watch out for that. Then there is the Better Ad Standard, which is something that, particularly from Chrome, they look at for some pages, where if they realize that a site is significantly not compliant with the Better Ad Standard  

#### [0:33:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2010) |  then Chrome might decide not to show

ads on that site at all. So that's something to look at. That's not necessarily related to SEO, but it kind of falls into the same category of types of issues. And I think that's pretty much it. I think, in general, when it comes to monetization on your site it's important that you do that in a way which is long-term sustainable so that you don't drive users away.  

#### [0:34:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2040) |  Because if you drive users away from

your website, then they're not going to be out there recommending your website to other people, which is something that, indirectly, we might pick up on in Search, with regards to SEO things. So if you do decide to work with monetization on your website-- which from our point of view is perfectly fine. It's like, you have to pay for your website somehow, you have to pay for your time and your work somehow. So it's not that monetization is bad.  

#### [0:34:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2070) |  But if you do decide to implement

some kind of monetization, make sure that it's implemented in a way that you can stand behind, where you can say, well, this is really the way I want my website to be presented in Search, the way I want my website to be presented to new users when they come and visit from the Search results. Second question. They are cross-posting my article on another forum with a canonical URL. Will that downgrade my ranking? My blog is all about programming,  

#### [0:35:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2100) |  and I do like sharing my posts

with a canonical URL on other developer forums. So is that going to hurt my ranking because the other forums are very authoritative and ranked very well on Google? So in general, there are, I think, two situations that can occur here, and it's something which our systems can't guarantee one outcome or the other. It's possible that we will index both of these pages individually.  

#### [0:35:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2130) |  If we look at these pages overall

and it looks to our systems like these are significantly different pages, then we may index them individually. And we may end up showing them in the Search results separately, which could mean that the website that is syndicating your content is ranking above you. So that's something that theoretically can happen. The other alternative is that we recognize that these pages are significantly the same. And in that case, we will try to pick one canonical URL.  

#### [0:36:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2160) |  And the rel canonical does help us

to understand which of these pages you prefer to have being chosen as the canonical. And in that case we will concentrate all of the signals on that one canonical URL and we will use that one for indexing and ranking. The thing to keep in mind is that the rel canonical is just one of the signals that we use for canonicalization. So there are also things like internal and external links, sitemap files, the hidden links within a website--  

#### [0:36:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2190) |  all of those things which kind of

play a role in determining which URL we should choose as the canonical URL. So it's not always guaranteed that we will pick your URL as the canonical. But those are kind of the two situations that can occur and, like I said, it's not guaranteed that it will happen one way or the other. So if you do choose to syndicate your content like this, I think that's just something to keep in mind, in that it's  

#### [0:37:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2220) |  possible that your information will be shared

more broadly, and your information will be findable on other people's websites, and that maybe we will show the other website as the one, in Search results, ranking a little bit higher. So that's something where you kind of have to think about, is it important that my page is visible in Search? And if that's the case, then maybe make sure that you're just publishing content  

#### [0:37:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2250) |  on your website. Or is it important

to you that my information is available in Search? And in that case, maybe it's fine to publish it on multiple different websites. So those are kind of strategic decisions that you can make there. And I don't think there's one answer that works for all websites. If you have security reports in Google Search Console, after some submissions Google will start to review them. After a couple of weeks will this reflect other crawlbots, like desktop, mobile, et cetera?  

#### [0:38:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2280) |  So, I'm not quite sure how you

mean there. So it's really kind of hard to say. Usually if there are security issues, for example, reported in Search Console-- that would mean, for example, that maybe your website is hacked, maybe there is malware that was found on some of your pages, maybe there was some phishing that someone hosted within your website-- then those issues wouldn't affect how we  

#### [0:38:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2310) |  crawl the rest of your website. It

can affect how we show it in Search, in that if we understand your website is hacked, then maybe we need to be more careful with what we show your pages for. So that's something that can play a role there. But I don't think it would affect how we would crawl your website overall. But regardless of any effect on crawling or indexing, if your website does have security issues, I would recommend resolving those as quickly as possible  

#### [0:39:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2340) |  and trying to figure out where they

came from. So if your website got hacked, then don't just fix that hack, but rather think about how were hackers able to actually get into my website and add that hacked content? And what can I do to prevent that in the future? Do backlinks from guest posts have any ranking value, or are we wasting our time for the sake of ranking and not for traffic? I don't know.  

#### [0:39:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2370) |  It feels like this topic comes up

every couple of weeks. We've kind of had our stance on this since a number of years now. And essentially the idea is if you're doing guest posts just for those links, then for the most part, I would assume that those links have no value. So that's essentially our stance there. And there are lots of fine details there, but we've talked about them so often, there's  

#### [0:40:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2400) |  lots of information out there to check

into as well. I work on a UGC website with more than 30 million pages of content. The main content of the pages does not change much, but the auxiliary content, like reviews and comments, are added frequently. We don't track very well when each content is updated. Our sitemaps are updated daily with current value URLs, but setting lastmod for them as the current date.  

#### [0:40:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2430) |  We also set priority and change frequency

to static values. We suspect we're being limited by Crawl Budget. Can our sitemap structure negatively be affecting how Google is crawling our website? So I think there are multiple things that come together here. In general, if you always have the same date in your sitemap file for all of your URLs, we're going to be ignoring that date. So if you're doing something like you mentioned here,  

![](https://i.ytimg.com/vi/7bAHUrvFECs/hq3.jpg)



#### [0:41:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2460) |  where you're taking 30 million pages and

saying all of them changed today, then we're probably going to be looking at your sitemap and saying, well, we're just going to look for new URLs within the sitemap file. We're not going to look at the date, because the date doesn't give us any more information. It's not that we can go off and re-crawl your whole website every day. So that's kind of the main thing here. The priority and change frequency settings  

#### [0:41:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2490) |  are also settings that we generally ignore,

because we've found that they don't provide a lot of extra information. If we have a date that we can use, then we don't need to know how frequently a page might be changing. With regards to setting a date as a change date in a sitemap file, we recommend using the date that is really significant for a change on your pages.  

#### [0:42:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2520) |  So if things, like, just a number

changes on your web page, that's not usually a sign that this page needs to be re-crawled and re-indexed. But if something significant changes on your website, on those pages, then that's something where I'd say it's worthwhile picking that up and using that as a new change date. So that's the recommendation with regards to change dates in general, the last modification. If you don't do that--  

#### [0:42:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2550) |  if you have it set up like

you have here-- we will ignore the last modification date, essentially, and we will just use the sitemap file to try to recognize new URLs on a website. But we don't penalize a site for this kind of sitemap file. It's not that we would crawl less frequently, or we would crawl worse if you have a bad sitemap file like this. We will just crawl naturally, like we would any other website. And usually what that means is we will just  

#### [0:43:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2580) |  go off and crawl pages on your

website, try to refresh them in cycles that we think kind of make sense. And we will just use the sitemap file to recognize new things on your website. This doesn't affect Crawl Budget at all. So Crawl Budget is specifically more of a foundational technical thing which is based, on the one hand, on the demand that we need, that we have on our side with regards  

#### [0:43:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2610) |  to crawling and indexing. Like, how many

pages do we think we need to re-crawl from this website every day. That's kind of the one thing. We would like to do this much. And on the other hand, we kind of have the limits, which can be the limit that you may set in the Search Console. It's also based on the server capacity. How quickly do we think your server can respond? How much-- I don't know, how many requests  

#### [0:44:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2640) |  can we send it every day? Those

kind of things. And those are all independent of the sitemap file. So just because-- just if you have a bad sitemap file doesn't necessarily mean we will crawl less frequently. We'll just crawl a little bit more organically, rather than direct based on your sitemap file. Is canonicalization a best practice, or is not having duplicate content at all the best practice?  

#### [0:44:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2670) |  I think a little bit of both.

So not having duplicate content makes it easier for us to crawl and index the primary content that you want on your site, but it's kind of impractical for all websites to not have any duplicate content at all. It's essentially a normal part of the web. So because it's such a common thing on the web, using the rel canonical, using proper canonicalization, just makes it a lot easier for us to focus on the good parts of your website.  

#### [0:45:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2700) |  So reducing the duplicate content on your

site is good. Using rel canonical is also good. Wow. Lots of questions left. Let me just double-check to see. There's one other crawl rate question. Can you suggest an optimal crawl limit for Googlebot? If I set a limit of 30 requests per second, is that enough? That's totally up to you in your website. So we don't have any specific limits that we recommend.  

#### [0:45:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2730) |  Usually with regards to the Search Console

setting, we suggest that you just leave it as, like, Google decide. Because the Search Console setting is more of an upper bound limit. It's not that you're saying Google will crawl this much, but it is that Google can crawl at most this much. So for most websites you don't need to set an upper limit. We will figure that out ourselves. If you do notice that we're killing your server, and causing you a high bandwidth bill, or something like that,  

#### [0:46:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2760) |  then setting that upper limit is definitely

a good idea. Wow. Still a bunch of questions left, but time is running kind of low. Maybe I'll switch to any questions from you all, if there's anything left from your side. BARRY SCHWARTZ: Just wanted to quickly confirm that this person saying, not a single website since December 2019 has been indexed or ranked that is new,  

#### [0:46:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2790) |  like a new website? And I asked

on Twitter, had any SEOs had any new websites indexed or ranked since December 2019, and I'm getting a bunch of yeses. So there you go. [LAUGHS] JOHN MUELLER: OK. OK. I mean-- BARRY SCHWARTZ: Yeah. JOHN MUELLER: I mean, maybe it's not a general issue, but it's still worthwhile looking at these things. You know. Sometimes there are weird quirks. MIHAI APERGHIS: John, can I ask another one on internal linking, really quick? JOHN MUELLER: OK. MIHAI APERGHIS: So assuming-- let's say you've changed something,  

#### [0:47:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2820) |  like the CMS of your website, or

something like that, and you have to use a 301 redirect. And maybe because of some issues like design, or anything like that, you kind of have to link using those 301 redirects. You cannot link to the final version. Your navigation and most of your internal linking still goes to the old URL, which then 301 redirects to the new one. For users, you kind of add that extra step of a 301 redirect.  

#### [0:47:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2850) |  Does that affect Google in any way?

I know that you will kind of-- can pass over it, and doesn't [INAUDIBLE]. So-- JOHN MUELLER: Yeah. That's-- I mean, it's not great, but we work around that. So essentially what happens there is, we try to understand what the canonical is. So we'll follow that redirect, and usually we will pick the destination of the redirect as the canonical URL,  

#### [0:48:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2880) |  and then we will treat that link

as being between the source page and the canonical destination. So just because there is a redirect in between doesn't mean that there's any value lost. It's still a link between the source and the canonical destination. MIHAI APERGHIS: And just to be sure that the 301 step, that 200 milliseconds, 300 milliseconds that the user gets in addition-- that's not happening on the Google side, because you kind of pick the URL separately.  

#### [0:48:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2910) |  You don't follow it like a user.

JOHN MUELLER: No. No. So the one exception, I think, is if you have more than five steps, five redirect steps in between. Then that's something where we'll have to re-crawl that in a second round. But otherwise, we will follow those steps. We will index the destination page. Probably we'll pick the destination page as the canonical, and if we pick the destination page as the canonical then users, when they come from Search,  

#### [0:49:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2940) |  they go directly to the canonical. They

don't even follow those redirects. So even from a speed point of view, users would be going directly to that canonical URL. And from that point of view, it's more that you're adding a little bit inefficiency, and it's like you're keeping these things along, where if you crawl the website on your own, then suddenly you have all of this cruft that's kind of collected over the years. But it's not that it'll cause any problems  

#### [0:49:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=2970) |  with regards to Search. MIHAI APERGHIS: OK.

And one last thing is we have a weird case where-- it's also related to pagination-- where the link to the next page is one URL, and it goes to the next page, but within a few seconds the link changes-- I think it's using the history API to restate or replace  

#### [0:50:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=3000) |  that-- I don't remember exactly which one

it was. How does Google interpret that? Does Google see this URL change, even though there is no refresh of any kind of done? Or what exactly is happening on Google's side? JOHN MUELLER: I'm not 100% sure MIHAI APERGHIS: [LAUGHS] JOHN MUELLER: Yeah. So we do watch out for this kind of-- when you use a history API to change the URL,  

#### [0:50:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=3030) |  because we do understand that some JavaScript

based sites, you click on a link and then it uses the history API to change the URL. And in that case, we should treat that as a link. And similarly on some sites you load URL and it uses the history API to change the URL, and that should be treated like a redirect. So that's something where we try to figure out what it is that you're trying to do there-- assuming that we can process the JavaScript that is doing this.  

#### [0:51:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=3060) |  So that could be that we will

treat that as a redirect to the URL that you're changing it to. Which-- I don't know if that makes sense in your particular case, or if that simplifies the URL, or if that-- so-- MIHAI APERGHIS: If we moved some of the extra parameters that don't really-- are just for the CMS to understand you want the next page, and if then we remove those and only  

#### [0:51:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=3090) |  leave, like, page equals to something-- JOHN

MUELLER: Yeah. Probably you would see that if you use inspect URL, and you saw that we chose as a canonical the simpler URL. So that's something where you can check both of those URLs manually with inspect URL. If we've seen the simpler URL, perhaps we have chosen that as the canonical for that kind of setup. If you check the more complicated URL, and you see we picked the simpler one as a canonical, then it's definitely the case.  

#### [0:52:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=3120) |  MIHAI APERGHIS: Cool. Cool. Thanks. I'll try

that. JOHN MUELLER: Cool. CHRIS DQ: Hi, John. If I may? JOHN MUELLER: Sure. CHRIS DQ: I don't know if you remember me. We spoke a couple of weeks ago. And I'm just, really simple, chasing up, really-- sorry to do this-- on the outbound link-- unnatural linking reconsideration saga which we're going through. And I just wanted to see if you managed to take a look for us. JOHN MUELLER: Which site was that? Oh, I think you posted it up.  

#### [0:52:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=3150) |  The career site, right? CHRIS DQ: Yeah,

that's correct. JOHN MUELLER: Yeah. I passed that on to the Search spam folks, but I didn't hear anything back. So, I don't know. Is it still pending, the reconsideration request? CHRIS DQ: Yes. JOHN MUELLER: That was a long time ago, right? The reconsideration request? CHRIS DQ: It was initially from the 7th of May, the initial notification. So from the last status we received, which was the processed notification,  

#### [0:53:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=3180) |  it's been 14 weeks [INAUDIBLE] JOHN MUELLER:

OK. That seems too long. OK. I'll ping them again, to see if they can double-check to see what is happening there. CHRIS DQ: All right. Brilliant. What's your recommendation for how long we should wait, anyway? Because it's been 14 weeks since we received the process notification. And we follow-upped a few times since. I think it's been around four weeks  

#### [0:53:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=3210) |  now since our last follow-up. But we

spoke about this on the last one. So I won't bring it up again. But what's your recommendation for the wait period at the moment? JOHN MUELLER: I don't know. I don't know what the current queue there is. I mean, your site-- I think it was in English, right? So it's not-- CHRIS DQ: Yes, an English site. Yeah. JOHN MUELLER: Yeah. Sometimes it's a bit different across different languages, where someone from one of the local teams has to double-check. But it feels like especially with English  

#### [0:54:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=3240) |  we should be fairly up to date.

I'm kind of curious to see if those extra submissions that you did after the main one kind of blocked things on our side. But even that shouldn't be making it take that long. CHRIS DQ: All right. Thanks for that. That was just because you said that you feared last time it could be stuck. This is why we're wondering still what to do. So yeah. JOHN MUELLER: Yeah. CHRIS DQ: If you could do something about it, just to get some response would be brilliant. JOHN MUELLER: All right.  

#### [0:54:30](https://www.youtube.com/watch?v=7bAHUrvFECs&t=3270) |  WD-40. CHRIS DQ: [LAUGHS] Yeah. Cool. JOHN

MUELLER: OK. We're kind of at time. I'm sure there are still more questions, but feel free to maybe drop them into the next session on Friday. And hopefully I'll see some of you all there, or at least in the next Tuesday one, depending on the time zone. Whatever works better for you. All right. Thank you all for joining. And I wish you all a great week in the meantime.  

#### [0:55:00](https://www.youtube.com/watch?v=7bAHUrvFECs&t=3300) |  MIHAI APERGHIS: Thank you, John. Cheers. JOHN

MUELLER: Bye, everyone. NICOLAS OCKLER: Thank you. Bye.  