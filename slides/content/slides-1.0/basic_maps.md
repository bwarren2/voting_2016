---
title: "Basic Performance Analysis"
date: 2019-02-13T01:58:00-05:00
draft: false
tags: ["v1.0"]
author: "Ben W"
---

# Where did Democrats have a large percentage of the vote?

{{<vega_iframe "/dem_2016.html">}}

# Where did Republicans have a large percentage of the vote?

{{<vega_iframe "/rep_2016.html">}}

# Where and how did the Democratic turnout change?

{{<vega_iframe "/dem_gain.html">}}

# Where and how did the Republican turnout change?

{{<vega_iframe "/rep_gain.html">}}

# Where was the net Republican shift?

{{<vega_iframe "/rep_shift.html">}}

## Methods

To understand what made 2016 different from 2012, we can just subtract.

We can approximate the Trump effect as the difference between the 2016 Republicans Presidential vote percentage and the 2012 percentage to see where Trump outperformed Romney (and won while Romney lost).

## Results

For example, in Winnebago, Wisconsin, Romney got 47% of the vote and Trump got 50.5%. This is a +3% Republican shift that flipped the county from blue to red.

In the map above, we clearly see that Trump underperformed Romney in Utah and parts of Idaho.  (This makes sense, since Evan McMullin was a spoiler candidate and Mormons abandoned Trump in droves.)  However, Trump overperformed in Missouri, Iowa, Ohio, and generally in the Great Lakes region.

## Next Steps

This leads to the obvious questions: Why these regions?  What was the basis of Trump's appeal?

Some local effects immediately jump out.  For example, that big blue blotch in Utah and Idaho (where the R candidate dramatically underperformed in 2016 compared to 2012) is Mormon country.  Romney, a Mormon, enjoyed much higher support than Trump, who struggled for support given his behavior.  Additionally, Ed McMullin (a Mormon) ran as a third party spoiler candidate, achieving his greatest support in his home state of Utah.

{{<vega_iframe "/mormons.html">}}

Let's look at [potential drivers of this shift.]({{< ref "education_vs_race_vs_shift" >}})
