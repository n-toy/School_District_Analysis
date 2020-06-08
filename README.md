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
