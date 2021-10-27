[![JavaScript SEO office hours May 27th, 2020](https://i.ytimg.com/vi/82j3JBbzU-4/maxresdefault.jpg)](https://www.youtube.com/watch?v=82j3JBbzU-4)

## JavaScript SEO office hours May 27th, 2020

This is a recording of the JavaScript SEO office-hours hangout from May 27th, 2020. These sessions are open to anything around SEO for JavaScript sites.



Watch out for new sessions, and add your questions at youtube.com/googlewebmasters/community



#### [0:00:00](https://www.youtube.com/watch?v=82j3JBbzU-4&t=0) |  MARTIN SPLITT: Hello, and welcome to this

week's JavaScript SEO Office Hours. My name is Martin Splitt. I am in the Google Search Relations team, and I am a little bit of an expert on the JavaScript rendering and indexing side of things. So I am here to answer your questions regarding JavaScript SEO problems. And you can ask your questions either in the YouTube post that we do before these meet-ups, or you can join these live recordings by joining the link that will be posted shortly  

#### [0:00:30](https://www.youtube.com/watch?v=82j3JBbzU-4&t=30) |  before the actual hanging out in the

YouTube post comments. Awesome. Thank you very much for everyone who's joining. I see that we are a small, select group today. There's not that many questions in YouTube. So we'll see how much content we have today. Let's start with a YouTube question. Hi, Martin. "From the quick look on the Frontify theme built with React JS, twentytwenty.frontify.org, can you see any SEO issues there or recommend some improvement?"  

#### [0:01:00](https://www.youtube.com/watch?v=82j3JBbzU-4&t=60) |  This is actually-- I think this is

a good opportunity to give you an idea of how I would look into these things. And let me just start a screen share. Because I actually haven't taken a look before. So I'll just do this now. And the question is if I can actually get that Chrome window that I just opened. No.  

#### [0:01:30](https://www.youtube.com/watch?v=82j3JBbzU-4&t=90) |  OK, in that case-- I just clicked

on the wrong thing. I actually have to share an entire window. That's fine. So I would start by looking at the theme itself. So the theme itself was twentytwenty.frontify.org.  

#### [0:02:00](https://www.youtube.com/watch?v=82j3JBbzU-4&t=120) |  No? Was it not? Actually I'm just

going to copy the link, and then we'll see what happens if I made-- OK. Ah, it's a redirect thing. Yes, I want to go to that site. There we go. I must have mistyped something somewhere. Frontity, not Frontify. I don't know why I said Frontify. Aha, OK. So a very quick kind of litmus test would be to just run a Lighthouse audit.  

#### [0:02:30](https://www.youtube.com/watch?v=82j3JBbzU-4&t=150) |  And in this case-- actually, you know

what, I'm just going to run all of these-- maybe the Progressive Web App, we don't care that much-- to just get a rough feeling for how does this website generally work, how well does it work, how fast is it. That looks pretty good. So the thing is, in the SEO audits in Lighthouse, they are very, very basic, and they are vendor-agnostic. So a lot of Google-specific stuff, we can't or don't want to put into Lighthouse.  

#### [0:03:00](https://www.youtube.com/watch?v=82j3JBbzU-4&t=180) |  But even here we see some suggestions.

That's potentially a mobile usability issue, where some of the tap targets are not large enough. Most of the audits pass. So we do have a viewport, we do have a title, we do have a meta description. In this case, that would be service setup. Kind of an issue, not really a theming issue. Links have descriptive text. robots.txt is valid. Alt attributes and images, hreflang, legible fonts,  

#### [0:03:30](https://www.youtube.com/watch?v=82j3JBbzU-4&t=210) |  avoids plugins so it's not using Java

or anything. In the performance, it looks pretty good as well. First contentful paint could be a little faster, but that's OK. First meaningful paint-- yeah, CPU idle, sure. So it could be better, but it's pretty solid. I wouldn't worry about that. So that's like the very first stage of taking a look at this that I would do. And then the next thing that I like to do is I like to ask the mobile-friendly test if there's  

#### [0:04:00](https://www.youtube.com/watch?v=82j3JBbzU-4&t=240) |  any surprises, any problems with actually getting

to the content. Oh, great. Yeah, and I see a car there, and I see a car there, and I don't see cars anymore. Oh, OK. Google doesn't trust my guest browsing window. No more crosswalks. Seriously? I don't think I have more buses.  

![](https://i.ytimg.com/vi/82j3JBbzU-4/maxres1.jpg)



#### [0:04:30](https://www.youtube.com/watch?v=82j3JBbzU-4&t=270) |  Oh, that was a cheap trick. Is

that a bus or is that a truck? No it's a FedEx. It's a truck. I wish I could machine learn these things and not have to fill them out. Are we good at some point, or are you showing me more buses? No, that's the red light. What? Argh, that is frustrating. Sorry, I should have just logged in,  

#### [0:05:00](https://www.youtube.com/watch?v=82j3JBbzU-4&t=300) |  and then I would have avoided all

these funky-- what? OK, I'm sorry. I'm a robot apparently. Maybe it's because I spend too much time with Google Bot. Who knows. What? What are you-- OK, nothing. It's not a bus. Good. [GROANS] I think I will cut that from the video, because that was just stupid. And here we go.  

#### [0:05:30](https://www.youtube.com/watch?v=82j3JBbzU-4&t=330) |  Come on, come on. Yeah, so performance-wise,

looks good. The screenshot looks all right to me in the very first get-go. Mobile-friendly, no loading issues, no surprises. There is something going on with some JSON issue, but we don't care. It doesn't matter for SEO. Yeah, the HTML looks pretty complete.  

#### [0:06:00](https://www.youtube.com/watch?v=82j3JBbzU-4&t=360) |  Can I see if they have a

description? Why is my computer going slow right now? Oof, come on. So we could figure out what this is. Where the data-rh comes from, I'm not sure. But it doesn't really matter. It looks pretty solid from an SEO perspective.  

#### [0:06:30](https://www.youtube.com/watch?v=82j3JBbzU-4&t=390) |  It's fast. Maybe look at the tap

target sizes, where Lighthouse was complaining, because that could also be a mobile usability issue. But besides that, I think this is an OK theme. And that's more or less what I look for. So I look at the rendered HTML. I do a smoke test of the screenshot. And Lighthouse gives you a few pointers as well. So good question, but I don't think there's anything to look at specifically here.  

#### [0:07:00](https://www.youtube.com/watch?v=82j3JBbzU-4&t=420) |  I guess, then, the tricky bit is

probably setting it up correctly with your actual content. But the theme itself seems to be fine. Do we have questions from the audience? Any of you having a question while we're at it? DAVE SMART: I've got a quick one. It's about how many resources and stuff load in the page, if there's any kind of limits that you recommend to make sure something's going to render properly. MARTIN SPLITT: Good point. DAVE SMART: I kind of got some arbitrary figures  

#### [0:07:30](https://www.youtube.com/watch?v=82j3JBbzU-4&t=450) |  when I looked. I try and keep

them under 50, and try and make sure they fire in, like, 0.2 seconds. And that seems to be a relatively sane target. And under that, they tend to get reliably thin. But that's not always the case. And you see pages with way more successfully always render and sometimes pages with less that don't. So I know there's a lot of nuances to that. But I don't know if there's any kind of guidance. MARTIN SPLITT: The general guidance is the fewer the better, I would say, with the asterisk  

#### [0:08:00](https://www.youtube.com/watch?v=82j3JBbzU-4&t=480) |  that you want to split reasonably so

that caching is effective. So basically we don't really have a hard limit or anything. It's just the more resources there are, the more likely you are to experience that something does not load. Or if you're looking from a user's perspective, there is a chance that the network cuts out or some transmission error happens. So the fewer resources, the better. But be reasonable.  

#### [0:08:30](https://www.youtube.com/watch?v=82j3JBbzU-4&t=510) |  It doesn't help to have everything in

one huge file, because then you can't effectively cache, because then if one thing in this large file changes, the entire file needs to be downloaded. So Google Bot generally tries to be smart about these things by caching very aggressively. So even if one render fails, we will see that it fails, but then we have at least cached a bunch of resources already. And then we would retry. And then we would probably get the rest of the resources. If crawl budget is a huge issue--  

#### [0:09:00](https://www.youtube.com/watch?v=82j3JBbzU-4&t=540) |  and that is usually true for websites

with millions of pages-- then that could be a consideration, like trying to keep the number of resources as low as possible. But for websites that are relatively small, that's not an issue. And for us in general, we are trying to fetch everything that we can. And we use aggressive caching to alleviate the number of resources. So that's why you see websites with lots of resources  

![](https://i.ytimg.com/vi/82j3JBbzU-4/maxres2.jpg)



#### [0:09:30](https://www.youtube.com/watch?v=82j3JBbzU-4&t=570) |  doing well, as well as websites with

smaller number of resources. And sometimes things just go wrong. And then it doesn't really matter how many resources you have. If it's that resource that is critical and we are not fetching, then we have to retry. But we are retrying, so that's at least good. But that's a good question. It's a very subjective thing and a very nuanced thing. As you said, you want to make sure that you are taking a look at your specific situation  

#### [0:10:00](https://www.youtube.com/watch?v=82j3JBbzU-4&t=600) |  and judge based on that. There's no

general formula or silver bullet that can be applied to this question. I could say, it depends. DAVE SMART: [CHUCKLES] MARTIN SPLITT: Right. One last YouTube question, and then I'll ask you again for audience questions. Thanks, Dave, for the question. "Hello, Martin, I have a new site where, in each article, comments are enabled by users."  

#### [0:10:30](https://www.youtube.com/watch?v=82j3JBbzU-4&t=630) |  So users can comment on articles. "These

comments are grouped in the HTML code within a JSON-LD called Comment, with different attributes like author text and date. I've seen that Google Bot renders these comments in the HTML view from the Mobile Finder tool. But I don't want to be indexed and searched because there are comments with no SEO value for the page. How can I manage the situation?" Generally speaking, you don't have to. The fact that we render something-- I mean, generally speaking, we index everything  

#### [0:11:00](https://www.youtube.com/watch?v=82j3JBbzU-4&t=660) |  that is on the page, generally. But

if the comments are user-generated, we are relatively good at A, figuring out that this is user-generated content, and B, it doesn't really matter. It doesn't hurt to have these comments there. It doesn't give you any benefit. But I would not-- this is one of these cases where I think you are looking at a non-problem. And when there is a non-problem, then you  

#### [0:11:30](https://www.youtube.com/watch?v=82j3JBbzU-4&t=690) |  don't have to solve anything. That's why

I would advise against trying to come up with a clever way of hiding it. There are definitely ways of hiding things from Google Bot's view, but I just would not. Because there is a chance that you are shooting yourself in the foot by creating something that is less stable, that's robust, or that you accidentally overshoot. So for instance, to give you a very simple example for this, one thing is, if these comments are fetched  

#### [0:12:00](https://www.youtube.com/watch?v=82j3JBbzU-4&t=720) |  by a script on your website-- let's

say you have a comments.js file that actually fetches these comments from the back end and puts them in the content. You could robot away the comments.js. And then we can fetch the comments.js. And so we can execute that JavaScript. And so we can actually fetch the comments. But if you play around with your robots.txt, you might end up accidentally, maybe, blocking more than just  

#### [0:12:30](https://www.youtube.com/watch?v=82j3JBbzU-4&t=750) |  that or, I don't know, block all

the JavaScript, and now your main content doesn't show up anymore. So then, in trying to fix something that wasn't a problem in the first place, you actually make the problem-- or you created an actual problem that wasn't there before. So I would advise against worrying too much about this unless you have very, very good reasons to. Like, I don't know, if the content is very hard to distinguish from the main content or something like that,  

#### [0:13:00](https://www.youtube.com/watch?v=82j3JBbzU-4&t=780) |  then we might not see that it's

user-generated common content. But if it is just comments, as you would normally mark them up, and there is sufficient content on the page, then don't worry about that. It's more risky than useful. We have exhausted our questions from YouTube, I think. I will check the previous JavaScript SEO office hours, because I know that sometimes people post after the actual  

#### [0:13:30](https://www.youtube.com/watch?v=82j3JBbzU-4&t=810) |  hang out into these posts. But do

we have an audience question in the meantime? Ooh, "Search News" was playing. That was loud. Do we have an audience question that we could look at? Not today. Fair enough. Let's have a look. Maybe we have something in the previous one.  

#### [0:14:00](https://www.youtube.com/watch?v=82j3JBbzU-4&t=840) |  I think I answered that one previously,

but I can answer it again. "My crawl rate is very low. I lost traffic. Is it because of that?" No, crawl rate has no quality indicator or signal of something positive. It's possible that your server was responding with a 500 for some request, or it's possible that we just have a version of the content  

![](https://i.ytimg.com/vi/82j3JBbzU-4/maxres3.jpg)



#### [0:14:30](https://www.youtube.com/watch?v=82j3JBbzU-4&t=870) |  and know that the change frequency is

low. In which case, why would we crawl again? It doesn't hurt. It's not a problem, per se. If you're running a single-page application, and it uses client-side rendering, and the HTML preview shows a blank page. You want to figure out-- so I'm assuming  

#### [0:15:00](https://www.youtube.com/watch?v=82j3JBbzU-4&t=900) |  that you mean the rendered HTML in

any of the testing tools that we provide, like the URL inspection tool, the mobile-friendly test, or the rich results test. If you see blank HTML or an empty page HTML that doesn't have the actual content in it, check if you are roboting any of your resources, like any of the JavaScript that fetches this stuff. If anything wasn't loaded properly, that's something that you want to look into. And last but not least, just double-check what could be the reason for this. I mean, I can't answer that question,  

#### [0:15:30](https://www.youtube.com/watch?v=82j3JBbzU-4&t=930) |  because it's like saying, my car doesn't

start. What's happening? And it can be anything. It can be the battery's dead. It can be that you have no fuel. It can be that it's still locked somehow, or whatever. It can be so many different things. And that's the same here. You want to be a little bit careful with that. But basically just try to make changes in the application, and simplify things in the application until you get a positive render that includes the HTML and rendered HTML.  

#### [0:16:00](https://www.youtube.com/watch?v=82j3JBbzU-4&t=960) |  And then try to figure out what

breaks it. I use a technique that's called bisecting. So I have a version here that doesn't work, and then I know I had a version here that did work. Let's say there's six months in between. I jumped three months back. Does it work or not? If it works at this point, then that means that my search radius is now only the last three months. Then I go 1 and 1/2 months back. Basically I jump-- so I'm three months back,  

#### [0:16:30](https://www.youtube.com/watch?v=82j3JBbzU-4&t=990) |  I jump 1 and 1/2 months to

the front. Still works here. So it must be in the middle here. Then I basically just iteratively jump closer to a version that will break. And eventually you find the versions, like, works here, doesn't work here. And then what the changes are that were made between the working version and the broken version. And that way you can figure out what could potentially be the problem. And this is why I am so happy that we have the newer tools. Because previously you had a screenshot  

#### [0:17:00](https://www.youtube.com/watch?v=82j3JBbzU-4&t=1020) |  in the old-fashioned render, and that didn't

really tell you anything. It's just like, yeah, it's broken, and I see it's blank, but that's pretty much it. And then trying to figure out what specifically broke that last bit that pushed it over the edge was not that easy. It's a lot easier now. You can use tools like localtunnel or ngrok to put your local development version into a publicly-reachable URL temporarily so that you can try this out with the testing tools. But yeah, that's what I would do.  

#### [0:17:30](https://www.youtube.com/watch?v=82j3JBbzU-4&t=1050) |  All right. If we don't have any

further questions from the audience, then I would say this was a short office hour, more like an office half an hour. Any questions from the audience? DAVE SMART: Sorry, just a very quick one if that's OK. MARTIN SPLITT: Sure. DAVE SMART: When you call something like an API, if you have no index with a robots header on that API, that's not really an issue, is it, for rendering?  

#### [0:18:00](https://www.youtube.com/watch?v=82j3JBbzU-4&t=1080) |  MARTIN SPLITT: I don't think that's an

issue. I haven't tested this. That's a very interesting question. I should definitely have a look at that. But normally we would fetch the API call because it's not a robot head. It's just no index. And then we would get the data back and use that in rendering. But I don't think that no index on an API makes any difference, really. DAVE SMART: OK. MARTIN SPLITT: That's what I would expect. I would test that, because I'm not 100% sure about this. But from logic, that should be how it behaves.  

#### [0:18:30](https://www.youtube.com/watch?v=82j3JBbzU-4&t=1110) |  Good question. I like questions where I

don't know the answer and I actually have to test. It's good. Awesome. In which case, thank you very, very much for joining. I'll post, into the youtube.com/goog lewebmaster/community, the thread for questions for the next office hours, which will be on Wednesday the-- oh, what day is that? 3rd of June or something, I think it is.  

#### [0:19:00](https://www.youtube.com/watch?v=82j3JBbzU-4&t=1140) |  I think it's already June, but I'm

not sure. Where's my calendar? Next Wednesday is the 3rd of June. Hey, I'm actually not bad. So on the 3rd of June, we'll have another JavaScript SEO office hours. I'll leave a thread on the Community tab of our YouTube channel. Where you can ask your questions. And then I'll also post the link to Hangout there if you want to join the recording. Thank you so much for joining my little audience here  

#### [0:19:30](https://www.youtube.com/watch?v=82j3JBbzU-4&t=1170) |  in the Hangouts call. It was a

pleasure. Stay safe, stay healthy, have a great time. Bye bye. MARIA AMELIE: Bye bye. Thank you. MARTIN SPLITT: Thanks for joining.  