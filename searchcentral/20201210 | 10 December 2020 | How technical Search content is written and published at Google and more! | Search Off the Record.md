[![How technical Search content is written and published at Google and more! | Search Off the Record](https://i.ytimg.com/vi/RhTIYq_t5VU/maxresdefault.jpg)](https://www.youtube.com/watch?v=RhTIYq_t5VU)

## How technical Search content is written and published at Google and more! | Search Off the Record

In this episode, John, Martin, Gary, and special guest Lizzi Harvey, technical writer, deep dive into how technical Search content is written and published at Google, give an update on the planned Virtual Webmaster UnConference, and discuss dupe detection and canonicalization. Have a listen!



Transcript for this episode → https://goo.gle/3lHxCR5



Watch more Search Off the Record on YouTube → https://goo.gle/2JL3t5Y

Have a favorite way you like to listen to podcasts? Find Search Off the Record on most major podcast platforms → https://goo.gle/search-off-the-record



Google Search developer site → https://goo.gle/35HtREZ 

Search Off the Record on the Google developer Site → https://goo.gle/3qt1XGP



Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



Search Off the Record is a podcast series that takes you behind the scenes of Google Search with John Mueller, Gary Illyes, and Martin Splitt from the Search Relations team.



#SearchOfftheRecord



#### [0:00:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=0) |  [MUSIC PLAYING] JOHN MUELLER: Welcome, everyone, to

the next episode of the "Search Off the Record" podcast. Our plan is to talk a bit about what's happening at Google Search, how things work behind the scenes, and who knows, maybe have some fun along the way. My name is John Mueller. I'm a Search Advocate on the Search Relations Team here at Google in Switzerland, and I'm  

#### [0:00:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=30) |  joined here by Martin and Gary, who

are also on the Search Relations Team. But that's not all. We have Lizzi joining us here today! MARTIN SPLITT: Whee, Lizzi! Do you want to introduce yourself briefly? LIZZI HARVEY: Sure, my name is Lizzi, and I'm also on the team, and I work with John, Gary, and Martin. I'm a technical writer, which means that I help people write stuff down, and I work on the Search documentation. MARTIN SPLITT: So what does a workday look like when you're not writing technical documentation?  

#### [0:01:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=60) |  LIZZI HARVEY: Writing a lot of emails,

and responding to emails, and meetings-- MARTIN SPLITT: Meetings, oh yeah, we have-- LIZZI HARVEY: --like a normal person. MARTIN SPLITT: [CHUCKLES] Like a normal person. Well, I try to avoid meetings as much as I can. But I think I also saw you at events, right? We were at the PE Summit together a couple of years back, for instance, and you were at the Webmaster Conference in Zurich last year. So that's happening as well, right? LIZZI HARVEY: Yeah, sometimes I go to those. MARTIN SPLITT: And not just go to them, because I remember that you also led a session at the Virtual Webmaster Unconference. LIZZI HARVEY: Yes, well, I was there.  

#### [0:01:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=90) |  Lead the session? [LAUGHTER] MARTIN SPLITT: I

mean, you were a facilitator, weren't you? LIZZI HARVEY: Yes, I was there, and I facilitated the session. Yeah, that's true. MARTIN SPLITT: That's cool. Will you make an appearance in our Virtual Webmaster Conference that's coming up? LIZZI HARVEY: Maybe. When will that happen? GARY ILLYES: What's that? MARTIN SPLITT: Well, OK, so here comes a confession. I know that I said it's going to happen in December, but it's not happening in December anymore. We are probably doing it in January or February next year.  

#### [0:02:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=120) |  So yeah, that's the thing. But you

would love it. LIZZI HARVEY: Really? MARTIN SPLITT: Yeah, I know, it takes longer. But it takes longer because we want to run it across multiple time zones, and we want to have community speakers as well, so it'll be a little larger but really, really cool. And I might need your help. JOHN MUELLER: What are you going to do at the conference, Martin? Is it like the same thing as the Unconference again or-- tell me more. MARTIN SPLITT: [GROANS] OK, so it's not the same as the Unconference. The Unconference was a different format, which was pretty cool,  

#### [0:02:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=150) |  and Lizzi can probably testify to it

being very different from normal events, right? It felt different. LIZZI HARVEY: Yeah, it was different. MARTIN SPLITT: But it was nice. LIZZI HARVEY: It was a nice change, because we haven't been to an event-- or I haven't been to an event since this whole thing started, I guess since January. Or when was our last event in-person? MARTIN SPLITT: Yeah, I think it's just January, the last one. I think I was at a conference in February. LIZZI HARVEY: Yeah, I was nervous about it. I didn't think-- I wasn't sure how a virtual event would go, but it ended up being completely different from what I thought and a lot less stressful because it wasn't like a presentation  

#### [0:03:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=180) |  you had to prep-- MARTIN SPLITT: Yeah.

LIZZI HARVEY: --which is, like, a big reason why I don't like leading a session. [CHUCKLES] MARTIN SPLITT: But you did, and I hear that the session was great. And did you get the feedback that you needed? LIZZI HARVEY: Yeah. Yeah, I thought it was pretty helpful, and I wish that it was longer and more. MARTIN SPLITT: OK. So the good news is that we will do Virtual Unconference events next year as well, but this one is not an Unconference. This one is actually one where you have sessions where people are preparing presentations and giving presentations. But we also want to have, like, live Q&A,  

#### [0:03:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=210) |  and we want to encourage people to

have also some sort of interactive session. We'll have to see how these interactive sessions would look like, but it's basically like a larger event. I want to get Googlers from multiple time zones in as well. It's probably stretching across two or three days, and yeah, it's open for everyone. The Virtual Webmaster Unconference was limited in the number of people who could attend, because we needed to make sure that the discussions didn't go too big and were, like, unproductive. But this time, everyone can join, and it's a virtual event.  

#### [0:04:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=240) |  And if I can, I would like

to see a session from maybe John-- or if you want to emcee, that's also an option-- you know, just saying. And maybe Lizzi has something that she wants to contribute. And I know that I want Gary to do his Life of a Query, if possible. GARY ILLYES: No. MARTIN SPLITT: [SIGHS] JOHN MUELLER: Is this, like, the public pressuring place? MARTIN SPLITT: Yeah. JOHN MUELLER: [LAUGHS] OK. MARTIN SPLITT: I'm trying to basically get a public commitment from you all, but Gary put a stop to it.  

#### [0:04:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=270) |  LIZZI HARVEY: Hey, this is off the

record, right? You can't get us to commit on the record. MARTIN SPLITT: [SIGHS] Damn it, you've got me there. Ahh. GARY ILLYES: [MISCHIEVOUS CHUCKLE] MARTIN SPLITT: Oh, god. [CHUCKLES] That was-- GARY ILLYES: This was great. MARTIN SPLITT: That was well done, well done. GARY ILLYES: We should promote Lizzi. LIZZI HARVEY: [LAUGHS] MARTIN SPLITT: It definitely-- GARY ILLYES: This was fantastic. [LAUGHTER] MARTIN SPLITT: Public relations work, A plus. GARY ILLYES: You caught him. MARTIN SPLITT: Next level stuff. GARY ILLYES: This was amazing. MARTIN SPLITT: So Gary, why can't I have a Life of a Query session from you?  

#### [0:05:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=300) |  GARY ILLYES: Man, I really wish I

could do it, but I really don't want to. MARTIN SPLITT: [SIGHS] LIZZI HARVEY: Wait, that's all you have to say? You can just say, I really don't want to, and we'll leave you be? MARTIN SPLITT: Don't teach her that! Why are you teaching her that? LIZZI HARVEY: [CHUCKLES] MARTIN SPLITT: No. No, Lizzi, I will never step down just because someone tells me that they-- oh, come on! GARY ILLYES: OK, I love this episode already-- MARTIN SPLITT: [LAUGHS] GARY ILLYES: --because it appears that I can team up with Lizzi against you, and this is just amazing. MARTIN SPLITT: This is the worst day of my life.  

#### [0:05:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=330) |  What is happening? GARY ILLYES: Finally, I'm

not alone. We are two against one unicorn-- MARTIN SPLITT: John-- GARY ILLYES: --and this is amazing. MARTIN SPLITT: --help! [LAUGHS] JOHN MUELLER: So, Gary, why don't you tell us a bit about Life of a Query before the conference? MARTIN SPLITT: Yeah, basically do it now, and then you don't have to record it again. Come on, do it. GARY ILLYES: That's because the Life of a Query class, that's two hours long, and we don't have two hours. MARTIN SPLITT: Then, OK, so we had a bit of crawling. What's next? What's up next in the queue, basically? GARY ILLYES: Right, so we were talking about the indexing,  

#### [0:06:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=360) |  actually, not crawling. Somehow-- MARTIN SPLITT: Right.

True. No, we had crawling and indexing. We had both, right? GARY ILLYES: I think we silently skipped over crawling, which is really weird, but-- [LAUGHTER] --we can cover that at one point where, perhaps, there's something to announce there on Googlebot, or something interesting happens with Googlebot. And then we can cover how Googlebot actually works. So I don't think that we lost all that much, but we were talking about indexing and rendering, and we covered quite a bit about indexing.  

#### [0:06:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=390) |  Namely, we talked about content conversion. We

talked about collapsing, basically error page detection. You talked about rendering a little bit. We collected signals, and now we ended up with the next step, which is actually canonicalization and dupe detection. JOHN MUELLER: Wow, that's a big word. MARTIN SPLITT: Isn't that the same, dupe detection and canonicalization? Kind of? GARY ILLYES: Well, it's not because first you have to detect the dupes, basically cluster them  

![](https://i.ytimg.com/vi/RhTIYq_t5VU/maxres1.jpg)



#### [0:07:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=420) |  together, saying that all of these pages

are dupes of each other. And then you have to, basically, find a leader page for all of them. MARTIN SPLITT: Ah, right. GARY ILLYES: And that is canonicalization. So you have-- MARTIN SPLITT: True. GARY ILLYES: --the duplication, which is the whole term, but within that, you have cluster building, like dupe cluster building, and canonicalization. MARTIN SPLITT: Right, got it. GARY ILLYES: So for dupe detection, what we do is, well, we try to detect dupes.  

#### [0:07:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=450) |  MARTIN SPLITT: [SNICKERS] GARY ILLYES: And how

we do that is perhaps how most people at other search engines do it, which is basically reducing the content into a hash or checksum and then comparing the checksums. And that's because it's much easier to do that than comparing perhaps the 3,000 words, which is the minimum to rank, well, in any search engine. JOHN MUELLER: Wait, wait. 3,000? LIZZI HARVEY: What? GARY ILLYES: Oh, I said that?  

#### [0:08:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=480) |  MARTIN SPLITT: Gary. JOHN MUELLER: We have

some documentation in our developers' documentation that's not 3,000 words. Should we add some fluff? GARY ILLYES: Is it ranking well? No. See? JOHN MUELLER: It's always ranking well. Come on. LIZZI HARVEY: I think it's doing OK. GARY ILLYES: Yeah, I'm basically trolling. MARTIN SPLITT: So Lizzi, do you want to reconsider which side you're on? [LAUGHTER] LIZZI HARVEY: Yeah, he's throwing the documentation under the bus. What the heck, Gary? I thought we were on the same team. GARY ILLYES: We are. MARTIN SPLITT: Nope. GARY ILLYES: We totally are. MARTIN SPLITT: Gary is on his own team.  

#### [0:08:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=510) |  GARY ILLYES: Yeah, that's true. JOHN MUELLER:

OK, so 3,000 words-- is that, like, a real thing or did you just make that up? GARY ILLYES: No, I just made that up. That's bull crap. So we are reducing the content into a checksum, and we do that because we don't want to scan the whole text, because it just doesn't make sense, essentially. It takes more resources, and the result would be pretty much the same. So we calculate multiple kinds of checksums about the textual content of the page, and then we compare the checksums.  

#### [0:09:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=540) |  MARTIN SPLITT: Does that catch near duplicates

or only duplicates, exact duplicates? GARY ILLYES: Good question. It can catch both. It can also catch near duplicates. We have several algorithms that, for example, try to detect and then remove the boilerplate from the pages. So for example, we exclude the navigation from the checksum calculation. We remove the footer as well, and then you are left with what we call the centerpiece, which is the central content of the page.  

#### [0:09:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=570) |  MARTIN SPLITT: Kind of like the meat

of the page. That's where it's at. GARY ILLYES: Considering you're a vegetarian, yes. That's the meaty part of the page, yes. LIZZI HARVEY: These meat jokes again. I feel like that has been, like, the theme of the week, from John-- GARY ILLYES: It is. Yeah, Sundar sent a memo about this on Monday. MARTIN SPLITT: About meat jokes? GARY ILLYES: Yes, it's the meat jokes week. MARTIN SPLITT: Oh. GARY ILLYES: And notice he doesn't know if I'm serious or not. MARTIN SPLITT: We're all out of cheese, I guess. LIZZI HARVEY: Yeah, because I'm not checking those emails. [CHUCKLES] I guess I should go check. MARTIN SPLITT: [GASPS] GARY ILLYES: But he's the boss!  

#### [0:10:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=600) |  LIZZI HARVEY: Well-- MARTIN SPLITT: I mean,

what could you say, Gary? You filter all of those emails, right? GARY ILLYES: I do. [CHUCKLES] I don't even see his emails, because I filter them. MARTIN SPLITT: [LAUGHS] GARY ILLYES: And for context, for those listening and being very confused about the meat jokes-- like, this week, we had several meetings with the team, or members of the team, and somehow we always end up with joking about meat, even though we have several vegetarians on the team. MARTIN SPLITT: [LAUGHS] GARY ILLYES: But going back to our dupe detection,  

#### [0:10:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=630) |  when we calculate to the checksums, and

we compared the checksums to each other, then those that are fairly similar, or at least a little bit similar, we will put them together in a dupe cluster. LIZZI HARVEY: I have kind of a dumb question. What is a checksum, and why do you keep mentioning it? GARY ILLYES: So a checksum is basically a hash of the content, basically-- MARTIN SPLITT: A fingerprint. GARY ILLYES: --a fingerprint, yes. That is a better word. Basically, it's a fingerprint of something.  

#### [0:11:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=660) |  In this case, it's the content of

the file in case of, for example, zip files, like packages. It could be, again, the content reduced into a checksum so you can easily compare two different packages to each other, essentially. JOHN MUELLER: So from a practical point of view, it's basically-- you take all of the letters in the document, and you add them all together, and you come up with this really long number. And then you just compare the numbers instead of comparing the text. LIZZI HARVEY: Mhm.  

#### [0:11:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=690) |  JOHN MUELLER: So it's kind of a

simple way to have a fingerprint for the whole document. GARY ILLYES: Yeah. JOHN MUELLER: And you just compare the numbers. You don't have to look at the text anymore. LIZZI HARVEY: What if the document changes? Does it get a new number? MARTIN SPLITT: Then the number changes. GARY ILLYES: Yeah, and then basically, if the number changes, then the dupe cluster would be, again, different because the contents of the dupe cluster would be different because you have a new number in the cluster. So that would just go into another cluster, essentially, one that's relevant to that number.  

#### [0:12:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=720) |  And then once we've calculated these checksums

and we have the dupe cluster, then we have to select one document that we want to show in the search results. Why do we do that? We do that because, typically, users don't like it when the same content is repeated across many search results. And we do that also because our storage space in the index is not infinite. Basically, why would we want to store duplicates in our index  

#### [0:12:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=750) |  when users don't like it anyway? So

we can basically just reduce the index size. But calculating which one to be the canonical, which page to lead the cluster, is actually not that easy because there are scenarios where, even for humans, it would be quite hard to tell, like, which page should be the one that is in the search results.  

#### [0:13:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=780) |  So we employ, I think, over 20

signals. We use over 20 signals to decide which page to pick as canonical from a dupe cluster. And most of you can probably guess what these signals would be-- like, one is obviously the content, but it could be also stuff like page rank, for example, like which page has a higher page rank, because we still use page rank after all these years. It could be, especially on the same site, which  

#### [0:13:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=810) |  page is on an HTTPS URL, which

page is included in a sitemap, or if one page is redirecting to the other page, then that's a very clear signal that the other page should become canonical. There are canonical attributes that's also-- is it an attribute? Tag-- it's not a tag. MARTIN SPLITT: It's a tag, yeah. GARY ILLYES: No, it's not. JOHN MUELLER: Link. GARY ILLYES: It's a link, the link tag. MARTIN SPLITT: It's a link tag with a relation attribute-- canonical.  

#### [0:14:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=840) |  GARY ILLYES: Right. Now I'm confused. But

anyway, so the link rel canonical tag is quite a strong signal, again, because people-- or someone, specifies that that other page should be the canonical. And then once we've compared all these signals for all page pairs, then we end up with actual canonical, right? And then each of these signals that we use have their own weight. And we use some machine learning voodoo to calculate the weights for these signals.  

![](https://i.ytimg.com/vi/RhTIYq_t5VU/maxres2.jpg)



#### [0:14:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=870) |  But for example, to give you an

idea, like 301 redirect-- or any sort of redirect, actually-- should be much higher weight when it comes to canonicalization than whether the page is on an HTTP URL or HTTPS. LIZZI HARVEY: Why? GARY ILLYES: Well, because eventually the user would see the redirect target, so it doesn't make sense to include the redirect source in the search results.  

#### [0:15:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=900) |  JOHN MUELLER: So do we get that

wrong sometimes? Why do we need machine learning? Like, we clearly just write down these weights once and then it's perfect, right? GARY ILLYES: So that's a very good question. And a few years ago, I worked on canonicalization because I was trying to introduce hreflang into the calculation as a signal, and it was a nightmare to fine tune the weights manually because even if you change the weight by 0.1 number-- I don't think that it has a measure-- then it can throw off some other number.  

#### [0:15:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=930) |  And then suddenly, pages that, for example,

whose URL is shorter, might show up or more likely to show up in the search results, which is kind of silly because like, why would you look at that? Like, who cares about the URL length? So it was an absolute nightmare to find the right weight when you were introducing, for example, a new signal. And then you can also see bugs. I know that, for example, John escalates quite a bit to index dupes, basically,  

#### [0:16:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=960) |  based on what he picks up on

Twitter, or the forums, or whatever. And then, sometimes he escalates an actual bug where the dupes team says-- why are you laughing, John? You shouldn't laugh. This is about you. I'm putting you on the spot. You should appreciate this. But anyway, so then he escalates a potential bug, and it's confirmed that it's a bug, and it's related to a weight. Let's say that we use, I don't know, the sitemap signal to--  

#### [0:16:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=990) |  or the weight of the sitemap signal

is too high. And then, let's say that the dupes team says that, OK, let's reduce that signal a tiny bit. But then when they reduce that signal a tiny bit, then some other signal becomes more powerful, but you can't actually control which signal because there are like 20 of them. And then you tweak that other signal that suddenly became more powerful or heavier, and then that throws off yet another signal.  

#### [0:17:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=1020) |  And then, you tweak that one and,

basically, it's a never-ending game essentially, so it's a whack-a-mole. So if you feed all these signals to a machine-learning algorithm plus all the desired outcomes, then you can train it to set these weights for you and then use those weights that were calculated or suggested by a machine-learning algorithm. JOHN MUELLER: Are those weights also like a ranking factor? You mentioned, like, is it in the sitemap file?  

#### [0:17:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=1050) |  Would we say, well, if it's in

a sitemap file, it'll rank better. Or is canonicalization kind of independent of ranking? GARY ILLYES: So canonicalization is completely independent of ranking, but the page that we choose as canonical, that will end up in the search result pages, and that will be ranked, but not based on these signals. MARTIN SPLITT: Right. I mean, that was a lot of stuff, and I wonder if we should just, like, write this up somewhere. GARY ILLYES: That's probably not a bad idea.  

#### [0:18:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=1080) |  MARTIN SPLITT: Hmm? LIZZI HARVEY: Hmm. JOHN

MUELLER: So if we wanted to write that up, what would we need to do? It sounds like Gary has all of the inside information, and he's willing to share it off the record. What would it take to get it on the record? LIZZI HARVEY: Well, since it's Gary, I think he could write it down himself, maybe. First draft, yeah, yeah. GARY ILLYES: No! LIZZI HARVEY: Because I've seen him write some stuff, and I think-- first draft, pretty good. MARTIN SPLITT: But to be fair, I find it super hard to write the first draft.  

#### [0:18:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=1110) |  How do you get a draft started?

Because basically, I stare at an empty Google Doc, and it stares back into my soul. LIZZI HARVEY: [LAUGHS] Yeah, you and I have had conversations about this. MARTIN SPLITT: I know. LIZZI HARVEY: The blank page is just like the death of all writing. [LAUGHS] MARTIN SPLITT: [LAUGHS] LIZZI HARVEY: And one thing that can really help is talking about it with someone else and then kind of roughly banging out, like, a skeleton of what you want to say, so maybe start with headings, like I want to talk about this, then this, then this, and then maybe some  

#### [0:19:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=1140) |  notes under each one. And I guess,

like, before even that, maybe deciding what the point of the doc would be, so for Gary, like for this one that he was just talking about, would it be something that people will read to then do something else about it? Is there any action needed that they need to do? Or is it explaining a concept so that they can understand how something works? So first, kind of deciding what's the main point, and then that will determine the structure. JOHN MUELLER: OK, so basically Gary would come up with this idea, that we should  

#### [0:19:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=1170) |  document this, and then create a rough

draft and send it to you. And then, you just copy and paste it into the documentation and hit Publish. Or-- LIZZI HARVEY: No, I think there's a little bit more back and forth. [CHUCKLES] Probably we would talk about it first and then I would say, Gary, can you please write something down? And then he would write it down, and then I would look at it and make comments, probably in a Google Doc. And then we would queue it up to go into another review process for DevSite, because we have to check it in to our content  

#### [0:20:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=1200) |  management system. And then we would do

a final review, stage it, make sure it looks nice, and then we would publish it. And depending on what it is, we might want to promote it a little bit as well, maybe on Twitter or, like, a blog post, depending on if it's related to a feature or if it's just explaining a search concept. JOHN MUELLER: OK, cool. So basically, you'd work on the Docs draft with Gary first. And then, I guess he would turn it into an HTML page, or how does that work with the developer documentation?  

#### [0:20:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=1230) |  LIZZI HARVEY: Yeah, either me or Gary.

But since Gary knows what to do, I think he would do it. JOHN MUELLER: OK. LIZZI HARVEY: But yes, he would write in HTML, because that's how our content management system works. JOHN MUELLER: OK, cool. And then he would basically check it in like any source code file or-- LIZZI HARVEY: Yes. JOHN MUELLER: OK, cool. LIZZI HARVEY: Exciting stuff. [LAUGHS] JOHN MUELLER: And then the publishing part, I guess, is like just clicking a button or is there something fancy? LIZZI HARVEY: Yes. JOHN MUELLER: Just clicking a button?  

#### [0:21:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=1260) |  LIZZI HARVEY: No, it's not fancy. You

just click a button. So it used to be a little bit more complicated, where there were two steps where you had to manually publish, but the team that maintains the site that we publish on fixed that so it was automatic. So all you do is submit to the code base and then it pushes it, like, within a second. So you just click a button, submit, and then it's live. JOHN MUELLER: So cool. So basically, you would just publish anything that we would bring you, and nobody would check it or-- LIZZI HARVEY: No, no. JOHN MUELLER: No? LIZZI HARVEY: That's not true.  

![](https://i.ytimg.com/vi/RhTIYq_t5VU/maxres3.jpg)



#### [0:21:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=1290) |  That's a little-- [CHUCKLES] I would not

just publish anything. JOHN MUELLER: Could we do, like, a guest blog on the developer documentation, a guest blog post? LIZZI HARVEY: Well, I don't know how interesting that would be to people, but maybe if people want to know about it, then maybe. I think that that's also a good point is, like, that's something that I often push back on, people who want to just write something. Like, what is the point, and why, and will this help anyone? Or are you just putting this out there just to put it out there? Because if there's a pile of information and some of it  

#### [0:22:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=1320) |  is not useful, like, that's not helping

anyone. JOHN MUELLER: OK, so, well, I mean, obviously, it should be useful. That kind of makes sense. [LAUGHTER] LIZZI HARVEY: Yes. [CHUCKLES] Step one, make sure it's useful or interesting. JOHN MUELLER: OK, do you do anything afterwards? Like once it's live, is it basically just live forever? Or do you go back and review that from time to time? Do you ever get feedback on these things? How does that tend to work? LIZZI HARVEY: Yeah, so we have a feedback mechanism-- well, multiple feedback places where you can report things. So sometimes it's on Twitter, which  

#### [0:22:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=1350) |  we don't like because it's hard to

track what's going on. There's a button in the documentation where you can click Send Feedback, and then write to us about what is wrong or what you found confusing. Mostly, it's like negative stuff, but you could write in some positive stuff if you wanted to if it helps you. We like to know that. But mostly, it's like typo, or like, "I don't like this," and it goes into this queue for us to look at, and then we will revisit and fix it. JOHN MUELLER: Oh, cool. LIZZI HARVEY: It's really helpful if it is specific.  

#### [0:23:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=1380) |  So there's an option where you can

select, too, like, "This part of the page is confusing." So when people give us more context, then it's easier for us to know like, how can we improve this? JOHN MUELLER: OK, so it's not like this just giant black box where people go, and they complain, and nobody actually reads it. It's actually-- it goes to people, and they try to read it and figure out what to do. LIZZI HARVEY: Yeah, and the people are me and Gary. We are looking at everything. A lot of it is, like, weird stuff or not very helpful.  

#### [0:23:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=1410) |  GARY ILLYES: Oh, yeah. LIZZI HARVEY: [CHUCKLES]

I had an idea that maybe we could have a video where we just, like, read the bad feedback, like the Twitter bad tweets, mean celebrity tweets, because some of it is so aggressive, or just like, this is bad, I don't like it. And when you get feedback like that, it's like, well, what should I do differently if it's just bad? Like what about it? I need specifics to improve it. JOHN MUELLER: OK. GARY ILLYES: So I was thinking about that video, and I'm in, actually.  

#### [0:24:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=1440) |  MARTIN SPLITT: Awesome. LIZZI HARVEY: [CHUCKLES] JOHN

MUELLER: I kind of think, as the lead of the team, we should be careful with doing something like that. [LAUGHTER] LIZZI HARVEY: Too much public shaming. GARY ILLYES: Come on. JOHN MUELLER: I mean, we shouldn't be encouraging people to leave even worse feedback. I think getting more actionable feedback is always useful. But it sometimes feels like-- especially with a big company like Google-- if there's a feedback link, then it's easy to assume, oh, nobody actually reads it. But it sounds like the feedback that  

#### [0:24:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=1470) |  comes in for the documentation, that's actual

people behind it. So if you want something changed or if you're frustrated because, I don't know, you're trying to implement something and it's just not working, then it sounds like people should just leave more clear feedback. LIZZI HARVEY: Yeah, and I completely understand why people don't. I mean, it's work to write in a long story about why you had trouble with something. And it's much easier just to say like, bad, one star, we don't like it.  

#### [0:25:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=1500) |  And if I did get a big

pile of that for like one document, then I would look into it more and probably have to speak to some people, like, run a survey or something for that doc to find out, OK, well, more specifically, I'm seeing a lot of one-star reviews for this doc. Why is it doing so poorly? What can we do to fix it? And then more specifics can kind of help that along. JOHN MUELLER: That sounds pretty cool. Yeah, OK. LIZZI HARVEY: And then also the forum. Sometimes, things start-- I meant to mention that one.  

#### [0:25:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=1530) |  So there's Twitter, and the feedback funnel

into the docs, and then the forum. So sometimes, people will write in there, and we'll get bugs surfaced from that if something's wrong, like maybe incorrect, or out of date, or something like that. And then we'll fix it. JOHN MUELLER: Cool. What about, like, non-English content? Is that something where you also process that, or does that just go to translators directly? LIZZI HARVEY: We also process that. The feedback tool that we have, it will translate what they are saying. A lot of the feedback there is like, oh,  

#### [0:26:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=1560) |  you used this word when you should

have used this other word in this language. And it will translate that into English, which doesn't really make any sense because sometimes that auto-translate thing just makes it sound like the same word. But that's a signal for us to look into it deeper to report back like, hey, are we sure that this is the right word? And then talk to our localization experts about what we should do about that. JOHN MUELLER: So cool. OK. So I guess, if you want to complain about the documentation on Twitter, you should go to Gary  

#### [0:26:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=1590) |  and he will accept your feedback. But

better than that is just to give actionable feedback in the documentation directly so that-- GARY ILLYES: Wait, what? JOHN MUELLER: No? GARY ILLYES: I don't know how I feel about this. LIZZI HARVEY: No. MARTIN SPLITT: [SNICKERS] JOHN MUELLER: OK, fine, fine. Then maybe don't complain about it on Twitter to Gary. GARY ILLYES: Yeah, complain to John! Why me? JOHN MUELLER: To me? GARY ILLYES: Yeah! JOHN MUELLER: I'm too nice. I'm too nice. Nobody complains to me.  

#### [0:27:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=1620) |  GARY ILLYES: (SARCASTICALLY) Right, yeah. MARTIN SPLITT:

(SARCASTICALLY) Sure. JOHN MUELLER: OK, sometimes, sometimes, sometimes. OK, we should move on. Cool, OK, I think that helps a lot with the documentation, so that's something where it sometimes comes across as, like, it just magically appears and nobody really knows where it's coming from. And for the documentation, do you do all of the Search documentation or is it just a part? LIZZI HARVEY: Just a part, yeah. So when you say Search documentation, there's a couple of different angles there.  

#### [0:27:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=1650) |  So there's the one that's just for

everybody who's trying to use Search, so like web search kind of thing, like, how do I search for a job or a business near me? That's a different team. There's also the Search Console documentation, which there's a tech writer, Josh, who's on the Search Console team who documents stuff about how to use Search Console. And then I work on the developers.google.com Search documentation, which is a little bit more technical, I guess.  

#### [0:28:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=1680) |  JOHN MUELLER: OK, cool. We should talk

a bit about how the process works with getting new features documented and all of that, but maybe we can do that in one of the next episodes-- I don't know-- if we didn't scare you too much with this podcast. [LAUGHTER] Cool! OK, I think maybe we should take a break here. It's been fun doing this episode, having more people join in, and kind of more viewpoints. And yeah, I hope you, as a listener, you found this useful, and entertaining,  

#### [0:28:30](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=1710) |  and a bit insightful. And if you

like these, then, of course, let us know on Twitter or wherever you can give feedback for podcasts in general. And hopefully, we'll see you again. Or wait, wait, I always mess this part up. We'll hear you-- no, you'll hear us again in one of the future episodes. And, of course, to hear us again on a future episode, don't forget to subscribe. See you then. Bye, everyone. MARTIN SPLITT: Bye. LIZZI HARVEY: Goodbye.  

#### [0:29:00](https://www.youtube.com/watch?v=RhTIYq_t5VU&t=1740) |  GARY ILLYES: [NON-ENGLISH SPEECH] [MUSIC PLAYING] 

