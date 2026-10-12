# Project 2 – Exploratory Data Analysis (EDA)

## Description

This project focuses on performing Exploratory Data Analysis (EDA) on a cleaned dataset using Python in Google Colab.

The purpose of the analysis is to understand patterns, trends, distributions, and relationships within the dataset. The analysis also identifies potential outliers and summarizes important observations.

## Dataset

The analysis uses the cleaned dataset generated from Project 1:

Cleaned_Dataset.csv

The dataset contains e-commerce order information such as:

* OrderID
* Date
* CustomerID
* Product
* Quantity
* UnitPrice
* ShippingAddress
* PaymentMethod
* OrderStatus
* TrackingNumber
* ItemsInCart
* CouponCode
* ReferralSource
* TotalPrice

## EDA Operations

### 1. Data Loading and Inspection

The dataset is loaded into Google Colab using Python and Pandas.

The dataset is inspected to understand:

* Number of rows and columns
* Column names
* Data types
* Missing values
* Basic structure of the dataset

### 2. Descriptive Statistics

Basic statistical measures are calculated for numerical columns, including:

* Count
* Mean
* Median
* Minimum
* Maximum
* Standard deviation

Important numerical columns include:

* Quantity
* UnitPrice
* ItemsInCart
* TotalPrice

### 3. Data Distribution Analysis

The distributions of numerical variables are analyzed to understand how the values are spread across the dataset.

Examples include:

* Quantity distribution
* Unit price distribution
* Total price distribution
* Items in cart distribution

### 4. Trend Analysis

The dataset is analyzed to identify trends and patterns such as:

* Sales trends over time
* Product-wise order patterns
* Order status distribution
* Payment method usage
* Referral source patterns
* Coupon usage

### 5. Outlier Detection

Potential outliers are identified in numerical columns such as:

* Quantity
* UnitPrice
* ItemsInCart
* TotalPrice

Statistical analysis and visualizations are used to identify unusually high or low values.

### 6. Data Visualization

Visualizations are created to make patterns and trends easier to understand.

The analysis may include:

* Histograms
* Bar charts
* Box plots
* Line charts
* Distribution plots

### 7. Key Observations

The results are summarized to identify meaningful insights from the dataset, including:

* Frequently ordered products
* Common payment methods
* Distribution of order statuses
* High-value orders
* Sales trends over time
* Common referral sources
* Coupon usage patterns

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn

## How to Run

### 1. Open Google Colab

Open the project notebook in Google Colab.

### 2. Upload the Dataset

Upload the following file to the Colab environment:

Cleaned_Dataset.csv

### 3. Install Required Libraries

If required, run:

!pip install pandas numpy matplotlib seaborn


### 4. Run the Notebook

Run the cells in the Google Colab notebook from top to bottom.

The notebook will:

1. Load the dataset.
2. Inspect the data.
3. Calculate descriptive statistics.
4. Analyze distributions.
5. Identify trends.
6. Detect outliers.
7. Generate visualizations.
8. Summarize key observations.


## Key Skills

* Exploratory Data Analysis
* Python
* Google Colab
* Pandas
* NumPy
* Descriptive Statistics
* Data Visualization
* Trend Analysis
* Outlier Detection
* Analytical Thinking
* Data Interpretation

## Project Goal

The goal of this project is to analyze the cleaned dataset and convert the data into meaningful insights by studying statistics, distributions, trends, and outliers.
