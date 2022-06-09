# School_District_Analysis

## Overview
Due to evidence of academic dishonesty on the reading and math scores for Thomas High School ninth graders, the PyCitySchools reports previously generated for the District must be modified. In this analysis, the reading and math scores for Thomas High School ninth graders have been invalidated to uphold state-testing standards. A new Distric and Schools Analysis have been conducted to reflect the clean data and describe how these changes affected the overall analysis.

## Results

### 1. District

#### Before
  <img width="914" alt="Before District totals" src="https://user-images.githubusercontent.com/104762216/172839190-80528ce2-ee72-471e-9850-404c850470ad.png">

  
#### After
  <img width="943" alt="Clean District Totals" src="https://user-images.githubusercontent.com/104762216/172838625-cf3f5d19-e478-483a-b4ad-72314c5420a9.png">

#### Observations
- The ninth graders at Thomas High School represent a small percentage of the total count of students in the District. Therefore, the District totals have been slightly affected.

### 2. School

#### Before 9th grade scores were invalidated
<img width="969" alt="Before Per school summary" src="https://user-images.githubusercontent.com/104762216/172949534-a0aa9bc4-3e7f-488f-bb9e-c04e8e161436.png">

- Once the metrics for the school summary were calculated with the invalid 9th graders scores, Thomas High School's overall passing percentage dropped significantly. The school went from having an overall passing rate of 90.9% to a 65%.
- In order to reflect a more accurate passing rate, I used the data from 10th through 12th graders to recalculate the passing math, passing reading, and overall passing percentages. The image below shows this analysis.

<img width="786" alt="per school analysis 10_12" src="https://user-images.githubusercontent.com/104762216/172950828-e00dbd89-b0bd-4ebf-a8e8-96d61d033c7e.png">

### 3. Other Metrics
- The Math and Reading scores by grade for Thomas High School were only affected for the 9th grade students. The other grades remained unchanged.

<img width="299" alt="Math scores by grade" src="https://user-images.githubusercontent.com/104762216/172956425-1e8a728b-6c04-4ef8-b618-3f7741975a0f.png">  <img width="297" alt="Reading scores by grade" src="https://user-images.githubusercontent.com/104762216/172956435-a7bfff1d-fee3-4d3e-9c94-3e19ad8b973d.png">

- Since Thomas High School spends $638 per student, it falls in the $630-$642 spending  range. This range's scores were negatively affected by the removal of the 9th grade scores in Thomas High School. The reading passing percentage went from 86% to 84%, the math passing percentage from 75% to 73% and the overall passing percentage from 66% to 63%. 
- The scores by school size  and school type were not affected at all.

## Summary
- The reading and math scores, and their passing rate percentages at the District level were negatively impacted by the removal of the Thomas High School nith grade scores. However, since the nith grade students at this particular high school represent a very small percentage of the total population of students in the Distric, the scores were only slighty affected.
- At the school level, counting the scores of all the students in Thomas High School, the averages and passing rates percentages for this charter school dropped significantly. The school rank goes from the top five high-performing schools to almost the bottom five.
- When we exclude the ninth graders from the calculations, it is observed that this charter school is likely to be a high-performing school.
- The invalidated scores from Thomas High School impacted negatively the scores by school spending by a few percentage points.






