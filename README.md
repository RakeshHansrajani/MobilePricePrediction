# Mobile Price Range Prediction
### Abstract
In the competitive mobile phone market, accurately estimating the price range of mobile devices is crucial for a new company to gain a competitive edge. This project focuses on predicting the price range of mobile phones based on their features, such as battery power, clock speed, camera specifications, memory, weight, and more. The K-Nearest Neighbors (KNN) algorithm will be utilized to accomplish this task. By establishing a relationship between the mobile phone features and their selling price, the company can make informed decisions about pricing their products.

### Problem Statement
The objective of this project is to predict the price range of mobile phones using the K-Nearest Neighbors algorithm. The CEO of a new mobile phone company seeks to estimate the prices of the mobile devices the company creates. By analyzing the sales data of mobile phones from various companies, the CEO aims to identify the relationship between the features of a mobile phone (e.g., RAM, internal memory) and its selling price. The KNN algorithm will be employed to predict the price range of a mobile phone based on its features.

### Dataset Information
The dataset consists of several predictor variables and one target variable, price_range. The target variable represents the price range of the mobile phone, categorized as 0 (low cost), 1 (medium cost), 2 (high cost), and 3 (very high cost). 
The dataset includes the following columns:

1. battery_power: Total energy a battery can store in one time measured in mAh
2. clock_speed: Speed at which the microprocessor executes instructions
3. fc: Front camera megapixels
4. int_memory: Internal memory in gigabytes
5. m_dep: Mobile depth in cm
6. mobile_wt: Weight of the mobile phone
7. n_cores: Number of cores of a processor
8. pc: Primary camera megapixels
9. px_height: Pixel resolution height
10. px_width: Pixel resolution width
11. ram: Random access memory in megabytes
12. sc_h: Screen height of mobile in cm
13. sc_w: Screen width of mobile in cm
14. talk_time: Longest time that a single battery charge will last when in use
15. price_range: Price range of the mobile phone (0: low cost, 1: medium cost, 2: high cost, 3: very high cost)

### Scope
This project will involve the following steps:<br>
**Data Pre-processing**: We will understand the basic structure and perform necessary data cleaning, handling missing values, handling duplicate values.<br>
**Exploratory Data Analysis (EDA)**: We will conduct an initial exploration of the dataset to perform Univariate, Bivariate, Multivariate Analysis and find patterns in the data. Also, we will treat outliers. <br>
**Training Models**: We have created user-defined functions which will ease our process of training dataset. We will train K Nearest Neighbour Machine learning algorithms with different tunning parameters to predict the price range of mobiles based on the provided features.<br>
**Model Evaluation**: We will tabulate and evaluate the performance of all trained models using appropriate evaluation metrics and assess their predictive capabilities.<br>
**Learning Outcome**: Through this project, you will gain a better understanding of exploratory data analysis, data preprocessing, and knowledge of various machine learning algorithms. You will also develop skills in model evaluation, and drawing insights from the results.<br>

### Conclusion
Completing this project will enhance your ability to analyze data related to mobile phones, build classification models to predict price range, and evaluate model performance using various metrics. By understanding the relationship between mobile phone features and their price range, you can assist the CEO in making informed pricing decisions for the company's products. This project will provide practical knowledge of EDA, data preprocessing, and the K-Nearest Neighbors algorithm. The ability to accurately predict the price range of mobile phones is crucial for success in the highly competitive mobile market.
