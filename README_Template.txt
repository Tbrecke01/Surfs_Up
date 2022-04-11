# Surfs Up

## Overview of Project
The purpose of this analysis was to determine the temperature patterns in Oahu, Hawaii to determine the viability of a surf and ice cream store in the area. June and December were chosen as the primary months for analysis. Analysis was done using by using SQLAlchemy to query SQLite databases.

## Analysis
<insert june temps>
<insert Dec temps>
As you can see above, temperatures in Oahu, Hawaii are fairly similair for the months of June and Decemnber with 3 key exceptions:
- Average (mean) and Max temperatures are fairly equal, with Avg temps being 3 degrees higher in June and Max temperatures being 2 degrees higher in June.
- Min temperature is much warmer in June, with the June min temp (64) being 8 degrees warmer than Decembers (56)
- More days and times are warmer in June as well, with the bottom quartile of June temperatures (73) being 4 degrees warmer than the bottom quartile of December temperatures (69). This difference holds for all quartile ranges.

## Results and Next Steps
Initial results look promising for a surf and ice cream shop in Hawaii. Even in December, average temperatures are high enough that individuals are likely to be out in the sun, on the beach, and craving a deliscious frozen treat. However, more analysis is still recommended, especially for the 'surf' shop piece.

The first additional query I would run would be on precipitation (rain) data. How often, and how long, it tends to rain are important data points as this is one of the big things that could keep people inside and not out surfing and eating ice cream. The next weather query I would run would be on wind speed. This is an important factor for surfers, as higher winds lead to higher waves (and therefore more surfers) while no winds would lead to a calm surf, great for the ice cream business but less for surfing! On the flipside, settling somewhere with too high of winds could lead to only surfers visiting. 

Finally, if branching out of weather data, some queries on water conditions like wave height, intervals, riptide, etc is a must. Localizing this data to more precise geographic points is also important to determine where best to open your new store.