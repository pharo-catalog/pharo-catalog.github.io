---
layout: post
title: "CodeFonts JetBrains Mono"
homepage: "https://github.com/astares/Pharo-CodeFonts"
category: [Fonts]
tags: [font, ui]
description: CodeFont JetBrains Mono - a typeface made for developers.
version: [Pharo 10]
icon: "iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAABGdBTUEAAK/INwWK6QAAABl0
RVh0U29mdHdhcmUAQWRvYmUgSW1hZ2VSZWFkeXHJZTwAAAHJSURBVDjLY/j//z8DJZiBZgY4
tN9wcO6+0erZd2uKc+fNfoeWGxMcW27Msiq+3GWUdIZXL/okI14D7JqvB+csf3Rv4p6X//t3
Pf/fvf35/8Ilj3471V3bph9zmougC6xrr8mETbu7q3jl40/FKx5+LVzy8Ltd+eUZBvGnOYjy
gk3llfKCZY++u3fcWutcd21B07on/61yz88kKgwsCi8qJc++9yhu2p37ppnnQ4C4oWblo/9W
OReXEjTANOsCs1PD9VVZ8+9/N0k7m6Yfe5LLOPFMR+Wyh/9dqq5eUvc6xIbXALOs8zEZc+9/
C+q+ddEw/rSfXuRxLfP0swuqgAYEt934pOq2nxenAUbJZ0TjJt9+Vbn80X+v5huXrbLOb7LM
OLfVterqjcYVj/+Htd38qey4TxqrAQaxpxntSy7PBvnVPO0MSmCZJ5/ZWL7g/v+ozlv/lex2
K2EYoB9zigsYPS6lSx7+j+i59UYn6JgtTIGK635hdY/D9dnT7vxP6L/9X9F+b4icxTYmFAMs
Ms6ti+2/9S9hwu3/Ac3X32oHHOlVdtoroGS/R0vb9/Aip8ILrwLrrv33rbn63zD02F5Zy22G
tM8LdDMAACVPr6ZjGHxnAAAAAElFTkSuQmCC"
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