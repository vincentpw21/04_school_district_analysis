# **School District Analysis Analysis**

## **Overview of Analysis**
The purpose of the analysis is to see how the summary metrics for the school district have changed since removing the invalid data for Thomas High School 9th Graders. The analysis will showcase the results that should be reported.

## **Results**
### **District Summary Differences**
**Original Summary**

![district summary via module](resources/district_summary_module.png)

**New Summary via Challenge**

![district summary via challenge](resources/district_summary_challenge.png)

    There is minimal shift in the average scores and the % passing for either subject or overall.

### **School Summary Differences**
**Original Summary**

![school summary via module](resources/school_summary_module.png)

**New Summary via Challenge**
![school summary via challenge](resources/school_summary_challenge.png)

    The only shifts are for Thomas High School as would be expected. The % passing for the subjects and overall decreased for Thomas High School. The average math score decreased from 83.42 to 83.35 while the average reading score increased from 83.85 to 83.90. In both instances, these differences are not sizeable.

### **Replacing Ninth Grader Scores Impact on Thomas High School relative performance to other schools (Top and bottom 5)** 
**Original Top 5**

![top 5 via module](resources/top_schools_module.png)

**New Top 5 Schools**
![top 5 via challenge](resources/top_schools_challenge.png)

    Thomas High School's relative performance is stable. The school remained in the top 5 and outside of the bottom 5 when sorting by % Overall Passing.
### **Math and Reading Scores by Grade**

**Original Math Scores**

![math scores via module](resources/math_scores_module.png)

**New Math Scores**

![math scores via challenge](resources/math_scores_challenge.png)

    New math scores tables reflects the removal of 9th grade scores from Thomas High School.
**Original Reading Scores**

![reading scores via module](resources/reading_scores_module.png)

**New Reading Scores**

![reading scores via challenge](resources/reading_scores_challenge.png)

    New reading scores reflect the removal of 9th grade scores from Thomas High School.

    Besides the NaN values there is no other shift in this data views, as expected.
### **Scores by school spending** 
**Original Scores by Spending**

![scores by spending via module](resources/scores_spending_module.png)

**New Scores by Spending**

![scores by spending via challenge](resources/scores_spending_challenge.png)

    The range of $630 to $644 was impacted by the Thomas High School edits. Percent passing rates decreased across each subject and overall as average scores dipped.

### Scores by school size

**Original Scores by Size**

![scores by size via module](resources/scores_size_module.png)

**New Scores by Size**

![scores by size via challenge](resources/scores_size_challenge.png)

    The only adjustment is the portion of those passing reading for the medium-sized schools which is still a minor adjustment in comparison. There was no impact on percetn overall passing for medium-sized schools.

### **Scores by school Type**

**Original Scores by Type**

![scores by type via module](resources/scores_type_module.png)

**New Scores by Type**

![scores by type via challenge](resources/scores_type_challenge.png)

    The scores by school type did not shift at all when removing the Thomas High School ninth grade scores.

## **Summary**
The changes found after the analysis showcase the impact that these ninth grade scores in a single high school can have on a data set with 39,000+ students.

1) Overall math and reading passing rates decreased slightly when looked at the district summary view.
2) The school level summary also highlighted the shift when removing ninth grade scores. The portion of students passing math and reading both decreased.
3) There was a visible impact to the analysis of spending per student in the $630 to $644 per capita range.
4) There was a slight decrease in the portion of students from mid-size schools passing reading as a result of the anlaysis.   

