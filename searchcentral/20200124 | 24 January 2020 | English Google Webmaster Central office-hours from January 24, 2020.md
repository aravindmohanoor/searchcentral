[![English Google Webmaster Central office-hours from January 24, 2020](https://i.ytimg.com/vi/RE6ATxMcDss/maxresdefault.jpg)](https://www.youtube.com/watch?v=RE6ATxMcDss)

## English Google Webmaster Central office-hours from January 24, 2020

This is a recording of the Google Webmaster Central office-hours hangout from January 24, 2020. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Watch out for new sessions, and add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



Feel free to join us - we welcome webmasters of all levels!



Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=0) |  JOHN MUELLER: OK, welcome everyone to today's

webmaster central office hours Hangout. My name is John Mueller. I am a webmaster trends analyst here at Google in Switzerland. And part of what we do are this office hour Hangouts, where folks can join in and ask their questions around SEO and websites and Google search, of course. A bunch of questions were submitted already. But if any of you want to get started with a question, you're welcome to jump on it now.  

#### [0:00:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=30) |  AUDIENCE: I would like to get started.

So I mentioned already in the comments, so we see at the moment huge issues when it comes to indexing of [INAUDIBLE]. So for example, for the brand IKEA in Germany at the moment, so when you're searching for IKEA kitchen in Germany, Google is showing the Austrian version of the URL instead of the German version and, on the second place, an old URL, which is in PDF, which is redirected. So we tried everything to fix this on the technical side.  

#### [0:01:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=60) |  So we were checking all redirects, [INAUDIBLE]

XML, hreflang, TXT, check technical issues, like all times regarding also CDN and so on, but we haven't found any issues technical side or content side. And also, have no manual action in place, especially no other search engines is showing this issue. So it would be interesting to get your thoughts about this.  

#### [0:01:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=90) |  JOHN MUELLER: Now, I saw that question

this morning. And I had a chance to briefly look into it. And it feels like something maybe on our side, where we're kind of holding onto two particular URLs. So I've passed that onto a team to double-check. AUDIENCE: OK. JOHN MUELLER: Yeah. I don't think there is anything particular on your side that you're doing wrong. Sometimes with different country versions that show the same content it's a bit confusing on our side,  

#### [0:02:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=120) |  but we should be able to catch

that better. Especially, I think, the PDF example that you gave with the PDF URL, that's something that to me just looks like something is stuck on our side. AUDIENCE: OK. So you will keep us updated on such an issue and will give an official update on this? JOHN MUELLER: Usually what happens with these kind of things is, when you pass them onto the engineering teams, they're able to kind of look at them and find a way to resolve them.  

#### [0:02:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=150) |  And that's something that'll resolve itself over

time. Most of the time, we don't have any official updates that we can pass back. AUDIENCE: OK. So we should see some updates in the Google search console regarding indexing status of [INAUDIBLE] subdomain. JOHN MUELLER: I imagine you'd see that, yeah. AUDIENCE: [INAUDIBLE]. OK. JOHN MUELLER: Yeah. AUDIENCE: Thanks, John. JOHN MUELLER: Sure. I think there was another one who wanted to jump in.  

#### [0:03:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=180) |  AUDIENCE: Hi, John. I had a question.

JOHN MUELLER: Hi. AUDIENCE: Hi. The thing is that yesterday I met a client, and I'm going to begin [INAUDIBLE].. When I saw the website, majority the pages are indexed in [INAUDIBLE]. And a few pages are indexed in [INAUDIBLE].. So is it OK if we just select the preferred domain as HTTPS [INAUDIBLE],, or do I need to do 301 for all the  

#### [0:03:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=210) |  [INAUDIBLE] pages to [INAUDIBLE]?? I'm just scared,

because the site is around five years old. And there are around 20 K-plus pages indexed [INAUDIBLE].. So I just want to check with you, yeah. JOHN MUELLER: Usually, the preferred domain is good enough for these kind of cases where it's the same content on both of the variations. From a best practice point of view, it's always good to redirect, though, to kind of make sure that you're following up on that. But if you can't set up the redirect,  

#### [0:04:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=240) |  then the preferred domain makes it easier

for the data to be in the right version. The other thing you can do is use domain verification in Search Console. If you use domain verification, then it doesn't really matter which of these versions are shown in search. All of the data will still be in that one account. AUDIENCE: OK. Thank you. JOHN MUELLER: Sure. AUDIENCE: Hi, John. Can I ask question? JOHN MUELLER: Hi, sure.  

#### [0:04:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=270) |  AUDIENCE: So I have a question regarding

Search Console. So in Search Console, I find my normally pages are 66 K [INAUDIBLE]. But in the mobile specific pages, I only see 3 K pages. So I was just wondering why this happened. JOHN MUELLER: So how do you mean in the mobile section? AUDIENCE: So in the main coverage page, I see 66 valid K pages. But when I see the mobile usability pages, I see only 3 K valid pages.  

#### [0:05:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=300) |  JOHN MUELLER: Oh, OK. That's completely normal.

So the index coverage report shows essentially all of the indexed URLs that we have from the site. And the aggregate reports, like the mobile usability report, the structure data reports, also the speed reports, they only focus on a small part of the total index. So that's something where it would be normal to see that difference between the total count.  

#### [0:05:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=330) |  What you would watch out for in

those reports is just kind of a percentage of errors that we show. So it's not so much that the total number of pages has to match, but that kind of the errors in those reports are fairly low. AUDIENCE: OK. Good, thank you. JOHN MUELLER: Sure AUDIENCE: Hey, John. Can you hear me? JOHN MUELLER: Depends on how complicated the question is? AUDIENCE: It's not that complicated. Yeah, so I guess this question is  

#### [0:06:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=360) |  sort of like a question off the

back of the knowledge panel feature snippets and how that's counted in Google Search Console. For a few of the key words that we've looked at in Search Console where, after this update has happened, we've basically just seen our position almost like go to the bottom of the search results. So is it counted at the bottom, or is it at the top? How is it supposed to function?  

#### [0:06:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=390) |  JOHN MUELLER: Nothing really changed there with

the way that Search Console tracks the position. So what happens in Search Console is we track the topmost position of either the URL or the site, depending on how you're looking at the report. And we use that for the averages. So if the topmost position hasn't changed, like if you're being featured as a featured snippet already, then that would continue to count the same. On the other hand, if your featured snippet moves  

#### [0:07:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=420) |  on the page or if the featured

snippet is no longer shown and only your normal-- I guess both of them are kind of organic search results, but kind of the traditional search results are shown instead, then that position would be ranking. What I've also seen in some screenshots-- I haven't looked at it in detail-- is that we also show something on the right side bar sometimes that looks like a mix between a knowledge panel and a featured snippet.  

#### [0:07:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=450) |  And that would probably count as, I

don't know, position 10 or 11, because we kind of number them down and then decide. So if the featured snippet moved from kind of the top of the first column to the top of the second column, essentially then that would count as a different position. AUDIENCE: Awesome. That perfectly answers the question. And I guess Danny was saying that we're going to make some changes potentially this weekend to roll that back, because we've seen  

#### [0:08:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=480) |  quite a big decline in clicks. Because

I think most people probably might focus on the left-hand side rather than the right-hand side. Yeah. JOHN MUELLER: I don't know. I haven't looked into that in detail. AUDIENCE: OK. JOHN MUELLER: But that's certainly possible. I know they're still working out some of the details and making some changes there. So it's like, some things are still in flux. AUDIENCE: Awesome. Thanks, John. JOHN MUELLER: Sure.  

#### [0:08:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=510) |  All right, let me run through some

of the submitted questions. And we can get to more live questions as we go along. In Search Console, I see a number of industry related websites have linked to a number of PDFs I have available on my e-commerce site. However, my PDFs don't have a link within them going back through the relevant product or category page. Should I add one? Would it help from an SEO ranking point of view?  

#### [0:09:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=540) |  So first off, I think this is

a really interesting question, because lots of people have PDFs on their website. And probably most people are not thinking about the links within the PDFs. Just from a pure usability point of view, I think it makes a lot of sense to have a link back to your products, back to your website, back to maybe the category pages even within these PDFs. Because these PDFs might get spread around. People might share the PDFs directly with other people. And making it easy for folks to get from the PDF  

#### [0:09:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=570) |  to your website is a fantastic idea.

So that's something I would encourage you to do, regardless of any SEO aspect there. With regards to SEO, because within PDFs there is no way to kind of let us know that a link is really a link that you want to use to pass signals, we would generally view these links as kind of text links that we also find in text files, essentially  

#### [0:10:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=600) |  similar to a no file [INAUDIBLE],, in

that we recognize the link is there. We can look at where this link is pointing at. But for the most part, we would not be forwarding any signals through those links. So from a pure SEO point of view, I would say it's questionable that you have any advantage from this. But from a usability point of view, I would totally make sure you have those links within your PDFs.  

#### [0:10:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=630) |  There's advice on the internet-- oh my

gosh, I'm sure this is bad. Advice on the internet-- about cleaning each HTML code and its effect on SEO. Is it really important to delete old HTML comments, for example? OK. Essentially, you don't need to clean HTML comments within your HTML pages. That's not something that has any effect on search at all unless you have kind of an extreme amount of HTML  

#### [0:11:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=660) |  comments in the sense that maybe you're

looking at a page that is 100, I don't know, kilobytes of HTML. And you have 100 megabytes of HTML comments in there. Then that's going to be really hard for us to figure out where the actual content is. But if you have a normal amount of HTML with kind of a reasonable amount of HTML comments in there, that makes absolutely no difference. And with regards to those extreme cases, that's something you'd also see from a speed point of view.  

#### [0:11:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=690) |  But I just from a personal point

of view, I have never seen any page that has so many HTML comments that it would cause any problem. So it feels like something where, theoretically, you could create such pages if you copied, I don't know, Shakespeare and "War and Peace" as HTML comments into a page. But that's not going to be something you see in practice. Multilingual sites sometimes use the same media library  

#### [0:12:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=720) |  that results in the same image being

used on the page in different languages. Do you recommend going through the hassle of duplicating the images, so relevant file name can be provided for each language version of the website? No, you absolutely don't need to do that. There are two things here. On the one hand, the file name is a really, really small factor. And we see a lot more information from the rest of the page. If you have text on the page, if your image is embedded  

#### [0:12:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=750) |  in a very prominent way, that helps

us a ton more than the file name. And on the other hand, when we recognize that images are duplicated across a website or across the web, kind of like with HTML pages, we fold them together and just keep one copy in our index anyway. So there is no advantage from just duplicating images for multilingual websites. How long does it take for Google to replace the old contents of the website if the website content has  

#### [0:13:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=780) |  been removed? How long does it take

for Google Mobile to index websites? So in general, I think this comes back to how Google crawls and indexes. And we crawl and index pages at different frequencies. So what will happen is that some pages we recrawl every couple of minutes. Other pages, we recrawl every couple of months. And somewhere in between there is kind of most web pages.  

#### [0:13:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=810) |  Usually, on a common website, we will

recrawl the important pages, like the home page, maybe the higher level category pages, every couple of days. And from there, it kind of goes down to maybe once every half year or so where we recrawl pages that we think are really a lot less critical on this home page or especially pages that we think don't change a lot. So depending on which page you changed,  

#### [0:14:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=840) |  if you change your home page, we'd

probably notice that within a couple of days. If you changed some random page way in the bottom of your website, then probably it would take a couple of months for us to recognize that. And if you change your whole website, then what will generally happen is the more important pages, the ones that are visibly shown in search, they'll be updated fairly quickly, within a couple of days, maybe a week or so. And the kind of less visible pages in search, they'll be updated over a longer period of time. So you'll see kind of this curve of it really updates quickly,  

![](https://i.ytimg.com/vi/RE6ATxMcDss/maxres1.jpg)



#### [0:14:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=870) |  and then it kind of slows down

with the update speed. If a user right-clicks an element on the Search Result page and opens a new tab, will it be counted as a click? Because the definition says, any click that sends a user to your page outside of Google Search is counted as a click. But in this case, that Google Search is still on. Good point. Maybe we should clarify that in our documentation,  

#### [0:15:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=900) |  but it feels like a really weird

edge case. Any click like that is counted as a click. So if you right-click, or if you middle-click, or if you have some other mechanism for opening a URL in a separate tab or in a separate window in a browser, we count that as a click, essentially anything where you're going to that page or loading that page directly. Is it important that all pages of the site are accessible within n transitions from the main page?  

#### [0:15:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=930) |  For example, some news from 2015, before,

say, is accessible only in 10-plus steps. Is that OK? That's perfectly fine. Usually what happens here or where this comes from is that on a lot of websites the home page is the most important part of the website. So we recrawl that fairly often. And from there, we try to find kind of new and updated  

#### [0:16:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=960) |  pages or other important pages. So what

will happen is we'll see the home page is really important. Things linked from the home page are generally pretty important as well. And then kind of as it moves away from the home page, we'll think, well, probably this is less critical. So that's something where you might see things like this, where someone will say, well, some amount of steps is the minimum steps from your home page. From our point of view, that's less about SEO and more about,  

#### [0:16:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=990) |  well, we have to discover all of

these pages somehow. So if news articles from 2015 are behind some archive where you have to kind of find that archive, find the year, and then look at the month, and look at maybe a category, and then find the news article, usually that's perfectly fine. On the other hand, if there's something that you really, really care about and you think is really important and you hide it away like that, then probably we'll think it's not as important.  

#### [0:17:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1020) |  So if you think it's important, then

make sure it's really easily findable within your website. I am seriously considering improving the usability of some of our pages by adopting an accordion page presentation. My concern is, as the user will have to physically open tabs or windows to see the content, then will this affect Googlebot's ability to read and assess the content? Please advise how accordions effect crawlability  

#### [0:17:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1050) |  and subsequent ranking. Yeah. I don't know

exactly what kind of setup you're looking at. So it's hard for me to say for sure. A really common kind of accordion that we see, or kind of like a carousel that's kind of similar, I guess, is where you use this UI element to essentially  

#### [0:18:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1080) |  navigate to other pages. And in cases

like that, usually the content within the accordion or within a carousel is still within the HTML page. So what would happen in a case like that is we'd be able to pick up this link to the other page regardless of how it's displayed on your page. And we would just follow that like a normal link. So that's generally a total non-issue. On the other hand, if you're setting something up where the full content is within an accordion,  

#### [0:18:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1110) |  then that's potentially kind of tricky. Maybe

that's also kind of OK. If the full content is within your HTML page from the beginning, then that's fine. On the other hand, if clicking on the accordion causes the server to load that content into the accordion content, then we would not be able to figure that out during crawling and indexing. In particular, anything that requires any interaction in order for the content to be loaded,  

#### [0:19:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1140) |  that's something we would probably miss out

on. If the content is already loaded by default, then that's generally not a problem. Theoretically, could a website that's only one to two weeks old rank for top positions on Google for ultra-competitive head keywords, say, for example, for shoes with significantly better content, only considering it's the most important part of the core algorithm? If not, then clearly time is a factor  

#### [0:19:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1170) |  when it comes to ranking pages for

highly competitive areas, no matter how good they are, unless new pages are created on already established websites. So I think these kind of theoretical questions are always a bit tricky, because the answer is, well, theoretically lots of things could happen. But in practice, things are not so theoretical. So I don't really know if there is  

#### [0:20:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1200) |  a good answer that would be useful

to give for something like this. We use lots of different factors when it comes to crawling, indexing, and ranking. And sometimes that means that completely new websites show up very visibly in search. Sometimes that also means that it can take a bit of time for things to settle down. In particular with completely new websites, one of the difficulties that we have is we might not have a lot of signals for those websites. So we have to make estimates.  

#### [0:20:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1230) |  And depending on how we make estimates,

that can sometimes mean that, in the beginning, we show this website a little bit more visibly than it turns out that the signals tell us in the end. It could also mean that, in the beginning, we show this website a little bit less visibly than the signals might tell us in the end. So that time period of understanding the website and understanding how it fits in with the rest of the web, that's always kind of a factor there.  

#### [0:21:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1260) |  But that can go both ways. It

can go in the direction of you are shown very visibly in the beginning, and it could also be that maybe you're shown less visibly in the beginning. And as we understand your website and how it fits in with the rest of the web, then we can kind of adjust that. And we do have different algorithms that pick up on things really quickly. So for example, some news item happens, and we try to pick that up within seconds. Sometimes it's also new websites that show up that we try to pick up really quickly.  

#### [0:21:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1290) |  So it's not that time is the

only thing that matters or time doesn't matter at all. There's lots of nuance. I have a two-year-old property website with more than 400,000 pages. The thing is my URLs are with underscores instead of dashes. As I'm doing an extensive on page SEO, I just wanted to ask, is it worth changing all my URLs from underscores to dashes?  

#### [0:22:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1320) |  So, no, you don't need to do

that. In general, we do understand words separated by dashes a little bit better than words separated by underscores, but that difference is really, really minimal. So that's something where I would not just revamp a whole website to go from one format to the other. The main reason I would not do this is because the positive effect is really tiny.  

#### [0:22:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1350) |  And the negative effect from revamping your

whole website to a completely new year URL structure, that is much stronger. And that's something that you will kind of like have to worry about for quite some time until it really settles down. So anytime you completely revamp the URL structure on your website, that means we have to understand all of the connections between all of the old URLs and the new ones. And we have to recrawl the whole website to understand  

#### [0:23:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1380) |  how the internal linking works. And usually

that's something that, I'd say, takes a couple of months at least. And it can take much longer than that depending on the website. So from my point of view, the potential upside of having dashes instead of underscores is so tiny compared to the downside of having to revamp the whole website. If you're starting a completely new website and it's like, dashes or underscores?  

#### [0:23:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1410) |  I don't care. I will just pick

one. Then I would go with dashes. But if you have an existing website, then don't revamp it just because of underscores versus dashes. I'm looking at my home page in Search Console live test, and it looks completely unstyled. Inspecting the More Info tab tells me the main CSS file wasn't loaded due to an other error. I'm concerned that Google will evaluate my site's UX negatively, because of this.  

#### [0:24:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1440) |  So first of all, we would not

evaluate your site's usability negatively because of this. That's something that sometimes happens when we render pages. What might happen in some of these cases is that we would have trouble understanding that it's a mobile-friendly page. But that's something that, for the most part, settles down fairly quickly. The other part of the question is, well, this other error is totally not actionable.  

#### [0:24:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1470) |  I have no idea what is wrong.

You're not wrong. That does seem like something that we should make a little bit clear. A lot of times, other error also just means that we didn't get around to fetching this year URL for this particular live test. And that's potentially different from when we actually indexed the page and render the page on our side. Because with a live test, we want to focus on speed.  

#### [0:25:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1500) |  We want to make it so that

you see a result as quickly as possible. So we will not use caching. And we'll have a much lower time out than we would for indexing, just so we can show you a result as quickly as possible. I don't think it's really that useful if you do a live test and it's like, oh, we will get back to you in a couple of hours with the results. That's not very useful for you. So we try to optimize for speed rather than for completeness  

#### [0:25:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1530) |  with a live test. And for indexing,

it doesn't matter. Because we can say, well, we'll spend, I don't know, an hour or so to figure out how to get all of these URLs that are embedded and to cache them properly, so that we can render all of the pages on your website. We have time. Nobody is rushing us when it comes to rendering. So that's something to kind of keep in mind there. I have a site map index of 200-plus [INAUDIBLE] files,  

#### [0:26:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1560) |  I guess. Usually, when we submit the

index in Search Console, it shows all site maps index. But on one of my domains, it suddenly stopped showing some site map indexes. Now, my many URLs have shifted from submitted an index to submitted, but not indexed. Errors have also reduced in half. What is happening here? It's really hard to tell without knowing your website. So I'd recommend maybe starting a forum thread with the details  

#### [0:26:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1590) |  there to double-check. In general, a site

map file helps us to better understand your website, but it's not a requirement for crawling and indexing. So if at any point we're not able to process your site map file, we'll still be able to crawl and index your pages normally. And that's essentially fine. The other thing to keep in mind is that we don't guarantee indexing of all pages. That's just physically not possible.  

#### [0:27:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1620) |  There's so many things that are submitted

as site map files. And we just don't have storage for all of that. So it's completely normal that we only index part of a website. And for smaller websites, we'll generally try to get everything. But especially for really large websites where you're creating hundreds of thousands of URLs and maybe you have different facets and filters and pagination and other URL parameters, that's something  

#### [0:27:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1650) |  where it's completely normal that we just

wouldn't be able to index all of them. Implementing a carousel of product pages with images on the home page or simple text links in normal font, does it make a difference for crawlers and priorities? Not really. Well, for crawling, we need to find those links. And if we find those links, that's completely fine. For search ranking in general, one of the things  

#### [0:28:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1680) |  to keep in mind is that anchor

text does help us to understand pages better. So if you don't have any anchor text leading to internal pages, for example, if you just have an image, then that makes it a little bit harder for us to understand what this page might be about, whereas, if you have a text link, that's a lot easier. With images, you can also use an Alt attribute for the image, and that works just as well as an anchor text.  

#### [0:28:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1710) |  Then that question from the beginning, we

talked about that. What happens to internal links page rank of a page when it's canonicalized to a slightly different page with different internal links? So when it comes to links, we see links as being between canonical pages. So we see any particular link on the web as going from this canonical page to another canonical page.  

#### [0:29:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1740) |  And on both sides, there might be

multiple pages or multiple URLs that are associated with that canonical, where we say, well, these, I don't know, five variations all belong to this one canonical. And on the other hand, maybe you also have multiple URLs that are associated with the canonical on your side. And from our point of view, we combine all of those signals and keep them with that canonical. And then with that link, we pointed it at the other canonical, and we combine all of those signals  

![](https://i.ytimg.com/vi/RE6ATxMcDss/maxres2.jpg)



#### [0:29:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1770) |  there, too. So if you're linking from

a non-canonical page to a page that is canonical, then that non-canonical page will first be canonicalized to the canonical. And then, from there, that link will essentially work. And similarly on the receiving side, if you have multiple pages that are canonicalized, that's collected in that canonical. So from that point of view, you don't need to do anything special.  

#### [0:30:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1800) |  You don't need to remove links on

non-canonical pages or anything like that. We try to just figure that out and make it work. My competitor is sending fake traffic to my website every day. Will that affect my website's SEO and ranking? No, absolutely not. If this is what keeps your competitor busy, then you have more of a chance to kind of focus on real business aspects. So that's something where it's like,  

#### [0:30:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1830) |  well, you can probably just block them

by IP address if you wanted to. But it has absolutely no effect on your site's SEO and ranking. So it's like, let them do useless things while you do something that makes a lot more sense. Is having search keywords Google translated in other languages on a page a bad thing for SEO? Users don't seem to click my website, because my title isn't in that language, but the search keywords are.  

#### [0:31:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1860) |  Does Google consider this bad behavior? So

I'm not quite sure what you mean with search keywords. If you mean the keywords meta tag, we completely ignore that. So you can put whatever you want in there. It has absolutely no effect. If you're just dropping these keywords on your pages, then probably that doesn't make a lot of sense. Because if your page isn't really in that language, then users might go to your page.  

#### [0:31:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1890) |  But they just go somewhere else after

they look at your pages. So from that point of view, we don't necessarily need to consider it bad behavior, because users are just not finding what they need on your website. And that's more your problem, not our problem. Well, I guess it's also our problem, because we're sending people to a page that is not that useful. But for the most part, it's really something where, if you're placing misleading content  

#### [0:32:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1920) |  on your pages and hoping that improves

your website in search, then that seems like a very, very short term thinking and not something that I would recommend. If I do convert my whole website into another language using Google Translate, will Google treat it as duplicate content? So first, we do not treat translations as duplicate content. Translations are totally unique pages. Secondly, if you're using Google Translate,  

#### [0:32:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1950) |  that translation might not be that great.

We would consider this to be automatically generated pages. So that's something where I wouldn't recommend just blindly using Google Translate. Using Google Translate together with manual translation reviews, kind of a normal quality assessment process behind that, that's totally different thing. You're essentially creating a localized version of your website. But just blindly using any kind of translation tool  

#### [0:33:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=1980) |  to automatically create a translated version, that

also seems like short-term thinking. Because a local speaker will look at that page and say, well, this is not what I need. I'm not going to stick around on this website. Is making attachment pages indexable a bad thing for SEO? My users like to get access to attachments separately. I populate the attachment page with the metadata of the file.  

#### [0:33:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2010) |  That seems perfectly fine. I don't see

any issues with that. Some people like to go to long form texts. Some people just like to get to a specific piece of content that they're looking for. And depending on what kind of attachments you have, what kind of information you have there, that could be completely reasonable type of page within a website. I would just watch out for kind of going down  

#### [0:34:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2040) |  the direction of creating pages for the

sake of having created pages. The number of pages on your website is not what you should be focusing on. You should really be focusing on the quality of the pages that you're creating. So for example, if you create attachment pages for every image on your website, then for most websites that doesn't make a lot of sense. Because you're creating all of these pages, and people aren't really using them. On the other hand, if it's a stock photography website,  

#### [0:34:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2070) |  then maybe that does make sense. So

that's something you kind of have to figure out on your own. I recently saw a significant drop in ranking, no manual action or security issues. However, some pages are still ranking high in the search results, but most of our service pages have really dropped significantly in ranking along with our blog posts. What could be the problem, some service pages still ranking high, while others have dropped significantly?  

#### [0:35:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2100) |  And there's the URL. I need to

take a look at the URL to see what exactly this might be. But in general, changes in ranking can happen. So that's something where just because things have happened ranking well for the moment doesn't mean they will always continue to be ranking well. And kind of similar to that question earlier on, new pages can also rank well. So it can also be that suddenly there  

#### [0:35:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2130) |  may be lots of other pages that

are ranking well, because either they're new and they're really good, or either our algorithms are thinking that maybe these are more relevant for some of these queries. So these kind of things is not something where there's one particular reason why this is happening. There can be lots of reasons why there might be changes in ranking. In general, what I'd recommend for cases like this where you're kind of unsure is it on my side,  

#### [0:36:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2160) |  is something on Google's side, I'd go

to the webmaster help forums. Make sure to mention your website and some of the queries that you are looking at, so that the folks there can take a look and give you a little bit more of an honest assessment where they say, well, your website looks fantastic. Maybe Google did something wrong. And they can also contact us and escalate it to us. Or similarly, they might look at your website  

#### [0:36:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2190) |  and say, well, actually, this doesn't look

that great. Maybe you should put more work into improving your website first. And then over time we'll see if this is something that Google needs to change as well. I've been getting hundreds of 500 errors in Search Console. I checked my server logs for the pages that got reported for 500 errors the days the Search Console site tried to access them, but I could only confirm that Googlebot visited these pages 1 out of 10 times.  

#### [0:37:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2220) |  Do you know I Search Console would

report crawl for a page on a certain day and it wouldn't show up in the server logs? So I think, first off, we don't kind of randomly generate errors and put them in a Search Console. If we're seeing crawl errors, then that's pretty straightforward. And that's something that we can report on. It's not something that we have kind  

#### [0:37:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2250) |  of algorithms that try to guess when

crawl errors might take place. But rather, these are pretty direct errors that come from our systems. So I would assume that the errors that you're seeing in Search Console, with regard to crawl in particular, are actual errors that we saw while we tried to crawl your website. The other thing that I have sometimes seen  

#### [0:38:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2280) |  is that a lot of websites have

multiple layers before a request actually reaches the server itself. And that could be something like, I don't know, security protections that you have all along the way. It could be content delivery networks that you have set up. All of these things can also return errors. And it can certainly happen that a request comes in from Googlebot site and is blocked by some security layer  

#### [0:38:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2310) |  outside of your normal web server. And

perhaps that layer either fails and returns a 500 error or blocks us completely, so that the request times out. And that might be something that you would not particularly see logged on your server. So that's something where it might make sense to double-check with your hosting provider to make sure that you're getting the full picture and that nothing is being kind of blocked or breaking there.  

#### [0:39:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2340) |  Finally, the last thing, I think, is

that 500 errors are things that you really want to take care of. 500 errors are server errors, which means that something along the way is breaking. So it's not a 404 error where the URL just acts like it doesn't exist, and we try it again. A 500 error is really something that we tend to take seriously in the sense that we sometimes assume that maybe it's our fault  

#### [0:39:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2370) |  something is breaking. Whoops-- something weird. OK.

So what else happens when presenting? OK. But like I said, 500 error is really something that-- Let me just mute you. Whoops. Oh, man. Too many buttons on his laptop.  

#### [0:40:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2400) |  500 errors, back to 500 errors, so

we assume that these are actual things that are causing problems. So what will happen is we will crawl less frequently. So that's kind of why fixing and finding the source of 500 errors makes a lot of sense. So usually it's a sign that something is really breaking. And usually, the result will be that Google crawls a lot less frequently. So it's really worthwhile to get to the bottom of those.  

#### [0:40:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2430) |  We're using the latest version of the

Yoast SEO plugin for our blog, which in theory should take care of implementing structured data automatically for all of our articles. Do you think that's enough, or should we implement structured data on each article if we want them to show up for featured snippets? So featured snippets don't need any structure data. So that's kind of the first thing there. So you're probably already on the good side there.  

#### [0:41:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2460) |  With regards to the structured data, I

wouldn't just blindly focus on one plugin and say, I installed a plugin. It should be OK. But rather, I'd use the testing tools to make sure that the type of structure data markup that you're using matches what you would like to have kind of picked up from these pages. So using things like the rich results test in Search Console or double-checking the aggregate reports in Search Console,  

#### [0:41:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2490) |  that's generally the direction I would head

there. The Yoast plugin does a lot of things really, really well, so I think that's definitely a good thing to have there. But it's not this one thing that you install, and it fixes everything. You still should kind of double-check to make sure that things are working the way that you want it. And it's not so much that maybe the plugin doesn't do it.  

#### [0:42:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2520) |  But maybe there are options that you

can activate or disable. So it's like, just e-check to make sure that things are working the way that you want it rather than just blindly saying, well, I have this installed. This will fix everything. Will Google ever offer a CDN solution of its own? So we do have a CDN. It's the AMP cache, essentially. So for AMP pages, that's something where we  

#### [0:42:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2550) |  cache these pages on our side. We

serve them directly from this CDN to users in the search results. They're even preloaded depending on how that's set up. So that's something we kind of have there. If you want something fancier or something separate from AMP, I don't know if there are potentially offerings on Google Cloud. Or maybe you can set up your own CDN like that. But there are also lots of third party CDNs out there  

#### [0:43:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2580) |  that are really, really well made. So

I wouldn't just say, if I want to install a CDN, I have to use Google CDN. And there some really, really good solutions out there that can provide a lot of functionality for you as well. And some of these are not crazy expensive. So it's worth looking around. OK. Wow, and a complicated long one.  

#### [0:43:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2610) |  Let's see if we can get through

this. Due to a copyright issue in Europe, the company I worked for has almost the same English language website on two different domains. With the exception of some branding differences, it's basically the same website on two domains. There's one domain for Europe and one for the rest of the world. We differentiate the two from here on by calling one the EU domain, the other the ROTW domain. The issue, in addition to concerns  

#### [0:44:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2640) |  over duplicate content, is that it seems

that Google may be confused as to which is the proper site to show in the search results depending on the location of the searcher. This gets more complicated as Europe has many languages, and thus we have many different language versions of the EU domain. However, we obviously do not cover every single language in Europe. Thus, we want the English version of the EU domain to be sort of default for European users that do not fit in with other various language  

![](https://i.ytimg.com/vi/RE6ATxMcDss/maxres3.jpg)



#### [0:44:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2670) |  versions of the website. How do we

tell Google that the default site for Europe is the English language EU domain, but the default domain for the rest of the world is the other one? I thought about using regional language hreflang tags and using the other as a [INAUDIBLE] default, but this would be an issue for two reasons. One would be that we'd have about 5 billion hreflang tags on each page. That seems a little bit exaggerated, but OK.  

#### [0:45:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2700) |  We'd have to have an English language

tag for each region in Europe in addition to hreflang tags for each non-English version of the site. The second would be to do with a copyright issue I mentioned at the beginning. We cannot send European users to the rest of the world domain. Hopefully, there is a more elegant solution. So unfortunately, I don't see an elegant solution here.  

#### [0:45:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2730) |  I think this is something you probably

need to set up with hreflang. And you probably need to go into that with the assumption that the hreflang markup on its own won't fix this completely. So the hreflang set-up, I think you kind of roughly understood how that works. So basically, you'd have to have, for every country, the English version kind  

#### [0:46:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2760) |  of marked up within hreflang. And you'd

have an [INAUDIBLE] default version, which would cover the rest of the world. So that's something that you can set up there. And that helps us to understand the connection between all of these variations. Obviously, that can get fairly complicated. So what I would recommend doing here is, first of all, making sure that you're really implementing it on the pages that matter, where you're actually seeing problems. It might be, for example, that this is just something  

#### [0:46:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2790) |  that you need to do on your

home page and maybe on a handful of other pages within your website and not on thousands of individual product pages. So if you can reduce the scope by focusing on pages where it really matters, that sometimes makes it from this crazy impossible thing to implement to something that's more reasonably possible. The other thing is kind of how I mentioned it's not guaranteed  

#### [0:47:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2820) |  that hreflang will fix this. Especially with

a really complicated hreflang setup, it's easy to introduce mistakes. And it's easy for things just not to be crawled in time for us to pick them up properly. So that's something where it can still happen that we show the wrong country version in the search results. And you need to have an elegant way of handling that on your side. So the solution that we usually recommend is using a banner on top of the pages  

#### [0:47:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2850) |  when you can recognize that a user

is looking at the wrong version of the page. That means that users who are kind of purposely looking at the wrong version of the page, they can still look at that page, which makes a lot of sense. Because users might be in one region, but actually they're based in a different region. And maybe they'd like to see this page in French even though they're based in maybe the UK at the moment. All of these things, that's something where a banner makes it possible for users  

#### [0:48:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2880) |  to continue to use the page, but

they're still guided to the right version. And the additional effect of a banner is that, when it comes to crawling and indexing, we can crawl and index those different variations. We're not kind of forced into the US path within your website. So kind of in your setup here, if you're redirecting European users to the European website and everyone else to the everyone else website,  

#### [0:48:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2910) |  then a user from the US would

be redirected to the everyone else website. That means Googlebot, when we crawl and index your website, we would never be able to see your European website. So we would never recognize that, oh, you have content in French. And you have content in Italian. We'd never even get there, because you'd always redirect us to the rest of the world English website. So those are the two aspects there.  

#### [0:49:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2940) |  On the one hand, I'd definitely look

at hreflang. And I'd focus on the pages where it's most critical. And I'd also find a clean solution for cases where people still get to the wrong version. All right, next question, can you name the top 50 ranking factors? OK, we're running kind of short on time, so maybe we can just shift to more live questions from any of you.  

#### [0:49:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=2970) |  I imagine that's more insightful. AUDIENCE: Hi,

John. JOHN MUELLER: Hi. AUDIENCE: I have a question regarding updating old content. JOHN MUELLER: OK. AUDIENCE: So what would be the best thing to do when you have an old content and you are trying to update it to something very broader than the original content?  

#### [0:50:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=3000) |  And you know, would it be wise

for me to delete the old content, which it was very narrow? And now, I'm trying to make it a lot wider. So my question would be, is it wise to update the old content or delete it and make a new article? Because, personally, what I've seen or in experience with Google is that it [INAUDIBLE] to just for me to have new content published  

#### [0:50:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=3030) |  rather than updating it. Because it takes

time for the old content to rank or [INAUDIBLE]. JOHN MUELLER: Yeah. So what I would do in a case like that, if the new content kind of matches the old content-- it's the same topic, and you're just creating a much better article there-- then I would rewrite the old content. I would keep the old URLs and kind of expand on them.  

#### [0:51:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=3060) |  The advantage of that is you keep

all of the signals that are associated with that page so far. And that could be things like people who are linking to that article or even just your internal navigation where we already understand this page is kind of about this topic. And we have some anchor text associated with that page. So if you're just expanding it, I would definitely keep the same URL. If you're writing something completely different, then I would just use a different URL.  

#### [0:51:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=3090) |  AUDIENCE: OK. And just one more question,

what are your views on activated mobile pages? Because across the web, even community [INAUDIBLE],, I don't see a lot of people endorsing it. And I [INAUDIBLE]-- AUDIENCE: [NON-ENGLISH SPEECH]  

#### [0:52:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=3120) |  JOHN MUELLER: OK, sorry. Go ahead. So

accelerated mobile pages, I think accelerated mobile pages are a great way to really make fast mobile sites. So from that point of view, I don't have anything kind of against them. I think, depending on the type of site that you have,  

#### [0:52:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=3150) |  sometimes it takes a lot of work

to make a really fast mobile site. And AMP is a nice framework that makes it easy to create new pages that are mobile friendly and really fast. But there are also other ways to create fast mobile friendly pages. So depending on the setup that you have, maybe using AMP is a great way to get started and to make these pages. Maybe there are other ways that work just as well. For a lot of the more common CMSs,  

#### [0:53:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=3180) |  I've seen plugins that just enable AMP

by default. And sometimes that's a really quick way to make your website significantly faster. So that's something that's worth looking at to see if that's an option for your website. AUDIENCE: Sure. Thanks, John. AUDIENCE: John, I have a analytics question, if you don't mind. JOHN MUELLER: OK, I'll try.  

#### [0:53:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=3210) |  AUDIENCE: Why would my insights in analytics

show me-- I'm going to paste an image into the chat-- an insight that tells me my revenue is up in dollars when it's a UK site in pounds? JOHN MUELLER: I have no idea. You probably need to ask someone from the analytics side.  

#### [0:54:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=3240) |  Or maybe check with Daniel Weisberg on

my team. I think he's also on Twitter. So I would just ping him and see. AUDIENCE: Right, because it's pulling the right property. They're linked correctly within Webmaster Tools and Analytics. [INAUDIBLE] it's got the income on the left in pounds and, on the right, in-- JOHN MUELLER: Oh, wow. I have no idea.  

#### [0:54:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=3270) |  I don't know. Maybe it's a separate

bank account that you don't know about. AUDIENCE: Daniel could tell me where the money is? JOHN MUELLER: I have no idea. AUDIENCE: Right. OK, yeah. And for webmasters, we're setting up a new site, this new site we're launching. It will have lots of different currencies. Are we best off setting up subproperties,  

#### [0:55:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=3300) |  or not subdomains, subfolders in Webmaster Tools

for each country? JOHN MUELLER: Usually, that's a good idea. If you really have country-specific content to separate it out in a clearly visible way, so that could be subdomains, it could be subdirectories-- AUDIENCE: Subfolders, yeah, subdirectories. JOHN MUELLER: Yeah. So the one thing I wouldn't do is to use like URL parameters for countries, because that's something that's really  

#### [0:55:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=3330) |  hard for us to figure out. URL

parameters work great for different languages, because we look at the languages on a per-page basis. But for countries, we try to figure out this block of the website. AUDIENCE: When you say URL parameters, do you mean just depending [INAUDIBLE].. JOHN MUELLER: Yeah. AUDIENCE: [INAUDIBLE] JOHN MUELLER: Yeah. If you have question mark country equals Germany, then-- AUDIENCE: Right. Yeah, no. JOHN MUELLER: --that's a lot harder for us to figure out. AUDIENCE: OK, cool. JOHN MUELLER: Cool. OK, let's take a break here.  

#### [0:56:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=3360) |  I have a bit more time. So

if any of you want to stick around and chat off the record, we can do that. I think we got through a bunch of other questions. There's still a lot more. So if there's something critical that I didn't get to, feel free to just copy it into the next office hour Hangout, and we can look at it there. AUDIENCE: [INAUDIBLE],, John, I have a small question. JOHN MUELLER: Sure. Feel free to stick around. I'll just pause the recording, and we can continue.  

#### [0:56:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=3390) |  It's good to kind of pause the

recording at some point, so that we don't have an infinite long thing. AUDIENCE: OK. JOHN MUELLER: All right. AUDIENCE: My question is that, nowadays I am facing lots of problem in my Google Analytics that my Google Analytic account is not providing my exact data.  

#### [0:57:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=3420) |  There is a real time of more

than 500 on my website. But when I check that total number of [INAUDIBLE],, they only provide in full of 10,000 people per day or 8,000 people per day. According to Google Analytics, if we  

#### [0:57:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=3450) |  have real time of 400 to 500,

then that must mean the traffic of 30,000 people plus in a day. JOHN MUELLER: So on the one hand, I don't know about Google Analytics. You'd need to check in with the Google Analytics folks on that, so maybe in their health center or help forum. The other thing that is something  

#### [0:58:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=3480) |  that I know we have in Search

Console as well and some of the other tools is that the live data is often unfiltered in that includes all kinds of traffic and things that tend not to be real users. So it can happen that the live numbers are much higher than what is actually recorded, because the live numbers include things like fake traffic and bots and things like that.  

#### [0:58:30](https://www.youtube.com/watch?v=RE6ATxMcDss&t=3510) |  So that might be a difference that

you're seeing there. But I would really check in with the analytics team directly. AUDIENCE: [INAUDIBLE] where can I get the solution for this problem? JOHN MUELLER: I would go to the analytics help forum. So there's a special forum for most of our products. I can pull it out and drop it in the chat here in a minute. AUDIENCE: Please do this.  

#### [0:59:00](https://www.youtube.com/watch?v=RE6ATxMcDss&t=3540) |  JOHN MUELLER: Sure. All right, so let's

take a break here. Thank you all for joining in. It's been great to have you all here. And if you want to stick around for a bit, feel free to do that. I'll set up the next batch of Hangouts soon. And until then, I wish you all a great weekend and a great week. AUDIENCE: Thank you, John.  