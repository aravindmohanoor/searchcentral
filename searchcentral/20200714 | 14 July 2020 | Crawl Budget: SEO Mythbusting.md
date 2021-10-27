[![Crawl Budget: SEO Mythbusting](https://i.ytimg.com/vi/am4g0hXAA8Q/maxresdefault.jpg)](https://www.youtube.com/watch?v=am4g0hXAA8Q)

## Crawl Budget: SEO Mythbusting

In the second episode of SEO Mythbusting season 2, Martin Splitt (Developer Advocate, Google) and Alexis Sanders (Senior Account Manager, Merkle) discuss the most common SEO questions and myths around crawl budget.



Specific timestamped topics discussed in this episode:

Why is crawl budget an interesting topic to discuss (0:00)

What is crawl budget? (1:15)

What is crawl rate, and what is crawl demand? (1:47)

How does Googlebot make its crawl rate and crawl demand decisions? (2:44)

ETags, HTTP headers, last modified dates, and similar (3:43)

What size of sites should worry about crawl budget? (4:35)

Server setup vs crawl budget (5:00)

Crawl frequency vs quality of content (6:18)

What to expect to see in one’s log files if Google is testing one’s server? (7:45)

Tips on how to get your site crawled accurately during a site migration (8:18)

Crawl budget and the different levels of one’s site’s infrastructure (9:40)

Does crawl budget affect rendering as well? (10:37)

Caching of resources and crawl budget (11:46)

Crawl budget and specific industries such as publishing (13:34)

What can be - generally speaking - recommended to help Googlebot out when crawling one’s site? (15:03)

What are the usual pitfalls people get into with crawl budget? (16:52)

Can one tell Googlebot to crawl one’s site more? (17:40)



Documentation mentioned in this episode:

What Crawl Budget means for Googlebot → https://goo.gle/3iIJHp2

How to move your content to a new location → https://goo.gle/3iKf2HS 

Reduce the Googlebot crawl rate → https://goo.gle/38LfMb5



Watch more SEO Mythbusting episodes → 

https://goo.gle/SEO-Mythbusting  

Subscribe to Google Search Central → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=0) |  MARTIN SPLITT: How about crawl budget? ALEXIS

SANDERS: I would love to talk about crawl budget. MARTIN SPLITT: All right. ALEXIS SANDERS: Yeah, I think it's a term that's thrown around a lot in the industry. And it seems like an abstraction of something that is much more technical and concrete. And I think we can get a lot of clarity through this video. MARTIN SPLITT: Fair enough. [MUSIC PLAYING]  

#### [0:00:30](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=30) |  Hello, and welcome to "SEO Mythbusting." With

me today is Alexis Sanders, from Merkle. ALEXIS SANDERS: Thanks for having me. MARTIN SPLITT: And you are a senior account manager? ALEXIS SANDERS: Yes. MARTIN SPLITT: OK, so you work with a lot of different companies and accounts, and have different kinds of work. Yesterday we were discussing fermented food because that's a hobby of yours. [LAUGHS] ALEXIS SANDERS: Yeah, definitely. I went on a trip, came back, and my boyfriend had fermented everything. MARTIN SPLITT: Everything. ALEXIS SANDERS: Yes. MARTIN SPLITT: So, lots of kimchi? ALEXIS SANDERS: Oh, my god. We have so much kimchi. MARTIN SPLITT: [LAUGHS] ALEXIS SANDERS: It's insane. Like in a huge jar.  

#### [0:01:00](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=60) |  MARTIN SPLITT: But we're not here today

to talk about kimchi. So what are the things that your clients and customers are dealing with, and what's a question that you often get? Or what's a topic you would like to discuss? ALEXIS SANDERS: I would love to talk about crawl budget today. So to get started, before we even talk about anything, can we start with what is crawl budget, kind of recapping some of the stuff that Gary covered in his Google Webmaster article. MARTIN SPLITT: That's a very, very good point. Actually, the article is a fantastic starting point to this entire journey. So, when we are talking Google Search and indexing and thus,  

#### [0:01:30](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=90) |  crawling, we have to have a bit

of a-- what's it called-- trade-off to make. And the trade-off that we have to make there is we want to get as much information crawled as quickly as possible, but we don't want to overwhelm the servers. ALEXIS SANDERS: Definitely. And would you categorize that part of it as crawl limit? MARTIN SPLITT: Yeah, pretty much. Or crawl rate. ALEXIS SANDERS: Almost like an abstraction under an [? objection. ?] MARTIN SPLITT: Yes. That's the crawl rate, basically-- how much stress can we put on your server without crashing anything or suffering from killing  

#### [0:02:00](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=120) |  your server too much. That's one thing.

The other thing is we just have to be reasonable with our resources. The web is really, really large, so instead of just crawling everything all the time, we need to make some distinctions there. A news website probably changes quite often, and we probably need to be catching up with them every now and then, whereas a website on the history of kimchi is probably not changing as often.  

#### [0:02:30](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=150) |  I mean-- ALEXIS SANDERS: Definitely. MARTIN SPLITT:

--nothing against kimchi, but I think the history isn't as fast-paced as the world news are. ALEXIS SANDERS: Yeah, definitely. MARTIN SPLITT: So that's the crawl demand. So we try to figure out is this something that we need to crawl more often, or is this something where it's OK if we check up every now and then. ALEXIS SANDERS: And what goes into that decision-making process? For instance, if you had that kimchi website, or if you had something like archive.org, where it's really just something that's going to be constant for a long period of time and there really isn't going to be any changes, how do you guys determine that? MARTIN SPLITT: We basically fingerprint content  

#### [0:03:00](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=180) |  as we crawl it. So we see

what is this page about. We use that for deduplication later on, but we also look into when was this last changed. So you can tell us, and things like structured data has possibilities. You can have date elements somewhere in your page. And we more or less keep track of how often or how frequently things are changing. And if we detect that the frequency of change is really low, then we don't have to crawl as much. That has nothing to do with quality. You can have fantastic content that will rank really high  

#### [0:03:30](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=210) |  or whatever that never changes. It's more

about is this information that we need to revisit every now and then, or is this something that we can leave alone for a longer period of time. ALEXIS SANDERS: Now, do you guys use something like the ETag or the last-modified network header, or is it more about taking that fingerprint of the content? MARTIN SPLITT: You can give us various hints. As I said, structured data dates are one. ETag is an interesting one, as well.  

#### [0:04:00](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=240) |  The HTTP headers are useful for this

last-modified date in sitemap. Right? And the more useful you're making these-- if you just automatically update the last modified date in the sitemap and we figure out that does not correspond to actual changes on the website, or the website changes are minimal, then that's not helping us. ALEXIS SANDERS: Don't want to waste our resources. MARTIN SPLITT: Exactly. Not only that. At some point we're just going to be like, OK, this is not useful for this particular site, so. But as much information as we get we will use to figure out what we can reasonably  

![](https://i.ytimg.com/vi/am4g0hXAA8Q/maxres1.jpg)



#### [0:04:30](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=270) |  expect as a change frequency. ALEXIS SANDERS:

So going backwards a little bit, what size of sites should be worried about crawl budget, should be worried that hitting that crawl limit? MARTIN SPLITT: Large sites. ALEXIS SANDERS: Large sites. And if we were to give-- MARTIN SPLITT: Millions URLs. ALEXIS SANDERS: Millions of pages. OK, cool. So if you have under a million pages, really, crawl budget is not something that you should be concerned about. MARTIN SPLITT: Yes. Unless you have a really flaky server setup. But then, again, crawl budget isn't your problem. Your problem is your server setup, right? ALEXIS SANDERS: No, definitely.  

#### [0:05:00](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=300) |  So do you typically see that the

issue isn't really with the server setup but more with the crawl demand? Or do you see it more with the server setup? MARTIN SPLITT: It depends on what you say the issue is. Normally, crawl budget gets cited in many, many different times when it actually wasn't an issue to begin with. It was just like the quality of the content was bad and that's why we didn't index it, so we crawled it. We figured out, oh, this is not worth keeping. Then we didn't index it. And people were like, so is this a crawl budget problem? And we're like, no, we have crawled it.  

#### [0:05:30](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=330) |  It was just not good. ALEXIS SANDERS:

And is that what you would typically see in the Excluded section of the GSA report? Something along those lines? MARTIN SPLITT: Yeah, exactly. These things are really helpful. Sometimes you also see people are like, oh, yeah. My crawl budget is really low. And then we're like, yeah, but is that a problem? Are you having lots of changing content? And they're like, actually, no. It's a blog that updates once a week. And then we're like, hmm. How big of a problem really is that? Sometimes it's also people just barely missing  

#### [0:06:00](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=360) |  the crawl window where it does not

discover the URL. And if you're not submitting it in sitemaps, then we have to crawl another page to find that link to that URL, and then we're going to crawl that one. So using sitemap reasonably is a good idea for these things. But again, if you're not having millions of pages then crawl budget is rarely an issue. ALEXIS SANDERS: Let's say you're working with a major e-commerce, or something like real estate, where you have hundreds of millions of pages that are a little bit smaller, maybe a little bit similar. Is there anything that those industries can do to make their pages crawled more often or more  

#### [0:06:30](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=390) |  appealing to Google? MARTIN SPLITT: The thing

is, being crawled more often is not necessarily helping. It's not giving us a signal for quality, or it's not meaning like, oh, this is fantastic. Having something crawled, and then indexed, and then never changing is OK as far as we're concerned. But for e-commerce, I would highly recommend-- you were saying something really interesting like lots of smaller pages that are very similar to each other. If they are very similar to each other, should they exist  

#### [0:07:00](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=420) |  is my first question. Can you extend

the content? For instance, if it's product variations of it, maybe you just describe them in the table inside one page rather than having 10 pages for all the variations. ALEXIS SANDERS: Definitely. MARTIN SPLITT: Which colors are available? Well, that's not-- ALEXIS SANDERS: It almost brings the fact that there's so many different issues that fit into crawl budget. MARTIN SPLITT: Exactly. ALEXIS SANDERS: Whether it's duplication, or finding the pages, or having a service. MARTIN SPLITT: Yes. Server speed is an issue, right? ALEXIS SANDERS: Yeah. MARTIN SPLITT: If you have a server that every now and then just flakes on us, then we don't know.  

#### [0:07:30](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=450) |  Is that because it's a flaky server?

Is that because we're about to overwhelm you? ALEXIS SANDERS: Got a flaky server. MARTIN SPLITT: Yeah, it's like it's just wobbly and falling over every now and then, then we have to be careful. ALEXIS SANDERS: No! MARTIN SPLITT: We have to touch very lightly on that server. ALEXIS SANDERS: So let's say someone is switching over their site to a more powerful server. What is something they should expect to see in their log files if Google is testing their servers to see how much they can handle? MARTIN SPLITT: They might see an increase in crawl activity and then a small decrease again, and basically there's  

#### [0:08:00](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=480) |  this wave motion that's going to happen.

But normally, when you just switch the server and nothing else changes, you might not even see us doing anything. You just see it just continues to go through. ALEXIS SANDERS: Definitely. MARTIN SPLITT: Unless you change from something that was broken to something that works. Then you probably see more crawling happening. ALEXIS SANDERS: OK. So what about in a situation of migrations? A lot of sites are really hyper-aware about how their site is being crawled during a migration. Are there any tips that you guys have to making sure that your site is being crawled accurately?  

#### [0:08:30](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=510) |  MARTIN SPLITT: What you can definitely do

is you can make sure that you're, more or less, progressively updating your sitemap and saying this has now changed. This has now changed. And this has now changed. And it's now time to crawl that. And we crawl it. We get a redirect. That's actually a change that is interesting for us. And then you can control a little bit on how we discover the change in the migration. But generally speaking, just make sure that both servers are up on par and running smoothly,  

#### [0:09:00](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=540) |  and not flaking out every now and

then or giving us error codes. Make sure that your redirects are set up correctly, as well, and that you're not accidentally blocking important things for us to understand once we are landing on the new site. If you have a robots.txt beforehand, and then you change that to completely different URLs being blocked and put that on the other thing, that we're like, what's happening here? ALEXIS SANDERS: What is going on? MARTIN SPLITT: So that's not a great idea. So try to do one thing at a time. Do not be like, we're going to change the text deck, we're going to change the server, we're going to change the URLs, we're  

![](https://i.ytimg.com/vi/am4g0hXAA8Q/maxres2.jpg)



#### [0:09:30](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=570) |  going to change the content, and we're

going to migrate to a different domain. That's a lot. ALEXIS SANDERS: Too much for one year. Too much for one project. No, for sure. So, for crawl budget, what levels of a site does it affect? So if you have a CDN, will it affect your site? If you have a subdomain, or a domain, at what levels of your infrastructure is it affecting? MARTIN SPLITT: That depends. So, generally speaking, we go on the site level, so everything that is on the same domain. Sometimes subdomains might be counted towards that.  

#### [0:10:00](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=600) |  Sometimes they are not. CDNs are one

where it's kind of counted against your site, but not really. You should normally not worry about it. I think crawl budget-- ALEXIS SANDERS: Stop stressing so much, SEOs. [LAUGHS] MARTIN SPLITT: Enjoy yourselves. What's interesting is, when it comes to crawl budget, where I would say you should consider this, especially if you're dealing with user-generated content, you can try to tell us not to index or not to crawl certain things that you know are bad.  

#### [0:10:30](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=630) |  So it's more of a content side

of things rather than the technical infrastructure side of things. ALEXIS SANDERS: Yeah, definitely. So does crawl budget actually affect both your crawling phase and your rendering phase? MARTIN SPLITT: Crawl budget does actually touch on rendering because as we render, we will fetch additional resources that comes with the crawl budget. Because, again, the trade-off is still there. When we're crawling initially, we don't want to overwhelm your server, but the same goes to when we are rendering. We don't want to overwhelm your server there.  

#### [0:11:00](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=660) |  What's the point in killing your e-commerce

website just because we are making thousands of requests at the same time to crawl all these resources? So it can happen, especially if you have a large site with millions of URLs and you get your caching wrong, for instance, that we actually have to fetch everything over and over and over again, which means we have a lot of simultaneous requests to your server. If your server then slows down significantly, then we'd be like, oh, OK. Careful. And then resource fetches might fail. So we might be able to fetch and render the first--  

#### [0:11:30](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=690) |  I don't know-- 500,000 pages, but then

suddenly the resources seem to fail because we're like, ah. We don't want to make more requests at this point. And then we can't really render them. So that would be bad. ALEXIS SANDERS: Yeah. So what do we do in terms of caching for those resources? Obviously, with pages, we can put them in [INAUDIBLE] sitemaps, and all the stuff you mentioned before with potentially structured data, and then maybe even adding some network headers. But what do you think about those resources that could be really consuming of Google's resources?  

#### [0:12:00](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=720) |  MARTIN SPLITT: Absolutely. The thing is, we

are trying to be as aggressive as possible when we are caching sub-resources, such as CSS, JavaScript, API calls, all that kind of stuff. If you have API calls that are not GET requests, then we can't cache them. So you want to be very careful with doing POST requests or something like that. ALEXIS SANDERS: Don't do POST. MARTIN SPLITT: Some APIs are doing that by default. And then I'm like, ay. That's an interesting one because we can't cache it, so that's going to consume your crawl budget quicker. The other thing is you can help us  

#### [0:12:30](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=750) |  by making sure that URLs, optimally, never

change. So what is a really good idea is you can have content hashes in your resources. So instead of saying application.JavaScript, you can say application dot and then this hash that describes the content, like AEF, CE-- ALEXIS SANDERS: Nice. So, basically, 16 characters. MARTIN SPLITT: Exactly. Like these [? MB5 ?] hashes dot JavaScript. And this will never change. So when you're making an update to your JavaScript, you get a different URL. So we can cache the other thing forever,  

#### [0:13:00](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=780) |  and once we get the new HTML,

we get the new URL for the JavaScript, and then-- ALEXIS SANDERS: It's almost like versioning, right? MARTIN SPLITT: It's like versioning in the URL. Exactly. ALEXIS SANDERS: Nice. MARTIN SPLITT: So that's a great idea. ALEXIS SANDERS: So for that first version that you would have, or any particular version that you would have, how long is that typically cached for? MARTIN SPLITT: It depends, but we're trying to cache as aggressively as possible, so this can be like a day. This can be a week. This can be a month. And we might ignore caching headers. So if you're telling us this expires tomorrow and we're like, no, it does not, then  

#### [0:13:30](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=810) |  we might just cache it nonetheless. ALEXIS

SANDERS: Yeah. Awesome. So do you find that any particular industries complain more about crawl budget than others? Or talk more about it? MARTIN SPLITT: That's true. I think e-commerce and publishers are quite prone to this because they have, historically, typically large sites with lots of pages, and they might actually run into this. We had a really interesting situation with one webmaster presented that at a Webmaster conference in Zurich once. In Japan, it's a website that has  

![](https://i.ytimg.com/vi/am4g0hXAA8Q/maxres3.jpg)



#### [0:14:00](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=840) |  lots of user-generated content. And they do

machine learning to figure out if the quality of the content that was produced is considered good or not. And if it's not good, then they put it in noindex, and they put it in robots.txt, so that we're not wasting crawl budget on it. And that way they steer-- because they had a crawl budget of 200,000 pages per day or something like that, but they had a million coming in, and most of it was spam. So they're like, ugh, it's annoying if we just waste our crawl budget for the day on spam that will not get indexed anyway. So that's an interesting one.  

#### [0:14:30](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=870) |  ALEXIS SANDERS: Do you believe that there

is an overall quality metric that Google uses? So, for that particular site in general, because they had so much non-high-quality content, did that affect Google's outlook on their content overall? MARTIN SPLITT: Not really. It was more like this page is not good. We're not going to put it in the index. So that's the outcome, really. ALEXIS SANDERS: OK, nice. MARTIN SPLITT: Or if it's light on content. If someone just literally posts a picture and says ha, ha, then that's not great content necessarily, especially if the picture is just a repost of some meme or some stock photo, right?  

#### [0:15:00](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=900) |  ALEXIS SANDERS: Yeah, definitely. So what are

some things that we, as webmasters, and SEOs, and agency people can recommend to our clients on how to help Googlebot out, and help me your rendering system out, as well? MARTIN SPLITT: If you know that there's URLs that you don't need to render the page-- and that's a very big be careful here because if you're blocking the entire API because you're like, oh, we don't need the API, and then the JavaScript does need the API to render the page, then that you shouldn't block. ALEXIS SANDERS: You don't get the full experience. Ugh! MARTIN SPLITT: Exactly. Do not block that because then we might actually not  

#### [0:15:30](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=930) |  see much content. But if you have

something that definitely-- like internal analytics, or some internal tools, or some chat tool that pops up, or whatever, don't let that be crawled because what's the point. Also, you can use-- ALEXIS SANDERS: And do you recommend blocking at the robots.txt for those particular resources, like kind of throwing them in a folder and-- MARTIN SPLITT: If you don't want them crawled, sure. Yes. Yes. Just be careful that you're not putting something in robots.txt that turns out to be useful and important later. ALEXIS SANDERS: Yeah. Big caution there. MARTIN SPLITT: Yes. You can also-- especially with client-side rendered apps,  

#### [0:16:00](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=960) |  you oftentimes have a bunch of API

calls going to and from. You can proxy that through a facade kind of thing. You basically build a little application, and all it does is it takes one request for one specific piece of data that you need to render the page, makes all the API requests and all the back-end requests that it needs, maybe has a layer of caching, as well, to make this faster, and then has one response going back. That way, you have one request, one response cycle. ALEXIS SANDERS: So I may sound a bit goofy, but this is something like GraphQL? MARTIN SPLITT: Right, GraphQL. Exactly, yes. But with GraphQL, again, be careful to not use  

#### [0:16:30](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=990) |  the POST mode. ALEXIS SANDERS: No POST

mode, people. MARTIN SPLITT: Make sure that it uses GET requests, not POST requests. ALEXIS SANDERS: OK. Cool. MARTIN SPLITT: Yeah, there's a bunch of stuff you can do. And, basically, cut off the bits that you don't want crawled. And give us information of the frequency of change in sitemaps and stuff, so that we can get a better grasp of where we should be spending our time. ALEXIS SANDERS: Definitely. And do you see any pitfalls that people fall into with crawl budget quite often? MARTIN SPLITT: Well, definitely the robots one. That happens all the time, that they block something that turns out to be an important resource.  

#### [0:17:00](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=1020) |  Like, it does not need to load

the CSS. And we're like, ah. ALEXIS SANDERS: We don't know what the page looked like, so we need the layout, or something like that. MARTIN SPLITT: Exactly. People sometimes fall for it when they do A/B testing, like something gets noindexed when they don't want it, and then they waste crawl budget on something that doesn't end up in the index. And I'm like, hmm. Yeah, all sorts of things can go wrong. My favorite is when people are dealing with servers that are not configured correctly, and then they just give you a 500-something. And we're like, OK, if this happens, then we're not crawling as much anymore because we don't  

#### [0:17:30](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=1050) |  want to overwhelm your server. And then

people are like, why is Google not crawling this? And we're like, well, because your server constantly tells us that it's overwhelmed, so hmm. ALEXIS SANDERS: Yeah. So let's say you have a very large site, and you know you have these mega-powerful servers with gigabytes and gigabytes of data. Is there any way that we can tell Google that, hey, you can crawl us more, like we expect you to crawl us more here? MARTIN SPLITT: You can't, really. We are detecting that. What you can do is you can limit us. But you can't really say more, please, more, please.  

#### [0:18:00](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=1080) |  ALEXIS SANDERS: OK. MARTIN SPLITT: This crawler

scheduler is relatively clever when it comes to these kind of things. And normally, if we detect like, oh, there's lots of good content out there on this page, and the site map is full of URLs, then we will try to grab as much as we can. And as long as your server doesn't tell us not to, we'll continue doing that. So, eventually, the crawl budget might ramp up to what you would expect to see. ALEXIS SANDERS: Ah, lovely. So just keep creating fresh, great-quality content. That's really what it comes down to to get [INAUDIBLE]  

#### [0:18:30](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=1110) |  MARTIN SPLITT: That's generally the answer to

pretty much everything. Good quality content. If it's fresh, also great. ALEXIS SANDERS: Awesome. MARTIN SPLITT: Yes. Alexis, thank you so much for being with me and having this fantastic conversation. And I think there was a bunch of nuggets in there. And it was great having you here, so. ALEXIS SANDERS: Thank you so much. MARTIN SPLITT: We did this. ALEXIS SANDERS: Yes! MARTIN SPLITT: And I hope you enjoyed it. And see you soon again. ALEXIS SANDERS: Thanks so much, everyone. [MUSIC PLAYING] MARTIN SPLITT: Next episode, we have Eric with us. And we're going to be talking about page speed-- how it works in ranking, what to look out for, what to not do,  

#### [0:19:00](https://www.youtube.com/watch?v=am4g0hXAA8Q&t=1140) |  and how to not get it wrong.

ERIC: It's such a great topic because so many people do get it wrong, I'm afraid. MARTIN SPLITT: So, don't miss out on the next episode.  