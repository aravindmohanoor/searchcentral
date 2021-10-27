[![Googlebot and Web Hosting (WMConf MTV '19)](https://i.ytimg.com/vi/JvYh1oe5Zx0/hqdefault.jpg)](https://www.youtube.com/watch?v=JvYh1oe5Zx0)

## Googlebot and Web Hosting (WMConf MTV '19)

Jin Liang, Software Engineer at Google, gives a brief overview on Googlebot and web hosting. Find out more about robots.txt, Google's crawl rate, and how HTTP serving has evolved.



Change Googlebot crawl rate → https://goo.gle/3dtWSY5 



Watch all the recorded talks from WMConf MTV '19 → https://goo.gle/2QHcmy6 

Subscribe to the Webmasters Channel → https://goo.gle/Webmasters event: Webmaster Conference 2019; re_ty: Publish; product: Search Console - General; fullname: Jin Liang;



#### [0:00:00](https://www.youtube.com/watch?v=JvYh1oe5Zx0&t=0) |  JIN LIANG: Hi, everyone. My name is

Jin, and I'm going to talk a little bit about Googlebot and web hosting. As many of you probably know, before Google can index a page and serve it to the users, we have to crawl the page and render it. This is done by our system known as Googlebot. Googlebot does a lot of things. For example, we follow out links and discover new content. We predict duplicated content behind different URLs,  

#### [0:00:30](https://www.youtube.com/watch?v=JvYh1oe5Zx0&t=30) |  so we can save crawl bandwidth. We

also recrawl URLs to keep our index fresh. But for today, I'm going to focus on some specific things. First, I will share some of our observations how web hosting has evolved over the years. Next, I will talk a little bit about robots.txt fetch and also our crawling rate. This is the graph that shows the HTTP server  

#### [0:01:00](https://www.youtube.com/watch?v=JvYh1oe5Zx0&t=60) |  popularity over the years. And popularity here

is defined as the percentage of websites that are served by a particular HTTP server. We can see that Apache started out being very popular. About 10 years ago, more than 70% of the websites are served by Apache, but this number has been dropping over time. Now, Apache is serving about 35% of the websites. On the other hand, Nginx has become really popular.  

#### [0:01:30](https://www.youtube.com/watch?v=JvYh1oe5Zx0&t=90) |  10 years ago, it was serving very

few websites. Now, it's serving about 40% of the websites. MicrosoftIS started about 22% of the sites. Now, the number is about 15%. There are a few other HTTP servers. I'm not going into the details. I should note that this kind of data is actually externally available. There are sources of data externally  

![](https://i.ytimg.com/vi/JvYh1oe5Zx0/hq1.jpg)



#### [0:02:00](https://www.youtube.com/watch?v=JvYh1oe5Zx0&t=120) |  you can find about HTTP server market

share or something. So the numbers will differ a little bit with what we see here, but we find that the general trend is consistent. This graph shows, from Google point of view, what's relative traffic between HTTP and HTTPS. 10 years ago, almost all of our crawling traffic is HTTP, but in the last several years, HTTPS has really picked up.  

#### [0:02:30](https://www.youtube.com/watch?v=JvYh1oe5Zx0&t=150) |  Today, about 75% of our crawling traffic

is HTTPS. HTTP only accounts for about 25% of the traffic. Now, on the one hand, we see that the web has become really more secure, but on the other hand, we can see there is also still quite some room for HTTPS to grow. This graph shows the average URL download  

#### [0:03:00](https://www.youtube.com/watch?v=JvYh1oe5Zx0&t=180) |  time seen by the Googlebot. So we

can see, about 10 years ago, to download a web page on average, it takes about 800 milliseconds. Today, the number is about 500 milliseconds. Of course, these numbers are specific to Googlebot, but I think the general trend seems to indicate that networks are getting faster, servers are getting faster. That's good news, because in the same amount of time,  

#### [0:03:30](https://www.youtube.com/watch?v=JvYh1oe5Zx0&t=210) |  Googlebot can download more web pages. Now,

let's switch gears and talk a little bit about robots.txt, which has been mentioned in multiple [INAUDIBLE] previous talks. So many of you probably know that robots.txt is a way for webmasters to specify access to their site. Here, you see an example robots.txt snippet. This one actually shows what URLs Googlebot  

#### [0:04:00](https://www.youtube.com/watch?v=JvYh1oe5Zx0&t=240) |  can crawl from this site and what

URLs we're not allowed to crawl. Also, robots.txt has been used in industry for more than 25 years. There has never been really a standard for it. This creates some issues because the same robots.txt may be interpreted differently by different search engines. That's why, in the past year, my team and the webmasters team here at Google, we work together,  

![](https://i.ytimg.com/vi/JvYh1oe5Zx0/hq2.jpg)



#### [0:04:30](https://www.youtube.com/watch?v=JvYh1oe5Zx0&t=270) |  and we also work with Bing to

propose draft standard to IETF. Once this becomes a real standard, hopefully, there's no more ambiguity in terms of how robots.txt can be interpreted. Now, when Googlebot is crawling the web, before we crawl every single URL, we have to check it against the robots.txt. In order to do this, we have to fetch the robots.txt itself,  

#### [0:05:00](https://www.youtube.com/watch?v=JvYh1oe5Zx0&t=300) |  and this fetch can fail. When we

try to fetch robots.txt, if we get 200, OK, that's great, because we have the robots.txt. We know how to check if a URL is allowed. If we get a 404 not found, that's also good because it means there is no restriction about crawling the URLs on that site. Sometimes, a web server will be temporarily overloaded, and they return 5xx responses.  

#### [0:05:30](https://www.youtube.com/watch?v=JvYh1oe5Zx0&t=330) |  That's fine as long as this is

a transient response because we will retry the fetch later. But if the website starts returning 5xx every single time, or for some other reasons, we cannot fetch the robots.txt at all, then it becomes more serious. Because we don't know the robots.txt, we don't have it, so we don't know whether a URL is allowed or not. So to be safe, we don't crawl any URL from the website.  

#### [0:06:00](https://www.youtube.com/watch?v=JvYh1oe5Zx0&t=360) |  This graph shows the distribution of robots.txt

fetch status on a typical day. We can see about 69% of the time, we get either 200 OK or 404 not found. This is great. About 5% of the time, we got 5xx. This is fine as long as it's transient. For 26% of the time, we got some other kind of errors. This could be that the site is just down, or sometimes,  

#### [0:06:30](https://www.youtube.com/watch?v=JvYh1oe5Zx0&t=390) |  a website will time out when we

try to download the robots.txt, or they just close the connection before sending anything back. So these are bad. So if the website is already returning 200 OK or 404, that's good. If it's a 5xx, we recommend that you don't-- only return this temporarily when the server is overloaded. For the other cases, we recommend that the webmaster either create a robots.txt  

![](https://i.ytimg.com/vi/JvYh1oe5Zx0/hq3.jpg)



#### [0:07:00](https://www.youtube.com/watch?v=JvYh1oe5Zx0&t=420) |  if you want to control access to

different parts of your site, or just return 404. This will make the life of a crawler much simpler. So lastly, let's talk a little bit about Google's crawling rate. When Googlebot is crawling the internet, we try very hard not to overload your server. That's why we maintain a crawl rate to every website  

#### [0:07:30](https://www.youtube.com/watch?v=JvYh1oe5Zx0&t=450) |  out there, and we have sophisticated ways

to adjust our crawl rate in order to meet both the internal demand and also the server's capacity needs. But our crawl rate is not perfect, and the notion of being overloaded can be different for different websites. That's why, in our search console, there is a tool called a Customer Rate tool. You can go there and set a crawl rate. That will limit how fast we can crawl.  

#### [0:08:00](https://www.youtube.com/watch?v=JvYh1oe5Zx0&t=480) |  There is actually a webmaster article explaining

how you can do this. But we should caution that just because you set a customer crawl rate, that does not trigger more crawls. Sometimes, the webmaster may have a misunderstanding. They want Googlebot to crawl more, so they try to set a higher number. This does not work. You will not trigger Googlebot to crawl more URLs, because the actual crawl rate determined by many things.  

#### [0:08:30](https://www.youtube.com/watch?v=JvYh1oe5Zx0&t=510) |  Sometimes, when you set a customer crawl

rate, it may actually accidentally reduce your crawl. Recently, we have news websites in some Asian country. They contacted one of our webmaster team members at midnight, and they complain about their crawl rates drop. Turns out they set a customer crawl rate a few days ago. So for these kind of reasons, our recommendation is, in terms of a Googlebot crawling rate, please leave it to Google unless your website is  

#### [0:09:00](https://www.youtube.com/watch?v=JvYh1oe5Zx0&t=540) |  being overloaded. That's all I have today.

I hope you find this interesting. If you have any questions, feel free to reach us through the webmaster forums channel. Thank you. [MUSIC PLAYING]  