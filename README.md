# Customer Shopping Behavior Analysis  

A data analytics project aimed at understanding how customers interact with products — from spending habits to subscription trends — and using those insights to guide smarter business decisions.  

---

### 1. Overview  

This project explores **3,900 shopping transactions** containing demographic, purchase, and behavioral data.  
The goal was to identify **patterns in customer spending**, segment buyers based on loyalty, and uncover opportunities to **improve marketing and retention strategies**.  

---

### 2. Dataset Summary  

| Category | Details |
|-----------|----------|
| **Rows** | 3,900 |
| **Columns** | 18 |
| **Missing Values** | 37 (in Review Rating) |
| **Data Source** | Retail Transactional Dataset |
| **Features** | Age, Gender, Item, Category, Amount, Discount, Subscription, Review, Shipping, etc. |

---

### 3. Tools & Technologies  

| Purpose | Tools Used |
|----------|-------------|
| Data Cleaning & EDA | Python (pandas, numpy, matplotlib, seaborn) |
| Database & Querying | PostgreSQL |
| Visualization | Power BI |
| Notebook Environment | Jupyter |
| Version Control | Git & GitHub |

---

### 4. Data Preparation Steps  

- Imported and explored dataset using `pandas`  
- Handled missing data (median imputation by category)  
- Standardized column names for consistency (`snake_case`)  
- Created new features like `age_group` and `purchase_frequency_days`  
- Stored cleaned dataset in **PostgreSQL** for SQL-based analysis  

---

### 5. Key Insights  

#### a. Revenue by Gender  
- **Male:** $157,890  
- **Female:** $75,191  

#### b. Top Rated Products  
Gloves, Sandals, Boots, Hat, and Skirt ranked highest in customer satisfaction.  

#### c. Shipping Type  
Express shipping slightly outperformed standard with higher average order values ($60.48 vs $58.46).  

#### d. Subscription Behavior  
| Type | Customers | Avg. Spend | Revenue |
|------|------------|-------------|----------|
| Subscribed | 1,053 | $59.49 | $62,645 |
| Non-Subscribed | 2,847 | $59.87 | $170,436 |

#### e. Customer Segmentation  
- **Loyal:** 3,116  
- **Returning:** 701  
- **New:** 83  

#### f. Revenue by Age Group  
| Group | Revenue |
|--------|----------|
| Young Adult | $62,143 |
| Middle-aged | $59,197 |
| Adult | $55,978 |
| Senior | $55,763 |

---

### 6. Dashboard Snapshot  

The **Power BI dashboard** provides an interactive overview of:  
- Subscription rates (27%)  
- Average purchase value (₹59.76)  
- Average review rating (3.75)  
- Age and gender-based filters for real-time insight  

---

### 7. Business Recommendations  

| Focus Area | Suggested Action |
|-------------|------------------|
| Subscriptions | Launch exclusive benefits for subscribers |
| Customer Loyalty | Reward frequent buyers with tiered perks |
| Discount Policy | Adjust offers to maintain profit margins |
| Product Positioning | Highlight high-rated and high-revenue products |
| Targeted Marketing | Focus on strong-performing demographics |

---




