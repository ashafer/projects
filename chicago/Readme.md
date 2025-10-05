Much of what I have experienced on the CTA matches what I was told to expect when I moved to Chicago a few years ago, but I'm curious if the local wisdom is anecdotal or whether there is data to back it up. Also, those of us navigating the trains in the hybrid commuting society we now live in post-pandemic have noticed changes both in ridership and seemingly an increase in crime relative. I have also heard that shifts within the city have lead to changes in which train lines are considered safe. Specifically, the Green line (historically the most dangerous) is now considered safe for commuters and conversely the Blue line, which used to be quiet and clean, has changed significantly to be less desirable for commuters.

I have 3 main questions that I hope to answer:
1. Are the trains actually safer during commuting hours?
2. Have there been shifts in the crime rate or types of crimes post-pandemic?
3. Is the Green line now safer than the Blue line during commuting hours?

To try to answer these questions, I'll use crime data for the city that can be filtered to CTA related areas, data and maps for the train lines and stations to narrow it down to only those routes, and finally ridership data to try to account for changes in ridership as I explore the historical trends and calculate the rates of different crimes. The ridership data is limited as it can only be collected at the station of entry (when the fare card is swiped) because transfers between lines do not require additional fare and neither does the destinaion. Also, in the area of downtown referred locally as "the loop", most of the trains either connect at the same station or allow for easy transfer, so it is impossible to tell which line the rider is actually entering and similarly which line a crime event may have been closest or related to. And ridership data is also limited to totals for weekday vs weekend or holiday, so incidence of crime during commuting hours is not answerable with this dataset. I'll revise the last question to just compare incidence rate but also take a look at the crimes commited during commuting hours on those lines even if not ridership adjusted.

Summary of Results:

1. Trains do appear to be safer during commuting hours. Approximately 69% fewer crime events occur during commuting windows, and the Violent events during those windows was an additional 28% lower during commuting periods. Note, that this model did not account for ridership levels or the spike in riders during these windows so ridership adjust numbers may be even lower.

2. There was an increase in Violent crime rates ( ~42% when adjusted for ridership) from 2022-24 when compared to pre-pandemic years of 2017-19 but Petty crime rates have held roughly steady.

3. I was only able to partially answer this question with the available data. The incidence of crime events on the Green line is substantially lower in the last 12 months than the historical average which gave it its reputation. The Red line and the Loop areas are now less safe than the Green line, a trend that may have started during the 2011 city initiatives to improve surveillance and safety on the CTA. The Blue line has now surpassed the Brown line as the line with the lowest rate of crimes committed per million riders but this appears to be driven by higher ridership on the Blue line not fewer crime events. (See Chicago_cta_crime_model for more modeling details)

Limitations:

- The overlap of stations in the Loop led to my handling these events as basically its own area/line. While this gives visibility into the geographical nature of the crime events occuring on or near the CTA, it doesn't necessarily help clarify which stations or trains may be safer in the downtown area.
- Only reported events are included in the crime database, so overall rates may be higher and shaped by systemic reporting biases.
- Each train line services many different neighborhoods and while crime events may be common in one area, they may be relatively low in other areas that the same line services so aggregates accross the whole train line may not be representative of riders experiences on a given section of a line.