# Ebay-Product-Performance-Analysis
This project focuses on analyzing a provided eBay dataset to understand customer preferences and product ratings. The primary goal is to clean the data using Power BI's Power Query Editor and create visualizations that highlight key insights.

![Alt text](https://github.com/Deirdre24/Ebay-Product-Performance-Analysis/blob/main/eBay%20Product%20Performance%20Dashboard.png)


# Table Of Contents
* [Installation]()
* [About the Project](t)
* [Data Gathering]()
* [File Description]()
* [Licensing And Authors]()


# Installation 
The code requires:
* `Excel`
* `powerbi desktop` for visualization purposes 


# About The Project 
This project involves several key operations to standardize the eBay dataset, which includes various phone models and their ratings. The process begins with importing the dataset into Power BI and using Power Query Editor for data transformation.


# Data Gathering 
Data was gathered from kaggle's amazing repository of datasets available for use.


# Data Cleaning
Importing Data:
- Download the dataset from Kaggle and save it as a CSV file on OneDrive.
- Open Power BI, select "Get Data," and import the CSV file.

Using Power Query Editor:
- In Power BI, select "Transform Data" to open Power Query Editor.
- Remove Unnecessary Columns: Select columns that are not needed and click “Remove Columns” on the Home tab.
- Filter Rows: Apply filters to remove inconsistencies, such as duplicate entries or rows with missing values.
- Standardize Data: Use functions to replace missing values and ensure uniformity across entries.
  
Recording Transformation Steps:
- All transformations are automatically recorded in Power Query Editor, ensuring that every time the query connects to the data source, these steps are applied consistently.
- Finalizing Data Preparation:
After standardizing the data, apply changes and close the Power Query Editor.


# Visualization Creation
Once the dataset is prepared, visuals are created in Power BI Report View by dragging and dropping graphs and charts onto the report pane. Filters are applied to focus on specific aspects of the data.

Key Visuals Include:
* Pie Chart: Displays the percentage of five-star ratings for different phone color categories.
Donut Chart: Shows five-star ratings for selected manufacturers, highlighting that Apple has the highest number of five-star ratings and models compared to other brands.
* Bar Charts: Compare model names against model numbers and internal memory specifications.

  
# Insights Derived:
Manufacturer Ratings: Apple leads with the highest number of five-star ratings and a diverse range of models.
- iPhones are available in various internal memory capacities, demonstrating a well-distributed offering.
- A wide variety of color options correlates with aesthetic preferences across different models.
  
Samsung's Position: The brand ranks second in five-star ratings, primarily focusing on models with 64GB internal memory.

Nokia's Performance: With only one model offering 128MB internal memory, Nokia has fewer models and color options, resulting in lower ratings.
  
These insights can guide manufacturers in focusing on producing models that align with customer preferences, ultimately saving resources by avoiding unprofitable designs.


# File Description 
The folder contains:
* `a data folder` A folder with the original dataset and cleaned datasets used for analysis 
* `data_analysis.pbix` - The Power BI report file containing all visualizations and insights derived from the data
* `presentation.pptx` - A PowerPoint presentation summarizing the analysis.
* `dashboard_screenshots.docx` - A Word document with snapshots of the dashboard and filtered insights.


# Licensing And Authors
