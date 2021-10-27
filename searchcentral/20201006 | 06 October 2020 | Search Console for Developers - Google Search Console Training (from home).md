[![Search Console for Developers - Google Search Console Training (from home)](https://i.ytimg.com/vi/Z3dHWPXFfPo/maxresdefault.jpg)](https://www.youtube.com/watch?v=Z3dHWPXFfPo)

## Search Console for Developers - Google Search Console Training (from home)

Search Console Training is back! In the first episode recorded from home, Daniel Waisberg goes over how developers can benefit from using Search Console. Stay tuned to learn more about the importance of Index Coverage report, URL Inspection tool, Security Issues report, and the Core Web Vitals report for developers building websites optimized for search performance.



Index Coverage report → https://goo.gle/2ESrHte 

URL Inspection tool → https://goo.gle/2ZrJsp9 

Security Issues report → https://goo.gle/3e9XvGJ 

Core Web Vitals report → https://goo.gle/2SdKke6 

Tools to measure Core Web Vitals → https://goo.gle/3l5xQBN 



Watch more Search Console Training videos → https://goo.gle/sct    

Subscribe to Google Search Central → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=Z3dHWPXFfPo&t=0) |  DANIEL WAISBERG: Hi. I'm Daniel Waisberg, Search

Advocate at Google, and today I'll talk about how to use Search Console if you're a developer. Since the tool provides a lot of information about search optimization, developers may think it's not useful to them, but I beg to differ. In this video, I'll talk about the most useful Search Console reports to help developers build websites that are healthy, findable, and optimized for Google search. In summary, use the Index Coverage Report  

#### [0:00:30](https://www.youtube.com/watch?v=Z3dHWPXFfPo&t=30) |  to understand sitewide search indexing issues. Use

the URL Inspection Tool to debug page level search indexing issues. Use the Security Issues Report to find and fix issues affecting your site, and use the Core Web Vitals Report to make sure your website provides a great page experience for your users. [MUSIC PLAYING] The first thing that is really important for you to know  

#### [0:01:00](https://www.youtube.com/watch?v=Z3dHWPXFfPo&t=60) |  is whether Google can find and crawl

your pages. Small glitches can have a massive effect when it comes to Google bot being able to read websites. For example, sometimes we see companies accidentally adding no index tags to entire websites, or blocking the content from being crawled through an error on their robot.txt file. These issues can be easily uncovered using the Index Coverage Report. When you open the report, the first page you see is the Summary page.  

#### [0:01:30](https://www.youtube.com/watch?v=Z3dHWPXFfPo&t=90) |  The default view shows indexing errors on

your website, but you can click to show valid with warnings, valid, and excluded pages. In addition, you will find a checkbox to add to the main chart the number of impressions your page has got on search. Here's what each status means with some examples. Errors prevent pages from being indexed. Pages with errors won't appear in Google, which can mean a loss of traffic to your website. For example, your page might be returning a 44 or a 500 level  

![](https://i.ytimg.com/vi/Z3dHWPXFfPo/maxres1.jpg)



#### [0:02:00](https://www.youtube.com/watch?v=Z3dHWPXFfPo&t=120) |  error. Additionally, you might get an error

if you submitted a page through a site map, but it contains a no index directive. All these cases would prevent the page from appearing on search results. Valid with warnings are pages that may or may not be shown on Google, depending on the issue, but we think there is a problem you should look into. For example, Google might find pages that are indexed, though blocked by robot.txt.  

#### [0:02:30](https://www.youtube.com/watch?v=Z3dHWPXFfPo&t=150) |  This is marked as a warning because

it's not clear if you intended to block the page from search results. If you do want to block the page, robot.txt is not the best way to avoid being indexed. To do so, you should either use a no index directive or request authentication to see the page. Valid pages have been indexed and can be shown on Google Search, so good job. Excluded pages were not indexed and won't appear in Google. But either we think that is your intention  

#### [0:03:00](https://www.youtube.com/watch?v=Z3dHWPXFfPo&t=180) |  or we think it's the right thing

to do. For example, the page has a no index directive, your choice, or the page is a duplicate of another page, Google's choice. You can watch the Index Coverage episode in this series to understand more about the issues affecting your site and learn how to validate the fix you have implemented. To debug an issue with a specific page, for example, a page Google is showing an error in the Coverage Report, you should use the Inspect URL tool.  

#### [0:03:30](https://www.youtube.com/watch?v=Z3dHWPXFfPo&t=210) |  You can use it to learn the

current index status of your pages, to test the live URL, to ask Google to crawl a specific page, and to view detailed information about the page's loaded resources and other information. You can access the tool from the top bar, from the sidebar, and you'll also see a little magnifying glass next to URLs in some reports. For example, if you drill down to a URL from the Index Coverage Report, you can click to inspect it.  

#### [0:04:00](https://www.youtube.com/watch?v=Z3dHWPXFfPo&t=240) |  Once the page displays the results, you

will see three different sections, all of them presenting information from Google's last crawl or crawl attempt. If you recently made changes to the page, you might want to check if they're working as intended by clicking Test Live URL and comparing the live version to the indexed one. In the presence on Google [? Card, ?] you'll get a verdict on whether or not the URL can appear in Google search results. There are two important options available for developers  

![](https://i.ytimg.com/vi/Z3dHWPXFfPo/maxres2.jpg)



#### [0:04:30](https://www.youtube.com/watch?v=Z3dHWPXFfPo&t=270) |  in this [? card. ?] First, if

you made a change to the page and want to request Google to reindex it, use Request Indexing. Second, you can click View Crawl Page to check the HTML version that Google indexed and more information on the HTP response and loaded resources. In the Coverage section, you'll learn where the page was discovered, such as a site map or referring page, when was the last crawl and by which user agent,  

#### [0:05:00](https://www.youtube.com/watch?v=Z3dHWPXFfPo&t=300) |  and whether the page is included in

the Google Index or another version of it was chosen as the canonical. In the Enhancements section, you'll find any structured data details, along with AMP and mobile usability warnings and errors. For example, if your page is not marked up properly with structured data, the inspection will return an error detailing the missing or wrong values. You can watch the Inspect URL episode in this series to learn how to use the tool to debug and fix  

#### [0:05:30](https://www.youtube.com/watch?v=Z3dHWPXFfPo&t=330) |  any issues you find. Search Console also

includes two reports that will help you optimize your site's help-- security issues and core web vitals. The Search Console Security Issues Report shows warnings when Google finds that your site might have been hacked or used in ways that could potentially harm a visitor or their device. For example, a hacker might inject malicious code in your pages to redirect your users to another site or to automatically create pages on your site  

#### [0:06:00](https://www.youtube.com/watch?v=Z3dHWPXFfPo&t=360) |  with nonsensical sentences filled with keywords. These

are examples of website hacking. An attacker might also trick users into doing something dangerous, such as revealing confidential information or downloading malicious software. That's called social engineering. When you log in to Search Console, you'll already be notified in the Overview page if you have security issues on your site. Clicking the alert will lead you to the Security Issues Report, where you'll find a list of all security issues  

#### [0:06:30](https://www.youtube.com/watch?v=Z3dHWPXFfPo&t=390) |  Google found in your website. In the

report, you'll find more details about the type of threat, a sample of pages affected by it, and a process for you to inform Google when you fix the issues. I recorded an episode about the security issues report with [INAUDIBLE],, my colleague from the Trust and Safety team. Check it out for more details. Lastly, the Core Web Vitals Report shows how your pages perform based on real-world usage data,  

![](https://i.ytimg.com/vi/Z3dHWPXFfPo/maxres3.jpg)



#### [0:07:00](https://www.youtube.com/watch?v=Z3dHWPXFfPo&t=420) |  sometimes called fill data. The report is

based on three metrics. LCP, or Largest Contentful Paint, is the amount of time it takes to render the largest content element visible in the viewport, starting from when the user requests the URL. This is important because it tells the reader that the URL is actually loading. FID, or First Input Delay, is the time from when a user first interacts with your page, when they click the link or tap the button, to the time when the browser responds  

#### [0:07:30](https://www.youtube.com/watch?v=Z3dHWPXFfPo&t=450) |  to that interaction. This is important on

pages where the user needs to do something, because this is when the page has become interactive. CLS, or Cumulative Layout Shift, is the amount that the page layout shifts during the loading phase. This score is rated from 0 to 1, where 0 means no shifting and 1 means the most shifting. This is important because having elements shift while a user is trying to interact with the page  

#### [0:08:00](https://www.youtube.com/watch?v=Z3dHWPXFfPo&t=480) |  is very annoying. I'm sure you will

agree. Log in to Search Console and navigate to the Core Web Vitals Report. You'll see that the report is broken down by mobile and desktop. Open one of them to see an aggregate report with more details. By default, the chart shows trends for pages with poor performance, but you can click on Need Improvement and Good to check their trends too. Be aware that if a page does not have a minimum amount of reporting data for any of these metrics,  

#### [0:08:30](https://www.youtube.com/watch?v=Z3dHWPXFfPo&t=510) |  it is omitted from the report, so

you probably won't see all your pages. Click an issue on the table to drill down. In this report, you'll find more details about the issue, a chart showing trends, and a table with simple URLs. Check the links in the description to find out more about the Core Web Vitals Report. You might also like to check out tools such as Lighthouse before you deploy changes to production. With that, I'll end this video.  

#### [0:09:00](https://www.youtube.com/watch?v=Z3dHWPXFfPo&t=540) |  It's too long already, and even if

you drank coffee in the beginning, the effect is probably starting to die away. To recap, use the Index Coverage Report to understand sitewide search indexing issues. Use the URL Inspection tool to debug page-level search indexing issues. Use the Security Issues Report to find and fix threats affecting your site, and use the Core Web Vitals Report to make sure your website provides a great page experience to your users.  

#### [0:09:30](https://www.youtube.com/watch?v=Z3dHWPXFfPo&t=570) |  Don't forget to subscribe to the Google

Webmasters YouTube channel to watch our upcoming Search Console videos. Stay tuned. [MUSIC PLAYING]  