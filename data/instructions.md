# Welcome Data Engineering/Science Product Exercise

```
TIMEBOX:    2-3 hours max. We mean it! Set at timer and hard-stop at 3 hours ⏱
LANGUAGES:  Any
FRAMEWORKS: Any
TESTS:      nice to have, but not mandatory
DOCS:       nice to have, but not mandatory
```

## Overview

This exercise is to implement the best possible solution to one of the exercises below in the time alloted. We're evaluating your ability to take a set of requirements and spike a holistic solution that demonstrates the ability to take structured data and generate models that will help drive user behavior. 

This is **NOT** a test of how well you know Python/SQL, nor should you try to impress us with overly clever and obtuse solutions. If you want to impress us, build something that is intuitive and easy to debug/test/extend :smiley: .

Ideally your solution would have some way to run locally and test the results so we can fully analyze your efforts.

## Choose **One** Of the following

---

> :rotating_light: :exclamation: :point_right: **Please use one of the salary datasets provided here for either exercise [/shared/salary_datasets](/shared/salary_datasets)** :point_left: :exclamation: :rotating_light:
## Exercise A: Perform rudimentary analysis on unsanitized Compensation data

The goal of this exercise is analyze a data set containing several CSVs of compensation data submitted by individuals via Google Sheets. This data has not been modified in any way from the original source.

* Ingest and persist the compensation data locally. Use whatever database or persistence engine you are the most familiar with.
* Validate that you can perform the following analyses. You can export the results of these queries via [Jupyter notebook](https://jupyter.org/), a CSV or attach screenshots of the the output
  * Average compensation of roles where the role is some kind of engineer/IT professional
  * Average, min, and max compensation per city/region 
  * One interesting query of your choice (*average compensation by gender perhaps???*)
### A few quick notes on submitting Exercise B

* Ideally this exercise would use SQLite or Postgres, but any SQL database is OK
* Feel free to upload the entire SQL dump (with schema) of the populated database, or create a script that creates the schema and populates the database with one or more of the provided salary data CSVs. Please do whatever makes the most sense given the time alloted.
* If you'd like to use a scripting language like Python or Ruby along with an ORM to make this easier, thats fine with us!

---

## Submitting your exercise

1. See [instructions for submitting your work](https://github.com/pineapplehq/hiring-exercises/blob/master/README.md#general-instructions)
