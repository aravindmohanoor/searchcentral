[![English Google Webmaster Central office-hours from February 18, 2020](https://i.ytimg.com/vi/vw--gvt99Mc/maxresdefault.jpg)](https://www.youtube.com/watch?v=vw--gvt99Mc)

## English Google Webmaster Central office-hours from February 18, 2020

This is a recording of the Google Webmaster Central office-hours hangout from February 18, 2020. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Watch out for new sessions, and add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



Feel free to join us - we welcome webmasters of all levels!



#### [0:00:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=0) |  JOHN MUELLER: All right. Welcome, everyone, to

today's Webmaster Central Office Hours Hangouts. My name is John Mueller. I'm a webmaster trends analyst here at Google in Zurich. And part of what we do are these Office Hour Hangouts where anyone can join in and ask any kinds of questions around websites and web search, and we can try to find some answers for you. A bunch of things were submitted already, but as always, if any of you want to get started with a question of your own  

#### [0:00:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=30) |  that's been burning on your mind, feel

free to jump in now. MIHAI APERGHIS: I could go ahead I guess. JOHN MUELLER: All right. Take it away. MIHAI APERGHIS: So this is in regards to actual site map handling for very large websites, or large websites-- hundreds, thousands, millions of URLs. And the website is in the classifieds area,  

#### [0:01:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=60) |  so there's a lot of new URLs

popping up every minutes, every few seconds, something like that. So obviously there is the documentation on building a sitemap. You can update it dynamically, as you should, and then ping Google to let them know that the sitemap has been updated. What do you do when that update frequency is incredibly large and every few seconds you get a new URL or something like that?  

#### [0:01:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=90) |  Is the sitemap still a good way

to notify Google of these new URLs? Or given that it's not a publisher, so you cannot really use the-- I'm not sure if you can use the [INAUDIBLE] kind of sitemap, because I know that's also an option but more for publishers. So what would the best practice here? JOHN MUELLER: You can definitely still use a sitemap or you can use an RSS feed.  

#### [0:02:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=120) |  I think those are kind of the

directions I would go. The one thing I would try to do is maybe split it up into parts where you have the recent content and kind of the more stable or longer form content so that you don't have to submit all of your sitemap files every time there's a change. So that you have something like a sitemap file for the last day or for the last couple hours, and you just resubmit that one when there are updates that are happening.  

#### [0:02:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=150) |  And then over time, when a URL

stays around for longer, you can move it to one of the more stable site files on your site. But essentially, you have kind of one smaller file that you submit with the regular updates. With an RSS feed, that kind of happens automatically because the RSS feed only has the last couple updates in it. And with the RSS feed, you can push those to Google as well, with PubSubHubbub or Web Push, what it's called now, to kind of send those updates a little bit  

#### [0:03:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=180) |  faster. But that's kind of the direction

I'd go. I wouldn't try to update all sitemap files all the time and just send all of them again, because that's too much work on your side, and we process all of the millions of your URLs and we only find 25 that are new. So you might as well just send us those new ones separately. MIHAI APERGHIS: OK. So what would be a good minimum frequency  

#### [0:03:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=210) |  for these kind of new URLs? Again,

given what we might have 50 URLs a minute or something like that-- 50 new URLs a minute. JOHN MUELLER: I would submit them once a minute maybe, once every couple of minutes, something like that so that you have a reasonable set, but you're not pulling Google constantly with submissions. MIHAI APERGHIS: And the other one can be once a day, the bigger one.  

#### [0:04:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=240) |  JOHN MUELLER: Sure. MIHAI APERGHIS: And regarding

the bigger one, that will likely also have a lot of classified ads that are expiring so they're no longer available. Is that fine if they're still in the sitemap or that they disappear the day after? So it's not a big problem? JOHN MUELLER: I think, especially with classifieds which have a specific runtime, I would use the unavailable after meta  

#### [0:04:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=270) |  tag to let us know that this

is something that will be valid for the next week or whatever. And then that's something that we can take into account a little bit faster rather than having to kind of refresh every page and then check for the no index. MIHAI APERGHIS: OK. So if you had to choose between the sitemap version and the RSS version, is there any benefit to either? JOHN MUELLER: I don't see any big advantage either way, no.  

#### [0:05:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=300) |  It's whatever is easier for you to

generate. That's kind of what I want to focus on. MIHAI APERGHIS: We'll try one of the versions, see how it works out, and take it from there. Thanks. JOHN MUELLER: Cool. JOSEPH SOUTH: John, I have a tangential question on that, particularly to the unavailable after. I work in the automotive industry, and we're seeing a lot of vehicle detail pages that remain on the website long after the vehicle has sold.  

#### [0:05:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=330) |  And then it's kind of muddying the

waters, because each of those product pages essentially has the brand, the manufacturer, and the make. Or, sorry, the make and the model of each one. And so we're ranking for those make model keywords. If we were to put in unavailable after, say, a week from today, would the crawler come back and check to see if it's changed before it hits that date?  

#### [0:06:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=360) |  And if we change the unavailable after

date to then extend it, could we roll that so that-- JOHN MUELLER: Sure. JOSEPH SOUTH: OK. Awesome. JOHN MUELLER: Yeah. That should work. You can definitely change the unavailable after date. And if we re-crawl that page then and we see that it's still there, then we'll still keep it in. So I think that might be an option. In general, though, with a lot of these things,  

#### [0:06:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=390) |  I think you have to assume that

sometimes we will try to send people to a page that doesn't exist anymore. So catching that in some kind of a user-friendly way is also very important. JOSEPH SOUTH: We have redirects that go to a search result page or a soft 404 afterwards. So there is a fallback. I just want to make sure that we have the most efficient line  

#### [0:07:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=420) |  of defense first. And then if that

fails, then we have a failsafe and that it would all still be customer approved and friendly. JOHN MUELLER: That sounds good. Cool. ARNOLDO C: Hi, John. Arnoldo here. JOHN MUELLER: Hi. ARNOLDO C: Hi, how are you? I'm calling in relation with a case we have open now for [INAUDIBLE] in a previous session  

#### [0:07:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=450) |  or agency in Germany. They contact you

through this forum. So now we are in the process of cleaning out, basically, a lot of all content. We are just doing a clean up. But we still see that Google ignored the German language version and ran the Austrian.  

#### [0:08:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=480) |  And then in Search Console, we see

also that the referral pages are like third party external spammy domains, which is weird. And that is the behavior that we see. But we've been doing the-- basically checking all the basic stuff, and we still see that Google doesn't catch the German version yet.  

#### [0:08:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=510) |  JOHN MUELLER: Yeah. Sometimes these things take

a while to settle down. So especially if there used to be or if there still is the same content in the same language on multiple URLs, then it can happen that we pick one of the country versions as the canonical, and we show that one in the search results. But I think I looked at it with the team after the last Hangout where this was mentioned, and it sounded like that's something  

#### [0:09:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=540) |  that the team is looking into to

see if we can speed that up in general so that it doesn't last as long for sites in the future. [INTERPOSING VOICES] ARNOLDO C: Yeah, I understand, thanks. The other behavior that we see is that Google is actually showing [INAUDIBLE] like all platform. Like URLs, sites that we migrated since two years ago and then also back in March we did another migration.  

#### [0:09:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=570) |  So it looks like you guys keep

these old URLs as a fallback. Why is that happening? JOHN MUELLER: I don't know which exact URLs you're looking at. But in general, there are two main reasons when this happens. On the one hand, when the canonicalization, from our point of view, is not completely clear.  

#### [0:10:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=600) |  So if we're not perfectly sure which

one of these URLs from the set of pages that we think belong together is the right one to show, then that's something where we might pick one which you think is like an older one or that we shouldn't have picked. And that's something where we use a lot of different signals to try to figure out which of these pages to show. And sometimes if those signals don't match, then we have to kind of make a judgment call.  

#### [0:10:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=630) |  Or rather, our algorithms do that. So

that's the one thing. And the other time that I see this happening fairly frequently is if you explicitly look for the old content. So I don't know if that's what you're seeing. But for example, if you move from one domain to another and you do a site call and query for the old domain, or you search explicitly for the old domain or the old brand name or something like that, then we'll still show you the old domain, even  

#### [0:11:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=660) |  though we've moved everything over to the

new domain. And that's something that can happen for, I think, several years going forward where-- or from the past-- where if you search for something that has moved a couple of years ago and we think you're specifically looking for that, then we'll try to show it to you because we're trying to be helpful. But from kind of an SEO point of view, from an analytics and tracking point of view, you don't want to Google to be helpful. You want to see the new thing.  

#### [0:11:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=690) |  But that's sometimes a confusing setup that

happens. And if there are redirects set up from the old one to the new one, then even if users see the old one in search, they'll make it to the new one. And it's not that the ranking would be any different if we pick the new URL by default. ARNOLDO C: Would you recommend-- right now we have the [INAUDIBLE] implementation on the sitemaps. Would it help to have it on the page,  

#### [0:12:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=720) |  or it will not make any difference?

JOHN MUELLER: It wouldn't make any difference. If we see it in the sitemap and it's the right URLs in the sitemap file, that's exactly the same from our point of view as if it's on the page. ARNOLDO C: OK. Perfect. Thanks. JOHN MUELLER: Sure. ARNOLDO C: I'll keep joining here and see how this develops. Thank you for your answers. JOHN MUELLER: Cool, thanks. JOSEPH SOUTH: John, in a space where you've switched domains, would clearing the cache then remove those indexed pages  

#### [0:12:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=750) |  from the previous domain? JOHN MUELLER: No.

So I assume you mean the removing the cache tool in Search Console? JOSEPH SOUTH: Yes. JOHN MUELLER: Yeah. No, that wouldn't change anything. That's basically-- it just hides the cache page from the search results and removes a snippet. It wouldn't change anything from the indexing side. In general, the URL removal and the cache update tool,  

#### [0:13:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=780) |  they don't change anything from indexing. They

just try to kind of apply a Band-Aid in the search results when someone searches for it. JOSEPH SOUTH: OK. Would removing the old domain-- completely shutting it down-- then removes the results for the old domain? JOHN MUELLER: Yes. It would remove those results, but it would also prevent you from getting any of the traffic if we accidentally sent people to the old domain. So that's something where I would recommend just  

![](https://i.ytimg.com/vi/vw--gvt99Mc/maxres1.jpg)



#### [0:13:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=810) |  keeping the redirect up, and that's something,

over time, we'll pick that up. The tricky part I've seen is when you change a domain name and people used to search for your domain name specifically, because maybe the domain name is almost like a part of your brand, then those are cases where if someone searches for the old domain name, we'll still show the old domain name. But if you look at the cache page for that URL, then  

#### [0:14:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=840) |  oftentimes you'll see we've actually indexed the

new version. We're just showing the old URL in the search results because we think that's what people were looking for. JOSEPH SOUTH: Does it maintain the old metadata, the old description? Or will it appropriate the new domain [INAUDIBLE] description? JOHN MUELLER: Yeah, it takes everything from the new domain. So if we've switched indexing to the new one and we just show the old URL, then all of indexing is based on the new one. The ranking is based on the new one, all of that.  

#### [0:14:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=870) |  So it's really just the URL that's

shown in the search results. OK. Let me run through some of the submitted questions, and if you have more questions along the way, feel free to jump on in. Hopefully we'll have some time towards the end as well to go through some other live questions. So some of these are pretty long. I'll try to shorten them a little bit.  

#### [0:15:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=900) |  The first one is, we have over

3,000 articles in our help section and we want to make them available in 25 languages. Would using the Cloud Translation API hurt our website? So of course, we'd use the Translation API markup and warnings. Would these articles be considered low quality? Is that too many articles? We can't do this manually. So first of all, I was not aware of the Translation API markup.  

#### [0:15:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=930) |  I looked that up. That was pretty

interesting to see. That's kind of a lang attribute that you can add to the pages, or to elements on a page, when they're machine translated, which helps our systems to understand that this is actually machine translated content. We shouldn't use it to learn further translations. So that's pretty cool. So from a purely technical point of view,  

#### [0:16:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=960) |  there is a bit of a split,

I would say, within Google with regards to what we'd recommend doing there. On the one hand, from the webmaster guidelines point of view, we might consider this to be automatically generated content and we'd say, well, you shouldn't allow automatically generated content to be indexed, especially if it's lower quality content. I think with machine translation, it's kind of reaching a point where machine translations are actually pretty good, and it's no longer the case  

#### [0:16:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=990) |  that machine translated content reads like gibberish

and you can barely guess what the meaning is. But actually, it's fairly reasonable translation. So from that point of view, you could argue either way and say, well, this kind of content is reasonable enough for me to stand behind as something that I would publish on my website. And in that case, that might be an option for you to say, well, I'll take these and run it over the articles that I have,  

#### [0:17:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1020) |  and generate it for the languages that

I think are important for our users. That might be something to take a look at. On the other hand, especially when we look at the quality of a website overall, we do look at the quality overall. And if you're taking 100,000 articles and you're running translations in 25 languages over it, then it's going to be really hard for you to confirm that the quality that you're generating like this is actually high enough that you'd be able to stand behind it and say, well, this is what I want my website  

#### [0:17:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1050) |  to be known for. So that's something

where I would take this step by step and think about it incrementally. Try things out. Test some languages where you have testers who can help you to double check that the localization is really actually useful translation and not just a you can kind of guess what the meaning is translation. And if you can determine that those languages for specific articles on your website are actually pretty good, then that  

#### [0:18:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1080) |  might be something you'd want to set

to be indexable. On the other hand, if you're really unsure if this is something that you want to have indexed for your website to stand behind, then that's something where maybe you'll set it to no index, or you'll use just the JavaScript widget so that it doesn't generate any separate pages for your website. So that's something where there isn't this by default behavior that we would say, oh, if you use this kind of translation, then we'll think your website is really fantastic.  

#### [0:18:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1110) |  But really, you need to double check

that yourself. And that's something that's sometimes a bit hard to do. So just blindly going and saying, I have 100,000 articles and I want 25 languages, and hitting the button to generate all of those, that's probably not the right approach. But rather, you want to take this step by step and make sure that you're actually creating something that is useful for your users that doesn't come across as gibberish, where if they come to your website  

#### [0:19:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1140) |  and they see this localized version they're

like, this doesn't make any sense. This website is more like spam rather than actually something reasonable. Our website focuses on troubleshooting, and I often find links getting posted on forums with foreign language or non-English forums. They're all relevant posts. Is it negative in the eyes of Google? The language on my website is 100% English. So that might be perfectly fine.  

#### [0:19:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1170) |  Just because people in other languages are

referring to your content doesn't mean that that's necessarily bad. I think, in general, that's actually a good sign. If you're creating something so useful that people refer to it even if it's not in their own language, then that's usually a good sign. So from that point of view, I wouldn't worry about this, but rather see it as kind of a positive thing. It might even be something where you go further and say, well, lots of people in these specific languages  

#### [0:20:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1200) |  are referring to my content. Maybe I

can do something on my website to cater my content better to them, even. But it's definitely not something where you'd look at it and say, well, these links are coming from foreign websites. Therefore I need to disavow them, or I need to block them somehow. It's perfectly fine and natural to get links from all kinds of websites. [INTERPOSING VOICES] JOHN MUELLER: Yes?  

#### [0:20:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1230) |  MATEI NICOLAE: I have a question. It's

[INAUDIBLE] measurement question. In Search Console, we have a client that has redirection based on [INAUDIBLE].. So when someone searches for their brand, they will be redirected to sometimes even a different domain than the one showing in the search results. Where is the click counted? [INTERPOSING VOICES] JOHN MUELLER: Where is it counted?  

#### [0:21:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1260) |  So if we show something in the

search results, then we would track that there in Search Console. So Search Console itself wouldn't know what happens after someone clicks on a page in the search results. In Analytics, you might see that differently. If you're tracking the user facing analytics, then that might be different. But in Search Console, that would refer just to what we show in the search results and which ones people clicked on there.  

#### [0:21:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1290) |  MATEI NICOLAE: OK. The problem is that

if the search term is HBO, and we're working with HBO Nordics. The first result when you search for HBO from Sweden is hbo.com. We think most of the users click there, but Search Console data shows over 50% click through rate on the Nordic domain-- the HBO Nordics domain. It feels kind of strange to have people clicking  

#### [0:22:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1320) |  on the second result when the first

one is what they're searching for. Is it possible that is double counted or no? JOHN MUELLER: No. That shouldn't be double counted or anything like that. I don't know the query and which languages you're seeing this in. But what can sometimes happen is that we show an English search result for something generic like that, as well as a local search result. And it might  

#### [0:22:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1350) |  be that users are just seeing, oh,

this English result and the result in my own language, and they click on their own language version. Because it's kind of tricky with a query like HBO where we wouldn't be able to tell which language the user is actually searching in. MATEI NICOLAE: OK. Thanks. JOHN MUELLER: Sure. That might also be something where using href lang would help you, because then we would  

#### [0:23:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1380) |  be able to take the user's language

settings and try to show the right version of that site. And that's something that you could do, for example, just for the home page, or separately for the home page from the rest of the site, so that for queries which are very generic, we'd be more likely able to show the version that matches the user's language directly. MATEI NICOLAE: OK. Thanks. JOHN MUELLER: Sure. All right. And now a structured data question.  

#### [0:23:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1410) |  I guess a tricky one. So when

you search for a half dome tent, the top result is the old product page, which includes a call out to kind of see the new version. And there's also a canonical on that page pointing to the new version of the product. And I think the question kind of goes into, would using structured data in any way help to show the newer version rather than the older version?  

#### [0:24:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1440) |  And I took a quick look at

some of the URLs that are involved with this. And essentially, what is happening is, on the one hand, we struggle to see the connection between the old URL and the new one because it's not that clear of a situation that these URLs are exactly the same content. So that's something for, from canonicalization, we're kind of unsure if these actually belong together. And the other part that's coming together here  

#### [0:24:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1470) |  is that, for canonicalization, we use a

number of signals. So we do use the rel canonical on the page, which is something that's specified well here. But we also use things like internal linking, external linking, sitemap files, all kinds of other sources as well. And I assume if you take a URL that is fairly well-established and you create a second URL with a product that replaces the first one, then that established URL is going to remain visible in the search results for quite some time  

#### [0:25:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1500) |  until we've really learned that the new

URL is the be better version for these kind of search results. So that's something where structured data probably wouldn't change anything there. So in particular, using something like successor of or predecessor of, that wouldn't change anything from our point of view. It's really just that canonicalization decision where we have a lot of collected signals for the old URL  

#### [0:25:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1530) |  and not really a ton of good

signals for the new URL, and we struggle to connect those two completely. One thing you could do is redirect from the old version to the new one. That would help us to figure this out a lot faster. But at the same time, if you want the old product to remain available in the sense that, if people search for the old product, they can find replacement parts or find manuals, those kind of things,  

#### [0:26:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1560) |  then you don't want to completely remove

the old product. The solution that we generally recommend for this general kind of problem where you have one product and then you have a replacement for that product is to reuse the old product URL for the new product, and move the old product content to kind of an archive section. That way you build upon the success of your old URL,  

#### [0:26:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1590) |  and you add the new content there,

the new product, the new product description, new pricing, or whatever you have. And you still have the old product information, and you just move the old product information to an archive section where it's a little bit less visible, less strongly shown in the search results, because it's a new URL. So that's the general situation, or general direction that we would head, with something like this.  

#### [0:27:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1620) |  I imagine for e-commerce sites, that's really

kind of tricky, because it's hard to move one product to an archive section and reuse the old URL with maybe an article ID and things like that that are associated with it. But that's generally the direction that we would go. We would also use this for recurring events. So if you have something like a yearly conference, then instead of creating new URLs for every year,  

![](https://i.ytimg.com/vi/vw--gvt99Mc/maxres2.jpg)



#### [0:27:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1650) |  then instead use one stable URL for

the conference, and move the previous years to an archive section. So that in both of these situations, you're building a stronger and stronger URL for the persistent version for that product, and you're moving the old things off to URLs which are a little bit weaker within your website so that they're less emphasized in search. And structured data-- I don't think structured data would play a role here at all.  

#### [0:28:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1680) |  So using this setup with regards to

structured data of saying, well, these are connected like this, that's not something that we would use at all for this canonicalization or figuring out which one of these URLs is the one to show at the moment. [INTERPOSING VOICES] SARAH MASON: Hey, John. MIHAI APERGHIS: Sorry, go ahead. SARAH MASON: I actually wanted to ask a structured data question. I thought I put it in the comments, and I'm not seeing it anymore. So I noticed that some of the Google structured data  

#### [0:28:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1710) |  requirements can be a little bit-- there

can be more requirements there than what schema.org requires. So I work for an educational institution, and we want to have content structured data around that talks to our degree programs, especially for use in Google colleges and universities. But I noticed that in the structured data list, there really doesn't seem to be a good type for full degrees.  

#### [0:29:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1740) |  In fact, some of your structured data

types specifically say it's not for full degrees. Do you have any recommendations there? Especially given that sometimes, when we test out some of the schema.org structured data types, we get notifications from Search Console that, hey, this thing is not parsable because it's not actually Google's structured data type. JOHN MUELLER: Yeah. So I don't know specifically about that kind  

#### [0:29:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1770) |  of structured data. But in general, it's

certainly the case that, within schema.org, there's a lot more structured data that's available. And we only take a small subset of that and use that directly for the rich results and the search results. If you use other parts of schema.org which we wouldn't use in the rich results, we would still try to understand that. But it's not that we would show it in any particular way in the search results. So going past what we would use directly  

#### [0:30:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1800) |  is certainly an option, but I think

for the most part you wouldn't get any visible effect from that. So that's kind of the starting point there. Within the structure data testing tool, I believe the structured data testing tool sticks a little bit stricter, or aligns more, with the schema.org markup. And the rich results test is really based on how Google would show that in the search results. So it only uses a subset of the general structured data  

#### [0:30:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1830) |  that we would find. With regards to

which one to best use in a case like yours, I don't know offhand. There are so many different types. But I would generally try to, first of all, see if there's a type that is actually shown in the search results that matches what you're trying to achieve, and then focus on that, which would be what we would have documented in the developer  

#### [0:31:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1860) |  documentation for search. And if there is

nothing there that works for you, then you can use the schema.org markup, but I wouldn't expect a lot of visible results from that. So in particular, we'd use this to better understand those pages. But if we can already understand that this is a course or there is information about an educational setup thing here, then that's something we probably already have that information. And we don't need a lot more information  

#### [0:31:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1890) |  about that to be able to show

those pages in search, because we're already mapping them to the right queries. Whereas if it's kind of ambiguous, then that's something where extra structured data helps us a little bit. SARAH MASON: Yeah, I think I was really thinking about it, especially in terms of Google Colleges and Universities, assuming that there would be a heavier reliance on structured data for that application within Google. I didn't know if that was something that-- in my research, I haven't found anything that specifically  

#### [0:32:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1920) |  says yes, but I kind of made

that assumption that that would be used moving forward. JOHN MUELLER: I don't know. So the tricky part is I think that's something that we only show in the US. So that's something where, if I don't see them in search, then it's really hard to get some firsthand experience with that. But I don't know exactly how we would show that  

#### [0:32:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1950) |  or where we would get that from.

But that's something where, if it's not documented in our developer documentation, then I'd assume that we don't use the structured data there directly. SARAH MASON: Thank you. JOHN MUELLER: Sure. OK. Is it true-- Oh, go for it, Mihai. MIHAI APERGHIS: I have a quick follow up to that example  

#### [0:33:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=1980) |  you gave earlier with the product being--

the same URL being reused for products that get out of stock and things like that events. I was also thinking about how you would apply that to the classified sites example I gave earlier. Would you be able to do something similar, given that most URLs are being created by actual users? And so it's user generated content.  

#### [0:33:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2010) |  But it's likely that a lot of

ads are very similar in what they have to offer. So when one expires, would it be possible to maybe redirect or use a rel canonical to add [? a different ?] ad from a different user that basically sells the same product or service? Would that be-- JOHN MUELLER: I think that might be a bit confusing for users. But having something like tag pages or category pages,  

#### [0:34:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2040) |  that seems like something that would work

better where, if you have a category page for this brand of car and you swap out the classified ads that you have so that this category page remains relevant for the long run, then that's something that we could probably pick up on and use like that. But for the individual classified ads, that seems tricky to determine that connection.  

#### [0:34:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2070) |  So it's very easy to say oh,

based on this one keyword in the old classified and the new one, I would just redirect it to something else. I could imagine that gets a bit confusing. MIHAI APERGHIS: That could be. So having listings or category or tag pages is probably a better way to target those [INAUDIBLE].. [INTERPOSING VOICES] JOHN MUELLER: Yeah. JOSEPH SOUTH: John, a question for you about linking from those category pages  

#### [0:35:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2100) |  and putting a relational tag on the

links themselves. Because it's user-generated content, would you recommend putting the UGC relation from the category page to the actual description page? Or is the UGC tag irrelevant? JOHN MUELLER: I wouldn't use it there because you're kind of linking to your own content. And within the classified ads of users ad links,  

#### [0:35:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2130) |  then that's something where I'd use the

rel UGC. So it's not for situations where you're linking to user-generated content, but rather where the user-generated content links to other places. JOSEPH SOUTH: Great, thank you. JOHN MUELLER: OK. And now an HTML5 question. Is it true that HTML5 semantic tags, like main, article, et  

#### [0:36:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2160) |  cetera, are very important. One SEO expert

said that HTML5 structure is used by Google for fast understanding of the page content before analyzing hundreds of other factors. So we do try to understand the structure of a page, but we can understand the structure of a page in lots of different ways. So it's not that HTML5 section tags are something that we would use specifically when it comes to SEO.  

#### [0:36:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2190) |  And it's not that you have a

ranking advantage over other sites if you use things like main or article elements within your pages. So I think it's good to use proper HTML in general so that it's a clear page. It works well on lots of browsers. It works well for users with disabilities. But it's not something that, from an SEO point of view, we would take into account. And one of the reasons why this is the case  

#### [0:37:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2220) |  is that these technical details are things

that users often don't even notice. And it wouldn't make sense for us to rank pages based on things that are essentially not noticeable by users in that sense. So that's something where you might load a page and it uses an old table-based layout and it hasn't been updated in 10 years, but it's still the right content-- relevant content for the query that you are looking for. It wouldn't make sense for us to say,  

#### [0:37:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2250) |  well, this other page has content that's

kind of OK as well and it uses HTML5 properly, therefore it must be a much better a better result for users. That's definitely not the case. So I think it's good to focus on clean HTML. It makes things a lot easier for your site in general. But I wouldn't see this as a primary SEO ranking factor in that, if you're struggling with ranking, you need to fix your HTML markup,  

#### [0:38:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2280) |  because in general, that's not going to

change anything when it comes to ranking. Oh wow, and a long question, I think, with regards to purchasing website. Can you explain the situation that happens when you purchase an established website, merge most of the content into your existing website, and then 301 from the purchased website's pages through the migrated content? In principle, I would have thought that the final single website would be sum of its parts.  

#### [0:38:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2310) |  However, I assumed that this is maybe

far from the case. Yeah. So in general, moving from one domain to another is something that's fairly straightforward in that we can take all of the old signals and forward it to a new domain. That's the simple part of a site move. Similarly, if you move from HTTP to HTTPS, that's something we can just take everything one to one and pass it on to the next setup, the next domain,  

#### [0:39:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2340) |  the next protocol version. That's essentially the

straightforward type of site move. But as soon as you do things like restructuring a website within the same website, like merging multiple websites into one website, splitting one website into multiple separate websites, that's where it gets a lot more complicated. And that's where, essentially, our algorithms have to reprocess the whole website  

#### [0:39:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2370) |  and understand what is this new website

that we have or these new multiple websites, if it's split into multiple websites, and how do they fit in with regards to the rest of the general ecosystem on the web? How should we understand how relevant some of this content is? Which of these pages can be understood a little bit better with the new configuration? Which of these pages might be harder to understand with the new configuration?  

#### [0:40:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2400) |  And that's a process that can take

a significant amount of time. So in general, if you're looking at various changes on a website and one of the options is, oh, I will restructure everything, or I will merge multiple websites, or split one website into multiple websites, then it's good to keep in mind that those are long term changes that will take a lot of time to be reprocessed. You might see this as something that slowly goes from one state  

#### [0:40:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2430) |  into the other. You might also see

it as something where we start to see this complete restructuring and then we say, oh my god, everything is different. We have to be careful here and try to understand this new website first, where you see a significant dip until we're able to stabilize on a new kind of better understanding of the website in general. So that's something which is really hard to predict ahead of time how these things will happen. I think it's just important, as a site owner,  

#### [0:41:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2460) |  that if you're considering any of these

options, that these are things that will take a lot of time and where you may see significant changes and fluctuations until things settle down into a more stable state. And that stable state doesn't necessarily mean that it'll be the same as before in that, if you restructure a website significantly within the same website, you might see better results later on because you have a cleaner structure.  

![](https://i.ytimg.com/vi/vw--gvt99Mc/maxres3.jpg)



#### [0:41:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2490) |  Similarly, you might see worse results because

maybe the new structure is worse. If you merge multiple websites, it might be that you have a stronger visibility in the search results. But it might also mean that you're merging multiple things, and they're merging in ways that are clashing with each other, which are resulting in a similar search visibility to before, where you had multiple websites showing. Now you have one website showing, but it's kind of shown in a similar way in the search  

#### [0:42:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2520) |  results. So this is something where it's

really hard to predict ahead of time what exactly will happen. And it's definitely not the case that you can just blindly assume that this one plus that one will equal the new one, because you're creating a completely new website, which we have to essentially understand completely first. So that's something where-- I'm not saying nobody should do these kind of moves.  

#### [0:42:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2550) |  Sometimes you have to do them just

because things are changing within your business. But it's good to be cautious about these kind of moves, and especially to see this as something that you don't want to do just to try it out and see what happens. So if you're aware of one of these moves needing to be done in the future, then try to do that in one step so that you have everything moved over to the final state  

#### [0:43:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2580) |  so that you don't run into a

situation where it's like, oh, I will merge everything first, and then I will split it off again, and then maybe I'll restructure part of this again. Because all of those individual changes, they will require a significant amount of time on their own. So ideally, try to find the stable approach that you can keep for the long run, and focus on moving things over to that. Is Zulu time for a news sitemap?  

#### [0:43:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2610) |  OK, so particularly with regard to publication

date. So Zulu time is if you have a Z at the end of the time, which is essentially-- I had to look it up. It's kind of-- what is it?-- GMT time. So essentially, a specific time zone which it refers to. From our point of view, using a specified time zone, like if you have a plus and then a number of hours or minus  

#### [0:44:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2640) |  and a number of hours is fine.

Using the Zulu time is also fine. Those are both well-defined time formats that work well for us. So they're equivalent from our point of view. The examples that you have in the question are not quite equivalent, because they're different times and different days. But essentially, you can use either one of these formats. You can also use some URLs with the Zulu  

#### [0:44:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2670) |  time, some with the offset. That's totally

up to you. The one thing I would watch out for here is to try to be as consistent as possible so that you don't end up in a situation where you specify one time in the sitemap and use a different time zone on the pages themselves. So that's something that we sometimes see, especially when it comes to news content. On the pages themselves, in the news article, you can also specify a time. If you specify the wrong time zone in one of these places,  

#### [0:45:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2700) |  then we'll be kind of conflicted. Or

if you specify the time zone in one of the places and you don't specify the time zone in the other place, then that's also one of those situations where we don't perfectly know what you mean. So if you're using any way of specifying the time zone, then I would make sure to be consistent across your website so that it's really perfectly clear to us, when we look at your pages, this is the exact point in time  

#### [0:45:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2730) |  that you're referring to, not that we

have to guess, oh, the server is located in this place, therefore probably they mean this time zone, so we'll guess that that's the case. Really be as clear as possible if you want to specify something like this. We use got Data Studio for several reportings. And now we recognize that URL impressions plus click through rate and sometimes not even URL clicks sum up as visible in Search Console. How is this possible?  

#### [0:46:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2760) |  What are we doing wrong? Is it

possible to get the correct data in Data Studio? So I think there are a few things that are possibly happening here. It's hard to say exactly what you're seeing. So on the one hand, the fresh data currently isn't visible in the APIs and appropriately not in the Data Studio that is--  

#### [0:46:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2790) |  I think that's also based on the

API. So if you're looking at things from today that happened in the last week, for example, in the performance report in Search Console, then that would not match what you would see in the API. We're looking at ways that we can add the fresh data to the API as well in ways that don't confuse the consumers of the API. Because one of the tricky parts with the fresh data in Search  

#### [0:47:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2820) |  Console is that this is data that's

not really finalized yet, where it might be that we have to clean things up. And that's something that happens in the pipelines along the way. So sometimes you'll see the fresh data shows this many clicks and impressions for a period of time. If you look at that a few days later, you'll see a different number there. That's just because that data has been finalized at that point. And if we were just to blindly inject the fresh data into the API as well, then all of those people  

#### [0:47:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2850) |  who were always trying to get the

newest data with the API, they would be working with the fresh data, which could end up in situations where that data has even stronger mismatch to what is shown long term in Search Console. So we're trying to find a way to make that a little bit easier. The other thing to keep in mind is that the aggregation of the counts that are shown above the table in the performance reports, and the individual rows which are shown,  

#### [0:48:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2880) |  are aggregated separately. So it can happen

in situations where the count on top is slightly higher than the count if you add up all of the rows. Sometimes that's due to the privacy filtering. Sometimes that's just due to the way that we aggregate the data. In general, the higher count is the more accurate one. So if you see a higher count in the sum above, then that's the one that I would focus on. If you see a higher count in the rows shown below,  

#### [0:48:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2910) |  then that's what I would focus on.

But that's something where the different aggregation methods that are used in Search Console, they can be a bit confusing in the UI sometimes. We regularly have people ask us about that. But they're certainly also confusing if you're using the API and comparing the API results to one of those sets, either the numbers on top or the rows that are shown. So that's something where you might see differences because of that.  

#### [0:49:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2940) |  MIHAI APERGHIS: There's actually a good official

support article on how aggregation works, the property aggregation versus page aggregation if you take the rows and just look at the pages. So I found that to be useful as well. JOHN MUELLER: Oh yeah. Definitely, yeah. That's the other point which also makes it tricky. The property and the URL and the query aggregation are sometimes a little bit different as well. It gets really hard when you have a lot of data,  

#### [0:49:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=2970) |  and all of these aggregations, they become

pretty tricky, especially for larger sites. And one place where I've seen the differences more visibly is if you have a larger site and you look at a very small section of that site. Then because those small numbers are a bit out of the aggregate from the larger site, you might see bigger percent wise changes there.  

#### [0:50:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=3000) |  Oh wow, we're running towards the end

of time, so I'll maybe shift things over to questions from you all before I have to jump out of the room here. PATTARIN PINTUSOPON: Yeah, hi, John. Just a quick question about URL inspect in Google Search Console. The thing here is that, because we actually have been through a couple of migration, so we take the same product URL and tested it. And then we found out that the current page that we have live  

#### [0:50:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=3030) |  doesn't have any canonical URL from Google.

But the rest are pointing to a URL that doesn't really exist. JOHN MUELLER: So what is pointing to a URL? PATTARIN PINTUSOPON: So it's pretty much the same URL that is live without the [? trailing ?] slash, so it gets a 301 redirect. So we don't really know how Google come about in picking that new URL to start it, because it's never used on the site.  

#### [0:51:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=3060) |  JOHN MUELLER: I don't know. It's hard

to say without looking at a specific example. If you want to copy the URL into the chat here, I can take a look at that afterwards. PATTARIN PINTUSOPON: Yeah, sounds great. Yeah, I can do that. JOHN MUELLER: OK. Cool. PATTARIN PINTUSOPON: Yep, and just a very quick question-- another one-- on referring page, also in URL inspect.  

#### [0:51:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=3090) |  So we noticed that we are getting

a referring page from a different domain that seems like a spammy domain that are redirecting a couple of times to our page. And Google actually referred that as the referring page. Shouldn't Google only pick the referring page within our domain only?  

#### [0:52:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=3120) |  JOHN MUELLER: No. If we can pick

up a URL from other sources, we might show that too. But it's not going to be the case that this is negatively affecting your website because it's some spammy domain that's linking to your website. But rather it's just we happened to have initially found the URL there and we started crawling from there. So it's not a sign of any quality issue there.  

#### [0:52:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=3150) |  It's more, from a technical point of

view, we found it, and we picked up on it and tried to index it like that. PATTARIN PINTUSOPON: OK. But if we disavow it, for example? JOHN MUELLER: That wouldn't change anything for those URLs that we've already seen because, once we've seen URLs from your website and we've indexed them and noticed that we can index them, then we'll continue to try to index them. If you disavow it, it basically just tells us  

#### [0:53:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=3180) |  we shouldn't be passing any signals to

that URL. But from purely an indexing point of view, from the inspect URL point of view, that would probably remain there. PATTARIN PINTUSOPON: All right [INAUDIBLE].. Thanks. JOHN MUELLER: Sure. DAVE VAN DEN HEUVEL: Hello. JOHN MUELLER: Hi. DAVE VAN DEN HEUVEL: Yes, I'm running a movie website, and we've been working with the schema.org review for quite some time, and it  

#### [0:53:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=3210) |  worked for two or three years. But

after the recent Google update, we keep getting warnings in our Google Search Console that the review item is not supported even if the markup is correct in the rich results test. And I was just wondering, before we change 900 reviews, what should we do? Is there anything for movie websites that are not selling anything, that are just reviewing movies?  

#### [0:54:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=3240) |  JOHN MUELLER: I don't know offhand. But

I do know, with regards to the-- I believe it's the review markup or one of the other types of structured data markups-- we started sending out more warnings about situations where we see that websites are using it incorrectly. So it's not that there is going to be a manual action and we're going to block these. But more it's just, well, this isn't  

#### [0:54:30](https://www.youtube.com/watch?v=vw--gvt99Mc&t=3270) |  aligned with our guidelines. So we want

to let you know that this currently isn't supported like that. And I would focus on the documentation that we have on the developers guide and see if there is a type that matches what you're doing. But I don't know anything specific for movie sites, for example. DAVE VAN DEN HEUVEL: OK. Thank you very much. JOHN MUELLER: Sure. All right. I need to take a break here. There's someone waiting for the room.  

#### [0:55:00](https://www.youtube.com/watch?v=vw--gvt99Mc&t=3300) |  So thank you all for joining in.

The next one in English, I think, will be on Friday, and on Thursday we have another one in German lined up. So if you're keen on joining, feel free to jump in there. Thanks again for dropping by, and hope to see you in one of the future ones. Bye, everyone.  