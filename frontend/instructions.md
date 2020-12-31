# Welcome Frontend Exercises

```
TIMEBOX:    2-3 hours max. We mean it!
LANGUAGES:  Javascript
FRAMEWORKS: React and any libraries you want
TESTS:      nice to have, but not mandatory
DOCS:       nice to have, but not mandatory
```


# Overview
This exercise is to implement the best possible solution to given criteria in the time alloted. We're evaluating your ability to take a set of requirements and spike a holistic solution that demonstrates craftsmanship and thoughtfulness. Ideally your solution would have some way to run locally and visualize the results in a browser so we can fully analyze the experience and not just the source code.

# Requirements
* Your implementation should be in React or vanilla javascript
* Feel free to use any libraries or frameworks you desire
# Exercises
--------------
## Exercise A: Creating an offer
###  As a hiring manager I want to...
* Create a a new offer of employement
    * Specify the monetary compensation details of an offer (salary, equity, bonus, etc)
    * Specify non-monetary compensation and benefits (culture, learning opportunities, etc)
* See a list of the offers I've created
* Share a link to an offer via a unique URL
### As an employee receiving an offer I want to...
* View an offer that was sent to me
    * **stretch goal**: Ask a question about the offer (ideally a subsection of the offer)
* Understand the non-salary compensation I am being offered (stock valuation, value of healthcare benefits)
* See detail about the role, team, and organization
## Exercise B: Visualizing Compensation and Benefits

###  As a HR-team member I want to....
* "Upload" a CSV/JSON file with my the compensation data of my current organization
    * **NOTE**: You don't need to create an API around file storage/IO. Use any/all of the sample files in [/shared/salary_datasets](/shared/salary_datasets) or create your own simple faked data set.
* View the data in a simple tabular view
    * **stretch goal**: be able to sort or search by any unique identifiers (name, email, etc) so I can find specific rows
* View simple visualization(s) of the distribution of salary compensation so I can get an overview/aggregate of overall compensation
    * **stretch goal**: be able to visualize data across more than one dimension
