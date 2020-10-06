---
layout: default
title: Web Maps
parent: Example Pages
nav_order: 7
---
# Adding an OpenIndexMap web map

You add web maps of just about any kind to your site, however it does require some extra files and customization. As a basic example, let's demonstrate a web map powered by Leaflet.js which displays an index map in the OpenIndexMap (OIM) content format standard.

In this case we've created 2 extra files called `oim-index.js` and `oim-map.html` – which are located in your sites `content/data/`:

```
├── content
│   ├── data
│   │   ├── oim-index.js
│   │   ├── oim-map.html
│   │   └── ...
```
### oim-index.js

The `oim-index.js` file is a JavaScript file containing only one variable - the .geoJson-structured information for your (OIM) index map. In this case we're using an index for a series of maps showing the forest cover of British Columbia in the 1950s, but you can swap .geoJson text for any OIM index you have.

Your index map must have OIM standard fields or it wont work.
{: .danger}

### oim-map.html

The `oim-map.html` file is your map document, which displays at full size. [Here's a direct link](../data/oim-map.html){:target="_blank"}.

We can also add a "window" to that map on any Markdown document by using an `<iframe>`.

For instance this: `<iframe src="../data/oim-map.html" height="500"></iframe>`

Will give you this:

<iframe src="../data/oim-map.html" height="500" width="100%"></iframe>
