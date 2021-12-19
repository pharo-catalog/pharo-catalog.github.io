---
layout: post
title: "CodeFonts Hack"
homepage: "https://github.com/astares/Pharo-CodeFonts"
category: [Fonts]
tags: [font, ui]
description: CodeFont Hack - a workhorse typeface for source code
version: [Pharo 10]
expression: "
   LoadableProject new 
		repository: 'astares/Pharo-CodeFonts'; 
		baselineName: 'CodeFonts'; 
		version: 'main';
		group: 'Hack';
		load.
	StandardFonts codeFont: (LogicalFont familyName: 'Hack' pointSize: 10)"
---

Hack - a popular code font for coding as embedded font for use in Pharo images

Check [https://github.com/astares/Pharo-CodeFonts](https://github.com/astares/Pharo-CodeFonts) and [https://github.com/source-foundry/Hack](https://github.com/source-foundry/Hack)