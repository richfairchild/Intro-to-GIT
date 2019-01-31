Intro to git
================
Libby Rogers
January 31, 2019

Git with R
----------

dplyr\_tutorial.Rmd includes a quick tutorial with some code to fill in using some operations from the `dplyr` r package. This has been adapted from a `dplyr` [vignette](https://dplyr.tidyverse.org/articles/dplyr.html).

We'll use this to show some examples of how to work collaboratively with git. The answers you fill in don't matter, we're just using it as an example file to make some changes to.

To run the markdown doc in R you'll need to have `dplyr`, and `nycflights13` installed in R - although you don't need to run anything (or even having R installed) to follow the tutorial, just a text editor.

If you want to install them, run:

``` r
install.packages("dplyr")
install.packages("nycflights13")
```

Team leader

1.  Fork this repo into your own github account as a private repo.
2.  Add your team as collaborators.

All team members:

1.  Pull it into your local environment (or can all be done in the browser on github.com).
2.  You might need to add the original repo as your upstream: `git remote add upstream https://github.com/LiRogers/Intro-to-GIT.git` Github desktop will do this for you.
3.  Create a new branch in your fork and fill in some of the answers in dplyr\_tutorial in your local environment (Don't worry about these being correct, we just want to make some changes to the file), or make some other changes.
4.  Push your branch to github.
5.  Compare your branch to your team mates via pull requests.
6.  Resolve any conflicts and merge your answer branches into one.
7.  Compare this to the dplyr-solutions branch.
8.  Resolve any conflicts and merge into one branch.
9.  Fetch the upstream repo to see if anything has changed.
10. Merge your branch into the master branch in your fork, rebase if necessary.
11. Submit a pull request to merge your master with the upstream master on github.

Useful links:

<https://help.github.com/>
