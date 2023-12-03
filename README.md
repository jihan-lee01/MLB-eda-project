# The Effects of Payroll on MLB Team's Success
Authors: Jihan Lee and Calvin Brauer

ENGRD 302W: Technical Writing, Dr. Greg Palermo

---

<strong>Overview</strong>

Our project aims to utilize recent data about individual team's player's salaries in Major League Baseball (MLB). 
Our goal is to test whether there exists a statistically significant causal relationship between a team's payroll and their respective winning percentage. 
We'd like to leverage this knowledge in order for owners and general managers to be able to better make informed decisions about which contracts to offer to which players.
In order to do our testing, we used the Granger Causality Test in the programming language R.

<strong>Using this repository</strong>

Our main analytics lie in the "analysis" folder in a file titled `eda-project.Rmd`. A nicer, compiled version of our project is also included in the form of an HTML webpage of the same title. 
Both our original data and our inflation-adjusted data can be found in the "data" folder. 
When cloning this repository, use the `renv.lock` file to ensure that your system has all of the necessary versions of the libraries that were used in this project.
