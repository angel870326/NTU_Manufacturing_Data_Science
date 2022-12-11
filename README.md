# NTU_Manufacturing_Data_Science

|Assignment|Questions|References|
|---|---|---|
|Assignment 1|1. Linear Regression Analysis for Wine Quality<br/>2. Association Rule - Market Basket Analysis<br/>3. Manufacturing System Analysis|[Association Rules](http://rasbt.github.io/mlxtend/user_guide/frequent_patterns/association_rules/) <br/>[Apriori](http://rasbt.github.io/mlxtend/user_guide/frequent_patterns/apriori/) <br/>[Apriori 完整中文教學](https://artsdatascience.wordpress.com/2019/12/10/python-%E5%AF%A6%E6%88%B0%E7%AF%87%EF%BC%9Aapriori-algorithm/)
|Assignment 2|1. 維度的詛咒<br/>2. 資料品質 (Data Quality)<br/>3. 決策支援<br/>4. 遺漏值填補 (Missing Value Imputation)<br/>5. 線性分類器 (Linear Classifier)||
|Assignment 3|1. Decision Tree Algorithms<br/>2. Feature Selection<br/>3. Deep Learning|[Missing value imputation](https://towardsdatascience.com/imputing-missing-data-with-simple-and-advanced-techniques-f5c7b157fb87)<br/>[Cross validation & Decision trees in sklearn](https://stackoverflow.com/questions/35097003/cross-validation-decision-trees-in-sklearn)<br/>[GridSearchCV with multiple evaluation metrics](https://scikit-learn.org/stable/auto_examples/model_selection/plot_multi_metric_evaluation.html)<br/>[Gradient Boosting](https://machinelearningmastery.com/gradient-boosting-with-scikit-learn-xgboost-lightgbm-and-catboost/)<br/>[Stepwise regression](https://github.com/AakkashVijayakumar/stepwise-regression)<br/>[Lasso regression for feature selection](https://machinelearninghd.com/lasso-regression-in-python/)<br/>[Sort correlation matrix](https://www.geeksforgeeks.org/sort-correlation-matrix-in-python/)<br/><br/>Handwritten Digit Recognition with Python & CNN (Keras):<br/>1. [Simple ver.](https://techvidvan.com/tutorials/handwritten-digit-recognition-with-python-cnn/)<br/>2. [Complete ver. (with evaluation)](https://medium.com/analytics-vidhya/deep-learning-project-handwritten-digit-recognition-using-python-26da7ed11d1c)<br/>3. [Complete ver. (with evaluation & improving methods)](https://machinelearningmastery.com/how-to-develop-a-convolutional-neural-network-from-scratch-for-mnist-handwritten-digit-classification/)|
|Assignment 4|1. Data Imbalance Problem<br/>2. Metaheuristic Algorithms<br/>3. Markov Decision Process<br/>|Tabu Search for Single Machine Total Weighted Tardiness Problem: <br/>1. [Medium Tutorial](https://medium.com/swlh/tabu-search-in-python-3199c44d44f1)<br/>2. [Github code](https://github.com/taylankabbani/Metaheuristic-Algorithms-for-SMTWTP)<br>Genetic Algorithm for Flow Shop Scheduling Problem: <br>1. [Tutorial in Mandarin](https://github.com/wurmen/Genetic-Algorithm-for-Job-Shop-Scheduling-and-NSGA-II/blob/master/implementation%20with%20python/GA-flowshop/GA%20for%20flow%20shop%20problem.md)<br>2. [Github code](https://github.com/wurmen/Genetic-Algorithm-for-Job-Shop-Scheduling-and-NSGA-II/blob/master/implementation%20with%20python/GA-flowshop/GA_flowshop_tardyjob.py)|




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

