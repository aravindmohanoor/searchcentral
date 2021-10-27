[![English Google Webmaster Central office-hours from April 3, 2020](https://i.ytimg.com/vi/3n_4B7ZXjjI/maxresdefault.jpg)](https://www.youtube.com/watch?v=3n_4B7ZXjjI)

## English Google Webmaster Central office-hours from April 3, 2020

This is a recording of the Google Webmaster Central office-hours hangout from April 3, 2020. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Watch out for new sessions, and add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



Feel free to join us - we welcome webmasters of all levels!



Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=0) |  JOHN MUELLER: All right, welcome everyone to

today's Webmaster Central Office Hours Hangout. My name is John Mueller. I am a Webmaster trends analyst here at Google in Switzerland. And part of what we do are these office hour Hangouts, where people can join in and ask their questions around websites and web search. I hope you're all doing well regardless of the current crazy situation. And hopefully we can get some of these questions answered  

#### [0:00:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=30) |  that are still on your mind. All

right, bunch of stuff was already submitted, but you're welcome to jump in now if anyone wants to get started with the first question. REHAAN: I'd be happy to if no one else wants to go. JOHN MUELLER: All right, go for it. REHAAN: OK, so our website's been around for about 16 years. And we've never done any link building at all, not even S course, nothing like that. I looked in Google search console,  

#### [0:01:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=60) |  and I see that we have 320,000

adlinks. And when I go through the list, the bottom 90% are just no good. The domains look spammy. There's nothing good about them. And I know that you said that Google does a pretty good job of finding out what those domains are and just not counting them at all. But you also said that if you're losing sleep about this, then just go ahead and submit a disavow file. So I didn't do that. And I have two questions regarding that. One is you said that the disavow doesn't come into effect,  

#### [0:01:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=90) |  or at least it's-- maybe you didn't

see this, but I've read that the disavow doesn't come into effect until 100% of those links are crawled once again. So does that mean that every domain in that list has to be crawled? And only when it reaches 100% of that list as the disavow come into effect? Or does it happen on a domain by domain case within that file? JOHN MUELLER: It happens on a per year old basis  

#### [0:02:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=120) |  within that file. So as we recall

the individual links that are pointing at your site, if they are mentioned in your disavow file or their domain is mentioned in the disavow file, we will essentially just drop that link. So it's not something you have to wait for. It just happens incrementally. I think in general with a website that old, you're going to collect a lot of weird things over the years. And you probably also collect a lot  

#### [0:02:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=150) |  of good things over the years. So

I really-- I assume you probably would not need a disavow file for something like that. I don't know your website. I don't know what all has happened with it. But if it's a normal website, if like you said, you haven't been doing link building all these years, you didn't hire CEOs to do things that you don't know about, then probably-- I'd say 99% of the cases you wouldn't  

#### [0:03:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=180) |  need to do anything with the disavow.

REHAAN: Yeah, I wouldn't really be looking into it, except for with the Jan Co-opted, we took a huge dive in terms of traffic. So I'm just trying to do everything I can. JOHN MUELLER: No, that makes sense. Go through all of the small stuff, as well. That make sense. REHAAN: Thank you. JOHN MUELLER: All right, any other questions before we get started?  

#### [0:03:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=210) |  OK, well, in that case, I'll just

jump in through the questions that were submitted on YouTube. And if anyone has any comments along the way, or needs any further clarification, or disagrees, feel free to jump in. And we'll see where we can go today. OK, most of the WordPress themes have to navigation menus in the HTML code, one for desktop, one for mobile.  

#### [0:04:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=240) |  It means that they're duplicate menu URLs

on every page in the code. Is Google not able to understand the topic-- the logic of desktop, mobile menus? For example, when a page is displayed on a mobile phone, only the mobile menu is displayed, and the desktop menu's hidden. When a page is displayed on desktop, the mobile menu is hitting the desktop menu as displayed. Does Google Bot ignore the hidden menu links in the code? Does the hidden links penalize the website? So I think for the last question,  

#### [0:04:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=270) |  that's a definitive no. It's not the

case that these kind of links on a page cause any harm for a website. I think in general, it's probably something that can be cleaned up. I know a lot of sites use responsive design in a way that they have the HTML or the menu in there once and they use a CSS to display it in different ways, depending on desktop and mobile. So in many cases, you can probably  

#### [0:05:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=300) |  clean it up from a practical point

of view from Google's side. The links go to the same places from our side. That's essentially OK. It might be from a usability point of view might make sense to clean that up. It might be from a pure page size point of view, it would make sense to clean it up. But just purely from Google's CEO point of view, that's not something you'd need to change.  

#### [0:05:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=330) |  Our business has a larger number of

branches. But we have had to temporarily close some of them and redirect customers to collect their goods from other bigger branches. So we added an image highlighting the branches temporarily closed with a link to the nearest branch to that. This is currently no follow. Is this the best way to do it? Or is there anything you can recommend? We don't want to confuse Google by linking two branches and making it no follow. But we also don't want to harm rankings.  

#### [0:06:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=360) |  So you don't need to make this

a no follow link. That's something that seems like a perfectly natural link to have on a site. And probably, you already have the branches linked across each other in some other way anyway. So from that point of view, that's not something you'd need to do as a no follow. Using an image to let people know that this branch is closed  

#### [0:06:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=390) |  is also fine. Essentially, by, using an

image you prevent that text from being indexed. However, you can also use something like the data no snippet HTML attribute to let us know that something shouldn't be shown in a snippet. Which is essentially the same thing. From a usability point of view, using an image is obviously a lot harder to read. If someone is using a screen reader, they wouldn't see what is on that image. So that's something where I might use a normal HTML Alt  

#### [0:07:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=420) |  text banner instead of an image. But

ultimately, that's a small thing from a search point of view. The important part here is that you're not taking down the website completely, that you're not returning a 503 for these kind of situations because if you take the website down completely, or you serve a 503 response code, then what will happen is Google will drop that website from our search results.  

#### [0:07:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=450) |  And depending on how long this is

the case, it might be that it gets dropped from our index completely, which means people if they were searching explicitly for that branch, they wouldn't find anything. And similarly, once you reopen that branch, it'll essentially take a pretty much pretty long time for everything to get back into the index, to get back into a state where it's reasonably findable and search.  

#### [0:08:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=480) |  So the setup that you have here

with the banner pointing at a different branch, giving information about closure, that's something-- that's a perfect setup. And no follow or followed link, from my point of view, you can also use a normal followed link. I don't think that would change much. We're looking at redoing our navigation on our e-commerce sites. Would it be beneficial from an SEO point of view if popular product pages could be accessed directly  

#### [0:08:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=510) |  from the navigation as opposed to the

user going through a category page first? Can it benefit the apparent category page if all the linked power was going to child product pages? Or should they follow a hierarchy order as the value of any links gets diluted the more levels you go down? So in general, if you're thinking about page rank, which is in this direction. Then for a lot of websites, it is the case  

#### [0:09:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=540) |  that the home page is the primary

page that people link to. It's the strongest page on a website. And the closer items are linked from the home page, the more we can pass value onto them and say, well, these are pages that are really important from looking at this website because they're even linking to it from their home page, for example. So that's something where as you see that,  

#### [0:09:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=570) |  you might have individual products, which are

more important, for example, which could be more important in the sense that you're selling them really well. It could be that you have a better ROI on those products. It could be that it's something that you're trying to build up. If you have products like this, and you want to make sure that they're a little bit more visible in search, then linking them higher up within your website generally makes sense.  

#### [0:10:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=600) |  The important part here is that you're

giving Google a sense of hierarchy, a sense of these pages are more important, and these other pages are a little bit less important. So if you were to take that situation and say, well, all of my pages should be promoted because they're all the most important page on a website, then you're not giving Google that hierarchy anymore. Then suddenly, if everything is important, nothing is important. So really taking a bit of time to think about what  

#### [0:10:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=630) |  are the things that you really find

critical when a user comes to your home page that they find first. And usually, those are the things that you would want to link there. And usually those are the things that you want to give a little bit more value to when it comes to search. So that's the direction I would look at it there. So going back to your question, if there's something that you find really important, it's not so much that you need to link it directly from the general menu on a site but more that you link it  

#### [0:11:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=660) |  a little bit higher up within your

website, a little bit closer to the pages that tend to be more popular or stronger within your website. We had a lot of errors in our schema markup. So does Google still use it for pages that are OK? Or is it a site by date? The structure data markup is always on a per page basis and a per item basis. So if on a particular page, you have  

#### [0:11:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=690) |  some structured data that's valid and some

structured data that's invalid, then we'll use the structure data that's valid because we can understand that. And we'll just ignore the part that's invalid. So even within a page, we can pick those that are valid. And when you're looking at it across a bigger website overall, if there's some pages that have invalid structure data and others have valid structure data, we'll use a structured data from the pages that are valid.  

#### [0:12:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=720) |  It's not the case that we would

see as a website as being lower quality because of structured data errors. It's not the case that we would see a website as being higher quality because it has no structured data errors. Essentially with structured data, you're giving us a little bit more information about the pages and what you're writing about there. And we can take some of that to show the richer snippet, essentially, in the search results for those pages.  

#### [0:12:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=750) |  So it's not that we'll rank them

higher but more that we'll be able to show them in a slightly different way in search, which is often something that people are looking for. Because the clearer you can make it for your users what our page is about, the more likely they'll be able to say, well, this is really what I want. And you'll end up having more qualified visitors going to your website. Our product pages-- on product pages, it's informational. Behind tab's still discounted from a ranking point  

#### [0:13:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=780) |  of view or not. So I think

we've been talking about this for a number of Hangouts already. But essentially, with mobile first indexing, the content that is behind things like tabs or behind user interface elements that where it's not immediately visible on a page, that's something that we still take into account. So from purely from an SEO point of view, we can still use that.  

#### [0:13:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=810) |  We can still use that for ranking.

From a usability point of view, obviously, if you're putting stuff behind tabs, behind user interface elements which are perhaps unclear to users, then they won't be able to discover that content. So when people find your web pages in search and they think, oh, this is really the page that I wanted to because it has information on this topic that I was interested in. If they go to that page, and they see  

![](https://i.ytimg.com/vi/3n_4B7ZXjjI/maxres1.jpg)



#### [0:14:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=840) |  or they don't see any of that

content, then it's very likely that they'll go back to search and maybe click on something else. And so purely from a usability point of view, if something is important, then make sure it's important on your pages so that both search engines and users are able to find it as quickly as possible. Is Google controlling results related to some health terms, specifically Corona, by filtering out some specific types of sites?  

#### [0:14:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=870) |  If yes, how can we make sure

that it isn't controlling other terms as well? So I'm not aware of anything where we're manually filtering outside specifically around health terms. I do know that, specifically around health people, have very high expectations of search results. And therefore, we work really hard to make sure that the search results that we provide there are of the highest quality possible. So it's not so much that we need to filter things out,  

#### [0:15:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=900) |  but rather that we need to make

sure that our algorithms are really working as well as they should be. And having good algorithms that figure out what content is relevant for users or not, that's something that makes sense across the board. So it's not like we would only need to do that for one specific query. But rather, we can use these algorithms and use them everywhere. So whenever someone is searching for something  

#### [0:15:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=930) |  and we have an algorithm that helps

us to better understand what they're searching for, and to better show search results for that, and we will try to do that. So from that point of view, it's not that we're doing anything really special for these kind of terms, maybe apart from the various one boxes that we have in search where we try to highlight the more current information a little bit better. But apart from that, it's not that we're doing anything  

#### [0:16:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=960) |  that we wouldn't otherwise want to do

elsewhere in search. Will data highlighter be a part of the new search console? If possible, would you please let us know how many people are actively using it? So I don't have any metrics to share, sorry. But it is something that people are working on. So it's not something where I say we decided to just turn it off because if we wanted to just turn it off, we would have turned it off  

#### [0:16:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=990) |  already. In general, I see Data highlighter

as a way to get started with structured data and to try things out. I would not see that as something that you should be doing in the long run. So if you've noticed that your structured data is working well that you put together with Data Highlighter, then my really strong recommendation would be to implement that on the site directly so that you don't need to go through Data Highlighter.  

#### [0:17:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1020) |  Because that's something where if it's on

your site directly, then other search engines will be able to use that as well. And you'll be able to control it in a much more granular way. And you'll be able to say this is really this specific type of data and this is something slightly different rather than having to rely on Google's algorithms to figure that out. So from that point of view, if you've been using data highlighter regularly, I'd really strongly recommend that you find a way to implement that markup directly on your pages.  

#### [0:17:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1050) |  And if you're curious about structured data,

and you don't have time to install a plug-in or to implement structured data, then data highlighter is a great way to start. Should I take Moz domain authority too seriously because it's been declining? So I can't tell you how seriously you should be taking Moz's domain authority because that's not a metric that we provide. It's not something that we use at all and search.  

#### [0:18:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1080) |  That doesn't mean it's irrelevant for your

website. It might be the case that this gives you some information that is useful for you on your day to day work. So maybe there is something that you see there, which tells you, oh I'm doing things right. And you can show that to your boss and say, look, I've been doing things right. This metric that I'm looking at has been going up. Ultimately, it might be that you're looking at this, and you're seeing it going down. And if you determine, well, this metric  

#### [0:18:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1110) |  reflects this specific thing in search and

it's going down. Maybe that's something that you could be working on. But essentially, that's totally up to you. And So I can't tell you how seriously you should be taking this particular metric. It's similar to maybe other performance metrics where the pace speed inside score might be going up or down. I can't tell you how seriously you should be taking this. It's something where you should take that metric,  

#### [0:19:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1140) |  figure out what it determines and work

out for yourself how relevant that is for your current situation, for the work that you've been doing. So from that point of view, I can't say you should ignore it completely because maybe it is useful for you. And at the same time, I can't say it's the most critical thing you should be focusing on because your website will disappear from search if not. Both of those are not the case.  

#### [0:19:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1170) |  Everyone knows that a do follow link

will help to gain rank besides many other signals. So no one is linking to me with a do follow link as it cost some link juice for them as well. So how can a newbie like me grow my website if no one is willing to give me do follow links. And furthermore, many big sites have implemented site wide no follow policies. So it's just next to impossible for me as a newbie to get a do follow link from a big site. How can a newbie grow in 2020?  

#### [0:20:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1200) |  Or should they just write content in

the wait indefinitely? Is Google's system the same like others who favor only big players? Or will Google come up with new rules for links that will not differentiate between the type of links? So for that last one, I think we're already in that state where essentially, we're using no follow as a signal. It's not the case that we completely always ignore those links.  

#### [0:20:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1230) |  So especially in some locations, we've seen

that a lot of new websites are only linked with no follow links. And it would be a shame for us not to be able to discover those links and to show them in search. So that's something where we do try to follow more as a signal for the moment. In general, though, I think it's also worthwhile to think about the bigger picture when it comes  

#### [0:21:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1260) |  to the web and not just to

assume that you need to always just get links and then you'll be shown in search. But rather you're essentially opening up as a business as a store front in a bigger city. And it's both the case that you shouldn't just wait for someone to recommend your business nor the case that you should just open your business up. And you wait outside and see if anyone who happens to come by  

#### [0:21:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1290) |  and want to visit your business. But

rather you need to do different things to help promote your business. And sometimes you do things to call attention to your business in ways that encourage people to take note and to notice how this business exists and are doing some really great stuff. And then people will come. And then over time, recommendations will come as well. So that's not something that just happens automatically.  

#### [0:22:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1320) |  That might be that you have to

do advertising for a while to get things going. It might be that you have to do some kind of special activities to stand out even more than you otherwise would. But essentially, opening up a website is the same as opening up a business. And you need to do various things to get the ball rolling. And at some point, if you're doing really great work, if you're doing something that's really fantastic for four  

#### [0:22:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1350) |  people, then you will get recommendations from

various folks. And those recommendations could be in the form of do follow links. They could be in the form of follow links. They could be just general recommendations maybe on social media, where people are saying, well, this business is doing a great job. You should check it out. And you might just get more and more people coming back. So with all of that said, I would say that you need to think more than just looking at links.  

#### [0:23:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1380) |  And rather think about how you can

grow a business in general, which involves all kinds of activities. Can Google follow links behind JavaScript? From an SEO point of view, is there something that we need to be aware of so that we don't harm any internal linking? I don't know. We have an expert here on Javascript. MARTIN Yes, I actually also clarifying question there  

#### [0:23:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1410) |  because the question is, what do you

mean by JavaScript links. If your JavaScript link is with-- JavaScript links what you mean is a link that is injected by JavaScript as normal anchor tags and a HTML tag with an eight track that has a URL, even if it's JavaScript injected, we can totally discover that and use that scrolling later. If you are using something else like, I don't know, a button or a span or a link that has no traffic but has an on-kick handler, then no we cannot follow those.  

#### [0:24:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1440) |  JOHN MUELLER: Do you think that will

change at some point, Martin? MARTIN: Who knows. I'm bad at predicting the future, it turns out. So I would rather not say something too definite. But it could hypothetically happen that we find better ways to deal with things. But it is just a very resource intensive thing to actually click on everything, especially if it's not something interactive. It's a button and you can say, well, at least  

#### [0:24:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1470) |  it's interactive. If it's a date for

a span, then it's just a piece of text. So why would you click on a piece of text? And we would have to click on pretty much every piece of text. So that's a little bad. And also there are accessibility considerations there. So I would not expect this to change anytime soon but, who knows. JOHN MUELLER: OK what if you have some of those links in the HTML and you also have them with JavaScript? Does that causing you problems?  

#### [0:25:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1500) |  MARTIN: Sorry, I muted myself. That doesn't

really cause problems fundamentally. If you have it in the inital HTML, we might be able to pick it up a little earlier because we do run a link scan on the initial HTML. But with rendering picking up on speed, it shouldn't be that much of a difference. And it's not a problem anyway. JOHN MUELLER: Cool, OK. And you occasionally do these JavaScript office hours  

#### [0:25:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1530) |  as well, right? MARTIN: I do the

next one is next Wednesday, or actually Wednesday. So April the 8th, 7:00 PM Swiss time, you can just check out the calendar where you also find these office hours. And you can submit your questions on YouTube once I actually post the thing on YouTube, as well. JOHN MUELLER: Cool, OK. So Peter, if you need more information on JavaScript,  

#### [0:26:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1560) |  it sounds like you have an expert

that you can go to and get that directly. Cool, OK. If I use the subdomain of my parent company, would it prevent me from ranking for my own knowledge graph, since whenever people type relevant keywords, my parent companies knowledge graph will show up instead? I don't know how you mean that, specifically. So it's really hard to say.  

#### [0:26:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1590) |  If you want to send me some

queries or maybe post them on Twitter, that would be useful so that I can take a look. In general, it's probably not something where the subdomain or main domain is really the issue, but rather if we see that something is really strongly associated with one particular company, it might be that we showed that knowledge panel as background information regardless of these individual products, for example.  

#### [0:27:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1620) |  But it's really hard to say from

this kind of a question. So if you want to send me some more detailed information, I'm happy to take a look at that. Regarding keyword categorization, when two URLs from the same website are appearing on the search results for the same query, the question is, is this something that confuses the algorithm, meaning the fact that there are two URLs, the existing one confuses the algorithm and hurts the ranking of the other URL?  

#### [0:27:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1650) |  Let's say I have one URL in

position 4 and the other URL in position 7 for the query. If I remove the second one, does the first one perhaps improve its position? I think this is a complex topic. And at the same time, it's something that people often overthink. But in general, what I would of think about is what you want to have shown for a particular query?  

![](https://i.ytimg.com/vi/3n_4B7ZXjjI/maxres2.jpg)



#### [0:28:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1680) |  And then use that to focus your

efforts on that one particular item. Because as soon as you have multiple items that are essentially strongly overlapping, then it's on the one hand harder for us to pick which one of these pages might be the most relevant one. On the other hand, it might be harder for the users to figure out which one of these is actually the one that they're looking for. And finally, from your side, it's also a bit trickier to determine which one of these should you be maintaining, which one of these should you be updating.  

#### [0:28:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1710) |  So with that in mind, I'd really

strongly recommend making sure that a content-- [AUDIO OUT] --you're creating is really-- [AUDIO OUT] --there and focused on one particular topic so that these individual pages can become really strong for those particular topics for maybe those individual queries. And you don't have to worry about like how is overlap happening here. On the other hand, if you have something like a blog,  

#### [0:29:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1740) |  or something where you just bring out

new content all the time without regularly updating the old content as well, that might be that it's just of naturally happens that you have some amount of overlap in content. Because maybe you write about a preannouncement where some company is about to announce something new or has just announced that they're working on something new. And later on, they announced that it's actually live now. That it's available.  

#### [0:29:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1770) |  And it makes sense to write about

both of those situations right away. So that's something where it would be kind of normal for you to say, well, I have some content on this topic already. I have some content on the new variation of this topic already. And maybe I'll just create something even newer on that topic as well if that product is already in use. And you're able to write a review about that. So that's something where on the one hand, it makes sense to focus, to try to bring some sense of focus  

#### [0:30:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1800) |  into your website. On the other hand,

sometimes it also makes sense to just write about things as they come. How effective is old off page SEO like backlinks creation? Many agencies spend lots of time doing old off page activities such as image sharing with links, articles mission on sites like Tumblr, classified sites, and other free posting sites, where people hardly  

#### [0:30:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1830) |  read any of the posts. But those

platforms for dropping links with some text, basically a majority of their site has poor quality posts. So I've found all of those examples that you mentioned are really terrible ways of promoting your website. So that's something where if you hire an agency, and they go off and post links on Tumblr, on classified sites, and free posting sites, and they claim  

#### [0:31:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1860) |  that this is going to help your

website, then I would move to some other agency. So just to be really clear, this kind of activity has zero value for SEO. It's not something where you're promoting your website in any way. But rather essentially, they're spamming the web. So that's something I would strongly discourage anyone from doing. On the other hand, creating really fantastic content and then reaching out to perhaps other sites who  

#### [0:31:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1890) |  want to talk about that content, that's

like a totally different story. So it's not the case that I would say any work that you do that results in getting a link is a bad thing. But rather, you should be focusing on things where you end up getting natural links because of the value of your content that you're providing and not focusing on dropping links into random places anywhere you can drop a link randomly. That's not going to help your website.  

#### [0:32:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1920) |  That's just going to be considered a

spam. So that's a really bad idea. So that's-- I can't say in any amount of working on a website to improve the links that you would get is bad. But rather you should definitely not be doing this kind of spam. And if an agency is doing this kind of spam for you, I would switch to a different agency. I've created a web page. And it's ranked on a second page.  

#### [0:32:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1950) |  I want to take my page to

the first page. So I'm thinking I have a new branded site, how can I rank my web page at that page? So I don't think there is any magic trick to ranking higher. And essentially, ranking is not so much something that is an attribute of a website. But rather, essentially what you should be looking at is how your website is relevant with regards  

#### [0:33:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=1980) |  to individual query. So you can rank

for anything at first position if it's specific enough to your individual pages. If you make up a word, and someone searches for that word, then maybe your website will be the only one that are shown in those search results. So just ranking alone I think is a bad way to think about it. But rather, think about it, what kind of value do you want to provide with your pages? And how can you show that value?  

#### [0:33:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2010) |  How can you work on promoting your

website to make sure that other people are aware of your website and the relevance that you're providing? And then focus on the ranking of those keywords rather than just ranking itself. Another thing that you can do, which I strongly recommend, is to think about how you can branch out. And maybe focus on more niche keywords to get started so that you don't have to compete with all  

#### [0:34:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2040) |  of the big sites, for example. So

one way you can do this is to use a various keyword research tools that are out there. There's also a Google trends, where you can take one keyword. And you can pick a location location that perhaps you'd like to talk by target. And it'll give you a little bit of insight into how that keyword or how that phrase is used in those regions. And it will also give you some alternatives, so some other ways that people are searching for similar topics.  

#### [0:34:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2070) |  And often, that can give you some

more ideas on how you can write about this. And instead of just taking a very competitive keyword and focusing on that, maybe it makes sense to focus on something a little bit longer, a little bit less competitive, and to build out your website from there. So that's the directions that I would take in cases like this. But in general, if you're starting out  

#### [0:35:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2100) |  with a new website, everything will be

a little bit shaky in the beginning until things settle down. So take your time. Take your time to do some research on what your strengths are, what the value is you can bring to the web. And also take the time to figure out which topics you really want to write about or create content on. And how you can expand from just one narrow topic to maybe a broader set of topics.  

#### [0:35:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2130) |  What's the optimal way to build a

site map with links that have hreflang to other regions? Is it enough to put one link and let Google read the meta of that link that has hreflang? Or should we list all variations of all countries for that specific link? Does Google ever visit your site without declaring itself as a Google crawler? So for the first one, when it comes to hreflang, there are various ways that you can implement hreflang.  

#### [0:36:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2160) |  It could be either in a site

map file, like you mentioned here. It could be within the HTML on the page. It could also be within the HTTP response headers. And all of those places are places where we pick up the hreflang links. We combine them all. And based on the combined information that we have, we essentially try to use that appropriately. So that's something where theoretically you could make site maps and HTML meta tags,  

#### [0:36:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2190) |  for example, to pull together the complete

set of hreflang links. From a practical point of view, hreflang can be extremely complicated, especially if you have a lot of pages in a bunch of different languages or countries. So my recommendation would be to pick one location and to focus only on that location, just to make sure that it's easier for you to debug, it's easier for you to maintain if you change your URLs, all  

#### [0:37:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2220) |  of those kind of things. So theoretically,

you could split it up into different locations. But practically, I would really recommend just picking one to make it easier on yourself. Regarding "does Google ever visit your site without declaring itself as a Google crawler," I think that's possible. It all depends on what you mean with Google. If you mean Google employees, then definitely  

#### [0:37:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2250) |  we use browsers just like anyone else.

And they're not kind of declared as a Google bot. And we have various other tools that also access websites in various ways. When it comes to search, we do always declare it as a Google bot when we want to index content. So we really want to be clear that when it comes to indexing things for search, we want to make sure that we're accessing it a really straightforward way, that we  

#### [0:38:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2280) |  ask for permission first. We check the

robot's text file. And if the robot's text file isn't accessible, then we might hold off. If it is accessible and lets us crawl, then we will crawl. And we'll do that with the normal Google bot user agents. So from a search point of view, we definitely always declare it. How to make a link completely crawlable-- we want to have some links for user navigation,  

#### [0:38:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2310) |  but we don't want Google to spend

crawl budget on crawling or storing those links. So probably that doesn't make much sense because we have essentially enough crawl budget to crawl those websites. It's extremely rare that we run into situations where we are of limited by the amount of crawling that we can do. And usually, those are situations where the server is overloaded or something like that.  

#### [0:39:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2340) |  And also in cases like that, the

issues are not so much individual links that we run across, but rather that we run across situations where suddenly the same page is indexed 1,000 times with different URLs. That's something where, like when it comes to crawl budget that we could run into issues there. On the other hand, if it's like URL more, one URL less, or 10 URLs more, or 10 URLs less,  

#### [0:39:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2370) |  that's not a situation where crawling budget

would ever come into play. So probably in a case like this where you have individual links that you just want to hide from Google, that has absolutely no effect on crawl budget. So probably, you don't need to focus on anything there. In general, if you want to make sure that a link is not crawlable, then I would block the URL that you're linking to by robot's text. That's the clearest signal that you can give us that don't want Google to crawl this link,  

#### [0:40:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2400) |  and then Google won't crawl that link.

So that's kind of the direction I would head instead of trying to kind of obfuscate the link from being seen. Obviously, there are various ways how you could obfuscate that link. You could use-- I don't know-- some fancy combination of JavaScript in a way that Martin said you shouldn't do. And then suddenly, we won't be able to see that link.  

#### [0:40:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2430) |  It might happen that, at some point

later on, we actually do figure out how to crawl those kind of JavaScript links and then you're stuck again. It might be that you use-- I don't know-- Flash or some other technology that Google bot doesn't understand anymore and set up a link like that. There are various ways to block links from being seen by Google. But from a practical point of view, I don't think any of that makes sense. You're adding a lot of complexity for something that has probably zero value for your website.  

#### [0:41:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2460) |  So you're spending a lot of time

on things that make absolutely no difference from an SEO point of view. If the same link is present in many ways as well as the primary content of the page, is there any possibility the link in the primary content is giving additional support for SEO, like understanding, relating the content better? It can help us a little bit better, primarily with regards  

#### [0:41:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2490) |  to the anchor text. So if you

have a little bit of a longer anchor text in one place, then we can combine those anchor texts and get a little bit better context about that link. But in general, it's OK to just have the link in one place. It's also OK to have it multiple places. It's not like there's a big difference between those two. Uh-oh, rumor has it that FeedBurner might be retired soon?  

![](https://i.ytimg.com/vi/3n_4B7ZXjjI/maxres3.jpg)



#### [0:42:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2520) |  Do you know anything about it? Is

it just a conspiracy? I don't know anything about. I mean, I do know about FeedBurner. FeedBurner is a cool way to kind of propagate RSS feeds. But I don't know of any specific plans that are out there with regards to that. It does sometimes feel like RSS is a bit of something that few people care about nowadays, but it is still a big part of the web. It is still something that is used.  

#### [0:42:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2550) |  For example, with podcasts, it's kind of

the primary mechanism for distributing podcasts. And podcasts are really popular. So I don't think, in general, that RSS is going anywhere. But I don't know of any specific plans with regards to FeedBurner in particular. If I want my video on the page to be ranked and indexed, is video or embed tag better than iframe?  

#### [0:43:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2580) |  I think we probably understand all of

these variations. Essentially, as long as we can understand that there is a video that you're embedding on a page, and we understand which video files are associated with that, then any of those variations will work. There's also the video structure data that you can use to explicitly tell us about the video content on a page. But essentially, if you're using a setup that  

#### [0:43:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2610) |  is commonly in use on the web,

then probably that will just work. So if you're embedding YouTube videos, for example, or if you're embedding videos from Vimeo or any of the other bigger providers, then we've seen a lot of those video embeds, and we can just work with them. And it's not the case that any one of these embeds is better than the other. Because as long as we can pull out the video and understand how it is on this page, then we have what we need. There is no additional value in tweaking the tag  

#### [0:44:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2640) |  to be more SEO-friendly or less SEO-friendly.

Apple recently updated Safari on iOS and Mac to block third-party cookies. As a result, should we expect a drop in mobile traffic in Google Analytics. Or will this not affect analytics tracking on iOS and Mac users? I don't know. I don't know how Analytics handles that  

#### [0:44:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2670) |  or how that affects individual websites. I

would recommend checking in with the Analytics folks. They seem to be pretty active on Twitter. So there's, I think, a Google Analytics account on Twitter that you can ask directly who would probably know more on this. Is there a way to get explanations from Google SEO teams when a website is penalized or filtered from the search results with no message in Search Console?  

#### [0:45:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2700) |  My website has suddenly disappeared from the

search results since July 2019. I'm not sure I understand why. I try to respect Google's guidelines as much as I can, but I don't achieve it to get it back in search results. I don't know. So in general, when it comes to manual actions-- so when the webspam looks at websites and sees that you're doing something that  

#### [0:45:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2730) |  goes against Google's guidelines, we do send

notifications in Search Console. And you both get a message in Search Console as well as have that manual action section report in Search Console. So from that point of view, if anything is penalized, then that would be visible there. If it's not visible there, then that's something where, essentially, our algorithms are trying to figure out where this web page will be relevant and how we should be able to show it in search.  

#### [0:46:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2760) |  I think, in general, if you're running

into a situation where a website is not indexed at all in search-- like if you're saying it disappeared from the search results, I would try to figure out is it indexed or not? Because if it's not indexed, then most of the time, for normal websites, that will be due to technical reasons on the website. So that could be something where perhaps you or your host  

#### [0:46:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2790) |  is inadvertently doing something that prevents Google

from being able to index its content at all. And those kind of technical issues are things that tend to be easier to resolve. It might be, for example, that maybe you're blocking users in the US. And Google bot is crawling from the US, so we wouldn't be able to pick up that content. It might be something else as well.  

#### [0:47:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2820) |  If the website is indexed, and it's

just not ranking where you want it to rank, then that's obviously a little bit trickier. Because there are so many factors that play into ranking that it's really hard to say this is the one thing that you're doing wrong or that you should be doing slightly differently. It's really a lot trickier. I don't know, I think I just saw a comment in the chat which suggests that maybe you're here live.  

#### [0:47:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2850) |  Is that possible? If so, what I

can do is, after we finish with the normal-- REHAAN: [INAUDIBLE]. JOHN MUELLER: After we finish with the normal Hangout, maybe if you want to stay on, then I can take a quick look at your site to see if there is anything obvious. It's a bit hard to do that in the live Hangouts because I have no idea about your website and where I should even start. But after the recording is finished,  

#### [0:48:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2880) |  then I tend to have a little

bit more time to double check. REHAAN: OK, thank you. Thank you. JOHN MUELLER: We can take a quick look there. REHAAN: Thank you. JOHN MUELLER: All right. I think we're running kind of low on time, but maybe I can just shift over to any other questions from you all in the meantime. SPEAKER 1: Hi, John. JOHN MUELLER: Hi. SPEAKER 1: Again, [INAUDIBLE] from [INAUDIBLE].. So I would like to follow-up with the question I  

#### [0:48:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2910) |  had in last Hangout about large images

in [INAUDIBLE].. So far, here is what you have found through our tests. So when we use AMP, all of our images-- like all of our images are pulled large. But then we switched to non-AMP, they are becoming small. And sometimes, I don't notice that even AMP  

#### [0:49:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2940) |  images on other websites have small thumbnails.

But in our case, we have all the time large when we use AMP. But then we use non-AMP, it's small. And I did the following tests-- I changed the image aspect ratio a Google recommended aspect ratio to thumbnail to see if it does help, but it didn't. I a little bit like the changed our optical schema  

#### [0:49:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=2970) |  to play around-- to see if it

does any impact, but it didn't. And I would like to know is there any specific scripting AMP that it has pull images large and we can implement on the regular web pages. JOHN MUELLER: I think there are two ways that you can do that with the large images. One is that form. I don't know if you filled that out. SPEAKER 1: Yes, we did fill out many times long time ago.  

#### [0:50:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=3000) |  JOHN MUELLER: OK. SPEAKER 1: Yes. And

I did fill it again like a few days ago, but I don't know if it was reviewed or not. JOHN MUELLER: OK. And the other is the max image preview robots meta tag. SPEAKER 1: We do have. JOHN MUELLER: I think you have that as well. OK. I'll double check specifically for your site with the team on that.  

#### [0:50:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=3030) |  SPEAKER 1: Thank you very much. JOHN

MUELLER: To see if there is anything kind of blocking that maybe I can point out or if it's blocking on our side and we just need to unblock. SPEAKER 1: Thank you very much. Appreciate it. JOHN MUELLER: Sure. All right. Anyone else with any questions before we pause the recording? REHAAN: I could just in with another one if you'd like.  

#### [0:51:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=3060) |  JOHN MUELLER: OK, go for it. REHAAN:

So you've said that one of the sites which is over the mobile-first indexing, that's the only thing that's going to be in the index. Now I'd imagine, obviously, you'd also cross-check the desktop site occasionally. But what I'd like to know is should all my SEO focus now only be on the mobile site? Because suppose, on our website, we have a theme for mobile. So rather than making the change both times when it's something that's just technical SEO, like a meta description or schema,  

#### [0:51:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=3090) |  am I safe if I just do

those changes on the mobile side? JOHN MUELLER: From talking with the indexing team, they would like to see anything consistent across the desktop and mobile site. But we will-- essentially with mobile-first indexing, we only use a mobile site for indexing. So from that point of view, I think it's OK to focus on the mobile site, but in the long-run,  

#### [0:52:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=3120) |  it should really be across the whole

site. And using things like responsive design makes that a non-issue, if at some point you can switch to something like that. REHAAN: I get what you're saying. Thank you. JOHN MUELLER: Sure. All right. More questions from any of you?  

#### [0:52:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=3150) |  No more questions? SPEAKER 1: If anybody

doesn't have, I will give one. JOHN MUELLER: OK. SPEAKER 1: So what would be the best recommendation from you to avoid meta descriptions rewrites? JOHN MUELLER: To avoid them from being rewritten-- so we try to do two things when it comes to displaying the description in the search results. On the one hand, we try to recognize when there's kind of irrelevant meta description given  

#### [0:53:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=3180) |  on a page, which could be a

collection of keywords. It could be something where you have the same description across a large number of pages. That's something where we would probably jump in with our algorithms to try to resolve that. And the other case is when the meta description is something that doesn't match at all what the user is searching for, where we think probably it would be easier  

#### [0:53:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=3210) |  for the user to understand why this

page is relevant if we pick something from the page itself that covers those queries a little bit better what they're actually looking for. So those are kind of the main situations where we end up rewriting the description that we provide in the search results. So if you can make sure that your pages have unique meta descriptions that are kind of short but they would fit into a snippet on a page  

#### [0:54:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=3240) |  and that they match what users would

generally be looking for when they're going to that page, then chances are pretty high that we'll just reuse what you have in the description meta tag. SPEAKER 1: Because very frequently, we see that Google does pull as a meta description first sentence, the H1 tag, which is repeating the title tag. Like one does see a blue link, the headline of the article.  

#### [0:54:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=3270) |  And in the meta description, the same

text goes. JOHN MUELLER: Yeah. I don't know, I think that would suggest, to me, that we're not completely sure about the meta description that you have on that page. SPEAKER 1: OK. JOHN MUELLER: When we try to pull out text from a page,  

#### [0:55:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=3300) |  it's sometimes tricky to find the right

part of a page to pull from. And sometimes headings make sense. Sometimes something that's higher up on the page makes sense. But it's sometimes a bit tricky. SPEAKER 1: Just sent an example of that case. JOHN MUELLER: OK. Cool. All right. I think we're pretty much at time.  

#### [0:55:30](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=3330) |  I'll be around a little bit longer

if any of you want to stick around afterwards. But thank you all for joining in. Thanks for all of the questions that you submitted. And hopefully, we'll see each other again in one of the future Hangouts. And of course, in the meantime, stay safe, stay healthy. Don't do anything crazy like going outside, depending on where you're located, I guess. All right, wish you all a great weekend. And hope to see you all again next time.  

#### [0:56:00](https://www.youtube.com/watch?v=3n_4B7ZXjjI&t=3360) |  Bye. SPEAKER 1: Bye.  

