---
layout: post
title: Introducing Noir
date: 2020-01-01 10:00:00
---

Noir is an automatic dark mode adaptation of the [Poole theme](https://github.com/poole/poole) for [Jekyll](https://github.com/jekyll/jekyll).

Noir includes all of the original features from the Poole theme, such as:

* Complete Jekyll setup included (layouts, config, [404]({{ site.baseurl }}/404.html), [RSS feed]({{ site.baseurl }}/feed.xml), posts, and [example page]({{ site.baseurl }}/about))
* Mobile friendly design and development
* Easily scalable text and component sizing with `rem` units in the CSS
* Support for a wide gamut of HTML elements
* Related posts (time-based, because Jekyll) below each post
* Syntax highlighting, courtesy Jekyll's built-in support for Rouge

It goes a step further and adds some awesome things[^1] which make it even better though. The biggest one? Having automatic dark mode support which, 
depending on the device's setting changes the color of the background, text, masthead, headers, blockquotes, lists, inline code, pagination, tables, etc.

![](/assets/splash.png)

Noir also expands upon message blocks by adding some color and style to go along with them plus the ability to add a close button to the block if desired.

<p class="warning"><small><b>Warning!</b> You could use this to warn the reader about something important.</small></p>

<p class="info"><small><b>Information:</b> Make this information stand out by putting it in a message block.</small></p>

<p class="success"><small><b>Success!</b> If you placed your laptop in boiling water as instructed it should be ruined now.</small></p>

<p class="danger"><small><b>Danger!</b> If your data backups are in the same physical location it doesn't count!</small></p>

To include the ability to close the message block just use the following `span`:

{% highlight html %}
<span class="closebtn" onclick="this.parentElement.style.display='none';">&times;</span>
{% endhighlight %}

<p class="info"><span class="closebtn" onclick="this.parentElement.style.display='none';">&times;</span>
<small><b>Hello!</b> Look at me, I'm a special message with a close button.</small></p>

Noir is developed using and hosted with GitHub. You can head on over to the [GitHub repository]({{ site.github.repo }}) to download it, report any bugs, and to request features.

Thank you so much for your interest in this theme!

***
[^1]: Like this Wikipedia-style highlighting of the currently active footnote.
