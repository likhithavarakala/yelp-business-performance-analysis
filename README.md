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

## Analysis

### Data Loading and Preprocessing

The Yelp dataset is loaded into PySpark, and various libraries are imported. The Spark Session is initialized, and data preprocessing techniques are applied.

### Exploratory Data Analysis (EDA)

he Yelp dataset is loaded into PySpark, and various libraries are imported. The Spark Session is initialized, and data preprocessing techniques are applied.

### Exploratory Data Analysis (EDA)

EDA techniques are applied to gain initial insights into the dataset. This involves examining summary statistics, visualizing distributions of ratings and review counts, and exploring categories.

1. **Average Rating by Organization:**
   - The dataset is grouped by organization, and the average rating for each organization is calculated.

2. **Top 10 Most Reviewed Businesses:**
   - The dataset is grouped by organization and sorted in decreasing order of the number of reviews received.

3. **Popular Categories by Review Count:**
   - The dataset is analyzed to determine the most popular categories based on the number of reviews received.

4. **Average Rating for Each Category:**
   - The dataset is analyzed to determine the average rating for each category.

5. **Distribution of Yelp Businesses by Category:**
   - The analysis involves aggregating the counts of businesses by category and sorting the results.

6. **Distribution of Ratings:**
   - A subset of the dataset consisting of the 'rating' column is used to create a histogram.

7. **Top 20 Organizations Count by City:**
   - The count of organizations based on the city is calculated, and a bar graph is generated.

### Clustering Analysis

The k-means algorithm is utilized to conduct clustering analysis based on the rating and number of reviews.

1. **Cluster Analysis: Rating vs. Number of Reviews:**
   - A scatter plot is generated to visually represent the distribution of data points across different clusters.

   - Cluster 0 Center: [Rating: 2.72, Number of Reviews: 26.49]
   - Cluster 1 Center: [Rating: 4.06, Number of Reviews: 2314.81]
   - Cluster 2 Center: [Rating: 3.98, Number of Reviews: 523.50]

## What Worked

- The PySpark framework provided efficient and scalable processing capabilities for handling the large-scale Yelp dataset.
- EDA techniques allowed for a comprehensive exploration of the dataset, providing initial insights into the data's characteristics.
- Analytical tasks, such as calculating average ratings and analyzing category distributions, were successfully executed.

## What Did Not Work and Why Not

- Data quality issues: Incomplete or inaccurate data in the Yelp dataset could impact the reliability of the analysis results.
- Complexity of relationships: Unraveling complex relationships between variables influencing business success may require more advanced analytical techniques or additional data sources.
- Limitations in external factors: The analysis may not fully account for external factors such as economic conditions or industry dynamics, which can influence business success.

## Conclusion

Throughout the project, the experience of working with PySpark for analyzing the Yelp dataset was insightful and valuable. The findings and insights derived from the analysis provided meaningful information about the organizations, ratings, reviews, categories, cities, and states in the dataset.

### Key Conclusions:
   - The analysis revealed the top-rated organizations, allowing for recognition of businesses that consistently received positive reviews.
   - Understanding the distribution of ratings and reviews provided insights into customer sentiments and satisfaction levels.
   - Exploring the most common categories helped identify popular business types and industry trends.

