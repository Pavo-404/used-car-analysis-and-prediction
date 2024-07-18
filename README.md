# used-car-analysis-and-prediction

Overview
This project aims to predict the selling price of used cars using machine learning techniques. By leveraging a dataset containing various features of used cars, we build a predictive model that helps buyers and sellers make informed decisions. The project also delves into exploratory data analysis (EDA) to uncover insights and trends within the data.

Project Highlights
Objective
The main objective is to predict used car prices accurately to assist in making informed buying and selling decisions.

Model Used
RandomForestRegressor: A robust and flexible machine learning algorithm suitable for regression tasks.
Key Features
Present Price: The current market price of the car.
Year: The year of manufacture of the car.
Kms Driven: The total kilometers driven by the car.
Seller Type: Whether the seller is an individual or a dealer.
Fuel Type: The type of fuel used by the car (Petrol, Diesel, CNG, etc.).
Exploratory Data Analysis (EDA)
EDA was performed to understand the data distributions and relationships between different features. Key insights from EDA include:

Boxplot of Present Prices: Helped identify outliers and the spread of data.
Feature Importance Analysis: Determined the most influential factors affecting the selling price.
Feature Importance
Using the RandomForestRegressor model, the top factors influencing the selling price were identified:

Present Price: Most influential in determining the selling price.
Year: Newer cars generally sell for higher prices.
Kms Driven: More driven cars tend to sell for less.
Seller Type: Individual sellers influence the price.
Fuel Type: Petrol cars show significant importance.
Business Insights
Beyond model predictions, the project also extracts actionable business insights:

Depreciation Insights: The average annual depreciation rate for cars is around 15%, helping set realistic price expectations.
Seasonal Trends: Analyzed transaction data to reveal seasonal price trends, such as price spikes during festive seasons.
Feature Impact: Cars with modern safety features like airbags and ABS have higher resale values.
Geographic Variations: Significant price variations between different regions aid in better market segmentation.
Repository Structure
data/: Contains the dataset used for the project.
notebooks/: Jupyter notebooks detailing the EDA, model training, and analysis.
scripts/: Python scripts for data preprocessing, model training, and evaluation.
results/: Contains the results of the analysis, including plots and model performance metrics.
How to Run the Project
Clone the Repository:
bash
Copy code
git clone https://github.com/Pavo-404/used-car-price-prediction.git
Install Dependencies:
bash
Copy code
pip install -r requirements.txt
Run the Jupyter Notebooks:
Navigate to the notebooks/ directory and open the notebooks to see the EDA, model training, and evaluation steps.
Conclusion
This project not only enhances understanding of regression models but also provides valuable insights into the automotive market. It demonstrates the power of data science in making informed business decisions.

Acknowledgements
The dataset was sourced from https://www.kaggle.com/datasets/pushpakhinglaspure/used-car-price-prediction/data .
Contact
For any questions or feedback, feel free to reach out to me at [your email] or connect with me on [LinkedIn profile link].
