[![Page Speed: SEO Mythbusting](https://i.ytimg.com/vi/XUOD6pcvnso/maxresdefault.jpg)](https://www.youtube.com/watch?v=XUOD6pcvnso)

## Page Speed: SEO Mythbusting

In the third episode of SEO Mythbusting season 2, Martin Splitt (Developer Advocate, Google) and Eric Enge (General Manager of Digital, Perficient) discuss the most common SEO questions and myths around page speed.



Specific timestamped topics discussed in this episode:

The general misconception about page speed & ranking (0:00)

Why is page speed important? (1:57)

Page speed vs content relevancy (3:00)

Average vs recommended web page size (4:54)

Page speed optimization (5:48)

The intricacies of Lighthouse reports, data, and scores (7:44)

Page speed on the different user devices and connections (9:18)

Page speed, Accelerated Mobile Pages (AMP), and Progressive Web Apps (PWA) (11:36)

More on page speed as a factor in Google Search ranking (13:06)



Documentation mentioned in this episode:

Evaluating page experience → https://goo.gle/2ZOnBd3 

Why performance matters → https://goo.gle/3hmaHJh 

Mobile page speed - industry benchmarks → https://goo.gle/3joze29 

Lazy loading → https://goo.gle/30wEGYh 

Lighthouse → https://goo.gle/3jqspgD 

Chrome User Experience Report → https://goo.gle/2WHxLdP 

Progressive Web Apps → https://goo.gle/3fQ95XQ 



Watch more SEO Mythbusting episodes → 

https://goo.gle/SEO-Mythbusting  

Subscribe to Google Search Central → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=XUOD6pcvnso&t=0) |  MARTIN SPLITT: What do you think are

misconceptions about page speeds and especially page speed and ranking? ERIC ENGE: Well, a lot of people think that it's a big ranking factor. In fact, I was literally looking at a document that a company had produced. This document actually talked about SEO, and it had a section on SEO which is good. At least they're thinking about it. But the first thing they listed was page speed. And they were actually quite insistent in the write up that it was the most important ranking factor. MARTIN SPLITT: Oh, no. ERIC ENGE: And I was like, OK.  

#### [0:00:30](https://www.youtube.com/watch?v=XUOD6pcvnso&t=30) |  I've got to find the right way

to tell them that I want them to deal with this because it's really important. And it clearly impacts user engagement and conversion. No, it doesn't mean you're going to move up three spots in the results. MARTIN SPLITT: Right. Yeah. [MUSIC PLAYING]  

#### [0:01:00](https://www.youtube.com/watch?v=XUOD6pcvnso&t=60) |  MARTIN SPLITT: Hello and welcome to another

episode of SEO Mythbusting. With me today is Eric Enge. And would you like to introduce yourself? Because you're doing so much stuff. What is it that you're doing? ERIC ENGE: Well, you know, I'm General Manager of part of the digital marketing team at Proficient Digital. And altogether, we do SEO, content creation, content marketing, pay per click, analytics, conversion rate  

#### [0:01:30](https://www.youtube.com/watch?v=XUOD6pcvnso&t=90) |  optimization-- MARTIN SPLITT: Trainings, Twitter, conference speaking.

ERIC ENGE: Yeah. That's a fair amount of stuff to keep us busy. MARTIN SPLITT: A fair amount of stuff to keep us busy. But today we're going to get busy talking about page speed. ERIC ENGE: It's a great topic. Because so many people get it wrong. MARTIN SPLITT: Oh. yeah. It's quite a deep topic as well. ERIC ENGE: Yes. MARTIN SPLITT: So what kind of questions do you have around ranking, factor, trade speed, and page speed in general? ERIC ENGE: So let's actually start in general and just talk about why page speed is important. How's that sound? MARTIN SPLITT: Sounds fantastic.  

#### [0:02:00](https://www.youtube.com/watch?v=XUOD6pcvnso&t=120) |  I think if you look at what

you're trying to accomplish as you're trying to accomplish that, you're building a good website for your users. Right? ERIC ENGE: Right. MARTIN SPLITT: So now, how many times have you been on the metro or in the car or somewhere in the countryside where you didn't have fantastic reception on your mobile phone? And you were basically just like really quickly trying to find something out and it just took ages for the content to actually show up. That's painful, isn't it? ERIC ENGE: It is painful. MARTIN SPLITT: And in fact, on some sites that can happen when you are in a place where you've  

#### [0:02:30](https://www.youtube.com/watch?v=XUOD6pcvnso&t=150) |  a perfectly strong signal. MARTIN SPLITT: That's

actually true Yeah. Yeah. ERIC ENGE: And that's not-- that's so frustrating. MARTIN SPLITT: Right. And you don't want to frustrate your users. ERIC ENGE: Right. MARTIN SPLITT: And we as a search engine do not want to have users frustrated when they see content. So for us it makes sense to consider fast web sites a little more helpful to the users than very slow web sites. Right? ERIC ENGE: It does make sense. And I guess my thought process in this has always been that well, yes, it's  

#### [0:03:00](https://www.youtube.com/watch?v=XUOD6pcvnso&t=180) |  likely that you're using at some levels

a ranking factor. But you can't make it such a strong ranking factor that you won't show the most relevant content. MARTIN SPLITT: Oh, yeah. Absolutely. If you have bad content, if you are the fastest website out there but the content is not great, then that's not helping you. ERIC ENGE: Right. Right. I mean, to get the content you don't want quickly is probably not what the user's looking for. MARTIN SPLITT: Exactly. Like, I have a blank website. It's the fastest website ever. What's the point? ERIC ENGE: Yeah. Well, yes.  

![](https://i.ytimg.com/vi/XUOD6pcvnso/maxres1.jpg)



#### [0:03:30](https://www.youtube.com/watch?v=XUOD6pcvnso&t=210) |  Exactly. But it does make sense to

consider it at least at some level. And there's actually a fun pair of statistics I think they're both from Google. One is that something like 53% of sessions are abandoned if it takes longer than three seconds for the page to load. And then the companion statistic is, and I think it's a little bit old but still, the average page takes 15.3 seconds to load.  

#### [0:04:00](https://www.youtube.com/watch?v=XUOD6pcvnso&t=240) |  What a frightening combination. MARTIN SPLITT: It

is frightening. It's frightening. And it's so many different factors. Right? Sometimes it's slow servers. But sometimes it's just like the server responds really quickly but then there's a ton of JavaScript that has to be processed first. And JavaScript is a very expensive resource because it has to be fully downloaded and then parsed and then executed. But, yeah. So we keep seeing this. And everyone knows this. Anecdotal evidence is there as well. You have studies. You have the anecdotal evidence of you sitting in front of a website going like, ugh. And Just imagine being on a metered connection  

#### [0:04:30](https://www.youtube.com/watch?v=XUOD6pcvnso&t=270) |  where you actually pay by megabyte when

you fly or something. It's like you can buy 20 megabytes for 10 euros or something. And you're like, oh, OK. Open one website. You said, what was it 15 megabyte is the average or something? ERIC ENGE: Well 15.3 seconds is what I'm was talking about. MARTIN SPLITT: Oh, sorry, 15.3 seconds. So you can just imagine how much data you were pulling in these 15 seconds. ERIC ENGE: Yeah. In fact, I did see-- I really was looking at this just yesterday. There is this data from Think with Google  

#### [0:05:00](https://www.youtube.com/watch?v=XUOD6pcvnso&t=300) |  where by market sector it shows the

average web page size. And they're all in the megabytes in every market. And I think your recommendation is 500 k-bytes or less, if I'm not mistaken. MARTIN SPLITT: Yeah, the fewer, the better. The fewer, the better, really. And just think about it. Like I grew up with entire video games on like two or three floppy disks which each fit like a megabyte and a half or something. So why are we doing this on the web now?  

#### [0:05:30](https://www.youtube.com/watch?v=XUOD6pcvnso&t=330) |  ERIC ENGE: Hm. What a great idea.

Well, maybe we should help people speed their sites up. What do you think? MARTIN SPLITT: That's the thing. And that's why ranking these by speed is also an important factor. But as you say, like content still is king. Like there's no question about that. ERIC ENGE: Right. Absolutely. MARTIN SPLITT: How do you think people are thinking about page speed as a ranking factors? Like what are they trying to do when they are trying to optimize for it? ERIC ENGE: Well, in terms of what they try to do,  

#### [0:06:00](https://www.youtube.com/watch?v=XUOD6pcvnso&t=360) |  I think there's a few things that

people are really good at thinking about related to page speed. So I think almost everybody recognizes that images are a potential issue. And certainly, pre-sizing the image rather than making the browser do it, for example, and things like that. And so they get to that first level of optimization. But I think there's other things that they find a lot more difficult. So for example, the idea of not loading the content below the fold  

#### [0:06:30](https://www.youtube.com/watch?v=XUOD6pcvnso&t=390) |  until the content above the fold is

present, of course, that's a little harder to implement. MARTIN SPLITT: We have native lazy loading images for now. So that's something, at least. ERIC ENGE: Yes. It is something. And then I think another thing that they have trouble with is-- and you actually mentioned it a moment ago-- the idea that the way you're hosted and the way your CDN is set up can be big factors if those aren't actually  

#### [0:07:00](https://www.youtube.com/watch?v=XUOD6pcvnso&t=420) |  set up properly. First of all, they

might not have the CDN. But they may have it, and it may not be properly configured as well. MARTIN SPLITT: Configured with caching and stuff. We've seen all of this. ERIC ENGE: Yeah, exactly. And then it could be as simple as, I need more memory in my web server. Or a dedicated server, when I'm on a shared server connection. MARTIN SPLITT: All of that sounds pretty solid. But is there any misconceptions or myths that are going around where like, what's happening here, where is this coming from, is that true?  

#### [0:07:30](https://www.youtube.com/watch?v=XUOD6pcvnso&t=450) |  ERIC ENGE: So I do think, and

maybe I could state the myth almost as an inverse, is they are too focused on just a few surface level factors. And they don't realize there are other layers to this problem. MARTIN SPLITT: There's layers to this, yes. ERIC ENGE: Although there's another thing I can suggest actually as a myth, if you will. Which is if I go into and get my Lighthouse tools report on a page, and I see it says, oh, this will cut six  

#### [0:08:00](https://www.youtube.com/watch?v=XUOD6pcvnso&t=480) |  seconds out of the load time. And

then they do that thing and the page didn't speed up by six seconds. And I don't think people realize that some of these things are threaded. MARTIN SPLITT: Oh, yeah. ERIC ENGE: So yes, I did something good. But I have four other problems that also need to be fixed. MARTIN SPLITT: Yes. ERIC ENGE: So I do see a lot of people getting tripped up on that. MARTIN SPLITT: That's an interesting one. Yeah, and Lighthouse is a tricky one to begin with. Because people are getting confused by the idea that what they are seeing in Lighthouse  

#### [0:08:30](https://www.youtube.com/watch?v=XUOD6pcvnso&t=510) |  is what users are seeing. And that's

not the case. Because you are literally testing from your machine, from your browser, from your internet connection, and not necessarily what real people are experiencing when they're on their mobile phones, on their spotty connection out there. So I think it's important to remember Lighthouse is lab data. And it makes predictions on what you can improve. But that doesn't necessarily mean that, oh, now you're all doing fine. Do you also think that people are paying too much attention to the scores itself? Because I hear that quite a lot.  

#### [0:09:00](https://www.youtube.com/watch?v=XUOD6pcvnso&t=540) |  So like the myth is like, oh,

we're using the Lighthouse score for ranking. That's not happening. That's not what we're doing. ERIC ENGE: Right. No. Exactly. In fact, they get too attached to that score. And sometimes it misleads them to thinking that they are doing just fine when they actually still have problems. MARTIN SPLITT: Yeah. ERIC ENGE: And another area that I see people running into is it works fine from my phone, but the user doesn't have such a nice phone.  

#### [0:09:30](https://www.youtube.com/watch?v=XUOD6pcvnso&t=570) |  So you have to remember that there's

different devices. MARTIN SPLITT: And you could see that in Google Analytics. You can actually figure out what kind of devices you were seeing on your site. And then you can specifically try to understand-- best way would be to buy one of the phones that is most prevalent on your site. ERIC ENGE: Yes. MARTIN SPLITT: And [? I can ?] have a look. ERIC ENGE: A very interesting idea. And I actually shared a slide in one of my presentations recently which showed data actually for CNN.com processing.  

#### [0:10:00](https://www.youtube.com/watch?v=XUOD6pcvnso&t=600) |  And it was around three seconds for

the high speed phone. But by the time you get to a user with a less than $100 phone, it was 15 seconds to load. And you just really need to remember that the users have all different [INAUDIBLE] devices. And you probably want to do a good job by the great majority of them. MARTIN SPLITT: Absolutely. And you want to be aware that a slow phone on a slow connection is like the worst situation you can probably run  

#### [0:10:30](https://www.youtube.com/watch?v=XUOD6pcvnso&t=630) |  into in this kind of situation. And

you can use things like web page test to get a better feeling for how that would feel. Like you can test from different locations and different network connections. I would definitely recommend doing that. There's so much more that you can do. And also, if you have a website that is listed in Chrome User Experience Report or [? CRUX, ?] then definitely use that as well. And I think not many people are trying that out. ERIC ENGE: Right. Well, it's good to get real world data. MARTIN SPLITT: Real world data, real user metrics, absolutely.  

![](https://i.ytimg.com/vi/XUOD6pcvnso/maxres3.jpg)



#### [0:11:00](https://www.youtube.com/watch?v=XUOD6pcvnso&t=660) |  ERIC ENGE: Yeah. Absolutely. In fact, you

could broaden that piece of advice well beyond the page being conversation, by the way. Like it relates to all manner of aspects and things around mobile, for example, because we have everybody who designs for a desktop and then has to slam that down into a mobile phone format. Maybe designed for the mobile and then it's kind of easy to figure out how to run [INAUDIBLE] desktop. MARTIN SPLITT: Exactly. You have more [INAUDIBLE] so yeah. ERIC ENGE: Yeah. Exactly. But for the page speed conversation, absolutely.  

#### [0:11:30](https://www.youtube.com/watch?v=XUOD6pcvnso&t=690) |  You just have to do that. MARTIN

SPLITT: Definitely. Right? And yeah, I mean, it's such an important thing. And people-- do you remember the entire controversy on people like AMP is a ranking factor? ERIC ENGE: Oh my. Yes. MARTIN SPLITT: It's not. And then people are like, but, it-- and page speed pastes into that as well. Right? AMP gives you a certain expectation that you can have for your sites in such results. And I've seen good fast web sites rank higher than the end equivalent. So like, maybe it is not the most important ranking factor.  

#### [0:12:00](https://www.youtube.com/watch?v=XUOD6pcvnso&t=720) |  But it's definitely an important one as

in like page speed is an important ranking factor. AMP, not so much. AMP is just like this little batch that gives the user an expectation that they can have about it. But page speed does matter for your users. And it does matter for your conversions, as you said. Sometimes it's configuring your CDN-- getting a CDN, configuring your CDN, making sure that caching is done right, and making sure that you architect your websites and web apps in the way that they are fast by default.  

#### [0:12:30](https://www.youtube.com/watch?v=XUOD6pcvnso&t=750) |  If you can do that without AMP,

then that's fantastic. AMP is a fantastic tool kit to help you do that if you don't know how. ERIC ENGE: Yeah. And you could go with Progressive Web Apps as well, by the way, which are very nice because of their ability to preload content into the cache on your phone. So by the time the user requests the page, it's [? continuous ?] [INAUDIBLE].. MARTIN SPLITT: Yeah. That's true. ERIC ENGE: And it's another way to skin a cat. No. I'm not supposed to say that. Because that's really uncomfortable for cats. MARTIN SPLITT: It's really uncomfortable for cats. ERIC ENGE: So take it the way I meant it. MARTIN SPLITT: I get it. I get it.  

#### [0:13:00](https://www.youtube.com/watch?v=XUOD6pcvnso&t=780) |  So anything else around page speed where

you're like, what's happening there? Any questions you have on page speed? ERIC ENGE: I mean, really, I guess it's reasonable to presume that there's not any prospect of Google dialing up that ranking notch. It's basically, you're kind of set with what you've done. I mean I know that algorithms change all the time. MARTIN SPLITT: Algorithms change all the time. ERIC ENGE: But just from the logic perspective, the issue that we talked about already between the relevance of the content being--  

#### [0:13:30](https://www.youtube.com/watch?v=XUOD6pcvnso&t=810) |  well, content being king. It's still going

to be king. MARTIN SPLITT: Absolutely. Absolutely. ERIC ENGE: Have to deliver the right result. MARTIN SPLITT: You want the relevant content first. ERIC ENGE: If you had five right results and maybe it nudges something up. MARTIN SPLITT: Like if you have two results that are basically doing fine content wise, we would probably get the one that is faster, more prominence in the search results. And also, I think it's important to understand that we're not doing it by Score or Lighthouse or something like that.  

#### [0:14:00](https://www.youtube.com/watch?v=XUOD6pcvnso&t=840) |  It is more we're bucketing pages into

like this is a programmatically slow one. This is an OK one. And this is a fast one. You see that in the speed report as well, in the Search Console. So I think people need to just like figure out if they have really slows pages, how to make them faster. And probably if they're in the middle bit, you also want to go to the fast bit. But it doesn't matter if you have a Lighthouse score of 90 or 95. That doesn't really make a difference. All right, Eric. Thank you so much for being here and talking all things page  

#### [0:14:30](https://www.youtube.com/watch?v=XUOD6pcvnso&t=870) |  speed with me. That was amazing. And

I hope that everyone liked it and leave comments and likes with us. And thank you very much. ERIC ENGE: Hope you all enjoyed it. MARTIN SPLITT: Bye. Hey, everyone. So next episode is going to be with my fantastic guest Rachel Costello. And Rachel, what have you brought for us? RACHEL COSTELLO: We're going to be talking about canonicalization and URL de-duplication. MARTIN SPLITT: Sounds really cool. Don't miss it. RACHEL COSTELLO: See you then.  