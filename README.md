# Perth-School-Catchments
_Let's see if we can map the school catchment boundaries in Perth, Western Australia to compare against prospective real estate._

## Status
We're in the early development stages, so any help would be very much appreciated.

## How to help
Choosing a property within a good school zone is a common optimisation problem for parents and, as far as I am aware, there is no easy, preexisting solution publically available.

## To Do List
### Research
1. Determine the best format for presenting polygons (the school boundaries) on Google Maps
2. Determine a good data structure to save the school bounrady info in
 1. Storing the most N, E, W, S points in the boundary will help optimise comparisons of points (properties) to polygons (boundaries)
### Data collation
1. Get the complete list of Perth metro schools and their websites (maybe via #4?)
2. Search/scrape each to find their boundaries
3. Turn the boundaries into lists of clockwise lat-longs
4. Scrape the schools info site (link??) for the available school stats (and maybe links to their websites)
