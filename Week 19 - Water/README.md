Overview
================
Pramod Surve
5/10/2021

## Week 19 Water Dataset

I concentrated on ggiraph and gganimate packages to create interactive
and animation for water points installed by country.

1.  Bar Graph

![](Output/Animation_Bar.gif)

1.  Line Chart

![](Output/Animation.gif)

### Learnings

-   The graphs become too cluttered if there are many lines in
    gganimate. If not animated with gifski 100 png files are created.

-   For Brushing (ggiraph) the long labels on x and y axis makes the
    graphs too small and unreadable. Need to find a way to reduce the
    size of labels in the output.

-   Bar graph animation produces graph where the country moves because
    of change in the rank at that year but there is a glitch where row
    for one data point was removed and so water point shows up as zero
    for that country.
