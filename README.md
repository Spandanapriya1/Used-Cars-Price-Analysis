**Used Cars Price Analysis—Data Analytics Project**

**Project Overview**

A data-driven study, the Used Cars Price Analysis project looks at how used car costs vary depending on a number of variables, such as brand, fuel type, EMI choices, and availability in various cities. Through the use of Python for web scraping (with BeautifulSoup), data cleaning, analysis, and visualization, this project offers insightful information to assist consumers in making well-informed decisions about used automobile purchases.

In order to illustrate variations in pricing trends, consumer preferences, and regional market features, this study examines the used automobile marketplaces in Bengaluru, Hyderabad, Mumbai, and Kolkata, among other important Indian cities. In order to help companies, auto dealerships, and individual consumers make the best decisions possible, the initiative also identifies the variables that affect automobile pricing, demand, and affordability.

**Project Objectives**

Examine used car pricing trends according to a variety of factors (brand, fuel type, EMI options, availability).
Examine automobile markets in various cities to find regional differences in prices.
Identify the best-value used cars by analyzing price-to-quality ratios.
Determine the influence of fuel type on pricing and consumer preference.
Help buyers make data-driven decisions by providing clear insights into car pricing trends.
Assist businesses and dealerships in understanding demand and optimizing their inventory.

**Data Collection & Preprocessing**

**1. Data Acquisition (Web Scraping)**

The project collects used car data from reputable sources such as CarWale and other used car-selling websites using Python web scraping techniques.

**(i) Tools Used for Web Scraping:**

BeautifulSoup – Extracting HTML content and parsing structured data.
Requests: Fetching webpage content for analysis.

**(ii) Data Extraction Steps:**

Identify key attributes (Car Brand, Model, Price, Mileage, Fuel Type, Location, EMI Options).
Fetch data using requests to extract structured content.
Parse HTML material using BeautifulSoup to target relevant data points.
Store extracted data in CSV or JSON format for future processing.

**2. Data Cleaning & Preprocessing**

Pandas and NumPy were used for data preprocessing in order to guarantee accuracy and consistency.

**Data Cleaning Tasks:**

Dealing with missing values (such as partial records or missing pricing).
Standardizing data formats, such as normalizing mileage and converting currencies.
Eliminating redundant records to prevent biased analysis.
Eliminating superfluous information to concentrate on legitimate automobile listings.
Following cleaning, the data was exported for additional analysis and organized in Pandas data frames.

**3. Exploratory Data Analysis (EDA)**

Matplotlib and Seaborn were utilized in the EDA process to find important trends and insights in used car prices.

**Data Analysis Performed:**

Price distribution among cities to find cost variances.
Mileage's effect on car prices to comprehend patterns in depreciation.
Fuel kinds are compared to ascertain consumer preferences.
Where luxurious and affordable automobiles are available in different areas.
EMI programs' impact on buyers' affordability.

**Key Insights & City-Wise Comparisons**

Bangalore vs. Hyderabad

**(i)Bengaluru (Bangalore):**

The median price has increased to ₹6 lakhs.
High demand for hybrid and luxury vehicles.
Enhanced inclination towards electric cars (about 10% of the market).

**(ii)Hyderabad:**

The market is more affordable, with a typical price of ₹4.5 lakhs.
Diesel vehicles predominate (around 45%) because they are less expensive to operate.
Consumers value affordability and fuel economy over luxury.

**(iii)Conclusion:**

The market in Mumbai is more varied, with both luxury and budget automobile purchasers.
Kolkata is more cost-conscious and favors gasoline-powered vehicles.

**3. Fuel Type Preferences Across Cities**

Government incentives are encouraging more purchasers in Bengaluru and Mumbai to choose electric and hybrid cars.
Hyderabad and Kolkata: Due to availability and cost, there is a strong preference for gasoline and diesel vehicles.

**(i)Implication:**

Metro areas are seeing an increase in EV demand, which suggests room for expansion.
In areas like Hyderabad and Kolkata where money is tight, diesel vehicles are still very popular.

**4. Location-Based Pricing Insights**

Mumbai: Expensive vehicles are located in Andheri, Bandra, and Navi Mumbai.
Bangalore: Expensive automobiles are concentrated in Indiranagar, Whitefield, and Koramangala.
Cheaper automobiles in the suburbs of Hyderabad and Kolkata.
Instead of high-demand metro areas, buyers can find better offers in outlying areas.

**Technologies & Tools Used**

Python: Data Collection & Analysis
BeautifulSoup: Web Scraping
Requests: Fetching web page content
Pandas, NumPy—Data Processing
Matplotlib, Seaborn: Data Visualization
Jupyter Notebook, Visual Studio Code, Development Environments
CSV/JSON: Data Storage

**Business & Consumer Impact**

**(i)For Buyers:**

Assist in finding the most affordable used automobiles by considering factors like price, mileage, and fuel type.
Offers data-driven insights to help make informed purchases.

**(ii) For Car Dealers & Businesses:**

Better inventory planning based on regional demand is made possible by this.
Sales strategies are guided by insights into fuel type preferences.

**(iii)For Policymakers:**

Draws attention to the growing need for hybrid and electric cars in urban areas.

**Conclusion**

Data-driven insights into the used automobile market are successfully provided by this study on used car prices, assisting both buyers and sellers in making well-informed choices.

Real-world data was gathered from online automobile listings using web scraping techniques.
Data was cleaned and analyzed to reveal market patterns.
Visualizations emphasized fuel preferences, pricing trends, and geographical variations.

This project showcases expertise in:
Python-based data analytics
Web scraping using BeautifulSoup
Data visualization using Matplotlib & Seaborn
Business intelligence & market analysis
