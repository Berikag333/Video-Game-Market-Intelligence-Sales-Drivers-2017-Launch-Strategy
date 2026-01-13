# Video-Game-Market-Intelligence-Sales-Drivers-2017-Launch-Strategy
Analyses global video game sales, reviews, platforms, and genres to identify commercial success drivers and inform a 2017 marketing strategy using EDA and hypothesis testing.

## Project Overview
Ice is an online store selling video games worldwide. This project analyses historical video game sales data (up to 2016) to identify patterns that drive commercial success. The insights support data-driven decisions on which platforms and genres to prioritise when planning a marketing campaign for 2017.

The analysis combines data preparation, exploratory analysis, regional market profiling, and statistical hypothesis testing to produce business-ready recommendations.

---

## Business Objective
The objectives of this project are to:
- Identify factors associated with video game commercial success
- Evaluate platform life cycles and shifting market trends
- Define a relevant data period to inform a 2017 campaign strategy
- Profile regional preferences (NA, EU, JP) by platform, genre, and ESRB rating
- Validate assumptions using statistical hypothesis testing

---

## Dataset
Source file:
/datasets/games.csv


### Key Columns
- `name`, `platform`, `year_of_release`, `genre`
- `na_sales`, `eu_sales`, `jp_sales`, `other_sales`
- `critic_score`, `user_score`
- `rating` (ESRB)

---

## Analytical Workflow

### 1) Data Preparation
- Standardised column names (lowercase)
- Converted data types (years, scores, sales)
- Handled missing values and `tbd` user scores
- Created `total_sales` as the sum of all regional sales

### 2) Exploratory Market Analysis
- Release trends over time and data relevance by period
- Platform performance and life cycle patterns
- Identification of leading and declining platforms
- Sales distributions by platform (boxplots)
- Relationship between reviews (critic/user) and sales (correlation + scatter)

### 3) Regional Market Profiles (NA, EU, JP)
For each region:
- Top 5 platforms and market share differences
- Top 5 genres and regional preference patterns
- Impact of ESRB rating on sales

### 4) Hypothesis Testing
- Compare average user ratings: **Xbox One vs PC**
- Compare average user ratings: **Action vs Sports**
- Select significance level (alpha) and apply appropriate statistical tests

---

## Key Outputs
- Clean analysis-ready dataset with total sales feature
- Platform and genre insights supporting 2017 planning
- Regional market profiles for NA, EU, and JP
- Evidence-based conclusions from hypothesis testing
- Practical recommendations for marketing focus and product strategy

---

## Tools & Technologies
- Python
- Jupyter Notebook
- pandas / numpy
- matplotlib
- scipy.stats (hypothesis testing)

---

## Repository Structure
video-game-market-intelligence/
├── notebooks/ # Full analysis notebook
├── data/ # Dataset (or platform reference)
└── README.md


---

## Conclusion
This project translates historical market data into actionable insights for campaign planning. It demonstrates an end-to-end analytics workflow that combines data preparation, exploratory analysis, and statistical testing to support strategic decisions in a global entertainment market.

---

## Author
**Erika González**
MBA | Marketing & Data Analytics  
Focus areas: Market Intelligence, Customer Behaviour, Statistical Analysis
