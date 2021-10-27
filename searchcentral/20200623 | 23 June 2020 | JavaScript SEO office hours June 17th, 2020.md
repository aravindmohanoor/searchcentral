[![JavaScript SEO office hours June 17th, 2020](https://i.ytimg.com/vi/XsNTFqy8uFs/maxresdefault.jpg)](https://www.youtube.com/watch?v=XsNTFqy8uFs)

## JavaScript SEO office hours June 17th, 2020

This is a recording of the JavaScript SEO office-hours hangout from June 17th, 2020. These sessions are open to anything around SEO for JavaScript sites.



Watch out for new sessions, and add your questions at https://youtube.com/googlewebmasters/community



#### [0:00:00](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=0) |  MARTIN SPLITT: Hello, and welcome to the

JavaScript SEO Office Hours. Today is June 17. And I see that we have a few YouTube questions. Besides Dave, one else joined the Hangout recording today, so far. Oh, no, as I speak, here is Pedro joining-- or not joining us. I don't know. Yeah, yeah, here we go. Hi, Pedro, you're on air now. I just started the recording. PEDRO DIAS: Hi, there. MARTIN SPLITT: I'll edit this part out, no worries.  

#### [0:00:30](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=30) |  I'll edit this part out. All right,

so assuming that we just-- how are you doing? PEDRO DIAS: I just came to say hi. I am doing good. MARTIN SPLITT: Oh, OK, that's good then. Sweet. So I'll officially start the recording now. I mean, I started it, but I'll just retake the intro. Hello, and welcome to JavaScript SEO Office Hours on June 17, 2020. Great to have you watching this video, or joining this recording, or asking questions on YouTube.  

#### [0:01:00](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=60) |  We have a few YouTube questions today

that I'll go through. Then I'll give the audience an opportunity to ask their questions, and then you will have the chance to submit questions for the future JavaScript SEO Office Hours on YouTube. Sweet. So our first question is a ReactJS question. They got two different home page SEO on the Google-- on the page Google Cloud. Uh-huh OK.  

#### [0:01:30](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=90) |  I'm guessing that they mean, like meta

tags or something. I'm not sure. One is Index HTML, and the other one is the Helmet Component. Well, the Helmet Component is probably part of what gets rendered for that. All right, let's see. How is it possible? I have checked out-- right, I have checked with a tool, some sort of tool, I have not heard about the tool beforehand. So they used a tool. And the tool gives a grade of 0, and says content is not available. Then, that's not a good tool, I would guess.  

#### [0:02:00](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=120) |  So I would say don't use tools

that don't reflect the real thing. I would always recommend using the tools that we provide, because they show you the rendered HTML as it comes out of our actual indexing and rendering pipeline. So if we see them in the testing tools, then that should be fine. Now, they posted the website that they have. I'm not going to pull it up on screen. But I had a look, and they do have the meta description and a few other meta tags twice.  

#### [0:02:30](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=150) |  I would assume that you have to

put it in the actual index HTML file, but then React, as it renders the page, creates its own set of these tags. So I would suggest that you either remove them from the index HTML and rely on React Helmet to render these tax specifically on the components that get rendered. Talk to your developer. If you're not sure what happens there, talk to your developer. But very likely you want to remove the ones in the index  

#### [0:03:00](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=180) |  HTML, because they are not specific to

the content that is on the page, or React if you are using client side rendering with React. Then, we have a second question-- "does the CSS and JavaScript formatting of a website affect SEO?" Not sure what you mean by the CSS and JavaScript formatting. But generally speaking, use the testing tools, look into the rendered HTML, the thing that we see there that's what we actually care about.  

#### [0:03:30](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=210) |  So if you feel like I'm not

answering the actual question, try to give me more details for the next Hangout so that I can answer your question better. And we have a navigation related question. And I think that is the second to last question that I'll have today. And then, the audience gets their turn to ask questions on top of it. "A large website has a three-level flair out menu--" three level?  

#### [0:04:00](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=240) |  Wow, OK, fair enough. "Second level links

are provided in code as a href links." Good. "Third level links are loaded by a JSON file when hovering with a mouse." Aha. Right. "Do I understand it correctly that the third level links, which are packed in JSON file, are not provided and will be ignored and not crawled if they're not linked elsewhere?" Yes. Anything that isn't in the HTML as we render it--  

#### [0:04:30](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=270) |  so you can use the rendered HTML

that is produced by all the testing tools, for instance, like Mobile-Friendly Test, Switch Results Test, Google Search Console, your Inspection Tool. Anything that isn't there as a link, we're not going to see it. Especially if there's a user gesture involved, it's not going to happen. Last question. "When Google is crawling URLs on the sites, like a certain example, with the only references to something like that in rendered code being associated with a form--" so there's a form that has a form action,  

![](https://i.ytimg.com/vi/XsNTFqy8uFs/maxres1.jpg)



#### [0:05:00](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=300) |  and that's where these URLs show up.

"--Google crawls these URLs and gets a 404 error. Why would that happen?" Without a specific example site to look into, many options come to mind. It might be in the site map. It might be that there is some other website out there linking to these things. It is possible that somehow we get JavaScript that submits  

#### [0:05:30](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=330) |  these forms or something. Things can definitely

happen. It can also be that we think, like, well, maybe there is interesting content behind this form. I don't think we do that, but I don't know. So I'd rather not speculate on that. But, basically, if it's a 404 URL, then that doesn't really hurt you unless you are running into very specific problems with units. If you're not having a problem, you shouldn't really worry about it much. If you want us to not crawl these URLs, then you can also block them via robots.txt.  

#### [0:06:00](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=360) |  That's also an option. Then we won't

crawl them anymore. But generally speaking, if it's a 404, I don't see that as a problem. There's nothing, then, for us to index. And besides maybe crawl budget if your side has millions of pages, that shouldn't be a problem. Awesome. Sweet. With that, I hope that was helpful for those who posted questions on YouTube. If not, feel free to post follow-up questions  

#### [0:06:30](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=390) |  for the next thread. And now I'll

open it up to the audience. Anyone with questions in the audience they would like to ask? Hi, Shao. SHAO CHIEH LO: Hi, Marty, how are you? I have a follow-up question. I think one of the YouTube questions touched base on that a little bit about the CSS and JavaScript. I remember several weeks ago I asked you if we blocked CSS and JavaScript if it's a problem or not. You say, no, it's not going to be floating. But in some cases, we let them crawl,  

#### [0:07:00](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=420) |  but sometime we return robot noindex, and

sometimes we don't let them crawl then. Even if textual content itself still doesn't change, they do change some user experience and some functionality of JavaScript sometimes. Do they be beneficial? I mean, if you don't like Google crawling, then it's not considered cloaking. But if we let Google crawl and are letting indexing,  

#### [0:07:30](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=450) |  is it beneficial to help Google better

understand and in turn beneficial for SEO? MARTIN SPLITT: So if you're giving us a noindex, then that doesn't mean that we can't crawl them. So we would still crawl them. We would just not put them in the index. But I don't think we would put them in the index in the first place. So that's already a little bit of an edge case. When you block us from running JavaScript and CSS, then you are running into a situation that can potentially  

#### [0:08:00](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=480) |  be problematic. For one, if there is

content that somehow gets generated from running some JavaScript, then we are not going to see that content. It can also be that-- as you say, if you have user experience improvements, such as lazy loading that isn't using native lazy loading, but you have some JavaScript library that does this correctly, then we might not see the image URLs, unless you use the NoScript work around. So I would not block Googlebot from using and crawling  

#### [0:08:30](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=510) |  the JavaScript and CSS files. SHAO CHIEH

LO: From what you said, you say that Google don't index CSS or JavaScript? MARTIN SPLITT: Mmhmm. SHAO CHIEH LO: They don't? So how do they know-- how does Google know what's happening on the page? MARTIN SPLITT: Yes, so I think what might be the problem here is a misunderstanding of what is crawling, and what is indexing,  

#### [0:09:00](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=540) |  and what is rendering. These are three

different, distinct things. When we crawl, crawling just means we make an HTTP request and fetch the result back. If you use robots.txt and say it just allow crawl, that means we can't make this HTTP request. That is a problem, because then we can execute the JavaScript because we can't download the JavaScript, right? That's one thing. That's crawling. Then, we render, which means we take the crawled JavaScript and run it in the browser.  

#### [0:09:30](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=570) |  And then, whatever content that produces on

the page that includes that JavaScript can be put in the index. And that's the third stage, where we say, here is content that we want to potentially show to a user, so we put it in our database, so to speak. Normally, JavaScript does not have interesting content for us to show to a user, because it's not really a website. It is just an asset to another website. So we would index the website that uses the JavaScript, but not the JavaScript file itself.  

![](https://i.ytimg.com/vi/XsNTFqy8uFs/maxres2.jpg)



#### [0:10:00](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=600) |  So we wouldn't put like application.js in

the index, because that's not something that we would ever want to show to a user. We would crawl it. We would render it, but we would not index it. SHAO CHIEH LO: So the robot noindex HTTP header on JS or CSS is meaningless in the first place? Oh, because Google don't do it in the first place. MARTIN SPLITT: Pretty much, yeah. There are certain situations where somehow, sometimes, we get it wrong and then put something in the index,  

#### [0:10:30](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=630) |  and then you can remove it from

the index using that. But it's very, very rare that that happens. SHAO CHIEH LO: So Google don't index the HTML file itself in that, in Google-- MARTIN SPLITT: The HTML file, yes. The JavaScript file, no. SHAO CHIEH LO: So when Google indexing a page, it's indexing the DOM, rendered DOM, or the HTML. MARTIN SPLITT: Well, the rendered DOM is pretty much what gets-- and also not even that. So it is even more complicated. So, basically, what happens when we index is we take the URL  

#### [0:11:00](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=660) |  that we are getting from wherever-- a

link, site map, whatever-- and then we index a bunch of information about the content on the page. And the information on the content in the page comes from the rendered DOM. But it isn't exactly the rendered DOM. SHAO CHIEH LO: I see. Another thing that I found kind of interesting is that I realized some pages is blocked by robots.txt. But some URL that redirect to that page is not blocked.  

#### [0:11:30](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=690) |  And Google sometimes don't rank those URLs

that redirect to the blog page. So Google knows that that URL is redirected to that page, and they can see the page that's being blocked but being redirected to. MARTIN SPLITT: Wait. So you have a page, A, that redirects to page B, and page A is blocked by robots.txt, or? SHAO CHIEH LO: B is blocked by robots.txt.  

#### [0:12:00](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=720) |  So do-- MARTIN SPLITT: Right. SHAO CHIEH

LO: Then, Google rank page A very highly, which indicates that Google actually knows that page A redirects to page B, and they consider the content of the page B, because they can see that? MARTIN SPLITT: I would not expect that to be the case. But it is possible that if page A gets enough positive signals  

#### [0:12:30](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=750) |  from elsewhere-- so if it's linked from

a lot of places, and just generally like seems to be useful for whatever reason-- I don't know where the signals come from. But if it looks like this might be a good candidate to show, then we could show it, even though it is just a redirection to a page that we can't crawl. Also, actually, we sometimes index pages that we can't crawl. Even though we don't know what is on there, we might get the information of what might be on there from the context of which it is linked.  

#### [0:13:00](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=780) |  SHAO CHIEH LO: So in this case,

you would say that we shouldn't block page B in the first place if page B is important? MARTIN SPLITT: If you care about page B, you shouldn't block it, yes. SHAO CHIEH LO: OK. Go back to the JavaScript thing, sorry. Sorry, I just have-- MARTIN SPLITT: No worries. SHAO CHIEH LO: I wanted to finish that up. You say that if they have contextual problem, it's a problem. But if they say there is no contextual problem, no textual change from JS or CSS.  

#### [0:13:30](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=810) |  It's just user experience. And I am

under impression that Google take user experience into account, especially for some more interactive page. In this case, JavaScript will be relevant to-- JavaScript and CSS will be relevant to SEO. In this case, if we block JS and CSS that serve inferior user experience, will that hurt our SEO? MARTIN SPLITT: Yeah. SHAO CHIEH LO: OK, thank you.  

#### [0:14:00](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=840) |  MARTIN SPLITT: You're welcome. Awesome. Good questions.

I like good questions. Do we have another question from the audience? DAVE SMART: I'd like to ask one if that's OK. MARTIN SPLITT: Sure. DAVE SMART: Is there any way to reset the Performance Observer between routes? So if you've got an SPA site or something like an outside [INAUDIBLE],, it begins collecting on the first page you hit. But then, you go to a different route, you go to a different page, and it's kind of, then, the sum of two because it is one page.  

#### [0:14:30](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=870) |  Is there some kind of method that

you can reset between the two so you're getting the proper CLS, the LCP, et cetera, data from that page? MARTIN SPLITT: I don't think you get an opportunity to reset it. That's a really, really interesting question. And I wonder how we would go about that, because, technically, the browser-- in a single-page application, the browser might not know that there is effectively a navigation  

![](https://i.ytimg.com/vi/XsNTFqy8uFs/maxres3.jpg)



#### [0:15:00](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=900) |  happening. So I don't think there is

a way to measure that. You can probably-- no, you can't even use any other APIs or metrics. DAVE SMART: Hmm, I mean the scruffy thing is just, kind of, time stamp it, and take it from there, and reassess it. MARTIN SPLITT: Yeah, that would be an opportunity, yeah. I think you can also use-- I think there's, like-- I think it's called the User Timing API that you can possibly use to build your own.  

#### [0:15:30](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=930) |  But I'm not sure how well that

would work. Yeah, there's like performance.mark that allows you to set marks on the timeline, so you could maybe use that. Yeah, there is no ready-made, easy solution for this, it seems. DAVE SMART: Excellent. Do you know if that rolls back into CrUX state when sent through, or do they-- MARTIN SPLITT: Not sure. Not sure. I'm not familiar with how CrUX gathers its information, its telemetry.  

#### [0:16:00](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=960) |  Good question. Don't know. I'm wondering if

there's anywhere where you could bring this up. I'm pretty sure there's-- the standard has-- not sure if the standard is, like, finalized. I think the standard is still pretty much in flux for Performance Observer. So this might be a question that would be good to take into the standards body, which probably is literally just a GitHub discussion for this, yeah. The spec is on GitHub. And if you have questions for the spec,  

#### [0:16:30](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=990) |  then probably literally opening an issue on

GitHub is a good way-- it's very likely a good way to get a feeling for what they think about this, because I'm not sure if anyone ever thought about this. So I'll post the link to the GitHub repository where that spec is being worked on. Good question. Thank you very much, Dave. All right, I think we have time for one or two more questions. Anyone in the audience?  

#### [0:17:00](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=1020) |  Now is your opportunity to ask. No

more questions? OK. So I think-- let me reload the YouTube thread, not to miss a question. Sometimes we get a few late birds. Oh, yeah, there are late birds I think.  

#### [0:17:30](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=1050) |  There's now nine comments before, and it

has been less. "We're updating our website to a responsive design and possibly incorporating headless e-commerce. What are the main considerations that should be taken into account from an SEO JavaScript perspective?" That the Google crawler can still see your content. You can test that with all the testing tools, look at the rendered HTML. I sound a little bit like a broken record, but that's more or less what you should always do. And surprising amounts of people don't do that.  

#### [0:18:00](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=1080) |  So definitely check for the rendered HTML.

Oh, OK. Come join the Hangout. But someone just joined. So I'm not sure. I hope that this isn't, like, a random thing, because I heard that Hangout apparently sometimes kicks out more than six people. But we were eight at some point. Now we are seven. I hope that this isn't a larger problem. But sorry, Clint, that you couldn't join. I hope I answered your question reasonably well.  

#### [0:18:30](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=1110) |  The biggest concern of the day is

making sure that your content shows up in the rendered HTML. That's the biggest concern. "I have an a href link to navigate to my website." Good. "But when you click on the link, the unclicked code prevents the default action, so the href is actually ignored. And the unclick updates the content on the current page. Is that considered cloaking?" No, unless the content is very different from what you would expect to get. And yes, we would still consider this to be a link.  

#### [0:19:00](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=1140) |  Unless, again, you're misleading the user and

you're doing weird stuff, having an unclick handler that overrides what the href would do is not a problem. OK. Anyone in the audience? Last question? Last opportunity to ask a question.  

#### [0:19:30](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=1170) |  No questions? OK. There are no further

questions. Thank you very much for joining the Hangout. And thank you very much for posting all your questions on YouTube. I hope this was helpful. Let me know if you have further questions. I will post to the YouTube channel a new thread for next week's JavaScript SEO Office Hours. You can always ping me on Twitter as well. And have a great time.  

#### [0:20:00](https://www.youtube.com/watch?v=XsNTFqy8uFs&t=1200) |  Stay safe. Take care. Thanks a lot

for watching. Bye.  