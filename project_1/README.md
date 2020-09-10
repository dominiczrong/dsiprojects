# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Testing, Statistical Summaries and Inference



### Problem Statement

What are the actions and strategies that can be taken to increase SAT participation rates among high school students in US States?

---

### Executive Summary

The ACT has been outpacing the SAT in participation rates in recent years, steadily gaining ground across the country. The College Board implemented some major design changes to the SAT in 2016, in an attempt to revitalize their test. 

In this project, we take a look at SAT and ACT participation and scoring data by state in 2017 and 2018, to see if we can glean any strategies the College Board might employ to increase SAT participation rates moving forward.

Based on 2017 and 2018 SAT data, there is a great disparity in SAT participation rates across states.

College Board wants to improve SAT participation rates across US States.

This project aims to investigate why certain states have low SAT participations rates and investigate whether there are any underlying trends or factors affecting a State’s SAT Participation Rate.

This project will employ exploratory and statistical data analysis to uncover trends and insights to tackle this problem of low SAT participation rates among certain US States.

Visualizations Plotted:

- Correlation Heatmap
- Tableau Geographical Visualizations
- Histograms
- Scatter Plots
- Box-plots


### Contents:
- [2017 Data Import & Cleaning](#Data-Import-and-Cleaning)
- [2018 Data Import and Cleaning](#2018-Data-Import-and-Cleaning)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Data Visualization](#Visualize-the-data)
- [Descriptive and Inferential Statistics](#Descriptive-and-Inferential-Statistics)
- [Outside Research](#Outside-Research)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)

---

### Conclusions and Recommendations

After analyzing the datasets and synthesizing my findings, the 3 key reasons why SAT Participation Rates are low in certain US States are as such:

1. Many US States with low SAT Participation Rates have very high ACT Participation Rates as certain States prefer their students to take 1 particular test (ACT) over the SAT test.

2. Administering tests can be costly for poorer States and in public schools as well. Increasing access to free tests could be the key in swaying certain US States to adopt one test over the other.

3. Making tests mandatory and enforcing higher school accountability could also significantly increase test participation rates.

#### Recommendation 1 - Improve Attractiveness

**Promoting SAT Test to US States that predominantly administer ACT Tests for its students.**

- Demonstrate the advantages of SAT testing
- Make the SATs more attractive to student and States


#### Recommendation 2 - Improve Accessibility

**Increasing access for US States to SAT School Day Programs**

- Cost-saving incentives for poorer states and public schools
- Improve access to free preparation material for students

#### Recommendation 3 - Improve Reforms

**Promote mandatory SAT Testing for US States over ACT Testing**

- Enforce statewide high school accountability across US States.

---


### Datasets

#### Provided Data

For this project, you'll have two provided datasets:

- [2017 SAT Scores](./data/sat_2017.csv)
- [2017 ACT Scores](./data/act_2017.csv)

These data give average SAT and ACT scores by state, as well as participation rates, for the graduating class of 2017.

You can see the source for the SAT data [here](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/), and the source for the ACT data [here](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows). **Make sure you cross-reference your data with your data sources to eliminate any data collection or data entry issues.**

#### Additional Data

2018 state-by-state average results and participation for the SAT are available in PDF reports [here](https://reports.collegeboard.org/sat-suite-program-results/state-results). 2018 ACT state-by-state mean composite scores and participation rates are [here](http://www.act.org/content/dam/act/unsecured/documents/cccr2018/Average-Scores-by-State.pdf) .

**This data has been compiled into CSV files which are also included in the *data* directory of this repo**

Final combined dataset:

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|ACT/SAT|List of 51 US States| 
|sat_2018_participation|float64|SAT|Student Participation Rate per State in taking SAT tests in 2018|
|sat_2018_erw|int64|SAT|Average SAT Evidence-based Reading and Writing Score per State in 2018| 
|sat_2018_math|int64|SAT|Average SAT Math Score per State in 2018| 
|sat_2018_total|int64|SAT|Average Total SAT Score per State in 2018|
|act_2018_participation|float64|ACT|Student Participation Rate per State in taking ACT tests in 2018| 
|act_2018_composite|float64|ACT|Average ACT Composite Score per State in 2018|
|act_2018_english|float64|ACT|Average ACT English Score per State in 2018| 
|act_2018_math|float64|ACT|Average ACT Math Score per State in 2018| 
|act_2018_reading|float64|ACT|Average ACT Reading Score per State in 2018| 
|act_2018_science|float64|ACT|Average ACT Science Score per State in 2018| 
|sat_2017_participation|float64|SAT|Student Participation Rate per State in taking SAT tests in 2017|
|sat_2017_erw|int64|SAT|Average SAT Evidence-based Reading and Writing Score per State in 2017| 
|sat_2017_math|int64|SAT|Average SAT Math Score per State in 2017| 
|sat_2017_total|int64|SAT|Average Total SAT Score per State in 2017| 
|act_2017_participation|float64|ACT|Student Participation Rate per State in taking ACT tests in 2017| 
|act_2017_english|float64|ACT|Average ACT English Score per State in 2017| 
|act_2017_math|float64|ACT|Average ACT Math Score per State in 2017| 
|act_2017_reading|float64|ACT|Average ACT Reading Score per State in 2017| 
|act_2017_science|float64|ACT|Average ACT Science Score per State in 2017| 
|act_2017_composite|float64|ACT|Average ACT Composite Score per State in 2017|

---

