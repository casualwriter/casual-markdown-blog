## Portable lightweight web crawler


org-post: https://dev.to/casualwriter/a-portable-lightweight-web-crawler-using-powerpage-3o0p

Just code a portable lightweight web crawler using **Powerpage**. 

[Powerpage Web Crawler](https://github.com/casualwriter/powerpage-web-crawler) is a 
portable javascript-application running with [Powerpage](https://github.com/casualwriter/powerpage). 
It is coded by vanilla javascript in about 350 lines codes, without any dependency.

`Powerpage Web Crawler` is a portable program, just simply download and run `powerpage.exe`. 
It is a powerful and easy-to-use web-scrawler suitable for blog site crawling and offline-reading.

Just simply define below, for example

* `base-url` := `https://dev.to/casualwriter`  // the home page of favor blog site
* `index-pattern` := `none`  // RegExp of the url pattern of category page
* `page-pattern` := `/casualwriter/[a-z]` // RegExp of the url pattern of content page
* `content-css` := `#main-title h1, #article-body`  //css selector for blog content. 

Program will
 
* crawl all category pages.
* find out all url of content pages.
* crawl content for one page, or all pages. 
* save setting and links to database (support multiple sites)
* save content pages to local files.
* allow off-line reading from local files.

**About [Powerpage](https://github.com/casualwriter/powerpage)** 

 `Powerpage Web Crawler` run with `PowerPage`, which is a lightweight web browser with DB capability and windows accessibility, for quick development of javascript/html/css application. 

for the source code of **Powerpage**, please visit https://github.com/casualwriter/powerpage/tree/main/source/src


By the way, sorry for beginner coding style and rough screen layout (for independence). 


Enjoy,


----
Screen records:

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/kdc3tpb1hwoc47i6jcsq.gif)







