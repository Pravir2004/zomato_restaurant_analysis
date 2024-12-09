# zomato_restaurant_analysis

This project focuses on analyzing restaurant data from Bangalore and Pune to gain insights into dining preferences, pricing trends, popular cuisines, and restaurant performance metrics. It employs Python and its data visualization libraries to uncover trends and relationships in the restaurant industry.

Features
Dataset Exploration: Examine restaurant datasets for missing values and clean them for analysis.
Visualizations:
Distribution of restaurants across localities.
Pricing trends and their relationships with dining ratings.
Clustering restaurants by location using K-Means.
Top Restaurants and Popular Cuisines:
Identify top-rated restaurants and most preferred cuisines in Bangalore and Pune.
Statistical Analysis:
T-tests to compare ratings of specific cuisines.
Regression analysis to understand the impact of pricing on dining ratings.
Geographical Insights:
Visualize the geographic distribution of restaurants and clusters.
Key Metrics:
Average pricing for two people by category.
Localities with the highest dining ratings.
Installation
Clone this repository:
bash
Copy code
git clone https://github.com/Pravir2004/zomato_restaurant_analysis.git
Navigate to the project directory:
bash
Copy code
cd zomato_restaurant_analysis
Install the required Python libraries:
bash
Copy code
pip install pandas matplotlib scipy statsmodels scikit-learn
Usage
Ensure the datasets (Bangalore_Restaurants.csv and Pune_Restaurants.csv) are in the project directory.
Run the analysis scripts:
For Bangalore:
bash
Copy code
python bangalore_analysis.py
For Pune:
bash
Copy code
python pune_analysis.py
Explore the visualizations and insights generated during the analysis.
Results
Top-rated Restaurants:
Bangalore: Windmills Craftworks, CTR Shri Sagar, Brahmin's Coffee Bar, and more.
Pune: Le Plaisir, Gong, The French Window Patisserie, etc.
Popular Localities:
Bangalore: BTM, Indiranagar, Whitefield.
Pune: Kothrud, Wakad, Viman Nagar.
Cuisine Insights:
Most popular cuisines and their average pricing for two people in both cities.
Statistical Findings:
Minimal differences between Asian and Italian cuisine ratings in Bangalore and Pune.
Positive correlation between pricing and dining ratings in Pune.
Technologies Used
Languages: Python
Libraries:
Data Manipulation: pandas
Visualization: matplotlib
Statistical Analysis: scipy, statsmodels
Clustering: scikit-learn
Contributions
Contributions are welcome! Feel free to fork the repository and submit a pull request.

Author
Pravir Mishra
GitHub: @Pravir2004
