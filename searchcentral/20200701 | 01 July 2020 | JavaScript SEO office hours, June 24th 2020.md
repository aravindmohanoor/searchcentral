[![JavaScript SEO office hours, June 24th 2020](https://i.ytimg.com/vi/xgc58EHkX6Q/maxresdefault.jpg)](https://www.youtube.com/watch?v=xgc58EHkX6Q)

## JavaScript SEO office hours, June 24th 2020

This is a recording of the JavaScript SEO office-hours hangout from June 17th, 2020. These sessions are open to anything around SEO for JavaScript sites.



Watch out for new sessions, and add your questions at youtube.com/GoogleWebmasters/community



#### [0:00:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=0) |  MARTIN SPLITT: Hello, and welcome to a

new edition of the JavaScript SEO Office Hours. Today, I have 13 people here in the Hangouts. We have a few questions on YouTube, so stay tuned for this episode, so to speak. I'm not even sure if this is an episode. I think it's like an episodical thing. It's a series of Hangouts, but I'm never sure if it's an edition, or an episode, or what would I call it. Anyway. Whatever. I'm digressing.  

#### [0:00:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=30) |  There is a bunch of questions on

YouTube. Let's start with the YouTube questions before we go into the audience questions. "Showing different content for an existing user based on the js-cookies. Will this hurt my SEO? For example, 'A' User is new. For this user, we show one promotion, like get started. And User B is already an existing user. For this user, we show the latest promotions. Does this impact my SEO?"  

#### [0:01:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=60) |  Kind of. Yes, it does. I mean,

it doesn't really, but it kind of does, in the sense that Googlebot does not run with set cookies, so we would only see the content that a new user would see. I would suggest to have different landing pages and then actually expose both of these through links to Googlebot so people can also see the latest promotions, if you care about that. And that would allow you to show the same content to both users and Googlebot. Just you would move the people to different starting  

#### [0:01:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=90) |  URLs, for instance. You would redirect people

if a cookie is present. That is fine. That wouldn't hurt your SEO, per se. "Can a JavaScript front-end technology change cause a drop in Google ranking? We have a few million visitors per month and follow Google guidelines. When we switched from Angular/PHP-- so, server-side rendering-- to Vue and Nuxt with server-side rendering we lost rankings immediately, about -20% traffic. Our overall Lighthouse score went from 40 to 85.  

#### [0:02:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=120) |  So do you think it's possible for

a site to drop because of the change in JavaScript? Bonus info-- we did notice that other sites had been hacked and that the hackers have made subfolders on these pages with our entire site copied in smart canonicals to spam shop pages." I'm not sure what smart canonicals are, but OK. "Could it be that, because of the timing of this, Google has considered some of the hacked sites as the true source of the content that belongs to us, as Google has to understand our new JavaScript?  

#### [0:02:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=150) |  And if so, what to do? Examples

of sites, in case these are helpful." These are helpful, but I'm not sure if I have the time to look at them right now. Generally speaking, a switch in technology should not mean that much of a change in pretty much anything except for-- I'm guessing you didn't just change technology. You probably also changed, maybe, site structure, or maybe you changed the way that your content was presented,  

#### [0:03:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=180) |  If you made changes above the threshold

of where technology is serving. We don't really care about the technology that runs. We care about the content. So if you have made changes to the way that you present the content, that would mean that we would have to take time to actually re-understand things. It could coincide with the other hacks that were trying to take content away. You can check if we consider your pages canonical  

#### [0:03:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=210) |  for the content that you produce. So

that's something that I would double-check. And ranking can always change a little bit. There's things happening on the web all the time. So ranking changes are not necessarily something that comes from the technology that you choose, but other factors might be part of that, as well. It could be that it was an update to the algorithms. Ranking isn't really my area of expertise. But, generally speaking, assuming that all the content is visible and present in the rendered  

#### [0:04:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=240) |  HTML and your website apparently got faster,

I wouldn't expect that to be the source of ranking changes. It could be these hacked websites. It could be that just the way that you represent your content has changed fundamentally and that we need time to reprocess it. That's also the same thing with people redoing their sites, revamping their sites, changing the way that the content looks like and is presented to the user, and then they see changes like this because fundamentally you have created a new website.  

#### [0:04:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=270) |  If you really just changed the underlying

technology, and everything else-- the way that you show the content, and the URLs and all that-- stayed the same, then we wouldn't have seen that much of a difference. Then there's a question. "Hi, Martin. I'm helping a nonprofit, and I'm afraid that the content in a very important part of their website is not indexable because it's made up of widgets loaded by scripts. Will you be able to confirm and maybe have some tips on how they could add the content differently  

#### [0:05:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=300) |  to make sure it's indexable by the

bots?" Well, what you're saying is you're afraid that, which means you're probably not sure that this is actually a problem. Content loaded by scripts and widgets is not exactly an issue per se. I would plug this URL into any of the testing tools-- be it the URL inspection tool, be it the mobile-friendly test, the rich results test-- and look at the rendered HTML. If the content that you care about in this section of the page is present in the rendered HTML,  

#### [0:05:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=330) |  then there's nothing to worry about. If

it isn't, then you would have to investigate why it isn't in the rendered HTML. There's a follow-up question, a pretty good question, on the first question, the first question being the one regarding showing different content based on cookies. "How about websites where new users, including Googlebot, are shown on the HTML side, but logged in users are shown the JavaScript homepage without any textual content at all?"  

#### [0:06:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=360) |  Per se, what happens once you're logged

in is not something that search engines really care for. I mean, do what you feel is right. We can't see things behind the login to begin with, so I wouldn't worry about that, to be honest. For SEO reasons, anything behind the login is invisible to us. You're welcome. I think it's time to take a few questions from the audience. Anyone has a question today? CHRISTIAN KUNZ: Yes.  

#### [0:06:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=390) |  Hi, Martin. MARTIN SPLITT: Hi, Christian. CHRISTIAN

KUNZ: I would like to start. I have two questions, but maybe the first one. It's from a client of mine and I only have it in German, so I tried to translate it. MARTIN SPLITT: You can actually ask the question in German, hypothetically, and I'll happily answer it in English. But I think if you can translate it that would be fantastic for the audience. CHRISTIAN KUNZ: Yes, yes. I will try. It's about a single page application.  

![](https://i.ytimg.com/vi/xgc58EHkX6Q/maxres1.jpg)



#### [0:07:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=420) |  It's under a domain which is redirected

to the www domain. And this causes problems with end users who have a bookmark to the non-www domain. It's causing a CORB, C-O-R-B error because the service worker who delivers pages from the cache for the database content points to the other domain, which is with www.  

#### [0:07:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=450) |  This is causing these CORB problems. And

the question would be, is it OK to redirect to the www only if the user agent is Googlebot or a crawler, and show the non-www version for the normal page visitors?  

#### [0:08:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=480) |  MARTIN SPLITT: Just making sure that-- that

was a lot, and it's early. You have a non-www and you have a www domain. And the problem is with people who bookmark the non-www. Why don't you redirect everyone to the www domain, including those who have bookmarked the non-www domain? CHRISTIAN KUNZ: Yeah, because then  

#### [0:08:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=510) |  the client says there's a problem with

database fetching and the service worker, because it shows these CORB errors. MARTIN SPLITT: Right. But that means that this service worker, or whatever it is that is making these requests, while being on the www domain requests something on the non-www domain. CHRISTIAN KUNZ: Yes. MARTIN SPLITT: That's the root cause. You should fix the root cause. In that case, your service worker should use the www domain to make fetches.  

#### [0:09:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=540) |  And then you redirect everything to the

www domain. CHRISTIAN KUNZ: If that's difficult from a technical point of view-- I am not into it so deep, so I can't-- would it be OK to only redirect the users to the www and not Googlebot? MARTIN SPLITT: I think that is OK. But, to be honest, I think it's as much effort  

#### [0:09:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=570) |  to do that than to fix the

service worker making requests on the wrong domain. I think the effort is pretty much the same. It's different people having to do this, I agree. It's very likely that someone else makes the redirect versus the person who writes the service worker. But I would argue you can do it. I think it's fine. I don't see an inherent problem with it to do the redirect only for Googlebot. It might turn out to be tricky to test things later on,  

#### [0:10:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=600) |  and you might run into situations in

the future where it's harder to debug problems with this kind of setup because you're treating Googlebot differently than normal users. So I would recommend to fix the root cause, which is the service-- redirect everyone to www, and then make sure that the service worker does the thing it needs to do properly on the www domain rather than trying to make a request on the other domain. This might be as simple as changing  

#### [0:10:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=630) |  one constant or variable somewhere in your

scripts to actually use the correct domain. But if you can't do that, then, sure, a technical work around is that, but I would consider that not a solution but a workaround. CHRISTIAN KUNZ: OK. OK. Thank you. MARTIN SPLITT: You're welcome. Happy to help. CHRISTIAN KUNZ: And maybe if I may ask my second question? MARTIN SPLITT: Sure. We have time. CHRISTIAN KUNZ: OK, cool. Another client who has a home page and a website,  

#### [0:11:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=660) |  and before loading the main content he

shows content to collect user consent for legal issues, something like that. And only if the user consent is collected the main content is loaded. And this all takes place on the same URL. And the question would be, would it be OK to not show Googlebot this legal user consent page  

#### [0:11:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=690) |  and immediately load the main content? So

you treat Googlebot differently than the other users. Would that be OK from an SEO point of view? MARTIN SPLITT: I think that is fine. Depending a little bit on our heuristics, we might false-qualify this as cloaking, which then might cause issues. But normally-- we would have to test this--  

#### [0:12:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=720) |  it should not be a problem. I

advise a little bit against it. Unless there is literally legal reasons not to load the content in the background and then just make the user consent beforehand, there might actually be legal reasons to not load content before someone has given consent to something. In that case, yeah, that's fine. That's a workaround that I would say is OK.  

#### [0:12:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=750) |  CHRISTIAN KUNZ: OK. And you would consider

this a low risk that something goes wrong? MARTIN SPLITT: I would not consider it low risk. CHRISTIAN KUNZ: OK. So we have to try. We're going to have to test it. MARTIN SPLITT: I would try that very carefully, and be ready to roll that back if need be. CHRISTIAN KUNZ: OK. Thank you very much. MARTIN SPLITT: You're welcome. Suki has a question. Suki-san, excuse me. This may not be related to JavaScript.  

#### [0:13:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=780) |  Well, it kind of is probably related

to [INAUDIBLE].. "How can I identify the largest content when my LCP is slow? And question 2, how can I find what elements cause poor cumulative layout shift?" The LCP, that's a tricky one. I would probably use the webpage test and look at the film strip. What is the largest blob where basically it's mostly white, or whatever the background color of your website is, to suddenly there is content.  

#### [0:13:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=810) |  Whatever loads in that large blob is

probably what's blocking the largest contentful paint time. Very likely going to be images, but it could hypothetically also be text blocks. But it's more likely that these are images that make your LCP time high. For which elements cause poor CLS, you can look at the requests and then block individual requests. You can either use a script, if you are looking for--  

#### [0:14:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=840) |  let me see if I can find

this real quick. Tobias [? Willman ?] wrote a script using Puppeteer for this, which I think is pretty cool. Haven't tried it out, so I don't know how well that actually works. But I think Tobias is usually producing good stuff, so I wouldn't be surprised if this is actually pretty cool. I posted it in the chat, and I'll make sure that I put it in the YouTube description, as well. I might forget that. Let's face it. But I'll try to remember to put it in the YouTube description  

![](https://i.ytimg.com/vi/xgc58EHkX6Q/maxres2.jpg)



#### [0:14:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=870) |  when this video goes up. But basically,

I can probably show this-- maybe I can show this on an example. Do I have a good example, though, where I load different pieces of content? Yeah, I think I do. We'll find out. Let's see. 50 lines of code weblog, and if I go-- I'll share my screen with you in a second.  

#### [0:15:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=900) |  Let's see. A Chrome tab, and I

want to share this Chrome tab. So if I'm not sure what causes things here to go wrong, I can go into the Network tab. I can load things. And then, if I'm wondering-- actually, let me get this away here. And maybe I start with images.  

#### [0:15:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=930) |  This one, for instance. I can say

I want this URL to not actually be loaded. And then I can load again and see if things are shifting or not. And you can see that this image has no longer been loaded. You can basically go through the different elements and then run your metrics to see if you-- no, hold on. This is where I wanted to go. You can run your metrics to see if that makes a difference or not. I think it respects request blocking.  

#### [0:16:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=960) |  I hope. But, anyway, there is a

Puppeteer script that does this for you, which is even nicer, and gives you a better feeling for what's happening. But I'm pretty sure-- wow! Why is Lighthouse warming up so long? Well, to be fair, my computer is acting up a little bit this week, so I'm not super surprised. Not super sure what we are getting.  

#### [0:16:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=990) |  Unfortunately, we don't get to see if

the image was loaded or not. But I'm pretty sure, if I basically now go and block pretty much every image, that we will end up getting a better score. So you can have a look at what requests make the biggest impact on your scores. Oh, Lighthouse 6.0 gives you this info! That's awesome. I didn't know that we have that built in. Dave, thank you very much for following up on this one.  

#### [0:17:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=1020) |  So, yeah. PageSpeed Insights does that. Lighthouse

6.0 will roll out, I think, with the next Chrome release, probably. Or you can install it from GitHub if you want to run that. That's pretty cool. Then it tells you which elements are affected. Anyone else with a question from the audience?  

#### [0:17:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=1050) |  We have a few questions on YouTube

if no one from the audience has a question. All right. I'm not sure I understand this question, but maybe some of you can help me with this. "Why would first contentful paint and largest contentful paint be far apart in Lighthouse and PageSpeed Insights? The Performance tab says they happen at the same time and, as a real user, I see the whole page load  

#### [0:18:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=1080) |  at all these elements at the same

time." Well, it is possible that-- with Lighthouse, it runs on your computer unless you run it from web.dev/measure. PageSpeed Insights runs from the cloud, so it might give you different data, if that's the question. Also, first contentful paint and largest contentful paint do not necessarily have to happen at the same time, especially if you're on a device with slower CPU. And these can divert quite substantially.  

#### [0:18:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=1110) |  They might load at the same time

on your device, as in your computer, but it's unlikely that this might take longer on a slower network connection, or on a slower device with a slower CPU, like an older mobile phone. That happens. "How is largest contentful paint by page type determined?" What does that mean? What page type? I don't fully understand the question because I'm not sure what you mean by page type. "The element seems to shift."  

#### [0:19:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=1140) |  Well, that has nothing to do with

largest contentful paint. That would be CLS. That would be Cumulative Layout Shift. Jennifer, if you want to ask this question with a little more detail in the next Hangout, let me know. Or, basically, just go to YouTube and put it in the next Hangout comments or in any of the next coming up Hangout column threads because I'm not sure what  

#### [0:19:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=1170) |  you mean by page type. Largest contentful

paint-- how it's determined is explained quite nicely on web.dev. But I'm not sure what you mean by page type. Then, "We have a sports betting website that streams sports games and data to end users. We use JavaScript's framework-- Ember.js, in this case-- to render the sportsbook views. The page URL structure is mysite.com/lives ports#football/e ngland/competitionID/matchID.  

#### [0:20:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=1200) |  Our customers want us to get rid

of the hash sign and provide them with slash routes in order for Googlebot to crawl them and index them. However, when the match time comes, and when the match ends, the URL returns a 404. Question-- is there a real reason to remove the hash? Will Google index those temporary JavaScript routes? If yes, then what will happen if, a few days after it,  

#### [0:20:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=1230) |  the page returns a 404 status?" Generally,

if you want these things indexed, you need to remove that hash. But if these URLs are short-lived-- and by short lived, I mean 90 minutes of a match-- then I don't see why you would do that. Unless you do have them up upfront, and they are there for like a week or longer than a couple of days or minutes.  

#### [0:21:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=1260) |  Then, I think if you want people

to find it before the match or while the match is running, then it makes sense to have these URLs present and rendering properly a couple of days beforehand, before the match. It's fine for URLs to go 404 afterwards. What would happen is, if you give us enough time to discover these URLs-- and enough time can be a few days, or even a week or so, because we might not crawl your page quite that often, or your site quite that often.  

#### [0:21:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=1290) |  But if we do discover them and

crawl them, we would index them. We can't do that if there's a hash in there, so people would not find this while the match is running or before the match starts. So if your customer relies or wants people to find this content before the match or while the match is running, then you should definitely get rid of that hash in the URL. And once you are returning a 404-- even using JavaScript you're returning the 404  

#### [0:22:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=1320) |  because the match is over-- that's fine.

We'll eventually see that as a 404 page and then remove it from the index again. So it depends a little bit on what your customer wants and how your customer thinks about these URLs. It's fine to have these temporary URLs indexed. Nothing wrong with that. But if you want them indexed, you can't use a hash route. "Can we somehow only use JavaScript to make  

#### [0:22:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=1350) |  a working comment form?" Yeah. But with

a comment form, I mean, that's a form that you use to enter comments. You can totally use JavaScript to do that. I'm not sure I understand that question. If you have follow-up information, please post a follow-up question in the next Hangouts.  

#### [0:23:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=1380) |  Right. That's it for the YouTube comments,

I think. Let me reload the page because sometimes people are commenting while the Hangouts is happening. No. Any more questions from the audience then? Now is your time. DAVE SMART: I've got a quick one, Martin, if that's all right. MARTIN SPLITT: Sure. DAVE SMART: Came across a couple of questions and stuff in the forums where people are pre-rendering,  

#### [0:23:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=1410) |  but they're kind of serving everything with

the JavaScript after pre-render. So they're kind of enacting [INAUDIBLE].. It's my understanding that's kind of missing some of the points of it. Are you better to remove that JavaScript? And does it particularly cause troubles if you do [INAUDIBLE]?? Will Google try and then render the page anyway? MARTIN SPLITT: That's a good question. If I think about this, if I want to pre-render, 90% of the time,  

#### [0:24:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=1440) |  probably, people don't have to pre-render for

Googlebot. They might want to pre-render for other bots that don't run JavaScript, but unless they have a technical reason that they should fix elsewhere, then using pre-rendering as a workaround is kind of-- it's a work-around. And if you are then not removing the JavaScript from the pre-rendered page, then yeah, you're kind of missing the point. Because then, sure, we do have the content in the initial HTML, but if your JavaScript kind of overwrites  

#### [0:24:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=1470) |  it and overwrites it incorrectly, then we

might end up still seeing the incorrect content, or the missing content, or whatever it is if your JavaScript just overwrites everything and doesn't work properly, and if that's the reason that you pre-render in the first place. I would suggest if you pre-render for Googlebot, because your JavaScript causes the content to be incorrect, or missing, or whatever, do test very, very carefully if your pre-rendered solution actually  

#### [0:25:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=1500) |  fixes the problem when the JavaScript remains

on the page. If it doesn't, I would just fix the JavaScript and get rid of pre-rendering. If it works, don't touch it. If it's not broken, don't fix it. It's fine. You can do it. I kind of feel like if your JavaScript renders fine in the first place, then pre-rendering is just a way to burn money, because servers costs money, and pre-rendering usually takes server load.  

#### [0:25:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=1530) |  So I would say if you pre-render,

the page should come out without JavaScript at the end. But if it works for you otherwise, then fine by me. You do miss out on the benefits, though. DAVE SMART: Thank you, Martin. MARTIN SPLITT: Thank you for the question. Anyone else with questions? I see there's a bit of Twitter chit-chat.  

#### [0:26:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=1560) |  Oh, people are posting random stuff on

Twitter. Sorry. Do we have a question? ALVARO LOZANO: Yes, Martin? MARTIN SPLITT: Awesome, Alvaro! ALVARO LOZANO: How are you? MARTIN SPLITT: Great. ALVARO LOZANO: I have a quick one. It's not probably related with JavaScript. But we're thinking about implementing FAQ Schema Markup in some of our pages. And I'm wondering if that is going  

#### [0:26:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=1590) |  to decrease a little bit the page

speed of the website in adding this LAD JSON data inside the page. And also, if this is also a good practice if you are trying to acquire customers for, let's say, pegging keywords, all the keywords that are bringing direct sales, rather than information on our transactional queries.  

#### [0:27:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=1620) |  I don't know if you got my

point. MARTIN SPLITT: I got your point. ALVARO LOZANO: Oh, that's brilliant. Thanks. MARTIN SPLITT: You're welcome. Great question. FAQ Markup is most helpful for informational queries, not really customer acquisition. Especially because, if you are too blatantly advertising your services or products as an answer to a non-product-related question, it doesn't really help that much. FAQ is more a way to give people information around something  

#### [0:27:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=1650) |  that you offer quicker than having them

to go to your website. Also, adding JSON-LD bots does not really impact page speed that much. It does add a few bytes to the website. But that's insignificant. If you look at the amount of JavaScript that you usually ship, and the amount of images that you usually ship, it's a small, small, small percentage. And it doesn't really make the browser slower by parsing, because it basically parses the script, sees it's not a JavaScript, and kind of skips it.  

#### [0:28:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=1680) |  So I wouldn't worry too much about

page speed implications. I think having FAQ data can help, especially for customer service-related informational queries. But I don't think it has much impact in terms of customer acquisition. But I might be wrong about that last part. ALVARO LOZANO: Perfect. I agree. I agree with you, actually. Thank you. MARTIN SPLITT: You're welcome. Awesome. Do we have other questions from the audience?  

#### [0:28:30](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=1710) |  No further questions? All right. So 5,

4, 3, 2, 1. All right. In that case, thank you so much for watching.  

#### [0:29:00](https://www.youtube.com/watch?v=xgc58EHkX6Q&t=1740) |  Thank you so much for posting questions

on YouTube, joining this Hangout, and asking them live, as well. I hope you have a fantastic day. Stay safe. Take care. Thanks for joining. And see you soon in the next JavaScript SEO Office Hours. Bye-bye. ALVARO LOZANO: Bye-bye.  