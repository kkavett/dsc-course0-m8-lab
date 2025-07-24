# Aviation Accident Analysis

The purpose of this project is to analyze airplane safety based on a number of factors. The analysis is conducted on a data set of aviation accident data from 1948-2003.

## Data Cleaning
The notebook Aviation_Accidents_Cleaning contains all of the steps used to clean and filter the data in AviationData.csv. This includes filtering the data to professionally-built airplanes from the last 40 years. This also includes removing data that is unnecessary for this analysis or has too many missing values to be useful, as well as additional cleaning and consolidation tasks.

The cleaned data set is created as CleanAviationData.csv to be used in subsequent analysis.

## Data Analysis
The notebook Aviation_Accidents_Data_Analysis contains analysis done on the cleaned data, including analysis about injury rates by plane make and model (grouped by small and large airplanes), destruction rates by make and model (grouped by small and large airplanes), rate of destruction grouped by phase of flight, and rate of destruction grouped by phase of flight and purpose of flight.

Some key conclusions include:
   - Large airplanes have a lower injury likelihood than small airplanes.
   - The overall mean of Injury Likelihood is 26%. All of the 15 Makes with the lowest rates of Injury Likelihood, for both large and small aircraft, fall below this mean.
   - For small airplanes, Bombardier and Waco are the top recommendations based on Make, based on the metrics of rate of Injury Likelihood and rate of Destruction.
   - For large airplanes, Aero Commander, Mooney, Hughes, Gulfstream, Grumman, and Swearingen are the top recommendations based on Make, based on the metrics of rate of Injury Likelihood and rate of Destruction.
   - Based only on the metric of likelihood of injury, the Cessna 180C, Bell 47G-4A, and Grumman G164B are the top recommendations for small planes. Boeing 737-800, Boeing 737-3H4, Mcdonnell Douglas MD-80, and Boeing 757 are the top recommendations for large planes.
   - Across all flight purposes, the three most dangerous phases in terms of rate of destruction are maneuvering (43%), climbing (39%), and cruising (33%).

Please see the notebook for the full analysis and charts supporting these conclusions.