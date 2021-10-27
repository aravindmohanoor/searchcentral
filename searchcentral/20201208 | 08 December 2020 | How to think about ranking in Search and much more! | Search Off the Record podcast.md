[![How to think about ranking in Search and much more! | Search Off the Record podcast](https://i.ytimg.com/vi/JagcQtuJt6o/maxresdefault.jpg)](https://www.youtube.com/watch?v=JagcQtuJt6o)

## How to think about ranking in Search and much more! | Search Off the Record podcast

In this episode, John, Gary, and Martin discuss how to think about ranking in Search, deliver their feedback on submitting feedback, give tips on rendering SEO (JavaScript files bundling and splitting), and share their experience with recording videos at home.



Transcript for this episode → https://goo.gle/3mEtr9P



Watch more Search Off the Record on YouTube → https://goo.gle/2JL3t5Y

Have a favorite way you like to listen to podcasts? Find Search Off the Record on most major podcast platforms → https://goo.gle/search-off-the-record



Google Search developer site → https://goo.gle/35HtREZ 

Search Off the Record on the Google developer Site → https://goo.gle/3qt1XGP



Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



Search Off the Record is a podcast series that takes you behind the scenes of Google Search with John Mueller, Gary Illyes, and Martin Splitt from the Search Relations team.



#SearchOfftheRecord



#### [0:00:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=0) |  [MUSIC PLAYING] JOHN MUELLER: Welcome, everyone, to

the next episode of "Search Off the Record," a podcast from the Search Relations team here at Google. Our plan is to talk a bit about what's happening at Google search, how things are working behind the scenes, and I don't know, maybe have some fun along the way. My name is John Mueller. I am a webmaster trends analyst, or Search Advocate,  

#### [0:00:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=30) |  here at Google. I work together with

the Search Relations team here. I'm joined today by Martin and Gary. MARTIN SPLITT: Hi. GARY: Morning. JOHN MUELLER: Ooh, all right. Gary, do you want to take us off? GARY: Why it's always me? MARTIN SPLITT: Because reasons. GARY: It's always me. I'm in a fantastic mood because I just spilled coffee all over my keyboard, and I had to switch keyboards at, like-- I don't even know what the time is. Like, 10:00 AM. MARTIN SPLITT: Is that a hot-swap? GARY: Thanks, Martin. MARTIN SPLITT: You're welcome.  

#### [0:01:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=60) |  GARY: That cheered me up so much.

Anyway, I wanted to talk a little bit about feedbacks. Lizzie and I-- Lizzie, as in our tech writer-- we are processing feedback, and also the translations for the dev site-- developers.google.com/search. And we got tons of great feedback that was actionable. You can think of, like, translation quality, for example, where people were pointing out that we were switching between the different tones of German,  

#### [0:01:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=90) |  like formal or informal. And we were

doing some really weird things in Japanese as well. And the feedback-- in general, it's really, really great. But then, some people leave feedback in the form of, well, some things are just rants about something completely unrelated to the article, and they come through to us and sometimes we read them. And while they are not useful, we can't really  

#### [0:02:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=120) |  do anything about them. And another category

is where people are asking for help about something. So, for example, just today, I had to wake up at 6:00 AM for reasons that are beyond me, and I was processing some feedback. And there was this person who had their email account suspended for some reason. And I would love to help, but I really can't with that. I can't even respond to these feedbacks,  

#### [0:02:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=150) |  which is probably a good thing for

the person filing the feedback. So if you have, in general, something about the documentation itself, if you could leave feedback about that, that would be great. Otherwise, we can't really do much. On the bright side, sometimes it also gives us lots of great points to think about. For example, we noticed that we got lots of feedback from bloggers.  

#### [0:03:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=180) |  Let's say, people who are not developers.

And they were commenting that we sent them, for example, structured data messages that something is wrong with their structure data. And they can't do anything about it. Like, they don't know what to do about it because they just installed, for example, a plug-in. And the plug-in generates the structure data for them. And that prompted us to think about how can we  

#### [0:03:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=210) |  help also those people? And John started

an internal thread, which somehow ended up, I think, a little derailed. But then I just jumped over Twitter and asked people for some help, I guess. And we'll see where that goes. But thank you for filing feedback. Thank you for filing feedback in multiple languages because it's been really, really, really helpful. And just think about how you leave feedback and about what  

#### [0:04:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=240) |  because, really, we can help with absolutely

everything. JOHN MUELLER: So where should people go for things like their Gmail account? GARY: We have specialized forums for most products, I think. And those forums are filled with people who are insanely helpful. We used to call them top contributors, but I don't have any idea what we call them nowadays. MARTIN SPLITT: Product experts. GARY: Product experts, OK. They are insanely helpful, and they can point people  

#### [0:04:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=270) |  in the right direction. And ideally, those

who have problems with our products, they would just go to the forums and ask for help there. MARTIN SPLITT: I think, generally speaking, it's a good idea to give us feedback, and I'm really happy that you bring this up. Because I know that, from the outside, sometimes it feels like talking into the void. I don't think we are able to give a response back, so I think when people are writing actionable feedback  

#### [0:05:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=300) |  on our documentation or on Search Console

or something like that, it's invaluable to have this feedback. And a lot of changes are happening because of this feedback, even though it might not necessarily look like that from the outside, right? GARY: It's actually funny because, apparently, there is a setting somewhere buried that would enable us to respond to feedback. But when Lizzie found it and she was saying that, oh, my god, can you imagine Gary replying to this feedback, I LOL'd.  

#### [0:05:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=330) |  MARTIN SPLITT: Fair enough. Yeah. I'm not

sure if people would want that. (LAUGHS) JOHN MUELLER: Yeah. I think there's some kind of feedback where it's useful to be able to let them know and to kind of inform them that, oh, we read this and we totally agree. We fixed this issue. We tried to improve the documentation in that way. That's something that I see, for example, from the Google Maps team. I think they do that really well, where if you submit feedback and say, oh, actually, this road is closed or something like that, then they'll  

#### [0:06:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=360) |  send you an email back over time

and say, hey, we saw your feedback, we fixed it. And I think that kind of helps to encourage other people to submit more feedback, and kind of keep things going. Because it's kind of important to us that our documentation and the help that we provide is useful to people. So if people are confused or people don't find it as useful as it should be, it's really helpful to know. We can't kind of read that from people's minds.  

#### [0:06:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=390) |  MARTIN SPLITT: True. GARY: Yeah. MARTIN SPLITT:

Yeah, and this is, like, the black hole kind of character of the feedback. You give feedback, seemingly nothing happens, and six months later, a feature is rolled out that implements what you have been sending feedback about. It might not feel very encouraging, so I think it's a good opportunity for us to say, like, thank you to everyone who provides feedback. We do take it into account, and it does matter a lot to us, especially on the [? Docs. ?] JOHN MUELLER: Yeah. Talking about black holes, maybe we should talk about JavaScript and search.  

#### [0:07:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=420) |  What do you think, Martin? MARTIN SPLITT:

Oh, my. What an elegant segue into the thing that happened recently. GARY: John, you will get a cookie for this. MARTIN SPLITT: Oh, Gary's cookies are fantastic. I'm now slightly jealous. So Onely ran this free webinar recently-- there's a recording of it on YouTube as well-- where they invited me to talk a little bit more about rendering SEO. That's how they try to talk about specifics in rendering when JavaScript is involved.  

#### [0:07:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=450) |  So it's not just JavaScript SEO, but

they are really, like, focusing on rendering. And after that webinar, I got a question on Twitter, as well, regarding should we split our JavaScript into multiple smaller files, or should we bundle them together in one large file? And that was an interesting conversation because the answer is kind of weird because the answer is bundle it up and then split it. JOHN MUELLER: So what is bundling JavaScript? Is it like, put it in a zip file? MARTIN SPLITT: Not really.  

![](https://i.ytimg.com/vi/JagcQtuJt6o/maxres1.jpg)



#### [0:08:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=480) |  It's more like merging all the files

together. So if you have a library and then you have code that uses that library, 20,000 years ago, you would basically just have the library in one script tag and then have another script tag for the code that uses that library. But that makes a lot of HTTP requests, and the number of HTTP requests is limited that you can do at the same time in the browsers. So people were like, hm, maybe we should just make one file where we put the library first, and then the actual application JavaScript that we write. And so people are using these bundlers.  

#### [0:08:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=510) |  There's a bunch of different tools, like

webpack and Browserify and what they are all called-- Parcel and so on and so forth-- that basically just puts all of the JavaScript that you write from the different files that you create into one big file, and that's usually referred to as a bundle. JOHN MUELLER: OK, so it's not something you manually do. You kind of run it through a script, and then it creates one big JavaScript file-- MARTIN SPLITT: Yeah. JOHN MUELLER: --from that. MARTIN SPLITT: Yeah. And usually, also, it's like you can do it manually, but then you're kind of wasting your time because there's  

#### [0:09:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=540) |  fantastic tools that do this. And these

tools also do other things, like shorten the variable names so that it's less bytes on the wire, and remove code that is never used and all this kind of stuff. So it's pretty powerful tooling, and a bunch of people are using this to bundle their JavaScript in one gigantic file. JOHN MUELLER: Is that something that complicated sites need to use? I sometimes write JavaScript as well, but it's, I don't know, maybe two pages of code. Should I run it through one of these tools, as well,  

#### [0:09:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=570) |  or is that more if you're creating

a really complex JavaScript applet? MARTIN SPLITT: I think it is more for people who use frameworks and libraries a lot. If you write a little bit of JavaScript to do something fancy when you click a button in, let's say 100 lines or something, I think minifying your code is useful, but not as useful-- it's not really a necessity. But if you're using a framework like React, Angular, View, there's so much code involved that these bundling tools are definitely helpful. JOHN MUELLER: Cool.  

#### [0:10:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=600) |  MARTIN SPLITT: Yeah. And the oddity is

that-- so while I say that, and it's an accepted best practice to bundle all these things in one big file, it comes with a downside, which is that if I have a huge application with lots of different views, like-- I don't know-- a blog, and then I have an e-commerce part of my website. And then maybe I have a login accounts page or something like that, or an order dashboard or whatever. If I have all the code to power all this content in one  

#### [0:10:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=630) |  huge JavaScript file, that means that if

any of these parts change, the entire cache is invalid, and we have to re-download everything. And also, if I just come for the blog, then why would I download an order page or a card system or an account system? So you download a lot of stuff that you don't need. So that's why the recommendation is to bundle things up, but then split them according to the content that people might visit specifically so that you separate the different parts of your page,  

#### [0:11:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=660) |  code-wise. JOHN MUELLER: OK. That sounds pretty

complex. MARTIN SPLITT: Yeah. It's called code splitting, or "Sh-plitting," if you ask me, obviously. GARY: You didn't. MARTIN SPLITT: I did, I did. It's such an original joke. No one ever toys with my name like that, so I had to do it, I guess. GARY: I literally facepalmed. MARTIN SPLITT: You're welcome. (SINGING) What can I say except you're welcome? So yeah, a bunch of these tools that are bundling have options to specify how you want  

#### [0:11:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=690) |  to split your bundle as well. So

for instance, you can say, oh, this is code that every page needs. It's kind of like the boilerplate or the runtime or whatever you want to call it. And then you create one JavaScript file that contains this boilerplate because the boilerplate probably doesn't change very often. So you can keep that cached forever, basically. And then you have only the code for each specific page or view separated into different bundles. So there are options, and there are tools that help you with this. But if you want to do that manually, that's really, really hard to do.  

#### [0:12:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=720) |  JOHN MUELLER: Do you think this is

something that someone like an SEO should do afterwards, or does the developer need to do this? MARTIN SPLITT: I think it's something that an SEO should make developers aware of because not every developer is aware of this. As I said, the old, established best practice that still is somewhat valid is to bundle everything in one file. Now, it's like bundle it up in multiple files, but make that a reasonable bundling. And I think it's not something that the SEO needs to do afterwards. It's better if the developer does this while developing the site because it's usually embedded  

#### [0:12:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=750) |  in the developer tools, how you can

split these things. And it might require some changes in the way that the code is written, so definitely make your developers aware of that. JOHN MUELLER: Is there a simple way that an SEO could recognize this? If you look at-- I don't know-- at a waterfall diagram, would that be obvious that you need to bundle the code, or you need to split the code? MARTIN SPLITT: So I think if you're seeing your website downloading 20 different pieces of JavaScript, or 30, 40 pieces of JavaScript, that's a case where there is no bundling,  

#### [0:13:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=780) |  and you should definitely think about bundling

this because that's a lot of requests and it's kind of pointless to have all these requests separate. If you see one request that keeps repeating every page you visit, like an app.js or a main js or something like-- or bundle.js is a classic, and you know that the website is very large and has lots of different pages, then that's a hint that you probably want to split your bundle, especially if this bundle is multiple megabytes. If you have a bundle.js or an app.js that is five megabytes,  

#### [0:13:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=810) |  then that's a very clear candidate for

splitting the bundle up into smaller chunks. JOHN MUELLER: Sounds cool. OK. I will test some of the web pages that I access to see if I can figure something like that out. I can't help them to fix a problem, but it seems like something that you should be able to try out on random websites that you visit and see if you could recognize this as kind of, I don't know, an exercise. MARTIN SPLITT: Yeah, and it's just  

#### [0:14:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=840) |  something that is nice for the user,

and easier for us, also, to deal with, caching-wise. But it's not like a ranking factor or anything like that. It's not-- we are not looking at this. It doesn't necessarily help you with [INAUDIBLE] [? vitals ?] or something, so it's not directly impacting your ranking or anything. But it is just a helpful thing to do. JOHN MUELLER: OK. Speaking of ranking factors-- GARY: Oh, dear. Please don't tell me JavaScript is a ranking factor. JOHN MUELLER: I don't know. JavaScript can be a ranking factor. Sure. Why not? MARTIN SPLITT: Uh-oh, uh-oh.  

#### [0:14:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=870) |  JOHN MUELLER: Wow, OK. It's kind of

a tricky topic in that I see people write about this all the time externally. I see us using that as well. We use it when we talked about the page experience benchmark, where we said this would be a ranking factor. And then, obviously, the next question from everyone is, well, how strong of a ranking factor is it? Do I have to throw away my website and just make a fast, empty page instead?  

#### [0:15:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=900) |  And obviously, that doesn't make any sense

either. So I think there are two mental models I have when it comes to ranking factors in general. On the one hand, search is not a science. I think that's really important to keep in mind in the sense that there is no absolute truth out there, with regards to which page should be ranking for which query. But rather, these are things that can change over time. These are things where people are working  

#### [0:15:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=930) |  on it to keep improving things and,

sometimes, you can have discussions with smart people about which of these pages should be ranking first, or if we have two very similar pages, should they be both ranking, or should only one of them be ranking? Those are very interesting discussions to have. But it's all based on, I don't know, opinions and ambiguous information that you have from the web. So that's the one thing.  

#### [0:16:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=960) |  And the other thing is that there

are so many different ways to reach a final result in search. It's not that every site has to do the same thing. So I use a mental model of something like a neural network, which is not how we would do this in search, but it kind of helps me in that we take the query that a user has, and we try to understand it and split it up into lots of small parts. And these small signals that we have from what the user is looking for, they go through this big network, where  

![](https://i.ytimg.com/vi/JagcQtuJt6o/maxres2.jpg)



#### [0:16:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=990) |  different knots along the way let the

individual parts pass, or they reroute them a little bit. And in the end, we come up with a simple ranking for the different web pages for that kind of a query. And when you have this kind of a network, there are lots of different paths that could lead through that network that end up with the same result. So it's not that every site has to do the same thing, but rather, there are multiple ways to get there. And you don't have to blindly follow just one ranking factor  

#### [0:17:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1020) |  to get to the end result. And

it's also not the case that any particular factor within this big network is the one deciding factor, or that you can say that this factor plays a 10% role because maybe, for some sites, for some queries, it doesn't play a role at all. And maybe for other sites, for other queries, it's the deciding factor. It's really hard to say how to keep those together. So this big network thing also changes over time, of course,  

#### [0:17:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1050) |  as we try to improve our search

results. And essentially, we try to optimize how we understand the query. We try to optimize how we understand the routing between the query and the search results. And these kind of changes take place all the time. And the best way for a website to remain in a stable position, which is not guaranteed at all, is really to make sure that you have a wide variety  

#### [0:18:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1080) |  of different factors that you work on,

and to keep this diversity of your website upright. So similar to how you might want to improve diversity in a team to get different viewpoints, that's the same thing that you'd want to see on a website. So that regardless of how things are routed through this network to find the search results, we can understand that this website is relevant in different ways, and all of these add up into telling us that it's actually relevant for a particular query.  

#### [0:18:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1110) |  So that's all to say that it's

really, really hard to take any particular element and say, this has such-and-such an effect on the search results. And similarly, it's pretty much impossible to kind of go from the other way around and say, well, looking at the search results, I can tell that this particular search results factor is this important, or more important than this other factor. Because it's really not the case that you can route things  

#### [0:19:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1140) |  backward and say, well, looking forward, it

goes like this and looking backward, it's exactly the same route because there are just so many different ways to get to the end result. So that's my short monologue on ranking factors. I think it's worthwhile to keep in mind that when you talk about ranking factors externally, there are lots of different ways to get there. And it's not something that you can just deduce into one specific element or simplify  

#### [0:19:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1170) |  into an ordered list of elements that

you need to check off. But rather, you need to make sure that your website is good in a variety of different ways, and don't just blindly focus on one particular element and then try to make that element look natural so that it's like, hopefully, the algorithms won't think that I'm trying to do something sneaky here. But instead, just make sure that everything is natural. GARY: Do we have hundreds of ranking signals, by any chance?  

#### [0:20:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1200) |  JOHN MUELLER: We have lots of them.

I don't know how you would count them because it feels like things like how we sort strings is essentially a ranking factor, right? GARY: What? JOHN MUELLER: No? There's all of these different algorithms that play a role in the final result. It's like, how do you even count them? MARTIN SPLITT: That's a good question. GARY: I think it's 420. JOHN MUELLER: 420. OK. MARTIN SPLITT: Just because of the 420 joke, did you literally just make a 420 joke?  

#### [0:20:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1230) |  GARY: Maybe. MARTIN SPLITT: (SIGHS) GARY: I

would never joke about this. Come on, Martin. MARTIN SPLITT: Seriously. JOHN MUELLER: We should count those ranking factors now, but I really have no idea how you would count them and how you would even like split them up. On the other hand, what I think is really neat is when people externally try to understand search and they try to figure out how search might be working, to look behind the bigger picture  

#### [0:21:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1260) |  and try to figure out what kind

of algorithms might be playing a role here? How can I understand how search engines work? Because there is technology behind all of this. It's not a magic box where you just drop things in and things come out. It's essentially something that people can code, and you can learn how to code and you can learn how to make search engines. It's not something that you should ignore completely. MARTIN SPLITT: So I think this is an important point.  

#### [0:21:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1290) |  You say, yeah, you can code this

and you can understand how it works. But I guess, ultimately, the goal of search engines is to show the most relevant and useful content for users to the users searching for something. So how does that work? Do we know exactly how we need to rank or how to do this? Or is this something that is emerging, or how does that work? JOHN MUELLER: It's something that we have to keep working on. Like I said, it's not a science where you can say,  

#### [0:22:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1320) |  this is the absolute correct answer and

everything else is wrong. But rather, you could discuss that maybe this is the best answer or something else is the best answer. It might be, today, this is the best answer. But maybe next week or next month, we discover, well, actually, we should have been looking at it differently. Maybe something else is the best answer. And obviously, there are some things where there is a scientific answer. Like, if you ask, what is 2 plus 2, the answer is obviously 4.001 when it comes to computers.  

#### [0:22:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1350) |  Or maybe it's just 4, I don't

know. But a lot of things really don't have absolute answers. And this changes over time fairly quickly, as well, where maybe if you're looking for a vacation destination, you'd like to find some general information about that destination. But if suddenly, that vacation destination is in the news, then probably you want to see something different when you search for that location. I mean, I don't know who's going on vacation nowadays,  

#### [0:23:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1380) |  but at some point, we'll be able

to go on vacation again. So that'll be relevant then, I'm sure. GARY: I just shed a tear. MARTIN SPLITT: Aw. JOHN MUELLER: Aw. GARY: I want a vacation. MARTIN SPLITT: There will be vacations again at some point. GARY: Anyway, I would also like to add there that we also take quite a bit of user voice into shaping the algorithm because when we evaluate new launches, then it is tested first on humans, pretty much  

#### [0:23:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1410) |  all the launches. Be that live experiments,

where actual users are getting the new algorithm or piece of the algorithm into their search results, and they can see different results, differently sorted results. And then we look at things like clicks, how they reacted to the new results, to understand whether the launch is good or bad.  

#### [0:24:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1440) |  And then, we also have raters, humans

who would leave us feedback on side-by-sides to help us understand what went well and what went wrong with a specific potential improvement. MARTIN SPLITT: And I think tracking ranking is also pretty weird and tricky for people externally. Because even if your website continues to be fantastic, other websites might come into the web that have better information or more up-to-date information  

#### [0:24:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1470) |  for something. And then you just don't

rank as high anymore. That doesn't say anything about your website specifically. It just says something about both how we are thinking about ranking as it comes to the different ranking factors, as well as the web moving. That's just something that happens. JOHN MUELLER: I think that's definitely something that comes into play every now and then as well. On the one hand, our algorithms change. On the other hand, user expectations change. Some of that might be reflected in the algorithms directly.  

![](https://i.ytimg.com/vi/JagcQtuJt6o/maxres3.jpg)



#### [0:25:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1500) |  And then, of course, all the other

websites on the web are in the same pool. And sometimes, it makes sense to show some of them more frequently. Sometimes, it makes sense to show your side more frequently if we think that it's more relevant for users. And I think another tricky aspect there is that sometimes, there is just a lot more than pure relevance when it comes to ranking. In particular, factors like-- I don't know-- HTTPS or speed are things where we can say,  

#### [0:25:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1530) |  well, technically these sites are just as

relevant to users, but we think this one provides a better user experience, or maybe we feel this one makes it easier to view the actual content. And maybe it makes sense to show that one a little bit higher. So these are all small, subtle things that also play a role in there. And in some cases, maybe they don't play a big role. In other places, maybe they do play a significant role in which of the results we show first in the search results.  

#### [0:26:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1560) |  GARY: Interesting. JOHN MUELLER: Yeah. GARY: Fun

stuff. JOHN MUELLER: OK. Well, that's, I think, my monologue all about ranking factors and things. I do wish that people continue to stay curious about these things, but it's also worth taking them with a grain of salt to think about, well, actually, there is a lot more involved, rather than just one factor that you should be focusing on, or one element that you should be using as feedback to send to Google and say, well, my website is faster  

#### [0:26:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1590) |  than this other one. Therefore, it should

be ranking first. MARTIN SPLITT: Hm. JOHN MUELLER: Yeah. MARTIN SPLITT: Fun times. JOHN MUELLER: Fun times. Yeah. I don't know. Talking about fun times, how is the video recording going, Martin? MARTIN SPLITT: Oh, my. Oh, my. So not all of us, but some of us have been sent this-- a bunch of kit for recording videos from home because the studios are closed, which is super sad. But it makes sense that we are producing video content from home now. So Web Dev Live is an online event  

#### [0:27:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1620) |  full of pre-recorded talks that are being

put on YouTube with a live Q&A with speakers, and super cool idea, super cool concept. We do the same thing with the Webmaster Conference Lightning Talks. We do record these videos continuously. We have recorded some before the lockdown and some are recording now. And yeah, it has been interesting to assemble the kit like this. So much stuff that you need to screw together, and then  

#### [0:27:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1650) |  put in the right position. And then,

we have been chasing around our apartments to find the right spot to film so that it looks nice, but not too noisy. And aye, aye, aye, aye, aye. So that took quite a while. And then we recorded. And then I am used to recordings, and I do enjoy them. And I'm normally one or two takes for a thing. But not anymore. We recently recorded a few things from home, and it took me quite a while.  

#### [0:28:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1680) |  First, I was misconfiguring the teleprompter, and

then the light was changing because there were clouds. I don't know. John, you're recording videos from home as well. How was the experience for you? JOHN MUELLER: I think it went perfect. I just had one take, and we were done in like 10 minutes. I don't know, Martin. MARTIN SPLITT: You liar. JOHN MUELLER: No, actually-- (LAUGHS) it did take quite a bit of time. So finding the right position and moving things around so that it looks kind of reasonable. I mean, it just takes time.  

#### [0:28:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1710) |  And getting the lighting in a way

that makes sense, that takes time. And of course, we're not in a studio, but rather, at home, so the rest of the family is out and about doing things. I think, for one part of the recording, we had random noises from the kitchen all the time, which is, well, understandable. You have school and kids have to get something to eat in between. So you have to do something quietly in the kitchen.  

#### [0:29:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1740) |  But all of these small distractions just

make it a little bit harder, I guess. But I think, overall, it's been interesting. You have a lot more appreciation for the team that's usually involved with recordings, where usually, your job is just to speak some text and kind of look reasonable into the camera. And now, it's like all of these small parts that have to play in together. And it's like, oh, is the color right? Is the sound the right level? All of these small things, where it's really--  

#### [0:29:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1770) |  there's just so many fantastic people that

are involved in these recordings. MARTIN SPLITT: And we had a beautifully shared moment in one of the recordings where there were garbage trucks backing up into back alleys in three different locations at the exact same time. It was hilarious. People were looking at me like, hold on, there's a garbage truck backing up. And then, one of the producers was like, oh, wait a minute. That's actually-- that's on my end. This is happening here. I'm like, no, no. It's also happening here. And then the third person in the call is like, no, no.  

#### [0:30:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1800) |  This is also happening here, as well,

actually. And that was kind of interesting. That was funny. JOHN MUELLER: Yeah. I mean, ultimately, we try to make these as clean as possible, but it's not a sterile environment. We work from home and try to get things right. MARTIN SPLITT: I think it makes them even more personable, right? It's like, oh, yeah. They are at home as well. Look at that. JOHN MUELLER: Yeah. It'll be fun to look back at these after a couple of years when everything settles down.  

#### [0:30:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1830) |  I mean, hopefully it doesn't take a

couple of years, but at some point, it'll be settled down and kind of see how things were back then. Maybe we should just document it more. MARTIN SPLITT: And it's all the anecdotes. Anna, our producer, when we were trying to find the right place, was super picky. The bookshelf was too much clutter in the background-- visual clutter. And then my walls were white and boring so we couldn't use these. And she was quite picky. It took us quite a while, but it was good.  

#### [0:31:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1860) |  I think this-- as you say, it

makes you appreciate the effort even more. JOHN MUELLER: Yeah. Cool. Well, I-- GARY: Wait, wait, wait. Wait, wait. MARTIN SPLITT: Whoa. GARY: I have one very important thing to say. Well, actually two. One, John, your hair is back. I'm so disappointed. JOHN MUELLER: It happens. I don't know. It's like, I took it all out, and then it came back. GARY: I think you should dye it. JOHN MUELLER: Dye it? MARTIN SPLITT: Wait, what? Oh, I misheard that sentence because I'm like, wow, Gary.  

#### [0:31:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1890) |  That's rude. GARY: Dying hair rude? How

about you, Martin? You look like a-- MARTIN SPLITT: Careful. GARY: --some PG-13 unicorn that fell into a unicorn lake. MARTIN SPLITT: Yes, precisely what happened. I told you my user agent is PinkFluffyUnicorn. GARY: You have a user agent? MARTIN SPLITT: I do have a user agent. JOHN MUELLER: That's perfect. Wow. GARY: Wait, you actually have a user agent? MARTIN SPLITT: Yes. GARY: Like, you modified your browser's user agent?  

#### [0:32:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1920) |  MARTIN SPLITT: Actually, yes. Fun story. Yes,

I did, just to piss off one person that I know is checking their analytics for the different browsers that are accessing their website. I used to run with a very specific user agent, and they're like, who the hell is this? And because I was traveling so much recently in the last couple of years, he couldn't pinpoint it down because the requests were coming from all over the place. JOHN MUELLER: Oh, man. You're such a troll, Martin. GARY: That's amazing. JOHN MUELLER: I love it. GARY: I should do that.  

#### [0:32:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1950) |  MARTIN SPLITT: Definitely. GARY: I should just

put Gary as user agent. MARTIN SPLITT: Just put Internet Explorer 4.5. JOHN MUELLER: Oh, my gosh. That's terrible. GARY: I actually wonder how the web would break for me if I modified my user agent to just be Gary. [LAUGHTER] JOHN MUELLER: I think you should try it out. MARTIN SPLITT: Yes. JOHN MUELLER: Yeah. GARY: I should try it out. JOHN MUELLER: And if you don't see anything break, then you should color your hair. MARTIN SPLITT: Oh. GARY: I will not do that, I promise you that. MARTIN SPLITT: Aw. JOHN MUELLER: OK. MARTIN SPLITT: All right. JOHN MUELLER: Well, in that case, looking forward to seeing Gary in my server logs.  

#### [0:33:00](https://www.youtube.com/watch?v=JagcQtuJt6o&t=1980) |  [LAUGHTER] All right. Well, thanks for listening,

everyone. I hope you found this episode insightful, and if you did, let us know in the comments, ideally on Twitter, so that we can see where we could improve, what we could change, how things are working for you as well. And of course, like and subscribe, as always, like you do with these podcasts or YouTube videos. I don't know. Now I'm confused.  

#### [0:33:30](https://www.youtube.com/watch?v=JagcQtuJt6o&t=2010) |  But let us know. All right. Thanks

for joining us, and hope to talk to you, I guess, in the future at some point. GARY: Bye. JOHN MUELLER: Bye. MARTIN SPLITT: Have a day. GARY: Have a day. [MUSIC PLAYING]  