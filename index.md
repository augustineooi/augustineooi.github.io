# Portfolio

---

## Data Science

### Loan Default Prediction

[![](https://img.shields.io/badge/Jupyter-Open%20Notebook-F37626?logo=Jupyter)](https://github.com/augustineooi/portfolio_loan_default/blob/35cc81384382f357e7973a6702eb1088fb58a87c/Loan_Default_Prediction_v1.ipynb)

- The goal of the project is to identify potential defaulters based on given data about applicants. The dataset used is provided by the fintech firm Home Credit, and includes a myriad of behavioral and  traditional financial data. Some of the key challenges are: (1) large numbers of features - raw data has 120+ features with the potential to balloon drastically when categorical data is converted to numerical via one-hot encoding), (2) highly imbalanced dataset – ratio of defaulters to non-defaulters are around 1:9, (3) features in the raw dataset is not highly correlated with the target variable.

- To tackle this problem I first employed Phi-K Correlation to provide a guidance for feature selection. Based on the correlation coefficient matrix generated, I narrowed down features for data modelling by 80%. I also experimented with various methods to improve the performance of the model, including balancing the datasets (best was by random undersampling followed by oversampling with SMOTE), standardization and dimensionality reduction using Principal Component Analysis (PCA), and using different classification algorithms (logistic regression, random forest classifier), as well as feature engineering.

- In conclusion, I found that the model performs best when the data has been balanced, and can be drastically sped up by using data that is dimensionally reduced. Using a Logistic Regression model, I achieved ROC-AUC score of 0.6.

<img src="images/loan_default_pic.png?raw=true"/>

---

### Entertainment Engine

[![](https://img.shields.io/badge/Jupyter-Open%20Notebook-F37626?logo=Jupyter)](https://github.com/augustineooi/portfolio_entertainment_engine/blob/711e193e260014274cad5e01cb08927fb1ff44f9/Entertainment_Engine_v1.ipynb)

- The goal of this project is to create a clean dataset that allows for visualizations of contents provided by 4 streaming platforms (Netflix, Amazon Prime, Disney+, Hulu), so that differences can be easily analyzed. A movie recommender is also created which enables the user to see a list of recommended shows and platforms they are on. The visualizations and recommender are aimed to help the user make a more informed decision on which platform to subscribe to.

- As part of data wrangling I aggregated 5 datasets consisting of content information from streaming platforms, and cleaned the data (including unifying features of duplicated titles, logical grouping of maturity ratings and genre, one-hot encoding of genres).

- Based on the cleaned dataset I came up with visualizations that allows the analysis of difference in platforms (volume of titles offered, genre specialization, proportion of new shows offered, etc).

- For the movie recommender, I vectorized the features and description of each show content into a format that machines can understand using Term Frequency – Inverse Document Frequency (TF-IDF). I then compared the differences between show contents based on Cosine Similarity. Shows that are highly similar on this measure are recommended to the user.


<img src="images/entertainment_engine_pic.png?raw=true"/>

---

### Bank Direct Marketing Outcome Prediction

[![](https://img.shields.io/badge/Jupyter-Open%20Notebook-F37626?logo=Jupyter)](https://github.com/augustineooi/portfolio_bank_marketing/blob/d98648a7d0d12f1098b55a5a3d1fa1dead81e4a4/Bank_Marketing_v1.ipynb)

- A supervised classification problem where the goal is to predict if a customer will subscribe to a term deposit, based on 20 input features consisting of consumer, marketing campaign and economic data. The data is also highly imbalanced.

- I performed comprehensive EDA to understand important variables, handled missing values using imputation, scaled the features, balanced the data using oversampling with SMOTE, and reduced the dimension of the dataset using PCA. The resulting dataset is fed into Logistic Regression models to predict the effectiveness of a marketing campaign.

- My best model achieved an ROC-AUC of 0.93.

<img src="images/bank_marketing_pic.png?raw=true"/>

---

## Visualization

### Streaming Entertainment Platforms

[![](https://img.shields.io/badge/Tableau-See%20Viz-E97627?logo=Tableau)]
(https://public.tableau.com/views/Entertainment_Platform_Viz/Entertainment_Viz?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

- Data preparation include using Tableau Prep to amalgamate 5 different data tables, rationalizing movie genres and age ratings, as well as creating a new parameter to store the rationalized genres. The method enables different genres to be selected and calculated fields presented (e.g. IMDB ratings by a certain genre).

<img src="images/viz_entertainment_pic.png?raw=true"/>

---

## Python Coding

### Vehicle Rent Program

[![](https://img.shields.io/badge/Python-See%20Code-3776AB?logo=Python)](https://github.com/augustineooi/python_vehicle_reg/blob/a8a99f7ef9a5379a4e14f86be19f6d26d27c7fdb/Vehicle_Rental.py)

- Implemented a Vehicle Rent Program capable of maintaining reservations for a vehicle rental agency. Designed using object-oriented method and UML diagrams.

<img src="images/python_vehicle_pic.png?raw=true"/>

---

### Tic-Tac-Toe Game

[![](https://img.shields.io/badge/Python-See%20Code-3776AB?logo=Python)](https://github.com/augustineooi/python_tictactoe/blob/c9036e487915e8ed08afefb4b8eb7b8e6c7991a3/TicTacToe_OOI.py)

- Built a tic-tac-toe game for 1 or 2 players. The single-player plays against the AI, which plays the game based on the minimax search algorithm.

<img src="images/python_tictactoe_pic.png?raw=true"/>

---
