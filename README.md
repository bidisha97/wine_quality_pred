# wine_quality_pred
This dataset consists of two kinds of wine which are; red and white wine. Both the dataset is emerged to create a better classification model.
At first it has been compared with both kinds of wine using data visualization and then implemented Logistic Regression. We are fortunate that the dataset does not have any missing values to deal with. Quality of score varies for red and white wine. As this is a multi-class model we have to encode features for a better outcome.
Therefore we have created dummy feature for the target variable as good and bad quality of wines. The problem that we faced with this dataset is multi-collinearity
and over-fitting of trainning dataset. At the  end we have applied K-fold Cross Validation and got a score of 77%.
Features which have significant effect on the quality of wine are residual sugar level, presence of alcohol,fixed acidity and citric acid.
