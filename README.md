Intro to git
================
Libby Rogers
January 31, 2019

Git with R
----------

dplyr\_tutorial.Rmd includes a quick tutorial with some code to fill in using some operations from the `dplyr` r package. This has been adapted from a `dplyr` [vignette](https://dplyr.tidyverse.org/articles/dplyr.html).

We'll use this to show some examples of how to work collaboratively with git.

To run the markdown doc in R you'll need to have `dplyr`, and `nycflights13` installed in R - although you can still do the git tutorial without running anything (or even having R installed). To install them run:

``` r
install.packages("dplyr")
install.packages("nycflights13")
```

Team leader

1.  Fork this repo into your own github account as a private repo.
2.  Add your team as collaborators.

All team members:

1.  Pull it into your local environment (or can all be done in the browser on github.com).
2.  Add the original repo as your upstream: `git remote add upsteam https://github.com/LiRogers/Intro-to-GIT`
3.  Create a new branch and fill in some of the answers in dplyr\_tutorial
4.  Compare your branch to your team mates.
5.  Resolve any conflicts and merge your answer branches into one.
6.  Compare this to the dplyr-solutions branch.
7.  Resolve any conflicts and merge into one branch.
8.  Submit a pull request on the original repo.
