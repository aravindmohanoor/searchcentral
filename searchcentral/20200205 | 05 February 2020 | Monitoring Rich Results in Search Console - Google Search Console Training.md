[![Monitoring Rich Results in Search Console - Google Search Console Training](https://i.ytimg.com/vi/Vmfvf8nG09k/maxresdefault.jpg)](https://www.youtube.com/watch?v=Vmfvf8nG09k)

## Monitoring Rich Results in Search Console - Google Search Console Training

In this episode of Search Console Training, Daniel Waisberg goes over how to use Search Console to monitor and optimize your performance with Google rich results. Understand what rich results are, how to monitor their appearance on Google Search, where to find errors in your structured data, and how to ask Google to validate fixes you’ve added to your website. 



Rich result status reports → https://goo.gle/36Nv38w   

Explore the search gallery → https://goo.gle/searchgallery 

Implement structured data → https://goo.gle/2GEiPEP

Rich results test tool → https://goo.gle/richresults  

More on the rich results test → https://goo.gle/2vESl3K  

Google Search Console → https://goo.gle/searchconsole 



Watch more Search Console Training videos → https://goo.gle/sct

Subscribe to Google Search Central → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=Vmfvf8nG09k&t=0) |  Hi, I'm Daniel Waisberg,  Search Advocate

at Google and today I'll talk about  how to use Search Console to monitor and optimize  your performance with Google rich results. By the end of this video, you will understand what are rich results, how to monitor the rich results  appearance on Google Search, where to find errors  in your structured data, and how to ask Google to validate fixes you've done to your website. ♪ [music] ♪  

#### [0:00:30](https://www.youtube.com/watch?v=Vmfvf8nG09k&t=30) |  But before I go into the nuts

 and bolts of Search Console, I'd like to say a few words  about structured data and rich results. As an introduction,  if you haven't heard about it or to refresh your memory. When you search on Google,  you can see many kinds of results, including blue links  with text snippets and rich results. For example, if you search  for a venue or a music band, you may get results  that show you nearby events or if you search for falafel recipes, you may get instructions on how to cook it.  

#### [0:01:00](https://www.youtube.com/watch?v=Vmfvf8nG09k&t=60) |  Those are examples of rich results. If

you own a website, you might want to trigger  this type of results for your site as they can be more attractive to users. For that, you'll need to implement structured data markup. Check our developer documentation to find out more about what, how,  and why to implement structured data. In a nutshell, here's how your decision-making process should look like. Review the Search Gallery examples,  

![](https://i.ytimg.com/vi/Vmfvf8nG09k/maxres1.jpg)



#### [0:01:30](https://www.youtube.com/watch?v=Vmfvf8nG09k&t=90) |  find the structured data type that matches

your content, check guidelines and requirements to be eligible to appear on search, implement the markup on your pages. After you do that, you can start using Search Console to help optimizing your implementation and monitoring your performance. In addition  to the Search Console Interface, which we'll talk about in a minute, you can also use a public  structured data testing tool called Rich Results Test. This tool can verify the syntax of your structured data  

#### [0:02:00](https://www.youtube.com/watch?v=Vmfvf8nG09k&t=120) |  and, in some cases, provide a sample

of what the result might look like in Google Search. You can either upload a piece of code or check a specific URL for Google to crawl. The tool shows whether  your implementation has any errors. You'll also have an option to preview your pages search appearance on Google Search results and how it will be seen by Googlebot. Checking your own code can be very handy during development cycles to make sure your structure data is valid even before you move to production.  

#### [0:02:30](https://www.youtube.com/watch?v=Vmfvf8nG09k&t=150) |  Over time, as the pages with structured

data are indexed by Google, Search Console will start showing reports for those structured data types. After setting up your pages  and seeing them get indexed, your next step is to monitor their performance. Let's run through an example  of how you check your rich results  performance on your site. First, open Search Console  and navigate to the Performance Report. Select Search appearance in the tabs just below the main chart.  

#### [0:03:00](https://www.youtube.com/watch?v=Vmfvf8nG09k&t=180) |  You'll see in a glance the volume

 of traffic coming to your website through rich results. In order to understand  your rich results performance over time, add the future to the report including only rich results. You can do that by clicking  the Rich results row in the table. This will update your performance charts to show your rich results traffic by queries, pages, countries, and devices. You might find patterns in your data that show how important or how unimportant  a specific segment of traffic is.  

![](https://i.ytimg.com/vi/Vmfvf8nG09k/maxres2.jpg)



#### [0:03:30](https://www.youtube.com/watch?v=Vmfvf8nG09k&t=210) |  Perhaps a specific group of queries or

pages are not driving rich results, which could point at opportunities to enhance your structured data implementation. Additionally, you might notice  a drop in rich results performance if your structured data implementation was affected by a website change. Once you have a better idea  of your overall performance, you should take a closer look  into each specific structured data report in order to learn  about warnings and errors that Google has encountered in your website.  

#### [0:04:00](https://www.youtube.com/watch?v=Vmfvf8nG09k&t=240) |  Errors disqualify your rich results  from

being shown in Google Search, but you may still be shown through a standard plain blue link. Warnings can provide a somewhat  reduced experience for users. When Search console  detects structured data for one of the supported  rich results types on your website, it will create a report for each,  summarizing all errors and warnings, and it will send an email to account owners. But if an existing issue gets worse, it won't trigger an email.  

#### [0:04:30](https://www.youtube.com/watch?v=Vmfvf8nG09k&t=270) |  So it is important for you 

to check your account periodically. This is not something  you need to do every day, but I recommend  you check it once in a while to make sure everything is working as intended. For example, if your website  development has defined cycles, it might be a good idea  to log in to Search Console after changes are made to the website to check that nothing broke down. You'll find the structured data reports under the enhancements section in the sidebar.  

#### [0:05:00](https://www.youtube.com/watch?v=Vmfvf8nG09k&t=300) |  You will see a report only if

Search Console has data  for that rich result type on your site and Search Console offers a report for that type. Open the structured data type summary report you have access to. By default, you'll see the trends  for error items in the main chart, but you can also click Valid with warnings and Valid to check  their trends at the chart and more details in the table. The bar chart is great  for monitoring trends over time, but you'll probably want to check the details in the table below the chart  

![](https://i.ytimg.com/vi/Vmfvf8nG09k/maxres3.jpg)



#### [0:05:30](https://www.youtube.com/watch?v=Vmfvf8nG09k&t=330) |  which provides the specific issues  that

Google found in your website. To get more details on a specific issue, click one of the errors  to open a detailed report. Here, you'll see the date  when the error was detected, the number of errors over time, and examples of pages  where Google detected it. You can click a specific example page to check instances  of the error in your HTML code. Now that you know  what needs to be fixed,  

#### [0:06:00](https://www.youtube.com/watch?v=Vmfvf8nG09k&t=360) |  you have two options: make the required

code change yourself or share the details with a developer that can perform code changes  to your website. You can do that by grabbing a link using the Share button. After you or your developer have fixed the error, click Validate Fix, and Google will validate your changes. There are quite a few types of errors and warnings. So, if you don't understand what's wrong, check the developer documentation on the specific structured data type you implemented.  

#### [0:06:30](https://www.youtube.com/watch?v=Vmfvf8nG09k&t=390) |  You can find a list of them

in the Search Gallery. Before I leave you  to work on your property, I want to mention one last report, unparsable structured data. If Google finds structure data that, for some reason, breaks while parsing the page before it can even identify the rich result type, it will show that item as an error  in the unparsable structured data report. Parsing issues could point you to lost opportunities for rich results for your site.  

#### [0:07:00](https://www.youtube.com/watch?v=Vmfvf8nG09k&t=420) |  You should fix the errors in this

report to get the benefits of structured data. Once they're fixed, the page structure data will be added to Google or, in case there is still an issue, it will show up in the respective structured data report. That's it for today. Hopefully, you'll be more comfortable to monitor and optimize your rich results from now on. In the next episode, I'll talk about how to use Search Console to improve your AMP implementation and make your site more usable. Don't forget to subscribe  

#### [0:07:30](https://www.youtube.com/watch?v=Vmfvf8nG09k&t=450) |  to the Google Webmasters YouTube channel where

we'll be publishing  lots of Search Console videos. So, stay tuned. ♪ [music] ♪  