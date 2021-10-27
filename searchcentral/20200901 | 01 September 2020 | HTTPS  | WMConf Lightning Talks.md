[![HTTPS  | WMConf Lightning Talks](https://i.ytimg.com/vi/ZyKZm6kF0QI/maxresdefault.jpg)](https://www.youtube.com/watch?v=ZyKZm6kF0QI)

## HTTPS  | WMConf Lightning Talks

In this Webmaster Conference Lightning Talk, John Mueller, Search Relations Lead, covers how HTTPS works, why you might want to use it, how to plan a migration from HTTP to HTTPS, and some of the common questions we've seen on this topic. 



Site moves with URL changes → https://goo.gle/34bgsq1 

Change of Address Tool → https://goo.gle/2EefYV4 



See more videos like this → https://goo.gle/2VclBJz

Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



#HTTPS #SearchLightningTalks #webdev



#### [0:00:00](https://www.youtube.com/watch?v=ZyKZm6kF0QI&t=0) |  Hi, everyone. Welcome to another Webmaster Conference

lightning talk. This video series is based on sessions presented at our Webmaster Conference series of events. Our goal with these videos is to make the information we shared at these events available to everyone. Today's video will focus on HTTPS and its importance for your site. In this talk, we'll cover roughly how HTTPS works, why you might want to use it, how to plan a migration from HTTP to HTTPS,  

#### [0:00:30](https://www.youtube.com/watch?v=ZyKZm6kF0QI&t=30) |  and some common questions we've seen on

this topic. ♪ (music) ♪ Let's start with the basics. What is HTTPS and why would you want to use it? HTTPS is a secure connection between your website and your users. It protects your website from unwanted activity. For security, HTTPS ensures three things.  

#### [0:01:00](https://www.youtube.com/watch?v=ZyKZm6kF0QI&t=60) |  First, authentication. Am I talking to whom

they claim to be? This is how users can be certain they're engaging with your website and not some intermediary. Second, data integrity. Has anyone tampered with the data? When your business is active online, you want to be sure that your users see your content exactly in the way that you provided. And third, encryption. Can anyone see my conversation? Information users enter and content they view  

#### [0:01:30](https://www.youtube.com/watch?v=ZyKZm6kF0QI&t=90) |  should be kept between your website and

your users. These three pillars of HTTPS are critical for secure and trusted modern web. Your users should feel safe on your site just like they would feel if they visited your business in person. Because HTTPS is such a foundational element of the modern web, it's also a requirement for many modern browser features. In particular, you need HTTPS in order to access  

#### [0:02:00](https://www.youtube.com/watch?v=ZyKZm6kF0QI&t=120) |  features like geolocation, auto-fill, camera, progressive web

apps, push notifications and more. HTTPS is also directly shown in modern browsers, or rather, because it should be active by default, the lack of HTTPS is shown. When users access a website that doesn't use HTTPS in Chrome, for example, it will be flagged as being insecure in the browser bar. Finally, Google Search gives pages that use HTTPS properly  

![](https://i.ytimg.com/vi/ZyKZm6kF0QI/maxres1.jpg)



#### [0:02:30](https://www.youtube.com/watch?v=ZyKZm6kF0QI&t=150) |  a slight ranking boost. So, you can

see there are lots of reasons to go to HTTPS. But how do you do it? HTTPS URLs are different than their HTTP counterparts so, to switch over, you need to redirect everyone from HTTP URLs to the HTTPS version. This is generally done with a server-side 301 redirect. For websites that's generally considered to be a site migration.  

#### [0:03:00](https://www.youtube.com/watch?v=ZyKZm6kF0QI&t=180) |  Let's take a look at the commonly

taken steps. First, set up your HTTPS site. For this, you might need help from your hoster and you'll need an HTTPS certificate. In general, all certificates supported by modern browsers like Chrome will do fine. Free certificates are perfectly suited. The exact steps you need to follow here vary from website to website. Sometimes it's just a matter of changing a setting, other times there's a lot more involved.  

#### [0:03:30](https://www.youtube.com/watch?v=ZyKZm6kF0QI&t=210) |  Second, verify ownership in Google Search Console.

This is critical so that you can track issues associated with your HTTPS version 2. Additionally, you may also opt to verify the whole domain, which would combine the HTTP and HTTPS data in one place. Make sure to use the same settings in Search Console. In particular, review the settings for geotargeting URL removals, the URL parameter settings, the crawl rate settings,  

#### [0:04:00](https://www.youtube.com/watch?v=ZyKZm6kF0QI&t=240) |  and the disavow file. If you have

co-owners in Search Console, add these too. Third, test your HTTPS site extensively. Allow even some of your users to try it out. Sometimes there are quirks that you missed and it's best to recognize and fix these before committing to the HTTPS version. Some of the things to test include avoid mixed content. Mixed content is when a page on HTTPS includes elements from HTTP.  

#### [0:04:30](https://www.youtube.com/watch?v=ZyKZm6kF0QI&t=270) |  For example, you might have embedded images,

ads, or analytic script with HTTP. This is bad for security and browsers will warn users when they recognize it. Check internal linking. Make sure that all internal links within your website. Go to the HTTPS version too. There are various tools to check this but you can also just click around in your browser and watch the URL that's displayed.  

![](https://i.ytimg.com/vi/ZyKZm6kF0QI/maxres2.jpg)



#### [0:05:00](https://www.youtube.com/watch?v=ZyKZm6kF0QI&t=300) |  Check hidden references. If you use a

rel=canonical or rel=alternate hreflang= link elements, adjust them to HTTPS. If you use structured data, make sure that all URLs refer to the HTTPS version. Check you sitemap files. Sitemap files help us to crawl and index more efficiently. So, it's important to point at the correct URLs there. Now, the HTTPS site is ready. Congratulations.  

#### [0:05:30](https://www.youtube.com/watch?v=ZyKZm6kF0QI&t=330) |  It's time to switch everything over. So,

fourth, use server-side redirects to forward all requests from the HTTP version to the HTTPS version. Double-check that all of the old URLs redirect by trying samples of each part of your website manually or use a tool to automatically check all URLs. If you have sitemap file, this is a good time to submit that too. Search engines will now start to use your HTTPS URLs.  

#### [0:06:00](https://www.youtube.com/watch?v=ZyKZm6kF0QI&t=360) |  Congratulations. Fifth, now it's time to monitor

your migration in Search Console. We recommend checking Search Console regularly in the beginning, to catch any potential issues before they cause problems. In particular, check that your sitemap files are being processed normally, that no unexpected crawl errors appear. That the index coverage report shows a rise for the HTTPs site, and of course, that your users are finding your HTTPS site in Search.  

#### [0:06:30](https://www.youtube.com/watch?v=ZyKZm6kF0QI&t=390) |  If all goes well, it's now just

a matter of time until things settle down again. Do you want to take it to the next level? After you're sure that everything is working as expected, and you've given it a few months to settle down, you may want to consider enabling HSTS. HSTS, that's HTTP Strict Transport Security, is a way of letting browsers know that they don't even need to check the HTTP version of your site anymore. It's a long term commitment  from your side.  

#### [0:07:00](https://www.youtube.com/watch?v=ZyKZm6kF0QI&t=420) |  Setting up HSTS is fairly easy. You

just need to add a header to your server's responses which tells browsers that they don't need to check the old HTTP version of your site's URLS anymore. Even when a user tries to go there directly. This still requires that a user goes to your site first, and you can go even further by adding your site to the HSTS preload list. This is a shared list of sites that have committed to HTTPS.  

#### [0:07:30](https://www.youtube.com/watch?v=ZyKZm6kF0QI&t=450) |  The list is used in Chrome directly.

This is a fairly big step, so it's only recommended if you're absolutely certain that everything is working correctly on your HTTPS site. Phew. That was a lot of information. HTTPS isn't something sites do everyday. So, it's normal to have questions about some details. Let's go through some of those questions here. How long do I need to keep the redirects?  

#### [0:08:00](https://www.youtube.com/watch?v=ZyKZm6kF0QI&t=480) |  Well, ideally redirects should remain in place

forever. There should not be a reason to not redirect from HTTP to HTTPS once your site has migrated. Is it okay to just move some pages to HTTPS? Maybe my login page? Well, yes technically that's possible, in practice, it's often not much more work to move the whole site over and ultimately, that's what you want to do anyway. What kind of certificate should I get?  

#### [0:08:30](https://www.youtube.com/watch?v=ZyKZm6kF0QI&t=510) |  Any certificate that's supported in a modern

browser like Chrome is fine. You can get free certificate through Let's Encrypt, for example. How long does a migration take? Google has a lot of experience with HTTPS migration so, if you have everything set up properly, it's usually processed in less then a week or so on most sites. In practice, the exact timing doesn't matter so much, since users will be redirected anyway. Will this migration affect my site's ranking?  

#### [0:09:00](https://www.youtube.com/watch?v=ZyKZm6kF0QI&t=540) |  No, usually not. Generally speaking, it's still

the same website embedded in the web in the same way. The ranking boost for HTTPS is quite small and generally not visible separately. Can I move back if something goes wrong? Yes, but it's not recommended. Instead of moving back, we recommend just fixing the issue and moving forward. Well, that was a lot, right? Moving to HTTPS isn't something you do every day, so take your time to research  what you really need to do  

#### [0:09:30](https://www.youtube.com/watch?v=ZyKZm6kF0QI&t=570) |  and go through those steps thoughtfully. Take

notes along the way. This helps you to avoid missing important elements and makes it easier to get help, should you need it. We have a lot of information on site migrations, including migrations for HTTPS in our Help Center. I hope you enjoy this excursion into HTTPs and how it can help your site to succeed in Google Search. There're even more things related to HTTPS that we could include,  

#### [0:10:00](https://www.youtube.com/watch?v=ZyKZm6kF0QI&t=600) |  but we decided to focus on the

most critical elements here. However, if there's anything you find that's important that we missed, let us know in the comments below and if you'd like to discuss the use of HTTPS on your site, feel free to drop by our webmaster help forums, where experts can often help with questions specific to your site. And finally, if there's something more general you'd like to let us know, you're always welcome to ping us on Twitter. ♪ (music) ♪  