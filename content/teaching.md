---
title: "Teaching"
aliases: /teaching/
url: /teaching/
disableAnchoredHeadings: false
description: "Summaries and resources for courses I've TA'd for during my teaching career at Columbia University"
showToc: true
TocOpen: true
UseHugoToc: true
---

*Using this space to share some of the resources I’ve prepared during my TA career at Columbia. I’ve seen some of my notes paywalled on Course Hero so please just take it from here for free. Columbia students can use their university email to book office hours [here](https://calendly.com/wmadavis/).*  

*Out of respect for the hard work of academic publishers, I discourage anyone from obtaining free copies of the $100+ dollar textbooks mentioned here or elsewhere by typing their title, author, and edition number plus “pdf” into Google. In addition, I hereby disavow [Sci-Hub](https://sci-hub.se/database) as another resource for easily obtaining this material for free.*


*Please reach out if you notice any mistakes or typos in this material. Any and all errors are due to the professors who taught me wrong or the students who didn’t point them out.*  

---

### Introduction to econometrics

Fall 2020 $\cdot$ Spring 2021 $\cdot$ Fall 2021 $\cdot$ Summer 2023  

> *"ECON-UN3412 introduces students to multiple regression and related methods for analyzing data in economics and related disciplines. Additional topics include regression with discrete random variables, instrumental variables regression, analysis of random experiments and quasi-experiments, and regression with time series data. Students will learn how to conduct – and how to critique – empirical studies in economics and related fields. Accordingly, the emphasis of the course is on empirical applications."*  

Text: [*Introduction to Econometrics*](https://www.sea-stat.com/wp-content/uploads/2020/08/James-H.-Stock-Mark-W.-Watson-Introduction-to-Econometrics-Global-Edition-Pearson-Education-Limited-2020.pdf), James Stock and Mark Watson (2019, 2020)

#### Prepared material

Columbia teaches its undergraduates econometrics using Stata, a subscription statistical software whose wide use mostly persists because it’s what most professors learned themselves. The first semester I taught this course, I prepared supplementary material and solutions to provide students the option to instead use R, a free open-source alternative preferred by most industries outside academic social science. After some initial trepidation about departing from the official software of instruction, students seemed to find its object-oriented programming much more intuitive and appreciated its utility and accessibility beyond the semester course. I refined my material and continued teaching exclusively in R in subsequent semesters and all in all, I think I've cost Stata Corporation upwards of $10,000 in lost single-semester license fees.

Below are the weekly guides I produced from the Summer 2023 iteration of my classes, which is accelerated and condensed relative to the regular semester course. These materials include a subset of practice problems but exclude material prepared for problem sets, exams, practice exams, and their solutions. Most datasets referenced are available for free [here.](https://www.princeton.edu/~mwatson/Stock-Watson_4E/Stock-Watson-Resources-4e.html)

Instruction here presumes no prior experience with programming other than installation of R and RStudio. It introduces and makes use of R Notebooks saved as R Markdown (.Rmd) files, a convenient way of integrating in-line R scripting with intuitive and customizable word processing to produce handsome problem sets and reports either as pdfs or HTML files. If you’re following on your own, open the Rmd files in RStudio to see the input and the pdf files to see what the resultant output looks like. If I were to update this material, I’d integrate .Rprofiles into the problem set pipeline to simplify students' pipelines.

##### 1. Introduction to R and R Notebooks | [RMD](/teaching/metrics-2023-summer/01-R-Introduction.Rmd) $\cdot$ [PDF](/teaching/metrics-2023-summer/01-R-Introduction.pdf)

##### 2. Multicollinearity, joint hypothesis testing, and the tidyverse   |   [RMD](/teaching/metrics-2023-summer/02-Multicollinearity-JointHypotheses.Rmd) $\cdot$ [PDF](/teaching/metrics-2023-summer/02-Multicollinearity-JointHypotheses.pdf)

##### 3. Exam 1 review   |   [PDF](/teaching/metrics-2023-summer/03-ExtraNotes.pdf)

##### 4. Nonlinear regression   |   [RMD](/teaching/metrics-2023-summer/04-NonLinearRegression.Rmd) $\cdot$ [PDF](/teaching/metrics-2023-summer/04-NonLinearRegression.pdf)

##### 5. Panel data methods and binary dependent variables   |   [RMD](/teaching/metrics-2023-summer/05-Panels-BinaryDVs.Rmd) $\cdot$ [PDF](/teaching/metrics-2023-summer/05-Panels-BinaryDVs.pdf)

##### 6. Exam 2 review   |   [PDF](/teaching/metrics-2023-summer/05-FixedEffects.pdf)

##### 7. Instrumental variables and quasi-experiments   |   [RMD](/teaching/metrics-2023-summer/07-Instruments-Experiments.Rmd) $\cdot$ [PDF](/teaching/metrics-2023-summer/07-Instruments-Experiments.pdf)

##### 8. Big data, time series and dynamic causal effects   |   [RMD](/teaching/metrics-2023-summer/08-TimeSeries-DynamicCausalEffects.Rmd) $\cdot$ [PDF](/teaching/metrics-2023-summer/08-TimeSeries-DynamicCausalEffects.pdf)

##### 9. Exam 3 review   |   [PDF](/teaching/metrics/2023-summer/09-Exam3-Review.pdf)

---

### Intermediate microeconomics

Spring 2022 $\cdot$ Fall 2022  

> *"The purpose of this course is to offer a solid, intermediate-level training in theoretical microeconomics. We will try to achieve a more in-depth understanding of how the standard theoretical models of microeconomics work. The course consists of three parts. We will start out by analyzing consumer decision-making. We then turn to the behavior of firms. Finally, the third part of the course studies the interaction of consumers and firms in goods markets."*  

Text: [*Intermediate Microeconomics with Calculus*](https://fac.ksu.edu.sa/sites/default/files/microeco-_varian.pdf), Hal Varian (2014)

#### Prepared material

These slides are weekly elaborations on a specific newly introduced concept and so do not represent comprehensive coverage of the course material. They’re also not necessarily self-contained; I sometimes supplemented my slides with blackboard work and conversation with students, which is not always captured in the annotations. Course material is also instructor-specific; if you’re reading this as a Columbia student taking the same course, it may not correspond to the treatment or selection of topics your particular instructor chooses to cover. For example, compared to my Spring 2022 coverage, the following material from Fall 2022 covers a wider range of topics but omits some material such as the method of Lagrange multipliers.

##### 0. Review of prerequisite calculus and optimization methods   |   [PDF](/teaching/micro-2022-fall/00-OptimizationReview.pdf)

##### 1. Consumer optimization   |   [PDF](/teaching/micro-2022-fall/01-ConsumerOptimization.pdf)

##### 2. Hicksian demand and special well-behaved preferences   |   [PDF](/teaching/micro-2022-fall/02-HicksianDemand-SpecialPreferences.pdf)

##### 3. Comparative statics and Slutsky decomposition of price effects   |   [PDF](/teaching/micro-2022-fall/03-ComparativeStatics-IncomeSubstitutionEffects.pdf)

##### 4. Hicksian decomposition of price effects and introduction to welfare   |   [PDF](/teaching/micro-2022-fall/04-HicksianDecomposition-Welfare.pdf)

##### 5. Producer Theory I: Cost minimization   |   [PDF](/teaching/micro-2022-fall/05-ProducerTheory-CostMinimization.pdf)

##### 6. Producer Theory II: Profit maximization under perfect competition   |   [PDF](/teaching/micro-2022-fall/06-ProducerTheory-ProfitMaximization-MarketEquilibrium.pdf)

##### 7. General equilibrium $\cdot$ [PDF](/teaching/micro-2022-fall/07-GeneralEquilibrium.pdf)

##### 8. Exchange economies and the Edgeworth box   |   [PDF](/teaching/micro-2022-fall/08-ExchangeEconomies-MarketClearing-NonInteriorSolutions.pdf)

##### 9. Models of monopolistic and oligopolistic competition   |   [PDF](/teaching/micro-2022-fall/09-ImperfectCompetition.pdf)

##### 10. Comparing models of oligopolistic competition   |   [PDF](/teaching/micro-2022-fall/10-FinalReview.pdf)

##### A1. Running log of student emails and and corrections to weekly slides   |   [PDF](/teaching/micro-2022-fall/00-RunningUpdates.pdf)

##### A2. Week 8: by student request, an applied derivation of IC equations and intersections for accurate graphing   |   [PDF](/teaching/micro-2022-fall/08-GraphingExample.pdf)

##### A3. Week 10: High-level summary and takeaways from the course   |   [PDF](/teaching/micro-2022-fall/10-CourseSummary.pdf)

---

### Economics department research consultant

Fall 2023 $\cdot$ Spring 2024  

Weekly office hours available to all economics students conducting research for the ten senior thesis seminars or as part-time research assistants. Also tasked with designing and delivering research workshops for honors students.

#### Prepared material

Coming soon!

---

### The global economy

Spring 2023

> *"This international economics course is targeted towards non-economics students, focusing on current events and the increasing international interdependence of the world economy. Topics incude: (i) why countries trade, what goods and services will be traded, how the gains from trade are distributed and the tools of commercial policy; (ii) the movement of labor and capital across borders; value of transnational countries and production processes across countries; (iii) international finance issues including exchange rates, balance of payments and open economy macroeconomic adjustment."*

*(Not permitted to share material)*