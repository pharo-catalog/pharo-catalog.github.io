---
layout: post
title: "CodeFonts JetBrains Mono"
homepage: "https://github.com/astares/Pharo-CodeFonts"
category: [Fonts]
tags: [font, ui]
description: CodeFont JetBrains Mono - a typeface made for developers.
version: [Pharo 10]
expression: "
   LoadableProject new 
		repository: 'astares/Pharo-CodeFonts'; 
		baselineName: 'CodeFonts'; 
		version: 'main';
		group: 'JetBrains';
		load.
	StandardFonts codeFont: (LogicalFont familyName: 'JetBrains Mono' pointSize: 10)"
---

JetBrains Mono - a popular code font for coding as embedded font for use in Pharo images

Check [https://github.com/astares/Pharo-CodeFonts](https://github.com/astares/Pharo-CodeFonts) and [https://github.com/JetBrains/JetBrainsMono](https://github.com/JetBrains/JetBrainsMono)