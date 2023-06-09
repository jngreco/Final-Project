# Chicago Freshman OnTrack: Fact or Fiction? 
## Definitions 
* **Freshman on Track (FOT)**: A first-time ninth grader is considered to be "On-Track" if they accumulated at least 5 course credits during their first year of high school, failed no more than 0.5 course credits in a core course (English, Math, Social Studies or Science) and did not leave the school as a dropout.
* **Attendance over time**: average daily student attendance rate is the percentage of the total number of days in which students during the school year were marked present at a school, divided by the total number of days that those students were expected to be in attendance
* **Cohort**:  a group of ninth graders who enroll in high school for the first time during a school year. The cohort dropout rates are the percentages of a cohort who drop out of school within the 5-year and 4-year time spans.
* **College Enrollment Rate**: measures the percentage of students graduating from a school who in the previous year who enrolled in a 2-year or 4-year college in the fall after graduation from high school
* **College Persistence Rate**: measures the percentage of students counted in the college enrollment rate that remained enrolled in college the following fall

## Abstract 
Whatever we end up finding lol 

## Project Summary 
A [joint report](https://toandthrough.uchicago.edu/sites/default/files/uploads/documents/Data%20Insights%202020%20v5_0.pdf) published by the University of Illinois (UIC), UChicago Consortium on School Research, and the To&Through Project preports that how a 9th grade high school student performs during their freshman year is the most reliable way to predict future success for that student. In other words, whether or not a high school freshman meets the criteria to be considered "OnTrack" is `"more predictive of a students odds of graduating"` than all other factors combined--- including `"gender, race, socioeconimic status, 8th grade test scores, mobility prior to High School, and Overage for grade."`The report also claimed that freshman who are OnTrack graduate at a rate of `87%` compared to "off-track" students who graduate at a rate of only `30%`.

At face value, these findings presented an interesting research opportunity;
initially, we set out to build a predictive model that could examine an 8th grade cohort's RIT test scores. We then planned to train this model to predict whether or not the results of these scores could be used to predict with at least 80% accuracy whether or not these cohorts would go on to be "OnTrack" as they entered their freshman year of high school.  However, as we began developing our models and delving further into our gathered data, we realized 

### Changing Directions 
Our first and perhaps most insurmountable issue, given the time constraints under which we were opperating, was finding a reliable way to track the 8th grade cohorts into their 9th grade year. 
* What did we not take into account? 
* What made this tracking improbable? 

Upon closer examination of the [joint report](https://toandthrough.uchicago.edu/sites/default/files/uploads/documents/Data%20Insights%202020%20v5_0.pdf) and the discovery of the original FOT report--- ["The Use of Ninth-Grade Early Warning Indicators to Improve Chicago Schools"](https://nuvirtdatapt1-tlp6224.slack.com/files/U04EKRZ5A77/F05BS2AEJUC/jesparon-track.pdf) in the Journal of Education for Students Placed at Risk (JESPAR), we concluded that, due to an apparent lack of peer-reviewed data and replicatable results, using FOT as our guiding metric for predictive success may not produce the outcomes we set out to obtain. This realization, in tandem with the near-impossibility of reliably tracking cohorts across grades, led us to shift our focus. 

### Final Decisions 
After a brief discussion, we set out to answer the question: is FOT really the most accurate predictor of high school graducation? Our goal became to use the insights previously gleamed form our initial data gathering and normalization; this time, however, we took a look at the percentage of freshman considered OnTrack and the overall graduation rates of each school in our dataset. Then, using multiple predictive tests, compare our models to existing graducation and college enrollment/persistence data. 

## Limitations 
* Aggregate data 
* Time constraints 
* Tracking cohorts across grades 
* MESSY, messy data! 
* Unreplicated studies that do not appear to be peer reveiwed to an adequate degree
* only used data from 2015-2019 due to a change in how FOT status was calculated pre-2015. Post-2019 data excluded due to pandemic. 

## Future Direcions 

### Sources, Spreadsheets, and Shit 
#### Normalized Data 
* [Freshman On Track](https://cps-final-project-bucket.s3.us-east-2.amazonaws.com/metrics_fot_schoollevel_2022-1.csv) 
* [Graduation and Dropouts](https://cps-final-project-bucket.s3.us-east-2.amazonaws.com/metrics_cohortgraduationdropoutadjusted_schoollevel_2011to2019+(1).csv) 
* [College Enrollment and Persistence](https://cps-final-project-bucket.s3.us-east-2.amazonaws.com/metrics_collenrollpersist_schoollevel_20222_CLEAN_3.csv) 

#### Sources 
* [Chicago Public Schools Distric Data Metrics](https://www.cps.edu/about/district-data/metrics/)
* [Chicago Public Schools Assessment Reports](https://www.cps.edu/about/district-data/metrics/assessment-reports/) 
* [Data Insights (To&Through, UChicago)](https://toandthrough.uchicago.edu/sites/default/files/uploads/documents/Data%20Insights%202020%20v5_0.pdf)



