
# BigBasket Product Data Analysis 📊

## 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on the BigBasket product dataset to understand pricing structure, discount patterns, product ratings, and category-level performance.

The dataset contains 27,555 products across multiple categories including Beauty & Hygiene, Grocery, Kitchen, Household, and more.

---

## 📂 Dataset Summary
- Total Products: 27,555
- Total Columns: 10
- Numerical Columns: Sale Price, Market Price, Rating
- Missing Ratings: 8,636 entries
- Memory Usage: ~2.1 MB

---

## 🛠 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib

---

## 🔎 Key Analysis Performed

### 1️⃣ Data Cleaning
- Identified missing values in rating, sale_price, brand, and description.
- Calculated discount amount and discount percentage.
- Handled outliers using IQR method for sale_price, market_price, and rating.

### 2️⃣ Pricing Analysis
- Average Sale Price: ~₹334 (before outlier treatment)
- After outlier treatment, pricing became more consistent.
- Most products fall within the moderate pricing range (₹50–₹350).
- Few extreme values (up to ₹1,12,475) were detected and treated.

### 3️⃣ Discount Strategy Insights
- Created new columns:
  - Discount Amount
  - Discount Percentage
- Majority of products have low or zero discount.
- Some products offer discounts up to ~83%.
- Discounting appears selectively applied rather than universally.

### 4️⃣ Rating Analysis
- Average rating: ~3.94
- Majority of products are rated between 3.7 and 4.3.
- Several products achieved 5.0 rating.
- 8,636 products have missing ratings — indicating incomplete customer feedback data.

### 5️⃣ Category-Level Performance
- Certain categories consistently show higher average ratings.
- Beauty & Hygiene and Gourmet categories show strong rating trends.
- Rating used as performance indicator due to absence of sales quantity data.

### 6️⃣ Visual Insights
- Histogram shows right-skewed pricing distribution.
- Category-wise rating bar chart highlights performance differences across product categories.

---

## 📊 Business Insights

- BigBasket primarily operates in the mid-range pricing segment.
- Discount strategy is not uniform — likely targeted promotions.
- Product ratings are generally positive (around 4.0 average).
- Missing rating data could impact performance analysis reliability.
- Outlier treatment significantly improved statistical reliability.

---

## 🚀 Conclusion
This EDA provides a clear understanding of pricing structure, rating trends, and discount behavior in the BigBasket product catalog. The analysis demonstrates practical application of data cleaning, feature engineering, outlier handling, and visualization techniques to extract meaningful business insights.

---

