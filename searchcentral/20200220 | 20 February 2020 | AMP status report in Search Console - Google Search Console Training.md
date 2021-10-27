[![AMP status report in Search Console - Google Search Console Training](https://i.ytimg.com/vi/n2mrpZLTtug/maxresdefault.jpg)](https://www.youtube.com/watch?v=n2mrpZLTtug)

## AMP status report in Search Console - Google Search Console Training

In this episode of Search Console Training, Daniel Waisberg goes over how to use Google Search Console to improve your AMP implementation. Find out more about AMP, why you should use it, how using it can benefit you in Google Search, and how to detect (and fix) issues with AMP in your website through Search Console.



AMP status report → https://goo.gle/2Out8PU 

Understand how AMP looks in search results → https://goo.gle/383rRqU 

AMP test tool → https://goo.gle/2OtwHGb 



Watch more Search Console Training videos → https://goo.gle/sct

Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=n2mrpZLTtug&t=0) |  Hi, I'm Daniel Waisberg, Search Advocate at

Google. And today, I'll talk about how to use Search Console to improve your AMP implementation. By the end of this video, you should be able to find AMP issues Google discovered in your website, fix them, and ask Google to validate your fixes. ♪ [music] ♪ Before I discuss the Search Console reports, I would like to give a quick intro to AMP,  

#### [0:00:30](https://www.youtube.com/watch?v=n2mrpZLTtug&t=30) |  just in case you're not familiar with

it. AMP, or Accelerated Mobile Pages, is an open-source HTML framework that provides a straightforward way to create web pages that are fast, smooth-loading, and prioritize the user experience. It can be used to easily create websites, stories, ads, and more. There are several reasons to use the AMP framework. Web page speed improves the user experience  

#### [0:01:00](https://www.youtube.com/watch?v=n2mrpZLTtug&t=60) |  and core business metrics, building AMP pages

is simple and reduces developer overhead, AMP has lots of components that can be used as website building blocks and they are already optimized for best performance. Besides the general benefits of the AMP framework, there are additional benefits for AMP on Google Search, such as serving from the Google cache, and more opportunities to appear in AMP-related experiences. If you want to learn more about how AMP looks  

![](https://i.ytimg.com/vi/n2mrpZLTtug/maxres1.jpg)



#### [0:01:30](https://www.youtube.com/watch?v=n2mrpZLTtug&t=90) |  in Google Search results, check our developer

documentation linked in the video description. When Google detects AMP on your website, you'll see a report in Search Console detailing any AMP issues that Google found on your pages. That can be really handy when reviewing your AMP implementation. It will help you focus your efforts on the most important tasks. The top level view shows crawled AMP pages with any issues found by Google. The default chart shows the trends for AMP errors,  

#### [0:02:00](https://www.youtube.com/watch?v=n2mrpZLTtug&t=120) |  but you can click Valid with warnings

and Valid to see their trends too. In addition, you will see a checkbox to add the number of impressions your AMP pages got on Search. This can be very helpful to understand how issues affect your results. Below the chart, you'll find a table with issues grouped by type. AMP pages that show an error cannot be shown in search results. For example, your AMP page is blocked by robots.txt,  

#### [0:02:30](https://www.youtube.com/watch?v=n2mrpZLTtug&t=150) |  custom JavaScript is not allowed, or the

HTML tag has an invalid layout specified by its attributes. AMP pages with warnings are indexed and can be shown in Google Search results. But they might not be shown in AMP rich results, or the top stories carousel. Warnings include non-optimal pages or use of deprecated features that may become errors in the future. Valid AMP pages work as expected for users  

#### [0:03:00](https://www.youtube.com/watch?v=n2mrpZLTtug&t=180) |  and can be included in AMP-related features.

So, if everything is green, it means you're doing a great job. By default, issues are sorted by a combination of severity, validation state, and number of pages affected. If you see an error that seems like a result of a bad template, fix it first. Then continue fixing other issues that are unique to each page. Click a specific issue to see more details, with a link to learn more about how to fix it  

![](https://i.ytimg.com/vi/n2mrpZLTtug/maxres2.jpg)



#### [0:03:30](https://www.youtube.com/watch?v=n2mrpZLTtug&t=210) |  and the process to notify Google about

your fixes, which I'll talk about in a minute. You'll also find the list of example URLs affected by this issue. You can click a specific URL to find the HTML and exact location of the offending code. If you want to see a full list of errors for a specific URL that is shown in the report, click the Inspect icon next to the URL. This will open the URL Inspection, already discussed in this video series.  

#### [0:04:00](https://www.youtube.com/watch?v=n2mrpZLTtug&t=240) |  This test pinpoints all errors, not just

the current issue, and provides a code explorer highlighting the errors and providing more information. It is possible that an error has been fixed in the live page but is still listed as an error because it has not been recrawled. You can check that by testing the live version of your page in the URL Inspection results. If that's the case, request validation through the AMP issue page.  

#### [0:04:30](https://www.youtube.com/watch?v=n2mrpZLTtug&t=270) |  Now that you know what needs to

be fixed, you have two options: make the required code changes yourself, or share the details with a developer that can perform code changes to your website. You can do that by grabbing a link using the Share button from any issue page. Note that the sharing link grants access only to the current page, plus any validation history pages for this issue. It does not grant access to other pages for your resource,  

#### [0:05:00](https://www.youtube.com/watch?v=n2mrpZLTtug&t=300) |  or enable the shared user to perform

any actions on your property or account. You can revoke the link at any time by disabling sharing for this page. It might also be a good idea to use the AMP test tool, where in addition to testing a specific page, you can also upload a piece of code to check for issues. This can be helpful to debug issues for new pages. But note that the tool will check your general AMP implementation without specific information about Google indexing.  

![](https://i.ytimg.com/vi/n2mrpZLTtug/maxres3.jpg)



#### [0:05:30](https://www.youtube.com/watch?v=n2mrpZLTtug&t=330) |  After you or your developer fix the

error, confirm the fix by inspecting the live version of the page. Then, click Validate Fix from the AMP issue page and Google will validate your changes. The validation process can take several days and you will receive progress notifications by email. If the current instance exists in a sample of pages, validation ends,  

#### [0:06:00](https://www.youtube.com/watch?v=n2mrpZLTtug&t=360) |  and the validation state remains unchanged. If

the sample pages do not have the current error, validation continues with state Started. When all error or warning URLs have been checked and the issue count is zero, the issue state changes to Passed. You can see the progress of a validation request by clicking the validation details link in the issue details page. To learn more about the AMP issues on their pages, missing pages troubleshooting, validation stages,  

#### [0:06:30](https://www.youtube.com/watch?v=n2mrpZLTtug&t=390) |  and other details about this report, visit

the Search Console Help Center. I hope this video helped you understand how to optimize your website by improving AMP warnings and errors. Your users will thank you for that. In the next episode, I'll talk about how to use Search Console to submit sitemaps to Google, how to review your sitemap submission history, and how to find errors that Google encountered when parsing your submitted sitemaps.  

#### [0:07:00](https://www.youtube.com/watch?v=n2mrpZLTtug&t=420) |  ♪ [music] ♪ Don't forget to subscribe

to the Google Webmasters Youtube channel, where we'll be publishing lots of Search Console videos. Stay tuned. ♪ [music] ♪ This is Webby, this is Ampy, they're going for a run. [as Webby] Wait for me, Ampy! Ah!  