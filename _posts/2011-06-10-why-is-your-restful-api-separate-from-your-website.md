---
layout: post
title: Why is your RESTful API Separate From Your Website
url: http://apievangelist.com2011/06/10/why-is-your-restful-api-separate-from-your-website/
source: http://apievangelist.com2011/06/10/why-is-your-restful-api-separate-from-your-website/
domain: apievangelist.com2011
image: 
---
{% include JB/setup %}

A while back I wrote a piece about Seevl titled, <a href="http://blog.apievangelist.com/2011/05/27/with-seevl-music-discovery-the-website-is-the-api/">With Seevl Music Discovery, the Website is the API</a>.  When building the Seevl API, instead of providing a separate API to access information, Seevl relies on content negotiation principles to deliver alternative representations of web pages.
As I was talking with Passant, I kept thinking about how RESTful APIs are often deployed separately from the web site or application.  Both are using HTTP, and often deliver the same information, they are just intended for two different audiences and potential uses.
This is not a new idea.  Flickr delivered the Flickr API this way in the early days, and web applications like <a title="Tumblr" href="http://www.tumblr.com/">Tumblr</a> offer their <a title="API" href="http://www.tumblr.com/docs/en/api">API</a> and application side by side.
You can visit my Tumblr blog at:  <a title="http://kinlane.tumblr.com/" href="http://kinlane.tumblr.com/">http://kinlane.tumblr.com/</a>
Simple add /api/read to the same URL:  <a title="http://kinlane.tumblr.com/api/read/" href="http://kinlane.tumblr.com/api/read/">http://kinlane.tumblr.com/api/read/</a>
And you you get back an XML representation of my Tumblr blog.
Add /JSON to that URL: <a href="http://kinlane.tumblr.com/api/read/json">http://kinlane.tumblr.com/api/read/json</a>
And you get back a JSON representation of my Tumblr blog.
<div>
In most cases, it does not makes sense for a web site or application and its RESTful API to be separated, for some reason many developers still see them as two completely separate things.
In my opinion, if the HTML, XML, and JSON representations of information are deployed side by side. And users know they can simple adjust the URL to get other formats, the type of users that hack on, embed, and redistribute information from APIs will grow beyond the developer community.
</div>
<h6 class="zemanta-related-title" style="font-size: 1em;">Related articles</h6>
<ul class="zemanta-article-ul">
	<li class="zemanta-article-ul-li"><a href="http://blog.apievangelist.com/2011/05/27/with-seevl-music-discovery-the-website-is-the-api/">With Seevl Music Discovery, the Website is the API</a> (apievangelist.com)</li>
	<li class="zemanta-article-ul-li"><a href="http://blog.apievangelist.com/2011/06/10/posterous-from-saas-to-paas-using-an-api/">Posterous, From SaaS to PaaS Using an API</a> (apievangelist.com)</li>
	<li class="zemanta-article-ul-li"><a href="http://blog.apievangelist.com/2011/05/21/discovery-services-for-common-apis/">Discovery Services for Common APIs</a> (apievangelist.com)</li>
</ul>

