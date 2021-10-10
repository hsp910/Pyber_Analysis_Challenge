# Pyber Analysis Challenge

## Overview and Background
Now this challenge is based on analyzing the data of a fake ride sharing company named Pyber. From the data we are given we can see how many drivers are in every city, the amount of money made from each and every ride, and the dates of each individual ride made. The data also breaks down cities by 3 different types: urban, suburban, and rural. Based on this data we are meant to create a summary of the data using Python and then show the differences for Pyber between each city type. Now while some assumption can be made about what "type" of city would make the most money we must also consider how we can possibly bring up the lower preforming types, or to instead maximize the amount of money being made from the most profitable types of city. From this data I will also provide 3 proposals for expanding each type of area's long term userbase and profit.

## Results

### Data Summary
Now from the data I created a summary of the differences between each type of city using the Pandas package in Python.

![Data summary created using dataframes](https://i.imgur.com/MLiPFZT.png)

From this data summary a few different things can easily be established. The primary concern of this data summary is that it is clear that urban cities make up the largest user base, and profit base, of Pyber's market. Urban cities make twice as much as suburban areas and rural areas make roughly 1/10th of the total amount that urban areas do. It should also be noted that cost per ride goes up with the smaller populations with rural rides costing roughly $10 more than the average urban one. We can also see that because of the high population of drivers in urban areas compared to rural areas that they actually make much less per driver. Urban drivers making less than 10% of what rural drivers make is an incredibly large gap on par with the difference in amount of fares collected by each type of area.

### Visualizing the Data

![This is a chart made to visualize the differences between city types](https://i.imgur.com/oVEKCfY.png)

This chart was made to help visualize the data from the summary shown earlier. It also shows how much total amount of fares collected changed over the weeks between January and April of 2019. We can see that the summary data is correct with each type of area falling into the same place as prior for weekly earnings. The spikes and valleys on the chart tend to happen around the same time for each type of area. This may be in part due to how people travel around certain times of years such as holidays. Urban and Suburban areas have roughly the same difference in their peak and bottoms at roughly a $1000 difference in weekly earnings through out the chart. Rural earnings seem to generally be the most volatile with almost no business some weeks and about $500 collected in one week for it's peak.

## Summary and Proposals

### Summary
Pyber clearly has a large userbase and most of it's profit share from urban areas, and roughly half of what the urban centers make in the suburban areas. The question must be made on how they wish to grow. They could focus primarily on their largets success, urban areas, and grow that userbase the most. They could try to grow the suburban base to make almost as much as the urban base. Finally they could try to bring up the rural base to a possibly higher level. Now I believe that growing the urban or suburban bases is the most reasonable options as they tend to be the largest users of ride sharing apps I will also include a proposal for what to do about growing the rural base.

### Urban Proposal
Now the most obvious proposal here would be to try to grow the userbase of the urban areas. This is due to the fact that we already have far too many drivers working these areas, to the point the average one only makes 67 cents. This means that if we can expand our current users we should have the drivers to back up this expansion to a much larger audience. We could achieve this through more aggressive targeted advertisements done in urban areas and cities, or by web marketing towards users that are living in those same areas. Pyber must also make certain that the number of drivers available for this expansion stays this way. It is unclear if the driver count in the data provided includes all active drivers or simply however many drivers are registered in those areas. We need a reliable base of drivers to expand our userbase in urban cities, and if necessary we may need to also provide more incentives to drives to get them coming back.

### Suburban Proposal
Now the suburban areas may be the trickiest areas to consider for improving the market within. Since it's directly in the middle there are many tactics that can be taken to try to push growth in those userbases. I believe one simple one would be offering some small discounts to suburban rides, or possibly giving drivers in these areas a small bonus for driving these less pursued areas. Suburban areas tend to have less business than urban areas since many people in suburbia have their own vehicles to drive to any locations they might need. Offering discounts, especially targeted at those that might be trying to go out to bars or breweries, could be an easy way to get some new customers, and hopefully from there more repeat users.

### Rural Prorposal
Rural areas having the least profit, smallest userbase, and smallest driver base is likely unsurprising for many. Rural areas largely are uninhabitable for many people without some sort of access to a vehicle. I believe that there is one userbase that could be expanded on to bring more life into these markets. Many senior citizens that live alone in these areas may not be able to drive to appointments anymore. By advertising to the elderly in this area Pyber may be able to create a large returning userbase in these senior citizens that need to get to places like doctor's appointments or social gatherings farther away from where they live. Pyber could even reach out to some local county offices to see if they have their own senior shuttle programs to see which are possibly looking for more help from companies like Pyber. The only issue with this would be the reality that we would need a very consistent driver base that is available during the day for such appointments. It would be hard to have seniors use an app like this for them to be unable to get a ride due to a lack of drivers.
