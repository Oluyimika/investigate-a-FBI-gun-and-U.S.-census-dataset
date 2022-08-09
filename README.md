# (Investigate a FBI Gun and U.S. Census Dataset)
## by (Oluyimika Sosanya)


## Dataset
> This data provided by Udacity in order to complete a project contains information on the number of firearms
background checks by month, state, and type from FBI's National Instant Criminal BackgroundCheck System sourced
from this [page](https://github.com/BuzzFeedNews/nics-firearm-background-checks/blob/master/README.md).
The data has been supplemented with state level data from [census.gov](https://www.census.gov/) for analysis.

## Goal of the project

> The goal of this project was to Choose one of Udacity's curated datasets and investigate it using NumPy and pandas. Go through the entire data analysis process, starting by posing a question and finishing by sharing your findings.

## Summary of Findings

> There were no strong correlation between census variables and high gun per capita. However, some variable showed weak positive and negative correlation with high gun per capita. To this end, it's difficult to conclude that any census variable is most associated with high gun per capita.

> Although gun purchase showed a mixed trend when explored by month, the upward trend and eventual peak in the summer holiday and festive periods might be a pointer to increased outdoor activities like hunting.

> Finally, gun purchase as an overall upward trend in the last 18 years but with no strong correlation with census variables. Analyzing the relationship between state and high gun per capita might be a more effective option.

## Limitations

> The FBI gun data contained missing values with I replaced with the mean. However, I dropped the 'Fact Note' column in census data for containing a lot of null values and not being useful for my analysis.

> After merging gun data and census data into one dataset using an inner join, gun data points for states with no match in the census data were dropped to avoid distorting our analysis.

> Gun data contains incomplete data for 2017 hence the decline in gun purchase after 2016.
