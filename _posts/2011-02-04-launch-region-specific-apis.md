---
layout: post
title: Launch Region Specific APIs
url: http://apievangelist.com2011/02/04/launch-region-specific-apis/
source: http://apievangelist.com2011/02/04/launch-region-specific-apis/
domain: apievangelist.com2011
image: 
---
{% include JB/setup %}

<img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/global-regional-api.jpg" alt="" width="250" align="right" />
One way to localize usage and increase API performance is to deploy region specific APIs.
There are several ways to do this including <a href="http://www.kinlane.com/2010/07/zeus-cloud-software/" target="_blank">global cloud load balancing</a>, but a more cost effective tool is <a href="http://www.kinlane.com/category/amazon/amazon-ec2/" target="_blank">Amazon EC2</a> Availability Zones.
Using <a href="http://www.kinlane.com/category/amazon/amazon-ec2/">Amazon EC2</a> you could deploy region specific servers in the following regions:
<ul class="mainlist">
	<li>United States - West Coast</li>
	<li>United States - East Coast</li>
	<li>European Union (EU)</li>
	<li>Asia Pacific</li>
</ul>
Using 4 separate servers I can create separate regional APIs sub-domains:
<ul class="mainlist">
	<li>api.uswest.apievangelist.com</li>
	<li>api.useast.apievangelist.com</li>
	<li>api.eu.apievangelist.com</li>
	<li>api.asia.apievangelist.com</li>
</ul>
If API usage grows in one region or another, regional Amazon EC2 servers can be deployed into necessary Amazon Availability Zones.
Something to consider when trying to scale your API and deliver high quality service on a budget.
