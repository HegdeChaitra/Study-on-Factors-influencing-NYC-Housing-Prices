# Study-on-Factors-influencing-NYC-Housing-Prices
## Enigma Datathon Runner-up
- Extracted and Processed five NYC open data to characterize a location in NYC in term of approachability, safety, standard of living, etc.
- Combined these location relevant features with the housing price dataset to enhance model's performance and understand factors driving
the house prices in NYC.

#### 5 different publicly available datasets were used to analyse the factors influencing the housing price.
## Datasets are :
1) Enigma NYC Property Sale:
Accessed value land, Floor area residential, Floor area total building, Year built, Residential Units, altering history
Gives information about  the particular house and its properties.

2) FourSqure Data: 
Gives following venue information about Zipcode: Professional places, shops&services, Residence, Outdoor&Recreation, College & University, Travel&Transport, Night life&Sports, Arts & Entertainment.
Gives idea about how engaging one area is

3) USZipcode API:
Converts latitude and longitude information to zip code
Gives other factors like : Number of House Units, Density, Land Area, Water Area, Population, Total wage, Wealthy
Gives intuition about quality of life and population and demographic information

4) NYU Yellow Taxi:
Number of pickups and drop offs from particular zip code
Gives information about how accessible area is.

5) NYC Crime Data
Gives following information based on Zipcodes: Felony, Misbehavior, Violation, Misdemeanor 
Gives intuition about safety of an area

## Correlation map of all variables of final Dataset:

![Alt text](download-1.png?raw=true "Title")


## Feature importance:
- Gross square feet (Enigma Dataset)
- Commercial Units(Enigma Dataset)
- Density(ZIP Code API)
- Art & Entertainment (Fousquare Dataset)
- Police precinct(Enigma Dataset)
- Felony (Crime dataset)
- Outdoor & Recreation (Foursquare Dataset)
- Land Square feet (Enigma dataset)

![Alt text](imp.png?raw=true "Title")

## Insights From Feature Importance:

- As expected, diverse datasets did give some idea about the different attributes that correlates with the price of a house, which we could also interpret as making a place for desirable to live. 
- Intuitively Gross Square Feet and Commercial Units are important trivially. 
- A high density naturally suggest high demand for living in the area. 
- Felony and police precinct can be used as a proxy for how safe the neighbourhood. 

## Conclusion:

We focussed our efforts on finding the attributes that primarily drive the price of a property. As as natural next step, we would like to gather more data and built a model to predict prices primarily based on the features which we found to be important.
