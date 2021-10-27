[![JavaScript SEO office hours June 10th, 2020](https://i.ytimg.com/vi/n18nYA2FqrI/maxresdefault.jpg)](https://www.youtube.com/watch?v=n18nYA2FqrI)

## JavaScript SEO office hours June 10th, 2020

This is a recording of the JavaScript SEO office-hours hangout from June 10th, 2020. These sessions are open to anything around SEO for JavaScript sites.



Watch out for new sessions, and add your questions at youtube.com/googlewebmasters/community



#### [0:00:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=0) |  MARTIN SPLITT: Hi, everyone, and welcome to

the June 10 edition of the JavaScript SEO Office Hours. I'm super happy to see that a few people joined the recording as well and that lots of questions were submitted. So let's get going. I'll start with a question from YouTube, and then I'll ask the audience if there's any questions in the audience as well. So, is Google Search Console a good way of identifying whether Google is able to crawl links that  

#### [0:00:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=30) |  are coded up within JavaScript. That is,

if I run a URL that has lots of JavaScript on the page and the source code, is the source code captured in Google Search Console a good way of identifying how Google is able to crawl that JavaScript? Yes. If you use any of the testing tools-- so the URL inspection tool in Search Console, the rich results test, or the mobile-friendly test, or the AMP test or whatever, you see the rendered HTML. That is what Google sees. If something is in there, good. If something is not in there, not good.  

#### [0:01:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=60) |  That means that we are not seeing

it. That's relatively easily said and done. Do we have questions from the audience? AUDIENCE: I've actually got a question that I did submit as well. MARTIN SPLITT: All right. AUDIENCE: It's just around-- so to add a bit of background, we basically have a number of customers that we help to kind of do SEO. And a lot of their websites are built  

#### [0:01:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=90) |  in platforms which don't give you the

ability to control change in different elements-- really basic elements, like title tags, headings, that sort of stuff. So we built a little JavaScript script that we added onto their website that would give us the ability, using JavaScript, to update some of these elements. Google doesn't always seem to pick up the changes that we make. So kind of two questions. One was, is there a certain way in which we should load that JavaScript-- a certain point at which it  

#### [0:02:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=120) |  should be loaded in when the page

is rendered? And then also, secondly is, what's the best way to check to see that Google's picked up on changes? MARTIN SPLITT: So generally, there's no problem with doing that. And I would say the earlier you do load the JavaScript, the better it is, because we are running a bunch of heuristics to figure out when the page is done. So if it takes a lot longer than-- basically, if the page does its thing, and then a long time passes, and then your script kicks in, we might actually miss that last bit.  

#### [0:02:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=150) |  So the earlier you can do it,

the better it is. Even better if you can do it server-side. If you can't, then that's fine as well. And to test this, the best thing is to use any other testing tools and check in the rendered HTML if what we're rendering there, or what we are seeing there, is what you expect us to see. AUDIENCE: OK. Yeah, because we started doing this quite a while ago, I think before the new version of Search Console. So that wasn't kind of fully available at the time. And what we were doing was we were seeing within the actual search results page  

#### [0:03:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=180) |  for the website the kind of title

that got put back in the meta description that got brought back, whether that was updated. Is that not a good way to test it? MARTIN SPLITT: That's not really a good way to test it, because we might rewrite that. AUDIENCE: It was-- the actual I think was happening was, it was actually showing the non-rendered [INAUDIBLE] title tag was showing in the search result and not rendered. MARTIN SPLITT: Yeah, might happen if we think that that's a better choice. AUDIENCE: OK. That's fair enough. Yeah, that's fine then. That's my question answered. Thank you. MARTIN SPLITT: Awesome. You're welcome.  

#### [0:03:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=210) |  Then we have a question on-- hold

on, no. I actually confused myself, and I'm not sure if I am in the right thing. Yes, here. What's the definition of the load event in the DevTools? Mozilla says the load event is fired when the whole page is loaded, including all dependent resources, such as style sheets and images. But what does the decision-- definition of "the whole page is loaded"? So there's two events, technically speaking, that the DevTools highlight.  

#### [0:04:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=240) |  One is the load event, one is

the DOMContentLoaded event, I think. The DOMContentLoaded event is the moment when the DOM has entirely been parsed, but things might still be pending. So for instance, if the HTML has an image, and an iframe, and a style sheet and whatnot in there, then the DOMContentLoaded would fire the moment we have parsed the HTML, so even before we know what's in the iframe, before we know the image-- like if the image exists, what the image looks like--  

#### [0:04:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=270) |  so that's like basically when the HTML

has been parsed and understood, and the DOM has been constructed. And then the load event waits for everything to finish its thing. So if we have like seen a script, and a style sheet, and two images, and a video, and an iframe, all of that would have to finish loading before the load event fires. But these scripts in turn might do things themselves,  

#### [0:05:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=300) |  like load something. This might or might

not be before the load event fires. Because the load event fundamentally says everything that is referenced in the DOM has been downloaded and is there. It does not mean that the scripts have been executed. And also, just imagine a script could hypothetically have a set timeout for five seconds, and then after five seconds make a network request. So the load event wouldn't wait for that to happen. The load event would fire the moment everything  

#### [0:05:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=330) |  has been downloaded that belongs to the

page-- every style sheet, every image, every video, everything. So content that is added afterwards by JavaScript is not considered in the load event. So the load event might fire before these things start to load. I know that's a little tricky sometimes to figure out why the load event is in a certain spot and not later or earlier. But that's roughly how that works.  

#### [0:06:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=360) |  All right. Do we have other questions

from the audience before I go to the YouTube questions? AUDIENCE: Yeah, I have a question about server-side rendering. So I'm considering doing a hybrid approach right now-- it's client-side rendering-- and to, let's say, save resources or prioritize, I'm asking, what would you recommend for the approach to take on what to prioritize? So for example, content or title tag or canonical?  

#### [0:06:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=390) |  What should I prioritize in terms of

going server-side hybrid? MARTIN SPLITT: Right. I would-- if you want the biggest bang for the buck when it comes to server-side rendering-- because server-side rendering is quite an investment, both in coding effort as well as infrastructure-- I would say everything that is critical content. So title, meta description, canonical, and the actual content that the user is interested when they come to the page.  

#### [0:07:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=420) |  So then what that is depends a

little bit on what your website looks like. If it's a shop, it's very likely that the main content that you want to server-side render is probably the actual product description and product images and stuff like that. If it's a blog, it's very likely the article content. And then everything that is kind of secondary-- I don't know, like comments, ratings, whatever-- these kind of things can potentially be client-side rendered afterwards, because you want the largest contentful pane, the big blob  

#### [0:07:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=450) |  of things that the user is interested

in, you want that as quickly as possible. And as quickly as possible usually means server-side rendered. AUDIENCE: Great, thanks. Also, in addition to that, the canonical right now on the server-side almost on all pages is going to the homepage, but then the rendered goes to the inner page. So would you then prioritize that over critical content? MARTIN SPLITT: I would say no. I would always go for the critical content over any  

#### [0:08:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=480) |  of the meta information. But having that--

it's probably better not having a canonical than having an incorrect canonical and then updating that, or adding that using client-side rendering. Because it is unlikely but it can happen that we get confused when you give us a canonical before the rendered version, after the rendered version. It is unlikely-- I say that again, because I know that that will be tweets and blog posts about this later. It is unlikely that this happens, but it can happen.  

#### [0:08:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=510) |  It's just a matter of giving us

misleading or like conflicting information, might mean knowing that we pick the wrong one. AUDIENCE: One way that I tried to investigate to see if that's happening is in a new page. So about April 2 is when the site switched over to mobile-first index. And after that, a new page was published. And the user declared canonical in the URL [INAUDIBLE] is the desktop URL.  

#### [0:09:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=540) |  And I have a separate mobile site

within that. And I'm suspecting that the canonical is the cause of this. So instead, I would expect to see the m-dot as the canonical. MARTIN SPLITT: With m-dot and mobile-friendly-- sorry, mobile-first indexing, there is like lots of variables in the error. It's hard to pin that down. But it could be. AUDIENCE: I guess what I was trying to say is that, is Search Console--  

#### [0:09:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=570) |  or can I use Search Console URL

inspection as an indicator if there is confusion regarding the canonical? MARTIN SPLITT: Yeah. AUDIENCE: OK. Thanks. MARTIN SPLITT: You're welcome. Right. We have lots of questions through YouTube today. So that's great. Is it a problem to return a robot noindex in the HTTP header of JavaScript or CSS files? I know it's better if they're crawlable, but should they be indexable from an SEO point of view? I don't think it hurts.  

![](https://i.ytimg.com/vi/n18nYA2FqrI/maxres1.jpg)



#### [0:10:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=600) |  I don't see that much of a

use for it, because normally they don't get indexed. So I would say you can do it. I wouldn't unless you are seeing a specific problem in that regard. I would not robots.txt block them-- different thing. I know that that's not in the question, but I am saying this to make sure that no one gets this wrong. If you robots.txt-- sorry, robots block JavaScript and CSS files from crawling, that might lead to problems in certain cases.  

#### [0:10:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=630) |  So I would not do that. One

more YouTube question. I use server with pure Nginx and Redis. The CMS is WordPress. OK. Optimizations are server-level caching, [INAUDIBLE] interface loads, duh, duh, duh, long-form pages. Page speed score is 92, the loading speed components are mostly green with nothing going above 3.2 seconds. Duh, duh, duh. But cache-- so don't use cache.  

#### [0:11:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=660) |  The cache colon URL thing is just

a convenient feature. If it doesn't look right, that means nothing. Ignore cache. Cache is not a testing tool. It's not a testing tool. Don't use the testing tool. Search Console inspect URL-- that's a testing tool, good-- feature shows HTML code where images are present but cannot generate screenshots. It throws an error each time trying to generate one. Tools that use headless Chromium also cannot generate screenshots and crash [INAUDIBLE]  

#### [0:11:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=690) |  Honestly, I don't care about the screenshot.

Look at the rendered HTML. If the rendered HTML looks the way you expect it, you're good. That's it. The screenshot is just a nice-to-have again. And using headless Chromium as a testing tool, that's a nice thing on top of it. But that might crash for completely unrelated reasons. So I wouldn't worry too much about it. Smaller pages, images are loaded fine. Search Console shows HTML has the images, URLs, generate screenshots and-- yeah. Again, doesn't matter.  

#### [0:12:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=720) |  It sounds like your website, like the

long pages, are just very long, and they exceed memory limits. And that's OK. That's not a problem. In indexing, we don't care. It's absolutely-- as long as the rendered HTML looks good, you should be fine. Why is there such inconsistencies? Welcome to the world of software. Computers are terrible. Is it possible that if Googlebot in Chromium might be glitching out visual render-- no. No, this would not be counted against you.  

#### [0:12:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=750) |  No. Does Googlebot headless Chromium support native

lazy loading? Yes, it does. All right. Then, Is it possible to not load scripts on specific pages if you do not use it there? For example, reCAPTCHA is only used on the [INAUDIBLE] page. Yeah, that is absolutely possible. The things you want to look for is-- or the term you want to look for is code splitting. Why is there always a big difference in Lighthouse score between desktop and mobile? Because mobile is a lot slower.  

#### [0:13:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=780) |  The CPU is throttled, because mobile app

processes are very different from desktop processors, both architecture-wise and performance-wise. So mobile is kind of like the lowest common denominator. And I would watch more for mobile than for desktop if I were you, because mobile devices usually are not as powerful as desktop devices are. And one last question before I go back to the audience.  

#### [0:13:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=810) |  We want to improve the load time

of our pages. We implemented lazy loading with a placeholder as it is advised by Google guidelines. Which Google guidelines? But OK. My issue is I would call in Google to crawl the page first. Google does not render the screenshot view-- it does not have any images in the screenshot view. The screenshot view doesn't matter as much. The rendered HTML is more important, actually. The source of the images in the rendered HTML-- aha-- still displayed as a placeholder images. That very likely means that we are-- that your lazy loading is not implemented correctly,  

#### [0:14:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=840) |  and we are not seeing the actual

image URLs. So you definitely want to look into that. And if we are rendering the placeholder URL, that is very likely an issue. Right. Back to the audience. Any questions in the audience?  

#### [0:14:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=870) |  AUDIENCE: Nobody else has questions, I can

still-- MARTIN SPLITT: Yeah. AUDIENCE: Sure. So I'm asking about the intrusive interstitials. And for starters, there's some documentation about mobile obtrusive or intrusive interstitials. I'm asking about desktop. Does desktop affect at all your ranking? Obviously, user experience can have effect.  

#### [0:15:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=900) |  But I'm wondering if a page would

get devalued on desktop. MARTIN SPLITT: That's a ranking questions, and I don't really answer ranking questions. AUDIENCE: Gotcha. So maybe the question that I do have regarding this does touch on JavaScript a bit, and maybe you can help out. I'm wondering about the-- let's say you have a privacy policy. Like in California, you know we have the privacy policy. So that's a full page. And I'm wondering just in the background,  

#### [0:15:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=930) |  how does Google know that this is

a privacy policy, and that it's OK, as opposed to something that's more advertising or promotion-related? MARTIN SPLITT: I guess it depends a little bit on how your interstitial looks like. I think if it blocks the entire page, that's probably not fantastic. If it's a pop-up or like a pop-over a kind of thing, like a cookie banner or whatever, it's probably better. But that's actually a question that is not really with me.  

#### [0:16:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=960) |  That's probably more for the general office

hours with John. AUDIENCE: OK. I'll bring it up. MARTIN SPLITT: Awesome. AUDIENCE: Thanks. MARTIN SPLITT: You're welcome. And I see that someone submitted something into chat that is also submitted on YouTube. But I'll take it anyway. Since rendering of widgets components by JavaScript are considered not useful for SEO but developers are always happy in doing more rendering some client sites JavaScript, as it helps in reducing-- there's like random notation  

#### [0:16:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=990) |  in here-- JavaScript as it helps in

reducing the patient load time with a big margin. What? But ever since-- evergreen Googlebot has already been announced, so it is being used in the much updated version of Chrome. As a result, we will be able to see the JavaScript AJAX driven items. So will the widgets rendered by JavaScript-- oh, my god. I don't know what you mean by widgets. If it's content that is put in the page  

#### [0:17:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1020) |  by client-side JavaScript, we'll probably see it,

and then we'll probably also use it. So yeah. I mean, we are running the evergreen Googlebot. There is no problem with client-side rendering per se. If it's in the rendered HTML, we can use it. Depends a little bit on what you mean with widgets and visualization. I'm not 100% sure what that means. Right. Do you have any current documentation with recommendations for processes and tools  

#### [0:17:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1050) |  to use for how SEO should go

about diagnosing issues with JavaScript-based websites? Yes, we do. If you go to Google-- sorry, developers.google.com/search then click on Guides, there's an entire section on JavaScript. And my favorite one is G-O-O dot G-L-E slash J-S-- actually, now I have to see if-- what was it? G-O-O dot G-L-E slash J-S-S-E-O--  

#### [0:18:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1080) |  J-S dash S-E-O dash-- screw it, I'll

just post it in the chat. Actually, I'm not in the chat, but under the question. Here we go. So if you go to developers.google.com/search, you'll see our guides-- multiple-- on JavaScript SEO. And they are pretty much up to date, because I keep them up to date. Some websites use different approaches or user behavior  

#### [0:18:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1110) |  for desktop, mobile, and AMP. On m-dot

web, browsing uses a layered approach-- what is a layered approach? On click, a page layer opens with [? may ?] lesser content against web version. OK. On desktop, regular click to URL approach redirects regular web page. On AMP, again, maybe click to URLs since AMP doesn't give flexibility to do so.  

#### [0:19:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1140) |  Will this be not recommended or a

good practice? I think this sounds more complicated than it's worth. I wouldn't do it. It's not per se bad. It's just, it invites problems. It's more complicated-- like, the possible downside is much bigger than the possible upside of it. So I wouldn't do it. That's Kieran's question that we answered earlier. That's [INAUDIBLE] question that I tried to answer earlier.  

#### [0:19:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1170) |  And then that's the questions for this--

I know that last week we skipped, so I'll have a look at what was submitted last week. Our client has a website built on WordPress, where he's using a very JS-dependent theme. Basically, after I disable JavaScript the website itself stops working, and there's almost no content in it. Is this a huge problem from SEO point of view? Is there something we can do other than switching themes of the website  

![](https://i.ytimg.com/vi/n18nYA2FqrI/maxres2.jpg)



#### [0:20:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1200) |  and therefore rebuilding it? It could be

a problem. It doesn't have to be a problem. If you are seeing issues with the site being indexed and showing up in Google, then this might be the reason, because that sounds like it's less robust than it could be. But then again, if it works fine, then I wouldn't fix it, because fixing something that isn't broken usually means you're actually breaking it.  

#### [0:20:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1230) |  However, I think reducing the dependence on

JavaScript is always useful. So I would probably actually switch themes, or at least understand why there is so much JavaScript and what this JavaScript does, and try to weed out the JavaScript that isn't absolutely essential. But that in itself is a lot of work as well. So you have to decide if the work invested there is worth it. And if it's not broken I wouldn't fix it,  

#### [0:21:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1260) |  because it's not broken. I recently have

a client that had an amazing first input delay score but terrible time-to-interactive and terrible total blocking time. How can this happen? I suppose when the JavaScript is loaded overall, it's split into smaller bundles. That might cause this, but I'm not sure this is the cause. Also, if I have amazing first input delay, do I still need to care about bad time-to-interactive and total blocking time?  

#### [0:21:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1290) |  That's a tricky one, because I'm not

100% sure how TTI and TBT are calculated these days. I think what I could imagine is that something does block the main thread in certain intervals, and that we are not picking this up when calculating the FID.  

#### [0:22:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1320) |  And then it's one of these cases

where measuring these things automatically is just really hard, and you have to see how it actually looks for a real user. And I would assume that if your first input delay is pretty low, and the user has an interactive page, then TTI and TBT don't-- none of these metrics makes sense when the real user experience is actually pretty good. Hypothetically, in a perfect world, that would never happen. In the perfect world, our metrics would reflect 100% what the user actually experiences.  

#### [0:22:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1350) |  But surprise, surprise, we don't live in

a perfect world, and these metrics are sometimes just off. But that's something that I would ask the Lighthouse team, or like open a bug in Lighthouse with the sample URL. Because it sounds like an edge case that isn't quite usual or quite frequently happening. Or maybe they know something that I don't know. But that's what I would think from the way that I rationalize about these metrics,  

#### [0:23:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1380) |  that this is an interesting edge case.

Then we had the load event question. I answered that. If nothing can be painted before CSS is downloaded and the CSS object model is constructed, how can flash of unstyled content logically happen? Because things can be painted before the CSS object model is done. The reason for that is that the browser has a default style sheet. It has a-- like, if you don't specify any styles, and you have headline, and a paragraph, and a button, and a link, all of these things have a default style, which  

#### [0:23:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1410) |  is kind of "unstyled" content. I mean,

you get like a sans font from the system, and headlines are big and black, and then links are blue and underlined, and stuff like that. That is what I would consider a flash of unstyled content if it takes too long to actually get the resource from the server to actually start loading your CSS.  

#### [0:24:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1440) |  That's why it's suggested to prevent that

from-- sorry, to prevent that from happening by inlining the critical styles, so everything that is very, very layout-critical-- like how large are our headlines, how roughly do our paragraphs look, like all this kind of stuff. So that the moment it starts parsing the HTML, it parses the inline CSS for the critical styles,  

#### [0:24:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1470) |  and then it continues parsing the actual

content. So when it constructs the contents, it can automatically link that to the CSS object model and have the actual stylus rather thank the default style. So that's how that works. The DOM can start rendering before the CSS is loaded, hypothetically. All right. Questions from the audience?  

#### [0:25:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1500) |  Oh, few questions in the chat. All

right, let's see. Do JavaScript websites consume additional crawl budget compared to a non-JS website with a similar number of pages? Will non-JavaScript websites have an advantage over JavaScript websites in terms of crawl budget? Maybe it's the answer to that. I say maybe, because I don't want to say "it depends" so often. It does depend. Assuming that you have a static website that has, let's say,  

#### [0:25:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1530) |  five HTML pages, and each of these

five HTML pages has one image inside and one style sheet that is the same across all the pages-- so like, you have a style.css that is loaded on all of these pages, all of these five HTML pages, and then you have five different images on each of these five HTML pages, and they are static, and there's no JavaScript involved-- then what would happen is, we would do five requests  

#### [0:26:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1560) |  for the HTML files. We would do

one request for the CSS file, because we catch it. So we request the first HTML we request. We also request the image, and we request the CSS file. We cache the image, we cache the CSS file. So when we request the second HTML file, which loads the same CSS file that we cached here, we are not going to request it again. We do request the other image, because it's a different image. So OK. So that would mean we have five HTML files, we have five image files-- so that's 10 requests--  

#### [0:26:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1590) |  and then we have one style.css file.

That's the 11th request. So these five pages would cause 11 requests, which is kind of what your crawl budget is-- or effects. If you have a JavaScript in there that add some funky functionality, and it's the same JavaScript on all of these pages-- or three of these pages have the same JavaScript, the other two doesn't even load any JavaScript-- then the same thing with the CSS would happen.  

#### [0:27:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1620) |  If all five HTML pages have the

same JavaScript applied to them, and it doesn't make any additional network requests, then we would download that JavaScript file, we would cache it, and then the other pages would just use the cached version of that. If this JavaScript, however, does network requests-- API requests, loading additional images, whatever-- these requests also count against the crawl budget. But let's say you have a JavaScript that loads--  

#### [0:27:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1650) |  I don't know, loads-- man-- a counter,

like a visitor counter, from a network database on an API or whatever, it makes an API call, it makes the same API call on all of these pages. Again, we would make this API call once and then cache the result for the other pages. So it does have impact on your crawl budget, but it doesn't automatically mean that you have a problem. Honestly, most pages, unless--  

#### [0:28:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1680) |  most sites, unless they are like sites

with like tens of millions of URLs, or sites that have a really bad server, don't really hit this problem. So I wouldn't say that JavaScript has a huge impact on crawl budget, to be honest. It can have a bit of an impact on crawl budget. But I would say it's not as relevant as people might think it is. Next question. If the website is completely blocked with no possible user  

#### [0:28:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1710) |  engagement when JavaScript is disabled, if we

display a message, "please enable JavaScript"-- yeah, that's kind of bad. I mean, not for SEO necessarily. If you say like, oh, you don't have JavaScript enabled, then screw you, but it just rubs me the wrong way in the sense of, if JavaScript goes wrong-- and JavaScript is more likely to go wrong than HTML downloads or CSS downloads, because these things can be starting  

#### [0:29:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1740) |  to have an impact as they download,

whereas JavaScript has to be fully downloaded then parsed and then executed. It's just more potential for things going wrong. It's not a problem per se. It also isn't exactly great for the user, especially if they decide to browse without JavaScript, or there is a problem with your JavaScript. I wouldn't fix it if you don't experience problems or bad feedback from users. But if I were to build a website today,  

#### [0:29:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1770) |  I wouldn't build it that way, I

think. We used to do that in 2012 or something. I remember that was like a default thing to do. And it felt wrong back then, and it does feel wrong today, if you ask me. But there is no inherent SEO downside or any inherent problem with it, from Google's perspective at least. Why field data and lab data have differences for page speed? Well, surprise-- they are not the same thing.  

![](https://i.ytimg.com/vi/n18nYA2FqrI/maxres3.jpg)



#### [0:30:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1800) |  Field data is coming from real users,

whereas lab data comes from a quite strong machine with probably good internet from somewhere around the world. So you might not see the same results. If the lab data is from, I don't know, Mountain View or-- let's make an example. If I run my server here in Switzerland, and my lab data comes from Switzerland,  

#### [0:30:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1830) |  then that's going to be really fast.

Like, we're going to have a fantastic network connection in between the two. If the lab data is gathered on my MacBook here, what has I don't know how many cores, and how much memory, and I don't even-- like, it has quite a bit of power under the hood, and it has a fantastic network connection. It's also a very short network connection. Like Zurich-- Switzerland is a small country, so the time, the physical time it takes to go to the server and the other end of Switzerland and come back is minimal.  

#### [0:31:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1860) |  So my lab data would look fantastic.

If my users are actually in the US, and they are in rural US, where they only have mobile connections, and they might not be on the fancy latest generation laptop, but they might have a laptop that has, I don't know, I've seen the likes of Windows XP or something-- like, it's an older laptop--  

#### [0:31:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1890) |  then this field data wouldn't look as

great. Because A, the data has to travel across the Atlantic and back-- well, actually, it comes from the other side of the Atlantic, it goes back over the Atlantic-- that takes longer. Their connection is probably spotty and slow. That makes everything slower. And then their laptop isn't very fast and fancy. So executing all my JavaScript is very likely also going to be slower. In that case, my lab data looks amazing,  

#### [0:32:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1920) |  and then my field data-- because my

users are sitting in the other end of the world-- looks terrible. That's what happens. Because the lab data is only synthetic. It's only an approximation of what happens in the real world. And then you have field data which, surprisingly, gives you the actual thing that people are experiencing. So if you know that you are serving users on slow, old phones, or on rural, like, spotty internet  

#### [0:32:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1950) |  connections, this is what happens. This is

where the field data looks a lot worse than what you see in lab data. And that's a general problem. Developers usually work with fantastic internet connections on modern laptops. And then the real-world user is on an old iPhone 2 somewhere in rural Northern Germany, where you have edge internet connection, if you are lucky.  

#### [0:33:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=1980) |  And then everything looks terrible for them,

and you're like, I don't understand why our users are complaining that everything is slow. It loads within a second for us. It's like, yeah, for you-- but not for your actual users. So again, field data is probably a better indicator for how real users are experiencing your website than lab data. Because lab data it's literally just someone's server making a request to your thing.  

#### [0:33:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=2010) |  And if that server happens to be

quite beefy, then you get pretty good looking numbers. But then the real world isn't as beefy and nice. All right. Do we have any other questions? AUDIENCE: I've got a quick one, if that's OK, Martin. MARTIN SPLITT: Yeah, sure. AUDIENCE: Yeah. I watched your thing yesterday with Onely about the render SEO. That was quite good. You mentioned that you'll look at the render tree rather than the-- you know, in general. MARTIN SPLITT: Yeah.  

#### [0:34:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=2040) |  AUDIENCE: Is that something most people would

actually need to worry about? And if so, is there something that we can look to from a Google perspective, other than maybe just a screenshot in mobile-friendly test? MARTIN SPLITT: So yeah, that's a good question. So what I said yesterday in the Onely webinar is that we do use the render tree rather than painting the actual pixels. But that's not something that you normally need to worry about, unless there are bigger problems that culminate  

#### [0:34:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=2070) |  in a problem with layouting. Normally, it

is enough to look at the rendered HTML to see if your content is there, if the content roughly looks in a real browser like you would expect it to look like, and then you should be fine. There are very rare cases where everything on a website is so screwed up-- and I literally mean, like, everything is screwed up-- that the layouting becomes an issue that topples over our ability to make guesswork happen. But if Google Search needs to guess things on your website,  

#### [0:35:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=2100) |  like is this the main content? I

don't know, because everything is in one large div, then you are already on a very, very dark path and should definitely backtrack. So normally, you don't have to worry about this. It's an implementation detail. It's quite geeky to begin with. And no one has to understand this or worry about this realistically. AUDIENCE: OK, cool. Thank you. MARTIN SPLITT: Awesome. More questions from the audience?  

#### [0:35:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=2130) |  You can also use the chat. Chat

is perfectly fine. I'm scrolling down-- oh, yeah. Here we go. In Google Search Console, we see this under URL inspection-- crawl page, more info, page resources, 36 out of the 73 couldn't be loaded. Some have a label "other error." How can we debug this error further? Ah, you can't really. That's the unfortunate thing here.  

#### [0:36:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=2160) |  Two things. First thing-- a resource not

loaded isn't per se a problem. It just means that we didn't load it. If you have things like Google Analytics on the page, we are very likely not loading this one because it doesn't really add benefit to our rendering. So a page-- a resource not loaded isn't a problem per se. The other error is the most dreadful possible error, because it means something that you don't really have an option to act on has happened.  

#### [0:36:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=2190) |  And most likely, what happens-- so most

of the time "other error" means we don't want to let you wait for an hour until we actually get a spot to download this resource to our infrastructure, so we're cutting it short here. I know that's not fantastic, but that's the trade-off that we have to do with the testing tools. The indexing infrastructure can afford to just wait for things. We also cache things heavily.  

#### [0:37:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=2220) |  Both of these things are not available

or not feasible in the testing tool. We want to show you the latest thing according to what is on your page. So we are not using caching. So we have to request everything. The way that we are building the testing tools is we are trying to be as close as possible to the actual indexing infrastructure, which means we're using the indexing infrastructure. However, the way the indexing infrastructure is designed is for background batch users. So like, Googlebot basically has infinite amount of time  

#### [0:37:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=2250) |  to wait for things. We can hypothetically

say like, download this thing and then it's OK if that download is only-- like, if this is in a queue for an hour or something, and then it actually gets downloaded, that's fine for indexing, because it doesn't really matter. The rest of the pipeline will run as the download has happened. We can't let you wait an hour in front of the mobile-friendly test until we wait for actually getting this resource. Images are very likely not necessary for the actual rendered HTML to show up correctly.  

#### [0:38:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=2280) |  It's just for the screenshot. So images

are the first to actually get kicked out, really. So as long as its images-- as you say, most of them are-- or some of them are images-- doesn't matter. We are not really downloading the images in indexing either. At least for main web crawling, we don't have to do that, because we are only interested in the URL of the image, really, and the alt text and the context that the image is in, rather than the actual image pixel data. So if that doesn't show up on the screenshot,  

#### [0:38:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=2310) |  that doesn't mean much. As long as

the image URL is correct in the rendered HTML, you're good. All right. On slow connections, I'm getting more blocking time due to AdSense ads. So what can we do? I would ask the ads team. I don't know about AdSense. That's probably something that they allow you to make things faster, but I don't know. So I would ask the AdSense folks for this.  

#### [0:39:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=2340) |  All right. Any other questions? Because I

think we have exhausted our YouTube questions. At least, I'm not seeing any others. No. Answered that. I'm not going to answer that one. Yeah. All right.  

#### [0:39:30](https://www.youtube.com/watch?v=n18nYA2FqrI&t=2370) |  Last chance for questions. 5, 4, 3,

2, 1. All right. If there are no further questions, then I'd like to thank you all for joining the recording. Thank you all for watching this later on YouTube. And thanks for being fantastic. Build cool stuff on the web. And stay safe, stay healthy. Bye-bye.  

#### [0:40:00](https://www.youtube.com/watch?v=n18nYA2FqrI&t=2400) |  Thanks for joining.  

