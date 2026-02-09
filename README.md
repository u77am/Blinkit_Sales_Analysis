# 🛒 Blinkit Sales Analysis Dashboard | Power BI Project

<div align="center">

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)

**A comprehensive Power BI dashboard analyzing Blinkit's sales performance, outlet metrics, and product insights**

*India's Last Minute App - Sales Analytics & Business Intelligence*

[Features](#-key-features) • [Dashboard Views](#-dashboard-overview) • [SQL Queries](#-sql-analysis) • [Contact](#-contact)

### 🌐 [**View Live Interactive Report**](https://app.powerbi.com/groups/0e8cfd98-3b96-4ae5-93e1-1a02119305a3/reports/f13babb3-4943-4714-ada9-fb49c5da3fe8/18ce33c5ae70d6171d2f?experience=power-bi)

💡 **Feel free to explore the `.pbix` file and adapt it to your own retail datasets!**

</div>

---

## 📊 Project Overview

This Power BI project delivers an end-to-end sales analytics solution for Blinkit, India's leading quick-commerce platform. The dashboard analyzes **8,523 items** across multiple outlets with **$1.20M in total sales**, providing comprehensive insights into product performance, outlet efficiency, and customer preferences.

### 🎯 Business Objectives

- **Sales Performance**: Track total sales, average sales, and sales trends across time periods
- **Product Analytics**: Analyze item types, fat content preferences, and product visibility
- **Outlet Performance**: Evaluate outlet efficiency by type, size, and location
- **Geographic Insights**: Understand sales distribution across tier-1, tier-2, and tier-3 cities
- **Establishment Trends**: Track sales growth by outlet establishment year
- **Customer Ratings**: Monitor average ratings and customer satisfaction metrics
- **Inventory Optimization**: Identify top-performing items and categories

---

## ✨ Key Features

### 📈 Advanced Analytics
- **Real-time KPI Monitoring** - Track Total Sales ($1.20M), Average Sales ($141), Number of Items (8,523), and Average Rating (4.0)
- **Fat Content Analysis** - Compare Low Fat ($776.32K) vs Regular ($425.36K) product sales
- **Multi-dimensional Analysis** - Analyze by Item Type, Outlet Location, Outlet Size, and Establishment Year
- **SQL-Powered Insights** - Comprehensive SQL queries for deep data analysis

### 🎨 Interactive Visualizations
- Sales trend analysis by establishment year (2012-2022)
- Item type performance comparison (16 categories)
- Outlet location tier analysis (Tier 1, 2, 3)
- Fat content distribution across outlets
- Outlet size and type performance metrics
- Item visibility and rating correlations

### 🔍 Comprehensive Filtering
- **Outlet Location Type** filter (Tier 1, 2, 3)
- **Outlet Size** selection (Small, Medium, High)
- **Item Type** multi-select filter (Fruits, Snacks, Household, etc.)
- Dynamic slicers for custom analysis
- Cross-filtering across all visualizations

---

## 🖥️ Dashboard Overview

### 📊 Main Dashboard
A comprehensive single-page dashboard providing complete sales analytics:

**Top KPI Cards:**
- 💰 **Total Sales**: **$1.20M** - Overall revenue across all outlets
- 📊 **Average Sales**: **$141** - Average transaction value
- 📦 **No of Items**: **8,523** - Total unique items sold
- ⭐ **Average Rating**: **4.0** - Customer satisfaction score

---

### 🥗 Fat Content Analysis

**Sales by Fat Content:**
- 🥗 **Low Fat Products**: $776.32K (64.7% of total sales)
- 🍔 **Regular Products**: $425.36K (35.3% of total sales)

**Key Insight**: Low fat products significantly outperform regular items, indicating strong health-conscious consumer preferences.

**Fat Content by Outlet Tier:**
```
Tier 3 Outlets:
├── Low Fat: $0.31M
└── Regular: $0.17M

Tier 2 Outlets:
├── Low Fat: $0.25M
└── Regular: $0.14M

Tier 1 Outlets:
├── Low Fat: $0.22M
└── Regular: $0.12M
```

---

### 🛍️ Item Type Performance

**Top Performing Categories:**
1. 🍎 **Fruits and Vegetables**: $0.18M
2. 🍿 **Snack Foods**: $0.18M
3. 🏠 **Household**: $0.14M
4. ❄️ **Frozen Foods**: $0.12M
5. 🥛 **Dairy**: $0.10M
6. 🥫 **Canned**: $0.09M
7. 🍰 **Baking Goods**: $0.08M
8. 💊 **Health and Hygiene**: $0.07M
9. 🥩 **Meat**: $0.06M
10. 🥤 **Soft Drinks**: $0.06M

**Additional Categories:**
- Breads: $0.04M
- Hard Drinks: $0.03M
- Others: $0.02M
- Starchy Foods: $0.02M
- Breakfast: $0.02M
- Seafood: $0.01M

**Key Insight**: Fruits/Vegetables and Snack Foods lead sales, indicating strong demand for both healthy and convenience food options.

---

### 🏪 Outlet Establishment Trends

**Sales by Year of Establishment:**
```
2012: $78K   (Early adopters)
2014: $131K  (Growth phase)
2016: $205K  (Peak expansion) ⭐
2018: $131K  (Consolidation)
2020: $129K  (Pandemic impact)
2022: $130K  (Recovery phase)
```

**Additional Years**: 2013 ($132K), 2015 ($132K), 2017 ($133K)

**Key Insight**: 2016 shows the highest sales, suggesting successful expansion strategies during that period.

---

### 📏 Outlet Size Analysis

**Sales Distribution by Outlet Size:**
- 🏢 **Medium Outlets**: $507.90K (42.3%) - Highest performing
- 🏪 **Small Outlets**: $444.79K (37.1%) - Strong contributor
- 🏬 **High/Large Outlets**: $248.99K (20.7%) - Opportunity for growth

**Key Insight**: Medium-sized outlets deliver the best ROI, balancing operational costs with sales volume.

---

### 🗺️ Geographic Distribution

**Sales by Location Tier:**
- 🌆 **Tier 3 Cities**: $472.13K (39.3%) - Highest sales
- 🏙️ **Tier 2 Cities**: $393.15K (32.8%) - Growing market
- 🌃 **Tier 1 Cities**: $336.40K (28.0%) - Metropolitan presence

**Tier 3 Market Share**: 71.3% penetration

**Key Insight**: Tier 3 cities show the strongest performance, indicating successful penetration in smaller markets and untapped potential.

---

### 🏬 Outlet Type Performance

**Comprehensive Metrics by Outlet Type:**

| Outlet Type | Total Sales | No of Items | Avg Sales | Avg Rating | Item Visibility |
|-------------|-------------|-------------|-----------|------------|-----------------|
| 🛒 **Supermarket Type1** | $787.55K | 5,577 | $141 | 4.0 | 0.06 |
| 🏪 **Supermarket Type2** | $131.48K | 928 | $142 | 4.0 | 0.06 |
| 🏬 **Supermarket Type3** | $130.71K | 935 | $140 | 4.0 | 0.06 |
| 🛍️ **Grocery Store** | $151.94K | 1,083 | $140 | 4.0 | 0.10 |

**Key Insights:**
- Supermarket Type1 dominates with 65.6% of total sales
- Grocery stores have highest item visibility (0.10)
- Consistent average rating (4.0) across all outlet types
- Similar average sales per item ($140-$142) indicates standardized pricing

---

## 🛠️ SQL Analysis & Data Processing

### Data Cleaning Process

**Challenge**: Inconsistent fat content categorization
- Original values: 'LF', 'low fat', 'Low Fat', 'reg', 'Regular'
- Impact: Reporting errors, inaccurate aggregations, filtering issues

**Solution**: Standardization query
```sql
UPDATE blinkit_data
SET Item_Fat_Content = 
    CASE 
        WHEN Item_Fat_Content IN ('LF', 'low fat') THEN 'Low Fat'
        WHEN Item_Fat_Content = 'reg' THEN 'Regular'
        ELSE Item_Fat_Content
    END;
```

**Verification**:
```sql
SELECT DISTINCT Item_Fat_Content FROM blinkit_data;
```

---

### 📊 Key SQL Queries

#### A. KPI Calculations

**1. Total Sales**
```sql
SELECT CAST(SUM(Total_Sales) / 1000000.0 AS DECIMAL(10,2)) AS Total_Sales_Million
FROM blinkit_data;
-- Result: $1.20M
```

**2. Average Sales**
```sql
SELECT CAST(AVG(Total_Sales) AS INT) AS Avg_Sales
FROM blinkit_data;
-- Result: $141
```

**3. Number of Items**
```sql
SELECT COUNT(*) AS No_of_Orders
FROM blinkit_data;
-- Result: 8,523
```

**4. Average Rating**
```sql
SELECT CAST(AVG(Rating) AS DECIMAL(10,1)) AS Avg_Rating
FROM blinkit_data;
-- Result: 4.0
```

---

#### B. Sales Analysis Queries

**Total Sales by Fat Content**
```sql
SELECT Item_Fat_Content, CAST(SUM(Total_Sales) AS DECIMAL(10,2)) AS Total_Sales
FROM blinkit_data
GROUP BY Item_Fat_Content;
```

**Total Sales by Item Type**
```sql
SELECT Item_Type, CAST(SUM(Total_Sales) AS DECIMAL(10,2)) AS Total_Sales
FROM blinkit_data
GROUP BY Item_Type
ORDER BY Total_Sales DESC;
```

---

#### C. Advanced PIVOT Analysis

**Fat Content by Outlet Location (Pivot Table)**
```sql
SELECT Outlet_Location_Type, 
       ISNULL([Low Fat], 0) AS Low_Fat, 
       ISNULL([Regular], 0) AS Regular
FROM 
(
    SELECT Outlet_Location_Type, Item_Fat_Content, 
           CAST(SUM(Total_Sales) AS DECIMAL(10,2)) AS Total_Sales
    FROM blinkit_data
    GROUP BY Outlet_Location_Type, Item_Fat_Content
) AS SourceTable
PIVOT 
(
    SUM(Total_Sales) 
    FOR Item_Fat_Content IN ([Low Fat], [Regular])
) AS PivotTable
ORDER BY Outlet_Location_Type;
```

**Query Explanation:**
1. **Subquery**: Aggregates sales by location and fat content
2. **PIVOT**: Transforms fat content categories into columns
3. **ISNULL**: Replaces NULL values with 0 for cleaner reporting
4. **Result**: Cross-tabulation showing fat content sales across location tiers

---

#### D. Outlet Performance Queries

**Sales by Outlet Establishment Year**
```sql
SELECT Outlet_Establishment_Year, CAST(SUM(Total_Sales) AS DECIMAL(10,2)) AS Total_Sales
FROM blinkit_data
GROUP BY Outlet_Establishment_Year
ORDER BY Outlet_Establishment_Year;
```

**Sales Percentage by Outlet Size**
```sql
SELECT 
    Outlet_Size, 
    CAST(SUM(Total_Sales) AS DECIMAL(10,2)) AS Total_Sales,
    CAST((SUM(Total_Sales) * 100.0 / SUM(SUM(Total_Sales)) OVER()) AS DECIMAL(10,2)) AS Sales_Percentage
FROM blinkit_data
GROUP BY Outlet_Size
ORDER BY Total_Sales DESC;
```

**Window Function Explanation:**
- `SUM(Total_Sales)`: Group-level aggregation
- `SUM(SUM(Total_Sales)) OVER()`: Grand total across all groups
- Result: Percentage contribution of each outlet size

---

#### E. Comprehensive Outlet Metrics

**All Metrics by Outlet Type**
```sql
SELECT Outlet_Type, 
    CAST(SUM(Total_Sales) AS DECIMAL(10,2)) AS Total_Sales,
    CAST(AVG(Total_Sales) AS DECIMAL(10,0)) AS Avg_Sales,
    COUNT(*) AS No_Of_Items,
    CAST(AVG(Rating) AS DECIMAL(10,2)) AS Avg_Rating,
    CAST(AVG(Item_Visibility) AS DECIMAL(10,2)) AS Item_Visibility
FROM blinkit_data
GROUP BY Outlet_Type
ORDER BY Total_Sales DESC;
```

---

## 🏗️ Data Architecture

### Database Schema
```
blinkit_data (Main Table)
├── Item_Identifier
├── Item_Weight
├── Item_Fat_Content (Cleaned: 'Low Fat' | 'Regular')
├── Item_Visibility
├── Item_Type (16 categories)
├── Item_MRP
├── Outlet_Identifier
├── Outlet_Establishment_Year
├── Outlet_Size (Small | Medium | High)
├── Outlet_Location_Type (Tier 1 | Tier 2 | Tier 3)
├── Outlet_Type (Grocery Store | Supermarket Type1/2/3)
├── Total_Sales
└── Rating
```

### Key Data Points
- **8,523 unique items** across inventory
- **10 outlet establishment years** (2012-2022)
- **4 outlet types** (Grocery + 3 Supermarket types)
- **3 outlet sizes** (Small, Medium, High)
- **3 location tiers** (Tier 1, 2, 3)
- **16 item categories** from Fruits to Seafood

---

## 📐 Key Measures & DAX Calculations

### Core Metrics
```dax
Total Sales = SUM(blinkit_data[Total_Sales])

Average Sales = AVERAGE(blinkit_data[Total_Sales])

No of Items = COUNT(blinkit_data[Item_Identifier])

Average Rating = AVERAGE(blinkit_data[Rating])

Average Visibility = AVERAGE(blinkit_data[Item_Visibility])
```

### Advanced Calculations
```dax
Total Sales (M) = 
DIVIDE(
    SUM(blinkit_data[Total_Sales]),
    1000000,
    0
)

Sales by Fat Content = 
CALCULATE(
    [Total Sales],
    blinkit_data[Item_Fat_Content] = "Low Fat"
)

% Sales by Outlet Size = 
DIVIDE(
    [Total Sales],
    CALCULATE([Total Sales], ALL(blinkit_data[Outlet_Size])),
    0
)

Item Count by Type = 
CALCULATE(
    COUNT(blinkit_data[Item_Identifier]),
    ALLEXCEPT(blinkit_data, blinkit_data[Item_Type])
)
```

### Conditional Formatting
```dax
Sales Performance Rating = 
SWITCH(
    TRUE(),
    [Total Sales] >= 500000, "Excellent",
    [Total Sales] >= 200000, "Good",
    [Total Sales] >= 100000, "Average",
    "Below Average"
)
```

---

## 📊 Key Performance Indicators (KPIs)

| Metric | Value | Category |
|--------|-------|----------|
| 💰 **Total Sales** | $1.20M | Revenue |
| 📊 **Average Sales** | $141 | Transaction |
| 📦 **No of Items** | 8,523 | Inventory |
| ⭐ **Average Rating** | 4.0 | Satisfaction |
| 🥗 **Low Fat Sales** | $776.32K | Product Mix |
| 🍔 **Regular Sales** | $425.36K | Product Mix |
| 🏪 **Medium Outlet Sales** | $507.90K | Outlet Performance |
| 🌆 **Tier 3 Sales** | $472.13K | Geographic |

---

## 💡 Business Insights & Recommendations

### 🎯 Key Findings

1. **Health-Conscious Market**
   - Low fat products account for 64.7% of sales
   - **Recommendation**: Expand low-fat product range and promote health benefits

2. **Tier 3 Market Dominance**
   - Tier 3 cities generate 39.3% of total sales
   - **Recommendation**: Increase outlet density in tier 3 markets

3. **Medium Outlet Efficiency**
   - Medium-sized outlets deliver highest ROI
   - **Recommendation**: Prioritize medium-format store openings

4. **Category Leadership**
   - Fruits/Vegetables and Snacks lead at $0.18M each
   - **Recommendation**: Optimize inventory mix with focus on top categories

5. **Consistent Quality**
   - 4.0 average rating across all outlet types
   - **Recommendation**: Maintain quality standards while scaling

### 📈 Growth Opportunities

- **Tier 1 & 2 Expansion**: 60.7% untapped potential in metropolitan areas
- **Large Outlet Format**: Only 20.7% market share - opportunity for premium stores
- **Underperforming Categories**: Seafood, Breakfast items need marketing focus
- **2016 Model Replication**: Analyze successful strategies from peak year

---

## 🎓 Learning Outcomes

This project demonstrates proficiency in:
- ✅ **Power BI Dashboard Development** - Single-page comprehensive analytics
- ✅ **SQL Query Writing** - Complex aggregations, PIVOT tables, window functions
- ✅ **Data Cleaning** - Standardization and quality assurance
- ✅ **DAX Calculations** - Advanced measures and calculated columns
- ✅ **Retail Analytics** - Sales analysis, inventory optimization
- ✅ **Visual Design** - Clean, professional dashboard layout
- ✅ **KPI Tracking** - Business metric definition and monitoring
- ✅ **Data Storytelling** - Insights presentation and recommendations

---

## 🔍 Use Cases

### For Business Analysts
- Track sales performance across multiple dimensions
- Identify top and bottom performing categories
- Analyze geographic sales patterns
- Monitor outlet efficiency metrics

### For Store Managers
- Compare outlet performance benchmarks
- Optimize product mix based on sales data
- Track customer satisfaction ratings
- Identify inventory opportunities

### For Marketing Teams
- Understand customer preferences (Low Fat vs Regular)
- Identify high-performing product categories
- Target marketing campaigns by location tier
- Develop data-driven promotional strategies

### For Operations Teams
- Optimize outlet size and format decisions
- Plan expansion strategies based on historical performance
- Manage inventory levels by item type
- Ensure consistent quality across outlets

### For Executives
- Monitor overall business health through KPIs
- Make strategic decisions on expansion
- Understand market penetration by tier
- Track year-over-year growth trends

---

## 📧 Contact

**Project Maintainer**: Uttam Kumar Biswal

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/https://www.linkedin.com/in/uttam-kumar-biswal-752a10120)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/u77am)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:uttam.biswal047@gmail.com)

---

## ⭐ Show Your Support

If you find this project helpful, please consider giving it a ⭐ star on GitHub!

---

## 🙏 Acknowledgments

- **Blinkit** for providing the business context and dataset structure
- **Power BI Community** for visualization best practices
- **SQL Community** for query optimization techniques
- **Retail Analytics Experts** for domain knowledge validation

---

## 📚 Related Projects

- [Bank Loan Analysis Dashboard](https://github.com/yourusername/bank-loan-analysis)
- [Insurance Portfolio Analytics](https://github.com/yourusername/insurance-analytics)
- [E-commerce Sales Dashboard](https://github.com/yourusername/ecommerce-dashboard)

---

<div align="center">

**Made with ❤️ and Power BI**

*Empowering Quick-Commerce with Data-Driven Insights*

*Last Updated: February 2026*

</div>
