---
layout: post
title: "Pharo-MySQL"
homepage: "https://github.com/pharo-rdbms/Pharo-MySQL"
category: [Persistency - Databases - SQL]
tags: [tools, database]
description: Database binding to work with MySQL
version: [Pharo 10]
expression: "
   LoadableProject new 
		repository: 'pharo-rdbms/Pharo-MySQL'; 
		baselineName: 'MySQL'; 
		version: 'master';
		group: #default;
		load"
---

Pharo Drivers for MySQL and MariaDB, including a [Glorp](https://github.com/pharo-rdbms/Glorp) adaptor.

Check [https://github.com/pharo-rdbms/Pharo-MySQL](https://github.com/pharo-rdbms/Pharo-MySQL)