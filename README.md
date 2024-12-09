Crop Yield Analysis Project
Project Overview
This project focuses on analyzing agricultural crop yield data to identify and categorize samples based on their yield performance. The goal is to extract high-performing ("Top") and mid-performing ("Middle") samples for different crop types, providing a basis for further analysis or predictive modeling.

Features
Categorization of Crop Yields:
For each crop, the dataset is sorted by yield to identify the top and middle yield samples.
Sampling:
Extracts n samples for both the top-yielding and middle-yielding groups for each crop.
Flexible Data Selection:
Handles a variety of categorical (Region, Soil Type, Weather Condition) and continuous features (Rainfall, Temperature).
Output:
Creates a combined dataset with yield categories labeled ("Top" and "Middle").
Saves the results to combined_yield_samples_unencoded.csv.
Dataset
Columns
Categorical Features:

Region
Soil_Type
Weather_Condition
Continuous Features:

Rainfall_mm
Temperature_Celsius
Target:

Crop
Yield:

Yield_tons_per_hectare
Requirements
Python 3.x
Pandas library
Install dependencies using:

bash
Copy code
pip install pandas
Usage
Step 1: Load the Dataset
Ensure your dataset (crop_yield.csv) is in the project directory.

Step 2: Run the Code
Run the script to process the data and create the categorized samples:

bash
Copy code
python crop_yield_analysis.py
Step 3: Output
A new CSV file, combined_yield_samples_unencoded.csv, will be generated with the categorized data.

Example Output
Region	Soil_Type	Weather_Condition	Rainfall_mm	Temperature_Celsius	Crop	Yield_tons_per_hectare	Yield_Category
North	Chalky	Cloudy	874.77	27.90	Barley	9.95	Top
East	Loam	Cloudy	933.09	39.45	Barley	9.74	Top
