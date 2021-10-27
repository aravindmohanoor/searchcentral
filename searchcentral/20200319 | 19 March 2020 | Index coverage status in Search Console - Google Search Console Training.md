[![Index coverage status in Search Console - Google Search Console Training](https://i.ytimg.com/vi/L0UqvdHJaXE/maxresdefault.jpg)](https://www.youtube.com/watch?v=L0UqvdHJaXE)

## Index coverage status in Search Console - Google Search Console Training

In this episode of Search Console Training, Daniel Waisberg shows how to find out which of your pages have been crawled and indexed by Google, and any problems found during the process.



Index Coverage report → https://goo.gle/2QlHxPE 

How Google Search Works → https://goo.gle/3d3GbTh 



Watch more Search Console Training videos → https://goo.gle/sct  

Subscribe to Google Search Central → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=L0UqvdHJaXE&t=0) |  DANIEL WAISBERG: Hi. I'm Daniel Waisberg, Search

Advocate at Google. And today, I'll talk about how to use Search Console to learn which of your pages have been crawled and indexed by Google and any problems found during that process. [MUSIC PLAYING] Crawling is the process by which Google Bot discovers new and updated pages to be added to the Google index. Google Bot processes each of the pages it crawls in order  

#### [0:00:30](https://www.youtube.com/watch?v=L0UqvdHJaXE&t=30) |  to compile a massive index of all

the words it sees and their location on each page. When a user enters a query, Google machines search the index for matching pages and return the results we believe are the most relevant to the user. The index coverage report discussed in this video will give you an overview of all the pages Google indexed or tried to index in your website. To learn more about how indexing works, read through our documentation.  

#### [0:01:00](https://www.youtube.com/watch?v=L0UqvdHJaXE&t=60) |  It will help you get the most

out of this video series. Check the links in the description. Before I go into the report, I want to say a few words about when and how often you should check the index coverage status report. If Search Console detects a new index coverage issue on your website, you will get an email. But if an existing issue gets worse, you won't. This means that you don't need to check the coverage report every day, but keep an eye once in a while to make sure that nothing is going from bad to worse.  

![](https://i.ytimg.com/vi/L0UqvdHJaXE/maxres1.jpg)



#### [0:01:30](https://www.youtube.com/watch?v=L0UqvdHJaXE&t=90) |  When you open the index coverage report,

the first page you see is the summary page. The default view shows indexing errors on your website. But you can click to show valid with warnings, valid, and excluded. In addition, you will find a checkbox to add to the main chart the number of impressions your page has got on search. Here is what each status means, with some examples.  

#### [0:02:00](https://www.youtube.com/watch?v=L0UqvdHJaXE&t=120) |  Errors prevent pages from being indexed. Pages

with errors won't appear in Google search results, which can mean a loss of traffic to your website. For example, you might get an error when you submitted a page containing the no index directive. Additionally, Google might find a server error, or your page might be returning a 404. All these cases would prevent the page from appearing on search results. Issues on pages you submit via site maps  

#### [0:02:30](https://www.youtube.com/watch?v=L0UqvdHJaXE&t=150) |  are explicitly called out, since they're most

likely to be problems we should resolve. Valid with warnings are pages that may or may not be shown on Google search results, depending on the issue, but we think there is a problem that you should look into. For example, Google might find pages that are indexed though blocked by robots.txt. This is marked as a warning, because we're not sure if you intended to block the page from search results.  

![](https://i.ytimg.com/vi/L0UqvdHJaXE/maxres2.jpg)



#### [0:03:00](https://www.youtube.com/watch?v=L0UqvdHJaXE&t=180) |  If you do want to block this

page, robots.txt is not the correct mechanism to avoid being indexed. To do so, you should either use the no index directive or request http: authentication to see your page. Valid pages have been indexed and can be shown on search results. No need to do anything. Excluded pages were not indexed and won't appear in Google, but either we think that is your intention  

#### [0:03:30](https://www.youtube.com/watch?v=L0UqvdHJaXE&t=210) |  or we think it's the right thing

to do. For example, the page have the no index directive, your choice, or the page is a duplicate of another page, Google's choice, or the page is simply not found and returns a 404 error. For a more comprehensive list of issues, check our Help Center. In the summary page, you should start by checking the chart to learn if your valid pages trend is somewhat steady. Some amount of fluctuation is natural.  

#### [0:04:00](https://www.youtube.com/watch?v=L0UqvdHJaXE&t=240) |  And if you're aware of content being

published or removed, you might see that reflected here. Let's take a look at the errors list now, as they're the most pressing issues. The table is sorted by severity and the number of affected pages, so start investigating at the top of the list. If your site doesn't have any errors, you can also follow along with any of the other tabs. Click the top issue to drill down into the issue details.  

#### [0:04:30](https://www.youtube.com/watch?v=L0UqvdHJaXE&t=270) |  The details page shows an over time

distribution of all pages suffering from this issue and provides a list of examples that you can check more closely. You'll also find a link to learn more about the error in the Search Console Help Center. In addition, you should click an example URL and inspect it. This will show all the details available for a specific page, as explained in the URL inspection episode of the series. Try both the indexed and live versions.  

#### [0:05:00](https://www.youtube.com/watch?v=L0UqvdHJaXE&t=300) |  What you see in the index coverage

report reflects the index data in the early inspection and it might differ from the live test result. Watch the URL inspection episode to learn more about it. Once you understand what needs to be fixed, you have two options, make the required changes yourself, or share the details with a developer that can perform code changes to your website. You can do that by grabbing a link using the Share button.  

#### [0:05:30](https://www.youtube.com/watch?v=L0UqvdHJaXE&t=330) |  The link grants access only to the

current page, plus any validation history pages for this issue. It does not grant access to other pages for your resource or enable the shared user to perform any actions on your property. You can revoke the link at any time by disabling sharing for this page. After you or your developer have fixed the error on all your pages, click Validate Fix and Google  

#### [0:06:00](https://www.youtube.com/watch?v=L0UqvdHJaXE&t=360) |  will validate your changes. That's the index

coverage status report. Hopefully now you understand how to read the information, prioritize your fixes, and let Google know when you do it. Don't forget to subscribe to the Google Webmasters YouTube channel, where we'll be publishing lots of Search Console videos. Stay tuned. [MUSIC PLAYING] Hey, green. Hey, blue. What's up? Oh, good. Did you watch the new episode of the Search Console training  

#### [0:06:30](https://www.youtube.com/watch?v=L0UqvdHJaXE&t=390) |  series? No, I didn't watch the last

one. You want to watch with me? Of course I do. Let's go.  