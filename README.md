# **School District Analysis**

## **Purpose**

The purpose of this analysis was to access different libraries within Python such as Pandas and Numpy to perform the school district analysis. Part of the analysis was to see if there is a trend between math and reading scores based on school size, school type, & school budget. 

## **Results** 

### _How is the district summary affected?_ 

The school board was suspecting Thomas High School of manipulating there scores which could alter schools in the top five position. After taking out the reading and math scores for all ninth graders, the district summary did not change. The following table ![table](https://github.com/tutran90/School_District_Analysis/blob/main/Resources/Top_schools_before_edit.pnr.png) displays the ranking of the top five schools before the scores were taken out. The following table ![table](https://github.com/tutran90/School_District_Analysis/blob/main/Resources/Top_schools_after_edit.png) displays the ranking of the top five schools after the scores were taken out. There was not a significant change in ranking. Thomas High School was still one of the top 5 performing schools in the district. 


### _How is the school summary affected?_ 
The following table ![table](https://github.com/tutran90/School_District_Analysis/blob/main/Resources/School_summary_before.png) displays all the schools and details about their schools. Nothing changed after the grades were removed. 

### _How does replacing the ninth graders' math and reading scores affect Thomas High School's performace relative to other schools?_ 

Like mentioned above, Thomas High School still performed pretty well even without ninth graders' math and reading scores. Thomas High School was still one of the top five performing schools in the district. The difference in average math scores was less than 0.1 points with the Average Math Score before edits were made being 83.41 and after being 83.35. The other categories: Average Reading Score, % Passing Math & Reading, and % Overall Passing, also had less than 0.3 points different after the grades were adjusted. 

### _How does replacing the ninth-grade scores affect the following:_

For the following analysis, please refer to the following table for before edits![table](https://github.com/tutran90/School_District_Analysis/blob/main/Resources/Top_schools_before_edit.pnr.png) and the following table for after edits ![table](https://github.com/tutran90/School_District_Analysis/blob/main/Resources/Top_schools_after_edit.png)

* Math and reading scores by grade

    1. Average Math scores for Thomas High School had a 0.1 point difference after edits were made. (before: 83.41, after: 83.35)
    2. Average Reading scores for Thomas High school had a 0.002 point difference after edits were made. The grade average after adjustments were made were slightly higher but not significantly. (before: 83.848, after: 83.846)
    3. Percentage passing math for Thomas High School had a 0.09 point difference after edits were made. (before: 93.27, after: 93.18)
    4. Percentage passing reading for Thomas High School had 0.28 point difference after edits were made. (before: 97.30, after: 97.018)
    5. Overall passing percentage for Thomas High School had a 0.31 point difference. (before: 90.94, after: 90.63)

* Scores by school spending

    The total school budget was unchanged after edits were made. It stayed at $1,043,130.00. 

* Scores by school size & type

    Score by school size and type did not change signgificantly even after the edits were made. The following table displays the same data for both before and after ![table](https://github.com/tutran90/School_District_Analysis/blob/main/Resources/School_size_scores_before.png)

## **Summary** 

Based on the analysis that was provided during this summary, it is safe to say that Thomas High School did not inflate or alter there scores. There was not a significant change in their scores even with the ninth graders' scores being removed. However, another way to determine if this truly was true is to perform the same analysis but removing each grade level one at a time. 

The following table ![table](https://github.com/tutran90/School_District_Analysis/blob/main/Resources/Type_summary_before.png) however gives us a good picture between the difference in how Charter and District schools perform. It shows that Charter schools perform higher than students for District schools. The Overall Passing percentage for Charter schools' was 90% while District schools' passing percenatage was 54%. It is safe to theorize that Thomas High School would still perform well since they are a Charter school. 