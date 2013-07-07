---
layout: post
title: The Secret to Amazons Success Internal APIs
url: http://apievangelist.com2012/01/12/the-secret-to-amazons-success-internal-apis/
source: http://apievangelist.com2012/01/12/the-secret-to-amazons-success-internal-apis/
domain: apievangelist.com2012
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/blog/amazon-com-logo.jpg
---
{% include JB/setup %}

<p>The insight about how Google approached the API for Google+ is interesting, but what is far more interesting is the insight the Google engineer who posted the rant, Steve Yegge, provides about his time working at Amazon, before he was a engineer with Google.</p>
<p>During 6 years at Amazon he witnessed the transformation of the company from a bookseller to the almost $1B, Infrastructure as a Service (IaaS) API, cloud computing leader. &nbsp;As Yegge's recalls that one day Jeff Bezos issued a mandate, sometime back around 2002 (give or take a year):</p>
<ul class="mainlist">
<li>All teams will henceforth expose their data and functionality through service interfaces.</li>
<li>Teams must communicate with each other through these interfaces.</li>
<li>There will be no other form of inter-process communication allowed: no direct linking, no direct reads of another team&rsquo;s data store, no shared-memory model, no back-doors whatsoever. The only communication allowed is via service interface calls over the network.</li>
<li>It doesn&rsquo;t matter what technology they use.</li>
<li>All service interfaces, without exception, must be designed from the ground up to be externalizable. That is to say, the team must plan and design to be able to expose the interface to developers in the outside world. No exceptions.</li>
</ul>
<p>The mandate closed with:</p>
<blockquote>
<p><strong><em>Anyone who doesn&rsquo;t do this will be fired. &nbsp;Thank you; have a nice day!</em></strong></p>
</blockquote>
<p>Everyone got to work and over the next couple of years, Amazon transformed itself, internally into a service-oriented architecture (SOA), learning a tremendous amount along the way.<br /><img src="http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg" alt="" width="200" align="right" /><br />Think about what Bezos was asking! &nbsp;&nbsp;Every team within Amazon had to interact using web services. &nbsp;If you were human resources and you needed some numbers from marketing, you had to get them using an API. &nbsp;He was asking every team to decouple, define what resources they had, and make them available through an API. &nbsp;Every team within your company essential becomes a partner of the other.</p>
<p>Some of the lessons Amazon learned along the way:</p>
<ul class="mainlist">
<li><strong>Support</strong>&nbsp;- Support for your teams interface becomes critical</li>
<li><strong>Security</strong>&nbsp;- Every teams becomes a potential DOS attacker requiring service levels, quotas and throttling</li>
<li><strong>Monitoring / QA</strong>&nbsp;- Monitoring and QA are interconnected, you will need smart tools for not just telling if something is up and running, but actually delivering the expected results</li>
<li><strong>Discovery</strong>&nbsp;- Service discovery becomes important. &nbsp;You will need to know what APIs there are, if they are available and where to find them.</li>
<li><strong>Testing</strong>&nbsp;- Sandbox and debugging is essential for all APIs</li>
</ul>
<div>Of course this is a very small sampling from a rant of a former employee. &nbsp;&nbsp;There are dozens, maybe hundreds of individual lessons like these that Amazon had to discover organically.</div>
<div>
<p>Yegge&rsquo;s &nbsp;points out that,&nbsp;<em>&ldquo;Organizing into services taught teams not to trust each other in most of the same ways they&rsquo;re not supposed to trust external developers.&rdquo;</em></p>
<p>This makes deploying internal APIs a great exercise for preparing your company for the coming API economy where, you will have to have expose self-service, partner and public APIs to stay competitive in your industry.</p>
<p>When Amazon started, it was difficult to see how the bookseller would be come the e-commerce powerhouse it is today, let alone to see that Amazon would transform culturally into a company that thinks and operates as a service oriented architecture, delivering Amazon Web Services, that not only changed how the company operates, but created an entire platform that would change how the Internet works.</p>
</div>
