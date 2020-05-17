# Data-cleaning

Template code for data cleaning and creating indicators that can be used in statistical analysis.

*############# Notebook summaries ##############*

create_and_clean_covariance_matrix

This notebook requires the following inputs:

1) Specify file directory
2) Specify technical indicators and associated functions
3) Specify how we deal with autocorrelation


It will then do the following things

1) Check to see if there is anything in the file directory
2) If there is, calculate technical indicators based on what is in the directory
3) De mean and standardise the data
4) Make the data stationary by losing as little signal as psosible
5) Tests for autocorrelation

identify_technical_clusters

This notebook requires the following inputs:

1) Specify file directory
2) Specify technical indicators and associated functions
3) Specify how we deal with autocorrelation


It will then do the following things

1) Group technical indicators into groups
2) Group technical indicators into time period groups
3) Identify which clusters are of interest



Framework
1. Data ingestion
2. [Data cleaning]
3. Strategy creation
4. Strategy testing
5. Implementation
6. Implementation testing
