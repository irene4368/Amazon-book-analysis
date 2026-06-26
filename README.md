📌 Project Overview

An end-to-end exploratory data analysis of Amazon's Top 50 Bestselling Books from 2009 to 2019. This project uncovers trends in reader preferences, pricing patterns, author dominance, and genre performance across a decade of bestseller data.

Dataset: 550 records | 7 features | Source: Kaggle

Tools: Python, Pandas, Matplotlib, Seaborn, Power BI


❓ Business Questions Explored


Which authors dominated the bestseller list across the decade?
How did reader engagement (reviews) change year over year?
Is there a price difference between Fiction and Non Fiction books?
Which genre performed better in terms of ratings?
What does the distribution of user ratings look like across all books?



📊 Key Findings


Suzanne Collins had the highest total reviews by a significant margin, driven by The Hunger Games trilogy
Non Fiction books made up the majority of bestsellers across most years, outnumbering Fiction consistently
Fiction books are priced higher on average than Non Fiction titles despite similar rating distributions
Reader engagement (total reviews) peaked around 2014 and dipped slightly before recovering toward 2019
Average user rating across all 550 books is 4.62 out of 5, indicating strong reader satisfaction across the board
Books priced between $8–$15 dominate the bestseller list — very few high-priced books make it in



📁 Project Structure

amazon-book-analysis/
│
├── data/
│   └── bestsellers_with_categories.csv      # Raw dataset
│
├── notebooks/
│   └── amazon_books_eda.ipynb               # Full analysis notebook
│
├── dashboard/
│   ├── Amazon_Books_Dashboard.pdf           # Exported Power BI dashboard
│   └── dashboard_screenshot.png            # Dashboard preview
│
├── visuals/
│   ├── top_10_authors.png
│   ├── reviews_over_time.png
│   ├── fiction_vs_nonfiction_price.png
│   └── rating_distribution.png
│
└── README.md


🔍 Methodology

1. Data Loading & Inspection


Loaded CSV using Pandas
Checked shape, dtypes, null values, and duplicates
Found and removed duplicate entries for books appearing across multiple years


2. Data Cleaning


Verified no missing values in key columns
Standardized Genre column (Fiction / Non Fiction)
Confirmed correct data types for numeric columns


3. Exploratory Data Analysis


Aggregated reviews and ratings by Author, Genre, and Year
Built distribution plots for Price and User Rating
Compared Fiction vs Non Fiction across price, rating, and frequency


4. Visualization


6 charts built using Matplotlib and Seaborn
Interactive Power BI dashboard with Genre and Year slicers



📈 Dashboard

Built an interactive Power BI dashboard featuring:


KPI cards: Total Books (350 unique), Average Rating (4.62), Average Price ($13.10)
Top 10 Authors by Total Reviews (bar chart)
Reviews Over Time 2009–2019 (line chart)
Genre slicer and Year range slider for dynamic filtering


📎 View Dashboard PDF


🛠 Tech Stack

ToolPurposePython 3.xCore analysisPandasData manipulation and cleaningMatplotlibStatic visualizationsSeabornStatistical plotsPower BIInteractive dashboardJupyter NotebookDevelopment environmentGit + GitHubVersion control


💡 What I Would Do Next


Add a price trend over time analysis to see if book prices have inflated
Incorporate Amazon sales rank data if available for deeper revenue insights
Build a simple recommendation model based on genre and rating
Expand dataset to include 2020–2023 for post-pandemic reading trend analysis



👩‍💻 Author

Irene Jijo

B.Tech Data Science Engineering | SCMS School of Engineering and Technology, Kerala

GitHub | LinkedIn | Kaggle
