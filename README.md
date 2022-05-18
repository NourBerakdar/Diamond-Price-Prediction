# Diamond Price Prediction Project:
In this project i train three models to predict price diamond that dependent on many features(weight ,quality of the cut,clarity ,length ,width,depth,...,etc).
i follow some steps to train these models :
1- read the data from kaggle (https://www.kaggle.com/competitions/shai-club).
2- visulize this data.
3-remove duplicate data or rows,faulty values( dimensionless[2-D or 1-D] diamonds ),and outliers using IQR.
4-apply ordinal encoder on categories data and data scaling 
5-model training[linera regression,decision tree,random forest]
6-fine tunning model(grid_search )

The RMSE ( Root Mean Squared Error) of final model is 131.24048666283161.
