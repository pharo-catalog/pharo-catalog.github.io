---
layout: post
title: "Pharo-SQLite3"
homepage: "https://github.com/pharo-rdbms/Pharo-SQLite3"
category: [Database]
tags: [tools, database]
description: Framework for Pharo to access relational databases via ODBC
version: [Pharo 10]
expression: "
   LoadableProject new 
		repository: 'pharo-rdbms/Pharo-SQLite3'; 
		baselineName: 'SQLite3'; 
		version: 'master';
		group: #default;
		load"
---

Standalone [SQLite3](https://www.sqlite.org/) database binding for [Pharo](https://www.pharo.org)

Check [https://github.com/pharo-rdbms/Pharo-SQLite3](https://github.com/pharo-rdbms/Pharo-SQLite3)