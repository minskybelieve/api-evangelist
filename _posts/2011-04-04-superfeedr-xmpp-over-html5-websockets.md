---
layout: post
title: Superfeedr XMPP over HTML5 WebSockets
url: http://apievangelist.com2011/04/04/superfeedr-xmpp-over-html5-websockets/
source: http://apievangelist.com2011/04/04/superfeedr-xmpp-over-html5-websockets/
domain: apievangelist.com2011
image: 
---
{% include JB/setup %}

XMPP provides identity, authentication, presence, and notifications for APIs and other feeds, and with the growing adoption of HTML5, the <a title="HTML5 WebSockets API" href="http://dev.w3.org/html5/websockets/">WebSockets API</a> is the perfect built-in browser client to interact with APIs and feeds in the browser.
The <a title="Superfeedr Ejabber Module" href="https://github.com/superfeedr/ejabberd-websockets">Superfeedr Ejabber module</a> is written in Erlang and available over at <a title="Github" href="https://github.com/superfeedr/ejabberd-websockets">Github</a>.  They recommend you use the module with <a title="SropheJS" href="https://github.com/metajack/strophejs">Strophejs</a>, an XMPP library written in Javascript.
XMPP is growing in popularity as a protocol for providing real-time API and feed updates, while increasing the efficiency of API networks by minimizing polling of API endpoints.
