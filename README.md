## School District Analysis
# Purpose
The purpose of this analysis was to compare schools and their scores in math and reading when taking in certain factors such as the budget, size, and district of the school. From this we were able to summarize the overall passing percentages of these schools based up said factors. The purpose of changing Thomas High School's 9th grade scores was to see how changing certain datapoints affect the whole district's data and in particular the statistics of Thomas High School's passing rate and scores in both reading and math.
# Results 
The results of Thomas High school was deeply affected when changing the 9th grade scores to NaN. We see in the image after changing the results the total student count is changed due to the fact that a whole grade at a school score's are not being accounted for. 
![Thomas NaN](https://github.com/mckjack/School_District_Analysis/blob/main/Thomas%20NAN.png)
Another thing that the replacement of the 9th grade scores did was change the Thomas High School passing rate drastically. Taking away a whole grade scores took Thomas from being a high performing school in the top 5 to a poor performing school in the bottom 5. 
![Thomas before Adjusted](https://github.com/mckjack/School_District_Analysis/blob/main/Thomas%20Before%20Adjusted.png)
Here we see they have a overall passing rate of 65% which is not good at all. However we were able to get rid of these NaN values by filtering the school data of Thomas High School to just the 10th to 12th graders. After this we see the passing rate increase. 
![Thomas after adjusted](https://github.com/mckjack/School_District_Analysis/blob/main/Thomas%20after%20adjusted.png)
Some other key takeaways the ninth graders score being adjusted did was,
- Affect the math and reading scores of the whole school by dropping the percentage of the passing rate in these two respective subjects.
- The school spending was $630-$644 per student meaning that it was more expensive per student when the 9th grade scores were adjusted.
- The school size stayed the same in the 1000-1999 range considering there was only 461 students in grade 9.
- The school type score changed roughly for the Charter type considering a whole grade was removed from one school in their district.
# Summary 
Overall the four changes that had an effect on the school district analysis were the scores for Thomas High Schools in both math and reading being negatively affected and the percentage of students passing those subjects dropped severely. A result of this caused the overall passing percentage of Thomas High School to drop taking them out of the top 5 performing schools. Another change would be the district scores for math and reading going down as well slightly. This change was not too big but affected the district due to change in scores for all ninth graders at Thomas High School. Lastly, the size of Thomas High School changed due to the fact that grade 9 was the highest student count causing such a drastic change in their scores. 
