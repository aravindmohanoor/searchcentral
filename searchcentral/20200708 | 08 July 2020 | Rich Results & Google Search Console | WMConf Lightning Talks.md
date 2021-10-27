[![Rich Results & Google Search Console | WMConf Lightning Talks](https://i.ytimg.com/vi/B4MlM1sJ5ZE/maxresdefault.jpg)](https://www.youtube.com/watch?v=B4MlM1sJ5ZE)

## Rich Results & Google Search Console | WMConf Lightning Talks

Daniel Waisberg, Search Advocate at Google, goes over best practices on how to get started with rich results and how to use Search Console to optimize your search appearance in Google Search.



Search Gallery → https://goo.gle/2LIpD6J  

Rich result status reports → https://goo.gle/3g3tFoj 



Watch all WMConf Lightning Talks → https://goo.gle/2VclBJz

Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



#SearchLightningTalks #SEO #SearchConsole



#### [0:00:00](https://www.youtube.com/watch?v=B4MlM1sJ5ZE&t=0) |  DANIEL WAISBERG: Hi. I'm Daniel Waisberg, Search

Advocate at Google, and welcome to another lightning talk from the Webmaster Conference Lightning Talk series. Today, I'm going to talk about how to get started with rich results and use Search Console to optimize your search appearance in Google search. There are four questions I'll try to answer today-- what are rich results and structured data, how to uncover issues with alerts and checks, how to fix and validate errors and warnings,  

#### [0:00:30](https://www.youtube.com/watch?v=B4MlM1sJ5ZE&t=30) |  and how to monitor and optimize search

traffic. [MUSIC PLAYING] Many years ago, you would search for a piece of information on Google and all results would come up as plain blue links. Over time, the answers that Google provided to your queries became richer, evolving in what we call today rich results. Rich results are search results that  

#### [0:01:00](https://www.youtube.com/watch?v=B4MlM1sJ5ZE&t=60) |  provide special features or information. For example,

for recipe rich results, you might see a small picture of the dish and a preview of some ingredients. For a job posting rich result you might see a description, salary, and click through to apply for the job. Those results are powered by Google's ability to understand the content of a website. Sometimes Google can also use markup that developers add to their pages so machines can understand their content better.  

#### [0:01:30](https://www.youtube.com/watch?v=B4MlM1sJ5ZE&t=90) |  This markup is called structured data. To

get started, visit our search gallery and browse through all the structured data types supported by Google. This will help you identify which types would work for you, and you might even find a specific case study to help you understand the value of implementing it. Once you find one or more features you'd like to implement, read the documentation to learn how it works, see sample code, guidelines, and detailed reference information.  

![](https://i.ytimg.com/vi/B4MlM1sJ5ZE/maxres1.jpg)



#### [0:02:00](https://www.youtube.com/watch?v=B4MlM1sJ5ZE&t=120) |  Depending on your content management system, you

can install an extension or plugin that does the hard work for you. Otherwise, your developers can use the rich results test to check and modify their code in the live code editor. This can save valuable time and effort. It's always more efficient to have your markup working properly before moving into production. Once you've implemented structured data on your site, you can start analyzing it in Search Console enhancement  

#### [0:02:30](https://www.youtube.com/watch?v=B4MlM1sJ5ZE&t=150) |  reports. There are three questions that are

at the heart of the reports you see in Search Console. Is there anything wrong with my site? How can I fix any issues and tell Google about it? And how can I optimize my search performance? Let me go through an example of how you would use Search Console to answer those questions for your rich results. In order to answer question number one,  

#### [0:03:00](https://www.youtube.com/watch?v=B4MlM1sJ5ZE&t=180) |  there are two things you need to

know. The first one is that we'll notify you whenever we find an issue on your website. Whenever Search Console finds an error in your pages, we'll send you an email to let you know about it. You'll get some details about the issue with a link to more information or to the report you need to check. The second thing you need to know is that if an existing issue starts affecting more pages, you won't get an email. So take a look at the enhancement reports  

#### [0:03:30](https://www.youtube.com/watch?v=B4MlM1sJ5ZE&t=210) |  once in a blue moon and check

that the trends are somewhat steady. Some amount of fluctuation is natural, but you don't want to see sudden spikes. To see a summary of the health of all the structured data on your site, go into Enhancement Report in Search Console. There is a separate report for each rich' result type and another report for structured data that had errors that prevented us from knowing the type of rich result. You'll see an enhancement report only for rich result types  

![](https://i.ytimg.com/vi/B4MlM1sJ5ZE/maxres2.jpg)



#### [0:04:00](https://www.youtube.com/watch?v=B4MlM1sJ5ZE&t=240) |  that we detect on your site. See

the documentation for a list of rich results report types that we currently support. By default, issues are sorted by a combination of severity and number of pages affected. If you see an error that seems like the result of a bad template, fix it first. Then continue fixing other issues that are unique to each page following the order in the table. Click an issue in the table to see more details about it, as well as a list of URLs affected by it.  

#### [0:04:30](https://www.youtube.com/watch?v=B4MlM1sJ5ZE&t=270) |  For URLs which you'd like to further

explore in depth, click the small inspection icon close to it. This will run a URL inspection for this page. You'll find three main sections in the URL inspection results. In the presence on Google Card, you'll see a verdict on whether or not a URL can appear in Google search results. In the coverage section, you'll learn where the page was discovered, when was the last crawl, and by which user agent, and whether the page is included  

#### [0:05:00](https://www.youtube.com/watch?v=B4MlM1sJ5ZE&t=300) |  in the Google web index or another

version of it was chosen by Google. In the Enhancement section, you'll find any structured data details along with AMP and mobile usability warnings and errors. You can use Search Console to dive deeper into the issue and debug it. Take a look at the results and try to identify what needs to be fixed in your page. Once you fix your issue, go back to this page and click Test Live URL. This runs a test against a live page for information  

#### [0:05:30](https://www.youtube.com/watch?v=B4MlM1sJ5ZE&t=330) |  similar to the indexed URL. This is

very useful to test live if an issue still exists even after you fixed it in your site. Now, go back to the issue page on the structured data report and click validate fix. This will trigger a validation process for the current issue. First, Google will check a few sample pages. If the issue exists in any one of them, validation ends and the validation state remains unchanged.  

![](https://i.ytimg.com/vi/B4MlM1sJ5ZE/maxres3.jpg)



#### [0:06:00](https://www.youtube.com/watch?v=B4MlM1sJ5ZE&t=360) |  If the sample pages do not have

the current error, validation continues with state started. When all errors of warnings URLs have been checked and the issue count is 0, the issue state changes to passed. You can see the progress of validation requests by clicking the validation details link in the Issue Details page. I've spoken a lot about errors and warnings. Now, let's talk about something nice--  

#### [0:06:30](https://www.youtube.com/watch?v=B4MlM1sJ5ZE&t=390) |  optimizing and growing your search traffic. In

order to do that in Search Console, I recommend using the performance report, which provides you with plenty of data about your traffic from Google Search. In that report you'll find a Search Appearance tab just below the main chart. You'll see in a glance the volume of traffic coming to your website through rich results. Some rich results have dedicated filters. For example, how to and FAQ rich results. To understand your rich results performance over time,  

#### [0:07:00](https://www.youtube.com/watch?v=B4MlM1sJ5ZE&t=420) |  add the filter to the report for

the specific search appearance you want to examine, such as videos or product results. You can do that by clicking a row in the table of the search appearance tab. This will update all your performance charts to show only rich results traffic by queries, pages, commentaries, and devices. Look for patterns in your data that show how a specific segment of traffic is performing. For example, you may find out that the specific group  

#### [0:07:30](https://www.youtube.com/watch?v=B4MlM1sJ5ZE&t=450) |  of pages is not driving rich results,

which could point at opportunities to enhance your structured data implementations. You may also notice a drop in rich results performance if your structured data implementation was affected by a website change. I hope that now you have a better idea of how Search Console can help you optimize your search appearance on Google. If you liked this video, make sure to check out the Search Console training series in the Google Webmasters  

#### [0:08:00](https://www.youtube.com/watch?v=B4MlM1sJ5ZE&t=480) |  channel. You'll love it. And I look

forward to seeing you at one of the upcoming webmaster conferences. Stay tuned. [MUSIC PLAYING]  