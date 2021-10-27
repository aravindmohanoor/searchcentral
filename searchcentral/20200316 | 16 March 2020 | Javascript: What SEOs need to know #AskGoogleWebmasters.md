[![Javascript: What SEOs need to know #AskGoogleWebmasters](https://i.ytimg.com/vi/GdCBkX5mm2U/maxresdefault.jpg)](https://www.youtube.com/watch?v=GdCBkX5mm2U)

## Javascript: What SEOs need to know #AskGoogleWebmasters

In this episode of Ask Google Webmasters, John is joined again by Martin Splitt, Developer Advocate at Google, to discuss Javascript & SEO. Stay tuned as they answer questions, such as:



When using Rails Asset Pipeline for caching what status code do we give the old asset? Googlebot crawls these stale assets which we currently have 404'd. Do we 410 instead or keep the old assets alive for a couple months? It's killing our crawl budget? (submitted by @ruth_hearn77) (0:43)



In prerendering can we replace or skip irrelevant elements? I.e. svg bar graphs generated by JS? (submitted by @m_karg) (2:19)



If your site has a chat function that rewrites the title tag for notifications to the visitor, how do you or the app supplier prevent Google from indexing the JS rewritten version of the title tag? (submitted by @GOMaonaigh) (3:18)



In prerendering: can still be JS inside? JS that generates minor content layout changes, but not AJAX requests. (submitted by @m_karg) (4:00)



Will pre-rendering or dynamic rendering ever go away? (short discussion) (5:10)



Check out the JavaScript SEO playlist to deep dive into the SEO for JavaScript best practices → https://goo.gle/2RmKEG5



Relevant Google documentation:

Fix Search-related JavaScript problems → https://goo.gle/2VIh8Qs 

Implement dynamic rendering → https://goo.gle/2vm2mDe 

More on JavaScript rendering on the web → https://goo.gle/3cPVejg 



Send us your questions on Twitter with the hashtag AskGooglebot and your question might be answered! 

Google Search Central on Twitter → https://goo.gle/3f4Z0a8



Watch more AskGooglebot episodes → https://goo.gle/2OjWcvS

Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



#### [0:00:00](https://www.youtube.com/watch?v=GdCBkX5mm2U&t=0) |  [MUSIC PLAYING] JOHN MUELLER: All right, welcome

everyone to another special episode of "Ask Google Webmasters." [ROARS] MARTIN SPLITT: Today, we picked dinosaur t-shirts. JOHN MUELLER: Yeah, cool. MARTIN SPLITT: Yeah. JOHN MUELLER: Dinosaurs, because we like dinosaurs. MARTIN SPLITT: Yeah, we're into dinosaurs and scary topics. JOHN MUELLER: Scary topics, like JavaScript. MARTIN SPLITT: [LAUGHS] It's not scary. Come on. JOHN MUELLER: Not scary. All right, so in the Ask Google Webmaster series, Webmasters, SEOs, anyone really, can submit questions  

#### [0:00:30](https://www.youtube.com/watch?v=GdCBkX5mm2U&t=30) |  to us using the hashtag-- MARTIN SPLITT:

#AskGoogleWebmasters. JOHN MUELLER: Yeah. And today's topic is all about JavaScript, so let's get started. MARTIN SPLITT: All right. JOHN MUELLER: Ruth asks us on Twitter, when using the Rails Asset Pipeline for caching, what status code do we give the old asset? Googlebot crawls the stale assets, which we currently have 404'd. Do we 410 them instead? Or do we keep them alive for a couple of months? What do you think?  

#### [0:01:00](https://www.youtube.com/watch?v=GdCBkX5mm2U&t=60) |  I don't really know what a Rails

Asset Pipeline is, Martin. Can you tell us more? MARTIN SPLITT: To be fair, it doesn't really necessarily matter to the specific question, because it's pretty much the same for every asset that you've got and that you might update at some point. The Rails Asset Pipeline, however, is a way for rails to process and preprocess your assets as you have them in development for the production ready site. So it's basically like an automatic pipeline of dealing with your assets in your rails application. But what it boils down to is, you have old assets, you eventually have a new version of your website,  

![](https://i.ytimg.com/vi/GdCBkX5mm2U/maxres1.jpg)



#### [0:01:30](https://www.youtube.com/watch?v=GdCBkX5mm2U&t=90) |  and then you have new assets, like

some old JavaScripts, some previous version of your CSS, some images that you're no longer having on your page, stuff like that, right? So how do you deal with that? Well, you just keep it around for a while, until we recrawl your actual HTML content. And then we get the new assets afterwards. But because of caching, we try to make it so that we can crawl and index your page as quickly as possible. But that might mean that we're going to keep using outdated URLs.  

#### [0:02:00](https://www.youtube.com/watch?v=GdCBkX5mm2U&t=120) |  And if you 404 them, then we're

just going to end up with broken renders in between. And that's something you probably want to avoid. JOHN MUELLER: All right, so better to keep them around for a while. MARTIN SPLITT: For a while, mm-hmm. And you can use your server logs to figure out when we stop asking for these assets, and then just fully remove them. JOHN MUELLER: Cool. MARTIN SPLITT: Our next question comes from Michael. Michael is asking, if, in prerendering, can you skip or replace irrelevant content, like JavaScript generated SVG bar graphs, or anything else that is JavaScript generated really?  

#### [0:02:30](https://www.youtube.com/watch?v=GdCBkX5mm2U&t=150) |  JOHN MUELLER: From my point of view,

you should include everything, as much as possible, so that whenever Googlebot accesses your pages, it sees the full content. Does that kind of match? MARTIN SPLITT: Yeah. JOHN MUELLER: I'm not really sure. With prerendering, do they mean-- MARTIN SPLITT: Yeah, so they can either mean-- so prerendering really is just running your JavaScript on the server side once, whenever the content changes, and then deploying the static assets to everyone. In this case, no, you do not skip things.  

![](https://i.ytimg.com/vi/GdCBkX5mm2U/maxres2.jpg)



#### [0:03:00](https://www.youtube.com/watch?v=GdCBkX5mm2U&t=180) |  But if you mean dynamic rendering where

you would basically just give different content to the users, versus crawlers, then, even then I wouldn't skip it. JOHN MUELLER: Cool. OK, so include everything. Our next question comes from Graham. Graham asks on Twitter, if your site has a chat function that rewrites the title tag for notifications to the visitor, how do you, or the app supplier, prevent Google from indexing the JavaScript rewritten version of the title tag?  

#### [0:03:30](https://www.youtube.com/watch?v=GdCBkX5mm2U&t=210) |  MARTIN SPLITT: You don't, I would say,

no. So, as we are rendering the page, we are picking up rewritten titles. So, in that case, whoops. What you could do is you could hide or delay the chat behind the user interaction, because Googlebot doesn't interact with things. So if you have to click on the Chat button first, and then the chat pops up and then changes the title, I think that would be one way of dealing with this properly. Michael is asking, or asking again, in prerendering,  

#### [0:04:00](https://www.youtube.com/watch?v=GdCBkX5mm2U&t=240) |  can I still use JavaScript inside the

rendered output? Is it like JavaScript that generates minor content, or layout changes, or anything that isn't really heavy AJAX requests? JOHN MUELLER: Yeah, definitely. So with prerendering, you're basically generating those pages ahead of time and serving all of that to users. And it's perfectly fine to have some JavaScript elements in there as well. I think, from a user point of view, that makes sense anyway.  

#### [0:04:30](https://www.youtube.com/watch?v=GdCBkX5mm2U&t=270) |  Because sometimes, you can serve content very

quickly if it's prerendered. And you can use JavaScript to add interactive elements. And that's perfectly fine to mix that. So you don't have to strip out all of the JavaScript if you prerender your pages. MARTIN SPLITT: Absolutely. And also, if you do prerendering and then use something that is called hydration-- that's basically what you're aiming at-- you have all the content prerendered. And then you use JavaScript to enhance it into a single page [INAUDIBLE],, for instance, that is perfectly OK. It's just about giving the content to the user as quickly  

![](https://i.ytimg.com/vi/GdCBkX5mm2U/maxres3.jpg)



#### [0:05:00](https://www.youtube.com/watch?v=GdCBkX5mm2U&t=300) |  as possible. JOHN MUELLER: So it sounds

like JavaScript and SEO are going to be with us for a while, again. MARTIN SPLITT: I do think so, yes. JOHN MUELLER: Yeah. Well, that sounds pretty cool. So one of the things I keep hearing from people is, is prerendering or dynamic rendering, is that ever going to go away? Do I still have to bother with all of that? MARTIN SPLITT: Ah, yes. This question comes up a lot. So fundamentally, it will not necessarily go away entirely, maybe except for dynamic rendering. Dynamic rendering is a work around, so we hopefully do not have to keep that around for much longer. But server side rendering and prerendering  

#### [0:05:30](https://www.youtube.com/watch?v=GdCBkX5mm2U&t=330) |  are actually very fundamentally useful concepts, because

they give the users and crawlers the content quicker, right? It's HTML. We can parse that as it comes in. JavaScript needs to be parsed and executed to generate the content, so we cannot basically stream the content on the browser side. And we don't have to. We have server side rendering available. JOHN MUELLER: Wow. Yeah, it sounds like there's still a lot to do. Maybe we should do separate YouTube videos for that.  

#### [0:06:00](https://www.youtube.com/watch?v=GdCBkX5mm2U&t=360) |  What do you think, Martin? MARTIN SPLITT:

It's a great idea, and one we all ready have. If you're checking out this channel's playlists, you'll see that we have a series called JavaScript SEO already. It has a bunch of episodes that are covering many different topics already, but we are working on more episodes. So I guess, subscribe to this channel to stay tuned for more. JOHN MUELLER: Yeah, that sounds awesome. And feel free to continue submitting your questions using the hashtag-- MARTIN SPLITT: #AskGoogleWebmasters. JOHN MUELLER: All right. Thanks, for watching. And see you next time. MARTIN SPLITT: Bye.  

#### [0:06:30](https://www.youtube.com/watch?v=GdCBkX5mm2U&t=390) |  [MUSIC PLAYING]  
