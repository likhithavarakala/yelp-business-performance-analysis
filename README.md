# Yelp Business Performance Analysis
## Summary

This project aimed to analyze the Yelp dataset using PySpark, Spark SQL, and various data analysis techniques. The steps involved in the project included data preprocessing, exploratory data analysis, clustering, aggregation, and visualization. The purpose was to gain insights into the Yelp dataset and uncover meaningful patterns and trends related to organizations, ratings, reviews, categories, cities, and states.

## Dataset Information

**Columns:**
- ID: Unique identifier for each entry
- Time_GMT: Time of the entry in GMT
- Phone: Phone number associated with the business
- Organization: Name or organization associated with the business
- OLF: Unknown variable
- Rating: Average rating given to the business
- NumberReview: Total number of reviews for the business
- Category: Category or type of business (e.g., restaurant)
- Country: Country where the business is located
- CountryCode: Country code of the business location
- State: State or province where the business is located
- City: City where the business is located
- Street: Street address of the business
- Building: Building number or identifier associated with the business

## Problem Statement

The problem being addressed in the analysis of the Yelp dataset is to understand the factors that contribute to the success of businesses on Yelp. By exploring the dataset and performing various analyses, the goal is to uncover insights that can guide business owners in enhancing their performance, improving customer satisfaction, and ultimately achieving success on the Yelp platform.

## Benefits

1. **Business Performance Improvement:** The analysis helps businesses identify areas of strength and weakness, allowing them to focus on improving their products, services, or customer experience.
2. **Customer Satisfaction Enhancement:** Understanding the factors that drive positive ratings and reviews enables businesses to tailor their offerings to meet customer expectations and preferences.
3. **Competitive Advantage:** Uncovering patterns and trends in the dataset provides businesses with a competitive edge by identifying opportunities or niches that have been overlooked.

## Drawbacks

1. **Data Limitations:** The analysis relies on the quality and completeness of the Yelp dataset. Inaccurate or missing data can impact the reliability of the findings.
2. **External Factors:** The analysis is limited to the Yelp dataset and may not account for external factors that influence business success, such as economic conditions or industry dynamics.

## Challenges

1. **Big Data Processing:** Handling a large dataset like Yelp's with millions of rows requires efficient big data processing techniques, such as distributed computing using tools like PySpark.
2. **Data Preprocessing:** Preparing the Yelp dataset for analysis involves dealing with missing values, data cleaning, and transforming the data into a suitable format.
3. **Complex Relationships:** Unraveling the complex relationships and interactions between various factors affecting business success on Yelp can be challenging.

## Tools and Techniques Used

In the project, several tools and techniques were used to analyze the Yelp dataset:

1. **PySpark:** Python API for Apache Spark, chosen for scalable and distributed data processing.
2. **Spark SQL:** Module in Apache Spark for working with structured and semi-structured data using SQL-like syntax.
3. **DataFrame API:** Provides a tabular data structure for easy manipulation and analysis of structured data.
4. **Data Preprocessing Techniques:** Applied to clean and transform the raw Yelp dataset before analysis.
5. **Exploratory Data Analysis (EDA):** Techniques used to gain initial insights into the Yelp dataset.
6. **Aggregation and Statistical Functions:** Used for summarizing and analyzing the Yelp dataset.
7. **Clustering Algorithm (K-Means):** Applied for identifying separate clusters in the dataset based on ratings and reviews.

## Installations

Here is a step-by-step guide for installing PySpark and Jupyter on a computer that already has Java Development Kit and Spark:

1. **Install PySpark:**
   - Open a terminal or command prompt and install PySpark using `pip install pyspark`.

2. **Install Jupyter Notebook:**
   - Install Jupyter Notebook using `pip install jupyter`.

3. **Launch Jupyter Notebook:**
   - Open a terminal or command prompt, navigate to the directory where you want to start Jupyter Notebook, and run `jupyter notebook`.

4. **Create a New Notebook:**
   - In Jupyter Notebook, click on "New" and select "Python 3" to create a new notebook.

## Analysis

### Data Loading and Preprocessing

The Yelp dataset is loaded into PySpark, and various libraries are imported. The Spark Session is initialized, and data preprocessing techniques are applied.

### Exploratory Data Analysis (EDA)

EDA techniques are applied to gain initial insights into the dataset. This involves examining summary statistics, visualizing distributions
