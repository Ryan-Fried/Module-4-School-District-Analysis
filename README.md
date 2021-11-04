# Module-4-School-District-Analysis
Module 4: PyCitySchools

# Overview

The purpose of this exercise was to analyze a school district through a variety of metrics, from student performance to the impact of factors like school budgets and student population sizes. This specific anaylsis has been conducted to reevalute the results in light of apparent academic dishonesty amongst ninth graders at Thomas High School, which may have skewed the original results.

# Results

* After disregarding the 9th grade scores from Thomas High School and determining a new student count for that school with which to conduct our analysis, the outcome of the district summary changed minimally. The results for the Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, and % Overall Passing in the district as a whole all decreased very slightly, some so little that no change is observed when the data is formatted to the tenths decimal place as will be the case for most of the following results. Though the module and challenge suggest the dataframes be formatted to the tenth decimal place, the images in this report will display more precise results in order for the slight differences between the original and updated analyses to be apparent. Below are the original district summary and the updated district summary, respectfully:

![OG1](https://user-images.githubusercontent.com/91569387/140263185-89fbd996-18a6-4aef-b41a-e0fc29ea78e1.png)
![UP1](https://user-images.githubusercontent.com/91569387/140263201-f515f568-e618-4f32-8d36-e8aa8730cb86.png)

* As with the district summary, the results for the Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, and % Overall Passing have all changed very slightly as a result of the change in data for Thomas High School. In this case, the formatting of the chart to a further decimal place allowes the miniscule differences between the original and updated analysis to be a bit more evident upon close inspection. All but the Average Reading Score (which increased by .047%) decreased slightly. Below are the original and updated per school summaries, respectfully:

![OG2](https://user-images.githubusercontent.com/91569387/140263565-cecdf256-6a95-4212-b24d-36953b5c66fd.png)
![UP2](https://user-images.githubusercontent.com/91569387/140263588-7ea2709b-50e4-4579-84f0-c28fbbeaf51a.png)

* Relative to other schools, replacing the 9th grader's math and reading scores had no impact on Thomas High School's performance, as it ranked as the second highest school by Overall Passing Percentage in both the original and updated analysis. Below are the top 5 schools from the original and updated analysis, respectfully:

![OG3](https://user-images.githubusercontent.com/91569387/140263636-d60c2a6a-6c73-4c95-86d3-e1a2c96364b7.png)
![UP3](https://user-images.githubusercontent.com/91569387/140263644-f2d4822e-6a5b-445e-9bf7-7f8a91961e9e.png)

* The math and reading scores by grade see no change from the original except for the exclusion of the data for Thomas High School's 9th grade class, which is represented by 'nan'. The grades for 10th, 11th, and 12th grade remain unchanged. Below are the original and updated math scores, followed by the original and updated reading scores:

![OG4 1](https://user-images.githubusercontent.com/91569387/140264980-d94634bd-8ad1-4dd0-8cbe-ece3ebbf3077.png)
![UP4 1](https://user-images.githubusercontent.com/91569387/140265001-83b33bd4-b90c-42f7-8435-c7fe6d2edfc3.png)

![OG4 2](https://user-images.githubusercontent.com/91569387/140265033-42198399-b444-41ac-a2f6-4c6672463b5f.png)
![UP4 2](https://user-images.githubusercontent.com/91569387/140265038-2fc1014d-a5dc-4d3e-a466-c87416c0f15f.png)

* Thomas High School's average spending per student is $638, meaning only the data in the $630 - $644 bin has changed. Due to the change in results being so small, when expressed to the tenth decimal place, the outcomes for scores by spending range are identical between the original and updated analyses. As shown here, the results differ by less than a tenth of a percent in most cases, with all but average reading scores showing a small decrease. Below are the original and updated scores by school spending:
    
![OG5](https://user-images.githubusercontent.com/91569387/140266263-eefa7cda-1b4b-4a53-a0ea-4644dfed6f88.png)
![UP5](https://user-images.githubusercontent.com/91569387/140266273-66cbea3c-babb-4e49-b839-408e20df9b0e.png)

* The same can be said for the results for scores by school size. Thomas High School has 1635 students making it a medium sized school, thus only the Medium (1000-2000) bin has changed. The differences between the original and updated results are once again so small that they are invisible with the formatting recommending in the assignment and module. As shown, the results differ by less than a tenth of a percent, with all but average reading scores showing a small decrease. Below are the scores by school size outcome for both the original and updated analyses:

![OG6](https://user-images.githubusercontent.com/91569387/140267749-27d191e8-c428-4a8a-8d32-01a5bc3bff5f.png)
![UP6](https://user-images.githubusercontent.com/91569387/140267762-d9331021-0dcf-4ce1-8ec2-6bbda1d8b1d8.png)

* Thomas High School is a charter school (which seem to generally perform better than district schools in this dataset), thus only the charter index has changed. For scores by school type, once again, the differences between the original and updated results are so small that they are invisible with the formatting recommending in the assignment and module. All of the results differ by less than a tenth of a percent, with all but average reading scores showing a small decrease. Below are the scores by school type outcome for both the original and updated analyses:

![OG7](https://user-images.githubusercontent.com/91569387/140268309-5fb77168-77b8-468c-80b2-f36f06dbb8d9.png)
![UP7](https://user-images.githubusercontent.com/91569387/140268325-c6386028-725f-49a3-b984-e232ba499958.png)

# Summary

It is quite difficult to make note of changes in the results once the 9th grade scores from Thomas High School have been taken out, as the difference between the original and updated datasets is evidently quite small, to the point of debatable insignificance. Because all of the changes are so small (generally under a tenth of a percent, if not a hundreth of a percentage difference), we can figure that even if the scores were academically dishonest, the percentage of students passing math and reading and the average scores of those students were very similar and representative of those figures for the other grades in Thomas High School overall. Perhaps the most noteworthy change, or at least that change that seems to stand out comes in the average reading scores, which throughout all of the results are the only metrics which increase in value, although to a very small degree. Conversely the average math scores, as well as the passing math, reading, and overall percentages display a slight decrease.
