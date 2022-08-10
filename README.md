# Oregon's Accidents

## Team Members & Roles
- Ashley Morgan
    - Psudeo code, coding
- Connor French
    - Data wrangling, coding
- Greg Kell
    - Documentation, presentation, QA
- Molly Brown
    - Database, presentatin, QA



## Overview
For this project our team is going to take a closer look at potential causality of vehicle accidents in the state of Oregon in particular intersections. We will look at what factors are present in crash data from 2011 to 2015 including age, intoxication level, population density, etc. and try to determine what, if any, correlation exists between factors and the probability of a crash and where they happen.

We decided to focus on this after being initially interested in what makes intersections dangerous for pedestrians after reading this article on the <a href="https://www.google.com/url?q=https://www.vox.com/23178764/florida-us19-deadliest-pedestrian-fatality-crisis?fbclid%3DIwAR01wf7MAKZq0WSfzcHIXdFbYVJIQZu4Tfx4n5NoxRreMgKYhDvdrX1_LmQ&sa=D&source=docs&ust=1660099190520573&usg=AOvVaw1brG1VsDvkzz6zmrkaunKn">Deadliest Road in America</a>, but found that the data cited in a lot of the research papers was not accessible and decided to expand the scope of our inquiry. In general, we are all interested in exploring this topic as it could provide insight into a real-world problem that has devastating impacts on the people involved in fatal automobile accidents.

We will use an unsupervised machine learning algorithm with the intent of examining how these factors are clustered and discover what makes certain intersections dangerous and what contributes to their level of danger.

To do this analysis we will use data from the National Highway Traffic Safety Administration’s (NHTSA) Fatality Analysis Reporting System (FARS) which has an excellent <a href="https://www.google.com/url?q=https://cdan.dot.gov/query&sa=D&source=docs&ust=1660099224827534&usg=AOvVaw20YALS4-fo7wnJHcGq-CRR">query tool</a> to pull data on this subject. 

Depending on the results of our unsupervised machine learning algorithm we may take our analysis further by inputting the data into a supervised machine learning model to see if we can predict the number of accidents in a particular zip code.
