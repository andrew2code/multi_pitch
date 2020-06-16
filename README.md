# The Best Multi Pitch Routes in the World

## Introduction

There is a great crowd-sourced website for climbers called Mountainproject.com. I have always thought that the search feature could be better. I want to find places to go that will leave unforgettable memories. For me, this means multi pitch routes. This project will attempt to solve for the best multi pitch routes in the world, using Pandas data analysis.

## Data Dictionary

| Field | Description |
| :--- | :--- |
| Route | This is the name of the route given by the person who first set the route |
| Average Stars | This is the rating of the climb in terms of its enjoyment and overall fun experience factor |
| Number of Pitches | The climber ascends in between sections of the rock that allow him to reuse the rope repeatedly. The longer the climb, the more pitches. A typical rope is 70 meters long. If a route is 15 pitches long, then the route is roughly 1,050 meters long |
| Length(f) | Length in feet |
| Length (m) | Length in meters |
| Latitude | The GPS latitude of the climb |
| Longitude | The GPS longitude of the climb || Local Location | This is the specific location of the route |
| Loc 1 through Loc 6 | This is the local, regional, and country description of the route |
| Route Type 1 to Route Type 3 | There are different technical styles of climbing: Trad, Aid, Sport, TR, each with it own technical skill set. This analysis will cover only Sport Climbing. |
| Class | This follows the Yosemite Decimal System. Class 5 is technical roped climbing  using protection hardwware (quickdraws, cams, nuts, etc) and belaying.
| Protection Rating | This is an optional rating that rates the spacing of the protection and the quality of the protection for a lead climber. 
PG: One dangerous location with a few places of poor or non-existent placements. A fall should result in minor injury.
PG13: A few protection, falls may be long (15 feet) but could cause serious injury
R: Some placements very far apart and a fall could result in broken bones, even when protection is placed
X: No protection, very dangerous or a fall that could result in death even when properly protected |
| Aid Climbing Grading | This applies only for Aid Climbing, the higher the number, the more difficult it is to place protection
| URL | This is the link to the mountainproject.com detail |




## Important Links

* [Final Report Notebook](http://localhost:8888/notebooks/report.ipynb#)
* [EDA Notebook](http://localhost:8888/notebooks/eda.ipynb)
* [Link 1](http://www.mountainproject.com) - Source Data is taken from here
* [Link 2](https://en.wikipedia.org/wiki/Sport_climbing) - Sport climbing explained
* [Link 3](https://www.youtube.com/watch?v=2F0MPMcSEMg) - Outside climbing
