SUPSI 2024-25  
Data Visualization course, M-D3202E
Final group project


## NYC: New York Crashes
Authors: [William Ambrosetti](https://github.com/WiiLife), [Alexandra Biddiscombe](https://github.com/ambiddisco), [Youssef Sedra](https://github.com/Ysedra)

[NYC: New York Crashes](https://dataviz-supsi.github.io/2024/template/)


## Abstract
A trip to the scenic New York, seeing the Times Square, the great Central Park, the iconic Statue of Liberty. Sounds amazing no? Well, if you choose to drive around the city, things might not be as scenic as imagined.
Through our data analysis we’ll help you visualize the most optimal time to reduce the risk of a traffic accident ruining your trip. Following our line graphs, tree maps, and the geographic map we have, it will help give you a colorful narrative highlighting how different factors like time and location will affect the rate of accidents in New York!
Don’t hesitate to dive deeper into the data set that we’ll have linked and enjoy learning about the intricate world of Motor Collisions.


## Introduction
When thinking of something man made, not much is more flashy and attention drawing than our thousand-kilogram metal moving machines that are basically mechs, that we call cars. And taking it a step further, what is even more man-made is the biproduct of a human using such a machine, and the effects it has on the surrounding humans. In this data visualisation project, the story we intend to share is one on how to avoid harm from these machines and their pilots, through a study on a famous city and it's history of crashes and collisions, taking decade-old pile of rubble and transforming it into a safety rail.

Our objectives are to find the statistically most harmful sets of variables, so as to allow pedestrians to be mindful of the circumstances to avoid, when navigating the famous city of New York. The city was selected as an example, as it is well-known and a tourist attraction and disposes of complete data sources, and not due to any outliers in the number of collisions in this region as opposed to any other, nor for other outside factors.


## Data Scources
In order to perform meaningful research and analysis, the main dataset used in the visualisation project was taken from the official city site at "cityofnewyork.us", released by the NYPD, and updated daily starting from the year 2014. This dataset contains 2.1 million rows of data - each describing a unique crash - and 29 columns describing various factors and specifics relating to the crash, such as location, time, and vehicles involved.
For additional research, weather data for the same region was taken from Kaggle, and used for finding possible correlation in the datasets, as crashes may occur due to any myriad of circumstances. This ended up being a mostly fruitless - albeit interesting - experiment.


[NYC Motorvehicle Collision Dataset](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95/about_data)

[NYC Wather Dataset](https://www.kaggle.com/datasets/aadimator/nyc-weather-2016-to-2022/data)


## Data pre-processing
At first glance, the motorvehicle collision dataset looks imposing and frightening, containing much more data than we have been made used to during our courses, and yet its completeness and easy readability provided with less stress than anticipated in the pre-processing steps.
To obtain the data used in the visualisations, we removed any rows with missing or outlier positional data, then selected the features we deemed important and useful to our objectives, and did not make use of some variables which may have been of use with other research questions in mind, but that did not lead to direct help in this case, such as data about the state of the driver in the crash. 


## Data visualizations
We chose to visualise important data surrounding the research following questions:
- Where, as a citizen or tourist, am I most likely to be in danger when traversing the city of New York?
- When am I most likely to be in danger?

These two important questions are explored with the following visualisations:

### New York Crashes: The Where and the Why
With this first data visualisation we want to answer the questions:
“Where, as a citizen or tourist, am I most likely to be in danger when traveling through NYC?”
“What is most likely to cause that danger?”
You can find the answers by selecting a view of all boroughs of NYC, or by selecting a specific one on each graph by ticking its respective box.
[<img src="assets/images/visualizations/space.jpeg" width="800" alt="visualising accidents in space">]()

### New York Crashes: The When
At any moment, calm may be disrrupted by a sudden mishap in the vicinity. To know when to stay the most alert, we plotted a series of timelines showing the number of accidents that happened in NYC.
[<img src="assets/images/visualizations/time.jpeg" width="800" alt="Placeholder image">]()


## Key findings
After all our research, some of our expectations were confirmed and others were shattered. We found that the most famous places are the most likely to be dangerous, the dead of night is the safest time from cars, and holidays are the most devious and dangerous times of year, but some of our preconceptions were shattered as our research into weather data had to be discarded due to lack of evidence showing any relation whatsoever to crash numbers. This shows us that no matter what we may expect, and no matter how obvious we may think our initial conclusions are, additional research is always necessary to confirm a theory.


## Next steps
As mantioned in the paragraph about dataset pre-processing, this visualisation made no use of some features that could be deemed interesting under different research questions, including data about the state of the drivers of the vehicles involved in the collisions, as these are not factors a pedestrian can control. A future step to enhance the understanding on motorvehicle crashes could include a deeper dive into the reasons behind accidents, and so look at the features we ignored, whilst also exploring other possible outside explanations in the same vein as the influence of the weather. This could possibly include research on local wildlife, public city events, natural phenomena like earthquakes, or even the influence of social actions like the practices put into action during the CoVid-19 outbreak.