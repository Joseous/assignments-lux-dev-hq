# 📊 Assignment 2: Data Analysis Dashboard Project

## 🏷️ Project Title
**Jumia Product Performance Dashboard: Analyzing Pricing, Discounts, and Customer Reviews**

---

## 🎯 Project Objective
The objective of this project is to design and build an **interactive Excel dashboard** that analyzes the performance of products listed on Jumia.

Students will explore how:
- Pricing
- Discounts
- Reviews
- Ratings  

influence product performance and customer engagement.

The final dashboard should support **data-driven decision-making** in an e-commerce context.

---

## 📂 Dataset Overview
The dataset contains product-level data with the following columns:

| Column Name      | Description |
|-----------------|------------|
| Product         | Name of the product |
| Current Price   | Current selling price in Kenyan Shillings (KSh) |
| Old Price       | Original price before discount (KSh) |
| Discount        | Discount percentage applied |
| Reviews         | Number of customer reviews |
| Rating          | Average customer rating out of 5 |

---

## 🧹 Data Cleaning and Preparation

- Check for and handle missing values (especially **Reviews** and **Rating**)
- Identify and remove duplicate product entries
- Convert price columns into numeric format:
  - Remove `"KSh"`, commas, and text
  - Use:
    - **Text to Columns**
    - **Find & Replace (Ctrl + H)**
- Ensure **Discount** is numeric and formatted as a percentage:
  - Use `LEFT()`, `RIGHT()`, or **Text to Columns**
- Convert **Rating** from text (e.g., `"4.5 out of 5"`) into numeric values
- Convert negative reviews to positive values

---

## ➕ Data Enrichment

### 1. Discount Amount (KSh)

### 2. Rating Category
- **Poor** → Rating < 3  
- **Average** → Rating between 3 and 4.4  
- **Excellent** → Rating ≥ 4.5  

### 3. Discount Category
- **Low Discount** → Discount < 20%  
- **Medium Discount** → 20% – 40%  
- **High Discount** → Discount > 40%  

---

## 📈 Data Analysis

### 🔹 Descriptive Analysis
- What is the **average**:
  - Current price
  - Old price
  - Discount percentage
  - Rating
- Identify:
  - Most expensive product
  - Least expensive product
- What is the average rating and discount by **discount category**?
- How are products distributed across **rating categories**?

---

### 🔹 Trend and Relationship Analysis
- Analyze relationship between:
  - Discount % vs Number of reviews
  - Rating vs Number of reviews
- Determine:
  - Do higher discounts increase customer engagement?
  - Do higher-rated products have more reviews?

---

### 🔹 Product Performance Analysis
- Top 10 products with:
  - Highest discounts
  - Most reviews
- Top 5:
  - Highest-rated products
  - Lowest-rated products
- Compare:
  - High-discount vs low-discount products (rating & reviews)

---

## 📊 Dashboard Design

### ✅ Dashboard Requirements
Create a **single interactive Excel dashboard** with the following sections:

---

### 📌 Overview
- Total number of products
- Average rating
- Average discount percentage
- Total number of reviews

---

### 📌 Product Performance
- Top products by rating
- Top products by number of reviews
- Top products by discount percentage

---

### 📌 Trend Analysis
- Discount % vs Reviews (Scatter Plot)
- Rating vs Reviews (Scatter Plot)

---

### 📌 Product Categories
- Products by **rating category**
- Products by **discount category**

---

## 🎨 Visualization Guidelines
- Use **Pivot Tables** as the primary data source
- Recommended charts:
  - Bar charts
  - Column charts
  - Pie / Donut charts
  - Scatter plots
- Apply **conditional formatting**:
  - Highlight high discounts
  - Highlight low ratings
- Add **Slicers** for:
  - Rating category
  - Discount category
  - Price range
 


---

## 🚀 Deliverable
A fully functional **interactive Excel dashboard** that:
- Is clean and well-organized
- Provides actionable insights
- Supports filtering and interaction using slicers

  ### SOLUTIONS
**Question 1** Discount Amount
<img width="897" height="222" alt="image" src="https://github.com/user-attachments/assets/54fc8837-a062-43a3-b6ef-cb59fb14faad" />
