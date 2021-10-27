[![Web Deduplication (WMConf MTV '19)](https://i.ytimg.com/vi/LsfIlviyDvE/hqdefault.jpg)](https://www.youtube.com/watch?v=LsfIlviyDvE)

## Web Deduplication (WMConf MTV '19)

Allan Scott, Software Engineer at Google, gives a presentation on web deduplication. Stay tuned to find out what web deduplication is, how Google identifies and clusters duplicate web pages, representative URLs are picked, and how signals are forwarded to canonical URLs.



Watch all the recorded talks from WMConf MTV '19 → https://goo.gle/2QHcmy6 



Consolidate duplicate URLs → https://goo.gle/2Lgif1O 

Tell Google about localized versions of your page → https://goo.gle/2QN52kI 

Avoid creating duplicate content → https://goo.gle/2xtejr8 



Subscribe to the Webmasters Channel → https://goo.gle/Webmasters event: Webmaster Conference 2019; re_ty: Publish; product: Search Console - General; fullname: Allan Scott;



#### [0:00:00](https://www.youtube.com/watch?v=LsfIlviyDvE&t=0) |  ALLAN SCOTT: So my name is Allan.

I'm here to talk about web deduplication. So probably I should explain what web deduplication is first. So what we do is we identify and cluster duplicate web pages, anything that looks the same, basically. And then we take these clusters. We pick representative URLs that actually get put into the index and served to users at search time. In the process, we generate a mapping from dupes to these representative URLs, which  

#### [0:00:30](https://www.youtube.com/watch?v=LsfIlviyDvE&t=30) |  are usually called canonicals. And we forward

the signals, some of the time, so that these deduplicated pages don't just lose their signals. You can keep them. So why do we do this? Well, first, most intuitive answer is that search users don't want to see the same result 20 times, same page over and over again. That's not a very good search experience. The second reason is that, once you  

#### [0:01:00](https://www.youtube.com/watch?v=LsfIlviyDvE&t=60) |  have removed all these pages, you actually

get a bunch of space back in the index. So you can serve more unique results, so you can start handling long-tail queries. And this is also advantageous to webmasters, because you can retain signals for your site when you redesign it, when you move pages around. The signals get forwarded from the old location to the new location. And the last thing that we get out of this is we get what we call alternate names. Now, this is two different things at the same time.  

#### [0:01:30](https://www.youtube.com/watch?v=LsfIlviyDvE&t=90) |  These days, it's used mostly for localization.

But the older use is if you wanted to, say, rebrand your site. We used to be-- let's say that Larry decides that he's tired of Google and he wants to fold it into Alphabet. He redirects Google.com into the Alphabet page. Well, we can still serve a search for Google with Google.com, because we'll know that Google is now an alternate name for Alphabet. So I'm going to talk about three things in specific.  

![](https://i.ytimg.com/vi/LsfIlviyDvE/hq1.jpg)



#### [0:02:00](https://www.youtube.com/watch?v=LsfIlviyDvE&t=120) |  So the signals that we use to

cluster pages, I'll talk a little bit about localization specifically, because localization tends to get caught in the grill a little bit here. And then I'll talk a little bit about how we select representative URLs. So the signals that we use, there's a bunch of them. The three that are most prominent and that are most at your disposal as well are redirects, the actual content of the page, and rel=canonical tags that you  

#### [0:02:30](https://www.youtube.com/watch?v=LsfIlviyDvE&t=150) |  sent us. There's a few others that

we use, mostly variance on URL normalization. But those are a little different. So redirects are the most trustworthy signal that we get. This is one of the reasons why, when you guys redesign your sites, we always suggest please redirect the old pages to the new pages, because then it makes it very trivial for us to identify, oh yes, this guy is now over here,  

#### [0:03:00](https://www.youtube.com/watch?v=LsfIlviyDvE&t=180) |  and we can continue to forward the

signals as correct, as appropriate. Now, in terms of content, to the surprise of no one, we take checksums of the content of your page. We make a number of various efforts to ignore the boilerplate in them. Now, what you might be surprised by is that what sometimes gets caught in the grill here is what we call soft error pages, where someone has served us a 200, and then some kind of very fancy elaborate looking  

#### [0:03:30](https://www.youtube.com/watch?v=LsfIlviyDvE&t=210) |  crypto error that says, sorry, this page

is not here. We do have some machine learning models that try to catch these. But webmasters are very, very creative and constantly surprise us with new ways of representing what is basically this page is not here. So this is one of the reasons why we prefer getting an HTTP error, because then instead of just dupe eliminating your page, we can do error handling, which is a little bit different. One of the things that often gets caught here  

![](https://i.ytimg.com/vi/LsfIlviyDvE/hq2.jpg)



#### [0:04:00](https://www.youtube.com/watch?v=LsfIlviyDvE&t=240) |  is site goes down for maintenance, and

puts up a "this page is down for maintenance," and suddenly half the site is gone because we crawled it while you were in maintenance mode. So please serve us a 500 instead of a 200. Now, finally, the rel=canonical annotations that you guys use, they get fed directly into clustering. We have a fair amount of validation in front of these guys, because sometimes people make mistakes.  

#### [0:04:30](https://www.youtube.com/watch?v=LsfIlviyDvE&t=270) |  My favorite one was when we opened

up one rel=canonical to discover something to the effect of open squiggly brace, open squiggly brace, rel=canonical target, closed squiggly brace, closed squiggly brace across the entire site. But this happens in ways that are not so obvious, like your entire site is rel=canonical to [? forward ?] slash, so please check your scripts. Now, on localization, most of the time,  

#### [0:05:00](https://www.youtube.com/watch?v=LsfIlviyDvE&t=300) |  when you think localization, you say, OK,

here's the French version of my page. Here's the German version of my page. And they have nothing to do with web deduplication, because the content is completely dissimilar. Now, when deduplication does get involved is when, for example, you have same language, different country, or someone decides to get clever with a bunch of geo-redirecting, and to us it all looks like the same page. So everything gets jammed into one cluster. Same for we see a lot of cases where people localize only  

#### [0:05:30](https://www.youtube.com/watch?v=LsfIlviyDvE&t=330) |  the boilerplate, and then we throw at

the boilerplate, and then it looks like the same page to us. In these situations, we're basically hoping that you guys will tell us what to do with your hfreflangs, because, to us, it looks like you guys have sent us the same page. OK, so picking representative URLs, obviously, if we jam a whole bunch of your pages into one cluster, then we have to figure out which one actually goes into the index.  

#### [0:06:00](https://www.youtube.com/watch?v=LsfIlviyDvE&t=360) |  We have a machine-learned trained system that

has every signal compete-- or every pair of pages compete on a set of signals that we've chosen. The main thing that we try to do here is avoid hijacking. That's rule number one. Everything else falls behind that. And in that case, it's actually very useful that we get escalations via WTA through the forums. And these are a great source of reports for us.  

![](https://i.ytimg.com/vi/LsfIlviyDvE/hq3.jpg)



#### [0:06:30](https://www.youtube.com/watch?v=LsfIlviyDvE&t=390) |  Once we get past hijacking, our second

concern here is basically the user experience. So is this really a good page to send the user to? So something like a slow meta refresh is a bad experience. Security-- if the page has an expired certificate, it's a bad experience. One thing that people fall into here is that we actually care quite a bit about your dependencies for secure pages. So if your secure page has insecure dependencies, we're not sure that it's going to work properly.  

#### [0:07:00](https://www.youtube.com/watch?v=LsfIlviyDvE&t=420) |  It might just have a broken script.

It might not render. So check your dependencies. And then finally, once we get past all that, then all the stuff that you guys have really direct control over, so you can just tell us your rel=canonical target is the URL that you think we should make canonical of this cluster. Great. Or you can use redirects, particularly 301s in this case. They are a signal. And site maps we use to some extent, because these are pages  

#### [0:07:30](https://www.youtube.com/watch?v=LsfIlviyDvE&t=450) |  you prefer us to crawl. So there's

probably good reason for us to use them. So finally, to recap, some suggestions from what I just said, use redirects to clue us in to how you redesign your site. Send us meaningful HTTP results. Check your rel=canonical links. Sometimes there's broken scripts, that kind of fun stuff. Use hreflang to help us localize. Please keep reporting those hijacking cases to the forums.  

#### [0:08:00](https://www.youtube.com/watch?v=LsfIlviyDvE&t=480) |  Secure dependencies on your secure pages. And

finally, try to keep your canonical signals unambiguous. Sometimes we see webmasters will say, here's a 301 with a rel=canonical pointed the other way. And then we're like, well, I don't know what to do. The webmaster has told me both cases are good. So if you keep them unambiguous, then you'll get what you want. If they are ambiguous, the system's probably going to just go off and find something else. All right. And that's it for me.  

#### [0:08:30](https://www.youtube.com/watch?v=LsfIlviyDvE&t=510) |  Thank you. [MUSIC PLAYING]  

