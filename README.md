This project focuses on analyzing restaurant data from Bangalore and Pune to gain insights into dining preferences, pricing trends, popular cuisines, and restaurant performance metrics. It employs Python and its data visualization libraries to uncover trends and relationships in the restaurant industry.
Features
•	Dataset Exploration: Examine restaurant datasets for missing values and clean them for analysis.
•	Visualizations:
o	Distribution of restaurants across localities.
o	Pricing trends and their relationships with dining ratings.
o	Clustering restaurants by location using K-Means.
•	Top Restaurants and Popular Cuisines:
o	Identify top-rated restaurants and most preferred cuisines in Bangalore and Pune.
•	Statistical Analysis:
o	T-tests to compare ratings of specific cuisines.
o	Regression analysis to understand the impact of pricing on dining ratings.
•	Geographical Insights:
o	Visualize the geographic distribution of restaurants and clusters.
•	Key Metrics:
o	Average pricing for two people by category.
o	Localities with the highest dining ratings.
Installation
1.	Clone this repository:
bash
Copy code
git clone https://github.com/Pravir2004/zomato_restaurant_analysis.git
2.	Navigate to the project directory:
bash
Copy code
cd zomato_restaurant_analysis
3.	Install the required Python libraries:
bash
Copy code
pip install pandas matplotlib scipy statsmodels scikit-learn
Usage
1.	Ensure the datasets (Bangalore_Restaurants.csv and Pune_Restaurants.csv) are in the project directory.
2.	Run the analysis scripts:
o	For Bangalore:
bash
Copy code
python bangalore_analysis.py
o	For Pune:
bash
Copy code
python pune_analysis.py
3.	Explore the visualizations and insights generated during the analysis.

4.	
Results
•	Top-rated Restaurants:

o	Bangalore: Windmills Craftworks, CTR Shri Sagar, Brahmin's Coffee Bar, and more.
o	Pune: Le Plaisir, Gong, The French Window Patisserie, etc.
•	Popular Localities:
o	Bangalore: BTM, Indiranagar, Whitefield.
o	Pune: Kothrud, Wakad, Viman Nagar.

•	Cuisine Insights:
o	Most popular cuisines and their average pricing for two people in both cities.

•	Statistical Findings:
o	Minimal differences between Asian and Italian cuisine ratings in Bangalore and Pune.
o	Positive correlation between pricing and dining ratings in Pune.

Technologies Used
•	Languages: Python

•	Libraries:
o	Data Manipulation: pandas
o	Visualization: matplotlib
o	Statistical Analysis: scipy, statsmodels
o	Clustering: scikit-learn


Contributions
Contributions are welcome! Feel free to fork the repository and submit a pull request.


Author
Pravir Mishra
GitHub: @Pravir2004
