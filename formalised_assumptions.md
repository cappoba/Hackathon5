# Formalised assumptions

<u>What level of granularity do you use?</u> 

We've decided to split all flights by 4 metrics
- Day of Week: weekends have lower proportion of eligible customers (72% compared to 70-71%) with Monday-Wednesday having a higher proportion of customers in Tier compared to other days (2.2% vs 2.0%) due to different profile of travel (e.g. business vs leisure) on each day
- Time of Day: time of day will have differing eligibility splits due to profile of customers at each time of day (e.g. business vs leisure).  The early morning is more likely to have customers in Tier 2 and less likely to have customers in Tier 1 while the evening has the smallest proportion of customers eligible and lowest proportion in Tier 3.
- Country Group Name: splitting by route would be too low-level as this may change season-on-season, while there is significant difference in behaviour by continent (e.g. Canada has 2.8% in Tier 1 while USA has 5.0%) therefore use country group which should be low-level enough to capture differences in behaviour but high-level enough to not be affected by schedule changes
- AC Type Group: this is a key split as the amount of premium cabin capacity available on a flight will have a significant effect on the eligibility of customers as e.g. First customers contribute to Tier 1


<u>What metric do you use to come up with Lounge eligibility profiles?</u>

Summed up all passengers for each of these four splits + tier and divided by total number of passengers in tier
