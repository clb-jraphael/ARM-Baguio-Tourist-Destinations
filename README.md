Tourist Behavior Analysis in Baguio City
Overview
This project aims to identify the tendencies of tourists visiting Baguio City. By analyzing the destinations that tourists visit, we can predict which destinations they are likely to visit next. This model uses Association Rule Mining (ARM) to study tourist behavior patterns.

Purpose
The purpose of this project is to study tourist behavior in Baguio City. Specifically, it identifies patterns and tendencies regarding which destinations tourists are likely to visit based on their previous visits.

Installation
To run this project, ensure you have the following packages installed:

bash
Copy code
pip install pandas mlxtend
Data
The data for this project is collected from a survey and stored in a CSV file named FormResponses1.csv. The key column in this dataset is:

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

Conclusion
This ARM model provides valuable insights into the behavior of tourists in Baguio City. By analyzing which destinations are frequently visited together, stakeholders can better understand tourist preferences and optimize travel recommendations and marketing strategies.
