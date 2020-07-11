# Tidyverse Workshop Series

These materials support a series of hour long interactive, virtual workshops on using packages that are part of the [tidyverse](https://www.tidyverse.org/) or use the programming approach of the tidyverse.

## Before the Workshop

### Set up R and RStudio

[Install R and RStudio](https://sites.northwestern.edu/researchcomputing/resources/r-and-rstudio/) on your own laptop (both are free).  If you can't install these programs or run into issues installing packages, [RStudio Cloud ](https://sites.northwestern.edu/researchcomputing/resources/r-and-rstudio/#option-2-rstudio-cloud) is a good option.

Also, install (or update) the tidyverse package.  Instructions are at the bottom of the [installation instructions page](https://sites.northwestern.edu/researchcomputing/resources/r-and-rstudio/).  If you run into installation issues (about 5-10% of you are likely to based on past workshops), you can send me an email at christina.maimone@northwestern.edu.

I will be using tidyverse version 1.3.0 and R version 4.0.2 in the workshop.  You will want to update the tidyverse packages to have the most recent version, as they do make notable changes between releases.


### Get Materials

I will email an R Markdown (notebook) file to registered participants before each session.  You can also download the materials from this repository (individual links below).

## Materials

### Background

These workshops assume you are familiar with R outside of these packages.  Sessions build on each other to some extent.  Sessions after the first one assume you understand the material covered in the first session.  Later sessions may also use additional concepts from earlier sessions.

You may also want to learn about R Markdown files (and R Notebooks, which are a special type): https://rmarkdown.rstudio.com.  They're useful for when you want to combine R code, output, and text together in a document. The files for these workshops are R Markdown documents, which will be run in Notebook mode so the output appears below the code cells in the file. 

### Links

*Download links should prompt you to save the linked .Rmd file, but behavior may vary across browsers.* You can always [download this entire  repository](https://sites.northwestern.edu/researchcomputing/resources/downloading-from-github/) instead.

* Session 1: Tidyverse basics, dplyr – select, filter, mutate.  [download](https://nuitrcs.github.io/r-tidyverse/01-intro.Rmd) | [view](https://nuitrcs.github.io/r-tidyverse/html/01-intro.html)  
* Session 2: dplyr – group by, summarize, arrange, across.  [download](https://nuitrcs.github.io/r-tidyverse/02-dplyr-group.Rmd) | [view](https://nuitrcs.github.io/r-tidyverse/html/02-dplyr-group.html)        
* Session 3: dplyr – joins - working with two data frames. [download](https://nuitrcs.github.io/r-tidyverse/03-dplyr-join.Rmd) | [view](https://nuitrcs.github.io/r-tidyverse/html/03-dplyr-join.html)   
* Session 4: a quick intro to ggplot2.  [download](https://nuitrcs.github.io/r-tidyverse/04-ggplot2.Rmd) | [view](https://nuitrcs.github.io/r-tidyverse/html/04-ggplot2.html)
* Session 5: tidyr – pivot_longer, pivot_wider, separate, separate_rows.  [download](https://nuitrcs.github.io/r-tidyverse/05-tidyr.Rmd) | [view](https://nuitrcs.github.io/r-tidyverse/html/05-tidyr.html)
* Session 6: utility packages – stringr, lubridate, forcats, readxl.  

## Learning More

[R for Data Science](https://r4ds.had.co.nz/) covers the use of tidyverse packages for data analysis in depth.  Written by two of the authors of these packages, this free online book is a good place to go for additional information and practice.  

Note, however, that this book was written a few years ago, so some of the packages and functions have evolved.  In particular, pivot_longer and pivot_wider used to be functions called gather and spread.  For a tutorial on pivot_* functions, see https://tidyr.tidyverse.org/articles/pivot.html

[RStudio Videos](https://www.youtube.com/watch?v=jOd65mR1zfw&list=PL9HYL-VRX0oQOWAFoKHFQAsWAI3ImbNPk): Data Wrangingling with R and the Tidyverse.  These cover material from roughly the first 3 sessions of this workshop series.  

For more on ggplot2, see [our guide](https://sites.northwestern.edu/researchcomputing/2020/04/13/online-learning-resources-r-ggplot2/) with free (for Northwestern folks) resources.
