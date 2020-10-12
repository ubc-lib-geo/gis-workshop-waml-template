---
layout: default
title: ArcGIS Online
parent: Example Pages
nav_order: 3
---
# Embedding ArcGIS Online Content

#### Here's how to add content from ArcGIS online into a Markdown file
___

**Basic Map**

We'll start with a basic map. Once you've saved any map in ArcGIS Online, you can get it's embed code by clicking Share. Because you can add HTML directly to Markdown, just paste the code provided by AGOL directly into the Markdown file:

```html
<style>.embed-container {position: relative; padding-bottom: 80%; height: 0; max-width: 100%;} .embed-container iframe, .embed-container object, .embed-container iframe{position: absolute; top: 0; left: 0; width: 100%; height: 100%;} small{position: absolute; z-index: 40; bottom: 0; margin-bottom: -15px;}</style><div class="embed-container"><iframe width="500" height="400" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" title="CU Aerial Photo Collection (final)" src="//ucboulder.maps.arcgis.com/apps/Embed/index.html?webmap=68fe25f1df2149878fa88e15a4044d52&extent=-108.1261,38.2881,-101.4079,41.3297&zoom=true&previewImage=false&scale=true&disable_scroll=true&theme=light"></iframe></div>
```

<style>.embed-container {position: relative; padding-bottom: 80%; height: 0; max-width: 100%;} .embed-container iframe, .embed-container object, .embed-container iframe{position: absolute; top: 0; left: 0; width: 100%; height: 100%;} small{position: absolute; z-index: 40; bottom: 0; margin-bottom: -15px;}</style><div class="embed-container"><iframe width="500" height="400" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" title="CU Aerial Photo Collection (final)" src="//ucboulder.maps.arcgis.com/apps/Embed/index.html?webmap=68fe25f1df2149878fa88e15a4044d52&extent=-108.1261,38.2881,-101.4079,41.3297&zoom=true&previewImage=false&scale=true&disable_scroll=true&theme=light"></iframe></div>

____

**Embedding an ArcGIS Web App**

ArcGIS Online doesn't always provide embed code for Web Apps, but no matter! Just use the same embed code from above but replace everything after `src=` and before </iframe> with the url for the Web App:

```
<style>.embed-container {position: relative; padding-bottom: 80%; height: 0; max-width: 100%;} .embed-container iframe, .embed-container object, .embed-container iframe{position: absolute; top: 0; left: 0; width: 100%; height: 100%;} small{position: absolute; z-index: 40; bottom: 0; margin-bottom: -15px;}</style><div class="embed-container"><iframe width="500" height="400" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" title="CU Aerial Photo Collection (final)" src="https://ucboulder.maps.arcgis.com/apps/webappviewer/index.html?id=7ef03caa3cd848139ce0e9176da9b7e8"></iframe></div>
```

<style>.embed-container {position: relative; padding-bottom: 80%; height: 0; max-width: 100%;} .embed-container iframe, .embed-container object, .embed-container iframe{position: absolute; top: 0; left: 0; width: 100%; height: 100%;} small{position: absolute; z-index: 40; bottom: 0; margin-bottom: -15px;}</style><div class="embed-container"><iframe width="500" height="400" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" title="CU Aerial Photo Collection (final)" src="https://ucboulder.maps.arcgis.com/apps/webappviewer/index.html?id=7ef03caa3cd848139ce0e9176da9b7e8"></iframe></div>

_Note: this could take some formatting tweaks to get right!_

____

**Embedding a StoryMap**

Want to embed a Story Map? Same exact procedure. Replace everything after `src=` and before </iframe> with the url for the Story Map:

```
<style>.embed-container {position: relative; padding-bottom: 80%; height: 0; max-width: 100%;} .embed-container iframe, .embed-container object, .embed-container iframe{position: absolute; top: 0; left: 0; width: 100%; height: 100%;} small{position: absolute; z-index: 40; bottom: 0; margin-bottom: -15px;}</style><div class="embed-container"><iframe width="500" height="400" frameborder="0" scrolling="yes" marginheight="0" marginwidth="0" title="CU Aerial Photo Collection (final)" src="https://storymaps.arcgis.com/stories/3c38d9c4e2844e25a020eb6bade919b9"></iframe></div>
```


<style>.embed-container {position: relative; padding-bottom: 80%; height: 0; max-width: 100%;} .embed-container iframe, .embed-container object, .embed-container iframe{position: absolute; top: 0; left: 0; width: 100%; height: 100%;} small{position: absolute; z-index: 40; bottom: 0; margin-bottom: -15px;}</style><div class="embed-container"><iframe width="500" height="400" frameborder="0" scrolling="yes" marginheight="0" marginwidth="0" title="CU Aerial Photo Collection (final)" src="https://storymaps.arcgis.com/stories/3c38d9c4e2844e25a020eb6bade919b9"></iframe></div>

*Note: if you want to enable scrolling, you'll need to set the following: `scrolling="yes"`. This is in the iframe code.

Presto!
