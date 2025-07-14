# 📊 YouTube Trending Video Data Analysis

##  Overview
This project analyzes **YouTube trending video data across multiple countries** to uncover insights into viewer engagement, **optimal posting times**, **top-performing channels**, and more. The analysis leverages **Python (Pandas, Plotly, Seaborn)** and focuses on understanding what drives video performance on YouTube.

## Project Goals & KPIs
- Engagement Rate
- Avg. Time to Trend
- Top Categories by Views
- Top Performing Channels
- Top countries Activity / views
- What’s the best hour/day to post videos?
- correlation between **publish_time** and **engagement**
- Do videos with disabled comments perform worse?

## Dataset
The dataset consists of `.csv` files containing trending video data from various countries. Each file includes:
- Video metadata (title, channel, description)
- Metrics (views, likes, comments)
- Timestamps (publish_time, trending_date)
- Flags for comment/rating disabling
[Dataset Link](https://www.kaggle.com/datasets/datasnaek/youtube-new)

## Tools & Technologies
- Python
- Pandas
- Seaborn
- Plotly
- Matplotlib
- Jupyter Notebook

## Key Insights
- **Engagement Rate** was highest for videos published between **3 AM and 6 AM**, suggesting that early morning uploads may benefit from lower competition or align with peak viewing times in other regions.
- **Time to Trend** varied significantly by country, with some markets (e.g., the US) showing faster trending dynamics.
- **Top Performing Categories** included **Entertainment, Music, and Film&Animation**, which consistently attracted high views and interaction.
- **Top Channels** were those that posted consistently and maintained a strong audience base.
- **Countries with the Highest Views** were the **GB, US ,and CA**, indicating strong demand in these markets.
- **Disabled Comments** correlated with slightly lower engagement, likely due to reduced opportunities for audience interaction.


## How to Run
1. Clone the repository.
2. Place the dataset `.csv` files in the specified folder (`Data/data`).
3. Run the Jupyter notebook file: `YT Project.ipynb`
4. Make sure you have the required libraries:
```bash
pip install pandas plotly matplotlib seaborn
```

## 👤 Author
**Omar Fares** – Data Analyst  
[LinkedIn Profile](www.linkedin.com/in/omar-fares10) 
---

> This project is part of my data portfolio demonstrating end-to-end data analysis with real-world data.
