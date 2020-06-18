# datasets

Sources: 
* https://github.com/washingtonpost/data-police-shootings
* https://www.kff.org/other/state-indicator/distribution-by-raceethnicity/?dataView=1&currentTimeframe=0&sortModel=%7B%22colId%22:%22Location%22,%22sort%22:%22asc%22%7D

Findings: 
Using Washington Post data... and joining population statistics.... 
For every black person there  are X white people in the US:
2015: 5.12
2019: 4.97
- Note: Black to white ratio dropped. We'd expect to see a drop in likelihood that black people would be killed by cop. 
To prove that, you take the white deaths and divide by the rate of white over black population (number from above). 
2015: 97.12
2019: 81.29
Note: This is what the rates SHOULD be based on population. 
Taking the number of black people actually killed and dividing that by the expected rate (from above), you can get the indexing (over/under) of how often black people are killed more/less often than white taking population into consideration. 
2015: 2.70
2019: 2.99
Notes: It has gotten WORSE even though the population of black people has gone DOWN.  
- In 2019, a black person was 3 times more likely to be killed by a cop than a white person.  
There were three states where the numbers indicate that in 2019, white people were more likely to be killed:  
- GA: 0.95
- MS: 0.75
- VA: 0.95
(States without black deaths in 2019 excluded: DC, DE, HI, ID, MA, ME, MT, ND, NH, NM, SD, VT, WY)
The rest of the 34 states show likelihood > 1
30 of those 34 states show a likelihood > 2
Top 5 overindexing states: 
IL: 36.02 up from 11.73 in 2015
UT: 22.55 up from 0
LA: 15.80 up from 2.38
WA: 13.55 up from 0
NE: 8.95 up from 2.59
Most improved states (Excluding those with 0 deaths in 2019 since the deaths are low counts anyway):
MD: 2.45 - Down from 7.21
VA: 0.94 - Down from 4.82
WV: 5.69 - Down from 8.95
IN: 2.32 - Down from 4.84
CO: 5.93 - Down from 8.43 
- Note: There does not appear to be a correlation with the legalization of drugs in either case (increased index nor decreased index)
Keep in mind that in the state with the most improvement, a black person is still 2.45 times more likely to be killed by a cop than a white person. 
Still more things to do with the data, but this is what I put together tonight.  Happy to share my tableau workbook if you want to play around with the data.
