# Analyzing Trends in Successful Kickstarter Campaigns
##Conducting quantitavive descriptive analysis a broad swathe of Kickstarter data to extract trends and commonalities present in successful Kickstarter campaigns

There are a number of trends visible within Kickstarter campaigns that influence success. Principally, the time of year appears to possess a high degree of correlation on the success or failure of a Theater-related kickstarter.

###Launch Date Trends
![SuccessByLaunchDate](https://github.com/Patchwork-Chimera/KickstarterAnalysis/blob/main/Outcomes%20by%20Launch%20Date.png)

Visible in the graph above, certain months appear to be highly favorable (and others unfavorable) for the success of a Theater campaign. The most favorable month to launch appears to be May, during which 66.8% of kickstarters attained their funding goal. This is also the month seeing the largest number of Theater kickstarters launched, at a total of 166 campaigns. 

Worth considering is that these traits may be due to students with an interest in theater who have either graduated, or are otherwise beginning a break period, launching their campaigns as school ends. This must be considered as a potential data-skew, as larger portions of kickstarters are likely started earnestly by those with newfound time and with requisite competence to appeal to potential donors during these months. This factor is not possible to assess with the data at hand however, and follow up analysis is necessary to quantify the effect this has on campaign success. As it stands, May presents a statistically significant amount of campaign success relative to other months, and thus would likely be the best timeframe to launch.

###Subcategory Trends
Another trend visible in the data is the correlation of marked subcategory on campaign success.

![SuccessBySubcategory](https://github.com/Patchwork-Chimera/KickstarterAnalysis/blob/main/Subcategory%20Outcomes.png)

Theater campaigns launched with the subcategory of "plays" enjoy a success rate of slightly higher than 60%, whereas plays subcategorized as "musical" result in approximately 45% reaching successful outcomes. While the data at hand provides no ability to study if there is a causal relationship present, or if campaigns launched in the "play" category simply happen to resonate more with potential backers when compared to those in the "musical" category, there is a demonstrably higher degree of success reached in the "plays" category. Thus, it may be a prudent measure to categorize the campaign as a "play" rather than stratifying it as a "musical" specifically.

###Meta-trends
Finally, there are some aspects about the campaign itself that appear to influence success. 

When setting a goal, there does appear to be a "sweet spot" range of about $1,500 to $5,000 USD for both successful play campaigns as well as successful musical campaigns. This represents approximately 50% of all successful campaigns within those two categories, and may be due to a number of factors. Most importantly, the achievability of such goals is likely to be attractive to potential backers. When searching for campaigns to contribute to, backers are unlikely to be as swayed by campaigns they can only make insignificant, drop in the bucket sized contributions to; whereas campaigns of this size can be assisted meaningfully by fairly "everyday" quantities of money.

The duration of campaigns also appears to be worth nothing. The average time it takes for successful campaigns to reach that point is 33.4 days. This value is overwhelmingly concrete, as only a very small percentage of successful campaigns resulted in the following 30 days, the 60 day mark being the other "spike" of successes and failures. These are near certainly due to campaigns being pre-timed for 30 or 60 days, and thus the vast majority of campaigns will culminate at this point. However, of the campaigns that do not reach their funding goal by this point, only relatively few reach it by day 60 of the campaign. Thus, if the campaign does not reach its goal by day 30, it may be prudent to re-evaluate the advertising and description for the campaign to make it more appealing. 

Lastly, while near impossible to quantify with the available tools and data (NLP models would likely be the most effective at performing further analysis to this effect), the "blurb" likely plays an important role in attracting potential donors. As an anecdotal trend, though one that is intuitively sound and is consistently reinforced by SMEs in this field as well as adjacent fields, campaigns with concise, emotive descriptions appear to enjoy higher relative success when compared to campaigns with wordy or bland descriptions. It would thus seem a highly attractive investment of time to create a "blurb"/description confidently able to draw in potential backers.
