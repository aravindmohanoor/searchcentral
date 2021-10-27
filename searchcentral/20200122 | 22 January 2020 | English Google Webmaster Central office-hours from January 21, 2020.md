[![English Google Webmaster Central office-hours from January 21, 2020](https://i.ytimg.com/vi/1iDw3fVBhpE/maxresdefault.jpg)](https://www.youtube.com/watch?v=1iDw3fVBhpE)

## English Google Webmaster Central office-hours from January 21, 2020

This is a recording of the Google Webmaster Central office-hours hangout from January 21, 2020. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Watch out for new sessions, and add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



Feel free to join us - we welcome webmasters of all levels!



Subscribe to Google Search Central → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=0) |  JOHN MUELLER: All right. Welcome, everyone, to

today's Webmaster Central office-hours hangout. My name is John Mueller. I'm a webmaster trends analyst here at Google in Switzerland, and part of what we do are this office-hour hangouts where folks can join in and ask their questions all around Web Search. Today, it looks like I'm in a train, but it's actually a meeting room here in the office. Because the office is right next to the train station, they have some rooms that look a little bit different.  

#### [0:00:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=30) |  Seems to be working OK, so we'll

see how things hold up with my laptop on a stool. As always, a bunch of questions were submitted already on YouTube. If any of you want to get started, feel free to jump on in now. Or if not, that's also fine. AUDIENCE: I can-- [INTERPOSING VOICES] AUDIENCE: Is that OK to start? JOHN MUELLER: Go for it. AUDIENCE: OK. My name is Armen Hareyan.  

#### [0:01:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=60) |  I'm from Charlotte, North Carolina. I have

a question, John. I have written it down. So is there a benefit in removing meta name robots content equals follow? Because you know, by default, Google follows the content if there is no index or no follow, right. But you know, on the website that I'm consulting, the follow is there and I asked to remove it. They said, let's find out if there is benefiting in removing it, or what's the pros and cons. JOHN MUELLER: For us, it doesn't matter. So we don't use it at all.  

#### [0:01:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=90) |  If it says follow, that's kind of

the default value. We essentially ignore it. So if you have it or if you don't have it, it doesn't change anything for Search. There's obviously a small size difference in the HTML page, but for the most part, most HTML pages, that's like very minimal and probably wouldn't have any effect overall. AUDIENCE: Thank you very much. JOHN MUELLER: My guess is you can leave it there. It doesn't cause any problems.  

#### [0:02:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=120) |  The main reason I might remove something

like that is so that you don't run into this question later on. Like a year later, someone's looking at your website and like, do we need to remove this or not, because it doesn't have any function. It's like, well, you already cleaned it up. But it's totally up to you. It has no effect on Search. AUDIENCE: Thank you very much. My next question is, we're talking about the very large website, e-commerce retail website. So a lot of times, it happens that a product is no longer available.  

#### [0:02:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=150) |  We're talking about hundreds of thousands of

products and some of them may be no longer available for some different reason. Either it's no longer available or the vendor decided to change the product numbers and simply created a new page, and this one is no longer available. So in this scenario, what is the best thing to do? Is the product no longer available for sale? Should we remove it or should we redirect it to the same, basically same or very, very similar product?  

#### [0:03:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=180) |  JOHN MUELLER: If you have a replacement

product, I would always redirect because that way, you're keeping the value of the existing page and you're passing that on to a replacement. If you don't have a replacement, then doing what you would normally do with out of stock products is kind of my recommendation, where what you would normally do can depend. So ideally, let us know that this product is out of stock. On the one hand, you can do that with the normal HTML page saying, not available, with the schema markup  

#### [0:03:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=210) |  saying it's not available. You can return

that page with a no index if you want. You can return that page with a 404. You can return a generic 404 page. All of those are different options. I think it depends a little bit on how you want to work with out-of-stock pages, how much manual effort you can put in. So if you can't figure out where you have a replacement product, if it's a really large site, then obviously you have to do something generic, but how  

#### [0:04:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=240) |  you handle that in practice is really

up to you. AUDIENCE: I can let other people ask questions, and then I have two more questions. I can ask them later. JOHN MUELLER: Sure. AUDIENCE: Hi, John. JOHN MUELLER: Hi. AUDIENCE: My question concerns internationalization SEO. So I'm managing SEO for a multiregional website. We're targeting various English-speaking countries.  

#### [0:04:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=270) |  We've implemented hreflang tags on the website

but we don't have a country language selector. Is that a problem in itself? We're using IP redirects to direct users to the correct regional version of the website. JOHN MUELLER: OK, so I think there are a few things to kind of watch out for. On the most general level, I think you need to be careful with IP redirects if you use that as your main method of guiding  

#### [0:05:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=300) |  people to the right version because Googlebot

will only crawl from one location, and usually, that's from the US. So if you're treating users from the US in any specific way where you're saying, everyone from the US goes to the generic English version and you always redirect them there, then Googlebot will never see the other country versions so they will never be able to be indexed separately. We won't be able to use hreflang for that version because we can never look at those 0's. So that's kind of from a technical point of view one  

#### [0:05:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=330) |  thing to watch out for. The solution

we have for that is to use a banner instead of a redirect. So if you can recognize that someone is from the wrong country, then show a banner on top and say, hey, we have a version for your country. It's here. And usually, that means like we have local currencies, local prices, maybe other shipping prices, all of that kind of to guide them to the right version but to still let them look at the other versions.  

#### [0:06:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=360) |  And the advantage for indexing there is

we can look at all of these different country versions and we can understand how they belong together, and we can show the right version in Search for users. AUDIENCE: OK, makes sense. JOHN MUELLER: Yeah, I think that's generally what I'd recommend doing there. You can also do that with maybe a country selector or dropdown on the page or just links to individual country versions. All of that helps us to find the different country versions,  

#### [0:06:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=390) |  but the important part is really that

we can actually crawl the country versions. AUDIENCE: Mm-hmm. OK, thanks so much. Do you mind if I jump in with a second question? JOHN MUELLER: Go for it. AUDIENCE: So I'm managing a travel brand, and on our blog, we have a category that is titled "Travel Porn." now, as you might expect, this is causing our website to appear in search results for various porn-related queries,  

#### [0:07:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=420) |  and I'm just wondering how much that

negatively affects our website and our topical relevancy for various articles that we might be putting out there. Is it such a big deal that we need to change the title of that category? Because it is a big deal in terms of brand consideration. JOHN MUELLER: So I assume it's just travel porn with regards to it being cool pictures about travel without adult content.  

#### [0:07:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=450) |  AUDIENCE: Yeah, yeah, yeah. JOHN MUELLER: OK,

so purely from our point of view, that's something where I don't see a problem with that from just purely a search point of view. What can happen is we will show your pages in Search for people who are searching for those terms, but it's not that the rest of your site will be seen as less valuable or that the other queries going to your site would be kind of affected by that.  

#### [0:08:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=480) |  It would be different if you actually

had adult content there under a label like that because then we'd be in a situation where we have to figure out how do we deal with Safe Search and the site where some parts are for adults and some parts are kind of for a general audience, but if it's just a label that you're putting out there, then that's something where it's just, you will get some search queries like that, it'll show up in the search results like that, but it's not going to affect the rest of your site.  

#### [0:08:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=510) |  And then that's more a question of,

do you want your site to show up in search queries like that or not? And if you don't care, because like that page won't show up if someone just searches for your brand name-- it's not like you search for your brand name and then like porn shows up as the first result, but rather if someone is explicitly looking for that kind of a query, then that'll show up as well. So it's not that by default, your brand will be shown like that.  

#### [0:09:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=540) |  It's really, well, they were really looking

for that so this is kind of an OK match from a keyword basis, so that's why we showed it. But sometimes you don't want that, so sometimes you really just want to make sure it's not shown at all like that. Then what you'd probably want to do is just put a new index on the page so that people can go there if they really like it but to make sure that that page doesn't get indexed like that. AUDIENCE: OK, that is very helpful to know.  

#### [0:09:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=570) |  Thank you so much. JOHN MUELLER: Sure.

All right, any other questions before we get started with the submitted ones? AUDIENCE: If there is no one asking questions, I can ask one more questions before we go. JOHN MUELLER: Go for it. AUDIENCE: So in this organization, there is a large retail organization. They are doing JavaScript redirects. Let's say it says the domain name, the description of basically the key phrasing, the URL, and then  

#### [0:10:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=600) |  there is the N number, which is

basically the product number. It's done in the redirect in such a way so that anything you remove between the domain name and the N number, it still shows the same URL. And is this equal to 301 redirect? JOHN MUELLER: In the end, we do treat JavaScript redirects the same as any other kind of redirect, so the practical difference is for JavaScript redirects, we have to process the JavaScript first,  

#### [0:10:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=630) |  so it can take a little bit

longer, but in practice, that's a question of maybe, I don't know, a day or so. So it's not something that would significantly affect a website overall, so if that's kind of the way you have redirects set up, then I generally wouldn't worry about that. AUDIENCE: And it's OK if that creates millions of redirects? JOHN MUELLER: I mean, when you change a website's structure,  

#### [0:11:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=660) |  you have a lot of redirects, and

that's like. AUDIENCE: Because every time they change something in the product name, in the product title, they also change the URL. Is there a need for that, to change the URL really? JOHN MUELLER: Usually you wouldn't need to do that. AUDIENCE: Right. JOHN MUELLER: But some CMSs make life complicated. I think the important part is really that you also make sure that internal linking is consistent, that you have the new URL in the SciPy file.  

#### [0:11:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=690) |  Everything points to the new URL, and

then what will happen is we will see that redirect, we will know everything else points to that new page and we'll focus on the new page instead. So it's not every time we recrawl, we see the redirect. It's more that, oh, we saw you shifted so we will focus on the new URL that you have. AUDIENCE: Thank you, and my last question, John. So when I present consulting to a company sometimes, they ask me, OK, show me some number, like for example,  

#### [0:12:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=720) |  if we improved images, how much our

traffic will go-- for example, having the description in image file like you posted yesterday and things like that. I tell them that there is no way to tell you numbers like how much the traffic will increase, 50%, but they always want numbers. Basically what I'm telling, hey, we're just following Google's best practices, OK. So what is the best answer if the upper management, top management, wants a number? What is the best answer to this scenario? JOHN MUELLER: I don't know. It's kind of like how you have to convince them,  

#### [0:12:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=750) |  but I think the general thing is

also that you can make some guesses for some of these numbers. Like you can look at the total number of impressions that you get, and if you're always ranking for that query and you go up in rankings based on these changes, then that's something where you can kind of estimate how many additional clicks to our page we could get based on just kind of the historical data of which  

#### [0:13:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=780) |  ranking position drives how much percent of

the traffic, which is something you can kind of see from Search Console. So if you look at overall the traffic to your website and you see which of these URLs are ranking in which place, you can look from the total number of impressions to the clicks that you've got to kind of make a judgment on like, OK, if we can go from number 7 to number 6, then we would expect this much more traffic. You can't guarantee it, of course,  

#### [0:13:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=810) |  because maybe you'll go up in rankings

and people just don't want to click on your results because it doesn't match what they need or maybe the titles are bad or things like that, but it gives you a little bit of room to say, well, in general this would drive so much more traffic. And based on that you can then make judgment calls and say, well, our conversion rate is maybe so much, so if we drive 10% more traffic to this page, then that could mean this much more conversion.  

![](https://i.ytimg.com/vi/1iDw3fVBhpE/maxres1.jpg)



#### [0:14:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=840) |  So that might be an approach that

you can take, but in general with a lot of these SEO changes, you can't guarantee that things will change. It's something where you have to go a little bit more on your experience and based on what you've seen in the past, what kind of queries these are and how strong the competition is, you can kind of make judgment calls and say, well, it's possible for us to go up in ranking or maybe it's questionable that we'll actually go up  

#### [0:14:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=870) |  in ranking, so we need to make

sure that our search result looks better rather than we focus on trying to rank higher. AUDIENCE: Thank you. I appreciate that. JOHN MUELLER: Sure. AUDIENCE: John, can I ask a quick question? JOHN MUELLER: Sure. AUDIENCE: All right, so we have a stocked vector graphic site. It's in roughly eight different languages. English is the main language coming in so that's where all the input's coming from. hreflang is the most complicated thing I've ever worked on from a technical perspective for SEO. So anyway, so here's what we see is that most of our traffic  

#### [0:15:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=900) |  comes to our search result pages, so

let's say like a dog search result page. Dog vectors is the page it ranks for that. We can see in a site command for our own site that's what ranks. So we have hreflang from our dog page to our Spanish perro page, and like cachorro, et cetera, across all the languages. So from our dog hreflang to our perro hreflang, the search results for the page are the exact same. So our own internal search results. So if we're showing 50 results on the page,  

#### [0:15:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=930) |  those 50 results are the exact same

on the dog page and the exact same on the perro page. With hreflang, is that the correct implementation? Because we're having issues to where the perro page in Spanish does not rank at all, and we get [SPANISH] perro, and we get all these other variations with our hreflang. We're finding, like, on our Spanish pages that hreflang pages don't really rank as well as pages that don't have hreflang.  

#### [0:16:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=960) |  So there's some kind of confusion there.

We're just kind of curious to see if on search results pages, should they be the exact same, or should they be different with hreflang? JOHN MUELLER: So the idea behind the hreflang markup is that if we were to show one of the pages from the set for a query, then we would try to map the diversion that matches the user most. So from a practical point of view, that doesn't-- that means we don't change the ranking  

#### [0:16:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=990) |  of the individual pages. But rather, if

someone, in searching in Spanish, were to see the English version of that page, then we would swap that out against the Spanish version. So in a case like that, if someone in Spanish is searching for "dog," then we would be able to swap out the Spanish version. But if someone is searching for the Spanish word for dog, then we would already show the Spanish version. We wouldn't change anything. So from that point of view, I think what you're seeing is just the normal ranking differences  

#### [0:17:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1020) |  across different languages where we need to

have support for the individual language versions so that we kind of can rank them individually. And where you would most likely see an effect from hreflang are places where people search for the same term in multiple languages. So for a site, maybe like yours, maybe your brand name or your website name, when people search for that website name, it's unclear to us which of your pages  

#### [0:17:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1050) |  should be ranking. And with hreflang, we

can then swap out the one that matches that best. So if they're searching for, I don't know, you're a stock photo brand and you have different home pages for different country versions, then we could say, well, one of these versions would show, therefore, we can find the best matching version for this and swap it out. But for specific queries that people are already doing in a local language, the hreflang wouldn't change the ranking there. It's like, well, we already have the Spanish version  

#### [0:18:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1080) |  that we would show here, and that's

the best matching version that we have. It's not ranking as high as when someone is searching in English, but it's like the best version that matches the user's question already, so we don't have to swap anything out. So from that point of view, it's something where maybe it makes sense to look at the kinds of queries that you get for your website, and to figure out which of these queries are really ones where Google gets the language origin wrong, and then to kind of focus on those,  

#### [0:18:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1110) |  which could be things like your home

page, maybe category pages or about pages, where people use the same terms in multiple languages to refer to kind of the technique or the kind of files that you have. And to leave the other ones, where people are already looking in their local language, essentially just to rank on their own. So that's something. I don't know. It's probably a bit late to say you don't need to put hreflang on these pages,  

#### [0:19:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1140) |  but probably you wouldn't need to. The

one place where you would need to do that is if you have the same language content for multiple countries. AUDIENCE: So that's where it gets kind of confusing, because it's like, we have eight different languages. And so for the dog page in English, essentially we have the exact same search results for dog, perro, cachorro, chat, et cetera, across [? dogs. ?] So we're like, hey, there's eight different versions of this dog page across all our locales, so we're trying to figure out, like, hey, we don't want Google  

#### [0:19:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1170) |  to see these all as duplicate. So

is hreflang what we should do to say, hey, when you see these eight exact same pages across these eight subdomains, they're all the same, and this is the relationship between them? So we were trying to-- we were scared about the duplicate content perspective, so we thought hreflang is maybe the appropriate way. But now we're like, we're seeing all kinds of ranking issues outside of English, and we're worrying is-- because hreflang got super, super complicated across eight different languages,  

#### [0:20:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1200) |  and we have non-circular references. And one

word in English may mean two different things in Spanish, but then how do you get them to point back to each other? It was super, super complicated. So we're kind of rethinking the whole hreflang thing, especially around search result pages. But if the dog page is the exact same results as the perro page, should those really have hreflang between each other? JOHN MUELLER: From my point of view, that's a perfect use case for hreflang. If that's kind of the Spanish version of this page,  

#### [0:20:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1230) |  then that's the correct use of that.

From a practical point of view, I don't think that you would need hreflang there, though, because those pages would have different language content. Like, if you have a page for "dog," then the titles in Spanish would be "dog" in Spanish, and maybe descriptions would be, appropriately, in Spanish. So we already wouldn't treat those as duplicates, even if the images themselves are the same. But things like the text on the page, the titles, it's a localized version of that page,  

#### [0:21:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1260) |  so it's different content. We would treat

it as a unique page. That's a common, I think, misconception with international sites, that if it's translated, it's still the same. And from our point of view, if it's translated, it's different text. So we would automatically treat it as something unique. AUDIENCE: OK. And so with that, everything on the page is essentially the exact same, but we do have one instance of the file name. So when the file name comes in, like, let's say, resource number 1 on the dog pages,  

#### [0:21:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1290) |  beautiful dog background, well, that file name

is beautiful-dog-background.jpg, right? Well, on the Spanish page, we were worried of creating-- we have a million resources, so we were worried about creating a million different files for all eight locales and trying to keep all those indexed and everything like that. So we used that beautiful-dog-background.jpg on the dog page, the Spanish perro, the Portuguese-- you know, all the different versions of that. And we've never translated those, so we've always wondered, do you see there's an opportunity, if we were to go translate that file  

#### [0:22:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1320) |  name correctly across the locales we could

rank better in Google image search, or should we keep that one English version across all? JOHN MUELLER: I would just keep one version. So we do use the file name as a really small factor when it comes to images, but we use the text on the page much stronger. So if the text on a page is already translated, then that's kind of what you want. And in the background, if we see multiple files that lead to the same content, like the same image with multiple file names, we'll treat those as duplicates  

#### [0:22:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1350) |  and fold that into one URL anyway.

So if you can avoid us having to struggle with this by telling us, like, this is that one image and this is the only URL that points to that image, then that makes it a lot easier for crawling and makes it a lot easier for image indexing as well. AUDIENCE: OK, thank you very much, John. Appreciate it. JOHN MUELLER: Sure. OK, let me run through some of the questions that were submitted, and we can get back to more live questions afterwards as well.  

#### [0:23:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1380) |  So the first one I have here.

Since Wednesday last week, Search Console for all submitted pages on our site dropped to 70 valid pages. This is from 267k. We're on Google News, and we've been reaccepted yesterday on the new Publisher Center. We seem to have major issues with indexing in the past week, though. OK, so I didn't see a URL here in the question, but I think you tweeted a screenshot  

#### [0:23:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1410) |  where the URL was visible. And I

took a quick look at this on our side, and it looks like one of the things that's kind of bubbling up is that we see a lot of spammy user generated content across these pages, which usually is a sign that something got hacked or that you have user generated content on a lot of these pages, and people are taking advantage of your site and dropping a lot of spammy content there. So I haven't looked into the details of what exactly  

#### [0:24:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1440) |  that one might be, but maybe that

helps you to kind of figure out which direction to start looking. What I would also do in a case like this is go to the Webmaster Help Forum and post your URLs there, especially some that you've seen that have dropped out of search so that folks there can take a look. Sometimes, this kind of spammy content, especially if it's from someone hacking your site, it might be that they're cloaking it specifically to Googlebot. That means when you look at the page in a browser,  

#### [0:24:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1470) |  it looks normal. When Googlebot looks at

the page, then it looks really spammy. So that's something where there are multiple tools that you can use to kind of take a look at that to figure out what's happening more. And the folks in the help forum are extremely helpful, and have a lot of practice with pulling out these kind of things. So that's something where I'd try to get some help in that regard.  

#### [0:25:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1500) |  Does page rank go nowhere if we

set up a no crawl option for specific URLs in the URL Parameters setting in Search Console? For example, we don't want some sorting pages to be crawled because of crawl budget issues. So in a sense, page rank goes nowhere in cases like that. This is because what happens on our side is we see links as being between two canonical URLs, and if there is no canonical destination  

#### [0:25:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1530) |  URL on your side for a specific

URL, then we will think, well, this link goes nowhere, and we don't use it. From a practical point of view, that's usually fine, though, because especially if you're looking at sorting pages and different parameter options for maybe an e-commerce site, nobody's going to be linking to one specific variation and kind of driving a lot of your site's page rank like that. So there'll be individual links like that,  

#### [0:26:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1560) |  and if they get dropped, then that's

usually no big problem. So from my point of view, that's not something that you need to worry about. If you're seeing that Google is having trouble crawling your site because there are just so many different URLs, then I would definitely set up this setting so that Google can focus on the URLs that really matter for your site. And if we can crawl your site faster, if we can get to your new and updated content faster, then that'll generally be worth a lot more than kind of those individual links coming from random places going to this one  

#### [0:26:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1590) |  specific variation of a sorting kind of

category page, for example. If you do want to have those links taken into account, then we need to be able to crawl those URLs and we need to find the rel=canonical on those pages pointing to a version that you prefer to have indexed. As per Google's Quality Rater Guide for your money or your life sites, it's important to have the credibility of the author  

#### [0:27:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1620) |  of the main content. The question is,

how does Google determine the credibility factors on a page where no author details are present? I've seen such pages ranking high. So I think there are multiple things here. On the one hand, the Quality Rater Guidelines are for our quality raters when they review algorithmic changes across kind of a large set of sites. So I think it's useful for site owners to take a look at these Quality Rater Guidelines  

#### [0:27:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1650) |  to understand where we're kind of headed,

but it's not that the Quality Rater Guidelines is a one to one guide for how our algorithms will work. So from that point of view, I wouldn't see the Quality Rater Guidelines as kind of like the list of ranking factors. Instead, I see this as something that kind of gives you some gentle nudges and some ideas of areas for improvement for your website. So if, on your website, you're focusing  

#### [0:28:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1680) |  on medical topics or other topics that

fall into this category of sites, then try to find a way to show that your authors or the people who are behind your content on your site are people that users should be able to trust. And there are various ways that you can do that. It's not that you have to do one or the other. There is no simple meta tag that says, trust me, I know what I'm talking about. But there are lots of different options there. And I would kind of use the Quality Rater Guide  

![](https://i.ytimg.com/vi/1iDw3fVBhpE/maxres2.jpg)



#### [0:28:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1710) |  as kind of a list of ideas

of things that you could be focusing on there. Is there a solution to this problem? So let me just double check. I think this is some tweets on very specific sites that are seeing some very specific changes,  

#### [0:29:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1740) |  and it's not loading for me. Oh,

need to log in. OK. So I can't double check what exactly there was, but I believe this was a set of sites that were seeing some issues and some reports in Search Console. And I've been looking at this with the Search Console team to figure out what exactly is happening there, and I posted some preliminary information on Twitter. So that's something for those specific sites who are seeing that kind of a problem to take a look at there.  

#### [0:29:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1770) |  I don't think there is anything general

that's happening there. It's just for some sites, we, I don't know, we've kind of re-evaluated how we think those sites should be shown in search, and these kind of re-evaluations happen all the time. How much do links to subdomains contribute to the relevance of the main domain? Any site you can-- any insight you can give would be appreciated. So this is kind of similar to the previous question  

#### [0:30:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1800) |  with the parameters. Essentially, we need to

have canonical URLs on your site. And we will see those links between those canonical URLs, and within your website, you also need to have links so that we can crawl your website and kind of forward the signals across the rest of your site. And it doesn't matter so much if those are on subdomains or subdirectories or on the home page. If we see a link to a page on your website, from there, we can kind of forward signals across the rest of your site.  

#### [0:30:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1830) |  So that's something where there's nothing really

special with regards to subdomains or subdirectories happening. It's really just kind of like, we're technically following the links and forwarding the signals that we collect along the way. And with signals, that can be all kinds of things. So page rank is kind of the obvious one. We've documented that quite a bit. But there's a lot more to search than just page rank.  

#### [0:31:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1860) |  If a site is incorrectly flagged by

Safe Search, there used to be a form you could submit that would go to the Safe Search team. That form was removed, and the link now redirects site owners to the Webmaster Forums. Is there any way for site owners to send that feedback directly to Google without having to post in the forums? Some publishers are being filtered when they really shouldn't be. So, no.  

#### [0:31:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1890) |  At the moment, there is no kind

of private channel with regards to Safe Search reviews. What we noticed with that form is that like 99.9% of all submissions there were completely normal from our point of view with regards to Safe Search. There were all kinds of adult sites or almost adult sites that were trying to get out of the Safe Search filter, and we just realized that there wasn't a lot of value in providing a form like that if we can't actually get any useful information that way.  

#### [0:32:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1920) |  So that's something that we thought would

make a little bit more sense in the forums, because then it's a lot easier for people to also get feedback on these kind of questions. And we do get escalations from the forum from the product experts that are posting there. That's always really useful. So that's kind of the direction we moved with regards to that form. We don't have any private channel for these kind of submissions. And also, what I notice is when people ping me  

#### [0:32:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1950) |  on Twitter with these kind of questions,

quite often, it's not that we're filtering a site by Safe Search. A really simple way to double check is to just do a site query, and then to turn-- to add the URL parameters "Safe equals on" or "Safe equals off" to see, is this really being filtered by Safe Search? And if you see the same results there, then that's essentially not being filtered by Safe Search.  

#### [0:33:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=1980) |  With regards to ranking, obviously there are

lots of things that can flow into ranking of a site. But if it's kind of Safe Search, at the moment, it's something that's more like it's either on or off. We merged three brands into one, but the old brand is showing on the meta title at the end. Any tips to get this removed? So whenever you're merging sites, that's something that takes quite a bit of time  

#### [0:33:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2010) |  for everything to be reprocessed. And it

can take a significant amount of time for us to relearn things like titles, to understand what kind of the-- this website is about, what should we use as a site title, essentially, for this site and for some of the pages on the site. So that's something where the main thing you can do is to be consistent and really make sure that across the whole site, you focus on the new name that you want to use.  

#### [0:34:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2040) |  And then it just essentially just takes

time. There's no meta tag to say, you must use this title, or this is really, really the title that I want you to show, but rather, we try to understand that over time. And when you're merging different sites-- so it talks about three brands merging into one. I assume this is three different websites that are merged into one. That's something that always takes a little bit longer than if you're just moving from one domain to another.  

#### [0:34:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2070) |  So this is a tricky situation for

us to reprocess, and usually these things just take a pretty long time. And by pretty long time, I'm thinking-- I don't know, depending on the website, how often we crawl it, probably on the order of several months for something like this to be reprocessed and to really be visible across a large part of the pages on a site. For most websites, we tend to recrawl  

#### [0:35:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2100) |  pages at least every half year. So

that's kind of the upper limit for just recrawling pages, but signals like titles, like brands, usually, we can pick them up a little bit faster by just focusing on the important pages on a site. But that's something where you're still talking about several months, probably, until that really settles down. How long does it take for a piece of content to fall off of Google's index once it's been redirected,  

#### [0:35:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2130) |  and is there anything we can do

as webmasters to speed this up? So when you're talking about redirecting a piece of content, essentially, we need to understand that this piece of content has really moved. And we do this in a process called canonicalization, whereby we basically understand that there are multiple URLs on your website that lead to the same content or that show the same content.  

#### [0:36:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2160) |  And from this set of URLs that

are kind of in this cluster of potential canonicals, we will pick one as the canonical URL. So that's essentially how it works. With a redirect, we have a really strong signal that you have one preference. You have other ways of expressing preferences, like the internal links on a website, the site map file, kind of the hidden references within a site, things like the hreflang, the rel=canonical,  

#### [0:36:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2190) |  those kind of things. And when all

of those signals align to one version, then we'll generally switch to that one version for indexing. So that's something where if you can give us all of these signals right away, then we can probably shift over within a day or so. Sometimes it takes a little bit longer. It also depends a little bit on how often we recrawl those pages. Like I said, some pages we recrawl every day.  

#### [0:37:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2220) |  Some pages we recrawl every half year.

And if this is one of those pages that takes us a half a year to recrawl, then you'll kind of have that lead time of at least a half year until we actually crawl that page to see, oh, it's redirecting to somewhere else. So that's kind of the unknown there. The other thing that makes this a little bit more complicated for SEO is sometimes is when we recognize that someone is explicitly looking for the old version of a page,  

#### [0:37:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2250) |  we'll try to show it to them.

So that's very visible if you do a site move. You move from one domain to another, and we'll probably be able to process that within, I don't know, a couple of days, couple of weeks, if we recognize it as a clean move. But if you explicitly look for the old URL, if you do a site query for the old website, then we'll still show that old URL in the search results for quite a long time, just because we know that this query that people--  

#### [0:38:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2280) |  that you gave us is associated with

that old URL. And what you can do here is kind of look at the cache page and usually, when we've switched over to the new version, you'll see the cache page says, this is the new URL. So as soon as the cache page points at the new URL, that's essentially a sign that we switched to canonical. You can also look at the canonical in Search Console with the Inspect URL tool. So that's another way of double checking  

#### [0:38:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2310) |  that we picked up the right version

or your preferred version as a canonical. But those are lots of things. And if you just care about, well, how do I kind of redirect one URL to another, then the short answer is it depends, and the long answer is, like, all of these technical details. Usually, if this is an important page on a site, we'll recrawl it fairly quickly within a couple of days and we'll switch things over fairly quickly if the signals are clear.  

#### [0:39:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2340) |  But those few days can be extended

to somewhere around a half a year or longer, too. An external consultant claims that a website's main content isn't relevant, and a website about car insurance can just as well get top rankings for a page about diabetes. I don't see how this can be correct, due to lack of authority for the topic, nor the expertise and trust signals of the author. Can you confirm or deny?  

#### [0:39:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2370) |  So we do take the content of

a page into account for ranking. It's one of the most important parts, I think, of a web page, like what it's actually showing. So from that point of view, the content is really important. And if the content is not good or not relevant, then we're definitely not going to, or we're going to try not to show that in those search results. So from that point of view, I would really  

#### [0:40:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2400) |  recommend focusing on content rather than taking

a page about car insurance and then trying to make it rank for diabetes. Because, I mean, ultimately, even if you do make that page rank for diabetes, if a user goes to your car insurance page, they're not going to convert, because they're looking for something else. So even if you happen to rank a page for irrelevant content, it's not going to be useful for your business. Also, is there a maximum ratio of how much content  

#### [0:40:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2430) |  a website can syndicate before it affects

the value of the rest of the articles, especially if the other website won't add a canonical back to us? Not really. I don't think we have any fixed numbers with regards to how much content a website can syndicate. Usually, what happens in cases like that is we recognize the content, the primary content of the page is the same, and we'll try to find the most relevant page  

#### [0:41:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2460) |  kind of that matches that query, that

matches the content. And usually, that means we go back to the original page and say, well, this is the page that should be ranking for that query. But it's not that we have a limit on the number of pages that you can copy or the percentage of pages that you can syndicate. Let's see. For the past couple months, we're getting "couldn't fetch" errors, "site map couldn't be read"  

#### [0:41:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2490) |  in Search Console report. Although in running

Inspect URL on the site map URL, we're getting "page fetch successful." The site map XML files are hosted on Google Cloud with Cloudflare CDN. What could be the problem? It's really hard to say without looking at individual URLs. So this is another case where I'd say maybe go to the help forum, because people there have a lot of experience with these kind of issues, and they can guide you to kind of troubleshoot that issue, or can look at your specific URLs  

#### [0:42:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2520) |  and give you a little bit more

feedback on what you could be doing there. Or if they see that you're doing everything right, everything is perfect on your end and Google's messing up, then they can escalate that issue to us as well. We're running an economic portal. Once a month or every two months, the content needs to be replaced and updated based on economic trends. Is it good practice to create new pages for the outdated content?  

#### [0:42:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2550) |  Ultimately, that's totally up to you. If

this is, like, a new site, then maybe it makes sense to create new pages for new pieces of content. If you're just updating existing content, then keeping the same URLs makes it a little bit easier for us to kind of focus on the URLs themselves, rather than having to track more and more and more URLs. So kind of keeping existing URLs and updating those, maybe moving the content to an archive section, that's kind of what I would recommend doing here.  

#### [0:43:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2580) |  But if this is essentially just a

news website where you're creating more news articles based on the current situation, then maybe creating new URLs for this is also fine. It really kind of depends on the setup that you have, the way that you want to present that to your users. I have an informative multi-language site-- English, Spanish, and French-- and I'm using hreflang tags. Is it OK that the English version has more content  

#### [0:43:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2610) |  than the other two versions? Can it

be bad for SEO? That's perfectly fine. That's something that sometimes happens where, if you focus on one or two languages, you have a lot of content that's in that language, and maybe some of those pages are translated into multiple other languages, and that's perfectly fine. Like I mentioned in the beginning, we use hreflang to swap out the URLs. So when we aren't sure which version to show to a user, we'll swap that out.  

#### [0:44:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2640) |  But if you only have one version

of the content for a specific query, we'll focus on that. So if you have, say, 10 pages in English and five of those are translated into other languages, that's perfectly OK. You don't need to have everything localized if you don't want those localized versions indexed. Which one is better for mobile optimization-- AMP or PWAs?  

#### [0:44:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2670) |  Which would you recommend? Those are very

different technologies, so I think it's really hard to, I don't know, draw a line between which of these that you should do. There's also a combination available there as well, where you essentially use AMP pages as a part of a PWA. So that's something where instead of just blindly shifting to whatever technology someone is  

#### [0:45:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2700) |  telling you is the best at the

moment, I would recommend taking a look at your website, the content that you have available, the kind of infrastructure that you have available, and then making a decision based on that, based on the different options that you have available. So instead of just blindly saying, well, PWA is best, I will switch everything to PWA, think about, like, what are the options? How easy is it for you to shift to one different technology? Is that something that even makes sense for your website?  

#### [0:45:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2730) |  For example, if you have a highly

interactive website, then maybe shifting to AMP is a bit tricky, because AMP is so based on a lot of the kind of caching and things like that. You can still do it, but it'll take a lot more work. So I would really kind of use these as different frameworks and different ways of building websites, and kind of pick the setup that matches your current environment best, rather than to just blindly say  

#### [0:46:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2760) |  one of these is the best. And

from an SEO point of view, we try not to give preferential treatment to any of these specific frameworks. So if you're using AMP or if you're using a PWA setup or if you're using, I don't know, a React framework or you're using WordPress or using Blogger, we try to just work with the infrastructure that you have, and we try to rank that appropriately. So it's not like switching to one of these technologies will make your site pop up in rankings.  

#### [0:46:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2790) |  It's more, well, they're different ways of

making a really fantastic website, and you need to figure out which way works best for the situation that you're in at the moment. All right, we're running low on time, so let me double check. Wow, lots of things in the chat. But maybe I can open it up to folks from your side  

#### [0:47:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2820) |  if there's anything. AUDIENCE: John? JOHN MUELLER:

Yeah. AUDIENCE: Hi, my name is Brian. I'm based in Spain. I have a rather convoluted issue. I think it's fairly unique, but we'll find out in a second. Maybe I'm overcomplicating it. So basically, due to a copyright issue in Europe, I-- that I work for, we have two-- we have almost the same exact English language website  

#### [0:47:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2850) |  on two different domains. With the exception

of some branding differences, it's basically the exact same website on two different domains. One is for the rest of the world, and one is for Europe. So in addition to concerns over duplicate content, it seems that Google's having-- it's a bit confused as to which is the proper site to show in search depending on the location of the searcher, i.e. whether the searcher's in Europe or outside Europe. This gets even more complicated as Europe has so many languages  

#### [0:48:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2880) |  and thus, we have various different language

versions of this European domain. However, we obviously do not cover every single language in Europe. We have covered, let's say, five languages. Thus, we want the English version of the EU domain to be the default for European users that don't fit into one of those other languages within Europe, right? So for example, if somebody's searching from Poland, we don't have a Polish version of that domain.  

#### [0:48:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2910) |  We want them to go to the

English one, right? OK. So the question is, how do we tell Google that there's a default site for Europe in English, and also that there is an English language version of the website for the rest of the world? hreflang would be what I would say, except for then we start getting into weird situations where we have, like, 50 hreflang tags because we want to tell Google that the rest of the world--  

#### [0:49:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2940) |  the one domain is for the rest

of the world in English, but we have a domain in Europe that's for English. And then you have to go, you know, German English, Spanish English, you know, x country in Europe English. Is there a more elegant way to do that, or is that the way you would do that? JOHN MUELLER: That's essentially what you'd need to do now. So, I mean, you can use the same page and say, this is for, like, this set of countries in English. And then you have an x default version,  

#### [0:49:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=2970) |  which is a different URL. AUDIENCE: Right.

JOHN MUELLER: But essentially, that's kind of what you need to do. And I think the tricky part will be this is not a guaranteed approach, in that we will take the hreflang and use it as a signal. And if we see the same content on multiple pages, then it might be that we still pick one of those to show in search. So it's kind of the best you can do, that kind of thing, when it comes to search, but it's not guaranteed. So what you'd still want to do is do something  

#### [0:50:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=3000) |  like a banner on top and say,

well, this is kind of the wrong version of the site. We have one specific for Europe, and you can click on the link here to go there, to kind of back that up. The other approach could be to do some kind of geospecific redirect, which in your case might be possible. What would happen there is we-- because Google primarily crawls from the US, we would see the kind of global version.  

#### [0:50:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=3030) |  And if you redirect everyone from non-European

countries to the global version, then we would be able to index the global version properly. And when users from Europe go to the global version and you redirect them to the European version, then we'd-- like, we wouldn't see that, because we crawl from the US, but you can do that for users because you know a little bit more. And especially if the content is the same on the global and the European version, then there's no loss with regards  

#### [0:51:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=3060) |  to search if we were to only

index the global version. If the content were different, then that's something you'd want to avoid that. In particular, if you have different language versions, then if you redirect, like, all American users to the English version and European users can look at the French, German, Spanish versions, then we wouldn't be able to notice that you have French, Spanish, German versions. But if it's English, English, and the content is exactly the same, then you can essentially do that with a redirect, too.  

#### [0:51:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=3090) |  So those are kind of the two

options there. With regards to redirect, I don't know if there is something from the European side that you need to watch out for. I seem to vaguely remember something that you shouldn't redirect users from Europe automatically, but I don't remember the details there. But purely from a search point of view, that's something you could do. Showing a banner is a little bit friendlier, and that users can still choose which one to go to. But those are kind of the two options.  

#### [0:52:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=3120) |  hreflang is something that would help here,

but it gets really tricky. When you have so many different pairs and when you have the same content, it can still happen that we'd pick one of the other versions to show. AUDIENCE: OK, sure. And just to follow up on that really quickly, I think my webmaster is quite-- he's based in the US, and he's afraid of duplicate content. So he's almost afraid to point out to Google  

#### [0:52:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=3150) |  that we have these two domains that

are almost exactly the same in English. JOHN MUELLER: That's, like, no problem at all. That's-- AUDIENCE: That's what I tell him, but just wanted to-- this will be my evidence, so. JOHN MUELLER: Yeah. AUDIENCE: OK, great. JOHN MUELLER: I mean, that's a really common situation. We see that a lot here in Europe with German content for Germany, Austria, and Switzerland, where they all speak German. So it's the same content. These are different countries. And that's essentially perfectly fine.  

#### [0:53:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=3180) |  From a duplicate content point of view,

we will recognize that it's duplicate content, and we might fold them together into one URL. But with the hreflang, we can kind of swap that back, and there is no disadvantage to us recognizing duplicate content. It's not that we will treat this site in any way worse and say, like, oh, there's duplicate content. It's a bad site. There are technical reasons for duplicate content, and that's perfectly fine. AUDIENCE: OK, great. Thanks for the help. JOHN MUELLER: Sure.  

#### [0:53:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=3210) |  OK. We're kind of at time. If

someone has a really short question, I can-- AUDIENCE: Sorry. JOHN MUELLER: --take that. AUDIENCE: Very short question, John? JOHN MUELLER: OK. AUDIENCE: Right. So we're working on a website which we cannot really make mobile. We can not really make it mobile friendly, so it's kind of a desktop version. And we are aware that Google has switched to the mobile first indexing strategies. So we are wondering if we decide that we are actually moving forward with the desktop version of the site,  

#### [0:54:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=3240) |  is Google-- how much of a penalty

is it going to incur on our side? JOHN MUELLER: Yeah. So with mobile first indexing, we use the mobile-- the version that you would see on a mobile device as a basis for indexing. That doesn't mean it has to be mobile friendly. So if you can zoom in on the mobile device and you see the full content, that's perfectly fine. A lot of these ancient web pages that maybe have a table setup or just, like, ancient HTML,  

#### [0:54:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=3270) |  they work on a mobile device. You

have to zoom and kind of swipe around to see the content, but the content is there. And in those cases, mobile first indexing is perfectly fine. What you will see is probably an effect from ranking for users on mobile when they search on mobile. We will recognize, oh, this page isn't friendly for mobile devices. Maybe we shouldn't rank it as high. But if you're saying, like, people only care about our site when they're on desktop, then that doesn't change anything.  

#### [0:55:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=3300) |  AUDIENCE: And as a very quick follow-up,

if there is, on some pages that we've designed, some content when we render the page immediately, it might be closed. It might be hidden from the user. If we instead of basically showing the content as text on the page, if we use the micro lay-- what's the word? Micro layout-- the JSON-LD, basically, to say that, oh,  

#### [0:55:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=3330) |  this is the content of the page,

is Google going-- will Google use that information instead of the basically hidden-- again, we're wondering if Google is going to penalize us for-- if text is not immediately available on the page. JOHN MUELLER: So we wouldn't penalize the site for that, but we wouldn't use that structured data. So for example, if you have reviews in structured data and the reviews are not in the HTML, then we would say,  

#### [0:56:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=3360) |  well, this review is probably not visible

to users. We won't use that review. We won't show that review in the search results. We can show their page for its normal rankings, just not with that review. So that might be OK. On mobile, a common pattern is that you click on something and it falls out or expands. If the content is in HTML and it just becomes visible or it becomes invisible, that's perfectly fine. AUDIENCE: OK. Thanks.  

#### [0:56:30](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=3390) |  Thanks a lot. JOHN MUELLER: Sure. All

right, so let's take a quick break here. It looks like there's still lots of questions. There are more in the chat as well, but we have another session lined up on Friday, so feel free to copy things over to the Friday one and we can take a look at that there. And in the meantime, you're also welcome, of course, to use Twitter to contact us, or to use the Webmaster Help Forum to contact the product experts that we have that have spent a lot of time to understand these problems  

#### [0:57:00](https://www.youtube.com/watch?v=1iDw3fVBhpE&t=3420) |  and can generally help out as well.

All right. So thanks a lot for joining, everyone, and I hope you found it useful. And hopefully, I'll see you all again in one of the future sessions. AUDIENCE: Thank you, John. We appreciate it. Thanks. JOHN MUELLER: Bye, everyone. AUDIENCE: Bye, everyone.  