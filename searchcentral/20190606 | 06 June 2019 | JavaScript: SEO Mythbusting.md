[![JavaScript: SEO Mythbusting](https://i.ytimg.com/vi/EZtCgrpa6ss/hqdefault.jpg)](https://www.youtube.com/watch?v=EZtCgrpa6ss)

## JavaScript: SEO Mythbusting

In this third episode of SEO Mythbusting, Martin Splitt (WebMaster Trends Analyst, Google) and his guest Jamie Alberico (SEO Product Manager, Arrow Electronics) discuss the issues of JavaScript in the context of SEO, such as: 

Where do misconceptions about SEO & JavaScript come from? (0:00)

Is JavaScript the devil :) ? (1:56)

Lazy loading in search (5:11)

Ajax, SEO, and crawl budget (5:36)

Googlebot & JavaScript (8:21)

Is pre-render always the best solution? (10:48)

What are the user benefits of implementing JavaScript SEO well? (12:38)

What should SEOs look for in a website solution stack? (13:33)

Recommended testing tools for JavaScript SEO (15:10)



Documentation mentioned in this episode:

Search-related JavaScript troubleshooter → https://goo.gle/search-js-troubleshooter

Lazy loading in search → https://goo.gle/lazy-loading-in-search

Crawl budget → https://goo.gle/crawl-budget



Next week, look forward to the fourth episode - Web Performance: SEO Mythbusting.



Watch more SEO Mythbusting episodes → https://goo.gle/SEO-Mythbusting 

Subscribe to Google Search Central → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=0) |  MARTIN SPLITT: Coming from a development background,

there are so many misconceptions and myths about SEO that developers come up with or have heard, or that come from the SEO world, as well. Where do these come from? How do these get into the world? JAMIE ALBERICO: The myths, the legends that come through about JavaScript? I think a lot of it is people with very good intentions will try to provide the information they have available. And there's a gap in translation between the SEOs and the developers, and how they think and what they consider.  

#### [0:00:30](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=30) |  So by going ahead and adopting acceptance

criteria as part of my tickets when I work with devs, that lets them know very specifically, instead of being like, and I want you to make magic for me. And when you go from, give me magic, to hey, here's my user story. I would like to accomplish three pieces for acceptance criteria, you can bridge the gap. [MUSIC PLAYING]  

#### [0:01:00](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=60) |  MARTIN SPLITT: Hello, and welcome to another

episode of SEO Mythbusting. With me today is Jamie Alberico. Jamie, what do you do in your job, exactly? JAMIE ALBERICO: Thank you so much for having me here. I'm a Technical SEO with Arrow Electronics. And that means that I am embedded with a number of dev teams across a number of projects. We try to execute these initiatives to get new features available on the site in an effective and search-friendly way.  

#### [0:01:30](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=90) |  And that means a lot of times,

we have to have conversations about how we're using our JavaScript. MARTIN SPLITT: Having you here is fantastic because then we can have a conversation about pretty much everything that you want to know from the search side, as well as the web developer side. So any questions that you have in mind? Anything that pops into your mind? JAMIE ALBERICO: Oh, so many questions. I get to poke at the black box of Google here. And I have one that's absolutely burning. Is JavaScript the devil? MARTIN SPLITT: [LAUGHS] That's a fantastic question.  

#### [0:02:00](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=120) |  It might seem that way sometimes, especially

when things are not going the way you want it. JAMIE ALBERICO: You see the horror stories. They're on forums. They're on Twitter. Everything is gone! MARTIN SPLITT: Yeah, that's one thing, the SEO side. On the developer side it's also like, oh, it's a language that wasn't designed to be super resilient. But it actually is. And then often, people are, oh, it's a C-type language, and it's not really. It's a LISP-type language, so a lot of misconceptions coming from both worlds together and clashing here.  

#### [0:02:30](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=150) |  I don't think it is the devil.

I think it has its benefits. I mean, it allows us to build really cool and fantastic stuff on the web and be really responsive to what the user does and wants to do with our applications. And it has moved the web from being a document platform towards an application platform. And I think that's fantastic. So I think we are already pushing hard on fighting this, JavaScript is the devil, and if you use JavaScript, you can't be indexed at all.  

#### [0:03:00](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=180) |  So that's not true for a long

time. But I think now the documentation is catching up with outlining the different bits and pieces that you should be aware of, and the features that you have to deal with that are not available. One thing, for instance, is you probably have built single-page applications, right? JAMIE ALBERICO: Oh, yes. MARTIN SPLITT: Has there been problems in terms of SEO when they rolled out? JAMIE ALBERICO: I was pretty lucky. I had a dev team who believed in SEO. MARTIN SPLITT: That's good. Oh, fantastic. JAMIE ALBERICO: That's really good.  

#### [0:03:30](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=210) |  That was actually my-- the big moment

of my career, when I got into technical SEO. And I came, and I talked to one of my new developers for the first time with this very specific problem he was trying to solve. And he just paused and looked up from his keyboard and went, [GASPS] you're not snake oil. So I think we're making a lot of progress between SEOs and devs. MARTIN SPLITT: That is fantastic. That's a great story. So you might hear a few people in the community going, ooh, should we do a single-page application? Is that risky? And one of the things that a bunch of developers  

![](https://i.ytimg.com/vi/EZtCgrpa6ss/hq1.jpg)



#### [0:04:00](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=240) |  are not aware of and some SEOs

are not necessarily communicating all the time is that we are stateless. So that means with a single-page application, you have a bit of an "application state," right? You know which page you're looking at and how you transition between these pages. However, when a Search user clicks on a Search result, they're not having this application state. They're jumping in right to the page that we indexed. So we only index pages that can be jumped right into. So a lot of the technology, the JavaScript technology is making assumptions of how the user navigates  

#### [0:04:30](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=270) |  through the application. So as a developer,

I might test, so OK, here's my application. I click on the main navigation for this particular page. And then I click on this product, and then I see that everything works. But that might not do the trick because-- JAMIE ALBERICO: But you need that unique URL. It has to be something we can get to. MARTIN SPLITT: Correct, not using a hashed URL. And also, the server needs to be able to serve that right away. If I do this journey and then basically take this URL and copy and paste it into an incognito browser.  

#### [0:05:00](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=300) |  I want people to see the content,

not the home page and not a 404 page. So that's something that we're working on giving more guidance for. Lazy loading, you probably have seen a bunch of communication about that one, as well. JAMIE ALBERICO: Oh, yes. How do we get a rich media experience out to users, but do it in a way where, if you're on your cell phone, we keep that very small time frame we have to get your attention? MARTIN SPLITT: Mhm, correct. And you want to make sure that if you have a long list of content, you don't bring everything  

#### [0:05:30](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=330) |  into the-- especially on a cell phone,

right, just dealing with like, a hundreds images. Ugh. JAMIE ALBERICO: So what about AJAX? What about using Asynchronous JavaScript And XML? MARTIN SPLITT: Right, that is perfect-- ooh, I haven't heard AJAX being used in a while and spelled out in a while. I mean, everyone's-- JAMIE ALBERICO: Well, I think a lot of-- MARTIN SPLITT: Everyone's using it, but no one's talking about it that much. And it was just like, yeah, you just load data in as you go. That's perfectly fine. We are able to do that. Also, I often get asked about how that affects the crawl--  

#### [0:06:00](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=360) |  JAMIE ALBERICO: Crawl budgets. MARTIN SPLITT: I

knew you that you would still say that. JAMIE ALBERICO: Crawl budget. Let's talk. MARTIN SPLITT: So what worries you about that? JAMIE ALBERICO: Well, if we're using AJAX, when we request, say, a product detail page, and we're using AJAX to supplement a lot of pieces of content to it. Google bots requested one URL, and it's gotten back nine, because each of those AJAX calls had a unique string. How do we handle that? And does it negatively impact our crawl budget? MARTIN SPLITT: So, I wouldn't say it negatively impacts your crawl budget, because crawl budget is much more complex than you might see.  

#### [0:06:30](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=390) |  It's one of these things that looks

super simple, but there's more than meets the eye. We're doing a bunch of caching, right? Because we expect that content doesn't necessarily update too much. So let's say you have this product page. You make one request to the product page. And then that makes nine more requests. We don't distinct between loading the CSS or the JavaScript, or the images, or the API calls that get you the product details. So if you have nine calls from this one page load,  

#### [0:07:00](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=420) |  then that's going to be ten in

the crawl budget. But because of caching, we might have some of these in the cache already. So if we have something that is already cached, that doesn't count towards your crawl budget. JAMIE ALBERICO: So if we were to version our AJAX calls, those could be cached instead of called every time. MARTIN SPLITT: Those could be cached. Exactly, yes. And then that's one way of working around it, if you can do that, if that's a possibility. The other thing is you could also consider it not just an issue for the crawl budget,  

#### [0:07:30](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=450) |  but also an issue for the user,

right? Because if you're on a slow network or a spotty network connection, it might flake out in the middle. And then you are left with broken content. That's not a great user experience. You want to probably think about pre-rendering, or hybrid rendering, or server-side rendering anything in between there. And crawl budget is tricky generally because we're trying to deal with the host load situation, so what can your service actually deal with. So we are constantly adjusting that anyway. So it's like, oh, this affected our crawl budget negatively.  

![](https://i.ytimg.com/vi/EZtCgrpa6ss/hq2.jpg)



#### [0:08:00](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=480) |  Not really, because we just had host

load issues with your service, so we adjusted it anyways. So we had balancing issues across your entire content. So I wouldn't say that it's that much of a deal, normally speaking. But I see that it's very important for people to understand that. And unfortunately, that's not that easy. JAMIE ALBERICO: Can we demystify Googlebot a little bit? MARTIN SPLITT: Oh, yeah. JAMIE ALBERICO: Because we have this-- the ominous, the great, Googlebot! But it actually goes through a series of actions.  

#### [0:08:30](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=510) |  So we get that initial HTML parse.

We find the JavaScript and CSS that we need to go ahead to make our content, then call those pieces. We know since Google I/O, there is actually a gap between our initial parse and our HTML rendering. But I want to know more, because Googlebot follows HTML/HTML5 protocols. There are some nuances there I don't think-- I know I didn't know about. Say you've got an iframe in your head, and you've got a closing head script right there.  

#### [0:09:00](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=540) |  That ends your head for Googlebot, and

all of our lovely meta content, hreflangs and canonicals below that, have a tendency to exist. MARTIN SPLITT: [LAUGHS] That is true. There's a bunch of things at play. So when we say Googlebot, what we actually mean on the other side of the curtain is a lot of moving parts. So there's the crawling bit that literally takes in URLs, right, and then fetches them from the server, so that when you are providing the content to us,  

#### [0:09:30](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=570) |  we get the raw HTML. That tells

us about the CSS, the JavaScript, and the images that we need to get, and also the links in the initial HTML. And because we have that already, we have such a wealth of information already, we can then start to go off and fetch the JavaScript and everything that we need to render later on. But we can also already use the HTML that we've got and say, like, oh, look. There's links in here that need to be crawled. So when you have links in your initial HTML, we can go off and basically start the same process  

#### [0:10:00](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=600) |  for these URLs as well. So a

lot of things happen in parallel rather than just one step and then the next step and then the next step. So this is definitely the start of it. And as we get the HTML, in parallel to extracting the links and then crawling these, we queue them for rendering. So we can't index before we have rendered it, because a bunch of content needs to be rendered first. JAMIE ALBERICO: But in a way, that benefits us. If we've got a single-page application, Googlebot has the template. They've just got to grab the content that fits within there.  

#### [0:10:30](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=630) |  So wouldn't that mean that Googlebot likes

these JavaScript platforms? MARTIN SPLITT: It'd probably like that. The more content you get us quickly in the first step, in the crawling step, the better it is, because we can then basically carry that information over, rather than having to wait for the rendering to happen. JAMIE ALBERICO: But is pre-render always the best solution? MARTIN SPLITT: That's a tricky one. I think most of the time, it is, because it has benefits for the user on top of just the crawlers. But you have to very carefully measure what you doing there,  

#### [0:11:00](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=660) |  I think. So giving more content over

is always a great thing. That doesn't mean that you should always give us a page with a bazillion images right away, because that's just not going to be good for the users because they're going to have to then-- If you're on a really old phone-- and I have a pretty old phone-- and you have a page that is full of images and transitions and stuff, then you're like, I can't use this website. So pre-rendering is not always a great idea. It should be always a mix between getting  

#### [0:11:30](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=690) |  as much crucial content in as possible,

but then figuring out which content you can load lazily in the end of it. JAMIE ALBERICO: So for SEOs, that would be-- we know that different queries have different intents, informational, transactional. So elements critical to that intent should really be in that initial parse. MARTIN SPLITT: Yes, exactly. And you might consider, if the intents are wildly different, and the content is very, very different, consider making it into multiple pages, or at least multiple views if you're using a single-page application, so that you have an entry  

#### [0:12:00](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=720) |  point for the crawler to specifically point

at it when it comes to surfacing the search results. JAMIE ALBERICO: So treat it like a hub, and let the users branch out from there. MARTIN SPLITT: Mhm, yes. JAMIE ALBERICO: So that's where we'd use maybe our CSS toggle for visibility. MARTIN SPLITT: That is a possibility. Just having different URLs is always an option. Especially with the History API, you can probably, in the single-page application, figure out which route to display, and then have the content separated between different routes. So it would be a little more dynamic.  

![](https://i.ytimg.com/vi/EZtCgrpa6ss/hq3.jpg)



#### [0:12:30](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=750) |  And we support parameters. So even if

you use URL parameters, basically expose the state that is relevant to the user in the URL. JAMIE ALBERICO: What other ways does that benefit our users? Because our ultimate goal is to make them happy. MARTIN SPLITT: Yeah, and that's our ultimate-- so we are the same in terms of what our goal is. We both want to surface useful information to the user as quickly as possible. So the user's benefits are, especially if you do hybrid rendering or the server-side rendering, that they get the content really quick, normally,  

#### [0:13:00](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=780) |  if it's done well, if it's not

overloading their device. And they get to jump in right where the meaty bits are, right? So if I'm looking for some specific thing, and you give me a URL that I can use to go to that specific thing, I'm right there, and I'll have a great time because it's the content that I needed. So yeah, if you have performance metrics going up as well, then even if I'm on a slow phone or a really spotty network, I still get there. JAMIE ALBERICO: I mean, our performance metrics, that's based on a lot of pieces.  

#### [0:13:30](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=810) |  We have a stack of technology. MARTIN

SPLITT: That is true. JAMIE ALBERICO: What should SEOs look for in our stack? Where should we try to identify those areas where we could have a better experience for not just Googlebot, but our humans? MARTIN SPLITT: Yeah, so I think a bit that is oftentimes overlooked, not by SEOs but by businesses and developers, is the content part. So you want to make sure that the content is what the users need and want, and it's written in a way that helps them. But on the technology side-- JAMIE ALBERICO: Wait, so that blurb at the top people always do where they're like, here's my hero image and then  

#### [0:14:00](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=840) |  500 words about this thing-- and I'm

a human who wants to buy something. And there's so much stuff in the way. MARTIN SPLITT: Yeah, don't do it. JAMIE ALBERICO: Don't-- [LAUGHTER] MARTIN SPLITT: Or at least have two pages. Have the promotional page that you want to direct marketing towards. And then if I specifically look for your product, just give me your product. JAMIE ALBERICO: Just let me give you money. MARTIN SPLITT: So I think talking about performance and all the different metrics, it's a bit of a blend of all the things. Look at, when does my content actually arrive?  

#### [0:14:30](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=870) |  When does my page become responsive? So

you look at first contentful paint. You look at time to first byte as well-- less important than the first contentful paint, I would say, because it's fine if it takes a little longer if then the content is all there, versus-- JAMIE ALBERICO: So time to first byte can take a bit of a hit if we deliver that faster first meaningful paint. MARTIN SPLITT: Exactly, because in the end as a user, I don't care about if the first byte has arrived quicker if I'm still looking at a blank page because JavaScript is executing or something is blocking a resource.  

#### [0:15:00](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=900) |  If it arrives a little later, but

then it's right there, that's fantastic, right? And you can get there in multiple ways. I highly recommend testing, testing, testing, testing. JAMIE ALBERICO: What testing tools would you recommend? MARTIN SPLITT: So I definitely recommend Lighthouse. That's a great way. [? Wepend ?] is a more broad approach as well. And you could also use PageSpeed Insights or the new SEO audits in Lighthouse. Mobile-Friendly Test also gives you a bunch of information of how-- JAMIE ALBERICO: PageSpeed Insights  

#### [0:15:30](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=930) |  seems to look at that full page,

though. And we have a bit of a gap. We have almost this futurist Lighthouse where we want that time to interactive. And then we have people adopt this methodology, and that's how we got so much content via AJAX, because full page load is fast. But all that content was still coming. MARTIN SPLITT: So I would recommend Lighthouse. That gives you the filmstrip view of when things are actually ready for the user to work with. So I would highly recommend looking at Lighthouse. But PageSpeed Insight gives you good first view, and it integrates with Lighthouse really nicely now.  

#### [0:16:00](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=960) |  JAMIE ALBERICO: Wonderful. MARTIN SPLITT: Do you

think that JavaScript and SEO can be friends now, and that developers and SEOs can also work together? JAMIE ALBERICO: I do. I really think that if Google is a library and a web page is a book, using these JavaScript frameworks let us make pop-up books and rich experiences to engage with. MARTIN SPLITT: Oh, that's a fantastic analogy. I love that image. That's a beautiful one. Thank you so much, Jamie-- JAMIE ALBERICO: Thank you very much. MARTIN SPLITT: --for being here. And I hope you enjoyed it, and see you next time.  

#### [0:16:30](https://www.youtube.com/watch?v=EZtCgrpa6ss&t=990) |  Have you ever wondered where on the

map you should put UX and performance when you're talking about SEO? So have I. Let's find out in the next SEO Mythbusting episode.  