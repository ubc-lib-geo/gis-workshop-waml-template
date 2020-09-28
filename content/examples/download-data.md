---
layout: default
title: Data Downloads
parent: Example Pages
nav_order: 5
---
# Data downloads
GitHub.com allows you to upload data files to your repositories. While the platform works best with text-based files, you can still upload .zipped Shapefiles or images and store them too. Just be aware that [GitHub recommends keeping your repos less than 1GB](https://docs.github.com/en/free-pro-team@latest/github/managing-large-files/what-is-my-disk-quota#file-and-repository-size-limitations) in total file size.

Since our beloved .geojson is text-based, it renders really well in the GitHub UI – [like this geojson of UBC's buildings](https://github.com/UBCGeodata/ubc-geospatial-opendata/blob/master/ubcv/locations/geojson/ubcv_buildings.geojson). However, if you want someone to download the file in your workshop, you'll need to provide a link.

Best practice is to transfer your data files as one (or a minimal) zipped package of content. This way you can preserve a directory structure and avoid losing any auxiliary files. The downside is that GitHub won't render them in the browser (╯°□°)╯︵ ┻━┻
{: .note}

## Linking your data for download

To be able to link your data, you'll just need the path from the page you're providing the link to the file itself.

This
```
[Download Data](../data/us-national-parks.geojson)
```
Will provide a link like this:

[Download Data](../data/us-national-parks.geojson)

## Adding a button
Maybe you want that link to look more apparent?? Well, why not try a button!

```
[Download Data](../data/us-national-parks.geojson){: .btn .btn-blue }
```
Looks like:    

[Download Data](../data/us-national-parks.geojson){: .btn .btn-blue }


## Adding a .pdf
