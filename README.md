
## Deliverable 6 Written Analysis
While doing the analysis I discovered that the .describe() function can be extremely useful. If applied correctly you can get 
the count, mean, standard deviation, minimum value, maximum value, and the percentiles. Another discovery 
I found is that Wagner, Dixon, and Sullivan all have weaknesses in either math or reading. None of the three schools dominated in 
both categories so they all could inmprove their test scores.
One thing that caught my eye was how easily the code reads. For example 
#student_df.loc[:, ["math_score", "school_type", "reading_score"]].groupby(["school_type"]).mean()
Here we are locating the data, saying we want the mean of the math and reading scores which will be displayed in columns for both school 
types(Charter and Public) which is what they were grouped by.
Another discovery was the str.replace function. As used in #(student_df['grade'] = student_df['grade'].str.replace('th', '')
We are going into the data frame, grabbing the grades and replacing all the "th" strings with "". Empty quotes meaning empty strings 
so all you will see is the 
number. An analysis point that is worth considering in my opinion would be descriptive statistics of each county. 
Another point that I see as being worth looking at would be max scores for charter and public schools. 

