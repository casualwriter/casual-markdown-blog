## casual-markdown-blog (to-be-released)

Build blog site by markdown files. 

1. write blog by markdown (e.g. 20220728-use-markdown-for-blog.md)
2. config site at index.md (title, logo, menu, category, style)
3. update blog index at index.md

### Sample Site 

* [Casual-Markdown Sample Blog](https://casualwriter.github.io/casual-markdown/blog)
* [Casualwriter's Blog](https://casualwriter.github.io/blog)

### Usage Guide

simply put copy [index.html](https://github.com/casualwriter/casual-markdown-page/blob/main/source/index.html) 
or all-in-one version [index-one.html](https://github.com/casualwriter/casual-markdown-page/blob/main/source/index-one.html) 
to web server. 

* config site at index.md (title, logo, menu, category, style)
* update blog index at index.md
                                          
below is index.md for [Casual-Markdown Sample Blog](./blog)
 
~~~  
-----------------------------------------------------------------------------
github  : https://github.com/casualwriter/casual-markdown 
title   : Casual-Markdown Sample Blogs 
style   : #header { background: linear-gradient(to bottom right, #06c, #fc0); }
menu    : 
  Search  : .
  List    : .
  About   : about.md
-----------------------------------------------------------------------------
   
## Highlight

- 2021/07/20: [powerpage web crawler](20210720-powerpage-web-crawler.md) ![](pp-web-crawler.jpg)
- 2022/07/22: [release casual-markdown v0.85](20220722-casual-markdown-v0.85.md) 

### July 2022
                    
* 2022/07/30: [frontmatter for simple YAML](20220730-frontmatter.md) {#markdown,#regexp,@pp-web-crawler.jpg}
* 2022/07/22: [release casual-markdown v0.85](20220722-casual-markdown-v0.85.md) {#markdown,#regexp,@pp-web-crawler.jpg}
* 2022/07/19: [about table-of-content](20220719-table-of-content.md) {#markdown,#regexp,@pp-web-crawler.jpg}

### Oct 2021

* 2021/10/20: [simple markdown parser](20211020-simple-markdown-parser.md) {#markdown,#regexp,@image.jpg}
* 2021/07/20: [powerpage web crawler](20210720-powerpage-web-crawler.md) ![](pp-web-crawler.jpg)
* 2021/06/18: [develop html/css/jsavscript application by PowerPage](20210618-html-app-by-powerpage.md) ![](powerpage.jpg)

~~~ 


### To-Do

* todo: code casual-markdown-blog.html for basic blogs site
* todo: more customized options
 
