## casual-markdown-blog (to-be-released)

Build blog site by markdown files. 

1. write blog by markdown (e.g. 20220728-use-markdown-for-blog.md)
2. config site at index.md (title, logo, menu, category, style)
3. update blog index at index.md

### Sample Site 

* [self-host on github](https://raw.githack.com/casualwriter/casual-markdown-blog/main/source/index.html)
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
github  : https://github.com/casualwriter/casual-markdown-blog
title   : Casual-Markdown Sample Blogs 
color-m : BlueViolet
menu    : 
  Home    : index.md
  Dark    : javascript:darkmode()
  About   : about.md
-----------------------------------------------------------------------------
<div id="md-post">

# Archives
   
### Aug 2022
                    
* 2022/08/19: [Markdown as blog](20220819-markdown-as-blog.md) { @campo.jpg, #markdown, #blog }
* 2022/08/10: [Is regexp readable?](20220810-is-regexp-readable.md) { @image.jpg, #regexp, #web-dev }
* 2022/08/03: [My dream web browser](20220803-my-dream-web-browser.md) { @image.jpg, #web, #dev }

### July 2022
                    
* 2022/07/30: [frontmatter for simple YAML](20220730-frontmatter.md) { @pp-web-crawler.jpg, #markdown, #regexp }
* 2022/07/22: [release casual-markdown v0.85](20220722-casual-markdown-v0.85.md) {#featured, #markdown, #regexp, @pp-web-crawler.jpg }

</div>
~~~ 


### History

* 2022/08/19: a roughly version, minor revised from [casual-markdown-page](https://github.com/casualwriter/casual-markdown-page)
* todo: 
* todo: more customized options
 
