# School_District_Analysis
## Project Overview
The ninth-grade students  at Thomas High School have been cheating. While administration does not know the full extent of this academic dishonesty, they want to uphold the standards of state testing and have asked us to provide analysis on students grades. We have been asked to:
* Replace the ninth-grade math and reading scores from Thomas High School
* Keep all other data associated with the ninth-grade students and Thomas High School intact.

## Resources
	Data Source: schools_complete.csv, students_complete.csv
	Software: Python 3.8.3, Jupyter Notebooks

## Recreate the district and school summary DataFrames
* How is the district summary affected?
### Original District Summary
![Original District Summary](https://github.com/n-toy/School_District_Analysis/blob/master/Resources/District_summary_original.jpg)

### Fixed District Summary
![Fixed District Summary](https://github.com/n-toy/School_District_Analysis/blob/master/Resources/District_summary_fixed.jpg)

There is very little impact to the district summary. The percentage of student passing math, reading, and overall decreases by 1 point after nullifying Thomas High School's ninth-grade student's scores

* How is the school summary affected?
### Original School Summary
![Original School Summary](https://github.com/n-toy/School_District_Analysis/blob/master/Resources/school_summary_original.jpg)

### Fixed School Summary
![Fixed School Summary](https://github.com/n-toy/School_District_Analysis/blob/master/Resources/school_summary_fixed.jpg)

The percentage of students passing math and reading at Thomas High School drops dramatically. Originally Thomas High School some of the highest percentage of excelling students with a 90.1% overall passing percentage

Thomas High School now has a 65.1% overall passing percentage which is a reduction of 25%. Thomas High School's passing math and passing reading percentages also suffer similar reductions of over 20%.

## Recalculate the high- and low-performing schools
* how does replacing the ninth graders' math and reading scores affect Thomas High School's performance, relative to other schools?
  * Originally Thomas High School was the 2nd highest school (90.9% overall passing) in terms of overall passing percentage. After replacing the ninth graders' scores they are now the 8th school (65.1% overall passing) when it comes to overall passing percentage


## Recalculate the scores by grade, scores by school spending, scores by school size, and scores by school type
* how does replacing the ninth-grade scores affect the following? 
  * Math and Reading Scores by Grade
    * Originally the ninth-graders were tied for the second highest average math score. Now they are last with NaN (counted as a zero)
	* The same for reading as above. They had the 7th highest average reading score, and now they are last with NaN (counted as zero)
  * Scores by School Spending
	* School spending falls into the buckets of <$528, $585-629, $630-644, and $645-675
	* Thomas High School spends $630-644 per student
	  * Schools who spent $630-644 originally had a 63% overall passing percentage, and a 73% and 84% percentage for passing math and reading respectively
	  * Now Schools who spent $630-644 have a 56% overall passing percentage, and a 67% and 77% percentage for passing math and reading respectively
	  
  * Scores by School Size
	* School Size falls into the buckets of Small(<1000), Medium(1000-2000), and Large (2000-5000)
	* Thomas High School is a medium sized school with 1,635 students
	  * Medium sized schools originally had an 91% overall passing percentage, and a 94% and 97% percentage for passing math and reading respectively
	  * Medium sized schools now have an 85% overall passing percentage, and a 88% and 91% percentage for passing math and reading respectively
  *Scores by School Type
	* School types fall into the buckets of Charter and District
	* Thomas High School is a Charter School
	  * Charter schools originally had a 90% overall passing percentage, and a 94% and 97% percentage for passing math and reading respectively
	  * Charter schools now have an 87% overall passing percentage, and a 90% and 93% percentage for passing math and reading respectively




















