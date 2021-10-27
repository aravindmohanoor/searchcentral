[![Canonicalization: SEO Mythbusting](https://i.ytimg.com/vi/gEWkYTPSEjs/maxresdefault.jpg)](https://www.youtube.com/watch?v=gEWkYTPSEjs)

## Canonicalization: SEO Mythbusting

In this episode of SEO Mythbusting season 2, Martin Splitt (Developer Advocate, Google) and Rachel Costello (Technical SEO Consultant, Builtvisible, at the time of recording Technical SEO & Content Manager, DeepCrawl) discuss the most common SEO questions and myths around canonicalization.



Specific timestamped topics discussed in this episode:

Canonicalization is not a topical grouping (0:00)

The most common canonicalization myths (1:29)

Is canonicalization a directive or a signal for Google Search? (2:01)

Should canonicalization be used as a redirect? (3:08)

What are the actual factors for duplication and deduplication? (4:25)

Site’s preference for the canonical URL vs user’s preference (7:33)

Canonicalization vs unique content on pages with a canonical tag (08:59)



Documentation mentioned in this episode:

Learn more about canonicalization → https://goo.gle/2DX7OjI 

Canonical URLS: How does Google pick the one? (video)  →  https://youtu.be/8j_hxBw5B4E



Watch more SEO Mythbusting episodes → 

https://goo.gle/SEO-Mythbusting  

Subscribe to Google Search Central → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=gEWkYTPSEjs&t=0) |  RACHEL COSTELLO: I think that a lot

of people see canonicalization as kind of topical grouping, which kind of isn't right at all. They need to, the pages need to be either identical or near. MARTIN SPLITT: Near identical, exactly. RACHEL COSTELLO: Yeah. MARTIN SPLITT: Yeah That's what it boils down to. Canonicalization is about duplication management. So basically, you want to remove duplication, so that we don't have to crawl things multiple times and we don't have to render and index things multiple times. And we also do not serve them all the time, like the same things basically in three different URLs.  

#### [0:00:30](https://www.youtube.com/watch?v=gEWkYTPSEjs&t=30) |  That's not good search results really, right?

[MUSIC PLAYING] Hello, everybody, and welcome to another episode of "SEO Mythbusting." With me today is Rachel Costello. You are a DeepCrawl Technical SEO and Content Manager. So what is it that you're doing every day?  

#### [0:01:00](https://www.youtube.com/watch?v=gEWkYTPSEjs&t=60) |  RACHEL COSTELLO: So I basically, well, I

used to be a technical SEO myself, and now I've moved into more of the content production side of things. So writing white papers, articles, to educate the wider dev community, digital marketing community, about technical SEO and the impact it has. MARTIN SPLITT: Awesome. That's really interesting. So you're seeing a bunch of misconceptions and confusions and stuff. And we picked an interesting topic, didn't we? RACHEL COSTELLO: We did. MARTIN SPLITT: What's the topic that you want to talk about today? RACHEL COSTELLO: It's all about canonicalization. MARTIN SPLITT: Ooh. All right. So what are the top myths and misconceptions  

#### [0:01:30](https://www.youtube.com/watch?v=gEWkYTPSEjs&t=90) |  that the community is dealing with? RACHEL

COSTELLO: So I think the first thing is that people think it is a directive. You set a canonical tag. It's going to be accepted. Another one, yeah exactly. Another one is that they kind of use it like a redirect. So if you have a product page that goes out of stock, you add a canonical to that category page, which doesn't really work that way. Because I've heard that the content needs to ideally be identical, if not very similar. MARTIN SPLITT: Yeah. RACHEL COSTELLO: So lots of things like that. MARTIN SPLITT: Oh, interesting.  

#### [0:02:00](https://www.youtube.com/watch?v=gEWkYTPSEjs&t=120) |  All right, let's start with the idea

that it is a directive, because it's not. RACHEL COSTELLO: No. MARTIN SPLITT: No. It is a signal for us, right? So when we talk about canonicalization, we're talking about detecting content or the same content or a very similar content that exists on different addresses and the different URLs, right? So we can do many different things to basically identify these things, right? We can just crawl multiple pages and see like, oh, this is actually the same content.  

![](https://i.ytimg.com/vi/gEWkYTPSEjs/maxres1.jpg)



#### [0:02:30](https://www.youtube.com/watch?v=gEWkYTPSEjs&t=150) |  We can also probably see if the

same links and like the same kind of context is used. But also, we can use the canonical tag, right? It's a signal. We're using many different signals to figure out if something is the same content or not. And canonicalization with a canonical tag is just one of them. So putting a canonical tag on pages that are not the same is not going to work. Putting a canonical tag on each of the pages that are exactly the same is also not going to work. It is a signal.  

#### [0:03:00](https://www.youtube.com/watch?v=gEWkYTPSEjs&t=180) |  It helps us identify what we want

to canonicalize, but it doesn't say you have to use this. That's a big one, I think. And you're right. And you should not use it as a redirection either. It's not a redirect. RACHEL COSTELLO: I think people just want to group link equity wherever they can, and it's maybe a bit of a desperate act to try and keep all of their link equity in one place. MARTIN SPLITT: It is, it is. Again, like canonicalization makes sense if you cross post the same content on different, I don't know, platforms, or different channels in slightly different locations  

#### [0:03:30](https://www.youtube.com/watch?v=gEWkYTPSEjs&t=210) |  for whatever reason you're doing that. That's

where canonicalization comes in. But if you are having something that goes out of stock, you should either redirect it to something similar that makes sense for the user at that point, or you can just tell us, this is a 404 for the moment and might come back. But do not just think that you can, no, it's not the same as a redirection. Also, you're wasting crawl budget that way. Because we are just not understanding like, oh, so you're saying this is the same as the other page, but it clearly is not.  

#### [0:04:00](https://www.youtube.com/watch?v=gEWkYTPSEjs&t=240) |  So we're just going to continue doing

this. But if you have two pages that are identical and you're not canonicalization or you're not canonicalizing them the way that it makes sense, then we kind of have to look into both as well. And sometimes we get these like flipping canonicals. Yeah. What are the typical problems that you're seeing that people are having besides these misconceptions? Like, what are people doing with them you think makes no sense? RACHEL COSTELLO: So I think people are just not quite sure. We've been trying to piece together  

#### [0:04:30](https://www.youtube.com/watch?v=gEWkYTPSEjs&t=270) |  what these different signals are that play

into [? effects. ?] You've got redirect, site maps, backlinks and things like that. I think people are trying to weigh up how many of these signals they should add. Maybe they're kind of doing it like a mass equation. Like if I do these two things, then this will mean that Google picks my canonical tag that I want. But it would just be interesting. I'm always interested to know more about how the signals are weighted, which ones are more preferential to others. Because sometimes I see that maybe, this is just my theory, that maybe Google puts more weighting to signals that  

#### [0:05:00](https://www.youtube.com/watch?v=gEWkYTPSEjs&t=300) |  are more likely to have been implemented

by human rather than maybe an auto-generated setting. I don't know if that has any. MARTIN SPLITT: Well, duplication and deduplication is actually done without much human interaction. So this is all automated signals. But we do like content fingerprinting. We look at things like, what is the gist of it really, what are the, what's the information here, how does this relate to the site structure, what does it say in the site map. So we're looking at a bunch of different factors,  

![](https://i.ytimg.com/vi/gEWkYTPSEjs/maxres2.jpg)



#### [0:05:30](https://www.youtube.com/watch?v=gEWkYTPSEjs&t=330) |  but they're mostly technical factors. RACHEL COSTELLO:

OK. MARTIN SPLITT: Yeah. And we are basically scoring them on an ongoing basis. So it's not that we're like determining at once and then just stick to it. We are always looking at the fresh content that we got from crawl, and then have a look at, does this change, is it changed, is it now very close to what it has been before. Now maybe something that has been in duplication is no longer a duplicate, because it has changed its contents. So that is absolutely possible, right? But sometimes, especially when pretty much everything is showing up in the same URL structure  

#### [0:06:00](https://www.youtube.com/watch?v=gEWkYTPSEjs&t=360) |  and it's maybe like different language versions

of the same thing, but it is the same content, then we might end up with a scoring that is very similar. So we have both versions. And let's say like one 0.49 and one is 0.51 of what we think is a duplication of the other, then it's really hard to pick which one will be the canonical. And that can change, right? A change in, I don't know, how we crawl things or how the crawler has fetch data  

#### [0:06:30](https://www.youtube.com/watch?v=gEWkYTPSEjs&t=390) |  and how it has been touching the

other pages beforehand might influence us to have like a tiny little bit of a jump in these two numbers. And then the other one is the canonical. So make sure that you're trying to give us as clear a signal as possible and not confuse the algorithms that are working with figuring out which one is the duplication of which other thing. Because if we are having two equal pieces of content, then how do we know which one we should pick?  

#### [0:07:00](https://www.youtube.com/watch?v=gEWkYTPSEjs&t=420) |  RACHEL COSTELLO: Exactly. And you don't want

Google to be in that position where they feel like they have to pick for you or Google bot feels like it has to pick for you. MARTIN SPLITT: And it makes everything more complicated on your side as well. RACHEL COSTELLO: Yeah. MARTIN SPLITT: Especially if you're using things like search console, right? We are, we're gathering data and showing you data based on the canonical. So if it starts flapping between two URLs, then that's going to look really weird. RACHEL COSTELLO: Mm-hmm. MARTIN SPLITT: So anything else that you would say is unclear about it or is there something that makes your life really hard when it comes  

#### [0:07:30](https://www.youtube.com/watch?v=gEWkYTPSEjs&t=450) |  to kind of canonicalization? RACHEL COSTELLO: I

think it's figuring out that certain thresholds you need to get to override Google's decision on what is the preferred URL. Because we can align all of our signals on site. I saw that John Mueller on the Ask Google Webmaster video about canonicalization, he said that there's two aspects. You've got kind of the on site signals, but you've also got what Google thinks that the user would most like to have a look at. MARTIN SPLITT: That's true, yeah.  

#### [0:08:00](https://www.youtube.com/watch?v=gEWkYTPSEjs&t=480) |  RACHEL COSTELLO: Yeah. MARTIN SPLITT: That depends

on a bunch of different things. So for instance, we might canonicalize one language version over the other. If you were telling us that all of them are canonical at the same time and they have pretty much the same content, especially if it's in the same language, just for different countries, then we might show the version to the searcher that the searcher is in the country of. So if we have a DE version and an AT version, of the German version and an Austrian version,  

![](https://i.ytimg.com/vi/gEWkYTPSEjs/maxres3.jpg)



#### [0:08:30](https://www.youtube.com/watch?v=gEWkYTPSEjs&t=510) |  that are pretty much the same. They

use the same currency. That might have even the same price, if you're unlucky. We might show different URLs to searchers, depending on where they are from. It makes more sense for a customer in Austria to see the Austrian version of the website rather than the German one, even though the German one is the canonical. So that might be a little confusing and misleading. RACHEL COSTELLO: Mm-hmm. MARTIN SPLITT: Any other questions from your side? RACHEL COSTELLO: Yeah, so there was one question I had in that. So if Google accepts the canonical tag on a page,  

#### [0:09:00](https://www.youtube.com/watch?v=gEWkYTPSEjs&t=540) |  that it will ignore any unique content

on that page. But then that's interesting, because surely, the pages have to be identical in the first place. This is something I've heard. If there's any unique content on the canonicalized page, it'll be ignored. So how would that work? Would the canonical tag not be accepted then, because they're slightly different pages? MARTIN SPLITT: So that depends on how different the unique content is. If you have mostly the same content and then maybe have like one sentence that is slightly different, then we might still think that it's pretty much the same thing.  

#### [0:09:30](https://www.youtube.com/watch?v=gEWkYTPSEjs&t=570) |  And then we would not see the

unique content necessarily if we think that it's just a copy of another page that is canonical. If this page has the canonical, then we would probably see the unique content there as well, because it's the page that we picked. However, if the content is completely different or different enough for the algorithms to decide that this is not a duplication, then the canonical is pointless. RACHEL COSTELLO: Mm-hmm. MARTIN SPLITT: Unless there's another page that happens, or another URL that happens to point to the exact same page. Then it becomes interesting again,  

#### [0:10:00](https://www.youtube.com/watch?v=gEWkYTPSEjs&t=600) |  because then we have two different pointers

to the same thing. And we get that oftentimes that people are like linking [? to ?] pages and accidentally have like some, I don't know, some URL parameter that basically gets ignored or doesn't actually matter, or there's like a slightly difference in the way that the URL looks like. Maybe you have like a slash de, something something, and then like slash de, something something question mark, cache equals falls or something like that, that doesn't really matter.  

#### [0:10:30](https://www.youtube.com/watch?v=gEWkYTPSEjs&t=630) |  Then we might canonicalize one of these

pages, and probably the one that does not have parameters and stuff. That also is debatable. It might also happen that we canonicalize something with parameters. But that way, you're again making it harder for us to pick a canonical, because if you're not saying like, oh, this is specifically the canonical we want, then it's back to guesswork. RACHEL COSTELLO: Mm-hmm. And I think that's the problem. People are just trying to group pages topically maybe with canonicalization, but that's not how it works. MARTIN SPLITT: That's not how it works, no.  

#### [0:11:00](https://www.youtube.com/watch?v=gEWkYTPSEjs&t=660) |  RACHEL COSTELLO: Thank you for confirming that.

MARTIN SPLITT: Canonical tags and canonicalization is about reducing duplication. RACHEL COSTELLO: Yes. MARTIN SPLITT: That's what it is for. RACHEL COSTELLO: Exactly MARTIN SPLITT: Awesome. Rachel, thank you so much for being here and talking a little bit about canonicalization with me. And I think that was useful. And I hope you enjoyed it. Have a good time. Bye bye. [MUSIC PLAYING] Hey, everyone. I hope you liked the previous episode. Next episode, me and Glenn are going to discuss site moves, right? GLENN: Site moves, domain name changes, URL migrations  

#### [0:11:30](https://www.youtube.com/watch?v=gEWkYTPSEjs&t=690) |  and more. MARTIN SPLITT: So stay tuned

and check it out.  