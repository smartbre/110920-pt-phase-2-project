King County Housing Data Analysis
Author: Brent Smart

Overview
This project analyzes sale price of homes in King County, WA in order to make recommendations to homeowners on improvements they can make to their homes to fetch a higher sell price. This analysis uses data from multiple datasets and only contains records of complete and relevant data. It also uses additional colums that were calculated using these datasets. The data analysis attempts to show the both the negative and positive relationships between Sale Price and several features, including number of bathrooms, bedrooms, total living area. Unfortunately, the models were only able to estimate 15%-22% of the variability in home sales. 

Business Problem
pic1

This data analysis aims to answer questions about about home sales in King County, WA. Focusing on the homes with a Sale Price greater than zero may be helpful to homeowners looking to sell.

Data
This analysis focuses on homes that sold for more than $0. This data uses the public online movie datasets from publically available data. Each data set provides information essential to address the aim of this data analysis. 

Methods
This analysis uses descriptive analysis. The data was modeled using a variety of graphing features.

Results
The model showed some improvement, from its first to second iteration. 


Conclusions
Transforming the data helped to increase the R2. The predicted Sell Price was under and over predicted, meaning the model could not fully explain the variance of the Sale Price.

Please review our full analysis in our Jupyter Notebook or our presentation.

For any additional questions, please contact Brent & smartbrent1@gmail.com

Repository Structure
Describe the structure of your repository and its contents, for example:

├── README.md              <- The top-level README for reviewers of this project
├── Exploratory.ipynb      <- Narrative documentation of analysis in Jupyter notebook
├── Model Improvement.pdf  <- PDF version of project presentation
├── data                   <- Both sourced externally and generated from code
    └── processed
    └── raw
