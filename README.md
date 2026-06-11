# Gurgaon Real Estate Market Analysis

## Project Overview

This project analyzes residential apartment listings in Gurgaon, India, to identify the key factors influencing property prices and uncover actionable business insights for real estate stakeholders.

The analysis goes beyond descriptive statistics by applying data cleaning, feature engineering, market segmentation, correlation analysis, and multivariate exploration to understand how property characteristics impact valuation.

A major objective of this project is to distinguish between factors that drive pricing in standard residential properties versus luxury properties.

---

## Business Problem

Real estate listings contain large amounts of information, but it is often unclear which factors truly drive property prices.

This project answers questions such as:

* What factors have the strongest influence on property prices?
* Does property size affect luxury and standard properties equally?
* Which societies command premium valuations?
* How do bedrooms, bathrooms, and area types impact pricing?
* What differentiates luxury properties from the standard market?

---

## Dataset

The dataset contains residential apartment listings from Gurgaon and includes:

* Property Price
* Area (Sqft)
* Price per Sqft
* Bedrooms
* Bathrooms
* Balconies
* Floor Information
* Area Type
* Society
* Additional Property Attributes

---

## Project Workflow

### 1. Data Understanding

* Data structure inspection
* Missing value assessment
* Duplicate detection
* Data quality review

### 2. Data Cleaning

* Price standardization
* Society name normalization
* Missing value treatment
* Duplicate removal
* Feature engineering

### 3. Exploratory Data Analysis

#### Univariate Analysis

* Price distribution
* Area distribution
* Bedrooms and bathrooms distribution
* Outlier investigation

#### Bivariate Analysis

* Price vs Society
* Price vs Area
* Price vs Area Type
* Price vs Market Segment

#### Correlation Analysis

* Relationship between numerical features and price
* Identification of key pricing drivers

#### Multivariate Analysis

* Area Type vs Market Segment vs Price
* Area vs Price by Market Segment
* Bedrooms and Bathrooms vs Property Price

### 4. Market Segmentation

Instead of removing high-price outliers, luxury properties were identified and separated into a dedicated market segment.

This approach preserved valuable business information while allowing comparison between:

* Standard Properties
* Luxury Properties

---

## Key Findings

* Society is one of the strongest drivers of property valuation.
* Property size is the strongest numerical predictor of price.
* Bathrooms have slightly stronger pricing influence than bedrooms.
* Area size is highly important in the standard market.
* Luxury property pricing depends more heavily on location and society prestige.
* Super Built-up Area properties achieve the highest median prices among area types.
* Properties with five bedrooms and six bathrooms record the highest median valuations.

---

## Business Recommendations

* Use property size as a primary pricing factor for standard residential units.
* Prioritize society and location when valuing luxury properties.
* Consider market segmentation when building pricing strategies.
* Focus premium marketing efforts on high-value societies.
* Incorporate property configuration and area type into valuation models.

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Jupyter Notebook

---

## Skills Demonstrated

* Data Cleaning
* Data Wrangling
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Correlation Analysis
* Business Analysis
* Market Segmentation
* Data Visualization
* Insight Generation
* Business Recommendation Development
