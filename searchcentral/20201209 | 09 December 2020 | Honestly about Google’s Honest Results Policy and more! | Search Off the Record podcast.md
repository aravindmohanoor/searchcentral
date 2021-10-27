[![Honestly about Google’s Honest Results Policy and more! | Search Off the Record podcast](https://i.ytimg.com/vi/t46OTdKmbyE/maxresdefault.jpg)](https://www.youtube.com/watch?v=t46OTdKmbyE)

## Honestly about Google’s Honest Results Policy and more! | Search Off the Record podcast

In this episode, John, Martin, and Gary discuss the different types of rendering, they deep dive into the details of Google’s Honest Results Policy, and reveal how the association between John & ‘cheese’ came about. Have a listen!



Transcript for this episode → https://goo.gle/3lGg2Nu



Watch more Search Off the Record on YouTube → https://goo.gle/2JL3t5Y

Have a favorite way you like to listen to podcasts? Find Search Off the Record on most major podcast platforms → https://goo.gle/search-off-the-record



Google Search developer site → https://goo.gle/35HtREZ 

Search Off the Record on the Google developer Site → https://goo.gle/3qt1XGP



Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



Search Off the Record is a podcast series that takes you behind the scenes of Google Search with John Mueller, Gary Illyes, and Martin Splitt from the Search Relations team.



#SearchOfftheRecord



#### [0:00:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=0) |  [ELECTRONIC MUSIC] JOHN MUELLER: Welcome, everyone, to

the next episode of "Search Off the Record," a podcast that we're trying out. Our plan is to talk a little bit about what's happening at Google behind the scenes and maybe have some fun along the way. My name is John Mueller, a Search Advocate on the Search Relations team here at Google in Switzerland.  

#### [0:00:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=30) |  And I'm joined by Martin and Gary,

who are also on the team. MARTIN: Hi. JOHN MUELLER: Hi, Martin. Hi, Gary. GARY: [NON-ENGLISH] JOHN MUELLER: Good morning. So we've done a number of episodes now. And I think we're slowly getting the hang of it. It feels a little bit new and exciting every time, though, so that's pretty cool. How's it working for you all? MARTIN: It's going pretty well. I'm really enjoying these recordings and these episodes and the responses we get. It's quite fun. GARY: It's awkward. JOHN MUELLER: That's fantastic. Cool.  

#### [0:01:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=60) |  All right. Martin, you had a topic

that was kind of on your heart. MARTIN: Oh, yeah. JOHN MUELLER: What's happening on your side? MARTIN: I was wondering if it's just me, or if it's, like, a larger thing, but I got a bunch of messages and questions regarding the different kinds of rendering. And I also observed that whenever people are asking about JavaScript sites, the number one thing that they get as a response is, oh, you need to pre-render this. And I was wondering, do you guys actually  

#### [0:01:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=90) |  know the difference between pre-rendering, server-side rendering,

and dynamic rendering? Or is that, like, all a blurry thing? JOHN MUELLER: Those are just different names for the same thing, right? MARTIN: Yeah, it's not. GARY: So the reason we hired you is to not have to know about these things. MARTIN: Fine, fine. OK. You are probably representative of the general population in this case, because I think it is seen as being like different names for the same thing,  

#### [0:02:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=120) |  but it's actually slightly different things. So

you can pre-render things when you know when the content is changing. Then you're basically, like, creating static content from your dynamic setup with JavaScript. And you would run that on the server side. But you know when the content is changing. So if you have a normal website, like a blog, for instance-- your recipe blog is a fantastic example for that, Gary, because when know you are updating a recipe or adding a new recipe, and then you basically run your JavaScript-- well, if you would use JavaScript. I know you hate JavaScript. You're not going to use JavaScript, probably.  

#### [0:02:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=150) |  But you would then run your JavaScript

and create the static version of that and then be done until you then make the next change or publish the next recipe. But then there's websites that are a lot more dynamic-- like, I don't know-- social networks or auctioning platforms or something like that where things happen dynamically based on user input. And then you would have to run your JavaScript every single time someone is visiting the page, either in the browser or on the server. So server-side rendering is doing that whenever the request comes in from a user to your server.  

#### [0:03:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=180) |  The JavaScript runs on the server, generates

the HTML there. And then there's dynamic rendering, which is kind of server-side rendering, but you only do server-side rendering for bots like Google Bot and other search engines and stuff like that. So they're not the same thing. Many people are like, oh, but Martin, if they're not the same thing, which one should we use? And it's like-- it's the answer we probably always give, which is "it depends." And then people are like, what does it depend on-- which is a legitimate follow-up question, if you ask me. And it's like, it depends on your site.  

#### [0:03:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=210) |  What kind of side do you have?

How often does your content Change I don't know. But yeah, that's a question that I get often. GARY: So you said on server-side rendering that the JavaScript runs on the server. MARTIN: Mm. JOHN MUELLER: So why wouldn't-- like, for example, in case of a WordPress blog, where things are generated by PHP, would you still run the JavaScript on the server, or you just generate the stuff with PHP and forget about JavaScript altogether because life would be so much better?  

#### [0:04:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=240) |  MARTIN: I mean, the thing is, if

you have WordPress which is written in PHP, then yeah, PHP would generate the content. And then JavaScript adds some fancy bits and pieces of functionality over it. But for instance, if you're using Ghost, which is a blog engine similar to WordPress-- not [? SCMSC, ?] I think, but it's pretty much the same thing. But it was written in Node.js, so you would run the JavaScript on the server side. And then it does the same thing as PHO would do. It takes whatever inputs come from the request, maybe makes a read to the database, and then generates the HTML on the server.  

#### [0:04:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=270) |  GARY: So basically, in case of server-side

rendering, what you're saying is that JavaScript acts as a server-side language. JOHN MUELLER: Yeah. MARTIN: And that's it. JOHN MUELLER: Pretty much. MARTIN: Interesting. JOHN MUELLER: But you can combine those as well, right? GARY: Yeah. JOHN MUELLER: Why? GARY: Because you can. So I'm kind of thinking at one of the CMSs I made, like, a long time ago to go back to the old CMS topic where basically, there was a giant database behind it. And every time it needed to generate a new page,  

#### [0:05:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=300) |  it could do that on the fly,

but it was just really slow. So I cached, like, the whole HTML response. I just cached that. And the next time someone went to that page, I just pulled that page from the cache. And that's kind of like server-side rendering, so something kind of, I guess, in between there, right? MARTIN: Well, it pretty much is server-side rendering plus caching, but there's an additional bits on the spectrum, kind of, which is like server-side rendering and hydration. If you say, OK, so here's the thing--  

#### [0:05:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=330) |  I don't know. Let's say, like, I

have a blog. And on this blog, I do have comments that work a little bit like a chat. So you should be seeing when people are typing things. But there's nothing stopping me from building this in JavaScript. And then if I do it completely client side, that's a little bit of a waste because then basically, everyone who comes to my website then has to like run the JavaScript to generate just the static part of the content, like the article and the comments that have been written beforehand. So I could just use the same codebase that I used to make that happen dynamically  

#### [0:06:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=360) |  and flexibly in the browser. I can

run that on the server to get all the content that already exists from the database or from a cache-- I mean, caching is fine-- and then load the JavaScript in the browser again to then also have the dynamic bits and pieces where, when people are typing, that it says, like, someone is typing a new comment, and things like that, and have it more tech-y like. So then you get the best of both worlds, kind of. And that's why you would do this-- because then you have one code base, and you get the benefits of server-side rendering,  

#### [0:06:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=390) |  but you also get the benefits of

client-side rendering where server-side rendering gives you speed and stability and client-side rendering gives you the flexibility and dynamic-ness of-- I think it's just like the dynamic-- the dynamic of an application in the browser. JOHN MUELLER: So you're kind of saying, all of these things are not pure SEO techniques? Like, they weren't made for other reasons, actually? MARTIN: Yeah. One thing-- it's often quoted developer experience-- like, as a developer, you don't want to write  

#### [0:07:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=420) |  a bazillion different pieces of code that

kind of do the same thing. Obviously, try to write one piece of code that is then easier to maintain than three or four pieces of code that are kind of doing the same thing. The other thing is user experience, which I think is even more important than developer experience, because browsers are damn good at parsing HTML as it arrives, whereas JavaScript-- I mean, the JavaScript engines get faster and faster, but still, they have to get the entire JavaScript blob, then parse that, then execute that.  

#### [0:07:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=450) |  And then that makes network requests to

fetch data, and then that creates the HTML. That's bound to be slower than making network requests, get the HTML start rendering. There's no way that we can speed that up with pure JavaScript, I think. JOHN MUELLER: I have an idea. MARTIN: Uh-oh. What? JOHN MUELLER: What if we make JavaScript a ranking signal? And if you use JavaScript, then your site will rank lower. MARTIN: What if we make you a ranking signal,  

#### [0:08:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=480) |  and whenever you're having bad mood or

comments like this, then websites just generally rank better, which would lead to everything ranking better and every SEO being happy? How about that? JOHN MUELLER: Martin, this is a horrible idea. GARY: That's what I was about to say. Ah, that's amazing. So we agree! I love this. JOHN MUELLER: So we should put little gifts of Gary and Martin on pages and-- GARY: It's GIFs. JOHN MUELLER: GIFs? GIFs? MARTIN: The inventor says GIFs, and the inventor is wrong how his own invention is actually properly named.  

#### [0:08:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=510) |  JOHN MUELLER: OK. So we'll make pings.

What about pings? MARTIN: That's good. I like that. I didn't know that people pronounce it like that. JOHN MUELLER: We can make WebPs. WebPs are animated too. MARTIN: What are WebPs? JOHN MUELLER: WebPs? MARTIN: I only know WebM or WebP. GARY: Ah, yeah. WebP-- oh, our pop filter is not helping with this. MARTIN: Pop filter really isn't helping with this. JOHN MUELLER: So I have no idea what you two are talking about, by the way.  

![](https://i.ytimg.com/vi/t46OTdKmbyE/maxres1.jpg)



#### [0:09:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=540) |  MARTIN: So we have that format, the

WebP. JOHN MUELLER: Yeah. MARTIN: We are talking about that. JOHN MUELLER: Oh! MARTIN: If you make multiple WebPs, you know? JOHN MUELLER: Yes. I completely forgot that that exists. Yes. MARTIN: Well, shame on you. GARY: So we could make one WebP of Martin and one WebP of Gary. And if you put them both on the same page, it kind of evens out. And your page will rank equally as before. How about that? JOHN MUELLER: Why don't we just create a new meta tag called Meta Name Ranking, and then it can have the values good or bad?  

#### [0:09:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=570) |  MARTIN: We already have that. JOHN MUELLER:

Which one is it? MARTIN: Well, we have Meta Page Rank. And you can assign whatever value to it, and that will be your page rank. GARY: Oh, I love that. That's amazing. More people shouldn't use this, I think. MARTIN: Is that shouldn't use it or should use it? GARY: Should use it. MARTIN: Oh, OK. GARY: Everyone should have it. MARTIN: Just checking. GARY: Yeah, no, I'm serious now. [MUSIC PLAYING] And another thing that kind of surprised me while I was at this entire demystifying  

#### [0:10:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=600) |  the different rendering scenarios and performance of

each of them, and blah, is that a lot of people are sending me questions via direct messages on Twitter, or some people even guess my email address, and then the emails-- I just ignore them because I don't want to encourage that. Because we can't really-- as far as I'm aware, we can't really answer things in private, right? MARTIN: Yeah, that's generally right. GARY: Do you get these kind of things, and how do you deal with them? MARTIN: Sometimes. GARY: Yeah. This is an interesting topic and something that we should talk about, perhaps.  

#### [0:10:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=630) |  It's also a hairy topic, so bear

with me. Generally-- MARTIN: Bears are hairy. Yeah, that's true. Sorry. GARY: I want to quit. MARTIN: No. Keep talking about it. How do you deal with these things? Teach me your ways. GARY: So this is kind of a sensitive topic. In general, we-- or I don't. And when I get an email from someone asking for help, then usually I will read the email, at least so I know what is it about. But in the vast majority of the cases,  

#### [0:11:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=660) |  I will opt for not answering. And

in this case, it's not because I'm mean, but it's because we have an internal policy called Honest Results. And that policy helps us keep the playing field equal for everyone. So basically, it doesn't matter if you are a small publisher or a big publisher or you spend $1 or you spend nothing with Google or you spend millions of dollars with Google Ads  

#### [0:11:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=690) |  or you have your own Google product--

you work at Google, and you have your product-- or you have Google acquaintance, an employee working at Google. It doesn't matter. We have to keep the playing field equal for everyone. And based on that policy, I usually opt for not answering. Basically, if someone wants to get an answer, then I would much more prefer if they asked in public.  

#### [0:12:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=720) |  I don't know how John handles these

kind of questions, but this is my way, and this is my interpretation of the quite clear policy that doesn't require interpretation. MARTIN: So I get a lot of these emails and direct messages as well, sometimes by Twitter, sometimes through other channels. And for the most part, I do try to funnel them through the public channels. So from my side, that's kind of publicly on Twitter,  

#### [0:12:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=750) |  and asking in the public realm there,

joining the office hours, Hangouts, asking there. But I also send a lot of people to the Webmaster Help Forums that we have where there is experts that are active there that can try to help resolve an issue or help look at other ways of looking at an issue. And if they don't see ways to resolve it, then they can also escalate that to Googlers. The main reason why sometimes I look at things that come in privately is to double check  

#### [0:13:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=780) |  to see what's happening there. So in

many cases, people will be like, I have this problem in search, and my website is not indexing anymore. And you're like, wow. It's like, OK, but I have no idea what you're talking about. Can you at least give me some examples? And those examples that they send are sometimes useful to figure out, is this more of a systemic issue, or is this something that is kind of like a one-off on their website?  

#### [0:13:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=810) |  So that's kind of why I look

at those emails. GARY: Yeah. I think that's an important bit. If we notice that there might be something systemic going on, then we generally would start looking into it and escalate. Because we do want to catch outages, as we talked about in previous episodes. And these kind of emails generally can help with that. So for example, during the last outage  

#### [0:14:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=840) |  that was a few weeks ago, I

think both John and I noticed that we started getting emails that followed a very specific pattern or pointed in the same general direction. And that helped us identify that there was an ongoing issue with search. But in general, we try not to dig too much, I guess. MARTIN: Yeah. GARY: And also, the same applies if there's an internal escalation. Like for example, we have Google employees who talk to external folks--  

#### [0:14:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=870) |  like for example, people working on Google

Ads, say account managers. Obviously, they talk to their publishers, their advertisers. And in some cases, those advertisers might face an issue with search, with organic search. And our culture is kind of-- try to be helpful. And the account managers would try to help those publishers.  

#### [0:15:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=900) |  And then they would escalate internally or

try to escalate internally. And we can take those questions. We can't answer them. We can't even really debunk them because that would give an unfair advantage to a publisher or advertiser who spends money with Google. And it just wouldn't be fair with the wide ecosystem. MARTIN: Yeah. GARY: We do know that this puts the account manager, for example, or whoever took  

#### [0:15:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=930) |  the question from the external party in

a tough position. But we do have to-- and I stress this a lot-- we do want to keep a fair playing field for everyone. MARTIN: Yeah. And that makes it also so tricky. So I do read these emails. I do read the direct messages. But one thing with direct messages is that I think they're inherently unfair, especially on some social media platforms where you can search in them-- like, Twitter direct messages, for instance.  

#### [0:16:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=960) |  I don't want to point out Twitter

specifically, but they are like a fire hose. Either you are lucky and I see them because I happen to be in my direct messages at the time yours comes in, or I don't. And I only recently noticed that there's, like, two different-- so if someone I don't follow writes a direct message, they land on two different lists. Apparently, there's the message request, and then there's whatever they consider a filtered message request. And I only recently found out that the second list exists. And I'm like, oh, my god.  

#### [0:16:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=990) |  I'm so sorry. There's this message from

a week ago and this list that I just learned that exists. And it's one that is, after looking into it, a one-off issue. And I don't feel like I should respond to them. So I usually then send like a response like, hey, sorry. I can't provide you with private support. Please go to the Webmaster Forum. Or if it's a JavaScript-specific problem, to my office hours, if it's a more general problem, to John's office hours, or if it's a JavaScript-specific issue, you can also go to the mailing list, the .ly/js dash [INAUDIBLE] dash wg.  

#### [0:17:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1020) |  And then I hope for understanding. And

most people are really understanding. And some people are just repeating their question. And I'm like, I'm sorry. I want to be helpful. I want to help you here, but I can't. There are the public channels. Please use the public channels. And yeah. If you are unlucky and you send them during the night, for instance, and 20 other people send me direct messages, I'm literally just not seeing them. GARY: Right. One thing that I sometimes do when someone asks me something in public on Twitter,  

#### [0:17:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1050) |  for example-- and then I would ask

for a URL because I do want to debug. And then they say that, well, they can't post the URL in public. Then I would DM them and ask for the URL, and then at least with that, I can start debugging. But I would not continue providing support in private. I would go back on the public Twitter thread and continue there without disclosing anything about the site, of course, because that's how they chose  

#### [0:18:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1080) |  to proceed with the escalation. MARTIN: And

sometimes, if I do see the direct messages and they are asking for something that is documented publicly, I just send them the link to the public Docs. I think that's fine too. GARY: Yeah. JOHN MUELLER: This all sounds, like, kind of random ranking questions, and how do I do this in search kind of thing. But what if there is a real bug in search? You search for-- I don't know-- my name, and some political scientist shows up inside of a photo of me, which is an obvious bug.  

![](https://i.ytimg.com/vi/t46OTdKmbyE/maxres2.jpg)



#### [0:18:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1110) |  And if I were an advertiser and

went to my account manager and reported that-- would you say, well, this is a bug, will fix this medially, or what would you do there? GARY: Here's the thing. We know that our results are not perfect, but we also cannot take literally every question. There's just no way that we could. If we could hire perhaps, like, 100,000 engineers whose only job is to work on search and debugging search issues,  

#### [0:19:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1140) |  maybe we could take a look at

every single escalation that we get, perhaps. But in the current state, it's just not feasible to take every question and debug and fix every potential issue that we find. The other aspect of this is that I can't take questions or I can't give preferential treatment to acquaintances or friends. So I wouldn't be able to escalate your issue, John.  

#### [0:19:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1170) |  Sorry. JOHN MUELLER: Oh, no. GARY: Well,

tough up. JOHN MUELLER: But let's say my site-- I am an advertiser at Google, and my site is really important. It's nothing like my actual blog. And it's something that lots of people search for on Google. And they really want to find it. And suddenly it gets dropped from the index. And I contact my account manager, and I'm really angry. And he's like, I will stop advertising with Google unless you fix this indexing issue for my site. What kind of thing would happen there?  

#### [0:20:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1200) |  GARY: So here's the thing. The point

where you lost me is the money aspect of it. Well, you partially lost me. Whenever I see that people are quoting that they spent millions with Google Ads, it's like, well, yeah, OK. And basically, that's it. That will not make us debug. In this context, in your questions context, what might make a difference is that the policy recognizes that we  

#### [0:20:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1230) |  might need to take action where we

know that the problem is affecting lots of our users. But those kind of decisions are essentially made by the search leadership, not individual search engineers-- or us, essentially. JOHN MUELLER: OK. But those exceptions are not based on how important I feel my site is. It's based on some objective measure that Google would apply. GARY: Yes indeed, yes. It's never based on how much you spend  

#### [0:21:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1260) |  on Google Ads or any other Google

product, Google Cloud or whatever, or how important you think your site is, or pretty much anything-- just like, objectively how important your site is for Google users. JOHN MUELLER: OK. So basically, if I have a problem with my site in search, then I need to go to the public channels. But what if the problem is not my site per se, but rather, some spam that is ranking above my site? And surely Google wants to clean out that spam, right?  

#### [0:21:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1290) |  GARY: Now I feel like I'm in

a deposition or a journalist grilling me or some EC hearing or something. Thank you for these questions, John. They are great. So spam is yet another thing that we don't like in our results, and we do our best to keep it out the results. And we encourage people to submit spam reports. I don't remember how you can get to that spam report form,  

#### [0:22:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1320) |  but you can search for it, and

you will probably find it. But we take those spam reports in aggregate. We don't take action on individual spam reports. We look at the bigger picture painted by the spam reports and try to find scalable ways to deal with specific kinds of spam. So if you have an issue with spam, then yeah, report it. And that's pretty much your best bet.  

#### [0:22:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1350) |  And just don't wait for a quick

action, because that's not how it happens. JOHN MUELLER: OK, cool. And I guess another question I sometimes see, especially from coworkers on the sales side, is when a site has trouble verifying in Search Console or when they have trouble using Search Console in a specific way. Would that fall under this kind of policy as well? Or would we say, well, Search Console  

#### [0:23:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1380) |  is just a product, and using it

doesn't affect search? GARY: Well, Search Console is a search product. So by definition, it falls under honest results. And I know it's super frustrating for account managers and customer support managers and whoever talks to external folks and escalates internally. But even there, we cannot give unfair advantage. Because think about it. We wouldn't be able to keep the same level of support  

#### [0:23:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1410) |  with someone who is-- I don't know--

computer illiterate and happens to find our email and email us. Because we just don't have capacity for that. If we had capacity for that, then again, it might make things different. But currently, we don't. And we do want to have a fair or a level playing field for everyone. JOHN MUELLER: That sounds pretty good. I do see how frustrating this can be for co-workers on the sales side with these kind of things.  

#### [0:24:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1440) |  I don't know. Do you also sometimes

see these cases being escalated up where it's like, my boss will talk to your boss, and then next boss and VP and whatever? Do you see those kind of situations being helpful, or does that not change anything? GARY: Turns out that I have feelings, which I didn't know. But sometimes they come up, and it's weird. And when people escalate to us and we have to tell them no because honest results,  

#### [0:24:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1470) |  I do feel bad for them because--

like, I work on support a long while ago before Google, and I know that it puts them in a very tough position. But escalating on the ladder is not making anything better. If anything, I might actually develop a bias against that person and essentially don't feel anything next time they escalate something and just be more blunt with them on email  

#### [0:25:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1500) |  when they will escalate. And also, I

think those working on honest results, those who are enforcing the policy, they also don't really appreciate these ladder escalations. Because ultimately, the honest results internally is very clear on what we can do and what we cannot as a search team where we can take escalations from and where we cannot. And just escalating on the ladder will not solve literally anything.  

#### [0:25:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1530) |  If anything, it will just add more

frustration. JOHN MUELLER: Yeah. So have you seen some of these sites where you push back, for honest-results reasons, end up going to the public channels? Or do they just try to figure things out in different ways? GARY: I did, actually. I do see, every now and then, people who I push back on-- post on Twitter, for example. Like, if I recognize the name, then I don't even need the URL from them. I can start looking.  

#### [0:26:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1560) |  But they would still get the same

level of support. So for example, if I miss their tweet, for example, I will not go and actively look for their tweet. If it happens to show up in my face when I go to Twitter, which happens a lot, then I might start looking. But then that happens with other tweets as well. JOHN MUELLER: Cool. So if you were working at a bigger company that had relationships with Google already, what would you do if you ran into a search issue  

#### [0:26:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1590) |  with your website? It's not being indexed

properly. It's ranking in a way that you think is bad. Would you still try through the account manager side, or would you say, oh, I'll just do everything public? GARY: Honestly, I would go to your office hours. JOHN MUELLER: Yeah, these office hours. So I tend to do them about once a week, and I post about them on our YouTube channel in the Community section. So if you go there, you can find out when the next ones are.  

#### [0:27:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1620) |  We also have them listed on the

Events page for the group overall. So in that Events Calendar, you can see the next office hours that are lined up. And usually what happens is people can post their questions on YouTube, and I'll post the link to join the office hour session, which is basically just a video call with a smaller group of people. And they can join in, ask questions directly, interact a little bit. And we'll post a recording of that  

#### [0:27:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1650) |  afterwards on the YouTube channel. MARTIN: So

go to youtube.com/googlewebmasters or to google.com/webmaster-connect, I think, right? JOHN MUELLER: Wow. You're like a walking bookmark collection, Martin. Awesome. MARTIN: Yeah. Digging it. GARY: I already worked on Search, right? I know that account managers or cloud customer managers, they can't authoritatively answer search questions. And I know already that they will be pushed back on it. So there's no point escalating there.  

![](https://i.ytimg.com/vi/t46OTdKmbyE/maxres3.jpg)



#### [0:28:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1680) |  But I would still rather talk to

a person who claims to be a real and try to get some answer, at least. To me it's obvious already that we can't always give direct answers. We can't directly answer something. But I also found that just giving a general direction-- and I salute general direction-- can be very helpful. If you just see the path that you should take, that might already be enough to debug  

#### [0:28:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1710) |  a certain issue on your side or

on my side on, non-Google side. JOHN MUELLER: Cool, yeah. GARY: And the other thing is that I know for certain that this person, John Miller-- don't make that face. You know that person too. He does escalate internally when he thinks that there is something systematic going on or something looks utterly weird, and we should perhaps debug. And for that, we have internally this form called  

#### [0:29:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1740) |  go/bet or Go Bet where people can

escalate to the Search team and Ranking team issues that they think are important and what they encountered themselves, perhaps. It's not a general debugging forum. JOHN MUELLER: General debugging. GARY: Yes. I salute general debugging. It's not a debugging forum, so it's not like the Ranking team will take action or start debugging every single issue posted there.  

#### [0:29:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1770) |  It's more like a collection of issues

that were reported, I suppose-- basically, historic records of issues so we can see that there is something systematic going on, for example, or it's a one-off issue. JOHN MUELLER: OK. MARTIN: So yeah, I would just go to the office hours. I heard they are awesome. I've never been but, I heard they're awesome. GARY: They're fantastic. And also, I used the [? Go Bad ?] forum a few times for things that were quite badly broken,  

#### [0:30:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1800) |  and they get triaged quite quickly if

they're obviously problematic. MARTIN: I mean, this is something that we see externally all the time. I guess people who are more involved with search, they tend to have an eye for this, whereas someone on Twitter or some acquaintance will be like, oh, I searched for this popular term, and I received these really weird results. And it feels like Google should be serving something better. It's not that I have a site that is directly involved  

#### [0:30:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1830) |  or that I have anything tied to

this particular query, but this search is just broken. And it could be improved. And for cases like that, this forum is something that I really think is useful. I mean, like you said, Gary, we just get so many different kinds of issues all the time. It's impossible to fix everything that comes up. And with any complex piece of software, I guess there are always some parts that are subtlely broken or sometimes visibly broken.  

#### [0:31:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1860) |  So there's always something to do. But

it's cool to have this way to report these kind of issues. I guess externally, you can also use the feedback form directly in the search results. But sometimes, if something is really critically broken and really badly broken, then getting our attention, either like one of us three or Danny Sullivan or someone else on the Search side, that can make it so that we can recognize  

#### [0:31:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1890) |  the issue a little bit faster and

fix it a little bit faster. GARY: Yeah. I'm kind of happy that you mentioned the feedback form because I know that some of the analysts do escalate from those feedbacks to the [? Go Bad ?] group. So they do get attention. There is some human-- well, someone who claims to be human-- looking at those feedbacks and taking them internally if they are actionable, at least. JOHN MUELLER: Cool, cool. So I guess the other thing that is perhaps less common  

#### [0:32:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1920) |  nowadays is when people go to your

desk, and they ask questions. They're in person. Is that something you've ended up doing, Gary? GARY: I miss those times. I used to have so much fun with going to others' desk. JOHN MUELLER: What do you mean, so much fun? MARTIN: Like when he taped my mouse or when he put something into one of the USB ports. And I was like, why is this not working? And yeah. GARY: What do you mean, one of the ports? I thought it was all of the ports.  

#### [0:32:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1950) |  MARTIN: Right, two, yeah. All of them.

True. GARY: Yeah. I would not go for one port. I would just tape all the ports. JOHN MUELLER: When I went to the office recently after such a long time not being able to go, I tried to use my computer, and the mouse didn't work. And I was like, hmm. I wonder if Gary was here. But it turns out that my whole computer had just frozen, so-- [LAUGHTER] GARY: Yeah. I like to pull minor practical jokes on my co-workers.  

#### [0:33:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=1980) |  And sometimes that ends up being very

public expression of affection, I guess. JOHN MUELLER: Oh. You mean like the time I expressed my love for cheese? [LAUGHS] GARY: Yes. That was one of those cases. That was a friendly reminder that your computer has confidential information that others should probably not see, and your account has access to confidential information that others might not need to see.  

#### [0:33:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=2010) |  So I gave you a very affectionate

hint to lock your computer when you are not at your computer. Of course, you were just, like, 3 feet, 1 meter away from the computer, but still. I have to keep you on your toes. MARTIN: Yeah. GARY: So I posted your name on Twitter that you love cheese. You're welcome. JOHN MUELLER: It was great. I thought it was fun, and it seemed to pick up some steam as well. At one of the conferences back when you went to conferences--  

#### [0:34:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=2040) |  it's such a long time ago-- in

one of the conferences, someone gave me a cap and a t-shirt with "I love cheese" on it. It was fantastic. MARTIN: Aww, that's awesome. GARY: But now I'm safe. At least I think I'm safe. MARTIN: Don't give Gary ideas. GARY: I miss conferences. MARTIN: I do miss conferences too. GARY: I used to get swag all the time. JOHN MUELLER: I don't miss the swag, but I do miss the people and the point that you can have conversations.  

#### [0:34:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=2070) |  GARY: Yeah. I only miss the swag.

[LAUGHTER] I mean, look. I'm showing it to you. I'm sitting in a t-shirt with Daniel Weisberg's face on it. MARTIN: Wow. JOHN MUELLER: That's amazing. GARY: I have Daniel Weisberg's face on my chest. That came out wrong. JOHN MUELLER: That came out very wrong. GARY: On a t-shirt. JOHN MUELLER: Yeah. GARY: On a t-shirt. JOHN MUELLER: So you're saying we should have Daniel on this podcast as well? Or is he indirectly present already? GARY: Yeah, he's already here.  

#### [0:35:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=2100) |  Come on. And he's very quiet. I

appreciate that. But we should definitely have guests. Maybe we could have [? Anna, ?] our producer, sometimes chime in, for example. MARTIN: Oh, wow. GARY: For example, she could explain how hard it is to work with us-- well, with me. Or we could have-- oh, we could have Lizzi, our tech writer, Lizzi Harvey. JOHN MUELLER: Oh, yeah. MARTIN: Oh, yeah. GARY: We could have her. We could have [? Sherry, ?] for example, [? Sherry ?] [INAUDIBLE]. She's our teammate working on Southest Asia, outreach  

#### [0:35:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=2130) |  in Southeast Asia-- well, actually, APAC, I

think. We could have her. JOHN MUELLER: I think we're putting a lot of pressure on us now that we mention all of these people that we could have as guests. GARY: I'm doing it on purpose. MARTIN: The other one I thought would be kind of cool is someone from the internal SEO team. Because Google needs SEO as well, different Google properties. And that would be, I guess, an interesting discussion also with regards to honest results policies there.  

#### [0:36:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=2160) |  It's like, how do they interact with

us? GARY: Oh, yeah. JOHN MUELLER: Because from what I usually see, they come to us with a question sometimes. And usually, they just get pushed back right away. So it'd be interesting to see their side of that story, how that works out for them. GARY: Yeah, we should definitely do it. JOHN MUELLER: OK, fine. We will get something set up. MARTIN: Also, if you, listener, have ideas about what you would like to hear on this podcast,  

#### [0:36:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=2190) |  feel free to ping us on Twitter.

GARY: And please don't self-nominate. JOHN MUELLER: Direct messages, or would you prefer in the Help forum? GARY: No, not direct messages. MARTIN: Public tweets. GARY: Public tweets. Just tweets. Also, they can't DM me. I don't allow people to DM me. JOHN MUELLER: OK, cool. All right. So I guess with that, let's take a break here. Thank you all for listening in. I hope that you found this insightful and kind of useful and saw a little bit of some of the challenges that we face with all of the escalations  

#### [0:37:00](https://www.youtube.com/watch?v=t46OTdKmbyE&t=2220) |  that we get from people externally. I

always find it interesting to talk about these topics because it's-- like, all of us get different kinds of questions externally, and hearing how we handle them. So it's sometimes really interesting. So if you're keen on listening to the next episode, make sure to stay tuned. Subscribe to the podcast. And if you are one of the guests that we mentioned as being a potential guest, then I don't know. Watch out for an email from us.  

#### [0:37:30](https://www.youtube.com/watch?v=t46OTdKmbyE&t=2250) |  And if you have feedback for us

in general, feel free to drop that on Twitter. Thanks again, and see you next, time. Bye! GARY: [NON-ENGLISH] [UPBEAT ELECTRONIC MUSIC]  