[![Site Speed: What SEOs Need to Know #AskGoogleWebmasters](https://i.ytimg.com/vi/7HKYsJJrySY/maxresdefault.jpg)](https://www.youtube.com/watch?v=7HKYsJJrySY)

## Site Speed: What SEOs Need to Know #AskGoogleWebmasters

In this special episode of Ask Google Webmasters, John is joined by Martin Splitt, Webmasters Trend Analyst at Google, as they discuss questions around site speed and SEO, such as:

- What is the ideal page speed of any content for better ranking on SERP? (submitted by @rsthakur1988) (0:21)



- If a website's mobile speed using the Test My Site tool is good and GTmetrix report scores are high, how important are high Google PageSpeed Insights scores for SEO? (submitted by @olgatsimaraki) (1:27)



- I am testing an almost empty page on devtools Audits (v5.1.0) it usually gives minimum results which 0.8ms for everything and 20ms for FID but sometimes it gives worse results in TTI, FCI and FID. Same page, same code. Why? (submitted by @onurcelik66) (2:49)



- What is the best metric(s) to look at when deciding if page speed is “good” or not? Why / why not should we focus on metrics like FCP / FMP instead of scores given by tools like PageSpeed Insights? (submitted by @drewmarlier) (4:21)



Useful links related to this episode:

PageSpeed Insights docs → https://goo.gle/2pUA0wF 

Lighthouse scoring guide → https://goo.gle/2BS4Wk0 

How to think about Speed tools → https://goo.gle/2PpaD0I 

What is speed? → https://goo.gle/31Wuxme 

How to measure speed → https://goo.gle/2WpPa9h 



Send us your questions on Twitter with the hashtag AskGooglebot and your question might be answered! 

Google Search Central on Twitter → https://goo.gle/3f4Z0a8



Watch more AskGooglebot episodes → https://goo.gle/2OjWcvS

Subscribe to Google Search Central → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=7HKYsJJrySY&t=0) |  [MUSIC PLAYING] JOHN MUELLER: Welcome, everyone, to

a special episode of Ask Google Webmasters. Here today is Martin. MARTIN SPLITT: Hi, everyone. And this is John. JOHN MUELLER: Hi. Yeah, we're going to be answering questions on the topic of speed that were submitted with the #AskGoogleWebmasters on Twitter. So let's start off with a question from Rohit. What is the ideal page speed of any content for better ranking on Search? MARTIN SPLITT: Oh, you're asking me that question. OK. So basically, we are categorizing pages,  

#### [0:00:30](https://www.youtube.com/watch?v=7HKYsJJrySY&t=30) |  more or less, as really good and

pretty bad. So there's not really a threshold in between, it's just we are, more or less, roughly categorizing the speed experience for users. And how are we actually doing that? Where do we get the data from? JOHN MUELLER: Yeah. That's important. So we mostly get data from two places. On the one hand, we try to calculate a theoretical speed of a page using lab data, and then  

#### [0:01:00](https://www.youtube.com/watch?v=7HKYsJJrySY&t=60) |  we also use real field data from

users who have actually tried to use those pages. And that field data is similar to the Chrome User Experience Report data. MARTIN SPLITT: Cool. So we are having hypothetical data and practical data. So we don't really have a threshold to give away, but basically the recommendation I would say is just make sites fast for users. That's what it boils down to. JOHN MUELLER: That sounds good. Yeah. MARTIN SPLITT: The next question comes from Olga. And Olga is wondering if a website's mobile speed is best  

#### [0:01:30](https://www.youtube.com/watch?v=7HKYsJJrySY&t=90) |  looked at using the Test My Site

tool, the GTmetrix tool, or PageSpeed Insights? Hm. That's a really good question. What's the most important tool for SEO? JOHN MUELLER: We have multiple tools that measure multiple things. And I can understand that that can be kind of confusing at times. In general, these tools measure things in slightly different ways. So what I usually recommend is taking these different tools, getting the data that you get back from that,  

![](https://i.ytimg.com/vi/7HKYsJJrySY/maxres1.jpg)



#### [0:02:00](https://www.youtube.com/watch?v=7HKYsJJrySY&t=120) |  and using them to discover kind of

low hanging fruit on your web pages-- so things that you can easily improve to really give your page a speed bump. How's that sound? MARTIN SPLITT: Yeah. That sounds pretty good. And also, the tools are differently aimed. Some of these tools, like Test My Site, is pretty high level, so everyone understands roughly what's going on there. Whereas, GTmetrix is a lot more technical. And PageSpeed Insights, I think, is kind of in the middle of that. So depending on who you are catering to, who you are trying to give this report to get things fixed,  

#### [0:02:30](https://www.youtube.com/watch?v=7HKYsJJrySY&t=150) |  you might use one or the other.

So figuring out what is the low hanging fruit and using the tool that gives you the best insight into that for the audience that you are trying to convince. Is it a C level? Is it another marketer? Is it someone from the tech side, like is it a developer? Then, you'd probably pick a different tool. JOHN MUELLER: Next question comes from Onur. Onur is asking, I am testing an almost empty page on DevTool audits, and it usually gives me minimum results, which are 0.8 milliseconds for everything,  

#### [0:03:00](https://www.youtube.com/watch?v=7HKYsJJrySY&t=180) |  and 20 milliseconds for FID. What is

FID? MARTIN SPLITT: First input delay. JOHN MUELLER: First input delay, of course. But sometimes, it gives worse results for TTI, FCI, and FID. MARTIN SPLITT: Right. OK, let's talk about these metrics. FID, we have covered, first input delay. TTI is time to interactive. That's when you can first interact with the page. And FCI is first CPU idle, which means that there is no more JavaScript work or other work that  

#### [0:03:30](https://www.youtube.com/watch?v=7HKYsJJrySY&t=210) |  needs to be done by the CPU.

JOHN MUELLER: So it's the same page, same code, different numbers. Why would that happen? MARTIN SPLITT: Well, first things first. These measurements aren't perfect, right? So if it's between 0.8 milliseconds and 20 milliseconds, 20 milliseconds is a lot more than 0.8, but it's still quite a short amount of time, if you think about it. You roughly have 10 milliseconds for a single frame to draw. So yeah, 20 milliseconds isn't too bad. So you will always see some, basically, noise  

![](https://i.ytimg.com/vi/7HKYsJJrySY/maxres2.jpg)



#### [0:04:00](https://www.youtube.com/watch?v=7HKYsJJrySY&t=240) |  in that measurement. And also, don't get

too hung up on these metrics, specifically. If you see that there's a perceptible problem, and there's actually an issue that your site stays working on the main thread and doing CPU work for a minute or 20 seconds, that's what you want to investigate. If it's 20 milliseconds, it's probably fine. Our next question comes from Drew. And Drew asks us, what is or are the best metric or metrics to look at when you want to decide  

#### [0:04:30](https://www.youtube.com/watch?v=7HKYsJJrySY&t=270) |  if a page is fast or slow?

And why or why not would you just look at things like FCP, which is first contentful paint, FMP, which is first meaningful paint, instead of just the scores that these tools give you? JOHN MUELLER: Wow. I don't know, Martin. You need to tell me some more about that. MARTIN SPLITT: Right. OK, so I guess the question here really boils down to, what's the metric that you should look at? And that's a really tricky one, because I guess it depends on the site. It's the typical "it depends" answer.  

#### [0:05:00](https://www.youtube.com/watch?v=7HKYsJJrySY&t=300) |  If you have just a website where

people are reading your content and not interacting as much, then I think first meaningful paint or first contentful paint is probably more important than first input delay or time to interactive. But if it's a really interactive web application where you want people to immediately jump in and do something, then probably that metric is more important. So don't try to break it down. And that brings us to the scores. The problem with the scores is they are oversimplifying  

#### [0:05:30](https://www.youtube.com/watch?v=7HKYsJJrySY&t=330) |  things, aren't they? JOHN MUELLER: Yeah, it

sounds like it. I mean, all of these measurements sound like they're measuring different things and ultimately trying to understand what a user would perceive when they access the page. So a score might be, I guess, a simple way to look at it overall, but it's probably not all of the details that you'd need. MARTIN SPLITT: It just gives you a ballpark, really. It's like, how fast is this page? Five. What does that mean? It doesn't really convey meaning, doesn't it?  

#### [0:06:00](https://www.youtube.com/watch?v=7HKYsJJrySY&t=360) |  So I would say, use that to

figure out how you're roughly doing, and then use the specific insights the different tools give you to figure out where you have to improve or what isn't going so well. JOHN MUELLER: Wow. Yeah, sounds like speed is a tricky topic. And you kind of have to know what you're measuring, so that you can take action on the right things. MARTIN SPLITT: Yep. JOHN MUELLER: So would that explain why there is no simple number that Google is just giving? MARTIN SPLITT: Yeah, so that definitely explains it.  

![](https://i.ytimg.com/vi/7HKYsJJrySY/maxres3.jpg)



#### [0:06:30](https://www.youtube.com/watch?v=7HKYsJJrySY&t=390) |  Because if you think about it, you

can't break down speed into one simple number. It is a bunch of factors. If I am painting really quickly, but then my app is all about interaction, it's a messenger, so I show everything, I show the message history. But if I try to answer the message that I just got and it takes me 20 seconds until I actually can tap on the input field and start typing, is that fast? Not really. But is it so important that I can use the contact form on the bottom of a blog post within the first 10 seconds?  

#### [0:07:00](https://www.youtube.com/watch?v=7HKYsJJrySY&t=420) |  Not necessarily, is it? So how would

you put that into a number? You don't. So I guess it's hard. JOHN MUELLER: Speed? Speed sounds hard. What do you think? Will this get easier? MARTIN SPLITT: I guess it will get easier, but it will never go to a point where you just have a score that you optimize for and be done with It, right? It is such a broad topic that it's really hard to break that down into one number.  

#### [0:07:30](https://www.youtube.com/watch?v=7HKYsJJrySY&t=450) |  JOHN MUELLER: OK. So you imagine the

more advanced people will continue to focus on the counting metrics and counting milliseconds, and others will look at a bigger overview picture? MARTIN SPLITT: I guess so. JOHN MUELLER: And together, we'll try to find ways to improve the speed of the pages, overall. MARTIN SPLITT: I think browsers are also doing a lot of work to make things faster, in general, and easier to understand. But generally speaking, you will still need to go and do the work of figuring out what matters to you, your audience, and your website, right?  

#### [0:08:00](https://www.youtube.com/watch?v=7HKYsJJrySY&t=480) |  Is it interactive? Is it contentful paints?

Depends. JOHN MUELLER: That sounds cool. Yeah. So I expect more questions on speed on the #AskGoogleWebmasters. And as we get those questions, we'll ask an expert, like Martin, who knows all of these three-letter abbreviations, and who can help us figure out which ones are the right ones. So thanks, for submitting all of these questions. And hopefully, see you again on one of the future episodes, Martin. MARTIN SPLITT: Hopefully. Thank you, very much, for having me. And thanks, for all the questions.  

#### [0:08:30](https://www.youtube.com/watch?v=7HKYsJJrySY&t=510) |  [MUSIC PLAYING]  

