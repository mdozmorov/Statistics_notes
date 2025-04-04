# Statistics tutorials and learning resources

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com)

Statistics learning and data analysis resources. Please, [contribute and get in touch](CONTRIBUTING.md)! See [MDmisc notes](https://github.com/mdozmorov/MDmisc_notes) for other programming and genomics-related notes.

# Table of content

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Cheatsheets](#cheatsheets)
- [Survival](#survival)
- [Bayesian](#bayesian)
- [Mixed models](#mixed-models)
- [Repositories](#repositories)
- [Courses](#courses)
- [Videos](#videos)
- [Books](#books)
- [Linear algebra](#linear-algebra)
- [Misc](#misc)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Cheatsheets

- [probability_cheatsheet](http://www.wzchen.com/probability-cheatsheet) - A comprehensive 10-page PDF probability cheatsheet that covers a semester's worth of introduction to probability, by William Chen (http://wzchen.com) and Joe Blitzstein (http://stat110.net).

- [Common statistical tests are linear models (or: how to teach stats)](https://lindeloev.github.io/tests-as-linear/)

- [Resources for learning about the history of statistics and statisticians. By statisticians, for statisticians](https://github.com/sctyner/history_of_statistics) - references to blog posts, books, journal articles, podcasts, interviews, news, and other material about the history of statistics

- [Distribution explorer](https://distribution-explorer.github.io/index.html) - Overview and examples of various distributions (univariate/multivariate, categorical/continuous), their parameters, interdependencies. Code in numpy, scipy, Stan.

## Survival

- A collection of four-part articles covering basic concepts (survival and hazard, Kaplan-Meyer estimate, log-rank and nonparametric tests for survival differences), multivariate approaches (Cox proportional hazards model, parametric PH models, accelerated failure time models, stratified survival analysis), sample size considerations (with covariates), model selection, quality (Martingale residual plots), advanced topics (missing data). Mentions [nQuery](https://www.statsols.com/) software for clinical trials power analysis. 
<details>
    <summary>Paper 1</summary>
    Clark, T G, M J Bradburn, S B Love, and D G Altman. “Survival Analysis Part I: Basic Concepts and First Analyses.” British Journal of Cancer 89, no. 2 (July 2003): 232–38. https://doi.org/10.1038/sj.bjc.6601118.
</details>
<details>
    <summary>Paper 2</summary>
    Bradburn, M J, T G Clark, S B Love, and D G Altman. “Survival Analysis Part II: Multivariate Data Analysis – an Introduction to Concepts and Methods.” British Journal of Cancer 89, no. 3 (August 2003): 431–36. https://doi.org/10.1038/sj.bjc.6601119.
</details>
<details>
    <summary>Paper 3</summary>
    Bradburn, M J, T G Clark, S B Love, and D G Altman. “Survival Analysis Part III: Multivariate Data Analysis – Choosing a Model and Assessing Its Adequacy and Fit.” British Journal of Cancer 89, no. 4 (August 2003): 605–11. https://doi.org/10.1038/sj.bjc.6601120.
</details>
<details>
    <summary>Paper 4</summary>
    Clark, T G, M J Bradburn, S B Love, and D G Altman. “Survival Analysis Part IV: Further Concepts and Methods in Survival Analysis.” British Journal of Cancer 89, no. 5 (September 2003): 781–86. https://doi.org/10.1038/sj.bjc.6601117.
</details>


## Bayesian

- Bayesian statistics and modeling primer. Methods and applications overview, terminology description. Prior distributions, elicitation, uncertainty. Model fitting using MCMC, other methods (Table 1). Applications in behavioural sciences, ecology, genetics. Reproducibility considerations. Table 2 - Bayesian inference software, various OSs and languages. Box 1 - Bayes theorem explanation. Box 2 - Bayes factors. Box 3 - likelihood function. Box 5 - WAMBS (when to Worry and how to Avoid the Misuse of Bayesian Statistics) checklist. Many references. <details>
    <summary>Paper</summary>
    Schoot, Rens van de, Sarah Depaoli, Ruth King, Bianca Kramer, Kaspar Märtens, Mahlet G Tadesse, Marina Vannucci, et al. “Bayesian Statistics and Modelling,” 2021, 26. https://doi.org/10.1038/ s43586-020-00001-2
</details>

- [stat_rethinking_2022](https://github.com/rmcelreath/stat_rethinking_2022) - Statistical Rethinking book and course, by Richard McElreath, 2022 edition. Slides, videos. Original [rethinking](https://github.com/rmcelreath/rethinking) GitHub repo. [Andrew Gelman's note about the book](https://andrewgelman.com/2016/01/15/mcelreaths-statistial-rethinking-a-bayesian-course-with-examples-in-r-and-stan/), [Video lectures](https://www.youtube.com/watch?v=kSgqH_eD1-0&list=PLDcUM9US4XdM9_N6XUUFrhghGJ4K25bFc).
    - `Statistical-Rethinking` - An interactive online reading of McElreath's "Statistical Rethinking: A Bayesian Course with Examples in R and Stan" by Levi Waldron. https://github.com/lwaldron/Statistical-Rethinking

- [A Brief Introduction to Graphical Models and Bayesian Networks](http://www.cs.ubc.ca/~murphyk/Bayes/bnintro.html), by Kevin Murphy, 1998.

- [A Student's Guide to Bayesian Statistics](https://www.youtube.com/playlist?list=PLwJRxp3blEvZ8AKMXOy0fc0cqT61GsKCG), by Ben Lambert . More Bayesian Class [Videos](https://discourse.mc-stan.org/t/bayesian-class-videos/3173)

- [A Bayesian Course with Examples in R and Stan](http://xcelab.net/rm/statistical-rethinking/) book sample. Link to the full [video lectures](https://www.youtube.com/playlist?list=PLDcUM9US4XdMdZOhJWJJD4mDBMnbTWw_z)

- [Bayesian Methods for Hackers](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers) - An introduction to Bayesian methods + probabilistic programming with a computation/understanding-first, mathematics-second point of view

- [Bayesian Data Analysis demos for Python](https://github.com/avehtari/BDA_py_demos)

- [Bayesian-Modelling-in-Python](https://github.com/markdregan/Bayesian-Modelling-in-Python) - A Python tutorial on bayesian modeling techniques (PyMC3)

- [Bayes Rules! An Introduction to Bayesian Modeling with R](https://www.bayesrulesbook.com) by Alicia A. Johnson, Miles Ott, Mine Dogucu. [Tweet](https://twitter.com/Miles_Ott/status/1407101386437926913?s=20)

- [Bayesian Computing Course](https://github.com/fonnesbeck/Bayes_Computing_Course) - Python notebooks with applied examples and explanations

- [Probabilistic-Programming-and-Bayesian-Methods-for-Hackers](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers) - An introduction to Bayesian methods + probabilistic programming with a computation/understanding-first, mathematics-second point of view. All in pure Python. 

- [Bayesian Data Analysis at Aalto (CS-E5710)](https://github.com/avehtari/BDA_course_Aalto) course material, slides, video lectures, code demos, assignments 

- [awesome-bayes](https://github.com/dimenwarper/awesome-bayespwdd) - List of resources for bayesian inference.

- [bayesian-basics/](https://m-clark.github.io/bayesian-basics/) - Bayesian data analysis introduction by Michael Clarl. [GitHub](https://github.com/m-clark/bayesian-basics)

- [book](https://github.com/StatsWithR/book) - a written companion for the Course 'Bayesian Statistics' from the Statistics with R specialization available on Coursera.

- [understanding-bayes/](http://alexanderetz.com/understanding-bayes/) - "Understanding Bayes" series of blog posts by Alex Etz. The other posts are also worth reading.

## Mixed models

- [Mixed Models with R](https://m-clark.github.io/mixed-models-with-R/), Getting started with random effects, by [Michael Clark](http://m-clark.github.io). [GitHub](https://github.com/m-clark/mixed-models-with-R), [Tweet](https://twitter.com/statsdatasci/status/1483089238925185025?s=20).

- [How Linear Mixed Model Works](https://towardsdatascience.com/how-linear-mixed-model-works-350950a82911) by Nikolay Oskolkov

- [Introduction to linear mixed models](https://ourcodingclub.github.io/tutorials/mixed-models/) - mixed and random effects, R syntax. [GitHub](https://github.com/ourcodingclub/CC-Linear-mixed-models)

- `CC-Linear-mixed-models` - Introduction to linear mixed models, https://ourcodingclub.github.io/tutorials/mixed-models/, https://github.com/ourcodingclub/CC-Linear-mixed-models


- [julianfaraway/rexamples](https://github.com/julianfaraway/rexamples) - mixed effect model examples from two chapters of Julian Faraway's book [Extending the Linear Model with R](https://julianfaraway.github.io/faraway/ELM/). Each model is fit using several different methods: lme4, INLA, STAN, BRMS, MGCV. Another useful book: [Bayesian Regression Modeling with INLA](https://julianfaraway.github.io/brinlabook/index.html)


## Repositories

- `brr` - "Biostatistics for Biomedical Research" by Frank Harrell, the creator of `Hmisc` package and many more. [https://github.com/harrelfe/bbr](https://github.com/harrelfe/bbr). Video lectures, https://www.youtube.com/channel/UC-o_ZZ0tuFUYn8e8rf-QURA

- `BIOS2` - Biostatistics 621 / 821 course by Levi Waldron. Classical statistics, from all aspects of regression, survival analysis to dimensionality reduction basics. iPython and R. [https://github.com/waldronlab/BIOS2](https://github.com/waldronlab/BIOS2)

- `book_sample` - Another Book on Data Science. Learn R and Python in Parallel. Web, https://www.anotherbookondatascience.com/, GitHub, https://github.com/rnorm/book_sample

- `bysh_book` - Repo for Feb 2018 version of Broadening Your Statistical Horizons [https://github.com/broadenyourstatisticalhorizons/bysh_book](https://github.com/broadenyourstatisticalhorizons/bysh_book). The rendered version can be found at: [https://bookdown.org/roback/bookdown-bysh/](https://bookdown.org/roback/bookdown-bysh/)

- `CHE379` - Statistical refresher course by Chris A. Mack, From Data to Decisions: Measurement, Uncertainty, Analysis, and Modeling. Videos, esercises, slides in PDF. [http://www.lithoguru.com/scientist/statistics/course.html](http://www.lithoguru.com/scientist/statistics/course.html). Video playlist [https://www.youtube.com/playlist?list=PLM2eE_hI4gSDnF-mEa9mrIYx7GCLQVN89](https://www.youtube.com/playlist?list=PLM2eE_hI4gSDnF-mEa9mrIYx7GCLQVN89)

- `DATA606Spring2017` - the DATA 606 course for the Spring 2017 semester by Jason Bryer. The course website is at data606.net. [https://github.com/jbryer/DATA606Spring2017](https://github.com/jbryer/DATA606Spring2017)

-`FES` - Feature Engineering and Selection: A Practical Approach for Predictive Models, by Max Kuhn and Kjell Johnson. [http://www.feat.engineering/](http://www.feat.engineering/), [https://github.com/topepo/FES(https://github.com/topepo/FES)]

- `fiveMinuteStats` - A repo of short "vignettes" illustrating statistical concepts, https://stephens999.github.io/fiveMinuteStats/. https://github.com/stephens999/fiveMinuteStats.git

- `Intro2R` - data mining and machine learning, https://github.com/johnros/Intro2R

- `ISAT 251 Intro to Statistics with R` - basic statistics by Nicole Radziwill

- `ISLR` - An Introduction to Statistical Learning with Applications in R (ISLR). The book, R code  and the data are available at [http://www-bcf.usc.edu/~gareth/ISL/](http://www-bcf.usc.edu/~gareth/ISL/). Videos and slides are at [https://www.r-bloggers.com/in-depth-introduction-to-machine-learning-in-15-hours-of-expert-videos/](https://www.r-bloggers.com/in-depth-introduction-to-machine-learning-in-15-hours-of-expert-videos/). Slides are also available at [https://www.alsharif.info/iom530](https://www.alsharif.info/iom530)

- `Kalman-and-Bayesian-Filters-in-Python` - Kalman Filter book using Jupyter Notebook. Focuses on building intuition and experience, not formal proofs. Includes Kalman filters,extended Kalman filters, unscented Kalman filters, particle filters, and more. All exercises include solutions. https://github.com/rlabbe/Kalman-and-Bayesian-Filters-in-Python

- `OpenIntro-Statistics` - An open-source textbook written at the college level. OpenIntro also offers a second college-level intro stat textbook and also a high school variant. https://www.openintro.org, https://github.com/OpenIntroOrg/openintro-statistics. Videos, https://www.youtube.com/user/bleue894/playlists, slides, https://github.com/OpenIntroStat/openintro-statistics-slides

- `practicing_R` - R and statistics, https://github.com/johnros/practicing_R

- `PractitionerGuidetoMultiplicity` - Practical Guide for Multiple testing, https://github.com/johnros/PractitionerGuidetoMultiplicity

- `stat540_2014` - STAT540 Statistical Methods for High Dimensional Biology course by Jenny Bryan

- `stat401A` - conscise statistical refresher by Jarad Niemi, STAT 401A course at Iowa State University. [https://github.com/jarad/stat401A](https://github.com/jarad/stat401A). Jarad's web-site with more statistical courses STAT 544 and STAT 615 [http://www.jarad.me/courses/](http://www.jarad.me/courses/)

- `statcomp` - Statistical Computing, BIOS 735 - Introduction to Statistical Computing. http://biodatascience.github.io/statcomp, https://github.com/biodatascience/statcomp, https://github.com/biodatascience/statcomp_src

- `thinkstats` - Statistical Thinking for the 21st Century. Book, http://statsthinking21.org/, and GitHub, https://github.com/psych10/thinkstats

- `WinVector.github.io` - Various statistical topics with R and Python examples. "IntroductionToDataScience" course. https://winvector.github.io/ - web-facing pages, https://github.com/WinVector/WinVector.github.io/ - github repo

- `www_stat_cmu_edu_cshalizi_350` - Statistics 36-350: Data Mining by Cosma Shalizi. http://www.stat.cmu.edu/~cshalizi/350/

## Courses

- [fastStat](https://github.com/matloff/fastStat) - Quick introduction to statistics for those with a probability background, by Norm Matloff. Also, [fastBigStat](https://github.com/matloff/fastBigStat)

- [intro-gam-webinar-2020](https://github.com/gavinsimpson/intro-gam-webinar-2020) - Introduction to Generalized Additive Models with R and mgcv, by Gavin Simpson. Video, slides, code

- [Introduction to Causal Inference](https://www.bradyneal.com/causal-inference-course) Fall 2020 course by Brady Neal. Video, lecture material. [Twitter](https://twitter.com/CasualBrady/status/1297626885481017345?s=20)

- [BIOS 735 - Introduction to Statistical Computing](https://biodatascience.github.io/statcomp/) - Statistical concepts in R, by Naim Rashid. [GitHub](https://github.com/biodatascience/statcomp_src)

- CS229T/STATS231: Statistical Learning Theory, Stanford / Autumn 2018-2019. "Texts and References" section has a good set of course notes and links.  [https://web.stanford.edu/class/cs229t/](https://web.stanford.edu/class/cs229t/)

- The Coursera Class: Statistics One, by Princeton [https://github.com/svkerr/Statistics_Class_Princeton](https://github.com/svkerr/Statistics_Class_Princeton)

- Introduction to Statistics for Biologists, by [Peter Ralph](http://ralphlab.usc.edu/). [https://github.com/petrelharp/bisc305](https://github.com/petrelharp/bisc305)

- Introduction to Probability and Statistics, [stat20.org](https://www.stat20.org/). [GitHub](https://www.stat20.org/)

- Data wrangling, exploration, and analysis with R, UBC STAT 545A and 547M courses. [https://stat545-ubc.github.io/](https://stat545-ubc.github.io/) and the Git repository [https://github.com/STAT545-UBC/STAT545-UBC.github.io](https://github.com/STAT545-UBC/STAT545-UBC.github.io)

- Harvard CS 109: Data Science course with video lectures, pdf slides and iPython notebooks. [Course overview](https://cs109.github.io/2015/), [Videos](https://cs109.github.io/2015/pages/videos.html), [Git repository](https://github.com/cs109/2015), [All course-related material on Github](https://github.com/cs109)

- Advanced data analysis techniques, CVEN 6833, Dr. R. Balaji. Lots of material and links on regression and modeling techniques. [http://civil.colorado.edu/~balajir/CVEN6833/](http://civil.colorado.edu/~balajir/CVEN6833/)

- [Econometrics Academy](https://sites.google.com/site/econometricsacademy/econometrics-models) - main statistical methods, examples in R and SAS, short video tutorials

## Videos

- MIT 18.065 Matrix Methods in Data Analysis, Signal Processing, and Machine Learning, Spring 2018, by Gilbert Strang, https://www.youtube.com/playlist?list=PLUl4u3cNGP63oMNUHXqIUcrkS2PivhN3k

- Statistical inference for data science, Brian Caffo. Full book on [http://rpubs.com/cbchisanga/143127](http://rpubs.com/cbchisanga/143127), videos on [https://www.youtube.com/watch?v=WkOinijQmPU&list=PLpl-gQkQivXiBmGyzLrUjzsblmQsLtkzJ](https://www.youtube.com/watch?v=WkOinijQmPU&list=PLpl-gQkQivXiBmGyzLrUjzsblmQsLtkzJ), GitHub version on [https://github.com/bcaffo/LittleInferenceBook](https://github.com/bcaffo/LittleInferenceBook)

- Statistics 110: Probability, by Joe Blitzstein, https://www.youtube.com/playlist?list=PL2SOU6wwxB0uwwH80KTQ6ht66KWxbzTIo. The book "Introduction to Probability" https://twitter.com/stat110/status/1101502622358556674

## Books

- [Improving Your Statistical Inferences](https://github.com/Lakens/statistical_inferences)  by Daniël Lakens. [Website](https://lakens.github.io/statistical_inferences/index.html)

- [The Effect: An Introduction to Research Design and Causality](https://theeffectbook.net/index.html) - book by Nick Huntington-Klein intended to introduce the concepts of research design and causality in the context of observational data. [GitHub](https://github.com/NickCH-K/causalbook), accompanying [Videos](https://nickchk.com/videos.html).

- [Gaussian Processes for Machine Learning](http://www.gaussianprocess.org/gpml/) - book by Carl Edward Rasmussen and Christopher K. I. Williams. 

- [An Introduction to Statistical Learning](https://www.statlearning.com) - classic stats learning book by Gareth James, Daniela Witten, Trevor Hastie, Rob Tibshirani

- [practical-statistics-for-data-scientists](https://github.com/gedeck/practical-statistics-for-data-scientists) - Practical Statistics for Data Scientists, 50+ Essential Concepts Using R and Python, by Peter Bruce, Andrew Bruce, and Peter Gedeck. Code repository for O'Reilly book

- [Probabilistic Machine Learning](https://github.com/probml/pml-book) - a book series by Kevin Murphy. GitHub repo with links to buy and PDF download

- [Forecasting: Principles and Practice](https://otexts.com/fpp2/) by Rob J Hyndman and George Athanasopoulos, Monash University, Australia. R-based examples. [Tweet](https://twitter.com/seandavis12/status/1267865789396406272?s=20)

- "Advanced Statistical Computing" by Roger D. Peng. https://bookdown.org/rdpeng/advstatcomp/

- "Modern Statistics for Modern Biology" book by Susan Holmes and Wolfgang Huber. Data and code provided. https://www.huber.embl.de/msmb/index.html

- "Causal Inference Book" by Miguel Hernan and  Jamie Robins. [https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/)

- Notes and exercises for a classical free book "[An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/)" [https://github.com/asadoughi/stat-learning](https://github.com/asadoughi/stat-learning)

- "From Algorithms to Z-Scores: Probabilistic and Statistical Modeling in Computer Science" book, [http://heather.cs.ucdavis.edu/probstatbook](http://heather.cs.ucdavis.edu/probstatbook) by prof. Norm Matloff

- "Introduction to probability" introductory book, published by the American Mathematical Society. [Web-page](https://www.dartmouth.edu/~chance/teaching_aids/books_articles/probability_book/book.html) and references therein, [PDF](https://www.dartmouth.edu/~chance/teaching_aids/books_articles/probability_book/amsbook.mac.pdf).

- "Modeling and Solving Linear Programming with R" open book introducting linear modeling, in R. [Book, PDF](http://www.omniascience.com/scholar/index.php/scholar/issue/view/19)m [Git with corresponding code](https://github.com/jmsallan/linearprogramming)

- "An introduction to psychometric theory with applications in R" by William Revelle, the creator of `psych` R package. The book with downloadable PDFs: [http://personality-project.org/r/book/](http://personality-project.org/r/book/), the course based on the book: [http://personality-project.org/revelle/syllabi/405.syllabus.html](http://personality-project.org/revelle/syllabi/405.syllabus.html), and the `psych` R package: [https://cran.r-project.org/web/packages/psych/index.html](https://cran.r-project.org/web/packages/psych/index.html)

- "Data Science Live Book" by Pablo Casas, from exploratory data analysis to regression/classification. https://livebook.datascienceheroes.com/

- [Advanced Data Analysis from an Elementary Point of View](http://www.stat.cmu.edu/~cshalizi/ADAfaEPoV/ADAfaEPoV.pdf) book by Cosma Rohilla Shalizi, PDF, 828 pages. Statistics, with R examples

- [Applied Statistics with R](https://book.stat420.org/) by David Dalpiaz. [GitHub](https://github.com/daviddalpiaz/appliedstats)

- [the_statistics_handbook](https://github.com/carloocchiena/the_statistics_handbook) - the statistics handbook open source repository.

## Linear algebra

- [The-Art-of-Linear-Algebra](https://github.com/kenjihiranabe/The-Art-of-Linear-Algebra) - Graphic notes on Gilbert Strang's "Linear Algebra for Everyone"

- [Calculus resources](https://brohrer.github.io/calculus_resources.html), [Python resources](https://brohrer.github.io/python_resources.html), [Linear algebra resources](https://brohrer.github.io/linear_algebra_resources.html) by Brandon Rorher. [Source](https://twitter.com/_brohrer_/status/1163423524079452163?s=03)

- "Introduction to Applied Linear Algebra" by Stephen Boyd & Lieven Vandenberghe, http://vmls-book.stanford.edu/, [vmls.pdf](http://vmls-book.stanford.edu/vmls.pdf). Includes [examples in Julia](http://vmls-book.stanford.edu/vmls-julia-companion.pdf)

- [numerical-linear-algebra](http://www.fast.ai/2017/07/17/num-lin-alg/) - Computational Linear Algebra for Coders by FastAI. [Video series](https://www.youtube.com/playlist?list=PLtmWHNX-gukIc92m1K0P6bIOnZb-mg0hY), [GitHub](https://github.com/fastai/numerical-linear-algebra)

## Misc

- [applied_statistics_2024](https://github.com/pileyan/applied_statistics_2024) - Курс по прикладной статистике ВШЭ (2024). 

- [MANOVA(Multivariate Analysis of Variance) using R](https://www.statisticalaid.com/manova-using-r/) by [Statistical Aid](https://www.statisticalaid.com/)

- A Beginner’s Guide to Eigenvectors, PCA, Covariance and Entropy. [http://deeplearning4j.org/eigenvector](http://deeplearning4j.org/eigenvector)

- `Goeman.pdf` - STATISTICAL METHODS FOR MICROARRAY DATA
- `MPR04.pdf` - Introduction to Statistical Methods for Microarray Data Analysis

- How to Do Mediation Scientifically. https://blog.methodsconsultants.com/posts/how-to-do-mediation-scientifically/



