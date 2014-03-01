---
layout: post
title: Installing JSAnimation for IPython Notebooks
date: 14-03-01 16:31:12 
categories: instructions, reference
---

To enable javascript animations in IPython Notebooks, first download the package from [Jake Vanderplas' Github](https://github.com/jakevdp/JSAnimation) by running:

{% highlight bash %}
git clone https://github.com/jakevdp/JSAnimation.git
{% endhighlight %}

To install the library for Python2.7-ish run

{% highlight python %}
cd JSAnimation/
sudo python2 setup.py install
{% endhighlight %}

You can then enable JSAnimation within an IPython notebook with

{% highlight python %}
from JSAnimation.IPython_display import display_animation
{% endhighlight %}


