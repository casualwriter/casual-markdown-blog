## Is RegExp readable?

![](campo03.jpg)

Of course not! But does RegExp make the code not readable?

I learned RegExp by coding a [markdown parser](https://github.com/casualwriter/casual-markdown). love it!

When I review the code, agree that reading RegExp is really pain in the ass, but it doesnot mess up the code. 
On the contrary, it make the code structure more clear!

for example:

~~~ RegExp
-- parse syntax "[text](link)"
mdstr = mdstr.replace( /\[(.*?)\]\((.*?)\)/gm, '<a href="$2">$1</a>')
mdstr = mdstr.replace( /\n/, '<br>' )
~~~

~~~ normal
-- code in another style
var md_str = "this is a test\n test for [text](http://link) lin synatx"

var lines = md_str.split('\n')
var pos1, pos2, pos3

for (var i=0; i<lines.length; i++) {
  pos1 =  lines[i].indexOf( '[' )
  pos2 =  lines[i].indexOf( '](', pos1 )
  pos3 =  lines[i].indexOf( ')', pos3 )
  if (pos1>0 && pos2>0 && pos3>0) {
    lines[i] = lines[i].substr( 0, pos1 ) + '<a href="' 
           + lines[i].substr( pos2+2, pos3-pos2-2 )
           + '">' + lines[i].substr( pos1+1, pos2-pos1-1 ) + '</a>'
  } 
}

md_str = lines.join('<br>')
~~~

I prefer to read the first code if donot need to figure out how regexp work.

I finally realized that make the code not readable is the "Complexity" instead of "RegExp". 
"RegExp" solve the problem, and compress the "Complexity" in a piece of code. That's why it is hard to read!


(2022/08/26, hk)
