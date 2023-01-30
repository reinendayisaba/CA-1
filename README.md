# Computer-assignments
The purpose of this program is to conduct exploratory data analysis on a house price dataset so that it can eventually be used for predicting the price of a house. The dataset can be accessed through https://github.com/ArinB/MSBA-CA-Data/raw/main/CA01/house-price-train.csv. It contains 81 features, which represent different factors that can affect the sale price of a house, and 1460 rows. There are 3 parts to the program. The first part – data understanding – includes univariate, bivariate, and multivariate analysis, as well as various visualizations to explore the distribution of both the continuous and categorical features. This part also includes two data quality reports – one for the continuous features and a second one for the categorical features.  The second part of the program – pre-processing – includes cleaning, transforming, and manipulating the raw data. Finally, the third part of the program – post-processing – includes collinearity analysis and the identification of the features that need to be dropped from the dataset since they aren’t needed to predict the target variable – sale price. Every block of code contains a few comments that give a brief description of what’s being done and the explanation of the result.

Four libraries need to be imported in order to run the code. Specifically, the NumPy library, which is used for mathematical and scientific calculations, as well as different functions that can be applied on arrays. The Pandas library, which provides various tools for operating data frames and series , also needs to be imported. Moreover, the matplotlib.pyplot module, which is part of the matplotlib library, should also be imported to be able to create the different visualizations provided in the program. In addition to this module, the Seaborn library, which also provides a set of visualizations, needs to be imported since there are some visualizations that use this library. 

For the code to run successfully, all the above-mentioned libraries and modules need to be installed and imported. The dataset should also be properly read into the notebook using pd.read_csv() and the link to dataset. From there, the code has to be run sequentially from the beginning to the end. 
