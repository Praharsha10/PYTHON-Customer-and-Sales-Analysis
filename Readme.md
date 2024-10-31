# Amazon Sales Analysis 

## Introduction
The "Amazon Sales Analysis" project is a Python-based data analysis endeavor aimed at exploring and understanding sales data obtained from Amazon. The project employs various Python libraries, including NumPy, Pandas, Matplotlib, and Seaborn, to analyze and visualize the dataset.

## Data Loading and Inspection
The first step involves loading the sales data from a CSV file using Pandas. The dataset contains 128,976 entries with 21 columns, including information such as Order ID, Date, Status, Sales Channel, Quantity, Amount, and more. Initial inspection using methods like `head()`, `info()`, and `shape` provides a quick overview of the data structure.

## Data Cleaning
The dataset undergoes cleaning processes to enhance its usability. Unrelated or blank columns, such as 'New' and 'PendingS', are dropped. Null values are handled by dropping rows or filling in missing information. Data types are adjusted, ensuring consistency, and columns like 'Date' are converted to datetime objects for better analysis.

## Exploratory Data Analysis (EDA)
### 1. Size Analysis
The distribution of purchases based on size is explored using count plots, revealing that M-Size is the most popular among buyers.

### 2. Grouping by Size
Grouping the data by size allows for a deeper understanding of the quantity of products sold for each size. The analysis confirms that M-Size products dominate sales.

### 3. Courier Status and Order Status
Analyzing the shipping methods and order statuses through count plots indicates that the majority of orders are shipped through couriers.

### 4. Category Distribution
A histogram is used to visualize the distribution of purchases across different product categories, highlighting that T-shirts are the most frequently bought items.

### 5. B2B Analysis
The project includes a pie chart to showcase the distribution of Business-to-Business (B2B) and retailer buyers, indicating that 99.3% of buyers are retailers.

### 6. Fulfilment Analysis
A pie chart illustrates the distribution of fulfilment methods, with Amazon being the primary fulfilment service.

### 7. Scatter Plot and State-wise Distribution
Scatter plots are used to explore relationships between product categories and sizes. Additionally, state-wise distribution plots provide insights into the geographical concentration of buyers, with Maharashtra having the highest number of customers.

## Conclusion
The Amazon Sales Analysis project provides valuable insights into customer preferences, popular product categories, and geographic distribution. This information can be leveraged by the business to make informed decisions, optimize inventory, and enhance customer satisfaction.
