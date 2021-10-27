[![English Google Webmaster Central office-hours from May 15, 2020](https://i.ytimg.com/vi/W9xWTYPqgaU/maxresdefault.jpg)](https://www.youtube.com/watch?v=W9xWTYPqgaU)

## English Google Webmaster Central office-hours from May 15, 2020

This is a recording of the Google Webmaster Central office-hours hangout from May 15, 2020. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Watch out for new sessions, and add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



Feel free to join us - we welcome webmasters of all levels!



#### [0:00:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=0) |  JOHN MUELLER: All right. Welcome, everyone, to

today's Webmaster Central office hours hangout. My name is John Mueller. I'm a Webmaster trends analyst at Google in Switzerland. And part of what we do are this office hour hangouts, where folks can join in and ask their questions around the website and web search, and we could try to find answers for them. A bunch of stuff was submitted on YouTube already, lots of questions, looks like. But if any of you want to get started  

#### [0:00:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=30) |  with the first question from here, feel

free to jump on in. If not-- AUDIENCE: Hi, John. JOHN MUELLER: Yeah, go for it. AUDIENCE: Yeah. So one question was very, very much like-- Sometimes it happens, but it not guideline. While we were dealing with our tech team, by mistake some redirection were made 404 were  

#### [0:01:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=60) |  some [INAUDIBLE] pages which we wanted to

remove. Right. So they were made 404. Sorry, let me make it clear. We wanted to redirect them. We were doing site migration. So we were planning to redirect those pages to new pages, but because of technical limitations, they just made them 404. And while the pages were 404, they were just working on resolving the issue,  

#### [0:01:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=90) |  and I am sure that maybe Google

would have just called them and found them 404. It happens sometimes. In this case, when Google has culled them and just dropped them from indexing as 404, then we are setting up redirect to page moves to a new page. What should we think? Are the pages' content completely moved? It was 301 genuine case, but the page was 404 for some time. And then setting up redirect, how Google just  

#### [0:02:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=120) |  understands this kind of thing? JOHN MUELLER:

Yeah. So I think, first of all, you're not alone. I think pretty much everyone who has moved a few websites has run into this, where you wanted to set up redirects, and the team just essentially turns off the old website instead of setting up redirect. That happens every now and then. And from our point of view, we will recall those URLs,  

#### [0:02:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=150) |  and we will see the redirect, and

then we will process the redirect, and that should be more or less OK. It's sometimes a question of how long the pages were 404 before you set up the redirect again, and that's more a matter of how long it takes for everything to be picked up again. But in general, that happens, and our systems have to live with it as well and figure out  

#### [0:03:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=180) |  how to catch that and clean it

up again. AUDIENCE: So in this case, a new page ranking, the ranking may fluctuate. What should we assume? JOHN MUELLER: I think what will happen is-- so usually, what happens is those pages drop out of the index because of the 404. And then when we start seeing the redirect again, we can pick them up and we can process them normally again. So it's more a matter of, things will be fluctuating  

#### [0:03:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=210) |  with a site move in general. And

if you do it in a state like this, then it fluctuates a lot more, but it should catch up, and it should settle down normally again. AUDIENCE: So it means we can say that with time, the ranking will be for new page, there is nothing to worry? JOHN MUELLER: No. I mean, it really depends on how long it was like that. If you're talking about a few days,  

#### [0:04:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=240) |  I don't see much of a problem.

If you're talking about a few months, then obviously that's a significant amount of time where our systems may have thought, well, this page is probably gone forever. But it sounds like a couple of days, then you notice the technical problem, you fix it, and then it's OK now. So I don't see a big problem with that. AUDIENCE: OK, cool. Thanks. JOHN MUELLER: Sure. All right.  

#### [0:04:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=270) |  Any other questions before we jump into

the submitted ones? No? OK, cool. So feel free to jump in between if something comes up, or we'll probably have time towards the end again to do more open questions as well. The first one is kind of an international sites question. Googlebot usually comes to our website from the US. At the moment, we don't fully block all of the US states.  

#### [0:05:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=300) |  We use alternative methods. But let's say

we have to block content for the US IPs. Then, if Googlebot comes from a blocked US state, we have only two, in my opinion, bad options. The first one-- display a substituting law-compliant content instead of displaying the full content and risk that this substituting content will be indexed for all users around the globe, or be identified Googlebot by agent header and display the full content.  

#### [0:05:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=330) |  However, we risk cloaking, as users with

the same IP would get different content based on only the user. What else could we do? So you're right. This is a tricky situation. For the most part, we do crawl from the US. So with regards to our webmaster guidelines, our guideline is pretty clear-- that users from the same location as the Googlebot should have the same experience as Googlebot. So in other words, when Google is crawling from the US,  

#### [0:06:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=360) |  if you need to block all users

from the US, then you would also need to block Googlebot. And in practice, what this means is that your website or this content will not be indexable, because you're blocking Google from actually accessing it. And the two options that you mentioned there are essentially the only ones that we see from our side essentially displaying content that you're allowed to display in the US.  

#### [0:06:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=390) |  I think that's probably the cleanest approach.

That's the approach that we usually recommend, because that makes sure that you have one version of the content that's available to users in that location. They can go there. If they want to sign up and then the sign up is blocked because they're from the wrong location, then that's something that's more of a usability issue on your side. From our point of view, that's OK. From an indexing point of view, you're correct that we would only be indexing  

#### [0:07:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=420) |  this publicly-available content. The second option, the

one that you mentioned there, is essentially cloaking to Googlebot, which is not what we would recommend doing, because that would be cloaking. That would be something where the web spam team would be pretty unhappy about seeing. So essentially, if you're in the situation where you need to block the US and everyone else can access the page, then it's always going to be very hard.  

#### [0:07:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=450) |  It's easier the other way around, or

with other countries. So if Googlebot is crawling from the US and you need to block all users from Switzerland, because these Swiss people, I don't know, you don't like them-- if you needed to do that then, from Google's point of view, that would be totally a non-issue. Because we would crawl from the US, we would see the content that users in the US would be able to see, we'd be able to index everything,  

#### [0:08:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=480) |  and just Swiss users, when they come

to your site, would be blocked. So that's kind of the easier situation is, if it's not from a location where Googlebot is crawling, but otherwise, that's kind of a tough situation where you have to deal with that. AUDIENCE: Hi, John. Can I have a follow-up? JOHN MUELLER: Sure. AUDIENCE: Yeah. It doesn't concern the whole UI.  

#### [0:08:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=510) |  It concerns only a few states in

the US. So is there any option we can do like state-specific? Or, since it's in some states, we need to block users from all US? JOHN MUELLER: We don't specify the exact level when it comes to kind of showing Google about the same content as users from the same region would be.  

#### [0:09:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=540) |  So from that point of view, if

you can recognize where Googlebot's IP addresses are coming from, which states, then you're welcome to kind of do it on that level. Most of the situations that I've run across tend to be more on a country level, where you need to block the whole country for maybe legal reasons. And that's where, essentially, the US is the whole country, and all of the crawling comes from the US, or most of the crawling comes from the US. So you would be blocking the whole country.  

#### [0:09:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=570) |  If there is differences on a per

state level and you can recognize where the IP addresses are coming from to some degree of certainty, then that's fine too. AUDIENCE: OK. So the solution would be to try and track IP addresses of Googlebots, and if they are coming from the same state we are not allowed to show the content, then block the content for those states, right? JOHN MUELLER: Yeah.  

#### [0:10:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=600) |  I suspect it will be kind of

tricky, because the mapping of the IP addresses to the specific location is kind of an art, not really a science. AUDIENCE: I can imagine. JOHN MUELLER: But I would give it a try. If that's an option that you have that you can do it on a state level, then maybe that's a solution. AUDIENCE: OK, thank you. JOHN MUELLER: Sure. AUDIENCE: Hey, good morning, John.  

#### [0:10:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=630) |  How's it going? JOHN MUELLER: Hi. AUDIENCE:

I want to ask, can I backdate my posts [INAUDIBLE] to backdate. Than I realized such cosole is showing excluded your pages. I don't know why, because I have 5.4k pages-- 5.4K posts, but it's scrolling just 500. And others, 5K is showing excluded, apparently not  

#### [0:11:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=660) |  indexed, from one month. Why is that?

JOHN MUELLER: That can be a lot of reasons. It is really hard to say. It sounds like from a technical point of view, we can probably access your page as well. So from that point of view, it's probably not a technical issue, and more a matter of maybe the quality in general, where our systems, they tend to try  

#### [0:11:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=690) |  to focus on kind of higher-quality content.

And if our system recognizes that, in general on this website, maybe the content is kind of questionable, then generally they wouldn't index all content. Even, I think, outside of the quality questions, it's completely normal that we don't index all content on a website. AUDIENCE: It can be because I backdated my older posts, or it's normal because I backdated my posts?  

#### [0:12:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=720) |  JOHN MUELLER: I don't think backdating would

be necessarily a sign of low-quality content, but I don't know. AUDIENCE: OK. OK. Or, can I get like no-folloow links from Reddit? It's good for SEO because I'm getting tons of links from Reddit, and someone's saying it's not good for your SEO. If you will keep doing this, it's going to be bad for your SEO.  

#### [0:12:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=750) |  JOHN MUELLER: I don't think it has

any effect at all. If these are no-follow links and they're coming to your site, then we don't pass any signals there essentially. So that has no effect. AUDIENCE: OK. OK. Thank you. JOHN MUELLER: Sure. AUDIENCE: John, really a small follow-up on this. JOHN MUELLER: OK. AUDIENCE: So I just wanted to confirm with you, last updated in the page is really considered by Googlebot? I don't think so.  

#### [0:13:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=780) |  I think Google always gives the recommendation

that a similar site last modified is recognized. But what if the person does not have XML site map and just updates on the post that last updated two hours back or three hours back? Is it really understood by Google that the content is changed? Because this is mentioned on the page. JOHN MUELLER: Sometimes, yeah. Yeah. So we use the date in the site map primarily to determine when we need to crawl the page.  

![](https://i.ytimg.com/vi/W9xWTYPqgaU/maxres1.jpg)



#### [0:13:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=810) |  But after we've crawled the page, we

look at the content primarily. We see what the content says. If there's maybe a date on the content, if the date is marked up with structured data, then all of these things are or elements that we would look at and we would try to pick up on and use that appropriately for search. AUDIENCE: OK.  

#### [0:14:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=840) |  JOHN MUELLER: All right. Any pitfalls for

using loading equals lazy for images inside an article? No, not from my point of view. With regards to SEO, this is a really simple way to add lazy loading to your images within a page in the sense that these are normal image tags that you keep in your HTML. So when any search engine comes along, they see the image tags, and they can act on those image tags and index  

#### [0:14:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=870) |  the images directly like that. However, for

the browsers that support it, which I think are Chrome, and maybe Firefox and Safari-- I'm not 100% sure-- for those browsers that recognize this as a form of lazy loading, they would load those images when that part of the page comes into the viewport. So it makes it a lot faster to load those pages. So from that point of view, I would strongly recommend using this kind of lazy loading,  

#### [0:15:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=900) |  or maybe another kind of lazy loading

if you have other preferences, specifically for images, because it can significantly increase the speed of your pages being loaded. In an ideal situation, we use hreflang to make sure people from other countries do not land on the EN US page, but we don't have an alternative page for, say, English Canada, since the product doesn't sell in Canada. Should we just let the uses land on the English US page,  

#### [0:15:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=930) |  or how should we handle this? So

essentially, that's up to you. So there are two general trains of thought here. On the one hand, you can have a page that says "this product is not available here," and you could just use hreflang to mark that one as that version. On the other hand, you can just say, well, this is the US page, and when users try to put it in their card, for example, if it's a product, then you can say,  

#### [0:16:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=960) |  well, this product is unfortunately not being

sold in your country. So those are essentially the approaches there. In general, when it comes to hreflang, I strongly recommend having fewer pages rather than more pages. So instead of just making landing pages for every country and language version, if you can simplify that to just the languages that you actually need, then that makes it a lot easier. Then that might result in a situation here where you just have one English landing page.  

#### [0:16:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=990) |  And depending on the country, the location

of the user, then you can respond to that individually in a part of the page where you say, well, actually we don't sell this to you, but here's all of the information. That also makes it a little bit easier for users who are either recognized as being in the wrong country or who might be traveling. So they can still get the information that they need and kind of make a call based on that.  

#### [0:17:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1020) |  We had a page that listed all

of the products on our site. We retired that page about two years ago, and it currently returns 404. It contained a lot of incorrect or missing schema.org micro data for products. Our problem has two parts. We have a lot of search console errors that are coming from crawls of this page that happened around two to four years ago. We can't issue requests for re-validation. The UI currently shows validation passed  

#### [0:17:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1050) |  with no button to validate fix. This

is also compounded by the fact that our site used to route users around the site with a website.com question mark main page equals product type of URL. We've since changed that to a standard URL structure, and in 99% percent of the cases Google search shows those results. But since the old-style links redirect to working pages, search console seems to treat them as discrete pages.  

#### [0:18:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1080) |  This has also been treating Google Ads

URL parameters as discrete pages on top of that. So the list of errors can get into the thousands. I looked into the removals tool, but those require that your URL returns 404 for part of the URL before URL parameters, which is our website. Now, should we be worried that these errors are affecting our ability to get rich content results and Google search for products on this retired page  

#### [0:18:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1110) |  we are getting errors for? Is it

possible that it would cause other penalties on our site? Long question. OK. So first of all, if you remove that page and you don't want that page to be indexed in search, then it's correct to return 404 for those URLs. And it's completely normal to see errors in Search Console for that, because essentially, you removed this page, we tried to look at it,  

#### [0:19:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1140) |  and we're telling you, well, we saw

an error when we tried to look at it. And from a technical point of view, that's what you want Google to see. You want Google to see that this page no longer exists so that it can be dropped out of the index. So from that point of view, it's totally OK to have 404 errors in Search Console. That's essentially a sign that you're doing things right, that you're using the proper response codes and everything is set up correctly.  

#### [0:19:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1170) |  So from that point of view, I

don't think you need to do anything specific here. If these pages no longer exist, keeping them 404 is perfectly fine. You don't need to do anything with validation. You don't need to use the content removal tools or anything like that. Essentially, they drop out of the index. We start crawling them less frequently, but we will still check them over time. And there is absolutely no penalty,  

#### [0:20:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1200) |  no manual action associated with that, no

demotion. It's not a sign that your website is of lower quality if you have 404 pages. Can we use jump links for an internal linking page? Will Google crawl these links? So jump links-- I'm not sure what the technical term is for those, but essentially, you have the kind of hash in the URL, and it just jumps to particular part of the page.  

#### [0:20:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1230) |  Yes, you can absolutely use those. We

don't crawl those links, because we would see the same content as the normal page. It's just jumping to a different location on that page. But we do recognize them, and sometimes we show them in search as well. If we feel that the user is searching for something that's on a particular part of your page and you have a link kind of pointing to that part of the page, then maybe it makes sense to kind of help the user go to that part of the page  

#### [0:21:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1260) |  immediately. So that's something-- I would definitely

use those. Over the past few weeks, I've noticed steady increasing number of backlinks in search console from two domains to my website. From these two domains, every single page on my website is linked about two to three times, accumulating more than 500 backlinks over the past four to eight weeks. Looking at the originating URLs in Search Console, I saw that these originating URLs from two domains  

#### [0:21:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1290) |  are empty pages. The home page on

these two domains is simply an empty page. My discovery of this issue correlates with a 50% drop in traffic. These backlinks don't show up in other SEO tools on the Search Console. As these originating URLs are empty pages, do you have any idea why they would show up in Search Console as referring pages? And is this a scenario where the disavow tool makes sense,  

#### [0:22:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1320) |  or does Google detect them as unnatural

and will ignore them as a ranking signal? It's really hard to say what you're seeing here. It's certainly possible that there are pages out there that show an empty page to users, and then they show a full page to Googlebot. From a practical point of view, there's essentially no real reason why to do that. So it seems more like a technical mistake  

#### [0:22:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1350) |  rather than someone trying to maliciously do

something with your website. So from that point of view, I would just ignore those pages. From my site, if you're actually looking at those pages, maybe if you look at them with the mobile-friendly test, you can kind of see what Google IP addresses would see. If you're not seeing any content there, then I wouldn't worry about that. I don't think this is something that you need to disavow. It probably looks weird in the links report,  

#### [0:23:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1380) |  but I really wouldn't worry about this.

With regards to the drop in traffic that you're seeing, from my point of view, that would probably be unrelated to these links. There's no real, I don't know, a situation where I could imagine that essentially empty pages would be causing an issue with regards to links.  

#### [0:23:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1410) |  So I would just ignore that. If

you decide to put them into a disavow file anyway, which you can certainly do if you wanted to do that, just keep in mind that this would not affect how we show the data in Search Console. So the links report would continue to show those. I don't think there is any reason to use a disavow file in this particular case. So I would just leave them be.  

#### [0:24:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1440) |  My coverage report shows a valid page

has been decreasing since January. I don't know what happened. Crawled, currently not indexed and discovered, currently not indexed is slowly rising. Most pages can be indexed when checked in the URL inspection tool, but they're all listed as excluded. I checked the robots.txt and letter tag. Everything appears normal. Can you give me some suggestions about the situation? Is this an impact of algorithm update? Yeah, I don't know. It's really hard to say.  

#### [0:24:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1470) |  In general, we tend not to index

all pages on our website. So from that point of view, that can be completely normal. As I mentioned before, one of the more common situations where if a page is technically indexable but we just don't want to index it, a common situation is really that our algorithms are just not sure about the overall quality of the website. And in cases like that, we might crawl the URL,  

#### [0:25:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1500) |  we might look at the content and

say, I don't know. Or, we might know about the URL, which would be like it's discovered, but we haven't indexed it, which is kind of a sign of, well, we know about this URL on your website, but we're not really 100% convinced about your website. So maybe it's not yet worth our effort to go off and try to index the content of the URL. So in that regard, what I try to recommend  

#### [0:25:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1530) |  and what I try to do here

is take a step back and think about your website overall, and think about ways that you can make sure to significantly increase the quality of your website overall. That might be by working on your content. It might be by working on kind of everything around your content. Because when we look at a website, we don't just look at the words in the primary content.  

#### [0:26:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1560) |  We essentially try to look at everything

similar to how a user might look at everything on a website. So that's kind of the direction I would go there. I know this is never an easy situation, because obviously if you've been working on your website for such a long time, then it's your baby and you don't want to accept that maybe there are things that you could be doing differently. But sometimes it is really worth taking a hard look at everything and thinking about ways  

#### [0:26:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1590) |  that you can really significantly ramp things

up. One approach that some people take is to kind of prune back pages that they find were lower quality, or combine those pages into other pages, and make the existing pages higher quality. That's certainly something that you can do. It's not the case that you need to delete pages on your website, because there is like a limited number of pages that can be indexed, but it's really just like the pages that we find and the pages that we index, we want  

#### [0:27:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1620) |  to make sure that they're of high

quality so that it makes sense for us to show them to users. AUDIENCE: Sorry, John. [INAUDIBLE] JOHN MUELLER: Yeah. AUDIENCE: I have a question. We have a client. They are a solar panel company. They sell solar panels [INAUDIBLE] better. So their rank for the LG solar panel Sydney or solar panel keyword. Now, the page rank for these keywords, that is actually not brand page.  

![](https://i.ytimg.com/vi/W9xWTYPqgaU/maxres2.jpg)



#### [0:27:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1650) |  That is one of the LG's solar

product directory. So what we did, we actually replaced the content on that page with the new content, and we added all of our product names on that page so it would probably make the page LG solar panel brand page. And then the content we had previously, we moved it to another page. But when we did this, we saw the ranking of that page drop, and the new page we created with the old content, that  

#### [0:28:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1680) |  actually ranked for the LG solar panel

keyword I did. So is there something wrong? Is it because of the new algorithm update, or is this because we moved up, changed the content? JOHN MUELLER: I wouldn't see this as something that is specific to an algorithm change. It sounds more like you you've made some changes on your website, and now things are ranking slightly differently. So I would see that more as an effect of those changes  

#### [0:28:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1710) |  that you made within the website. And

if this is something that you made kind of changes that you made fairly recently, then sometimes it just takes a while for things to settle down, especially if you're moving content between different pages, maybe if you're redirecting pages, or folding pages together, combining things slightly differently. That's all something that sometimes takes a bit of time to settle down. Where in the beginning, it'll be that our algorithms are not  

#### [0:29:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1740) |  quite sure what to do, like how

these pages are relevant between each other. And over time, when we see how things fall into place within your website, then we can rank those a lot better. AUDIENCE: One more question, John. This is about image artifact. So on our client website, we have some infographics. It is most about efficiency of solar LG panels.  

#### [0:29:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1770) |  So this is just a graph, image

of the graph, and shows the efficiency dropped to 83% within 25 years. So this is what I put in my alt [INAUDIBLE] and caption of the image. So it looked like a little bit bigger description or bigger [INAUDIBLE]. Is it OK? JOHN MUELLER: That sounds perfectly OK, yeah. The alt attribute should be something that describes the image and should be describing, essentially, the image  

#### [0:30:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1800) |  in the context of your page. So

it's not just that you have to say, this is on the image, but rather, this is on the image, and this is the reason why it's included here. It's like a graph showing the efficiency of whatever your products are there, and that's essentially fine. With regards to search, the thing to keep in mind there as well is that in image search,  

#### [0:30:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1830) |  people might search slightly differently. So if

you're seeing that you're creating content that you think would work well in image search, then it probably makes sense to think about what kind of keywords people would use to try to find that content. And it's not something that you need to stuff those keywords into the alt text, but make sure that you have them on the page somewhere at least so that when someone goes to Google Images and searches for those keywords,  

#### [0:31:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1860) |  then we can recognize that your page

is a good landing page for that and this image is a proper image that fits to what they were asking for. AUDIENCE: Thank you, John. JOHN MUELLER: Sure. Let me just-- AUDIENCE: I have one more question. I have a platform. We are creating [INAUDIBLE]. If someone will use copyright image, then can we like-- I want to create a bot to send auto-reply--  

#### [0:31:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1890) |  it's a copyright image. You can't publish

this content. I don't want to hire someone to do all of these things. Is Google supporting any kind of this application or API, because I'm using Node.js or [INAUDIBLE].. I want to make something like this, which will like-- I will send out request, and the reply comes back from Google or any other service, which will tell it's the copyright image or it's not.  

#### [0:32:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1920) |  Then, on the basis of that, I

will make a decision what should I do. JOHN MUELLER: I don't think we have any kind of service like that from Google's side. I suspect there are other services that do something like this, but I don't know of any offhand. AUDIENCE: Which one is doing like this kind of work? JOHN MUELLER: I don't know. I don't know. AUDIENCE: OK. I will find. Thank you.  

#### [0:32:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1950) |  JOHN MUELLER: Let me grab some more

questions that were submitted, and then we'll have some more time for all of the live questions as well. I have a lot of 301 and 404 pages on my site. What do I need to do with them? That's perfectly fine. You don't need to do anything. You don't need to block them in any particular way. 404s are perfectly fine. Redirects are also perfectly fine. I'm working for a travel portal. I'd like to understand due to COVID-19, travel has taken a dip. Will there be an organic ranking drop as well?  

#### [0:33:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=1980) |  I don't think that would be related.

I mean, obviously within the whole ecosystem, things are all going in all kinds of weird directions. So it's really hard to say what will be happening. But it's not the case that we would say, suddenly travel portals should be ranked lower just because coronavirus happens. It might be more the case that things are just generally different with coronavirus. And maybe people aren't searching as much  

#### [0:33:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2010) |  for travel sites at the moment, but

maybe they'll search even more when things pick up again. So that's really hard to say, but there is no kind of coronavirus-related demotion in search for travel sites. We recently transferred our website from example account to multilingual one. So for most language extensions, we have an ordinary setup, like example an FR and LES, but for Swedish we kept the original domain like random.se.  

#### [0:34:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2040) |  The domain is within the same directory

as our primary. Let's see. I was totally against this setup, because I don't believe Google will see this domain extension as our main Swedish extension and will treat it as a separate domain. So in general, this is perfectly fine. With regard to international websites, sometimes you can have brand.countrycode,  

#### [0:34:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2070) |  top-level domain. Sometimes you have different brand

names depending on the country. Sometimes you have one kind of general website, and then some individual country code versions. That's perfectly fine. The connection with hreflang helps us to figure out which one of these to show. But essentially these are separate websites, so we will treat them as separate websites. So from that point of view, you don't need to match the part before the top-level domain.  

#### [0:35:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2100) |  The other problem is I try to

block the domain in robots.txt while it has been translated, but some pages are still showing up in search. I can't block the entire site, as it shares the same directory as the primary. So that seems like more of a technical issue on your side than something that we can really help with. If you're using a server where you have the same robots.txt file that are shared across multiple websites,  

#### [0:35:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2130) |  then that's something where you need to

find a way to kind of adjust your robots.txt files so that it works well for the content that you have there. And if you want to have a different robots.txt file for different domains, then maybe that's something that you can fix on the server side. Most of the time, there are tricks to do this, even if you surf the website from the same directory within the server, where you can kind of map the host name that  

#### [0:36:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2160) |  was requested and then serve different URLs

based on that. There are various I guess technical workarounds that you could do there. So I would work together with your tech team to find a solution there. Would you say it's best to include image URLs for indexing or to exclude them, especially in a recipe website, where there might be four to five images for a post that is about one specific recipe? I think it is always good to have images on a website,  

#### [0:36:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2190) |  and particularly on a recipe website, where

people will probably use Google images to try to find your content every now and then. So I'd strongly recommend keeping those indexable. And also, on a recipe website you can use the recipe structure data. The recipe structure data highlights your pages in a particularly nice way if we can recognize that they're recipes in the search results, including an image or a thumbnail from your recipe.  

#### [0:37:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2220) |  So that's something we can only do

if we can actually index that image. So from that point of view, I would strongly recommend making those images indexable. Obviously you don't need to make every image indexable. For example, if you have more decorative images on the website, like fancy corners of buttons or fancy parts of the UI or something like that, then maybe that's something that you don't need to make indexable. But if these are really high-quality images that  

#### [0:37:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2250) |  are something that users might want to

search for in Google Images, then I would totally make those indexable. Let's see. Some longer questions. Let me jump over those. Can URLs in a site map contain non-ASCII characters? Yes, of course. That's perfectly possible. With regards to site map XML files, in the site map spec, there is I think information on the encoding  

#### [0:38:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2280) |  that you need to use for the

URLs. So I would just watch out for using the right encoding, but you can certainly use non-ASCII characters in site map URLs. I have a motivational website. My hreflang and cannonicals are OK, but in reports there is traffic from other countries that had their own segment landings. Why does this happen? So hreflang is not something that is absolutely exact  

#### [0:38:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2310) |  and that will block all users from

going to the wrong version of the site. So from that point of view, I always recommend having some kind of a backup mechanism on your site when you can recognize that a user is coming from a different location. My usual recommendation is to have some kind of a banner that you can show to users like that, something saying like, it looks like you're from this country, and we have special pages for our users in this country. So maybe this is something that you would like to see.  

#### [0:39:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2340) |  By using a banner like that, there

are two things that you can do here. On the one hand, users can still access the other version, which sometimes helps, because users sometimes travel, or at least they used to travel. And sometimes it's possible that you recognize that they're in a different location than they actually are. So the kind of location lookup is not perfectly exact all the time. And on the other hand, when Google goes to those pages  

#### [0:39:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2370) |  and tries to index those pages, then

we don't automatically get redirected somewhere else. So in that regard, if Google were to send users to the wrong country version of your pages, then that banner would essentially guide them to the right version again. So kind of taking a step back and going back to your question, sometimes it is completely normal  

#### [0:40:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2400) |  that you would see user traffic from

other countries to hreflang versions that you have marked up, and that's just something where it's kind of due to the general-- I don't know, the general difficulty in understanding exactly what should happen with those kind of users. So I would just accept that this can happen and work with a backup situation like a banner.  

#### [0:40:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2430) |  I have a multiple-location website. The content

of the pages is similar. So Google dropped the .com/fr page and said that the domain.com/ca page is canonical for us. What we need is to have the French page and Canadian page. We updated the location on the page, created schema markup to show Google each page is connected to a country using hreflang, local businesses, localized titles, and re-indexed the page in Search Console.  

![](https://i.ytimg.com/vi/W9xWTYPqgaU/maxres3.jpg)



#### [0:41:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2460) |  Still, Google doesn't want to take this

into account even after crawling it. Domain.com/ca is still considered by Google to be the canonical of the page. Yes, this can sometimes happen, in particular if the content is in the same language, but for different countries. And essentially what happens here is our systems look at these two pages and they recognize that the content is either identical,  

#### [0:41:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2490) |  or almost identical, and then our systems

try to make things easier on by picking one of these pages and using them as a canonical. The canonical is the one that we will crawl a little bit more often. The canonical is the one that we use as a basis for indexing. With hreflang, if you use that on these pages in addition, then what will happen is we will still have that one canonical, but we will swap out the URLs when a user is searching.  

#### [0:42:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2520) |  So in a case like this, if

we were able to recognize the hreflang on these pages and we had processed that, then we would still index the Canadian version of this page. And if users in France were to search, we would show the domain/com/fr version in the search results, but it would still be based on the indexing of the Canadian version. So what you can do if you need to make sure  

#### [0:42:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2550) |  that these pages are absolutely indexed individually

is to make sure that the content of these pages is significantly different. So don't just tweak things like put a local phone number on there, or add structure data markup to say, well, this is for this country, this is for another country, but really make sure that when our systems look at these pages, they say, oh, this looks completely different. It makes sense for us to invest some more time and to index the this page individually.  

#### [0:43:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2580) |  From a ranking point of view it

doesn't change anything. So it's not the case that one page will be ranking higher or lower in a case like this. It's really just like we use this page as a basis for the indexing, or we use both of these pages as a basis for indexing. It doesn't change anything with regards to how and when it is shown in search. So from that point of view, sometimes it makes sense to just say, well, OK, Google  

#### [0:43:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2610) |  does this weird thing with the canonicalization,

but it saves me some trouble. So I'll just leave it as is. Sometimes there might be situations where you really say, I absolutely need to make sure it's indexed individually, because maybe the company slogan is completely different in Canada and in France. So we need to make sure that our snippets are completely different across those two versions, and then it makes sense to try to split things up.  

#### [0:44:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2640) |  AUDIENCE: John, regarding this, there are some

genuine case sometimes happen. So like, I was working in one university website where because of COVID-19, the campus is closed and the website has moved to online courses. In this case, obviously those levels would be the same [INAUDIBLE] students will come, first thing. Second thing is that the duration is also the same,  

#### [0:44:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2670) |  but in this case, I can not

get an online course on campus page, because I don't know for how long this online will go on. JOHN MUELLER: I'm not sure how you mean. AUDIENCE: So like my on-campus degree course page was ranking and everything was good after COVID-19. On campus, students are not getting registered because of visa restrictions.  

#### [0:45:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2700) |  Correct? And the company or the university

has moved to online courses, because a company also needs money. So in this case, if I am going with a new page for online courses, obviously the content would be same, the order structure is the same, the duration is the same, and I cannot suggest to them to play with on campus page, because I don't know for how long COVID-19 will go on, and again, they will be back to on-campus page.  

#### [0:45:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2730) |  JOHN MUELLER: Yeah. AUDIENCE: Sometimes it is

very difficult for us to plan for if we want to target online now what more we should be doing, because 80% of the content genuinely is the same. JOHN MUELLER: Yeah But I think in a case like that, the significant part of the content would be significantly different. If you're talking about on-campus versus online courses, that's a very, very different setup.  

#### [0:46:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2760) |  In a case like that, I'm pretty

sure we would index both of those pages, because they're targeting very different things. AUDIENCE: [INAUDIBLE] I have some additional content, just to make like different content on both pages, because the syllabus would be same, exams kind of thing would also be same? JOHN MUELLER: I wouldn't artificially just add content to make it look more different.  

#### [0:46:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2790) |  I think in general, the online/offline variations

there, that should be significant on the page, and that's something that we will pick up on. I don't see any problems with that. I think the trickier part, which you mentioned initially as well, is nobody knows how long this will last and how much time we should be investing in making those pages better. That's something where it might also make sense to say,  

#### [0:47:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2820) |  I will work on the persistent version

of this page, and just assume the course is kind of the main product that's being sold, and the variations-- kind of in-person or online-- are more attributes of that main thing, just to keep your existing main page, and then add information about the online course there. The advantage of using your existing pages is that they're already pretty strong within your website.  

#### [0:47:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2850) |  It's already understood how they work within

your website. So ranking is going to be a lot easier. Whereas if you create new pages for the online courses, then that's something where we will have to understand those new pages first, and understand how they fit in with your website, and understand how they work with the rest of the way. AUDIENCE: Yeah. JOHN MUELLER: I don't know. Probably it's too late to make big changes like that, but that's kind of the direction I would tend to go if you need to make these kind of changes,  

#### [0:48:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2880) |  where you're taking the same product and

providing it in a different way. AUDIENCE: Yeah, OK. JOHN MUELLER: OK, cool. We're running low on time. I have a bit more time afterwards if any of you want to hang around, but feel free to ask any questions that are still on your mind. No questions.  

#### [0:48:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2910) |  OK. I mean, I can grab more

questions that were submitted. Let's see. We had to adapt the information on one of our holistic content pages due to COVID-19. The changes will be temporary. Concerning the meta-description of the page, I got the SEO tip to include a second meta description and title concerning this topic info into the header. Would this really make sense to Google?  

#### [0:49:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2940) |  So if you're including a second meta

description tag on a page, we will treat that the same as if you just extend the existing meta tag on the page. So there is no kind of bonus to using a second description tag on a page compared to just adjusting your existing one. With regard to the title, that's the same thing. It's not that there's any kind of a bonus attached to making a second title tag.  

#### [0:49:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=2970) |  Essentially, you might as well just write

a clear new title using the existing title. On some query in Thailand, the Facebook page is indexed on number one, and I've noticed this for almost a year already. Is it because Facebook is more authoritative and leaves no chance for other websites to be indexed on position one for this query? Is there something called SEO for Facebook profiles as well?  

#### [0:50:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=3000) |  I'm pretty sure there is something called

SEO for Facebook profiles. I don't know what the name is, but I am pretty sure for all of these big networks, there are people that work on optimizing their profiles and optimizing their pages to work well there. So that part of the question is something I can't really help with, but I'm pretty sure that's the case. With regards to Facebook ranking for some queries in Thailand,  

#### [0:50:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=3030) |  I think it's completely normal to have

a site like Facebook growing for some queries in Thailand. It's not the case that we would say, Facebook is the best page in the world, therefore it should rank for all queries. But for some queries in some locations, it probably makes sense to rank some of that content there. The content there is essentially public web content. Like anything else, we can crawl and index it. And if we think it's relevant for users, we will try to show it in the search results. So that's essentially pretty straightforward.  

#### [0:51:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=3060) |  With regards to competing in a situation

like this, it's essentially up to you how you want to interact there. It might make sense to look into those bigger platforms and find ways to kind of highlight your content there as well. It might make sense to continue working on your own website, where you have a little bit more control over what you actually do, and to work on promoting that over time.  

#### [0:51:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=3090) |  So I really can't give you advice

one way or the other, but essentially, there's nothing kind of magical about content that's hosted on Facebook versus content that's hosted on your own website, with WordPress, or maybe content where you're using Wix, or some other content management system. All of this content can rank highly in the search results, and it's not that there's any kind of magical lever on our side that says this domain has  

#### [0:52:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=3120) |  to be the one that we show

for this query. Technical issues can cause a swing between normal rankings and return to normal if we have temporary server errors, like 500. Such events lasting a few hours, and Search Console does not log these events is errors. So this is something where it is hard to say  

#### [0:52:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=3150) |  exactly what you mean there. But in

general, technical issues that happen temporarily are things that we can work around for the most part. So if your site is returning 500 errors or 503 errors for maybe a few hours, then what will happen practically is our systems will say, well, this looks like something temporary is going wrong here, and we will get back to this website and check back with it later on. And if later on we get to this website again  

#### [0:53:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=3180) |  and we see that things are still

broken, then, after a certain period of time, we will drop those URLs from our index. And at that point we will highlight that and search console and say, this page is no longer indexed because of crawler issues. Whereas temporary issues like this, which kind of come and go and our systems are able to deal with them appropriately, those are not things that we would necessarily need to report in Search Console, because they wouldn't affect indexing  

#### [0:53:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=3210) |  until they do become something that happens

for a longer period of time. So from that point of view, that's kind of working as intended. The one thing where these kind of errors would have an effect a little bit faster than maybe before the URLs drop out of the index is with regards to the crawl rate of the website, where if we see a lot of URLs suddenly returning server errors, then usually our crawl system will say,  

#### [0:54:00](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=3240) |  oh, we need to be careful here

that we're not the reason why these pages are returning errors, and they will tend to scale back the amount of crawling that we do on this website. And usually this happens over a couple of days. And as we see that those errors go away again, then we can ramp up the crawling again and crawl as much as we did before. This is essentially a kind of a protection mechanism to avoid Google being the reason for causing issues  

#### [0:54:30](https://www.youtube.com/watch?v=W9xWTYPqgaU&t=3270) |  on a website. All right. I think

we're kind of over time. So let me pause the recording here. If any of you want to stick around, you're welcome to hang out a little bit longer. Otherwise, I wish you all a great weekend. Stay safe, and hopefully I'll see you again in one of the future hangouts. Bye, everyone.  