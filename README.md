# pandas-challenge

## District Summary
Applying calculation across dataset to summary schools combined.
Creating variable to count number of passed students for match, reading, and combined was solved using loc and conditions to collect student passing.

## School Summary
Used groupby to group data by school and needed columns.
In order to calculate student pass/fail for a test, I created bins ranges to determine pass (1) or fail (0) and use the data to calculate pass percentages.

Once lists of need column by school was created.  I merged the together to create dataframe to summarize and display.

## Top/Bottom Perfming Schools
I reordered data using 'sort_value' for repective requests and displayed top/bottom five using 'head()/tail()''

## Math/Reading Scores by Grade
I reloaded CSV data because I changed original data frame in previous work and wanted to start with fresh data.
Filtered data by grade and applied necessary calculations into series.  When I calculated two of these lists, there result needed a name(used rename) in order to merge in the next stop.
Merged the data frames and displayed.

## Scores by various ranges
I appended original data with "Pass/Fail" columns for each test evaluation to be used for %Passing fields.  In addition, added "Budget per Student" column for the first Scores Summary.
Next, I reviewed range for requested summary type (Student Budget per School,...) and created bin ranges.
Filtered data by grade and applied necessary calculations into series.  When I calculated two of these lists, there result needed a name(used rename) in order to merge in the next stop.
Merged the data frames and displayed.

QUESTION
For the last series Scores by ranges.  The code was very repetitive and I thought I might be able to create a function, but didn't get it to work.