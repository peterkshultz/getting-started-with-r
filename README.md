# Getting Started with R (and exploring R packages)

* Discuss usefulness of R in a data-intense world
* Run-down of RStudio installation
* Inclusion of packages
* Numerical summaries 
* Data visualizations

# Introduction

In any given discipline, from business to academia, there is a need for data analysis. Amongst the most popular tools to analyze data sets is R, a programming language that allows users to easily perform statistical analyses and create data visualizations.

In this article, we're going to use R to do some basic numerical analysis on a dataset. Following this, we'll make some cool visualizations on the same data. If you haven't used R before, no problem! I'll get you set up with the proper software.

# Downloading R and RStudio

If you haven't already downloaded R, you can do so at the following links [for a Mac](https://cran.rstudio.com/bin/macosx/R-3.2.4.pkg), [for a PC](https://cran.rstudio.com/bin/windows/base/R-3.2.4revised-win.exe), and [for various flavors of Linux](https://cran.rstudio.com/bin/linux/).

Downloading R is all well and good, but doing significant work with the language is best done using an integrated development environment, or IDE. One of the most popular choices is RStudio, with support for Mac, Windows, Debian, Ubuntu, and Redhat. Downloading is painless: click [this link](https://www.rstudio.com/products/rstudio/download/) and choose the proper download for your system and architecture. After installing, fire RStudio up. You're now ready to begin programming with R!

# Learning R

Learning a new programming language is tough, especially if you haven't learned one before. Luckily, there are dozens of great resources available to teach you the ins-and-out of R. While MOOCs are always an option, you might have better luck using sites like [DataCamp](https://www.datacamp.com/) or [Code School](http://tryr.codeschool.com/).

The coolest option that I've seen as of late 


# Packages

R by itself can do quite a bit, but the real fun comes in with **packages**. Put simply, packages extend the functionality of R to do just about anything users can dream of. Don't believe me? [Check out all 8,153 of the packages currently available ](https://cran.r-project.org/web/packages/available_packages_by_name.html) (as of 26/03/2016).

At their core, R packages are just libraries of specially-created R functions. Rather than making an R function and keeping it for the good of one, programmers in the R community share their R functions by packaging them up and sharing them on the Comprehensive R Archive Network (CRAN). 

Not all packages are going to come in handy to beginners. That's why I listed some that are integral to any work in R, whether you're a newcomer or a PhD-holding statistican:

## Learning

* `swirl`: You can learn R through RStudio using this package. Lessons take 15-20 minutes, so you're guaranteed to walk away with having learned something, even if only on a coffee break.

## Manipulation
* `tidyr` AKA "Tidy R": Cleans up datasets. This package was actually made by the developers of RStudio. [As RStudio describes,](http://blog.rstudio.org/2014/07/22/introducing-tidyr/) `tidyr` allows users to easily manipulate datasets by categorizing columns of your data. Performing statistical analysis on those columns then becomes a cinche. 
* `dplyr`: Goes hand-in-hand with `tidyr`. Easily creates data tables (think: Excel table), more frequenty referred to by the R community as a **data frame**.  

## Visualization
* `ggplot2`: Considered one of the most important visualization package in all of R. Its syntax can be a little scary, but once you see a couple of examples it can be fully utilized.
* `htmlwidgets`: Allows users to make visualizations that can then be easily exported to the Internet. `htmlwidgets` is used by a bevy of other packages. You can see them all [at this link](http://www.htmlwidgets.org/showcase_leaflet.html).
* `shiny`: Interested in making a web app from your analysis, but without skills in HTML, CSS, or Javascript? If so, `shiny` is for you. Also by the makers of RStudio, `shiny` has developed quite a community. It even has its own [site](http://shiny.rstudio.com/) chock full of documentation to help get you started.

# Installation

Installing and utilizing packages is a three step process:

1. Install
2. Include
3. Use

For installing, simply enter the command `install.packages('<package_name>')` where `<package_name>` is the name of your package. Next, load the package using the command `library('<package_name')`. 

At this point, any functions within the package installed is now ready to use. Call the function by typing `<function>()`, where `<function>` is the function name.

