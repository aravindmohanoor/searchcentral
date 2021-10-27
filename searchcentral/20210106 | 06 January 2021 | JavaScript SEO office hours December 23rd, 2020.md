[![JavaScript SEO office hours December 23rd, 2020](https://i.ytimg.com/vi/i-eAkWmQB1s/maxresdefault.jpg)](https://www.youtube.com/watch?v=i-eAkWmQB1s)

## JavaScript SEO office hours December 23rd, 2020





#### [0:00:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=0) |  MARTIN SCHMIDT: Hello, and welcome to the

pre-Christmas JavaScript SEO office hours. My name is Martin Schmidt. I am in the Social Relations Team at Google. And I am really happy to answer any questions about JavaScript and, well, Google Search. Today, we have a few questions submitted through YouTube. We have a few people in the audience live today as well. We do these roughly fortnightly. So every 14 days, roughly, I am doing these sessions.  

#### [0:00:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=30) |  There is a thread in our YouTube

channel's Community section where you can ask your questions. Or if you want to join the live recording and commenting with a YouTube link in there so that you can ask-- not the YouTube link, the Hangout link in there so that you can join the live recording if you wish. So there are a few questions-- very few questions on JavaScript, actually, but a few questions that touch roughly on JavaScript. So I'll happily have a look at those.  

#### [0:01:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=60) |  Gregory Scott asks, "From my understanding, the

speed ranking factor for Web Core Vitals"-- Core Web Vitals, but roughly-- "would be based entirely on field data and not on lab data. Is this correct?" Yes. At the time of this recording, that is absolutely correct. "What that means, if I'm not wrong, is that the guidance from the lab tests, like Lighthouse, web.def, PageSpeed Insights, may deliver results  

#### [0:01:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=90) |  that are inflated scores." Or deflated, actually.

It might give you very different scores. That is correct. "Which are pointless." Ah, I disagree. They're not pointless. They are indicative. So they are not necessarily the accurate values that you would see in field data, but they give you a hint on where might be issues. It does not cover everything, obviously. While lab data might show everything's fine, field data might show actually that things are not very fine.  

#### [0:02:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=120) |  That's why it's important to also measure

in field data. But lab data usually is a good canary in the coal mine. It gives you a feeling for where you are and where potential problems lie. So they're not pointless, but they are not the truth. It's really, really hard to say what is the truth when it comes to website performance, because it really depends on lots of factors. Then there is-- he gives an example of WordPress where changing plugins gave the options to remove the version  

#### [0:02:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=150) |  string from the files which inflated performance

scores and was practically useless for field data. Then you know that that's not useful. That's gaming the metrics in that case. So the main question. "Does this mean that delay js function in some of the more popular caching plugins for WordPress lately is just that, a trick for the lab data scores that won't have any practical meaning for the field data?" Measure. That's not generally-- delaying JavaScript to a later point might be useful. It might not.  

#### [0:03:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=180) |  You have to measure if that's a

problem for people on your website or not. I would not trust the lab data 100%. Again, the lab data gives you a rough guidance. It gives you a tracer bullet to figure out where problems might be and debug these problems relatively interactively, which you really can't do with field data. So it has its purpose. But obviously, there are things that can game the metrics. But that's a little pointless, because if the users are still  

#### [0:03:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=210) |  experiencing a slow website, that's going to

reflect in field data. So be a little careful with that. But if your measurements show that the field data does not benefit from that function, then that's probably an indicator for that being a metric gaming rather than an actual improvement for users. Tobias Mertz is asking, "Hi there. We have a problem with our cumulative layout shift. We implemented a sticky nav without position sticky since it's not supported in all browsers.  

#### [0:04:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=240) |  Our solution is more like Bootstrap Affix."

I don't know what that is. I know Bootstrap, but I have no idea what Affix is. "So we listen to the scroll event and set the position fixed top 0 with the nav [INAUDIBLE] top. To prevent a jump or layout shift, we have a wrapper around the menu with the explicit height. Therefore, the wrapper still has the same height. Even the nav gets position fixed. So there is no layout shift. Everything seems to work fine. It looks good for the user, but the CLS is coming up every time and a lot. Why is that so?"  

#### [0:04:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=270) |  Without having a look at the specific

example, that's really hard to say. I could imagine figuring out a way to take nav out of the nav flow, like position absolute. But I was thinking position fixed does that as well. But I would definitely consider asking on either the JavaScript site's mailing lists, so bit.ly/js-sites-wg, with an example URL to look at, or maybe the Webmaster forum.  

#### [0:05:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=300) |  Or feel free to go to Stack

Overflow as well with these kind of questions. And again, provide a clear example. And you can build a fake example that just shows the behavior. Because without something to actually investigate or look at, it's really, really hard to give an answer to that question. And there's one more question from Gregory Scott around the Core Web Vitals. Hold on. No, I answered that one.  

#### [0:05:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=330) |  Oh, right. It sounds like it's the

same question, but it's not the same question. It starts with the same introduction, but then it's like, "Does it make sense for an informational site to block all countries out there except the few bigger ones in order to get the best average field score for that speed? I know I can do that. The question is if I have, for example, low return on investment from countries with slow internet connections with a large population, does it make sense to cut them from accessing  

#### [0:06:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=360) |  our website since they have a slow

connection that hurts my field scores?" No, that's thinking that is laser focused on the Core Web Vitals, and that's really, really risky. A, because people from these countries, if they want to access your website, they will through a proxy or what's called a VPN, which really is mostly a proxy for most cases. And then, the speed is even slower, so not helping. The other thing is, Core Web Vitals and Page  

![](https://i.ytimg.com/vi/i-eAkWmQB1s/maxres1.jpg)



#### [0:06:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=390) |  Experience is one ranking factor out of

hundreds of ranking factors. So you should not overestimate the power of this ranking factor. It is important. It is not the most important. And I think if you have useful information and you can get this information to people and get some ROI, you should probably do that. Because again, there's hundreds of ranking factors. Speed is not the only thing. Because if speed would be the only thing, then a blank website would rank really well because it's really, really fast.  

#### [0:07:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=420) |  That's not the point. Fast is an

important quality signal, but there are other quality signals that really, really matter too. So I would not do that. Also, that implies a more complex setup, which usually invites more problems. I would not do that. I don't think that's a reasonable thing to do here. And then, we have a third question from Gregory. "I don't know if you know this, but WordPress decided to reinvent itself with a new editor called Gutenberg." Yes, I know that.  

#### [0:07:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=450) |  They're using Web Components in there. "With

installation of the plugin, you can get more current features that they think to implement. It's basically turning the whole page into blocks." I'm not sure if these blocks are only happening when you edit the page or if that's also in the output of the pages. I will have to look into that as well. "Since one page of 2K words and images could actually be something to 20 or 30 blocks or more, as each new paragraph is considered a new block, what I noticed on the last changelogs  

#### [0:08:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=480) |  is that they would consider splitting styles

so that each block has its own style CSS. This means that loading one page could result in having 30 or more style CSS files." I would assume that they don't do that when they deliver the actual page, but maybe I'm wrong. That's a question for the Gutenberg team. I would ask them. I would ask them and check what they think, because I'm pretty sure they're not doing something for the sake of just doing it.  

#### [0:08:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=510) |  I'm pretty sure they have some reason

behind it. And I think performance is on their radar. So the way you describe it sounds like a performance issue, or potential performance issue. I'm pretty sure they don't do that just for the fun of it. Ask them. Everything is on GitHub. You can ask on the Gutenberg repository why they're doing that. And if they are-- or what's offsetting the performance hit from that. And I'm pretty sure they'll have something to say to this. Then we have a question on--  

#### [0:09:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=540) |  "Hiya, John Miller." Not quite. Close enough,

though. Martin here. Hi. Hi, Rafael. "I'm from Brazil, so when I run PageSpeed inside laboratory data generated regarding my website, it's made for Brazilian users, but it's hosted in the US with a server-- with a CDN. Is the data from the Brazilian server or US server? I think it matters, but what matters really is the field data." Yeah.  

#### [0:09:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=570) |  The field data is actually what matters.

PageSpeed Insights probably generates it from a US server. If your server is hosted in the US and PageSpeed is hosted in the US, then they'll likely have a better connection than users coming from Brazil, even though Brazil and the US shouldn't be too bad. If the server would be in Australia, I would be more worried than that. But yes, the field data is what you should really consider. Again, the lab data gives you a rough tracer bullet for where problems might be, but it might not  

#### [0:10:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=600) |  show all the problems because, again, the

disparity between the two-- field data and lab data. And then, that's it from-- no, there's one more YouTube question from Mustafa, who's also on the call. I know that. "Regarding Crawl Stats report, what should I do about a huge drop on the Crawl Stats report, from 300K requests to 50K to 70K requests? I checked the performance on the social site clicks,  

#### [0:10:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=630) |  and the sessions on GA both look

normal." Then my answer is, that doesn't seem to be a problem. The amount of crawling that happens is no indication for quality or ranking or whatever. The crawling we do is based on lots of things. And as long as your Crawl Stat report doesn't show anything scary, as in your server is actually generating lots of errors or your server is really slow in responding--  

#### [0:11:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=660) |  as long as that's not the case,

you should be fine. And thankfully, you gave us a sample URL, so I can actually take a look. I shall do that here. And as far as I can tell from the coverage, nothing really has changed. So it's not that we are not seeing something or that, as you say, the performance hasn't dropped. So that's not a problem, really. As far as I can tell, the crawl is going up again,  

#### [0:11:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=690) |  with 200 crawl requests recently-- Sunday. So

that's three days ago. I do see a drop from 300K to 41K-ish. But that itself is not a problem. It's just meaning we crawl less, but that has no meaning on anything. We don't think it's less quality. We don't think-- we've just decided, oh, most of the pages probably haven't updated. We don't need to crawl as much.  

#### [0:12:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=720) |  We only need to crawl a few--

10,000 pages, like 40,000-50,000. And now, we are probably seeing that we need to adjust again, so we are upping the crawl budget to 200K. Maybe it goes further up, maybe it goes further down. It doesn't really matter. As long as you're not seeing any issues in the performance or in the coverage, I wouldn't be worried about that. Also, the increase in crawling could also come from the fact  

#### [0:12:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=750) |  that I think we switched the site

to [INAUDIBLE] indexing recently, so it might be that we are re-crawling with Google SmartPhone now. So that is why the crawling goes up. And then it will probably go back down again. If we establish that we don't need to do as much crawling, that's just it. Again, as long as the performance is fine, as long as the coverage is fine, there's nothing to worry about. And with that, we are through the YouTube questions. And I'm very happy to take audience questions now.  

#### [0:13:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=780) |  Now it's your turn, everybody. Pava. SPEAKER

2: Hi, everybody. I've got a question, I hope not a silly one. So, we've got this server side rendering website built with Gatsby and React. And what I noticed is that our website was really fast.  

![](https://i.ytimg.com/vi/i-eAkWmQB1s/maxres2.jpg)



#### [0:13:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=810) |  For a user, it's a very fast--

I mean, the user experience, from the point of user experience, it's a really fast website. But when I look into Google tools like Lighthouse, I just notice that the site got much slower in Lighthouse after installing Tag Manager. And I know that Tag Manager code is performed asynchronously.  

#### [0:14:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=840) |  Sorry for my English. MARTIN SCHMIDT: No

worries. No worries. All good. SPEAKER 2: So I just wonder where does it come from? I just feel that it's related somehow, but I can't figure out what's the reason. And I'm just looking for some kind of explanation, I think. MARTIN SCHMIDT: So as I said, the lab data and the field data  

#### [0:14:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=870) |  are not necessarily the same. If you

have Chrome UX Report available for the site, if it has enough data points in there that it shows, then I would look into that. And Search Console has it under the Core Web Vitals Report. So if those look fine, then I wouldn't worry too much. For Lighthouse and WebPageTest and all of the others like PageSpeed Insights, I know that they-- how do I put this? They have a really hard task, which  

#### [0:15:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=900) |  is to generate a score from a

lot of different metrics. Now, these metrics are not all what is in Core Web Vitals. There's more metrics than there are in Core Web Vitals. Core Web Vitals are just a part of what these tools report on. And to generate a score, they have to mix these metrics somehow. The mix-- at least for Lighthouse, the mix is documented somewhere in their documentation. And you can find out how they weighed the different metrics  

#### [0:15:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=930) |  to generate the score in the end.

And depending on how that score is generated, you might see interesting fluctuations. And if Google Tag Manager does something that is relatively heavy but does it in the background, that might not actually affect what users perceive or notice, and that's great. But it might affect one of the metrics that these tools are looking into, whatever that metric is. It could be total blocking time. It could be time to--  

#### [0:16:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=960) |  DOM content loaded. It could be various

different things. It could be the parse time. It could be that the Tag Manager detects these tools and then loads slower or something. And then that mixes into the scores, and then that's why we would get a lower score. As long as the real user metrics look good, you shouldn't be worried too much about that. Again, the lab data testing tools-- Lighthouse, PageSpeed Insights, WebPageTest-- they give you an indication on where to look.  

#### [0:16:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=990) |  But then, you still have to interpret

these metrics. A Lighthouse score of 100 doesn't mean anything unless you actually understand that the metrics that you care for are really looking fine. A Lighthouse score of 50 might mean something, might mean, oh, we should look into this, but might also just be like, oh yeah, this is measuring things that we don't really that much worry or care about. So that's not a big problem. Luckily, web.def has lots of important information on how these metrics work and what they mean so that you can  

#### [0:17:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=1020) |  make a more educated guess on what

you should do about the scores you're seeing. But when you see these discrepancies-- and I've heard a few offenders like Google Ads, apparently, is a thing where that can happen. Google Tag Manager is a thing where that can happen. Certain YouTube embeds have this issue. So even Google properties are not excluded from that because the testing tools don't care where requests are made to or coming from. So you might see differing values between the real user  

#### [0:17:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=1050) |  metrics and the field data. If you

have your user metrics available, that's what I would look into. Field data-- sorry, lab data is interesting to just debug things and get a feeling for where you are going. But I wouldn't worry too much about it if there is an issue with just the lab data values. SPEAKER 2: Thank you. I think it's clear. And this is what you said.  

#### [0:18:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=1080) |  I noticed that the tool shows me

some information about total blocking time. So that might be one of the factors. Then, generally speaking, just-- so if I understand correctly-- so the important thing is how really, user experience the website. MARTIN SCHMIDT: Yes, that is correct. SPEAKER 2: OK, thank you.  

#### [0:18:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=1110) |  MARTIN SCHMIDT: You're welcome. And this seems

to be the theme of today, because most questions are circling around that. As a general note, I want to say that measuring user experience in terms of responsiveness of the site and speed of the site is ridiculously complicated and has lots of caveats that are really, really hard to quantify. And the goal, really, is to have something that is a very human interaction, as in, how quickly does the site respond? How quickly does it show the content also?  

#### [0:19:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=1140) |  All of these things. How much of

my CPU does it spin? How much of my battery does it consume? We tried to put all of this into a number, and that's always a hit and miss. Oftentimes, it works. In some edge cases, it doesn't. In some edge cases, you get reports that don't make sense. And then, there was-- someone asked the question-- Tobias asked the question with the CLS where they're like, we don't think that that's the case. I would try to report-- if you see CLS values being very high, in Lighthouse for instance, I would  

#### [0:19:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=1170) |  report that to the Lighthouse team with

a sample URL so that they can take a look at it. Because maybe it's just a glitch in the way that CLS is calculated. That is absolutely possible because it is surprisingly hard to get these values accurately and also to find metrics that are-- that's the whole reason with the Core Web Vitals. It's not like, oh, we wanted to make something up so that we are busy. No. It has been that we had lots of metrics, and the web has changed and the way that users interact with the web has changed, and the metrics  

![](https://i.ytimg.com/vi/i-eAkWmQB1s/maxres3.jpg)



#### [0:20:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=1200) |  did no longer fit how people were

actually experiencing the web. So we had to come up with new metrics. That happened relatively randomly, which pissed off people, understandably. If you are optimizing for the metrics that you are given and then the metrics change and now your optimization work looks like nothing has happened or actually has made things worse, you're like, what the hell? So the Core Web Vitals give you a more structured and timeslotted way because we are considering updating them once a year, roughly, and not  

#### [0:20:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=1230) |  in random times throughout the year. So

it gives you a more predictable set of goals to look into even though we understand, and hopefully you understand, these Core Web Vitals aren't perfect either. Because there will be websites that are really fast for users but don't look great in Core Web Vitals. So that's why these metrics keep evolving and keep improving. But getting a perfect score for what people are experiencing on websites is really, really hard. All right, any further audience questions?  

#### [0:21:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=1260) |  And again, you can use the chat

or you can use the microphone. And you can use the Raise Hands feature. Dave. SPEAKER 3: Hi. Since we're on a bit of a performance bend today, is there massive benefit on streaming response, particularly something like an SSR side rendered something, maybe, [INAUDIBLE] later. Tends to compile [INAUDIBLE] all across. I can see there's a few frameworks now trying to push towards streaming that initial response.  

#### [0:21:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=1290) |  It looks hugely complex in certain parts,

and it seems to have some drawbacks. But is it really worth something pushing towards, or do you think it's a case-by-case basis or there's no real rule? MARTIN SCHMIDT: I think it's probably on a case-to-case basis. But generally speaking, it does make sense if you think about it. With server-side rendering, the big challenge is the-- real server-side rendering, not like static pre-rendering or whatever. The request comes in, a program runs, generates the DOM--  

#### [0:22:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=1320) |  or generates the HTML and then sends

the HTML over the wire in one big block. So basically, what happens is the request comes in, and from the browser's perspective, nothing happens for a while. And then, it all comes over. If we could shorten the amount of nothing happens for a while from the browser's perspective, I think that would be good because then you could start-- or the browser can start to build the DOM as the data arrives, which has been the case with static websites. You have a file on disk.  

#### [0:22:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=1350) |  You have the browser requesting it. And

basically, immediately as the file is opened, the data is streamed over the network so it arrives bit by bit in the browser. Not like, nothing happens for a long while, and then the entire thing starts streaming in. But that being said-- you already hinted at this-- streaming a HTML response that was generated by any kind of program-- and I'm not even saying JavaScript, specifically. This could be a Java program, This could be a PHP or Perl program. It doesn't matter. Python. C++, if you really want to have the pain of that.  

#### [0:23:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=1380) |  Having that stream the data as it

generates it is probably a lot of complexity. That usually means-- where there is complexity, there are bugs and edge cases that are surprisingly hard to cover. So I would not be surprised if that is not worthwhile, especially if the time that the program runs is in the subseconds. If your PHP script or your HTML script--  

#### [0:23:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=1410) |  HTML script. If your PHP script or

Node.js script takes like 0.5 seconds, then I don't think it's worth the hassle. If it does run for 10, definitely worthwhile. Definitely worthwhile sending the data. And 10 is just a very extreme number to just make sure that we are talking very extreme numbers here. But the reality is somewhere in the middle, probably like subsecond, and then everything that is longer than a second you can probably see benefits. Everything that is longer than two seconds, you very likely see benefits. But again, then what's the complexity that you invite into your code?  

#### [0:24:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=1440) |  Is it worth it? Can we make

it so simple that it doesn't generate so much overhead that, A, the program runs slower and, B, problems happen that we then need to mitigate with even more code? I think that's an interesting venue to explore. I haven't seen as much exploration in the wild yet. But I think it's an interesting thing to try out and see if you can actually gain significantly. I remember I did that with WebGL I was exploring if a certain WebGL format--  

#### [0:24:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=1470) |  so basically, like JPEG for 3D graphics

glTF-- if that could be streamed and what you would gain from it. And the gains we saw were huge. But the complexity we saw in creating these models in a way that they would be streamable was so big that even the huge gains we made-- and we were talking gains of like 20 to 30 seconds on a 3G connection. But it would take tens of hours of 3D artists with specific tools that are really, really expensive to actually generate these models.  

#### [0:25:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=1500) |  So we decided it's not worthwhile. And

we might as well run into the situation like this with streaming for a server-side rendering framework. But I think it's worthwhile to try it out. We should probably try it out as a community. [INAUDIBLE] Thanks for the question. SPEAKER 3: You're welcome. MARTIN SCHMIDT: Oh, Tobias. Yes, you can simply open an issue on GitHub.com/googl echrome/lighthouse.  

#### [0:25:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=1530) |  I think that's the GitHub repository anyway.

And they have an issue striker. And if you say, like, Lighthouse reports CLS here, and we don't understand why, then-- is it Lighthouse? No, it's not Rendertron. Rendertron is completely different than Lighthouse. You can search the issues here or-- so either add to an issue that exists, or you can add a new issue there. Report it, and you'll get an answer.  

#### [0:26:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=1560) |  Even if the answer is no, that's

working as intended. And that gives you a hint that it's not the tooling. That's something that you are not seeing there. But I would not be surprised if there is a glitch. All right. Further questions? It's funny because the recording will be sent in two things. I'll get a video, and I'll get a text file with the chat. It's always funny when that happens. [INAUDIBLE]  

#### [0:26:30](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=1590) |  We do not have further audience questions.

I would like to say thank you very, very much to everyone who submitted a question through YouTube. Thanks for everyone who joined today. I hope that you're all safe and healthy, that you have a fantastic holiday time, and enjoy. And see you in the new year. SPEAKER 4: Thanks, Martin. Merry Christmas, everyone. MARTIN SCHMIDT: Thanks. Bye. SPEAKER 2: Merry Christmas. Bye-bye.  

#### [0:27:00](https://www.youtube.com/watch?v=i-eAkWmQB1s&t=1620) |  SPEAKER 3: Happy New Year.  

