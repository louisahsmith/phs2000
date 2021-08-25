
# PHS 2000 Summer Prep tutorial

This R packages allows you to run the R, probability, and statistics tutorial on your own computer if the site at https://phs2000-prep.hmdc.harvard.edu/ is not working.

## Installation

Unlike the online version, you need R installed and running for this tutorial to work. You can follow [step 1.1 here](https://intro-to-r-2020.louisahsmith.com/exercises/01-exercise/) if you don't already have R on your computer.

First you'll need to make sure you have the `{remotes}` package installed. You can do so by opening an R session and typing this into the console:

``` r
install.packages("remotes")
```
After that is installed, do the same with this:
```r
remotes::install_github("louisahsmith/phs2000")
```
Once that is installed, you are ready to go. 

In the console, run
```r
learnr::run_tutorial("prep", "phs2000")
```
and a browser window will open (after some code runs). You can do as much of the tutorial as you want, as long as you keep R running in the background. If you close out of the browswer or out of R, just run the `learnr::run_tutorial("prep", "phs2000")` to get it back!
