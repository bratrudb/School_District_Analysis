# School_District_Analysis
Using Python and Pandas to develop school district analysis

## Overview of the school district analysis
We were tasked with using Python and Pandas within Jupyter Notebook to evaluate the performance of schools within a school district based on the outcome of students' test scores in math and reading. This analysis will allow the school board to allocate funding levels to each of the schools.

## Results

#### How is the district summary affected?
The district summary overview information is unaffected by the updated analysis. There are still 15 total schools with the same number of students and overall budget. The difference in the updated analysis is in the test scores for the district. By removing the Thomas High School ninth grade test scores, the average score in math is down slightly. The average reading score is unchanged at the level of significant figures used. The passing percentages for math, reading, and overall are all down slightly after removing the Thomas High School ninth grade test scores.

#### How is the school summary affected?

The school summary is unaffected except for the Thomas High School information. The number of students, overall budget, and budget per capita for Thomas High School is unchanged. the average math score is down slightly and the average reading score is up slightly after removing the the ninth grader's test scores. The percentage of students passing is slightly lower in each of the categories.

#### How does replacing the ninth graders' math and reading scores affect THomas High School's performance relative to the other schools?

Thomas High School's standing relative to other schools is unchanged. Their overall passing percentage is still second highest.

#### How does replacing the ninth-grade scores affect the following:

  - Math and reading scores by grade
      - The Thomas High School ninth grade scores for both math and reading now list nan
  - Scores by school spending
      - Unchanged
  - Scores by school size
      - Unchanged
  - Scores by school type
      - Unchanged

## Summary

  - In the district summary, the average math score and pass percentages are lower after removing the ninth graders' scores.
  - In the school summary, the average math score is down and the average reading score is higher for Thomas High School after removing the ninth graders' scores.
  - In the school summary, the percentage of students passing is slightly lower in each of the categories for Thomas High School after removing the ninth graders' scores.
  - In the math and reading scores by grade, the Thomas High School ninth grade scores both list nan after removing the ninth graders' scores.
