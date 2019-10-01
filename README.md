# Identify Customer Segments
#### (Unsupervised learning)

## Project Overview
In this project, I worked with real-life data from Bertelsmann partners AZ Direct and Arvato Finance Solution. The data here concerns a company that performs mail-order sales in Germany. Their main question of interest is to identify facets of the population that are most likely to be purchasers of their products for a mailout campaign. Thus, I used unsupervised learning techniques to organize the general population into clusters, then used those clusters to see which of them comprise the main user base for the company.

## What to install

This project uses Python 3 and is designed to be completed through the Jupyter Notebooks IDE. The following libraries are used in this project:

NumPy
Pandas
Sklearn / scikit-learn
Matplotlib (for data visualization)
Seaborn (for data visualization)

## Files
`Identify_Customer_Segments.ipynb`: The code is provided in this notebook file
`Udacity_AZDIAS_Subset.csv`: Demographics data for the general population of Germany; 891211 persons (rows) x 85 features (columns).
`Udacity_CUSTOMERS_Subset.csv`: Demographics data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).
`Data_Dictionary.md`: Detailed information file about the features in the provided datasets.
`AZDIAS_Feature_Summary.csv`: Summary of feature attributes for demographics data; 85 features (rows) x 4 columns

Each row of the demographics files represents a single person, but also includes information outside of individuals, including information about their household, building, and neighborhood. I used this information to cluster the general population into groups with similar demographic properties.
