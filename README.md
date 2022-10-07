# NTU_Manufacturing_Data_Science

|Assignment|Questions|References|
|---|---|---|
|Assignment 1|1. Linear Regression Analysis for Wine Quality<br/>2. Association Rule - Market Basket Analysis<br/>3. Manufacturing System Analysis|[Association Rules](http://rasbt.github.io/mlxtend/user_guide/frequent_patterns/association_rules/) <br/>[Apriori](http://rasbt.github.io/mlxtend/user_guide/frequent_patterns/apriori/) <br/>[Apriori 完整中文教學](https://artsdatascience.wordpress.com/2019/12/10/python-%E5%AF%A6%E6%88%B0%E7%AF%87%EF%BC%9Aapriori-algorithm/)


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

