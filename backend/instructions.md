# Welcome Backend-focused Product Exercise

```
TIMEBOX:    1-2 hours max. We mean it!
LANGUAGES:  Python or Javascript
FRAMEWORKS: Any Python of Javascript server-side framework (Django, Flask, Node, etc)
TESTS:      nice to have, but not mandatory
DOCS:       nice to have, but not mandatory
```

## Overview

This exercise is to implement the best possible solution to one of the exercises below in the time alloted. We're evaluating your ability to take a set of requirements and spike a holistic solution that demonstrates craftsmanship, thoughtfulness and attention to user experience. This is **NOT** a test of how well you know React or ES7+, nor should you try to impress us with overly clever and obtuse solutions. If you want to impress us, build something that is beautiful, intuitive and easy to debug/test/extend :smiley: .

Ideally your solution would have some way to run locally and visualize the results in a browser so we can fully analyze the experience and not just the source code.

## Choose One Of the following

---

### Exercise A: Expose an API for querying compensation data

:rotating_light: :exclamation: :point_right: **Please use the salary datasets provided here [/shared/salary_datasets](/shared/salary_datasets)** :point_left: :exclamation: :rotating_light:

#### As a developer I want to

* list compensation data via API `GET` request
  * Filter by one or more fields/attributes (e.g. `?salary[gte]=120000&zip_code=11201` )
  * Sort by one or more fields/attributes (e.g. `?sort=last_name`)
  * **Stretch Goal**: return a sparse fieldset (e.g. `?fields=first_name,last_name,salary`)
* fetch a single record via GET request
* have the data be normalized into a uniform schema via a serializer or json template

#### As an employee receiving an offer I want to

* View an offer that was sent to me
  * **stretch goal**: Ask a question about the offer (ideally a subsection of the offer)
* Understand the non-salary compensation I am being offered (stock valuation, value of healthcare benefits)
* See detail about the role, team, and organization

## Exercise B: Visualizing Compensation and Benefits

### As a HR-team member I want to

* "Upload" a CSV/JSON file with my the compensation data of my current organization
  * **NOTE**: You don't need to create an API around file storage/IO. Use any/all of the sample files in [/shared/salary_datasets](/shared/salary_datasets) or create your own simple faked data set.
* View the data in a simple tabular view
  * **stretch goal**: be able to sort or search by any unique identifiers (name, email, etc) so I can find specific rows
* View simple visualization(s) of the distribution of salary compensation so I can get an overview/aggregate of overall compensation
  * **stretch goal**: be able to visualize data across more than one dimension

---

## Submitting your exercise

1. See [instructions for submitting your work](https://github.com/pineapplehq/hiring-exercises/blob/master/README.md#general-instructions)
