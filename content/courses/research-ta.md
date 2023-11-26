---
title: "Departmental research consultant"
aliases: /teaching/research-ta
url: /teaching/research-ta
disableAnchoredHeadings: false
description: "Resources used for preparation of research workshops"
showToc: true
TocOpen: true
UseHugoToc: true
---

### General

+ [Cheatsheet for using R](/teaching/research-2023/tidyverse-cheatsheet.pdf) [(source)](https://posit.co/resources/cheatsheets/). The most relevant sheets by function:
    + Data cleaning: *dplyr* and *tidyr*
    + Figures: *ggplot2*
    + Working with character/word vectors: *stringr*
    + If you plan on using R Notebooks: *rmarkdown*
+ [Cheatsheet for using Stata here](/teaching/research-2023/tidyverse-cheatsheet.pdf) [(source)](https://geocenter.github.io/StataTraining/portfolio/01_resource/)

### [Workshop 1: script-writing](/teaching/research-2023/Workshop1-Slides.pdf)

+ See my [econometrics notes below](/teaching/#introduction-to-econometrics) for a refresher on R, R Notebooks, and for an intro econometrics refresher.
+ R: [*fixest*](https://cran.r-project.org/web/packages/fixest/vignettes/fixest_walkthrough.html) for running regressions (as opposed to lm or plm)
    + faster estimation
    + flexible formula writing allows simultaneous estimation of many similar regression models, much simpler and more convenient inclusion of leads, lags, and differences of variables, and intuitive specification of standard errors
    + its **etable** function provides a nice pipeline for creating very customizable tables automatically (better in my opinion than the usual suggestion, which is the stargazer package)
+ R: [*magrittr* for piping](https://magrittr.tidyverse.org/) for very intuitive and readable script-writing especially for data processing. An intro [here](https://www.datacamp.com/tutorial/pipe-r-tutorial).
+ Stata: an intro to [data cleaning functions](https://geocenter.github.io/StataTraining/part2/)

### [Workshop 2: project-oriented workflows](/teaching/research-2023/Workshop2-Slides.pdf)

+ [A guide to code and data for researchers](https://web.stanford.edu/~gentzkow/research/CodeAndData.pdf)

R-specific:

+ [Why use R Projects?](https://rstats.wtf/projects) (the other chapters here are great too)
    + A more basic guide [here](https://stat545.com/r-basics.html)
+ [Relative filepaths using the *here* package](https://here.r-lib.org/)
+ [A guide to R Notebooks](https://bookdown.org/yihui/rmarkdown/notebook.html)
+ A bit more advanced: [R profiles](https://rstats.wtf/r-startup.html)
+ [Setting seeds](https://r-coder.com/set-seed-r/) for replicability

Stata-specific:

+ [Stata's equivalent of R's *here* package for relative filepaths](https://github.com/korenmiklos/here)
+ [Workflows for automating tables](https://lukestein.github.io/stata-latex-workflows/gallery/)
+ More advanced: [Stata's equivalent of R Profiles](https://www.stata.com/support/faqs/programming/profile-do-file/)
+ More advanced: [Jupyter Notebooks for Stata](https://www.stata.com/features/overview/jupyter-notebooks/)
+ [Setting seeds](https://www.stata.com/manuals13/rsetseed.pdf) for replicability

### Additional topics

Topics I'd cover with more time

+ Debugging tips: how to identify bugs in your code
+ Using ChatGPT as a coding resource. Error prone but really valuable if you ask questions well. It also generates reproducible examples if you ask. Some things I use it for:
    + "How do I do [task] in Stata?"
    + "How do I implement [task] in R using [package, e.g. the tidyverse]?"
    + Copy and paste a chunk of code and then ask what each line is doing
    + [pasted code] What's a more efficient way of accomplishing the same thing?"
    + "This is my code: [pasted code]. I get an error that says [X]. Where is my mistake?"
+ Writing your own functions
    + [A guide in R](https://www.dataquest.io/blog/write-functions-in-r/)
    + [A guide in Python](https://www.w3schools.com/python/python_functions.asp)
+ Implementing different kinds of regressions (I do this a little bit in my econometrics notes)
+ Customizing regression tables
+ Data visualization
    + R: see the ggplot2 cheatsheet
    + Stata: see the commands in the cheatsheet and [here](https://geocenter.github.io/StataTraining/part4/)'s a guided introduction

### Other possibly helpful research resources:

+ Trello for keeping notes, maintaining to-do lists, storing relevant documents, summarizing research meetings, etc. Sychronizes across all devices.
+ [How to present an applied micro paper](https://scholar.harvard.edu/files/shapiro/files/applied_micro_slides.pdf)
+ Browser extensions
    + **EZProxy Redirect** to access online resources that Columbia has subscriptions to when away from university internet and without using a VPN
    + **Simple Mass Downloader** to download all files contained in a web page
+ Literature review
    + Google Scholar search is obvious but also click on the "Cited by" link under a search result to find other relevant and possibly more up to date papers and methods or see if someone’s already done what you want to do