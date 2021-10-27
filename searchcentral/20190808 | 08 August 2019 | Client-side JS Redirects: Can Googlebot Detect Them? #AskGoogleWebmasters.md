[![Client-side JS Redirects: Can Googlebot Detect Them? #AskGoogleWebmasters](https://i.ytimg.com/vi/_SDIN0KiQp4/maxresdefault.jpg)](https://www.youtube.com/watch?v=_SDIN0KiQp4)

## Client-side JS Redirects: Can Googlebot Detect Them? #AskGoogleWebmasters

In this episode of Ask Google Webmasters, John Mueller discusses whether or not Google Search can detect client-side JavaScript redirects and how Googlebot uses Chromium for rendering (a question submitted by @YesImVini). 



JavaScript indexing for Search → https://goo.gle/2VIh8Qs 



Send us your questions on Twitter with the hashtag AskGooglebot and your question might be answered! 

Google Search Central on Twitter → https://goo.gle/3f4Z0a8



Watch more AskGooglebot episodes → https://goo.gle/2OjWcvS

Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=_SDIN0KiQp4&t=0) |  [MUSIC PLAYING] JOHN MUELLER: Hi, everyone, John

Mueller here with another episode of "Ask Google Webmasters," a video series In which we answer your questions about Google Search and websites. Today's question is from YesImVini, who is asking, can Google Evergreen Chromium detect client-side JavaScript redirects. I'm not able to submit Google search console, indexing requests to pages that have client-side JavaScript  

![](https://i.ytimg.com/vi/_SDIN0KiQp4/maxres1.jpg)



#### [0:00:30](https://www.youtube.com/watch?v=_SDIN0KiQp4&t=30) |  redirects to a subscription page. Thank you

for all your questions. But first, let me back up a bit and explain where some of that comes from before diving into the question itself. Googlebot is what we use to crawl the web to find public and crawlable pages that we can include in our search results. Over the years, we've started using a version of Chrome to do a part of that, to make sure that we can see what users would see  

#### [0:01:00](https://www.youtube.com/watch?v=_SDIN0KiQp4&t=60) |  when they use their browsers to view

those pages. Until earlier this year, we were using a special, older version of Chrome for that. And now we've started using a recent version of Chrome. And we're updating that automatically over time. A browser that's kept updated automatically is often called an evergreen browser. So essentially when we talk about Evergreen Googlebot, we're saying that it's rendering with the recent version of Chrome, similar to what you'd have on your computer as well.  

![](https://i.ytimg.com/vi/_SDIN0KiQp4/maxres2.jpg)



#### [0:01:30](https://www.youtube.com/watch?v=_SDIN0KiQp4&t=90) |  By using redirects, you're telling us that

you'd prefer to have a different URL, or at least the contents of a different URL indexed. We support JavaScript redirects of different types, and follow them similar to how we'd follow server-side redirects. JavaScript redirects are important for, well, unsurprisingly, JavaScript-based sites, which we also work hard to support. All that said, submitting a URL for indexing that redirects  

![](https://i.ytimg.com/vi/_SDIN0KiQp4/maxres3.jpg)



#### [0:02:00](https://www.youtube.com/watch?v=_SDIN0KiQp4&t=120) |  doesn't really make much sense for indexing

since the redirect tells us you'd prefer to have the other URL indexed. So my recommendation would be to submit the URL that you'd like to have indexed instead. Or even better, make sure that we can discover those URLs automatically. For example, if this URL is linked properly within your website, you'll discover it through our normal crawling anyway. You can also help us to pick up changes a bit faster by using a site map file.  

#### [0:02:30](https://www.youtube.com/watch?v=_SDIN0KiQp4&t=150) |  I hope this helps to clear up

some of the questions here. If you have further questions about how Google uses JavaScript and Search, make sure to check out our developer documentation linked in the description below. And if you want to ask us a different question, don't forget to use the hashtag AskGoogleWebmasters on Twitter. [MUSIC PLAYING]  