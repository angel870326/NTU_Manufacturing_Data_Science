# NTU_Manufacturing_Data_Science

|Assignment|Questions|References|
|---|---|---|
|Assignment 1|1. Linear Regression Analysis for Wine Quality<br/>2. Association Rule - Market Basket Analysis<br/>3. Manufacturing System Analysis|[Association Rules](http://rasbt.github.io/mlxtend/user_guide/frequent_patterns/association_rules/) <br/>[Apriori](http://rasbt.github.io/mlxtend/user_guide/frequent_patterns/apriori/) <br/>[Apriori 完整中文教學](https://artsdatascience.wordpress.com/2019/12/10/python-%E5%AF%A6%E6%88%B0%E7%AF%87%EF%BC%9Aapriori-algorithm/)
|Assignment 2|1. 維度的詛咒<br/>2. 資料品質 (Data Quality)<br/>3. 決策支援<br/>4. 遺漏值填補 (Missing Value Imputation)<br/>5. 線性分類器 (Linear Classifier)||
|Assignment 3|1. Decision Tree Algorithms<br/>2. Feature Selection<br/>3. Deep Learning|[Missing value imputation](https://towardsdatascience.com/imputing-missing-data-with-simple-and-advanced-techniques-f5c7b157fb87)<br/>[Cross validation & Decision trees in sklearn](https://stackoverflow.com/questions/35097003/cross-validation-decision-trees-in-sklearn)<br/>[GridSearchCV with multiple evaluation metrics](https://scikit-learn.org/stable/auto_examples/model_selection/plot_multi_metric_evaluation.html)<br/>[Gradient Boosting](https://machinelearningmastery.com/gradient-boosting-with-scikit-learn-xgboost-lightgbm-and-catboost/)<br/>[Lasso regression for feature selection](https://machinelearninghd.com/lasso-regression-in-python/)|

## Convert google colab jupyter notebook (.ipynb) to HTML
```
from google.colab import drive
drive.mount("/content/gdrive")
```
```
%%shell
jupyter nbconvert --to html ///content/gdrive/MyDrive/....../MDS_Assignment1.ipynb
```
Output: <br/>
[NbConvertApp] Converting notebook ///content/gdrive/MyDrive/....../MDS_Assignment1.ipynb to html <br/>
[NbConvertApp] Writing 662641 bytes to ///content/gdrive/MyDrive/....../MDS_Assignment1.html

