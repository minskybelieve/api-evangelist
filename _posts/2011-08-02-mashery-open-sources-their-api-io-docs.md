---
layout: post
title: Mashery Open Sources Their API IO Docs
url: http://apievangelist.com2011/08/02/mashery-open-sources-their-api-io-docs/
source: http://apievangelist.com2011/08/02/mashery-open-sources-their-api-io-docs/
domain: apievangelist.com2011
image: 
---
{% include JB/setup %}

I/O Docs provides an interactive documentation system for RESTful web APIs. By defining APIs at the resource, method and parameter levels in a JSON schema, I/O Docs will generate a JavaScript client interface. API calls can be executed directly from the documentation interface, proxied through the I/O Docs server, producing formatted responses.
Mashery has <a title="open-sourced a version of the I/O docs on Github" href="https://github.com/mashery/iodocs">open-sourced a version of the I/O Docs on Github</a>, for any API owner to deploy for their own documentation. This version of I/O docs runs on <a title="Node.js" href="https://github.com/joyent/node/wiki/Installation">Node.js</a> and uses <a title="Redis" href="http://redis.io/download">Redis</a> as a data store.
Last year Apigee launched their <a title="API consoe" href="http://apigee.com/about/products_togo.html">API console</a> which allows users to also make calls against an API, and <a title="earlier this year they made it freely available for any API owner" href="http://blog.apievangelist.com/2011/03/07/apigee-api-console-is-now-free-for-everyone-to-use/">earlier this year they made it freely available for any API owner</a> to deploy. The API console is a popular tool with developers to get up and going using an API, and build an understanding how an API works. Apigees move to make free was a significant market play, and definitely built awareness of their platform.
Masherys approach to API exploration reflects an alternative view from Apigees, one that integrates API discovery with API documentation, as opposed to being an entirely separate tool. Masherys move to open-source their I/O Docs on Github, is great to see. I'm sure it will definitely attract more attention to their platform and tools.
You can <a title="download or fork the Mashery I/O docs on Github" href="https://github.com/mashery/iodocs">download or fork the Mashery I/O Docs on Github</a>, and find necessary installation info and documentation.

