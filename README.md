# School_District_Analysis
The School Board has notified us of some irregularities in the student data master file.
Specifically, reading and math scores for Thommas High School appear to have been altered.
In order to uphold proper academnic standards, the School Board has asked for an in-depth
analysis of the test score data to reveal any details about the irregularities.

## Methodology
The previous analysis includes math and reading grades for all students.  In order to 
test for any anomolies, this analysis will first remove all ninth grade reading and math scores by replacing the scores
in the dataset with null values.  The analysis will be altered further by calculating the count of Thomas High School ninth graders
and removing them from any cumulative analyses.  The results of both sets of research will then be contrasted
and compared in order to identify any outliers that could represent academic dishonesty.

### District Summary

Pre-data scrub:
![alt text](https://github.com/brian-mcrae/School_District_Analysis/blob/main/Resources/District_Pre_Scrub.PNG)

Post-data scrub:
![alt text](https://github.com/brian-mcrae/School_District_Analysis/blob/main/Resources/Disctrict_Post_Scrub.PNG)

The data informs us that the distribution of grading data for ninth graders at Thomas follows the data for the entire district.  
Conclusion: No anomaly found

### School Summary

Pre-data scrub:
![alt text](https://github.com/brian-mcrae/School_District_Analysis/blob/main/Resources/School_Pre_Scrub.PNG)

Post-data scrub:
![alt text](https://github.com/brian-mcrae/School_District_Analysis/blob/main/Resources/School_Post_Scrub.PNG)

The data informs us in both cases that the distribution of grading data for ninth graders at Thomas follows the data for the entire
disctric.  In both cases, removing the Thomas data from the dataset resulted in a ~.3 point shift in the average grades.  No anomaly found.

### Thomas High School Performance relative to other schools
The data informs us that there is no meaningful difference

