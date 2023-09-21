---
title: "Introduction to econometrics (ECON-UN3412)"
weight: 1
url: /teaching/metrics
summary: "Fall 2020, Spring 2021, Fall 2021, Summer 2023"
editPost:
    URL: "https://github.com/wmadavis/Teaching-IntroEconometrics"
    Text: "Github page"
showToc: true
disableAnchoredHeadings: false

---

Sessions taught: Fall 2020, Spring 2021, Fall 2021, Summer 2023

## Course description

ECON-UN3412 introduces students to multiple regression and related methods for analyzing data in economics and related disciplines. Additional topics include regression with discrete random variables, instrumental variables regression, analysis of random experiments and quasi-experiments, and regression with time series data. Students will learn how to conduct – and how to critique – empirical studies in economics and related fields. Accordingly, the emphasis of the course is on empirical applications.

##### Prerequisites

+ Intermediate microeconomics or intermediate macroeconomics
+ Calculus III
+ Introduction to probability and statistics with calculus

##### Textbook

+ "Introduction to Econometrics” — James Stock and Mark Watson (2019, 2020)

I respect academic publishers too much to suggest [Googling the textbook title and authors with "pdf"](https://www.google.com/search?q=introduction+to+econometrics+stock+watson+pdf&oq=introduction+to+econometrics+stock+watson+pdf&gs_lcrp=EgZjaHJvbWUyCQgAEEUYORiABDIICAEQABgWGB4yCggCEAAYhgMYigUyCggDEAAYhgMYigXSAQg0NTcxajFqN6gCALACAA&sourceid=chrome&ie=UTF-8&bshm=rime/1) to get a free electronic copy. Or downloading them, also for free, off [Sci-Hub](https://sci-hub.se/database).

---

## Resources

(to be updated soon, placeholders for now)

Columbia teaches its undergraduates econometrics using Stata, an expensive statistical software whose wide use persists because it’s what most professors learned themselves. The first semester I taught this course, I prepared supplementary material and solutions to provide students the option to instead use R, a free and more flexible open-source alternative like Python and Julia preferred by most industries outside academic social science. After some initial trepidation about departing from the official software of instruction, students seemed to find its object-oriented programming much more intuitive and appreciated its usefulness and accessibility beyond the semester course. I refined my material and continued teaching exclusively in R in subsequent semesters and all in all, I think I cost Stata Corporation upwards of $10,000 in lost single-semester license fees.

Below are the weekly guides I produced, mostly from the Summer 2023 iteration of my classes. These exclude problem sets, exams, practice exams, and their solutions. Most datasets referenced are available for free on the textbook's official website. Instruction here assumes no prior experience with programming other than installation of R and RStudio. It introduces and makes use of R Notebooks saved as R Markdown (.Rmd) files, a convenient way of integrating in-line R scripting with intuitive word processing to produce handsome problem sets and reports either as pdfs or HTML files. If you’re following on your own, open the Rmd files in RStudio to see the input and the pdf files to see what the resultant output looks like.

If I were to teach this course again, I’d replace the working directories coverage with an introduction to R Projects and the here() function, which I’ve since integrated into my own coding practice. It’s a minor and very intuitive adjustment that quickly makes up for the time spent learning it so there’s actually no time tradeoff here. Until then, here’s a guide that would immediately put you ahead of probably 95% of professional social scientists in terms of project management hygiene and coding etiquette. Packages used throughout are not necessarily my favorites (for example, fixest is clearly the cutting edge for panel data methods), but were chosen to produce estimates identical to Stata’s.

##### 1. Introduction to R Notebooks

+ Rmd
+ pdf
+ Written practice problems

##### 2. Downloading R packages, loading datasets, working directories, and regressions

+ Rmd
+ pdf
+ bonus points of emphasis

##### 3. Cleaning data, control variables, multiple regression, and hypothesis testing

+ Rmd
+ pdf
+ bonus material on bad controls, bonus points of emphasis

##### 4. Indexing, interaction terms, and using regressions for “predictions”

+ Rmd
+ pdf

##### 5. Panel data methods and cluster-robust standard errors

+ Rmd
+ pdf
+ bonus material on fixed effects

##### 6. Pre-midterm tips

##### 7. Binary dependent variables (linear probability, probit, and logit)

+ Rmd
+ pdf

##### 8. Instrumental variables

+ Rmd
+ pdf
+ Written practice problems

##### 9. Time series methods and merging datasets

+ Rmd
+ pdf
+ Written practice problems

##### 10. Pre-final tips


+ Rmd
+ pdf