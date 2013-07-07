---
layout: post
title: Prepaid Billing for APis
url: http://apievangelist.com2011/04/23/prepaid-billing-for-apis/
source: http://apievangelist.com2011/04/23/prepaid-billing-for-apis/
domain: apievangelist.com2011
image: 
---
{% include JB/setup %}

But there are other ways to handle payments.  Rather than billing at the end of a month based on the number of calls made, you can offer developers the option to prepay.  While they're still billed based on calls, that bill is paid in advance.<img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/api-evangelist/prepaid-api-billing.png" alt="" width="250" align="right" />
<a title="Phaxio" href="http://www.phaxio.com/">Phaxio</a>, an API that allows developers to <a title="Phaxio" href="http://www.phaxio.com/">integrate faxing capabilities into their applications</a>, is one example of this.
Under your account settings, Phaxio provides a Recharge your Balance tool for paying for calls made via the API.
You can select an amount between $10.00 and $1,000.00, enter a credit card and billing information, and prepay for all calls made to the API.
All incoming and outgoing faxes through the Phaxio API are 7� per page, debited against your prepaid account balance.
A prepaid billing model for APIs make a lot of sense, concerns about potentially out of control cloud computing bills are common.   Paying for estimated API use ahead of time is a great way to keep development and IT costs under control.
