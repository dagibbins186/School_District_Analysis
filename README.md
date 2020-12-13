# Project Overview
\
This analysis examines 15 schools' and 39,170 students' reading and math performance. It considers the schools' type, size and budget as well as the students' grade levels and genders. 
# Executive Summary
\
The evaluation ranked students' overall performance by the top 5 schools. Initially, Cabrera High School (1) and Thomas High School (2) demonstrated the top marks for both reading and math. However, evidence of academic dishonesty came to light for Thomas High School's ninth graders. As a result, a second analysis removed this problematic data, and replaced the reading and math scores with "not a number value" (NaN). Griffin High School assumed the second-place-ranking afterward. The cheating scandel nominally affected the district's performance. Reading, math, and overall scores dropped about 1% to 74%, 86% and 64% respectively when the Thomas High School-9th grade-scores were excluded.
# Results
\
**Overall Performance by Schools**
\
The top five high schools for overall performance were:
\
!["Top_5_Schools_OverallScores_ExcludeTH9th_withCode"](https://github.com/dagibbins186/School_District_Analysis/blob/main/Images/Top_5_Schools_OverallScores_ExcludeTH9th_withCode.png)
\
Griffin High School moved into second place after the scores of Thomas High School's ninth graders were removed from the analysis. Wright High School shifted into the fifth ranking. Thomas High School's upper classman did not perform as well as Wright High School's upper classman. For example, Wright High School's 11th graders earned 83.84% in math. Its 12th graders obtained a 84.07% in reading. Comparatively, Thomas High School's 11th graders received math scores of 83.50%. It's 12th graders posted reading scores of 83.83%. While the score-differences beween the high schools appeared marginal, it effectively pushed Thomas High School out of the top-five-schools-list.
\
\
**District Performance with and without Thomas High School**
The district's overall performance look similar before and after Thomas High School's data alterations.
\
\
*Before:*
\
!["School_District_Analysis/blob/main/Images/District_Summary_All"](https://github.com/dagibbins186/School_District_Analysis/blob/main/Images/District_Summary_All.png)
\
*After:*
\
!["School_District_Analysis/blob/main/Images/District_Summary_ExcludeTH9th"](https://github.com/dagibbins186/School_District_Analysis/blob/main/Images/District_Summary_ExcludeTH9th.png)
\
\
Overall performance dropped about 1% across 3 indicators of achievement: students passing math, reading and overall. These scores decreased to 74%, 86% and 64% respectively.
\
**Other Comparisions** 
\
Thomas High School is a charter school with about 1,635 students and a budget of $1,043,130. Its % of students passing math (93.27%), reading (97.31%) and overall marks (90.95%) dropped 26.36%, 30.4% and 25.87% to 66.91%, 69.66%, 65.08%. Even though only 461 student scores switched to NaN, it greatly affected Thomas High School's profile.
\
Binning schools into sizes of small (<1,000 students), medium (1,000-2,000 students) and large (2,000-5,000) students, Thomas High School falls into the medium category. Without its 9th graders scores, the performance of 'medium' size schools decreased dramatically. 
\
*Before*
\
!["SchoolSize_Scores_All"](https://github.com/dagibbins186/School_District_Analysis/blob/main/Images/SchoolSize_Scores_All.png)
\
*After*
\
!["SchoolSize_Scores_Exclude_TH9th"](https://github.com/dagibbins186/School_District_Analysis/blob/main/Images/SchoolSize_Scores_Exclude_TH9th.png)
\
\
The initial analysis showed 94% of students passing math, 97% of students passing reading and 91% of students passing overall. In the edited analysis, only 88% of students passed math, 91% of students passed reading and 85% of students passed overall among the medium schools.
\
Similarly, performance among charter schools became worse after excluding the Thomas High School 9th graders. 
\
*Before*
\
IMAGE
\
*After*
\
Image
\
In both scenarios, charter schools do better than the district schools. The average math and average reading scores also do not change. However, the % of students passing in math, reading and overall goes down 3-4 percentage points among charter schools. 
