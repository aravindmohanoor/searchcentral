[![Links & JavaScript | WMConf Lightning Talks](https://i.ytimg.com/vi/4vtVUBzw9Rs/maxresdefault.jpg)](https://www.youtube.com/watch?v=4vtVUBzw9Rs)

## Links & JavaScript | WMConf Lightning Talks

Martin Splitt, Developer Advocate at Google, explains how Googlebot uses links to discover pages on the web and how JavaScript can be used together with links without causing trouble.



Understand the JavaScript SEO basics → https://goo.gle/2Um3aBA 



Watch all WMConf Lightning Talks → https://goo.gle/2VclBJz

Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



#SearchLightningTalks #webdev #SEO



#### [0:00:00](https://www.youtube.com/watch?v=4vtVUBzw9Rs&t=0) |  MARTIN SPLITT: Hello, and welcome to the

Webmaster Conference Lightning Talk serious. In this series, we share short versions of the content that we might share at Webmaster Conferences around the world as well. This time we will talk about everyone's favorite-- links in JavaScript web apps. [MUSIC PLAYING] All right. I think everyone who has ever used the web has seen them-- links.  

#### [0:00:30](https://www.youtube.com/watch?v=4vtVUBzw9Rs&t=30) |  They take users from one page to

another, either within the same site or on another site. They were the killer feature of the web when it was introduced, and they're a pretty big deal today as well. But besides letting users navigate between different content, they also serve an important purpose for bots and search engines, such as Google Search. First and foremost, they allow crawlers to find other pages of your website and move  

![](https://i.ytimg.com/vi/4vtVUBzw9Rs/maxres1.jpg)



#### [0:01:00](https://www.youtube.com/watch?v=4vtVUBzw9Rs&t=60) |  from page to page by finding the

links in the page and then following them. The other important purpose is that by following links, the crawler gains an understanding of site structure and information architecture. This is helpful when understanding what pages might be relevant to a given topic. But, now, how do you make a link? It turns out that this isn't as straightforward as one might think.  

#### [0:01:30](https://www.youtube.com/watch?v=4vtVUBzw9Rs&t=90) |  The most straightforward way to put a

link on your website is to just use a good old a tag with the URL of the page it points to in the href attribute. You may also sprinkle a little bit of JavaScript on your link. That's absolutely fine. This way, the link stays functional, and you can upgrade it with JavaScript functionality too. Now, you may consider leaving out the href attribute, but that's not a good idea.  

#### [0:02:00](https://www.youtube.com/watch?v=4vtVUBzw9Rs&t=120) |  This way, the link only works when

JavaScript works properly, and crawlers can't really find out where the link goes to. This is making your link more brittle, so it's better to avoid it. It also doesn't help to add an href attribute without a useful URL or with a pseudo URL, like this JavaScript URL here. The result is the same as with a link without an href attribute. It's not a good idea.  

![](https://i.ytimg.com/vi/4vtVUBzw9Rs/maxres2.jpg)



#### [0:02:30](https://www.youtube.com/watch?v=4vtVUBzw9Rs&t=150) |  Using a button might seem an option,

but that's not a good idea either. The rule of thumb is if it does something on the current page, it should probably be a button. If it takes the user to a different piece of content that wasn't on the page before, it should be a link. It's worthwhile to say that you also shouldn't simulate links by using any other HTML element and add a click handler in JavaScript. This breaks the built-in accessibility features  

#### [0:03:00](https://www.youtube.com/watch?v=4vtVUBzw9Rs&t=180) |  and isn't a good idea either. That

all goes to say use semantic HTML link markup and point your link to a proper URL. So what's a proper URL? Well, we've ruled out pseudo URLs, like the JavaScript code on something, something. But let's take a look at URLs for a moment. These URLs are typical examples. There's a protocol-- basically the language  

![](https://i.ytimg.com/vi/4vtVUBzw9Rs/maxres3.jpg)



#### [0:03:30](https://www.youtube.com/watch?v=4vtVUBzw9Rs&t=210) |  that is spoken when accessing the URL--

in this case, HTTP or HTTPS. It also has a host-- example.com here-- so a name that some computer or multiple computers respond to. Last but not least, it also has a path to a specific piece of content on that computer. This URL here also has another part-- a fragment identifier. That fragment identifier isn't a different piece of content.  

#### [0:04:00](https://www.youtube.com/watch?v=4vtVUBzw9Rs&t=240) |  If we leave it out, we get

the same content. What the fragment identifier does, though, is it points to a specific part of the document. And here's the thing. Because fragments aren't meant to point to different content, crawlers ignore them. They just pretend that the fragments don't exist, but that means if you build a single-page application with URLs that look like this, crawlers  

#### [0:04:30](https://www.youtube.com/watch?v=4vtVUBzw9Rs&t=270) |  won't follow these links. So to sum

it all up, use proper link markup, do not use fragment URLs for links that you want crawlers to discover and follow, and you should be building websites that work well with JavaScript, and the links will be found. Thank you very much for listening. Have a great time, and see you soon again. [MUSIC PLAYING]  