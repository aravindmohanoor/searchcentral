[![Mobile-First Indexing | WMConf Lightning Talks](https://i.ytimg.com/vi/TTUzxHdx2jY/maxresdefault.jpg)](https://www.youtube.com/watch?v=TTUzxHdx2jY)

## Mobile-First Indexing | WMConf Lightning Talks

Martin Splitt, Search Advocate at Google, goes over how mobile-first indexing works, challenges that can occur with mobile-first indexing on one’s website, and best practices to avoid these. Watch this lightning talk to better prepare for when Google switches to mobile-first indexing for all websites later next year!



Mobile-first indexing best practices → https://goo.gle/2HayU5I 

Prepare for mobile-first indexing (with a little extra time) → https://goo.gle/2DFgISI 



Watch all WMConf Lightning Talks → https://goo.gle/2VclBJz

Subscribe to the Google Search Central channel → https://goo.gle/SearchCentral



#SearchLightningTalks #webdev #SEO #indexing



#### [0:00:00](https://www.youtube.com/watch?v=TTUzxHdx2jY&t=0) |  MARTIN SPLITT: Hello, and welcome to the

Webmaster Conference Lightning Talk series. This time, we will talk about mobile-first indexing. [MUSIC PLAYING] As many of you may already know, mobile-first indexing is an ongoing effort by Google for several years. So what is mobile-first indexing, exactly? Let's look at how Google indexing works. First, Googlebot will crawl URLs from your site with the desktop and mobile user agent.  

#### [0:00:30](https://www.youtube.com/watch?v=TTUzxHdx2jY&t=30) |  With the original desktop-first indexing, the indexing

system will get the page information from the desktop page content. Finally, the page will be shown in the search results if the information has enough relevance for user queries. With mobile-first indexing, the indexing system will look at the mobile page instead of the desktop page for information. Well, now that we know the difference between desktop-  

#### [0:01:00](https://www.youtube.com/watch?v=TTUzxHdx2jY&t=60) |  and mobile-first indexing, what challenges can occur

where there's mobile-first indexing on your site? One possibility is that something's going wrong when we crawl with the mobile Googlebot. The request might be treated differently by your server based on the user agent, or something else might be going wrong when making a request to the mobile pages. Then if that happens, there will be little to no information  

![](https://i.ytimg.com/vi/TTUzxHdx2jY/maxres1.jpg)



#### [0:01:30](https://www.youtube.com/watch?v=TTUzxHdx2jY&t=90) |  that we can get from your pages.

And if that happens, we can't get the necessary signals to show your page in the search results. Another possibility is that your mobile page is having content issues. We might get less or maybe even incorrect information from your page, which results in us getting less information about the page's relevance. Both situations will prevent Google from serving your site well when your site is enabled  

#### [0:02:00](https://www.youtube.com/watch?v=TTUzxHdx2jY&t=120) |  for mobile-first indexing. Now, that is something

that you probably want to avoid. So how can you avoid issues like that? For example, you may have put the following rule in robots.txt under your mobile site. It tells Google about not to crawl pages under your mobile version. Or if you add any of these meta tags on your mobile pages, they tell Googlebot not to index these pages.  

#### [0:02:30](https://www.youtube.com/watch?v=TTUzxHdx2jY&t=150) |  Those settings will prevent Googlebot from either

crawling or indexing these pages, so please don't set any of the mobile pages you expect to appear in Google Search up like that. For another example, if you put the following rule in robots.txt under your resources host, it tells Google not to crawl any files under mobile-css. If you add any of these meta tags on the mobile pages,  

#### [0:03:00](https://www.youtube.com/watch?v=TTUzxHdx2jY&t=180) |  they would tell Googlebot not to follow

any of the links on these pages. Those settings will prevent Googlebot from crawling the resources. If you let Googlebot crawl resources for your desktop page, you should probably also let it crawl them for your mobile page. Otherwise, it cannot understand your mobile page as well as your desktop page. To conclude, for mobile crawl issues, you need to check your robots.txt files,  

![](https://i.ytimg.com/vi/TTUzxHdx2jY/maxres2.jpg)



#### [0:03:30](https://www.youtube.com/watch?v=TTUzxHdx2jY&t=210) |  and you also want to be careful

with noindex and nofollow tags for indexing issues. Please also check if your hosts have enough crawl capacity to handle as many mobile crawls as they handle desktop crawls. Setting mobile-page content correctly is as important as setting the mobile crawler correctly. Our general suggestion is to make sure your primary content is the same on desktop and mobile versions. Let's look at some cases where it might not be the same.  

#### [0:04:00](https://www.youtube.com/watch?v=TTUzxHdx2jY&t=240) |  Let's say you have a desktop page

that looks like this with several images, and some text. But then you make your mobile version look like this with only two images and very few text. Users need to click the Plus button to let the rest of the page load. However, Googlebot won't click the button to load them, so all of the unloaded information is invisible to Google. And a special note-- if it's your intention to have less  

#### [0:04:30](https://www.youtube.com/watch?v=TTUzxHdx2jY&t=270) |  content on the mobile page, please be

aware that Google might not be able to serve your site as well as before mobile-first indexing. That is because we cannot get the full information from your site as we did before. Headings are also important for Googlebot to understand your page. This is a good example of a heading. It uses the good old h1 tag. Well, this is not a good example. Regardless of its class, Googlebot will treat it as if it is normal text rather than a heading.  

#### [0:05:00](https://www.youtube.com/watch?v=TTUzxHdx2jY&t=300) |  It will then affect how Googlebot understands

the page. So don't forget to use semantic heading tags on your mobile pages. If you also care about image and video traffic of your site, you need to do some extra checks for them. For example, this is a good example on how to define an image, while this is not. Because the alt text is empty, it will be a bad experience for some users.  

![](https://i.ytimg.com/vi/TTUzxHdx2jY/maxres3.jpg)



#### [0:05:30](https://www.youtube.com/watch?v=TTUzxHdx2jY&t=330) |  Neither is this one because the alt

text is not meaningful. People don't know what the image is about just looking at the alt text. So please don't do that. Also, don't do it this way either. That's not even a semantic image tag. Googlebot cannot index CSS images like that. For images and videos, another important thing is to check their position on the page. Let's say you have a desktop page like this,  

#### [0:06:00](https://www.youtube.com/watch?v=TTUzxHdx2jY&t=360) |  with the video as an easy-to-see position,

while on the mobile page, you put an ad on the top of the page like this. Users need to scroll down a lot to finally see the video here. Imagine what they will feel like if they were only searching for the video. So please don't let your mobile pages have such a bad user experience. Finally, it is better to do some extra checks for invisible parts of your page. They won't affect user experience, but they will affect how Googlebot understands them.  

#### [0:06:30](https://www.youtube.com/watch?v=TTUzxHdx2jY&t=390) |  One such example of an invisible part

of the page is structured data. We suggest you keep structured data the same on desktop and mobile pages. The other one are meta descriptions. Please don't forget to add them to your mobile pages. They matter a lot for Googlebot as well. If you want to learn more about mobile-first indexing, check out the video description for more information, and follow us on Twitter @GoogleWMC to stay  

#### [0:07:00](https://www.youtube.com/watch?v=TTUzxHdx2jY&t=420) |  tuned with more on the journey to

mobile-first indexing. Thank you very much for watching. Have a great day. [MUSIC PLAYING]  