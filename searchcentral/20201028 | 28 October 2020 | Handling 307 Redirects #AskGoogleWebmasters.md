[![Handling 307 Redirects #AskGoogleWebmasters](https://i.ytimg.com/vi/zb5ZVfS9Lyo/maxresdefault.jpg)](https://www.youtube.com/watch?v=zb5ZVfS9Lyo)

## Handling 307 Redirects #AskGoogleWebmasters

In this episode of Ask Google Webmasters, John Mueller discusses how a Googlebot interacts with HSTS /307s. The question was submitted by @getvisible. Thank you!



HTTP Strict Transport Security → https://goo.gle/35tQMUA 



Send us your questions on Twitter with the hashtag AskGooglebot and your question might be answered! 

Google Search Central on Twitter → https://goo.gle/3f4Z0a8



Watch more AskGooglebot episodes → https://goo.gle/2OjWcvS

Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



![](https://i.ytimg.com/vi/zb5ZVfS9Lyo/maxres1.jpg)



#### [0:00:00](https://www.youtube.com/watch?v=zb5ZVfS9Lyo&t=0) |  [MUSIC PLAYING] JOHN MUELLER: Today's question is

from Lee McCoy. And Lee asks, how does Googlebot interact with HSTS /307s? Well, in short, it doesn't interact with them. 307 redirects are generally not real redirects. So what does that mean? Well, when you make a site HTTPS, you can optionally use HSTS. HSTS tells users to only get the HTTPS version of a page.  

![](https://i.ytimg.com/vi/zb5ZVfS9Lyo/maxres2.jpg)



#### [0:00:30](https://www.youtube.com/watch?v=zb5ZVfS9Lyo&t=30) |  So when a user enters a URL

or clicks on a link that would otherwise go to HTTP, the browser remembers the HSTS and goes directly to the HTTPS version. To make it clear what's happening, it acts like there was a redirect. Chrome causes a 307 redirect. So if you use Chrome, and you see a 307 result code with a tool, it's not really there. When it comes to Googlebot, we try to crawl URLs  

![](https://i.ytimg.com/vi/zb5ZVfS9Lyo/maxres3.jpg)



#### [0:01:00](https://www.youtube.com/watch?v=zb5ZVfS9Lyo&t=60) |  with a fresh slate. So we wouldn't

keep the HSTS lists and rather, just directly access the HTTP URL directly. If that URL redirects, which is usually the case with an HTTP and HTTPS site, we would follow that. So, in short, Googlebot doesn't see the 307 that you'd see in a browser, and that's fine. I hope I got all the HTTPS and HSTS's is right, and I'll see you in the next episode.  

#### [0:01:30](https://www.youtube.com/watch?v=zb5ZVfS9Lyo&t=90) |  [TONE] --which is usually the case with

an HTTP. I hope I've got all the HTTPS and HSTS's right. I hope I got all the HE-- [EXHALES] [MUSIC PLAYING]  