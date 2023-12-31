# Using AI to Predict Credit-Line Utilization	


# Project Description

This thesis project focuses on the predictive analysis of credit lines, particularly drawdown and utilization rates, leveraging the power of Artificial Intelligence (AI) techniques. We orchestrated a comprehensive approach, starting with the aggregation of multiple datasets. These datasets encompass a wide spectrum, including client loan records, historical client transactions, credit line data, credit card transactions, and supplementary data that provides additional context. Notably, some of these datasets are static in nature, while others are time-series data. However, we meticulously harmonized and standardized them, forging a unified and meticulously curated master dataset.

Conducting thorough Exploratory Data Analysis (EDA) is pivotal for project success. This phase allows us to glean insights into the data, uncover patterns, and discern specific features that influence credit lines. Our feature analysis encompassed various facets, scrutinizing factors that influence repayment difficulties, those connected to the extension of credit to clients, and those related to drawdown and utilization rates per loan.

Subsequently, we transition into predictive modelling, utilizing conventional statistical models like Linear Regression alongside more intricate methodologies such as Decision Trees, Random Forests, LightGBM, and Convolutional Dense Neural Networks.

Primary objective is to unearth the factors that shape and govern credit lines, including the nuanced interplay of financial and non-financial elements, even delving into sociological aspects. By harnessing the capabilities of AI and machine learning, we aspire to empower institutions with the tools they need to make well-informed decisions, particularly in the realm of credit risk assessment.

Datasets can be found here https://www.kaggle.com/c/home-credit-default-risk/data



## Installation
Project consists of .ipynb files and open-source datasets available on Kaggle. It can be set up using any Python IDE with access to additional computing power.

Due to the large amount of data, additional RAM and computing units is necessary to perform a lot of the operations in this code, both during EDA & Modelling.

The underlying datasets and information upon which this thesis was structured is available in open-source, everything discussed and conducted in this project is therefore publicly available and replicable.

```bash
# Clone the repository
git clone https://github.com/rs66023/Loan-Rate-Prediction-using-AI.git

# Navigate to the project directory
cd your-project

# Install dependencies (if any)
pip install -r requirements.txt
- 
