---
layout: post
title: "Pharo-ODBC"
homepage: "https://github.com/pharo-rdbms/Pharo-ODBC"
category: [Persistency - Databases]
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

ODBC framework for [Pharo](https://www.pharo.org) based on [Dolphin Smalltalk's](https://github.com/dolphinsmalltalk/Dolphin) Database Connection package. Thanks to [InfOil](http://www.infoil.com.ar) for supporting this project.

Check [https://github.com/pharo-rdbms/Pharo-ODBC](https://github.com/pharo-rdbms/Pharo-ODBC)