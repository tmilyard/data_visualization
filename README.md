Summary

The visualization I created used Prosper loan data which is a peer to peer loan marketplace.  The main data points I focused on are Prosper Loan Rating, which is a relative measure of risk on the loan, as well as, the loan applicant credit score.  The number of loans across Prosper Loan Rating is also displayed and all of the data is from the years 2009-2014.

Design

The main topic or question I wanted to explore in this data is:  Have lenders, in this case, individual lenders, “learned their lesson” from the financial crisis of 2008?  Meaning, in aggregate are lenders requiring higher credit scores for loans to have the best risk ratings or will acceptable levels of credit scores slip over time.  The implication being that lenders are always competing for loans.  When lenders begin relaxing the bar or requirements for who has access to loans, there is an increased systemic problem within financial markets.  A large part of the great recession was the fact that sub-prime borrowers were getting access to loans they shouldn’t have otherwise gotten.  Now that we’ve seen what that can do over time, I wanted to see how quickly, if at all, average credit scores drop for each prosper loan rating.  

I saw two main takeaways in the data: 

1)	As expected, the better the loan rating, the better the average credit score.   I was pleased to see that this relationship was fairly predictable and constant over every time series. 
2)	 In the final 18 months of the animation, the average credit score for many loan ratings dropped. I believe this to potentially be the start of a new cycle of lax lending standards as the economy has recovered and the impacts of the great recession fades.  

I brought down all of the available Prosper loan data into Excel and began reviewing the data fields for which ones may tell the story of changing standards in lending practices.  I also wanted to choose data points which were easily understandable or common in their own right so that the viewer would need less context.  

I made the decision to average loan credit scores against loan ratings which yielded a positive relationship.  Therefore to best show this I decided on adding a line to my chart showing these averages.  The left Y axis was assigned the values of credit score while the x-axis was given categorical loan rating information.  Since average can only tell you so much and doesn’t show the range of values, I added “average + 1 Standard Deviation” and “average – 1 standard deviation” to give a sense of where approximately 65% of loans fell.  These were two additional line graphs added to the chart.  Finally I added another dimension of data, the number of loans per loan rating.  I made this data set a bar chart to be in contrast to the line graphs and added a second (right) Y-axis to give scale to the number of loans.  For the time series, I decided that quarterly snapshots would yield too many time periods for the chart while yearly would be too few.  Therefore I chose 6 month windows. 

Feedback

I shared my chart with members of the Udacity community as well as several of my work colleagues.  While the feedback was very positive, I was also provided many useful suggestions for improvement.  Here is a sampling of those suggested improvements: 

•	Consider using your main finding as the title to help drive the message to the audience;

•	You may want to explain which shape is associated with which vertical axis as you definitely don't want to leave the reader guessing. 

•	Increase the size of the time interval legend for easier reading

•	The scale on the right side changes which makes it more difficult to compare or identify trends over time. 

•	Consider adding a short paragraph to explain your main conclusion, this can help the reader to understand the visualization.

•	It took me a bit to identify which vertical axis went with which data (bars/lines)—maybe you can do something to visually tie them together.  Even though the bars are in the background, for some reason my instinct is that those would be tied to the left axis

•	Since the # of loans axis is changing with each time period, it is difficult to make comparisons across time and correlations between # loans and Std dev/avg credit score are lost. I think it would be better to keep the axis set, so those changes are obvious.

•	It would be nice to create a button or something to click on to start the animation. Otherwise, the chart starts to dancing when I am not ready to read it

•	I think the way you show your standard deviation is odd. Maybe you should create error bar or some shadow instead of two lines for standard deviation

•	The year label could be shown in a more obvious way, e.g. larger size or in the middle of svg

•	I had a hard time to figure out which y axis is for the bar, which one is for the line

The most obvious theme in the feedback was difficulties created by allowing the secondary Y axis to change.  I decided to have a constant scale on that axis as well as add that series to the legend so that it would be easier to know what what was being measured.  I also changed the backgruond color of the buttons to make them easier to see/read.  I debated adding more notes around what I saw or was hoping to prove in the visualization, but decided against it because I felt it could bias the viewer into seeing what I wanted them to see. 

Resources

•	http://dimplejs.org/examples_index.html

•	https://www.sitepoint.com/create-data-visualizations-javascript-dimple-d3/

•	http://christopheviau.com/d3list/gallery.html

•	Nanodegree Course Materials


CHANGES AFTER FIRST PROJECT SUBMISSTION AND REJECTION: 

Make title more informative – even a question?
Add sentence explaining source of data
Perhaps remove standard deviation
Fix y axis to start at zero
Year on x axis 
Helps number of loans too
Type of rating be the series
Number Of instead of #
Up size of time period label
Explain what 1H and 2H mean (if keeping time series same)
Add paragraph to graphic
Update comments in code per suggestions
Try out line graph for number of sales

