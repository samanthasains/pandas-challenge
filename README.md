# pandas-challenge
In this repo, I analyze test scores and budgets for a school district using pandas.

I've generated several data frames to show different levels of analysis for the school district.

## High Level summary of the district
![alt text](https://raw.githubusercontent.com/samanthasains/pandas-challenge/main/PyCitySchools/Images/district_summary.PNG "District Summary")

## High Levels Summary By School
![alt text](https://github.com/samanthasains/pandas-challenge/blob/main/PyCitySchools/Images/school_summary.PNG?raw=true "Schools Summary")

## Top Performing Schools by Test Scores
![alt text](https://github.com/samanthasains/pandas-challenge/blob/main/PyCitySchools/Images/top_performing_schools.PNG?raw=true "Top 5 Schools")

## Bottom Performing Schools by Test Scores
![alt text](https://github.com/samanthasains/pandas-challenge/blob/main/PyCitySchools/Images/bottom_performing_schools.PNG?raw=true "Bottom 5 Schools")

## Math Scores by Grade per School
![alt text](https://github.com/samanthasains/pandas-challenge/blob/main/PyCitySchools/Images/math_scores.PNG?raw=true "Math Scores")

## Reading Scores by Grade per School
![alt text](https://github.com/samanthasains/pandas-challenge/blob/main/PyCitySchools/Images/reading_scores.PNG?raw=true "Reading Scores")

## Test Scores by School Spending
![alt text](https://github.com/samanthasains/pandas-challenge/blob/main/PyCitySchools/Images/scores_by_spending.PNG?raw=true "Test Scores by Spending")

### Trend to Note: Implications of Spending per Student
In the Test Scores by School Spending data frame, each measure of succcess decreases as spending per student goes up. This trend suggests that if schools have relatively lower test scores and percentage of passing students, it isn't likely to be explained by less money to allocate to students.

## Test Scores by Size
![alt text](https://github.com/samanthasains/pandas-challenge/blob/main/PyCitySchools/Images/scores_by_size.PNG?raw=true "Test Scores by Size")

### Trend to Note: Implications of School Size
The Test Scores by School Size show insignificiant difference for average math and reading scores and percentage passing for small and medium schools. However, large schools (2000-5000 students) show a drop off from small and medium schools, ranging from 2 percentage points lower in average reading score to 6 percentage points lower in average math score. The percentage of passing students drops significantly as well. This trend suggests that students at small and medium schools have higher test scores and passing rates than large schools.

## Test Scores by Type of School
![alt text](https://github.com/samanthasains/pandas-challenge/blob/main/PyCitySchools/Images/scores_by_type.PNG?raw=true "Test Scores by Type")

### Trend to Note: Charter versus District Schools
The Top 5 Performing schools by test score are all Charter schools, and the Bottom 5 Performing schools by test score are all district schools. Further, scores by School Type shows that average math and reading scores and percentage passing overall are all higher for Charter schools than District schools. This data suggests that Charter schools have higher test scores and passing rates for math and reading than district schools.


