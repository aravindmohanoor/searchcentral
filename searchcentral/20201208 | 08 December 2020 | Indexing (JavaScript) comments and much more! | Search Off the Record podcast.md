[![Indexing (JavaScript) comments and much more! | Search Off the Record podcast](https://i.ytimg.com/vi/3V1zaNNwCb8/maxresdefault.jpg)](https://www.youtube.com/watch?v=3V1zaNNwCb8)

## Indexing (JavaScript) comments and much more! | Search Off the Record podcast

In this episode, Gary gives an update on his new website, and John, Martin, and Gary discuss how they started at Google. In the second part of the episode, the team deep dives into indexing comments and Martin goes over client-side vs server-side JavaScript.



Episode transcription → https://goo.gle/37sMqxW



Watch more Search Off the Record on YouTube → https://goo.gle/2JL3t5Y

Have a favorite way you like to listen to podcasts? Find Search Off the Record on most major podcast platforms → https://goo.gle/search-off-the-record



Google Search developer site → https://goo.gle/35HtREZ 

Search Off the Record on the Google developer Site → https://goo.gle/3qt1XGP



Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



Search Off the Record is a podcast series that takes you behind the scenes of Google Search with John Mueller, Gary Illyes, and Martin Splitt from the Search Relations team.



#SearchOfftheRecord



#### [0:00:00](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=0) |  [MUSIC PLAYING] MARTIN: Welcome, everyone, to the

next episode of "Search Off The Record," a podcast that we are trying out. Our plan is to talk a bit about what's happening at Google Search, how things work behind the scenes, and maybe have some fun along the way. My name is Martin Splitt. I'm a developer advocate at the Search Relations Team. And I'm joined here by John and Gary.  

#### [0:00:30](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=30) |  GARY: You don't see this, but we

are waving. MARTIN: That's fantastic. Everyone waves into the microphone, which is a great idea. Sweet. So Gary, how is your website coming along? GARY: Why do I always start this? MARTIN: Oh, I can start if you want to, but-- GARY: Well-- MARTIN: Do you want to start or do you want to start? GARY: Well, actually, I'm funnier. So probably I should start. MARTIN: Yeah. So there you go. GARY: Uh, website. Websites are hard, it seems. And yeah, I'm on track, I guess. But I reached a point where I would rather pay someone  

#### [0:01:00](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=60) |  to actually create the things that I

want to create rather than developing myself because I'm running a WordPress installation. And it's great, as usual, but I need some custom plug-ins, and I'm actually developing that. So the idea is that Lizzie, our tech writer, and I test out things on the website once we actually published the Docs about those features or structure data  

#### [0:01:30](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=90) |  or whatever. And for that, I need

some custom plug-ins. Like, for example, I can't just use a normal recipe plug-in because there might be a lag between our public release and how fast the plug-in developers implement those new features. So I want to be able to add custom structure data to every page. The second thing is that I do want to have dropdown or an accordion or something  

#### [0:02:00](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=120) |  where I say a few words about

why I added certain things to the page. For example, why I chose this title or why did I link to johnmu.com/hacking and so on. And those take time. And I was wondering if I should just create, let's say,  

#### [0:02:30](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=150) |  an HTML page from scratch for every

single recipe that we want to publish and then that would be a relatively easy to add whatever we want to? But I thought that's perhaps a bad idea. The second idea was that I actually create a CMS from scratch, which is not a foreign concept for me because I did create a CMS I think right before I joined Google. And it was actually quite great. And it was working pretty well.  

#### [0:03:00](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=180) |  It was based on the Google Docs

API. And basically, you were writing your content in Google Docs, and then there was a container running on standard web server, an Apache web server. And that was pulling in content from Google Docs. And back in the days, that was quite cool, and it worked quite fast. Like, serving time was under one second. But then it got more slow, as I imagine more users started  

#### [0:03:30](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=210) |  to use Google Docs API. And at

one point, I think the load time for the content itself, the container loaded perfectly and snappy, in a snappy way, but then the content appeared only like with a five-second lag, I would say. And that was a no from me. And the second problem was that the website got fairly popular. And I got an email from the I think API team at Google  

#### [0:04:00](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=240) |  that maybe I should scale back or

upgrade my plan. And at that point, I think I already signed my contract with Google. And I was like, hmm, maybe this is a good time to stop. MARTIN: Oh, my goodness. GARY: Yeah, but it was fun. So yeah, back to the website or my new website. It's probably on track, but I like procrastinating. And this is a good time to procrastinate as well.  

#### [0:04:30](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=270) |  And I'm baking cookies for Martin. MARTIN:

Third-party cookies, yes. GARY: So that's more important than the website itself. MARTIN: Absolutely agree. GARY: Oh, yeah. The CMS, it was right before I joined Google. And it was one of my favorite projects. MARTIN: It kind of makes me happy to see that other people also built their own CMS. I think I built multiple CMSs myself because the first one sucked. And then the second one was quite nice, but also it relied on some third-party service that then just got discontinued or something, yeah.  

![](https://i.ytimg.com/vi/3V1zaNNwCb8/maxres1.jpg)



#### [0:05:00](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=300) |  GARY: As they do. MARTIN: Fun times.

GARY: How did you join, John, or when and why? JOHN: When did I join? GARY: What? JOHN: Oh, that was-- GARY: And how? JOHN: --a long time ago. I think, what was it, maybe 2007. So I don't know, 12, 13 years ago? I forgot how to count. Something like that. I think at the time, I was also making my own CMS. Maybe this is like a requirement. I don't know.  

#### [0:05:30](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=330) |  But basically, I had a small software

company, and we started doing more and more things on the web, as you do. And I started working on some of these websites because it was interesting, something kind of new. And at some point, I started helping out in the webmaster forums, as they were just started. So I think site maps just launched around that time. And I was active, kind of helping people with the site maps stuff and trying  

#### [0:06:00](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=360) |  to give them my opinion on things

they're all doing wrong. And at some point, I received an email from someone at Google saying it would be nice if I would drop by their office in Zurich since I'm already in Switzerland. It was kind of weird because the email came to a domain that I don't actively check for emails. So it was almost accidental that I noticed. But it was pretty neat. So I went to Zurich. I met some of the people from the Site Maps  

#### [0:06:30](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=390) |  Team who were active in Zurich. And

it was pretty interesting. It was like a small office, not a ton of people. And that's kind of the first connection I had there. And then we set up interviews, and I learned all of the webmaster guidelines by heart because that's what I assumed I would be asked about. I flew over to Mountain View, met a bunch of other people there. And we had good conversations. It was really interesting.  

#### [0:07:00](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=420) |  And then essentially, I had to make

the tough decision of should I keep my own company or should I join this big corporation, which at the time was not as big as today. But it still felt quite a bit bigger than kind of running your own company. And I decided, well, I might as well try something new out for a change. So I ended up going over to Google and doing stuff there. I think at the time, there were two other people  

#### [0:07:30](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=450) |  on the Webmaster Trends Analyst Team, Jonathan

and Susan. MARTIN: Oh, I miss them. JOHN: Oh, yeah. No, they were great. And I don't know, for a while we were pretty much kind of a small team, working together with the Webmaster Tools Team back then. So that was, like, it's my one chance to say Webmaster Tools and be correct, I guess. And we started trying to expand and trying to find good  

#### [0:08:00](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=480) |  matches for the team and for Google,

which is kind of hard because it's a tricky role, in that it's not like a software engineer where you can test on whether they can do coding properly. But rather, there's some amount of communication and some amount of guessing and understanding involved. And I think you, Gary, were also active in some of the forums at the time, especially the News Publisher forums. GARY: Yeah. JOHN: And for whatever reason, I don't know, we were in touch. So at some point, we thought maybe we could hire this guy.  

#### [0:08:30](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=510) |  GARY: Yeah. That was a mistake. JOHN:

No, that was great. That was great. That was great. GARY: Yeah, the way we met actually was you set up a chat, I think. And you were trying out things on that chat. And some of the bionic posters, some of the contributors joined the chat. And then we were just chatting there. JOHN: Oh. And one thing that I thought was very cool-- sorry to interrupt, Gary. So sorry-- was you set up this cool system on how Google could  

#### [0:09:00](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=540) |  index JavaScript pages. GARY: Oh. Ooh. JOHN:

Remember? GARY: I remember. I hated JavaScript back then as well. Surprise. And I set up a headless Firefox that was doing server-side rendering. Oh, that was a long time ago. That sucked so much. JOHN: I'm shocked, shocked I tell you. GARY: Ugh. JOHN: Yeah, it's so weird.  

#### [0:09:30](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=570) |  It's like, and then we found someone

else to also help us with JavaScript at some point. MARTIN: Who? JOHN: Martin. MARTIN: Oh, that was such a little weird, weird thing. I got contacted by a recruiter at some point. And then Illyeh reached out to me. Like, hey, I saw that you're in touch with the recruiter on this position. And I'm like, yeah, but I still don't fully understand the position because it was like Web Content Ecosystem, and it was really vague. And I'm like, ah, sounds interesting,  

#### [0:10:00](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=600) |  but I'm not exactly sure what's happening

there. And then I asked Illyeh, and Illyeh's like, oh, you know, this is not so much about the web platform and JavaScript. This is more about Search and SEO and maybe News and maybe a little bit of Assistant. And I'm, like, OK. Sounds less interesting. And then I had a conversation with you, John, and I think we went for lunch because I was in Zurich at the time, and you all have also been in Zurich. And then I asked about the position, and it's like, yeah, it's a lot about JavaScript  

![](https://i.ytimg.com/vi/3V1zaNNwCb8/maxres2.jpg)



#### [0:10:30](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=630) |  and the web and Chrome. And I'm

like, oh, OK. This is misleading. This is weird. And then I asked all of you what a typical day looks like. And I got the least satisfying response, which was like, there is no such thing as a typical day. It can be whatever. And I'm like, well, thanks. That's helpful. And then I was going through the interviews nonetheless, and then once I got the offer, I was like, I'm still not sure what the hell I would be doing. And I figured out that you all were, like, basically  

#### [0:11:00](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=660) |  super pros in how Google Search works

internally. And I had no idea. And I couldn't see myself being, like, super helpful in that regard. So I remember this moment that sealed the deal for me was when I asked you, I think either during our second lunch or after our second lunch, like, OK. But why me? And then you're like, because you're a web developer, and we need to figure out this JavaScript thing. And I'm like, oh. Oh, yeah. That makes sense. Oh, yeah. That's actually pretty cool. So yeah. That's how I got my mission and how I  

#### [0:11:30](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=690) |  signed the contract in the end. Probably

also a big mistake for you all. I'm sorry. GARY: Yeah. You're way too optimistic. And way too happy all the time. It's kind of annoying. MARTIN: I'm kind of balancing someone else then, I guess. JOHN: It's a fantastic team. Don't worry. GARY: Yeah. JOHN: It's like, everyone fits in. GARY: That's just like your opinion. MARTIN: I'm super happy to be part of this team. I like you all. GARY: Of course you are, Martin. MARTIN: Ah, it's wonderful. And it's quite cool that we get to help so many webmasters all around the world.  

#### [0:12:00](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=720) |  That's really interesting. At least to me,

that's interesting. JOHN: Yeah. MARTIN: Maybe I help you with the plug-ins, Gary. [ELECTRONIC MUSIC] JOHN: So how is the JavaScript stuff working out now? Do you think we have it all solved? It's like, no more bugs. MARTIN: Oh, my. Definitely not. The biggest thing I learned in the last two years at Google is that developers and SEOs are both extremely creative in building things that don't work, in interesting ways. Like, it's quite fascinating. Most of the things are fantastic ideas on paper.  

#### [0:12:30](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=750) |  And then you implement them, and then

you find out, oh, it doesn't work the way that you would expect it. Sometimes, that's because the creativity is misplaced, and sometimes it's because we are just having glitches. Like recently, I think it was on Twitter-- I think Gary made me aware of it. So someone was asking about Discourse comments, I think. And that's not something that is very specific to Discourse, by the way. It's basically websites using a third party to pull in content that they care about.  

#### [0:13:00](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=780) |  This can go wrong for many different

reasons. In this case, it was a glitch on our side. We found out what the glitch was, fixed it, and basically within the day, we had it back working. But I think this kind of started a larger discussion as to how you should do things when it comes to JavaScript and critical content from third parties because the challenge is that you as a website owner don't really have control over a third party. And if you are using client side JavaScript  

#### [0:13:30](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=810) |  to pull in content from a third

party in the browser, things can go wrong. They could robot their JavaScript API. And then we can't make the request or maybe their service are really under load. And then we decide not to make these requests to the third party because they are already experiencing high load situations. And there are usually ways of doing this on the server side. So if the third party exposes an API that you can interact with from the client side, from the browser with JavaScript,  

#### [0:14:00](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=840) |  you can very likely also do that

on the server side and then basically avoid these problems. Because then your server controls what happens when-- in terms of when the data comes in from the third party. But I think not as many people do that. And I would hope that people are kind of warming up to the idea of doing that instead of doing everything in the client side. JOHN: So is it a bad idea to rely on third parties or is it just have to be careful? MARTIN: It's an OK idea to rely on third parties.  

#### [0:14:30](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=870) |  You just have to be careful, and

you have to understand that in the browser, you have very little control over what happens and how it happens. And if you are relying on Googlebot to do the heavy lifting and figure out how to get the data from the third party, then you are less in control than when your server does that work. Because your server is an environment that you have control over, hopefully. JOHN: That sounds a bit like Gary's problem with the plug-ins, where if the plug-ins are doing one thing and you're trying to do something slightly different,  

#### [0:15:00](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=900) |  then kind of balancing the offloading of

writing code to whoever is making the plug-in versus being able to choose exactly what you want to do. MARTIN: Yeah. Yeah. And I guess for many people, it's fine. I think if you are pulling certain pieces of content, I don't know, like comments or something, and you don't really think that they are your main content, then I think it's fine to just go with an off-the-shelf solution with a third party that may or may not work well in Googlebot and other browsers.  

#### [0:15:30](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=930) |  But if you want to have control

over things, like Gary wants to have control over the structured data on his pages, then I guess you want to run that on your server in a controlled environment. GARY: So Martin, I was taking notes while you were speaking. And I just wrote down one thing. MARTIN: Oh. GARY: And that do not use JavaScript, exclamation mark. MARTIN: That's a-- GARY: Did I summarize right? MARTIN: No. Not really. But I mean, for your point of view, JavaScript is evil. So I kind of see where that's coming from.  

![](https://i.ytimg.com/vi/3V1zaNNwCb8/maxres3.jpg)



#### [0:16:00](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=960) |  But then, I think you can use

JavaScript. It's kind of fun. But you know, if you don't want to, then don't. By the way, JavaScript can run on the server side, just FYI. GARY: Because that's such a great idea, yes. MARTIN: It's a fantastic idea. You could hypothetically-- so there's a thing that lets you run PHP in JavaScript. So you could do that. GARY: Brilliant. MARTIN: Yeah. And then there's a thing that lets you run JavaScript in PHP. So you could build a fantastic stack-- JOHN: Hey, don't give him any better ideas.  

#### [0:16:30](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=990) |  I mean-- GARY: I'm rolling my eyes.

JOHN: He already started with a CMS that was built on top of Google Docs, which is built on JavaScript. So I don't know. MARTIN: It's a great thing. GARY: No, no, no. I was actually doing with that what Martin was saying, that pool the content on server side. MARTIN: Good boy. GARY: And that actually worked excellently-- MARTIN: Good boy. GARY: --until things started to slow down. But that was out of my control. JOHN: That was probably before speed was a ranking factor. So you were probably OK. MARTIN: Probably. GARY: Oh, no.  

#### [0:17:00](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=1020) |  You said it. MARTIN: Oh. GARY: You

said the bad-- JOHN: Bad word. Because of ranking? Is ranking a bad word now? GARY: Well, this killed the discussion all right. MARTIN: No, no, no, no. Well done. JOHN: So one last thing, Gary, I guess. With regards to indexing the comments, because Discourse is basically comments from other people. Is that generally a good idea or bad idea? Should sites kind of block the comments from being shown or should they get them indexed? GARY: I mean, it depends on the comments, right?  

#### [0:17:30](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=1050) |  You can have comments that are, like,

super useful and worth having them in the index and having them help you rank for certain things, a little at least. But then you go to certain blogs that are-- I don't want to say. That will be R rated then. You go to certain blogs, and you read the comments, and you just want to take a spoon and just--  

#### [0:18:00](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=1080) |  MARTIN: Eat ice cream? GARY: I don't

know. Just pop out your eyes or some-- MARTIN: Oh. GARY: Yeah. Like, it's just really bad. In those cases, you probably don't want the comments. Also, I think we saw this before. But depending on where the content is on the page, it might weight less than, for example, content that's in the centerpiece. Like, for example, if we can detect that the meaty part of the content is in the middle and between these sections, then very likely that will  

#### [0:18:30](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=1110) |  be the pulling content for your ranking,

meaning that that will help you the most with topicality, with relevancy, I guess. And then, if we detect that something is outside that boundary, then that will weight less. And it will help you less with ranking. And then you have, for example, footer, where generally people just put a bunch of links. We kind of detect that that's not that useful for users.  

#### [0:19:00](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=1140) |  And so it doesn't help you all

that much with ranking. JOHN: OK. So it sounds like if suddenly the comments of a site started to get indexed, it's something worth kind of looking at. But it's probably not your highest priority to figure out, like, do I-- GARY: Yeah. JOHN: --need to, I don't know, clean out all of the comments and all of my old posts. It's like, it's OK to look at it, but it's not critical. MARTIN: Yeah. GARY: Sure. I mean, there is one corner case where you probably  

#### [0:19:30](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=1170) |  want to look at it. And that's

how many, for example, F-bombs people drop in the comments and how R rated the comments are because if you are writing about cookies, for example, lemon cookies, specifically, and there are a few thousand comments below your recipe that are all of them R rated, then that might easily confuse our Safe Search algorithms, for example. And then your content wouldn't do  

#### [0:20:00](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=1200) |  so well when Safe Search is on

in Google Search. MARTIN: Fun. JOHN: And links, just use rel UGC. GARY: Well, nofollow UGC if you want to help. I would definitely use nofollow, just to make sure that you are following the guidelines that you learned by heart before you got hired, John. JOHN: Thank you. OK. Cool. GARY: Oh, my. MARTIN: All right. Well, this one's really interesting. I kind of like the excursion into understanding what to do with comments. I think we can take a break here.  

#### [0:20:30](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=1230) |  It's been great doing this session with

you all. Looking forward to seeing how your cookies turn out, Gary, and maybe hearing a review from Martin in the form of a comment on a blog post at some point. JOHN: I'll comment on Gary's blog. GARY: They will be epic. MARTIN: They will be epic. GARY: I will not have comments on my blog. MARTIN: Then I'll comment on Twitter. GARY: That you already do. JOHN: Does Twitter get indexed? MARTIN: I think so. GARY: Let's not go there. MARTIN: OK. All right. Well, thanks everyone, for listening in.  

#### [0:21:00](https://www.youtube.com/watch?v=3V1zaNNwCb8&t=1260) |  I hope you found this useful, insightful,

and a little bit entertaining perhaps. Hopefully, I'll see you all again or rather you will hear us again in one of the future episodes and until then, bye everyone. JOHN: Bye. MARTIN: Have a day. [ELECTRONIC MUSIC]  