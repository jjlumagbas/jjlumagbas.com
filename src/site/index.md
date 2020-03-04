---
title: Hi, I'm JJ
subtitle: I'm a <strong>Front End Developer</strong> specializing in <strong>Interactive Data Visualizations</strong>
layout: layouts/base.njk
---

I work with the **Scaling Science** project at **[MIT Media Lab](https://www.media.mit.edu/)**, building internal visualization tools to help researchers explore a large, graph-based data set.

A lot of the project is still pre-publication, unfortunately, so I can't share too many details about it. I do have permission though to share some demos of prototypes we're working on. I collaborated on the design of these visualizations, and built them using [D3.js](https://d3js.org/).

### [Bubble chart with clustering options →](https://viz-gnosfwkwfc.now.sh/)

Features:

- A slider to show change over time
- Assign a different variable to color
- Clustering options
- Clickable circles to show lablels (so you can track changes to that circle)

### [Network diagram with dynamic addition/removal of nodes →](https://local-community.jjlumagbas.now.sh/)

Features: 

- A slider to show change over time (again)
- Pan and zoom (scroll on desktop, pinch on mobile)


### [2D Range slider →](https://2d-rangeslider-qyuheaispc.now.sh/)

I built a control input that would select weights of multiple variables simultaneously by dragging a circle around. Inspired by the control input at [Gen Studio](https://gen.studio/map/%3Fid%3D9405%26ids%3D%5B9405%2C9232%2C22848%2C8396%2C751402%2C79226%5D), and extended so you can change the number of variables dynamically.


### [Wealth of Nations chart in D3.js and VueJS →](https://upbeat-lumiere-3c2320.netlify.com/)

This is a recreation of [Hans Rosling's famous chart](https://www.ted.com/talks/hans_rosling_the_best_stats_you_ve_ever_seen) showing the change over time in a country's income per capita (x-axis) in relation to life-expectancy (y-axis). (Size of a circle is a country's population.)

Using VueJS, I implemented the display of the SVG circles, and the interactive year scrubber. Most of the [D3 code is from Mike Bostock](https://observablehq.com/@mbostock/the-wealth-health-of-nations).

This demo shows you can use D3's awesome utilities to do all the hard math stuff (e.g. scaling), while leveraging the reactive nature of VueJS for chart updates in response to user inputs.