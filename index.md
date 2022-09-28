## Portfolio

---

### Data Science

#### Loan Default Prediction

[![](https://img.shields.io/badge/Jupyter-Open%20Notebook-F37626?logo=Jupyter)](https://github.com/augustineooi/portfolio_loan_default/blob/35cc81384382f357e7973a6702eb1088fb58a87c/Loan_Default_Prediction_v1.ipynb)

- The goal of the project is to identify potential defaulters based on given data about applicants. The dataset used is provided by the fintech firm Home Credit, and includes a myriad of behavioral and  traditional financial data. Some of the key challenges are: (1) large numbers of features - raw data as 120+ features which has the potential to balloon drastically when categorical data is converted to numerical via one-hot encoding), (2) highly imbalanced dataset – ratio of defaulters to non-defaulters are around 1:9, (3) features in the raw dataset is not highly correlated with the target variable.

- To tackle this problem I first employed Phi-K Correlation (which is able to generate correlation amongst categorical data) to provide a guidance for feature selection. Based on the correlation coefficient matrix generated, I narrowed down features for data modelling by 80%. I also experimented with various methods to improve the performance of the model, including balancing the datasets (best was by random undersampling followed by oversampling with SMOTE), standardization and dimensionality reduction using PCA, and using different classification algorithms (logistic regression, random forest classifier), as well as feature engineering.

- In conclusion, I found that the model performs best when the data has been balanced, and can be drastically sped up by using data that is dimensionally reduced. Using a Logistic Regression model, I achieved ROC-AUC score of 0.6.

<img src="images/loan_default_pic.png?raw=true"/>

---
[Project 2 Title](/pdf/sample_presentation.pdf)
<img src="images/dummy_thumbnail.jpg?raw=true"/>

---
[Project 3 Title](http://example.com/)
<img src="images/dummy_thumbnail.jpg?raw=true"/>

---

### Python Coding

- [Project 1 Title](http://example.com/)
- [Project 2 Title](http://example.com/)
- [Project 3 Title](http://example.com/)
- [Project 4 Title](http://example.com/)
- [Project 5 Title](http://example.com/)

---




---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
