[![Rendering & Crawl Budget - #AskGooglebot](https://i.ytimg.com/vi/rwxXOJT4tRo/maxresdefault.jpg)](https://www.youtube.com/watch?v=rwxXOJT4tRo)

## Rendering & Crawl Budget - #AskGooglebot

In this episode of AskGooglebot, John Mueller discusses what crawl budget is, and whether the web rendering service reduces it. The question was submitted by @m_karg. Thank you!



What crawl budget means for Google → https://goo.gle/2Iqf9uY

Reduce the Googlebot crawl rate → https://goo.gle/38LfMb5



Send us your questions on Twitter with the hashtag AskGooglebot and your question might be answered! 

Google Search Central on Twitter → https://goo.gle/3f4Z0a8



Watch more AskGooglebot episodes → https://goo.gle/2OjWcvS

Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=rwxXOJT4tRo&t=0) |  [MUSIC PLAYING] JOHN MUELLER: Today's question comes

from Michael, and it's, "does intensive use of WRS also reduce crawl budget for a site?" Thank you for your question, Michael. There are a few things that come together here, so let's briefly unpack them before we dive into the details. WRS refers to Web Rendering Service, which is what Googlebot uses to render pages like a browser,  

![](https://i.ytimg.com/vi/rwxXOJT4tRo/maxres1.jpg)



#### [0:00:30](https://www.youtube.com/watch?v=rwxXOJT4tRo&t=30) |  so that we can index everything in

the same way that users would see it. Crawl budget refers to the system that we use to limit the number of requests that we make to a server, so that we don't cause problems during our crawling. This isn't something that most sites need to worry about since Google has no problem crawling enough URLs from most websites. While there's no specific threshold, I'd consider a crawl budget a topic that mostly large websites-- let's say, sites with more than a few 100,000 URLs--  

![](https://i.ytimg.com/vi/rwxXOJT4tRo/maxres2.jpg)



#### [0:01:00](https://www.youtube.com/watch?v=rwxXOJT4tRo&t=60) |  really have to think about. For crawl

budget, our systems automatically determine the maximum number of requests that a server can process over a given period of time. This is done automatically and adjusted over time. As we see that the server starts to slow down or return server errors, we reduce the crawl budget available to our crawlers. There is a bit more about crawl budget in a blog post linked in the description if you want to check that out.  

#### [0:01:30](https://www.youtube.com/watch?v=rwxXOJT4tRo&t=90) |  For rendering, our services need to be

able to access embedded content, such as JavaScript files, CSS files, images, and videos, as well as server responses from APIs that are used on the pages. We use a lot of caching to try to reduce the number of requests needed to render a page. But, in most cases, rendering results in more than just one request, so more than just the HTML file being made to the server.  

#### [0:02:00](https://www.youtube.com/watch?v=rwxXOJT4tRo&t=120) |  In short, if you're working on a

large site, then reducing the number of embedded resources required to render a page can help with crawling. Of course, doing that usually also makes pages faster for users as well. So you can cover both sides at the same time. I hope you found this video useful and insightful. If there's something else you want to add or if this video helped you in some way, feel free to comment below. [MUSIC PLAYING]  