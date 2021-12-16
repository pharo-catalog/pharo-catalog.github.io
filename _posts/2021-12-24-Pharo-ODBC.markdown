---
layout: post
title: "Pharo-ODBC"
homepage: "https://github.com/pharo-rdbms/Pharo-ODBC"
category: [Database]
tags: [tools, database]
description: Framework for Pharo to access relational databases via ODBC
version: [Pharo 10]
expression: "
   LoadableProject new 
		repository: 'pharo-rdbms/Pharo-ODBC'; 
		baselineName: 'ODBC'; 
		version: 'master';
		group: #default;
		load"
---

ODBC framework for Pharo based on Dolphin Smalltalk's Database Connection package. Thanks to <a href="http://www.infoil.com.ar/">InfOil</a> for supporting this project.

Check [https://github.com/pharo-rdbms/Pharo-ODBC](https://github.com/pharo-rdbms/Pharo-ODBC)