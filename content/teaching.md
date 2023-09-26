---
title: "Courses"
aliases: /courses/
url: /courses/
disableAnchoredHeadings: false
description: "Summaries and resources for courses I've TA'd for during my teaching career at Columbia University"
showToc: true
TocOpen: true
UseHugoToc: true

---

*Columbia students can use their university email to book office hours [here](https://calendly.com/wmadavis/).*

*Using this space to share some of the resources I’ve prepared during my TA career at Columbia and my graduate-level coursework at Oxford and Columbia. I’ve seen some of my notes paywalled on Course Hero so please just take it from here for free.*

*Please reach out if you notice any mistakes or typos in this material. Any and all errors are due to the professors who taught me wrong or the students who didn’t point them out.*  

---

### Teaching

*Out of respect for the non-predatory academic publishing industry, I discourage you from finding a free version of any textbooks mentioned here or elsewhere by [Googling their titles]((https://www.google.com/search?q=Introduction+to+Econometrics+watson+4th+edition+pdf&sca_esv=568605030&sxsrf=AM9HkKm2WdaM2SNR0--eUd572Acbx9Egyg%3A1695760925959&ei=HUITZaOMOqOs5NoP5biHSA&ved=0ahUKEwjjjvbckcmBAxUjFlkFHWXcAQkQ4dUDCBA&uact=5&oq=Introduction+to+Econometrics+watson+4th+edition+pdf&gs_lp=Egxnd3Mtd2l6LXNlcnAiM0ludHJvZHVjdGlvbiB0byBFY29ub21ldHJpY3Mgd2F0c29uIDR0aCBlZGl0aW9uIHBkZjIGEAAYFhgeSO8pUN4EWNEocAR4AZABAZgBmQGgAbYTqgEFMTAuMTS4AQPIAQD4AQL4AQHCAgoQABhHGNYEGLADwgIFEC4YgATCAgUQABiABMICFBAuGIAEGJcFGNwEGN4EGOAE2AEBwgIHECMYigUYJ8ICCBAAGIoFGIYD4gMEGAAgQYgGAZAGCLoGBggBEAEYFA&sclient=gws-wiz-serp&bshm=rime/1)), their authors, the edition number, and adding “pdf” at the end. Failing that, I am also hereby disavowing [Sci-Hub](https://sci-hub.se/database) as a resource for obtaining this material as well.*

*I cannot guarantee a response but feel free to email clarifying questions. Video recordings of my econometrics and microeconomics classes may be available upon request to those looking to follow along or supplement their own studies, particularly those from developing countries.*  

#### Senior seminars and research workshops

##### Fall 2023, Spring 2024

Serving as the economics department's research consultant TA providing guidance and preparing workshops for undergraduate and master's students conducting research as part of the honors program, the nine senior seminars, or as part-time research assistants. Resources to be uploaded here as they're produced.

---

#### [Introduction to econometrics](https://github.com/wmadavis/Teaching-IntroEconometrics)

##### Fall 2020, Spring 2021, Fall 2021, Summer 2023

##### Course description

Prerequisites

+ Intermediate microeconomics/macroeconomics
+ Calculus III
+ Introduction to probability and statistics with calculus

> *ECON-UN3412 introduces students to multiple regression and related methods for analyzing data in economics and related disciplines. Additional topics include regression with discrete random variables, instrumental variables regression, analysis of random experiments and quasi-experiments, and regression with time series data. Students will learn how to conduct – and how to critique – empirical studies in economics and related fields. Accordingly, the emphasis of the course is on empirical applications.*

##### Material

Columbia teaches its undergraduates econometrics using Stata, an expensive statistical software whose wide use persists because it’s what most professors learned themselves. The first semester I taught this course, I prepared supplementary material and solutions to provide students the option to instead use R, a free and more flexible open-source alternative preferred by most industries outside academic social science. After some initial trepidation about departing from the official software of instruction, students seemed to find its object-oriented programming much more intuitive and appreciated its usefulness and accessibility beyond the semester course. I refined my material and continued teaching exclusively in R in subsequent semesters and all in all, I think I cost Stata Corporation upwards of $10,000 in lost single-semester license fees.

Below are the weekly guides I produced from the Summer 2023 iteration of my classes, which is accelerated and condensed relative to the regular semester course. These materials include a subset of practice problems but exclude problem sets, exams, practice exams, and their solutions. Most datasets referenced are available for free on the textbook's official website (or else [here](https://www.princeton.edu/~mwatson/Stock-Watson_4E/Stock-Watson-Resources-4e.html). Instruction here assumes no prior experience with programming other than installation of R and RStudio. It introduces and makes use of R Notebooks saved as R Markdown (.Rmd) files, a convenient way of integrating in-line R scripting with intuitive word processing to produce handsome problem sets and reports either as pdfs or HTML files. If you’re following on your own, open the Rmd files in RStudio to see the input and the pdf files to see what the resultant output looks like.

If I were to update this material, I’d integrate .Rprofile and .Rproj files into the problem set pipeline to simplify students' calling frequently used libraries and functions.

##### 1. Introduction to R and R Notebooks

###### Class notes ([Rmd](/teaching/metrics-2023-summer/01-R-Introduction.Rmd) | [PDF](/teaching/metrics-2023-summer/01-R-Introduction.pdf)) || Data practice problems ([Rmd](/teaching/metrics-2023-summer/01-R-Introduction.Rmd) | [PDF](/teaching/metrics-2023-summer/01-R-Introduction.pdf))
###### Written practice problems ([PDF](/teaching/metrics-2023-summer/01-PracticeProblems-iPad.pdf))

##### 2. Multicollinearity, joint hypothesis testing, and the tidyverse

###### Class notes ([Rmd](/teaching/metrics-2023-summer/02-Multicollinearity-JointHypotheses.Rmd) | [PDF](/teaching/metrics-2023-summer/02-Multicollinearity-JointHypotheses.pdf))

##### 3. Exam 1 review: points of emphasis ([PDF](/teaching/metrics-2023-summer/03-ExtraNotes.pdf))

##### 4. Nonlinear regression

###### Class notes ([Rmd](/teaching/metrics-2023-summer/04-NonLinearRegression.Rmd) | [PDF](/teaching/metrics-2023-summer/04-NonLinearRegression.pdf))

##### 5. Panel data methods and binary dependent variables

###### Class notes ([Rmd](/teaching/metrics-2023-summer/05-Panels-BinaryDVs.Rmd) | [PDF](/teaching/metrics-2023-summer/05-Panels-BinaryDVs.pdf))

##### 6. Exam 2 review: intuition for fixed effects ([PDF](/teaching/metrics-2023-summer/05-FixedEffects.pdf))

##### 7. Instrumental variables and quasi-experiments

###### Class notes (([Rmd](/teaching/metrics-2023-summer/07-Instruments-Experiments.Rmd) | [PDF](/teaching/metrics-2023-summer/07-Instruments-Experiments.pdf)) || The control variable approach to IV regression ([PDF](/teaching/metrics-2023-summer/07-ControlVariableApproach.pdf))

##### 8. Big data, time series and dynamic causal effects

###### Class notes ([Rmd](/teaching/metrics-2023-summer/08-TimeSeries-DynamicCausalEffects.Rmd) | [PDF](/teaching/metrics-2023-summer/08-TimeSeries-DynamicCausalEffects.pdf)) || Additional big data practice problems ([PDF](/teaching/metrics-2023-summer/08-bigDataPracticeProblems.pdf))

##### 9. Exam 3 review: final points of emphasis ([PDF](/teaching/metrics/2023-summer/09-Exam3-Review.pdf))

---

#### [Intermediate microeconomics](https://github.com/wmadavis/Teaching-IntermediateMicro)

##### Spring 2022, Fall 2022

##### Course description

Textbook: ["Intermediate Microeconomics with Calculus” --- Hal Varian (2014)](https://www.google.com/search?q=intermediate+microeconomics+with+calculus+hal+varian+pdf&oq=intermediate&gs_lcrp=EgZjaHJvbWUqCAgCEEUYJxg7Mg8IABBFGDkYgwEYsQMYgAQyCAgBEEUYJxg7MggIAhBFGCcYOzINCAMQABiDARixAxiABDINCAQQABiDARixAxiABDITCAUQLhiDARjHARixAxjRAxiABDINCAYQABiDARixAxiABDIGCAcQRRg90gEIMjg4NmowajeoAgCwAgA&sourceid=chrome&ie=UTF-8&bshm=rime/1)  

Prerequisites

+ Principles of Economics
+ Calculus III

> *The purpose of this course is to offer a solid, intermediate-level training in theoretical microeconomics. We will try to achieve a more in-depth understanding of how the standard theoretical models of microeconomics work. The course consists of three parts. We will start out by analyzing consumer decision-making. We then turn to the behavior of firms. Finally, the third part of the course studies the interaction of consumers and firms in goods markets.*  

##### Material

These slides are weekly elaborations on a specific newly introduced concept and so do not represent comprehensive coverage of the course material. They’re also not necessarily self-contained; I sometimes supplemented my slides with blackboard work and conversation with students, which is not always captured in the annotations. Course material is also instructor-specific; if you’re reading this as a Columbia student taking the same course, it may not correspond to the treatment or selection of topics your particular instructor chooses to cover. For example, compared to my Spring 2022 coverage, the following material from Fall 2022 covers a wider range of topics but omits some material such as the method of Lagrange multipliers.

##### 0. Pre-course material

###### Review of prerequisite calculus and optimization methods ([PDF](/teaching/micro-2022-fall/00-OptimizationReview.pdf))
######  Running log of responses to student emails and and corrections to weekly slides ([PDF](/teaching/micro-2022-fall/00-RunningUpdates.pdf))

##### 1. Consumer optimization ([PDF](/teaching/micro-2022-fall/01-ConsumerOptimization.pdf))

##### 2. Hicksian demand and special well-behaved preferences ([PDF](/teaching/micro-2022-fall/02-HicksianDemand-SpecialPreferences.pdf))

##### 3. Comparative statics and Slutsky decomposition of price effects ([PDF](/teaching/micro-2022-fall/03-ComparativeStatics-IncomeSubstitutionEffects.pdf))

##### 4. Hicksian decomposition of price effects and introduction to welfare ([PDF](/teaching/micro-2022-fall/04-HicksianDecomposition-Welfare.pdf))

##### 5. Producer Theory I: Cost minimization ([PDF](/teaching/micro-2022-fall/05-ProducerTheory-CostMinimization.pdf))

##### 6. Producer Theory II: Profit maximization under perfect competition ([PDF](/teaching/micro-2022-fall/06-ProducerTheory-ProfitMaximization-MarketEquilibrium.pdf))

##### 7. General equilibrium ([PDF](/teaching/micro-2022-fall/07-GeneralEquilibrium.pdf))

##### 8. Exchange economies and the Edgeworth box ([PDF](/teaching/micro-2022-fall/08-ExchangeEconomies-MarketClearing-NonInteriorSolutions.pdf)

###### By student request, an applied derivation of IC equations and intersections for accurate graphing ([PDF](/teaching/micro-2022-fall/08-GraphingExample.pdf))

##### 9. Models of monopolistic and oligopolistic competition ([PDF](/teaching/micro-2022-fall/09-ImperfectCompetition.pdf))

##### 10. Pre-final review

###### Comparing models of oligopolistic competition ([PDF](/teaching/micro-2022-fall/10-FinalReview.pdf))
###### High-level summary and takeaways from the course ([PDF](/teaching/micro-2022-fall/10-CourseSummary.pdf))

---

#### The global economy

##### Spring 2023

> *This international economics course is targeted towards non-economics students, focusing on current events and the increasing international interdependence of the world economy. Topics incude: (i) why countries trade, what goods and services will be traded, how the gains from trade are distributed and the tools of commercial policy; (ii) the movement of labor and capital across borders; value of transnational countries and production processes across countries; (iii) international finance issues including exchange rates, balance of payments and open economy macroeconomic adjustment.*  


---

## Graduate coursework

(working links coming... eventually)

*An incomplete archive of notes of variable quality from the two graduate schools I’ve attended. I may scan and upload my handwritten notes once I can regain access to them. The gold standard is still [Luke Stein’s first-year notes from the Stanford core sequence](https://faculty.babson.edu/lcdstein/steincoresummary.pdf).*

#### Columbia PhD core

##### Year 1:

+ **Econometrics I, Part II**: Asymptotic theory, restricted estimation, and resampling
+ **Econometrics II, Part II**: Resampling, multiple testing, quantile regression, non-parametrics, and treatment effects
+ **Macroeconomics I, Part I** (incomplete summary): Introduction to growth theory
+ **Macroeconomics I, Part II**: General equilibrium theory, real business cycles, and an introduction to macro-finance

#### Oxford M.Phil core and fields


##### Year 1 Core

+ **Macroeconomics**: Qualitative summary of the entire year of material: neoclassical growth theory, macro-finance, monetary economics, macroeconomic policy
+ **Macro-finance**: consumption CAPM, exotic preferences, disaster risk, evidence on financial crises, financial frictions, the Great Recession, liquidity, quantitative easing, and financial bubbles

##### Year 2 Fields

+ **Advanced Microeconomics**: Contracts under information asymmetries, bargaining, and theories of the firm. Notes make reference to figures that are handwritten and not included
+ **Political Economy of Development**:  Literature review: culture and institutions, political reform and political failure, corruption, and conflict
+ **Applied microeconomics**: production function estimation (incomplete short summary), problems and accounting