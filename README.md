# Getting Started with R (and exploring R packages)

## Introduction

In any given discipline, from business to academia, there is a need for data analysis. Amongst the most popular tools to analyze data sets is R, a programming language that allows users to easily perform statistical analyses and create data visualizations.

In this article, I'm going to share with you the best tools to manipulate datasets in R such that they're easy to analyze. In addition, you'll be introduced to a wide variety of visualization tools that are sure to bring your data to life. If you haven't used R before, no problem! I'll get you set up with the proper software.

## Downloading R and RStudio

If you haven't already downloaded R, you can do so at the following links [for a Mac](https://cran.rstudio.com/bin/macosx/R-3.2.4.pkg), [for a PC](https://cran.rstudio.com/bin/windows/base/R-3.2.4revised-win.exe), and [for various flavors of Linux](https://cran.rstudio.com/bin/linux/).

Downloading R is all well and good, but doing significant work with the language is best done using an integrated development environment, or IDE. One of the most popular choices is RStudio, with support for Mac, Windows, Debian, Ubuntu, and Redhat. Downloading is painless: click [this link](https://www.rstudio.com/products/rstudio/download/) and choose the proper download for your system and architecture. After installing, fire RStudio up. You're now ready to begin programming with R!

## Learning R

Learning a new programming language is tough, especially if you haven't learned one before. Luckily, there are dozens of great resources available to teach you the ins-and-out of R. While MOOCs are always an option, you might have better luck using sites like [DataCamp](https://www.datacamp.com/) or [Code School](http://tryr.codeschool.com/). If you'd rather go old school, I recommend the PDF [R for Beginners](https://cran.r-project.org/doc/contrib/Paradis-rdebuts_en.pdf)

The coolest option that I've seen as of late is a package [more on this later] called `swirl`. This package allows you to learn about R right within RStudio. If I were relearning the language, this would be my first stop.


## Packages

R by itself can do quite a bit, but the real fun comes in with **packages**. Put simply, packages extend the functionality of R to do just about anything users can dream of. Don't believe me? [Check out all 8,153 of the packages currently available ](https://cran.r-project.org/web/packages/available_packages_by_name.html) (as of 26/03/2016).

At their core, R packages are just libraries of specially-created R functions. Rather than making an R function and keeping it for the good of one, programmers in the R community share their R functions by packaging them up and sharing them on the Comprehensive R Archive Network (CRAN). 

Not all packages are going to come in handy to beginners. That's why I listed some that are integral to any work in R, whether you're a newcomer or a PhD-holding statistican.

### Learning

* [`swirl`](http://swirlstats.com/): You can learn R right within RStudio using this package. Lessons take 15-20 minutes, so you're guaranteed to walk away with having learned something, even if only on a coffee break.

### Manipulation
* `tidyr` AKA "Tidy R": Cleans up datasets. This package was actually made by the developers of RStudio. [As RStudio describes](http://blog.rstudio.org/2014/07/22/introducing-tidyr/), `tidyr` allows users to easily manipulate datasets by categorizing columns of your data. Performing statistical analysis on those columns then becomes a cinche. 
* `dplyr`: Goes hand-in-hand with `tidyr`. Easily creates data tables (think: Excel table), more frequenty referred to by the R community as a **data frame**.  

### Visualization
* [`ggplot2`](http://ggplot2.org/): Considered one of the most important visualization package in all of R. Its syntax can be a little scary, but once you see a couple of examples it can be fully utilized to make great visualizations. This really is the R community's visual gold standard.
* [`htmlwidgets`](http://www.htmlwidgets.org/): Allows users to make visualizations that can then be easily exported to the Internet. `htmlwidgets` is used by a bevy of other packages. You can see them all [at this link](http://www.htmlwidgets.org/showcase_leaflet.html).
* [`shiny`](http://shiny.rstudio.com/): Interested in making a web app from your analysis, but without skills in HTML, CSS, or Javascript? If so, `shiny` is for you. Also by the makers of RStudio, `shiny` has developed quite a community. Its site is chock full of documentation to help get you started.
* [`LightningR`](https://github.com/Ermlab/lightning-rstat#usage): An up-and-coming visualization tool that I've worked with in the past. Lightning's visualizations utilize the best technology in web graphics, and their [gallery of visualizations](https://github.com/Ermlab/lightning-rstat#documentation) speaks for itself.

The R packages listed above are just a few of my favorites, and are especially good for just starting out. Doing anything with R the first time around can be challenging, and so limiting the number of packages [read: options] you utilize is important. Keep it simple!

## Installation

Installing and utilizing packages is an easy three step process:

1. Install
2. Include
3. Use

For installing, enter the command `install.packages("<package_name>")` where `<package_name>` is the name of your package. Next, load the package using the command `library(<package_name)`. 

At this point, any functions within the installed package is now ready to use. Call the function by typing `<function>()`, where `<function>` is the function name.

When it comes to utilizing packages, documentation is your best friend. Luckily, any package available on [CRAN](https://cran.r-project.org/) will have documentation, or perhaps its own site!

## About the Author

Peter Shultz is a student at the University of Michigan studying computer science.
