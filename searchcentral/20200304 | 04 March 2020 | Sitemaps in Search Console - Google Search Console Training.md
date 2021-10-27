[![Sitemaps in Search Console - Google Search Console Training](https://i.ytimg.com/vi/JlamLfyFjTA/maxresdefault.jpg)](https://www.youtube.com/watch?v=JlamLfyFjTA)

## Sitemaps in Search Console - Google Search Console Training

In this episode of Search Console Training, Daniel Waisberg gives a brief overview of the sitemaps report in Search Console. Find out more about what a sitemap is, decide whether you need one or not, and learn how to submit a sitemap and track its status using Search Console.



Managing sitemaps→ https://goo.gle/399Xj7v 

Check out John Mueller’s series Ask Google Webmasters → https://goo.gle/2OjWcvS 



Watch more Search Console Training videos → https://goo.gle/sct

Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=JlamLfyFjTA&t=0) |  Hi, I'm Daniel Waisberg, Search Advocate at

Google. And today, I'll talk about how to use the Search Console sitemaps report. By the end of this video, you should be able to understand what a sitemap is, decide whether you need one or not, and learn how to submit a sitemap and track its status using Search Console. ♪ [music] ♪ A sitemap is a signal about which URLs you would like Google to crawl  

#### [0:00:30](https://www.youtube.com/watch?v=JlamLfyFjTA&t=30) |  on your site. It may provide information

on URLs that were recently created or modified, and give us some extra information about them. Google supports four main ways for you to provide additional information. You can extend a URL with images included in it, you can also extend a URL with videos included in it, you can include information about alternate languages or country versions with hreflang annotations,  

#### [0:01:00](https://www.youtube.com/watch?v=JlamLfyFjTA&t=60) |  and, finally, for news sites, you can

use a special variation of sitemaps, to give us information about the most recent updates. Note that this information won't necessarily be highlighted on Search Console. But you can still provide it in your sitemap. But if I don't have a sitemap, will Google find all my pages? I'm glad you asked, John. Usually, if you have a relatively small website, and your pages are properly linked,  

![](https://i.ytimg.com/vi/JlamLfyFjTA/maxres1.jpg)



#### [0:01:30](https://www.youtube.com/watch?v=JlamLfyFjTA&t=90) |  Googlebot can discover your content. So, you

don't need to worry about the sitemap. However, if your site meets one of the following criteria, a sitemap might help Google decide what and when to crawl your website. If your site is really large, a sitemap will help Google prioritize the URLs to crawl. If your pages are isolated, or not well linked to each other, a sitemap might help Google find those pages. If your site is new, or it has a lot of quickly changing content,  

#### [0:02:00](https://www.youtube.com/watch?v=JlamLfyFjTA&t=120) |  such as a news website, a sitemap

will help Google discover your content. Please, remember, that using a sitemap doesn't guarantee that all your pages will be crawled and indexed. But in most cases, your site will benefit from having a sitemap. And there is no disadvantage for having one. In addition, sitemaps don't replace normal crawling. And not including URLs in a sitemap, won't result in those URLs no longer being crawled.  

#### [0:02:30](https://www.youtube.com/watch?v=JlamLfyFjTA&t=150) |  Hmm... interesting. I might need a sitemap.

But how can I create one? Another great question, John. Ideally, the system running your website will make sitemap files for you, automatically. For example, you can find a WordPress plug-in, or a Drupal extension if you use those content management systems. Check the documentation from your provider, as every platform is slightly different. We recommend finding a way to automatically generate sitemaps,  

#### [0:03:00](https://www.youtube.com/watch?v=JlamLfyFjTA&t=180) |  rather than creating them manually. Usually, this

will involve running code on your server, so if you're not a developer, you might need help from one. There are limits to the number of URLs and the maximum size of a sitemap file. If you need more space, you can make multiple sitemap files. You can also submit all of these sitemap files together, in the form of an index sitemap file. Doing that makes it a bit easier to track them all together in one place.  

![](https://i.ytimg.com/vi/JlamLfyFjTA/maxres2.jpg)



#### [0:03:30](https://www.youtube.com/watch?v=JlamLfyFjTA&t=210) |  To learn more about sitemap's formats and

guidelines, check our Help Center. Before I go into Search Console, please note that the sitemaps report shows only sitemaps that you submitted using Search Console. It does not show any sitemaps discovered through a robot.txt reference or other discovery methods. However, even if we already discovered a sitemap through other means, you can still submit it using this report, in order to track errors and warnings.  

#### [0:04:00](https://www.youtube.com/watch?v=JlamLfyFjTA&t=240) |  So, let's look at the report. Open

Search Console and find the sitemaps report. If you have already submitted one  or more sitemaps, you'll find the following information about each sitemap that you submitted: the sitemap URL; the type or format of sitemaps, such as XML, TXT, RSS, or Atom; the last submission date using this report; the date it was last read by Google;  

#### [0:04:30](https://www.youtube.com/watch?v=JlamLfyFjTA&t=270) |  the crawl status such as Success, Has

errors, Couldn't fetch, and others; the number of URLs discovered in the sitemap. You will note an icon next to each successful sitemap. Clicking it will lead you to the index coverage status report for the specific sitemap. I'll talk about this report in the next episode. But sitemaps can also be partially read, even if they have errors. If your sitemap status is Success,  

![](https://i.ytimg.com/vi/JlamLfyFjTA/maxres3.jpg)



#### [0:05:00](https://www.youtube.com/watch?v=JlamLfyFjTA&t=300) |  good job! If you have any errors

in the status column, click the specific row to see more details. You'll find a complete list of errors, and what to do in each case in the Search Console Help Center. If you want to submit a new sitemap, simply open the sitemaps report, and submit the URL. You will need owner permission for a property in order to submit it. If you submitted a sitemap but it's not relevant anymore,  

#### [0:05:30](https://www.youtube.com/watch?v=JlamLfyFjTA&t=330) |  you can delete it from Search Console.

But know that deleting a sitemap, removes it from this report, but doesn't make Google forget the sitemap or any URLs listed on it. In order for Google to forget the sitemap, just remove it from your site and return a 404. After some attempts, Google will give up and completely stop refreshing the sitemap. But this has nothing to do with the URLs in the sitemap. If you truly need Google to stop visiting the URLs listed in a sitemap,  

#### [0:06:00](https://www.youtube.com/watch?v=JlamLfyFjTA&t=360) |  you will need to return a 404

or use a robot.txt rule for the URLs that you want to block. This is what you would do in order for Google to stop crawling this page. If your goal is to remove the URL from the Google index altogether, you should either use the noindex directive or require HTTP authentication for users to see your page. I hope this video helped you understand when you should use a sitemap, and how Search Console can help you.  

#### [0:06:30](https://www.youtube.com/watch?v=JlamLfyFjTA&t=390) |  In the next episode, I'll talk about

how to use Search Console to check which of your pages have been indexed, and any problems found during that process. And, by the way, check out the Ask Google Webmasters series, where John Mueller, our guest star today, actually answers lots of questions submitted by the Webmaster community. And don't forget to subscribe to the Google Webmasters YouTube channel, where we'll be publishing lots of Search Console videos. So, stay tuned. ♪ [music] ♪  

#### [0:07:00](https://www.youtube.com/watch?v=JlamLfyFjTA&t=420) |  Junior, what are you doing there? That's

not a sitemap! [woman laughs]  