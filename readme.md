# Tidyverse Workshop Series

These materials support a series of hour long interactive, virtual workshops on using packages that are part of the [tidyverse](https://www.tidyverse.org/).

## Before the Workshop

### Set up R and RStudio

[Install R and RStudio](https://sites.northwestern.edu/researchcomputing/resources/r-and-rstudio/) on your own laptop (both are free).  If you can't install these programs or run into issues installing packages, [RStudio Cloud](https://sites.northwestern.edu/researchcomputing/resources/r-and-rstudio/#option-2-rstudio-cloud)  is a good option.

Also, install (or update) the tidyverse package.  Instructions are at the bottom of the [installation instructions page](https://sites.northwestern.edu/researchcomputing/resources/r-and-rstudio/).  If you run into installation issues (about 5-10% of you are likely to based on past workshops), you (Northwestern folks) can send me an email at christina.maimone@northwestern.edu.

I will be using tidyverse version 1.3.1 and R version 4.1.0 in the workshop (any R version starting with a 4 should be OK).  You will want to update the tidyverse package to at be at least 1.3.0, as there were notable changes from earlier versions.  To update a package, make sure you are starting from a fresh R session (no packages loaded), and then just install it again:  `install.packages("tidyverse")`.


## Materials

### Background

These workshops assume you are familiar with R outside of these packages.  Sessions build on each other to some extent.  Sessions after the first one assume you understand the material covered in the first session.  Later sessions may also use additional concepts from earlier sessions.

You may also want to learn about R Markdown files (and R Notebooks, which are a special type): https://rmarkdown.rstudio.com.  They're useful for when you want to combine R code, output, and text together in a document. The files for these workshops are R Markdown documents, which will be run in Notebook mode so the output appears below the code cells in the file. 

### Links

Links for each session will show the rendered html file.  There is a button in the upper right of each file to download the .Rmd file to work with in RStudio yourself. Or [download this entire repository](https://sites.northwestern.edu/researchcomputing/resources/downloading-from-github/) instead to get the .Rmd files for all sessions.

* [Session 1](https://nuitrcs.github.io/r-tidyverse/html/intro.html): Tidyverse basics
* [Session 2](https://nuitrcs.github.io/r-tidyverse/html/dplyr1.html): dplyr – select, filter, mutate
* [Session 3](https://nuitrcs.github.io/r-tidyverse/html/dplyr-group.html): dplyr – group by, summarize, arrange, across    
* [Session 4](https://nuitrcs.github.io/r-tidyverse/html/dplyr-join.html): dplyr – joins - working with two data frames
* [Session 5](https://nuitrcs.github.io/r-tidyverse/html/ggplot2.html): a quick intro to ggplot2
* [Session 6](https://nuitrcs.github.io/r-tidyverse/html/tidyr.html): tidyr – pivot_longer, pivot_wider, separate, separate_rows

Additional Sessions:

* [Bonus 1](https://nuitrcs.github.io/r-tidyverse/html/others.html): utility packages – stringr, lubridate, forcats, readxl: this is an overview lecture without exercises

## Learning More

[R for Data Science](https://r4ds.had.co.nz/) covers the use of tidyverse packages for data analysis in depth.  Written by two of the authors of these packages, this free online book is a good place to go for additional information and practice.  

Note, however, that this book was written a few years ago, so some of the packages and functions have evolved.  In particular, pivot_longer and pivot_wider used to be functions called gather and spread.  For a tutorial on pivot_* functions, see https://tidyr.tidyverse.org/articles/pivot.html

[RStudio Videos](https://www.youtube.com/watch?v=jOd65mR1zfw&list=PL9HYL-VRX0oQOWAFoKHFQAsWAI3ImbNPk): Data Wrangingling with R and the Tidyverse.  These cover material from roughly the first 4 sessions of this workshop series.  

For more on ggplot2, see [our guide](https://sites.northwestern.edu/researchcomputing/2020/04/13/online-learning-resources-r-ggplot2/) with free (for Northwestern folks) resources.
