[![English Google Webmaster Central office-hours from April 28, 2020](https://i.ytimg.com/vi/MlLVBz9xntk/maxresdefault.jpg)](https://www.youtube.com/watch?v=MlLVBz9xntk)

## English Google Webmaster Central office-hours from April 28, 2020

This is a recording of the Google Webmaster Central office-hours hangout from April 28, 2020. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Watch out for new sessions, and add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



Feel free to join us - we welcome webmasters of all levels!



#### [0:00:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=0) |  JOHN MUELLER: All right. Welcome, everyone, to

today's Webmaster Central office hour hangout. My name is John Mueller. I'm a webmaster trends analyst here at Google in Switzerland. And part of what we do are these office hour hangouts where webmasters, SEOs, publishers can join in and ask any kind of website search-related questions that might have come up. Looks like a handful of people are here already, but I'm sure we'll see more over time.  

#### [0:00:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=30) |  A bunch of questions were submitted already

on YouTube, so we can go through some of those. But, like always, if any of you want to get started with the first question, you're welcome to jump in now. Or not. AGARWAL AKHIL: Hi, John. JOHN MUELLER: Go for it. AGARWAL AKHIL: Thanks. Oh, hi Martin. Great to see you as well. John, I had a quick question about cloaking, basically.  

#### [0:01:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=60) |  And the context is that we want

to add tracking parameters to our internal link structure. And it's always said that adding too much might not be good because it delays crawling, and it might be not good for a million-URLs website which we have. So the data team has suggested that when someone clicks a URL, they add it on the go, and they block the bot from accessing those parameters by identifying  

#### [0:01:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=90) |  user agents. Is that a permissible technique?

Because the content remains the same, just that the tracking parameters are added for the users and not the bots. JOHN MUELLER: In general, it's permissible. You can do this. I think it's probably not a great practice, but, in general, it's doable. It's essentially similar to the old session IDs that used to be used in the old days where per session  

#### [0:02:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=120) |  you would add parameters to the links

on the page, and then when a user clicks on those links, those session parameters would be passed on so that you can track that a little bit better. In general, for crawling, that's something that makes sense to suppress so that search engines don't run across those. What I would not do is block them by robots.txt, but instead maybe use a rel=canonical on those pages  

#### [0:02:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=150) |  to point out the canonical version, or

maybe even redirect to the canonical version, if you can do that. In general, I try to avoid doing this kind of tracking through the URL itself because it makes everything a little bit messier. Because then, when you look at your log files, it's a lot harder to tell which are the pages that actually get the most traffic, how do users in general navigate around my website, because you always have these kind of tracking parameters attached to the URL,  

#### [0:03:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=180) |  depending on the user, depending on how

they came in. So I think it's probably suboptimal to do it like that. It's not illegal in any sense, or against the webmaster guidelines or anything like that. It's just, I'd say, not a great practice. AGARWAL AKHIL: Cool, John. Thank you so much. And hope everyone is safe at business. JOHN MUELLER: Thanks. Cool. Any other questions before we jump in with the rest?  

#### [0:03:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=210) |  SHAO CHIEH LO: Hey, John. I have

a question. JOHN MUELLER: Hi. SHAO CHIEH LO: My question is just that I want to clarify how keyword cannibalization actually works. Is the whole concept of keyword cannibalization is just referring-- a concept to describe it's counterproductive to target the same keyword with two page, or it's actually an algorithmistic penalty for two page to target the same keyword? So, for example, if I rank for top four for a page,  

#### [0:04:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=240) |  if I publish another page targeting the

same keyword, will it drag down the top four ranking? Or it's just counterproductive to publish another page to target that? JOHN MUELLER: There is no penalty for doing that. It's not that there is any kind of manual action or any algorithmic action that would say, oh, you have two pages, therefore they can't be as good. Most of the time, the issue just comes up in that you tend to have two pages that  

#### [0:04:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=270) |  are somewhat mid-term with regards to how

good they are, how strong they are. And if the alternative is to have one page that is much stronger, that could potentially rank better than any of those pages individually, then you're trading off having two pages shown in Search, but they're a little bit lower in the rankings versus one page that's showing a little bit more visibly in Search. So in that kind of a trade-off situation, often  

#### [0:05:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=300) |  you will prefer to rank a little

bit higher just because you're a little bit more visible in that case. There are many cases where, essentially, there would be no change in ranking, where maybe the top results are so strong that there is no chance for you to kind of jump in there by combining your pages. Or maybe you're already ranking number one and number two, or number one and number three. Then it's not that you would be ranking better than number one if you just had one page.  

#### [0:05:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=330) |  So from that point of view, it's

always something where I think it's a good idea to look at this, but also to keep in mind the context and to think about what the alternative would be. So don't just blindly see it as something that is bad and you need to fix, but rather think about what would the alternative be. Would it be better for my site if I had one page? Or does it not change anything at all, perhaps? SHAO CHIEH LO: I see. Thank you so much. JOHN MUELLER: Sure.  

#### [0:06:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=360) |  All right. Any other questions before we

jump on in with the rest? SHAO CHIEH LO: I have another question, if you don't mind. JOHN MUELLER: All right. Go for it. SHAO CHIEH LO: Is it a bad idea that we always use noncanonical URL in the internal link? So for example, especially if we implement internal link, it always have a parameter in that. And that parameter canonicalizes to the one result.  

#### [0:06:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=390) |  I see a lot of websites doing

this kind of link throughout the site. Will that hurt their page rank flow? JOHN MUELLER: It doesn't hurt the page rank flow or the page rank of the pages in that sense because we see those multiple URLs, and we see there's the same content, they have a rel=canonical, so we treat them as one page. What can happen, however, is that we pick one of these URLs  

#### [0:07:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=420) |  to use as a canonical instead of

the one that you have specified as the rel=canonical. Sometimes you'll see these URLs in Search if you do a site query or if you search for them specifically. Sometimes you'll see them in Search Console and in the reports. And it essentially just makes it a little bit harder for you to kind of keep track of things because you're looking, essentially, at both of these URLs and saying, well, in my mind I have to keep in mind  

#### [0:07:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=450) |  that these are the same URLs when,

actually, they're multiple URLs, where you could make it easier just by having one single URL. But that's essentially something where, from a ranking point of view, it wouldn't change anything. It's really just making it easier for you to understand your site. SHAO CHIEH LO: OK. Is any of that also make Google easier to identify which one is canonical if I link them directly? JOHN MUELLER: Yeah. When we pick a canonical, we use the rel=canonical.  

#### [0:08:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=480) |  We use internal and external links. We

use redirects, a bunch of other factors as well to pick a canonical. So if the rel=canonical points at one URL and the internal links point at another one, then we're kind of in a conflicted situation. SHAO CHIEH LO: I see. So also follow up on that, in Google Merchant Center they have a feed, right? Is that a bad idea to use canonicalized link in the Google Merchant Center's link? Or should we use the actual product page  

#### [0:08:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=510) |  that is canonical in the Google Merchant

Center's feed? JOHN MUELLER: I don't know for sure. I need to check out all of these details with the Merchant Center team because they've kind of opened things up and gone towards the direction of more organic search results, at least in the US. But I don't know what their recommendations are in detail,  

#### [0:09:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=540) |  so I need to double-check that everything

is the same. SHAO CHIEH LO: I see. So if I have a question specifically for Google Merchant Center, what is a canonical resource that I can go to? Is that a person or a group that I can get authoritative answer for it? JOHN MUELLER: I don't know. I don't know at the moment. I'd need to look that up. It might be, as a first step, that maybe the Google Ads team would be good to guess because that's kind of where the Merchant Center, so far, has  

#### [0:09:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=570) |  been located. SHAO CHIEH LO: OK. Thank

you so much. JOHN MUELLER: Sure. MIHAI APERGHIS: John, can I follow up a bit on that last question regarding internal links and canonicals? JOHN MUELLER: Sure. MIHAI APERGHIS: So let's say that you have this internal linking where all links point to those pages that also canonicalize to all the pages, but you figure out canonicals and respect them, and everything is OK from that point of view.  

#### [0:10:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=600) |  Do they still use crawl budget? Fixing

that and putting the actual canonical version would help with the crawl budget or that doesn't make any difference? You still need to crawl those noncanonical version every now and then because they're within the internal linking architecture? Or do you kind of figure out, oh, I know what this is about. I won't really bother crawling that page.  

#### [0:10:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=630) |  JOHN MUELLER: We do still look at

them from time to time, but it's not as often as we would crawl normal URLs. So usually what happens when we have a set of URLs and we pick one URL as canonical for that set, then we will mostly focus on that single URL and crawl that one primarily. We'll still occasionally look at the other ones. But it's not nearly as much as the normal crawling would.  

#### [0:11:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=660) |  So when it comes to crawl budget,

it's something where initially we would look at all of those different URLs. So if you went to a big site, and you started adding session parameters again to all URLs, then initially we would get lost with crawling. But fairly quickly we would figure out, OK, these are the canonical URLs. These are noncanonical URLs. We will focus on the canonical ones. And that should more or less still work out. MIHAI APERGHIS: But do internal links play any role here?  

#### [0:11:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=690) |  So if you have internal links or

not to those noncanonical URLs, does that affect how often you'll re-crawl, even if rarely, those versions? JOHN MUELLER: [INAUDIBLE] I will describe the differences between canonical URLs [INAUDIBLE] will focus on the canonical URLs.  

#### [0:12:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=720) |  If it's kind of like 50/50, like

we choose these or we choose those, it's possible that we will likely crawl those noncanonical URLs a little bit more often than URLs that we think are completely irrelevant. MIHAI APERGHIS: OK. So is that the case with redirects as well? So if you're internally linking to a page that always redirects to something else, does the internal link-- should you replace that with a final version? Or you'll kind of manage it on your own end?  

#### [0:12:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=750) |  It doesn't matter if you're internally linked

to the redirect page or to the final destination. JOHN MUELLER: I imagine you would see something similar. I think in practice this difference is more theoretical than it is practical. If you have access to the server logs of a bigger site, you can probably find pages like that, where you know you're linking to a redirecting page. And you can double-check to see what the amount of crawling  

#### [0:13:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=780) |  actually is there. I imagine, for the

most part, we just figure this out, and we pick the canonical and we focus the crawling really primarily on that. I don't have any numbers to throw out. But I wouldn't be surprised if it's-- I don't know-- 30-to-1 or some really strong ratio like that, where we'd say we really focus on the canonical URLs. And every now and then we'll still look at the noncanonical ones, regardless  

#### [0:13:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=810) |  of where they came from. MIHAI APERGHIS:

OK. I'm just asking whether if you have a very big site and it's linking to all of these pages that either redirect or canonicalize to something else, whether it's worth the effort going URL-by-URL or maybe some automatic way to try to replace everything so it leads directly to the final version, whether that's worth the effort. JOHN MUELLER: I think if you have a really large site and you're doing this on a large scale, I would clean that out.  

#### [0:14:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=840) |  Let's say-- I don't know-- if YouTube

had redirects from all of the old pages to new ones, and the internal links still went to the old pages, that's something I would say is worth cleaning up because there are just so many of those URLs, and if we keep running into the old ones and keep trying them, then it's just adding such a mass of unnecessary crawling. But if you have a normal-sized website, even kind of like a mid-sized e-commerce site with--  

![](https://i.ytimg.com/vi/MlLVBz9xntk/maxres1.jpg)



#### [0:14:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=870) |  I don't know-- a couple million URLs,

I don't see this playing a practical role. MIHAI APERGHIS: OK, thanks. JOHN MUELLER: Sure. All right. Let me look at some of the questions that were submitted. And feel free to jump in in between as well. Or, if you have more questions or comments on the questions or answer, we can take a look at that. I heard Googlebot sometimes submits forms. If so, could it do it if the form is in an iFrame as well?  

#### [0:15:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=900) |  And what if the iFrame is hosted

on another domain? How would that impact crawling, indexing, and so on? It's extremely rare that Googlebot would submit a form. We primarily did this way in the beginning when websites were structured in a way that we could not crawl them properly. In particular, we saw this issue on a lot of government websites, where there was a lot of content on the site  

#### [0:15:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=930) |  but to find it you had to

go to a search form to actually find links to that content. And for sites like that, pretty much the only way to get to the detailed content was to go through the search form. However, for pretty much every modern site, we can crawl normally. And people are used to creating a structure where we can crawl with categories and subcategories where essentially we never need to go through any of the forms. So I would imagine most of the people who  

#### [0:16:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=960) |  have sites who have logs that they

can look at, if you look at the server logs and you look at Googlebot you would probably never see Googlebot submitting any of the forms that you have on the site. So that's something that's really extremely, extremely rare and something usually where, whenever it does happen with a website, it's kind of a sign that we can't crawl normally, where we realize there's a lot of content but we can't actually find that content at all.  

#### [0:16:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=990) |  So that's something where, if you're seeing

this happening, I would kind of go down the direction of what am I doing wrong, what could I be doing differently with regards to my site's navigational structure. That's, I think, the primary aspect there. And with that in mind, adding more complexity like iFrames or other domains, I suspect a lot of that would just not happen, just  

#### [0:17:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1020) |  for practical reasons. Because we want to

avoid running into a situation where we accidentally enter things like credit card numbers and accidentally Googlebot goes off and buys things, or fills out some contact forms with random information. All of that doesn't really make sense, and it causes almost more problems than it helps anyone. So that's something where I imagine if you have a configuration with iFrames and other domains, you would probably never see Googlebot go through that.  

#### [0:17:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1050) |  The one thing where sometimes you'll see

something like this happening is if you have an AJAX-based website or JavaScript-based website in general, where you're using some kind of a POST request to get data to load on a page. Then that's something where Googlebot might be executing that. So if that's a part of your pages rendering, that it does a post request to an API and then it gets some answers and displays those answers, then that's something where, when we render the page,  

#### [0:18:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1080) |  we might be doing that. It's not

that Googlebot is crawling those POST requests for the form data, but just that in the process of rendering your page, if there's a POST request, we'll try to do what a normal browser would do, and we might show that. And in a case like that, we follow, I imagine, the normal browser or security guidelines. So doing things like cross-domain I believe is just a lot harder.  

#### [0:18:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1110) |  I don't know offhand what the defaults

are there with modern browsers, but that's something where you're adding more complexity again. We had two goals in our mind. The first is showing ratings as rich results for our seller pages when someone searches for a seller name plus reviews and ratings. And the second is showing a search box when someone searches for our brand.  

#### [0:19:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1140) |  In February, for case one, we implemented

organization schema on our seller page, added organization attributes like brand name, URL, logo, address, reviews, ratings. For case two, we implemented sitelinks search box schema on our homepage. The result one, in Search Console Enhancement reports we started seeing logo section, where we have around 250 valid items. But in performance, we haven't gotten any rich results for seller pages yet.  

#### [0:19:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1170) |  In the search console section we started

seeing one valid item, but we're not seeing any search box when we type our brand name in Google Search. My boss is upset with me now. My thoughts for the next step for the seller pages are remove all organization schema and implement ratings only. One of our competitors is doing the same. Is there any hidden mistake that I should take care of? Our main focus is this search box. For reviews, you definitely need to watch out for the guidelines  

#### [0:20:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1200) |  that we have with regards to review

markup in our developer documentation. In particular, reviews are only available for a certain set of items that you mark up on a page. So it's not the case that you can take anything and just add reviews and Google will show those reviews in Search. But rather, we only show them for a certain set of structured data elements. So I'd double-check to make sure that you're  

#### [0:20:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1230) |  following the guidelines there and that the

information that you are marking up matches the policies that we have for reviews. That's probably the most important part. With regards to the sitelink search box, this is kind of a tricky one and something I see people struggle with from time to time. The hard part here is that adding the markup does not make it more likely that a sitelink search  

#### [0:21:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1260) |  box will be shown. But rather, if

we were to show one, we would use one that's based on your markup. So it's very rare. Or I don't know. It feels very rare that we would show a sitelink search box in general for queries for sites. And only for those cases where we would show it, if you have the markup, we'll try to use the markup. If you don't have it, we'll just use a default setup. So that's something where, if you're currently not seeing  

#### [0:21:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1290) |  a sitelink search box at all, then

adding the markup for that will have no effect. A question on the FAQ schema. I've seen in documentation what qualifies as an FAQ and what not. But for my website, the FAQ was showing for some pages. Now it has disappeared. But in Search Console I can still see unapplicable to the FAQ schema. It's really hard to say what exactly was happening here.  

#### [0:22:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1320) |  On the one hand, the policies are

definitely important, so I'd watch out to make sure that you're following the policies. On the other hand, with structured data in general, just because you have marked something up does not guarantee that it's shown in search. There are various things that come into play here. On the one hand, it has to be valid markup. It has to follow our policies. It has to be a site that's kind of a reasonably high quality  

#### [0:22:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1350) |  so that we can kind of trust

it. And all of these things have to align. And it's possible [INAUDIBLE] and things like some of the other, more visible, types of markup. It doesn't make sense for us to [INAUDIBLE] this for every URL that's shown in the search results because otherwise everything just will look really messy. So that's something where also kind of worth looking at the queries that you're actually  

#### [0:23:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1380) |  targeting and seeing what the results look

like there. So that's kind of the direction I would go here. Question about maintaining multiple TLDs that all contain the same English content. If a company has a dot-com and they expanded to multiple TLDs 10-plus years ago using the same content written in English, and the content is generic, does it  

#### [0:23:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1410) |  make sense to remove the ccTLDs and

fold them together with dot-com via a site migration? Maybe redirect them back to dot-com? Again, the English content definitely applies to all of those countries, and Google is already choosing the dot-com as canonical for many of those URLs. Some of the ccTLDs do rank in their country now based on hreflang magic where Google is choosing a dot-com as canonical and displays the ccTLD  

#### [0:24:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1440) |  in the search results. Maintaining those additional

ccTLDs is tough for the company, and it doesn't make sense to keep a complete duplicate of the dot-com sitting on multiple TLDs. It sounds like you've already figured out that the ccTLDs aren't as critical for that particular case. So that's something where maybe it does make sense to fold things together and to kind of pick one version as the canonical version.  

#### [0:24:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1470) |  In general, I would use country code

versions, or just generally local versions, when you really have something unique that you want to do on a per country basis. So if there may be policy reasons or legal reasons why you need to have individual country versions, or if you have different content depending on the country versions, have separate URLs.  

#### [0:25:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1500) |  But if, essentially, it's all the same

content, and you just have the different country versions for historical reasons, then it probably makes sense to fold all of those together into one version so that you have one clear, one strong version. Makes it easier for tracking as well. Makes it a lot easier for maintenance, definitely. So that's something where I think you've already kind of analyzed that, like all of this is duplication that you don't necessarily need.  

#### [0:25:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1530) |  So I would tend to fold those

together. BARUCH LABUNSKI: Can I ask a follow-up to that? JOHN MUELLER: Sure. BARUCH LABUNSKI: If a current brand doesn't want to expand globally and just stay locally, and sitting on a dot-com for 15 years now, is it worth it to go ahead and redirect the dot-com to the dot-ca from a TLD purpose?  

#### [0:26:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1560) |  I know you guys count that as

an immediate geo-targeting. There's no need to do that in Search Console, right? So is it worth it to go ahead if they don't want to expand? JOHN MUELLER: I think that's fine, too. Yeah. So a dot-ca can be active globally as well. It's not that it's suppressed in other countries. So from that point of view, if you just want to have one version, and the dot-ca is your primary version, then that's perfectly fine.  

#### [0:26:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1590) |  Yeah. BARUCH LABUNSKI: But the ranking will

tank for a little bit and then come back? JOHN MUELLER: I think if you're folding things together, then I wouldn't worry so much about the ranking because you're kind of taking one existing site and you're just adding to that. It's not that you're taking two sites and changing them. But you're kind of building up on one existing site. So probably from a ranking point of view,  

#### [0:27:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1620) |  that should be fairly stable. BARUCH LABUNSKI:

OK. Thanks. SHAO CHIEH LO: I have another follow-up question on that. I have a question about x-default in a multi-lingual site. For example, there is a lot of website they actually redirect their root domain to en US version. But they put x-default to the root domain. So they're basically putting x-default to a page,  

#### [0:27:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1650) |  pointing to a page that being redirect.

So is that makes sense? That page is not 200. And I think a lot of time, the root domain actually have more backlink than the en US URL. So in this case, is that actually a good idea to just put a root domain as the en US alternative instead of redirect then to en US and put en US as en US alternative?  

#### [0:28:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1680) |  JOHN MUELLER: I think in a case

like that, where you have a root URL that's redirecting depending on the country version or the country of the user, that's something where we've said in the past that using the x-default is fine. Essentially, what you're saying with the x-default there is that on the root URL, you have your own logic for handling users of different countries. And if you tell us these are the known country versions,  

#### [0:28:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1710) |  then we will send people there when

we recognize they're from there. But if people from other countries come to your website, you're telling us please send them to my root URL, and I will decide where they should go. And from our point of view that's perfectly valid decision for you to make. SHAO CHIEH LO: So from what I hear is that if they're using browser detection, then it's OK to put x-default to a root domain that being redirect.  

![](https://i.ytimg.com/vi/MlLVBz9xntk/maxres2.jpg)



#### [0:29:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1740) |  JOHN MUELLER: Yeah. Definitely. The only thing

I would watch out for is the individual language and country versions, don't do the browser detection there. So on the root, through the browser detection, but if you send them to the en US version, then keep them on the en US version even if their browser happens to be in French. Don't do-- SHAO CHIEH LO: I'm sorry. Another follow-up question that I heard that it's actually not a good idea to do browser detection from Google's  

#### [0:29:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1770) |  guidelines. So should we prevent just not

doing it on root domain also? For example, root domain is just the content of English, right? So should we just redirect the root domain to en US no matter what? Or maybe just put root domain as en US instead of redirecting. If we want [INAUDIBLE] anymore.  

#### [0:30:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1800) |  JOHN MUELLER: I think that's up to

you. From our point of view, if you have one page where you're doing this kind of browser or country detection, that's fine, as long as we can really access the other version. So that's kind of the tricky part, where sometimes we've seen people on the en US version, they also check for browser and location and then they redirect, which sometimes results in Googlebot finding, for example, the French version. And Googlebot crawls from the US, so it gets redirected to the English version.  

#### [0:30:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1830) |  And then we would never be able

to index the French version. But if you only do this kind of detection on the root URL, where there's actually no content, then that's not a problem for us. SHAO CHIEH LO: I see. So in this case, we detect in a browser when people go to the root domain. And root domain has a very high backlink. But it redirect different places according to their browser or IP location.  

#### [0:31:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1860) |  How would the PageRank work in this

case then? JOHN MUELLER: So it's tricky. Usually what would happen is we would see the redirect from the root URL to the English version. And that would be the one that we would use for PageRank calculation. But with hreflang, we can swap out the different URL. So it's something where usually that just works out. It's not that you have to do anything special  

#### [0:31:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1890) |  with regards to PageRank in a case

like that. SHAO CHIEH LO: OK. Thank you so much. JOHN MUELLER: Sure. VAHAN: Hi, Mr. Mueller. JOHN MUELLER: Hi. VAHAN: I am Vahan from search engine German. We were experimenting with Google News app and build the sections of our website by submitting either an RSS or web  

#### [0:32:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1920) |  location. So on certain categories, we don't

have an AMP, and we have to submit their web location. But when I open a Google News app on the phone, open the section on the app, I have found that articles are not sorted by the freshness. They are sorted by kind of like relevancy. And the first article I see, I see articles from March.  

#### [0:32:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1950) |  And the most fresh articles in that

case are pushed like the bottom. But sometimes I see fresh ones first. So is this something that was done intentionally? Or is it kind of bug? JOHN MUELLER: I have no idea. I don't know how the Google News app deals with those kind of things. Intuitively, I think it's something-- I mean, I only see this in Discover, when I look at Discover.  

#### [0:33:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=1980) |  But in there, I feel that's something

where we try to understand what the relevance is. And sometimes it's just not the newest stuff is the most relevant. But I have no idea how that's handled on the Google News side. So that's something where it's probably worth checking with the Google News team. I believe in the News Publisher Help Center, there is a contact form that you can use, where you should be able to reach out to someone  

#### [0:33:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2010) |  from the Google News team. And maybe

they can help you with this. I mean, it's a bit of a tricky question because it's almost like a ranking question. But especially if you find something that looks to you more like a bug rather than a misunderstanding, then that's something I would let them know. VAHAN: Thank you. Thank you, Mr. Mueller. CHRIS ANDREWS: I've seen that as well, and have given the News team feedback about that. It used to also be on desktop.  

#### [0:34:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2040) |  You only had articles on Google News

from the last 30 days, and now sometimes they'll be months old. It's old news sometimes on Google News. [LAUGHS] VAHAN: When we did use a feed as a section source, it does pull order correctly by the freshness. But when we did switch to a web location, and I want to add a tweet that we have a least item schema implemented in our category pages,  

#### [0:34:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2070) |  so it stays the order of the

articles by that schema as well, which can help Google understand the order. So web location kind of loads differently. CHRIS ANDREWS: Yeah, on the Publisher Center, the web crawl, the web location does not seem to work as reliably as crawling it from a feed. VAHAN: Yeah. CHRIS ANDREWS: If you have generating the articles by the feed it's much more reliable.  

#### [0:35:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2100) |  VAHAN: Yes. But the problem there is

if we generate [INAUDIBLE] articles from feed, it is going to add inside the News app. But we want traffic to come to our website. CHRIS ANDREWS: And for that, you have to have the AMP. VAHAN: Yeah. We have AMP, but on certain categories, we don't have AMP. So that is a problem. JOHN MUELLER: Oh, man, Chris. I think we need to do a special session just with you. [INTERPOSING VOICES] CHRIS ANDREWS: Sorry. Didn't mean to hijack your forum here.  

#### [0:35:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2130) |  JOHN MUELLER: No, no. This is perfect.

It's always like people coming in with these kind of News Publisher questions and I was like, I have no idea. And you're one of the people that has the most experience in this, so cool to have you here. What's the status of Google's decision on the mobile-first indexing after September? Any delay due to COVID-19? So far, we're still seeing lots of sites  

#### [0:36:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2160) |  shifting over and getting ready for mobile-first

indexing. So we haven't completely made up our mind that we will stick with this date. But we want to give it a little bit more time to settle down and see how it all works out. My guess is within the next month or so we'll make that call and go one way or the other. It's also really useful to have feedback from any of you who are running into issues around this where you're seeing that your development team just  

#### [0:36:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2190) |  isn't available to make these kind of

changes, or anything around that. The more feedback we have, the easier it is to just make a decision on this. Because otherwise we just see sites are being improved, and we think, oh, well, people are still doing the good work kind of getting things ready, so maybe we don't need to change the date. But send us feedback. Question about cloaking.  

#### [0:37:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2220) |  The case that we have with a

site with millions of URLs is growing, and we want to manage crawl budget efficiently. Oh, I think this is the parameter question that we looked at in the beginning. AGARWAL AKHIL: Yes, John. That's right. JOHN MUELLER: OK. Is there anything more that you have that we should cover in that regard? AGARWAL AKHIL: Yes. Just to make a statement and say that technically  

#### [0:37:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2250) |  we call this cloaking, in terms of

statements. Right? JOHN MUELLER: I think it's tricky with just that name, because there's so many different ways that a website can be dynamic and kind of subtly be different. For us, what is really problematic when it comes to cloaking is when the content  

#### [0:38:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2280) |  is significantly different. So when, for example,

you have a web page about cars and when Googlebot crawls it it's a web page about pharmaceuticals, then that's really hard for us. And that's something where the WebSpam team might get involved. On the other hand, if you're just adding parameters to individual URLs, that's something where we tend not to worry too much about that. AGARWAL AKHIL: But generally, you would probably advise to not do it, and have a better way of solving it.  

#### [0:38:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2310) |  JOHN MUELLER: Yeah. That's generally what we

advise anyway, just because it makes all of the maintenance and debugging so much easier. So it is very common that we run across situations where maybe someone from the Indexing team will contact us and say, please contact this website and tell them to stop cloaking. And then they give us details which basically say they're showing Googlebot something broken, and they're showing users something that works. And they're shooting themselves in the foot.  

#### [0:39:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2340) |  And they don't realize it because when

they look at the website themselves, it looks fine. But when Googlebot looks at it, it looks broken. AGARWAL AKHIL: Got it. Thanks. JOHN MUELLER: So that's something where it's very easy to break things in subtle ways. So if you can stick to one version, it just makes it so much easier. AGARWAL AKHIL: Got it. Thank you so much, John. NANDHINI BABU: Hey, John. I have a question that's related to the unknown traffic that we're receiving. I don't know if it's coming from a spambot.  

#### [0:39:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2370) |  But while checking on Analytics, the traffic

is coming from California. We are based out of India. And also, I've checked the source. It's coming from Facebook, and the average session duration is less than 0.2 seconds. Even I checked the IP log data. But I'm not able to arrive at any solution. So is there any way that I've missed? Or can you just suggest me a solution? JOHN MUELLER: I don't know. The IP address comes from Facebook? Or the referrer comes from Facebook?  

#### [0:40:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2400) |  What are you seeing? NANDHINI BABU: The

IP log data that I've taken from our website. We have not checked anything from Facebook's side. JOHN MUELLER: OK. I don't know. So in general, if you're seeing something like this where it's not coming from Google crawling, and maybe it looks like bot traffic or it looks like traffic that is irrelevant for your website in general, then from our point of view,  

#### [0:40:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2430) |  just purely from a search side, you're

welcome to block that traffic. Because at least from our point of view, if we feel that normal users when we send them to your website, they're seeing a normal experience, and if you're blocking traffic that you don't want to have access your website, that's essentially up to you, between you and those users that you're blocking. And if you feel that these requests are not actually made  

#### [0:41:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2460) |  from users at all, and they don't

provide you any value for your website, then maybe that's something that you could just block. NANDHINI BABU: Is there any way that I can just block them because I'm not able to get the IP location. So how is that I block them? JOHN MUELLER: That depends on your server and on the setup that you have. BARUCH LABUNSKI: Yeah, check the server logs. JOHN MUELLER: Sometimes you can check the server logs.  

#### [0:41:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2490) |  Sometimes that's something where you can just

block an IP range directly on the server and say don't respond to these IP addresses. It might also be the case that your website is set up in a way that you don't easily have access to that information. You can't easily block things. And sometimes a workaround might be to use something like a content delivery network in between which does give you a little bit more functionality in that regard.  

#### [0:42:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2520) |  So that's something where you need to

kind of check it out with the technical people working on your website and work with them to find ways to block that kind of traffic. OK. ANGIE B: Hi, John. JOHN MUELLER: Hi. ANGIE B: Hi. I have two questions for you today. The first is actually about AJAX calls, so I was happy to see that Martin is here.  

#### [0:42:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2550) |  Hi. Not actually a dev, so I

might get some of the details a little muddled. But we have an infinite scroll implementation that uses an AJAX call to fetch the-- it's for a category page of articles, so the AJAX calls to fetch more articles. And the variable for the AJAX call is like a URL, I guess, that doesn't exist. It's not a page. It just responds with a JSON response.  

#### [0:43:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2580) |  And those URLs are being indexed by

Google. So they were appearing in Search Console. Initially we had a bug where when there was no data-- so for category pages that didn't have enough content, let's say-- they were producing a 500 error instead of the JSON response. So that's when we noticed that these were being picked up by Google. So the 500 errors are fixed now, but the URLs  

![](https://i.ytimg.com/vi/MlLVBz9xntk/maxres3.jpg)



#### [0:43:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2610) |  are still being indexed. I don't know

what the best way to handle these URLs are, or if we should even do anything to them. Would it be best to just let them be indexed? Because I'm not sure how that affects the rendering of the page. If we let them be indexed, is it the case that then Google can see additional articles that are being loaded with the call? Is it the case that we should try  

#### [0:44:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2640) |  to prevent those URLs from being indexed

and crawled at all for the sake of crawl budget or whatever? I'm just not really sure what the best way to handle it is. JOHN MUELLER: OK. So I think there are probably those two aspects that are important there. On the one hand, the rendering, which is something where I would not block them in a way that they would block rendering, just so that you really have  

#### [0:44:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2670) |  your pages rendered completely. So as much

as possible we can get to all of your content. So don't block those JSON requests with something like a robots.txt because that would prevent us from actually loading the content. That's the one thing. The other thing is with regards to indexing. One way that you could block those from being indexed is to use an X-Robots-Tag HTTP header, which is something that you specify in the response  

#### [0:45:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2700) |  on the server side where you say

this file-- here's the content, but please don't index it. That's something that you could do. From a technical-- ANGIE B: Sorry. If we go that route, will it not noindex the main page? JOHN MUELLER: No. ANGIE B: No. OK. Some people were talking about [INAUDIBLE].. I was a little unclear about that. Someone said they did that with a robots noindex in the X-Robots header, and it prevented the parent page  

#### [0:45:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2730) |  from being indexed. JOHN MUELLER: No. That

shouldn't be happening. If you see something like that happening, that would be a bug. And that would be something that we'd want to fix. So that definitely shouldn't be happening. The other thing that I think is also worth mentioning here is that probably it doesn't matter if these pages are indexed because, most likely, the content in those JSON files will be content that you have in the rendered version of your page already.  

#### [0:46:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2760) |  And the rendered version of your page

is a normal HTML page. And we can understand that page really well. So if someone searches for words in that content, we will show your HTML page. We won't show the JSON file. So technically it'll be indexed. And theoretically you could do a query and make that appear in search. But for all practical purposes, it doesn't matter at all. So it's something where I'd say you can use the X-Robots tag to block it from being indexed, but it's not critical.  

#### [0:46:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2790) |  It's a nice way to clean things

up, but it's not going to make or break anything for your website. MARTIN SPLITT: And also, in crawl budget, it doesn't make a difference on crawl budget because we have to make the request anyway. So if we do it indexing it and then put it in the cache, and then when you do the AJAX call we use it from the cache, it doesn't make a difference. If you would noindex it, we would still have to crawl it when you make the AJAX requests. So that's why you should not put it in robots.txt.  

#### [0:47:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2820) |  Because if you put it in robots.txt

and disallow us from crawling, then we can't fetch that content anymore and then we're not seeing the content in the JSON file. So, yeah. As long as it's not ranking on anything that you care for, it doesn't make a difference. ANGIE B: OK. KAMLESH KUMAR: I haven't been on the crawler, but [INAUDIBLE] so can I? JOHN MUELLER: Sure. KAMLESH KUMAR: We have the News Publisher. And we are filing 350 stories every day.  

#### [0:47:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2850) |  Every day 350 story. And suddenly some

big news came, and we filed 500 to 1,000-page stories on that day. After the 350 [INAUDIBLE] story, that will crawlable on same day or not? What is the best practice for that? JOHN MUELLER: Probably it doesn't matter. KAMLESH KUMAR: Don't matter. JOHN MUELLER: Yeah. If you look at your server logs--  

#### [0:48:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2880) |  I don't know your website. But I'm

guessing you see that we do multiple thousands of requests every day from your website. So if you have 300 articles, you have 500 articles, that difference is so small compared to those several thousands of pages that we request every day. So from that point of view, I don't think that would make a big difference. I think it would be different if you went from 300 articles on one day  

#### [0:48:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2910) |  to 30,000 articles on the next day.

That's something where it's like, OK, that's a significant difference, and then we might have trouble keeping up. But just from a practical point of view, I think that would be hard. KAMLESH KUMAR: OK. I have one more question. We have the News Publisher, and we have the brand name. So if we do a search our brand name in Search, then suddenly we see our website.  

#### [0:49:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2940) |  Then website news article appearing on top

of our brand in Google. Plus, if I search my brand name, the news article up third website, which is also publisher. We both have the publisher. So the third-party URL and then our brand name. And we are bigger than that website.  

#### [0:49:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=2970) |  It's very difficult to how we can

handle this because we are the bigger brand. Then we have to double them which publisher ranked better than us. JOHN MUELLER: OK, so-- KAMLESH KUMAR: I tweeted this to you and you responded. And I'm not feeling-- I repeat question over there. So this is the best platform to ask you and your help.  

#### [0:50:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=3000) |  JOHN MUELLER: I think it would be

useful to have some screenshots of what exactly you're seeing because-- KAMLESH KUMAR: I have. JOHN MUELLER: --it's hard for me to understand. But it's also something where what we would not do is make any kind of manual adjustments for those kind of cases. So it's very possible that, in some situations, if you search for maybe a company name that a news article about that company will rank above it.  

#### [0:50:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=3030) |  It's certainly possible. I think seeing that

regularly, or always, with different news articles about a company, that would be kind of awkward, especially if it's a reasonable company. KAMLESH KUMAR: [INAUDIBLE]. JOHN MUELLER: But seeing it once or twice, I think that would be kind of expected. KAMLESH KUMAR: This started after the COVID-19 coverage. JOHN MUELLER: OK. KAMLESH KUMAR: It's applicable for only COVID-19 live blog.  

#### [0:51:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=3060) |  That publisher published live blog on COVID,

and that live blog appeared ever than us, even on brand name. Only we are using brand name, our brand name in higher articles above then us. JOHN MUELLER: OK. That sounds like something where it would be useful to get some examples. If you can post maybe some details in the chat or if you can send them to me on Twitter, then I'd love to take a look at that and pass that on. KAMLESH KUMAR: I will.  

#### [0:51:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=3090) |  Cool. Thank you. JOHN MUELLER: Sure. MICHAEL

LEWITTES: John, can I ask you a quick question? JOHN MUELLER: Sure. MICHAEL LEWITTES: What's the difference between noreferrer and nofollow? Because I see that sometimes when I look at different coding of things. And is there one that's preferable in certain circumstances? JOHN MUELLER: They do different things. The nofollow is essentially something that we use, or search engines use, to not pass signals from one URL to the next one with a link. And the noreferrer is something that browsers  

#### [0:52:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=3120) |  use to block the referrer from being

shown on the other page. So usually if you click on a link that goes to a different website, it would say this user came from that referring website. And the noreferrer attribute basically just says, don't say anything about where you came from. And usually that makes sense for cases where maybe the URL itself is something that is perhaps private data.  

#### [0:52:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=3150) |  Like, for example, you could imagine a

social network where the URLs have a long ID. And if you go to that ID directly you can see the content, even if it's not for you directly. So you might want to have cases like that where if someone clicks on a link, not include that URL itself. Some people choose to do that. I think some CMS's have some defaults as well with regards  

#### [0:53:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=3180) |  to how they mark up the different

links. I don't know if noreferrer is one of those things that people just use. There's also noopener, which is another attribute that a lot of CMS's use. I forgot what that one does. I don't know if it prevents it from opening in a new tab or something weird like that. I don't know. MICHAEL LEWITTES: OK. Thank you. JOHN MUELLER: Sure. SHAO CHIEH LO: Hey, I have another question.  

#### [0:53:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=3210) |  This is just a question about faceted

navigation. So this big website, what I did is I blocked all the faceted navigation in robots.txt. But recently I read in the Webmaster blog, they say that it's actually not necessarily the best practice because some [INAUDIBLE] higher level of faceted navigation might be useful to be indexed. And also that don't consolidate the authority of those pages.  

#### [0:54:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=3240) |  So if I want to change the

robots.txt row right now, there will be a bunch of URLs suddenly being crawlable. How hard it will be to hurt my crawl budget? And should I care about crawl budget since Google are so powerful nowadays? And also, should I only let higher-level parameter to be crawled, or should I just open all of them to be crawled and then canonicalize them?  

#### [0:54:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=3270) |  JOHN MUELLER: I think with crawl budget

in general, most sites don't need to worry about this. It's something where I would say, just to give an order of magnitude, if it's less than tens of millions of pages, probably you don't need to worry about crawl budget. If it's more than that, then it's really something where if you're suddenly duplicating or triplicating all of the URLs on your website, then that makes it a lot harder for us to crawl things.  

#### [0:55:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=3300) |  But if it's a couple 100,000 pages,

and suddenly they're twice as many, then we can usually just deal with that. With regards to faceted navigation, if you were to unblock that in robots.txt, I think you would see a rise in the amount of crawling that we would do, at least temporarily, until we figured out how these parameters actually work. And that's something where, depending on the site, you might see that affecting the rest of the crawling  

#### [0:55:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=3330) |  as well for a period of time,

I'd say-- I don't know-- maybe a couple of weeks, something around that time. That's where I'd say if you want to make that kind of a significant change, then maybe pick a time where crawling from search is not as critical for your website. So if you have maybe a season where there is less traffic from search, where you have fewer new products, fewer new articles, then that would be a good time to change that around.  

#### [0:56:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=3360) |  Whereas if everything is under fire and

your website is already running at its limits, then that's probably a bad time to make significant changes like that. SHAO CHIEH LO: So would you say that a better way to deal with faceted navigation is not block them by a robots.txt, it's canonicalize? JOHN MUELLER: Yeah. To canonicalize or use noindex, that's essentially what we would recommend. SHAO CHIEH LO: OK. Thank you so much. JOHN MUELLER: Sure. All right. I need to jump off to another meeting.  

#### [0:56:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=3390) |  It's been great having you all here.

Thank you all for joining in. It's so cool to have so many people in. KAMLESH KUMAR: John, one more question please. JOHN MUELLER: One really quick one. One really quick one. KAMLESH KUMAR: We have a news website called [INAUDIBLE].. And we have that website appearing in Google as a top result. But since three to four months, the website is not appearing in Google top results on any of the keywords.  

#### [0:57:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=3420) |  So just want to know what we

have to do for that, and what is the next process. I didn't get any information regarding how to embed in Top Stories browser. So please help. JOHN MUELLER: I don't have any kind of magic tricks for Top Stories. That's something where it's an organic feature, and we use normal ranking algorithms in there. So what I would recommend doing in a case  

#### [0:57:30](https://www.youtube.com/watch?v=MlLVBz9xntk&t=3450) |  like this is going to the Webmaster

Help Forum and getting as much input from other people as possible, and thinking about what makes sense, what doesn't make sense for your particular case. KAMLESH KUMAR: OK. JOHN MUELLER: It's not that I have [INAUDIBLE] something I can do. KAMLESH KUMAR: Thank you so much. JOHN MUELLER: All right. All right. Cool. I really need to jump off.  

#### [0:58:00](https://www.youtube.com/watch?v=MlLVBz9xntk&t=3480) |  Thank you all for sticking around. I

have the next ones lined up for Friday, and Thursday if you speak German. So we can stay in touch then. CHRIS ANDREWS: Thank you. JOHN MUELLER: Stay safe. AGARWAL AKHIL: Thank you, John. ANGIE B: Thank you, John.  