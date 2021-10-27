[![AJAX Crawling & Hash-bang URLs #AskGoogleWebmasters](https://i.ytimg.com/vi/kDs-MufuiAg/maxresdefault.jpg)](https://www.youtube.com/watch?v=kDs-MufuiAg)

## AJAX Crawling & Hash-bang URLs #AskGoogleWebmasters

In this episode of Ask Google Webmasters, John Mueller discusses the current status of AJAX crawling, hash-bang URLs, and how one moves to a different URL structure.



Initial announcement, for those interested in history → https://goo.gle/2kzyuxQ 

Deprecation notice → https://goo.gle/2lMVIRl 

Rendering of #! Pages → https://goo.gle/2kAIKWD 



Send us your questions on Twitter with the hashtag AskGooglebot and your question might be answered! 

Google Search Central on Twitter → https://goo.gle/3f4Z0a8



Watch more AskGooglebot episodes → https://goo.gle/2OjWcvS

Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



![](https://i.ytimg.com/vi/kDs-MufuiAg/maxres1.jpg)



#### [0:00:00](https://www.youtube.com/watch?v=kDs-MufuiAg&t=0) |  [MUSIC PLAYING] JOHN MUELLER: Today, let's talk

about AJAX crawling. Oleg is asking, what's the current status of hashbang AJAX crawling, and how do I set up redirects Allow me to dwell in the mists of history a little bit. The AJAX crawling scheme was something we proposed in the early days of JavaScript sites way back in 2009, so about 10 years ago, or one third of the way back towards the invention of the web back in 1989.  

![](https://i.ytimg.com/vi/kDs-MufuiAg/maxres2.jpg)



#### [0:00:30](https://www.youtube.com/watch?v=kDs-MufuiAg&t=30) |  That was a really long time ago,

and apparently people are still using the AJAX crawling scheme. Who would have thought? Well, this worked great for a number of years, but over time, it became kind of redundant. Search engines, or at least Google, had learned how to render most pages like a browser would and, in the meantime, were even using a special version of Chrome for crawling and rendering. In short, for Google, you no longer need to do anything special for hashbang URLs.  

![](https://i.ytimg.com/vi/kDs-MufuiAg/maxres3.jpg)



#### [0:01:00](https://www.youtube.com/watch?v=kDs-MufuiAg&t=60) |  We'll just try to render them directly.

In order to move to a different URL structure, you need to use JavaScript on these pages to create the redirects. It's not possible to use server-side redirects, since everything after a hash, so the number symbol, is not sent to the server, but rather processed in the browser. Once you've set up those redirects, as Googlebot re-processes the hashbang URLs on the site, it'll spot the redirect and follow it appropriately.  

#### [0:01:30](https://www.youtube.com/watch?v=kDs-MufuiAg&t=90) |  I hope this has answered your question,

Oleg. There are more episodes of "Ask Google Webmasters" coming to the Google Webmasters YouTube channel. So I'd recommend subscribing to the channel to get notified whenever there's a new video. Until the next episode. [MUSIC PLAYING]  