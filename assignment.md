# 📊Excel Assignment : Data Analysis Dashboard Project

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
  **Data Cleaning And Preparation Solutions**
  
  **Check for and handle missing values, especially in the Reviews and Rating columns**
  
  <img width="1712" height="499" alt="Screenshot 2026-03-30 210724" src="https://github.com/user-attachments/assets/e0ddee88-7f54-48f8-aa42-b8194b6825fe" />
  
  **Identify and remove duplicate product entries**
  
  <img width="707" height="307" alt="image" src="https://github.com/user-attachments/assets/0ef92ada-f652-4f44-8452-9786dfe3a2e2" />
  
  **Convert price columns into numeric format by removing “KSh”**
  
  <img width="858" height="264" alt="image" src="https://github.com/user-attachments/assets/76b0cdcd-fb95-40a4-9bc1-9067e3e92718" />
  
  **Ensure the Discount column is numeric and properly formatted as a percentage**
  
  <img width="454" height="320" alt="image" src="https://github.com/user-attachments/assets/39612fc7-5811-43ae-bee5-a049667e5af7" />
  
  **Convert the Rating column from text format (e.g., “4.5 out of 5”) into numeric values**
  
  <img width="643" height="251" alt="image" src="https://github.com/user-attachments/assets/21153d9b-ccf3-4f2c-a5f8-f7f917cf75ac" />
  
  **Convert negative reviews to positive**
  
  <img width="437" height="218" alt="image" src="https://github.com/user-attachments/assets/5800b858-dd68-4719-b442-124e92c2ccef" />

  **Data Enrichment**
  
  *Create the following additional columns:*
  
**Discount Amount (KSh): Old Price minus Current Price**

<img width="897" height="222" alt="image" src="https://github.com/user-attachments/assets/54fc8837-a062-43a3-b6ef-cb59fb14faad" />

**Rating Category: Poor for ratings below 3, Average for ratings between 3 and 4.4, Excellent for ratings of 4.5 and above**

<img width="612" height="207" alt="image" src="https://github.com/user-attachments/assets/b7e46a78-9744-4fd5-80a4-1e53dc2ac33d" />

**Discount Category: Low Discount for discounts below 20%, Medium Discount for discounts between 20% and 40%, High Discount for discounts above 40%**

<img width="895" height="221" alt="image" src="https://github.com/user-attachments/assets/a1bd3726-b4c7-4776-8e34-8dc516a4e1ef" />

**Data Analysis**

**What is the average current price, old price, discount percentage, and rating?**

<img width="464" height="190" alt="image" src="https://github.com/user-attachments/assets/96bf55e0-2d91-423c-9db5-bafffa5fdab7" />

**Which product is the most expensive and which is the least expensive?**

<img width="411" height="308" alt="image" src="https://github.com/user-attachments/assets/ca972b45-3886-4371-8cc8-6c05177f9313" />

**What is the average rating and discount by discount category?**

<img width="333" height="247" alt="image" src="https://github.com/user-attachments/assets/2e0921e3-1ad5-4c75-9915-3e1dd7ff8888" />

**How are products distributed across rating categories?**

<img width="414" height="232" alt="image" src="https://github.com/user-attachments/assets/c0f49725-59d3-4aa4-9a5b-d1381492483a" />

**Trend and Relationship Analysis**

**Analyze the relationship between discount percentage and number of reviews**

<img width="368" height="223" alt="image" src="https://github.com/user-attachments/assets/7ca584bf-89ef-4f7c-b608-20e4f369687e" />

**Analyze the relationship between rating and number of reviews**

<img width="420" height="323" alt="image" src="https://github.com/user-attachments/assets/48fd4971-aced-434a-997c-6933aff02086" />

**Determine whether higher discounts lead to increased customer engagement**

<img width="952" height="241" alt="image" src="https://github.com/user-attachments/assets/6ffac889-d0d2-4538-a2f6-8e230f7104a6" />

**Determine whether higher-rated products tend to have more reviews**

<img width="370" height="356" alt="image" src="https://github.com/user-attachments/assets/3e1503a4-f0fc-4215-b0c5-6fcfe59f1991" />

**Product Performance Analysis**

**Identify the top 10 products with the highest discounts**

<img width="632" height="308" alt="image" src="https://github.com/user-attachments/assets/7e8f1e67-39c9-4db1-9379-268dcb8133e3" />

**Identify the top 10 products with the most reviews**

<img width="595" height="309" alt="image" src="https://github.com/user-attachments/assets/3d072ff7-87e2-499f-a68c-c7f4a9150015" />

**Identify the top 5 highest-rated and bottom 5 lowest-rated products**

<img width="635" height="269" alt="image" src="https://github.com/user-attachments/assets/fff73a41-f102-46a5-801c-65a81a03ab02" />

<img width="598" height="221" alt="image" src="https://github.com/user-attachments/assets/19ec9adf-682e-4cff-8f89-0c3c9488f63b" />

**Compare high-discount and low-discount products based on average rating and number of reviews**

<img width="373" height="224" alt="image" src="https://github.com/user-attachments/assets/b68c38cb-148c-4dac-a8cf-231bd420443e" />

### Dashboard Design
**Dashboard Requirements, Create a single interactive Excel dashboard containing the following sections:**

*Overview*

* Total number of products
* Average rating
* Average discount percentage
* Total number of reviews
* Top products by rating
* Top products by number of reviews
* Top products by discount percentage
* Visualizations showing discount percentage versus reviews
* Visualizations showing rating versus reviews
* Breakdown of products by rating category
* Breakdown of products by discount category

  <img width="581" height="424" alt="image" src="https://github.com/user-attachments/assets/e01df9d4-00ab-468a-b7d5-323df452ec56" />


















