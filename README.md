# School District Analysis

## Overview of Analysis
The school board is concerned with academic dishonesty regarding reading and math grades for 9th graders at Thomas High School. The school board has requested that the compromised data be replaced with NaNs while keeping the rest of the data intact. Once the indicated data is replaced, Maria will need an updated school district analysis. 

## Results
### How is the district summary affected from removing 9th grade students from Thomas High School?
- Average Math Score: decreased from 79 to 78.90.
- Average Reading Score: did not change from 81.9.
- Percent Passing Math: decreased from 75.0% to 74.8%.
- Percent Passing Reading: decreased from 86.0% to 85.7%.
- Percent Overall Passing: decreased from 65.2% to 64.9%.

![District Summary Before](resources/district_summary_before.png)
![District Summary After](resources/district_summary_after.png)
    
### How is the school summary affected?
- Average Math Score: did not change from 83.4.
- Average Reading Score: increased from 83.8 to 83.9.
- Percent Passing Math: decreased from 93.3% to 66.9%.
- Percent Passing Reading: decreased from 97.3% to 69.7%.
- Percent Overall Passing: decreased from 90.9% to 65.1%.
    
![Thomas High School Summary Before](resources/ths_summary_before.png)
![Thomas High School Summary After](resources/ths_summary_after.png)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- Average Math Score: THS no longer remains in top 5 schools for average math score.
- Average Reading Score: No change in how THS performed relative to other schools. 
- Percent Passing Math: THS went from ranking 7th to 9th relative to the other schools. 
- Percent Passing Reading: THS went from being the top ranking school to the lowest ranking school in % passing reading.
- Percent Overall Passing: THS went from ranking 2nd to 8th for % overall passing.
    
**NOTE: At this point, the 9th grade scores were taken out from total student count in order to better reflect true overall passing percentage for THS.**

### How does replacing the ninth-grade scores affect the following:
-Math and reading scores by grade: The 9th grade scores were removed and the others stayed the same.
-Scores by school spending: No significant change in scores by school spending since the NaNs were no longer counted in the total student count regarding the total scores. 
-Scores by school size: No significant change in scores by school size since the NaNs were no longer counted in the total student count regarding the total scores.
-Scores by school type: No significant change in scores by school type since the NaNs were no longer counted in the total student count regarding the total scores.

![District Summary by School Size and Spending](resources/district_summary_complete.png)
![District Summary by School Type](resources/district_summary_schooltype.png)


## Summary
After initial score replacement for Thomas High School, ranking among other schools in the district was decreased significantly. However, once the 9th grade NaNs were no longer taken into consideration for Thomas High School's average and overall scores, THS moved back up the ranks and had no significant change in overall district rank. 
