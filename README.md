Marketing/Advert Dataset Analysis
Overview
This project involves analyzing a marketing/advert dataset obtained from Kaggle. The objective is to test various hypotheses on specific variables to assess their relevance and impact. Additionally, visualizations are created to effectively communicate the findings.

Dataset
The dataset used for this analysis contains various attributes related to marketing and advertising efforts, including:

userId: Unique identifier for each user.
test group (ad/psa): Indicates whether the user was exposed to an advertisement (ad) or a public service announcement (psa).
converted: Indicates whether the user performed a desired action (e.g., made a purchase, signed up).
total ads: Total number of ads viewed by the user.
most ads day: The day of the week when the user viewed the most ads.
most ads hour: The hour of the day when the user viewed the most ads.
Objectives
The main objectives of this project are:

Data Cleaning: Ensure the dataset is clean and ready for analysis by handling missing values and outliers.
Hypothesis Testing: Formulate and test hypotheses on various variables to determine their relevance in the marketing context.
Visualization: Create visual representations of the data and analysis results to facilitate understanding and communication.
Hypotheses Tested
Some of the hypotheses tested in this project include:

Test Group vs. Conversion Rate: Testing whether being in the ad or PSA group has a significant impact on conversion rates.
Total Ads vs. Conversion Rate: Investigating if the total number of ads viewed by a user influences their likelihood to convert.
Most Ads Day vs. Conversion Rate: Assessing if the day of the week when users view the most ads affects conversion rates.
Most Ads Hour vs. Conversion Rate: Analyzing whether the hour of the day when users view the most ads impacts conversion rates.
Visualizations
Various visualizations were created to support the analysis, including:

Histograms: To show the distribution of key variables.
Box Plots: To highlight outliers and the spread of data.
Bar Charts: To compare categorical data.
Files
The repository contains the following files:

data/: Directory containing the raw dataset and any cleaned/processed versions.
notebooks/: Jupyter notebooks with the data cleaning, analysis, hypothesis testing, and visualization code.
README.md: This README file.
.
Results
The results of the hypothesis tests and the insights gained from the visualizations are documented in the notebooks. Key findings are summarized as follows:

There is a significant difference in conversion rates between users in the ad group and those in the PSA group.
A higher total number of ads viewed is positively correlated with conversion rates.
The day of the week when users view the most ads shows some influence on conversion rates.
The hour of the day when users view the most ads shows some influence on conversion rates, with specific hours being more effective.

Acknowledgments
Kaggle for providing the dataset.
The open-source community for their valuable tools and libraries.
