# Payroll and Team's Success in Major League Baseball (MLB)
## Exploratory Data Analysis (EDA) of MLB Payroll Data
### Authors: Calvin Brauer and Jihan Lee
This project is a part of the coursework for ENGRD/QTM 302W: Technical Writing taught by Dr. Greg Palermo.

[![Binder](http://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jihan-lee01/eda-project/HEAD)

## Project Intro/Objective
Our project aims to investigate the relationship between payroll and team's success by utilizing recent data about individual team's player salaries in Major League Baseball (MLB). Our goal is to test whether there exists a statistically significant relationship between a team's payroll and their respective winning percentage. We would like to leverage this knowledge in order for owners and general managers to be able to better make informed decisions about which contracts to offer to which players. In order to do our testing, we used the Granger Causality Test in the programming language R.

### Methods Used
* Data Visualization
* Augmented Dickey-Fuller Test
* Granger Causality Test
* etc.

### Technologies
* R 
* R Markdown

## Project Description (in Detail)
This project centers around the intriguing research question: Can teams buy success? To explore this, we use total payroll and win percentage as proxies for financial investment and on-field success, respectively. Our analytical approach involves a variety of visualization techniques tailored to different aspects of the data:

* Line Plots: We employ line plots to clearly illustrate trends over time, particularly focusing on how total payrolls have evolved.
* Histograms and Boxplots: To analyze the distribution of numeric variables such as payroll amounts and win rates, we use histograms and boxplots. These visualizations help us understand the spread, central tendencies, and outliers in our data.
* Scatter Plots: To examine bivariate relationships, such as the correlation between payroll expenditure and team performance, scatter plots are utilized. They provide a clear view of how these variables interact with each other.
* Heat Maps: For a more intuitive understanding of complex relationships and patterns in the data, heat maps are used. They are particularly effective in conveying dense information in an accessible manner.

Looking ahead, the potential next steps involve conducting more rigorous research using causal inference techniques. This would allow us to delve deeper into the causal aspect of the relationship between financial investment and team success, moving beyond mere correlation to explore if, and how, teams can effectively 'buy' success.

## Getting Started
To begin exploring our project, you can easily access a binderized version by clicking on the binder badge located at the top of this page. This will allow you to interact with the project in a live environment without the need for local setup.

Our core analysis is meticulously documented and stored in the **analysis** folder. Here, you will find files in `.Rmd` format which contain the main codes and narratives. For your convenience, we have also provided compiled versions of these analyses in the form of HTML files, offering an accessible and comprehensive view of our work.

The essential data that drives our analysis, including 5 years of MLB payroll data and Consumer Price Index (CPI) data, is organized in the **data** folder. This repository of data is key to understanding the trends and patterns we explore in our project.

To ensure a seamless experience when cloning this repository, please refer to the `renv.lock` file. This file lists all the specific versions of the R packages used in this project, enabling you to recreate the exact environment we used and avoid any compatibility issues.

## Contact
* **Calvin Brauer**: calvin.brauer@emory.edu
* **Jihan Lee**: jihan.lee@emory.edu
