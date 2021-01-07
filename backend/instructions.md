# Welcome Backend-focused Product Exercise

```
TIMEBOX:    2-3 hours max. We mean it! Set at timer and hard-stop at 3 hours ⏱
LANGUAGES:  Python, Javascript, SQL
FRAMEWORKS: Django, Flask, NodeJS, etc (Exercise B can be pure SQL)
TESTS:      nice to have, but not mandatory
DOCS:       nice to have, but not mandatory
```

## Overview

This exercise is to implement the best possible solution to one of the exercises below in the time alloted. We're evaluating your ability to take a set of requirements and spike a holistic solution that demonstrates craftsmanship, thoughtfulness and good architectural design. This is **NOT** a test of how well you know Python/Django/Flask/SQL, nor should you try to impress us with overly clever and obtuse solutions. If you want to impress us, build something that is beautiful, intuitive and easy to debug/test/extend :smiley: .

Ideally your solution would have some way to run locally and test the results so we can fully analyze your efforts.

## Choose **One** Of the following

---

> :rotating_light: :exclamation: :point_right: **Please use one of the salary datasets provided here for either exercise [/shared/salary_datasets](/shared/salary_datasets)** :point_left: :exclamation: :rotating_light:

### Exercise A: Expose an API for querying compensation data

The goal of this exercise is to design a read-only API (REST or GraphAPI) that returns one or more records from static set of compensation data.

#### User Story: As a developer I want to

* list compensation data via API `GET` request
  * Filter by one or more fields/attributes (e.g. `/compensation_data?salary[gte]=120000&zip_code=11201` )
  * Sort by one or more fields/attributes (e.g. `/compensation_data?sort=last_name`)
* fetch a single record via GET request
  * **Stretch Goal**: return a sparse fieldset (e.g. `/compensation_data?fields=first_name,last_name,salary`)
* have the JSON response be normalized into a uniform schema via a serializer or json template
  * **Stretch Goal**: serialize more than one compensation [data set](/shared/salary_datasets)

### A few quick notes on submitting Exercise A

* Don't worry about any web application concerns other than serializing JSON and returning via a GET request.
* The example above (`/compensation_data`...) is not a contract. Feel free to design the URL structure and JSON schema that you believe creates the best client/consumer experience

---

## Exercise B: Database Design Exercise - Storing Compensation Data

The goal of this exercise is to design a highly normalized database schema for storing compensation data

* Create a schema for storing the compensation data provided in one of the [available data sets](/shared/salary_datasets). This schema should be in at least [3NF](https://en.wikipedia.org/wiki/Third_normal_form) with tables for **employee**, **role**, and anything else that makes sense for the data given.
* Upload at least one dataset to the schema
  * **Stretch Goal**: upload all 3 salary datasets to the database schema
* Validate that you can perform the following queries. You can export the results of these queries via CSV or attach screenshots of the the output
  * Average compensation of roles where the role is some kind of engineer (hint: `ILIKE`)
  * Average, min, and max compensation per city (if available in dataset)
  * One interesting query of your choice (*average compensation by gender perhaps???*)
* Create a quick database schema diagram
  * Many admin tools and clients will allow you to generate these from your schema. If not possible, just draw a super-simple diagram in MS Paint or similar tool 🎨

### A few quick notes on submitting Exercise B

* Ideally this exercise would use SQLite or Postgres, but any SQL database is OK
* Feel free to upload the entire SQL dump (with schema) of the populated database, or create a script that creates the schema and populates the database with one or more of the provided salary data CSVs. Please do whatever makes the most sense given the time alloted.
* If you'd like to use a scripting language like Python or Ruby along with an ORM to make this easier, thats fine with us!

---

## Submitting your exercise

1. See [instructions for submitting your work](https://github.com/pineapplehq/hiring-exercises/blob/master/README.md#general-instructions)
