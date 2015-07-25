---
title       : Developing Data Products Project
subtitle    : Inspecting the Phoenix Data Project
author      : LowTech
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Purpose

The Phoenix Data Project is an open source project for generating political event data--conflict (coups, wars, that kinda stuff) and cooperation (alliance activity, declarations of peace, etc.). Fun! I wanted to see what the data looked like, so I put this project together. It just looks at the # of recorded events per day, and the distribution of conflict and cooperation.

--- .class #id 

## Comparing Days: Event Counts

Example, 6/10/15

Download the specified day's file, read in the data. How many political events occurred? *


```
## [1] 3696
```

* The Phoenix Data Project processes a few hundred select known news sources, to try to get as much high quality coverage as possible. Of course, not all areas are covered equally (or at all).

--- .class #id 

## Comparing Days: Conflict/Cooperation

Example, 6/10/15

Goldstein Scores, from -10 to 10', -10 being most conflictual, 10 being most cooperative

![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png) 

--- .class #id 

## More info

For more information on the Phoenix Data Project, go to phoenixdata.org

You can follow (nearly) all of the collaborators on Twitter (they seem like nice people)
@charlie_simpson, @ahalterman, @johnb30, @PatrickTBrandt

And if you're really interested, I'm on the Internet, too: @petergowen

