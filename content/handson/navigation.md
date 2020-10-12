---
layout: default
title: Change Navigation
parent: Hands On
nav_order: 6
---
# Change the Navigation Order

You've noticed that this page is all the way at the bottom of the navigation menu. Let's change that so the page is just below the land acknowledgements.

The navigation structure and functionality is inherent of the Just the Docs theme. [Full documentation can be found here](https://pmarsceill.github.io/just-the-docs/docs/navigation-structure/).
{: .note}

Your page's Front Matter includes a parameter for `nav_order`. As you might assume, the value after this parameter determines where it falls in the navigation order. Right now our page's Front Matter looks like this:   

```
---
layout: default
title: Your New Page's Title
nav_order: 11
---
```
### *1*{: .circle .circle-blue} Change your `nav_order` to 2.5

Our navigation order is already set, so you might think that inserting one page it will require you to +1 to the nav_order of all of the files that come after it. But, since Just the Docs allows us to use floating point values, we can add a decimals to the nav_order value and insert pages at .5 increments.

This is probably not the best practice since it may get confusing later on if you choose to insert many additional pages and need to keep track of your significant figures. But the workshop instructors like to live in the moment and so it's what we're doing for this hands-on session.
{: .warn}

### *2*{: .circle .circle-blue} Change your page title

The Front Matter also includes a value for the page `title`. The page title is used for what shows up in the navigation, among other things. Let's change the default title to:

`Favorite Map`

Now you should commit your changes, count to 30, then refresh your browser to see the changes.
