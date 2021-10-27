[![Google Search: State of the Union  (Google I_O'19)](https://i.ytimg.com/vi/ufcijo46LCU/maxresdefault.jpg)](https://www.youtube.com/watch?v=ufcijo46LCU)

## Google Search: State of the Union  (Google I_O'19)

Learn about the latest Google Search features and how to take advantage of the new APIs and capabilities to help optimize your content (text, images, and video) to be discovered on the Search results pages.



Watch more #io19 here: 

Web at Google I/O 2019 Playlist → https://goo.gle/2vIoGnb

Google I/O 2019 All Sessions Playlist → https://goo.gle/io19allsessions 

Learn more on the I/O Website → https://google.com/io



Subscribe to Google Search Central → https://goo.gle/SearchCentral

Get started at → https://www.google.com/webmasters



Speaker(s): John Mueller, Martin Splitt



T280EC event: Google I/O 2019; re_ty: Publish; product: Search Console - General; fullname: John Mueller;



#### [0:00:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=0) |  [MUSIC PLAYING] JOHN MUELLER: Search is obviously

really big thing at Google. We live and breathe everything around websites and web search. So that's a really big topic for us. Search used to look like this. This screenshot is a little bit older. It feels a bit foreign to me now. But Search has been moving forward quite a bit, evolving together with the rest of the ecosystem, constantly adapting to modern user and publisher needs.  

#### [0:00:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=30) |  So things are really changing in Search.

And the functionality available to developers and publishers to highlight their pages, well, your pages, and the pages that you work on-- that has evolved similarly. While it's still possible to appear like this in Search, you can also do so much more now. Really cool stuff. MARTIN SPLITT: Aww.  

#### [0:01:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=60) |  [CHUCKLES] JOHN MUELLER: And with that, our

tools have also made big jumps in the last year. Again, this is an older screenshot. You might remember this tool. And look at the progress that's been made in Search Console to make it easier for you to create fantastic websites that work really well in Google Search. So today, we try to take a step back and review the state of the union with an eye on developers and publishers, so for you and the people  

#### [0:01:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=90) |  that you make websites for. We'll start

very briefly by looking at how modern Google Search works. It's important to understand the basics so that it's clear where these aspects fit in. And then we'll look at different aspects that interact with Search, such as images, structured data, and of course, Search Console. So, Martin, why don't you take it away with an overview of how Search works? MARTIN SPLITT: Awesome, awesome.  

#### [0:02:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=120) |  Thank you very much, John. I think

that's a good idea. So before we go into all the new cool stuff that we have in store for you, I think it's a good idea to look at Search a little more in depth. If you think about it, it's just this input box, and it looks pretty simple, right? You just type in your query, and then you get a bunch of results. Done. However, if you look at it from a developer's perspective, it's a little more complex than that. There's a lot of things that have to work together to actually make Search work. So, I mean, you know, generally speaking,  

#### [0:02:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=150) |  as a web developer or a publisher,

you can just assume that things will work automatically. But you can help Search-- and not just Google search. You can help search engines understand your content better and make things run a lot smoother. So basically, what are the things that you should look at? And how do they fit together when it comes to search engines? Well, let's start with something that you hopefully all have. If not, then I'm not exactly sure what you're doing in this session. But we have plenty of cool stuff for you to look at anyways.  

#### [0:03:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=180) |  If you have a website like this,

this is interesting for you to be in Search, right? But wait a minute. So when I say websites, the web has evolved a lot. What do I mean when I say "website?" Let's have a look at what websites are when it comes to Google Search. So anything that we consider a website in Search has to have a URL somewhere on the web. That makes sense. We're a web search engine. You should have some content on the web somewhere. And this content should not just be hidden away  

#### [0:03:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=210) |  behind a login or something. Search works

for everyone who might not even have a login yet who might become a customer, but isn't a customer yet of yours. So you want to make sure that it's publicly accessible, right? Which means not necessarily everything that is publicly accessible has to be in Search, right? You can tell us to not do that. You can tell us to stay away. There's methods like the robots.txt or the meta tag for no indexing. You have the possibility to opt out of this, obviously. We are nice citizens of the web. We don't force you into this.  

#### [0:04:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=240) |  And also, you want to make sure

that once people actually see you in Search, and they come to your site, they can actually access their content. That spans things like being able to view this in every modern browser, but also look at things like performance and accessibility as well. So, what are examples of websites? Well, you have the classical typical HTML page. These are perfectly fine and a great way to have content hosted on the web. But also things like progressive web apps-- as far as we're concerned, the progressive web app is still  

#### [0:04:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=270) |  a website, so you'll be fine. These

things can be indexed just as well. Generally speaking, web applications that are more dynamic and using JavaScript are also websites from our perspective, right? And that includes things like AMP, Angular, React, Vue, Ember, all these other things, Polymer, lit-html-- whatever you use to make websites these days is basically still a website at its core. So how does Google Search get involved? Well, we have our little friend here, Googlebot.  

#### [0:05:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=300) |  Googlebot is basically busy continuously browsing the

internets, more or less, right? So, like crawling, crawling, crawling all these pages that we have and we want to index in the web. Currently, that is over 130 trillion pages, right? So that's a lot of pages. That's pretty busy. But what if I basically then create a new home page. It's a brand new site. I just put it online. But Googlebot is still really busy crawling the web.  

#### [0:05:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=330) |  So it doesn't really know that your

website has just come online and is now theoretically available to be indexed. So how can I get my website known to Googlebot? Well, there's a few ways. The most typical way is something on the internet that we are already looking at and crawling is linking to you. That tells Googlebot, hey, there's something new that you should definitely take a look at and crawl, that you check this out. Of course, there's other ways, and we're going to talk about them in a bit. But you can use this to tell us, or like,  

#### [0:06:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=360) |  someone can use this to tell us

about your website. But there's also things like you can submit it in Search Console. And you can use other things, other means that we're going to talk in a second. So now Googlebot has found this link and now knows about this one page of your website. Let's say it's the home page. Someone linked your home page somewhere, and we come to your home page. What Googlebot now does is it looks through all the links that we find in this page that hopefully leads us to the rest of your website. It's the internal links that help us understand what else is there on your website  

#### [0:06:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=390) |  that we should definitely take a look

at. And I mean, this website is wild-- cars, planes, and even a boat?! I mean, come on, that's a pretty cool website. And I think this is really important that we crawl this. And look at how excited Googlebot is about that boat. I mean, wow, holy shit. And then this is just the beginning of this relationship, right, John? We are just starting here. So basically what you want to do is you want to help us find all the great content you put on the web, right? So to sum this up, basically Googlebot  

#### [0:07:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=420) |  needs to have a reference to your

website. Typically, that's a link that someone else recommends. Or like, someone goes like, this is great content. You should check it out. But you also want to make sure that you link us to all the other pages. You should have some sort of internal linking structure and some sort of page structure that tells us what the rest of the website looks like. And last but not least, if you link, use a link. This shouldn't be rocket science. But I think it's worthwhile calling this out. This is a link.  

#### [0:07:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=450) |  It has an href. And that is

a URL in that href. Good link. A-plus, right? So please give us proper, unique URLs for your site so that we can actually discover and crawl them properly as well. Also, if you don't want us to do that, if you would like some things to not end up in Search, please use the robots.txt to tell us so. We will respect that and help you not have something in Search that you don't want in Search, right? Also, if you want us to discover, links are not the only way to make sure that we see content  

#### [0:08:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=480) |  on your website. Another possibility is to

upload an XML file, for instance, to Search Console. Or tell us there's a site map with all the URLs that you consider worthwhile discovering for Googlebot. Also, if you have RSS feeds, you can give them to us using a thing called WebSub. And then we basically will start calling your RSS feed entries as well. If you have structured data, and we're going to-- you're going to talk about structured data later, right? Yeah. So we have structured data for jobs and live streams. If you are doing live streams or have  

#### [0:08:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=510) |  job offers on your website, you can

use an indexing API to tell us about these as well. Last but not least, if you are really excited about something new that you put in and don't want to use the other ways, you can also literally go into Search Console-- we're going to look into that tool a little later-- and add it manually in Search Console. All right. Now, discovery is just the very first step. As I said, it's the beginning of this beautiful relationship, right? But it might take a while for us to actually get  

#### [0:09:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=540) |  around crawling 130 trillion pages-plus. And, I

mean, the web just keeps growing. That's a lot of stuff for Googlebot to look at. So we can't just immediately do that. So it will take some time for us to come to your sites and web pages to basically crawl them in. But don't worry about that. If you're worried about if we have discovered it already, use Search Console to see that we have discovered it, when we have crawled it, and when Google crawled it last time. So you can use Search Console to learn more about that. But we'll talk about that in a little more detail later.  

#### [0:09:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=570) |  OK, now when I say "crawling," I

wonder if there's web developers in here who are like, OK, but what is crawling exactly? And does that work with my web application or PWA, right? Well, crawling, very fundamentally, is an HTTP request, but your browser does it. It's a GET request to the URL that you provided us or that we discovered. And that is great for web sites that are just HTML. But modern web sites are actually not just plain HTML. They look more like this, where you basically have a very barebone HTML structure  

![](https://i.ytimg.com/vi/ufcijo46LCU/maxres1.jpg)



#### [0:10:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=600) |  that loads JavaScript. And then JavaScript generates

the content on the fly. So how do we actually get that into our index? How do we understand what the content of this website actually is? Well, for that, we have to render. Now, rendering is a whole different can of worms, and it's a beautiful topic with lots of interesting details. We have a session on that at 1:30 together with someone from the rendering team, with Zoe, my lovely co-worker from the rendering team-- Stage 3 if you want to join us for that. Or check out the livestream later or the recording if you're watching this on YouTube.  

#### [0:10:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=630) |  Definitely worth learning more about rendering. And

there is one thing that is quite cool that I would like to take away already. But we basically go in much more detail later. And that is that we are now actually using a modern Chrome in Googlebot. So Googlebot-- [APPLAUSE] It has been the number one thing that you guys asked-- you all asked us, right? You asked us, hey, when do we get the latest Chrome?  

#### [0:11:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=660) |  What Chrome version is this? Why can

we not have the latest Chrome? When is it coming? Will it be updated? All these questions, we listened. We took them very seriously, but we also make sure that we have a good strategy in place and that we have a sustainable strategy in place as well. And you don't have to worry about things anymore. So that's why we decided to not only update to the latest Chrome, but keep it evergreen. So that's the big news here, really. This is not just a one-time update, and then you have to wait again. We'll keep continuously updating Googlebot with these new Chrome  

#### [0:11:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=690) |  releases coming out. Also, there's a blog

post if you want to learn more about what that means to you as a web developer or publisher. I highly recommend checking that one out too. Right. I heard a lot of people. We announced this in the dev keynote really briefly. And a few people asked us questions already-- not a few. A bunch of people asked us really good questions. I love these questions. Keep them coming. But the number one concern that is underlying all these questions is, do I have to worry about this? What does that mean for me and my site?  

#### [0:12:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=720) |  Is this a problem? And I can

tell you no, don't worry about it. It's cool. We will not just start using the modern Chrome. We have been doing that beforehand. We have very carefully tested on an increasing number of sites. And today, I am happy to announce that if you have a URL on the web that is being crawled and rendered, it is rendered with the modern Google Chrome. So no worries about that. We tested this out very carefully. Also, we keep monitoring rendering carefully, right? If something goes wrong, we'll probably  

#### [0:12:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=750) |  be very quickly to notice that and

fix that as well. So don't worry. We have you covered. And also, if you want to learn more about the user agent, a few people have seen-- you're still seeing the old user agent. That's because we don't want to break sites that don't know about this yet. So we'll give you a heads-up in Google Webmaster Blog-- so stay tuned on our blog-- whenever we are about to change the user agent. So please prepare your insights. Do not hard-code the user agent exactly. Use something like pattern matching to be a little more flexible.  

#### [0:13:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=780) |  But basically, we will update the user

agent. But we haven't done that now because we want to make sure that we are not breaking your content, all right? Cool. If you want to learn more about that, as I said, please join us 1:30 PM tonight. It's going to be fun. All right, so that was very brief. And the session is going to cover more details. If you are using JavaScript frameworks, not everything will just magically work now. A lot of things have been fixed. We have over a thousand new features.  

#### [0:13:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=810) |  But if you want to learn more

about how to work with your specific framework and improve SEO on your specific sites, definitely check out our YouTube video series. It's called JavaScript SEO. You can find it on YouTube.com/GoogleWebDevelop-- Webmasters, sorry. Nearly had a slip there. Right. But that's not the only thing that we are doing. We also thought, hmm, the web usage patterns have changed. Who here has a smartphone? Who here does not like to raise their hands when  

#### [0:14:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=840) |  questions are asked? Caught you. So, like,

pretty much many people have smartphones and use smartphones to browse the web. So we thought it's time for Googlebot to step up its game, right? So we want to represent the way that users actually browse the web. So to do that, we started a multi-year effort called mobile-first indexing. We announced it last year at I/O. And we are happy and proud to update you that we are now over 50% of the sites that we are indexing are indexed mobile-first. So Googlebot has stepped up its game  

#### [0:14:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=870) |  and finally bought a smartphone. That's great.

And it's using the smartphone user agent to crawl your websites. So as not only we are parsing-- sorry, indexing and rendering most sites with a smartphone user agent. We are actually also using-- sorry, seeing more than 50% search results now being actual mobile sites. And I think that represents the users on the web much, much better than it had been before. But none of this would have been possible without your support.  

#### [0:15:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=900) |  Every single one of you who is

making websites that work great on mobile has helped us so much. And we are very grateful for that. Thank you so much for your support, and I hope that you get your continued support on this. So this is for you all. Thank you very much for helping us with this one. [APPLAUSE] JOHN MUELLER: Yeah. MARTIN SPLITT: So there's one thing that I would like to note. And that's that mobile-first indexing does not necessarily mean that we are only indexing mobile sites. We are trying that with pretty much every page, even old desktop pages.  

#### [0:15:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=930) |  So is there something that you should

be doing to make sure that you are doing fine in mobile-first indexing? Well, I mean, the thing is, if you are making a website these days, you want to make sure that the websites that you are serving to mobile and desktop are more or less on par, right? The content should be more or less the same, the text, the images, the videos. But that's not all. It also matters to include things like alternative site links, canonicals. Meta tags for search engines should be also there.  

#### [0:16:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=960) |  Structured data, very important, should also be

in your mobile sites. John is going to talk about cool stuff happening in structured data as well. So make sure that this works. And what we noticed is that basically the thing is if you use multiple different URLs, that's a little tricky sometimes to do. So we highly recommend that you actually try to make a responsive website that responds to the different sizes of screens and not use a www URL and an m dot URL.  

#### [0:16:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=990) |  Because then the question is, what should

go into the index? What should we serve? So you can make your life easier by having just one version. Also, we are probably going to make sure that we alert you if there's changes to mobile-first indexing. And we have a lot of stuff that is still to be done on our side. But we'll keep you updated as the updates come. So definitely keep an eye on our blog and our Twitter feeds. And yeah, I mean, the question is, can we maybe eventually switch to mobile-first indexing for everyone?  

#### [0:17:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=1020) |  100% is what we are striving for.

So definitely keep an eye on what we are saying on Twitter and our blog. Right, with that said, once your page is actually in the index, it might show up in search results. So is there something that you can do to make it stand out a little more? And I think that the most straightforward thing for the simple search results that we are having here in this example is you want to make sure that the title is actually very useful for the user and makes clear what the page is about.  

#### [0:17:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=1050) |  But that's not the only thing. Titles

are something that you give us. But we might not exactly show them the same way, or we might change them slightly for the different queries that people are asking. So don't worry if your title doesn't show up exactly like you specified it in search results. That's a good thing. We are trying to help the user understand better what your pages are about. So do not worry. Just give us a good title to start from. And you'll be fine. The same goes for the meta description. If you give us a meta tag for the description,  

#### [0:18:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=1080) |  we'll show that little snippet. And we'll

try to match what is the best snippet that-- from what you've given us and what is on the page, what's the best thing that we can show for this query for this user in the search results, right? We also try to understand the website when we're indexing not just from these two things. We're looking at every text that is on the website, headlines, image descriptions, alt text. That kind of stuff is also very important for us in indexing and helps us better understand the page and better show it, and basically we want to show your pages in the best possible light.  

#### [0:18:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=1110) |  Speaking of which-- best possible light-- I

think images are a great way to even boost that further, right? This tech stuff is nice. But images are something that helps people understand the information you're presenting more better and more visual. And I think they are a great opportunity for your site. So, John, would you like to talk a little more about images? JOHN MUELLER: OK, fine. MARTIN SPLITT: Yes. JOHN MUELLER: All right, so thanks for the intro  

#### [0:19:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=1140) |  on how Google Search works, Martin. I

think that'll be really useful. But let's talk about images a little bit more. So for example, what if I'm looking for a Halloween costume? Or what if my website is selling Halloween costumes? How do I get those into Google and make them findable? So, we believe that traffic from Google Images is very valuable and applicable to all kinds of different sites because of how we've seen users adapt to images. People come to Google Images for all kinds of visual intent.  

#### [0:19:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=1170) |  You might be coming for an outfit

for a birthday party, designing your living room, planning a wedding, finding a Halloween costume. Or maybe you're looking for a vegetarian recipe for friends coming over. Or maybe you're just using GIFs to respond to a text that you received. So we realized that with all of these things that users come to Google Images for, from planning an event to learning about fashion, they're not just looking for the image.  

#### [0:20:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=1200) |  They're looking at the image as a

gateway to the content underlying it. The image is sometimes just an ideal snippet to show in Search. So we've done a number of things to improve Google Images for users and for developers like you all. And as a result, publishers are benefiting more and more from engaged users. So let's take a quick look at what Google Images has been working on. So here is an overview, very briefly, of how we've evolved Google Images. Consider I want to build a tire swing with my niece.  

![](https://i.ytimg.com/vi/ufcijo46LCU/maxres2.jpg)



#### [0:20:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=1230) |  Previously, when I search for "kids tire

swing," I would just see all kinds of images of, well, tire swings, I guess. But it was hard to tell what I would get from there. So now when I look at the results in Google Images, I get a lot more context. So it really helps me understand a lot more what the pages are going to be about, whether that's a guide about how to build a tire swing,  

#### [0:21:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=1260) |  or if it's a tire swing I

can buy online. And this additional context means that I can intentionally navigate to the content and to the site that's most relevant to my interests. And similarly, there's a lot of metadata that's shown here in the search results that really makes it easier for me to understand what I'm going to get. So now I have a bunch of tire swing pages bookmarked to check out with my niece, so I'll get started on that. So, tire swings look really cool.  

#### [0:21:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=1290) |  And I'm going to take a ton

of photos as I move along and put these photos on my blog. But how do I get these into Google Images then? What recommendations do I have to follow? Well, for Google, it's pretty straightforward. I mean, it doesn't get simpler than this. First, you really need to make great websites and have fantastic images. These are things that we really watch out for. It's kind of obvious, I guess. And then on those pages, we have to see those images prominently  

#### [0:22:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=1320) |  for visitors and for search engines. It

really has to be clear to us what this page is about and that the image plays an important role here. So you should give us more context about those images by placing text around the images and by using appropriate alt text where it makes sense to understand more about the image and how it might be interesting in Search. And similarly, if something is important, don't embed it in the image, but rather keep it in text form  

#### [0:22:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=1350) |  so that we can really find the

text and understand what this image is about rather than trying to decode the image. And structured data-- we've heard about structured data quite a bit so far. Structured data gives a lot more context about the images. So that is really something that I'd recommend using whenever you can. With structured data types, like product and recipe in particular for images, you can give us  

#### [0:23:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=1380) |  information about pricing, availability, ratings, cooking time,

ingredients, and a bunch more. We'll have additional details on that later on in this session. And finally-- this is kind of easy as well-- use descriptive file names and a clean URL structure whenever you can. So it's not that we won't be able to recognize an image if it just has a number as a file name. But it does help us a little bit.  

#### [0:23:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=1410) |  So, similar to how Martin showed with

links, where we really need to get HTML, with images, HTML is also important. And it really makes sense to do something that's semantically correct so that it's clear to everyone who's looking at the HTML page what this is. So in particular, we don't pick up images that are only embedded using CSS styles. That's really hard for us to tell that it's supposed to be an image because it's in completely different locations.  

#### [0:24:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=1440) |  Whereas if it's an image tag, we

can pick that up. We see in alt text for that, and we process that right away. So the basics will help you get started and enable your site to be shown in Google Images. But you can go further. I'm sure you want to do that. So responsive images, for example, are a great way to provide different resolution images by device type. These can be implemented in a search-friendly way using the picture element and the source set attribute.  

#### [0:24:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=1470) |  And another thing a lot of modern

sites use is lazy loading. So with that, you can speed up the loading of your pages. We recommend using JavaScript that leverages IntersectionObserver and using a polyfill where you need to do that. And that new lazy loading that you might have heard of in the developer keynote that's coming to Chrome-- that just works by default. So if you're going to go that direction, that'll work perfectly. And finally, we've talked about this a little bit.  

#### [0:25:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=1500) |  Martin mentioned this, I think, twice-- robots.txt.

So Googlebot is a polite crawler. If your images are blocked by robots.txt, then we can't crawl and index those images. So if you want them indexed, then make sure they're accessible. So, that sounds pretty good. But we also have one new thing when it comes to Google Images. So let's take a look. Woohoo. So we're really excited to announce a new program that'll  

#### [0:25:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=1530) |  be available soon, specifically for websites with

fantastic, large, and high-resolution images. Users really love seeing larger images since they can provide a lot more context about a page. And accordingly, showing bigger images in Search can give your pages a little bit more attention. So if you have large images on your website and you want to make those accessible to users directly through Google products, you'll be able to opt in to displaying these soon. So we'll have details about that.  

#### [0:26:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=1560) |  And the current plan looks something a

little bit like this. So we'll have a combination of a setting in Search Console where you can tell us this site is interested in taking part in this process. And additionally, per image, using structured data markup like this, you can tell us which images you'd like to have indexed. So here's a rough idea of what that'll look like. We'll have full details on this later on, including a license  

#### [0:26:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=1590) |  URL that you can use, some sample

code, more information on the Search Console functionality. So I'd keep an eye on the Webmaster Central Blog to find out more. Wow, that's a lot. So a lot of-- another cool source of traffic is Google Discover. So the Google Discover feed is a feature in Google Search that helps users stay up to date on all of their favorite topics without actually needing any queries.  

#### [0:27:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=1620) |  So it's kind of like Search without

having to search. Users get to their Discovery experience in the Google app, on the Google.com mobile home page, or by swiping right on the home screen on a Pixel phone. It's grown significantly since launching in 2017 and now helps over 800 million monthly active users get inspired and explore new information, perhaps from your website as well. So, Discover surfaces is the best of the web regardless of publication date, from recipes all the way  

#### [0:27:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=1650) |  over to human interest stories, to fashion

videos, and more. We have a guide for optimizing for Discover that's linked here. And of course, images play a big role there too. So as you can imagine, having large images in Google Discover can make your pages particularly compelling to users. Should you opt in to displaying large images in Google product, we'll also be able to show these directly in the Discover feed like that too. So if you're curious, sign up or watch out  

#### [0:28:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=1680) |  for the Webmaster Central Blog, and learn

more about the information there. So another thing that's coming to Google Images fairly soon is the "swipe up to navigate" interaction. And so when your website uses AMP mobile pages, and a user clicks on an image preview, then Google Images will automatically prefetch and render a preview on the bottom. That lets the user swipe up to instantly interact with your content.  

#### [0:28:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=1710) |  No more page loading delays. Instant gratification

thanks to the pre-rendering support in AMP. So net net, your existing AMP pages give you better visibility. They work in a new place. And they get you engaged audiences interested in your content. So we've looked at flat images. But how could it be taken to the next dimension? Imagine you're studying human anatomy and wanting to learn about muscle flexion.  

#### [0:29:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=1740) |  What if you could view a 3D

model, in this case, from our partner, Visible Body, directly in the search results? Or how about a model that you can pull out and see directly on your desk? So it's one thing to learn about flexion or extension, but it's another thing to see it right in action in front of you. So for example, if you work with a furniture store website, you could enable users to see your products in 3D directly in the search results and to pull them out and view them in augmented reality directly from Search. How cool is that?  

#### [0:29:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=1770) |  So today, we're working with a small

set of partners to start bringing this content from websites into Search. We hope to be able to index more models from other sites in the future. There are various tools that you can already use to bring your 3D content to the web, for example, the open source model-viewer component makes it really easy to add 3D content without needing to have any specialized knowledge. So this is the same viewer that powers essentially the  

#### [0:30:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=1800) |  features in Search as well. So, shifting

gears a little bit-- what other elements are critical for Search on a website? Well, structured data is one we've talked about a bit-- a few times. So let's take a quick look at some of that. So once upon a time, Search was really bland and blue-- links to great websites, but just a small text snippet with information about why they're good results for the user.  

![](https://i.ytimg.com/vi/ufcijo46LCU/maxres3.jpg)



#### [0:30:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=1830) |  This is what Search looked like in

1998. And it's been awhile. So how can you make your search results stand out a little bit more than just this? So in comes structured data. In the old days on websites, it's mostly about text on a page. So here, basically HTML. There's some list items that are marked up, but we don't really understand what this page is about. With structured data, you can provide the same information in a machine-readable way directly on your pages.  

#### [0:31:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=1860) |  There are multiple supported formats that we

provide. We recommend using schema.org vocabulary with JSON-LD structured data markup. So to get started, I recommend going to the Search developer's documentation and review the search types that you find relevant there and implement them maybe on a test page. I'd recommend starting with just one type so that you can get a feeling for the steps that are involved. It's easiest to take just a sample page from your website,  

#### [0:31:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=1890) |  copy it into a temporary location, and

work on that. Use the appropriate testing tool to make sure that it's working. There are different tools for different types, so watch out for that. And when your sample page works, then you can add structured data to your real site. So, when will it be shown? Remember how Martin mentioned that crawling and indexing takes time? Well, it also takes time for structured data to be visible in the rich results.  

#### [0:32:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=1920) |  So keep in mind structured data can

make your pages eligible to be shown into rich results, but it doesn't guarantee it. So if over time you see it doesn't work, we recommend checking three things. First, the markup needs to be technically correct. Second, it needs to be implemented in a way that's compliant with our guidelines. And finally, the overall website quality is also critical for developers as well because if Google's systems aren't sure about the quality of the website,  

#### [0:32:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=1950) |  then your work, the structured data, might

not result in rich results being shown. So, how do you work on quality? I recommend trying to get really honest and hard feedback about the website. This is a screenshot from an older blog post with ideas to look at. A good source of feedback is from your users, maybe doing a user study, getting feedback from other users. And when in doubt, I'd also recommend  

#### [0:33:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=1980) |  checking in with other people who've had

similar problems. In other words, check in with your Piers. So I think he's sitting back there. Hi, Piers. And actually, what I meant is checking in with your colleagues and webmaster peers. So, for example, there are lots of awesome folks in the Webmaster Help forums who've probably seen a lot of similar cases and can help point out issues to work on.  

#### [0:33:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=2010) |  So, what are some newer types that

you might not have heard about? We'll run through this fairly quickly. One of the recent types is the how-to markup. This is for step-by-step tutorials on real-world tasks. So this is a great way to help users find out what they should be doing to kind of do the steps that you're looking for. So you can specify the steps with videos, images, and with text. How-to markup is pretty easy to do.  

#### [0:34:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=2040) |  Structured data is specified in our developer

documentation. So it's mostly just a matter of filling that out. Another cool form is for question and answer pages. So QA pages or web pages that contain one question which users are commonly seeking an answer for, often about a product or service that you have. For example, you might use this for individual customer support requests that your business gets. And similar to QA pages, there are frequently  

#### [0:34:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=2070) |  asked questions pages that have multiple questions

on them. So that's a great way to help answer questions about your products and services. And there is structured data for more than just really fancy features. Dates matter as well. So we have a bunch of guidance on dates and how you implement them in Search in the link here. And the short version is kind of that it's important that you be consistent with dates so that we really can confirm that the date and the time  

#### [0:35:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=2100) |  and the time zone are actually matching

across your pages. So you can do that with structured data, of course. Specify the date in a machine-readable way, include the correct time zone, and make sure that it really matches what is shown on the page. And there are lots more types of structured data and rich results that you might want to implement. These are just some of the newer ones. As site owners often ask us, how do you manage this?  

#### [0:35:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=2130) |  How do you keep track? Like, Martin,

do you have any ideas on what-- MARTIN SPLITT: I do. JOHN MUELLER: --people should be doing? MARTIN SPLITT: Thank you so much for John's fantastic introduction to all the new structured data stuff. And if you want to basically manage that and maintain that, I highly recommend checking out Search Console, right? Search Console is pretty much your window into the world of Search when it comes to your sites. And how that works is you have to tell us or prove to us that you actually are the legitimate owner of the domain. You can do that with various ways.  

#### [0:36:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=2160) |  You can use a token in your

HTML. You can use something else. They have a few methods available. You can also use a domain name, which is kind of nice. And that's the very first step. The next step is that you basically do what the setup instructions tell you. And if you're building websites for other people, so if you're an agency for instance, you can use an API to do that. So you don't have to basically do that manually for every site that you're managing. It takes us a little while to verify your site and aggregate all the data.  

#### [0:36:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=2190) |  But after a couple of days, once

we have the data available, we basically show you all the details. By the way, if you're using the domain name, that's quite cool, because it includes all the subdomains and all the different sites under this domain name as well. So that's something you want to check out. It's relatively new domain properties. So if it's been a while since you used Search Console, or you never use it, but you use Webmaster Tools, you might want to have a look again because the UI has changed a lot. And we are still expanding it to match the functionality  

#### [0:37:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=2220) |  that the old tools had. So we're

not done there yet, but pretty much everything vital has been moved. So you can definitely use the things, the new reports, that we have in the new tool. But feel free to switch to the old tool whenever needed. That's absolutely fine. But we don't just want to make a new, shiny interface. We actually thought about it from the ground up. How can we help you achieve the tasks that you have to do quicker and easier? So what can we do to help you be more successful in Search as a site owner?  

#### [0:37:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=2250) |  And we think that one of the

great new reports that we have here is the index coverage report that helps you identify which pages are in the index, which are not, and why they're not, and if there's problems that you should definitely look into. All of this is visibly straight in this report, right? And we can also help you identify and recognize issues that we just detected as they come up. So for instance, what if you deploy something, and a set of pages just suddenly return server errors or 404s?  

#### [0:38:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=2280) |  We can tell you about that. That's

really, really useful. Also, once we have notified you of the issue, you can basically drill down into samples of this issue occurring on your site, double-check that the issue actually still exists, and then work to resolve it. It's pretty easy to check that you fixed the problem. There's a button that you can say, verify fix. And once you know that you have fixed the problem, you can ask us to reprocess that URL and the URLs that are affected by this issue. And we bring you back into the Search results really quickly. So this is pretty unique. It's a unique feature.  

#### [0:38:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=2310) |  And it has helped users to significantly

be faster at improving your websites. Also, we have this lovely performance report that helps you understand how you're performing in search results. And it gives you 16 months of data. So that's pretty cool. You can see that evolve over time. We also show you Discover feed performance. It's a separate feature and really useful as well. And on top of that, we also bring this information into Search results. If you search for your own content and you're logged in, you'll see it right in the Search results. You don't have to actively go to Search Console anymore.  

#### [0:39:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=2340) |  So that's pretty cool. AMP pages, structured

data, all that has aggregated reports as well. So if you want to dig into these details, definitely do that. Also, we have a new speed report. Sign up for the test. We tweeted it from the Google Webmasters account. Definitely sign up. Give us feedback before we roll it out. And if you want to participate, that is fantastic. And I think to sum it up, Search Console wants to be the dashboard for the features of the future. We want to give you control over your sites and Search.  

#### [0:39:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=2370) |  And that's what we want to use

Search Console for. A fun example-- Duplex on the web. You heard about it. You can use robots.txt to let us not do that. But I think it's pretty cool to be able to perform transactions on the web automatically. You don't have to do anything like that. We do the machine learning for you that basically enables all of these features, right? And if you want to prepare, verify your site in Search Console. New features are coming to Search Console to help you. We'll give you more updates on the Google Webmasters Blog, so definitely subscribe and check that one out. And I think [EXHALES] to just quickly sum it up,  

#### [0:40:00](https://www.youtube.com/watch?v=ufcijo46LCU&t=2400) |  I believe Googlebot is now mostly smartphone.

And we are continuing that journey, so that's pretty cool. JavaScript's welcome as well. We have-- JOHN MUELLER: Yeah, users love really high quality, large images and showcasing your site in Google products like Search and Discover. So we'll have more on that soon. And-- MARTIN SPLITT: And? JOHN MUELLER: --there are many ways that your content can be highlighted in Search. So it's worth checking out the Search Gallery and our documentation to find out what works for you.  

#### [0:40:30](https://www.youtube.com/watch?v=ufcijo46LCU&t=2430) |  MARTIN SPLITT: And last but not least,

use the Search Console to get the most out of Search. And I think with that, we just want to let you know the web keeps evolving. It's a powerful platform. And Google Search is here to help your users and others unlock this potential via Google Search. Thank you very much for coming. Have a fantastic day. Enjoy. [APPLAUSE] [MUSIC PLAYING]  