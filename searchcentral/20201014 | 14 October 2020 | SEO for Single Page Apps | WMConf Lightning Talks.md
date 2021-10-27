[![SEO for Single Page Apps | WMConf Lightning Talks](https://i.ytimg.com/vi/l-JWN2x_Na0/maxresdefault.jpg)](https://www.youtube.com/watch?v=l-JWN2x_Na0)

## SEO for Single Page Apps | WMConf Lightning Talks

Martin Splitt, Developer Advocate at Google, goes over how to ensure your Single Page App is discoverable via Google Search. He also explains what a Single Page App is and what to look out for when building them.



Useful resources:

JavaScript SEO basics guide → https://goo.gle/js-seo-basics

Google Search testing tools → https://developers.google.com/search/tools

Fixing JavaScript issues in Search → https://developers.google.com/search/docs/guides/fix-search-javascript 



Watch all WMConf Lightning Talks → https://goo.gle/2VclBJz

Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



#SearchLightningTalks #SEO #webdev



#### [0:00:00](https://www.youtube.com/watch?v=l-JWN2x_Na0&t=0) |  Hello, and welcome to another Webmaster Conference

Lightning Talk-- this time, as you can see, recorded from home. In this video, we will discuss how to make sure that your single-page application is discoverable via Google Search. ♪ [music] ♪ Before we dive in, let's recap what a single-page application actually is. Unlike a regular website, a single-page app uses JavaScript  

#### [0:00:30](https://www.youtube.com/watch?v=l-JWN2x_Na0&t=30) |  to control the page's life cycle. JavaScript

is typically used to create the HTML that creates the page. It also uses JavaScript to load other content when users are navigating to other parts of the single-page application. These are often called views rather than pages. This technique allows us to load views without the browser doing a full reload and allows us to use custom transitions between the different parts of the application.  

#### [0:01:00](https://www.youtube.com/watch?v=l-JWN2x_Na0&t=60) |  Single-page apps might use an architectural pattern

called the app shell model, where the shared parts of the UI in code, like menus, headers, footers, and so on, are loaded when initially loading the single-page application. And the different views are dynamically loaded into this shell, reducing the amount of data needed to send over the network. Okay. So what do we need to look out for when building single-page apps?  

![](https://i.ytimg.com/vi/l-JWN2x_Na0/maxres1.jpg)



#### [0:01:30](https://www.youtube.com/watch?v=l-JWN2x_Na0&t=90) |  I think it is time to look

at our sample app, test it, and then improve it where we see potential. Our example application is an e-commerce web app-- a cheese shop. You can browse different product categories, learn more about a specific product, and you can put it into your cart. It also uses the user's location to display prices in the local currency.  

#### [0:02:00](https://www.youtube.com/watch?v=l-JWN2x_Na0&t=120) |  When we run the mobile-friendly test, there

is a bit of an issue. The main content doesn't show up. Time to investigate this. In the JavaScript console messages, we can see that there is a problem with our code. We are incorrectly using an unsupported feature. That's an important point here. Sometimes, we do forget that code doesn't always take the happy path. In our example, we assume that we always get the user location.  

#### [0:02:30](https://www.youtube.com/watch?v=l-JWN2x_Na0&t=150) |  But we forgot to deal with situations

where that isn't available. It's important to make sure that you cover all code paths to avoid these scenarios. Googlebot, for example, declines the request for the geolocation. I also noticed something else when using the shop. It does not change the URL when navigating between different views.  

![](https://i.ytimg.com/vi/l-JWN2x_Na0/maxres2.jpg)



#### [0:03:00](https://www.youtube.com/watch?v=l-JWN2x_Na0&t=180) |  But as Googlebot uses URLs to locate

these different "pages," or views in our case, this would mean that Googlebot would only see our homepage and nothing else. To fix this, we can use the history API and proper link markup with href attributes to expose the other views as URLs within the links. It's also a good idea to take a look at the titles and meta descriptions for our different views. Right now, all views have the same generic title and meta description.  

#### [0:03:30](https://www.youtube.com/watch?v=l-JWN2x_Na0&t=210) |  This isn't really helpful when people are

searching for the one specific product or a specific category in our shop. With a little bit of extra JavaScript, we can fix this quite quickly. [swishing sound] Ah, nice! This will look much better in the search results. A very common problem is the way that single-page applications are dealing with error scenarios, such as invalid URLs.  

#### [0:04:00](https://www.youtube.com/watch?v=l-JWN2x_Na0&t=240) |  In our example, the application displays an

error message, but the server reports an HTTP 200. That is a bit of an issue, specifically, in single-page applications because the server doesn't really do the error handling anymore. Usually, the server serves the web app in all cases, and then the JavaScript and the browser decides if it wants to display an error. But HTTP status codes do help Googlebot and browsers  

![](https://i.ytimg.com/vi/l-JWN2x_Na0/maxres3.jpg)



#### [0:04:30](https://www.youtube.com/watch?v=l-JWN2x_Na0&t=270) |  decide how to deal with the response.

So we should fix this. Here's the JavaScript that deals with the error situation. It reads the URL and fetches the data, and if that fails, it displays an error message. But we can't just tell JavaScript to report a different status code because this status code can't be changed once the server sent it.  

#### [0:05:00](https://www.youtube.com/watch?v=l-JWN2x_Na0&t=300) |  What we can do, though, is to

configure our server to respond with an error code for a specific URL, like /not-found gives a 404 and /maintenance gives a 500, and so on. When we do that, we can use JavaScript to redirect to the designated error URL. This signals to the browsers and Googlebot that the page is just a redirect to another URL,  

#### [0:05:30](https://www.youtube.com/watch?v=l-JWN2x_Na0&t=330) |  and this URL is an actual error.

Alright, now our webshop can be crawled and indexed, gives useful product information and search result pages, and behaves properly when there is an error. If you are interested in learning more, do check out the links for a tutorial, our documentation, the JavaScript SEO video series,  

#### [0:06:00](https://www.youtube.com/watch?v=l-JWN2x_Na0&t=360) |  and like and subscribe if you want

to see more videos like this. Thanks for watching. Have a great day. Bye. ♪ [music through to the end] ♪  