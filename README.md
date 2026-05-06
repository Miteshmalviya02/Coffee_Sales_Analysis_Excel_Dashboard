# Coffee Sales Analysis — Excel Dashboard

---

## Project Overview

This project analyzes sales data from a coffee chain operating across **3 store locations** — Astoria, Hell's Kitchen, and Lower Manhattan. Key business questions were answered and visualized through an **interactive Excel Dashboard** built using Pivot Tables, Charts, and Slicers.

---

## Data Columns

| Column | Description |
|---|---|
| `transaction_id` | Unique ID for each transaction |
| `transaction_date` | Date of transaction |
| `transaction_time` | Time of transaction |
| `transaction_qty` | Number of items purchased |
| `store_id` | Store identifier |
| `store_location` | Store name / location |
| `product_id` | Product identifier |
| `unit_price` | Price per unit |
| `product_category` | High-level category (Coffee, Tea, Bakery, etc.) |
| `product_type` | Sub-type within category |
| `product_detail` | Specific product name |

---

## Dashboard Overview

**Total Orders:** 149K &nbsp;|&nbsp; **Total Revenue:** $699K &nbsp;|&nbsp; **Average Order Value:** $4.69

<img width="900" alt="Dashboard Overview" src="https://github.com/user-attachments/assets/7f3972d0-c5f7-4a14-bb48-66f188a71fe1" />

---

## Business Questions & Insights

---

### Q1. Which months and days generate the highest revenue?

<img width="600" alt="Sales Trend by Month" src="https://github.com/user-attachments/assets/496755b0-1c9b-473e-9519-ba45379287be" />

<img width="600" alt="Sales by Weekdays" src="https://github.com/user-attachments/assets/3f102c59-73f7-4225-b3f2-60dd2816735a" />

**Monthly Trend:**
Revenue grew consistently from January through June with one small dip in February.

| Month | Revenue |
|-------|---------|
| January | $82K |
| February | $76K |
| March | $99K |
| April | $119K |
| May | $157K |
| June | $166K |

Revenue nearly **doubled from February to June** — showing strong upward momentum across the 6-month period. June was the highest performing month at $166K.

**Day of Week:**

| Day | Revenue |
|-----|---------|
| Monday | $102K |
| Thursday | $101K |
| Friday | $101K |
| Wednesday | $100K |
| Tuesday | $99K |
| Sunday | $98K |
| Saturday | $97K |

**Monday is the strongest day**, followed closely by Thursday and Friday. Weekends are the weakest — suggesting the customer base is primarily **weekday commuters and office-goers.**

---

### Q2. Which store location performs best in total sales and transaction volume?

<img width="600" alt="Sales by Store Location" src="https://github.com/user-attachments/assets/0a953a7a-7aba-4840-9e09-01414a283464" />

<img width="500" alt="Store Table" src="https://github.com/user-attachments/assets/c3cbd896-0b0e-4f8a-85b8-ca4459df3d98" />

| Store | Total Sales | Avg Transaction | Transaction Volume |
|-------|-------------|-----------------|-------------------|
| Hell's Kitchen | $237K | $4.66 | 70.99K |
| Astoria | $232K | $4.59 | 71.74K |
| Lower Manhattan | $230K | $4.81 | 71.74K |

All three stores are performing **remarkably close to each other** — each crossing $230K in revenue and 70K+ in transactions. **Hell's Kitchen leads** in total sales and transaction volume. However, the gap between stores is very small, which shows strong and consistent operations across all locations.

---

### Q3. Which product categories and types contribute most to revenue?

<img width="700" alt="Sales by Category" src="https://github.com/user-attachments/assets/6c07c8c1-0f36-49d6-8cda-baa65c910a8b" />

<img width="600" alt="Top 10 Products" src="https://github.com/user-attachments/assets/a293f1de-22c1-4853-91da-76537fb2f249" />

| Category | Revenue | Share |
|----------|---------|-------|
| Coffee | $270K | 38.63% |
| Tea | $196K | 28.11% |
| Bakery | $82K | 11.78% |
| Drinking Chocolate | $72K | 10.36% |
| Coffee Beans | $40K | 5.74% |
| Branded | $14K | 1.95% |
| Loose Tea | $11K | 1.60% |
| Flavours | $8K | 1.20% |
| Packaged Chocolate | $4K | 0.63% |

**Coffee is the top category at $270K (38.63%)**, followed by Tea at $196K (28.11%). Together they account for nearly **67% of total revenue.**

Within Coffee, **Barista Espresso** is the single highest revenue product at **$91K.** Within Tea, **Brewed Chai Tea** is the top performer at **$77K** — making it the 2nd highest revenue product overall across the entire chain.

---

### Q4. What is the best-selling product detail (specific item) across all stores?

<img width="600" alt="Best Selling Products by Store" src="https://github.com/user-attachments/assets/45859331-edfa-4da5-b821-2f08f8a73f22" />

| Product | Astoria | Hell's Kitchen | Lower Manhattan |
|---------|---------|----------------|-----------------|
| Earl Grey Rg | 1725 | 1522 | 1461 |
| Dark Chocolate Lg | 1755 | 1452 | 1461 |
| Morning Sunrise Chai Rg | 1545 | 1589 | 1509 |
| Latte | 1561 | 1500 | 1541 |
| Peppermint Rg | 1673 | 1396 | 1495 |

**Earl Grey Rg and Dark Chocolate Lg are the best-selling products across all 3 stores** — performing consistently high in every location. These are the chain's most universally loved items regardless of store.

---

### Q5. What are the peak hours of the day for transactions?

<img width="700" alt="Transactions by Hours" src="https://github.com/user-attachments/assets/80146a14-5d77-4377-b02b-c5bf552366eb" />

| Hour | Transaction Volume |
|------|--------------------|
| 6 AM | 6.87K |
| 7 AM | 19.45K |
| 8 AM | 25.20K |
| 9 AM | 25.37K |
| 10 AM | 26.71K |
| 11 AM | 25.34K |
| 12 PM | 12.69K |
| Post 12 PM | Steady decline |
| 8 PM | 0.88K |

Transactions **spike sharply from 7 AM and peak at 10 AM with 26.71K transactions.** After 11 AM, volume drops quickly through the afternoon and evening. This is a clear **morning rush pattern** — the business is driven almost entirely by the early morning coffee habit of its customers.

---

### Q6. Are there specific days of the week with consistently higher sales?

<img width="600" alt="Sales by Weekdays" src="https://github.com/user-attachments/assets/f4dfc1e0-ea5d-479b-9d1b-356eee183981" />

**Monday, Thursday, and Friday are the consistently strongest days.**

| Day | Revenue |
|-----|---------|
| Monday | $102K |
| Thursday | $101K |
| Friday | $101K |
| Saturday | $97K (Lowest) |

These three days contribute significantly more than weekends. Saturday is the lowest at $97K. This pattern confirms the customer base is largely made up of **working professionals** who are most active at the start and end of their work week.

---

### Q7. How does product preference vary across store locations?

<img width="600" alt="Product Preference by Store" src="https://github.com/user-attachments/assets/4d435623-5841-4885-be2f-8acdd18f1300" />

| Product | Strongest Store |
|---------|----------------|
| Earl Grey Rg | Astoria (1725) |
| Dark Chocolate Lg | Astoria (1755) |
| Morning Sunrise Chai Rg | Hell's Kitchen (1589) |
| Peppermint Rg | Astoria (1673) |
| Latte | Astoria (1561) |

While the top products are popular across all stores, **Astoria dominates in quantity sold** for most items. **Hell's Kitchen leads specifically for Morning Sunrise Chai Rg** — suggesting that store has a customer base that leans more toward chai-based drinks. Each store has its own subtle product personality despite selling the same menu.

---

### Q8. Which store has the highest average transaction value?

<img width="500" alt="Avg Transaction by Store" src="https://github.com/user-attachments/assets/3cf344e2-ee67-4d6a-a7dc-d79a40c4bde3" />

<img width="450" alt="Store AVG Table" src="https://github.com/user-attachments/assets/1fff2b31-65be-4c5b-b0f8-b8d810223dc3" />

| Store | Avg Transaction Value |
|-------|-----------------------|
| Lower Manhattan | **$4.81** |
| Hell's Kitchen | $4.66 |
| Astoria | $4.59 |
| Overall Chain | $4.69 |

**Lower Manhattan has the highest average transaction value at $4.81** — even though it has the lowest total revenue among the three stores. This means customers there spend more per visit but visit slightly less often. This makes Lower Manhattan a strong candidate for **upselling and premium product strategies.**

---

## Summary

| # | Insight |
|---|---------|
| 1 | Revenue grew strongly month-on-month — June at $166K was the best month |
| 2 | All 3 stores perform similarly — Hell's Kitchen leads by a small margin |
| 3 | Coffee + Tea together = 67% of total revenue |
| 4 | Peak hours are 7 AM – 10 AM — morning rush drives the business |
| 5 | Lower Manhattan spends the most per visit — best store for upselling |

---
