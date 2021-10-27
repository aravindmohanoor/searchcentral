[![Improving Search Over the Years (WMConf MTV '19)](https://i.ytimg.com/vi/DeW-9fhvkLM/hqdefault.jpg)](https://www.youtube.com/watch?v=DeW-9fhvkLM)

## Improving Search Over the Years (WMConf MTV '19)

Paul Haahr, Distinguished Engineer for the Google Search Team, goes over how Search as a platform has improved over the years. Stay tuned to find out more about several case studies, the Google synonym system, emojis, and much more!



How Google Search works → https://goo.gle/2XjMQ47 



Watch all the recorded talks from WMConf MTV '19 → https://goo.gle/2QHcmy6 

Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral event: Webmaster Conference 2019; re_ty: Publish; product: Search Console - General; fullname: Paul Haahr;



#### [0:00:00](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=0) |  PAUL HAAHR: So I'm going to actually

talk a bit about how we improve things in Search. I'm going to go through a bunch of case studies. And I actually-- I put together a few. And I only realized after I put them together that all are in one way or another about language. And I think that really gets to how we think in Search about things, which is that language is really important to understanding what we do. So how do we think about ranking problems?  

#### [0:00:30](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=30) |  I could try to put together a

step by step methodology of what we do. But it would be a lie, because there isn't one. We have lots and lots of different ways we approach the problems we think about. And there's a lot of debugging and experimentation guesswork about what might work, evaluation to see if it does, research, both into what we know and what we can learn from academics and other industry publications,  

#### [0:01:00](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=60) |  and then just a lot of luck

and maybe stumbling upon something that works. And hopefully you'll see a bunch of examples of that throughout this. So here are some examples of things that we've done over the years. In some cases, I worked to create the problem that underlies this. In other cases, I worked on the solution. And in some cases, just work by other folks and I'm presenting it because it's a good story.  

#### [0:01:30](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=90) |  So I've first got to talk about

something-- about something in one of our language understanding systems, which is the synonym system. And so what is our synonym system? It's something that is there to bridge a gap between user vocabulary and query vocabulary, or user vocabulary and document vocabulary. That is, when we see a query, it often  

#### [0:02:00](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=120) |  is written in a different language than

the documents used. And we're trying to match those things. The way this actually works is, it looks a lot like we add a bunch of terms with OR. Who here in the audience has used the OR operator? You're experts, so there are probably a bunch. Not many people use it these days. Back in a sort of 2002, 2003, back in the AltaVista days, in the late '90s, you really needed to use OR a lot in your searches. And the way our synonyms system work is effectively,  

#### [0:02:30](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=150) |  we take a user query and we

add a lot of OR terms to it. And this is actually one of Google's most important ranking components, that it's sort of-- it's something that we launched roughly 15-plus years ago, has improved a lot over the years. I'll give you one example here, which is if you do the query "cycling tours in Italy," what we actually search for is cycling OR cycle OR bicycle OR  

#### [0:03:00](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=180) |  bike OR biking. Tours turns into tour

OR holidays OR vacation. The "in" I didn't mark up, but we actually allow-- that's what we call a stop word. So we're willing to drop it. And then Italy, we say Italy OR Italian. And you'll notice that bike holidays in Italian doesn't make sense to a reader. But Italian bike holidays might. So that's why that shows--  

#### [0:03:30](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=210) |  Italian shows up there. Now, these are

also-- synonyms are not just straightforward rewriting, because they're actually done in context of a full query. So in the context of truck, GM turns into General Motors. In the context of baseball, it turns into General Manager. In the context of various foodstuffs, it turns into Genetically Modified. And so there's a little bit of smarts in the system to try to understand not just an individual word  

#### [0:04:00](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=240) |  but a whole query. And I just

want to sort of make clear that this is not the same as something that's trying to provide synonyms for actual content, because this is not a thesaurus equivalent. Doesn't work that way. And it's really designed just to help you find good search results. So it's hidden behind the scenes mostly.  

![](https://i.ytimg.com/vi/DeW-9fhvkLM/hq1.jpg)



#### [0:04:30](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=270) |  There are some ways you can probe

at it. But mostly we hope that from an optimization perspective, you don't need to pay attention to it. From a user's perspective, you don't need to pay attention to it. And it's really unimportant whether these are actually synonyms to a human reader. One of the secrets of the synonym system is actually that for a long time-- I don't know if this is still true or in what context this is still true-- we considered buy and sell synonyms because if somebody was looking to buy something,  

#### [0:05:00](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=300) |  a page that was selling it was

actually good, and so on. But-- and this was one of the bugs-- in 2005, the top result for United Airlines was continental.com. Now before people say, but wait, didn't they merge? Yes, they did merge. It was 2010. We don't think it was our fault. We really hope it wasn't.  

#### [0:05:30](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=330) |  There were a number of bugs involved

in this. But the big one was that we were actually rewriting United Airlines as United or Continental Airlines or air or airline. There were some other things that sort of removed some safeguards. And those were my fault. The synonym system bug here was not my fault. And so how did we learn this? Or how do we fix this is actually--  

#### [0:06:00](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=360) |  we want algorithmic solutions. We did not

go in and say, OK, we're going to prevent this synonym from happening. We do not manually block these problems. We want something that scales. We want something that's going to attract or that's going to affect similar problems across the entire synonym system, and so on. So we want to look for patterns of failures. And so what we were doing here, we learned that, yes, people use United and Continental  

#### [0:06:30](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=390) |  in very similar ways, which is how

come our synonym system learned it. That is, they are interchangeable if you look at-- if you look at words as the meaning of words is defined by their context, which is the sort of linguistic notion or philosophical notion of how you understand the meaning of words. But occasionally when you do this, you will find what we call siblings,  

#### [0:07:00](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=420) |  which are two words that serve similar

roles but aren't at all interchangeable. And rival siblings is something that happens a lot. So how do we solve this? And again, we started looking at the searches that people were doing. And it turns out that people compare synonyms-- compare siblings to each other. So we actually looked through our query stream and looked for things where people were comparing United versus Continental or Cannon  

#### [0:07:30](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=450) |  versus Nikon or Beatles versus the Stones

and said, these things are actually bad synonyms. And it turns out that was the beginning of a sort of solution to this one. The only problem with it was-- and it worked. And we learned that we had been synonymizing cat to dog. And we learned that we had been synonymizing part time to full time. And these were all bad things to do. But in the process of fixing this,  

#### [0:08:00](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=480) |  we also lost some really good synonyms.

We learned that sign in and sign on were siblings in some sense, probably because people were comparing the usage of those two words. And that address and contact, which are actually really good synonyms to have in a whole bunch of places, were bad synonyms. So this sort of process of looking at the data, running some experiments, evaluating the results, and repeating and repeating, gets us to a point where we're happy with the trade-off between what  

#### [0:08:30](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=510) |  this helps us with and what this

hurts us with. And so where I summarize this one or generalize from this one is that understanding patterns of failures can be very useful in fixing your problems like this. I think the rigor of not doing manual patches over algorithmic problems and looking for algorithmic solutions really helps us keep things general.  

#### [0:09:00](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=540) |  And this is just sort of an

example of where-- one of the places where we did that. And we have these issues multiple times every day where it's like, oh, this is one little stupid thing. Shouldn't we just fix it? And the answer tends to be no. And we tend to be pretty rigorous about that. But then also the side of, every change we do has wins and losses. And [? Feroze ?] is in the back, one of the ranking leads. And he'll tell you that if you get a 6 to 5 win-loss ratio, you're really happy. So understand that everything we do  

![](https://i.ytimg.com/vi/DeW-9fhvkLM/hq2.jpg)



#### [0:09:30](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=570) |  is sort of approximate and probabilistic like

that. Another thing I'm going to talk about-- next example I want to talk about is something called non-compositional compounds. So I'll get to what that means in a second. But I want to just point out that the original version of this was actually done by Ben Gomes, who's currently the SVP who leads Search. So he was a working engineer at one point, at least. So information retrieval, which is sort of the basic area  

#### [0:10:00](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=600) |  that I work in, that Google Search

is based on, core underpinning of all sorts of-- all search engines, really, is mostly about matching and counting words, and things like, are the words in the title or the body? Are the words in links? What is the frequency in which they occur? And things like that. And you have to understand, that's where everything starts. And so relevance just comes from matching words. So consider these pages and the query "New York hotels."  

#### [0:10:30](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=630) |  Oh, I should mention a little notational

thing. I put queries in brackets because that's our internal convention. So if you see something in square brackets, that means it's a query. So these are pages that Google, at least today, thinks are good for New York hotels. And you might be able to recognize them or not. And again, you have title hits. You have body hits. You have links, et cetera. They mention the words the right amount,  

#### [0:11:00](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=660) |  all these things, and nothing surprising there.

And now the question is, are these pages good for York hotels? And if they're not, why not? Because they say York every time they say New York. And they've got all the same counts and frequencies and so on. And this is where I'm going to introduce actually what the notion of compositional and non-compositional compounds are. So a compositional compound is a phrase of two or more words  

#### [0:11:30](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=690) |  where the words in the phrase have

the same meanings inside the compound or inside the phrase as they do elsewhere in their conventional meanings. And a non-compositional compound is one where the meanings differ. And so New York is non-compositional. And the observation is that even though it's formed by compounding New and York-- and at one point, the city was named after the city of York-- there's nothing really York-related  

#### [0:12:00](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=720) |  now. But you should note that not

all place names follow the same rule. You don't talk about New York as York. But you do talk about Vegas as-- or Las Vegas as Vegas. You do talk about New Jersey as Jersey. So it's not like this is a rule about place names. There's something more specific going on. And the question was, could we figure that something out? And here is what we built. We started  

#### [0:12:30](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=750) |  with a set of two word phrases.

There are three word non-compositional compounds. Turns out not to be as much of a problem. Look at pages where they occur. If on a lot of those pages only one of the underlying words appears, you probably have a non-compositional compound. You need to get the counts right and the ratios right. But for New York, New appears alone on a lot of those pages.  

#### [0:13:00](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=780) |  People will talk about a new thing

in New York. But "York" appears alone on very, very few of those pages. And you can look at the ratios there and you can look at the ratios on compositional compounds and they're very, very different. And that lets you distinguish them. And then what do we do once we have non-compositional compounds? Well, we actually built sort of something special into our retrieval system that says,  

#### [0:13:30](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=810) |  if you see York hotels because York

is part of this non-compositional compound, don't match York if the word to the left of it is New. And it's this really funky thing that we actually didn't realize we needed in the system. But it turns out-- it turned out to be useful. So note that this is a very-- so some lessons here. First of all, this is an edge case. It is very, very hard to predict it in advance if you do an information retrieval system that you're going to have this problem until you've  

#### [0:14:00](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=840) |  seen the problem. And then once you've

seen the problem, you can't unsee it. You can't forget it. Once seen, it's actually pretty obvious that there's a general pattern here. Here are a couple of other ones where this actually-- where the solution triggers today in ranking. Fantasy game is not Final Fantasy. View office is not Mountain View. And we have problems with both of those. If you turn this system off, we actually get those wrong.  

![](https://i.ytimg.com/vi/DeW-9fhvkLM/hq3.jpg)



#### [0:14:30](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=870) |  So the hard work here-- it's done

all offline. It's done all by looking at sort of building a language model to understand what are the phrases in this category. And then there was a very small change in how our code works at serving time to support this. One more example. So I said that these three talks or these three examples  

#### [0:15:00](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=900) |  are about language. This is a way

that probably people don't think of language as evolving. But if somebody had sent you the rolling on the floor laughing emoji in 1996, would you have known what it meant? And I'm going to bet probably not, because emoji didn't appear till the next year. Who here has not used an emoji today in a text? Anyone? A couple of us.  

#### [0:15:30](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=930) |  Or received one? OK. So I'm not

the only old person in the room. People use emoji all the time. People actually use emoji a lot without knowing what they mean. And so they search for emoji and try to figure out what they mean. And of course, that would be our job.  

#### [0:16:00](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=960) |  Unfortunately, for a very long time, we

completely ignored emoji and all other special characters because nobody searches for them. And it is actually expensive to index them if they're not searched for. One of our biggest costs is the amount of storage used in our index and how we manipulate the index as we build it.  

#### [0:16:30](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=990) |  So we just didn't have any information.

So if you searched for a smiley face, we just didn't find anything. If you search for a smiley face and the word smiley face, it sort of worked. We returned what the words "smiley face" returned. And most of the time, that worked. If you searched for smiley face and meaning, we found dictionaries. And I guess you could look up emoji in some of those dictionaries. And that would maybe sort of work. But it wasn't a great experience.  

#### [0:17:00](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=1020) |  So there were sort of two reasons

why this ended up being a very difficult thing for us to do. First is, changes to actually what we index are incredibly difficult for us to pull off logistically. And it's that we first have to update indexing to allow emoji. Then we have to wait for all the documents in the index, or enough of them, to be re-indexed. And then we change how queries are handled. But first, we actually have to make the argument  

#### [0:17:30](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=1050) |  that it was worth it to do,

because again, big expense. Lots of process in changing things. And the argument that we actually ended up making was, people are searching for emoji greater than a million times a day, even though it doesn't work. And eventually that argument worked. So we did this. It took literally over a year to do.  

#### [0:18:00](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=1080) |  After the data was in the index,

we fixed query parsing. We ran some evaluations. And there were some very negative results. And it turned out there were lots of other systems that needed to be updated before we launched. Link processing didn't know how to deal with these things. So a link to a site that used an emoji-- we didn't see the emoji. We didn't see the text. It was all bad. Spelling-- if it's on emoji in the query, it thought, this is just garbage. We're going to drop the whole thing.  

#### [0:18:30](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=1110) |  Autocomplete didn't know about emojis, and so

on. So it took actually just time going through dozens of systems and making sure they were ready to deal with this data and fixing them and so on. While we were at it, we actually fixed it for math symbols. Someone else added punctuation. So there's actually more than just emoji. It does work. You can search for emoji today. The points I'd make here are, things  

#### [0:19:00](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=1140) |  which look easy from the outside can

be a lot of work to implement. And those stupid assumptions you bake into your code 20 years ago, they will come back and bite you. And nobody thought about emoji when we started this process. Anyway-- and by the way, this was the search emoji team out on our launch celebration lunch. So that is what I was going to talk about.  

#### [0:19:30](https://www.youtube.com/watch?v=DeW-9fhvkLM&t=1170) |  [MUSIC PLAYING]  

