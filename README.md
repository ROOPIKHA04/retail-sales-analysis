# 🛒 US Retail Sales Analysis | 2014–2017

## About This Project
I wanted to get hands-on with a real business dataset, so I picked up the Sample Superstore dataset and dug into 4 years of US retail transactions. Using SQL to explore the data and Power BI to bring it to life visually, I uncovered some genuinely interesting findings — especially around how discounting was quietly hurting the business's bottom line.

---

## Tools I Used
- **SQL** (DB Browser for SQLite) — for querying and analysing the data
- **Power BI** — for building the interactive dashboard

---

## About the Dataset
- **Source:** Sample Superstore Dataset (Kaggle)
- **Records:** 9,994 transactions
- **Period:** 2014 – 2017
- **Coverage:** 49 U.S. states, 3 product categories, 793 unique customers

---

## What I Found

### Revenue & Profit
The business generated **$2.30M in total revenue** and **$286.40K in profit** over 4 years, with both figures growing steadily year after year — which is a good sign overall.

### Category Performance
Technology was the clear winner — highest sales at **$836K** and the best profit at **$145K**. Furniture had decent sales but surprisingly thin margins. Office Supplies was the smallest category but held up well on profit.

### Regional Performance
The **West region** was the strongest market, making up nearly **38% of total profit**. California alone contributed **$76K in profit** — by far the top state. On the flip side, Texas was a problem — high sales volume but consistently losing money.

### 💡 The Most Interesting Finding — Discounts Are Hurting Profit
This was the finding that really stood out to me. When I analysed the impact of discounts on profit:
- Orders with **no discount** were the most profitable
- Orders with **over 20% discount** were generating a **negative average profit of -$45**
- Orders with **over 30% discount** were losing an average of **-$107 per order**

So the business was actually losing money on its most heavily discounted sales — despite those orders still showing up as revenue. That's a real business problem hiding in plain sight.

### Customer Insights
The **Consumer segment** made up the largest share of orders. **Sean Miller** was the top spending customer overall.

### Seasonal Trends
Sales spiked in **November and December** — no surprise there. The slowest months were January and February right after the holiday rush.

---

## Files in This Repository

| File | Description |
|------|-------------|
| `Sample - Superstore.csv` | Raw dataset |
| `Retail_Sales_Analysis.pbix` | Power BI dashboard file |
| `dashboard_page1.png` | Sales Overview screenshot |
| `dashboard_page2.png` | Deep Dive screenshot |

---
