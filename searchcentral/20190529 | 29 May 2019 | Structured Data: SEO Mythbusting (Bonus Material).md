[![Structured Data: SEO Mythbusting (Bonus Material)](https://i.ytimg.com/vi/Je6G4IUYcGI/hqdefault.jpg)](https://www.youtube.com/watch?v=Je6G4IUYcGI)

## Structured Data: SEO Mythbusting (Bonus Material)

In this bonus material from the filming of last week’s episode (Googlebot: SEO Mythbusting), Martin Splitt (WebMaster Trends Analyst, Google) and his guest Suz Hinton (Cloud Developer Advocate, Microsoft) dive into the topic of “new microformats”: structured data! 



Documentation mentioned in this episode:

Intro to structured data →  https://goo.gle/structured-data-intro 

Overview of supported structured data in Google Search →  https://goo.gle/search-gallery 

Structured data testing tool → https://goo.gle/2K9rTo5 

Rich results rest → https://goo.gle/30SEWA3 

Rich result status reports →  https://goo.gle/rich-results-report 



Next week, look forward to a new full episode - JavaScript: SEO Mythbusting.



Watch more SEO Mythbusting episodes → https://goo.gle/SEO-Mythbusting 

Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=Je6G4IUYcGI&t=0) |  [MUSIC PLAYING] SUZ HINTON: There is one

term that I'm going to mention to you just based on this is the reason why I had to submit the URL to be re-indexed. And that's microformats. MARTIN SPLITT: Oh! All right. SUZ HINTON: So can we talk about-- are they still a thing? I haven't really had to do a lot of SEO optimization for a while. And I knew microformats was such a huge thing because let's say you've got a product page and it has reviews on it and you want to show the little stars and all of that kind of rich content.  

#### [0:00:30](https://www.youtube.com/watch?v=Je6G4IUYcGI&t=30) |  And every time I made a tweak

and we deployed, I would have to then submit to get re-crawled and see if the results got more written. And that was definitely a very slow feedback cycle. MARTIN SPLITT: Yes. SUZ HINTON: So what is the state? Is microformat still a thing? And are there better resources out there right now for us to be able to pull that rich content out? MARTIN SPLITT: You're going to be very happy. And we have much better things. SUZ HINTON: Yay! MARTIN SPLITT: They are still a thing. But they are now called structured data. SUZ HINTON: Structured data. MARTIN SPLITT: And we are using JSON-LD, so  

![](https://i.ytimg.com/vi/Je6G4IUYcGI/hq1.jpg)



#### [0:01:00](https://www.youtube.com/watch?v=Je6G4IUYcGI&t=60) |  JSON for Linked Data. SUZ HINTON: Yeah,

this is all new terms to me. MARTIN SPLITT: Right. And you probably used literally the microdata attributes in HTML. SUZ HINTON: Yes. Yep, exactly. Yeah, we were using them. And they were very hit and miss. MARTIN SPLITT: Yes. SUZ HINTON: It was very easy to just mess up one tiny thing. And the validator didn't catch it. And then the stars would disappear. And we'd be like [GASP]. MARTIN SPLITT: And we have moved on from there. SUZ HINTON: OK, that's good. MARTIN SPLITT: So there is now-- schema.org is an open source organization where people can submit or discuss or change or do stuff with the semantic data  

#### [0:01:30](https://www.youtube.com/watch?v=Je6G4IUYcGI&t=90) |  that they want to put on the

web. SUZ HINTON: Got it. MARTIN SPLITT: And people that's participating-- there is much more semantic data out there than we are supporting in search results. But a bunch of it is supported in the search results. So for instance, if you have an event that we want to have showing up with the location and if you can get tickets and who is the performer and all that kind of stuff-- if you have a recipe where you might have an image or the instructions on how to make it or the time it takes to make it and reviews, how nice this recipe might be, articles, books, and TV  

#### [0:02:00](https://www.youtube.com/watch?v=Je6G4IUYcGI&t=120) |  series, all sorts of things, we have

documentation on that specifically as well. If you go to developers.google.com/search, you find all the supported types. And they show up nicely in the search results. So you get a little preview picture. And then you get the stars and all that kind of stuff. SUZ HINTON: Oh, this would have been amazing. MARTIN SPLITT: It's fantastic. And it's JSON. SUZ HINTON: Which is so much easier. MARTIN SPLITT: It's the script tags with JSON in it. It's so much easier. SUZ HINTON: It's just not little meta attribute things? MARTIN SPLITT: Correct, yes. So you have your JSON block. And we have what's called the Structured Data Testing Tool.  

![](https://i.ytimg.com/vi/Je6G4IUYcGI/hq2.jpg)



#### [0:02:30](https://www.youtube.com/watch?v=Je6G4IUYcGI&t=150) |  That is a little dated by now.

But it supports-- generally, basically everything that we know of shows up as either valid or invalid. And then we have the Rich Results Test, because the Structured Data Test, while being very generic, is also not very specific to what you want to achieve. You want to probably achieve the nice little stars showing up in the search results. This is what we call rich results. And there's the Rich Results Test for it. And that even gives you a preview of how that might look like in the search results. There's no guarantee that it does  

#### [0:03:00](https://www.youtube.com/watch?v=Je6G4IUYcGI&t=180) |  look like that in the search results

because people have been using it to spam stuff, like-- SUZ HINTON: Yeah, true. MARTIN SPLITT: I have a bazillion reviews. And then we're like, yeah, you just have some JavaScript generating fake reviews. That's not really-- SUZ HINTON: Well, how do you actually use the tool? Because I remember you used to have to dump your entire HTML file in there. MARTIN SPLITT: You [? don't. ?] [INAUDIBLE] SUZ HINTON: And if you did it too many times, you got timed out. MARTIN SPLITT: Right. SUZ HINTON: Yeah. MARTIN SPLITT: But that doesn't happen anymore. SUZ HINTON: Oh, OK. That's pretty exciting. MARTIN SPLITT: So you have two options. You can dump a URL in it, which is nice. And you can even use ngrok or something if you have a local--  

![](https://i.ytimg.com/vi/Je6G4IUYcGI/hq3.jpg)



#### [0:03:30](https://www.youtube.com/watch?v=Je6G4IUYcGI&t=210) |  SUZ HINTON: Oh, you could do local

host? MARTIN SPLITT: Yes. SUZ HINTON: Oh, this is very fancy. MARTIN SPLITT: Or you can even also still do like you dump your HTML in there. We execute the JavaScript. So if you're using JavaScript within that code dump, that's fine. SUZ HINTON: Oh, wonderful. MARTIN SPLITT: If you're running it-- yes. And you can basically live debug as you type. You press a button and it goes like, nope. And you're like, oh, damn it. And you get the feedback here. And it's like, missing performer for your event. And I'm like, OK, sorry, sorry. And you write it in. And then it reruns it. And you're like, OK, cool. This is what I want. And I can take it back to [INAUDIBLE] SUZ HINTON: That is awesome. MARTIN SPLITT: And yeah, we have that tool.  

#### [0:04:00](https://www.youtube.com/watch?v=Je6G4IUYcGI&t=240) |  We have Search Console that gives you

a live view of what happens on your page, also for structured data. Yeah, microdata is not that much of a thing. But the structured data is still going strong. SUZ HINTON: Well, it sounds like it's come a long way. That's very exciting. MARTIN SPLITT: It does. SUZ HINTON: If I'm ever working for a large retailer ever again, then I feel like I got this. MARTIN SPLITT: If you have a blog, add the article markup. You might get [INAUDIBLE] SUZ HINTON: Oh, so OK. I'm going to look at the schema for that. That would be like author and stuff. MARTIN SPLITT: And other sources might pull the data as well,  

#### [0:04:30](https://www.youtube.com/watch?v=Je6G4IUYcGI&t=270) |  right? It's an open source format. So

theoretically, voice assistance could use it as well. So just imagine if you have a recipe blog and then you stand in the kitchen, go like, hey, assistant thing-- whatever it is, whatever company you're choosing. There's a variety of options these days, right? And then the thing goes like yeah, Martin's apple pie. First step-- take some apples and peel them. And you're like oh, OK, fair enough. That can come from the structured data as well. So that's pretty cool. SUZ HINTON: That is really cool.  

#### [0:05:00](https://www.youtube.com/watch?v=Je6G4IUYcGI&t=300) |  I didn't even think of those use

cases. I just always thought about search results. [MUSIC PLAYING]  