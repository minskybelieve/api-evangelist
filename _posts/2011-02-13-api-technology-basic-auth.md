---
layout: post
title: API Technology Basic Auth
url: http://apievangelist.com2011/02/13/api-technology-basic-auth/
source: http://apievangelist.com2011/02/13/api-technology-basic-auth/
domain: apievangelist.com2011
image: 
---
{% include JB/setup %}

Because Basic Auth is integrated into <a class="zem_slink" title="Hypertext Transfer Protocol" rel="wikipedia" href="http://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol">HTTP protocol</a> it is the easiest way for users to authenticate with a <a class="zem_slink" title="Representational State Transfer" rel="wikipedia" href="http://en.wikipedia.org/wiki/Representational_State_Transfer">RESTful API</a>.
Basic Auth is easily integrated, however if <a class="zem_slink" title="Transport Layer Security" rel="wikipedia" href="http://en.wikipedia.org/wiki/Transport_Layer_Security">SSL</a> is not used, the username and password are passed in plain text and can be easily intercepted on the open Internet.
OAuth is a much better choice for RESTful API authentication, but Basic Auth is perfectly suited for APIs that are intended for a wider audience and do not give access to sensitive information.
<h6 class="zemanta-related-title" style="font-size: 1em;">Related articles</h6>
<ul class="zemanta-article-ul">
	<li class="zemanta-article-ul-li"><a href="http://blog.apievangelist.com/2011/02/10/instapaper-launches-full-api/">Instapaper Launches Full API</a> (apievangelist.com)</li>
	<li class="zemanta-article-ul-li"><a href="http://blog.programmableweb.com/2011/01/11/google-adds-api-for-url-shortener-and-link-analytics/">Google Adds API For URL Shortener and Link Analytics</a> (programmableweb.com)</li>
	<li class="zemanta-article-ul-li"><a href="http://blog.apievangelist.com/2011/02/12/api-status-dashboard-with-pingdom/">API Status Dashboard with Pingdom</a> (apievangelist.com)</li>
</ul>

