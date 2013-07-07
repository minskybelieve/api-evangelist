---
layout: post
title: Google Apps Supports OAuth
url: http://apievangelist.com2010/10/12/google-apps-supports-oauth/
source: http://apievangelist.com2010/10/12/google-apps-supports-oauth/
domain: apievangelist.com2010
image: 
---
{% include JB/setup %}

OAuth will make integration with the Google Apps platform much more secure by not requiring administrators to share their username and password with third party applications.
The advantages to using OAuth are:
<ul class="mainlist">
	<li>OAuth is more secure: OAuth tokens can be scoped and set to expire by a certain date, making them more secure than using the ClientLogin mechanism.</li>
	<li>OAuth is customizable: Using OAuth, you can create tokens that scripts may only use to access data of a particular scope when calling Google Apps APIs. For instance, a token set to call the Email Migration API would not be able to use your login credentials to access the Google Apps Provisioning API.</li>
	<li>OAuth is an open standard: OAuth is an open source standard, making it a familiar choice for developers to work with.</li>
</ul>
The Google Apps API services that support OAuth are:
<ul class="mainlist">
	<li>Provisioning API</li>
	<li>Email Migration API</li>
	<li>Admin Settings API</li>
	<li>Calendar Resource API</li>
	<li>Email Settings API</li>
	<li>Audit API</li>
</ul>
OAuth for authentication is more accepted by developers, and it makes many IT administrators much more comfortable with allowing third party integration with their Google Apps Premier, Education and Government editions.
To learn more about the OAuth standard, visit <a href="http://oauth.net">http://oauth.net</a>.

