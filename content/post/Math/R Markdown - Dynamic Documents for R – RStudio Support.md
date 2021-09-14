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

R Markdown은 R에서 동적 문서, 프레젠테이션 및 보고서를 쉽게 생성할 수 있는 저작 형식입니다. 

이것은 [markdown](http://daringfireball.net/projects/markdown/basics)이라는 문법에 기반한 텍스트 포맷으로도 최종 적으로 문서가 출력될 수 있는 임베디드 R 코드 청크가 포함됩니다. 

R 마크다운 문서는 기본 R 코드로 이뤄져 있으며, 데이터가 변경될 때마다 *자동으로 재생성*될 수 있습니다. 이것이 마크다운 문서의 힘입니다. 

R Markdown 사용 방법을 배우기 위해서는 [rmarkdown.rstudio.com](http://rmarkdown.rstudio.com/)의 개발센터를 통해 배울 수 있습니다. 

그 곳에서는 다음과 같은 R Markdown자료를 볼 수 있습니다. 

-   [Markdown
    Basics](http://rmarkdown.rstudio.com/authoring_basics.html) 에서 가장 일반적으로 사용되는 마크다운 구성을 설명하며

-   [R Code
    Chunks](http://rmarkdown.rstudio.com/authoring_rcodechunks.html),
    이곳에서는 내제된 R 코드에 관해 좀더 깊이 있는 학습을 할 수 있습니다.

-   [R Markdown Cheat Sheet
    (PDF)](http://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf),
    일반적인 코드에 관해 학습을 마쳤다면 이 곳에서는 가장 많이 쓰이는 R 코드, knitr옵션 및 출력형식에 관한 빠른 가이드를 받을 수 있습니다.
    
-   [R Markdown Reference Guide
    (PDF)](http://www.rstudio.com/wp-content/uploads/2015/03/rmarkdown-reference.pdf), 이곳에서는 markdown, knitr, output 에 관한 포괄적인 가이드를 받을 수 있습니다.

-   [Bibliographies and
    Citations](http://rmarkdown.rstudio.com/authoring_bibliographies_and_citations.html),
    R markdown 보고서에 레퍼런스를 폼함하는 방법에 대해 설명합니다.

-   [Interactive Documents with
    Shiny](http://rmarkdown.rstudio.com/authoring_shiny.html), R Markdown문서에서는 대화형 문서인     [Shiny](http://shiny.rstudio.com/)를 작성하는 방법을 배웁니다.

-   [Compiling
    Notebooks](http://rmarkdown.rstudio.com/r_notebook_format.html), R Markdown문서로 작성하면 HTML, PDF, or MS Word 로 컴파일이 가능합니다. 이 곳에서는 그 방법을 설명합니다.

-   서류의 출력형태에 관해 알고 싶다면 아래를 참고하세요.
    [HTML](http://rmarkdown.rstudio.com/html_document_format.html),
    [PDF](http://rmarkdown.rstudio.com/pdf_document_format.html),
    [Word](http://rmarkdown.rstudio.com/word_document_format.html),
    [Markdown](http://rmarkdown.rstudio.com/markdown_document_format.html),
    and [Tufte
    Handout](http://rmarkdown.rstudio.com/tufte_handout_format.html).

-   R 마크다운으로 문서를 작성하면 Presentation파일로 쉽게 만들 수 있습니다. 
    [ioslides](http://rmarkdown.rstudio.com/ioslides_presentation_format.html),
    [Slidy](http://rmarkdown.rstudio.com/slidy_presentation_format.html),
    [Beamer](http://rmarkdown.rstudio.com/beamer_presentation_format.html)

이제 어느정도 학습을 하였다면 지금부터는 깊이있는 학습으로 인도합니다.

-   The website for the [knitr package](http://yihui.name/knitr/). Knitr는 내제된 동적 컨텐츠 생성을 위한 매우 강력한 도구입니다. 이 곳에서는 매우 풍부한 관련 자료를 찾아볼 수 있습니다. 

-   [Pandoc
    Markdown](http://rmarkdown.rstudio.com/authoring_pandoc_markdown.html)은 R Markdown 문서로 구현되는 모든 형태의 문서를 찾아볼 수 있습니다.
    
또한 R Markdown developer 문서에서는 

-   재생가능한 문서 템플릿[Document
    Templates](http://rmarkdown.rstudio.com/developer_document_templates.html)

-   문서 포맷 생성 가이드 [Creating New
    Formats](http://rmarkdown.rstudio.com/developer_custom_formats.html)
    for R Markdown

-   [HTML
    Widgets](http://rmarkdown.rstudio.com/developer_html_widgets.html)를 활용한 대화형 콤포넌트 추가하기 
    그리고 [Shiny
    Widgets](http://rmarkdown.rstudio.com/authoring_shiny_widgets.html)

