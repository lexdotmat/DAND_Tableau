# DAND_Tableau

Github repository for the Tableau project of the Data Analytics NanoDegree.

## Dataset choice

For this Analysis the flights dataset has been chosen. Given my background and interest in Aeronautic (I've worked different industries related to Aeronautic), this comes as a natural choice. 

## Summary

The data comes originally from RITA where it is described in detail. These files have derivable variables removed, are packaged in yearly chunks and have been more heavily compressed than the originals.
the current analysis focus on the 2008 flights.


## Design

Link to the Tableau public Story : 
https://public.tableau.com/profile/maxime.letellier#!/vizhome/DANDStoryFlights/Story1?publish=yes
Design aims to be simple. Colors are uniforms per graphics and elements of High importance are highlighted using a gradient color (darker or brighter).

#### Most Visited vizualization
For the first vizualization of the most visited, I first tried a bar chart which did show the most visited but didn't show the whole dataset, i.e. the percentage of flights concerned.

Using the Treemap is a good alternative, the surface shows how important the two destination are. 

#### Evolutions
To show how it evolve, the best for time series are in usually lines. However, in the case of this vizualization. I wanted to use the trend lines and how is the curve, that's how I came with the Bar + trend line design.

#### Map
Last but not least, it was interesting to have a vizualization showing the locations of both Airport, I'm not from USA and showing both Airports are indeed a good thing to know! 

##  Feedback 

You might need to ask specific questions to prompt the reader. Here are some questions to help you. You can, of course, ask others.

- What questions do you have about the data? 
What about the other Locations? In Europa and Asia ?

- What do you think is the main takeaway from this visualization?
The most visited Airport in 2008 was Chicago, most probably Atlanta in the next following years. 

- Is there something you don’t understand in the graphic? 
No

Regarding the evolution of the vizualization, the first vizualization can be consulted here:
https://public.tableau.com/profile/maxime.letellier#!/vizhome/Flights_28/Sheet2 

The main issue was that that names were not readable, the usages of IATA codes is not natural. The bar chart does not transmit how important are the first datasets in comparison to the whole.

A treemap version as been designe and can be found here.
https://public.tableau.com/profile/maxime.letellier#!/vizhome/DANDTableauv1/Mostvisiteddestination 

And that's how the Story and the associated vizualization were later added. 

An Overview of all the dataset has been added (i.e. Map), however, regarding the other continent, they are not present into the data. I personnaly also tried to add Aircraft type into the vizualization to understand what types of traffic was present and found too much NA values to correctly take this variable into account.

## Resources 
http://stat-computing.org/dataexpo/2009/the-data.html

http://stat-computing.org/dataexpo/2009/supplemental-data.html
Top 3 Airlines :
https://de.delta.com
https://en.wikipedia.org/wiki/Atlantic_Southeast_Airlines
Note that the Atlantic Southeast Airlines have changed and does not exist under this name 
https://en.wikipedia.org/wiki/AirTran_Airways
same for AirTran Airways
