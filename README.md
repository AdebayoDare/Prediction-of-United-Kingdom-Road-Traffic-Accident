# Prediction of United Kingdom Road Traffic Accident

The project was aimed at advising UK government agencies about how to improve road safety and predict accidents. It also analyses the road traffic data for the year 2019.

## Table of Contents

- [Project Description](#project-description)
- [Data Used](#data-used)
- [Data Cleaning](#data-cleaning)
- [Findings](#findings)
- [Models](#models)
- [Recommendation](#recommendation)
- [Limitation](#limitation)
- [References](#references)

## Project Description

The United Kingdom publishes the road traffic accidents twice a year. This is aimed at analysing this data. It also helps to investigates the probable causes of these accidents in order to guide the government to implement policies to prevent or reduce the impacts of these accidents on families and on the economy.

This project did not consider car accidents alone, but included every accident recorded

## Data Used

Describe the data you used for your project. Include information about the source of the data, its format, and any preprocessing steps you performed.

## Data Cleaning

Explain the steps you took to clean and prepare the data for analysis or modeling. This may include handling missing values, removing duplicates, transforming variables, or any other data preprocessing techniques you applied.

## Findings

Present the findings or results of your analysis. Describe any insights or patterns you discovered during the project. You can include visualizations, statistics, or any other supporting evidence to illustrate your findings.

## Models

Several models were built to predict the severity of accidents. Decision tree and logistic regression classifiers were trained, achieving high-performance judged by different performance metrics. To further improve these metrics, an ensemble or stacked model was necessary. After training gradient boost and random forest ensembles, approximate accuracies of 94% and 97% were achieved, respectively. The random forest ensemble exhibited the best model performance across all metrics, with 97% accuracy, while logistic regression had the lowest accuracy at 93%.

The following steps where taking before training models on the data: 

FEATURE SELECTION: Select K-Best and chi-square libraries were used to select the best attributes in the dataset to increase model performance, while other attributes were dropped.

DATA SCALING: Due to the relatively high figures in some of the dataset, the minmaxscaler library was used to scale the data in the dataframe.

IMBALANCE: The imbalance issue in the dataset was addressed through the Synthetic Minority Over-Sampling Technique (SMOTE).


## Recommendation
1.	The analysis shows that Kent has a relatively more accident. Hence, there is a need for the police in the area to be more proactive in ensuring road accidents are reduced.
2.	There is a need to involve the police to control road traffics accidents on Fridays as most of the accidents occur on Fridays.
3.	The police and order traffic marshals should be deployed to control traffic between 8:00am and 9:00am in the morning and 5:00pm and 6:00pm in the evening everyday as most accidents occur at this period.
4.	Government should enact policies to support women while taking their children to school as the analysis shows that women have more accidents than men during this period compared with other times.
5.	Government should put measures in place to help a safe driving to and from work as most of the accidents happen are work related. 
6.	Most of the accidents that occur at night in places with over 60mph speed limit where there is no street light. Therefore, government needs to provide street lights at these places.


## Limitation

The project does not consider accidents that are not reported to the police. However, a well-policed country like the United Kingdom should have very few occurrences of such unreported accidents.

## References

DfT (2013) Road accidents and safety statistics. Available online: https://www.gov.uk/government/collections/road-accidents-and-safety-statistics [Accessed 15/05/2022].

DfT (2019) Data on all licensed and registered cars, produced by Department for Transport. Available online: https://www.gov.uk/government/statistical-data-sets/veh02-licensed-cars [Accessed 13/05/2022].

DfT (2020) Light Rail and Tram Statistics,
England: 2019/20.  Available online: https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/951076/light-rail-and-tram-statistics-england-march-2020.pdf [Accessed 13/05/2022].

DVLA (2020) Vehicle licensing statistics: 2019. Available online: https://www.gov.uk/government/statistics/vehicle-licensing-statistics-2019#:~:text=At%20the%20end%20of%202019%2C%20there%20were%3A,licensed%20vehicles%20in%20Great%20Britain [Accessed 13/05/2022].

Latlong (2022) London, the UK. Available online: https://www.latlong.net/place/london-the-uk-14153.html [Accessed 13/05/2022].

RAC (2011) Mortality statistics and road traffic accidents in the UK. 13/05/2022].

TaD (2019) Clock Changes in London, England, United Kingdom 2019. Available online: https://www.timeanddate.com/time/change/uk/london?year=2019 [Accessed 13/05/2022].

UKPD (2021) English Counties by Population and Area 2021/2022. Available online: https://populationdata.org.uk/english-counties-by-population-and-area/ [Accessed 23/05/2022].

