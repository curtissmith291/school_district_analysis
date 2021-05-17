# school_district_analysis
Module 4 pandas coursework

### Module 4 Challenge

## Overview of the School District Analysis

After the initial school distric analysis looking at the trends of math and readig grades vs. school, school types, funding, etc., it was determined that some evidence of academic dishonesty was present, specifically the reading and math grades for THomas High School ninth graders. We were asked to remove the Thomas High School ninth grade reading and math grades and re-run the previous analysis and describe what changes the removal affected. 

## Results

# Distict Summary Changes

There are 39,170 total students in the PyCity School District and 461 ninth graders from Thomas High School were removed; as the total amount of students removed was relatively small, the summary did not change much beyond a few points per thousand. The before and after summaries are presented below:

![District Summary Before](https://github.com/curtissmith291/school_district_analysis/blob/main/Resources/District_Summary_Before.png)

![District Summary After](https://github.com/curtissmith291/school_district_analysis/blob/main/Resources/Disctrict_Summary_After.png)

As shown, the passing rate for math, reading, and overall dropped by 0.02%, 0.01%, and 0.03%, respectively. 

# School Summary Changes

The order of school ranked by % Overall Passing did not change. The passing rates for math, reading, and overall at Thomas High School prior to the removal of the ninthe grades scores were 93.3%, 97.3%, and 91.3%, respectively, and changed to 93.1%, 97.0%, and 90.6% after the changes. The School Summary tables are presented below. 

![School Summary Before](https://github.com/curtissmith291/school_district_analysis/blob/main/Resources/School_Summary_Before.png)

![School Summary After](https://github.com/curtissmith291/school_district_analysis/blob/main/Resources/School_Summary_After.png)

# How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

As shown above, the changes in grades were minor, so the rankings between schools did not change. 

# How does replacing the ninth-grade scores affect the following:

-Math and reading scores by grade

As the ninth grade reading and math grades were removed from onlt Thomas High School, scores did not change. 

-Scores by school spending

% Passing Reading in the $630-644 range was the only value to change after the ninth grade Thomas High Schol Students were removed. The % Passing Reading was 84.4% before and dropped to 84.3% after, as shown in the tables below. 

![School Spending Before](https://github.com/curtissmith291/school_district_analysis/blob/main/Resources/School_Spending_Before.png)

![School Spending After](https://github.com/curtissmith291/school_district_analysis/blob/main/Resources/School_Spending_After.png)

-Scores by school size

As above, % Passing Reading was the only value to change in the Medium (1000-2000) category, from 96.8% to 96.7% after the ninth grade Thomas High School student grades were removed, as shown in the tables below.

![School Size Before](https://github.com/curtissmith291/school_district_analysis/blob/main/Resources/School_size_Before.png)

![School Size After](https://github.com/curtissmith291/school_district_analysis/blob/main/Resources/School_size_After.png)

-Scores by school type

The % passing rates did not change after the the ninth grade Thomas High School student grades were removed, as shown in the tables below.

![School Type Before](https://github.com/curtissmith291/school_district_analysis/blob/main/Resources/School_Type_Before.png)

![School Type After](https://github.com/curtissmith291/school_district_analysis/blob/main/Resources/School_Type_After.png)

## Summary

As shown above, after dropping the ninth grade scores from Thomas High School, the summaries either only changed by a few points per thousand, or did not change at all when rounded to the tenths place. 
