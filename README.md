# 📊 Amazon Sales Dashboard

This project presents a fully interactive **Amazon Sales Dashboard** built in **Power BI**. It merges Amazon Sales Data with Amazon Fashion Product Details to deliver insights on regional performance, product trends, and category-level breakdowns.

---

## 🔍 Introduction

The dashboard provides a 360-degree view of Amazon product performance by integrating transactional sales data with rich product metadata. It allows users to explore key metrics, track trends, and make informed decisions with interactive visuals and filters.

---

## 🎯 Objective

- Analyze Amazon’s fashion product sales across regions and categories.
- Track KPIs like Total Sales, Orders, and Ratings.
- Provide detailed product-level analytics including stock, discount, reviews, and more.
- Enable product preview with image, price, and description for better product understanding.

---

## ⚙️ Process

### 1. **Data Cleaning & Modeling**
- Merged two datasets:
  - **Amazon Sales Data**: Order ID, Date, Fulfillment, Sales Channel, Quantity, Location, etc.
  - **Amazon Fashion Details**: ASIN, Product Name, Ratings, Reviews, Seller, Description, etc.
- Cleaned nulls, corrected data types, and removed duplicates.
- Created relationships between tables and applied DAX measures for KPIs.

### 2. **Dashboard Pages**

#### 📌 Overview Page
- KPIs: **Total Sales**, **Total Orders**, **Average Rating**
- Visuals:
  - **Bar Chart**: Sales by State and City
  - **Line Chart**: Sales Trend over time
  - **Filters**: Category, Product, Sales/Units
  - **Buttons**: Navigation across report pages
  - **Branding**: Amazon logo and themed visuals

#### 🛍️ Product Page
- Product-wise insights
- Tooltip with:
  - Description
  - Ratings
  - Sales Trend
- Filter by Category and Product
- Image and trend visualization

#### 🔍 Product Preview Page
- Product Gallery View:
  - Image
  - Price
  - Description

---
## 📸 Dashboard Preview

*(Add screenshots in a `/Screenshots` folder and embed here)*

---

## 📈 Insights

- **Top-performing categories** drive the bulk of the revenue.
- **Specific cities/states** have higher conversion rates.
- **Higher ratings and reviews** correlate with stronger product sales.
- **Best Seller** and **Amazon Prime** tags positively impact sales performance.
- Sales trends vary significantly by category and time of year.

---

## 💡 Recommendations

- Focus advertising on high-performing regions.
- Promote top-rated and best-seller products.
- Maintain stock levels for fast-moving items.
- Enhance listings of underperforming products (images, descriptions).
- Utilize Prime and discount strategy to increase engagement.

---


## 🛠️ Tools Used

- **Power BI**
- **DAX**
- **Data Modeling**
- **Data Cleaning & Transformation**

---

## 📌 How to Use

1. Clone or download this repository.
2. Open the `.pbix` file in Power BI Desktop.
3. Interact with filters and visuals for deep insights.
4. Modify or enhance the visuals as per your own business needs.

---



## 📬 Contact

For questions, feedback, or collaboration ideas, feel free to reach out!

---

