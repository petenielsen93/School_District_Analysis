# School_District_Analysis
    1. This analysis was for Maria and her supervisor, who work for the school board. They requested this analysis of student and school data to make decisions for the coming years. They requested a high-level snapshot of the district's key metrics, presented in a table format, as well as overviews for each school. After conducting this analysis, the school board informed us that there was academic dishonesty, making some of the data uncredible. The challenge was to replace the tainted data, and then re-do the analysis with the correct numbers.


## Results
    - The district summary before the data rework and after are not too much different. The Average Reading Score was the one metric that did not change at all, while the Average Math Score only dropped one tenth of a percent. The percent of students passing math (% Passing Math) dropped by .2 to 74.8%, and the percent of students passing reading only dropped by .3 to 85.7%. The overall percentage of students who passed also only decreased by a tenth of a percent. In the grand scheme of things, the removal of the data did not do much to affect the district averages, as taking out the data for one grade from one school is not a significant percentage of the population. See below for the comparison of district tables, with the pre-rework displaying first. 

    ![](Resources/PreReworkDistricts.png)

    ![](Resources/PostReworkDistricts.png)

    - The school summary before the data rework and after are identical, except for Thomas High School of course. The changes there are still very minimal, with % Passing Math, % Passing Reading, and % Overall Passing percentages all moving less than a percent, although decreasing. See below for the tables, with pre-rework showing first.

    ![](Resources/PreReworkSchools.png)

    ![](Resources/PreReworkSchools.png)

    - It appears that removing the data from Thomas High 9th graders did not affect the overall scoring of the school as well. Thomas High School still ranks #2 when listing the schools by % Overall Passing. See below for the list of Top 5 Schools, with the pre-rework table showing first. 

    ![](Resources/PreReworkTop.png)

    ![](Resources/PreReworkTop.png)


    - Replacing the 9th graders from Thomas High School affects some of the other data as well. The Math and Reading passing percentages by grade were definitely brought down by leaving out the scores, but Thomas High School was ranked as the #2 school based on Overall Passing Percentage, before and after the rework. 
    - When it comes to Scores by School Spending, its important to remember that Thomas High School is a small charter school. However, they spend between $630 - $644 per student. The rework did not have any affect on this data, as the averages and percentages for their spending range of $630 - $644 per student did not change. 
    
    ![](Resources/SpendingRangePerStudent.png)

    - Scores by Size was a bit trickier to derive information from, because in the Challenge analysis, I used a larger amount of bins than in the Module analysis. In the Module analysis, we used 3 different size ranges: <1000 (Small), 1000 - 2000 (Medium), and 2000 - 5000 (Large). In the Challenge analysis, the ranges were broken up by the 1000's. In the Module analysis, Thomas High landed in the Medium category with 1625 students, while in the Challenge analysis, they ended up in the Small category (1000 - 2000 students). This (thankfully) created the same bin but in different analysis' (both use the 1000 - 2000 range.) Knowing this, you can see our data did not change at all. We still used the same total of students when calculating the Range per Student, so the numbers would not have changed anyways. See the below tables, with the first being from the Module analysis. 

    ![](Resources/PreSizeAnalysis.png)

    ![](Resources/PostSizeAnalysis.png)

    - Scores by type did result in some changes, but very minor ones for the Charter type. The % Passing Math and Reading dropped less than a percent, but the % Overall Passing actually increased. This is possible because when removing the Thomas High 9th graders, the percentage of students that passed both reading and math increased, while the percentage of students the passed math OR reading decreased. We can conclude that Thomas High 9th graders were more likely to pass math or reading, but not both. See the tables below, with the first being pre-rework.

    ![](Resources/PreType.png)

    ![](Resources/PostType.png)

## Summary

- Four major changes that occured after the data update are as follows. First, the school averages for Thomas High School decreased slightly after retooling the data to not include the 9th graders. Secondly, the exclusion of that data decreased the passing percentage for Math and passing percentage for Reading for all 9th graders. Next, the analysis confirmed that the passing percentage for Reading and Math decreased for students at Charter schools. And finally, the Overall Passing percentage for the Charter Type increased, meaning that Thomas High 9th graders are more likely to pass math or reading, but not both. 