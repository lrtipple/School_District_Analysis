# School_District_Analysis

## Overview of Project
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; 
specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. 
Although the school board does not know the full extent of the academic dishonesty, 
they want to uphold state-testing standards and have turned to Maria for help. 
She has asked me to replace the math and reading scores for Thomas High School with NaNs while keeping 
the rest of the data intact. I replaced the math and reading scores, and
Maria asked me to repeat the school district analysis that I did in this module and write up a report 
to describe how these changes affected the overall analysis.

## Resources
- Data Source: schools_complete.csv and students_complete.csv
- Software: Python 3.7.6, Pandas, Jupyter Notebook

## Results
**How is the district summary affected?**
- The original district summary went down by a tenth of a percent in the revised analysis, from an average of 79% to 78.9% for only the math score. The reading score and passing percentages did not change between the two analyses.
  - **Original district summary:**
![original_district_summary](https://user-images.githubusercontent.com/99093289/158078632-d65fd584-715a-417c-8a15-3ce350a2fb63.PNG)
  - **Revised district summary:**
![Revised_District_summary](https://user-images.githubusercontent.com/99093289/158078641-41d621a2-9226-4ec5-a2fd-3b25b99f624a.PNG)

**How is the school summary affected?**
- The indiviudal school averages for Thomas High School only increased by a tenth of a percent for the average reading score, however the % passing average decreased by a tenth of a percent for passing math and two tenths of a percent for the % passing reading.
  - **Original school summary:**
![original_school_summary](https://user-images.githubusercontent.com/99093289/158079160-a86c41c7-acd1-4c57-adf9-73c03b8a7687.PNG)
  - **Revised school summary:**
 ![Revised_school_summary](https://user-images.githubusercontent.com/99093289/158079163-550ca70a-d6a6-48ac-9504-37880470c06e.PNG) 
 
**How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**
- Replacing the ninth fraders' math and reading scores did not impact Thomas High School's overall performance relative to the other schools. They were the 2nd highest top performing school in the original analysis and the revised analysis.
  - **Original top schools:**
![Original_Top_Schools](https://user-images.githubusercontent.com/99093289/158080601-708a3a5c-336c-4f75-a138-f42ff58b104f.PNG)
  - **Revised top schools:**
![Revised_Top_Schools](https://user-images.githubusercontent.com/99093289/158080613-a55e845b-ba04-412f-ad75-bf5aa6c826a4.PNG)

**How does replacing the ninth-grade scores affect the following:**
**Math and reading scores by grade**
- Replacing the ninth-grade scores decreased the overall ninth grade average from 80.4 to 80.1 in math and from 82.5 to 82.4 in reading.
![grade_comparison](https://user-images.githubusercontent.com/99093289/158081269-3e06ba03-3bdb-4bf1-a84d-81dd5c10f284.PNG)
**Math and reading scores by spending, size, and type**
- Replacing the ninth-grade scores had no impact to the average scores by spending, size, or type.
  - **Scores by spending:**
![Revised_scores_by_spending](https://user-images.githubusercontent.com/99093289/158081385-0f85a93a-2d21-4a44-9f00-26ab88019abc.PNG)
  - **Scores by school size**
![score by size](https://user-images.githubusercontent.com/99093289/158081485-cc07a1c6-0fdf-4e8a-8395-8195e862e14b.PNG)
  - **Scores by school type**
![score by type](https://user-images.githubusercontent.com/99093289/158081487-fde99b85-85fb-4b17-918d-e4b571b39104.PNG)

## Summary
By replacing the ninth graders' scores for Thomas High School with NaNs, these are four of the changes:
- Thomas High School dropped from the 4th highest math score average to the 5th highest math score average, of high schools in the district.
- Thomas High School increased from the 7th highest reading score average to the 5th highest reading score average, of high schools in the district.
- Thomas High School's overall passing percentage dropped .3%, but the school maintained 2nd highest in the district for overall passing.
- Thomas High School's overall passing math percent dropped by .1%.
