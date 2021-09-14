---
title: R Markdown Dynamic Documentes for R
description: This is documents of Future Technology
featuredImage: 
toc: true
authors: Byeonghui-Won
tags:
categories: Future
series: Stock
date: '2021-09-14'
lastmod: '2021-09-14'
draft: false
---

이 블로그는 R Markdown형식으로 제작되었습니다. 이 웹사이트는 R프로그램으로 제작되었습니다. 디자인 템플릿은 R 프로그램에서 유명한 Yihui의 템플릿을 기반했습니다. 여기서 오늘 말하고자 하는 것은 이 웹사이트내에 블로그 형식으로 올리는 글에 관한 것입니다. 그래서 다시 한번 더 말하지만, 이 블로그는 R Markdown형식으로 제작되었습니다. 

이 문서는 몇가지 장점이 있습니다. 우선, 일종의 텍스트 기반 문서입니다. 따라서 파일 크기가 10kb 내외로 매우 작습니다. 또한, 텍스트 기반 문서이지만 실제 R 프로그램내에서 작동되기 때문에 외부데이터를 실시간으로 받아 문서를 출력할 수 있는 기능을 가지고 있습니다. 이것을 Dynamic Documentation이라고 합니다. 마지막으로, 이 문서는 프레젠테이션 및 보고서를 쉽게 생성할 수 있는 다양한 출력기능을 갖고 있어 pdf, ppt, docs, docx등의 형태로 변환이 매우 자유로우며, html기반의 문서로 출력될 수 있기 때문에 이렇게 블로그로 글을 작성할 수 있습니다. 

## R Markdown

R Markdown으로 블로그 생활을 1년여 하면서 이 것의 장점을 알릴 방법은 없을까 생각하다가 그동안 찾아보면서 배웠던 내용을 몇가지 정리해서 올려보고자 합니다. 

우선 이것은 [markdown](http://daringfireball.net/projects/markdown/basics)이라는 문법에 기반한 텍스트 포맷으로도 최종 적으로 문서가 출력될 수 있는 임베디드 R 코드 청크가 포함됩니다. R 마크다운 문서는 기본 R 코드로 이뤄져 있으며, 데이터가 변경될 때마다 *자동으로 재생성*될 수 있습니다. 이것이 마크다운 문서의 힘입니다. 

## R Markdown 사용법 배우기 

R Markdown 사용 방법을 배우기 위해서는 [rmarkdown.rstudio.com](http://rmarkdown.rstudio.com/)의 개발센터를 통해 배울 수 있습니다. 

그 곳에서는 다음과 같은 R Markdown자료를 볼 수 있습니다. 

+ [Markdown Basics](http://rmarkdown.rstudio.com/authoring_basics.html)에서는 가장 일반적으로 사용되는 마크다운 구성을 알 수 있습니다.

+ [R Code Chunks](http://rmarkdown.rstudio.com/authoring_rcodechunks.html)에서는 내제된 R 코드에 관해 좀더 깊이 있는 학습을 할 수 있습니다.

+ [R Markdown Cheat Sheet    (PDF)](http://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf)에서는 가장 많이 쓰이는 R 코드, knitr옵션 및 출력형식에 관한 빠른 가이드를 받을 수 있습니다.
    
+ [R Markdown Reference Guide    (PDF)](http://www.rstudio.com/wp-content/uploads/2015/03/rmarkdown-reference.pdf)에서는 markdown, knitr, output 에 관한 포괄적인 가이드를 받을 수 있습니다.

+ [Bibliographies and     Citations](http://rmarkdown.rstudio.com/authoring_bibliographies_and_citations.html)에서는 R markdown 보고서에 레퍼런스를 폼함하는 방법에 대해 설명합니다.

+ [Interactive Documents with     Shiny](http://rmarkdown.rstudio.com/authoring_shiny.html)에서는 R Markdown의 대화형 문서인 [Shiny](http://shiny.rstudio.com/)를 작성하는 방법을 배웁니다. 매우 강력한 기능입니다.

+ [Compiling Notebooks](http://rmarkdown.rstudio.com/r_notebook_format.html)에서는 R Markdown문서로 작성하면 HTML, PDF, or MS Word 로 컴파일하는 방법을 가이드 받을 수 있습니다. 

## R Markdown의 다양한 출력형태

R Markdown으로 출력되는 다양한 형태의 문서에 관해 알고 싶다면 아래를 참고하세요.

+ [HTML](http://rmarkdown.rstudio.com/html_document_format.html),

+ [PDF](http://rmarkdown.rstudio.com/pdf_document_format.html),

+ [Word](http://rmarkdown.rstudio.com/word_document_format.html),

+ [Markdown](http://rmarkdown.rstudio.com/markdown_document_format.html),

+ [Tufte Handout](http://rmarkdown.rstudio.com/tufte_handout_format.html).

## R Markdown으로 PPT 파일만들기

R 마크다운으로 문서를 작성하면 Presentation파일로 쉽게 만들 수 있습니다. 

+ [ioslides](http://rmarkdown.rstudio.com/ioslides_presentation_format.html),

+ [Slidy](http://rmarkdown.rstudio.com/slidy_presentation_format.html),

+ [Beamer](http://rmarkdown.rstudio.com/beamer_presentation_format.html)

## 심화학습 하기

이제 어느정도 학습을 하였다면 지금부터는 깊이있는 학습으로 인도합니다.

+ The website for the [knitr package](http://yihui.name/knitr/). Knitr는 내제된 동적 컨텐츠 생성을 위한 매우 강력한 도구입니다. 이 곳에서는 매우 풍부한 관련 자료를 찾아볼 수 있습니다. 

+ [Pandoc Markdown](http://rmarkdown.rstudio.com/authoring_pandoc_markdown.html)은 R Markdown 문서로 구현되는 모든 형태의 문서를 찾아볼 수 있습니다.
    
또한 R Markdown developer 문서에서는 

+ 재생가능한 문서 템플릿[Document     Templates](http://rmarkdown.rstudio.com/developer_document_templates.html)

+ 문서 포맷 생성 가이드 [Creating New     Formats](http://rmarkdown.rstudio.com/developer_custom_formats.html) 

+ [HTML Widgets](http://rmarkdown.rstudio.com/developer_html_widgets.html)를 활용한 대화형 콤포넌트 추가하기 

+ [Shiny Widgets](http://rmarkdown.rstudio.com/authoring_shiny_widgets.html)

를 알아볼 수 있습니다.

