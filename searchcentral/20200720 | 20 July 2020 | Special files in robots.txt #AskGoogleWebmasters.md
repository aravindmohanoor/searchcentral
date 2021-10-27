[![Special files in robots.txt #AskGoogleWebmasters](https://i.ytimg.com/vi/Kruk8MhSzPk/maxresdefault.jpg)](https://www.youtube.com/watch?v=Kruk8MhSzPk)

## Special files in robots.txt #AskGoogleWebmasters

In this episode of Ask Google Webmasters, John Mueller goes over special files in robots.txt such as *.css, php.ini, and .htaccess, and explains why one does not have to and should not disallow these files from being crawled. The question was submitted by @svperflvid. Thank you!



Send us your questions on Twitter with the hashtag AskGooglebot and your question might be answered! 

Google Search Central on Twitter → https://goo.gle/3f4Z0a8



Watch more AskGooglebot episodes → https://goo.gle/2OjWcvS

Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



![](https://i.ytimg.com/vi/Kruk8MhSzPk/maxres1.jpg)



#### [0:00:00](https://www.youtube.com/watch?v=Kruk8MhSzPk&t=0) |  [MUSIC PLAYING] JOHN MUELLER: Today, I'll be

answering Anthony's question. Regarding robots.txt, should I disallow asterisk.CSS, disallow PHP.ini, or even disallow .HTaccess? Thanks. No. I can't disallow you from disallowing those files. But that sounds like a bad idea. You mentioned a few special cases. So let's take a look. Asterisk.CSS would block all CSS files.  

![](https://i.ytimg.com/vi/Kruk8MhSzPk/maxres2.jpg)



#### [0:00:30](https://www.youtube.com/watch?v=Kruk8MhSzPk&t=30) |  We need to be able to access

CSS files so that we can properly render your pages. This is critical so that we can recognize when a page is mobile-friendly, for example. CSS files generally won't get indexed on their own, but we need to be able to crawl them. You also mentioned PHP.ini. This is a configuration file for PHP. In general, this file should be locked down or in a special location so that nobody can access it.  

![](https://i.ytimg.com/vi/Kruk8MhSzPk/maxres3.jpg)



#### [0:01:00](https://www.youtube.com/watch?v=Kruk8MhSzPk&t=60) |  And if nobody can access it, then

that includes Googlebot, too. So again, no need to disallow crawling of that. Finally, you mentioned .HT access. This is a special control file that can't be accessed externally by default. Like other locked-down files, you don't need to explicitly disallow it from crawling, since it can't be accessed at all. My recommendation is not to just reuse someone else's robots.txt file and assume it'll work.  

#### [0:01:30](https://www.youtube.com/watch?v=Kruk8MhSzPk&t=90) |  Instead, think about which parts of your

site you really don't want to have crawled, and just disallow crawling of those. I hope that answers your question. And stay tuned until the next episode of "Ask Google Webmasters." [MUSIC PLAYING]  