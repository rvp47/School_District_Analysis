# School_District_Analysis

## Overview
The school board found evidence of academic dishonesty for the math and reading grades for Thomas High School ninth graders. The purpose of this analyse is to understand how changing the data to replace nineth graders' math and reading scores affects how Thomas High School performances relative to other schools. This analysis compares the results of a previous school district analysis with unaltered scores to an updated school district analysis with changes to the math and reading scores for the ninth graders at Thoman High School.

The updated analysis includes the following:
- District summary DataFrame
- School summary DataFrame
- Top 5 performing schools, based on the overall passing rate
- Bottom 5 performing schools, based on the overall passing rate
- Average math score for each grade level from each school
- Average reading score for each grade level from each school
- Scores by school spending per student
- Scores by school size
- Scores by school type

## Results
By making changes in the data, each of the seven school district metrics was affected: district summary, school summary, Thomas High School’s performance relative to the other schools, math and reading scores by grade, scores by school spending, scores by school size, and scores by school type.

### District Summary
How is the district summary affected?

Changing the data resulted in the district summary having a lower average math score, lower % passing math, lower % passing reading, and lower % overall passing than the district summary using the original data. The average reading score was no different.

Original data
![district_summary_original](https://user-images.githubusercontent.com/90656004/140653248-290fb0c9-a84b-4ac5-a341-59bc38cf21b6.PNG)

Cleaned up data
![district_summary](https://user-images.githubusercontent.com/90656004/139881119-61d55b11-8edd-49fd-9dce-3eb748156490.png)

### School Summary
How is the school summary affected?

After cleaning up the data, Thomas High Schools saw a lower average math score, higher average reading score, lower % passing math, lower % passing reading, and lower % overall passing. However, the differences were very slight at less than a 1% increase or decrease.

Original data
![school_summary_original](https://user-images.githubusercontent.com/90656004/140653485-2d562021-f2fd-424b-ac3e-3ed61a3a15fb.PNG)

Cleaned up data
![school_summary](https://user-images.githubusercontent.com/90656004/140653399-6d9cfeee-b2b4-4cde-8fb7-69c887922b28.png)

### Replacing ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Replacing the scores did not affect Thomas High School’s performance relative to the other schools in the district.

Original data

Top performing schools: ![top_original](https://user-images.githubusercontent.com/90656004/140653593-065a7c47-b6e1-4aa1-bb00-f8a1009eab0c.PNG)
Bottom performing schools: ![bottom_original](https://user-images.githubusercontent.com/90656004/140653594-ba76a82c-0853-4283-9291-be29c609f113.PNG)

Cleaned up data

Top performing schools: ![top](https://user-images.githubusercontent.com/90656004/140653533-96fd434d-a9f3-4151-ab55-91a5f560aee0.PNG)
Bottom performing schools: ![bottom](https://user-images.githubusercontent.com/90656004/140653560-a741b33b-7ad8-4200-a0ba-c1f11a8bec6d.PNG)

### How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade
  - There was no change in the average math and reading scores by grade other than the cleaned up data having “nan” in place of the average ninth graders’ score for Thomas High School.

- Scores by school spending
  - For scores by school spending, there was no difference between original and cleaned up data. 

  Original data
   ![scores_by_spending full table original](https://user-images.githubusercontent.com/90656004/140653671-9e977e95-870a-46fa-a381-ff92909b06cb.PNG)
   ![scores_by_spending original](https://user-images.githubusercontent.com/90656004/140653729-629b4588-a035-441d-8cff-e33da89c7ad3.PNG)

  Cleaned up data
  ![scores_by_spending full table](https://user-images.githubusercontent.com/90656004/140652645-5ef23bed-63f5-4a27-bb32-9b58d4da85d9.PNG)
  ![scores_by_spending](https://user-images.githubusercontent.com/90656004/140652575-be8e3b1b-c37d-4344-a454-a917e8e266b7.png)

- Scores by school size
  - The cleaned up data was no different than the original data for scores by school size.

  Original data
  ![scores_by_size original](https://user-images.githubusercontent.com/90656004/140653868-3e58cb8a-71a0-4b57-a17e-69b7b1dae936.PNG)
  
  Cleaned up data
  - ![scores_by_size](https://user-images.githubusercontent.com/90656004/140652591-d3775605-7861-4eae-81fb-a2c7e02541bc.png)

- Scores by school type
  - Based on the cleaned up data, there was no difference between the original and cleaned up data for scored by school type.

  - ![scores_by_school_type](https://user-images.githubusercontent.com/90656004/140652598-c6d129cc-97bd-45a9-ba53-b765a4139464.png)

## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
