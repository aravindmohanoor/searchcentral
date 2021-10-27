[![Search Console under the hood - Google Search Console Training (from home)](https://i.ytimg.com/vi/Wo0qZDebKOo/maxresdefault.jpg)](https://www.youtube.com/watch?v=Wo0qZDebKOo)

## Search Console under the hood - Google Search Console Training (from home)

Daniel Waisberg is joined by Hillel Maoz, Engineering lead for Search Console in our final episode of the Google Search Console Training series. They get under the hood of Search Console and share how it actually works and how the team thinks about its features and go about building them. 



Share your feedback on Twitter →  https://twitter.com/googlesearchc



Watch more Search Console Training videos → https://goo.gle/sct    

Subscribe to the Webmasters Channel → https://goo.gle/searchcentral



#### [0:00:00](https://www.youtube.com/watch?v=Wo0qZDebKOo&t=0) |  DANIEL WAISBERG: Hi, I'm Daniel Waisberg, search

advocate at Google. HILLEL MAOZ: And I'm Hillel Maoz, engineering lead for Search Console. DANIEL WAISBERG: First of all, thanks for joining me today, Hillel. HILLEL MAOZ: Thank you, Daniel. DANIEL WAISBERG: This is the very last episode of the Search Console training series. And we are going into the bits and bytes of the product. And who better than you to talk about it? HILLEL MAOZ: Sure, Daniel, always great to chat about what we do and how we do it. DANIEL WAISBERG: Today we'll talk about what happens under the hood in Search Console. We'll focus on two areas, how Search Console actually works  

#### [0:00:30](https://www.youtube.com/watch?v=Wo0qZDebKOo&t=30) |  and how it fits into the search

ecosystem and how we think about features and go about building them. [MUSIC PLAYING] HILLEL MAOZ: Before we go into the nuts and bolts of Search Console, it's important to say out loud what the team is trying to accomplish. Our mission is to provide data and tools to help site owners improve their websites and optimize their appearance on Google.  

#### [0:01:00](https://www.youtube.com/watch?v=Wo0qZDebKOo&t=60) |  The product extracts important, relevant information from

Google Search internal systems, reports it to site owners, and enables them to improve their website performance on Google. Now, you may be asking yourself, what exactly is the search ecosystem? Daniel, can you take that one? DANIEL WAISBERG: Sure. First, there's the web, where millions of websites publish content all the time, including you, watching this video right now. Second, there is Google, which crawls the web,  

![](https://i.ytimg.com/vi/Wo0qZDebKOo/maxres1.jpg)



#### [0:01:30](https://www.youtube.com/watch?v=Wo0qZDebKOo&t=90) |  finds content, and stores it in the

Google index. It extracts all the relevant information from every page so that it can retrieve the best results for user queries on the Google Search results page. And third, there are Search users looking for answers and navigating from Search results to their desired web pages. Search Console is the main communication channel between Google Search and site owners-- basically, you.  

#### [0:02:00](https://www.youtube.com/watch?v=Wo0qZDebKOo&t=120) |  The tool provides information on how your

site performs on Search. And it provides technical information on potential issues Google found in your pages. From working together with the team for some time now, I know they're always monitoring Google internal systems and data sets for important website information. They're also tightly integrated with other Google Search teams to make sure Search Console is ready for new features. And of course, we keep our ears open to learn what are your needs. There are numerous reports and features on Search Console.  

#### [0:02:30](https://www.youtube.com/watch?v=Wo0qZDebKOo&t=150) |  We organize them into three main groups.

The Search Analytics group displays all the relevant user activity data related to website performance in Google Search. The Reporting group focuses on helping you track issues, debug, and validate fixes on specific pages or entire websites. The Configuration group manages site and user configurations as well as alert settings. Hillel, can you give us a little more information  

#### [0:03:00](https://www.youtube.com/watch?v=Wo0qZDebKOo&t=180) |  about each of those groups? HILLEL MAOZ:

Sure, Daniel. The Search Analytics group is the part of the team that works on retrieving and reporting data from our internal systems about users' clicks and impressions on Search results. There are billions of search results every day. We process that information and store data for every site for a period of 16 months. This information is mainly surfaced through the performance reports, where you can slice and dice the data to learn more about patterns and anomalies  

![](https://i.ytimg.com/vi/Wo0qZDebKOo/maxres2.jpg)



#### [0:03:30](https://www.youtube.com/watch?v=Wo0qZDebKOo&t=210) |  in your Google Search traffic. The Reporting

group is the part of Search Console that surfaces how your pages are seen by Google Search. For example, is Google finding all your pages? Are there any errors that prevented Google from crawling your pages? Are there issues with your structured data implementation? Google crawls pages from millions of domains. It looks for hundreds of signals supporting dozens of search features, such as AMP, recipes, and FAQs.  

#### [0:04:00](https://www.youtube.com/watch?v=Wo0qZDebKOo&t=240) |  The information is available through actionable reports

that help you debug, fix, and inform Google to start a validation process for pages you just fixed. We also offer testing tools to enable you to trigger the entire Search stack for any given URL. For example, when you type a URL in inspect URL or the rich results test, we run a simulation of the Google index and give you the information we find with high fidelity. This enables site owners to debug any URL on their site  

#### [0:04:30](https://www.youtube.com/watch?v=Wo0qZDebKOo&t=270) |  easily and effectively. Accounts is the group

responsible for managing site and user configurations. Their primary goal is to help site owners verify their sites and get access to their accounts, and of course, to prevent anyone that is not site owner to see your Search Console information. This group also handles all the emails that you receive from Search Console. They do that for dozens of other types across all the different reports, making sure you never miss an important change or update.  

#### [0:05:00](https://www.youtube.com/watch?v=Wo0qZDebKOo&t=300) |  DANIEL WAISBERG: Well, now that we know

how the Search Console team is organized, let's talk a little bit about how the team developed the reporting tools that you use. The process can be roughly divided into three main steps. I know. It's the third time in this video that we've grouped something in threes. Coincidence? Maybe. The first step is to define what can  

![](https://i.ytimg.com/vi/Wo0qZDebKOo/maxres3.jpg)



#### [0:05:30](https://www.youtube.com/watch?v=Wo0qZDebKOo&t=330) |  help a page succeed on Search. We

check that Google crawls the pages and gets all the content the site wants to share with us. For example, for topics such as mobile friendliness, core web vitals, or structured data, we define all the signals that can validate their implementation in every page. That leads us to the second step, which is to build a pipeline to go over all the pages in the index periodically and classy them against the signals. If we find that a page fails for a specific website, we collect all the relevant details such as the reason  

#### [0:06:00](https://www.youtube.com/watch?v=Wo0qZDebKOo&t=360) |  the page couldn't be crawled, or why

we're unable to use its structured data. And finally, the third step is to build reports to share this information with you using the Search Console interface, which is where you can see this information for your site. For a complete picture, we publish dedicated documentation articles where users can learn about these new reports and better understand the information being displayed. Keep in mind that Google is always evolving. So new opportunities to shine on search arise frequently.  

#### [0:06:30](https://www.youtube.com/watch?v=Wo0qZDebKOo&t=390) |  Our job as a team is to

keep up with these changes and build an effective way for you to leverage new and existing Search features to the fullest. HILLEL MAOZ: Daniel, before we forget, there's one last point to discuss before we part. The team is always looking for feedback from the Search community. You are a valuable source of information to help drive product strategy and improve Search Console. If you have feedback, make sure to submit it through the product, or mention us on Twitter.  

#### [0:07:00](https://www.youtube.com/watch?v=Wo0qZDebKOo&t=420) |  DANIEL WAISBERG: Thank you so much for

joining us today, Hillel. And thanks for all the work you and your team put into this. It's helping lots of websites succeed on Search. Hopefully now you will understand a bit more about how and why the Search Console team builds features in the product. If you liked this video, make sure to check out the Search Console training series in our YouTube channel. You'll love it. Stay tuned. HILLEL MAOZ: Oh, I just realized, the holidays  

#### [0:07:30](https://www.youtube.com/watch?v=Wo0qZDebKOo&t=450) |  are coming. Are you doing anything, Daniel?

DANIEL WAISBERG: No, not much. But I'll definitely take some time to rest a bit. This year was challenging, to say the least. HILLEL MAOZ: True. So let's take this opportunity to wish the SEO community a wonderful holiday season and a happy, peaceful, and healthy new year. DANIEL WAISBERG: Here's to a great 2021.  