A gRadual intRoduction to data visualization
================
Chester Ismay and Ted Laderas

Welcome! This is a workshop for the Cascadia R conference that is meant to be a gentle introduction to data visualization using the `ggplot2` and the `plotly` packages.

You'll learn the basics of the grammar of graphics and learn how to visualize and understand relationships between different kinds of variables in your dataset.

Prerequisites
-------------

To participate in this workshop, you'll need to do the following:

-   Have the latest R/Rstudio Installed ([Directions are here](https://ismayc.github.io/rbasics-book/3-rstudiobasics.html))
-   Be familiar with the [basics of the RStudio Interface](https://ismayc.github.io/rbasics-book/3-rstudiobasics.html)
-   Have the following packages installed:
    -   `tidyverse`, `plotly`, `gapminder` and `fivethirtyeight`

<!-- -->

    install.packages("tidyverse", "plotly", "gapminder" and "fivethirtyeight")

Remember, in this workshop we will adhere the [code of conduct for this conference](https://cascadiarconf.com/coc/). Be respectful of your fellow students and let's learn together.

Outline of this Workshop
------------------------

1.  Visualizing continuous data (scatterplots)
    -   Learning about Aesthetics
    -   Some basic geoms
2.  Visualizing categorical data
    -   More about geoms
    -   Learning about faceting
3.  Visualizing categorical versus continuous data (boxplots)
4.  Making your plots interactive with `plotly`
