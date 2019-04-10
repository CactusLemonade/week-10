# Week 10<br>Web Maps, Observable, and Javascript

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MUSA-620-Spring-2019/week-10/master?filepath=lecture-10.ipynb)

## Updating your local environment

There is one new package we'll need this week so we'll need
to update your Python environment.

### Option 1

From the Anaconda Prompt or Terminal, run

```
conda activate musa-620
conda install -c conda-forge folium
```

### Option 2

The `environment.yml` in this repository
contains all of the necessary packages. To update your local environment:

**Step 1.** Download the `environment.yml` file in this repository to your computer.

**Important:** Make sure you download the **raw** version of the file from GitHub and that the file extension on your computer is `.yml`.

**Step 2.** From either the Anaconda Prompt (Windows) or Terminal app (MacOS):

```
conda env update --file environment.yml --name musa-620
```

where `musa-620` should be the same name of the environment you have been using.

## Reference

- folium
  - [Documentation](https://python-visualization.github.io/folium/index.html#)
  - [Good example use case](http://andrewgaidus.com/leaflet_webmaps_python/)
- Observable / Javascript
- leaflet
  - [Documentation](https://leafletjs.com/reference-1.4.0.html)
  - [Tutorials](https://leafletjs.com/examples.html)
  - [Leaflet Tile Providers](https://leaflet-extras.github.io/leaflet-providers/preview/)
  - [Leaflet Plugins](https://leafletjs.com/plugins.html)
  - [Leaflet Heat](https://github.com/Leaflet/Leaflet.heat)
- [census-data-downloader](https://github.com/datadesk/census-data-downloader)
- [Vega Color Schemes Reference](https://vega.github.io/vega/docs/schemes/#reference)
- Observable notebooks:
  - [Leaflet](https://observablehq.com/@nickhand/leaflet)
  - [5-minute introduction](https://observablehq.com/@observablehq/five-minute-introduction)
  - [Introduction to Code](https://observablehq.com/@observablehq/introduction-to-code)
  - [Intro to JS/Observable](https://observablehq.com/@nickhand/a-minimal-introduction-to-javascript-and-observable)
  - [Introduction to Notebooks](https://observablehq.com/@observablehq/introduction-to-notebooks)
  - [Observable User Manual](https://observablehq.com/@observablehq/observable-user-manual)
  - [Fork, share, merge](https://observablehq.com/@observablehq/fork-share-merge)
