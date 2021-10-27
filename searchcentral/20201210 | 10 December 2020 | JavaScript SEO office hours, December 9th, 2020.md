[![JavaScript SEO office hours, December 9th, 2020](https://i.ytimg.com/vi/Z-x9l3ayBYU/maxresdefault.jpg)](https://www.youtube.com/watch?v=Z-x9l3ayBYU)

## JavaScript SEO office hours, December 9th, 2020

In the JavaScript SEO office hours, you can ask your questions about Google Search and JavaScript. You can either join the recordings live or post questions in the relevant thread on youtube.com/c/GoogleSearchCentral/community



#### [0:00:00](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=0) |  MARTIN SPLITT: Hello, and welcome to the

JavaScript SEO Office Hours today, December 9, 2020. I don't know. Today has been the longest month of the year, or the longest year of the month. I'm not sure. Great to have you all here. We will go through some of the submitted questions from YouTube, and then I'll hand over the word to the audience. If you have been to one of these office hours beforehand or if you're watching the recording and wonder what this is and how you can participate,  

#### [0:00:30](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=30) |  every two weeks we-- or I-- am

posting a thread on the Community tab of our YouTube channel where you can submit questions, and I also then, if you click on the-- in the comments, you click on the Sort By Newest first, and then you see me also posting the Hangout link to these Hangouts if you want to join the live recordings. We have a few questions today, one comes from [? Rafael, ?] who asks, facing a big problem with page speed and size  

#### [0:01:00](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=60) |  in Google AdSense. Pages with AdSense are

a battle of the metrics, so yellow or red. The pages without are green and yellow. So is there any way to delay the AdSense JavaScript in the plugin called WP Rocket? I don't know if there is a specific option for this. I know that this is hiding the issue from page speed metrics. However, I think if you have a way to insert it delayed,  

#### [0:01:30](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=90) |  that also makes it a little better

for the user, because the website becomes interactive and visible and the content is there. And then you load-- hopefully then you load the AdSense code. That should be a better user experience. And if it works, that's great. But for AdSense, I would ask the AdSense folks, because I'm not that familiar with the AdSense code base or the way that their stuff works. So that's that from my side.  

#### [0:02:00](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=120) |  And I have no suggestions to work

around this issue. I would bring it up with the AdSense support, because I think it's important that also our AdSense product makes good on the promise of good user experience. So that's that. But I'm not in the AdSense team. I can't really speak for them. Ricardo is asking about the intersection observer. He says, from what I understand, and correct me if I'm wrong, Googlebot renders the page using a very tall viewport. How tall is that, by the way? Good question.  

#### [0:02:30](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=150) |  For this reason, the suggestion for the

lazy loading of the images is to take advantage of the intersection observer, among other things. But what if my page is really tall, much taller than the viewport used by Googlebot? Everything not included in the viewport and therefore is not yielded is ignored by Googlebot? So that's a really good question. The reason why I know that Asaf, who is also on the call, has a question about the viewport, as well. The reason why I don't want to speak too much about the viewport is that that's an implementation  

#### [0:03:00](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=180) |  detail that can change at any point

in time without reference, and you should make your website work in a way that allows access to all content without having to be on a very specific viewport. Now, that being said, regarding how tall it is, it is as tall as it needs to be within certain limits. Now, I know that's a fantastic response. But what we do is-- and again, that's an implementation detail that can, at any point in time,  

#### [0:03:30](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=210) |  change. The way that we deal with

things is we don't scroll because that's surprisingly expensive and glitchy. What we do instead is we expand the viewport. And when we see that there's new content being loaded, we expand the viewport further. We can do that quite a while. At some point, due to memory constraints, we might not do it any further. So I would recommend making sure that you have a way to either split the content up so that you can access it  

#### [0:04:00](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=240) |  via a specific URL, or making sure

that the individual bits and pieces that you care about are available under different URLs and are submitted through the sitemap, or use the intersection observer, but don't expect everything to be in the page unless it is a reasonable-- or a reasonably small amount. So I would say if you need, let's say, like a million pixels, then you are probably looking at something where eventually we would cut off. I picked a million pixels arbitrarily. I'm not saying we can't go further  

![](https://i.ytimg.com/vi/Z-x9l3ayBYU/maxres1.jpg)



#### [0:04:30](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=270) |  than one million pixels. I'm also not

saying we are going to one million pixels. What I'm saying is, there is a certain amount of wiggle room where the intersection observers still work. And I think we might actually fire all intersection observers unless we see that it stops creating new code. But I can't guarantee that that's the case. And I am not sure what the limitations are, where the [? heuristics ?] kick in. So again, as long as these items are just basically links to other pages that have the actual content, that's  

#### [0:05:00](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=300) |  not a problem, because then you can

submit these individually to sitemaps, for instance, or offer a paginated version of the infinite scroll. But infinite scroll is definitely a challenging and interesting use case. Normally, intersectional observers should get you pretty far. So that's that, which guides me gently into Asaf's question. I know you have a question about the desktop crawling viewport, don't you? AUDIENCE: Right. Yeah.  

#### [0:05:30](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=330) |  So you want me to-- MARTIN SPLITT:

Feel free to. I can also-- do you want me to read it out? I can also read out your question. AUDIENCE: Yeah. It's a better idea. MARTIN SPLITT: All right. So Asaf was asking if, on Googlebot desktop, so he has a site with three column layout. And one of the columns is triggered only when the viewport is at least 1,200 pixels wide. You haven't seen it being rendered either on the [? screenshare ?] or the code itself. What's the threshold for getting the content rendered? I guess the threshold is 1,024 pixels.  

#### [0:06:00](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=360) |  If that's the correct dimension, do you

think it's aligned with most desktop cases? 1,024 is not really a desktop size, more a tablet size these days. Yeah. So as I said, I don't actually know the dimensions, because I don't care and it shouldn't matter as much. I know that there is an option. Hypothetically we could even do what we do for vertical layouts in horizontal.  

#### [0:06:30](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=390) |  We can expand horizontally. But as far

as I'm aware, Googlebot doesn't make use of that. What's the default width of the viewport? It should actually be-- I think the default starting width and height is 10,000 pixels in each direction. So I'm surprised that you seem to be seeing 1,024 pixels. That's a very specific number and I'm not sure where that comes from. AUDIENCE: So basically, we ran around 20 tests  

#### [0:07:00](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=420) |  and we hit that 1,024 and it

broke the left column. MARTIN SPLITT: And you could see the rendered HTML included the content only when you were broader than 1,024. AUDIENCE: Right. MARTIN SPLITT: Right. That's interesting, because it should be broader. But generally-- AUDIENCE: Also, we want to prevent of having the 1,024,  

#### [0:07:30](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=450) |  because we don't want to show it

for tablet. MARTIN SPLITT: An interesting question there is why-- so if it's a matter of not showing it or showing it differently-- so if it's a proper responsive design, then that shouldn't be a problem. Then it should always be in the DOM somewhere. Is that the case, or is it only being loaded into the DOM if the screen size has a certain size, or if the viewport is a certain size?  

#### [0:08:00](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=480) |  AUDIENCE: Right. So if you stretch it

and reach the-- like from browser, can you reach the 1,200? MARTIN SPLITT: Yeah. AUDIENCE: So you-- it's showing up. But if you reduce it-- MARTIN SPLITT: But when you say showing up, does that mean it loads additional content at that moment? AUDIENCE: Right. MARTIN SPLITT: Right.  

#### [0:08:30](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=510) |  Well, what's the use case here? Why

is this content not available to someone on a smaller screen device? AUDIENCE: Because we want to differentiate between tablet users and desktop users. Like, we don't want to have this column on tablet, because it's look like too-- can't think of the word. MARTIN SPLITT: Right. I understand what you mean. It looks too busy. It looks too full. AUDIENCE: Too busy, yeah.  

![](https://i.ytimg.com/vi/Z-x9l3ayBYU/maxres2.jpg)



#### [0:09:00](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=540) |  MARTIN SPLITT: Interesting. The thing that I'm

surprised by is, though, that it's 1,024. That's a very odd number that I wouldn't have expected. And your inner width and inner height report 1,024, as well? And it is quite arbitrary. As far as I'm aware the default number-- I would have to double check what we are actually using in indexing, because it's a configuration that goes through [? WRS. ?] And I'm not exactly sure what is the configuration.  

#### [0:09:30](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=570) |  But again, it's also an implementation detail.

And the question really is, how can-- if this content is important for you, or important enough for you so that Google needs to see it, how can you include the content in a way that doesn't make the design too busy? And there's lots of ways of doing that, right? AUDIENCE: So basically we did add the functionality that will take this unit and embed it in the shrink version.  

#### [0:10:00](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=600) |  MARTIN SPLITT: Mm-hmm. AUDIENCE: So we're talking

about the author bio. So-- MARTIN SPLITT: Oh. OK, I see. Yeah. AUDIENCE: So we do want to have-- to get it crawled by Google. But we need some kind of solution. I'm just wondering what is the threshold like? MARTIN SPLITT: Seems to be 1,024, even though I would not rely on that. As I said, this can change any time in either direction,  

#### [0:10:30](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=630) |  because we are not guaranteeing this. There's

a reason-- this is one of the cases where there is a gap in the documentation and the gap in the documentation has a reason. The reason is that you shouldn't rely on it and you can't rely on it. AUDIENCE: And the second that I wrote there is, is that the case for desktop viewport, like 1,024? So I think this one-- this is the--  

#### [0:11:00](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=660) |  MARTIN SPLITT: Seems to be, which surprises

me, because I know that at least for vertical, we do expand. Not 100% sure if we expand for horizontal. I don't think we do. So you would normally see taller viewports, as in more height of the viewport, depending on how large or how tall your content is. That should generally work. Not 100% sure what's happening with height. Pretty sure that is fixed. And I'm not sure what it is fixed to.  

#### [0:11:30](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=690) |  Probably 1,024. If you say that that's

what your test concludes, I have no reason to doubt that. AUDIENCE: Yeah, like after 20 test we will reach that number I wouldn't be surprised if that's what's happening I'm actually trying to search the source code right now to find that specific part-- ooh, what's happening out there? Let's see if I can find the-- ah, no. I clicked on the wrong button and now I have the ugly version again. Damn it. The new interface is fascinating.  

#### [0:12:00](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=720) |  Let's put it that way. And it

does no longer have the old files, which is unfortunate, because that was useful. I am pretty sure-- ah, hold on. Actually, I can try it here. Aha. I can try it by actually just passing in the request through the rendering system and then I'll see what comes out. But the 1,024 is a good possibility. You also had the question with the no archive tag inserted  

#### [0:12:30](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=750) |  by [? helmet. ?] That should be

fine. That should be picked up. I would argue that that's maybe a glitch in the cache and then that's a problem, because the cache is not really maintained anymore. AUDIENCE: Again? I didn't understand. MARTIN SPLITT: Oh, so the no archive, if I remember correctly, is pretty much just so that you are not getting into the down time cache thing,  

#### [0:13:00](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=780) |  like view page in cache. Should be

fine. If it isn't, if you see that it behaves differently, then that's a good possibility that the way that the cache feature picks it up happens at an earlier stage in the pipeline, which is a bit of a tricky thing, because the cache feature itself is actually not actively maintained anymore. It just is there because it kind of works. And it would be a shame to stop supporting it.  

![](https://i.ytimg.com/vi/Z-x9l3ayBYU/maxres3.jpg)



#### [0:13:30](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=810) |  AUDIENCE: Probably you are not rending the

page through-- MARTIN SPLITT: It's possible-- well, I mean we are always rendering the page. What's possible is that the cache service kicks in right after crawling, which would then basically mean that we are not getting the rendered version. We are rendering the page. We're just not getting the rendered version for the cache, or the cache actually pulls out data before the rendering happens, which is a bit unfortunate if that's a problem.  

#### [0:14:00](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=840) |  AUDIENCE: The AMP team regards the AMP

HTML tag, they say that they don't rely on JavaScript. And you need to-- MARTIN SPLITT: Because they don't have to. Yeah. AUDIENCE: Yeah, so maybe with no archive is the same. MARTIN SPLITT: That is very much possible. But I would be surprised, because I know the bit that parses meta tags. And AMP is not a meta tag.  

#### [0:14:30](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=870) |  The meta tags in non-AMP pages are

parsed before and after rendering. The question is, when does the cache build its entry? When does the cache get populated? It is possible that the cache populates immediately with a fetch reply from the crawler. So immediately after crawling, it pulls itself a copy. It is also possible that it actually only pulls itself a copy once things get into the index. I could see that being reasonable, as well. And that would basically mean that you would not  

#### [0:15:00](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=900) |  see problems with a JavaScript injected variation

of this. But again, it is possible that we are pulling it earlier in the process and then you will probably see that it's not picking this one up. And this is actually really tricky to debug, because it might also just be race conditions, because a lot of things happen in parallel. So sometimes we might see the rendered version. Sometimes we might not. That's something that we see with a cache in general. Sometimes we see the rendered version in the cache.  

#### [0:15:30](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=930) |  Most of the time, we don't. And

I have the feeling that because the cache tries to extract information as early as possible from the document. And that's very likely to end up being before rendering. So I wouldn't rely on the no archive tag being inserted from JavaScript. Generally, I would always try to get the meta tags consistent before you need JavaScript, or at least leave them out, if you can, and only add them with JavaScript if you can't make them consistent between the [? server sent ?]  

#### [0:16:00](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=960) |  version and the JavaScript-rendered version. [SNEEZING] Excuse

me. AUDIENCE: Bless you. MARTIN SPLITT: Thank you. AUDIENCE: So currently our main [INAUDIBLE] is desktop. So we did have this tag on the raw HTML and laptop. But when we will move to mobile first, don't have a solution yet, but-- MARTIN SPLITT: Should be fine. I mean, on the other hand, what's the big problem with the cache?  

#### [0:16:30](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=990) |  I'm not sure most people are even

aware that that still exists. I only use it when the website is down. AUDIENCE: Why we don't want our pages to be cached? It's a secret. MARTIN SPLITT: OK. Everything's secret. Oh my. Awesome. AUDIENCE: No, it's like, we're a publisher, and you know. MARTIN SPLITT: Right. Aha.  

#### [0:17:00](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=1020) |  OK. I see where this is going.

All right. OK. I understand that. Right. Oh my. The data on the marketplace thing is broken. I can't actually access the output from [? Rafael ?] right now. That's unfortunate. Yeah, so I would test it. But I think you have a 50/50 chance. I think it's a race condition kind of situation. AUDIENCE: Got it. Thank you very much for both of them. MARTIN SPLITT: Doing my best. Sorry.  

#### [0:17:30](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=1050) |  All right. Do we have any other

questions? We have a few more minutes before I've got to head out for today. All right. There's no further questions. I'd like to thank everyone who joined. Today's recording has been a huge pleasure. I wish you all a lovely, lovely time. Stay safe. Stay healthy. The next office hours is going to be in two weeks.  

#### [0:18:00](https://www.youtube.com/watch?v=Z-x9l3ayBYU&t=1080) |  I'll get this video updated-- updated, uploaded

to the channel as soon as possible. And then I'll put the thread for the fortnightly next edition of the JavaScript SEO Office Hours into the YouTube channel. Thanks a lot. Have a lovely evening or a lovely morning, afternoon, whatever it is where you are. It has been a pleasure. Stay safe. Stay healthy. AUDIENCE: Bye bye.  