# Restaurant Data Analysis

## Project Overview

This repository contains the analysis of a restaurant dataset, which includes various insights and visualizations. The analysis covers multiple aspects such as popular cuisines, city-specific insights, price range distribution, online delivery impact, rating distribution, cuisine combinations, geographical patterns, restaurant chains, and votes analysis.

## Dataset

Number of records: 9551 row & 21 columns

The dataset includes various attributes of restaurants such as:

- Restaurant ID
- Restaurant Name
- City
- Address
- Locality
- Longitude
- Latitude
- Cuisines
- Average Cost for Two
- Currency
- Has Table booking
- Has Online delivery
- Is delivering now
- Switch to order menu
- Price range
- Aggregate rating
- Rating color
- Rating text
- Votes

## Tools

- Pandas: Data manipulation and analysis
- Matplotlib: Data visualization
- NumPy: Numerical operations
- Seaborn: Statistical data visualization
- Geopandas: Geospatial data manipulation
- Folium: Interactive maps
- Contextily (for geographical analysis)

## Tools and Techniques Used

### Data Analysis

1. **Pandas**: For data manipulation and analysis.
    - Loading the dataset.
    - Handling missing values.
    - Calculating statistics such as average ratings and vote counts.
    - Filtering and grouping data for specific analysis.

### Visualization

1. **Matplotlib**: For creating visualizations.
    - Histograms for rating distribution.
    - Bar charts for comparing average ratings.
    - Customizing plots with dark color schemes and gridlines.
    - Saving plots as images.

### Geographical Analysis

1. **Folium**: For plotting geographical data on maps.
    - Visualizing restaurant locations using longitude and latitude.
2. **Contextily** - for geographical analysis- Interactive maps

### Data Cleaning and Preparation

1. **Regular Expressions (re module)**: For cleaning and preprocessing text data.
    - Handling and cleaning address and cuisine data.

### Machine Learning (Geographical Clustering - Optional)

1. **Scikit-Learn (sklearn)**: For clustering analysis.
    - DBSCAN for identifying clusters in geographical data.

### Code Implementation

1. **Python**: General programming language used for the entire analysis.
    - Basic Python functions for iterating through datasets and performing calculations.
    - Conditional statements and loops for data filtering and processing.

## Analytical Methods

1. **Descriptive Statistics**
    - **Usage**: Summarizing data with metrics like mean, percentage, and frequency
    - **Example**: Calculating the average number of votes, average ratings, and percentages of online delivery
2. **Data Filtering and Grouping**
    - **Usage**: Extracting subsets of data and grouping by categories for detailed analysis
    - **Example**: Identifying the top cuisines, city-specific insights, and cuisine combinations
3. **Correlation Analysis**
    - **Usage**: Exploring relationships between variables
    - **Example**: Analyzing the correlation between votes and ratings
4. **Geographical Analysis**
    - **Usage**: Analyzing spatial patterns and distributions
    - **Example**: Plotting restaurant locations on a map using longitude and latitude

# Visual Summary:

- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical operations
- **Matplotlib**: Visualization (bar charts, histograms, scatter plots)
- **Seaborn**: Enhanced visualizations
- **Jupyter Notebook**: Interactive analysis and documentation

## Objectives

- Identify top cuisines and their prevalence.
- Determine cities with the most restaurants and highest average ratings.
- Analyze restaurant price categories.
- Compare ratings with and without online delivery.
- Examine common rating ranges and average votes.
- Identify popular cuisine pairs and their ratings.
- Map restaurant locations and identify clusters.
- Evaluate ratings and popularity of restaurant chains.
- Correlate votes with ratings to find trends.

# Key Insights(Analysis)

### 1. Popular Cuisines

- **Top Cuisines**: North Indian, Chinese, Fast Food
- **Percentage of Restaurants Serving Top Cuisines**: North Indian (28.7%), Chinese (14.6%), Fast Food (11.8%)![top_3_cuisines_horizontal](https://github.com/user-attachments/assets/d427ed7b-0ea7-41d8-84d6-2738f61ec8c6)


### 2. City Insights

- **City with Most Restaurants**: New Delhi
- **Average Rating by City**: New Delhi (3.9), Gurgaon (3.8), Noida (3.7)
- **City with Highest Average Rating**: New Delhi![top_cities_number_of_restaurants](https://github.com/user-attachments/assets/ea1997c8-34a6-4069-9392-af4bc97129ed)
![top_cities_avg_rating](https://github.com/user-attachments/assets/f4ca56a2-e8dc-4d3b-97b5-e542df236d94)


### 3. Price Range Distribution

- **Price Range Distribution**: See `price_range_distribution.png`![Percentage of Restaurants by Price Range](https://github.com/user-attachments/assets/04fd3615-9705-406b-a67f-933f53552a7a)


### 4. Online Delivery Impact

- **Restaurants Offering Online Delivery**: 52.3%
- **Average Rating with Online Delivery**: 3.8
- **Average Rating without Online Delivery**: 3.7
- **Visual**: `average_ratings_online_delivery.png`
![average_ratings_online_delivery](https://github.com/user-attachments/assets/50b18906-3099-4381-b4dc-3ecb2137ae7c)

### 5. Rating Distribution

- **Most Common Rating Range**: 3.5 - 4.0
- **Average Number of Votes**: 200
- **Visual**: `rating_distribution.png`![rating_distribution](https://github.com/user-attachments/assets/e146d7a0-d853-4383-bdb7-d17ceaa05c43)


### 6. Cuisine Combinations

- **Common Cuisine Combinations**:
    - North Indian, Chinese
    - Fast Food, Beverages
    - North Indian, Mughlai
- **Cuisine Combinations with Highest Ratings**:
    - North Indian, Chinese: 4.1
    - Fast Food, Beverages: 3.9
    - North Indian, Mughlai: 4.0![cuisine combinations ratings](https://github.com/user-attachments/assets/3c7ddadb-77ec-44a6-8987-1a0df5087321)


### 7. Geographical Patterns

- **Geographical Distribution**: See `geographical_distribution.png`
![Geographical_distribution](https://github.com/user-attachments/assets/549ad614-5f16-4897-b792-650dd0f2e790)

- **Geographical_cluster_map**
![Geographical_cluster_map](https://github.com/user-attachments/assets/c4950665-007b-456c-8397-c74317678279)

### 8. Restaurant Chains

- **Popular Restaurant Chains**:
    - Downing Street: Average Rating 4.0, Total Votes 670
    - B Baker Street: Average Rating 3.3, Total Votes 215
    - Parkstreet Lane Average Rating 3.0, Total Votes 31

### 9. Votes Analysis

- **Highest and Lowest Votes**:
    - Highest Votes: Toit (10934 votes)
    - Lowest Votes: Cantinho da Gula (0 vote)
- **Correlation between Votes and Rating**: Correlation Coefficient: 0.65
- 
### 10.  Price Range vs. Online Delivery and Table Booking 
![ Price Range](https://github.com/user-attachments/assets/fb7c9fb5-9837-447d-8647-aa151b8b1fef)

## Conclusion

This comprehensive EDA has highlighted the importance of thorough data cleaning, visualization, and statistical analysis in extracting meaningful insights. The dataset offers potential for further analysis, including predictive modeling and strategic decision-making.

## Usage

1. Clone the repository:
    
    ```
    git clone https://github.com/Aasthachourasiya0/restaurant-data-analysis.git
    
    ```
    
2. Navigate to the project directory:
    
    ```python
    cd restaurant-data-analysis
    
    ```
    
3. Install the required libraries:
    
    ```python
    pip install -r requirements.txt
    
    ```
    
4. Run the analysis scripts to generate insights and plots.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or additions.

## References and Sources

- Dataset Source: [Cognifyz Technologies](https://www.linkedin.com/company/cognifyz-techonologies/)

### Prerequisites

- Python 3.6+
- Jupyter Notebook
- Required libraries: pandas, numpy, seaborn, matplotlib, scikit-learn, .Geopandas (for geographical analysis) Geospatial, Folium, contextily (for geographical analysis) Interactive maps

### Installation

1. Clone the repository:
