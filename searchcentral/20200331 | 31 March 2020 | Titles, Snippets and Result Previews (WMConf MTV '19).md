[![Titles, Snippets and Result Previews (WMConf MTV '19)](https://i.ytimg.com/vi/ezLO7yC4aFo/hqdefault.jpg)](https://www.youtube.com/watch?v=ezLO7yC4aFo)

## Titles, Snippets and Result Previews (WMConf MTV '19)

Phiroze Parakh, Software Engineer at Google, discusses the core pillars for result previews: relevance, guidance, depth, and diversity. Find out how titles, snippets, pictures, and videos are shown in Google Search.



Create good titles and snippets in Search Results → https://goo.gle/2ZflXzh 



Watch all the recorded talks from WMConf MTV '19 → https://goo.gle/2QHcmy6 



Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral event: Webmaster Conference 2019; re_ty: Publish; product: Search Console - General; fullname: Phiroze Parakh;



#### [0:00:00](https://www.youtube.com/watch?v=ezLO7yC4aFo&t=0) |  PHIROZE PARAKH: So my name's Phiroze Parakh,

and I'm going to be talking about titles, snippets, and result previews. My general area of focus is core ranking in search, but the last few years I was asked to look into this area about result previews. And there's a pretty good reason for it. If you think about it, on a search page, one of the large tasks that a user has is to find the content they want, find the page they want to get to. And in the world of 10 blue links,  

#### [0:00:30](https://www.youtube.com/watch?v=ezLO7yC4aFo&t=30) |  this was the only information they had,

literally, was a title, and a snippet, and perhaps the URL. So part of what we did was we rethought what would be the important pillars for an effort around result previews. So primary to our goal, of course, is relevance to the user need. We certainly cannot have previews not be relevant to the user query. Our second goal would be to make sure that whatever preview we generated actually helped users make a choice.  

#### [0:01:00](https://www.youtube.com/watch?v=ezLO7yC4aFo&t=60) |  We wouldn't just generate previews absent mind

of that. A third one would be we would want to illuminate the depth of content within websites. I personally believe that there's a ton of content written by wonderful people out there, like yourself. And it's important for users to understand that there is a lot of relevant information within sites. And if they don't know that information is within that site, they're unlikely to visit it. So this is a large pillar.  

#### [0:01:30](https://www.youtube.com/watch?v=ezLO7yC4aFo&t=90) |  And the final one was this notion

of diversity. There is a ton of different kind of content out there, from imagery, to videos, to forums, to lists, to tables. It's sort of boundless, I think, in terms of human imagination. And so we needed to catch up, and we needed to be able to express the diversity of the content that was out there in the ecosystem. And our sense was, if we did this, then people would benefit, users would benefit. And then consequently, the ecosystem would benefit.  

![](https://i.ytimg.com/vi/ezLO7yC4aFo/hq1.jpg)



#### [0:02:00](https://www.youtube.com/watch?v=ezLO7yC4aFo&t=120) |  So here's what we had to work

with. We had to work with something called attribution, which is the source of the site, the name of the site, the title itself, so the URL, and then this abstract notion of a content preview with its character limits and size limits. So in the next few slides, I'm going to talk through some of the newer formats that we have built out. These are all algorithmic, driven  

#### [0:02:30](https://www.youtube.com/watch?v=ezLO7yC4aFo&t=150) |  by those original pillars. But as you'll

see, they're actually quite useful for users. We were putting a lot of effort. It's not that the previews themselves were just built without effort. Here's an example of us attempting to change the snippet in response to the query. The very same algorithm that decides that a page is relevant for a query can be used to decide what part of the page should be relevant for the user, if they were to choose it.  

#### [0:03:00](https://www.youtube.com/watch?v=ezLO7yC4aFo&t=180) |  So if you change the query, you

can expect your snippet to change. And you can expect the user to read that to understand if that page, indeed, is relevant for them or not. But we can do more than that, so an example. One of the things we discovered-- I think it was around 2016, 2017-- was that images really help users choose between different results. There's often this latent desire. I want to see a particular type of image. I want to see a particular type of flower, or I'm looking for a particular type of shoe. And the image suddenly becomes exceedingly relevant for them.  

#### [0:03:30](https://www.youtube.com/watch?v=ezLO7yC4aFo&t=210) |  So we can algorithmically extract relevant images

from the page and show them. The placement's on the right. This is important, because you want the image to be secondary to the main source of information, which is the title and the snippet. Occasionally, we can extract galleries. This is when the content of the page cannot be rendered by a single image, rather the user would benefit if they saw a sense of this kind of content, the kind of imagery on the page.  

![](https://i.ytimg.com/vi/ezLO7yC4aFo/hq2.jpg)



#### [0:04:00](https://www.youtube.com/watch?v=ezLO7yC4aFo&t=240) |  And we make sure not to use

all the images. There's limits on what fraction is used. And as a consequence, we noticed that users actually would start visiting a greater diversity of sites. So in a strong sense, this helped us understand that this can benefit the ecosystem. Following images, the obvious thing to do is then look at videos. And you can understand similarly that you're going to look for relevant videos. There could be multiple videos on the page,  

#### [0:04:30](https://www.youtube.com/watch?v=ezLO7yC4aFo&t=270) |  but you're going to look for the

relevant one. And you can mutate your preview type, depending on whether the video is the dominant content on the page. And you'll see this notion in subsequent previews, too, or where it is only supportive, and therefore on the right. If you wanted to express the depth of content within sites, then within that height limit of ours, the only information we have is this ability to generate what are called site links. And these are links to pages within your site  

#### [0:05:00](https://www.youtube.com/watch?v=ezLO7yC4aFo&t=300) |  that we believe are relevant for the

user. So if you're looking at a restaurant, then clearly, contact, drinks, private events, finding tables-- these are all links that can be very useful for users. These are all extracted algorithmically. Occasionally, the site structure does help us, and it drives traffic into your site. Sitelink images was another change we added when we realized that if their page had image previews, then it should be simple for us to, again, algorithmically decide whether the sitelinks could  

#### [0:05:30](https://www.youtube.com/watch?v=ezLO7yC4aFo&t=330) |  have images. And this actually helped in

cases where the sitelinks don't really help the user disambiguate the type of content that's on your site. We could go further. We went down this path of entity facts. This is when, as you can imagine, as in the bottom right, in this case, I think Killan Jornet is a wrestler, and there are facts around this wrestler that  

![](https://i.ytimg.com/vi/ezLO7yC4aFo/hq3.jpg)



#### [0:06:00](https://www.youtube.com/watch?v=ezLO7yC4aFo&t=360) |  are pertinent to the user. Entity facts

are a way for us to illuminate some of those facts, so that people can then say, oh, this site is pretty legitimate. It does explain facts about this user, and therefore, it's deep. And therefore, I'm willing to go to this site. Similarly, forums-- I think Ellen had talked about structured markup to help us understand forums, Q&A sites. There are tons of forums out there  

#### [0:06:30](https://www.youtube.com/watch?v=ezLO7yC4aFo&t=390) |  that don't have structured markup on them,

and it's a big disservice to users if we're not able to help people understand that this is a forum and help people understand what kind of content's out there. So algorithmically, we can extract posts, subject to our ability to do so. We choose the forum cluster. There's a set of related content on the site that might be related to the query for the user. We certainly see users engaging with this a lot. And we know that if you're going to provide us with markup, then we certainly want to use that.  

#### [0:07:00](https://www.youtube.com/watch?v=ezLO7yC4aFo&t=420) |  And so markup always takes priority over

these algorithmic forms. We can do the same thing with tables and lists. So if your site has a dominant table, and we want to show the preview for that page, then clearly, showing that table to some extent is a better thing for the user, because they can understand this is really what the content is on this page. And the structure and the position of that HTML does guide the preview.  

#### [0:07:30](https://www.youtube.com/watch?v=ezLO7yC4aFo&t=450) |  So in summary, relevance infuses everything. These

previews have to be relevant to the user. They have to be relevant for the query. Attribution helps the user choose the source. We make a lot of effort to ensure that the depth of your content is well expressed, and therefore, a user is invited to visit your site. And you can see that both with sitelinks and forums. And we make sure that we have a diversity of preview formats to support the ecosystem.  

#### [0:08:00](https://www.youtube.com/watch?v=ezLO7yC4aFo&t=480) |  Thank you. [MUSIC PLAYING]  

