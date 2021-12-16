---
layout: post
title: "XML-XMLParserStAX"
homepage: "https://github.com/pharo-contributions/XML-XMLParserStAX"
category: [XML]
tags: [tools, xml]
description: XMLParserStAX is a pull parser for XMLParser
version: [Pharo 10]
expression: "
   LoadableProject new 
		repository: 'pharo-contributions/XML-XMLParserStAX'; 
		baselineName: 'XMLParserStAX'; 
		version: 'master';
		group: #default;
		load"
---

XMLParserStAX is a pull parser in Pharo for XMLParser that provides a streaming interface for "pulling" XML events and also supports pull-style DOM parsing for dynamically converting events into DOM nodes.

Check [https://github.com/pharo-contributions/XML-XMLParserStAX](https://github.com/pharo-contributions/XML-XMLParserStAX)