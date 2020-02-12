# MACS 30150 - Perspectives on Computational Modeling in Economics (Winter 2020)

|  | [Dr. Richard Evans](https://sites.google.com/site/rickecon/) | Keertana Chidambaram |
|--------------|----------------------------|--------------------------|
| Email | rwevans@uchicago.edu | keertana@uchicago.edu |
| Office | 1155 S 60th St., Room 217 |     |
| Office Hours | T 10:30am-12:30pm | Th 1-3p, (224 Lounge) |
| GitHub | [rickecon](https://github.com/rickecon) | [keertanavc](https://github.com/keertanavc) |

* **Meeting day/time**: MW 11:30am-1:20pm, Saieh Hall, Room 247
* Office hours also available by appointment

## Main text
* James, G., Witten, D., Hastie, T., & Tibshirani, R. (2013). [*An Introduction to Statistical Learning*](http://link.springer.com.proxy.uchicago.edu/book/10.1007%2F978-1-4614-7138-7). New York: Springer.


## Course description

This course is an economics-focused survey of modern computational modeling methods that are valuable to empirical, computational, and numerical research. The course begins with some basics of numerical derivatives and integrals. We then spend two days on dynamic programming, which is a very general and flexible way to pose a dynamic problem and which has powerful iterative global solution techniques. We then transition into a week-and-a-half of structural estimation methods. These methods generalize many of the specific estimation techniques that come after. Finally, we spend the last half of the course with a survey of some of the most common statistical learning/machine learning methods.

## Grades

You will have 9 problem sets throughout the term. I will drop everybody's lowest problem set score. For this reason, problem sets will only account for 80 percent of your grade.

| Assignment       | Quantity | Points | Total Points | Percent |
|------------------|----------|--------|--------------|---------|
| Problem Sets     | 9        | 10     | 80           | 80%     |
| Midterm exam     | 1        | 20     | 20           | 20%     |
| **Total Points** | --       | --     | 100          | 100%    |

Late problem sets will be penalized 2 points for every hour they are late. For example, if an assignment is due on Monday at 11:30am, the following points will be deducted based on the time stamp of the last commit.

| Example PR last commit | points deducted |
| ---------------------- | --------------- |
| 11:31am to 12:30pm     | -2 points       |
| 12:31pm to 1:30pm      | -4 points       |
| 1:31pm to 2:30pm       | -6 points       |
| 2:31pm to 3:30pm       | -8 points       |
| 3:30pm and beyond      | -10 points (no credit) |

## Assignment submission procedure

This folder on your fork of the class repository `github.com/YourGitHubHandle/persp-model-econ_W19/ProblemSets/` is where you will submit your problem sets and project assignments. You will just commit and push your assignments to the appropriate folder ON YOUR FORK (NOT ON THIS MAIN COURSE REPOSITORY). For example, your files for PS1 should be committed to the PS1 folder on your fork of the class repository.

`/persp-model-econ_W19/ProblemSets/PS1/YourFile.pdf`

I will use a shell script to clone all class members' repositories at the time the assignments are due.

## Disability services

If you need any special accommodations, please provide us with a copy of your Accommodation Determination Letter (provided to you by the Student Disability Services office) as soon as possible so that you may discuss with me how your accommodations may be implemented in this course.

## Course schedule

| Date | Day | Topic | Readings | Assignment |
|------------|-------|---------------------------------------------------------|--------------|------------------------------|
| Jan.  6 | M | Model/theory building, data generating processes | [V1997](http://people.ischool.berkeley.edu/~hal/Papers/how.pdf), [Slides](https://github.com/UC-MACSS/persp-model-econ_W20/blob/master/Slides/PerspModel_Intro.pdf) | [PS1](https://github.com/UC-MACSS/persp-model-econ_W20/blob/master/ProblemSets/PS1/PS1.pdf) |
| Jan.  8 | W | Numerical derivatives | [Notes](https://github.com/UC-MACSS/persp-model-econ_w20/blob/master/Notes/ACME_NumDiff.pdf) | [PS2](https://github.com/UC-MACSS/persp-model-econ_W20/blob/master/ProblemSets/PS2/PS2.pdf) |
| Jan. 13 | M | Numerical integration | [Notebk](https://github.com/UC-MACSS/persp-model-econ_w20/blob/master/Notebooks/NumIntegr/NumIntegr.ipynb) |  |
| Jan. 15 | W | Dynamic programming   | [Notes](https://github.com/UC-MACSS/persp-model-econ_W20/blob/master/Notes/DynProg_Evans.pdf) | [PS3](https://github.com/UC-MACSS/persp-model-econ_W20/blob/master/ProblemSets/PS3/PS3.pdf) |
| Jan. 20 | M | **No class (Martin Luther King, Jr. Day)** |  |  |
| Jan. 22 | W | Dynamic programming   | |     |
| Jan. 27 | M | Maximum likelihood estimation (MLE) | [Notebk](https://github.com/UC-MACSS/persp-model-econ_S20/blob/master/Notebooks/MLE/MLest.ipynb) | [PS4](https://github.com/UC-MACSS/persp-model-econ_S20/blob/master/ProblemSets/PS4/PS4.pdf) |
| Jan. 29 | W | Maximum likelihood estimation (MLE) | |  |
| Feb.  3 | M | Generalized method of moments (GMM) | [Notebk](https://github.com/UC-MACSS/persp-model-econ_W20/blob/master/Notebooks/GMM/GMMest.ipynb) | [PS5](https://github.com/UC-MACSS/persp-model-econ_W20/blob/master/ProblemSets/PS5/PS5.pdf) |
| Feb.  5 | W | Generalized method of moments (GMM) |  |  |
| **Feb. 10** | **M** | **Evans Midterm** |  |  |
| Feb. 12 | W | Statistical learning and linear regression | JWHT Ch. 2, 3, [Notebk](https://github.com/UC-MACSS/persp-model-econ_W20/blob/master/Notebooks/LinRegress/LinRegress.ipynb) | [PS6](https://github.com/UC-MACSS/persp-model-econ_W20/blob/master/ProblemSets/PS6/PS6.pdf) |
| Feb. 17 | M | Classification and logistic regression | JWHT Chs. 2, 4, Notebk |  |
| Feb. 19 | W | Resampling methods (cross-validation and bootstrapping) | Notebk | PS7 |
| Feb. 24 | M | Interpolation | Notebk |  |
| Feb. 26 | W | Tree-based methods | JWHT Ch. 8, Notebk | PS8 |
| Mar.  2 | M | Tree-based methods | JWHT Ch. 8 |  |
| Mar.  4 | W | Support vector machines | JWHT Ch. 9, Notebk |  |
| Mar.  9 | M | Neural networks | HTF Ch. 11, G Ch. 10 | PS9 |
| Mar. 11 | W | Neural networks  | Notebk |  |

## References and Readings ##

All readings are required unless otherwise noted. Adjustments can be made throughout the quarter; be sure to check this repository frequently to make sure you know all the assigned readings.

* [A2019] Athey, Susan, ``The Impact of Machine Learning on Econometrics and Economics,'' keynote presentation, American Economics Association/American Finance Association joint luncheon at the Allied Social Sciences 2019 Annual Meeting, Atlanta, Georgia (January 5, 2019). [[Slides](https://github.com/UC-MACSS/persp-model-econ_W19/blob/master/Slides/Athey2019_AEAAFAv2.pptx)]
* [A2018] Athey, Susan, ``[The Impact of Machine Learning on Economics](https://www.nber.org/chapters/c14009.pdf),'' forthcoming in *The Economics of Artificial Intelligence: An Agenda*, eds. Ajay K. Agarwal, Joshua Gans, and Avi Goldfarb, National Bureau of Economic Research (forthcoming).
* [G2017] Géron, Aurélien, *Hands-On Machine Learning with Scikit-Learn & TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems*, O'Reilly (2017).
* [HTF2009] Hastie, Trevor, Robert Tibshirani, and Jerome Friedman, [*The Elements of Statistical Learning: Data Mining, Inference, and Prediction*](https://web.stanford.edu/~hastie/Papers/ESLII.pdf), 2nd Edition, Springer (2009).
* [JWHT2013] James, G., Witten, D., Hastie, T., & Tibshirani, R. (2013). [*An Introduction to Statistical Learning*](http://link.springer.com.proxy.uchicago.edu/book/10.1007%2F978-1-4614-7138-7). New York: Springer.
* [V2016] VanderPlas, Jake. (2016). [*Python Data Science Handbook*](http://proquestcombo.safaribooksonline.com.proxy.uchicago.edu/book/programming/python/9781491912126). O'Reilly Media, Inc.
* [V1997] Varian, Hal R., "[How to Build an Economic Model in Your Spare Time](http://people.ischool.berkeley.edu/~hal/Papers/how.pdf)," in *Passion and Craft: Economists at Work*, eds. Michael Szenberg, University of Michigan Press, 1997.
