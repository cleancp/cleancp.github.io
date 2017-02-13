---
layout: post
title:  "欢迎来到RocZou的个人技术博客"
date:   2017-02-14
excerpt: "Welcome to RocZou‘s personal technolgy blog"
tag:
- welcome 
- personal
- technolgy
- blog
- jekyll
comments: true
---

开始个人博客第一天
Don't Too Much Talk Show With Me;


Jekyll使用

## HTML Elements

{% highlight html linenos %}
# Heading 1
{% endhighlight %}
# Heading 1

{% highlight html linenos %}
## Heading 2
{% endhighlight %}
## Heading 2

{% highlight html linenos %}
### Heading 3
{% endhighlight %}
### Heading 3
### Body text

{% highlight html linenos %}
#### Heading 4
{% endhighlight %}
#### Heading 4

{% highlight html linenos %}
##### Heading 5
{% endhighlight %}
##### Heading 5

{% highlight html linenos %}
###### Heading 6
{% endhighlight %}
###### Heading 6

{% highlight html linenos %}
**This is strong**
{% endhighlight %}
**This is strong**

{% highlight html linenos %}
![Smithsonian Image](https://mmistakes.github.io/minimal-mistakes/images/3953273590_704e3899d5_m.jpg)
{: .image-right}
{% endhighlight %}
![Smithsonian Image](https://mmistakes.github.io/minimal-mistakes/images/3953273590_704e3899d5_m.jpg)
{: .image-right}

{% highlight html linenos %}
*This is emphasized*
{% endhighlight %}
*This is emphasized*


### Blockquotes
{% highlight html linenos %}
> Lorem ipsum dolor sit amet, test link adipiscing elit. Nullam dignissim convallis est. Quisque aliquam.
{% endhighlight %}
> Lorem ipsum dolor sit amet, test link adipiscing elit. Nullam dignissim convallis est. Quisque aliquam.

## List Types

### Ordered Lists
{% highlight html linenos %}
1. Item one
   1. sub item one
   2. sub item two
   3. sub item three
2. Item two
{% endhighlight %}
1. Item one
   1. sub item one
   2. sub item two
   3. sub item three
2. Item two

### Unordered Lists
{% highlight html linenos %}
* Item one
* Item two
* Item three
{% endhighlight %}
* Item one
* Item two
* Item three

## Tables
{% highlight html linenos %}
| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|----
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=====
| Foot1   | Foot2   | Foot3
{: rules="groups"}
{% endhighlight %}
| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|----
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=====
| Foot1   | Foot2   | Foot3
{: rules="groups"}


## Code Snippets
{% highlight html linenos %}
{% highlight css %}
#container {
  float: left;
  margin: 0 -240px 0 0;
  width: 100%;
}
{% endhighlight %}
{% endhighlight %}

{% highlight css %}
#container {
  float: left;
  margin: 0 -240px 0 0;
  width: 100%;
}
{% endhighlight %}
## Buttons
{% highlight html linenos %}
`.btn`
{% endhighlight %}
`.btn`

{% highlight html %}
<a href="#" class="btn btn-success">Success Button</a>
{% endhighlight %}

<div markdown="0"><a href="#" class="btn">Primary Button</a></div>
<div markdown="0"><a href="#" class="btn btn-success">Success Button</a></div>
<div markdown="0"><a href="#" class="btn btn-warning">Warning Button</a></div>
<div markdown="0"><a href="#" class="btn btn-danger">Danger Button</a></div>
<div markdown="0"><a href="#" class="btn btn-info">Info Button</a></div>

## KBD

You can also use `<kbd>` tag for keyboard buttons.

{% highlight html %}
<kbd>W</kbd><kbd>A</kbd><kbd>S</kbd><kbd>D</kbd>
{% endhighlight %}

Press <kbd>W</kbd><kbd>A</kbd><kbd>S</kbd><kbd>D</kbd> to move your car. **Midtown Maddness!!**

## Notices

**Watch out!** You can also add notices by appending `{: .notice}` to a paragraph.
{: .notice}
