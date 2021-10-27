[![English Google Webmaster Central office-hours from December 13, 2019](https://i.ytimg.com/vi/5QxYWMEZT3A/maxresdefault.jpg)](https://www.youtube.com/watch?v=5QxYWMEZT3A)

## English Google Webmaster Central office-hours from December 13, 2019

This is a recording of the Google Webmaster Central office-hours hangout from December 13, 2019. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Watch out for new sessions, and add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



Feel free to join us - we welcome webmasters of all levels!



Subscribe to Google Search Central → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=0) |  JOHN MUELLER: All right. Welcome, everyone, to

today's Webmaster Central Office Hours Hangouts. My name is John Mueller. I'm a webmaster trends analyst here at Google in Switzerland. And part of what we do are these office hour hangouts where people can join in and ask their questions all around their websites and search. A bunch of things were submitted already, so we can go through some of that. But as always, if any of you want to get started with a question, feel free to jump on in.  

#### [0:00:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=30) |  AUDIENCE: Hi, John. JOHN MUELLER: Hi. AUDIENCE:

One thing that we have faced or one issue with one of our clients, [INAUDIBLE]. So most of the time, they get a gift basket or [? gift ?] [INAUDIBLE]. And we transmit it well after a few-- four or five years. But this year, we made something new from the website. But the blog we have, we moved it to a subdomain.  

#### [0:01:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=60) |  So now blog is-- the blog URL

is like blog dot domain name dot com or something like this. That is all the URL of the blog post changed. Now, our strategy was writing good content for the blog at [INAUDIBLE]. And we give link from our blog to the product category and product pitch. But after changing this thing, after moving the blog from the domain to the subdomain, ranking dropped a lot. So is there a reason that what we did [INAUDIBLE]??  

#### [0:01:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=90) |  We submit the subdomain to the Google

search console. But do you think it is because of the-- moving the blog from the domain to the subdomain? JOHN MUELLER: It might be. It's hard to say kind of absolutely. But what might be happening there is that we start seeing this as a separate site. And we see essentially you going from one site  

#### [0:02:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=120) |  to splitting it up into two sites.

And that takes a while for us to understand. And that takes a while for us to understand kind of the context of those two new sites, even if it's the same content as before. So that's something that could be coming from that. But it is really kind of hard to say. And it's something where there is not really  

#### [0:02:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=150) |  a technical indicator that would tell us

this is because of this or because of that. It's essentially just kind of the new ranking. And if this is something that was recently done like, say, in the last couple of months, then I could imagine that it just takes a little bit longer to settle down. AUDIENCE: And the next question is the structure data. So if I had two types of a structure that I wanted, is it OK, for example, if it is an e-commerce site  

#### [0:03:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=180) |  and local business? So if I add

one structure data for the product and another structure data for the local business, is it OK? JOHN MUELLER: Yeah. Yeah. AUDIENCE: And my last question, does Google consider block comment as main content or supplementary content? JOHN MUELLER: It depends. I mean, we see it as a part of the page. So that's something where we would probably see it as part of the main content in the sense  

#### [0:03:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=210) |  that when we look at a web

page, we have things like the navigation all around, the footer, the sidebars, these things which are kind of the parts that we would see as boilerplate content and not as critical. But the blog post and kind of the changing content on a blog page, which would include the comments is something that we would see as the primary content.  

#### [0:04:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=240) |  We would try to understand that these

are blog comments, but essentially, these are a part of the primary page. And sometimes what can happen is that maybe you don't have a lot of content in your blog post, but there are lots of really good comments on there. So it's important for us to say, well, this could be something that is really useful for this particular page, so we should not just ignore it by default. AUDIENCE: OK, thank you. JOHN MUELLER: Sure.  

#### [0:04:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=270) |  All right. Let me run through some

of the questions that were submitted. And as always, you're welcome to jump in in between. And we should have some time towards the end as well to go through other questions that come up. Can editing the robots.txt on the main domain affect crawling of images that are served by separate CDN domain. What happens if the robots.txt for the CDN returns a 503?  

#### [0:05:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=300) |  So robots.txt is per hostname and protocol.

So if we're looking at a web page that's hosted on, say, www.example.com, and that includes content from a different subdomain or from a different domain completely, then we would use the primary robots.txt file on www.example.com for that page.  

#### [0:05:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=330) |  And for the embedded content, we would

use wherever that embedded content is hosted. So that's something where essentially for that request that we want to make to the server, we check for that subdomain, for that hostname whether we are allowed to call it. So blocking something on the www version would not block it from being crawled from a different hostname or different subdomain.  

#### [0:06:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=360) |  What happens if the robots.txt returns 503?

So 503 is a temporary error that basically tells us we should try again later. It's a bit of a tricky one. Probably the question-- because it's a question as well in the sense that we see these errors as blocking in that by default, when we see a server error,  

#### [0:06:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=390) |  we say, we don't know what the

robots.txt file is, so therefore, we will not crawl anything from this hostname. That's kind of the default situation. However, sometimes we see that these kind of server errors are more like a permanent thing. They're not a temporary situation where we just temporarily can't get access to that file. But rather, we see this as a permanent error. And then in cases like that, we often  

#### [0:07:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=420) |  fall back into kind of this state

that, well, maybe the server is just sending us the wrong response code and this should be a 404 page. So what generally-- I think we have this documented in the robots.txt documentation as well. What generally happens is we see the 500 or 503 error. We stop crawling completely. And then after a certain period of time-- I don't know, maybe a couple of months or so.  

#### [0:07:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=450) |  I don't know if we have anything

specifically documented there with the time frame. After that period of time, we think, well, this is a permanent error, so therefore, we should treat it like a permanent [INAUDIBLE] and try to see what we can crawl normally. So that might be happening there. And if it's been 503 for a really long time, maybe we're crawling it because of that. AUDIENCE: Hiya, John. That was my question. Part of the reason I asked it was there  

#### [0:08:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=480) |  was a bit of misinformation going around

and people giving incorrect advice, so I kind of wanted a bit of a back opponent. And the scenario was interesting. It was a client with a Google shopping. And their shopping campaign got completely switched off because of the 503 error, and they couldn't access the images. And two days ago, the company fixed the problem and instantly, the images came back.  

#### [0:08:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=510) |  So confirming that's your behavior. JOHN MUELLER:

Yeah, that seems kind of the way that it should be working now. So a 503 is also a good way of stopping crawling completely if there was some technical reason that you really need to stop crawling of your website, then you can return 503 for your robots.txt file, and we'll stop crawling as soon as we reprocess that, which  

#### [0:09:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=540) |  is usually within a day. So sometimes

you need to have it stop crawling. Sometimes you don't want to have it stop crawling. AUDIENCE: Cool, cheers. JOHN MUELLER: Cool. Then question about thin content. Several months ago, we removed a lot of thin pages and redirected them to a single page which consolidates the content from these thin pages into one page. The thin pages are still being indexed in search  

#### [0:09:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=570) |  even though they redirect to the new

page. The URL inspection tool shows the thin pages as returning 200, but the screenshot shows the correct redirected page. What's happening here? So I think there are a few things kind combined here. On the one hand, redirecting thin pages and making a better version of a page, perfectly fine. I think that's always a great idea. On the other hand, the URL inspection tool-- we try to show the content that we would end up indexing there.  

#### [0:10:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=600) |  So we silently follow redirects on pages

like this. So if you look at a page that is redirecting to a valid page, then the URL inspection tool will say, well, there's a valid page here because that's what we would index under that URL. So you don't see that redirect there. That's kind of confusing if you're trying to diagnose a redirect like this. The last thing that almost always happens with redirects  

#### [0:10:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=630) |  is that we continue to understand where

the page used to be hosted, kind of the old URL. And if someone explicitly looks for something that seems like they're looking for the old URL, we'll try to show it to them. So a really common way to see this is if you do a site query for an old domain if you've moved to a different domain. You'll continue to see a lot of results there. And that's not because we didn't process those results,  

#### [0:11:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=660) |  but rather because we think you're looking

for the old domain, so we'll show it to you, kind of trying to be helpful when probably you don't want us to be helpful. So with a site query, that's pretty common. But what I imagine might also be happening in your specific case is if someone is looking for a query or looking at a query that looks very similar to your old URL  

#### [0:11:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=690) |  like taking the words from the old

URL and they're looking for that, then it might be that we would show that old URL in search as well. A good way to double check that we're picking up the new one is the URL inspection tool, kind of checking out which one we have indexed and looking at the cache page. So usually if you look at the cache page, you'll see the URL of the new page, which with that example that you have there, that's what's happening there.  

#### [0:12:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=720) |  So from my point of view, I

don't think you need to do anything different here. It's just kind of maybe it's good to be aware that. Sometimes we show the old URL in search even though we've switched everything over to the new URL. And I think you also mentioned the URL removal tool in the question. You definitely don't need to do that. The URL removal tool would just hide that page in search.  

#### [0:12:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=750) |  So in that case, if someone is

looking for the words that would trigger your old URL to be shown and you have the URL removal tool active, then we would not show anything. we wouldn't even show the new one. So the removal tool doesn't affect the choice of canonical or the choice of the visible URL. I have a website that was a mediocre quality, but I improved a lot in terms of content. Now it's suddenly appearing on pages 4 to 6  

#### [0:13:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=780) |  and sort of stuck there for the

last month. I read you once mentioned that the effects of refining websites can take more than six months to reflect in search. Does that still hold true? If yes, then it wouldn't make much more sense to start with a new domain instead of improving the old one. So six months is not a fixed time. That's essentially just something that I see from time to time.  

#### [0:13:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=810) |  And it's particularly something that with larger

websites you tend to see. Like if you make really significant changes on a larger website, then there's a lot of content that needs to be recrawled and reprocessed, and that takes a lot of time. So that's kind of where I pulled that six months number out. It doesn't mean it will always take six months. It doesn't mean that it will always be complete in six months. Sometimes it takes longer.  

![](https://i.ytimg.com/vi/5QxYWMEZT3A/maxres1.jpg)



#### [0:14:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=840) |  A lot of times for smaller websites,

it usually ends up happening a little bit faster. So in your case, it sounds like it's more of a smaller website. If you kind of significantly improve the content of the whole website, then that seems like something that you can kind of, I don't know, like I'm guessing on the order of maybe 100, couple 100 pages. And that's something that usually we  

#### [0:14:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=870) |  would be able to crawl and index

a lot faster. With regards to the ranking in general, there is no kind of fixed rule that we would rank pages significantly higher after you've improved the content. These things do take time as well. And sometimes, improving the content-- so there's a lot involved with improving the website. It's not just like rewriting some pieces of text and making them look a little bit better.  

#### [0:15:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=900) |  So that's something where I continue to

work on this to try to find ways to improve that. If you're active in a competitive area, then it might also make sense to kind of think about how you can differentiate yourself from other sites, not just with regards to the content that you have there, but kind of with your offering in general. Like what can you provide that is significantly different than everyone else that is such that when  

#### [0:15:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=930) |  people see your stuff for the first

time that they'll be able to-- or they'll want to come back specifically to your site. AUDIENCE: Hi, John. JOHN MUELLER: Hi. AUDIENCE: Yeah, how are you? JOHN MUELLER: Pretty good. AUDIENCE: Yeah, and I have a question regarding Google Search Console. Like one of the websites we have in Google Search Console, it's showing that the site bar, sitemap is not able to be a page.  

#### [0:16:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=960) |  So when I [? constrict ?] the

[INAUDIBLE] letter, what does it-- it's showing that it's typically not permitted. But, in fact, there is no-- [INAUDIBLE] has been defined. And the URL is accessible without any problem. I just want to know will it be a temporary kind of thing, or do we need to do anything specific? And right now, there is no preferred domain stating also it's not directly in the new Search Console. And so how I can fix this?  

#### [0:16:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=990) |  Yeah. JOHN MUELLER: Yeah, so preferred domain

you need for sitemap file. But like with any of the other features in Search Console that are not migrated over to the new Search Console yet, that's something-- you can continue to use those features. Just because it's in the old Search Console doesn't mean you can't use them. So I would continue to use that. With regards to sitemap file, it might be good  

#### [0:17:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1020) |  if you could send me a link

to the sitemap file. Maybe you can drop it in the chat here, and then I can take a look at that with the sitemaps folks afterwards. AUDIENCE: Sure, thank you. JOHN MUELLER: Cool. All right, let's suppose we have two authors. One is an expert and one is a no name. They write exactly the same piece of content. Will there be any difference in ranking based on which name is shown as the article author?  

#### [0:17:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1050) |  I don't know. This is-- this feels

like a very theoretical question in the sense that in practice, if you're writing as an expert, then you highlight your expertise and you show to users, you show everyone that you know what you're talking about, you kind of have background information, you can back your information up. So that's something where I would expect from-- even from a user's point of view to understand  

#### [0:18:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1080) |  that there is a difference between this

kind of content. And in general, when you're making a website, I would take steps to make sure that you're highlighting why your version of this content is a good version and why people should be able to trust you because you have background information, or you kind of have all of these references that you can point at, or you're an expert in this field. All of these things are things that I  

#### [0:18:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1110) |  would try to highlight as much as

possible. And that's something that we would be able to pick up directly or indirectly sometimes. It really depends on the pages themselves. But it's something I wouldn't kind of treat as a theoretical thing, but rather it's like this is a practical way of showing why people should trust your website and kind of come to you rather than to random other people. So that's something where I would expect things to--  

#### [0:19:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1140) |  all that to make kind of sense

and help out a bit. Oh wow, so many people jumping in. Does Google consume structure data better if it's coded in an at graph versus separate snippets in JSON-LD? And there's a link to I think a plug-in that does some structure data.  

#### [0:19:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1170) |  So I'm not aware of any difference

with regards to how we process this structure data. In general, what happens with structure data is either we can read it or we can't read it. It's not that there is a better or worse or kind of like if you do it like this, provide the exact same information and structure data as you would do it in a different way that one would be better and one would be treated with more weight or given a ranking advantage  

#### [0:20:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1200) |  or anything like that. If the structure

data is valid, if it works in the testing tools, if it shows up in Search Console as something that we've processed, then it works. So there is no better or worse from our point of view if we can process it. And I know Yost specifically that that you linked to there, they spend a lot of time to make sure that their structure data works. So that's something where if it works for you by using a plugin  

#### [0:20:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1230) |  like this, then go for it. I

wouldn't say you have to manually code it or you have to do it exactly the same way as we have in the developer documentation. But rather if it works, if it's technically correct, if it can be processed, then it can be processed. I'm having an issue where Google is ignoring 301 redirects when selecting canonical URLs. So I think this probably falls into a similar situation as one  

#### [0:21:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1260) |  of the earlier questions. So one thing--

maybe I [INAUDIBLE] with the other question is when it comes to canonicalization, we use multiple factors to try to figure out which URL we should be showing in Search, so which one we should pick as a canonical URL. A 301 redirect is definitely a really strong sign. There's also the rel canonical that you can put on a page, the meta tag or the header tag.  

#### [0:21:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1290) |  Internal linking plays a really big role

for us. Like if you're saying this page is canonical but you're not treating it as a canonical, then that would be kind of tricky for us. External linking plays a role as well, sitemap files, atrifling, all of these references of individual URLs within your website, they do play a role for us. So that's something where sometimes these signals all align and we try to follow that.  

#### [0:22:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1320) |  And sometimes they're a bit confusing and

we have to guess. And if you make it so that Google has to guess, then Google will guess, and maybe it won't guess what you want it to have happened. So that's kind of just as background with regards to canonicals. The other thing that I think is also really important to realize is that these things are generally not a ranking issue in the sense that if Google picks  

#### [0:22:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1350) |  a different canonical, it doesn't mean your

pages will rank worse. It just means that we will show that page with that specific URL in search. And usually the ranking would be exactly the same as any other canonical page. So for us, it's more a matter of practical thing, like which URL should we show in search, which URL should we be crawling the most? That's kind of the thing there. So if we're not picking the canonical that you want,  

#### [0:23:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1380) |  at least it's still ranking in the

same place. It's not critical that you urgently need to jump in and change something to make Google pick that up. So let me look at the examples that you have there. You have a redirect from a page that moved from one domain to another. Google selected the old domain as canonical despite visiting the new page in October. So, to me, there might be two things happening here.  

#### [0:23:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1410) |  On the one hand, maybe you're doing

a site query for the old domain. If you do that, then we will definitely try to show the old domain, even for a really long period of time. Sometimes multiple years, we'll know that the old domain used to be here and that it's now redirecting. And doing a site query for an old domain will still show that. So like October of this year, that seems like something definitely we could still be showing if you explicitly  

#### [0:24:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1440) |  look for that old domain. The other

thing is if you're saying this page was visited in October, that sounds like a page out we don't crawl that often. So that's probably something where maybe it's just a matter of us getting to all of these pages as well. But kind of like I said, in general, this is not something that would be affecting the ranking of this page. It's really just the URL that is shown for that page in the search results.  

#### [0:24:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1470) |  Redirect on a category page adjusting the

URL structure now using parameters. That seems like something where it might be that you're explicitly looking for those with a site query. It might also be that there are still kind of conflicting signals that we're seeing for these kind of things. So if you're changing the internal structure of a website, then often we'll still see a lot of internal links that are going to the old pages.  

#### [0:25:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1500) |  And as a user when you're clicking

around on the website, you don't necessarily immediately see that. But what you can do is use a local crawler, something like Screaming Frog or, I don't know, DeepCrawl or the these various crawler tools and run it over your website to really make sure that there are no links still going to the old version of the page that end up being redirected. So if you can really make sure that your internal navigation is clean and only points at the new URL,  

#### [0:25:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1530) |  then that helps us quite a bit.

AUDIENCE: Hi. John. Couple of quick questions on [INAUDIBLE].. One is related to that experiment I'm running with changing the URL to see if the page would start ranking better. You mentioned last time just show up for a core code to Google while also showing the page to use those so that Google drops  

#### [0:26:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1560) |  it completely out of the index while

users can still access it. Because Google did the canonical from our old URL when we dropped it to the new URL despite showing a 404 for the old URL. So idea is that we did that. We did the 404 codes and the page completely dropped out of the index. But the old URL is still showing a canonical to this one that we  

#### [0:26:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1590) |  404'd. So is it normal that I

can see in Search Console a URL that shows a canonical another page that's a 404 now? JOHN MUELLER: I think that could happen. But that's more like a temporary state in the sense that we need to propagate all of this information back in the index as well. I imagine over time that that will just  

#### [0:27:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1620) |  be seen as a 404 everywhere. But--

AUDIENCE: So if I change the URL to a new one now and let Google index it, would I have any issues in those older URLs changing and pointing as a-- Google choosing a canonical for this new one? JOHN MUELLER: I don't know. It seems like a very confusing state at the moment.  

#### [0:27:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1650) |  Yeah. AUDIENCE: So should I just leave

it [INAUDIBLE].. JOHN MUELLER: I would let that settle down a little bit first, yeah, yeah. AUDIENCE: OK. JOHN MUELLER: You're testing all of these weird things that are internal anecdotes almost of how we store things, so it's kind of cool to see. AUDIENCE: Living dangerously, yeah. Yeah, I'll just let the holidays pass then and see afterwards. One other thing is related to the URL parameters tool.  

#### [0:28:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1680) |  So the documentation doesn't really cover one

case where-- so you can choose which page should Google crawl, and you have the representative URL there. So that recommendation doesn't cover that case, so I'm not sure exactly what representative URL is. I mean, would Google crawl that URL as the representative URL, or the one  

![](https://i.ytimg.com/vi/5QxYWMEZT3A/maxres2.jpg)



#### [0:28:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1710) |  that it canonicalizes to or what exactly

is that? JOHN MUELLER: No, we would try to pick that one that you specify. So that's-- for example, if you have-- let's say you have multiple product variants and you have a parameter or something that specifies which variant. And you have, I don't know, different color shoes, for example, why not, like black, green, blue. And the parameter is color equals black,  

#### [0:29:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1740) |  color equals blue. Then you could say

this color parameter is one that you don't want to have crawled and the representative one is always black. It's like black shoes fit everywhere kind of thing. So that's how you could tell us this is the one representative URL that replaces all of these others. AUDIENCE: But in the URL parameters, you don't get to choose the parameter value. You only get to choose the--  

#### [0:29:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1770) |  so let me give you an exact

example. JOHN MUELLER: Maybe I'm misremembering that setting. But that's what I thought. OK, I'll have to click into that to double check though. AUDIENCE: Just to give you a quick example, let's say you're using UTM tracking parameters and you have that parameter there, the UTM campaign. And you choose representative URL. Does that mean that Google will try  

#### [0:30:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1800) |  to pick those URLs that contain UTM

campaign as the canonical version if you choose representative URL? JOHN MUELLER: I don't know. You're confusing me now. I would need to-- I'll double check afterwards. If we still have time afterwards, maybe we can-- we should double check together, sure. AUDIENCE: Sure, cool. JOHN MUELLER: OK. Does Google throttle or reduce link value to content that is significantly updated For example, you  

#### [0:30:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1830) |  may have very old content with lots

of links that's seriously out of date. If you rewrite the content, does Google kind of say, well, this isn't what people linked to, so we're not going to pass value to those links anymore? No, we don't really do that. The one thing where I see that sometimes happening is when it comes to things like expired domain. So if you just buy some expired domain and you put your own content up there, then from our point of view, that's a different site.  

#### [0:31:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1860) |  It's not-- like suddenly, the old expired

domain is passing everything onto your site. So that's the one case there. But with normal changes within a website, it's absolutely no problem. Sometimes content changes. Sometimes it changes significantly. That's perfectly normal. I used a Korean character on a URL of my posts, but when I share it on Facebook, the URL appears in this format of the escaped URL version.  

#### [0:31:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1890) |  The URL becomes so long. Does it

also affect my SEO or does it change anything, essentially? It doesn't change anything. You can use an escaped version of the URL. It's essentially treated as exactly the same URL from our side internally. If we see a link that goes to your website that uses an escape URL, we will kind of unescape that when it comes to indexing. Similarly, internal linking, you can use escaped URLs  

#### [0:32:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1920) |  or you can use direct Unicode characters

in the URL. Both of those are completely equivalent. It's not that there is a redirect in place there. It's essentially the exact same URL, just different ways of writing it. Can you tell me whether schema.org/course markup is supported outside of the USA? I don't really know, but I will check for you.  

#### [0:32:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1950) |  My understanding was it's supported everywhere, but

you're saying it's not so I'll double check. You earlier recommended not to block URLs with parameters since Google can't canonicalize the pages correctly and that the value from links to those pages gets lost. For example, we should use rel canonical instead of robots.txt or meta no index. My question is on an e-commerce website with many pages,  

#### [0:33:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=1980) |  do you also recommend no following links

to filters, which create URL parameters for crawl budget reasons? I would do that. I mean, that's something where using no follow probably makes sense. If you create a lot of fields or variations for URLs, then that could make sense. But you can also just link essentially normally with normal URL parameters, and you can also use the URL parameter settings  

#### [0:33:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2010) |  tool to help us with this. We

have a really, really long blog post on faceted navigation with-- I think it's like five good practices and five bad practices which covers all of this. So I would really double check that. The thing with robots.txt in particular-- I think I mentioned this is that we don't know what is behind that URL at all, so we can't canonicalize things. If there's a link there, we don't know what to do with it.  

#### [0:34:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2040) |  That's kind of the one thing there.

The other thing that I realized when I first read this question when I looked at it before is our crawling and indexing team-- they have never told me to go to a website and tell them to use robots.txt to block something like filters or pagination on an e-commerce website. It's always the opposite cases. So it's something where if there is an issue with regards to crawling and indexing content,  

#### [0:34:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2070) |  the crawling team is more likely to

tell me to go in and contact the website and tell them, hey, you have something incorrect with your robots.txt file. You need to unblock things so that we understand your site better. And they've never sent me out to kind of contact any e-commerce site and tell them to add robots.txt blocks because we get lost in the filters or we get lost in the pagination. So that's kind of as an anecdote there.  

#### [0:35:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2100) |  They've also never told us to go

off and tell people to use no follow for internal navigation, so that's another interesting part there in that for the most part, we should be able to deal with e-commerce sites and the normal navigations that they provide. For AMP search results, does Google gather the article's structure data from the AMP page itself or from the canonical page? Will the AMP search results work if only the canonical page  

#### [0:35:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2130) |  has the structure data? So this is

a confusing one that confuses me, at least-- apparently, also you-- in that we need to see the markup on both versions of the page. It's not just that we would say, well, the AMP version canonicalizes to the desktop version, so we'll just use that one. But rather, we would show the AMP version in the search results, so we need to make sure that the markup there  

#### [0:36:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2160) |  is also that what we would show

in the search results. So things like the article markup, that matters. Also things like metadata, like robots.txt, meta tags, they matter there too. If you have a no index on the AMP version and an index on the desktop version, then should we show the AMP version or should we not show the other version? It gets really confusing.  

#### [0:36:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2190) |  So ideally, make sure that the AMP

version has the same structure data and the same metadata as the primary version of the page. Or when I talk with the AMP team, they're always like, can't you encourage people just to use AMP? Like if they're already using AMP for their content and able to use it, sometimes it makes sense to just use AMP as a web framework and make the whole page AMP. Does a website's cache configuration have anything to do with the time it takes Google to index  

#### [0:37:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2220) |  it? No, not at all. So the

cache configuration usually applies to how a browser would be able to load that page with regards to being able to cache CSS files or things like that. And that doesn't affect us for indexing the web page at all. For rendering, we also pretty much ignore all of those cache parameters because they're-- because we do things so differently in rendering than a normal browser would do.  

#### [0:37:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2250) |  So we can cache things like CSS

files for a really long time and just reuse that and it works well for rendering, whereas in a browser, maybe you don't have that much storage to actually cache things that long. Machine learning has been a part of Google's search algorithm, and I can imagine it's getting smarter every day. Do you as an employee with access to the secret files know the exact reason why pages rank better than others?  

#### [0:38:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2280) |  Or is the algorithm now making decisions

and evolving in a way that makes it impossible for humans to understand? We get this question every now and then. And we're not allowed to provide an answer because the machines are telling us not to talk about this topic. So I really can't answer. No, just kidding. It's something where we use machine learning in lots of ways to help us understand things better.  

#### [0:38:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2310) |  But machine learning isn't just this one

black box that does everything for you where you feed the internet in on one side and the other side come out search results. It's a tool for us. It's essentially a way of testing things out a lot faster, trying things out, figuring out what the right solution there is. So, for example, we use machine learning for canonicalization. So what that kind of means is we have all of those factors  

#### [0:39:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2340) |  that we talked about before. And we

give them individual weights. That's kind of the traditional way to do it. And we say, well, rel canonical has this much weight and redirect has this much weight and internal linking has this much weight. And the traditional approach would be to say, well, we will just make up those weights, those numbers and see if it works out. And if we see that things don't work out, we will tweak those numbers a little bit. And with machine learning, what we can essentially do is say,  

#### [0:39:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2370) |  well, this is the outcome that we

want to have achieved. And machine learning algorithms should figure out these weights on their own. So it's not so much that machine learning does everything with canonicalization on its own, but rather it has this well-defined problem. It's working out what are these numbers that we should have there as weights, and kind of repeatedly trying to relearn that system and understanding on the web,  

#### [0:40:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2400) |  this is how people do it and

this is where things go wrong. And that's why we should choose these numbers. So when it comes to debugging that, we still have those numbers. We still have those weights there. It's just that they're determined by machine learning algorithms. And if we see that things go wrong, then we need to find a way, like how can we tell the machine learning algorithm that actually in this case, we should have taken into account, I don't know, phone numbers on a page more rather than just the pure content  

#### [0:40:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2430) |  to kind of separate like local versions,

for example. And that's something that we can do when we kind of train these algorithms. So with all of these machine learning things it's not that there's one black box and it just does everything and nobody knows why it does things. But rather, we try to apply it to specific problems where it makes sense to automate things a little bit in a way that saves us time and that helps to pull out patterns that maybe we wouldn't have recognized manually  

#### [0:41:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2460) |  if we looked at it. AUDIENCE: John,

I know it's been on the news like a couple of weeks ago that Google has developed a set of tools to be able to kind explain what's going on where-- in machine learning models. And you gave that example with weights to pages where they-- which canonical version should they pick?  

#### [0:41:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2490) |  So are you using those kind of

tools to understand what weights are actually being chosen and whether those are the correct ones to choose and adjust afterwards and things like that? JOHN MUELLER: I don't know specifically the setup that you're referring to, but we do try to understand as much as possible what is happening there. And that's something where the search quality team, they do have ways of debugging all of these things.  

#### [0:42:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2520) |  So on the one hand, you can

do that by separating out these problems a little bit more. And on the other hand, it's like you just-- with a complex system like Google Search, there are just always a lot of individual pieces that are moving around. So even without machine learning, it's not trivial, but it's something that we need to be able to debug. Because people come to us with weird ranking issues, like I get them from here every now and then.  

#### [0:42:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2550) |  You've sent me some really weird ones.

And it's something that we need to be able to figure out why is this happening and is this happening at a larger scale? Is it just happening to this one page or this one site? What can we do to improve it? So that's something where you always need kind of an understanding of what happened here, how did we get to this state, how can we improve it? AUDIENCE: Yeah, I think it's explainable AI.  

![](https://i.ytimg.com/vi/5QxYWMEZT3A/maxres3.jpg)



#### [0:43:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2580) |  I think that's how Google coined it.

JOHN MUELLER: OK. AUDIENCE: Yeah. JOHN MUELLER: I don't know if we use that exact thing. I mean, we-- there's so many different AI machine learning systems out there nowadays. I could imagine we use something like that for some aspects of search or some of our systems and other aspects use other things, so no. But in any case, like also that the meta question here--  

#### [0:43:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2610) |  does anyone really know how the algorithm

works? And that is something where we do have a lot of people in search quality that are able to debug pretty much any query and understand what is happening here, why are things ranking the way they are? That's something that, for example, Gary has spent a lot of time on as well. And he's been working on some of these search things too. So it's not limited to this elite set of priests  

#### [0:44:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2640) |  somewhere in Mountain View that know what

is happening, but rather engineers can learn it and it's something that we need to have at that level. It's not-- like it shouldn't be a big black box if we want to be able to improve it. OK, really long question on videos. So I-- so it goes into like video structure data, markup,  

#### [0:44:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2670) |  and kind of the questions are let's

say I host my video on YouTube. Would structure data and video sitemap help Google to choose my landing page to be ranked over my YouTube page? Not necessarily. So the structure data gives us more information about how you're embedding the video, but it doesn't necessarily mean that your page will be better suited than a YouTube landing page. However, it all depends on the query and the type of content you have on these pages.  

#### [0:45:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2700) |  So if you have really good content

that matches well what the user's intent is for query, then we'll try to show your page. And if otherwise the same content is available on the YouTube page and it's really visible and prominent there, and it's kind of hidden away on your page, then maybe the YouTube page is a better landing page for that specific query. It's not that we would always show one or the other. It's that we try to understand which of these pages is more relevant.  

#### [0:45:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2730) |  And then let's see. How does Google

make sure that the page-- including the video structure data or video site map-- belongs to them, that it's the same entity? We-- I believe we don't necessarily do that in the sense that we're trying to figure out what the most relevant page is, but we try not to make any algorithmic kind of evaluation on who the owner of the video is and is this person who's  

#### [0:46:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2760) |  embedding the video allowed to embed that

video? In practice, this is something that you can specify on YouTube where you can say, I want to allow embedding of the video or I don't want to allow embedding of the video. And if the video doesn't work on a page, then chances are it's not going to perform that well in search in the sense that if users don't see that video ever, they're not going to recommend that page as a video landing page anyway.  

#### [0:46:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2790) |  Finally, if the goal of my video

campaign is to drive more traffic to my website instead of brand awareness, some SEOs suggest you use self-hosting instead of YouTube. Do you agree with this point of view? You can do that if you want. So I think one of the big advantages of using a platform like YouTube or Vimeo or any of the other big video platforms is that they have infrastructure that make sure that your videos just work really well everywhere. They have kind of caches and content delivery  

#### [0:47:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2820) |  nodes pretty much worldwide to make sure

that it just works really quickly. It doesn't have to go through your one server. So that's something where I think there is a lot of value in using these kind of setups as CDNs for [INAUDIBLE] video content. So that's something where I wouldn't necessarily say you should avoid it or you should host it yourself. But rather if you want to host it yourself,  

#### [0:47:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2850) |  that's perfectly fine. That's totally up to

you. But just keep in mind that sometimes the technical requirements can be quite tricky. AUDIENCE: Hi, John. JOHN MUELLER: Hi. AUDIENCE: Can I add a question four to that? JOHN MUELLER: Sure. AUDIENCE: I've been doing quite a bit of video markup lately, and what I find is quite a few of the parameters that you want to do in the markup will not be visible on the page, things like duration  

#### [0:48:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2880) |  of the video, even maybe the description

because the video kind describes itself. So is there any issue if you're marking that up in metatext and things like that? Does Google understand it's kind of in the video? JOHN MUELLER: I mean, what we wouldn't do is extract kind of the content of the video to try to figure out how we should rank it. So things like transcribing the video and understanding what the text is inside and then trying  

#### [0:48:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2910) |  to rank that video based on that--

I don't think we would do that. From YouTube, that's something where I believe they show the transcription as a part of a page. So theoretically, that could be on the page there. But when it comes to descriptions and things like that, I would try to put those on the page somewhere or in the video markup itself. That's also one of the things where--  

#### [0:49:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2940) |  like a lot of these things come

up-- come to me when it comes to mobile-first indexing. And that the mobile first indexing team will come and say, well, this site is not performing as well on mobile or when we would switch it to mobile-first indexing because the videos are not able to be picked up properly. And often, that comes down to video structure data. It comes down to that the positioning of the video  

#### [0:49:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=2970) |  on the page. Is it a prominent

part of the page or not? Where on mobile, maybe you have a completely different layout of the page. And suddenly the video instead of being in the middle and center and large is like the small aspect in the corner somewhere. Then that's something where we would not be able to send as much video traffic to a site like that because we don't think it's really-- it's not really the same kind of video landing page as the desktop version would be.  

#### [0:50:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=3000) |  So all of these things are things

that the mobile-first indexing team kind of brings up and we talk about with regards to videos. And that does include the structure data, does include things like the description in the structure data. That kind of does play a little bit of a role there. It might be that we don't show it directly in the search results, but it's still useful for us for ranking purposes. AUDIENCE: All right, cheers.  

#### [0:50:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=3030) |  JOHN MUELLER: All right, I just noticed

we're kind of at time, so if there's anything left from your site that you want to ask right away, feel free and otherwise I'll pause the recording in a few minutes and stay online for a little bit longer if you just want to chat about other things as well. AUDIENCE: Hi John, I've got a question if that's OK? JOHN MUELLER: All right. AUDIENCE: I have a client and the woman who appears to have some sort of penalty.  

#### [0:51:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=3060) |  We've acquired a number of high quality

[INAUDIBLE] rulings for the last couple of years but for the [INAUDIBLE] movement. And we're getting a new website built and we have the opportunity to start fresh on a a new domain. And I'm just wondering based on your web content comment last week about of a building on shaky foundations if you would recommend not performing a 301 when we build  

#### [0:51:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=3090) |  the new site in order to not

[? pass and enforce ?] any issues. JOHN MUELLER: So you'd be starting on a new domain with completely new content or-- AUDIENCE: Yeah. JOHN MUELLER: Yeah? AUDIENCE: Yeah. But we do have the opportunity and we could 301 and, I guess, take the risk. But it's very hard to understand what's going on. It's just with very little self-movement over the last two years. I've put a significant amount of work into trying to move things.  

#### [0:52:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=3120) |  We did a lot of technical work.

We tried [INAUDIBLE] for old shitty links that other agencies had built in the past that doesn't seem to be lifting. So I just want to give the client the best-- the best advice going forward. JOHN MUELLER: Yeah. It's really hard to say offhand. I mean, the-- on the one hand, starting with a new domain with a new website is a chance to start fresh. On the other hand, that also means you do start fresh. So all of the kind of recommendations,  

#### [0:52:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=3150) |  the links, everything that you've built up

over the years would essentially be gone. And you'd need to kind of take your knowledge of that niche and kind of like go out and present yourself as a fresh website, essentially. So it has pros and cons. It feels like a lot of work compared to trying to improve something old. But sometimes, like especially if there is really weird stuff that has been happening  

#### [0:53:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=3180) |  with your old website, sometimes it makes

sense to start fresh and try it like that. AUDIENCE: Just having a look at the links, and some of the links just appeared to be the guest poster reach type links that they'd done. But there was a significant use of [? offer ?] boxes. And that, to me, seems like the only issue that could be from a link perspective. And I'm just wondering if that could be a factor. It is a bit of a risk starting from scratch.  

#### [0:53:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=3210) |  You've got locations up and down the

country, So? they've got location pages and several Google map businesses and stuff, so it would be a lot of work. So [INAUDIBLE] just-- JOHN MUELLER: I think offhand, I try to avoid starting from scratch, especially if there are lots of local listings as well  

#### [0:54:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=3240) |  and all of that, it seems like

that's a lot of value to throw away for something like this. So that's kind of my gut feeling there. It's also something where if you don't see something like a manual action in search console, then probably it's not that tricky with regards to the links there. But if you want to stick around after the recording stops, I can take a quick look to see if I see anything obvious.  

#### [0:54:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=3270) |  I mean, it's kind of hard as

a two minute check of a site. But maybe there's something obvious. And it sounds like you're in that almost desperate situation with like, ah, throw everything away and start over or continue working? AUDIENCE: The last part of the question is just if we did decide to do-- to new domain it, would a 301 possibly just pass along the problem?  

#### [0:55:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=3300) |  So I guess the other part of

the question is should we 301 or not and just stick with it with the current domain? JOHN MUELLER: Yeah, so if you 301 from one domain to another, then you're forwarding all of those signals. So links were being forwarded, all of that would essentially be forwarded. And we'd essentially see the new domain as a variation of the old one. So I don't think that would be that useful, which  

#### [0:55:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=3330) |  also kind of makes it even harder,

I guess, in a case like yours. But I'm happy to take a quick look afterwards if you want to drop the link in the chat. Then I can take a quick look there. AUDIENCE: That's great, John. Thank you. JOHN MUELLER: Sure. AUDIENCE: HI, John. JOHN MUELLER: Hi. AUDIENCE: I have a question related to the [INAUDIBLE].. Like [INAUDIBLE] so many local listings which have not [INAUDIBLE] and still they are ranking.  

#### [0:56:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=3360) |  So determining a specific parameter which you

need to optimize in our sites, are they local-backed, basically? JOHN MUELLER: For Google Local, I don't know how Google Local does a ranking. So that's really hard. But in general, what I sometimes see not specific with regards to the local business listings but with regards to sites in general is that there are lots of sites that do things wrong  

#### [0:56:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=3390) |  or that do things in ways that

is not optimal. And they can still appear well and search because they have lots of other signals that are telling us this is actually pretty useful site. So that's something that might be happening there where if you look at it and you say, well, they're missing all of these obvious optimizations but they're still ranking, then it might be that maybe they're doing other things really well, and that's kind of even things out. So it's not that you have to do everything.  

#### [0:57:00](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=3420) |  You have to do everything perfect. So

we try to pick the factors that play a role and to rank them accordingly. AUDIENCE: Thank you. JOHN MUELLER: All right, let me stop the recording here. And if you want, you're welcome to hang around for a little bit longer and we can chat about sites or anything else. And otherwise, I want to thank you all for joining in. Thanks for submitting so many questions.  

#### [0:57:30](https://www.youtube.com/watch?v=5QxYWMEZT3A&t=3450) |  I hope you have a great weekend.

And looking forward to seeing you all again in one of the future Hangouts. Bye, everyone. AUDIENCE: Bye, John. Thank you. AUDIENCE: See you.  