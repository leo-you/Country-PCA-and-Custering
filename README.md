# Country Profiling Using PCA and Clustering

The data from this analysis is from [kaggle Unsupervised Learning on Country Data](https://www.kaggle.com/rohan0301/unsupervised-learning-on-country-data), which contains socio-economic and health related factors of 167 countries over the world. The goal of the project is to categorise the countries using socio-economic and health factors that determine the overall development of the country.

The variables provided in the dataset include socio-economic factors such as export, import and GDP of a country, as well as heath-related factors such as child mortality rate, life expectancy and health spend % of a country. The data is relatively well formatted and unlablled. Due to the nature of the dataset, the analysis will use a combinatino of **Unsupervised Machine Learning techniques** such as kmeans clustering and **Dimensionality Reduction techniques** such as Principal Component Analysis. We'll also perform outlier analysis and scalling the data to provide a more accurate clustering result. The analysis will be performed in Python using Jupyter Notebook. The packages used in this analysis are as followed:

- Seaborn
- Sklearn
- Matlibplot
- Numpy
- Pandas
- Yellowbrick
