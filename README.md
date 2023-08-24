# Fundamentals of Package Development

### posit::conf 2023

by Andy Teucher

```{=html}
<!-----

INSTRUCTIONS FOR INSTRUCTORS: Please insert information about your
workshop below. Then, add workshop content in the materials folder and
link to each session’s materials from the schedule below. You are
welcomed to add more rows to the schedule. We just ask that you take
breaks at the specified times. Once you are done adding information, you
can remove these instructions from the README.

Alternatively, you can completely redo the organization of this repo 
as a Quarto website or some other format you prefer to host your workshop
materials. The only requirement is that your workshop materials are hosted 
here.

----->
```
:spiral_calendar: September 17 and 18, 2023\
:alarm_clock: 09:00 - 17:00\
:hotel: ROOM TBD\
:writing_hand: [pos.it/conf](http://pos.it/conf)

------------------------------------------------------------------------

## Overview

We are often faced with the need to share our code with others, or find ourselves writing similar code over and over again across different projects.
In R, the fundamental unit of reusable and shareable code is a package, containing helpful functions, documentation, and sometimes sample data.
This workshop will teach you the fundamentals of package development in R, using tools and principles developed and used extensively by the tidyverse team - specifically the 'devtools' family of packages including usethis, testthat, and roxygen2.
These packages and workflows help you focus on the contents of your package rather than the minutiae of package structure.

You will learn the structure of a package, how to organize your code, and workflows to help you develop your package iteratively.
You will learn how to write good documentation so that users can learn how to use your package, and how to use automated testing to ensure it is functioning the way you expect it to, now and into the future.
You will also learn how to check your package for common problems, and how to distribute your package for others to use.

This will be an interactive 1-day workshop, and we will be using the RStudio IDE to work through the materials, as it has been designed to work well with the development practices we will be featuring.

\*\*This workshop is for you if you...\*

1.  have written several R scripts and find yourself wondering how to reuse or share the code you've written.
2.  know how to write functions in R.
3.  are looking for a way to take the next step in your R programming journey.

## Prework

Please ensure you have installed a recent version of R (\>= 4.0) and are able to install packages.
The workshop will be taught using the RStudio IDE. You are welcome to use whichever IDE you are comfortable with, but you will find it easier to follow along if you are using RStudio as well.

### Git and GitHub

We will be demonstrating some workflows using Git and GitHub.
Knowledge of these tools is not required, and you will absolutely be able to complete the workshop without them, but some of the lessons will be more rewarding to you if you are prepared to try them out.
To take advantage of this you will need to Git installed on your computer, and sign up for a free GitHub account.

If you are looking to get started with Git and GitHub, we recommend you register for the "What they forgot to teach you about R" workshop on Day 1, and join us for this workshop on Day 2.

## Code of Conduct

Please note that all participants at posit::conf(2023) and workshops must abide by the [Code of Conduct](https://posit.co/code-of-conduct/).

## Schedule

### Day 1

| Time          | Activity                                                      |
|:--------------|:--------------------------------------------------------------|
| 09:00 - 10:30 | What is a package? Package Structure and State                |
| 10:30 - 11:00 | *Coffee break*                                                |
| 11:00 - 12:30 | Package Creation and Metadata; Documentation                  |
| 12:30 - 13:30 | *Lunch break*                                                 |
| 13:30 - 15:00 | Testing; Dependencies                                         |
| 15:00 - 15:30 | *Coffee break*                                                |
| 15:30 - 17:00 | Continuous Integration; Package Website; Package Distribution |

## Instructor

Andy Teucher is a data scientist and package developer with a passion for teaching others to learn how to use data science tools to make their work more efficient and reproducible.
His background is in conservation biology, with an MSc in Ecology from the University of Calgary.
He has spent much of his career as a data scientist in government, where he made it his mission to promote and teach open, reproducible data science practices.
He has written R packages for internal use in his teams as well as for a broader audience, with several hosted on CRAN.
Andy especially enjoys developing packages to make it easier to work with spatial data in R.
Andy is a certified Software Carpentry and Data Carpentry instructor, and has led many workshops teaching programming skills to scientists and data professionals.

------------------------------------------------------------------------

![](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
