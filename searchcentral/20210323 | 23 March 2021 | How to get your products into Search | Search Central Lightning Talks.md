[![How to get your products into Search | Search Central Lightning Talks](https://i.ytimg.com/vi/UQtdv_hoGuM/maxresdefault.jpg)](https://www.youtube.com/watch?v=UQtdv_hoGuM)

## How to get your products into Search | Search Central Lightning Talks

Do you want to drive more search traffic to your ecommerce site? 

Alan Kent, Developer Advocate at Google, describes the benefits of providing Google with your product data and shares the technical best practices for achieving it.



Free product listings on Google → http://goo.gle/30raj5N

Product structured data → http://goo.gle/3qchTLY

Create a feed → http://goo.gle/3sGRF66

SEO for ecommerce (Search Console Training video) → https://youtu.be/lB-E6060se0



00:00 Intro

00:27 Where does Google display product information?

01:39 The evolution of products on Google

3:43 Why is product data different?

4:31 Using structured data

5:00 How to get product data into Google Merchant Center

8:26 Key takeaways



Watch all Search Central Lightning Talks → https://goo.gle/2VclBJz

Subscribe to the Google Search Central Channel → https://goo.gle/SearchCentral



#ecommerce #seo #SearchLightningTalks



#### [0:00:00](https://www.youtube.com/watch?v=UQtdv_hoGuM&t=0) |  Do you want to increase traffic from

Google to products on your e-commerce site, for free? My name is Alan Kent. I'm a Google Developer Advocate specializing in e-commerce. In this Google Search Central Lightning Talk, I'm going to describe the benefits of providing Google with timely and accurate product data, as well as technical best practices to achieve it. Let's dive in. ♪ [music] ♪ First, let's look at the main ways  

#### [0:00:30](https://www.youtube.com/watch?v=UQtdv_hoGuM&t=30) |  we show your product data. Google Search

uses special formatting for products in search results to assist shoppers on their purchasing decisions. This can include: ratings, reviews, pricing, and stock levels. Google Images also uses product information when available. If Google knows how to display an image for a product, it may display additional badging and product information with the image, such as whether the item is currently in stock.  

#### [0:01:00](https://www.youtube.com/watch?v=UQtdv_hoGuM&t=60) |  If you visit the Google Shopping tab,

products are listed with richer information. The Google Shopping tab provides additional tools to help shoppers on their shopping journey, such as filtering by price range or brand. Finally, Google Maps can also show products available nearby if you provide Google information about where your inventory is located. This helps shoppers wanting to pick up purchases in person. While these are the most well-known services  

#### [0:01:30](https://www.youtube.com/watch?v=UQtdv_hoGuM&t=90) |  for a product to show up on

Google, there are others, and we're always exploring new opportunities. Product data is not new to Google, although its usage has evolved over the years. Let's take a quick look back down memory lane to understand the evolution of products on Google. Google Search was first launched back in 1998. Originally, Google bot would crawl the web, looking for pages, making the content available via Google Search.  

![](https://i.ytimg.com/vi/UQtdv_hoGuM/maxres1.jpg)



#### [0:02:00](https://www.youtube.com/watch?v=UQtdv_hoGuM&t=120) |  By 2002, Google's already identifying products on

web pages. To improve accuracy of the data captured, you could also provide a product data feed directly to Google for indexing. Moving forward to 2010, Google's offerings were more sophisticated. Structured data allowed website owners to more accurately convey product data to Google from inside web pages. Google Merchant Center was launched to capture product data,  

#### [0:02:30](https://www.youtube.com/watch?v=UQtdv_hoGuM&t=150) |  which was then fed into multiple paid

experiences, such as product listing ads in Google Search, display ads in the Google Display Network, and the Google Shopping tab. Typically, you'd only share product data for products you wanted to promote on Google services. This changed in 2020 with the introduction of several free offerings. First, Google now makes it free to participate in the Google Shopping tab.  

#### [0:03:00](https://www.youtube.com/watch?v=UQtdv_hoGuM&t=180) |  They're still paid experiences, but your products

can be listed for free, increasing your products' exposure to shoppers. In addition, product data from Google Merchant Center is also fed into organic search. This helps Google present your products more accurately to shoppers in organic search. This means it now makes sense for you to provide all of your product data to Google rather than just a selected subset. Google Search extracts a lot of information  

#### [0:03:30](https://www.youtube.com/watch?v=UQtdv_hoGuM&t=210) |  directly from web pages, so why is

product data different? The reason is product data needs to be accurate. Extracting information from web pages can be less reliable. For example, how does Google understand which is the product's price when both the original and the discounted price are shown? How does Google find the right product if the page also shows related products? How does Google understand  

#### [0:04:00](https://www.youtube.com/watch?v=UQtdv_hoGuM&t=240) |  whether additional costs, such as taxes and

shippings, are included in the price? Special treatments by Google are only available if Google is confident it has correctly obtained this additional information. Also, while some product fields are optional, others are required by Google before it will accept a product description. Using structured data is one way to make sure Google correctly understands all product details you are providing on a web page. There are several ways to encode structured data in a page,  

![](https://i.ytimg.com/vi/UQtdv_hoGuM/maxres2.jpg)



#### [0:04:30](https://www.youtube.com/watch?v=UQtdv_hoGuM&t=270) |  but a common way is to embed

it as JSON-LD-encoded content. More information on structured data can be found in the Google Search Central documentation. I added a link to the description below. So how to get your product data into Google Merchant Center? There are three approaches to choose between, suitable in different scenarios: by crawling your website,  

#### [0:05:00](https://www.youtube.com/watch?v=UQtdv_hoGuM&t=300) |  by periodically providing a feed of all

your products, or by using an API to update products individually. Let's look at these approaches in more detail. The first way is to configure Google Merchant Center to extract product data from pages crawled from your website. Using structured data on your pages can significantly increase the accuracy of the collected product data. In order to participate in the Google Shopping tab,  

#### [0:05:30](https://www.youtube.com/watch?v=UQtdv_hoGuM&t=330) |  you must also click through the appropriate

approvals in Google Merchant Center. Google Merchant Center also supports supplemental feeds that can add additional fields to the data from the primary field. For example, pricing, sales notifications, and stock level data can be provided via one or more supplemental feeds, so this data can be updated more frequently without waiting for the next crawl of your pages. The primary and the supplemental feed is combined by Google Merchant Center  

#### [0:06:00](https://www.youtube.com/watch?v=UQtdv_hoGuM&t=360) |  to form the final view of your

product data. Supplemental feeds can be provided via a Google Sheet for small data volumes, on-demand uploads, or it's via scheduled fetches. Data can be provided in a tab-separated text file or marked up in XML. The second strategy to provide your product data to Google Merchant Center is via a primary feed. A primary feed  

#### [0:06:30](https://www.youtube.com/watch?v=UQtdv_hoGuM&t=390) |  supports the same approaches as supplemental feeds.

For example, you may dump your whole product catalog to a file once a night, then make that file available to Google to load. It is worth noting that Google may compare your feed data to the original page to verify data consistency. Detected inconsistencies can result in products being excluded from Google, so it is important to keep your feeds in sync with the product data on your site as best as you are able.  

![](https://i.ytimg.com/vi/UQtdv_hoGuM/maxres3.jpg)



#### [0:07:00](https://www.youtube.com/watch?v=UQtdv_hoGuM&t=420) |  There are times, however, your website content

is updated more frequently than Google Merchant Center, particularly for product availability and pricing data. To support these two common sources of inconsistency, you can enable automatic item updates to update availability and price data in Google Merchant Center rather than flagging as an inconsistency. The third and final way in which you can provide data  

#### [0:07:30](https://www.youtube.com/watch?v=UQtdv_hoGuM&t=450) |  to Google Merchant Center is via the

Content API. Using the API, you can insert, update, and delete selected products instead of supplying complete replacement set of data for all products as is done in the previous two methods. The Content API can apply changes to specific products individually or in small batches for efficiency. This means your platform is responsible to work out which product changes you need to provide to Google,  

#### [0:08:00](https://www.youtube.com/watch?v=UQtdv_hoGuM&t=480) |  but the results can be live in

minutes rather than waiting for the next full processing run. It is worth noting that organic search results may take additional time to update after the new product data is in Google Merchant Center. So to wrap up, there are three ways you can provide detailed product data to Google. First, via web crawling product data from your site, preferably using structured data embedded in product pages.  

#### [0:08:30](https://www.youtube.com/watch?v=UQtdv_hoGuM&t=510) |  This can be easy to implement, but

you don't have as much control over how often your data is updated, unless you use a supplemental feed. Second, via feeds that you upload periodically, say, one or more times a day. Or third, via the Content API where you can update specific products on demand. With the content API, your updates can go live in minutes. What actions should you consider taking next? Add structured data to your web pages  

#### [0:09:00](https://www.youtube.com/watch?v=UQtdv_hoGuM&t=540) |  to increase the accuracy of extracting data;

decide on your strategy to get product data into Google, such as via website crawls, Google Sheets, scheduled fetches, uploads, or API calls; and remember that SEO still matters for organic search. Make your product details, such as images and descriptions, appealing to your customers. If you're curious about tracking how your products appear in Search, be sure to check out our video  

#### [0:09:30](https://www.youtube.com/watch?v=UQtdv_hoGuM&t=570) |  on Search Console for e-commerce sites. If

you have any questions or comments, feel free to add them below. Thank you. ♪ [music] ♪  