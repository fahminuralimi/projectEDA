# projectEDA
How to create some project Exploratory Data Analysis

Values:
-Able to overcome and check missing values
-Able to Duplicate value check and handling
-Able to Statistical Summaries of Columns
-Able to analyze univariate
-Able to analyize bivariate

Problem Conclusion:
1.The data does not contain major issues. There are only some NULL values and duplicated rows. We've handled them accordingly.
2.Overall, the minimum and maximum values make sense for each column.
3.Most of the columns with numerical values are somewhat symmetric.
4.From the barplot we can see outlier in recommendatiion_strength column. But it makes sense, because the min and max value are 1 and 5, the outlier is at "1", and it's possible.
5.From barcharts of admit_status and research_exp column, We can say that, applicants with research experience is more likely admitted.
6.From correlation heatmap: We can see that gre_score is correlated with gpa and toefl score. The relation is directly proportional. choose either of them for modelling.
