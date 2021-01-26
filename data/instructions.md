# Welcome Data Engineering/Science Product Exercise

```
TIMEBOX:    2-4 hours max. We mean it! Set at timer and hard-stop at 4 hours ⏱
LANGUAGES:  Python, SQL
FRAMEWORKS: Jupyter
```

## Overview

This exercise is to evaluate real-world compensation data. This is **NOT** a test of how well you know [Jupyter](https://jupyter.org/)/Python/SQL, nor should you try to impress us with overly clever and obtuse analysis. If you want to impress us use the time alloted to extract the maximum value from the data possible.

Submissions should be in the form of a [Jupyter notebook](https://jupyter.org/), however you are free to write custom SQL queries or functions if that better fits your work style. Ideally your solution would have some way to run locally and test the results so we can fully analyze your efforts.

### Inspiration
* [Github: jrenner/hacker-news-salaries-data](https://cdn.rawgit.com/jrenner/hacker-news-salaries-data/master/explore_salaries.html)
* [Github: minimaxir/sfba-compensation](https://github.com/minimaxir/sfba-compensation/blob/master/angelist_sfbayarea_jobs.ipynb)
* [Anaconda: gwinnen/sf-salaries-exercise](https://anaconda.org/gwinnen/sf-salaries-exercise/notebook)
* [Kaggle: drgilermo/salary-analysis](https://www.kaggle.com/drgilermo/salary-analysis)


## Exercise

---
The goal of this exercise is analyze a data set containing several CSVs of compensation data submitted by individuals via Google Sheets. This data has not been modified in any way from the original source.

* Clean and format all [3 compensation data CSVs](/shared/salary_datasets) to use a common set of fields/attributes/columns containing at least the following...
  * Role/Title
  * Location
  * Salary (base compensation) in $US dollars with cents
  * Years experience
  * Bonus
* Validate that you can perform the following analyses and export the results via [Jupyter notebook](https://jupyter.org/), a CSV or attach screenshots of the the output
  * **Compensation by Role**
    * Find the average compensation of roles where the role is some kind of technical professional
    * Visualize the relationship between compensation and role
  * **Compensation by Geographic Region**
    * Average, min, and max compensation per city/region
    * Visualize the relationship between city and salary/base compensation
  * **Compensation by Experience**
    * Visualize the relationship between cash compensation and other forms of compensation
    * Visualize the relationship between years of experience and total compensation (cash and bonus/equity)
  * Visualize One interesting query/facet of your choice (*average compensation by gender perhaps???*)

---

## Submitting your exercise

1. See [instructions for submitting your work](https://github.com/pineapplehq/hiring-exercises/blob/master/README.md#general-instructions)
