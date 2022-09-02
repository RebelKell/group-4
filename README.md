# Oregon's Fatality Factors

## Team Members & Roles
- Ashley Morgan
    - Psudeo code, coding
- Connor French
    - Data wrangling, coding
- Greg Kell
    - Documentation, presentation, QA
- Molly Brown
    - Database, presentation, QA


## Overview
For this project our team is going to take a closer look at fatal vehicle accidents in the state of Oregon. We will look at what factors are present in crash data from 2011 to 2015 including age, intoxication level, speed, etc. and try to determine what, if any, correlation exists between factors and the probability of a crash and where they happen.

We decided to focus on this after being initially interested in what makes intersections dangerous for pedestrians after reading this article on the <a href="https://www.google.com/url?q=https://www.vox.com/23178764/florida-us19-deadliest-pedestrian-fatality-crisis?fbclid%3DIwAR01wf7MAKZq0WSfzcHIXdFbYVJIQZu4Tfx4n5NoxRreMgKYhDvdrX1_LmQ&sa=D&source=docs&ust=1660099190520573&usg=AOvVaw1brG1VsDvkzz6zmrkaunKn">Deadliest Road in America</a>, but found that the data cited in a lot of the research papers was not accessible and decided to expand the scope of our inquiry. In general, we are all interested in exploring this topic as it could provide insight into a real-world problem that has devastating impacts on the people involved in fatal automobile accidents.

We will use an unsupervised machine learning algorithm with the intent of examining how these factors are clustered. We are interested to see which factors go into each cluster and each cluster's share of the dataset. 

To do this analysis we will use data from the National Highway Traffic Safety Administration’s (NHTSA) Fatality Analysis Reporting System (FARS) which we thought had an excellent <a href="https://www.google.com/url?q=https://cdan.dot.gov/query&sa=D&source=docs&ust=1660099224827534&usg=AOvVaw20YALS4-fo7wnJHcGq-CRR">query tool</a> to pull data, but we found that we were not able to get all the raw data we needed on this subject. Instead we ended up downloading 21 .csv files for each year of the study. Not all of these files were used, and 2015 had slightly different file setup from the other years.  


## Data
We pulled data files from the National Highway Traffic Safety Administration's (NHTSA) Fatality Analysis Reporting System (FARS) for years 2011 through 2015. Each year had to be filtered for only Oregon data. A detailed analysis of the processing and the data itself is in `data_README`

## Machine Learning
For the unsupervised ML portion of our project, we will be using Agglomerative Clustering and Dendrograms to visualize the groups. We will also explore a K-means algorithm for further analysis. For the supervised ML portion of our project, we will use linear regression to compare county results to the overall Oregon results.

## Collaboration Tools
To collaborate for this project we are using a Google Doc to collect our initial thoughts/brainstorming. We are using Slack to stay in touch asynchronously and using Zoom to host group meetings to talk through portions we are working on together.


## Presentation Preparation
The presentation is coming along nicely and can be see <a href="https://docs.google.com/presentation/d/1sumsFd5GnrvDwHLD4QbD8gdcZRA34VOBbRvQ7aJMU50/edit#slide=id.p1">Google Slides</a>.

Dashboard can be <a href="https://public.tableau.com/app/profile/greg.kell1682/viz/OregonAutoFatalaties/Dashboard1?publish=yes">seen here</a> and interactivity was added to incorporate filters of the data.


