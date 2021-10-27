[![JavaScript SEO office hours, April 8th 2020](https://i.ytimg.com/vi/UH35k9y6RAY/maxresdefault.jpg)](https://www.youtube.com/watch?v=UH35k9y6RAY)

## JavaScript SEO office hours, April 8th 2020

In the JavaScript SEO office hours, you can submit questions about JavaScript and Google Search or ask them live on air.



#### [0:00:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=0) |  MARTIN SPLITT: Hi there, and welcome to

another JavaScript SEO office hours recording, or public office hours Hangout. With me are 10 people in this Hangout tonight, and you have submitted various questions on YouTube. So let's see if we find the time to go through all of these questions. Before I jump into the YouTube questions, anyone here in the Hangout having any questions so far?  

#### [0:00:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=30) |  Three-- DAVE SMART: I have one. MARTIN

SPLITT: Yes. There you go. DAVE SMART: I have a question. WebSockets-- obviously, Googlebot currently doesn't support WebSockets and kind of things. But do you think that will ever change? Because sometimes you see things like-- I mean, I can understand why normally for those things like Firebase that has its live connection. And there's certain other things that sometimes use WebSocket--  

#### [0:01:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=60) |  Blazer, as well, which a new thing,

which kind of compiles it. So do you think that will ever change, or you think it's always going to stay as it is? MARTIN SPLITT: So while I cannot make any comments on the future, really, because I don't know what's going to happen, the fundamental goal for Googlebot and Google Search is to make the world's information generally accessible, including the web, obviously. And so if we see a major trend going to WebSockets  

#### [0:01:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=90) |  for essential communications, we will eventually probably

have it, as well. At this point, it is a very niche technology, in the sense of that most of the crucial content that people consume does not come over WebSockets, or it has a fallback mechanism. And as you said, we are not supporting it at this point in time. But I can't make predictions for the future. There's nothing-- it's not that I am like, oh, yeah, we are about to release this. No, there's no plans to be communicated  

#### [0:02:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=120) |  at this point for WebSockets. But very

good question. DAVE SMART: OK. Thank you. MARTIN SPLITT: Cool. I will be typing these questions down, as well, so that I have a running a log of questions that I can identify more frequent questions, which usually is a hint for us that we need to be addressing these additionally in the documentation. So if you see me typing, that's not because I'm, like, chatting with my co-workers, with John or something.  

#### [0:02:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=150) |  But it's that I am trying to

keep track of what gets asked. Thank you very much. Any other questions from the audience? If not, then I'll start with some questions from YouTube. I've seen that multiple people on YouTube submitted questions around lazy loading, which is really interesting for me, because it tells me  

#### [0:03:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=180) |  that I might want to look into

our lazy loading guidelines again, as it's apparently not clear yet. So to start with one, "Lighthouse recommends lazy loading off-screen images. I usually do this with JavaScript, and I use either a place holder or a very low quality version of the image as the initial source. Is this low-quality version or placeholder likely to be indexed over the lazy loaded images with JavaScript?" That depends on your implementation.  

#### [0:03:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=210) |  If you use the testing tools, you

see what we are seeing. If we are seeing the higher quality versions or the non-placeholder images that you load using JavaScript, that will be fine. If in the testing tools you see that the rendered HTML contains the low-quality version or the placeholder image, that means that there's something in your lazy load implementation that isn't quite right, and we would not see the higher quality version or the actual image lazy loaded by JavaScript in that case. So use the testing tools to determine if your setup works for us.  

#### [0:04:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=240) |  The other thing is, you can also

use the native lazy loading attributes for images so that you have something that degrades nicely-- or actually progressively enhances, really. So a browser would only see the regular image. And you would specify just the image source that you want, the high resolution image source that you want. And then Googlebot would also see that. And you would lazy load on top of it when the browser supports it. So that's not an issue there. And it's built into the browser, so you don't have to worry about implementation problems  

#### [0:04:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=270) |  with your JavaScript implementation. Question, "How can

I ensure that a one-time notification on each page is not indexed in Google. Is an onload event a solution? Because of this one-time notification, we are now found on searches including the term corona." Well, the unknown-- there's two different questions, really, in this one. Do we not see things that run on-- or in the onload event handler?  

#### [0:05:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=300) |  No. We're going to see those. So

that is not a very solid way of making sure that we are not seeing your notification. We might sometimes not see things when they only trigger on the onload event, but that's very unlikely. And that is probably because weird or shoddy JavaScript. I would very simply check if the navigator user  

#### [0:05:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=330) |  agent is Googlebot, and then if it

is, don't show the notification is one way of doing it. An alternative way is to hide it behind a user interaction, so only users that scroll or click or do something on the page somehow see the notification. I think for corona warning notifications, you just want to have whatever-- it's basically the same situation as with a cookie banner. So you could definitely use something like a button to actually only show the notification when  

#### [0:06:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=360) |  it has to-- when the user has

interacted with a page or when the user clicked on the page or something like that. If you don't want to wait for an interaction, I would go for the loading it only when Googlebot is not there-- or basically sniffing out if it's Googlebot or not. It's not a great practice, but it is not cloaking, either, because what you're doing is not swapping out content to mislead the user. You're just loading additional content. It's basically the same situation as if you would do server side or dynamic rendering,  

#### [0:06:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=390) |  where the content might be slightly different,

but it is still the same content that the user would expect coming to your page, unless the notice for corona would completely remove the entire content and only load that. That would not be a great idea. But use that wisely and carefully and you won't be within cloaking limits, so you should be fine. Questions from you all, or should I continue with the YouTube questions?  

#### [0:07:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=420) |  KAIXI LUO: Yeah, on the topic of

cloaking, can you go a bit more in detail what is the-- what is considered as cloaking and what's not? Where is the gray line or-- I don't know. MARTIN SPLITT: So that is a really interesting question. Where is the gray line? So the where is the gray line, I can't do much in terms of giving you too much detail for that. But fundamentally, cloaking means misleading the user.  

#### [0:07:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=450) |  That means if I see Googlebot is

requesting a website and I say, this website is about kittens and butterflies. And then when it's a user going to that website instead of Googlebot, having, I don't know, like an online drugstore, or trying to sell knockoff products or something like that, that would be very much against the intention of the user. And that would not match what we would show in Search results if the user searches for "cute kitten" or something  

#### [0:08:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=480) |  like that, right? So that's very, very

clearly cloaking. What isn't cloaking is if my website content is slightly different, because we all know that with responsive web design, we might have slightly different content to begin with. On a mobile phone, I might only load one product instead of 10 products or something like that, and then have the user click through multiple pages or something like that. That's not cloaking. That's just slightly different content, depending on what the browser can do,  

#### [0:08:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=510) |  or what the device capabilities are. That

is fine. If you show slightly different content for Googlebot than for real users, like a notification or a popup that doesn't show when Googlebot comes in, that is mostly fine, unless it is like a popup that has 90% of the content in it, and on the actual page is only an image, then we are again where it's like, hmm, does that still fall within the grounds of the user  

#### [0:09:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=540) |  sees what the user expects, or what

we saw as Googlebot? But generally speaking, as long as you're not misleading the user, you're definitely on the safe side. What you shouldn't be doing is you shouldn't be misleading your user. Anything that is within reasonable bounds of that is not a problem. KAIXI LUO: OK, because I can think of two examples, like for example, loading these dynamic prompts, like server-side rendering some part of the page,  

#### [0:09:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=570) |  but then actually enhance the behavior with

JavaScript, like-- but the content actually is same, OK. Or a more extreme case, the second case, is actually loading the translated version via JavaScript. MARTIN SPLITT: That is a little tricky one. So the first case is definitely not cloaking. The first one is just slightly different content,  

#### [0:10:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=600) |  but it has the same topic, it

has the same intention when I go there, let's say. When you load completely different content in the sense of a completely different language version, that is trickier. We do have mechanisms for that kind of stuff-- so for instance, you can use an alternative URL to something that is linked via hreflang. That would be safer, whereas when we are like, OK, so this website is about--  

#### [0:10:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=630) |  I don't know-- cats, and very clearly

is about cats, but then when I go there from my browser and it says katzen, that might not always be easy for us to distinguish that this is just the same content, just translated. So I would be very careful doing that kind of stuff. But you see there are certain gray areas. And it might be that this works, actually. I don't know. But that sounds to me like there is potential for this going wrong. So I would probably tread carefully.  

#### [0:11:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=660) |  But just loading slightly different versions of

the content because of server-side rendering versus client-side rendering, that's not something that you would need to worry about, definitely. KAIXI LUO: OK. Thank you very much. MARTIN SPLITT: You're very much welcome. Other questions from the Hangout? Or I go back to YouTube. OK. A question from-- a submitted question from YouTube.  

#### [0:11:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=690) |  "I have a site where it's Angular-based.

And all of the content, including meta tags, title, canonical, and the site content itself is rendered on the client side. Will this affect our ranking?" No. Unless it's broken and we're not seeing your content, it will not affect your ranking. If your website is very, very slow, that might affect your ranking, because speed is a ranking factor. But it's only one out of hundreds. So you shouldn't worry too much about this.  

#### [0:12:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=720) |  But definitely test, test, test, test, if

you do that. "I also notice that GSE-- well, Search Console-- is warning us on mobile issues for tag archive pages due to its rendering on first load as the CSS gets injected in later. Any recommendations?" Try to load the critical CSS as quickly as possible. That's also a recommendation in Lighthouse, by the way. And then only load CSS in later that is non-essential for the initial render.  

#### [0:12:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=750) |  That should make these warnings go away,

because that might actually cause trouble when we try to figure out if a page is mobile friendly or not. So I would recommend to get as much CSS-- as much critical CSS inlined into the page as possible, but not too much, for the obvious reasons that the new HTML is too large, and so on and so forth. Lighthouse has pretty good guidance on that. So check out Lighthouse for your CSS troubles.  

#### [0:13:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=780) |  Questions from you all? Because maybe these

inspired you? OK, I'll take one more from YouTube, and then we'll see if questions come up here. "Hi, Martin. What is your recommendation for the most optimal way of troubleshooting if a--" sorry, there's someone trying to get into the--  

![](https://i.ytimg.com/vi/UH35k9y6RAY/maxres1.jpg)



#### [0:13:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=810) |  oh, the pop-up has disappeared. OK. "Hi,

Martin. What is your recommendation for the most optimal way of troubleshooting if a JavaScript-based website is having issues with slow indexing where content is not indexed immediately due to longer processing times?" Not 100% sure what this means. If this is aiming at the two ways of indexing, don't worry about them. We have discussed that last time. If you do see that users are taking a very long time until-- or for users, your website  

#### [0:14:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=840) |  is very slow, that's something that you

want to improve on. I highly recommend using the web page test or Lighthouse to get a feeling for how fast your website is on people's devices. But generally speaking, slow indexing because of long processing times is not really that much of a concern these days. Anyone having a question to jump in with? DOMENIC FRANKE: Yeah. Can you hear me?  

#### [0:14:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=870) |  MARTIN SPLITT: Yes. DOMENIC FRANKE: Now it's

working. I've had a little bit of trouble with my Mac. So I have a question about structure data. MARTIN SPLITT: Mm-hmm DOMENIC FRANKE: We have a dynamic render page and add to this structure data. And we don't know if Google can get this normally with the render in original format, or it's a little bit difficult for Google to see the structure data, then we did now have the structure  

#### [0:15:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=900) |  data or not. We don't see anything

in the Google search results. MARTIN SPLITT: Right. That's a very good question. When you say dynamic rendering, do you mean as in you are using something like Rendertron or Prerender.io, or do you mean server-side rendering? DOMENIC FRANKE: So we don't do pre-renderings. We only at the moment--  

#### [0:15:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=930) |  MARTIN SPLITT: Client side. DOMENIC FRANKE: Yeah.

Client side. So-- MARTIN SPLITT: Client-side rendering. OK. DOMENIC FRANKE: But the Googlebot, I think the Googlebot do pre-rendering with Puppeteer also you talk about in your stream? Pretty much what I mean. Yeah. MARTIN SPLITT: Yes, yes. We're not actually using Rendertron, but we do render pages. So that we definitely do. I can show you some things. So to give you an example for now-- no, no, no, no. None of these.  

#### [0:16:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=960) |  To give you an example of what

you can do is I have created a few test pages to show this. Here we have a website that-- wait, hold on-- I'll try to make this larger so that it's easier to read, actually. Give me a second. I think-- yeah, this should be better. We don't need that at this point. So this website does not have any structured data in it, as you can see. There's no structured data here. But it does use Google Tag Manager.  

#### [0:16:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=990) |  And if you check out this one,

then you'd see that it does have some structured data. Using Google Tag Manager, it's injected dynamically. And when I want to know if Google actually sees this, I can just go to goo.gle richresults. So the Rich Results test-- I don't need that anymore. And then if I run this, I will see-- I know. Thank you very much.  

#### [0:17:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1020) |  I will see if it gets picked

up or not. And it gets picked up. In this case, it has successfully picked up that there's some organization markup and that there is a logo in there. And you can use the rendered HTML to see if your structured data shows up. If it is in the rendered HTML, that means that we are also seeing it. So generally speaking, it should not be a problem. If you need some support for that statement, then you can check out our developer documentation,  

#### [0:17:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1050) |  because under Guides, Enable Rich Results, there

is Generate Structure Data with JavaScript that has a lot more details than what I just described. But basically, we have documentation for this. Now, the question as in, why am I not seeing this in Google search results, that's because structured data is a necessity or a requirement to actually be eligible for rich results, but does not mean that we will always display rich results.  

#### [0:18:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1080) |  So even if your structured data implementation

is correct, we might choose not to show rich results because for, I don't know, various reasons. There might be a faster website. There might be a website that has higher ranking information. There's lots of factors to consider. It's basically a ranking question, and I can't really comment on ranking questions. But you make yourself eligible by having validating structured data. And you can use the Rich Results test to see if we are picking it up.  

#### [0:18:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1110) |  DOMENIC FRANKE: So to understand this. So

if I add this [INAUDIBLE] rich result, it's not guaranteed that Google will show this. So-- MARTIN SPLITT: Correct. DOMENIC FRANKE: But if Google is shown nothing structured data from anything else with the search result, this is-- OK, this can be the problem from size ranking or something else. MARTIN SPLITT: It can be all sorts of things  

#### [0:19:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1140) |  that make it not show up, mostly

ranking-related things, as long as we are picking it up. And also, Search Console should show you if we have picked up the structured data, if it is in Search Console, and/or you can see it in Rich Results tests, then you have successfully implemented it on the technology side of things. DOMENIC FRANKE: OK. MARTIN SPLITT: It doesn't guarantee that it shows up in Search results. DOMENIC FRANKE: Perfect. Thank you. MARTIN SPLITT: You're welcome.  

#### [0:19:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1170) |  I have a question in the chat.

"I have a question from my developer partner who doesn't want to ask himself directly." Well, that's fair. "We sometimes see websites which check the user agent in order to set specific behaviors for the Googlebot. Can it trigger something? Can it be seen as potential cloaking? And if so, how does Google work? It's very common here in our bilingual nation." Interesting question. We kind of scratched on that earlier on. If you are changing content so that we are under the impression that you are misleading the user,  

#### [0:20:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1200) |  that would be considered cloaking. Just user

agent sniffing and then loading slightly different content or, for instance, the example I gave is, what is fine to do would be to say, oh, this is Googlebot, so I'm not showing a corona information banner. That's fine. Whatever. This is not primary content to your website anyways. So you can just hide it out. If you're using it to swap out or redirect from a page that is about kittens to a page that is about cheap drugs online,  

#### [0:20:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1230) |  that is cloaking. So generally, when we

can't-- when we have the feeling or when we get content that is wildly different, that is considered cloaking. Where is the border between legitimate content changes and illegitimate content changes, a.k.a. cloaking? That is a tricky question and you will want to stay away from the murky waters  

#### [0:21:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1260) |  in the middle of that spectrum. So

as I said, server-side rendering something or hiding a notification from Googlebot, that's definitely not on the dangerous side of the spectrum. Completely going somewhere else and actually showing completely different content, that's a risky one. We had the example of translations. What if I also translate the content under the same URL? That is in the murky waters where I say, it might work. It might not work. I would probably steer clear of that and not risk it.  

#### [0:21:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1290) |  It's a tricky one. But generally speaking,

small content adjustments do not run under cloaking. "That's where the bilingual comes in. And we have some really funky decisions made by companies on which language they want to show you." If a contest is not available in some provinces or some regions in one language version-- so let's say I have a website in, I don't know, Canada, where you have French or whatever they  

#### [0:22:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1320) |  consider French, and English. And you have

some content that is only available in English. What I would do, if it's only available in English and I'm on the French side, is I would either say, I have a page that says, oh, this content isn't available in this language, or in this province, or whatever. How about you go there, and have a link to the other thing. Or just do a 404. But don't try to be clever, and don't try to force different content on users  

#### [0:22:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1350) |  where they don't expect it. It's not

a great user experience. And I'm not sure if Googlebot will handle this gracefully. So you definitely want to be very carefully testing this or avoid this to begin with. I think that's my guidance on that. Do we have questions in the audience? Or should I go back to the submitted questions? DOMENIC FRANKE: I have an extended question to the--  

#### [0:23:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1380) |  MARTIN SPLITT: Sure. DOMENIC FRANKE: --to the

question before. So I've tried this with my patch. And we add the 3D structure data. And I see I get no test result with this 3D structure data but with another structure data. If the testing tool cannot actually at this moment testing the 3D structure data, like the one from Wikipedia with [INAUDIBLE] or-- MARTIN SPLITT: I think that is a definite possibility,  

#### [0:23:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1410) |  because I think the test currently is

limited. I'm not sure where the-- we have some things saying that there is a limitation to this. But I'm not sure-- ah, here. Supported types. So currently we support a bunch of types, but we don't-- actually, I can put it in the chat if you want to check the chat. That's the piece of documentation that explains which types are supported. What you can do, though, is in the structure data testing  

#### [0:24:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1440) |  tool-- and actually, I'm going to run

this real quick through screen sharing one more time. I will be sharing this entire screen. If you are running this and you don't see your structured data, what you can try is you can-- oh, come on. Here we go. Use the rendered HTML, and you can, A, look for the-- wow, thanks. You can, A, look for the structured data  

#### [0:24:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1470) |  to be present here. But you can

also use it to actually take it from here and go into the Structured Data Testing Tool-- Structured Data Testing Tool. And that one should hypothetically support this better, because it has a few more things in support. It should show up here, but even that is not a guarantee that it's correct. You would have to manually make sure that everything that we say is required is actually present there.  

#### [0:25:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1500) |  3D data is a tricky one, because

it's relatively new. And I'm not even sure if it is, like, public public there, or if you are in an early access program. Let's see. That's relatively easy to find out. We can go in-- wait, where is the structured data gallery? It doesn't look like it is generally  

#### [0:25:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1530) |  available at this point, the 3D data.

At least, it's not showing up in here. So you might be in an early access or early adopters program. Yes. 3D and AR results are currently limited to people in the early access program. You can use a form to express interest if you're not having done that already. DOMENIC FRANKE: Thank you. Thank you. OK, good. I need to go to my boss and we need to add to the early access  

#### [0:26:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1560) |  program, then. Most of the page with

3D data files. MARTIN SPLITT: In that case, yes. DOMENIC FRANKE: Thank you. Thank you very much. MARTIN SPLITT: You're welcome. You're welcome. OK, other questions? Oh, a question on YouTube has been answered. Oh, one of the lazy loaded questions. That's cool. In that case, I may have a look at YouTube one more time.  

#### [0:26:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1590) |  "Hi. Does Googlebot have some issues crawling

isomorphic pages? And does it understand client-side routing? Or is it still safer to do the routing on the server side and avoid page rehydrations on the same URL?" No. Googlebot does not have fundamental issues with isomorphic pages. Isomorphic pages, for those of you who are wondering, are basically just server side rendering plus hydration, where you run more or less the same JavaScript on the server side as you do on the client side.  

#### [0:27:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1620) |  We support that. Client side routing is

fine, as well. And rehydrations are OK, too. Just make sure that it's implemented properly and that you test it with our testing tools to see if the content that you expect is actually visible to us in the rendered HTML. You can use the Google Search Console URL inspection tool. You can use the rich results test. You can use the mobile-friendly test. Any of these work. And with the rich results test and the mobile-friendly test,  

![](https://i.ytimg.com/vi/UH35k9y6RAY/maxres2.jpg)



#### [0:27:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1650) |  you can do it on local development

URLs, as well. If you use a tunneling tool like Localtunnel or ngrok or something like that, you can basically plug any URL in and see the rendered HTML that we see. So that's quite nice. "This article compiled the quotes from John Miller, [? Gary, ?] and Martin over time. Some of those quotes seem to contradict each other." There's a guide from--  

#### [0:28:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1680) |  or an article from OnCrawl on lazy

loading. And it "seems to contradict each other." The guide is from 2019, from April 2019. It's like a year old now. And the contradiction comes from the fact that they have-- I actually read the article earlier, because I saw this question earlier. If you look at Google search over time, you will see that it keeps changing and keeps improving  

#### [0:28:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1710) |  and keeps-- our mission is to basically

make sure that we understand the web that you create. So we keep improving things. That also means that quotes from a month ago, from a year ago, from five years ago might no longer be true. Things evolve. In this article, there are few things that look like they contradict each other and not necessarily contradict each other. And actually, this is elaborated in the question, as well. "I know lazy loaded images are, in principle, indexable  

#### [0:29:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1740) |  if done properly. But is it worth

the risk to lazy load important images like product images, even if they are below the fold?" Yes, it is worth it, because if you-- especially if you use the native lazy loading, there is no risk whatsoever, because it is an image element that has the actual product image as the source. It's just loading lazily when the browser supports it. So even crawlers that don't run JavaScript will get the high quality image.  

#### [0:29:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1770) |  But users on browsers that are more

modern will have that support and actually get a slightly better experience, or actually, much better experience, depending on your network speed and the price of your network, especially on mobile. Lazy loading is quite an improvement. And I would definitely recommend it. I would be careful with custom implementations these days, because why? If some browsers have it and other browsers fall back to less great but still solid behavior, I think that's worthwhile taking or using this opportunity.  

#### [0:30:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1800) |  "Also, do NoScript actually-- also, is NoScript

actually helpful for image indexing for lazy loaded images, or is it like John Miller said, Google ignores it?" The quote there is slightly out of context, I think. I actually haven't-- I don't remember. I think that the quote is slightly out of context there, because we do ignore content in NoScript,  

#### [0:30:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1830) |  except for images, interestingly enough. For images

specifically, we have the workaround that allows you to use images in NoScript and we will index it. But we are not sure how long that's going to stay that way and if we really need this. If engineering finds out they don't need to do this, they don't need to support this, they might remove it. We have seen with the pagination situation last year that that can lead to confusion.  

#### [0:31:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1860) |  It does happen every now and then.

There's many, many engineers working on this. And sometimes they decide that, well, we get the signals elsewhere, so it's no big deal. Then they run an experiment, find out, yeah, it really is no big deal. But then we have to communicate the changes. So I would shy away from NoScript, because there's better alternatives. The alternatives are using [INAUDIBLE] lazy loading, which is a fantastic progressive enhancing way, or using a as robust as possible JavaScript implementation to do lazy loading.  

#### [0:31:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1890) |  So I would not use the NoScript

fallback. At this time of recording-- today, April 8, 2020-- as far as I'm aware, we are still supporting the NoScript work around for images. But that's specifically for images. It does not work for the other things. Cool. Questions in the meantime? DAVE SMART: I've got another quick one, if that's OK. MARTIN SPLITT: Sure.  

#### [0:32:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1920) |  DAVE SMART: When you use the testing

tools or [INAUDIBLE] and render a page, and you've rendered HTML, it flattens iframes out in there. Are they considered just part of the content for ranking purposes, or do we not know? Is that secret sauce? MARTIN SPLITT: It's not secret sauce. And it is observable in the testing tools, too. In certain cases, we will flatten iframe content into the document. That is when the iframe is large enough  

#### [0:32:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1950) |  and when the content is-- I'm not

sure what the other signal is that we are using to consider it as inlineable. But if it's inlined into HTML, it is at least sent to indexing. What I don't know at this point, because that is also a question about indexing and somewhat related to ranking, is how ranking slash indexing actually considers this content. It is marked as flattened or injected or inlined--  

#### [0:33:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=1980) |  I think inlined is the term we're

using. It is marked as inline content. I'm not sure how it's used in ranking. I'm not sure how exactly it is used in indexing. So I would assume it gets inlined in certain conditions. And if you see it inlined in the testing tools, that means that we're at least seeing the content as part of this document. DAVE SMART: OK. Cool. MARTIN SPLITT: So very good question. Other questions?  

#### [0:33:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2010) |  No? All right, then I'll take another

one from YouTube. "There is a website that is dynamically excluding part of the content on its mobile version using JavaScript instead of CSS as a responsive solution, a Read More button. The content is being sent by the server, but excluded in the client side.  

#### [0:34:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2040) |  Mobile friendly tests and GSE seem to

not recognize that piece of content. Is that correct to affirm that the hidden content may not be read by Google?" In your case I am not 100% sure what the details of this implementation are. But if you say "Read More button," then I am assuming that you mean an actual button that we would have to click on to load the additional content. If that is the case and the content is not there in the rendered HTML, no. We are not going to see it. And we're not going to see it because there  

#### [0:34:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2070) |  is a user interaction required. We are

not interacting with your page. We're not clicking on anything. But generally speaking, if you don't see the content in the rendered HTML and the testing tools, it means that we are not seeing it when sending it to indexing. So yes, you want to be very careful with that implementation, unless you want to exclude that content, then mission accomplished. Do we have-- FILIPE SCHAAB: Actually--  

#### [0:35:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2100) |  MARTIN SPLITT: Yes? FILIPE SCHAAB: Actually, this

implementation, the content is being passed by the server, and it's being suppressed in the client side-- MARTIN SPLITT: In the client side. So what does that mean, it's being suppressed? FILIPE SCHAAB: Like dot remove with JavaScript. MARTIN SPLITT: Aha. OK, yeah, then we're not seeing it. If you remove it from the DOM, we're not seeing the content. FILIPE SCHAAB: OK, awesome. That's my main question, because we are discussing if we just  

#### [0:35:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2130) |  pass it by the server was enough

to render and to interpret it. So it's not, right? MARTIN SPLITT: No. If we are removing-- if you're removing it and we are rendering it, we are seeing the removed-- we're not seeing the removed content, because we are sending what is rendered to indexing. So the tools show you we have successfully removed the content you wanted to remove and we are not seeing it in indexing.  

#### [0:36:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2160) |  FILIPE SCHAAB: Awesome. Thank you. MARTIN SPLITT:

You're welcome. OK. Other questions? KAIXI LUO: OK, building up on this topic, what about the content that's on mobile, for example, or that is hidden, invisible, that-- for example, our sidebar that would appear on desktop,  

#### [0:36:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2190) |  but on mobile, it requires a user

interaction, like a tap on a Show Sidebar to see the sidebar. But the sidebar content is actually-- is actually in the HTML, we can say that. So would Googlebot even consider that content? Because it's not actually visible until a user clicks on Show Sidebar.  

#### [0:37:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2220) |  But it's there. I mean, on desktop

it's there, as well. It's in the HTML. But on mobile, it's not visible by default. MARTIN SPLITT: So let me be very careful here. Anything that is in the DOM is considered for indexing. So whatever we render, that goes into indexing. That means something that is invisible but present in the DOM, in the HTML, we will see that.  

#### [0:37:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2250) |  Whatever is in the rendered HTML that

the testing tools give you, we will use that for indexing. Now, if it is invisible, we might consider certain cases, like for instance, if it is invisible and matches topically, then we would consider it maybe not as important as the visible content, but we would still consider it. So we might not show it in bold in the snippet or something like that. But we will still consider it. If it is unrelated or if it feels  

#### [0:38:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2280) |  it is a spamming technique to basically

just add additional content that the user doesn't really see and doesn't really need, or isn't really beneficial to the user at this point, then we might exclude it from the actual weighting. But fundamentally, if it is related, useful content, even if it is not visibly visible, as long as it is in the DOM, we will see that. So the rendered HTML is what goes into indexing. And then indexing makes decisions based on things like,  

#### [0:38:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2310) |  is it visible or not? But that

doesn't mean that we are not seeing it or not using this for indexing. KAIXI LUO: OK. Thank you. MARTIN SPLITT: You're welcome. KAIXI LUO: I've had this question for so long. MARTIN SPLITT: No worries. And it is a tricky question, because a lot of people understand different things when they say "not visible." It's like, it's "not visible." And then it turns out they mean not in the rendered HTML. And it's like, well, if it's not in the rendered HTML, no, we are not seeing the content, whereas like--  

#### [0:39:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2340) |  yeah. And then you can do stupid

things when you try to hide stuff. It's pointless. That's a tricky one. If you require a user interaction to add it to the rendered HTML-- so like, if you have to click an actual button to load the thing-- we would also not see it. And it's not really present then. So there's gray zones of that. But very fundamentally, we are seeing invisible content  

#### [0:39:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2370) |  if it's part of the rendered HTML.

KAIXI LUO: Thanks. Now it's clear. It's finally clear. MARTIN SPLITT: Awesome. To answer Maria's question, "What's the one question you're itching to answer today?" I already answered that one. That was the lazy loading guide question was like, oh, there are so many comments and quotes from you all. And they are contradicting each other. And I'm like, well, the article is a year old, and also the comments were collected over a longer period of time.  

#### [0:40:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2400) |  That's something fundamental with SEO. The web

is moving forward really quickly, which is amazing, because that means that we get to improve and build new, cool stuff on the web. And Google Search is trying to keep up with the web as it evolves. So things change. Things change constantly. And the only constant thing is change. But that also means you want to be very careful when you read outdated articles or when someone says, like, when I tested this five years ago-- usually whenever I hear someone talking about something,  

#### [0:40:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2430) |  I'm like, that's outrageously wrong. And I

ask, so where does this come from? Then usually they say, oh, like three years ago. I'm like, yeah, three years ago we didn't have headless Chromium in Googlebot. We didn't have evergreen Googlebot. So since 2018, this has dramatically changed. So the best recommendation I can give you is, whenever you hear a quote and you're not 100% sure what's true or if it's true or not, test it. Test it. A good article should tell you, this is what I did.  

![](https://i.ytimg.com/vi/UH35k9y6RAY/maxres3.jpg)



#### [0:41:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2460) |  This is where I put it in.

So for instance, there's an article that explains that Google Tag Manager unstructured data does not work with Googlebot. And that article is like two years old. And they have a piece of code that you can copy onto your page and try it out. And I took that piece of code and I put it into the Structured Data Testing tool. And yes, Structured Data Testing tool does not show it. Structured Data Testing tool is not the latest and greatest in terms of using the right infrastructure.  

#### [0:41:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2490) |  The Rich Results Test, however, does use

the actual indexing infrastructure and shows you what we actually seeing when we index your page. And that one showed the structure of data. And I'm like, aha. So the source of these conclusions is outdated because Structured Data Testing tool is outdated. But because this article was very transparent and self-contained when it comes to the how to test the hypothesis that they started with before they came  

#### [0:42:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2520) |  to the conclusion, I could go along

and say, yes, the article is right. That was the case back in the time. It is no longer the case, as seen here, by taking that exact example, putting it into the actual tools, and seeing that it works, where it didn't work when the article was written. So always take everything with a grain of salt, including the things that Google have said. If I say something today, it might be valid today and tomorrow but not in two years, not in one year maybe.  

#### [0:42:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2550) |  Make sure that you have the latest

sources. Our documentation-- we are not always 100% up to date. But we are trying our best to stay as up to date as possible. And usually, we draft the documentation before the thing is launched. And when it launches, we update the documentation in one go. If not, then we usually communicate that very clearly. So make sure that you are not jumping to conclusions. Test for yourself. And try to find the most up-to-date source of information.  

#### [0:43:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2580) |  Now another question from the chat. Giacomo

is asking, "For web sites like e-commerce that are using structured data for products, when we need a very quick update on availability for a specific product-- out of stock or something similar-- would you suggest implementing structured data in the HTML without JavaScript? Will Googlebot [? power ?] structured data after getting the non-rendered version of the website without waiting for the internal Chrome service to render a page queue in the render list? Or structured data will pass anyway after the rendering phase?"  

#### [0:43:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2610) |  The queue is, at median, five seconds.

So assume every page gets rendered these days. And that does not make that much of a difference. However, that being said, in the guidelines for structured data and JavaScript, I noticed that we do cache aggressively. That means if your JavaScript needs to update to actually reflect the new change in the structured data-- which might not be the case.  

#### [0:44:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2640) |  If you use Google Tag Manager, then

the JavaScript does not need to update, because it's just a data change. If your JavaScript needs to update to actually reflect the new structured data, then you definitely want to make sure that you use proper caching-- in this case, something wrong with caching, with hashes or version numbers or something like that, because if we use an outdated, cached version of your JavaScript that contains the structure data as part of the asset, we might not see that updating very quickly.  

#### [0:44:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2670) |  So I highly recommend making sure that

your JavaScript is updating and caching properly using Google's tools. Basically, whenever you see an update, you want to make sure that what we are crawling is actually the latest version of it rather than an outdated version. If you don't version your assets, that is very, very hard to debug, just to give you an example. Generally speaking, putting your structured data in HTML is probably always going to be more robust.  

#### [0:45:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2700) |  But there's nothing inherently wrong or faster

or slower regarding JavaScript unstructured data. "What's the average expiration date for technical statements from you?" Oh my goodness. I don't know. Sometimes it is years. Sometimes it is months. Sometimes it is weeks. If you ask me about the Google Chrome version that is being used to render-- if you would have asked me that two weeks before I/O last year-- so let's say you would have asked me that end of April 2018, I would have said it's Chrome 41.  

#### [0:45:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2730) |  That would have immediately changed in May.

I would have hinted at that to potentially change soon. But some people then ignore the fact that I say, but this is about to change, and then just quote me on, like Martin says, Chrome 41, which is true. I said that. They are just ignoring the sentence I said afterwards. So be very, very careful when people are quoting me. Generally speaking, just point to our guidance. Our guidance is 99% likely to be the actual source of truth.  

#### [0:46:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2760) |  Average expiration, I don't know. A month

maybe? Don't know. Cloaking question-- "If we use dynamic rendering on a page with infinite scrolling, would it be OK if the static HTML version that crawls so you have href links to the [INAUDIBLE]?"?" No, that's fine. That's absolutely fine. If you have pages, as in, like, Previous and Next or pagination links in the version that only Googlebot sees,  

#### [0:46:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2790) |  that's not a problem. That is OK.

That's perfectly fine. That's not an issue. All right, one more question from YouTube, maybe. "Would you generally recommend implementing dynamic rendering on e-commerce sites that use JavaScript to display products on category pages? My feeling is that this should make indexing more safe and accurate, especially for crawlers other than Google." We've said it multiple times.  

#### [0:47:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2820) |  As far as we're concerned, dynamic rendering

is a workaround. I would not recommend dynamic rendering to anyone who can reasonably switch to server side rendering and hydration, because server side rendering and hydration gives a more robust rendering to crawlers that don't understand JavaScript, as well as a better and usually faster way of rendering things for users, as well, whereas dynamic rendering is only useful for bots, especially those that don't run JavaScript.  

#### [0:47:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2850) |  So dynamic rendering is considered a workaround.

I would not necessarily encourage people to do that, unless it is the most viable option for them, until they can consider server-side rendering, or if server-side rendering is an investment they are not willing to make or they can't make, for whatever technical reasons. But generally speaking, if you can't do server-side rendering and hydration, sure. Go for dynamic rendering. That will definitely help you with crawlers and bots that don't run JavaScript or don't run JavaScript as reliable.  

#### [0:48:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2880) |  There's nothing wrong with it. That's it.

But understand that dynamic rendering, even though it's a workaround, does incur infrastructure costs. It does mean maintenance on your end, and can hurt you if it's implemented incorrectly. Everything that is implemented incorrectly can hurt you, including HTML, static HTML. So it's just more complexity. And you want to be careful if you really  

#### [0:48:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2910) |  need that additional complexity to reach whatever

goal it is. If you don't really care about search engines that don't support JavaScript-- as far as I'm aware, Bing supports JavaScript. Google supports JavaScript. If your rendered HTML on the Google tools looks fine, at least we are not concerned. I'm not sure how you test it on other search engines, but unless you have a good reason to implement dynamic rendering, I wouldn't.  

#### [0:49:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2940) |  OK. Do we have other questions? No.

Do you guys have-- or do you, ladies and gentlemen and others, have questions for me? DOMENIC FRANKE: So if nobody has a question, I have a question. MARTIN SPLITT: Go ahead. DOMENIC FRANKE: Yeah.  

#### [0:49:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=2970) |  So it's for the type of cloaking

question. So we have 3D data and a table with information of this 3D data on our page. The Googlebot is coming to us with the mobile version. I can see the GSC. So the point is, in the mobile version, we show the user first the 3D model  

#### [0:50:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=3000) |  and secondary he can click on a

button and the table is showing and 3D model is display [? none. ?] So is it cloaking if we say, OK, both content is in the same time in the content, but if the Googlebot comes, you see first the table? MARTIN SPLITT: No. That's not cloaking. DOMENIC FRANKE: OK. Perfect. MARTIN SPLITT: All right.  

#### [0:50:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=3030) |  Awesome. I think it's time for the

last couple of questions. Now is your chance. I ran out of YouTube questions, as far as I can tell. I can refresh the page. Maybe there is an additional one. I don't know. No, no, no, no. Doesn't look like it. No, no one asked-- oh, actually, no, that's not true. There's one more question. "Can FAQ, schema, and special announcement be read and indexed by Google delivered  

#### [0:51:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=3060) |  through JavaScript that is part of a

third party tool or platform?" Possibly. It depends on the implementation. It depends on if they let us crawl-- or actually, if they let us request their resources. So let's say you are using-- you are example.com and you are using a service from structureddata.org. I don't know. And structureddata.org says, oh, our API.js shall not be crawled by robots. So they say, like, they block it in robots.txt.  

#### [0:51:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=3090) |  What happens then is if we come

to your website and your website loads that JavaScript file, we can't load it, because they are saying we can't load that page using our robot. So Googlebot can't fetch the JavaScript. So the JavaScript doesn't run. And then the content doesn't display. That is a scenario that happens more often than you might think. And there's other ways, as well. There can be issues on their side, there can be problems with your JavaScript.  

#### [0:52:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=3120) |  So you have to test your implementation.

Fundamentally, technology-wise, it is absolutely fine to have FAQ schema and special announcements generated by JavaScript following our JavaScript [? unstructured ?] data guidelines. But you want to test that very carefully. If the test shows you yes, all good, then you're safe. If not, then, well, then you want to either talk to your third party provider or you might want to migrate away from that third party  

#### [0:52:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=3150) |  if that's something that you care for.

Test. Definitely test. OK. Time for a last question from the audience, if anyone has one. You can also write it into the chat if you don't want to speak up. That's also fine. I'm flexible either way.  

#### [0:53:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=3180) |  Cool. Wait. Chat has a question. "Is

there a rendering budget for web sites?" No. "Asking this question related to my previous one, because I can see that using Google Tag Manager for structured data, the big e-commerce site after a Googlebot visit, we have not the structured data updated. This is also for more than a week. Using HTML version, we get the data refreshed way more faster."  

#### [0:53:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=3210) |  That is possible. But there is no

such thing as render budget. This can be a caching issue, possibly. Without looking at the specific website, I can't really make a judgment on that. But if you are seeing issues, you're very likely running into caching. And then if you really care very much for the data to update very quickly, then either host a version of the JavaScript yourself, or consider having it in the HTML.  

#### [0:54:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=3240) |  But again, caching is king here. And

also, if we are not crawling it very often, then I don't think that's going to be even faster. But I think from what you say is that we are calling quite frequently, as the HTML does have the update, whereas we don't when it's using Google Tag Manager. So I guess Google Tag Manager might be also affected by caching, which would surprise me, but it's not impossible.  

#### [0:54:30](https://www.youtube.com/watch?v=UH35k9y6RAY&t=3270) |  OK. Excellent. I would like to thank

you all very much for these fantastic questions and joining me here live, as well as on YouTube, to give us all your questions and discuss them here in this forum. The next JavaScript SEO Office Hours will be in approximately two weeks time. I'll update the YouTube community feed  

#### [0:55:00](https://www.youtube.com/watch?v=UH35k9y6RAY&t=3300) |  with the actual dates. And we'll also

post the link there again. Thank you very, very much for being fantastic. Stay safe. Stay healthy. And all the best for you. Hope to see you soon again. Bye bye. MARIA AMELIE: Bye bye. KAIXI LUO: Stay healthy. DOMENIC FRANKE: Bye bye. MARTIN SPLITT: Trying my best. Trying my best.  