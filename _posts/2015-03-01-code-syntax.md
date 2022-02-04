---
title: Code Syntax
published: true
---
To insert highlight code inside of a post, it's enough to use some specific tags, has directly described into the [Jekyll documentation](http://jekyllrb.com/docs/templates/#code-snippet-highlighting). In this way the code will be included into a ``.highlight`` CSS class and will be highlight according to the [syntax.scss](https://github.com/mojombo/tpw/blob/master/css/syntax.css) file. This is the standard style adopted by **Github** to highlight the code. 

This is a CSS example:
{% highlight css linenos %}

body {
  background-color: #fff;
  }

h1 {
  color: #ffaa33;
  font-size: 1.5em;
  }

{% endhighlight %}

And this is a HTML example, with a linenumber:
{% highlight html linenos %}

<html>
  <a href="example.com">Example</a>
</html>

{% endhighlight %}

Last, a Ruby example:
{% highlight ruby linenos %}

def hello
  puts "Hello World!"
end

{% endhighlight %}



## H2 Test
### H3 Test


**BLOD TEST**



[Link Name](https://google.com "Title")

[Link Name only](https://google.com)


![Foto Alt text]({{site.baseurl}}/https://i.imgur.com/fXkrS4l.png)



`test`


```
testasdasd
asdasda
```


``
ashdbjhabsjdha
``




> We loved with a love that was more than love


> PORT   STATE SERVICE VERSION
21/tcp open  ftp     vsftpd 3.0.3
22/tcp open  ssh     OpenSSH 8.2p1 Ubuntu 4ubuntu0.2 (Ubuntu Linux; protocol 2.0)
80/tcp open  http    Apache httpd 2.4.41 ((Ubuntu))

{% highlight ruby linenos %}
ftp <IP adress>
{% endhighlight %}
  
  
  
  
{% highlight ruby linenos %}
  PORT   STATE SERVICE VERSION
21/tcp open  ftp     vsftpd 3.0.3
22/tcp open  ssh     OpenSSH 8.2p1 Ubuntu 4ubuntu0.2 (Ubuntu Linux; protocol 2.0)
80/tcp open  http    Apache httpd 2.4.41 ((Ubuntu))
  
{% endhighlight %} 
  
  
-asdasdasd
- asdasdasdasdasdasd

1.Salam
1. Salamlar



<p>Check out <a href="https://www.freecodecamp.org/">freeCodeCamp</a>.</p>

<a href="https://www.freecodecamp.orga/">freeCodeCamp</a>


<p>Check out <a href="https://www.freecodecamp.org/" target="_blank" rel="noopener noreferrer">freeCodeCamp</a> </p>

<p>Check out <a href="https://www.freecodecamp.org/" target="_blank" rel="noopener noreferrer">freeCodeCamp</a>.</p>


