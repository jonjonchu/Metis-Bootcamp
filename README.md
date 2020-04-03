# WTWY Street Team Placement
This is the first project for the [Metis Data Science Bootcamp](www.thisismetis.com/), where we perform Exploratory Data Analysis (EDA)	on the [MTA turnstiles data](http://web.mta.info/developers/turnstile.html).


## Context
WomenTechWomenYes (WTWY) hosts an annual gala during the summer. To drive attendance, their Street team goes to subway stations in NYC to attract people to sign up for the gala.

## Goal
Provide recommendations on how WTWY csm optimize the placement of their Street teams in NYC subway stations, such that they can gather the most amount of signups.


## Methodologies

**1. Obtaining data:** We downloaded the [NYC MTA turnstile data](http://web.mta.info/developers/turnstile.html) of June 2019 to obtain the daily entries of people passing through the turnstiles at all stations in NYC. 

**2. Cleaning data:** 
  - Fixing errors: We corrected the turnstile entries' values where the entries were logging backwards. 
  - Removing outliers: We removed entries that are outside of 3 standard deviations. 
  - Creating the desired data fields: We calculated the entries through each turnstiles by day and by 4-hour interval
 
**3. Exploring data:** We created charts of top stations with the most foot traffic, broken down by day and 4-hour intervals.


## Deliverable
- [EDA]()
- [Presentation Slide]()


## Project Team
* [Andy Tan](https://github.com/github)
* [Jenny Wang](https://github.com/hellojenny) 
* [Jon Chu](https://github.com/jonjonchu)


## Additional Information
### Methods Used
* Exploratory Data Analysis
* Data Visualization

### Technologies Used
* Jupyter Notebook
* Python
* Pandas
* Numpy
* Matplotlib
* seaborn