# School_District_Analysis

## Overview
We have been tasked with assisting the chief data scientist for a city school district, Maria, with analyzing student test scores to inform discussions and stategic decisions. We will compare student test scores against budgets per student, as well as size of the school.

Furthermore, we have been notified that the test scores for Thomas High School (THS) ninth graders have been altered. We will remove these results and examine how that changes the overall outcome of the school district statistics.


## Results
We will compare the results without THS ninth graders test scores to see how they affected our original findings.
- How is the district summary affected?

Below we have a summary of the school district information, with THS ninth grade test scores removed.

![district_summary_noTHS9](https://user-images.githubusercontent.com/35434608/177090154-57114bc1-6fad-44ce-add7-6e38922d986e.png)

And here is the same table with the potentially fraudulent test scores included.

![district_summary](https://user-images.githubusercontent.com/35434608/177090564-dd04dbf8-72fa-4d9b-a4c6-57acd29c5548.png)

You can see that removing those test scores did not have a huge impact district wide. There are 15 schools in the district, and the problem only concerns one grade from one school. There are 461 ninth graders at THS, out of 39,170 students district wide. That is just over 1% of students.

That being said, removing the false data
	- lowered the Average Math Score by .1 points
	- lowered the % Passing Math by .2 points
	- lowered the % Passing Reading by .3 points and
	- lowered the % Overall Passing by .1 points.

- How was the school summary affected?

Below is a descriptive table of THS with the ninth grade scores removed, followed by a table with the ninth grade scores included.

![school_summary_noTHS9](https://user-images.githubusercontent.com/35434608/177110347-6a97b57c-f6c4-4830-9d4d-49e70e694c38.png)

Fraudulent scores included below:

![school_summary](https://user-images.githubusercontent.com/35434608/177110383-ba6eaab2-2253-491b-8b80-673b83d4cc6a.png)

After removing the test scores of 461 out of 1,635 students I expected a larger impact to the school's Average score. A possible explanation of this is that the scores we removed must have been very similar to the scores that remained.

- Compared with the other schools, 

removing the ninth grade scores did not change the fact that THS  students achieved the second highest % Overall Passing grades in the district, just behind Cabrera High School.

- In terms of spending compared to other schools, we found no difference.

![spending_summary](https://user-images.githubusercontent.com/35434608/177127070-18121ec2-3e2b-4b6e-9617-af99630699c8.png)

- We also found no difference when looking through size of the school, or the type of school.

![size_summary](https://user-images.githubusercontent.com/35434608/177127930-3f581197-7c75-4b24-86b3-dd75e205903e.png)

School types below:

![type_comparison](https://user-images.githubusercontent.com/35434608/177128931-b2bc4642-0a7c-40cf-9aac-a37528aad22b.png)





## Summary
The school district results in general showed that the biggest impact on student test scores was size of school. Four out of the top five schools in terms of percentage of overall passing students attended a school with fewer than 2,000 students.

The top ten performing schools showed a wider range of budgets per student, with four of the top ten being less than $586, and the rest are between $600 and $644.



