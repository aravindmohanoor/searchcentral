[![Rendering (WMConf MTV '19)](https://i.ytimg.com/vi/rq8sFkl0KnI/hqdefault.jpg)](https://www.youtube.com/watch?v=rq8sFkl0KnI)

## Rendering (WMConf MTV '19)

Erik Hendriks, Software Engineer at Google, goes over how rendering works and some of the challenges of rendering everything on Google Search. Stay tuned to find out about some of the challenges of rendering content on Google Search, such as fetching and JavaScript.



Understand the JavaScript SEO basics → https://goo.gle/2Um3aBA



Watch all the recorded talks from WMConf MTV '19 → https://goo.gle/2QHcmy6 

Subscribe to the Webmasters Channel → https://goo.gle/Webmasters event: Webmaster Conference 2019; re_ty: Publish; product: Search Console - General; fullname: Erik Hendriks;



#### [0:00:00](https://www.youtube.com/watch?v=rq8sFkl0KnI&t=0) |  ERIC HENDRIKS: My name's Eric Hendriks. I

work on rendering. I'll talk a little bit about how rendering works and some of the challenges that we've run into trying to render everything that goes into the Google Search index. So before we get started, I'll talk a little bit about what rendering is, just so that we're all on the same page. So rendering is the process that allows Googlebot to see the same content that we do, as normal users on the web. It's been a long time since web content was a blob of HTML that  

#### [0:00:30](https://www.youtube.com/watch?v=rq8sFkl0KnI&t=30) |  referenced a few images. Your browser does

a lot of JavaScript and additional fetching these days to actually load the content that you see in the end. Just a visual example of what that means. On the left, we have YouTube without rendering. I mean, we've rendered it a little bit just to do a layout and get something that we can paint. And then on the right, we've actually run all the JavaScript and additional fetching and gotten all the content.  

#### [0:01:00](https://www.youtube.com/watch?v=rq8sFkl0KnI&t=60) |  So Googlebot needs to do this, as

well, in order to see the same content that you do, which basically means it needs to behave like a browser. That's a tall order, because browsers are complicated, they do a lot, they're fairly expensive to run. The good news is that we actually have a good browser available to us. So Googlebot actually renders with Chrome these days. That's been true since about the beginning of this year.  

#### [0:01:30](https://www.youtube.com/watch?v=rq8sFkl0KnI&t=90) |  What that really means is that we

crawl your page with Googlebot, we go fetch the content, we give it to Chrome, and then Chrome does what Chrome does. Right? So it runs all the script. It loads additional content. Googlebot goes and fetches that content on behalf of Chrome. And then once everything's loaded, we take a snapshot of the page. And that's the content that actually  

![](https://i.ytimg.com/vi/rq8sFkl0KnI/hq1.jpg)



#### [0:02:00](https://www.youtube.com/watch?v=rq8sFkl0KnI&t=120) |  gets indexed into the web. So, great.

This works wonderfully. It gets interesting at scale, though. So we have trillions of pages in the web index, and we want to do this to all of them. So things get interesting. They get interesting along two axes, mostly. And the first one is fetching. So if we want to render a page, we need to fetch a lot of additional content that's going to become visible on the page in the end.  

#### [0:02:30](https://www.youtube.com/watch?v=rq8sFkl0KnI&t=150) |  And then we have to run the

JavaScript that actually does that. So that's a lot more logic than we ran before. So I'm going to start with fetching, because it's probably the more difficult problem from our point of view. It's harder for us to solve within Google. And that breaks down into, basically, two things that we see. And this is all us trying to be good citizens on the web, right?  

#### [0:03:00](https://www.youtube.com/watch?v=rq8sFkl0KnI&t=180) |  So we don't want to fetch content

that you don't want us to fetch. And we also want to make sure that our crawl volume is reasonable enough so that we don't cause problems for servers. So robots.txt is how you tell us not to grab something, but this cuts both ways. If you want some content to appear on your page, don't block it with robots.txt because we won't fetch it. And then there's just limited crawl volume, right? So we don't want to overload your server, so we limit how much we're willing to fetch  

#### [0:03:30](https://www.youtube.com/watch?v=rq8sFkl0KnI&t=210) |  from any server. So that's really the

big problem. And here's a few numbers to put that in perspective. So when we render a page, we see about 50 or 60 fetches. This number is a little lower than what normal users usually see, because we're obeying robots.txt. So that actually protects us from some crawling things, like ad networks and so on don't like robots. And that's fine with us, because that's less fetching we have to do.  

#### [0:04:00](https://www.youtube.com/watch?v=rq8sFkl0KnI&t=240) |  And if you render a bunch of

pages with a large shared cache, you can expect to see a cache hit rate around 60% or 70%. So if you do the math here and multiply it out, you end up with about 20 fetches or so per page. Or another way to look at that is my crawl volume is going to go up by 20 times when I start rendering. So that's a problem, right? That's not going to fly. This is the point where I say, hey, I want to render your page and the crawl folks tell me get out.  

![](https://i.ytimg.com/vi/rq8sFkl0KnI/hq2.jpg)



#### [0:04:30](https://www.youtube.com/watch?v=rq8sFkl0KnI&t=270) |  So we have to do something to

reduce this number. This can't stay the way it is, so we cut some corners, right? And the big one that we cut is around HTTP caching. Lots and lots of webmasters err on the side of marking their content not cachable. And frankly, it's too many for us to really obey those rules. So we will over cache. We cache anything and everything for long periods of time.  

#### [0:05:00](https://www.youtube.com/watch?v=rq8sFkl0KnI&t=300) |  The best way to cope with this,

as a web master, is really just to not rely on clever caching tricks. Try and make your content cachable. It's good for end users. It's good for Googlebot. Even when we do that, though, we still have a very large fetch volume. And there are cases when we can't fetch everything. So this happens frequently when there's a lot of fan in onto a single domain. So you can think of like a comment section that's  

#### [0:05:30](https://www.youtube.com/watch?v=rq8sFkl0KnI&t=330) |  served from a common server gets a

lot of fan in from lots of sites-- harder for us to load. So the way to deal with fetch volume issues is really two things. So reduce the number of fetches-- this has been good practice forever, so that's also good. And then, mostly, be resilient. So you want to be able to show as much content as you can, given the set of fetches that succeeds. Because when a fetch fails, it basically  

#### [0:06:00](https://www.youtube.com/watch?v=rq8sFkl0KnI&t=360) |  just looks like a fetch failure in

a normal browser inside Googlebot. OK, right. So pivoting a little bit, I'm going to talk a little bit about the other half of the puzzle here is JavaScript. So the good news is, as I mentioned earlier, we are running Chrome, which means that the JavaScript environment is, more or less, what you'd expect. There's not really a whole lot to say about it. The bad news is that there is a whole lot of JavaScript out there, and we are aiming to run a whole lot of it. So performance matters.  

![](https://i.ytimg.com/vi/rq8sFkl0KnI/hq3.jpg)



#### [0:06:30](https://www.youtube.com/watch?v=rq8sFkl0KnI&t=390) |  We are constrained with CPU, globally. So

we need to make sure that the errant pages will not damage the system by consuming too much. If you have a page that runs lots and lots of JavaScript for a long time, we will eventually interrupt it. This is a different behavior than normal browsers have.  

#### [0:07:00](https://www.youtube.com/watch?v=rq8sFkl0KnI&t=420) |  In extreme cases, we've actually seen this

render pages unrenderable, because the CPU consumption is such that we just can't get anything to load reasonably. And most pages don't have any problem with this, right? So any decently constructed page is not going to run into the thresholds that we have. But there are some cases where good pages run afoul of this.  

#### [0:07:30](https://www.youtube.com/watch?v=rq8sFkl0KnI&t=450) |  So I'm going to talk about some

of the common failure scenarios that we have, so popular ways to fail. Error loops are one. So in this case, I'm talking about JavaScript that fails at something, and then it wants to retry, right? And it does so, immediately. And then it fails again. So why might something fail? Like, robots.txt, it tries to fetch something that's blocked by robots.txt. It immediately turns around and tries to fetch it again  

#### [0:08:00](https://www.youtube.com/watch?v=rq8sFkl0KnI&t=480) |  and spins. That sucks. Missing features are

another way to do this. So you can try and use a feature that doesn't exist on Googlebot. For example, you can't use WebRTC. It's sort of an interesting networking feature. We just don't support that. So if you fail on that and spin, that's bad. Another one is cloaking. So cloaking refers to the practice of serving different content specifically to Googlebot.  

#### [0:08:30](https://www.youtube.com/watch?v=rq8sFkl0KnI&t=510) |  Some major websites to do this. I

think this content doesn't receive the same level of scrutiny because we've seen egregiously broken JavaScript coming from major domains at times. And again, it causes problems. This last bullet, cryptocurrency minors-- we don't actually see this a lot, but it kind of made us laugh because we had a bunch of pages that embedded these scripts. They're tremendously heavy, and they actually exploded the entire renderer every time and prevented indexing.  

#### [0:09:00](https://www.youtube.com/watch?v=rq8sFkl0KnI&t=540) |  All right. And that's what I've got.

Thanks. [MUSIC PLAYING]  