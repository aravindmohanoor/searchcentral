[![Web Performance: SEO Mythbusting](https://i.ytimg.com/vi/prmrFlaDtMg/hqdefault.jpg)](https://www.youtube.com/watch?v=prmrFlaDtMg)

## Web Performance: SEO Mythbusting

In this fourth episode of SEO Mythbusting, Martin Splitt (WebMaster Trends Analyst, Google) and his guest Ada Rose Cannon (Web Developer Advocate, Samsung) discuss the issues of web performance and usability, such as:

The mobile web & the web on low-end devices (1:21)

Performance metrics as a ranking factor for search results (2:17)

How does Google communicate up-to-date SEO metrics to SEOs/SEO companies/web developers? (3:31)

JavaScript sites - ranking, indexing, and performance (5:09) 

Is it more SEO-friendly to rely on modern, semantic HTML and CSS rather than JavaScript? (7:20)



Documentation mentioned in this episode:

The new mobile reality - Alex Russell → https://goo.gle/2WFveCB 

Using page speed in mobile search ranking → https://goo.gle/2RdLBAE 

UX improvements with page speed in mobile search → https://goo.gle/2KFw3nM 

User-centric Performance metrics → https://goo.gle/user-perf-metrics

Making Modern Web Content Discoverable for Search (Chrome Dev Summit 2018) → https://goo.gle/2WvzZKg 

Implement dynamic rendering → https://goo.gle/dynamic-rendering



Next week, look forward to the fifth episode - Web Frameworks: SEO Mythbusting.



Watch more SEO Mythbusting episodes → https://goo.gle/SEO-Mythbusting 

Subscribe to Google Search Central → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=prmrFlaDtMg&t=0) |  ADA ROSE CANNON: People often find that

their sales will go up. They'll get more engagement from audiences they didn't know they had just because they can now access the content. [MUSIC PLAYING] MARTIN SPLITT: Hello, and welcome to another episode of "SEO Mythbusting." With me, today, is at Ada Rose Cannon. And you were working for Samsung, is that right?  

#### [0:00:30](https://www.youtube.com/watch?v=prmrFlaDtMg&t=30) |  ADA ROSE CANNON: That's correct. MARTIN SPLITT:

So what do you do at Samsung? ADA ROSE CANNON: So, for Samsung, I'm a developer advocate for the web browser Samsung Internet. MARTIN SPLITT: Oh! ADA ROSE CANNON: Samsung Internet is a web browser for Android phones. You can get it from the Play Store, but not a lot people have heard about it. So there's-- a lot what I do is trying to raise awareness. MARTIN SPLITT: Makes sense. ADA ROSE CANNON: But, more importantly than that, what I'm trying to do is advocate for the web as a platform, to try and encourage developers to build for it and to make sure it lasts long into the future as a great and healthy platform  

#### [0:01:00](https://www.youtube.com/watch?v=prmrFlaDtMg&t=60) |  for people to build stuff with. MARTIN

SPLITT: I love to have you here because I want to talk to you about the SEO versus for performance and usability on the web. And I think we need to get some stuff out of the way, right? So would you say-- what is the most important bits and pieces that you would like people to focus on more when building web stuff? ADA ROSE CANNON: So I have a huge passion for ensuring that the web remains great for everyone around the world,  

#### [0:01:30](https://www.youtube.com/watch?v=prmrFlaDtMg&t=90) |  not just on people using the latest

handset and on desktop computers because most people aren't. People are using devices from years ago, and low-end, sub-$100 devices, where frankly, today, the modern web is just not even reaching them. MARTIN SPLITT: There's a fantastic talk from Alex Russell, who goes into the reality of people with phones that are less than $100. ADA ROSE CANNON: I love that, though. MARTIN SPLITT: Yeah, that's a fantastic one.  

![](https://i.ytimg.com/vi/prmrFlaDtMg/hq1.jpg)



#### [0:02:00](https://www.youtube.com/watch?v=prmrFlaDtMg&t=120) |  ADA ROSE CANNON: You'd have the naive

thought that, as time goes on, phones are getting steadily better and a bottom-of-the-line phone is, nowadays, is just as good as the top of the line phone four years ago, when they're not. MARTIN SPLITT: It's not. ADA ROSE CANNON: It's just getting wider and wider-- MARTIN SPLITT: Yeah, exactly. ADA ROSE CANNON: --and wider. MARTIN SPLITT: The chasm is opening, rather than anything else. ADA ROSE CANNON: What was really awesome, I heard recently, Google was doing performance metrics into their ratings for search results. MARTIN SPLITT: Yeah. ADA ROSE CANNON: And so was this front-end web performance,  

#### [0:02:30](https://www.youtube.com/watch?v=prmrFlaDtMg&t=150) |  like render speed, making sure it's not

janky? Or is this just making sure a page loads really quickly? MARTIN SPLITT: Mm-hm. So it is a little-- I think it's a tricky one because we have so many metrics. Right? We have time to first byte, we have time to interactive, we have time to first meaningful paint, and then you have the frame rates and stuff. Now, Googlebot, which is the tool that basically fetches the data and renders your website for search indexing,  

#### [0:03:00](https://www.youtube.com/watch?v=prmrFlaDtMg&t=180) |  we don't really interact that much with

the page, so we can't really get-- like, figure out if your scroll is smooth on something like that, but we do get the rendering bits. So we can tell you when the page becomes responsive to inputs, when the content is ready for the user to consume. So we're looking at a blend of these kind of modes of performance. ADA ROSE CANNON: Cool. MARTIN SPLITT: Does that make sense? ADA ROSE CANNON: It does make sense. MARTIN SPLITT: So do you have any other qualms with like how SEO influences the daily work of a web developer?  

#### [0:03:30](https://www.youtube.com/watch?v=prmrFlaDtMg&t=210) |  ADA ROSE CANNON: So a friend of

mine recently rebuilt her site using React. She was very excited about it and seemed to get quite good client-side performance once it all loaded. Unfortunately, when she sent it out to her company's team to-- which does SEO analysis, they came back with an answer of, we love your site, it's really good, but you basically don't appear in the rankings, even though she could show them that, look, right there, it's on Google.  

#### [0:04:00](https://www.youtube.com/watch?v=prmrFlaDtMg&t=240) |  MARTIN SPLITT: Ooh, all right. ADA ROSE

CANNON: Is Google engaging with people who do SEO analysis to ensure that they're running up-to-date metrics? MARTIN SPLITT: Mm-hmm. ADA ROSE CANNON: The similar ones to Google to ensure that, even a heavily client-side rendered page, they can feel confident that it is being measured well. MARTIN SPLITT: So we can't really fix what people are doing in terms of what tools they are using or something, but what we do want is we want to open this black box of SEO  

![](https://i.ytimg.com/vi/prmrFlaDtMg/hq2.jpg)



#### [0:04:30](https://www.youtube.com/watch?v=prmrFlaDtMg&t=270) |  for everyone. So we're having this conversation

with web developers. We're having this conversation with SEOs and tool makers, and we provide a bunch of metrics and tools as well. So we have a Search Console that gives you a bunch of insights on how you were doing in Search so that you're not relying on someone else basically sticking the finger in the wind and reading the stars and stuff. And we also want to make sure that people are understanding that blanket statements like, "JavaScript is going to kill your SEO," or, "you cannot use React or Angular,"  

#### [0:05:00](https://www.youtube.com/watch?v=prmrFlaDtMg&t=300) |  that's not necessarily the best way of

doing it. It's a really comfortable answer, probably, but it's not the right answer, sometimes. ADA ROSE CANNON: All right. So that Chrome Dev Summit, I saw your great talk on SEO in the web. MARTIN SPLITT: Thank you. ADA ROSE CANNON: And one thing you mentioned was the rendering for-- by Googlebot to actually process a JavaScript-heavy site could take up to a week to happen. Does this mean that JavaScript-heavy sites are effectively getting penalized in Google search  

#### [0:05:30](https://www.youtube.com/watch?v=prmrFlaDtMg&t=330) |  results? MARTIN SPLITT: Right. They are not

getting penalized. So they are ranking just fine, but the indexing stage is where the problem is because, as you say, we are processing by putting them first into a rendering queue. And then eventually, as we have the resources available, we are rendering them. And if the resources take a while to actually render, that means that we cannot refresh the content in the index as quickly. So new sites might want to look into that. But, then again, you have usability issues anyways, right? ADA ROSE CANNON: Yes. MARTIN SPLITT: Right, and that's because that's  

#### [0:06:00](https://www.youtube.com/watch?v=prmrFlaDtMg&t=360) |  bad for the user. We try to

find the search results that are good for the users, and if a page takes ages to load, that is not a good experience for me. So you want to fix that because of the users, not necessarily just because of the crawler. ADA ROSE CANNON: So if that page is built using-- I know I have a bit of a bias against these JavaScript-heavy front-end client rendered pages because they're terrible for everyone who doesn't have, like,  

![](https://i.ytimg.com/vi/prmrFlaDtMg/hq3.jpg)



#### [0:06:30](https://www.youtube.com/watch?v=prmrFlaDtMg&t=390) |  an iPhone or latest Pixel or something

or a desktop computer-- but, anyway, for these sites, if the way they make their money is delivering fresh content daily, does this mean that the content in the search results might actually be like out of date for them? MARTIN SPLITT: They might be lagging then. Yes, absolutely. And I think, again, like it's really important to get the users a great experience, and I don't think you can do that when you are heavily relying on client-side rendering because the-- ADA ROSE CANNON: I agree strongly. MARTIN SPLITT: The devices might be really old.  

#### [0:07:00](https://www.youtube.com/watch?v=prmrFlaDtMg&t=420) |  So, yeah, one way of working around,

unless you want to properly fix this and do hybrid rendering or server-side rendering, one way around of that is to do dynamic rendering and basically give us the static rendered version of your page for the crawler so that we can index you quicker, but that's not making the usability and user experience problems go away. ADA ROSE CANNON: Yeah. So would you say it's generally safer to rely more on latest HTML and CSS, knowing that they degrade more gracefully than JavaScript?  

#### [0:07:30](https://www.youtube.com/watch?v=prmrFlaDtMg&t=450) |  MARTIN SPLITT: Yes. Yes. Generally speaking, if

you look at the tristar of technology that we have in the web platform like HTML, CSS, and JavaScript, HTML and CSS are just more resilient than JavaScript is. So relying on JavaScript too heavily is always going to probably get you into trouble with certain ways in supporting network connections and stuff. So I would say use polyfills, use progressive enhancement, use what the web platform offers you, and use JavaScript responsibly.  

#### [0:08:00](https://www.youtube.com/watch?v=prmrFlaDtMg&t=480) |  ADA ROSE CANNON: Yeah. It's really great

to hear, especially from a Googler that, like, reducing reliance on JavaScript and taking advantage of good HTML and CSS where it's available can actually do wonders for your SEO. MARTIN SPLITT: Absolutely. Ada, thank you so much for being here and talking to me about performance and SEO. And I-- do you have a feeling that SEO and web developers can work together nicer? Or is there still-- ADA ROSE CANNON: I think as long as there's like the goals of what people are trying to accomplish  

#### [0:08:30](https://www.youtube.com/watch?v=prmrFlaDtMg&t=510) |  are clear and we're not just like

resorting to auguries or looking at the stars to work our what Google is thinking, then it's going to enable developers to actually build sites that make sense and take advantage of the web platform. Like, anything Google can do to ensure that the web works for everyone, and not just in the wealthy Western web, then it'll be really, really fantastic. MARTIN SPLITT: Fantastic closing words. Thank you so much for being here.  

#### [0:09:00](https://www.youtube.com/watch?v=prmrFlaDtMg&t=540) |  ADA ROSE CANNON: Thank you. [MUSIC PLAYING]

MARTIN SPLITT: This just in, the next episode of "SEO Mythbusting" is going to be about SEO in the age of frameworks. Jason Miller and I will talk about what that entails, so stay tuned on this channel. Subscribe to Google Webmasters, and see you soon.  