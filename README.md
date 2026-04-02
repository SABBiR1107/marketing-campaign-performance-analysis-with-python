# Tech Advertising Campaign Performance Analysis

## Project Overview
This project analyzes a **tech advertising campaign dataset** to understand which factors improve campaign performance and business outcomes.

The analysis focuses on key marketing and business KPIs such as:
- CTR
- CPC
- Conversion Rate
- CPA
- ROAS
- Profit

The goal is to identify which **platforms, campaign objectives, ad placements, audience segments, creative styles, and time factors** drive better results.

---

## Business Objective
The main objective of this project is to answer practical business questions such as:

- Which platform performs best?
- Which campaign objective gives the highest profit?
- Which ad placements generate better CTR and conversions?
- Does retargeting improve campaign performance?
- Which audience groups respond better?
- Which creative formats and emotions work best?
- What day and hour deliver stronger results?
- What factors are connected to high ROAS and profit?

---

## Dataset Summary
The dataset contains **10,000 advertising campaign records** and includes campaign setup, audience targeting, creative, engagement, and business performance variables.

### Important columns
#### Campaign information
- `campaign_id`
- `campaign_objective`
- `platform`
- `ad_placement`
- `device_type`
- `operating_system`

#### Creative information
- `creative_format`
- `creative_size`
- `ad_copy_length`
- `has_call_to_action`
- `creative_emotion`
- `creative_age_days`

#### Audience information
- `target_audience_age`
- `target_audience_gender`
- `audience_interest_category`
- `income_bracket`
- `purchase_intent_score`
- `retargeting_flag`

#### Time information
- `start_date`
- `quarter`
- `day_of_week`
- `hour_of_day`
- `campaign_day`

#### Performance and business metrics
- `quality_score`
- `actual_cpc`
- `impressions`
- `clicks`
- `conversions`
- `ad_spend`
- `revenue`
- `bounce_rate`
- `avg_session_duration_seconds`
- `pages_per_session`
- `CTR`
- `CPC`
- `conversion_rate`
- `CPA`
- `ROAS`
- `profit`

---

## Tools and Technologies
### Python
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

### Business Intelligence
- Power BI
- Power Query
- DAX

---

## Python Analysis Workflow
The Python part of this project is designed like a professional analyst workflow.

### Steps
1. Import libraries  
2. Load dataset  
3. Basic overview  
4. Data cleaning  
5. Feature engineering  
6. Univariate analysis  
7. Bivariate analysis  
8. KPI analysis  
9. Segment analysis  
10. Time-based analysis  
11. Correlation analysis  
12. Outlier analysis  
13. Business insights  
14. Final conclusion

---

## Key Analysis Areas

### 1. KPI Overview
The project evaluates overall campaign performance using:
- Total Impressions
- Total Clicks
- Total Conversions
- Total Ad Spend
- Total Revenue
- Total Profit
- Average CTR
- Average CPC
- Average Conversion Rate
- Average CPA
- Average ROAS

### 2. Platform Performance
This analysis compares platforms based on:
- Profit
- ROAS
- CTR
- Conversion Rate
- Spend and revenue

### 3. Campaign Objective Analysis
This helps identify which objective type drives stronger business performance.

### 4. Audience Analysis
This examines:
- Age groups
- Gender
- Interest category
- Income bracket
- Retargeting behavior

### 5. Creative Analysis
This explores:
- Creative format
- Emotional tone
- Call-to-action effect
- Placement effect

### 6. Time Analysis
This checks whether performance changes across:
- Day of week
- Hour of day
- Month
- Quarter

### 7. Profitability Analysis
This highlights:
- Profitable vs loss campaigns
- Top performing campaigns
- Underperforming campaigns
- Platform-objective combinations

---

## Feature Engineering
New analytical features are created to improve storytelling and segmentation, such as:
- `month`
- `month_name`
- `year`
- `profit_status`
- `roas_group`
- readable labels for boolean fields

---

## Recommended Visualizations
The project uses:
- Histograms
- Bar charts
- Count plots
- Line charts
- Heatmaps
- Boxplots
- Pivot-style comparison charts

These visuals help explain distribution, trends, performance differences, and outliers.

---

## Power BI Dashboard
The Power BI part turns the analysis into an interactive dashboard for decision-makers.

### Recommended dashboard pages

#### 1. Executive Overview
Shows:
- Total Campaigns
- Total Spend
- Total Revenue
- Total Profit
- Overall CTR
- Overall Conversion Rate
- Overall ROAS

#### 2. Audience Performance
Shows:
- Best age group
- Best gender segment
- Best interest category
- Retargeting impact

#### 3. Creative and Campaign Optimization
Shows:
- Best creative format
- Best emotional style
- Best ad placement
- CTA performance

#### 4. Time and Efficiency Analysis
Shows:
- Best hour of day
- Best day of week
- Monthly trend
- Platform vs objective matrix

---

## Example Power BI Measures
Useful DAX measures include:
- Total Campaigns
- Total Impressions
- Total Clicks
- Total Conversions
- Total Ad Spend
- Total Revenue
- Total Profit
- Overall CTR
- Overall CPC
- Overall Conversion Rate
- Overall CPA
- Overall ROAS

---

## Project Outcomes
By completing this project, we can:
- identify high-performing campaign setups
- optimize ad budget allocation
- understand which audience segments are most profitable
- improve creative decisions
- reduce inefficient ad spending
- support data-driven marketing strategy

---

## Portfolio Description
**Tech Advertising Campaign Performance Analysis**  
Analyzed 10,000 advertising campaign records using Python and Power BI to evaluate campaign efficiency, audience behavior, creative effectiveness, and business profitability. Built KPI-focused analysis and interactive dashboards to identify the best-performing platforms, objectives, audience segments, and campaign strategies based on CTR, conversion rate, CPA, ROAS, and profit.

---

## Suggested Project Structure
```bash
tech-advertising-campaign-analysis/
│
├── data/
│   └── tech_advertising_campaigns_dataset.csv
│
├── notebooks/
│   └── tech_advertising_campaign_analysis.ipynb
│
├── powerbi/
│   └── tech_advertising_campaign_dashboard.pbix
│
├── images/
│   └── dashboard_screenshots.png
│
└── README.md
```

---

## Final Recommendation
This project is a strong portfolio project for:
- Data Analyst
- Marketing Analyst
- Business Intelligence Analyst
- Junior Data Scientist

It shows both:
- **Python analytical skills**
- **Power BI dashboard skills**

---

## Author
**Ahsanur Rahman Sabbir**  
Software Engineering student with Data Science focus  
Interested in Data Analytics, BI, NLP, RAG, and AI-based solutions
