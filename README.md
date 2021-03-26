# excel-challenge
Organization and analysis of a database of 4,000 past Kickstarter projects for useful trends. 

See attached excel spreadsheet for raw data, pivot tables, and statistical analysis.

Using excel, my goal is to identify trends in kickstarter data which would better inform an individual on what type of campaigns tend to be successful (reaching their monetary goal within a set timeframe). 

From our sample of 4,000 Kickstarter campaigns, we can see that Theater, Music, and Film/Video tend to be the most successful categories, in terms of reaching their monetary goal in a set time. Campaign type plays a key role in how successful it will be.

![image](https://user-images.githubusercontent.com/12026338/112700172-e8964200-8e63-11eb-8c99-44dfa9e86035.png)

If we look at the sub-categories of the campaigns, we can see that there are a few stand out options for successful campaigns:

![image](https://user-images.githubusercontent.com/12026338/112700190-f055e680-8e63-11eb-8dad-38f7fd8727ff.png)

Plays are far more successful than other sub-categories on the platform, making Kickstarter a useful funding option for theaters. Outside of categorization, the initial monetary ask of a campaign plays into its success:

![image](https://user-images.githubusercontent.com/12026338/112700767-3f504b80-8e65-11eb-9d31-130922306587.png)

The more money a campaign asks for, the less likely they are to succeed in raising the funds. Using our lines of best fit, we can estimate a goal which would optimize for the greatest amount of funds that does not increase our risk of failure. Based on the data, asking for less than $30,000 improves the odds of a campaign being successful. If we wish to include canceled campaigns in this, an ask of 20,000 or less would be a useful limiting factor. This coincides with our percentage of success being 50% at this point. Thus, any goal asking for less than this amount has more than a 50% chance of success. 

Using statistical analysis on the number of backers for successful campaigns allows us to see how important the number of backers are for success:

![image](https://user-images.githubusercontent.com/12026338/112700218-019ef300-8e64-11eb-9e6c-05e66406b493.png)

![image](https://user-images.githubusercontent.com/12026338/112700221-0499e380-8e64-11eb-9157-a8c461779ba4.png)

The average amount of backers for the failed campaigns was much less than that of the successful campaigns, showing the importance of the volume of donors in the success of the campaign. 
	In terms of the center for successful and failing campaigns, median summarizes the data more accurately due to the high level of variance in the number of backers. While the failed campaign graph may not appear to have a center near 4, many campaigns that fail receive 0 backers, and this more accurately portrays the key issue that these failed campaigns have, which is a lack of backers.
	The variability in the number of backers for successful and unsuccessful campaigns seems to suggest an exponential growth with campaigns that are successful. The more backers a campaign has, the faster it spreads to other potential backers, thus creating high variability in the successful campaigns. Unsuccessful campaigns tend to be low in variability as they never reach a point which allows them to exponentially grow. 

<h2>Possible Errors and Limitations</h2>

While category may be useful for identifying successful trends in the data, it is possible some other factors may be causing the categories of Theater, Music, and Film/Video to be successful over others. The data collected does not consider advertisement of the campaigns on other social media sites or through local media. 
With more time, it would be useful to look at why some campaigns that are successful have a much higher backer count, or why some campaigns are able to go much over their initial goal. We might see that campaigns with a high backer count have a lower average donation, and a table / graph analyzing this would be useful for understanding what makes a Kickstarter successful. 

With regards to the notion of exponential growth of backers of a campaign, it would be interesting to pin down a critical point for which if a campaign reaches said number of backers, the growth of the campaign will be sufficient to guarantee a successful campaign. 
