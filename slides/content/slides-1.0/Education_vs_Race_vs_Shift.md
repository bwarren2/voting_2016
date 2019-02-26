---
title: "Education vs Race vs Republican Shift"
date: 2019-02-13T01:56:00-05:00
draft: false
author: "Ben"
---

# Comparing Three Variables At Once

<div style="display: block;margin-left: auto; margin-right: auto;">
<iframe width="800" height="800" frameborder="0" scrolling="no" src="//plot.ly/~bwarren2/2.embed"></iframe>
</div>

## Methods

This is a plotly 3D scatterplot of the two previous variables and the calculated Republican shift.  Putting them on the same plot at the same time makes it possible to easily see how the two variables are interacting.

## Results

Some observations immediately jump off of the page:

### A plane describes most of the points outside of the high-white, high-high-school-only area

If you had to draw a flat surface to approximate most of the plot, it would have a positive slope in the education dimension (more high-school-only-educated people means more Republican shift) and very little slope in the % white dimension (having fewer minority people doesn't change things much).

### Something weird is happening in the high-white, high-high-school-only area

Especially in the 93%+ white area, there are many points above the plane formed by the rest of the plot.  What exactly that area _is_ is in the next few slides.

### Education explains noise in the race chart

 * The "noise" we saw when looking at "% of county that is white" vs shift below 93%ish white is actually explained in the education dimension.  If you pick a region below that threshold, like the 40-60% range, you can see that as "% of county that is only high-school educated" increases, we get more shift, and that shows up as merely a cloud of points when you only look at % white vs shift

## Next Steps

So where are the places in that anomalous area?
