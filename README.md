# Demo-Projects

## True-Popularity.Rmd
This visualization uses SSA.gov data for baby names given by state to compare the "True Popularity" of a "Top N" name. The true popularity is the percentage of babies born with a given name in a "generation", that is, within a 5-year window centered around the year of birth.

**Parameters**
state: the two-letter state code for the state you want to visualize
rank: the lowest rank you want to consider (<=10 is probably best)
firstyear: the earliest year you want to consider (>=1910)
lastyear: the latest year you want to consider (<=2020)
roll: the window you want to use to consider true popularity. Choose odd for best results. 5 seems reasonable.
