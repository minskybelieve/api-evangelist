---
layout: post
title: iCloud Storage APIs
url: http://apievangelist.com2011/06/08/icloud-storage-apis/
source: http://apievangelist.com2011/06/08/icloud-storage-apis/
domain: apievangelist.com2011
image: 
---
{% include JB/setup %}

There are two ways that applications can take advantage of iCloud storage:
<ul class="mainlist">
	<li>Document Storage - Enabling storage and sharing of information in document form.</li>
	<li>Key-Value Data Storage - Enabling storage and sharing small amounts of data.</li>
</ul>
Most applications will use iCloud document storage to share documents, which is a feature that users think of when they think of cloud storage. Users care about whether photos, videos, and documents are accessible across devices while the key-value data store is not something a user would never see.
Key-value storage will be used for small amounts of data such as storing application state, settings, and other important information that delivers a better user experience.  Although not as apparent to the end-user, key-value storage will be just as important as document storage.
<img class="aligncenter" style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/apple/iCloud-Storage-APIs.png" alt="" width="550" align="center" />
All iCloud storage is managed centrally by the iCloud service, which handles coordination of documents and key-value stores.  The iCloud service handles storage searches, change notifications, version control, conflicts, and security for applications that integrate with a user's iCloud storage account.
Neither document storage or key-value storage in the cloud are anything new.  But when it is implemented as part of the IOS platform, it becomes much bigger.   Apple is solving everyday problems users face when using their smart phones, by storing data centrally in the cloud.
ICloud APIs will enable developers to build rich applications on the IOS platform, and continue to grow IOS market share.
<h6 class="zemanta-related-title" style="font-size: 1em;">Related articles</h6>
<ul class="zemanta-article-ul">
	<li class="zemanta-article-ul-li"><a href="http://blog.apievangelist.com/2011/06/06/apple-icloud-api/">Apple iCloud API</a> (apievangelist.com)</li>
	<li class="zemanta-article-ul-li"><a href="http://www.kinlane.com/2011/06/icloud-storage-apis/">iCloud Storage APIs</a> (kinlane.com)</li>
	<li class="zemanta-article-ul-li"><a href="http://www.kinlane.com/2011/06/documents-in-the-cloud-with-apple-icloud/">Documents in the Cloud with Apple iCloud</a> (kinlane.com)</li>
</ul>

