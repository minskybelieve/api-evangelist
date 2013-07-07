---
layout: post
title: Amazon Kills Alexa SOAP API Due To Security
url: http://apievangelist.com2011/06/26/amazon-kills-alexa-soap-api-due-to-security/
source: http://apievangelist.com2011/06/26/amazon-kills-alexa-soap-api-due-to-security/
domain: apievangelist.com2011
image: 
---
{% include JB/setup %}

On November 25, 2011 Amazon will deprecate the Alexa Top Sites SOAP API. The SOAP interface has had repeated security issues over the last couple of years, and since only a small percentage of users actually use the API, they decided to decommission it.
Alexa will also be enforcing that all requests to the API must be signed using <a title="signature version 2" href="http://docs.amazonwebservices.com/AlexaTopSites/latest/CalculatingSignatures.html">signature version 2</a>.  Version 2 is significantly more secure that the version, and all <a title="Amazon Web Services" href="http://aws.amazon.com/">Amazon Web Services</a> are being required to migrate to it.
I wonder if Amazon is having similar security issues with other SOAP APIs?   Maybe the other SOAP APIs just have more users and it was worthwhile for them to fix.
Makes you wonder how many SOAP users vs. REST users Amazon Web Services has.

