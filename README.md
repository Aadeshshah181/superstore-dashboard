# 📊 Super Store Sales Dashboard — Power BI Project

> **A complete 3-page interactive Power BI dashboard** built on the Sample Superstore dataset, analyzing **$2.30M in sales**, **9,994 orders**, and **$286K in profit** across 4 years (2016–2019).

---

## 📌 Project Overview

This project was built as part of my **Data Analytics training at Adani Skill Development Center** under the mentorship of **Shubham Dubey Sir**.

The goal was to transform raw transactional data from a fictional superstore into a fully interactive, decision-ready business dashboard — the kind that real companies use to track performance, spot problems, and make smarter decisions.

---

## 🗂️ Dataset Details

| **Source** | Sample Superstore (Tableau/Kaggle public dataset) |
| **File** | `Sample - Superstore.xlsx` |
| **Time Period** | 2016 – 2019 |
| **Total Records** | ~9,994 orders |
| **Key Columns** | Order Date, Region, Category, Sub-Category, Product Name, Sales, Profit, Discount, Quantity, Segment, Ship Mode |

---

## 📋 Dashboard Pages & Key Insights

---

### 📄 Page 1 — Executive Summary

**Purpose:** Give leadership a bird's-eye view of overall business health at a glance.

#### 🔢 KPI Cards
| Metric | Value |
|---|---|
| Total Sales | **$2.30 Million** |
| Total Profit | **$286.40K** |
| Average Order Value | **$28.66** |
| Total Orders | **9,994** |
| Profit Margin | **12.47%** |

#### 📈 Sales Trend Over Time (Monthly)
- Sales follow a **seasonal pattern** — consistently low in **January–March** and spike sharply in **October–December**.
- The **November–December peak** indicates strong holiday/end-of-year purchasing behaviour.
- This insight helps plan **inventory & marketing campaigns** around seasonal demand.

#### 🍩 Sales by Category
| Category | Sales | Share |
|---|---|---|
| Technology | $836.15K | **36.4%** |
| Office Supplies | $742K | **32.3%** |
| Furniture | $719.05K | **31.3%** |

- **Technology** leads in sales volume — driven by high-ticket items like Phones, Machines, and Copiers.
- All three categories are closely balanced, meaning no single category dominates — healthy diversification.

#### 📊 Sales by Region
| Region | Performance |
|---|---|
| **West** | Highest (~$0.73M) |
| **East** | Second highest |
| **Central** | Third |
| **South** | Lowest |

- The **West region is the strongest market** — likely due to higher population density & tech-savvy customers.
- The **South region underperforms** — a potential area for targeted sales campaigns.

#### 🏆 Top 10 Sub-Categories by Sales & Profit
- **Phones, Chairs, and Storage** are the top revenue-generating sub-categories.
- However, sub-categories like **Tables and Bookcases** show sales but negative or very low profit — a red flag.

---

### 📄 Page 2 — Profitability & Discount Analysis

**Purpose:** Identify where the business is losing money, which products are profit killers, and how discounts are impacting the bottom line.

#### 🔢 KPI Cards
| Metric | Value |
|---|---|
| Total Profit | **$286.40K** |
| Average Discount | **15.62%** |
| Loss-Making Orders | **196** |
| Best Profit Category | **Technology** |
| Best Profit Segment | **Consumer** |

#### 📉 Bottom 10 Products by Profit (Loss Leaders)
These are products that are actively **costing the business money**:
- **Cubify CubeX 3D Printer Double Head** — the single biggest loss-maker (approx. -$8.9K loss)
- **Lexmark MX611dhe Mono Laser Printer** — second largest loss
- Other loss products include: GBC DocuBind, Bush Advantage, Cisco TelePresence, Martin Yale Chadless Opener

**Why does this happen?** High discounts on already low-margin products result in selling at a loss. This is a **critical business problem** — heavy discounting is destroying profitability.

#### 📊 Profit by Category
| Category | Profit |
|---|---|
| Technology | **$145.45K** (highest) |
| Office Supplies | **$122.49K** |
| Furniture | **$18.45K** (alarmingly low given its sales volume) |

- **Furniture earns very little profit** despite accounting for 31.3% of sales — high costs or heavy discounts are likely the cause.
- **Technology is the most profitable category** — both in volume and margin.

#### 🎯 Achieved Profit vs Target
- **Achieved:** $286.40K
- **Target Range:** $0 – $572.79K (midpoint $429.60K)
- The business is currently at **~50% of the maximum target** — there is significant room for growth, particularly by reducing loss-making orders and limiting excessive discounts.

#### 📈 Profit Trend by Year (2016–2019)
- Profit has grown **steadily year-over-year** — from ~$40K in 2016 to ~$93K in 2019.
- This positive trend shows the business is maturing, but the growth rate needs to accelerate to hit targets.

---

### 📄 Page 3 — Sales Performance

**Purpose:** Understand which products drive revenue, how customers prefer to receive orders, and how sales have grown over the years.

#### 🏅 Top 15 Products by Revenue
| Rank | Product | Approx. Sales |
|---|---|---|
| #1 | Canon imageCLASS 2200 Copier | ~$62K |
| #2 | Fellowes PB500 Electric Punch | ~$28K |
| #3 | Cisco TelePresence System | ~$23K |
| #4 | HON 5400 Series Task Chairs | ~$22K |
| #5 | GBC DocuBind TL300 | ~$20K |

- **Technology products dominate** the top 15 — Canon, Cisco, HP, Lexmark all appear.
- High revenue ≠ high profit. Some of these top products appear in the **loss-making list on Page 2** — a key insight for pricing strategy.

#### 📈 Monthly Sales vs Quantity Trend (2016–2019)
- Both **sales value and quantity sold** have grown year-over-year.
- The trend is nearly linear — showing **consistent business growth** with no sudden drops.
- 2019 shows the steepest growth — indicating the business is gaining momentum.

#### 🚚 Sales by Ship Mode
| Ship Mode | Sales |
|---|---|
| **Standard Class** | $1.36M (most preferred — 59%) |
| Second Class | $0.46M |
| First Class | $0.35M |
| Same Day | $0.13M |

- **90%+ of customers choose Standard or Second Class** — customers prioritize cost over speed.
- Only **9.5% use Same Day** shipping — premium shipping is underutilised.

#### 🗺️ Sales by Category & Sub-Category (Treemap)
- **Technology** is dominated by Phones and Machines.
- **Furniture** is driven by Chairs and Tables.
- **Office Supplies** is the most diverse — Accessories, Binders, Paper, Storage, Art, and more.

---

## 🔧 Tools & Features Used

| Tool / Feature | Usage |
|---|---|
| **Power BI Desktop** | Main development tool |
| **Power Query** | Data cleaning & transformation |
| **DAX Measures** | KPI calculations (Profit Margin, AOV, Loss Orders) |
| **Slicers** | Region, Category, Segment, Year, Discount filters |
| **Bar & Line Charts** | Sales trend, regional comparison, yearly growth |
| **Pie / Donut Chart** | Category share of sales |
| **Treemap** | Sub-category sales distribution |
| **KPI Cards** | Key metric display |
| **Gauge Chart** | Profit vs Target visualisation |
| **Navigation Buttons** | Page-to-page navigation (Executive Summary / Profit & Discount / Sales Performance) |

---

## 💡 Key Business Insights Summary

1. 📦 **Technology is the star** — highest sales (36.4%) AND highest profit ($145.45K). Invest more here.
2. 🪑 **Furniture is a problem** — 31.3% of sales but only $18.45K profit. Revisit pricing & discount strategy.
3. 🔻 **196 orders are making a loss** — discounting too aggressively is costing money on specific products.
4. 🌍 **West region outperforms** — replicate its strategy in Central and South regions.
5. 📅 **Sales peak Oct–Dec** — plan inventory and marketing campaigns for Q4.
6. 🚚 **95% use Standard/Second Class** — consider incentivising faster shipping or reducing Same Day costs.
7. 📈 **Profit is growing** year-over-year but is only at 50% of target — room for major improvement.

---

## 🎓 About This Project

| | |
|---|---|
| **My Name ** | Aadesh Shah |
| **Institution** | Adani Skill Development Center |
| **Mentor** | Shubham Dubey Sir |
| **Tool Used** | Microsoft Power BI |
| **Dataset** | Sample Superstore (Public) |
| **Project Type** | Academic / Portfolio Project |

---

## 🤝 Connect With Me

If you found this project helpful or want to discuss data analytics, feel free to connect!

[![LinkedIn] (https://www.linkedin.com/in/aadesh-shah-6231093b4?utm_source=share_via&utm_content=profile&utm_medium=member_android)
[![GitHub](https://github.com/Aadeshshah181)

---

> *"Without data, you're just another person with an opinion." — W. Edwards Deming*
