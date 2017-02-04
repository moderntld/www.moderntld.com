---
layout: post
title:  "Testing GitHub Flavored Markdown"
date:   2015-10-10 19:37:30
categories: jekyll
---
Jekyll is simple but powerfull, and can hosted easely on github.
This is cheat codes for creating beautiful article with GFM (Github Flavored Markdown).
For more information about GFM, [click here](https://help.github.com/articles/github-flavored-markdown/).

##### # Links

Example :

[click here](https://github.com/riefachan).

Return :

```
[click here](https://github.com/riefachan)
```


##### # italic

Example :

*this is italic !*

Return :

```
*this is italic !*
```


##### # bold

Example :

**this is bold !**

Return :

```
**this is bold !**
```


##### # List

Example :

* Item 1
* Item 2
* Item 3

Return :

```
* Item 1
* Item 2
* Item 3
```


##### # code

Example :

```
function hello(){
	return "Hello World!";	
}
```

Return :

{% highlight text %}
```
function hello(){
	return "Hello World!";	
}
```
{% endhighlight %}


##### # code (inline)

Example :

`echo "Hello World!";`

Return :

````
`echo "Hello World!";`
````


##### # code (with highlight)

Example :

{% highlight javascript %}
function hello(){
	return "Hello World!";	
}
{% endhighlight %}

Return :

{% highlight text %}
{%raw%}
{% highlight javascript %}
function hello(){
	return "Hello World!";	
}
{% endhighlight %}
{%endraw%}
{% endhighlight %}
