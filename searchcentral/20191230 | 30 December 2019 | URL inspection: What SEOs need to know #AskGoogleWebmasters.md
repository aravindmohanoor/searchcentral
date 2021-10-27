[![URL inspection: What SEOs need to know #AskGoogleWebmasters](https://i.ytimg.com/vi/YofKLvX2t8I/maxresdefault.jpg)](https://www.youtube.com/watch?v=YofKLvX2t8I)

## URL inspection: What SEOs need to know #AskGoogleWebmasters

In the last episode of Ask Google Webmasters this year, John is joined again by Martin Splitt, Webmaster Trends Analyst at Google, as they discuss questions around rendering and URL inspection in Google Search Console, such as:

- According to the Google Search Console screenshots, Googlebot seems to be rendering only a part of our pages - is it just the screenshot or is there something faulty one needs to worry about? (submitted by @Balgev) (0:30)

- Why does Google Search Console tell me there is a .js error when I use arrow functions? (submitted by @l0c4lh057) (1:40)

- Why does the URL inspection tool report a status code 200 for a page that returns a 301 redirect? (submitted by @merlinox) (2:05)

- About making code changes to the URL inspection tool (3:05)



About the URL inspection tool → https://goo.gle/2ZrJsp9 



Send us your questions on Twitter with the hashtag AskGooglebot and your question might be answered! 

Google Search Central on Twitter → https://goo.gle/3f4Z0a8



Watch more AskGooglebot episodes → https://goo.gle/2OjWcvS

Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=YofKLvX2t8I&t=0) |  [MUSIC PLAYING] JOHN MUELLER: All right. Welcome,

everyone, to today's special episode of "Ask Google Webmasters." Here today with a special guest-- Martin. MARTIN SPLITT: Hi, everyone, and thanks for hosting us, John. JOHN MUELLER: Oh, it's great to have you here. So in the "Ask Google Webmaster," series we take questions that were submitted on Twitter using the hashtag #AskGoogleWebmasters. Today's questions are on the topic of Search Console. So let's get started.  

#### [0:00:30](https://www.youtube.com/watch?v=YofKLvX2t8I&t=30) |  Gev asks, "Googlebot seems to be rendering

only a part of our pages according to the search console screenshots, even after the recent evergreen Googlebot update. Question-- is it just the screenshot, or is there something faulty that I need to worry about?" MARTIN SPLITT: That's a good question, and in order to not just answer with it depends, let me go a little bit into more details. So if it's content that you care for, that is really important to you, you should make sure that it's actually rendered. But you should also check the rendered HTML source code  

![](https://i.ytimg.com/vi/YofKLvX2t8I/maxres1.jpg)



#### [0:01:00](https://www.youtube.com/watch?v=YofKLvX2t8I&t=60) |  if it's not in the HTML because

maybe sometimes it's in the HTML. It's not showing up on the screenshot because it's below the fold or something. So make sure that it's in the DOM in the source code that we show as rendered source code. And, also, sometimes things just go wrong, so try, try again, I guess. JOHN MUELLER: So if it's below the fold, would it just not be shown but still be used for indexing? MARTIN SPLITT: Yeah. Yeah. It's just we have to cut the screenshot somewhere,  

#### [0:01:30](https://www.youtube.com/watch?v=YofKLvX2t8I&t=90) |  so we're going to cut it where

normally-- especially if it's a mobile crawler, where the screen for a mobile phone would end. JOHN MUELLER: Cool. Thanks. MARTIN SPLITT: All right. Our next question comes from Twitter user Twitter Inofficial, and they ask, "Why does Google Search Console always tell me that there's a JavaScript error when I use arrow functions? Why does it not support them?" JOHN MUELLER: Well, that's an easy one, so thanks for asking me that question, Martin. The short answer is we support them now.  

![](https://i.ytimg.com/vi/YofKLvX2t8I/maxres2.jpg)



#### [0:02:00](https://www.youtube.com/watch?v=YofKLvX2t8I&t=120) |  MARTIN SPLITT: Ta-da. JOHN MUELLER: So if

you try again, it'll probably work. For our last question, @merlinox on Twitter asks, "Why does the URL Inspection tool report a status code 200 for a page that absolutely returns a 301 redirect? Nowhere in Search Console does there appear any indication that the URL tested gives a 301." MARTIN SPLITT: That's correct, yes. The reason behind that is that the URL Inspection tool is designed to show you what happens when we index pages, right?  

#### [0:02:30](https://www.youtube.com/watch?v=YofKLvX2t8I&t=150) |  And what happens when we get a

301? We make a new request to the URL that you redirected us to. So we are not ending up with a 301. We are ending up with whatever happens on the page that you redirected us to-- in that case, a 200. And that's by design basically because the URL Inspection tool, as I said, is meant to show you what actually happens when Googlebot processes your website. JOHN MUELLER: So I can see how that might confuse someone  

![](https://i.ytimg.com/vi/YofKLvX2t8I/maxres3.jpg)



#### [0:03:00](https://www.youtube.com/watch?v=YofKLvX2t8I&t=180) |  who has double-checked the result code, but

that definitely makes sense. So all of these are about the URL Inspection tool, which is a cool part of Search Console. I heard you even made some code changes there. Is that correct? MARTIN SPLITT: I did. Yes, that is correct. I made a tiny little change in the code. JOHN MUELLER: Wow. So what's involved there? Can I just go in there and add a bunch of images of cheese, or is someone actually watching out for-- MARTIN SPLITT: There are people watching out. So I work with a team. We agreed on building a certain feature, and then they guided me through the process of making  

#### [0:03:30](https://www.youtube.com/watch?v=YofKLvX2t8I&t=210) |  that feature actually happen. I wrote the

code. They made sure that it's tested properly, and we are now running what's called an experiment. So, basically, new features are undergoing the testing phase first, and only if I pass that testing phase my code will actually run for your inspections in Google Search Console. So you can't just add new stuff to it or break existing things. JOHN MUELLER: Wow. On the one hand, I'm kind of sad I just can't add pictures of cheese, but on the other hand, it's good to know that we're sending tools that actually  

#### [0:04:00](https://www.youtube.com/watch?v=YofKLvX2t8I&t=240) |  work to our users. [LAUGHTER] MARTIN SPLITT:

Yes. JOHN MUELLER: I hope you found these answers useful. Thank you for submitting them all. If there are more questions on the topic of Search Console or anything else, feel free to submit them on Twitter using the hashtag-- MARTIN SPLITT: #AskGoogleWebmasters. JOHN MUELLER: All right. Thanks, everyone. Thank you, Martin. And goodbye. MARTIN SPLITT: Thank you. Bye. [MUSIC PLAYING]  