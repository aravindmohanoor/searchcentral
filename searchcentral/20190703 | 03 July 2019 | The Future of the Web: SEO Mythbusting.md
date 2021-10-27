[![The Future of the Web: SEO Mythbusting](https://i.ytimg.com/vi/B3eysnid0Sk/hqdefault.jpg)](https://www.youtube.com/watch?v=B3eysnid0Sk)

## The Future of the Web: SEO Mythbusting

In this final episode of SEO Mythbusting, Martin Splitt (WebMaster Trends Analyst, Google) and his guest Dion Almaer (Director, Web Dev Ecosystem, Google) discuss what technical SEO might look like as the web keeps evolving, such as:

The same content in multiple versions, PWA/desktop site/AMP/etc. vs Google Search and SEO (2:19)

Current & future web & SEO tool integration (Google & third parties) (4:50)

The “unknown” variables & search performance (7:32)

Are web components and virtual scroller compatible with SEO? (10:06)

The future of assistants, and semantic & structured data (12:38)



Documentation mentioned in this episode:



Chrome Dev Summit 18’ - Keynote → https://goo.gle/2ZZulSI 

Search-related tools → https://goo.gle/2XBnwcF 

Web components → https://goo.gle/2XlTlqw 

Virtual scroller → https://goo.gle/326tukX 

Fix search-related JavaScript problems → https://goo.gle/search-js-troubleshooter 



Watch all SEO Mythbusting episodes → 

https://goo.gle/SEO-Mythbusting 

Subscribe to Google Search Central → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=B3eysnid0Sk&t=0) |  DION ALMAER: I feel like there's this

weird, interesting spectrum on the web where, on one end is content, and the other is app. But it blends at a certain point. MARTIN SPLITT: It does blend, it does. DION ALMAER: And it's that blending part that I find is always interesting, where I'd hate for us to be building something in a way that, then, search can't understand that piece. MARTIN SPLITT: Right. Because you want to find the content that lives inside the applications, and you want to still find the applications, right? DION ALMAER: Right. [MUSIC PLAYING]  

#### [0:00:30](https://www.youtube.com/watch?v=B3eysnid0Sk&t=30) |  MARTIN SPLITT: Hello, and welcome to "SEO

Mythbusting." Today, I have Dion Almaer with me. What do you work on? DION ALMAER: I work in the Web Developer Ecosystem group here at Google. And so that's within the Chrome organization, but we work across Chrome, and search, and ads, and all of the different areas of Google that care about the web. Personally, my passion is about the ecosystem.  

#### [0:01:00](https://www.youtube.com/watch?v=B3eysnid0Sk&t=60) |  Hence the name. So it's about looking

at the health of the web, and what are we doing to really help developers, but even beyond developers-- hence the SEO world and the like-- to make sure that people are being successful. So that could be successful in building amazing user experiences, but it's also successful in actually being able to pay the bills, and so they can keep making those amazing user experiences. MARTIN SPLITT: That is great. So when I have you here today, I would love to talk about SEO and the web platform going forward.  

#### [0:01:30](https://www.youtube.com/watch?v=B3eysnid0Sk&t=90) |  So we want to look into it,

like, what are the new use cases, what are the things that are coming up next, and what are the things that we from the search side should be preparing for, let's say. Do you have any highlights that you want to talk about? DION ALMAER: Yes. So I gave a keynote at the Chrome Dev Summit. in November 2018. And it's kind of going through sharing all of these great, amazing web platform updates and tooling updates. In the back of my mind, you're always thinking about, like, are we getting closer to search and helping the word?  

#### [0:02:00](https://www.youtube.com/watch?v=B3eysnid0Sk&t=120) |  Or are we causing more problems going

on? MARTIN SPLITT: Yeah, it's-- DION ALMAER: I'm actually really curious to get some of your thoughts on some of these items. MARTIN SPLITT: Amazing. Do you have any specific things that you would like to address there? Like is there any showcases, or anything that we should look into from a search perspective? DION ALMAER: Yes. So one case study, actually, that we showed was Pinterest. And it really got me thinking, because they came along, and their growth team built this new PWA that-- MARTIN SPLITT: That's fantastic. DION ALMAER: --was-- it's amazing. Like the performance is top notch.  

#### [0:02:30](https://www.youtube.com/watch?v=B3eysnid0Sk&t=150) |  It's a great experience. So they've got

this great PWA that's really exciting. Then they've got their kind of regular desktop site. They've got-- they're using an AMP for different things. And so if I'm a team like that, how do I, like-- I've got all of these kind of different sites, in a way, which is almost like the opposite of the promise of the web at times. Like, build it once, and it was everywhere. So, like, which of these-- how do-- what's the one that I want to give to search? Like how do I think about that? MARTIN SPLITT: That's a really good question. So I think, generally speaking, if you have the same content and multiple ways  

#### [0:03:00](https://www.youtube.com/watch?v=B3eysnid0Sk&t=180) |  that you present them to the user,

find out the one that is most likely to apply to as many people as possible. So if you have one specific thing for, let's say, like, sign up users, to actually remix it or something, that might not be the thing that you want to surface to search. Because me coming into it from outside and not having ever used it, and I might not even be able to use the feature, and then it's like why am I getting here? So try to think of what are people typing into a search bar? What is the purpose they are coming from? I want to see this image board that Dion has created  

![](https://i.ytimg.com/vi/B3eysnid0Sk/hq1.jpg)



#### [0:03:30](https://www.youtube.com/watch?v=B3eysnid0Sk&t=210) |  for a Chrome Dev Summit. So I

might type in, like, image board dev summit. And then I want to get the PWA probably, because it loads fastest, and it is available even if I'm offline, and stuff like that. So give me that. But also link to the end version, because then we can also show the end version next to it. So it's not really a ranking signal, so we might see, like, different rankings there depending on the purpose and the user characteristics, what they type into the search bar.  

#### [0:04:00](https://www.youtube.com/watch?v=B3eysnid0Sk&t=240) |  But if you link them, then we

can make the decision for you so you do not have to worry about that kind of stuff. If you then have a desktop site as well, that is great as well. If it's responsive, that's even better. If it's not responsive, then give us an alternate link so that we can decide, OK, so this is the Google crawler that uses mobile first, so we're probably going to highlight the PWA experience over the desktop site. Versus, if someone's using the desktop site, we might give them the other version rather than that. But we are trying to make the right decisions for your user  

#### [0:04:30](https://www.youtube.com/watch?v=B3eysnid0Sk&t=270) |  so that you don't have to worry

about these things. But, strategically speaking, give us a canonical that makes sense to as many people as possible so that we can surface the related information based on what people are looking for, rather than any differences in the presentation. DION ALMAER: Got it. Cool. The other thing that comes up a lot is integrating our tools together instead of having it in silos. So we've already been working-- we've got Lighthouse over here. We have PageSpeed Insights. We've got search. We've got all of these different pieces. We announced at Chrome Dev Summit  

#### [0:05:00](https://www.youtube.com/watch?v=B3eysnid0Sk&t=300) |  the unification of some of these. The

PageSpeed Insights now uses Lighthouse and the like, and that's super exciting. Wayfair, another company, built this performance portal to kind of help the team make sure that they don't regress. Because we see that, a large percentage of the times, people will, like, do an investment, have a quick burst, get their performance good, and then it will slowly go down. So they have this awesome performance culture that's trying to fix that. And I'm just looking at that, and thinking about it's yet another example.  

#### [0:05:30](https://www.youtube.com/watch?v=B3eysnid0Sk&t=330) |  Like here's all the performance stuff. Couldn't

we be surfacing the kind of SEO pieces into that too? How do we bridge these worlds together-- MARTIN SPLITT: That is [INAUDIBLE].. DION ALMAER: --so both sides can kind of see the other things that are going on? MARTIN SPLITT: So Lighthouse gets more SEO audits, which is great, I think. That probably, at some point, feeds into PageSpeed Insights as well. Search Console integrates some of these metrics as well, because performance is also important for search's core ability. We want to, like, reward the content that gets you-- that gets the user quicker into the content  

#### [0:06:00](https://www.youtube.com/watch?v=B3eysnid0Sk&t=360) |  rather than having to wait forever until

something loads, especially on mobile networks. But for external tools and external companies who want to dig into the data, I think Search Console is a great way of already doing that in a packaged way. But, but we are working on ways of integrating external parties and external content providers and platforms to get the data that we are collecting already for Search Console. So, for instance, if you know one of the many larger content management systems or platforms  

#### [0:06:30](https://www.youtube.com/watch?v=B3eysnid0Sk&t=390) |  that exist out there where people are

creating content, we don't want them to have to specifically go into Search Console, and now, like, deal with the interface they are used to, and then deal with something new. That's why we are bringing the data into these platforms. And, eventually, hopefully, once we have gathered enough information to understand how the data is used and what data is necessary and meaningful to external parties, we will open these interfaces. There will literally be an API to integrate the data from Search Console, which gives you information like click  

![](https://i.ytimg.com/vi/B3eysnid0Sk/hq2.jpg)



#### [0:07:00](https://www.youtube.com/watch?v=B3eysnid0Sk&t=420) |  through rates, how many impressions you get

from search, how many clicks you get from search, all this kind of thing, how many pages of your pages are indexed actually. Because not all of it might be indexed. There might be an issue. You might have a markup problem. We want to surface this where people already are. That can be an IDE integration. That can be something like Wayfair does. But, at this point in time, we are too early on to open that up to the general public, but eventually that's going to happen.  

#### [0:07:30](https://www.youtube.com/watch?v=B3eysnid0Sk&t=450) |  DION ALMAER: That's so exciting. And some

people were talking about how, like, they want to understand the unknown things. Like they wonder where like, what's-- if I do this, that, or the other, how does it affect my customer lifetime value, and these things? And we keep running into something on the performance side where they'll do this work, and they'll make something that's a lot better, but their metrics actually show in the field that it's slower. And we're like, what's going on? Like, in the lab it's faster. It's obviously faster. I can see it's so much better. How is it slower?  

#### [0:08:00](https://www.youtube.com/watch?v=B3eysnid0Sk&t=480) |  And then it's because the reach that

they got just totally changed. So these people are on, like, 2G networks in emerging markets that can actually really use this now. MARTIN SPLITT: That's moving targets. Then you're comparing apples to oranges. DION ALMAER: Right. So you've got all of these new customers. And so the mean metric isn't the thing that matters there. Now you've reached this new audience. You get more revenue, and the like. So, like, how do we know, like, with the search side and discovery, like, what are the things-- the next things I should do? Which shall I prioritize, and the like? MARTIN SPLITT: Right, right. I think a bunch of stuff that Search Console gives you already is kind of handy for that.  

#### [0:08:30](https://www.youtube.com/watch?v=B3eysnid0Sk&t=510) |  You see how certain content works, and

how certain other content might not work so great. And that can have technical difficulty-- sorry-- technical reasons. Or it can be actually content reasons. So what we are trying to do is we're trying to also broaden the perspective a little bit. I mean, you said that. Like, oh, yes, we're in this metric right now. We want to improve performance, but actually it has degraded. And it's like, well, it has, but it's not a bad thing, because what actually happened is we opened up to more people. That happens with search as well if you  

#### [0:09:00](https://www.youtube.com/watch?v=B3eysnid0Sk&t=540) |  look at it from a more holistic

perspective. So if you're not just looking at technology but also at your content strategy. And what I would love to see happening is that, if we bring this data to where people already are, that people become more aware of it, that maybe you should also look at your content and the way you present it, and the way you make sure that you're talking to the person on the other end who's trying to solve a purpose. You're looking for something specific rather than necessarily a specific product.  

#### [0:09:30](https://www.youtube.com/watch?v=B3eysnid0Sk&t=570) |  It's like I need this task to

be gone and done and dusted, and how do I do this? So I think bringing the data to other people will help. And I think what developers should look at is how their content is performing in search engines as well. So how often do I show up in search results? Where in the search results do I rank? How many clicks do I get from search results if the content looks like this versus like that?  

#### [0:10:00](https://www.youtube.com/watch?v=B3eysnid0Sk&t=600) |  So that's something that I hope to

bring to more people as well. DION ALMAER: Cool. Yes, that makes sense. So web components has been another big topic. MARTIN SPLITT: Oh, right, yes. DION ALMAER: And we released an early version of a new one that I'm super excited about called virtual scroller. And, basically, for years, web developers have been saying, like, give me a UI table view on the web that can perform, and scales with the DOM. And so we feel like we're going to be able to deliver that. But then what's that going to mean in the SEO world?  

#### [0:10:30](https://www.youtube.com/watch?v=B3eysnid0Sk&t=630) |  Is search going to be able to

understand this if it's all virtual? And, like, as we kind of push the bar here for performance and user experience, well, how do we make sure we don't leave it behind? MARTIN SPLITT: I think what a lot of people outside of our sphere don't realize is that we are working hand in hand. It's not like SEO-- or search versus the browser teams. We are trying to figure out how we can work with a web platform rather than against it. We are using the web platform. We are basically running a browser, if you wish.  

#### [0:11:00](https://www.youtube.com/watch?v=B3eysnid0Sk&t=660) |  So we are actually looking into things

like components and virtual scroller, specifically. And I think it's a fantastic thing, because we have literally just released documentation for lazy loading, or infinite scroll, whatever you want to call it. Basically-- you know the drill-- I can have a page with a bazillion images or product listings. You can't have them all on the page right away, right? You want to make sure that, as the user goes through the content, they come back. Well, how often did it happen to you that someone sends you a link, says like, have you seen this product? And then you go to the link and you see a lot of things  

#### [0:11:30](https://www.youtube.com/watch?v=B3eysnid0Sk&t=690) |  but not that product. And then they

go, oh, yeah, you have to scroll down for a few minutes. That's not good, right? Web components are another thing that we are, like, really careful about. And we have some guidance out there already, and we expect to give more guidance as well. Because if you build new web components from scratch, they look like they're semantic, but they are not necessarily semantic in the strong sense. If it's a button that just happens to look like a button but really is a diff underneath, you lose a lot of the accessibility features,  

#### [0:12:00](https://www.youtube.com/watch?v=B3eysnid0Sk&t=720) |  and so does search also loses a

bunch of the semantics behind it. So, right now, we are recommending putting the content, the meaty bits of your content, like the actual, well, what it is about, put that into the light DOM, and then to use the shadow DOM and your components for presentation. Virtual scroller is a specific interesting case where not only is presentation but also the way of how the content gets loaded and the content behaves. So we are working on figuring out how to make that consistent with search  

#### [0:12:30](https://www.youtube.com/watch?v=B3eysnid0Sk&t=750) |  so that you don't have to worry

about using these new technologies, because we're really excited about them as well. DION ALMAER: Yes. No, that's great. How do you feel about-- I keep longing for a world in the future where we add, with web components, these different semantics, kind of high-level semantics that search can understand but also assistants can understand, so we can get further into transactions and the like, with the notion of I really want to be able to go onto a commerce experience since I want to buy a T-shirt for Martin.  

#### [0:13:00](https://www.youtube.com/watch?v=B3eysnid0Sk&t=780) |  And everything is brokered in a way

that it knows your T-shirt size even if I don't. You know what I mean? MARTIN SPLITT: Yes. DION ALMAER: And there's a person tag, and all these different things. And then you get a great UI from it too, because it's standardized. But then search could use that, and assistant could do full transactions if we do it. And it feels like that would be a way for assistants to kind of reach the long tail, versus trying to go to everyone who's building a website. It's got a lot of work to do as it is, and we're asking them to modernize this, and fix your performance, and do this for discovery, and also build this thing for the assistant.  

#### [0:13:30](https://www.youtube.com/watch?v=B3eysnid0Sk&t=810) |  MARTIN SPLITT: Yes, that is true. DION

ALMAER: Do you feel like we'll ever get there? MARTIN SPLITT: I think we get there probably quicker than we think, because, conveniently, we have already pushed the idea of using structured data to expose, like, a bunch of information on your pages in a way that not only our crawlers can understand them, but also anyone else who basically parses this information. And we are using schema.org for that. So we use, like, a standardized format rather than just a proprietary thing. So I hope that gets more adoption  

#### [0:14:00](https://www.youtube.com/watch?v=B3eysnid0Sk&t=840) |  and we see it both picked up

by developers and by these assistant systems. Because, then, you can use the web really powerfully because you have all the semantic data that you can just pull together, and then package in such an experience as you explained, like the full end to end commerce, for instance. DION ALMAER: Cool. Nice. MARTIN SPLITT: Man, thank you so much. DION ALMAER: Thank you, Martin. MARTIN SPLITT: Thank you. See? Development and SEO don't have to be contradicting each other. Also, the iced tea is pretty not good.  

#### [0:14:30](https://www.youtube.com/watch?v=B3eysnid0Sk&t=870) |  [LAUGHS] Pretty watery. But it has the

fantastic right color. Like, you picked the exact, correct prop. [MUSIC PLAYING]  