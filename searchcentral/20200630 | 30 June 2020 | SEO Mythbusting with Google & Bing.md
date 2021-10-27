[![SEO Mythbusting with Google & Bing](https://i.ytimg.com/vi/y9GNFEne484/hqdefault.jpg)](https://www.youtube.com/watch?v=y9GNFEne484)

## SEO Mythbusting with Google & Bing

In the first episode of SEO Mythbusting season 2, Martin Splitt (Developer Advocate, Google) and Sandhya Guntreddy (Principal Program Manager, Microsoft) discuss the most common SEO questions they get, the trends they see in the SEO community as well as Bing Webmaster Tools and Google Search Console. 



Specific timestamped topics discussed in the first SEO Mythbusting episode:

If I have a lot of backlinks, will I rank higher? (0:00)

How to rank at the top of search engines? (1:43)

I run search ads, will I get ranked higher? (6:09)

Is the SEO community getting more technical? (6:35)

Blockers, Robots.txt, Bingbot and Googlebot (7:15)

Integration of Google Search Console and Bing Webmaster Tools (9:58)

Recommendations for JavaScript SEO (10:35)

Third-party tool scores and query intent vs user intent (12:53)



Documentation mentioned in this episode:

Bing Webmaster Tools

Verify Bingbot Tool → https://goo.gle/38an3kx 

URL & Content Submission API → https://goo.gle/2NDZeYN 

Crawl Control → https://goo.gle/2Zj6IWB 

Import sites from Google Search Console to Bing Webmaster Tools → https://goo.gle/2NGAKOv



Formalizing the Robots Exclusion Protocol Specification (blog post) → https://goo.gle/3g7K4Hu 



Watch more SEO Mythbusting episodes → 

https://goo.gle/SEO-Mythbusting  

Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=y9GNFEne484&t=0) |  SANDHYA GUNTREDDY: Especially in backlinks, there's one

angle on myths, right? If I have a lot of backlinks, I'll probably rank higher. So there's a myth. Yes, it's one of the signals, but that's the only signal. You've hundreds and hundreds of signals. And people actually spam-- MARTIN SPLITT: [INAUDIBLE] SANDHYA GUNTREDDY: --people actually spam the [INAUDIBLE].. MARTIN SPLITT: It's easy to game that one. If that would be the signal, it's so easy to game. You just buy a bunch of links, really, and then you're like woo! [MUSIC PLAYING]  

#### [0:00:30](https://www.youtube.com/watch?v=y9GNFEne484&t=30) |  Hello, and welcome back to "SEO Myth

Busting." This is the beginning of season 2. And we have listened to your comments and feedback last time. So in the first season, we were basically taking questions from developers and busting myths that are coming from developers.  

#### [0:01:00](https://www.youtube.com/watch?v=y9GNFEne484&t=60) |  This season is more of the SEO

side. And the first one is really exciting. And Sandhya from Microsoft, and you're on the team that makes the Bing Webmaster Tools. SANDHYA GUNTREDDY: Absolutely. Thank you, Martin, for inviting me. And it's amazing to be here and talking to you as two search engines. MARTIN SPLITT: Yes. And we are not isolated from each other. We are working together to make search better for all the users on the web and for all webmasters there. SANDHYA GUNTREDDY: Absolutely. Whatever we speak today is going to be my personal opinion.  

#### [0:01:30](https://www.youtube.com/watch?v=y9GNFEne484&t=90) |  I'm not a Microsoft spokesman-- person. So,

yeah-- MARTIN SPLITT: Yeah, pretty much the same on my side. So what we are doing here is exchanging our personal experience working in this field, working in this community. What would you say is actually the most frequent myth or question that people are coming with to you? SANDHYA GUNTREDDY: One of the top questions we ever hear in all forms of communication is, how can I rank on the top, right? MARTIN SPLITT: Yes!  

#### [0:02:00](https://www.youtube.com/watch?v=y9GNFEne484&t=120) |  SANDHYA GUNTREDDY: That's the number one question

everywhere. MARTIN SPLITT: That's the number one question from everyone, literally. SANDHYA GUNTREDDY: Literally. And it's interesting that they're very passionate about it. But we can't help it. MARTIN SPLITT: No. SANDHYA GUNTREDDY: And because at the end of the day, we are trying to meet the users' needs and what they really need. And we try to match the need and what they have. And so, we try to educate-- MARTIN SPLITT: And there's hundreds of factors-- SANDHYA GUNTREDDY: Yes! MARTIN SPLITT: --that we-- it's not that we can turn a knob or something, or we go into a database and go, change that number from 5 to 2,  

#### [0:02:30](https://www.youtube.com/watch?v=y9GNFEne484&t=150) |  and boom! SANDHYA GUNTREDDY: No, that never

happens. MARTIN SPLITT: It can't. SANDHYA GUNTREDDY: There is a myth. There is a myth that we could because some people actually reach out to us and say, hey, can you help! Can you tell us exact steps what to do? And we try to help as much as possible in terms of giving them what are the fundamentals they have to do on the website. And if they have the right intention-- MARTIN SPLITT: Yes. SANDHYA GUNTREDDY: --but-- MARTIN SPLITT: It's all in the public documentation.  

#### [0:03:00](https://www.youtube.com/watch?v=y9GNFEne484&t=180) |  You don't get private support from you

or me or-- SANDHYA GUNTREDDY: Yes, their webmaster-- yes. And they're all there on the webmaster guidelines, both in Google side as well as on Bing as well. So I think if they follow that, I'm sure for the right intent, they will rank on top. MARTIN SPLITT: Exactly. Just put the user first, and you'll be doing fine, mostly. That's the-- get the basics right, and you'll be doing all right. And I find it interesting, and like sometimes people get really creative. I got a message on Instagram asking about ranking. And I'm like, what's happening here?  

![](https://i.ytimg.com/vi/y9GNFEne484/hq1.jpg)



#### [0:03:30](https://www.youtube.com/watch?v=y9GNFEne484&t=210) |  SANDHYA GUNTREDDY: Yeah, I know. I do

get-- we get direct messages on Twitter sometimes, especially if you're active out there. And sometimes even on emails, support. Support is understandable, sometimes. They're trying to figure it out who knows you, and then they reach out through that as well. MARTIN SPLITT: Secondhand kind of thing. SANDHYA GUNTREDDY: Yeah, they do that. MARTIN SPLITT: This is interesting, because we get all these requests coming in. And people ask us questions pretty much all the time in all sorts of channels.  

#### [0:04:00](https://www.youtube.com/watch?v=y9GNFEne484&t=240) |  And I know that we are not

one person facing these questions in the public eye. And you are not one person on the team either. So you have Fabrice Canel, and you have Federick Du Bois. SANDHYA GUNTREDDY: Yes. MARTIN SPLITT: And it's you and it's others, probably, in the future as well. What we see happening is that sometimes we get asked the same question, each of us individually, to figure out, are we responding the same way. Do you get that? SANDHYA GUNTREDDY: Yes, absolutely. We hear that a lot because we see the similar pattern coming through.  

#### [0:04:30](https://www.youtube.com/watch?v=y9GNFEne484&t=270) |  So we're trying to be-- try to

give the same responses, at the end of the day. Otherwise they would get-- take it in a different context a little bit. MARTIN SPLITT: That's the thing, the context. Sometimes these questions depend on so much context. And then someone asks you a question, given this context, and the answer is A. But then the same question given a different context, the answer is B. SANDHYA GUNTREDDY: Yeah. MARTIN SPLITT: And then people like to ditch the context, and then just go like, but Martin said, A SANDHYA GUNTREDDY: Yeah. And they will take it literally.  

#### [0:05:00](https://www.youtube.com/watch?v=y9GNFEne484&t=300) |  MARTIN SPLITT: They take it literally. SANDHYA

GUNTREDDY: So we're very conscious about it. What we do is when you say it, we try to do little longer, bigger sentences so that it's not, yes, that's do-- that probably will take it in a different context. We try to cover that fully. We try to share as much and be transparent as much. If it's taken out of context, it's unfortunate. There would be some incidents like that. MARTIN SPLITT: It's a challenge. Sometimes it's a challenge. SANDHYA GUNTREDDY: It's a challenge. I'm sure Yandex and Baidu probably  

#### [0:05:30](https://www.youtube.com/watch?v=y9GNFEne484&t=330) |  do that same thing as well. MARTIN

SPLITT: Do you also have the feeling that certain things are getting a lot better, and we are getting a better understanding, and also the tone is nicer and more constructive? Or how do you-- what do you think the trend is in the community? SANDHYA GUNTREDDY: I think people are much more aware. I think there is a lot of evangelism of what happens behind the scenes. I think-- if you think about people understand how search works, earlier there was a concept in terms of, hey,  

#### [0:06:00](https://www.youtube.com/watch?v=y9GNFEne484&t=360) |  they're probably doing some manual actions and

things like that. But now people know it's not true. And the other thing which we also see now-- I don't know if you've seen from Google is, hey, I am advertising out here. Will I get ranked higher? MARTIN SPLITT: Oh, yeah. SANDHYA GUNTREDDY: Do you hear that? MARTIN SPLITT: We hear that. We hear that, yes. Do you have that as well? SANDHYA GUNTREDDY: Yes, we do hear that. So we're saying, no, ads is very different ranking and organics is very different. They're very separate. You don't want to mix it.  

#### [0:06:30](https://www.youtube.com/watch?v=y9GNFEne484&t=390) |  MARTIN SPLITT: Absolutely. There's is a very

strong separation between it. And I'm sure you're doing the same thing, yeah. So a thing that I wonder, and maybe that's just my personal lens to it because I am very technical and coming from the technical side of things, I think the community is picking up more and more technical SEO, and getting more technical, and looking at the technical details. Would you say the same, or is it different for you, what you are seeing? SANDHYA GUNTREDDY: No, they are definitely getting technical. And they're doing a lot of work, especially trying to give us-- making sure that we understand the content behind it, right,  

#### [0:07:00](https://www.youtube.com/watch?v=y9GNFEne484&t=420) |  and what's the intent, and what is

the website? They do a lot of work. But one thing we also notice is that they forget the fundamentals in the grand scheme of things and why they're doing it. And a classic example is the blockers in robots.txt, and you're not able to crawl them. Hey, why are you not crawling me? Hey, you blocked me! MARTIN SPLITT: You're telling us we shall not crawl, but you're not crawling me. You're like, uh? SANDHYA GUNTREDDY: Yeah. So we actually developed a couple of tools for that.  

![](https://i.ytimg.com/vi/y9GNFEne484/hq2.jpg)



#### [0:07:30](https://www.youtube.com/watch?v=y9GNFEne484&t=450) |  And we have a Verify Bingbot. The

reason we did that is because when we talked to all these people, hey, why are you blocking us, they say, hey you're crawling me too much! And then saying that we really-- because we have logs and stuff like that, and we found that that's actually somebody masking as Bingbot, and they were crawling. MARTIN SPLITT: That happens a lot, doesn't it? SANDHYA GUNTREDDY: Yes. And then-- we're basically telling them, hey, check out the IP range. And we said, this is the IP range from which Bingbot will crawl you. If it's different, you can just block it at your server level  

#### [0:08:00](https://www.youtube.com/watch?v=y9GNFEne484&t=480) |  or let us know, and then we'll

figure it out. MARTIN SPLITT: You're also having the indexing API that you can basically submit content? SANDHYA GUNTREDDY: Yes, URL submission. We call it URL submission API. Websites can actually submit two URLs, especially if it's new or updated. And we allow them instant-- very fast indexing, instant indexing of that. MARTIN SPLITT: Yeah, it's a push mechanism rather than a pull mechanism, as robots and crawling have been. SANDHYA GUNTREDDY: We've also done something called crawl control.  

#### [0:08:30](https://www.youtube.com/watch?v=y9GNFEne484&t=510) |  You tell us if it's big business

hours, then we won't crawl you. Tell us off-peak-- MARTIN SPLITT: I saw that. SANDHYA GUNTREDDY: --and then we'll crawl you during the time, and tell us the rate. And that's a good signal [INAUDIBLE].. MARTIN SPLITT: That's a really, really cool tool. SANDHYA GUNTREDDY: So after that, it's gotten better. But it's still-- it's still out there. A lot of people still do that. MARTIN SPLITT: We do get all sorts of support requests, like, oh, I have this problem that every now and then-- or not every now and then, like every day Googlebot crawls all these pages that I set to no index and forbidden robots.txt. And we're like, are you sure that it's Googlebot or not  

#### [0:09:00](https://www.youtube.com/watch?v=y9GNFEne484&t=540) |  someone masking a Googlebot? And then it

usually turns out-- if you do the reverse DNS lookup, it's someone else masking as a Googlebot. SANDHYA GUNTREDDY: There are so many crawlers out there. MARTIN SPLITT: We're seeing bunch of stuff's happening. So the robot.txt is a fantastic example, because it has been basically a de facto standard, but it is not really a standard. But I'm really happy to see that we are all working together and getting it into an actual standard and making that more explicit these days. SANDHYA GUNTREDDY: That's right. MARTIN SPLITT: That's really, really cool. SANDHYA GUNTREDDY: Yeah. And I saw the articles, very nice.  

#### [0:09:30](https://www.youtube.com/watch?v=y9GNFEne484&t=570) |  MARTIN SPLITT: Right. Gary is working with

y'all. And it's so nice to just get everyone together. And we are-- as you say, we are all trying to service the same SANDHYA GUNTREDDY: Same customer, same intention. MARTIN SPLITT: Exactly. SANDHYA GUNTREDDY: Absolutely right. MARTIN SPLITT: And we are not plotting each other against each other. It's just more like trying to figure out and learn from each other. I really, really like the Crawl Control Tool. And I wish we had that. But yeah, it's-- SANDHYA GUNTREDDY: There are so many tools out there which you have. I wish we had some of them as well. MARTIN SPLITT: You're integrating with them, right? SANDHYA GUNTREDDY: Yes.  

#### [0:10:00](https://www.youtube.com/watch?v=y9GNFEne484&t=600) |  MARTIN SPLITT: If I'm verified in Search

Console, I am automatically verified in Webmaster Tools. SANDHYA GUNTREDDY: Yes. We just released that. One of the things, I'm like, hey, it's so tough-- I mean, when we talk to webmasters, they said, hey, so it's very time-consuming to verify. And we noticed that the same verification mechanisms are also there on Search Console. So we said, hey, if the same verification mechanisms, they will honor that. And you've done all the work, so we'll honor it. You can actually keep both of them in sync together, right?  

#### [0:10:30](https://www.youtube.com/watch?v=y9GNFEne484&t=630) |  You verify, you can import your site

maps, and you're all set, in sync, making it so easier. MARTIN SPLITT: So I have an interesting challenge that I wonder how you are dealing about this. Because it is very hard to get people the right guidance on this. And when I'm saying that, I mean JavaScript. So we both know JavaScript is probably the most expensive resource you have on your website, because images are not that expensive. Even video you can pass more or less as it comes in. But JavaScript you can't. On one hand, people are building really cool things  

#### [0:11:00](https://www.youtube.com/watch?v=y9GNFEne484&t=660) |  on JavaScript. On the other hand, I

don't want them to entirely rely on JavaScript. It's really narrow path to navigate. SANDHYA GUNTREDDY: Yes. MARTIN SPLITT: What are you doing on these things? SANDHYA GUNTREDDY: So it's very similar. And the end of the day, the challenges are-- it's very expensive. And the first thing we have to figure out is the intent, if the website or the page has the right intent. And if you're able to figure out the intent behind it, it's easier to prioritize. And sometimes you will just have like--  

![](https://i.ytimg.com/vi/y9GNFEne484/hq3.jpg)



#### [0:11:30](https://www.youtube.com/watch?v=y9GNFEne484&t=690) |  just execute a couple of Java scripts

and no intent, no title, no description, no meta-script, none of that. I'm like, we don't even know what it is. Do we really want to execute? So that time it-- it's a challenge, because end of the day, you have a certain set of resources, and you-- MARTIN SPLITT: You have to use that reasonably. SANDHYA GUNTREDDY: Reasonably. It's a [INAUDIBLE] question. And I think that's a judgment call, which would increase the websites to actually to do that. MARTIN SPLITT: So would you say-- SANDHYA GUNTREDDY: It's the right balance. MARTIN SPLITT: It is a balance that you have to strike. So what do you say--  

#### [0:12:00](https://www.youtube.com/watch?v=y9GNFEne484&t=720) |  a client-side-rendered application in JavaScript is not

a problem by itself, it's just more expensive. And you have no hints upfront. So you can't figure out the intention, you do not have the title. None of this exists until the JavaScript is executed. Would you say that service site rendering and hydration is a good way to fix that? As in, you ship a bunch of intent-- initial content to the browser, and then use JavaScript to enhance it for the user, giving you a balance? SANDHYA GUNTREDDY: The right balance, yes.  

#### [0:12:30](https://www.youtube.com/watch?v=y9GNFEne484&t=750) |  You need to do both of them

because, end of the day, you also want to make sure it's a lively page. It's rich-- you want rich results as well to serve your customers. And especially in this world, people want richer results. MARTIN SPLITT: Richer results. SANDHYA GUNTREDDY: So you need to balance that, so some server side and some client side. MARTIN SPLITT: So that's lovely to hear that we are aligning on recommendations again. SANDHYA GUNTREDDY: Yeah. MARTIN SPLITT: This is really cool. And do you also sometimes get these weird questions where people are leading with a random third-party tool,  

#### [0:13:00](https://www.youtube.com/watch?v=y9GNFEne484&t=780) |  like, oh, we have this tool. And

the score on this tool is 75. And I don't understand why we're not ranking high? And you're like-- SANDHYA GUNTREDDY: Yeah, that's there, the DAs, and-- MARTIN SPLITT: All of these lovely metrics, and I'm like, mm, fantastic. SANDHYA GUNTREDDY: That's good. They need some number and metric. And they're trying to ask those questions, but you don't have an answer because that's not the only signal. There are multiple things. I think a lot of people really don't understand that there's a query intent.  

#### [0:13:30](https://www.youtube.com/watch?v=y9GNFEne484&t=810) |  People really think about the serving side

and what they have in the index. People forget there is a query intent, there's a user intent behind it. And we have to match. I think that education is not yet there for the audience. I think if we do a little more on that, people would understand, hey, there is a query intent, and then there is the-- MARTIN SPLITT: That would be-- SANDHYA GUNTREDDY: --the document intent. MARTIN SPLITT: So we can sum it up into, like, rather than just looking at a number that a random tool gives you,  

#### [0:14:00](https://www.youtube.com/watch?v=y9GNFEne484&t=840) |  try to understand what your user needs

and what the intention is, and then serve that intention. SANDHYA GUNTREDDY: Yeah. I mean, it's just an education. People need to get to know that. MARTIN SPLITT: That is true. But we keep saying this for years and years on end. SANDHYA GUNTREDDY: Yeah. It's not yet landed this way, I would [INAUDIBLE].. MARTIN SPLITT: It's unfortunate. But I think we have landed a success in getting an overview of what the community brings to our tables and to share that we are not  

#### [0:14:30](https://www.youtube.com/watch?v=y9GNFEne484&t=870) |  different in that sense. We are basically

seeing the same kind of challenges. And we're seeing the same kind of recommendations. SANDHYA GUNTREDDY: And if you do the same stuff, all the search engines would pick up exactly the same stuff. The fundamentals are very, very similar. There could be some differences, but that's expected. MARTIN SPLITT: Exactly. The secret sauce is a little different. SANDHYA GUNTREDDY: But the fundamentals are the same across all search engines. MARTIN SPLITT: So hopefully people will get to the point of serving their users and have very nicely clean intent pages.  

#### [0:15:00](https://www.youtube.com/watch?v=y9GNFEne484&t=900) |  And, yeah, we are seeing more interesting

things coming in the future. SANDHYA GUNTREDDY: Yes. MARTIN SPLITT: Thank you so much for being here and talking about all of this with me. SANDHYA GUNTREDDY: Yeah, thank you so much, Martin, for inviting me. This is wonderful. MARTIN SPLITT: Absolutely, absolutely. SANDHYA GUNTREDDY: Thank you. MARTIN SPLITT: All right, in that case, thank you very much for joining us, and enjoy. Hey there! I hope you liked the video. This is my next guest, Alexis Sanders. And in the next episode, we will be talking about-- ALEXIS SANDERS: Crawl budget. MARTIN SPLITT: --crawl budgets. So stay tuned and check out the next one to learn more about what we have to say on the topic.  

#### [0:15:30](https://www.youtube.com/watch?v=y9GNFEne484&t=930) |  ALEXIS SANDERS: See you there, everyone. Ciao!

 