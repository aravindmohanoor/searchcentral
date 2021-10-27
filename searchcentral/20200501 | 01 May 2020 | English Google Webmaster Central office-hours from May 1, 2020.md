[![English Google Webmaster Central office-hours from May 1, 2020](https://i.ytimg.com/vi/mc2cvOh-GGU/maxresdefault.jpg)](https://www.youtube.com/watch?v=mc2cvOh-GGU)

## English Google Webmaster Central office-hours from May 1, 2020

This is a recording of the Google Webmaster Central office-hours hangout from DATEDATE. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Watch out for new sessions, and add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



Feel free to join us - we welcome webmasters of all levels!



#### [0:00:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=0) |  JOHN MUELLER: All right. Welcome, everyone, to

today's Webmaster Central office hours hangout. My name is John Mueller. I'm a webmaster trends analyst here at Google in Switzerland. Well, at home at least. And part of what we do are this office hour hangouts where folks can join in and ask questions around their website, around search, Google, SEO, whatever. And we'll try to find answers. As always, a bunch of stuff was submitted already on YouTube,  

#### [0:00:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=30) |  but if any of you want to

get started with the first question, you're welcome to jump in now. KRISTOFFER HOLTEN: Hey, John, hi. JOHN MUELLER: Hi. KRISTOFFER HOLTEN: Hi, I have a quick question about the hreflang on this Shopify web shops. So we have both the visitors from UK and from US and from Australia and from New Zealand, other English language speaking countries. So how do we deal with duplicate content  

#### [0:01:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=60) |  since our private descriptions and our collection

pages do have the same content? But how do we deal with duplicate content and hreflang on these pages? JOHN MUELLER: Good question. So in general, you don't really need to worry about the duplicate content part. That's something that we can usually figure out on our own. I think the bigger question is really whether or not  

#### [0:01:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=90) |  you need to have country-specific versions of

those pages indexed or not. And for the most part, I would tend towards having fewer pages indexed rather than more pages. So if there's any way that you can limit the number of country-specific pages that you actually make available for indexing, that tends to make everything a lot easier because we can crawl faster, we can index things better, we can rank them a little bit better. Just everything is a lot easier if there are fewer versions.  

#### [0:02:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=120) |  If you do need to make country-specific

pages, then using the hreflang annotations is a good idea. With hreflang, you can do that on a per page basis. So you don't necessarily need to do it across all types of pages, or across all pages within the website in general. I see some websites do it for their home pages, for example, because that's something that's kind of unique per country. But maybe the products are actually the same across different countries.  

#### [0:02:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=150) |  So that's something where you can try

to find that balance yourself. And really, the main thing that I would try to focus on is just using fewer versions, rather than just going out and-- like, I can automate this, put it on 50 country versions, and then five language versions per country. It's easier to do programmatically, but then you create all of these urls, and it just makes things so much harder. KRISTOFFER HOLTEN: All right, that makes sense. So would you say that the hreflang text  

#### [0:03:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=180) |  kind of eliminates duplicate content? Or do

we still have to localize the English language, because you in the UK are a little different? JOHN MUELLER: The hreflang helps us to recognize which URL to show, but we would still recognize that it's duplicate content in cases like this, and what would happen is for indexing, we would try to fold it together. Pick one version for indexing, and then when showing it to the user, we'll try to swap out the URL against the appropriate local version.  

#### [0:03:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=210) |  So it's not something that's, like, critical,

that like, you'll get a manual action, or something will go wrong with your website. It's just kind of-- it makes it a little bit trickier. KRISTOFFER HOLTEN: Cool. Thanks a lot, John. That's everything. JOHN MUELLER: Sure. All right, someone else had a question as well, I think. IVAN KOKUTI: Hi, John. JOHN MUELLER: Hi. IVAN KOKUTI: Hi. I wrote it in the comments, but I can ask--  

#### [0:04:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=240) |  our URLs use pluses in our product

description, mailing pages-- is this best practice, or should we be using dashes? Or does it make much difference to the crawler? For crawlability? JOHN MUELLER: No, it doesn't make any difference. For crawling, usually-- people tend to use dashes more because it makes everything a little bit easier with regards to kind of when you're crawling  

#### [0:04:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=270) |  it yourself, or when you're looking at

it yourself, because a lot of tools, they swap out the plus against the space. And then if you have spaces in URLs, then sometimes things are a bit trickier to track. Like, if you have them in an Excel sheet, or some other text file with spaces in the URL, sometimes it makes things a little bit harder. That's why people tend to go towards dashes or underscores, but pluses work just as well. Purely from a technical point of view, that should work.  

#### [0:05:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=300) |  IVAN KOKUTI: OK. That's good to know.

I've got another question about local search. JOHN MUELLER: Sure. IVAN KOKUTI: Well, before-- pre-lockdown, we were using the Google blog, the post section. In regards to that, because we've got over-- probably over 400 stores. Could we post the same blog post on all 400 stores,  

#### [0:05:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=330) |  or should it be unique to each

store, each location? Does it-- does it matter? JOHN MUELLER: I assume you mean the Google My Business posts? Yeah? IVAN KOKUTI: Yeah. JOHN MUELLER: I don't know offhand. My understanding is you can do whatever you want there, because it's really only visible for those local locations. But I would probably double check with maybe some folks in the Google My Business help forum,  

#### [0:06:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=360) |  just to make sure. Because as far

as I understand, there's an API now for posts, as well. So that sounds like they're OK with posting things a little bit more frequently. IVAN KOKUTI: OK. Thank you. JOHN MUELLER: Sure. MICHAEL LEWITTES: John? Hi. How are you? I have a question. I notice sometimes that companies  

#### [0:06:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=390) |  do their categories-- let's say company name

dot com, backslash product. And then they'll do the same thing, backslash pricing. And then for some odd reason, on that same site, they'll do blog dot company name dot com. Is there a preferred structure? Should it have been backslash blog for consistency? JOHN MUELLER: That's essentially up to the site. Sometimes people use it on a subdomain, just purely  

#### [0:07:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=420) |  for technical reasons. If they have a

different infrastructure for the blog, then maybe they'll put it on a different subdomain so they can host it separately. But just purely from an SEO point of view, you can do that however you want. I tend to favor having everything on the same hostname, just to make it easier for tracking. So if you have a blog, maybe put it in a subdirectory instead of a subdomain. But essentially, you can do it any way you want.  

#### [0:07:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=450) |  MICHAEL LEWITTES: OK, and one other quick

question. I noticed on Google documents that the linking internally sort of takes you-- doesn't take you to a separate tab. Usually in the midst of, like, a white paper or something, if you click on the link, it will take you to what it's referencing. Is there a reason for that? I mean, I've always thought, like, a separate tab just makes it easier to come back. But I have noticed that on Google documents, and didn't know if that was a best practice,  

#### [0:08:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=480) |  or just that's your style? JOHN MUELLER:

I really don't know. I never noticed that. At least from an SEO point of view, it doesn't change anything if you open it in a new tab, or within the same tab. So that probably is OK. My guess is it just depends on whoever was writing that content. I know for some areas, the tech writers have very clear guidelines on how to structure things, just to make things  

#### [0:08:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=510) |  as consistent as possible. But it might

be that maybe in white papers, or in blog posts people are a little bit more flexible, and just try things out in different ways. MICHAEL LEWITTES: OK. Thank you. JOHN MUELLER: Sure. KRISTOFFER HOLTEN: Hey, John, quick other question. I'm using the change-- I know this is not a support forum, but I'm using the change of the address tool in search console, and I've had a website being moved since October 19th. I see this on multiple of my sites,  

#### [0:09:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=540) |  and I saw that last week you

mentioned something about having redirects up for at least six months. So what should we do about the address tool that's taking longer than usual, or expected? JOHN MUELLER: So you set up the change of address, and you also have the redirect in place? KRISTOFFER HOLTEN: Yes. Everything is still in place. Been in place since October, yeah. JOHN MUELLER: Yeah. And what are you seeing? Or what is-- KRISTOFFER HOLTEN: It just says-- still says  

#### [0:09:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=570) |  this website is being moved. JOHN MUELLER:

Oh, OK. Yeah. I think that setting just remains in place for a certain period of time. So it's just-- essentially just the UI in Search Console that says, by the way, like, if you want to do something with the website, keep in mind that you actually wanted to have it moved somewhere else. KRISTOFFER HOLTEN: All right, thanks. JOHN MUELLER: OK. Let me run through some of the submitted questions. We probably have more room for your questions,  

#### [0:10:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=600) |  as well, along the way. And if

there is something that comes up in between that kind of fits to one of the questions, feel free to jump in. Let's see-- the first one, does the link value deprecate with age, like the older link is less value at forwards? I don't know. Maybe it should be the opposite, right? It's like, the older the link is, maybe the stronger it should be. But just purely from an SEO point of view-- on the one hand, it feels like you're probably  

#### [0:10:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=630) |  focusing too much on links. So that's

kind of the one thing. On the other hand, it's not so much that we keep track of age of the links, but rather that sites evolve over time. So for example, if you get a link from a newspaper website, and that's in an article that's currently linked on the front page, because it's a really important article, then obviously that's going to be a really important link for us, because we notice that link is there. It's linked fairly closely to the home page.  

#### [0:11:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=660) |  It's something that's really relevant at the

moment. However, that news website is going to evolve, and over time that article that might have been on the front page is suddenly, like, on page two, or is in an archive somewhere, or is in a section for articles from the year 2020, which might be, like, 50 years ago at some point. So it's not as relevant anymore there. So it's not so much that the link itself is aging, but rather that the website where that link was  

#### [0:11:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=690) |  has evolved. And over time, that place

where that link was is no longer as relevant as it used to be. So that's something that, especially when it comes to news websites where things are changing fairly quickly, that's something that's definitely always involved. If we have 10 sub pages with a list of product categories, and all of them have canonical instruction directed to the first of them, how does this  

#### [0:12:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=720) |  affect, from a ranking point of view,

the products from sub-pages 2 to 10 of the list? This is something that comes up from time to time. It's like, you have a paginated touch, and you just want the first page indexed, so you set the canonical to the first page of that set. And generally, what would happen here is that we would see that canonical, and if we process that canonical and think, oh, this is a good selection, then we will only index the first page.  

#### [0:12:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=750) |  So essentially, everything that is on these

pages where you're saying this page itself is not canonical, we would drop that from the index. We would not index that. Assuming, again, we process that canonical and say, oh, you're right, this is a good selection. Canonicalization is a bit tricky in that it's not just the rel canonical on a page that we use. We do want to make sure that the content of the page is equivalent. We take into account other factors as well, so it's not, like, a clear one to one  

#### [0:13:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=780) |  relationship there. But essentially, if you have

things on pages and they're only mentioned on those specific pages, and at the same time, you're telling us that we should be indexing a different page, then it's very likely that those things on the non-canonical canonical page will essentially be dropped from our search results, because you're telling us that we shouldn't be indexing them. Is there any difference between link value  

#### [0:13:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=810) |  from static and main content? I mean,

links from navigations or product pages, do they have the same value? Again, it feels a little bit like you're focusing too much on links, rather than trying to make a website that works well for users. The tricky part with a lot of these things is obviously that we try to make our algorithms so that they respond to things similar to how users would respond. So if you're trying to essentially game the algorithms  

#### [0:14:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=840) |  the way that they're set up now,

that's something that if users change their behavior, and users decide, oh, this kind of content is no longer as interesting to me, or no longer as useful for me, then that's something where you're essentially stuck with that old version. So with this specific situation, usually what happens here is we do focus on the primary content on the page. And that's something that makes sense from a user point of view. If you have one page, then usually you  

![](https://i.ytimg.com/vi/mc2cvOh-GGU/maxres1.jpg)



#### [0:14:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=870) |  focus on what is actually unique about

this page, and you kind of ignore the rest. I mean, you still use it, but you primarily focus on the primary content. Yeah. So my general recommendation here, if you're doing internal linking, is essentially just to focus on making your website work well for users. We have a number of stores and our store addresses are also displayed on certain category  

#### [0:15:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=900) |  pages, which offer those services specific to

those stores. Next to the text of those addresses, we also have an internal link called Branch Details, going to a specific branch information page. How well does Google understand the association between the two with such a generic text anchor? From an SEO point of view, should we make the anchor more specific and have the city name, or the branch something which distinguishes it from other branches on other pages,  

#### [0:15:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=930) |  like buy product A from our B

branch, or does that sound like too much? So this is something where we try to pull in, essentially, the information that we have about your website. The different pages that we know. The kinds of content that we have on your site. So if you have one page that's about one specific topic and from there you link to other pages within your website which are about kind of a sub-topic of that, then it's not so much  

#### [0:16:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=960) |  the case that you need to provide

all of the context through the anchor text, but rather we understand a little bit of that through the linking, as well. So in a case like this, or in a general case where you have category pages, and then you have subcategories, or maybe products that you're linking to from those higher level pages, there's not really a need to provide full context of that category page on every link that you have there.  

#### [0:16:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=990) |  So if you have maybe a shoe

store, obviously, like everyone, I guess-- if you have a shoe store and you have a category for running shoes, and as a subcategory, maybe you have-- I don't know, different colored running shoes. So maybe you'd have, like, blue running shoes, or yellow running shoes-- it's not so much the case that you need to provide the full context of all of those details with every link that you have on the page  

#### [0:17:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1020) |  to the individual product. So you wouldn't

need to, when you're linking to a specific product, say, well, this is a running shoe, and it's in yellow, and it's this brand, or this type of running shoe. But instead, it's usually enough just to provide kind of the more detailed context there. And that makes sense for users, as well, because when users are looking at the page, they focus on the parts that are kind of unique, that stand out with regards to the link to the individual products.  

#### [0:17:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1050) |  It's not-- it wouldn't really make it

so useful for them if you have a list of, let's say, individual running shoes, and for each of the shoes, you mention all of the attributes of the categories that are higher there, as well. So usually instead, it just makes sense like, oh, you've drilled down. Like, the breadcrumb trail lets you know what the categories are. And you just want the more specific information there. So from that point of view, I'd try  

#### [0:18:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1080) |  to just focus the anchor text on

what makes sense. What's kind of unique within the existing context of those pages? I want to move some of my best articles from one domain to a new one, and I don't want to redirect or move the whole domain to avoid sending bad signals to the good ones, as well. I want to start a completely fresh site, from an algorithm point of view. What's the best way to do it? Should I delete the content of my old domain first, and then add it as a new domain?  

#### [0:18:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1110) |  Or what's the best way to avoid

cross domain duplicate content issues? Would now indexing the old articles help if the content stayed live on the old domain, as well? What about links that go to those articles that I want to move? Any way to safely redirect them without harming the new site? You know, I think this is a tricky situation where you kind of need to make up your mind what you want. Because on the one hand, you're saying  

#### [0:19:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1140) |  you want to redirect to a different

domain, and you want to keep all of the good things. On the other hand, you're saying you don't actually want to be associated with that old domain. You want to start fresh, right? So it's something where you almost need to make up your mind there. And depending on how that works out, that's something where you can kind of go one direction, or go the other direction. I think it's generally fine to take individual pieces of content, and to redirect them  

#### [0:19:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1170) |  to other websites. It's important to keep

in mind that what you're doing is kind of splitting the website up into individual pieces, which means from an algorithm point of view, it tends to be a little bit harder for us to understand exactly how we should process that. So essentially, we need to figure out which of these signals we can kind of forward, which of these signals we have to recalculate.  

#### [0:20:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1200) |  Looking at the new website, looking at

the old website. And from a practical point of view, that tends to mean that things just take a lot longer to be processed. So if you're moving one to one, from one domain to another, that's something that's easy for us to process. If you're splitting things up, or if you're merging things together, that's always going to be a lot harder. So that's just purely from splitting things up. With regards to kind of not being associated with the old website and still having something  

#### [0:20:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1230) |  on the new website, usually my recommendation

here is to-- like, if you want to start completely fresh, make sure you're starting completely fresh. So avoid reusing the existing content, avoid reusing kind of the existing URL structure. Avoid redirecting or linking to the new website. Because if you really want to start fresh, if you realize, for example, you did a lot of things wrong and it's going to take so much time to actually clean up  

#### [0:21:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1260) |  all of these things that happened over

the years, then starting completely fresh makes it such that it's like, we can really start fresh with a new website. Whereas as soon as you do redirects, or set up links, or set up canonicals, or reuse the same content on another website, then suddenly it's a situation where our algorithms look at that new website and say, well, this is actually part of the old website. We will help the webmaster because clearly, they forgot  

#### [0:21:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1290) |  to set up a site move here.

We will help the webmaster by linking these two together, and by treating them as one website. And that sounds like that's the kind of thing that you want to avoid. So if you really want to separate things out, do that completely, and do that as cleanly as possible. KRISTOFFER HOLTEN: John, quick follow up question to that. JOHN MUELLER: Sure. KRISTOFFER HOLTEN: If I were to trash my old website and start a new one, would Google--  

#### [0:22:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1320) |  if someone picked up my old website

and restored my content, would Google know that it's a new owner? Do they check-- any chance? Or am I just stuck with a competitor that took my old website, and my content? Should I keep the domain? Is that-- JOHN MUELLER: Yeah. I would definitely keep the domain. That's something where, especially if you've built up something over time, I would try to keep those domains as long as possible. You don't need to put any content on them,  

#### [0:22:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1350) |  but by keeping the domain, you're kind

of preventing that situation that someone takes over the domain, and they reuse your old content, or they post something completely different. And then suddenly your brand, or your old brand name is associated with this content that you have no control over. KRISTOFFER HOLTEN: Are there any period of time where you have to put down a website and let it go blank before Google knows it's a new owner? JOHN MUELLER: Not necessarily. The tricky part is that sometimes people mess up  

#### [0:23:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1380) |  and the website goes down, or they

forget to renew, and then after a while they realize, and they renew their domain name, and they put the content back up. And so it's something where sometimes our algorithms are trying to be helpful, and that kind of might be too helpful in a case like this. KRISTOFFER HOLTEN: Yeah, OK. So you could be lucky with an expired domain? Or unlucky.  

#### [0:23:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1410) |  JOHN MUELLER: Yeah. Yeah. I definitely wouldn't

use expired domains as a clear strategy, because you just don't know what you're getting into with regards to kind of the positive or the negative sides. KRISTOFFER HOLTEN: All right, thanks. JOHN MUELLER: Sure. OK. I noticed that there were a few people who had some questions around Google Discover. I don't really have any clear answers on that at the moment, but I'll definitely pass that on to the team.  

#### [0:24:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1440) |  So I think some of these were

about an Android website in Italy that's not being shown in Google Discover, and some-- another one was also, I think, a tech site that was from Sweden, that was not being shown in Google Discover. I think the tricky part is Discover is a very organic search feature, in that there is no clear kind of things that you need to do to be shown in Discover, and it's very possible  

#### [0:24:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1470) |  that our algorithms decide, like, we should

highlight this website more in Discover, or maybe we should highlight this website a little bit less in Discover. And that's very hard to kind of take as something where Google is doing it correctly, or Google is doing it incorrectly, because there are obviously no queries involved. It's not the case that someone is searching for a website and then not seeing it, but rather we try to bubble up information that we  

#### [0:25:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1500) |  think is useful to users through Discover.

But like, some of these questions here have a lot of details. So I'll definitely copy and paste that over to the Discover team to see if there is something that on our site we need to improve, or if there is something that maybe we can improve in our documentation to make it a little bit easier to understand what you might be seeing in cases like this. We have a small budget to freshen things up  

#### [0:25:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1530) |  in our e-commerce website, so having to

choose between desktop or mobile. Am I correct in believing that both desktop and mobile rankings are derived from the Google indexing the mobile version of the website. So would you say if we had to choose from which one, from an SEO point of view, to improve, then the mobile version would be more important, as this would impact rankings on both? Although we receive more traffic on mobile, the bounce rate is also higher. So in general, if we've switched the website over  

#### [0:26:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1560) |  to mobile first indexing, which we've switched

most websites over to mobile first indexing now, then we would only be using the mobile version for indexing as a basis for understanding what is on the website, as a basis for understanding the context between individual URLs of a website, so we would really only be using the mobile version for that, especially if you have a different version on desktop and mobile, then we would essentially just be using the mobile version  

#### [0:26:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1590) |  there. So if you're really in this,

I'd say, tough situation that you need to decide which of your kind of versions is your favorite one to work on more, then if we've switched to mobile first indexing, then I think the mobile version is probably the one that you should be focusing on. However, I wouldn't say that you can completely delete the desktop version and everything will continue to be OK, because probably you still  

#### [0:27:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1620) |  have a lot of users on desktop,

as well. Usually, my recommendation for people who are working on the website and trying to figure out desktop or mobile is to find a way to move more of the content to a more responsive design, so that you just have one version. Because if you just have one version to maintain, then you don't have to make that choice, and by fixing the content once, or the pages once, then  

#### [0:27:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1650) |  you're essentially fixing it for all of

your users. So moving to a responsive design would make this a lot easier. If you absolutely can't move to a responsive design, you need to pick one or the other, and you really only care about SEO, which is kind of tricky in itself, then the mobile version would be the one to kind of focus on. Does the product listing page lose page drink or some other signals if the product listing page  

#### [0:28:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1680) |  has links pointing to filtered listing pages

that have meta robots, no index pages? So I think this kind of goes back to a theoretical understanding of how page rank flows within a website, and this is actually something that our systems are pretty good at. So it's not something where I would say that a normal website needs to worry about how these kind of pages are linked together with regards to how  

#### [0:28:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1710) |  page rank flows within a website. Usually,

the bigger impact here, especially with an e-commerce website, if it's a larger e-commerce website, is the crawling side. In that if you have links to a lot of filtered pages that have unique URLs, maybe there are extra filters or facets in those URLs themselves, then that's something where we would  

#### [0:29:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1740) |  have to go off and crawl all

of these pages before we recognize there's actually no index there. So from a crawling point of view, I would try to keep it as clean as possible, but purely from an indexing point of view, or from a page rank point of view, this is not something that I would really worry about. Does a link in the content of a page which already exists in the main navigation make any sense from a ranking point of view? So I think this kind of goes back  

#### [0:29:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1770) |  to links in the main content versus

in things like the sidebar in the footer, those kind of things. From my point of view, like, this-- this definitely makes sense if it makes sense for your users. Purely from an SEO point of view, if a link from one page to another already exists on a page, then having that same link there a second time doesn't change anything. But users are probably more important, and you probably want to make sure that they actually convert on your website.  

#### [0:30:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1800) |  So making a website that works well

for users would be my priority here. It's not that I would stop linking internally within a website just because you already have one link there, which might be enough from an SEO point of view. If an internal link is underneath some text but related to that topic, does Google still understand and recognize that, or should the internal link always be within the text? We do try to understand the context of internal links,  

#### [0:30:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1830) |  so things like anchor text and the

text around that link, they do help us to understand a little bit more. But if you're asking, like, the link within a block of text or just right after a block of text, I don't think that plays any role at all. So that's not something I'd worry about. We have a number of categories on our e-commerce site with one or two items in them. While it might be easy for users to visually find them,  

#### [0:31:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1860) |  would it be better if these categories

were removed or 301'd, and the products moved into bigger categories, as currently those categories are weak and have created a lot more internal links going around the site? Yeah, so this is something that is something where you almost need to figure this out for your website individually. Usually it's more a question of if you  

#### [0:31:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1890) |  have kind of a flat website architecture

where everything is linked together, maybe where you have very few categories, or if you have a very, I don't know, deep website structure where essentially any user or search engine, if they want to go to a specific product page, they have to jump through a bunch of different categories, or subcategory sections to actually find those pages. And essentially what you want is something that's kind of a mix there. You don't want it too flat, because it's too flat, then it's hard to understand which pages belong together.  

#### [0:32:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1920) |  And you don't want it too deep,

because then users have to click around a lot to find those pages, and search engines have a lot more trouble kind of finding and recognizing the importance of individual pages on your website. So finding that kind of balanced size, where you have enough items in each category to kind of make sure that it's more of a-- I don't know, a balanced view of a website, where it's not too flat, not too deep-- that's something that I tend to recommend.  

#### [0:32:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1950) |  But there is no hard-- I don't

know, guideline where I'd say, like, two products is not enough, or you should make subcategories, if you have more than 20 products, that's something that you almost need to look at from the website to website basis. And it's sometimes hard because obviously, your business will grow over time, and you'll have more of some kind of products, and you'll have fewer of other kinds of products. And at some point, you almost need to restructure the kind of category,  

#### [0:33:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=1980) |  subcategory set up that you have there.

And purely from a search point of view, these kind of restructurings to make things a little bit more balanced, I'd say they definitely make sense. But it's always something that involves a lot of effort to make sure that you're setting up redirects and everything properly. So I wouldn't just blindly jump in and say two products is not enough,  

#### [0:33:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2010) |  I will redirect them and fix things.

There's a long question about Discover again. I'll take that to the team. Our blog section of our website just has a lot of articles, categorized by month they were uploaded. There is no grouping as such, as to putting all related articles within a particular section together, but there is some internal linking between related articles. Could that be the main reason that our articles are not  

#### [0:34:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2040) |  indexed anymore? They used to all be

indexed, but then after a particular algorithm update, you de-indexed them. It's the only part of the website that is de-indexed, even though the information and the articles are good quality. I don't think this would be a reason for our systems to de-index a lot of articles on our website. Essentially, we need to be able to discover those pages so  

#### [0:34:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2070) |  that we have the opportunity to go

out and index them. But if we can discover those pages, and they're just linked in a way that might not be optimal, then that generally wouldn't be a reason for us to say those pages themselves are not useful enough to actually be indexed. Usually when I see questions like this where it's like, we have a bunch of articles  

#### [0:35:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2100) |  and suddenly they're not being indexed as

much as they used to be, it's generally less of a technical issue, and more of a quality issue. So it's not so much that we can't find those pages, because probably they're still linked within your website, or at least they were findable in the past. It's probably not the case that we can't index them, because that's probably easy for you to check. And you can double check that there is not a no index, and that they can be crawled properly without crawl errors.  

#### [0:35:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2130) |  That's usually pretty easy to double check.

But it's more a matter of just our algorithms looking at that part of the website, or the website overall and saying, we don't know if it actually makes that much sense for us to index so many pages here. Maybe it's OK if we just index a smaller part of the website [INAUDIBLE] instead. So that's something where sometimes it's worth taking a hard look at your site,  

#### [0:36:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2160) |  or getting someone more neutral to look

at your website, and to give you some advice and say, like, well, it looks like all of these articles are about irrelevant things that happen at some point, and maybe they were relevant at some point in the past, but they're not so important anymore. It might be that someone looks at these articles and says, well, it looks like you've been rewriting existing articles from, maybe, other people's websites. Maybe that's not such a great thing to do.  

#### [0:36:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2190) |  Maybe that's something that Google doesn't really

appreciate-- which is definitely true. But all of these things are elements where sometimes when you're creating this website, it's like, your baby, and you're doing the best that you can to make it grow, but having someone neutral look at it can sometimes give you a little bit of a-- I don't know, a little bit of a kick to actually be a little bit more critical with your website, with your own content, and to find ways  

#### [0:37:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2220) |  to significantly improve it. And I realize

that's always hard to hear, and there is no simple path to significantly improving a website, but sometimes that's really the direction that you need to head if you care about this website, and the way that it's shown in search. When you search for basically anything-- meme generator-- those three pages of the same website show up. So there is one website that shows up,  

#### [0:37:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2250) |  and other sites don't show up, which

arguably have better meme generators. So I can't judge the quality of these meme generators, so it's really hard to say there. But in general, it can happen that a bunch of pages from the same website show up for individual queries. And that's something where with our algorithms, we try to limit the number of pages  

#### [0:38:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2280) |  that we show for normal, generic queries

from the same website. Usually that limit is-- I don't know, maybe two or three results from the same website. But if our algorithms have kind of a sense for the user actually searching for one specific website, then we will definitely show more results from that website. And sometimes, our algorithms are kind of on the edge there, or don't understand the query properly,  

#### [0:38:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2310) |  and they show more from one website

than maybe they should from others, as well. But in general, it's not something where we would say it's clearly broken if there are three pages showing from the same website. So that's something where if you're seeing individual queries where you feel, well, this could be improved if there were more diversity in those search results, then I would definitely use the feedback link on the bottom of the search results pages,  

#### [0:39:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2340) |  because that does go to the team

that works on these pages. But at the same time, I would also see it as something where reasonable people can argue in both directions on that topic, and it's not something where, for the most part, we would see that as a clear bug if we showed more pages from the same website in a particular query. Internal WordPress search question. href shows me duplicate content issues on my internal search  

#### [0:39:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2370) |  pages. Is this a problem for Google

even when they're no indexed? Can you tell us a best practice for internal search on content pages? So if these pages are blocked by robots text, blocked by no index-- no index robots meta tag-- then essentially, they would not be indexed, and we would not see that duplicate content. So just purely from that point of view,  

#### [0:40:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2400) |  that's something where probably it's good to

take this kind of feedback from tools, and to double check that it's working the way that you wanted, but in this particular case, I think that's OK. It's like, even if there's duplicate content on these pages, if they're not being indexed, then you're kind of doing the right thing. With regards to internal search pages in general, I would tend to differentiate between different kinds  

#### [0:40:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2430) |  of internal searches. In particular, if you

make your internal search pages so that they're more like category pages, then that feels like something that makes sense to be indexed. At least, maybe the first page of that. On the other hand, if the internal search pages are essentially any random keywords that people can provide and you will create a search page for that, then that feels like something that probably is not worth indexing individually, and then it's more a question of  

#### [0:41:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2460) |  should you be blocking these by robots

texts so that they don't go to your server at all, or should you just use no index? From our point of view, both of these are valid options. The robots text option makes a lot of sense if those searches on your website create a significant load, in that you don't want random crawlers to get stuck in those search pages and start trying to crawl through a whole bunch of pages like that.  

#### [0:41:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2490) |  On the other hand, using robots text

also means that we don't know that these pages should not be indexed, and it's possible that if someone links to one of these pages, we would index that page without knowing the content, of course. So no index might be better. I tend to focus more on the no index side rather than using robots text for internal search pages, just because that gives you a little bit more control. And again, if these search pages are  

#### [0:42:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2520) |  more like category pages in the end,

or if you use the same setup for your category pages as you would use for your internal searches, then having those category-like pages indexed is perfectly fine, because they're also useful for users. A client has a medical based information page, now they want to also create a community or forum on their subdomain. During the time of EAT, should they  

#### [0:42:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2550) |  totally no index the forum? Because normal

users will discuss there about medical topics, or does Google recognize that these topics are community driven? We want to avoid conflicts and problems with the main domain. So EAT is not really a ranking factor in the sense that you need to optimize those attributes for your website in order to rank well. So that's kind of though the one thing there.  

#### [0:43:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2580) |  But I would try to see this

more front from a user point of view, rather than purely an SEO point of view. And from a user point of view, it can certainly make sense to have some kind of a forum or community associated with an existing-- maybe a well-known medical brand. But you probably want to make sure that it's positioned in a way that it's really clear. That this is actually user generated content. Maybe it's not vettted by medical professionals.  

#### [0:43:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2610) |  Maybe it's people who are just anecdotally

giving advice on what they observed during-- like, maybe they had one of these diseases, as well. And anecdotally, they noticed that things got better when they did something specific. And purely from a medical point of view, that might be more correlation, not causation there. So it might not be, like, really clear medical advice  

![](https://i.ytimg.com/vi/mc2cvOh-GGU/maxres3.jpg)



#### [0:44:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2640) |  that people are posting there. So from

that point of view, you probably just want to make sure that it's positioned appropriately for users. So instead of focusing on how that would work from an SEO point of view, make sure it works well for users first. And then usually, the SEO side kind of falls into place on its own. So that's kind of the direction that I would head there.  

#### [0:44:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2670) |  If in some cases I can't automate

the site map on a back end, will crawler generated site map be a second best option? Or in this case, is it just better not to include an XML site map at all? I would strongly recommend finding ways to automate the site map file, because you really want to make sure that every small change that you make on a website is reflected in the site map file. And usually, that means if you have a larger website, it's a lot easier for us to actually find those changes.  

#### [0:45:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2700) |  I think if you're crawling your own

web site to generate a site map file, then you also have to keep in mind that maybe Google will just crawl your website and figure out which urls are there, as well. So it's hard to say that you're actually staying ahead of the curve by providing a site map file versus just letting Google crawl on its own right away. However, sometimes this does help us to get started with a website.  

#### [0:45:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2730) |  And even with smaller web sites, sometimes

if you change something that's kind of lower level within the website, then bubbling that up through an updated site map file can help. So my recommendation here would be to strongly look towards finding automated solutions for the site map file, but if you still want to provide your own site map file and you crawl your own website for that, then that's still an option. It's not something that you should avoid, let's say.  

#### [0:46:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2760) |  What would be the best solution if

we'd like to run a test for two weeks where we change bits of the content such as, for example, an H1? The current setup limits us to change the content directly on the page for a portion of the traffic. This means that users and crawlers see the changed H1. Could this impact rankings if the H1 is completely different to what we had? What if we ran a test like this every few weeks? So I think the question is kind of refined  

#### [0:46:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2790) |  to if I change my content temporarily,

will Google reflect that in search? And yes, if we see that the content has changed, then we will reflect that in search. So these kind of tests where you're changing the content to see kind of what the reaction is, they would tend to have a reaction. It might be that the reaction is very subtle, and very small. So if you're just kind of moving text blocks around on a page  

#### [0:47:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2820) |  and Google sees the same text in

just different positions on a page, then probably for the most part, that wouldn't change anything, but it would still be indexed as a new page. Because, like, you changed things on that page. If you ran such a test every couple of weeks in general, like you would have this change in indexing every couple of weeks, which from my point of view, probably just makes it harder to track the results properly. Because when it comes to search, it's a little bit unclear  

#### [0:47:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2850) |  when exactly a page would be reprocessed.

Let's say you're changing a page once a week, and we re-crawl crawl and update our index for that page every, let's say, six days, then depending on when you make those changes and that timeframe of when we re-crawl and reprocess that particular page, those effects might be visible in search in a way that makes it really hard to track back  

#### [0:48:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2880) |  what actually happened there. So if you're

making these kind of changes frequently on the same URLs, then it's really hard to determine which particular change resulted in which particular change when it came to search. If we could change the current setup, what would be the best option? For example, using a parameter to change the content, canonicalized to the product page without a parameter-- what would be a good solution that would allow a significant amount of testing that doesn't  

#### [0:48:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2910) |  hurt our organic visibility? So one approach

that I've seen in general four for AB testing is to set up different versions of the page, and then to canonicalize, like like you mentioned here, so that for indexing we would tend to focus on that canonical version. That seems like a good approach. The other thing to also keep in mind  

#### [0:49:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2940) |  is that if you're testing different things,

sometimes-- maybe it's also worth seeing how that reacts with regards to SEO, as well. Because maybe there are changes that you could make on a page which don't harm your visibility and search, but rather improve it. So that's something where sometimes maybe it doesn't make sense to completely decouple those tests from search.  

#### [0:49:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=2970) |  OK, wow, we just have a few

minutes left. Whole bunch of questions still remaining. But maybe we can switch over to any questions from you all in the meantime. ESBEN RASMUSSEN: I have a question, John. JOHN MUELLER: OK. ESBEN RASMUSSEN: OK, so I've got this website showing up in the search with the wrong opening hours. Actually, I thought the reason was due to some pages that were crawled back at Christmastime.  

#### [0:50:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=3000) |  They showed the Christmas opening hours. We

got Google to re-crawl all of those pages, checked it in search console, but still the wrong opening hours are displayed in the search, as sort of a special feature. Not as a snippet from the website itself. What data source would these be based on, now that everything seems to have been crawled correctly?  

#### [0:50:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=3030) |  JOHN MUELLER: I don't know. Hard to

say. In general, if it's from the page itself, then it might just be a matter of us re-crawling that page and being able to reprocess everything appropriately. Sometimes it's not updated from the first time that we re-crawl a page, especially kind of the derived metadata of a page. That's something that sometimes just takes a little bit longer to be reprocessed.  

#### [0:51:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=3060) |  That might be one thing. The other

thing is that it might also be that we're associating other data with that particular page. So for example, if you have a Google My Business listing and we know that it's associated with this website, and you update the hours in the Google My Business listing, then it's sometimes a matter of, well, do we kind of match those hours? Do we also show that on the website? Are these things that should be treated separately? That's sometimes tricky.  

#### [0:51:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=3090) |  So that's the other thing I might

look at there. If it's really been in place for a longer period of time and you're sure that things have been re-crawled or reprocessed a couple of times, then I'd love an example like that. If you could send it to me, I can take a look at that with the team, then. ESBEN RASMUSSEN: OK. I'll do that, then, because we've checked everything now. JOHN MUELLER: OK. Sure. You can just drop it here in the chat, and I can pick it up afterwards. ESBEN RASMUSSEN: It's already there. Yeah, great.  

#### [0:52:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=3120) |  JOHN MUELLER: Cool. ANDREJ KOCAK: Hello, John?

JOHN MUELLER: Hi. ESBEN RASMUSSEN: Yeah. OK, so I have a question regarding the length of how Google algorithms can remember signals and things from for a certain website, from the past. So let's say, like, the question is if these algorithms detect [INAUDIBLE] in the span of several years, or they in general focus on the current state of the website or page, minus the log for re-crawling,  

#### [0:52:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=3150) |  or something like that? So let's say

we screw something up, like, very badly, but then we fix it afterwards-- is there a possibility that it will be still due for next-- I don't know how many years? So let's say, one mistake in the past can trigger a penalty several years later? Is that possible? JOHN MUELLER: Usually, we try to focus on the current situation of a website.  

#### [0:53:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=3180) |  So if the current setup is correct,

then that's something that we would focus on there. There are very few situations where things linger a little bit longer. One might be with regards to links. So if there are external links to this website and you fix some of these, and it's just a matter of us reprocessing all of these things, and sometimes that can take a significant amount of time to be updated. Another one that I've seen from time to time  

#### [0:53:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=3210) |  is with regards to geo-targeting. If you

significantly change kind of the targeting of your website, then sometimes that just takes a while to be updated. I think for the most part, those are kind of the ones. There are some really weird edge cases sometimes that just stick around for a really long time. But that's not something where I'd say that's by design,  

#### [0:54:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=3240) |  and if you do something like this

wrong, then you're stuck with it forever. But usually more a matter of weird systems on our side that are not updating as quickly as they could be updating. So I think, especially when it comes to things like technical issues, that's something where if you fix those issues, if we can re-crawl and reprocess those pages, then that's fixed.  

#### [0:54:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=3270) |  That's not something that would linger for

longer. ANDREJ KOCAK: Mhm. So would you say it mostly concerns third parties? Like links, for example, right? That it's not so easily crawlable, like, when it's on our website? JOHN MUELLER: No. No. I think there might be some-- I mean, just because we look at the cases that go wrong,  

#### [0:55:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=3300) |  I feel like sometimes there are lots

of things that are going wrong. But it's probably just a very small subset of pages where I really see things kind of stick around a little bit longer than I'd like to see them stick around. I think another case where I've seen something similar like this happen is when we recognize that a website is really, really spammy. And they go out of thier way and they clean things  

#### [0:55:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=3330) |  up completely, then it's possible that our

algorithms might think, oh, well, this is just an affiliate website. We need to be a little bit more careful here, and that this kind of status sticks around for a little bit longer. Or for example, if we recognize that a website is an adult website, and at some time point we pick up that information. And if the website itself changes completely, or if the same domain name is reused for other purposes,  

#### [0:56:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=3360) |  that's something where it can sometimes take

a little bit longer for our algorithms to kind of get used to the current state. And by a little bit longer, that can sometimes be a couple months. That can also be several years. ANDREJ KOCAK: OK thank you. IVAN KOKUTI: John, sorry, I know I've asked a question already, but-- JOHN MUELLER: Sure, go for it. IVAN KOKUTI: Thanks. I've always wondered if high value keywords,  

#### [0:56:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=3390) |  like a big section of the population

is searching for certain keywords, is there any human part of the algorithm that quantifies these high value key terms, or is it all just algorithms called by bots? JOHN MUELLER: It is pretty much all algorithms. All the way, yeah.  

#### [0:57:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=3420) |  There are some aspects that might look

like there's a little bit more human touch to them. In particular, when we see that certain types of queries tend to be a lot more spammy, then what can happen is that the web spam team will go through those search results and try to figure out, like, which one of these are actually legitimate content, and which type of this content is more spam?  

#### [0:57:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=3450) |  And then it's not so much that

they're kind of like, determining the search results, determining the order, but rather they're looking at those queries and saying, well, this is a really important query. Lots of people are searching for it, and we're providing terrible search results because spammers are getting through our system, somehow. Therefore, we need to take my manual action on some of those sites. So it's not that we're filtering or sorting things out for those queries, but rather that the web spam team takes  

#### [0:58:00](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=3480) |  the time to look for the normal

type of spam within some of these queries. IVAN KOKUTI: OK. Yeah. Brilliant. JOHN MUELLER: OK. I think we're pretty much at time. I'll pause here, but I'll remain online a little bit. So if any of you want to stick around, you're welcome to stick around kind of off the record, I guess. So thank you all for joining in. Thanks for submitting some of your questions,  

#### [0:58:30](https://www.youtube.com/watch?v=mc2cvOh-GGU&t=3510) |  and for asking so many things. I

hope you all have a great weekend. In the meantime, I'll set up the next batch of office hours probably early next week. So if anything is still, missing you're welcome to drop those in there. Or, of course, drop by the Webmaster Help Forums, or catch us on Twitter. All right, thanks a lot, everyone. And wish you a great time until next time. SPEAKER 1: Thanks, John.  