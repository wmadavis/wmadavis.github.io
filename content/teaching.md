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

*(Columbia students can use their university email to book office hours [here](https://calendly.com/wmadavis/))*

*Using this space to share some of the resources I’ve prepared during my teaching career at Columbia. I’ve also seen some of my material paywalled on Course Hero so please just take it from here for free. I have also included some notes from graduate coursework I've taken.  *  

*I cannot guarantee a response but feel free to email clarifying questions about any of this material. Video recordings of my classes may be available upon request to those looking to follow along at their own pace or supplement their own studies, especially those from developing countries.*  

*Any errors are due to the professors who taught me wrong or the students who didn’t point them out.*  

### Senior seminars and research workshops (ECON-GU4999)

**Fall 2023, Spring 2024**  

Prerequisites

+ Intermediate microeconomics
+ Intermediate macroeconomics
+ Introduction to econometrics

Serving as the department's research consultant TA providing guidance and preparing workshops for economics students conducting research as part of the honors program, the nine senior seminars, or as part-time research assistants.

#### Resources

(to be updated)

---

### [Introduction to econometrics (ECON-UN3412)](https://github.com/wmadavis/Teaching-IntroEconometrics)

**Fall 2020, Spring 2021, Fall 2021, Summer 2023**  

Prerequisites

+ Intermediate microeconomics/macroeconomics
+ Calculus III
+ Introduction to probability and statistics with calculus

> *ECON-UN3412 introduces students to multiple regression and related methods for analyzing data in economics and related disciplines. Additional topics include regression with discrete random variables, instrumental variables regression, analysis of random experiments and quasi-experiments, and regression with time series data. Students will learn how to conduct – and how to critique – empirical studies in economics and related fields. Accordingly, the emphasis of the course is on empirical applications.*

#### Resources

Columbia teaches its undergraduates econometrics using Stata, an expensive statistical software whose wide use persists because it’s what most professors learned themselves. The first semester I taught this course, I prepared supplementary material and solutions to provide students the option to instead use R, a free and more flexible open-source alternative like Python and Julia preferred by most industries outside academic social science. After some initial trepidation about departing from the official software of instruction, students seemed to find its object-oriented programming much more intuitive and appreciated its usefulness and accessibility beyond the semester course. I refined my material and continued teaching exclusively in R in subsequent semesters and all in all, I think I cost Stata Corporation upwards of $10,000 in lost single-semester license fees.

Below are the weekly guides I produced, mostly from the Summer 2023 iteration of my classes. These exclude problem sets, exams, practice exams, and their solutions. Most datasets referenced are available for free on the textbook's official website. Instruction here assumes no prior experience with programming other than installation of R and RStudio. It introduces and makes use of R Notebooks saved as R Markdown (.Rmd) files, a convenient way of integrating in-line R scripting with intuitive word processing to produce handsome problem sets and reports either as pdfs or HTML files. If you’re following on your own, open the Rmd files in RStudio to see the input and the pdf files to see what the resultant output looks like.

If I were to teach this course again, I’d replace the working directories coverage with an introduction to R Projects and the here() function, which I’ve since integrated into my own coding practice. It’s a minor and very intuitive adjustment that quickly makes up for the time spent learning it so there’s actually no time tradeoff here. Until then, here’s a guide that would immediately put you ahead of probably 95% of professional social scientists in terms of project management hygiene and coding etiquette. Packages used throughout are not necessarily my favorites (for example, fixest is clearly the cutting edge for panel data methods), but were chosen to produce estimates identical to Stata’s.

**(links below to be updated eventually)**

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

---

### [Intermediate microeconomics (ECON-UN3211)](https://github.com/wmadavis/Teaching-IntermediateMicro)

**Spring 2022, Fall 2022**  

Prerequisites

+ Principles of Economics
+ Calculus III

> *The purpose of this course is to offer a solid, intermediate-level training in theoretical microeconomics. We will try to achieve a more in-depth understanding of how the standard theoretical models of microeconomics work. The course consists of three parts. We will start out by analyzing consumer decision-making. We then turn to the behavior of firms. Finally, the third part of the course studies the interaction of consumers and firms in goods markets.*  

Textbook

+ ["Intermediate Microeconomics with Calculus” --- Hal Varian (2014)](https://www.google.com/search?q=intermediate+microeconomics+with+calculus+hal+varian+pdf&oq=intermediate&gs_lcrp=EgZjaHJvbWUqCAgCEEUYJxg7Mg8IABBFGDkYgwEYsQMYgAQyCAgBEEUYJxg7MggIAhBFGCcYOzINCAMQABiDARixAxiABDINCAQQABiDARixAxiABDITCAUQLhiDARjHARixAxjRAxiABDINCAYQABiDARixAxiABDIGCAcQRRg90gEIMjg4NmowajeoAgCwAgA&sourceid=chrome&ie=UTF-8&bshm=rime/1)

#### Resources

(to be updated)

These slides are weekly elaborations on a specific newly introduced concept and so do not represent comprehensive coverage of the course material. They’re also not necessarily self-contained; I sometimes supplemented my slides with blackboard work and conversation with students, which is not always captured in the annotations. Course material is also instructor-specific; if you’re reading this as a Columbia student taking the same course, it may not correspond to the treatment or selection of topics your particular instructor chooses to cover. For example, compared to my Spring 2022 coverage, the following material from Fall 2022 covers a wider range of topics but omits some material such as the method of Lagrange multipliers.

##### 0. Pre-course material

+ [Review of prerequisite calculus and optimization methods](/teaching/micro-2022-fall/00-OptimizationReview.pdf)
+ Logistics and introduction to the course

##### 1. Consumer optimization

##### 2. Hicksian demand and special well-behaved preferences

##### 3. Comparative statics and Slutsky decomposition of price effects

##### 4. Hicksian decomposition of price effects and introduction to welfare

##### 5. Producer Theory I: Cost minimization

##### 6. Producer Theory II: Profit maximization under perfect competition

##### 7. General equilibrium

##### 8. Exchange economies and the Edgeworth boxBonus: by student request, an applied derivation of IC equations and intersections for accurate graphing 

##### 9. Models of monopolistic and oligopolistic competition

##### 10. Pre-final review

##### 11. Running log of responses to student emails and and corrections to weekly slides

##### 12. Comparing models of oligopolistic competition

##### 13. High-level summary and takeaways from the course

---

### The global economy (ECON-UN2257)

**Spring 2023**  

> *This international economics course is targeted towards non-economics students, focusing on current events and the increasing international interdependence of the world economy. Topics incude: (i) why countries trade, what goods and services will be traded, how the gains from trade are distributed and the tools of commercial policy; (ii) the movement of labor and capital across borders; value of transnational countries and production processes across countries; (iii) international finance issues including exchange rates, balance of payments and open economy macroeconomic adjustment.*  


---

### Graduate coursework notes

(working links coming eventually)

*An incomplete archive of notes of variable quality from the two graduate schools I’ve attended. I may scan and upload my handwritten notes once I can regain access to them. The gold standard is still [Luke Stein’s first-year notes from the Stanford core sequence](https://faculty.babson.edu/lcdstein/steincoresummary.pdf).*

#### Columbia PhD (Year 1)

+ **Econometrics I, Part II**: Asymptotic theory, restricted estimation, and resampling
+ **Econometrics II, Part II**: Resampling, multiple testing, quantile regression, non-parametrics, and treatment effects
+ **Macroeconomics I, Part I** (incomplete summary): Introduction to growth theory
+ **Macroeconomics I, Part II**: General equilibrium theory, real business cycles, and an introduction to macro-finance

#### Oxford MPhil (Year 2)

+ **Advanced Microeconomics**: Contracts under information asymmetries, bargaining, and theories of the firm. Notes make reference to figures that are handwritten and not included
+ **Political Economy of Development**:  Literature review: culture and institutions, political reform and political failure, corruption, and conflict
+ **Applied microeconomics**: production function estimation (incomplete short summary), problems and accounting

#### Oxford MPhil (Year 1)

+ **Macroeconomics**: Qualitative summary of the entire year of material: neoclassical growth theory, macro-finance, monetary economics, macroeconomic policy
+ **Macro-finance**: consumption CAPM, exotic preferences, disaster risk, evidence on financial crises, financial frictions, the Great Recession, liquidity, quantitative easing, and financial bubbles