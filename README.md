# School District Analysis
## Overview 
The school board believes the 9th grade math and reading scores for Thomas High School are showing signs of acedemic dishonesty.  The purpose of this analysis is to evaluate the impact to the mean scores when the grade nine scores for Thomas High School (THS) are excluded. A before and after comparison should be telling if cheating has occurred.  

## Results
In the results below, the images will show the results from removing the greade nine scores (first line in the image) against the original tabulation which included the grade nine scores (second line in the image) for THS.

### District Summary
The district shool summary **_Figure 1_** shows there is no change in the average scores or passing percentages.  Output 13 in the image excludes the 9th grade results from THS and there is no difference from the dataframe in output 88

**_Figure 1: District Summary_**

![District School Summary](/resources/district_summary.png)

### Top Schools & School Summary
In the Top Schools list, the **_Figure 2_** output line 108, shows THS was the 2nd highest ranked school based on the overall passing percentage.  After removing the nineth grade scores, output line 29 shows the school is still ranked in 2nd.  The overall, passing percentage dropped by a tiny fraction of 0.31%.  

**_Figure 2: Top Schools_**

![Top School](/resources/top_schools.png)


### Affects of Replacing Scores

No matter which view you take, **_Figures 3-8_**, show that there were either tiny or no impacts to the average math, reading, or overall percentage scores.  This holds true regardless of the type of school, funding, or school size.  

The average math scores fell by 0.087% and the average reading score dropped by 0.29% when the 9th grade scores were removed.  In both cases the mean on these scores remains fairly static.  There is no large swing to the left or right which could be a clue if there were some deception.  


**_Figure 3: THS School Summary_**

![School Summary](/resources/School_summary.png)


**_Figure 4: Math Scores Comparison_**

![Math Scores Compare](/resources/math_scores_compare.png)


**_Figure 5: Reading Scores Comparison_**

![Reading Scores Compare](/resources/reading_score_compare.png)


**_Figure 6: Scores by School Spending_**

![Scores by Spend](/resources/scores_by_spend.png)


**_Figure 7: Scores by School Size_**

![Scores by School](/resources/scores_by_school_size.png)

**_Figure 8: Scores by School Type_**

![Scores by Type](/resources/scores_by_type.png)

## Summary
In summary, academic dishonesty cannot be found in the analysis above.  If it did exist when the THS 9th grade results were removed we would have seen some sort of telling change in the mean.  Based on the evidence the mean math scores fell by 0.08% and 0.29% for reading scores.  The overall passing percentage did not change drastically either.  The conclusion is no dishonesty can be detected in this data set.
