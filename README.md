# Diamond Price Prediction Project:
In this project i train three models to predict price diamond that dependent on many features(weight ,quality of the cut,clarity ,length ,width,depth,...,etc).
** I follow some steps to train these models :
*  read the data from kaggle (https://www.kaggle.com/competitions/shai-club).
*  visulize this data.
* remove duplicate data or rows,faulty values( dimensionless[2-D or 1-D] diamonds ),and outliers using IQR.
* apply ordinal encoder on categories data and data scaling .
* model training[linera regression,decision tree,random forest].
* fine tunning model(grid_search ).

The RMSE ( Root Mean Squared Error) of final model is 131.24048666283161.
