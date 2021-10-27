[![Site Migrations: SEO Mythbusting](https://i.ytimg.com/vi/bGPB-rtxt-I/maxresdefault.jpg)](https://www.youtube.com/watch?v=bGPB-rtxt-I)

## Site Migrations: SEO Mythbusting

In the fourth episode of SEO Mythbusting season 2, Martin Splitt (Developer Advocate, Google) and Glenn Gabe (Digital Marketing Consultant, G-Squared Interactive) discuss the most common SEO questions and myths around site moves, URL migration, domain name changes, and more!



Specific timestamped topics discussed in this episode:

Redirecting images during a site redesign or migration (0:00)

Will you always experience a drop in traffic with a domain name change or a site migration? (1:53)

Buying a new domain name with history & traffic anomalies (2:40)

Site merger vs site move (6:24)

What goes on on the Google side once a domain name change is triggered? (8:12)

Why would one use the Change of Address Tool? (10:16)

If a site moves, is there a reassessment of content quality by Google? (11:15)

Should you revert back if a site migration results in a major drop in traffic? (14:54)

Should one unblock URLs normally blocked by robots.txt during a site migration? (17:31)

Most common problems after a site moves & doing things step-by-step (18:16)

(19:32)



Documentation mentioned in this episode:

How to 301 redirect images during a website redesign or CMS migration → https://goo.gle/32tGMJz 

Site moves (with URL changes) → https://goo.gle/2FQti2E 

Change of Address Tool  → https://goo.gle/3lh3uNq 

Penguin update → https://goo.gle/32j0ibi 



Watch more SEO Mythbusting episodes → https://goo.gle/SEO-Mythbusting

Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=0) |  GLENN GABE: I wrote a post actually

one time after I helped a large-scale e-commerce retailer that hadn't 301 redirected its images, right, so that the images were n-- MARTIN SPLITT: Oh, right. Mm-hmm. GLENN GABE: Right. So I wrote a post about, like, don't forget to redirect images during a migration, right? MARTIN SPLITT: Definitely. Visual content-- so important. GLENN GABE: Very important. You would recommend, obviously, making sure to 301 redirect all images-- MARTIN SPLITT: Yep. GLENN GABE: --and then just wait. If it takes a little longer to refresh in the image index, then just do that, right? MARTIN SPLITT: Definitely. Definitely. And just check the server logs on the old domain to see if traffic really has ramped down.  

#### [0:00:30](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=30) |  And once you are happy with not

seeing as much crawl activity, you can flip the switch and say, OK, we can now discard this. [THEME MUSIC] Hey. And welcome, everybody, to a new episode of "SEO Mythbusting." With me today is Glenn Glabe. And we usually meet at conferences,  

#### [0:01:00](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=60) |  when we're speaking on various stages, or

we talk on Twitter. But what are you doing when we are not meeting on conference occasions or when we are on Twitter? GLENN GABE: Yeah, sure. So I run my own consulting business, G-Squared Interactive, where I typically am helping companies that have experienced a drop in traffic. MARTIN SPLITT: Cool. GLENN GABE: Yeah. MARTIN SPLITT: All right. That sounds pretty awesome. GLENN GABE: Absolutely. MARTIN SPLITT: And today, we are here to talk about one possible issue that they might encounter, and that's site moves, right? GLENN GABE: Site moves, URL migrations, domain name changes--  

#### [0:01:30](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=90) |  right. Exactly. MARTIN SPLITT: All right. OK.

That's really cool. So what are the misconceptions or problems that people are facing there? GLENN GABE: Yeah, sure. So there's lots of myths. And there's actually a lot of confusion in the industry about these. Some site owners are scared to actually pull the trigger on it because they don't know what's going to happen. And others are actually pulling the trigger too quickly-- not preparing for it. And then there's a lot of people in between, right? MARTIN SPLITT: Mm-hmm. GLENN GABE: So I guess the biggest myth is that you will always experience a drop in traffic with a domain name change or site migration.  

#### [0:02:00](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=120) |  MARTIN SPLITT: Oh, yeah. Right. Yeah. I

think that's a very good one, because the answer to it is, it depends, as you know. So a lot of times, people are not understanding what a site move is. So if you are literally just moving from one domain to the other-- copying pretty much the entire URL structure and the entire content over-- then you will not necessarily see a drop of traffic. You will see that traffic drops off over time on one domain and picks up on the other. But overall, that doesn't really mean that you have a traffic drop-- you're not losing traffic.  

#### [0:02:30](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=150) |  If we can do this very clean

move, then there's not really going to be a drop period, where one drops and then the other picks up. But there is more a fluid transition. GLENN GABE: Got it. Now, what's interesting is that I've been part of some domain name changes-- let's stick on that one for a second-- that went completely smoothly. Sometimes the site will actually go up over time, so on and so forth. Then there were some weird anomalies, right, where-- and like you said, it depends, right? So a site that, three days after, completely tanks by 70%.  

#### [0:03:00](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=180) |  And is it based upon the history

of the domain? Maybe the domain that they're actually moving to was bought and had a history of its own. Is there anything that you could elaborate on that maybe? MARTIN SPLITT: So normally, it's not much about the history. The history does play a little bit into it, especially if it's basically being used for spending purposes and then you buy in and immediately switch. That's a tricky one. You want to make sure that you're not dealing with weird issues. And you want to make sure that you have your monitoring, and Search Console, and all that set up properly  

#### [0:03:30](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=210) |  before you do the switch. It can

also just be-- if you are making other changes as part of your site move, that's a risky one. Because then we can't really-- we don't know that it's just a move, but we see, like, oh, hold on, the-- when we are crawling this, there's differences in what we are seeing here. Hmm. Maybe we need to be careful and re-crawl a little more. And then you might-- depending on how large your site is, you might want to do crawl budget things. So it depends on a bunch of factors, but normally getting a domain that you know is not dealing with issues from the past  

#### [0:04:00](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=240) |  should be just fine. And even if

it's a domain with history-- we are aware that content on domains do change. But depending on what the domain looked like beforehand, we might not consider it a site move. And then we would have to re-crawl and reprocess everything. And that takes a little longer. GLENN GABE: Interesting. So let's say that there is a site-- a domain name that was used-- I'll give you an example, actually. It was a client that had a really long domain name. They were an e-commerce retailer.  

#### [0:04:30](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=270) |  And they were like-- wow, they want

to get just the four-letter domain name that represented their company. They finally got it. They went live with it, right, did the domain name change. And then they called me about a month in. And they're like, oh, no, this is not good. What's going on? It ends up that domain they didn't research. And it was some, like, rock band from the past that had all sorts of crazy spammy links and all sorts of stuff. MARTIN SPLITT: Ooh, yeah. GLENN GABE: So they definitely in the short term saw a dip, but then it corrected itself over time.  

![](https://i.ytimg.com/vi/bGPB-rtxt-I/maxres1.jpg)



#### [0:05:00](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=300) |  MARTIN SPLITT: Yeah, yeah, yeah. Exactly. As

we see, content can change. You bio spam your domain, or you just literally have it hacked for a while and then you fix it. You know how that goes, right? Whenever you have problems that we detect and point out to you, and you fix them, it takes a while for us to understand that it has changed and that everything is better now. But that's generally what happens. So you want to make sure that you will clean out anything that might be problematic up front and give us time to understand that things have now changed and we are now back to a clean slate. So you have to do some cleanup if there  

#### [0:05:30](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=330) |  was problems in the past. GLENN GABE:

Got it. So in that situation, it probably would have been smart, first of all, if they researched the history-- MARTIN SPLITT: Mm-hmm. GLENN GABE: --and then maybe filed a disavow if there were a bunch of bad links there, just to make sure from the beginning that this was more of a cleaner transition? MARTIN SPLITT: If you take over the domain, make sure that you are measuring what happens through tools like Search Console, and that you understand how the domain is doing. Maybe even consider removing the content and waiting for us to understand that the content has removed-- so that things are normalizing and we  

#### [0:06:00](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=360) |  are clearing out the signals. And then,

step by step, migrate your domain over so that as we discover the pages to be moved, we also understand, like, OK, so this is a new start for this domain. GLENN GABE: Got it. OK. All right. How about another myth? MARTIN SPLITT: Yeah, sure. Yeah, hit me. GLENN GABE: Or-- and then we could-- MARTIN SPLITT: What do you have? GLENN GABE: And then we could go into more details of what go-- MARTIN SPLITT: All right. Yeah, yeah, yeah. GLENN GABE: --goes on behind the scenes. How about taking a site, merging two sites into one site, and thinking that 1 plus 1 will equal 1 when  

#### [0:06:30](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=390) |  that won't necessarily happen? MARTIN SPLITT: Yeah.

GLENN GABE: And I've been part of a few of those that actually went very well and others that didn't go poorly, but it wasn't 1 plus 1 equals 2. MARTIN SPLITT: Yeah. So that's not such a simple situation anymore. Now, beforehand, we talked about a site move. And "site move" literally just means we're moving everything we've got over to somewhere else. That's the site move. The moment I'm combining two sites-- that's not moving two sites into one. That is creating a new site that is a merged version of the two. So that is, by definition, not a site move.  

#### [0:07:00](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=420) |  This means that we have to understand,

OK, so now there's a bunch of more this content moves here, this content moves here. But there's a bunch of other things going on here-- it's a completely different domain. Or maybe not. Maybe it's just, like, the URL structure change in some way or another, or there's there's new content moving here from somewhere else. None of that is as simple as a site move. So we have to basically re-crawl a lot of pages. Depending on how large your site is, that might mean that it takes a while for us to literally just get a lay of the land in terms  

#### [0:07:30](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=450) |  of what content is there now. Depending

on how you set up your site structure, we might understand, OK, this just, like, new section of the site has been created. Or if you're, like, mixing them in, then it's like, uh, what's happening here? Did the other things change as well, or is it just this new content? So depending on how you merge the sites, you might get very different results from how we are coming to an understanding of your new site structure and your new site content. And that can go smoother or less smoothly  

#### [0:08:00](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=480) |  depending on how you do it, yeah.

GLENN GABE: Got it. Got it. Now, with a domain name change-- just to hop back there-- so I'm really interested-- and I know site owners are interested in this, and a lot of SEOs, I'm assuming-- what goes on in the Google machine once the site move, the domain name change, is triggered, right? Change of Address is switched, right? MARTIN SPLITT: Right. GLENN GABE: That's activated. 301s are in place. What happens? MARTIN SPLITT: So what happens is that eventually we're going to be crawling what we used to know about your site.  

#### [0:08:30](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=510) |  And we do get the signals from

other sites pointing to your content there. And we understand, OK, there's a redirect, and it's not a redirect in isolation. It is basically literally just completely move here. And then we have to make sure that what we knew before is true for what happened afterwards, because you could hypothetically have changed the site fundamentally. And then, again, it is not a site move. But as more we discover that it's basically just a one-to-one copy and it's just like moving everything over from here to there, we will basically  

#### [0:09:00](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=540) |  make sure that we forward the signals

that we had from the old site to the new site, to the new domain, and then make sure that we are getting more or less an efficient lay of the land without having to re-crawl everything. You might still see increased crawling activity, but eventually that's going to settle down as we understand that the site is just a copy of what was there in the different space beforehand. And then, eventually, the signals will fade out and the crawling will fade out on the old domain.  

#### [0:09:30](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=570) |  And we're just going to be moving

swiftly on as if nothing happened afterwards with the new signals that we have for the new domain. GLENN GABE: Got it. Got it. And how fast do signals get passed? MARTIN SPLITT: That depends on so many different things. If your website doesn't get crawled as much, then, pfft, there's nothing that's going to make that go-- [SNAPS FINGERS]-- like this. GLENN GABE: OK. MARTIN SPLITT: If there's a lot of crawl demand and crawl budget for your website, then we might actually do that relatively quickly. It can be in a day. It can take a week.  

![](https://i.ytimg.com/vi/bGPB-rtxt-I/maxres2.jpg)



#### [0:10:00](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=600) |  It really depends. Also, how many links

do we have from different sites? How often do we crawl these? And how quickly can we discover that everything has been moved over? And yeah, it can take a few days, up to a few weeks. GLENN GABE: Got it. MARTIN SPLITT: Yeah. GLENN GABE: And what does the Change of Address tool do differently than just having 301s? Is there some trigger in the back that Google's like, OK, the Change of Address tool is being used. We know that it's verified by this owner. Is there something better that happens there?  

#### [0:10:30](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=630) |  MARTIN SPLITT: It tips us off that

this is what you were intending to do. So we know that it's not a temporary thing, or that it's a mistake, or something. You're explicitly telling us. You're giving us an additional signal, saying, like, hey, we're moving, rather than us being like, hold on, that's a bunch of redirects happening here. Do we-- is-- what's hap-- is that-- what's going on? So you're giving us a more explicit signal that this is a site move. So we can probably re-prioritize things. We can make more useful decisions  

#### [0:11:00](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=660) |  in how we want to crawl and

how we want to identify if we can pass the signals on or not. And that might speed things up because we can take a few shortcuts if we know that this is an intentional switch. GLENN GABE: Got it. So good to do? MARTIN SPLITT: Mm-hmm. Definitely. GLENN GABE: Right? OK. One thing I've seen-- and I don't know if this is true or not, but I'm just wondering when there's a site move if there's a reassessment of quality on a site? Like, when there's a domain name change, is Google going, OK, well, now let's re-evaluate quality there? Or if there was a URL migration--  

#### [0:11:30](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=690) |  URLs all changed-- would it trigger something

like that? MARTIN SPLITT: Well, that happens constantly, right? If you have a page that has high quality content, that doesn't mean that this will always be high quality content, which is also why having a history is not the end of everything. If you have a spammy or thin-content page that was bad and you improve it, we are going to reevaluate the quality as well, right? It constantly happens. Site move is no different. But obviously, when you change URLs and especially URL structure, then that tips us off to, like, oh, hold on,  

#### [0:12:00](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=720) |  there's some-- we're not sure about this.

Is this the same as we had beforehand? If so, we can just move the signals over to the new URL. If we are not sure about this, we have to make a very careful evaluation if that is true or not. So yes, it is doing that, but it does that all the time. GLENN GABE: Got it. Got it. So basically-- I've heard before, from John and stuff like that, that they're going to re-evaluate a piece of content based upon its current form, right?  

#### [0:12:30](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=750) |  MARTIN SPLITT: Mm-hmm. Absolutely. Yeah, yeah. GLENN

GABE: So that's kind of what you're saying, right? MARTIN SPLITT: Yeah. GLENN GABE: So it would make sense that sometimes-- because what I've seen is, let's say, a domain name change happens, a URL migration. And then maybe two weeks later, there's a core update. And suddenly, the site either goes up or down. It's like, was that due to the change, or was it something random? MARTIN SPLITT: No. Things always fluctuate, right? So it's really hard to see the signal from the noise there in site moves. Especially if it really is just a site move-- so you changed your domain name or something-- it don't really change the quality evaluation or something  

#### [0:13:00](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=780) |  like that, no. GLENN GABE: OK. Now,

we spoke about signals being passed. Can you just, for some people that might not know it, what signals you're talking about, or? MARTIN SPLITT: Right, right. So to explain that in very simple terms, when we visit a site, we collect a bunch of information, right-- so how fast is the site? Is this HTPS or not? Is the content good? What's this page about? All this kind of stuff. All these signals and information about the page that later go into ranking. There's, like, hundreds of these factors that we look at.  

#### [0:13:30](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=810) |  And we collect them per page. If

you would go to a restaurant, you kind of do the same thing, right? It's like, do I feel welcome here? Is the staff nice? Is the food quality nice? Is the price fair? These kind of things you put in your file as signals for this restaurant. And then if someone ask you for a recommendation, you are probably using these signals that you picked up-- like, oh, if you're into Asian cuisine, that place on the 35th Street, or wherever, is really, really nice, but quite pricey. And if you then know that this restaurant has moved,  

#### [0:14:00](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=840) |  you probably want to re-evaluate some of

these, right? So it's like, oh, yeah, I was there when they were in the other location. It was fantastic. I don't know how it is in the new location. So that's kind of the situation that we are facing as well, right? If you're literally just moving everything over, you can be like, yeah, no, the restaurant just moved somewhere else, or the food truck moved somewhere else. It's the same food truck. It just stands somewhere else. It's nice. It's still cheap. Nice, good stuff. But if something changes-- the food truck now moves into a location. And then you're like, is that nice?  

#### [0:14:30](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=870) |  Is it still the same stuff? Is

it still cheap, or is it now more pricey? And that kind of is true for search engines as well. We have to then re-evaluate what we are seeing, right? GLENN GABE: So first, we had a baby algorithms analogy from Gary [INAUDIBLE] MARTIN SPLITT: [CHUCKLES] Yes. GLENN GABE: And now we have a food cart analogy from you, which-- MARTIN SPLITT: Yeah, yeah. It just keeps getting more colorful, doesn't it? [LAUGHS] GLENN GABE: Absolutely. I can see a blog post coming out about that one too. How about this one, right-- and this happens sometimes. Let's say there's a domain name change or a URL migration.  

#### [0:15:00](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=900) |  Traffic plummets for whatever reason. When do

you revert, right? When do you-- MARTIN SPLITT: Fair enough, yeah. GLENN GABE: --roll this whole thing back? Now, only a few times in my career-- and I've been through a ton of these-- have we had to do that. And I know in the Google documentation it basically says, you have 180 days to reverse the Change of Address and then you kind of put 301s all the way back from where they were coming from. It's like a total nightmare. MARTIN SPLITT: Yeah. GLENN GABE: So from your perspective, when do you think-- let's say a site saw a drop of 50%  

![](https://i.ytimg.com/vi/bGPB-rtxt-I/maxres3.jpg)



#### [0:15:30](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=930) |  after a migration, for whatever reason. At

what point do you go, yeah, maybe you should roll this thing back? MARTIN SPLITT: I think that depends on what you're identifying as the reason for what went wrong. You definitely want to do some diagnosis first before you do any moves in any direction. It's like, so is it that we are still seeing the old ones and for some reason not registering that these are re-directions? Or are we just not crawling the old ones often enough so that we have just hit a really nasty spot in the timeline of where we could potentially have moved?  

#### [0:16:00](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=960) |  Or what's going on here? If you

really do not understand where this is coming from, and you have looked at everything, and you cannot explain what's happening, I would say after a few weeks, maybe a month-- maybe give it a month or something. And then I would consider either getting help-- that's the best way to do it. Get some help somewhere with this stuff-- or if you really don't understand what's happening and it doesn't get better after a month or so, consider doing a reversion.  

#### [0:16:30](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=990) |  But only if you are really, really

sure and out of options. Because most of the times, it is some sort of technical problem, or it's like, you missed half of your re-directions and we didn't really register that it was a change of address much, or whatever has gone wrong. There's so many things that can go wrong and we can misconfigure. But you want to see traffic that drops off eventually also pick up again on the other side. And you want to monitor both sides closely. And if you really see that there's literally no pick-up on the other side, then that's  

#### [0:17:00](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=1020) |  a sign that something was not well

done or well thought through. And then you want to reconsider if you might want to go back for a while, understand what happened, and then regroup. GLENN GABE: Right. Or something algorithmically happened, right-- MARTIN SPLITT: Or something algorithmic can happen. GLENN GABE: --which is possible, right? MARTIN SPLITT: Or if we detected spammy content or you had some issues in manual actions, that's also a good reason to say, like, OK, we don't want to get these in the mix. GLENN GABE: Got it. MARTIN SPLITT: So make sure that you're starting from a clean state. And then you should not have to revert. GLENN GABE: Got it. And then on that note-- so from a robots.txt perspective,  

#### [0:17:30](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=1050) |  there are some sites-- I usually help

large-scale sites. Sometimes they have a few 100,000 URLs being blocked by robots.txt. And they'd want that, right? MARTIN SPLITT: Mm-hmm. GLENN GABE: So during the move, does it make sense to open them up so Google can see all those old URLs that maybe it had indexed but were blocked by robots.txt or anything? Or does it-- would you think that just-- MARTIN SPLITT: I would not change that. I would just keep-- if you had a reason to not have them crawled,  

#### [0:18:00](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=1080) |  I don't see why a migration would

necessarily mean that you need to have them crawled now. GLENN GABE: Got it. OK. That's good to know, because, again, some large-scale sites have a ton of URLs categorized as that. And then they don't know what to do. So-- [LAUGHS] How about problems that you see from Google's end after a migration, like robots.txt blocking the new domain, or no index across the entire new content, or how about Google Search Console  

#### [0:18:30](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=1110) |  settings not being set on the new

domain? MARTIN SPLITT: Oh, yeah, yeah, yeah. GLENN GABE: You know, things like that. MARTIN SPLITT: Yeah, yeah. It's all sorts of these things. I think one of the things is that some people are trying to use site moves as an opportunity to change all sorts of things-- GLENN GABE: Ah, I was going to bring up that later, yeah. MARTIN SPLITT: --which is really, really weird. Because realistically, you want to-- if you're in an unsure situation or if you're in a situation where you're not sure where you're going, you don't want to change all the variables at the same time, because that means you have a lot of moving targets. And then, later on, if you have a problem, you're like, oh, no, is this our new URL structure?  

#### [0:19:00](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=1140) |  Or is this the new technology that

we're using? Or is this the new content that we put up? Or is it the site move? Or is it an algorithmic thing? Or is it a penalty? Or what's happening here? And you're not sure about this. If you're doing one step at a time-- you move to a different domain, or you-- before you move domains, you're switching to a new text deck, or whatever you're doing, do it step by step. GLENN GABE: OK. MARTIN SPLITT: I think that's the biggest thing that you can do for yourself to keep level-headed.  

#### [0:19:30](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=1170) |  GLENN GABE: Got it. Got it. And

do you-- does Google have anything behind the scenes kind of like what you brought up, where some sites are like, well, I'm going to change domain names because I've been algorithmically destroyed over the past few years or to get out of manual action, if some people think that they're going to do that? MARTIN SPLITT: [CHUCKLES] GLENN GABE: Back in the day, people were doing that for Penguin. And some people were saying that was working. So is there anything behind the scenes that when, let's say, a domain name change happens, they go, well, let's make sure that this is cool or not? Or is it not-- I don't know. MARTIN SPLITT: Yeah. As I said, we are constantly evaluating what happens on the page. So if you have a bad bunch of content and spammy links to one  

#### [0:20:00](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=1200) |  and then you just move to the

next, then we might lose some of the signals along the way. But basically, bad stays bad no matter where you move. Yeah. GLENN GABE: Got it. OK. That's good to know. MARTIN SPLITT: Awesome. GLENN GABE: Well, I think that was-- probably that was-- MARTIN SPLITT: That was [INAUDIBLE] GLENN GABE: That was a lot of information, right? MARTIN SPLITT: Yeah, that was amazing. GLENN GABE: Yeah. MARTIN SPLITT: Thank you so much for making it here. And I hope that you all enjoyed our little conversation on site moves. And stay tuned for more. Bye. [THEME MUSIC] Hey, everyone. I hope you enjoyed that episode.  

#### [0:20:30](https://www.youtube.com/watch?v=bGPB-rtxt-I&t=1230) |  Next episode, I have Lily Ray with

me. And what are we going to discuss, Lily? LILY RAY: We're going to talk about, is too much content a good thing for SEO. MARTIN SPLITT: All right. So stay tuned.  