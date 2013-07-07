---
layout: post
title: API Technology SOAP
url: http://apievangelist.com2011/02/08/api-technology-soap/
source: http://apievangelist.com2011/02/08/api-technology-soap/
domain: apievangelist.com2011
image: 
---
{% include JB/setup %}

SOAP uses Extensible Markup Language (XML) for its message format.  The SOAP Messaging Framework consists of:
<ul class="mainlist">
	<li><strong>Processing Model</strong> - Rules for processing a SOAP message</li>
	<li><strong>Extensibility Model</strong> - SOAP features and SOAP modules</li>
	<li><strong>Underlying Protocol Binding Framework</strong> - Rules for defining a binding to an underlying protocol that can be used for exchanging SOAP messages</li>
	<li><strong>Message Construct</strong> - Structure of a SOAP message</li>
</ul>
A SOAP message returning a users information might look like:
<script src="https://gist.github.com/817172.js?file=API%20-%20Tech%20-%20SOAP"></script>
SOAP was originally designed in 1998 as a Microsoft project and became a <a href="http://www.w3.org/TR/soap/" target="_blank">W3C Recommendation</a> in June 2003.
Even though SOAP has a long history with enterprise development, it has not seen the same adoption with the web 2.0 developer community, in no small part due to its complex and verbose nature.
SOAP is far from dead, but in the new generation of web-based APIs, RESTful interfaces returning JSON are fast replacing the bulky SOAP interfaces that returns XML.

