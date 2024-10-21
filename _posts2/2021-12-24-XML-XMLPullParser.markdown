---
layout: post
title: "XML-XMLPullParser"
homepage: "https://github.com/pharo-contributions/XML-XMLPullParser"
category: [XML]
tags: [tools, xml]
description: XMLPullParser is a streaming XML parser.
version: [Pharo 10]
icon: "iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAABGdBTUEAAK/INwWK6QAAABl0
RVh0U29mdHdhcmUAQWRvYmUgSW1hZ2VSZWFkeXHJZTwAAAEXSURBVDjLY/j//z8DJZhhmBpg
2POQn2wDDDof8HvOe3osYtXzDzCxuM2vP3gvfn4MJIfXAP22e0Ies58eK9r2+r//3Kf3YOIh
q17eK9v95j9ITrv2jhBWA/Ra7kVEr375vXDrq/9+s57eUy+4IY0kJx2w6Nk9kFzE0uffgXIR
KAboNtxlC1/+/GPljjdABc9+q+ZcM0Z3qmb5LWOQXOmml/8DZz7+qJB0hQ3FBerFNyNC5z/9
nrXqxX+Pvgf35OMuSSPJSXtPfXQPJBc089F3oFwE1jBQTLkiZNtw51jq4qf/XVvuwsPAa9Kj
exkrnv8HyclFXxTCGwsyERf4LctvHvPuvAePBf8pDz/Y1N45BpIbKUmZFAwAR3nW32nUrY0A
AAAASUVORK5CYII="
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