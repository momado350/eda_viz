# eda_viz
Exploratory data analysis (EDA) is an approach to analyze the data and find patterns, visual insights, etc. that the data set is having, before proceeding to model. One spends a lot of time doing EDA to get a better understanding of data, that can be minimized by using auto visualizations tools such as Pandas-profiling, Sweetviz, Autoviz, or D-Tale
EDA involves a lot of steps including some statistical tests, visualization of data using different kinds of plots, and many more. Some of the steps of EDA are discussed below:
Data Quality Check: Can be done using pandas library functions like describe(), info(), dtypes(), etc. It is used to find several features, its datatypes, duplicate values, missing value, etc.
Statistical Test: Some statistical tests like Pearson correlation, Spearman correlation, Kendall test, etc are done to get a correlation between the features. It can be implemented in python using the stats library.
Quantitative Test: Some quantitative test is used to find the spread of numerical features, count of categorical features. It can be implemented in python using the functions of the pandas library.
Visualization: Feature visualization is very essential to get an understanding of the data. Graphical techniques like bar plots, pie charts are used to get an understanding of categorical features, whereas scatter plots, histograms are used for numerical features.
To perform the above-mentioned tasks we need to type several lines of code. Here auto-visualization library comes into the play, which can perform all these tasks using just 1 line of code. Some of these auto-visualization tools we will discuss in this article:
Pandas-Profiling
Sweetviz
Autoviz
D-Tale
The dataset used for exploratory data analysis using the pandas-profiling library is the Titanic dataset downloaded from Kaggle.
Pandas-Profiling:
Pandas profiling is an open-source python library that automates the EDA process and creates a detailed report. Pandas Profiling can be used easily for large datasets as it is blazingly fast and creates reports in a few seconds.
Installation:
GitHub repository for pandas profiling can be
pip install pandas-profiling
GitHub repository for pandas profiling.
Usage:

Report:
The pandas-profiling library generates a report having:
An overview of the dataset
Variable properties
Interaction of variables
Correlation of variables
Missing values
Sample data
Image for post
(GIF by Author)
Sweetviz:
Sweetviz is an open-source python auto-visualization library that generates a report, exploring the data with the help of high-density plots. It not only automates the EDA but is also used for comparing datasets and drawing inferences from it. A comparison of two datasets can be done by treating one as training and the other as testing.
Installation:
GitHub repository for pandas profiling can be
pip install sweetviz
GitHub repository for pandas profiling.
Usage:

Report:
The Sweetviz library generates a report having:
An overview of the dataset
Variable properties
Categorical associations
Numerical associations
Most frequent, smallest, largest values for numerical features
Image for post
(GIF by Author)
Autoviz:
Autoviz is an open-source python auto visualization library that mainly focuses on visualizing the relationship of the data by generating different types of plot.
Installation:
GitHub repository for pandas profiling can be
pip install autoviz
GitHub repository for pandas profiling.
Usage:

Report:
The Autoviz library generates a report having:
An overview of the dataset
Pairwise scatter plot of continuous variables
Distribution of categorical variables
Heatmaps of continuous variables
Average numerical variable by each categorical variable
Image for post
(GIF by Author)
D-Tale:
D-Tale is an open-source python auto-visualization library. It is one of the best auto data-visualization libraries. D-Tale helps you to get a detailed EDA of the data. It also has a feature of code export, for every plot or analysis in the report.
Installation:
GitHub repository for pandas profiling can be
pip install dtale
GitHub repository for pandas profiling.
Usage:

Report:
The dtale library generates a report having:
An overview of the dataset
Custom filters
Correlation, Charts, and Heatmaps
Highlight datatypes, missing values, ranges
Code export
Image for post
(GIF by Author)
Conclusion:
I prefer to do my EDA with self-defined functions using several python libraries. The above-discussed libraries should be used to speed up your work.
For beginners, it is good to start doing EDA using the pandas library and writing python code before trying these libraries, as it is more important to be equipped with the fundamental knowledge and programming practices.
The best data auto-visualization amongst the above discussed is the DTale library, as it reports with detailed EDA, custom filters, and code export. Code export is the main highlight of this library that makes it better than others.
References:
[1] Towards Data Science (Aug 30, 2020): EDA with 1 line of python code

## all credits goes to:
https://towardsdatascience.com/@me.satyam