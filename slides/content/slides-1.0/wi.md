---
title: "Wisconsin"
date: 2019-02-11T14:05:03-04:00
draft: False
---

Your first intuitions in Wisconsin might be to check what was happening in Ohio to see if things are the same.  On a couple of counts, they are.

### Education vs Shift, OH + WI

{{<localplotly "WI/wi_oh.html" 600 600>}}

There is a very strong relationship between non-college rate and Republican shift by county, in Wisconsin as in Ohio.  Taken together, these two series have an r-squared of 0.65 and a p value of 6.09 * 10^-38, which are very decisive "this is not random" metrics.

### Education vs Shift vs Whiteness, OH + WI

{{<localplotly "WI/compare_scatter.html" 600 600>}}

And this is the same stronger-than-nationally trend we saw in the Ohio case.

But mining doesn't appear to be a factor because Wisconsin mining employment is de minimis in a state of 5.8 million people.

### Wisconsin Mining is Immaterial

<iframe src="https://fred.stlouisfed.org/graph/graph-landing.php?g=nNmN&width=670&height=475" scrolling="no" frameborder="0"style="overflow:hidden; width:670px; height:525px;" allowTransparency="true"></iframe>

### Wisconsin Manufacturing has shrunk like OH has

<iframe src="https://fred.stlouisfed.org/graph/graph-landing.php?g=nNmP&width=670&height=475" scrolling="no" frameborder="0"style="overflow:hidden; width:670px; height:525px;" allowTransparency="true"></iframe>

### GOP Turnout Didn't Flip Wisconsin, Dem Turnout Did

{{<localplotly "WI/turnout_bars.html" 600 600>}}

So where did the Dem votes change?

### Change in Dem Votes, Percentage

{{<localplotly "WI/d_vote_gain_%_2012.html" 825 425>}}

Just like Ohio, Dem turnout plunged across the board from 2012.  The best Dem showing was a 6% gain in Ozaukee, with two other counties (Dane and Waukesha) being near zero and most places being a 20% drop or more.  Milwaukee is especially troubling, because Milwaukee alone holds about 16% of the voting-aged population.

### Change in Dem Votes, Total

{{<localplotly "WI/dem_votes_map.html" 825 425>}}

### Where is the manufacturing?

<img src="/WI/WI_manufacturing.png" width="600" height="600" />

(Via [Brookings](https://www.brookings.edu/interactives/interactive-locating-american-manufacturing/))

The two big shortfall areas for Dems in terms of voters were the Appleton/Oshkosh area, (that blotch in the middle of the state,) and Milwaukee in the southeast.  Manufacturing concentrates in population centers, so this is not super surprising, but combined with the noncollege rate vs shortfall in turnout the data may suggest that declining labor prospects influenced votes.

## What Kinds Of Counties Mattered?

<img src="/WI/WI_vote_changes.png" width="600" height="600" />

(Via [Wiscontext](https://www.wiscontext.org/how-and-where-trump-won-wisconsin-2016))

Dem support fell apart across the state, and Milwaukee was the biggest single-county contributor, but the next-largest tier of counties by population caused a larger vote loss by far.

<img src="/WI/wi_map_wiscontext.png" width="600" height="600" />

(Via [Wiscontext](https://www.wiscontext.org/how-and-where-trump-won-wisconsin-2016))

Interestingly, there was extensive 3rd party voting in the Other Metro counties, which made the biggest difference in Clinton's outcomes.  (Clinton needed to lose ~200K votes compared to the Obama 2012 total, and half of that came from the Other Metro category.)  I am not really sure what the story there is.  Libertarian (and Republican governor) Gary Johnson took 100K of the 3rd party vote and Jill Stein took only 31K.  Did 2012 Obama voters pull the lever for the Libertarian in 2016, or did those voters stay home while some Republicans protest-voted and new voters came in to replace the 2012 Republicans in voting for Trump?  The latter seems more plausible intuitively, but I don't have the data to back it.

There is one highly plausible explanation for lower Dem enthusiasm in 2016 compared to 2012.  This is the map of candidate vists to Wisconsin in 2012

### Candidate Visits to WI in 2012

<img src="/WI/2012_visits.png" width="600" height="600" />

(Via [FairVote](https://www.fairvote.org/fairvote-maps-the-2012-presidential-campaign))

Note the darker blue pins in Madison, Milwaukee, and Green Bay, which represent visits by Obama during the 2012 campaign.  This map, produced in 2013, also happens to show the visits by Hillary Clinton as the candidate in 2016, because there weren't any.

<img src="/WI/2016_visits.png" width="600" height="600" />

(Via [FairVote](https://docs.google.com/spreadsheets/d/14Lxw0vc4YBUwQ8cZouyewZvOGg6PyzS2mArWNe3iJcY/edit#gid=0))

If having the candidate visit your state energizes voters and increases turnout, (which is probably true given how much time candidates spend on those events,) having fewer campaign visits in 2016 probably hurt Dem turnout overall compared to 2012.  It has been rumored that the campaign consciously chose to not visit Wisconsin because they thought increased exposure of the candidate _decreased_ support, but that is again a "Dems losing the state, not Reps winning it" scenario.
