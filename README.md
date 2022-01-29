# School_District_Analysis

## Overview of Project
&nbsp;&nbsp;&nbsp;The school board noticed evidence of academic dishonesty concerning reading and math scores at Thomas High School.  The alteration were specific to the 9th grade class in the file "students_complete.csv".  In order to keep to state-testing standards, the reading and math scores were ordered to be replaced with "NaN" but to keep the rest of the data intact. After replacing the requested data, the analysis on the school district data was repeated.
## Resources
&nbsp;&nbsp;&nbsp;* Data Source: schools_complete.csv, students_complete.csv
<br />
&nbsp;&nbsp;&nbsp;* Software: Python 3.9.7 64-bit, Jupyter Notebook 6.4.5

### Results
* The District Summary was affected in this way:

&nbsp;&nbsp;&nbsp;Changing the Thomas High School 9th grader's reading and math scores to "NaN" had a small but noticeable impact.  Here is a before and after screenshot of the district summary.  The district realized a slight decrease in the average math score, % passing reading, % passing math, and the % passing overall categories.
<br />

![uncleandistrict](https://github.com/LaszloCravensworth/School_District_Analysis/blob/main/Pics/Preclean%20District%20Summary.png)

![cleandistrict](https://github.com/LaszloCravensworth/School_District_Analysis/blob/main/Pics/Postclean%20District%20Summary.png)

* The school summary was affected in this way:

&nbsp;&nbsp;&nbsp; All of the data for Thomas High School was affected by these changes.  Cleaning this data revealed a much more accurate picture of Thomas High School. The school now ranks higher amongst the other schools in the district.
<br />

![uncleanschool](https://github.com/LaszloCravensworth/School_District_Analysis/blob/main/Pics/preclean_school_summary.png)

![cleanschool](https://github.com/LaszloCravensworth/School_District_Analysis/blob/main/Pics/postclean_school_summary.png)

* This is how Thomas High School's performance, relative to the other schools, was affected by replacing the ninth graders' math and reading scores:

&nbsp;&nbsp;&nbsp; Thomas High School saw a massive increase amongst its peers. It went from having an average performance to outperforming almost every other school.

* Replacing ninth-grade scores affect the following:

    * Math and reading scores by grade
    <br />
    before and after cleaning math scores:
    <br />
    <p float="left">
  <img src="https://github.com/LaszloCravensworth/School_District_Analysis/blob/main/Pics/preclean%20math%20scores.png" width="300" />
  <img src="https://github.com/LaszloCravensworth/School_District_Analysis/blob/main/Pics/clean_math_scores.png" width="300" /> 
</p>
    <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;before and after cleaning reading scores:
    <br />
    <br />
    <p float="left">
  <img src="https://github.com/LaszloCravensworth/School_District_Analysis/blob/main/Pics/preclean_reading_scores.png" width="300" />
  <img src="https://github.com/LaszloCravensworth/School_District_Analysis/blob/main/Pics/post_clean_reading_scores.png" width="300" /> 
</p>
    <br />
    
   * Scores by school spending
    ![scorespending](https://github.com/LaszloCravensworth/School_District_Analysis/blob/main/Pics/Score%20by%20school%20spending.png)
   * Scores by school size
    ![scoresize](https://github.com/LaszloCravensworth/School_District_Analysis/blob/main/Pics/Score%20by%20school%20size.png)
   * Scores by school type
   ![scoretype](https://github.com/LaszloCravensworth/School_District_Analysis/blob/main/Pics/Score%20by%20school%20type.png)
### Summary
&nbsp;&nbsp;&nbsp;Cleaning the 9th grade reading and math scores had a minor but noticable impact on the overall performance of Thomas High School. There was an increase in the percentage of students who passed reading, math, and overall. There was also an increase in performance amongst its peers.
