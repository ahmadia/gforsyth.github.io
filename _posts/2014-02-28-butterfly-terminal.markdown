---
layout: post
title: Butterfly Terminal in your Browser
date: 14-02-28 14:38:06 
categories: commandline, tools
---

[paradoxxxzero](http://paradoxxxzero.github.io/2014/02/28/butterfly.html) has just offered up a beautiful web browser terminal called **butterfly**.   

It supports quick selection from your prompt history, hitting **CTRL+SHIFT+up** will let you select any output in the terminal window and hitting **ENTER** will push it through to the prompt.  

It's still having some weird issues with vim on my machine, but even so this is going to be a pinned tab in my browser for a while to come.  Check it out!

{% highlight python %}
sudo pip install butterfly
butterfly.server.py     #launch server
{% endhighlight %}
   
![It's so pretty](/assets/butterfly.png)
