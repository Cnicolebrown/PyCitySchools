# PyCitySchools
python school analysis

**Overview of School District Analysis**

The primary purpose of this analysis was to recalculate the math and reading scores, accounting for the academic disonhesty that occured in Thomas High School. The analysis compared the math and reading scores of various high schools ranging from different types. Some important key components of the analysis was the examination of scores, school type, budget, and size of school. This analysis should be used to aide in the distribution of future funding to schools based on need and performance.

**Results of Analysis**

*Effects on District Summary*
  
 After rerunning the district summary with new edits, no drastic changes were observed. 
 When looking at the top five schools, they remained the same in both the originial and new analysis reports. 

# Sort and show top five schools (original)

top_schools = per_school_summary_df.sort_values(["% Overall Passing"], ascending=False)
                                                 
top_schools.head()    

# Sort and show top five schools.(new)
top_schools = per_school_summary_df.sort_values(["% Overall Passing"], ascending=False)
top_schools.head()
