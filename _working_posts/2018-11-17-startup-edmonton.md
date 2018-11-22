---
layout: post
title: General Value Functions; Beyond the Reward Signal in Reinforcement Learning
tags: [AI, RL, GVF]
---



Recently, I gave a talk at Startup Edmonton on General Value Functions, and because of the great feedback and interest in the topic I thought it a prime candidate for a blog post (of course with extended content).


# A brief brief on Reinforcement Learning 



# General Value Functions

So what is a General Value Function, and what makes them so general?


# Some Example Applications

Horde and Nexting

Laser Welding

Neuroprotheses

Pavlovian Control

# Some Architectures

# To the Future



Jekyll supports the use of [Markdown](http://daringfireball.net/projects/markdown/syntax) with inline HTML tags which makes it easier to quickly write posts with Jekyll, without having to worry too much about text formatting. A sample of the formatting follows.

Tables have also been extended from Markdown:

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

Here's an example of an image, which is included using Markdown:

![Image of a glass on a book]({{ site.baseurl }}/assets/img/pexels/book-glass.jpeg=250x)

Highlighting for code in Jekyll is done using Base16 or Rouge. This theme makes use of Rouge by default.

{% highlight js %}
// count to ten
for (var i = 1; i <= 10; i++) {
    console.log(i);
}

// count to twenty
var j = 0;
while (j < 20) {
    j++;
    console.log(j);
}
{% endhighlight %}

Type on Strap uses KaTeX to display maths. Equations such as $$S_n = a \times \frac{1-r^n}{1-r}$$ can be displayed inline.

Alternatively, they can be shown on a new line:

$$ f(x) = \int \frac{2x^2+4x+6}{x-2} $$
