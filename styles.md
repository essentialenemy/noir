---
layout: page
title: Styles
---

<p class="message">
  <small>This page serves to document the style of various elements used in the site's design.</small>
</p>

## <small>THIS IS A HEADER</small>

This is the font, size, color and spacing of regular ol' paragraph <p> text. Using Markdown makes it dead simple
to make text *italic*, **bold** or ***bold and italic***.

term
: *definition*

If you want to reference a footnote it appears like this[^1] in a sentence.

<figure>
  <img src="/assets/test.png" alt="Testing">
  <figcaption>Here is an image with a caption below it.</figcaption>
</figure>

Quotes look nice:

>"My fellow Americans, we are and always will be a nation of immigrants. We were strangers once, too."
>
><cite>~ Barack Obama</cite>

So do tables:

| This          | Is A          | Table |
| ------------- |:-------------:| -----:|
| Column 1      | happens to be | left-aligned |
| Column 2      | is the one    |  that's centered |
| Column 3      | is actually    |    right-aligned |

Here are the buttons whose class names and colors can be easily customized:

<span class="added">added</span> This span class is named "added" but you can change it.

<span class="removed">removed</span> This span class is named "removed" but you can change it.

<span class="improved">improved</span> This span class is named "improved" but you can change it.

<span class="fixed">fixed</span> This span class is named "fixed" but you can change it.

<span class="soon">coming soon</span> This span class is named "soon" but you can change it.


Remember to buy:
1. Milk
2. Bread
3. Eggs

Don't forget:
- To review all code
- Write up the changelog
- Make coffee when you're done

To Do:
- [x] Update Homebrew
- [ ] Update all of your gem dependencies
- [x] Drag your feet on updating gem dependencies 

Here are the message boxes with the optional close button enabled:

<p class="message"><span class="closebtn" onclick="this.parentElement.style.display='none';">&times;</span><small><b>Message:</b> This is a sentence inside of a message box.</small></p>
<p class="green"><span class="closebtn" onclick="this.parentElement.style.display='none';">&times;</span><small><b>Success!</b> This is a sentence inside of a message box.</small></p>
<p class="yellow"><span class="closebtn" onclick="this.parentElement.style.display='none';">&times;</span><small><b>Caution!</b> This is a sentence inside of a message box.</small></p>
<p class="orange"><span class="closebtn" onclick="this.parentElement.style.display='none';">&times;</span><small><b>Warning!</b> This is a sentence inside of a message box.</small></p>
<p class="red"><span class="closebtn" onclick="this.parentElement.style.display='none';">&times;</span><small><b>Danger!</b> This is a sentence inside of a message box.</small></p>
<p class="purple"><span class="closebtn" onclick="this.parentElement.style.display='none';">&times;</span><small><b>Please Note:</b> This is a sentence inside of a message box.</small></p>
<p class="blue"><span class="closebtn" onclick="this.parentElement.style.display='none';">&times;</span><small><b>Information:</b> This is a sentence inside of a message box.</small></p>

Try to only eat an entire bag of candy once a ~~week~~ month.

If you include any inline `code` it looks awesome.

A code block highlights the [syntax](https://en.wikipedia.org/wiki/Syntax_(programming_languages)) and displays the language:

{% highlight ruby %}
def test(a=1,b=2,c=a+b)
  puts "#{a},#{b},#{c}"
end
test        =>  1,2,3
test 5      =>  5,2,7
test 4, 6   =>  4,6,10
test 3, 4, 6   =>  3,4,6
{% endhighlight %}

 

***

[^1]: When a footnote is clicked or tapped on it will be highlighted and outlined Wikipedia-style.