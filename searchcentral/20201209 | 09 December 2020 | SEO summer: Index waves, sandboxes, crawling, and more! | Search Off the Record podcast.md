[![SEO summer: Index waves, sandboxes, crawling, and more! | Search Off the Record podcast](https://i.ytimg.com/vi/YDK78_jIGRs/maxresdefault.jpg)](https://www.youtube.com/watch?v=YDK78_jIGRs)

## SEO summer: Index waves, sandboxes, crawling, and more! | Search Off the Record podcast

In this SEO summer themed episode, John, Martin, and Gary discuss two waves of indexing, the sandbox and honeymoon periods, crawl budget, and more. Have a listen!



Episode transcription → https://goo.gle/3gn7Ws9



Watch more Search Off the Record on YouTube → https://goo.gle/2JL3t5Y

Have a favorite way you like to listen to podcasts? Find Search Off the Record on most major podcast platforms → https://goo.gle/search-off-the-record



Google Search developer site → https://goo.gle/35HtREZ 

Search Off the Record on the Google developer Site → https://goo.gle/3qt1XGP



Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



Search Off the Record is a podcast series that takes you behind the scenes of Google Search with John Mueller, Gary Illyes, and Martin Splitt from the Search Relations team.



#SearchOfftheRecord



#### [0:00:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=0) |  [MUSIC PLAYING] JOHN MUELLER: Welcome, everyone, to

the next episode of "Search off the Record," a podcast that we're trying out. Our plan is to talk a bit about what's happening at Google Search, how things work behind the scenes, and maybe have some fun along the way. My name is John Mueller. I'm a search advocate on the Search Relations team  

#### [0:00:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=30) |  here at Google in Switzerland. I'm joined

here today by Martin and Gary, who are also on the Search Relations team. Good morning! GARY ILLYES: What do you mean "good morning"? Do you wish me a good morning? Or mean that it is a good morning, whether I want it or not? Or that you feel good this morning? Or that it is a good morning to be good on? [SPEAKS RUSSIAN] JOHN MUELLER: Yes, yes. GARY ILLYES: "There's no such thing as a good morning." MARTIN SPLITT: You said yes. What does that mean? What does that mean, John? JOHN MUELLER: You gave me a bunch of options with or in between.  

#### [0:01:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=60) |  So the logical answer is yes if

one of those is true. GARY ILLYES: That's the opposite of logic. Ahh, this is the worst day of my life. JOHN MUELLER: So far. MARTIN SPLITT: And it's 4:00 AM. GARY ILLYES: Ahh. JOHN MUELLER: So far, Gary. MARTIN SPLITT: In Gary's time zone that is, right? GARY ILLYES: Ahh. JOHN MUELLER: All right, Martin, do you want to take us off? MARTIN SPLITT: Sure thing. Speaking of logic and fantastic things, do you remember when we were introducing the two waves of indexing like two years ago?  

#### [0:01:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=90) |  JOHN MUELLER: Yes, yes. I was involved

with a lot of that back then. We worked together, I think, with Tom Greenaway, who is also on the Developer Relations team at the time, to talk about rendering and indexing for the first time. And I think we introduced the two waves metaphor there. MARTIN SPLITT: Mhm, thanks for that. That's great. I think I understand where that's coming from. And if I remember correctly, basically, I joined the team right before you did that presentation  

#### [0:02:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=120) |  at I/O 2018. And I was convinced

back then that yeah, that's a fantastic way of explaining how things work in rendering, and indexing, and crawling. Because it's such a complicated process, with lots of things happening in parallel. But I got to say, I kind of have to deal with the fallout from that metaphor because it invites misunderstandings. And people are like basically relatively frequently asking, so how long does it take for the second wave to happen?  

#### [0:02:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=150) |  Or how do I deal with my

website being indexed before the second wave happened, and these kind of questions. Which, I think, given the metaphor, makes sense. But given the way that the process actually looks like, it's not helpful for them or is not like leading to the right results. And I really try to like phase out this metaphor, but it keeps coming back at me. And yeah, I mean, the way that we are seeing it in most cases-- and basically, that's nearly 100% of the cases--  

#### [0:03:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=180) |  your website gets crawled, then it gets

rendered, and then it gets indexed. There are certain situations where that isn't true, like when the rendering fails multiple times, or when we have other signals that we can pick up from the initial HTML and stuff. So it isn't necessarily that everything gets rendered. But pretty much, practically, every website gets rendered before it gets indexed. And, ah, yeah, so I wonder how long I'll have to, I don't know, swim through these two wave metaphors  

#### [0:03:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=210) |  to get to safer land? That's going

to be fun times. JOHN MUELLER: So do you think we should not have introduced it like that? Or do you think we just need to be clearer in what is the current status? MARTIN SPLITT: I think we should have introduced it like that but explain that it's a simplification, it's like a mental model for people to look at, and that it's not literally that. I think people took it quite literal. And that causes a few confusing moments, I think.  

#### [0:04:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=240) |  Where I would say like, if you

look for a simple mental model, assume crawl-render-index. And then if you are seeing really weird things, then you might actually look into what's going on more specifically or ask us more specific questions for your specific case where that might not be the case. But I think the metaphor was OK. It's just people took it a little too literal. JOHN MUELLER: Now, I mean all of rendering and JavaScript is pretty complicated.  

#### [0:04:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=270) |  So it's probably hard to find a

middle ground that explains where the problems might be coming from, and what they need to be doing. MARTIN SPLITT: That is true. JOHN MUELLER: But I think you've been here a couple of years now. And you see how, when you say things once on our side, it sticks around for a really long time. So-- MARTIN SPLITT: Yeah. JOHN MUELLER: Sometimes that's challenging. MARTIN SPLITT: And things just keep changing. And that's kind of fine because in the end, most of the changes are implementation details that have not much impact.  

#### [0:05:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=300) |  But then people kind of like latch

onto them and be like, ooh, so is this a big thing? And I'm like, no, it's fine, it's OK, don't worry about it. And then also there's ranking involved. It's like, oh, my website didn't get indexed. And I'm like, actually, it is indexed. It's just not ranking for anything. Yeah, fun times. There is always fun. And then people are like, ooh, is this because the website only gets out of the sandbox once the JavaScript has been processed?  

#### [0:05:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=330) |  I'm like, no, that's not-- ahh, yeah,

it's tricky. JOHN MUELLER: Sandbox, yeah. Well, I guess since we talked about waves and sandbox, this is almost like a visit to the beach, you know? [INAUDIBLE] MARTIN SPLITT: Ooh, vacation theme. JOHN MUELLER: The sandbox is probably one of those topics that's similar to, I guess, the two waves of indexing in the sense that people talk about it once. And sometimes, when it comes to SEO,  

#### [0:06:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=360) |  everything is so complicated that you try

to look for simplifications, and you cling to those simplifications for a really long time. And sandbox and honeymoon period are kind of two other simplifications that keep coming up over and over again. Is that something you ran into as well, Martin? MARTIN SPLITT: Oh, yeah. So I recently did this tech SEO Reddit AMA, where people were asking me questions. And not only did the two waves come up multiple times-- I mean, it's vacation time.  

#### [0:06:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=390) |  I think people are taking their mind

to the beach, so that's that. But also the sandbox and honeymoon periods came up. And it struck me as weird because kind of one precludes the other. It's like if my website is new, and I get all this traffic, why does the traffic then drop off eventually? Is this the honeymoon period kind of situation? And then the next person is like, well, my website is new, and I don't get any traffic or don't get any ranking in Google. Is this the sandbox? And I'm like, so what is it? Do we have a sandbox?  

#### [0:07:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=420) |  Do we have a honeymoon period? What's

going on? JOHN MUELLER: Yeah, I always find it interesting when someone on the team asks these kinds of questions as well. Because it's not that you can go into the internal Google documentation and look for the sandbox, does it exist. Because you probably won't find a lot of useful things there. But I think the general problem there is really more a practical thing. And the names are a bit, I don't know, simplified.  

#### [0:07:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=450) |  But the practical problem is really that

if you have a new website, we generally don't know a lot about it if it's new. Because we can look at the content. We can kind of see what's written on there. But we don't really know how it's accepted within the whole web ecosystem. So from a practical point of view, our systems essentially make some guesses. And we make some assumptions trying to figure out where should we position this site in the search results, how competitive  

![](https://i.ytimg.com/vi/YDK78_jIGRs/maxres1.jpg)



#### [0:08:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=480) |  is the search results area in general

for the queries that we think we might be showing the site for. And based on all of these different factors, we try to figure out like where could we position this website until we know more about it. And that's, essentially, this period of time, which people externally sometimes simplify into sandbox or honeymoon period, where maybe we will position it  

#### [0:08:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=510) |  in a way that is very optimistic

and say, oh, wow, this looks really good. I guess, it'll perform really well in search. And we'll get lots of really good signals over time. Or we could look at that and say, well, it's a very competitive environment. There are other sites that have been working on this area for a really long time. And they're really well accepted on the web. We might need to be a little bit more critical, or, I don't know, watch out a little bit more with regards to how we position this site.  

#### [0:09:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=540) |  And that's something that is not like

an algorithm that's built in that says like, we should hold the site back, or we should show it even more visibly for a certain period of time. It's really just we don't know how to show this site in search, so we have to make some guesses. We have to make some assumptions. And over time, as we figure out how we should be showing it, kind of when we have more signals to show-- and we use lots of signals in search, of course--  

#### [0:09:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=570) |  then we'll be able to show it

a little bit more reasonably. And that could mean that maybe we were showing it over optimistically in the beginning. And as we learn more about how it's accepted, we have to kind of pull that back a little bit. It could also mean that we showed it a little bit too pessimistically in search almost, and we need to show it a little bit more visibly. But these are all things that happen over time anyway. And in particular, when a site is new,  

#### [0:10:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=600) |  that transition from not knowing a lot

about the site to knowing more about the site is sometimes a bit jarring. It's a bit more visible compared to kind of the traditional changes that happen with the site over time. So that's kind of, I guess, where the sandbox and the honeymoon period come from. Usually, when people externally bring up one or the other, they focus on just that one aspect. And telling them or showing them how other people are talking  

#### [0:10:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=630) |  about exactly the other side or the

exact opposite of that, that makes it a little bit clearer to them that it's not just like one thing or the other. It's actually kind of a balance between the two things. So I don't know. I don't think it's a topic that will go away because there will always be new people who make websites on the web. And they'll always run into this situation, where they find someone saying like, oh, you have to write about these topics, and you will rank well.  

#### [0:11:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=660) |  And they do that. They follow those

instructions, and they don't rank well. Or they rank particularly well, and they're really enthused about doing more on the web. And the next website they do doesn't rank that well. So I suspect that will continue to follow us around for a while. Maybe longer than the two waves of indexing, I don't know. MARTIN SPLITT: Mhm, I think it makes sense that these kind of things come up because it's not very easy to understand or debug these from the external point of view.  

#### [0:11:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=690) |  I think we can look at what

signals we have and then see, oh, yeah, we don't know that much about this site. And this is an area where we are more optimistic for new things coming in. But yeah, it's interesting that you can explain it like that. And it makes perfect sense. Yet people are falling back to those simplifications. And I think that's also what happens with the two waves of indexing. So yeah, except that two ways of indexing is a much more niche topic, I guess. So that's how thing--  

#### [0:12:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=720) |  GARY ILLYES: Let's see if I remember

correctly. The sandbox thing, that's been around for like 20 years now. JOHN MUELLER: Wow, that's a long sandbox. GARY ILLYES: Yeah, that's a very long sandbox. It's probably more like a beach in Brazil. JOHN MUELLER: Do you remember how that initially came up? GARY ILLYES: Well, if I recall correctly, we used to have this batch-based indexing system, right? And then that did have this weird effect. Because-- how was it? I think we rebuilt the index every month,  

#### [0:12:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=750) |  but only once every month. And then

that meant that if you created a website at the wrong time, as in farthest away from when we built the index, then you had this long wait period. And during that time, you couldn't do much with that site because, well, we were not indexing things from your site. And then somehow that indexing sandbox, I guess, transformed into a ranking sandbox  

#### [0:13:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=780) |  in people's minds as well, which was

probably not that helpful. And then we just got to enjoy talking about it for like 20 years. MARTIN SPLITT: Another thing that you probably enjoy talking about, Gary, now that we are talking about indexing already, is probably-- GARY ILLYES: Cookies? MARTIN SPLITT: Cookies is one thing. But another thing that I want to bring up is, we recently published the second episode of "The SEO Myth Busting." And we talked with Alexis Sanders about crawl budget. GARY ILLYES: Cookies? MARTIN SPLITT: Actually, we talked about kimchis  

#### [0:13:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=810) |  and crawl budget but not cookies. I'll

pick up the cookies today. I know you have another batch for me ready. GARY ILLYES: Yes. JOHN MUELLER: Which also feeds back into the batch building of the index probably. But there is still like a lot of chatter about crawl budget. And I think that has been around forever as well, right? GARY ILLYES: Can we just talk about cookies instead of crawl budget? JOHN MUELLER: No. GARY ILLYES: [SIGHS]. MARTIN SPLITT: OK, here's the thing. You talk about crawl budget now, and then we can talk about cookies. How about that? As like a reward. GARY ILLYES: Sounds awful, let's do it. OK, crawl budget.  

#### [0:14:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=840) |  We publish quite a bit about crawl

budget, I think, lately, over the past couple of years. We've been pushing back on crawl budget historically, typically telling people that you don't have to care about. And I stand my ground, and I still say that most people don't have to care about it. We do think that there is a substantial segment of the ecosystem that has to care about it. That's why we publish more on that topic and talk a little bit more about it.  

#### [0:14:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=870) |  But I still believe that-- I'm trying

to reinforce this here-- that the vast majority of the people don't have to care about it. Everyone wants a number-- basically, how big your site has to be when you have to care about crawl budget? But I don't think it works like that. And I remember that when we were writing one of the Help Center documentations, then Josh, our Help Center tech writer, was also asking this question-- OK, let's define this. Like how many pages do you think or how many URLs on the site  

#### [0:15:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=900) |  you have to have to start caring

about the crawl budget? And we were working with a Google bot team on the documentation. And both the Google bot team and us, search relations or whatever we are called nowadays, were saying that, well, it's not quite like that. It's like, you can do stupid stuff on your site, and then Google bot will start crawling like crazy. Or you can do other kinds of stupid stuff, and then Google bot will just stop crawling altogether.  

#### [0:15:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=930) |  And eventually, he did convince us to

give a number, which I don't remember, but I think it's around a million, I would say, URLs on the site. And that's our baseline. So basically, if you have fewer than a million URLs on your site, then you don't really have to care about crawl budget. JOHN MUELLER: So what is crawl budget? Is it like how much money you have to pay Google to get crawled? GARY ILLYES: Oh, wow, you didn't.  

![](https://i.ytimg.com/vi/YDK78_jIGRs/maxres2.jpg)



#### [0:16:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=960) |  That was a big bust. Thank you.

You can't pay us money and get crawled. That's not how it works. It's never how it works. The crawl budget is essentially an external made-up term, which we tried to define as the number of URLs that Google bot can and is supposed to crawl or instructed to crawl. The instructions come from indexing.  

#### [0:16:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=990) |  Basically, we have a system called crawl

scheduling, which tries to estimate which pages need to be recrawled, for example. Not rickrolled but recrawled. And Martin is making a face. You can't see this, but it's beautiful. He's almost face pulming, I think. I love that. And crawl scheduler also tries to estimate which sections of the site has to be discovered, essentially.  

#### [0:17:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1020) |  Do we have to do discovery crawls?

Discovery crawl means that we think that there are URLs in a particular section of a site that has undiscovered URLs or has new URLs, something like that. So that's what crawl scheduler does. It instructs Google bots to crawl more and also what to crawl. And then we have pure discovery crawl,  

#### [0:17:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1050) |  where Google bot can just go crazy

on the site and hop essentially from one URL to the other and push stuff to indexing. Then how much crawl bot can crawl? We tried to be good citizens of the internet. And we try not to crush servers. Not crush-- crash. Crash servers. Yes, yes, that's better. And we do have enough crawl capacity to essentially crash parts of the internet.  

#### [0:18:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1080) |  But we don't want to use that

power. With great power comes great responsibility, right? As we learned from a very smart man. And we try to go slow as possible but still discover and crawl enough from sites. We don't want to harm sites with crawling. Nonetheless, sometimes it happens. And then we have to back out. Basically, we leave.  

#### [0:18:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1110) |  We look at signals from the site

that tells Google bot that we have to back out from the site-- back off. Well, internally, we call them back-off signals. So for example, if the site starts sending us 429 or 50-whatever status codes, or it slows down considerably, then we would back out. And Google bot starts crawling slower. And if the signals continue, then slower, slower, slower,  

#### [0:19:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1140) |  slower. And eventually, it can even stop

completely because it may perceive that the site is too overwhelmed to be crawled. I don't remember this happening or seeing escalations about this. But it can happen. Yeah, so that's crawl budget-- how much Google bot can crawl, and is willing to crawl, or is instructed to crawl. I forgot what was the topic? JOHN MUELLER: [LAUGHS] MARTIN SPLITT: Crawl budget. GARY ILLYES: OK, I covered crawl budget.  

#### [0:19:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1170) |  So now we can talk about cookies?

MARTIN SPLITT: Mhm. JOHN MUELLER: So how can you tell-- GARY ILLYES: Ahh. JOHN MUELLER: If you're like running into crawl budget issues, like you have 1,000,005 URLs on your website. GARY ILLYES: And this is one more reason why we didn't choose a number, or why we didn't want to choose a number. Because then, OK, so 1,000,005 is too much or that's still fine? Well, I would look at-- I have no idea what would I look at. Probably URLs that were never crawled. That's a good indicator for how well discovered,  

#### [0:20:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1200) |  how well crawled the site is. Of

course, that also links to the structure of the site. Like, for example, if you have orphan pages, then that's very hard for us to crawl. Because we can't see them unless you tell us about them somehow. So I would look at pages that were never crawled. For this, you probably want to look at your server logs because that can give you the absolute truth. Then I would also look at the refresh rates.  

#### [0:20:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1230) |  Like if you see that certain parts

of the site were not refreshed for a long period of time-- say, months-- and you did make changes to pages in that section, then you probably want to start thinking about crawl budget. So how can you actually influence crawl budget? Well, one thing is that you want to send us-- JOHN MUELLER: Cookies. GARY ILLYES: Yeah, not cookies. I tried that, it doesn't work. I have this site spammyguy.com.  

#### [0:21:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1260) |  And it-- stop laughing, Martin. MARTIN SPLITT:

Sorry. GARY ILLYES: Are you? MARTIN SPLITT: No. GARY ILLYES: That's what I thought. So I have this site spammyguy.com. And when I launched it, it's basically gibberish content with, I think, one link to mattcuts.com. And what I'm trying to do with that is observing how Google bot, for example, behaves. Let's say I generate a bunch of URLs. And then I see that Google bot goes crazy with those URLs, superexcited and starts to crawl like crazy.  

#### [0:21:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1290) |  And if I publish on another section

some good stuff, something that I do think that should show up in the index, it's not gibberish, then basically, Google bot is wasting time on the gibberish site. Because it's out to generate that gibberish content that is linking infinitely to other pages. And it's spending time on that stuff instead of going to the good section of the site. And if you think about it, then that kind of makes sense.  

#### [0:22:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1320) |  Like if you remove, if you chop,

if you prune from your site stuff that is perhaps less useful for users in general, then Google bot will have time to focus on higher quality pages that are actually good for users. Back-out signals or back-off signals, if you send us back-off signals, then that will influence Google bot crawl. So if your servers can handle it, then you want to make sure that you don't send us  

#### [0:22:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1350) |  like 429, 50x status codes, and that

your server responds snappy, fast. Yeah, I guess that's it. But in general, I would-- unless you need to, I wouldn't worry about the crawl budget. There are better things to worry about. Like if your site is still not mobile-friendly, for example, then you could, you know, catch up with 2003 and have a mobile site already. Oh, 13. 2013, sorry. JOHN MUELLER: So Martin, does crawl budget also  

#### [0:23:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1380) |  play a role with JavaScript. MARTIN SPLITT:

A little bit. Because if you are already crawl-budget sensitive-- and as Gary said, that's not very many websites. Like most websites that talk about crawl budget issues turn out to not have crawl budget issues. But if you do, then depending on how you build your JavaScript, you might actually end up having more requests than if you do like the server-side rendered version or a static version of your website. So as an example, if you have a client-side rendered website,  

#### [0:23:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1410) |  the website loads. It loads its JavaScript.

And then the JavaScript makes the five API requests to fetch the actual content. Then all of these five extra API requests do count against your crawl budget in a way. And that can then easily scale. It's like every page that you have on your website, and you have 10 million of these pages, then there's like 10 API requests, then that does add up quite quickly. But normally, that should be fine. As Gary said, most websites have other lower  

![](https://i.ytimg.com/vi/YDK78_jIGRs/maxres3.jpg)



#### [0:24:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1440) |  hanging fruit than crawl budget to reap

first. But yeah, if you are crawl-budget sensitive, then the way that you build your JavaScript or architect your web application, that does might have an impact. GARY ILLYES: That was a very good point, the JavaScript, and resources, and stuff. Because every single URL that we crawl on the site will chip away from crawl budget. So basically, if we have to crawl alternate versions of the site-- let's say that you have 170 language variations of a page--  

#### [0:24:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1470) |  then all those will chip away from

your crawl budget. It's not like, oh, these are just a variation, and we don't count it in the crawl budget. We do have to crawl them. And if we have to crawl them, then that means that it will chip away from your crawl budget. Basically, we will have less time on something else. JOHN MUELLER: Does that also include things like CSS files or images, which usually don't change? GARY ILLYES: Yes. MARTIN SPLITT: But we do have caching in place.  

#### [0:25:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1500) |  GARY ILLYES: Ah, that's what I wanted

to say. MARTIN SPLITT: Oh, sorry. GARY ILLYES: Damn it, Martin. MARTIN SPLITT: Sorry. GARY ILLYES: Now you go. MARTIN SPLITT: Right. So let's say like you have one stylesheet for all your pages. And then we crawl one URL. And then we make the request to that URL. That's one request, and your crawl budget gone. And then we crawl the CSS file. Let's say like, well, I don't know, main.css or something like that. That's the second one. And then maybe there's like one image on this one page that we just crawled. That's the third request. Then we'd see the next page.  

#### [0:25:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1530) |  That's the fourth request. But we would

not request the CSS again because we already have it in the cache. So that would not count again against your crawl budget. And the cache is relatively aggressive. JOHN MUELLER: Aggressive cache, OK. It kind of makes sense to use cache when you're talking about a crawl budget, right? MARTIN SPLITT: Ha-ha, you didn't. Oh, my, so punny. JOHN MUELLER: OK, so sorry. MARTIN SPLITT: No worries. JOHN MUELLER: It sounds like the two waves of indexing and the crawl budget are both kind of complicated topics,  

#### [0:26:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1560) |  where people try to simplify them into

ways that are a little bit easier to understand. But when you really dig into them, it's a lot of "it depends" in there. And it's not like this clear yes or no type answer that you can just easily give, right? MARTIN SPLITT: They are rabbit holes. You can dig quite deep into each of them. But I think it makes it even more important to just at the surface level understand how your site is doing, and what your site is doing, and where to spend the time to look further.  

#### [0:26:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1590) |  If your site has 10 pages, it's

very unlikely that you will suffer crawl budget issues per se. If your site uses like a regular JavaScript framework, and you are not ranking well, then that's very unlikely to be primarily a JavaScript issue, unless you see that we are not rendering your content. So you want to very carefully find out what's causing the problem, if it even is a problem.  

#### [0:27:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1620) |  Because sometimes, what looks like a problem

really isn't a problem, depending on the tools that you use. So like this website doesn't rank for the top 100 keywords that these [? two ?] things are important. It's like yeah, but your website is in a completely different industry or niche. So why do you care? JOHN MUELLER: Yeah, I think it's interesting because there are always new people that jump into SEO, and they start working on small sites, sometimes, in the beginning. And they hear all of these complicated things and wonder what they should be watching out for. But it sounds like the two waves of indexing and crawl budget--  

#### [0:27:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1650) |  if you're working on a smaller site,

you probably don't have to care about it all. And you can kind of grow into that over time if you start working on different kinds of sites, more complicated JavaScript sites or really large websites. MARTIN SPLITT: Yeah. JOHN MUELLER: Cool, so-- MARTIN SPLITT: Start with the basics. Always start with the basics, and then build up from there. JOHN MUELLER: Cool, so when it comes a crawl budget, I heard you have to give Gary cookies, and then you get more crawl budget. Is that right? Or like how does that work? GARY ILLYES: I haven't gotten more crawl budget.  

#### [0:28:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1680) |  But I have gotten fantastic cookies. I'm

really looking forward to the next batch. JOHN MUELLER: Oh, wait, he gives you cookies. You don't have to give him. MARTIN SPLITT: Yeah, Gary had a ridiculous amount of oatmeal in his pantry apparently. And he's like, what do I do? And I'm like, make cookies. And so I got two batches of cookies, and they were delicious. GARY ILLYES: And somehow, I still have, I think, maybe 1 pound worth of oatmeal. Well, actually more, like almost 2 po-- yeah, actually, almost 2 pounds of oatmeal.  

#### [0:28:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1710) |  MARTIN SPLITT: How much is that in

real measurement units? GARY ILLYES: It's like 1 kg. MARTIN SPLITT: Ah, OK. JOHN MUELLER: Is that like-- MARTIN SPLITT: Sweet. JOHN MUELLER: --27.5 cups? MARTIN SPLITT: [LAUGHS]. GARY ILLYES: Yeah, let's not talk about that. MARTIN SPLITT: How many Caterpillars is that? GARY ILLYES: At least seven. MARTIN SPLITT: I think that's right. GARY ILLYES: Yeah, I have no idea how I ended up with so much oatmeal. But it was occupying way too much space in my pantry, in my cupboards. And then I was trying to figure out what to do with them. And I just search for something like "what to do with lots of oatmeal." And then one of the first results  

#### [0:29:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1740) |  was, well, make cookies, you dumb idiot.

I actually have no idea how I ended up with-- because I'm making vegan cookies now. MARTIN SPLITT: Yes. GARY ILLYES: But I don't remember how I ended up with vegan cookies based on the oatmeal. I think it was like most of the recipes that I found that were using oatmeal for cookies were vegan. MARTIN SPLITT: Wow. GARY ILLYES: And also, I could never in my whole life manage to make good vegan cookies.  

#### [0:29:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1770) |  MARTIN SPLITT: Oh. GARY ILLYES: Like I

can make vegan food, but I could never make good vegan cookies. MARTIN SPLITT: That's no longer true. GARY ILLYES: Yeah, no longer true. But I always had problems with that. Like either the fat part of the cookie was not right. Or it had acquired taste that was like, well, disgusting. MARTIN SPLITT: [LAUGHS]. JOHN MUELLER: Acquired taste. GARY ILLYES: I don't know how to say it nicely. It was disgusting. So yeah, this is the first time I actually managed to create good vegan cookies,  

#### [0:30:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1800) |  and I'm very happy about it. That's

not true. I'm just like OK about it. MARTIN SPLITT: You are very happy about it. And it's also-- actually, technically, it's probably the second time. Because they're-- in the three batches that I got so far, there were two different types of cookies. And the first type of cookie was great. That was the lemon cookies that you made. GARY ILLYES: Oh, the lemon cookies were excellent. MARTIN SPLITT: Mhm, yes. GARY ILLYES: Those were really, really good. JOHN MUELLER: I wish you would publish these recipes somewhere, Gary. GARY ILLYES: I'm-- yes. MARTIN SPLITT: Spammyguy.com. GARY ILLYES: No, no, no, I have a new domain  

#### [0:30:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1830) |  name for the cooking site. Or not

cooking site, for recipes site. JOHN MUELLER: Cookieguy.com. MARTIN SPLITT: Cookie guy. Quick, register that. Cookie overlay. GARY ILLYES: Yeah, maybe I should have asked you. You have a better idea than I do, apparently. Yeah, I will not tell you the domain name. But yes, the cookies site is going to happen eventually. I actually didn't have time to work on it. Now I have two interns that we will maybe introduce externally as well. And they keep me very busy nowadays somehow.  

#### [0:31:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1860) |  JOHN MUELLER: So cool. GARY ILLYES: Which

is good. JOHN MUELLER: What are your interns working on? GARY ILLYES: They are working on the robots TXT parser. I don't want to spoil it yet, but they are doing some really interesting work on-- basically enabling others to build on top of the parser. MARTIN SPLITT: Ooh. JOHN MUELLER: That sounds good, that sounds good. MARTIN SPLITT: Yeah. JOHN MUELLER: Cool. It's just like the second wave of robots TXT processor [? rating? ?] GARY ILLYES: OK, I'm out from here. MARTIN SPLITT: [LAUGHS] .  

#### [0:31:30](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1890) |  JOHN MUELLER: So sorry, so sorry. OK,

maybe we should take a break here before our things go even more downhill. Thanks you too for joining in. It's been fun and entertaining, for me at least. Hopefully, for those of you who are listening along as well. Stay tuned, I guess, for our next episode. We'll have more of these over time. And thanks for listening in. Hope to see you next time. Well, hear you. Wait, you'll hear us next time. MARTIN SPLITT: Yeah. GARY ILLYES: At one point, you will  

#### [0:32:00](https://www.youtube.com/watch?v=YDK78_jIGRs&t=1920) |  have to figure this out, John. JOHN

MUELLER: I'm working on it. MARTIN SPLITT: This is fine. JOHN MUELLER: Cool. Bye, everyone. MARTIN SPLITT: Bye. GARY ILLYES: Good day. [MUSIC PLAYING]  