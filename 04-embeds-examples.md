---
layout: default
title:  Embeds
nav_order: 4
---

# Embedding from your digital collections

When embedding an item the best option is to look for an embed code option for the item you would like to add to your markdown page. You can add html or an iframe directly into Markdown.
____

## YouTube:
Just grab the embed link from the share button, add the iframe to your markdown file.

```html
<iframe width="560" height="315" src="https://www.youtube.com/embed/4xIKR6gpx-I" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```

<iframe width="560" height="315" src="https://www.youtube.com/embed/4xIKR6gpx-I" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



## Embedding a slide deck:  

### Google slides

In Google Slides, go to File, Publish to Web, Embed and publish your slides. Copy the embed code then paste the code into your Markdown file:

```html
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRda_iDkyPInOqL1YLCejV-9djrF9_a_DVQSNM8wUXn6n-qLGVfbDPr1SC0UWFl5RwaL8HSta4a4rUx/embed?start=false&loop=false&delayms=60000" frameborder="0" width="625" height="352" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
```

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRda_iDkyPInOqL1YLCejV-9djrF9_a_DVQSNM8wUXn6n-qLGVfbDPr1SC0UWFl5RwaL8HSta4a4rUx/embed?start=false&loop=false&delayms=60000" frameborder="0" width="625" height="352" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>




## From a digital repository:

```html
<iframe src="https://widgets.figshare.com/articles/6229142/embed?show_title=1" width="568" height="351" allowfullscreen frameborder="0"></iframe>
```

<iframe src="https://widgets.figshare.com/articles/6229142/embed?show_title=1" width="568" height="351" allowfullscreen frameborder="0"></iframe>


## A digital map:

**Basic Map**

We'll start with a basic map. Once you've saved any map in ArcGIS Online, you can get it's embed code by clicking Share. Because you can add HTML directly to Markdown, just paste the code provided by AGOL directly into the Markdown file:

```
<style>.embed-container {position: relative; padding-bottom: 80%; height: 0; max-width: 100%;} .embed-container iframe, .embed-container object, .embed-container iframe{position: absolute; top: 0; left: 0; width: 100%; height: 100%;} small{position: absolute; z-index: 40; bottom: 0; margin-bottom: -15px;}</style><div class="embed-container"><iframe width="500" height="400" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" title="CU Aerial Photo Collection (final)" src="//ucboulder.maps.arcgis.com/apps/Embed/index.html?webmap=68fe25f1df2149878fa88e15a4044d52&extent=-108.1261,38.2881,-101.4079,41.3297&zoom=true&previewImage=false&scale=true&disable_scroll=true&theme=light"></iframe></div>
```

<style>.embed-container {position: relative; padding-bottom: 80%; height: 0; max-width: 100%;} .embed-container iframe, .embed-container object, .embed-container iframe{position: absolute; top: 0; left: 0; width: 100%; height: 100%;} small{position: absolute; z-index: 40; bottom: 0; margin-bottom: -15px;}</style><div class="embed-container"><iframe width="500" height="400" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" title="CU Aerial Photo Collection (final)" src="//ucboulder.maps.arcgis.com/apps/Embed/index.html?webmap=68fe25f1df2149878fa88e15a4044d52&extent=-108.1261,38.2881,-101.4079,41.3297&zoom=true&previewImage=false&scale=true&disable_scroll=true&theme=light"></iframe></div>


**Embedding a StoryMap**

Want to embed a Story Map? Same exact procedure. Replace everything after `src=` and before </iframe> with the url for the Story Map:

```
<style>.embed-container {position: relative; padding-bottom: 80%; height: 0; max-width: 100%;} .embed-container iframe, .embed-container object, .embed-container iframe{position: absolute; top: 0; left: 0; width: 100%; height: 100%;} small{position: absolute; z-index: 40; bottom: 0; margin-bottom: -15px;}</style><div class="embed-container"><iframe src="https://storymaps.arcgis.com/stories/f75b31829f5744809834231307484682" width="100%" height="500px" frameborder="0" allowfullscreen allow="geolocation"></iframe></div>
```


<style>.embed-container {position: relative; padding-bottom: 80%; height: 0; max-width: 100%;} .embed-container iframe, .embed-container object, .embed-container iframe{position: absolute; top: 0; left: 0; width: 100%; height: 100%;} small{position: absolute; z-index: 40; bottom: 0; margin-bottom: -15px;}</style><div class="embed-container"><iframe src="https://storymaps.arcgis.com/stories/f75b31829f5744809834231307484682" width="100%" height="500px" frameborder="0" allowfullscreen allow="geolocation"></iframe></div>

*Note: if you want to enable scrolling, you'll need to set the following: `scrolling="yes"`. This is in the iframe code.
