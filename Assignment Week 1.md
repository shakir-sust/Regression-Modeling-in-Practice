## Assignment on "Writing About Your Data"
# Title: Introduction to Regression

## Sample
The sample is from Cortez and Morais study about predicting forest fires using metereological data [Cortez and Morais, 2007]. The study includes data from 517 forest fires in the Natural Park Montesinho (Trás-os -Montes, in northeastern Portugal) January 2000 to December 2003, including meteorological data, the type of vegetation involved (which determines the six components of the Canadian Forest Fire Weather Index (FWI) system (see below) and the total burned area in order to generate a model capable of predicting the burned area of small fires, which are more frequent.

## Procedure
This data was built using two sources. The first database was collected by the inspector that was responsible for the Montesinho fire occurrences. At a daily basis, every time a forest fire occurred, several features were registered, such as the time, date, spatial location within a 9×9 grid (x and y axis spatial coordinate within the Montesinho park map), the type of vegetation involved, the six components of the FWI system and the total burned area. The second database was collected by the Bragança Polytechnic Institute, containing several weather observations (e.g. wind speed) that were recorded with a 30 minute period by a meteorological station located in the center of the Montesinho park. The two databases were stored in tens of individual spreadsheets, under distinct formats, and a substantial manual effort was performed to integrate them into a single dataset with a total of 517 entries.

## Measures
The data contains the location of the fire (x,y axis spatial coordinate within the Montesinho park map: from 1 to 9), month and day of the week the fire occurred (january to december and monday to sunday), FWI system components: Fine Fuel Moisture Code (numeric rating of the moisture content of litter and other cured fine fuels: 18.7 to 96.2), Duff Moisture Code (numeric rating of the average moisture content of loosely compacted organic layers of moderate depth: 1.1 to 291.3), Drought Code (numeric rating of the average moisture content of deep, compact organic layers: 7.9 to 860.6) and Initial Spread Index (numeric rating of the expected rate of fire spread: 0.0 to 56.1), metereological variables: temperature (2.2 to 33.3 °C), relative humidity (15 to 100%), wind speed (0.4 to 9.4 Km/h) and outside rain (0.0 to 6.4 mm/m^2), among the burned area of the forest as response variable (0.0 to 1090.84 Ha).

## References
[Cortez and Morais, 2007] P. Cortez and A. Morais. A Data Mining Approach to Predict Forest Fires using Meteorological Data. In J. Neves, M. F. Santos and J. Machado Eds., New Trends in Artificial Intelligence, Proceedings of the 13th EPIA 2007 - Portuguese Conference on Artificial Intelligence, December, Guimarães, Portugal, pp. 512-523, 2007. APPIA, ISBN-13 978-989-95618-0-9. Available at: [http://www.dsi.uminho.pt/~pcortez/fires.pdf]

## Dataset extracted from https://archive.ics.uci.edu/ml/datasets/Forest+Fires on May 26, 2016
