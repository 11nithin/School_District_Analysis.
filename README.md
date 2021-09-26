# School_District_Analysis.

## Overview of the school district analysis

   The school board has identified an evidence of academic dishonesty on students_complete.csv file; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. To find the full extent of the academic dishonesty, the math and reading scores for Thomas High School replaced with NaNs while keeping the rest of the data intact and the School district analysis are conducted again to describe how these changes afffected the overall analysis. 


## Results
- District summary

   Replacing Thomas high school 9th grade scores by NaN is making only very less impact on district summary. The % overall passing fell 0.1% , % passing Math fell 0.2 % and % passing reading fell .3%. 
   
      District summary before

     ![before](https://github.com/11nithin/School_District_Analysis./blob/main/Resources/District_summary_before.PNG)

      District summary after

     ![after](https://github.com/11nithin/School_District_Analysis./blob/main/Resources/District_summary_after.PNG)

- School Summary and Schools perfomance
  
   Removing 9th grade data from Thomas high school made very less impact on school summary.  Even after removing the 9th grade scores from the summary, school ranking remained  same. Eventhough the % overall passing variation is very less, it can make an impact on the ranking. The first and 5th ranked %overall passing differnece is 0.71%. In this case eventhough Thomas High school % overall passing fell 0.31% it made no differnce in the ranking.

    ````
         Thomas High school summary change after removing 9th grade
         % overall passing fell 0.31%,
         % passing math fell 0.087%
         % passing reading fell 0.29%  
    ````
      Top Five Schools before

     ![Top](https://github.com/11nithin/School_District_Analysis./blob/main/Resources/Top_five_schools%20before.PNG)

      Top Five Schools after

     ![Top](https://github.com/11nithin/School_District_Analysis./blob/main/Resources/Top_five_schools.PNG)

      Bottom Five Schools before
   ![Bottom](https://github.com/11nithin/School_District_Analysis./blob/main/Resources/Bottom_five_schools%20before.PNG)

      Bottom Five Schools
   ![Bottom](https://github.com/11nithin/School_District_Analysis./blob/main/Resources/Bottom_five_schools.PNG)

      Since no other data are changed the bottom five remained same. 


- Impact of ninth grade score on Math and Reading scores by grade

      The only data that changed here is the Thomas High School 9th grade data to NaN. All the other data remained same.

   ![before_after](https://github.com/11nithin/School_District_Analysis./blob/main/Resources/Average%20Math%20and%20Reading%20score%20by%20grade%20before%20and%20after%20.PNG)

- Impact of Scores by school spending


   Since 9th grade data(461) is replaced by NaN it will impact Thomas high school spending per student. Average scores in each spending range havent made any changes from the original data. It doesnt make sense to keep Thomas high school in the $630-644 range since 9th grade scores are missing for Thomas high school. But in a bigger picuture thomas high school 9th grade score made no impact on the school spending.

![spending](https://github.com/11nithin/School_District_Analysis./blob/main/Resources/Spending%20range%20before%20and%20after.PNG)
--------------------------------------------------------------------
- Impact of Scores by school size

      9th grade scores made no impact on the average scores and even after removing the 9 grade students data. school size for Thomas High school remain in the 1000-2000 range. 

   ![size](https://github.com/11nithin/School_District_Analysis./blob/main/Resources/Score%20by%20sxhool%20size.PNG)

--------------------------------------------------------------------
- Impact of Scores by school type

      Thomas high school is charter type school and average scores for charter is not effected by the 9th grade data.

   ![type](https://github.com/11nithin/School_District_Analysis./blob/main/Resources/school%20type.PNG)

--------------------------------------------------------------------
## Summary
- In school summary % Overall passing for Thomas High School fell 0.31%. Eventhough this made no changes to the ranking. Slight variation can impact the ranking of the school. If we look at the first five we can see some schools only have 0.1% difference in there overall passing.
- In district summary % overall passing percentage changed by 0.1% 
- Eventhough school spending average score didnt change. Thomas high school's spending per student will change. 
- No noticebale impact Scores by school size and school type

