# Portfolio

---

## Data Science

### Loan Default Prediction

[![](https://img.shields.io/badge/Jupyter-Open%20Notebook-F37626?logo=Jupyter)](https://github.com/augustineooi/portfolio_loan_default/blob/35cc81384382f357e7973a6702eb1088fb58a87c/Loan_Default_Prediction_v1.ipynb)

- The goal of the project is to identify potential defaulters based on given data about applicants. The dataset used is provided by the fintech firm Home Credit, and includes a myriad of behavioral and  traditional financial data. Some of the key challenges are: (1) large numbers of features - raw data as 120+ features which has the potential to balloon drastically when categorical data is converted to numerical via one-hot encoding), (2) highly imbalanced dataset – ratio of defaulters to non-defaulters are around 1:9, (3) features in the raw dataset is not highly correlated with the target variable.

- To tackle this problem I first employed Phi-K Correlation (which is able to generate correlation amongst categorical data) to provide a guidance for feature selection. Based on the correlation coefficient matrix generated, I narrowed down features for data modelling by 80%. I also experimented with various methods to improve the performance of the model, including balancing the datasets (best was by random undersampling followed by oversampling with SMOTE), standardization and dimensionality reduction using PCA, and using different classification algorithms (logistic regression, random forest classifier), as well as feature engineering.

- In conclusion, I found that the model performs best when the data has been balanced, and can be drastically sped up by using data that is dimensionally reduced. Using a Logistic Regression model, I achieved ROC-AUC score of 0.6.

<img src="images/loan_default_pic.png?raw=true"/>

---

### Entertainment Engine

[![](https://img.shields.io/badge/Jupyter-Open%20Notebook-F37626?logo=Jupyter)](https://github.com/augustineooi/portfolio_entertainment_engine/blob/711e193e260014274cad5e01cb08927fb1ff44f9/Entertainment_Engine_v1.ipynb)

- The goal of this project is to create a clean dataset that allows for visualizations of contents provided by 4 streaming platforms (Netflix, Amazon Prime, Disney+, Hulu) so that differences can be easily analyzed. A movie recommender is also created which enables the user to see a list of recommended shows and platforms they are on. The visualizations and recommender are aimed to help the user make a more informed decision on which platform to subscribe to.

- As part of data wrangling I aggregated 5 datasets consisting of content information from streaming platforms, and cleaned the data (including unify features of duplicated titles, logical grouping of maturity ratings and genre, one-hot encoding of genres).

- Based on the cleaned dataset came up with visualizations that allows the analysis of difference in platforms (volume of titles offered, genre specialization, proportion of new shows offered, etc).

- For the movie recommender system, I vectorized the features and description of each show content into a format that machines can understand using Term Frequency – Inverse Document Frequency (TF-IDF). I then compared the differences between the different show contents based on the measure of Cosine Similarity. Shows that are highly similar on this measure are recommended to the user.


<img src="images/entertainment_engine_pic.png?raw=true"/>

---

### Bank Direct Marketing Outcome Prediction

[![](https://img.shields.io/badge/Jupyter-Open%20Notebook-F37626?logo=Jupyter)](https://github.com/augustineooi/portfolio_bank_marketing/blob/d98648a7d0d12f1098b55a5a3d1fa1dead81e4a4/Bank_Marketing_v1.ipynb)

- A supervised classification problem where the goal is to predict if a customer will subscribe to a term deposit based on 20 input features consisting of consumer, marketing campaign and economic data. The data is also highly imbalanced.

- I performed comprehensive EDA to understand important variables, handled missing values using imputation, scaled the features, balanced the data using oversampling with SMOTE, and reduced the dimension of the dataset using PCA. The resulting dataset is fed into Logistic Regression models to predict the effectiveness of a marketing campaign.

- My best model achieved an ROC-AUC of 0.93.

<img src="images/bank_marketing_pic.png?raw=true"/>

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
