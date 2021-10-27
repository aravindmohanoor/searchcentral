[![Removing content from Google | WMConf Lightning Talks](https://i.ytimg.com/vi/wp38JZPgJgI/maxresdefault.jpg)](https://www.youtube.com/watch?v=wp38JZPgJgI)

## Removing content from Google | WMConf Lightning Talks

Daniel Waisberg, Search Advocate at Google, goes over different ways to remove content from Google Search including the Search Console Removals tool, permanent removals, and other solutions.



Remove information from Google (general) → https://goo.gle/remove  

Search Console Removals tool → https://goo.gle/2QFVgAY   

Removal troubleshooter for Google’s services → https://goo.gle/33I6VEx 

Removal Troubleshooter for third-party pages → https://goo.gle/3mhv2ll 

Remove personal information off Google → https://goo.gle/2wzm4vK 



Watch all WMConf Lightning Talks → https://goo.gle/2VclBJz

Subscribe to the Webmasters Channel → https://goo.gle/Webmasters



#SearchLightningTalks #SearchConsole #GoogleSearch



#### [0:00:00](https://www.youtube.com/watch?v=wp38JZPgJgI&t=0) |  ﻿Hi, I'm Daniel Waisberg, Search Advocate at

Google. Welcome to another Webmaster Conference Lightning Talk. Today, I'll talk about the different ways to remove content from Google Search, including the Search Console Removals tool, permanent removals, and other solutions. This talk will be most relevant to website owners, professional SEOs, or developers. Here we go. ♪ [music] ♪  

#### [0:00:30](https://www.youtube.com/watch?v=wp38JZPgJgI&t=30) |  Removing content from Google can take many

forms. The content may be on your site or somewhere else. And actually, you might want to remove some piece of information from the entire web or just from Google Search. Before I dive in, let me give you a quick overview of what you can and cannot remove. You can remove content from your website fairly quickly and easily. You can remove it from Google or the entire web. You can ask Google to remove content from its properties,  

#### [0:01:00](https://www.youtube.com/watch?v=wp38JZPgJgI&t=60) |  such as YouTube, Blogger, and others if

it violates our policies. You can ask Google to remove content that violates its policies if it lives on someone else's website. But it will be removed only from Google Search results. To decide how to proceed, I think it's helpful to look at this as a decision tree. The first question you need to ask yourself is whether you control the content or not.  

#### [0:01:30](https://www.youtube.com/watch?v=wp38JZPgJgI&t=90) |  That's an important question because if you

do control the content, it's just a matter of using the right tools. The second question you should ask is whether you need to remove it permanently or temporarily. If you need to remove something urgently, you should probably start by submitting a request on Search Console for a temporary removal, then you can work on a permanent solution. I'll talk about both options in a bit.  

![](https://i.ytimg.com/vi/wp38JZPgJgI/maxres1.jpg)



#### [0:02:00](https://www.youtube.com/watch?v=wp38JZPgJgI&t=120) |  Back to the first question. If you

do not control the content, it might be more challenging to remove it. As you can see in the tree, for content hosted on a Google service such as YouTube, Blogger, or Ads, we provide a troubleshooter to help you remove the content. For other websites, the best option is to contact the website owner. But you might still be able to remove the content from Google Search in some special cases. Let's dive into the options and discuss each of them in more detail.  

#### [0:02:30](https://www.youtube.com/watch?v=wp38JZPgJgI&t=150) |  If you want to remove content that

you control from Google Search, we recommend one of three things: return a 404 or 410 HTTP response whenever the content is requested; protect your content with a password, so that it cannot be accessed by Googlebot or others on the web; or use a noindex metatag to indicate that the page should not be indexed. Simply redirecting an old page with a 301 response  

#### [0:03:00](https://www.youtube.com/watch?v=wp38JZPgJgI&t=180) |  or using a robots.txt directive might not

be enough to remove the old content from Google Search results. Again, this is what you should do to remove the content from Search permanently, so be careful. If your intention is just to hide the page until you fix it, you should use Search Console to do so. A temporary removal request is a way to quickly remove content on your site from Google Search results.  

#### [0:03:30](https://www.youtube.com/watch?v=wp38JZPgJgI&t=210) |  A successful request lasts only about six

months, which should be enough for you to find a solution to either allow the content to be seen or to remove it permanently. In other words, such a request will only hide the pages from Search results, but they'll still be crawled and indexed and will reappear when the request expires. Before I show you how to submit a request, I want to highlight some things that you should not use this tool for.  

![](https://i.ytimg.com/vi/wp38JZPgJgI/maxres2.jpg)



#### [0:04:00](https://www.youtube.com/watch?v=wp38JZPgJgI&t=240) |  Removing a page won't affect if a

page has a manual actions, if your website has been hacked, if you want to tell Google which version of a page you want us to index, if you're moving your site to another domain, or if you want to remove pages that are not helpful or updated. Don't worry, there are solutions to all those issues. Check our Help Center to find how to fix them. But don't use the Removals tool.  

#### [0:04:30](https://www.youtube.com/watch?v=wp38JZPgJgI&t=270) |  When you log into Search Console, you'll

find the Removals report in the navigation bar. Select the Temporary Removals tab, if it's not already selected, to submit a new removal request, then click New Request. You have two options of requests available. Temporarily Remove URL will block the URL from Google Search results for about six months. This will also clear the cached copy of the page. You can also use this option as a quick first step when permanently blocking a page from Google Search results.  

#### [0:05:00](https://www.youtube.com/watch?v=wp38JZPgJgI&t=300) |  Clear Cached URL clears the cached page

and wipes out the page description snippet in Search results until the page is crawled again when the snippet is generated from the new content. Until the next crawl, the page description will be empty in Search results. Use this option when you remove sensitive information from a page and want to update your results snippet in Google Search without removing the page itself from Search.  

#### [0:05:30](https://www.youtube.com/watch?v=wp38JZPgJgI&t=330) |  Be sure that you've removed the sensitive

information from your page before clicking this. Or else, Google will just re-crawl the page and find the same content. For each of these two options, you can submit a request for a single, specific URL or for an entire URL prefix. Make sure you think twice before submitting a request for an entire prefix, so that you don't unintentionally block pages that are important to you.  

#### [0:06:00](https://www.youtube.com/watch?v=wp38JZPgJgI&t=360) |  In the temporary removal section, you'll find

the summary of the page removals requested through this report in the past six months. You'll see the URL, the request type, the date requested, and the status. You can also use this report to cancel a request if it's no longer necessary. Now, what if you don't control the content? Let's go through your options. If the content you want to remove lives on a Google-owned service,  

![](https://i.ytimg.com/vi/wp38JZPgJgI/maxres3.jpg)



#### [0:06:30](https://www.youtube.com/watch?v=wp38JZPgJgI&t=390) |  we might be able to help. You'll

find the link in the description to a troubleshooter to help you report content that you would like removed from Google services. Provide as much information as you can to help us investigate and, if applicable, the information will be removed. You'll need to submit separate notices for each Google service where the content appears. To remove content from the web, which you don't control and is not hosted on a Google service,  

#### [0:07:00](https://www.youtube.com/watch?v=wp38JZPgJgI&t=420) |  your best option is to contact the

owner of the website to request for the content to be removed. Try sending a message via the contact link that is usually available in websites. You can also try to find the website owner's email through a Google Search including whois www.example.com. For information on that, check out the removal troubleshooter for third-party pages linked in the description.  

#### [0:07:30](https://www.youtube.com/watch?v=wp38JZPgJgI&t=450) |  With that said, there are ways to

remove the content from Google Search. You'll find more info about them in the troubleshooter. Here are some examples of information Google might take off Search results: copyright and other legal removals; child sexual abuse content; nonconsensual, explicit, or intimate personal images; involuntary fake pornography; financial, medical, and national ID information; and more.  

#### [0:08:00](https://www.youtube.com/watch?v=wp38JZPgJgI&t=480) |  Again, check the links in the description

to learn more. That's it. To recap, if you'd like to remove content from Google or from the web in general, you need to ask yourself two important questions: who controls the content and do I need to remove the content permanently or just for a period? With these questions, you can find the best approach to remove content from Google or the web.  

#### [0:08:30](https://www.youtube.com/watch?v=wp38JZPgJgI&t=510) |  If you like this video, check out

the Search Console training series in the Google Webmaster YouTube channel. You'd love it. Stay tuned. ♪ [music] ♪  