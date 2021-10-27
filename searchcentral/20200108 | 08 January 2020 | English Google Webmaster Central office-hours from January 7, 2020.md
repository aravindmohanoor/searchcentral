[![English Google Webmaster Central office-hours from January 7, 2020](https://i.ytimg.com/vi/vXwWuFCLTnc/maxresdefault.jpg)](https://www.youtube.com/watch?v=vXwWuFCLTnc)

## English Google Webmaster Central office-hours from January 7, 2020

This is a recording of the Google Webmaster Central office-hours hangout from January 7, 2020. These sessions are open to anything webmaster related like crawling, indexing, mobile sites, internationalization, duplicate content, Sitemaps, Search Console, pagination, duplicate content, multi-lingual/multi-regional sites, etc. 



Watch out for new sessions, and add your questions at https://www.youtube.com/user/GoogleWebmasterHelp/community



Feel free to join us - we welcome webmasters of all levels!



Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=0) |  JOHN MUELLER: All right, welcome everyone to

today's webmaster central office hours. My name is John Mueller. I'm a webmaster trends analyst here at Google in Switzerland. And part of what we do are this office hour Hangouts where people can jump in and ask any question around their website and web search and we can try to find answers for them. Thank you for joining the first one of this year. I hope you have a fantastic year, that the year works out  

#### [0:00:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=30) |  well for you. Lots of exciting things

coming up. And that you're successful at whatever you're working on. But I guess we can get started with questions from you all to keep things going. So if anything on any of your site is burning and you really are you need to find an answer, feel free to jump on in now. Afterwards, I'll go through some of the questions that were submitted.  

#### [0:01:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=60) |  MIHAI APERGHIS: I'll take a crack at

it. JOHN MUELLER: OK. MIHAI APERGHIS: Well, it's not burning, really, but since Barry mentioned the URL parameters, I'm still curious over-- what exactly does that represent URL option means since it's not really documented in the official docs.  

#### [0:01:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=90) |  JOHN MUELLER: I looked this up last

year when you asked and I forgot. So I don't know. I need to double check. My understanding is we just pick one URL as a representative for that set and index it like that. But I don't know what exactly came out of looking things up.  

#### [0:02:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=120) |  MIHAI APERGHIS: So do you mean like

a session-- so for example, a session ID parameter? Should the representative URL be chosen for programs like that? JOHN MUELLER: I would assume, for a session ID, we would drop that parameter completely because usually,  

#### [0:02:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=150) |  accessing the URL without a session ID

is a part of the query string, shows us the same content. And it's a cleaner URL, so we would probably just drop that completely. MIHAI APERGHIS: Right. But if you'd like to set it up in the parameters to help, is that the option you would choose? The representative URL option? Or just let Google put [INAUDIBLE]?? If you had to use the tool. JOHN MUELLER: I don't know. I don't know. I haven't looked at it this year, so your guess is as good as mine.  

#### [0:03:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=180) |  BARRY SCHWARTZ: That's funny. John, I have

a question. There's been like a lot of chatter about reconsideration requests after manual actions was taking longer than usual. Is that true? I mean, obviously, people are away for the holidays. JOHN MUELLER: I don't know about longer than usual, but sometimes they do take quite a bit of time to be reprocessed. BARRY SCHWARTZ: So there's no backlog  

#### [0:03:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=210) |  that your team is experiencing-- we have

to hire more people to get through these support requests? JOHN MUELLER: I mean, if it takes longer, then usually that's a sign of a backlog. But it's not it's not the case that we kind of artificially delay things. With regard to reconsideration requests, sometimes what just happens is that the team works on this in batches and they'll go through one set of reconsiderations  

#### [0:04:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=240) |  and then go through the next set,

and depending on how they patch things, it might be by country, or might be by kind of type of issue. Those kind of things. So that's something that sometimes happens, and sometimes you see that with regards to the backlog or kind of the time that it takes to process things, where suddenly a whole bunch of things will get reprocessed fairly quickly, and then it takes a while, again, for things to kind of catch up again. BARRY SCHWARTZ: Thank you.  

#### [0:04:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=270) |  JOHN MUELLER: All right. So let me

go through some of the questions that were submitted. And as always, you're welcome to jump in in between if there's anything that you'd like to add or more information that you need. Can you target English speakers in the US and UK using the same content but with relevant hreflang tags? For example, example.com/usenglishpage1  

#### [0:05:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=300) |  or GB English page 1. Content is

the same, not geo-targeted or anything? Yes, you can do that. I don't know if that's kind of the best use of your time and your website in general, but you can do that. If you want to create separate pages for individual countries and they're all the same language and you have a hreflang set up, then you can set it up like this. But what will probably happen, in practice, is we will recognize that these pages are the same.  

#### [0:05:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=330) |  They are essentially the same. And we

will just index one of those pages as a canonical. And then we'll try to use the hreflang annotations that you have to show the appropriate URL in the search results. So we'll pick one canonical for that search and we'll focus our crawling and indexing on that canonical URL. And when we show it to users, we'll try to swap things out with the appropriate hreflang tag. So it's something where you can't do that.  

#### [0:06:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=360) |  From an indexing point of view, we

just pick one of those pages anyway, so you could theoretically save yourself the trouble and just have that one English page. But essentially, that's up to you. On larger sites, sometimes it's really hard to separate out the content and to create separate content versions for individual countries. But for maybe other parts of that site, you do have clear different country versions, so sometimes that's just kind of a side effect there.  

#### [0:06:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=390) |  I wouldn't recommend doing this kind of

as a thing on its own. So don't just take an English website and split it up into different country versions and hope that you have any advantage from that, because essentially you're just giving us a lot more work. We have to crawl all of these different country versions. We have to recognize that they're all the same. And we'll swap out the URLs in the search results and try to get it right, but it's not guaranteed that we'll always get it right.  

#### [0:07:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=420) |  So you're creating a lot of extra

overhead and you're probably not going to get a lot of value out of that. On the other hand, if the rest of your site does have appropriate country versions and you have some pages that are in the same like this, then that's not something I would lose any sleep over. MIHAI APERGHIS: Can I ask something related to that? To hreflang? So we're working with a website that they have a Romanian version and the English version, and that's because of most of their business is in Romania,  

#### [0:07:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=450) |  but they do have one offline location

somewhere in Europe, which is why they have the English version. So the site has hreflang tags that are between the English and Romanian versions. The problem is that about-- not half, but a big portion Romanian users, when they download Chrome, they usually download using the English version. So it's automatically set up to go to Google in English,  

#### [0:08:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=480) |  rather than in Romanian. So they keep

they keep getting, when they're searching for the brand name, they keep getting the English version of the website, which is not that ideal, even though they're in Romania. Now, one solution I can think of is simply add an additional hreflang tag like en-ro. So to make sure that they do get to the Romanian version, not to the English version.  

#### [0:08:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=510) |  But other than that, other than actually

forcing or forcefully redirecting them, I'm not sure what we could do about that because we don't really want Romanian users to get to the English version of the site from Google. JOHN MUELLER: Usually what I recommend for things like that is to show a banner on the page so that users, when they go there, they have a banner in their language or where the banner clearly says, if you're coming from Romania, here's the Romanian version.  

#### [0:09:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=540) |  That's usually the recommended approach. I think

flagging a page as saying English for Romania, and then it's actually in Romanian, that would probably be a bit tricky because we do try to recognize the language of the page as well. And if you're telling us it's English but it's actually recognized as being Romanian, then there's a chance that we'll just ignore that hreflang value. So that's something that might be kind of making it tricky.  

#### [0:09:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=570) |  But in general, also, especially with Chrome

and other browsers where, when you download it, it kind of defaults to the English US settings, that's something that we do try to catch when it comes to localization. So especially on Google, when you go to Google and you have kind of the default browser settings, then that's something where we say, this is kind of the absolute default  

#### [0:10:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=600) |  version. And there's a chance that maybe

this user didn't explicitly choose the English version, but rather it was kind of installed like that by default. And so that's something where we do try to figure out which of these versions is actually the right one to show. But especially for brand queries, that's something where I could imagine it's really tricky for us to recognize what languages you're actually looking for.  

#### [0:10:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=630) |  So for things like that, I try

to do more with just like a banner or some other way to let people know about the appropriate local version. Theoretically, you could also redirect to the Romanian version, but that might make people unhappy who explicitly want to go to the English version of a local website. MIHAI APERGHIS: Right. Well, we've checked the analytics for this issue,  

#### [0:11:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=660) |  specifically. So one problem is a big

portion of users-- so it's not just like 10%, 5%, 10%. It's like 30%-- something like that-- of Romanian users get to the English version. And the vast majority of them then choose to go the Romanian version. So it's basically not an ideal stretch. It's an extra step for them to take in order to get to where they actually want to get. [INAUDIBLE] actually posting a banner in case  

#### [0:11:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=690) |  they actually want to see the English

version and maybe something like that. Would the redirect mess up any of your signals or-- for a 302 redirect, something? JOHN MUELLER: I mean, it wouldn't mess things up for us because we would probably crawl from the US anyways, so we wouldn't see that redirect. But it could confuse people.  

#### [0:12:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=720) |  I mean, another approach that you could

take is to put the language into the title tag, so that when people search for the brand, they see explicitly English or whatever the Romanian word is for Romanian so that they can make that choice themselves. But I would tend to focus more on a banner rather than forcing a redirect. But that's something you can also test. Set up a banner and see if people actually click on it  

#### [0:12:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=750) |  or not. Try it out with a

redirect. And maybe have a banner then that lets them go back to the English version if they want. And then you can kind of test both of those sites. MIHAI APERGHIS: I'm not sure what you mentioned above, the title tag because it is set up like this. So you have the branding and the Romanian description of the shop, and the brand name and the English description of the shop. But obviously, it's just one of them showing up in the search results when you're searching for the brand name. So it's not like users can choose one or the other.  

![](https://i.ytimg.com/vi/vXwWuFCLTnc/maxres1.jpg)



#### [0:13:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=780) |  JOHN MUELLER: Well, in that case you

probably don't need to do anything-- MIHAI APERGHIS: Yeah. [INAUDIBLE] Yeah, thanks. JOHN MUELLER: All right. If you have a real estate site that has listings in various countries, do you need an hreflang tag for the listings, as well? The listings will technically not be translated because they're totally different. So in such a case, the hreflang tag will only be used on sub directories, like the language version.  

#### [0:13:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=810) |  Yeah, if these are different things, then

the hreflang tag would not be appropriate here. So the hreflang auto tag-- link element, I guess-- is only relevant if it's the same thing and you have a version for one country in one language and the same version of that thing for a different country, different language. But if these are completely different things, like one is a radio and the other is a car, then you wouldn't have the hreflang links  

#### [0:14:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=840) |  between those pages. For category pages, it

definitely makes sense. For the home page, maybe for some marketing pages, that definitely makes sense. But in your case, specifically, I'd say for the individual items, it wouldn't make sense. It's also something where you have to consider the amount of work that's required to setup this hreflang annotation between pages and to maintain that annotation. And if you're not seeing the wrong traffic going  

#### [0:14:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=870) |  to individual page types, then it's probably

a sign you don't need to set up the hreflang annotations. So that's something where I'd really try to save yourself the trouble of just setting it up for the sake of having it set up, because you're not going to see any ranking advantage for the hreflang annotations. It's just that, when we do show one of those pages, we'll try to show the appropriate one. I'm a product expert over on the Google news publisher forum.  

#### [0:15:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=900) |  I'm hearing more and more publishers reporting

that they're either being outranked by sites that are scraping and republishing their content, or being scraped and the scraper sites appearing on Google with their articles hours before Google indexes and surfaces the original content. What advice can you give for publishers experiencing these issues? What can Google do to try to help these publishers? P.S., DMCA complaints, removals, are too after the fact to be effective for news sites.  

#### [0:15:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=930) |  So I would still do DMCA kind

of complaints if you can do that, if that's something that makes sense in your legal environment. Obviously, that's something that depends a little bit on the legal situation. You can't just randomly send them out to people. But that's something I would definitely still do, even if that's afterwards, because that's something that we do try to understand on a bigger-picture scale,  

#### [0:16:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=960) |  as well. So that's definitely one thing.

The other thing where, I guess the second part of your question, where when scraper sites are appearing hours before the original content appears, that seems to be more of an issue that we're actually not crawling and indexing the normal content as quickly, rather than kind of that these scraper sites are doing something different. And most of the time, that's due to technical issues  

#### [0:16:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=990) |  in the sense that, if we can't

crawl and index a site that quickly, if there's something making it hard for us to crawl a website, then it will take longer. So that could be things like we're not able to understand where the main hubs of a news site are, where the category pages are, where the main home page is. And we get lost crawling all of these different URL parameters or different parts of the website, and through our normal crawling, we  

#### [0:17:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1020) |  don't run into the new content as

quickly. And for things like that, you can do the normal SEO things, like making sure that you have fewer of these pages out there that you don't want to have indexed so that we don't get sidetracked with all of this. Making sure that you have a clear structure set up with canonical URLs, that you don't have kind of too many URLSs leading into different parts of the site. And then making sure that you have proper site maps  

#### [0:17:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1050) |  setup in a way that you will

flag us new URLs as quickly as possible when you publish them, ideally with a correct last modification date in the sitemap file, because that does help us to understand when new content is published. So those are kind of the main things. Then obviously, with regards to the server that we can crawl as quickly as possible, we need to have a server that responds fairly quickly, that  

#### [0:18:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1080) |  doesn't return server errors. So those are

kind of the, I say, kind of technical, baseline things. One of the difficulties that sometimes plays a role is that sometimes things get stuck on our side, as well, where we try to crawl sites fairly quickly, and then sometimes things kind of get backlogged a bit in some of our pipelines. And then suddenly, we're a few hours behind in crawling sites. And that's generally pretty rare.  

#### [0:18:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1110) |  I think that has happened, maybe last

year, a few times. But I know the team is working to try to avoid that. And that's not something that you can really work around. And if, when I asked the team about things like that, I'd ask them like, are you going to improve this? They're like, of course. We see this as a bug. It's not something that we're doing on purpose, that we're crawling sites slower, in any case. It's more that, well, sometimes things break on our side  

#### [0:19:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1140) |  as well, and then it gets a

bit slower. So that might be some of what you're seeing there. The first part of the question is something that's really kind of hard for me to answer in a general way. It's like, when the scraper ranks above your original content, that's something where I really need to see more examples. So if you want to send me some example URLs, some queries that you see, especially the timely things,  

#### [0:19:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1170) |  when you see them popping up in

the forum, I'd love to pass that onto the team because that is something that they do also care about, as well. One tricky aspect there is also that sometimes, a site might technically be a news website, but that doesn't mean that it's a really good website. And trying to understand that difference is sometimes a bit tricky.  

#### [0:20:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1200) |  But I'm pretty sure you've seen that

in the forums quite a bit, that people will say, I have this great news website, and you look at it, and it's like, you can hardly read the English. It looks like you copied it from somewhere else. It's like, eh. CHRIS ANDREWS: Right. I'm talking more about sites that actually have original content. They have something good. And then some scraper ranks above them. And it's just so disheartening for the publishers. JOHN MUELLER: Yeah. I mean, if you can send me some examples,  

#### [0:20:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1230) |  I'd love to pass that on to

a team. CHRIS ANDREWS: OK, what's the best way to send those to you? JOHN MUELLER: You can drop me a note on Twitter. That's probably easiest. Let me drop my email address here in the chat. Essentially, when you see these things coming up on the forums and it feels like it's kind of timely, then send those over my way and I  

#### [0:21:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1260) |  can chat with the team to see

what we can do to improve that. CHRIS ANDREWS: OK, great. Thank you very much. JOHN MUELLER: Sure. All right, when going through a change of address, what's the preferred amount of time to keep 301 redirects in place from the original domain? What kind of ranking disruption should be expected as a result of the change? So technically, a 301 redirect is a permanent redirect. So ideally, you would keep that forever.  

#### [0:21:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1290) |  I think, as a minimal baseline, what

I recommend is at least a year because what can happen on our side is, depending on the URLs, it can take up to maybe a half a year or so for us to crawl all URLs on a website. So if you give it a year, then at least we've seen that redirect twice across all of those URLs on this website. Practically speaking, I would try to keep it longer still.  

#### [0:22:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1320) |  So especially if this is something this

is a website that you've built up over the years and you're moving to a new domain, then I would try to keep that redirect and place as long as you can so that anyone going to that old domain will still get a redirect, even if that's a couple of years later. The other reason why I would try to keep that redirect up as long as possible is to make sure that you don't accidentally drop that domain and some spammer  

#### [0:22:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1350) |  takes over your old domain, and suddenly

they're putting spam out that looks like it might be associated with your brand, or at least with your previous brand. And that's something that is always kind of awkward because you don't have control over that domain anymore, so you can't really fix that problem. But at the same time, it looks like you're putting all of that spam out there, which is not really what you want. So ideally, keep that redirect as long as possible,  

#### [0:23:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1380) |  and definitely try to keep the old

domain as long as possible. Yeah? MIHAI APERGHIS: Sorry. JOHN MUELLER: Go for it. MIHAI APERGHIS: I'm guessing this kind of depends also if there are any internal or external links pointing to that domain. I mean, I assume if there are none, then that baseline you're talking about can be adjusted since Google will likely  

#### [0:23:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1410) |  crawl that all of those old URLs

less, rather than finding links. JOHN MUELLER: I mean, anytime you're moving domains, in our documentation we also have that step of going out and trying to get all of those old links updated so that they point out the new location, as well. But it's always awkward when you see spam ranking with your old domain name.  

#### [0:24:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1440) |  So I try to keep that as

long as possible. And if you decide to reuse the domain name yourself for something else, then that's something a little bit different. I'd still give it that one year, at least, with the redirects. But then at least it's still under your control. And kind of what you put out there with your previous brand name attached to it is still something that you can control. So that's a little bit less of an issue, I'd say. I'd like to know how representative the sample is  

#### [0:24:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1470) |  of the data of clicks in Search

Console for a big site with lots of users. The site has many more URLs and queries than the 50,000 a day, and there's no way of knowing how representative that data sample is when you exclude brand queries. It goes on a little bit and YouTube cuts it off. So essentially, we do try to show as much as possible.  

#### [0:25:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1500) |  And for very large sites, it is

possible that you have more queries than the 50,000 a day that-- I don't know if that's the limit, or the 50,000 data points that we have there a day. Not quite sure where that number is, but that's something where, for most sites, we try to get as much as possible. We filter things out, like queries that are only done on a very rare basis, which could potentially be kind of private information  

#### [0:25:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1530) |  in the query. So we try to

filter that out. For very large web sites, we try to show, essentially, the bulk of the queries there. And at some point, we'll cut it off and say, well, these are queries that just have fewer your URLs, so we kind of cut it off there. So that's generally how that set is put together. With regards to how representative that set is,  

#### [0:26:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1560) |  I don't know how you would quantify

how representative that is. It's essentially as much information as we can give there. What sometimes do-- where I think you can probably get a little bit more information-- is if you have a sub-directories set up or subdomain set up, and verifying those sections of the site separately  

![](https://i.ytimg.com/vi/vXwWuFCLTnc/maxres2.jpg)



#### [0:26:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1590) |  sometimes gives you the full set of

information for each of those sections. So that might be one thing to try out there, as well. Can you explain how Google calculates the average position in Search Console? Search Console uses a weighted average with the impressions. The documentation doesn't explain it in-depth. We actually have pretty good documentation on how the average top position is calculated. So I would double-check that Help Center page.  

#### [0:27:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1620) |  I think it's called, what are impressions,

clicks, and position-- something like that-- in the Search Console Help Center. So I tried to dig that up. Essentially, what happens is we have two ways of looking at this information. On the one hand, we look at it per URL. And on the other hand, we look at it per site for each query. So the per query thing is, essentially,  

#### [0:27:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1650) |  if someone is searching for something and

multiple of your pages would rank for that particular query, then we would take the average of the topmost position and use that. Whereas, if you're looking at it on a per URL basis, then obviously, we use the average position of that particular URL. So what can happen, for example, is if you have things that are shown as site links-- you might have maybe your home page as position 1 and individual pages otherwise on your site that  

#### [0:28:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1680) |  are listed as [INAUDIBLE] five or six

in the site links section. So on a per query basis, we would count that as position 1. On a per URL basis, for the individual things shown and the site links, we would count that as position 5 because that's where that one particular URL is shown. So if you compare across per query and per URL basis, then there will be a difference. And that's essentially based on that.  

#### [0:28:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1710) |  So that makes it a little bit

tricky. From my point of view, I think it's fine to separate it out like that. But I think it's something that, especially with a larger site, you really need to be aware of how this data is put together so that you can compare these results a little bit easier, so that when you look at Search Console and you see one number shown on top and then one number from the table, and you look at it in a different way. You filter things out and you see different numbers,  

#### [0:29:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1740) |  then that's something where you kind of

need to understand, this is not like Search Console trying to mess with you, but rather, this is essentially a side effect of how things are counted in Search Console. All right, subdomain, subfolder leasing. Wow. OK, gigantic question. I'm going to have to cut this a little bit shorter, I guess.  

#### [0:29:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1770) |  So I think we've gone through this

for a number of times, so I don't really know how much more I can say here. Essentially, I think what the question comes together, is sometimes large websites take a part of their website and they essentially rent it  

#### [0:30:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1800) |  to other sites, or they let others

place ads, essentially, on that part of the website. And that-- sometimes that shows up in search because it's content that's on a website. And there's lots of back and forth on whether or not that should be OK or that should not be OK, or how that should be treated. And I think there's just different points of views out there with regards to how that can be seen.  

#### [0:30:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1830) |  So this is a gigantic question with

lots of statistics and examples in it. So I don't really have anything specific to add there. But I think, in general, this is something where, when it comes to search, there are always different ways of looking at things and there are different ways of looking at it and saying, well, this is a good result, or this is a better result. And people can have different opinions on this.  

#### [0:31:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1860) |  So that's something where I wouldn't see

this as clear black or white thing, where this is always bad or this is always good. But rather that we, with our algorithms and the engineers that are working on the quality side, we need to find the appropriate way of showing this kind of content in search. And sometimes, it makes sense to show it very visibly. Sometimes, maybe it doesn't make that much sense. Maybe we need to find other ways of recognizing high-quality search results and showing that appropriately.  

#### [0:31:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1890) |  So from that point of view, I

don't think we'll have a clear black and white answer, like you're always allowed to do this, or you're never allowed to do this, or you'll never see this in search. But rather, over time, as we get feedback on our search results, we'll try to improve things the way that we can show them in search. ALVARO LOZANO: John? JOHN MUELLER: Yeah? ALVARO LOZANO: Yeah, hello everyone can I ask two questions?  

#### [0:32:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1920) |  JOHN MUELLER: Sure. ALVARO LOZANO: Sure. The

first one is about the sponsored link attributes. I've seen, you know, four months or so, you announced know the difference, user-generated content, and response, and so on. So I have analyzed a few sites. And I've seen that just a few of them, pretty much the biggest ones, use these attributes. But most of them common sites still don't use it.  

#### [0:32:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1950) |  So I don't know. My question is,

do you recommend using it for media reach and things like that? Or what would be the most common using of these attributes? And the second-- well, I don't know if I ask the second. JOHN MUELLER: Yeah. So I would try to use them as appropriate. So it's something where I wouldn't say you need to revamp your website immediately and switch  

#### [0:33:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=1980) |  to whatever kind of link attribute is

most appropriate for your specific use case. If you're using no follow and that's working for you, then that's fine. If you're setting up a new website and you have user-generated content, and maybe using the real UGC is kind of the right approach there. From our point of view, we don't see kind of the more specific types as something that is required from a website.  

#### [0:33:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2010) |  So it's not something that we wanted

to push out and say, OK, everyone needs to change how they're working with this. But rather, it can give us more information if you our more specific. So going forward, if you can give us kind of the more correct information, that would be great. If you don't want to update your website to do that, then that's also fine. So it's not like a critical thing that everyone must do. ALVARO LOZANO: Right.  

#### [0:34:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2040) |  Got it. Thanks. And the second one

place is, imagine you have a really large website and you generate thousands of URLs with, let's say, team A and team B. Imagine it's betting site. Sports betting. And obviously, you have the like the sport generic sport betting category. Let's say football, basketball, tennis, or whatever. And then you have a team A versus team B. And usually, people are always searching to bet just for this specific category, not for team A or team  

#### [0:34:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2070) |  B. Would it make sense for-- I

mean, what is the most correct way to proceed in this case? Just getting there the main category page of the sports betting as to follow with a canonical tag, and then the rest of the team A, team B with no index? Or the whole bunch of URLs of the website, that  

#### [0:35:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2100) |  could be half million URLs, all of

them indexed? And when there's team A versus team B with the right canonical to their right category? Which is the best practice? JOHN MUELLER: Essentially, that's up to you. So that doesn't really help you in your specific case, but it's something where you're balancing having concentrated content on your site where you're saying, I only have 10 pages because I focus on the category pages.  

#### [0:35:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2130) |  And the rest of the pages are

no index, or they have the real canonical set to those 10 pages. That's fine if you want to concentrate things together. But it might also be fine to say, well, these specific, kind of individual items are things that people are looking for. And I want to provide that information in search. Where you say, well, like I will expand and show those pages, as well. And that's sometimes more of a strategic decision  

#### [0:36:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2160) |  rather than a pure SEO decision, because

you can have fewer pages and they can be stronger, so they could rank better for more competitive queries. On the other hand, you could also have more different pages and they rank more kind of in the long tail queries. And finding that balance between content for kind of the competitive area where you have fewer pages that are focused on that, and also covering the long tail area, is something-- finding that balance is sometimes tricky.  

#### [0:36:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2190) |  Sometimes, that's also something where you can

test it out. And you can say, well, for this one specific event, I will only create category pages-- fewer pages and see if that works well and for the other one maybe I'll create a certain amount of long tail pages and see if that works well. ALVARO LOZANO: Right, yeah. The thing with that is with the long tail queries, we already generate content for covering them. So it's kind of-- they do cannibalize sometimes, you know? So-- JOHN MUELLER: Sure.  

#### [0:37:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2220) |  Yeah, I mean, in that case, I

think you have the answer there yourself. If you already cover those long tail queries well, then make sure that your important pages are kind of in that competitive area where you're really concentrating the value on those core pages. ALVARO LOZANO: Absolutely. Thank you very much. JOHN MUELLER: Sure. Do unnatural queries like a site colon,  

#### [0:37:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2250) |  are they also counted in Search Console

performance reports? As far as I know, they're not counted. At least, I haven't seen them in any of the reports that I've looked at. So from my point of view, I think we try to filter those kind of things out. We also try to filter a lot of other kinds of more unnatural type queries out. Oftentimes, these fall out automatically anyway because very few people use site  

#### [0:38:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2280) |  colon queries to search. If you publish

news content, but sometimes unpublish after discovering that your editorial guidelines have been breached, would a 410 help speed up removal from search so that you don't have thousands of readers landing on a 404 page? Submitting to Google for a removal option can take a long time. So, I think for news content, probably 404 or 410  

#### [0:38:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2310) |  doesn't make any difference. So I would

say that you can save yourself the trouble of trying to a special case that kind of situation. The URL removal tool would probably be a good approach here. The URL removal tool, if you have the site verified in Search Console, usually takes effect in less than a day. So that's fairly quick. With regards to general news content like this, where you really want to make it clear that you did not  

#### [0:39:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2340) |  mean to publish something like this, I

would still return 404 and maybe show some kind of information on that page and says this article doesn't exist, or whatever you would want the user to kind of guide them to the existing content on your website. But I don't think you would see any advantage of using 410 versus 404 So from a practical point of view--  

![](https://i.ytimg.com/vi/vXwWuFCLTnc/maxres3.jpg)



#### [0:39:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2370) |  so from a theoretical point of view,

410 10 generally falls out a little bit faster for normal web content, like it for crawling things every couple of days and we see a 410, then that generally falls out a little bit faster. From a practical point of view, that difference is very minimal. So compared to the amount of effort that you need to kind of special case the situation of returning 410 for this particular type of situation where page no longer exists,  

#### [0:40:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2400) |  I would just save myself the trouble

and just return 404 normally across all of those pages. So that difference between 410 and 404 is sometimes overrated. Let's see. If we have a back link from a site that has declining traffic, is the value of that back link devalued in the eyes of Google as a result of the decline in traffic from the site that we had the back line from?  

#### [0:40:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2430) |  If so, should we disavow? So first

off, you do not need to disavow any links just because you think that maybe the site is not getting as much traffic as it used to. So definitely no need to disavow anything like that. If these are natural links to your site, if these are normal sites that are linking to your website, there is nothing wrong with that. There is no need to disavow anything like that.  

#### [0:41:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2460) |  I remember, way in the early days

when we had page rank in the tool bar, people would be like, oh, do I need to ask people to remove links to my site if their page rank is three, or page rank is two? It was like, low page rank links, they will cause my site harm. And that's also not the case. So just because a site is not as popular or not as popular as it used to be, that does not mean that link from that site is in any way bad and that you need to in any way  

#### [0:41:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2490) |  react on that and say, oh, this

is bad. I need to block it from Google. So that's something where I would really look at it more as, this is a link that I kind of placed there a couple of years ago when I didn't know better. And I can't contact the webmaster anymore, or they don't want to remove it anymore, and I don't want to take taken into account. Then that's something you might want to disavow. Or if you had someone do that on a large scale, like go out  

#### [0:42:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2520) |  and buy a ton of links and

now you have a manual action on your website for link spam, then maybe that's something you'd want to disavow to kind of help clean up. But just because that site is not as good as it used to be or doesn't get as much traffic as it used to, that is definitely not a situation where you need to disavow anything. So I would really use the disavow tool only in those cases where you do have a manual action when it comes  

#### [0:42:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2550) |  just to link spam or when you

look at your link and you're like, Google is going to catch me and give me a manual action next week kind of thing. That's another reason to use the disavow tool to kind of preemptively catch that. And those are really the primary use cases of the disavow tool, but definitely not for things that just aren't as popular as they used to be. Another really common variation of this question is, what if I got a link from a page in a language  

#### [0:43:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2580) |  that I don't understand? Do I need

to disavow that? And that's also not something that you need to disavow. It can happen that you get a link from a website in a completely different language. And it's a normal link. You don't need to block that. Can Google detect if my content is the same, even if I changed my WordPress theme or even if I modify my HTML5 structure?  

#### [0:43:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2610) |  Sometimes. So, a lot of times, we

can recognize that the content is the same. And if you're moving things around on your website, you move things from one URL to another, and for whatever reason you can't set up redirects properly, then we will try to recognize that and treat that more as a move rather than a completely separate URL. So that's something we can kind of do. But obviously, if you're moving things around on your website,  

#### [0:44:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2640) |  using a redirect is much cleaner and

makes it much easier for us to recognize what's actually happening there. The question goes on, I guess, in a different direction. Some people copy my content. Is Google prepared to know that my content was the first? And if so, what happens if I then modify my article to add some more paragraphs? Will Google still consider me as the author? What would happen if I changed authority of an article?  

#### [0:44:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2670) |  So I'm not quite sure how you

changed the authority of an article. But in general, we do try to recognize original content and show that appropriately in search. That doesn't mean it will always rank first. So that's something that I see quite a bit with our blog, for example, in that we will published a blog post and it's all fantastic, and then Barry goes out and writes a blog  

#### [0:45:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2700) |  post about our blog post, and then

suddenly Barry ranks for our content, which, from one point of view, like, why is this guy ranking for our content? But on the other hand, he adds a lot of value to those pages and those are completely valid pages. And it makes sense, sometimes, to rank those above our content. So just because someone else who is writing about your content or using parts of your content ranks above your content doesn't necessarily mean that something is broken,  

#### [0:45:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2730) |  or that there's something wrong there. So

sometimes it's just, well, other people write about the same topic and they quote some of your content, and that's perfectly fine and valid. My question about backlinks. I was reading some articles and I commented on that article. As we know, mostly when we comment on an article, they take our URL and our name. So I put my name, not the company name and the company  

#### [0:46:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2760) |  URL, and now the problem is they're

showing my content on the latest comments page and the latest comment is showing on all pages of their site. So now I have 33,000 backlinks coming from that site. Is this a sign of backlink spam or something that I should disavow, or do something else? So if this is a legitimate comment on a site, then that's not really backlink spam.  

#### [0:46:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2790) |  That's essentially a comment that you placed

on a website. I think it's a slippery slope in the sense that people sometimes take this and say, oh, if this is a natural link, then maybe I should go out and comment on 100,000 sites and get 100,000 links. And then, at that point, our algorithms will probably say, well, all of the links are links that the person placed themselves, so maybe we should kind of ignore those links.  

#### [0:47:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2820) |  But if these are individual comments that

are left across the web and you're interacting with the rest of the web in comment sections, that's completely fine. A lot of cases, these kind of comment links will be with a no follow, or with a real UGC nowadays anyway. So it's not that we would take those links into account when it comes to ranking. But we would still show them in Search Console when you look at the links report in Search Console.  

#### [0:47:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2850) |  So we also show no follow links

there. So I guess, circling back, just because suddenly you see a lot of links from one website doesn't necessarily mean that there's anything bad that's happening there or that you need to disavow that website. If those are natural links, those are natural links. There is nothing to disavow about that. We have a directory site that's been online for nine years. We've collected five million reviews  

#### [0:48:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2880) |  and had rich snippets local business review

star ratings display for more than eight years. Around December 6, these went away, yet we have no manual action against us. And it cut the rest of the question off. Let see if I can reload. Let's see. Where were we? There we go. We're stumped, while our competitors remain intact. Can you provide us some insight?  

#### [0:48:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2910) |  So it'd be kind of useful to

know which sites, specifically, you're looking at there. Maybe if you can post in the forum, we can take a look there, or other people can take a look. We did change some things with regards to the review star ratings when we showed them in search with regards to what type of reviews we would show. So that might be something where you're seeing those changes, and those kind of policy changes, from our point of view, they can happen over time where we say,  

#### [0:49:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2940) |  well, this is something that didn't work

out so well. So we're going to change the way that we show them in search. And that's not necessarily something where, if you're implementing it that way and we decided that way is not something we want to show in search, then that's essentially something we wouldn't show in search. With regards to competitors remaining intact, sometimes people implement rich results in the wrong way. And that's not necessarily something  

#### [0:49:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=2970) |  I'd recommend copying. So if your competitors

are implementing them incorrectly and they're still being shown, then my recommendation would be not to just blindly copy the wrong markup that they're doing, but rather to kind of leave it at that. Yeah. OK, wow. We're running really low on time, so maybe I'll just open it up for any questions from any of you for the last couple of minutes.  

#### [0:50:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=3000) |  DALTON FINNEY: Yeah, I have a quick

question for you. Is there a reason-- we've got a pretty big website that's about 200,000 URLs and it's also being dynamically created site maps every day, closer to the end of the day. In the last month or so, I've really seen the last read numbers go down in the Search Console  

#### [0:50:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=3030) |  in terms of how often all of

our different site maps are read. It usually used to be like every day, every other day. And now it's just really flagging. And I don't know, since we're creating so much new content day-in and day-out, it's pretty crucial that it's being read all the time. Is there any way-- one, is there any reason why it's happening? And two, is there any way we can help improve that? Thank you. JOHN MUELLER: Yeah, I'd almost tend it's to post that in the Help Forum to try to get some more eyes on it  

#### [0:51:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=3060) |  because it might be that there are

ways that you can improve the structure of the site map. It could be that maybe we're just not catching up with the amount of crawling on the website itself. It could also be that, just from the kind of content that you're creating, we're looking at that and saying, well, it's not worthwhile to index all of a new content all the time. Maybe there are ways to kind of concentrate things a little bit.  

#### [0:51:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=3090) |  But a lot of that is feedback

you could get from the Help Forum. So I'd try that there. You can also paying me on Twitter or maybe send the URL that I can take a look at to see if there is anything generally wrong there or not. BARRY SCHWARTZ: I have a question. So Bing's-- [INAUDIBLE] from Bing basically made a short video saying keyword research practices are kind of going  

#### [0:52:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=3120) |  away and should be replaced by intent

research practices. So something about keywords thinking about intents. Do you have any thoughts about that? JOHN MUELLER: I didn't see that. But I think in general, there's probably always going to be a little bit of room for keyword research because you're kind of providing those words to users, and even if search engines are trying to understand more than just those words, showing  

#### [0:52:30](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=3150) |  specific words to users can make it

a little bit easier for them to understand what your pages are about, and can sometimes drive a little bit of that conversion process. So I don't see these things going away completely, but I'm sure search engines will get better over time to understand more than just the words on a page. BARRY SCHWARTZ: Thank you. JOHN MUELLER: All right. I need to jump out. It's been great having you all here.  

#### [0:53:00](https://www.youtube.com/watch?v=vXwWuFCLTnc&t=3180) |  Thanks for joining in for the new

year. And I have the next one lined up on Friday, so feel free to join there, or the German one on Thursday, of course. All right. Bye everyone. See you next time.  