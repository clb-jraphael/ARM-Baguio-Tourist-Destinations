Tourist Behavior Analysis in Baguio City

Overview

This project aims to identify the tendencies of tourists visiting Baguio City. By analyzing the destinations that tourists visit, we can predict which destinations they are likely to visit next. This model uses Association Rule Mining (ARM) to study tourist behavior patterns.

Purpose

The purpose of this project is to study tourist behavior in Baguio City. Specifically, it identifies patterns and tendencies regarding which destinations tourists are likely to visit based on their previous visits. This was done in order to help develop iteneraries and marketing strategies for companies that focuses on providing tour packages or itenraries

Installation

To run this project, ensure you have the following packages installed:

mlextend

Data

The data for this project is collected from a survey (conducted through google forms) and stored in a CSV file named FormResponses1.csv. The key column in this dataset is:


Which of the tourist destinations in Baguio City will/have you visited?: Contains the list of tourist destinations visited by each respondent.
Preprocessing
The preprocessing steps involve cleaning and transforming the data for ARM analysis:


Removal of Non-Standard Entries: Remove entries containing the word "Hindi".
Splitting Entries: Split the entries into lists of tourist destinations.
Dropping Original Column: Drop the original column containing the destinations.
Converting to List of Lists: Convert the cleaned data into a list of lists format.


Outputs
All the outputs, including screenshots and visualizations, can be found in the output folder.


Results

The results include:


Frequent itemsets discovered using the FP-Growth algorithm.
Association rules generated with confidence and lift metrics.
Filtered rules based on specific thresholds for antecedent length, confidence, and lift.
These results help in understanding the patterns and tendencies of tourist behaviors in Baguio City.


This ARM model provides valuable insights into the behavior of tourists in Baguio City. By analyzing which destinations are frequently visited together, you can better understand tourist preferences and optimize travel recommendations and marketing strategies.



Recommendations for improvements and for further analysis:

In my analysis of tourist tendencies, I have identified the following recommendations to improve the accuracy and reliability of the results:



Increase Population Size

To better identify any outliers, it is essential to use a larger population size (Since the model only made use of 100 individual responses). This approach ensures a more comprehensive understanding of tourist behaviors, capturing a wider range of preferences and patterns.


Broaden Scope Beyond Town Proper

My initial findings indicate that most tourist tendencies focus primarily on destinations near the town proper. By expanding the scope of data collection to include more peripheral and less frequently visited locations, you can gain insights into a broader array of tourist activities and preferences.



Enhance Minimum Support and Confidence

With a larger and more diverse dataset, you can increase the minimum support and confidence thresholds. This adjustment helps in identifying stronger and more significant patterns within the data, leading to more reliable and actionable insights.


Neutral Lift Value Adjustment

By adopting these recommendations, there will be less need to maintain a neutral lift value (lift = 1). A larger dataset and broader analysis scope inherently contribute to a more balanced and insightful analysis, rendering the neutral lift value less critical for achieving meaningful results.


Implementation Steps

Expand Data Collection: Increase the population size by including data from a wider range of sources and geographical areas.
Adjust Analysis Parameters: Increase the minimum support and confidence levels in your data mining algorithms to reflect the larger dataset.
Review and Refine: Continuously review the results to identify any new outliers or patterns, refining the data collection and analysis process as needed.
Following or trying out these recommendations, you can or may significantly improve the robustness of your analysis and gain deeper insights into tourist tendencies, leading to more effective decision-making and strategy development.
