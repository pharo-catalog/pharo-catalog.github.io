---
layout: post
title: "XML-XMLPullParser"
homepage: "https://github.com/pharo-contributions/XML-XMLPullParser"
category: [XML]
tags: [tools, xml]
description: XMLPullParser is a streaming XML parser.
version: [Pharo 10]
expression: "
   LoadableProject new 
		repository: 'pharo-contributions/XML-XMLPullParser'; 
		baselineName: 'XMLPullParser'; 
		version: 'master';
		group: #default;
		load"
---

XMLPullParser is a streaming XML parser. Instead of building a DOM tree, the parser streams over "events" (start tag, text, end tag) on demand. For more information on the technique in general, see [xmlpull.org](https://xmlpull.org)

Check [https://github.com/pharo-contributions/XML-XMLPullParser](https://github.com/pharo-contributions/XML-XMLPullParser)