# Solar Flare Prediction Project

The goal of this project is to use data mining techniques to predict solar flares, which are powerful eruptions of energy from the sun that can have significant impacts on Earth and human technology. The project will use the UCI Solar Flare Dataset, which contains a variety of information about solar flares that have occurred in the past, including the time, location, and intensity of the flare, as well as various characteristics of the sun's surface.

The data mining techniques that will be used in this project may include classification algorithms (such as logistic regression or decision trees) to predict whether a given set of solar activity will result in a flare. Additionally, clustering and association rule mining techniques may be used to identify patterns and relationships within the data that can help to improve the accuracy of the flare predictions.

The ultimate goal of this project is to develop a model that can accurately predict solar flares, which can be used to help protect satellites and other technology from damage, as well as to aid in the study of the sun's behavior.

## Datasets

Datasets are downloaded from archive.ics.uci.edu website. Flare.data2 dataset has 13 columns and 1066 rows without the header. The database contains 3 potential classes, one for the number of times a certain type of solar flare occured in a 24 hour period. Each instance represents captured features for 1 active region on the sun. The data are divided into two sections. The second section (flare.data2) has had much more error correction applied to the it, and has consequently been treated as more reliable. This informations had refered from archive.ics.uci.edu website.

## Attribute Information:

1. Code for class (modified Zurich class) (A,B,C,D,E,F,H)
2. Code for largest spot size (X,R,S,A,H,K)
3. Code for spot distribution (X,O,I,C)
4. Activity (1 = reduced, 2 = unchanged)
5. Evolution (1 = decay, 2 = no growth, 3 = growth)
6. Previous 24 hour flare activity code (1 = nothing as big as an M1, 2 = one M1, 3 = more activity than one M1)
7. Historically-complex (1 = Yes, 2 = No)
8. Did region become historically complex on this pass across the sun's disk (1 = yes, 2 = no)
9. Area (1 = small, 2 = large)
10. Area of the largest spot (1 = <=5, 2 = >5)

## From all these predictors three classes of flares are predicted, which are represented in the last three columns.

11. C-class flares production by this region in the following 24 hours (common flares)
12. M-class flares production by this region in the following 24 hours (moderate flares)
13. X-class flares production by this region in the following 24 hours (severe flares)

## Getting Started

1. Download the UCI Solar Flare dataset from the link provided.
2. Run the data cleaning process to get the dataset ready for data mining.
3. Visualize the data to find relationships
4. Apply different data mining techniques to the dataset to develop a model that can predict solar flares.
5. Interpret the results and conclusion.

## File Descriptions
* `SolarFlare.csv` : The original dataset from UCI.
* `SolarFlare_Clean.csv` : The cleaned version of the dataset.
* `SolarFlare_Analysis.ipynb` : Jupyter notebook containing the data cleaning, data mining and model evaluation process.

## Results
The results of this project will be presented in the form of visualizations and performance metrics.

## Conclusion
The conclusion will summarize the findings of the project and discuss the potential implications of the results.

## References
1. [UCI Solar Flare Dataset](https://archive.ics.uci.edu/ml/datasets/Solar+Flare)
2. [Solar flares and space weather](https://www.swpc.noaa.gov/phenomena/solar-flares)
3. [Solar flares and their effects](https://www.nasa.gov/mission_pages/sunearth/spaceweather/index.html)
