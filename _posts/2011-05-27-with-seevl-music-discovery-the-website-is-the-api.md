---
layout: post
title: With Seevl Music Discovery the Website is the API
url: http://apievangelist.com2011/05/27/with-seevl-music-discovery-the-website-is-the-api/
source: http://apievangelist.com2011/05/27/with-seevl-music-discovery-the-website-is-the-api/
domain: apievangelist.com2011
image: 
---
{% include JB/setup %}

When deploying the API, Seevl approached it a little differently than most.  Instead of providing a separate API to access data,  Seevl relies on content negotiation principles to deliver alternative representations of web pages.
This means the entire Seevl website is the API and you can get JSON representations of almost every page in the site.
Seevl relies on HTTP headers to let developers request data using a particular content-types, and authenticate using three parameters:
<ul class="mainlist">
	<li><strong>Accept</strong> - The content-type required</li>
	<li><strong>X_APP_ID</strong> - Developer application ID</li>
	<li><strong>X_APP_KEY</strong> - Developer application Key</li>
</ul>
Here is an example search results for beatles using curl:
<script src="https://gist.github.com/996079.js?file=Seevl%20API%20Request"></script>
This approach is meant to make it easier for to developers focus on the development and let the Seevl client libraries handle the content-negotiation.
The <a title="Seevl API" href="http://developers.seevl.net/">Seevl API</a> provides everal methods to search and pull specific data about individual bands and artists and related information.
While this approach is nothing new, its an interesting way to provide users with HTML views and developers with the JSON representations of information stored in a database.
<h6 class="zemanta-related-title" style="font-size: 1em;">Related articles</h6>
<ul class="zemanta-article-ul">
	<li class="zemanta-article-ul-li"><a href="http://blog.semantic-web.at/2011/05/19/seevl-explore-the-cultural-universe-based-on-semantic-web-technologies/">Seevl: Explore the cultural universe based on semantic web technologies</a> (semantic-web.at)</li>
	<li class="zemanta-article-ul-li"><a href="http://blog.apievangelist.com/2011/05/24/whats-next-for-apis-learning-from-social-apis/">Whats Next for APIs? Learning From Social APIs</a> (apievangelist.com)</li>
	<li class="zemanta-article-ul-li"><a href="http://blog.apievangelist.com/2011/05/21/google-apis-explorer/">Google APIs Explorer</a> (apievangelist.com)</li>
</ul>

