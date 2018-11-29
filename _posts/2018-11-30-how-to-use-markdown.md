---
title: "How to use Markdown"
date: 2018-11-30 07:05:00: -0000
categories: markdown
---
#How to use Markdown
[TOC]
##Highlight
`**Bold**` **Bold**
`*Emphasize*` *Emphasize*
`++Underline++` ++Underline++
`==Highlight==` ==Highlight==
`~~Strikethorough~~` ~~Strikethorough~~
`^superscript^` ^superscript^
`~subscript~` ~subscript~

##Link
`[bifam](바이팜.kr)` [bifam](바이팜.kr)

`@[bifam](바이팜.kr, 'BIFAM')` @[bifam](바이팜.kr, 'BIFAM')

`![google](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png "Google")` 
![google](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png "Google")

######Another Link usage
<pre>
[link1](thisIsLink1)
[link2](thisIsLink2)
[link3](thisIsLink3)

[thisIsLink1]:	https://jekyllrb.com
[thisIsLink2]:	https://github.com
[thisIsLink3]:	https://ep1stas1s.github.com
</pre>

[link1](thisIsLink1)
[link2](thisIsLink2)
[link3](thisIsLink3)

[link1]:	https://jekyllrb.com
[link2]:	https://github.com
[link3]:	https://ep1stas1s.github.com


##Code Review
`<pre><code> import... </code></pre>`or
<pre>
```
import...
```
</pre>
<pre><code>import java.util.*

class Main{
	public static void main(String[] args){
    	System.out.println("Hellow World")
    }
}
</code></pre>


##Order List
`1. list...`
1. list1
2. list2

` * list... or - list...`
* list1
* list2




##Check Box
`- [ ] checkbox...` 
- [ ] checkbox1

`- [x] checkbox...` 
- [x] checkbox2

##Table
<pre>| column | column |
|--------|--------|
| table1 | table2 |</pre>

| column | column |
|--------|--------|
| table1 | table2 |

##Break line
`* * *`
* * *
`- - -`
- - -
`---`

---
`<hr>`
<hr>










