-----------------------------------------------------------------------------
github     : https://github.com/casualwriter/casual-markdown-blog
title      : Casual-Markdown's Blog 
subtitle   : By Casual-Markdown-Blog
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

## [My dream web browser](20220803-my-dream-web-browser.md)
> ![My Dream brwoser](campo02.jpg)
> date: 2022/08/03, tags: `#wev, #dev, #html`
> 
> web browser is a powerful GUI render engine.
> have to work with web-server or web-service for app. dev.
> can we put them all together?


# Archives
   
### Aug 2022
                    
* 2022/08/20: [Markdown as blog](20220820-markdown-as-blog.md) { #markdown, #blog, #featured }
* 2022/08/10: [Is RegExp readable?](20220810-is-regexp-readable.md) { #regexp }
* 2022/08/03: [My dream web browser](20220803-my-dream-web-browser.md) { #web }

### July 2022
                    
* 2022/07/30: [frontmatter for simple YAML](20220730-frontmatter.md) { #markdown, #regexp }
* 2022/07/22: [release of casual-markdown v0.85](20220722-casual-markdown-v0.85.md) { #markdown, #regexp }

### Oct 2021

* 2021/10/20: [Code a markdown editor in 80 lines](20211020-powerpage-markdown-editor.md) { #powerpage, #markdown }
* 2021/07/20: [Crawl blogs by powerpage-web-crawler](20210720-powerpage-web-crawler.md) { #powerpage }
* 2021/06/18: [Develop html application by PowerPage](20210618-powerpage-html-application.md) { #powerpage }

</div>