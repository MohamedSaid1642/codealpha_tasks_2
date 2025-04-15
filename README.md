# codealpha_tasks_2
Code Alpha Second Project (Exploaratory Data Analysis EdA)



## 🏡 Airbnb NYC 2019 Data Cleaning & Exploratory Data Analysis (EDA)
### 📌 Project Overview
  This project analyzes Airbnb listings in New York City for the year 2019. The primary goal is to demonstrate strong data cleaning and exploratory data analysis (EDA) skills. Using Python, we uncover trends, identify data quality issues, and draw insights that can 
  be useful for both hosts and potential guests.

### 📂 Dataset
The dataset used is AB_NYC_2019.csv, publicly available through Inside Airbnb. It includes information about listings, such as:

name: Listing title

host_id, host_name: Host details

neighbourhood_group, neighbourhood: Location details

room_type: Type of listing (e.g., Private room, Entire home/apt)

price: Nightly cost of the listing

minimum_nights: Minimum nights per booking

number_of_reviews, last_review, reviews_per_month: Review metrics

availability_365: Availability throughout the year

calculated_host_listings_count: Number of listings per host

Total Rows: ~48,895

Location: New York City

Year: 2019

### 🧼 Data Cleaning Tasks
✅ Handled missing values in columns like name, last_review, reviews_per_month

✅ Dropped duplicates and irrelevant data

✅ Detected and treated outliers in features such as price, minimum_nights, and reviews

✅ Standardized data types and formatting across columns

### 📊 Exploratory Data Analysis (EDA)
Exploratory analysis was conducted to better understand the structure and behavior of the listings. Key analyses include:

🗺️ Geographical trends: Distribution across boroughs and neighborhoods

💰 Price analysis: Pricing trends by location and room type

🛏️ Room availability: Variation in room types and yearly availability

🗣️ Host behavior: Listings per host and review patterns

📅 Review activity: Monthly and yearly trends in guest feedback

### 📈 Key Insights
Many listings had unrealistically high prices or minimum nights, which were flagged as outliers.

A large number of listings had zero availability throughout the year—these might be inactive.

Room type and neighbourhood group play major roles in determining listing prices.

Numerous missing reviews and zero reviews_per_month indicate many new or inactive listings.

### 📌 Tools & Technologies
Language: Python 🐍

Libraries:

pandas – for data manipulation

numpy – for numerical operations

matplotlib, seaborn, plotly – for visualizations

folium – for interactive maps

jupyter – for exploratory analysis

### 📁 Features
Full pipeline from data ingestion to final visualization

Clean and readable code with markdown explanations

Use of interactivity with plotly and folium

Insightful visualizations to communicate findings

### 📸 Visualizations
Box plots for price, availability, and reviews

Histograms for distribution of numerical features

Heatmaps showing geographical concentration of listings

Interactive maps using folium

### 💻 Installation
To run the project locally:

bash
Copy
Edit
git clone <repository-url>
cd <project-folder>
pip install pandas numpy matplotlib seaborn plotly folium jupyter
jupyter notebook
Then open abnb.ipynb in your Jupyter interface.

### 🚀 Future Enhancements
Incorporate time-series analysis on review data

Build predictive models to estimate pricing or review frequency

Create interactive dashboards using Streamlit or Power BI

### 📌 Usage
Clone/download the repo

Launch the notebook (abnb.ipynb) using JupyterLab or VSCode

Run the cells sequentially to view the data cleaning and EDA process

Refer to markdown cells for commentary and insights

### 📜 License
This project is for educational and portfolio purposes. You are free to use and adapt it with proper attribution.

### 👩‍💻 Author Notes
This project was created as part of a personal portfolio to demonstrate data cleaning, EDA, and storytelling skills using a real-world dataset. Feedback is always welcome!

