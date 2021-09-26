# School_District_Analysis.

## Overview of the school district analysis

The school board has identified an evidence of academic dishonesty on students_complete.csv file; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. To find the full extent of the academic dishonesty, the math and reading scores for Thomas High School replaced with NaNs while keeping the rest of the data intact and the School district analysis are conducted again to describe how these changes afffected the overall analysis. 


## Results
### District summary
Replacing Thomas high school 9th grade scores by NaN is making only very less impact on district summary. The % overall passing fell 0.1% , % passing Math fell 0.2 % and % passing reading fell .3%. 
#### District summary before
![before](https://github.com/11nithin/School_District_Analysis./blob/main/Resources/District_summary_before.PNG)
#### District summary after
![after](https://github.com/11nithin/School_District_Analysis./blob/main/Resources/District_summary_after.PNG)

### School Summary and Schools perfomance
Removing 9th grade data from Thomas high school made very less impact on school summary.  
````
Thomas High school summary change after removing 9th grade
% overall passing fell 0.31%,
% passing math fell 0.087%
% passing reading fell 0.29%  
````
#### Top Five Schools before
![Top](https://github.com/11nithin/School_District_Analysis./blob/main/Resources/Top_five_schools%20before.PNG)

#### Top Five Schools after
![Top](https://github.com/11nithin/School_District_Analysis./blob/main/Resources/Top_five_schools.PNG)

Even after removing the 9th grade scores from the summary, school ranking remained same. Eventhough the % overall passing variation is very less, it can make an impact on the ranking. The first and 5th ranked %overall passing differnece is 0.71%. In this case eventhough Thomas High school % overall passing fell 0.31% it made no differnce in the ranking.

#### Bottom Five Schools before
![Bottom](https://github.com/11nithin/School_District_Analysis./blob/main/Resources/Bottom_five_schools%20before.PNG)

#### Bottom Five Schools
![Bottom](https://github.com/11nithin/School_District_Analysis./blob/main/Resources/Bottom_five_schools.PNG)

Since no other data are changed the bottom five remained same. 


### Impact of ninth grade score on Math and Reading scores by grade
![before_after](https://github.com/11nithin/School_District_Analysis./blob/main/Resources/Average%20Math%20and%20Reading%20score%20by%20grade%20before%20and%20after%20.PNG)
The only data that changed here is the Thomas High School 9th grade data to NaN. All the other data remained same.

