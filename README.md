# bikesharing
[link to dashboard](https://public.tableau.com/views/TimeandGenderCitiBikeAnalysis/Story1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
### Overview
This analysis was done to examine the trends of New York CitiBikes to determine how effective it will be in Des Moines, Iowa. First, a breakdown of customers vs. subscribers was done in conjunction with a breakdwon of gender. Second, the times of trips were evaluated and in particular, were looked at based on gender. Finally, the length of checkout times was analyzed, again further analyzed by gender.

### Results
The first dashboard created analyzed both the difference between customers and subscribers of the New York Citi Bike, in addition to users' gender. This is shown below:

<p align="center">
<img src="https://github.com/bchillman/bikesharing/blob/main/Images/Dashboard1-Customers_and_Gender.png" width="408" height="420">
</p>
We can see on the bottom two bar charts that there are a majority of both males and subscribers when it comes to number of bikes checked out, and looking at the top chart, we can see that there is a slight difference in when subscribers use Citi Bikes and when average customers use them. Subscribers tend to use these bikes more during the week, whereas non-subscribers tend to use these bikes more on the weekend. This makes sense, as someone using these bikes to go to work might see more value in paying for a subscription than someone who just occasionally wants to use them on the weekend.  
<br> <br>
The second dashboard allows us to take a closer look at the gender breakdown of when Citi Bikes are used. This can be seen below:
<p align="center">
<img src="https://github.com/bchillman/bikesharing/blob/main/Images/Dashboard2-Trip_Times_and_Gender.png" width="408" height="420">
</p>
Here we can see that while there is expectedly more trips taken by men at each time (there is a higher percentage of trips taken by men overall), the general pattern seems to stay consistent across genders. Thus, there does not seem to be any times where there is a significantly higher percentage of rides taken by one gender, once accounting for the difference in total rides.
<br> <br>
Finally, the third dashboard allows us to look at the checkout times taken for bikes. This lets us see how long each bike is used. This dashboard can be seen below:
<p align="center">
<img src="https://github.com/bchillman/bikesharing/blob/main/Images/Dashboard3-Checkout_Times.png" width="408" height="420">
</p>
In this dashboard we can first see on the top graph that most bikes are checked out for less than 30 minutes and almost no bikes are checked out for more than an hour. In our second graph (which is similar, but broken down by gender), we can see that the peak is sharper for men than women or unknown genders. This indicates that men have a shorter checkout time than both of these other groups, which could help estimate future availability of bikes in our Des Moines version.

### Analysis
These results allow us to gain some major insight into possible business strategies for our Des Moines version of the Citi Bike. First, when looking at the use times of subscribers and customers, we can clearly see that there are two types of riders. Riders that use bikes to ride to work daily (or on some days) typically already subscribe to Citi Bike; these users clearly already see value in subscribing. Other riders, however, tend to use the bikes more on weekends, and one potential strategy would be to offer a seperate subscription that, while cheaper, can only be used on these weekends. Another insight is that men tend to use these bikes more than women, when starting our Des Moines version, we should lean our advertising and marketing strategies more toward male markets to gain a foothold in the region. Finally, we can use the checkout time graphs to create an estimated checkout time, so that if all bikes are being used, a potential customer can know how long it is likely to take for a new bike to become available. This allows the user to make an informed choice about whether they should wait for that next bike or find another way of transportation. Some more visualizations to help aid this would look at the location of where bikes are checked in and out, and how that location changes over time. This would allow us to find the right number of bikes to place in specific locations, as well as aid our estimated time functionality. Another visualization that could be helpful in the future would be to periodically look at bikeIds compared to usage. Bikes that have significantly lower usage than others may be broken or need repair, and this vizualiztion would help us identify them.
