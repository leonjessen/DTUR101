DTUR101 - Introduction to Applied Data Analysis with R
================

-   [Course Introduction](#course-introduction)
    -   [Aim](#aim)
    -   [Teacher](#teacher)
    -   [Scope and Form](#scope-and-form)
    -   [Recommended Prerequisites](#recommended-prerequisites)
    -   [Content](#content)
    -   [Schedule](#schedule)
    -   [Software](#software)
    -   [Questions](#questions)
-   [Course Timetable](#course-timetable)
    -   [Week 1 - Monday January 29th 2018 13-17](#week-1---monday-january-29th-2018-13-17)
    -   [Week 2 - Monday February 5th 2018 13-17](#week-2---monday-february-5th-2018-13-17)
    -   [Week 3 - Monday February 12th 2018 13-17](#week-3---monday-february-12th-2018-13-17)
    -   [Week 4 - Monday February 19th 2018 13-17](#week-4---monday-february-19th-2018-13-17)
    -   [Week 5 - Monday February 26th 2018 13-17](#week-5---monday-february-26th-2018-13-17)
    -   [Week 6 - Monday March 5th 2018 13-17](#week-6---monday-march-5th-2018-13-17)
    -   [Week 7 - Monday March 12th 2018 13-17](#week-7---monday-march-12th-2018-13-17)
    -   [Week 8 - Monday March 26th 2018 13-17](#week-8---monday-march-26th-2018-13-17)
    -   [Week 9 - Monday April 9th 2018 13-17](#week-9---monday-april-9th-2018-13-17)
    -   [Week 10 - Monday April 23rd 2018 13-17](#week-10---monday-april-23rd-2018-13-17)
    -   [Week 11 - Monday April 30th 2018 13-17](#week-11---monday-april-30th-2018-13-17)
    -   [Week 12 - Monday May 7th 2018 13-17](#week-12---monday-may-7th-2018-13-17)
    -   [Week 13 - Monday May 14th 2018 13-17](#week-13---monday-may-14th-2018-13-17)
    -   [Course Curriculum Wrap Up](#course-curriculum-wrap-up)
    -   [Important Resources for Data Science in R](#important-resources-for-data-science-in-r)
    -   [Additional Videos](#additional-videos)

Course Introduction
===================

Aim
---

The aim of 'Introduction to Applied Data Analysis with R' is to introduce the [The R Project for Statistical Computing](https://www.r-project.org/) and the [Tidyverse framework](https://www.tidyverse.org/) to tidy, transform, visualise, analyse, model and communicate our data in the context of wet-lab bio-engineering. The course will run as a PhD+ course and participants are eligeble to collect 2.5 ECTS points.

Teacher
-------

The course will be taught by [Leon Eyrich Jessen](http://www.dtu.dk/service/telefonbog/person?id=22554&cpid=230023&tab=2&qt=dtupublicationquery) from the [Immunoinformatics and Machine Learning](http://www.bioinformatics.dtu.dk/english/Research_new/Health-informatics/Immunoinformatics-and-machine-learning) group at Department of Bio and Health Informatics at the Technical University of Denmark.

Scope and Form
--------------

The course consist of a series of [video lectures](https://www.youtube.com/playlist?list=PL4L59zaizb3FmBdxuDLRdzGsknTrZN6Ys) by [Morten Arendt Rasmussen](http://food.ku.dk/english/staff/?pure=en/persons/311655/), followed by hands-on exercises. Before each lecture students are expected to have seen the 1-2 videos. We will then start with discussing the videos and follow up with how to apply the concepts in R. This means that if the video includes a demonstration in R, you are of course welcome to see it - BUT it will not nessesarily be the demonstration we will work with at the exercises.

Recommended Prerequisites
-------------------------

It is expected that students have a basic knowledge of math and calculus and linear algebra equivalent to introductory university courses. No prior knowledge of programming is required.

Content
-------

Non-exhaustive: We will cover descriptive statistics, data distribution, t-test, PCA, data manipulation, exploration, visualisation and documentation in R.

Schedule
--------

The course will run in the spring semester (13-week period) of 2018, which according to the [DTU academic calendar](http://www.dtu.dk/english/education/student-guide/studying-at-dtu/Academic-calendar) is from 29/1 2018 to 8/5 2018, exluding holiday and non-teaching study breaks.

Software
--------

Students are required to bring their own laptop and preferably install the following software before the first class

-   [R](https://mirrors.dotsrc.org/cran/)
-   [RStudio](https://www.rstudio.com/products/rstudio/download/#download)

Questions
---------

Please contact course responsible [Leon Eyrich Jessen](http://www.dtu.dk/service/telefonbog/person?id=22554&cpid=230023&tab=2&qt=dtupublicationquery)

Course Timetable
================

Week 1 - Monday January 29th 2018 13-17
---------------------------------------

**Location**

-   The library at DTU Bioinformatics (building 208, room 027) at 1pm.

**Background**

The first day we will focus on getting the software we need up and running. Then we will dive into programming in R. There will be a learning curve, I am fully aware of this, but I am confident that if you put the effort into climbing it, the reward will be well worth it. Programming is not only learning what to write when, but it is also learning a certain way of thinking - A new mindset if you will.

Please try to install R and RStudio before the first class

-   [R](https://mirrors.dotsrc.org/cran/)
-   [RStudio](https://www.rstudio.com/products/rstudio/download/#download)

**Class Curriculum**

-   Installing R, RStudio and TidyVerse
-   Gentle introduction to programming in general and in R
-   If we have time, video: [1 - Descriptive Statistics](https://www.youtube.com/watch?v=SOYt84ZPTx0)

**Post Class**

-   [Here is the code we went through today](R/day_01.R)

Week 2 - Monday February 5th 2018 13-17
---------------------------------------

**Location**

-   Ly202-R8107-LIFE 1pm - 5pm

**Background**

Based on what we learned in week 1, we will move onto some data visualisation using the `ggplot` package, which is part of the [`tidyverse`](https://www.tidyverse.org/) framework. The `tidyverse` framework is a particular take on how to do data analysis. It implements a philosophy where the work goes into getting your data into a well-defined format and once this is obtained, the different `tidyverse` functions can be applied to import-tidy-transform-visualise-model-communicate your data as illustrated in this figure (taken from [R for Data Science](http://r4ds.had.co.nz/))

![](figures/data_cycle.png)

This means, that we will leave base R for now and henceforth we will continue our endevour using `Tidyverse`.

Please try to install `Tidyverse` before the class

-   In the console in RStudio, run this command: `install.packages('tidyverse')`

**Class Curriculum**

-   Recapitulation of previous class
-   Introduction to `Tidyverse`
-   Data visualisation using `ggplot`
-   Video: [2 - Plotting with ggplot2](https://www.youtube.com/watch?v=oXlXVyiedBw)

**Post Class**

-   [Here is the code we went through today](R/day_02.R)
-   [And a presentation on tidyverse](http://htmlpreview.github.io/?https://github.com/leonjessen/DTUR101/blob/master/doc/tidy_talk.html)

Week 3 - Monday February 12th 2018 13-17
----------------------------------------

**Location**

-   Ly202-R8107-LIFE 1pm - 5pm

**Background**

Now we have learned the basics of `R`, touched upon descriptive statistics and been introduced to `tidyverse` and `ggplot`. We continue with data visualisation and then turn to data distributions. We will take a closer at the normal distribution and also look at confidence intervals, when estimating population mean based on a sample.

**Class Curriculum**

-   Recapitulation of previous class
-   Data visualisation using `ggplot` continued
-   Introduction to data distributions
-   The normal distribution
-   Confidence intervals
-   Video: [7 - Normal distribution](https://www.youtube.com/watch?v=C_INrc633uk)
-   Video: [8 - Normal distribution Confidence Interval](https://www.youtube.com/watch?v=02S8L5H6l0U)

**Post Class**

-   [Here is the code we went through today](R/day_03.R)
-   [Confidence Intervals Visualised](https://github.com/leonjessen/confidence_intervals_visualised)

Week 4 - Monday February 19th 2018 13-17
----------------------------------------

**Location**

-   Ly202-R8107-LIFE 1pm - 5pm

**Background**

We have now become more familiar with `R` and we have tried to solve some simple tasks on our own. We have touched upon the normal distribution and used it to calculate some probabilities. We also discussed some properties of probability density functions. Now it is time to address how we state and test a hypothesis. Furthermore we will discuss how we interpret the result of a test and also possible errors. We will use the `t-test` as a point of reference for this.

**Class Curriculum**

-   Recapitulation of previous class
-   Briefly on cleaning data
-   The standard normal distribution
-   Statistical hypothesis
-   The `t-test`
-   Test statistics, p-values, level of significance, type I and II errors
-   Video: [9 - T-test](https://www.youtube.com/watch?v=D996ja8ZBN4)
-   Video: [10 - T-test inR](https://www.youtube.com/watch?v=KDpsF5dgIVI)

**Post Class**

-   [Here is the code we went through today](R/day_04.R)
-   [Answer to exercises](R/day_04_exercise.R)

Week 5 - Monday February 26th 2018 13-17
----------------------------------------

**Location**

-   NB! Class rescheduled to Friday March 2nd
-   Ly202-R8107-LIFE 1pm - 5pm

**Background**

Last class we went over cleaning of data, the standard normal distribution, what constitutes a hypothesis in statistical terminology. Lastly we turned to manual implementation of a t-test and in that context discussed the connection between the test statistics and the p-value. I realise that it a bit more challenging, but please try to remember that it is natural to feel frustration when absorbing new knowledge. Especially in this case, where you have to absorb not only how-to-code-in-R, but also statistics and math, which does require a level of abstraction, which is challenging. See it as if you are trying to learn a new language, which in essense is quite comparable to what we are doing. We will go over the manual t-test for the `shoe_size` variable to ensure that we are all on the same page. Then I will introduce and discuss some more statistical terminology: Level of significance, Type I error, Type II error and power.

**Class Curriculum**

-   Recapitulation of previous class
-   Manual t-test for `shoe_size` variable in our data
-   Level of significance, type I and II errors
-   Statistical power
-   Video: [17 - Power calculation for Ttest-data](https://www.youtube.com/watch?v=uDvfgpvrhqM)
-   Video: [18 - Power calculation for Ttest type data inR](https://www.youtube.com/watch?v=FeQKkkpd-Ew)

**Post Class**

-   [Here is the code we went through today](R/day_05.R)
-   [Answer to exercises](R/day_05_exercise.R)

Week 6 - Monday March 5th 2018 13-17
------------------------------------

**Location**

-   Ly202-R8107-LIFE 1pm - 5pm

**Background**

We will spent some time on the exercises from last week and then go over the going over basic statistical concepts again, so we all agree on:

-   Descriptive statistics
-   Statistical inference (sample versus population)
-   The normal distibution (aka Gaussian)
-   Confidence intervals
-   The standard normal distribution (standard-/z-score normalisation)
-   Hypothesis testing (null versus alternative)
-   p-values
-   Level of significance
-   Power
-   Alpha values
-   Beta values
-   Type I error (False positives)
-   Type II error (False negatives)
-   Confusion matrices

If you are still uncertain on these concepts, please take a look again at the code from the last classes, rewatch some of the videos and try yo use google. Please feel free to mail me, if you have reached the level of destructive frustration. After this we will do the exercises on correlation and covariance.

**Class Curriculum**

-   Midway evaluation
-   Recapitulation of previous class
-   Summary of basic statistical concepts
-   Correlation and covariance
-   Video: [5 - Correlation and Covariance - Nuts and bolt](https://www.youtube.com/watch?v=WcPGgtptxZ4)

**Post Class**

-   [Here is the code we went through today](R/day_06.R)
-   [Answer to exercises](R/day_06_exercise.R)

Week 7 - Monday March 12th 2018 13-17
-------------------------------------

**Location**

-   Ly202-R8107-LIFE 1pm - 5pm

**Background**

We will start with going over the results of the midway evaluation. Then we will expand on the topics of correlation and covariance.

**Class Curriculum**

-   [Results of midway evaluation](https://htmlpreview.github.io/?https://github.com/leonjessen/DTUR101/blob/master/doc/midway_eval.html)
-   [Answer to exercises](R/day_07_exercise.R)
-   Video: [Statistics 101: Simple Linear Regression, The Very Basics](https://www.youtube.com/watch?v=ZkjP5RJLQF4)
-   Video: [Statistics 101: Linear Regression, Algebra, Equations, and Patterns](https://www.youtube.com/watch?v=iAgYLRy7e20)
-   Video: [Statistics 101: Simple Linear Regression, The Least Squares Method](https://www.youtube.com/watch?v=Qa2APhWjQPc)
-   Video: [Statistics 101: Linear Regression, Fit and Coefficient of Determination](https://www.youtube.com/watch?v=kHZBy1uVNnM)

**Post Class**

Week 8 - Monday March 26th 2018 13-17
-------------------------------------

**Location**

-   Ly202-R8107-LIFE 1pm - 5pm

**Background**

We will start with briefly going over what we learned in the last class. Then we will briefly discuss correlation and causation and correction for multiple testing. Then we will turn to reduction of data dimensionality using PCA. I assume most of you have encountered PCA and I would like for you to understand what it is, what it does and how we can use it. Please watch the videos ahead of class.

**Class Curriculum**

-   Recapitulation of previous class
-   Correlation and causation
-   Correction for multiple testing
-   Video: [3 - PCA concept](https://www.youtube.com/watch?v=NFIkD9-MuTY)
-   Video: [4 - PCA estimation, centering/scaling, variance explained and biplot](https://www.youtube.com/watch?v=TraMXdEqeys)
-   Video: [6 - Correlation and PCA](https://www.youtube.com/watch?v=EHb_kuw1GNU)

**Post Class**

-   [Here is the code we went through today](R/day_08.R)
-   [Answer to exercises](R/day_08_exercise.R)
-   [Spurious Correlations](http://www.tylervigen.com/spurious-correlations)

Week 9 - Monday April 9th 2018 13-17
------------------------------------

**Location**

-   Ly202-R8107-LIFE 1pm - 5pm

**Background**

We will start with briefly going over what we learned in the last class. Then we will introduce functions and string detection `stringr` and revisit data manipulation and visualisation, aiming at practising our R syntax skills.

**Class Curriculum**

-   Recapitulation of previous class
-   Working with strings
-   Writing functions in R
-   Data manipulation and visualisation

**Post Class**

-   [Here is the code we went through today](R/day_09.R)
-   [And suggested answer to exercise](R/day_09_exercise.R)

Week 10 - Monday April 23rd 2018 13-17
--------------------------------------

**Location**

-   Ly202-R8107-LIFE 1pm - 5pm

**Background**

As usual, we will recap last session and then we will briefly go over how you can make your own functions in `R`. This is a very powerful way of formalising your analysis and allows you to make workflows easily repeatable. Then we will continue practising our data manipulation skills using Barracoda output as point of reference.

**Class Curriculum**

-   Recapitulation of previous class
-   Writing functions in R
-   Cheat sheets
-   Data manipulation and visualisation

**Post Class**

-   [Here is the link to the cheat sheets we discussed](https://www.rstudio.com/resources/cheatsheets/)
-   [Here is the code we went through today](R/day_10.R)
-   [And suggested answer to exercise](R/day_10_exercise.R)

Week 11 - Monday April 30th 2018 13-17
--------------------------------------

**Location**

-   Ly202-R8107-LIFE (12.00 - 15.00)

**Background**

Note the change in time! I hope you got at feeling for just how powerful `R` is at the last sessions. Based on the 'The Very Basics' book chapter you read, we will resolve any basic issues you may have and then go to working with function in `R`. Then we will turn to data visualisation using `ggplot` and the `mtcars` data set.

**Class Curriculum**

-   Working with functions in `R`
-   Data visualisation
-   Please read [Hands-On Programming with R by Garrett Grolemund - Chapter 1. The Very Basics](https://www.safaribooksonline.com/library/view/hands-on-programming-with/9781449359089/ch01.html) ahead of class

**Post Class**

-   [Here is the code we went through today](R/day_11.R)
-   [Here are the suggested answers to the exercises](R/day_11_exercise.R)
-   [Data Visualisation using `ggplot`](http://r4ds.had.co.nz/data-visualisation.html)

Week 12 - Monday May 7th 2018 13-17
-----------------------------------

**Location**

-   Ly202-R8107-LIFE

**Background**

Last time, you got a feeling for how you can write your own functions and apply them, when working with data sets. We also looked more into how we can use `ggplot` to visualise data ([Much much more here](http://r4ds.had.co.nz/data-visualisation.html)). Then I asked you for input on how we should spend the last two sessions and I noted that you were interested in practising your skills with respect to loading-cleaning-manipulating-visualisation, so basically a data science workflow. I would like to draw your attention to the data-science-cycle taken from [Garrett Grolemund](https://twitter.com/StatGarrett) and [Hadley Wickham](https://twitter.com/hadleywickham)'s [R for Data Science](http://r4ds.had.co.nz/): ![](figures/data_cycle.png) This captures the essense of a data science workflow: Based on the data, you create a communicable extract of information. Today we will look into how we can colloct and join data from multiple sources.

**Class Curriculum**

-   If you still have not read [Hands-On Programming with R by Garrett Grolemund - Chapter 1. The Very Basics](https://www.safaribooksonline.com/library/view/hands-on-programming-with/9781449359089/ch01.html), please do so
-   Data science workflow: Joining multiple excel sheets by shared identifiers

**Post Class**

-   [Here is the import and clean code we worked on today](R/day_12.R)

Week 13 - Monday May 14th 2018 13-17
------------------------------------

**Location**

-   Ly202-R8107-LIFE

**Background**

At our last session, we will as usual recapitulate last session and then continue with merging data from multiple sources. Once complete, we will briefly get an overview of what you should have learned during the course and then we will finish with a Q&A session on the entire course curriculum. Please do remember, that everything covered during this course is available in [R for Data Science by Garrett Grolemund and Hadley Wickham](http://r4ds.had.co.nz/) - This is the goto source for anything [TidyVerse](https://www.tidyverse.org/).

**Class Curriculum**

-   Recap of last session
-   Continue working with merging data from multiple sources
-   Recap of course curriculum
-   Q&A on course curriculum

**Post Class**

Course Curriculum Wrap Up
-------------------------

By now, the following concepts should be familiar to you:

-   Descriptive statistics (mean and standard deviation)
-   Statistical inference (sample versus population)
-   The normal distibution (aka Gaussian distribution)
-   Confidence intervals
-   The standard normal distribution
-   Standard-score normalisation (z-scores)
-   Hypothesis testing (null versus alternative)
-   Student's t-test
-   p-values
-   Level of significance
-   Alpha values
-   Type I error (False positives)
-   Power
-   Beta values
-   Type II error (False negatives)
-   Confusion matrices
-   Ordinary Least Squares (Linear model, linear regression)
-   Correlation
-   Covariance
-   Principal Component Analysis (PCA)
-   Data Import, tidying, transformation, visualisation, modelling and communicating using TidyVerse and ggplot

Important Resources for Data Science in R
-----------------------------------------

### Software Links

-   [The R Project for Statistical Computing](https://www.r-project.org/)
-   [RStudio - Open Source and Enterprise-ready professional software for R](https://www.rstudio.com/)
-   [Tidyverse website](https://www.tidyverse.org/)

### Materials on Data Science

-   [Hands-On Programming with R by Garrett Grolemund - Chapter 1. The Very Basics](https://www.safaribooksonline.com/library/view/hands-on-programming-with/9781449359089/ch01.html)
-   [R for Data Science by Garrett Grolemund and Hadley Wickham](http://r4ds.had.co.nz/)
-   [Youtube playlist with all video lectures](https://www.youtube.com/playlist?list=PL4L59zaizb3FmBdxuDLRdzGsknTrZN6Ys) by [Morten Arendt Rasmussen](http://food.ku.dk/english/staff/?pure=en/persons/311655/)

### Some Useful Links

-   [swirl - Learn R, in R](http://swirlstats.com/)
-   [RStudio Cheat Sheets](https://www.rstudio.com/resources/cheatsheets/)
-   [RStudio Community - Stuck? Ask a question and get help moving on](https://community.rstudio.com/)

### Guides on Good Data Practices

-   [Ten Simple Rules for Effective Statistical Practice](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004961)
-   [A Quick Guide to Organizing Computational Biology Projects](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1000424)
-   [A Guide to Reproducible Code by the British Ecology Society](https://www.britishecologicalsociety.org/wp-content/uploads/2017/12/guide-to-reproducible-code.pdf)

Additional Videos
-----------------

These are the remaining video lectures, that we did not find time to go through. I would however still recommend that you find time to watch them.

-   Video: [12 - Categorical Data - Chisq test - how to](https://www.youtube.com/watch?v=fEXa8dQwlDw)
-   Video: [13 - Binomial distribution](https://www.youtube.com/watch?v=F2NpmXEwFVE)
-   Video: [14 - Binomial Distribution Test](https://www.youtube.com/watch?v=L5jehIE_Sn0)
-   Video: [15 - Binomial distribution - estimation](https://www.youtube.com/watch?v=wZ9c7xG-et4)
-   Video: [16 - Power calculation for the binomial distribution](https://www.youtube.com/watch?v=O_D8csjLr4s)
-   Video: [19 - Oneway ANOVA](https://www.youtube.com/watch?v=1n74nlIqBTE)
-   Video: [20 - Contrasts in ANOVA models](https://www.youtube.com/watch?v=JpUSVNTNTQk)
