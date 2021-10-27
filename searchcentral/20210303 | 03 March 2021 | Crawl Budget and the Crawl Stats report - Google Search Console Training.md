[![Crawl Budget and the Crawl Stats report - Google Search Console Training](https://i.ytimg.com/vi/x_GoMrl6_u0/maxresdefault.jpg)](https://www.youtube.com/watch?v=x_GoMrl6_u0)

## Crawl Budget and the Crawl Stats report - Google Search Console Training

Daniel Waisberg comes back for a special episode of Google Search Console Training. He provides a short introduction to how Google crawls pages, and defines terms such as crawl rate, crawl demand, and crawl budget. Then he dives into the new Crawl Stats report in Search Console which provides data on crawl requests, average response time, and more.



Search Console Crawl Stats report → http://goo.gle/3aLcUOa

What Crawl Budget Means for Googlebot →  http://goo.gle/3shjGAR

Change crawl rate limit using Search Console → http://goo.gle/3sdjhiQ

How crawling works → http://goo.gle/3uo22NN

Watch more Search Console Training videos → https://goo.gle/sct  



Share your feedback on Twitter →  https://twitter.com/googlesearchc

Subscribe to the Webmasters Channel → https://goo.gle/searchcentral



#SearchConsole #seo



#### [0:00:00](https://www.youtube.com/watch?v=x_GoMrl6_u0&t=0) |  DANIEL WAISBERG: Hi, I'm Daniel Waisberg, Search

Advocate at Google. And today I'll provide a short introduction to how Google crawls pages, and provide definitions for terms such as crawl rate, crawl demand, and crawl budget. Then I'll dive into the Search Console Crawl Stats report, which provides data on crawl requests, average response time, and more. The report contains information for several Google crawlers, but I'll focus on the search aspect of it. As a disclaimer, this presentation  

#### [0:00:30](https://www.youtube.com/watch?v=x_GoMrl6_u0&t=30) |  will be more relevant if you work

with a large website. If you have a site with fewer than a few thousand pages, you do not need to worry about it. But if you ask me, never hurts to learn something new. Who knows, your site may become the next big thing. [MUSIC PLAYING] The crawling process begins with a list of web addresses from [? best ?] crawls and site maps provided by site owners.  

#### [0:01:00](https://www.youtube.com/watch?v=x_GoMrl6_u0&t=60) |  Google uses the web crawlers to visit

these addresses, read the information in them, and follow links on those pages. The crawlers will revisit pages already in the list to check if they have changed, and also crawl new pages it discovered. During this process, the crawlers have to make important decisions, such as prioritizing when and what to crawl, while making sure the website can handle the server requests made by Google.  

#### [0:01:30](https://www.youtube.com/watch?v=x_GoMrl6_u0&t=90) |  Crawl demand is how much the content

is desired by Google. It is affected by URLs that haven't been crawled by Google before, and by Google's estimation on how often content changes on the non-URLs. The successfully crawled pages are processed and passed to Google indexing to prepare the content for serving on Google Search results. Google wants to make sure that it doesn't overload your servers, as a good citizen would do.  

![](https://i.ytimg.com/vi/x_GoMrl6_u0/maxres1.jpg)



#### [0:02:00](https://www.youtube.com/watch?v=x_GoMrl6_u0&t=120) |  With that in mind, Google computes your

site crawl rate, which represents the maximum number of concurrent connections a crawler may use to crawl your site. This value is calculated by Google periodically based on your site's responsiveness-- or in other words, how much crawling traffic it can handle. If the site is quick and consistent to respond to crawlers, the rate goes up if there is demand from indexing. If the site slows down or responds with server errors,  

#### [0:02:30](https://www.youtube.com/watch?v=x_GoMrl6_u0&t=150) |  the rate goes down and Google crawls

less. In rare cases, where Google crawlers overload your servers, you can set a crawl rate limit using the crawl rate settings report in Search Console. Taking crawl rate and crawl demand together, we can define crawl budget as the number of URLs Google can and wants to crawl. My colleague [INAUDIBLE] wrote a detailed blog post about crawl budget in the Search Central blog.  

#### [0:03:00](https://www.youtube.com/watch?v=x_GoMrl6_u0&t=180) |  Check it out. To find out how

often Google crawls your site and what the responses were, you should use the Search Console Crawl Stats report, which provides statistics about Google's crawling behavior. Here are some questions you can answer with the data provided. What's your site's general availability? What's the average page response for a crawl request? And how many requests were made by Google to your site in the last 90 days?  

#### [0:03:30](https://www.youtube.com/watch?v=x_GoMrl6_u0&t=210) |  Let's dive in to learn more about

the report. Log in to Search Console and find the Settings page, where you can open the Crawl Stats report. Know that this report is only available for properties at the domain level. It is not available for properties that include [INAUDIBLE]. In the summary page, you'll find a lot of information. The main elements are the crawling trends chart, the host status details, and the crawl request breakdown.  

#### [0:04:00](https://www.youtube.com/watch?v=x_GoMrl6_u0&t=240) |  The chart shows the trends for three

metrics. The total crawl request for URLs on your site, whether successful or not. Request resources hosted outside of your site are not counted. So if your images are served on another domain, such as a content delivery network or CDN, they will not appear here. The total download size from your site during crawling. If Google casts a page resource that is used by multiple pages, the resource is only requested the first time.  

![](https://i.ytimg.com/vi/x_GoMrl6_u0/maxres2.jpg)



#### [0:04:30](https://www.youtube.com/watch?v=x_GoMrl6_u0&t=270) |  And the average page response time for

a crawl request to retrieve the page content. This metric does not include retrieving page resources such as scripts, images, and other linked or embedded content. The response time does not account for page rendering time. Look for major spikes, drops, and trends over time in your data. For example, if you see a significant drop in total crawl  

#### [0:05:00](https://www.youtube.com/watch?v=x_GoMrl6_u0&t=300) |  requests, make sure no one added a

new robots.txt to your site. Or maybe your site is responding slowly to Googlebot. These might be understood as a sign your server cannot handle all the requests. Another example would be a consistent increase in average response time. This might not affect your crawl rate immediately, but it's a good indicator that your servers might not be handling all the load. Ultimately, this may affect user experience, too. The host status is an easy way for you  

#### [0:05:30](https://www.youtube.com/watch?v=x_GoMrl6_u0&t=330) |  to check your site's general availability in

the last 90 days. If you verified your website as a domain property, you will see all child hosts separately here. This can be very handy to evaluate all your hosts performance in one place. When you click to get the host status details, you'll find three categories. Errors in this section mean Google cannot crawl your site for a technical reason. Robots.txt fetch tells you the failure rate  

#### [0:06:00](https://www.youtube.com/watch?v=x_GoMrl6_u0&t=360) |  when crawling your robots.txt file. Your site

is not required to have a robots.txt file, but it must return the successful response 200 or 404 when asked for this file. If Googlebot has a connection issue, for example, a 503, it will stop crawling your site. DNS resolution tells you when your DNS server didn't recognize your host name or didn't respond during crawling. If you see an issue here, check with your register  

#### [0:06:30](https://www.youtube.com/watch?v=x_GoMrl6_u0&t=390) |  to make sure your site is correctly

set up and that your server is properly connected to the internet. Server connectivity tells you when your server was unresponsive or did not provide the full response for your URL during a crawl. If you're seeing spikes or consistent connectivity issues here, you might need to talk to your provider about increasing your capacity or fixing availability issues. If Google found at least one of those errors  

![](https://i.ytimg.com/vi/x_GoMrl6_u0/maxres3.jpg)



#### [0:07:00](https://www.youtube.com/watch?v=x_GoMrl6_u0&t=420) |  on your site in the last week,

you will find a warning alerting you of problems last week. Dig deeper into the error and fix it. If Google found at least one error on your site in the last 90 days, but it occurred more than a week ago, you will see a warning that you had problems in the past. You should check your server logs or contact the developer to review what the problems were and decide whether you need to take any action. If Google didn't find any crawl availability  

#### [0:07:30](https://www.youtube.com/watch?v=x_GoMrl6_u0&t=450) |  issues on your site in the past

90 days, you're all green. Good job. The crawl request cards show several breakdowns to help you understand what Google crawlers found in your website. There are four available breakdowns. Crawl response shows the responses that Google received when crawling your site. Common response types would be 200, 301, 404 or server errors.  

#### [0:08:00](https://www.youtube.com/watch?v=x_GoMrl6_u0&t=480) |  Crawl file type shows file types returned

by the request. Common file types would be HTML, image, video or JavaScript. Crawl purpose could be discovery when a URL is new to Google, or refresh for a re-crawl of a known page. And Google type shows the user agent used by Google to make the crawl request. For example, smartphone, desktop, image, and others. Click any row to drill down to that value  

#### [0:08:30](https://www.youtube.com/watch?v=x_GoMrl6_u0&t=510) |  and review its strengths and specific sample

URLs. Check out the Help Center article about the Crawl Stats report to learn more details about it. To recap, crawl budget is the number of URLs Google can and wants to crawl on websites every day. It is relevant to large websites where Google needs to prioritize what to crawl first, how much to crawl, and how frequently to re-crawl.  

#### [0:09:00](https://www.youtube.com/watch?v=x_GoMrl6_u0&t=540) |  To help you understand and optimize Google's

crawling, you should use the Search Console Crawl Stats report. Use the summary page chart to analyze crawling volume and trends. Use the host status details to check your site's general availability. And use the crawl request breakdown to understand what Googlebot is finding when crawling your website. And make sure to check my Search Console training YouTube series to learn more about how to use the product to succeed on Search.  

#### [0:09:30](https://www.youtube.com/watch?v=x_GoMrl6_u0&t=570) |  [MUSIC PLAYING] That's all the crawling I'm

doing today. Stay tuned. [MUSIC PLAYING]  