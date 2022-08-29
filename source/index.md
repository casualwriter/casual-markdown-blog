-----------------------------------------------------------------------------
github     : https://github.com/casualwriter/casual-markdown-blog
title      : Casual-Markdown's Blog 
subtitle   : Simple is the best
nav-group  : featured, new-3, tags, months
nav-width  : 320px
css-header : background:linear-gradient(to bottom right, #06c, #fc0); color:white
menu       : 
   Home    : ?
   github  : https://github.com/casualwriter/casual-markdown-blog
   Dark    : javascript:darkmode()
   About   : ?page=about.md
-----------------------------------------------------------------------------
<style comment="additional style">
#header { {{css-header}}  }
#left-panel  { width:{{nav-width}} }
#right-panel { left: calc({{nav-width}} + 20px) }
h1 { border-bottom:1px dotted grey }
.nav-post a  { color: teal }
.nav-tag  a  { color: #06c }
.nav-month a { color: grey }
.post-date   { font-size:12px; font-weight:400; }
.post-title  { font-size:16px; color:#333 }
.post-tags   { left-margin:20px; padding:4px; font-size:10px; color:green; font-weight:400 }
</style>

<div id="md-post">
# Featured

## [Markdown as blog](20220820-markdown-as-blog.md)
> ![build blog site by markdown files](campo01.jpg)
> date:2022/08/20, tags: `#markdown, #blog`
> 
> build blog site by markdown files in minutes.
> host on github, or other static web hosting  

## [Is RegExp readable?](20220810-is-regexp-readable.md)
> ![does regexp make the code not readable?](campo03.jpg)
> date: 2022/08/10, tags: `#regexp, #web-dev`
> 
> Sure not. But does regexp make the code not readable?


# Archives
   
### Aug 2022
                    
* 2022/08/20: [Markdown as blog](20220820-markdown-as-blog.md) { #markdown, #blog, #featured }
* 2022/08/10: [Is RegExp readable?](20220810-is-regexp-readable.md) { #regexp }

### July 2022
                    
* 2022/07/31: [release of casual-markdown v0.90](20220731-casual-markdown-v0.90.md) { #markdown, #regexp }

### Oct 2021

* 2021/10/28: [Portable lightweight web crawler](20211028-powerpage-web-crawler.md) { #powerpage }
* 2021/10/05: [Develop html application by PowerPage](20211005-powerpage-0.60.md) { #powerpage }

</div>