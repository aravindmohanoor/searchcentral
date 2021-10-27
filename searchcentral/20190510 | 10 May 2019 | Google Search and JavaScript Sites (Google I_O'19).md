[![Google Search and JavaScript Sites (Google I_O'19)](https://i.ytimg.com/vi/Ey0N1Ry0BPM/maxresdefault.jpg)](https://www.youtube.com/watch?v=Ey0N1Ry0BPM)

## Google Search and JavaScript Sites (Google I_O'19)

Learn how Googlebot crawls and renders your website so your content can be discovered via Google Search through an optimized user experience. This session will cover architectural best practices (e.g. how to implement lazy loading), framework-specific (React, Vue, Angular) techniques for building Search friendly apps, and review various tools and reports (e.g. Search Console, LightHouse) to bring this to life.



Watch more #io19 here: 

Web at Google I/O 2019 Playlist → https://goo.gle/2vIoGnb

Google I/O 2019 All Sessions Playlist → https://goo.gle/io19allsessions 

Learn more on the I/O Website → https://google.com/io



Subscribe to Google Search Central → https://goo.gle/SearchCentral

Get started at → https://www.google.com/webmasters



Speaker(s): Martin Splitt, Zoe Clifford



TDA7CA event: Google I/O 2019; re_ty: Publish; product: Search Console - General; fullname: Martin Splitt, Zoe Clifford;



#### [0:00:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=0) |  [MUSIC PLAYING] MARTIN SPLITT: It's great that

we have you all here, and that you all gathered today to learn more about JavaScript and Search. And the coolest thing is, today, I have the pleasure of not just being the only one presenting this, but I have Zoe with me, who is working on the rendering team. So she is-- yes, she's the one from the team that made the new Googlebot happen, so please cheer and give another round of applause. ZOE CLIFFORD: Oh, well, it was a team effort, Martin,  

#### [0:00:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=30) |  but thank you. And it's great to

be here. Martin, I know you've done some work around JavaScript and Search. I'd love to discuss with you, if you have some time. MARTIN SPLITT: Actually, I have 40 minutes until I have to do the next thing, so let's talk a bit about it. But before, I would like to go into something else. I talk to SEOs, and I talk to developers all around the world, and it's great to do that. But I keep getting this sentiment, especially  

#### [0:01:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=60) |  from SEOs, that JavaScript is the worst

thing ever, and it's the new Flash, and it's evil, and you can't have a successful website if you're using JavaScript. ZOE CLIFFORD: Oh, my gosh, Martin, that sounds a little bit extreme. I think both developers and SEOs should work together to make sure their web content works well. JavaScript is a tool, and it can be used to make great web sites. But every tool can be used incorrectly and do harm.  

#### [0:01:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=90) |  MARTIN SPLITT: That is absolutely true, and

I that's such an important point to drive home. I mean, it is an essential part of the web. It is what enables so many new capabilities on the web. At the same time, if you use it incorrectly, or if you overuse it, that's a very, very bad thing. And I mean, we see that with things like this. You see the graph from HTTP Archive? We see that the amount of JavaScript that we are shipping to users loading our pages is growing and growing and growing over the year.  

#### [0:02:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=120) |  So what I'm wondering is, with JavaScript

being an essential part, and a good tool if used right, but JavaScript being so much in use, how does Google Search deal with that? ZOE CLIFFORD: Well, we keep improving Google Search for JavaScript sites. At the same time, we make sure we keep crawling and indexing efficiently. MARTIN SPLITT: That sounds very nice and airy, but do you have any examples for that? ZOE CLIFFORD: Oh, yes. So let's start with the big news.  

#### [0:02:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=150) |  You know Googlebot used to render pages

with the engine from Chrome 41, right? MARTIN SPLITT: Ah, yes, the number one question I got, and the number one question I asked you over and over again-- it was like, hi, Zoe, long time no see. So Googlebot update, no Chrome? So we're getting this update? ZOE CLIFFORD: Yes. Actually, we already got the update a couple days ago. MARTIN SPLITT: Yes! AUDIENCE: Woo! MARTIN SPLITT: Woo! So this means we haven't just updated it,  

#### [0:03:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=180) |  and we will start crawling your sites

with it. We are already doing that. ZOE CLIFFORD: Yes, that's correct. MARTIN SPLITT: So I somehow nearly missed the announcement on Tuesday. That was a little weird, but I think this is fantastic, and this is amazing. And just to make sure to get that absolutely right, this is the latest stable Chrome rendering engine? ZOE CLIFFORD: Absolutely. MARTIN SPLITT: Cool. So that is good news, but what I'm wondering is,  

#### [0:03:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=210) |  what does that mean for me as

a web developer? ZOE CLIFFORD: Well, it gives you access to over 1,000 new features that is now available to Googlebot when rendering pages. MARTIN SPLITT: That's really, really cool. I mean, that's not 1,000, but if you look around, you'll see that there's tons of new stuff. So that's great. So we have a modern web rendering service in Googlebot. That's lovely. But I have another question. Do you know what my next question's going to be like?  

#### [0:04:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=240) |  ZOE CLIFFORD: Oh, your next question? Are

you wondering if we'll get four years out of date again? MARTIN SPLITT: Yeah. When do we get the next update? ZOE CLIFFORD: Actually, we'll update the render engine regularly, so we'll be more or less around the same as desktop Chrome, give or take a few weeks. MARTIN SPLITT: A few weeks? ZOE CLIFFORD: Something like that. We're not making any promises, but that's the idea.  

#### [0:04:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=270) |  MARTIN SPLITT: A few weeks. That's amazing.

I love that. That's really big news. All right, let me get that straight. So modern JavaScript is no longer a blocker for SEO. Absolutely, yes. ZOE CLIFFORD: Yes. MARTIN SPLITT: And what kind of new features are these? ZOE CLIFFORD: Well, you can use pretty much any modern JavaScript feature, including Let, Const, a whole bunch a new array methods,  

#### [0:05:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=300) |  and so on and so forth. MARTIN

SPLITT: But that's the JavaScript language features. What about new APIs? ZOE CLIFFORD: Yes, many of those are available, too, like Intersection Observer. MARTIN SPLITT: Yes, I hoped for that one. So that's a fantastic news, and that probably also means, if we have more of the APIs available in the browser, that I don't leave as many polyfills as I used to. ZOE CLIFFORD: Right, right. You should still consider providing polyfills for older browsers, but if you have a polyfill that  

#### [0:05:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=330) |  exists purely for Googlebot compatibility, you can

remove them. MARTIN SPLITT: Yes! So I think one of these examples would be-- I know that one of the JavaScript frameworks shipped polyfill for every .fill as an optional thing for Googlebot. We can-- ZOE CLIFFORD: Yeah. MARTIN SPLITT: That is amazing. That's great, and these ongoing updates will probably also mean that we update the user agent eventually. ZOE CLIFFORD: Yes, eventually, we'll update the user agent string to reflect the version of Chrome  

#### [0:06:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=360) |  that we're running. MARTIN SPLITT: That's cool.

So right now, we're telling people 41 because we don't want to break sites that have precoded, hardcoded, but we'll do that update eventually. That's great. That's amazing. So what else will the future hold, speaking of the future? ZOE CLIFFORD: What else will the future hold? We're going to update the testing tools, too. We didn't get around to updating many of them yet, but look forward to that in the coming months for them  

#### [0:06:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=390) |  to run Chrome as well. MARTIN SPLITT:

Right, so unfortunately that means-- so we wanted to make sure that we get you this upgrade as quickly as possible. But that means that you might have some rockiness keenness on the way. But look at it from a different perspective. This means that if the testing tools we provide you with, like mobile-friendly tests and URL inspection tool, if they say it's fine, it will definitely be fine. If you get JavaScript errors, you still have a chance to actually make it into indexing. But you have to double-check things.  

#### [0:07:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=420) |  And I think that's OK. ZOE CLIFFORD:

Yeah. MARTIN SPLITT: You're working on that? ZOE CLIFFORD: Yeah we're working on it. Sorry for the glitches in the meanwhile. MARTIN SPLITT: Things like that happen. I mean, there was a huge update. You worked on this for years. And now we finally have it. And I think it's great that you give this to developers and SEOs out there. You can now run modern JavaScript in Googlebot. And I think that's the real update to focus on here. And with all that said, I don't think this is a silver bullet. What I'm wondering is, I, as someone  

#### [0:07:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=450) |  who is building websites, should I look

at something else. Like, can I do something to help everyone on the web? ZOE CLIFFORD: Why yes, Martin. You should keep your users in mind. MARTIN SPLITT: Fair point. That's a good point. ZOE CLIFFORD: And look, this example page has quite a bit of loading time. It takes a while for the cat pictures to load. MARTIN SPLITT: Yeah. I mean, come on, it's lots of cat pictures. And I guess for cats you can wait a little bit. ZOE CLIFFORD: Yeah, but maybe we can do a little better.  

#### [0:08:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=480) |  The browser streams the HTML as it

arrives. But there isn't much that can be displayed right away. We got some script tags, but the body is empty. And the browser won't discover and display the cat images until JavaScript has been downloaded, parsed, and executed. MARTIN SPLITT: Right, right. So what you're saying is, sure, I load a lot of images. But it could be so much faster. And the browser gives me the capability to do that faster for free, and I am breaking that?  

#### [0:08:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=510) |  ZOE CLIFFORD: Yeah, and it may hurt

your users. Isn't there some way to use your JavaScript framework to produce HTML and ship that the browser upfront? MARTIN SPLITT: Good question. And the answer is yes. But that brings us into this whole new world of web app architecture. So I think we need to talk a little bit about terminology. So I think the first thing that you want to probably look at is Universal JavaScript ZOE CLIFFORD: Universal JavaScript--  

#### [0:09:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=540) |  that's the same thing as Isomorphic JavaScript,

right? MARTIN SPLITT: Yes. Because we don't have enough terms, we have to invent new ones. So it's like Universal JavaScript, server-side renewable JavaScript, and Isomorphic JavaScript. But it's pretty much the same thing. ZOE CLIFFORD: Cool, and that's just JavaScript code that can run either on the server or in the browser, right? MARTIN SPLITT: Yes, absolutely. It's nice. So JavaScript itself is a pretty agnostic language, but there's features that only work in the browser.  

![](https://i.ytimg.com/vi/Ey0N1Ry0BPM/maxres1.jpg)



#### [0:09:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=570) |  And then there's features that only work

on the server. And you want to make sure that you use the subset that works on both sides. And that enables us to do server-side rendering. ZOE CLIFFORD: Ah, yes, server-side rendering-- like the olden PHP days [LAUGHS] When the server gets a request, runs some code, and generates the HTML that is sent to the browser. MARTIN SPLITT: Exactly, except that we are not running PHP. I mean, you can. And we are talking about running the JavaScript from your framework code basically on the server side  

#### [0:10:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=600) |  and generating that. ZOE CLIFFORD: And what

else is there? MARTIN SPLITT: So server-side rendering has a few-- well, not necessarily drawbacks, but a few characteristics that you want to not forget about. So one thing is it doesn't really give you the quickest response because you have to run it every request. So you can also do pre-rendering instead. ZOE CLIFFORD: Ah, pre-rendering. That happens when you make changes, like at build time or on deployment, right? MARTIN SPLITT: Absolutely. So basically, instead of doing it on every request,  

#### [0:10:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=630) |  you're only running the JavaScript when you

know that the content has actually changed. And that's useful if your content doesn't change that often. ZOE CLIFFORD: Ah, so it could be useful on stuff like landing pages, blogs, and so forth. MARTIN SPLITT: Oh, absolutely. I mean, those are fantastic candidates for pre-rendering. Because when you have a blog, and you know this content isn't going to change until I make an update until I publish a new post or edit an existing post, that you can run the pre-rendering at that point, and just be a static website  

#### [0:11:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=660) |  the rest of the time. ZOE CLIFFORD:

Oh, cool. And by the way, I think I heard another term at some point. I think it was hydration? What's that? MARTIN SPLITT: So hydration is the thing that every human should do properly. You should drink enough and keep yourself hydrated. But in this case, actually, it means something else. It's a variation of server-side rendering, because what we discussed so far, pre-rendering or server-side rendering, the pure version just generates static HTML sites. ZOE CLIFFORD: Yeah, and just generating  

#### [0:11:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=690) |  static HTML wouldn't be quite what I

want if I'm building an awesome single-page web app. MARTIN SPLITT: That's the thing. If you build a highly interactive app, where you want this interactivity to still be there, but the initial content should also already be rendered. So basically, yeah, that is what hydration is about. ZOE CLIFFORD: I see. So it sends the HTML to the browser, and then upgrades in the browser once the JavaScript is downloaded, parsed and executed.  

#### [0:12:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=720) |  MARTIN SPLITT: Exactly, so that gives you

this nice, dynamic nature of the website, even if you have the initial content in HTML already. And let's look at how that would look like in a project. So for instance, if I'm using React, I can do something like react-snap. It starts with my homepage, and then crawls all the links it finds, and then generates static HTML for that. But that's pre-rendering. And unfortunately, if you have a regular React application, what you might want to do, if you want to hydrate stuff as well on top of it, that means that you also  

#### [0:12:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=750) |  need to do some changes to your

code. So again, this is the main application code. You have to make this change that, if you see that the root element has already some child nodes, then that means that we actually are in the pre-rendered HTML in the browser. And then the app hydrates. But if it doesn't have anything in there yet, then we are on the server. And then we need to basically run this to generate the initial HTML. ZOE CLIFFORD: And is there some other way to do this with React? MARTIN SPLITT: Yes, especially if you  

#### [0:13:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=780) |  start a project from scratch and have

no old legacy code base. But I highly recommend taking a look at Next.js for instance. I mean, it does require some changes. But it is definitely worth it. ZOE CLIFFORD: Ah, but I don't want to rewrite everything. MARTIN SPLITT: OK, that's a fair point. So the thing is, when I said Next.js, Next.js is a higher-level framework in the sense of it uses your React components. But it gives you helpers for server-side rendering and hydration as well.  

#### [0:13:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=810) |  ZOE CLIFFORD: I see, I see. MARTIN

SPLITT: So this is that. But you might use other frameworks, right Zoe? What is your favorite framework. ZOE CLIFFORD: Oh, my fav-- MARTIN SPLITT: [INAUDIBLE] ZOE CLIFFORD: My favorite framework's JavaScript, Martin. MARTIN SPLITT: OK, well, yeah vanilla JavaScript, that's a fair point, I think. But if you would be using other frameworks, like Vue.js, for instance, you actually have options as well. You have three options for Vue.js. And the first one is the Vue.js server renderer.  

#### [0:14:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=840) |  And that gives you SSR plus hydration.

That's kind of cool. ZOE CLIFFORD: But you still have to rewrite a lot of your code, right? MARTIN SPLITT: Yeah, well, you still have to have universal code in your Vue application. So hmm-- it's unfortunate. Well, if you don't want to do that, there is another option. I think the second option is called the prerender-spa-plugin. I like that, because I want to be in a spa sometimes,  

#### [0:14:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=870) |  the SPA plugin. So it basically pre-renders

your page, like we saw in react-snap. But it doesn't give you hydration. ZOE CLIFFORD: Ah, so this only gives you pre-rendering, and not the benefits of hydration. So what if I start a new Vue project? MARTIN SPLITT: So similar to what we said about React, there's a thing that you should look into if you're starting a new Vue project. And I think the thing that I would recommend you look at is Next.js. Next.js is inspired by Next.js. Surprise-- the name is one letter difference.  

#### [0:15:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=900) |  It does pretty much the same thing

as Next.js for React. But it does this specifically for Vue. ZOE CLIFFORD: Ah, but it says pre-rendering right there as well. MARTIN SPLITT: OK, yeah, you caught me. So it does SSR in hydration. But it comes with the command line interface that you can install. And then you can say, OK, this page and this page and this page, I actually want to pre-render as well. So you get to mix and match a little bit. ZOE CLIFFORD: I see.  

#### [0:15:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=930) |  So you can choose one or the

other. And what does the server-side code look like? MARTIN SPLITT: Well, the server-side code depends a little bit. But let's say we use Express.js, which is a pretty popular Node.js server-side code framework or library. The first step is you create the Vue server renderer if you would be using the Vue server render option. ZOE CLIFFORD: I see that it creates a renderer with an HTML template. What's all that for? MARTIN SPLITT: So the HTML template allows you to have the site-wide data, like the general HTML structure.  

#### [0:16:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=960) |  And basically just the Vue application that

runs just gives you the content inside that template, ZOE CLIFFORD: I see, and does this template allow interpolation of page-specific data, like the title or meta snippet. MARTIN SPLITT: Tile and meta snippet, yes. So in the next step, whenever a request comes in, because we are now not pre-rendering, but we are doing SSR plus hydration, when the request comes in, we can specify the page-specific data. And that gets replaced in the template as well. ZOE CLIFFORD: I see.  

#### [0:16:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=990) |  So that will produce a string of

the template HTML, together with the HTML-generated from Vue.js, I guess. MARTIN SPLITT: Correct, exactly. And once we have this HTML in the string, we can give it to the browser. And that's what it's about, really. ZOE CLIFFORD: Nice, and that works with your Vue.js components? MARTIN SPLITT: It does, unless they're not written in Universal JavaScript. So you would still have to make sure that your JavaScript also runs on the server. You see a theme is evolving here, right ZOE CLIFFORD: Ah, yes.  

#### [0:17:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1020) |  MARTIN SPLITT: Write universal JavaScript. ZOE CLIFFORD:

So we still have to make edits to make sure it code is Universal JavaScript. But what about Angular? How does it work. MARTIN SPLITT: So for Angular, it's pretty much a similar story. The project is called Angular Universal, and it does SSR plus hydration as well. It comes with a bunch of stuff. So if you use Express.js, for instance, it comes with this NG Express engine that you can use, and you parse in the AppServerModuleNgFactory, which  

#### [0:17:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1050) |  is a really easy thing to say.

[LAUGHS] And yeah. ZOE CLIFFORD: So that NG Express engine runs our Angular app code on the server and generates the HTML we can serve, right? MARTIN SPLITT: Yeah, it's part of the Angular Universal, like all the hydration code and that kind of stuff piles on top of it. And you have to make some code adjustments, OK? But basically, you get SSR in hydration for Angular that way. And it's pretty well-supported. But again, without Universal JavaScript, that's not a good thing.  

#### [0:18:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1080) |  ZOE CLIFFORD: Ah, that was a lot

to take in. Is there somewhere to learn more about all this stuff? MARTIN SPLITT: Funny that you ask, because we happen to have made this YouTube video series that's called JavaScript SEO. If you haven't checked that out, go to YouTube.GoogleWebmaster, subscribe to the channel, and check out the JavaScript SEO playlist as well. Cool. Now, we have been talking quite a lot about dynamic SRA server-side rendering, server-side rendering rehydration, and pre-rendering. But last year at I/O I remember that John actually  

#### [0:18:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1110) |  said something about dynamic rendering. So I

think that dynamic rendering was this thing that you can use to render, but only do that for bottom crawlers and SEO. So does that now mean that we have the new Googlebot after all? Does that mean that we can ditch that and it's going away? ZOE CLIFFORD: Well, we want site owners focus on the user experience and content quality. For the time being, dynamic rendering may be useful. But it's not a long-term strategy. MARTIN SPLITT: Ah, right.  

#### [0:19:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1140) |  But, like-- hmm. So what would be

use cases for dynamic rendering, then? ZOE CLIFFORD: Ah, first and foremost, it's a workaround. Unfortunately, not all crawlers and bots support JavaScript right now. MARTIN SPLITT: Right, like the social media crawlers. Most of them don't run it, and some other search engines don't do that well as well. Right, OK. Gotcha, right. But I think it could also be a stepping stone. Like it's a workaround, but it can be a stepping stone towards improving your website,  

![](https://i.ytimg.com/vi/Ey0N1Ry0BPM/maxres2.jpg)



#### [0:19:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1170) |  because server-side rendering and hydration, that's a

bunch of work that you have to do, right? ZOE CLIFFORD: Yes, yes, but remember that server-side rendering and hydration bring the great benefits to your users, while dynamic rendering, not so much. MARTIN SPLITT: Ah, right, and that's because dynamic rendering basically only improves your HTML content coverage that basically is in the first stream that goes to the browser only for bots, not for users. So users still get the slower site if they're on--  

#### [0:20:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1200) |  ZOE CLIFFORD: Yeah, that's correct. So consider

dynamic rendering a workaround until other bots have caught up, or you have upgraded your website to server-side rendering or server-side rendering plus hydration. MARTIN SPLITT: I think that makes sense. ZOE CLIFFORD: That was a lot to take in, wasn't it? MARTIN SPLITT: That was so much stuff in so little time. But I think it actually gives you all a foundation to build from. And I think that's a very, very important thing to do,  

#### [0:20:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1230) |  isn't it? Like, do you like what

you just got? Yes? [APPLAUSE] But wait, there's more. [LAUGHTER] So, Zoe, while I've got you on stage, I was wondering, now that I build sites and consider SEO, can I also test what I'm building and if it's actually working properly? ZOE CLIFFORD: Ah, good question. Let's take a look at a few tools. MARTIN SPLITT: OK, fair enough. ZOE CLIFFORD: A great first stop is Lighthouse. It's right in your Chrome DevTools. MARTIN SPLITT: Come on.  

#### [0:21:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1260) |  I know that one. It has the

Performance audits. It has Best Practices. It has Accessibility but what does that have to do with SEO? ZOE CLIFFORD: Well, it's also got some SEO audits as well. And they help you improve your website's discoverability and make your users happier. Let's run the audit. And there we go. Here are your results. MARTIN SPLITT: This is not looking good. I mean-- whoops. OK?  

#### [0:21:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1290) |  ZOE CLIFFORD: Yeah 44 points. But no

worries. Many of these are low-hanging issues and easy to fix. The best candidates are probably at the title and meta description. MARTIN SPLITT: Right. Yes, because if you use JavaScript Frameworks you often forget about these. And it's not always quite obvious how to make this happen in JavaScript Frameworks. So let's look at React, for instance. React is a great framework. And if you use React Helmet, it's even better because you can do all these things. ZOE CLIFFORD: My React Helmet.  

#### [0:22:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1320) |  Martin, I'm building a website, not going

on a bicycle tour. [LAUGHS] What's that React Helmet for? MARTIN SPLITT: You should go on a bicycle tour It's quite nice weather outside. But similar to a bike helmet, that might not look fantastic, but it's really helpful. It protects you from not looking great in the-- I mean, bike helmets oftentimes don't make you look great. But they make things work out for you, so it's similar to React Helmet. React Helmet allows us to add to our template, and basically use any props in our component to set the title and the meta description  

#### [0:22:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1350) |  to something that is specific to the

page. Let's say I have a product detail page, right? ZOE CLIFFORD: Yes. MARTIN SPLITT: I could take the product name and put it in the title, and then some description for the product into the meta description. That's going to look fantastic in search results. ZOE CLIFFORD: Great, great, so this works for React. But what about other frameworks? MARTIN SPLITT: Right, OK, so the other frameworks-- Angular, for instance, has it built in. They're called the title and meta service. ZOE CLIFFORD: And they do the exact same thing? MARTIN SPLITT: Got it.  

#### [0:23:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1380) |  So here, we have the same thing.

We take the title and the meta description, and put something that is in our component into them to show what's on the page exactly. Yeah. And now, that's Angular and React. You might be asking next, what is about Vue.js? Vue.js jazz has an extension called vue-meta. Gives you this additional method in your components called the meta info, and it does the same thing. ZOE CLIFFORD: Ah, and so that's it? MARTIN SPLITT: Oh, actually, for Vue.js, you want to make sure if you use the vue-router to switch  

#### [0:23:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1410) |  to history API mode. ZOE CLIFFORD: Ah,

history mode. What's that for? MARTIN SPLITT: So it defaults to the fallback mode, which uses hash URLs. And hash URLs aren't exactly great for crawling. ZOE CLIFFORD: I see. So maybe only the homepage would be indexed. MARTIN SPLITT: Yeah, because we're not really crawling these fragmented URLs. We said that last year in the I/O talk as well. So that's no good. ZOE CLIFFORD: Hmm. Speaking of no good, Martin, Googlebot only sees the placeholder images on your website.  

#### [0:24:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1440) |  MARTIN SPLITT: Wait. Hang on. That's weird.

It works in my browser. So why does it not work here? We have a fresh Googlebot and everything? ZOE CLIFFORD: Yeah, yeah, do you maybe use Lazy Loading Images? MARTIN SPLITT: Ah, I actually do. And I do that-- like, this is the code. So this should be fine. I mean whenever you scroll, I figure out if the image is within the viewport. And if that is, then I load the actual image. So that should be good?  

#### [0:24:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1470) |  ZOE CLIFFORD: Well, Googlebot does support Lazy

Loading. But keep in mind it may interact with the page differently from your users. In your case, Googlebot doesn't scroll. So the scroll handler isn't checkered and the lazy loading contents aren't loaded. MARTIN SPLITT: Ah, right. But I guess what I should be doing is use something else, like IntersectionObserver server maybe? ZOE CLIFFORD: Yes, you could use an IntersectionObserver. This is an API that triggers a callback whenever any observed  

#### [0:25:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1500) |  element becomes visible. It's more flexible and

more robust. MARTIN SPLITT: Ah, so I can use the same code is still load by images. But now it's more robust, thanks to IntersectionObserver. And that's supported in modern Googlebot. That's amazing. ZOE CLIFFORD: It is. MARTIN SPLITT: So I wonder, can I also use, like, the new native Lazy Loading that Chrome's getting? ZOE CLIFFORD: Absolutely. It's still an experimental feature. But worst case scenario, it gets ignored. So feel free. MARTIN SPLITT: Ah, so that's pretty cool, because it's just this additional thing that we just  

#### [0:25:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1530) |  ignored, and it just works. OK, that's

cool. That's nice. So you can run, which is nice. So I can ask you another question, I guess. Is it OK if I ask you another question? ZOE CLIFFORD: Oh yeah. Go ahead. MARTIN SPLITT: So I was using Search Console earlier today. And I noticed that we have this weird thing called soft 404s. Sorry, not soft 404s. We have this issue where my pages-- I basically update my website. And then they get, like, crawled, but not really--  

#### [0:26:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1560) |  did discover, but not crawled yet. So

that's the one that I'm having struggles with. What does it mean to be discovered, but not crawled yet? ZOE CLIFFORD: Oh it means Googlebot hasn't indexed your page yet. Perhaps your site's crawl budget is too low for those pages to be indexed. MARTIN SPLITT: What's crawl budget? ZOE CLIFFORD: Well, crawl budget is a rate limit on how frequently Google can crawl a site. Oh could you go back a slide? MARTIN SPLITT: Right, let's stay here for a moment. Yeah, so it's how much Google crawls my site.  

#### [0:26:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1590) |  ZOE CLIFFORD: Yeah, yeah, and we do

this to be a good web citizen and avoid knocking over web servers with too many concurrent requests. MARTIN SPLITT: Ah, OK. Is there something else that I should know about crawl budget? ZOE CLIFFORD: Well, crawl budget also applies to resources loaded from the page during rendering. MARTIN SPLITT: What do you mean by resources? ZOE CLIFFORD: For example, JavaScript files loaded from script tags, or XHR or fetch requests triggered by JavaScript. MARTIN SPLITT: Those count against my crawl budget.  

#### [0:27:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1620) |  ZOE CLIFFORD: Yes. MARTIN SPLITT: All right.

OK, so I need to make sure that I'm not making too many requests, I guess. ZOE CLIFFORD: But one more thing, Martin. One more thing. We don't have forever to perform a render. And staying within the crawl budget can be tricky sometimes. To help with this, we cache certain subresources across renders. MARTIN SPLITT: So that means that if I have multiple pages, and they all use the same libraries or the same code, you don't fetch it over and over and over again.  

#### [0:27:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1650) |  ZOE CLIFFORD: Correct. Googlebot might just fetch

it once, and then reuse it. MARTIN SPLITT: OK, that's pretty nice. So what do you do if my site has an infinite loop? Is it OK? Is it going to be indexing what it's got so far? ZOE CLIFFORD: Yeah, yeah. If your site has an infinite loop then at some point, we'll cut off the JavaScript, and cut off any fetching that might still be going on, and return the contents that we have up to that point. MARTIN SPLITT: That's pretty cool. So that's nice.  

#### [0:28:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1680) |  Is there something else that I should

know? ZOE CLIFFORD: Yes, yes. Did you know that we put URLs we discover into a queue and crawl, render, and index them separately? It's not like Googlebot is clicking on links and going from page to page. MARTIN SPLITT: Damn it. [LAUGHS] So that means that the render queue is still a thing? We haven't removed that even with a new update yet, right? OK, right, but what if I use-- let's say, like, I might have a website that  

#### [0:28:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1710) |  requires you to set a cookie. And

only if the cookie is set after the second time, we actually show you the content. Would that work? ZOE CLIFFORD: No, that would not work. Googlebot does not store cookies across requests. So it always sees the page like a signed out user would. MARTIN SPLITT: Right, OK, so it doesn't do that with cookies. But what about the other ways to process data across page loads? Will you use, like, local storage, session storage, or IndexedDB? ZOE CLIFFORD: These APIs are available. But like cookies, they don't process data between renders.  

![](https://i.ytimg.com/vi/Ey0N1Ry0BPM/maxres3.jpg)



#### [0:29:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1740) |  So they're basically only available within a

single render pass. MARTIN SPLITT: All right, so that means I can't process data across-- OK, right. Fair enough, but what about other things like service worker or cache API? ZOE CLIFFORD: Well, currently, we don't support this service worker API. But if we did, every render would start with no service workers installed. MARTIN SPLITT: Oh, right, because basically, someone coming from search results is pretty much a first time user. So we can't rely on that. That makes sense.  

#### [0:29:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1770) |  I think that makes sense. So in

that case, whenever I use some feature on the web, I need to feature detect if it actually is present? ZOE CLIFFORD: Yes, feature detection is a great idea. Progressive enhancement is a good strategy where different users might be on devices or use browsers with varying capabilities. But you should make sure and also handle the not-so-happy path. MARTIN SPLITT: Oh, wait, so what you mean here is error handling, right?  

#### [0:30:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1800) |  ZOE CLIFFORD: Yeah. MARTIN SPLITT: I need

to make sure that my code does that properly. So let's say there's something like this right here. The idea here would be that I have localized content. So I check if geolocation exists. If not, I just load the fallback content. I think that's fine. And then when it exists, I just use the current position to load the localized content. Is that fine, or what happens if there's a mistake? ZOE CLIFFORD: Ah, well, imagine that getCurrentPosition  

#### [0:30:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1830) |  function throws an error or an exception.

Then your webpage's contents would not be shown to Googlebot. MARTIN SPLITT: Oh. ZOE CLIFFORD: Because the geolocation feature is available, but an error happens. MARTIN SPLITT: Oh. ZOE CLIFFORD: Yes, this can and does happen to Googlebot. I've seen it more than once. MARTIN SPLITT: OK, when? What kind of APIs could be affected. ZOE CLIFFORD: For example--  

#### [0:31:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1860) |  I think this is in another slide.

But WebSockets. MARTIN SPLITT: WebSockets? All right. But also things that require permissions, like microphone, webcam. What do we do with these things? ZOE CLIFFORD: We deny all permissions. MARTIN SPLITT: OK, I think that makes sense. After all, what would the webcam picture look like for Googlebot Like a server room or something? That would be weird. So I think to fix this, what I could do is basically just have an error fallback that also loads  

#### [0:31:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1890) |  the fallback content. ZOE CLIFFORD: Yes, and

making sure you treat these error conditions appropriately is important. You don't want to leave the mistake of leaving Googlebot or users without contents. MARTIN SPLITT: Yeah, that would be a mistake. Oh, by the way, you're going to love this, because this keeps happening to me. I noticed something in our performance report in Search Console. So we have the support page and it is great. But it keeps losing impressions and clicks on the search results.  

#### [0:32:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1920) |  So this is not exactly great. But

I don't understand what's happening here, because our code is perfectly fine. The site is on Google. It's indexed, and all the content is there when I test it. But there's something weird going on, because we figured out that it's not actually fetching the data from the API. But we're not sure why. ZOE CLIFFORD: Ah, well, would you mind showing me the code, Martin. MARTIN SPLITT: I mean, we are amongst us. So sure. Here we go. So our support bot basically opens a WebSocket connection, and then uses the connect event to show a bunch of initial FAQ  

#### [0:32:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1950) |  data and give you a welcome message.

And then it starts handing the chat code. ZOE CLIFFORD: Ah, this is what I mentioned earlier. And what I was worried about when you said your requests don't show up-- we don't allow WebSocket connections in Googlebot for architectural reasons. MARTIN SPLITT: Oh, OK. So that explains why we're not seeing the data. I guess making that static content, and maybe even use the new FAQ. Structured data is probably a good idea. Right, that makes sense.  

#### [0:33:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=1980) |  So I have one more question. We

have some time for that? ZOE CLIFFORD: Yes, we have a few minutes left. MARTIN SPLITT: We have a few minutes left. So basically, I noticed that we have this soft 404 problem. And I'm not so sure what that means. ZOE CLIFFORD: Oh, a soft 404 means you gave us a 200 HTTP OK. But the contents look like an error page. MARTIN SPLITT: OK, yes, that does happen in my single page application, because my server doesn't actually know all the different routes and products that we  

#### [0:33:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=2010) |  are serving. So what we do is

give you the index HTML. And then the JavaScript runs and figures out of that thing actually exists. And if not, it shows an error. But we can't change the HTML code anymore. So what would I do in this kind of case? ZOE CLIFFORD: Well, you've got a couple ways out of this situation. You can either redirect to a URL that returns a 404 from the server. Or alternatively, you can use the meta robots tag with no index. MARTIN SPLITT: Ah, but why do I even  

#### [0:34:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=2040) |  have to care about that kind of

stuff? Can't you just catch it for me? ZOE CLIFFORD: Ah, well, HTTP status codes, Martin, they're important. They tell Google how to interpret the response we get. You tell crawlers and user browsers this is a good URL. Here's some content and all is good. MARTIN SPLITT: I mean, that sounds good so far. ZOE CLIFFORD: But in the case of a soft 404, you tell us this is fine, and then turn around and give us something that says otherwise.  

#### [0:34:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=2070) |  [LAUGHS] MARTIN SPLITT: It's a bit backstabby.

That doesn't sound good. ZOE CLIFFORD: And it's not good, Martin. HTTP status give crawlers and users valuable information. MARTIN SPLITT: OK, so in that case, could you elaborate on that a little bit more? ZOE CLIFFORD: Oh, all day. [LAUGHS] So for example, so if you remove a page and give us a 404 status, we will remove the page from the index after a short while  

#### [0:35:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=2100) |  if it's not coming back online. MARTIN

SPLITT: Duh, I guess that makes perfect sense. ZOE CLIFFORD: And that's how it's supposed to be. But let's say this content wasn't removed. It has just moved to a new URL instead. We wouldn't know that. MARTIN SPLITT: OK, that's fair, because I guess if we just remove it, then you have to rediscover it from scratch. And then you wouldn't know that there's a new thing somewhere else, right? ZOE CLIFFORD: That's right. And that's why using 301 to indicate a redirect is a much better idea. MARTIN SPLITT: OK, so I got this.  

#### [0:35:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=2130) |  But I actually have an idea for

you. So hold this. Like, oh my god, I have a fantastic solution to the soft 404 problem. So how about this? I basically just add a node-index to all my pages, right? ZOE CLIFFORD: Right. MARTIN SPLITT: So the bot doesn't care. But then once I know that the cat that I'm loading actually exists, I change that to please index me. That solves the problem, right? ZOE CLIFFORD: Oh, well, that might not end well. MARTIN SPLITT: Why?  

#### [0:36:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=2160) |  ZOE CLIFFORD: Look, we see a no

index early on. So we could stop the process right there and not take the removal through JavaScript into account. And all your pages would be marked as no index in that case. MARTIN SPLITT: So that would remove all my website from the index. That's a terrible idea. I understand that now. Thank you very much for preventing that from happening. OK, right, looking at the time, we don't want to hold you all too long.  

#### [0:36:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=2190) |  So I think it's time to summarize

this a little bit. I mean, we have been talking about a bunch of edge cases. But luckily, all of those things are edge cases, right? ZOE CLIFFORD: Right. MARTIN SPLITT: As long as you follow the best practices and do the right things as a web developer and an SEO, you should pretty much be safe, right? ZOE CLIFFORD: Right, right, and I think it's important to mention that we're continuously working to improve things as well, like the new Chromium headless, the Chromium in indexing. It's good stuff. MARTIN SPLITT: Yes, and that's the big one, really.  

#### [0:37:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=2220) |  But also it's quite cool that we

discussed server-side rendering and server-side rendering with hydration and pre-rendering, because that can also improve the user experience of your site, not just the SEO side of things. ZOE CLIFFORD: Yeah, hydration. MARTIN SPLITT: Yes. Also, we talked a little bit about something else. And that was testing. ZOE CLIFFORD: Yeah, testing plus one MARTIN SPLITT: So it's basically test early, test often? ZOE CLIFFORD: Absolutely. You don't want any bad surprises.  

#### [0:37:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=2250) |  MARTIN SPLITT: Bad surprises are bad. ZOE

CLIFFORD: Is there anywhere to find out more about this stuff, Martin. MARTIN SPLITT: Indeed, that's a very good question. So again, we have a YouTube channel with lots of content. We also do bi-weekly office hours if you want to hang out with us online and ask those questions. That's a great idea to do that as well. ZOE CLIFFORD: And don't forget the docs. MARTIN SPLITT: Oh, right. ZOE CLIFFORD: We keep adding new docs all the time. MARTIN SPLITT: Yes, that's true. And I think the thing that both of us would love to take away from the session for you  

#### [0:38:00](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=2280) |  guys-- this is the main point here.

We don't want you to worry too much on, you know building stuff for search engines. We want you to build great user experiences on the web. ZOE CLIFFORD: Yes, our goal is to empower you to build great discoverable web apps and websites. That's why the new Googlebot is such a big leap forward. MARTIN SPLITT: It is an amazing thing. And we will continue to improve Googlebot and generally Google search with new features and capabilities. So please, please, please continue to make fantastic content for your users, and blow everyone away that comes to your website.  

#### [0:38:30](https://www.youtube.com/watch?v=Ey0N1Ry0BPM&t=2310) |  And with that being said, I would

like to say thank you so much for coming to this chat. We did it. ZOE CLIFFORD: You're very welcome Martin. MARTIN SPLITT: It's been a great pleasure having you. ZOE CLIFFORD: And thank you all, audience. MARTIN SPLITT: Thank you so much for being here. If you have any questions, we'll be around. You can ask us questions, follow us on Twitter, check out our YouTube videos. Thanks. [MUSIC PLAYING]  