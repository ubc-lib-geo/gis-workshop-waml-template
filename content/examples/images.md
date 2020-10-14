---
layout: default
title: Images
parent: Example Pages
nav_order: 1
---
# Adding images to your page

#### Adding an image is super easy! Here are a few methods
[View the source Markdown for this page](https://raw.githubusercontent.com/ubc-lib-geo/gis-workshop-waml-template/master/content/examples/images.md)

___

**Add an image from the web:**

Start an in-line link with an exclamation point then place the alt text in the brackets followed by the image link in the parentheses:

```
![WAML Logo](http://www.waml.org/groundwork-master/images/wamllogo200_15.jpg)
```

![WAML Logo](http://www.waml.org/groundwork-master/images/wamllogo200_15.jpg)

You can also add images "reference style." This is handy if you don't want to clutter up your Markdown. You can just place the references at the bottom of the page. It goes like this:

```
![Point Sublime][Sublime]

[Sublime]: http://www.waml.org/groundwork-master/images/grndcnyn.jpg
```

![Point Sublime][Sublime]

Nice job!

___  

**Add an image from your directory:**

You can also add images from a file directory. If you're using GitHub Pages, that means you would want a folder where your content or images live in your GitHub repository. The syntax is the same, except replace the link with the path to the image:

```
![Steezy WAML Logo](../img/WAML_sticker_stylized_serif.png)
```

![Steezy WAML Logo](../img/WAML_sticker_stylized_serif.png)

Sweet!

___

**Add a different format:**

Want to put a gif in there? No problem!

```
![Surfer Boy](https://media.giphy.com/media/dJUtqIcqeyMvK/giphy.gif)
```

![Surfer Boy](https://media.giphy.com/media/dJUtqIcqeyMvK/giphy.gif)

"gif" is pronounced with a hard "g"
{: .note}

___

**Link an image:**

To link an image, you just need to embed the image syntax within the syntax for a hyperlink:

Here's a regular link:

```
[WAML Conference 2020](http://www.waml.org/conf)
```

[WAML Conference 2020](http://www.waml.org/conf)

Here's a linked image:

```
[![WAML Logo](http://www.waml.org/groundwork-master/images/wamllogo200_15.jpg)](http://www.waml.org/conf)
```

[![WAML Logo](http://www.waml.org/groundwork-master/images/wamllogo200_15.jpg)](http://www.waml.org/conf)

_Click Me!_

So easy, right?!

____

**Need to get extra fancy?**

You can also add html directly to Markdown. Say you wanted to change the size of an image, for example.

```
<img src='../img/WAML_sticker_stylized_serif.png' width='250' alt='WAML sticker'>
```

<img src='../img/WAML_sticker_stylized_serif.png' width='250' alt='WAML sticker'>

Aren't you so fancy!!

![So Fancy](https://media.giphy.com/media/i5gAt8Fq6xl9C/giphy.gif)

<!--reference links-->
[Sublime]: http://www.waml.org/groundwork-master/images/grndcnyn.jpg
