---
layout: post
title: "ReStoreForPharo"
homepage: "https://github.com/rko281/ReStoreForPharo"
category: [Persistency - ORM Frameworks]
tags: [tools, database]
description: Object relational mapping (ORM) framework
version: [Pharo 10]
expression: "
   LoadableProject new 
		repository: 'rko281/ReStoreForPharo'; 
		baselineName: 'ReStore'; 
		version: 'master';
		group: #default;
		load"
---

ReStore is a framework enabling Pharo objects to be stored in and read from relational databases (SQLite, PostgreSQL etc.).

Check [https://github.com/rko281/ReStoreForPharo](https://github.com/rko281/ReStoreForPharo)