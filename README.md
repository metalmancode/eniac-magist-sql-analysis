# 📊 SQL Project – Eniac & Magist Case Study
SQL case study analyzing Eniac’s potential expansion into Brazil via Magist’s e-commerce database

## 📌 Project Overview
It’s the fall of 2018.  
COVID-19 has not yet emerged, and AI-powered chat agents are still in their infancy.  

**Eniac** is an online marketplace specializing in Apple-compatible accessories.  
Founded in Spain 10 years ago, it has since expanded across Europe, offering:
- A wide catalog of products at competitive prices  
- Friendly and professional tech support  
- A strong customer-first culture  

As Eniac grows internationally, the company is exploring **expansion into Brazil**.  
To do this, it considers partnering with **Magist**, a Brazilian SaaS company that provides:
- Centralized order management  
- Logistics & shipping services  
- After-sales support  

The key question:  
👉 *Is Magist the right partner for Eniac to enter the Brazilian market?*

---

## 🎯 Project Scope
As the **Data Analyst**, my task was to:
1. Explore Magist’s database snapshot  
2. Answer critical business questions around:
   - Tech product fit  
   - Seller ecosystem  
   - Delivery performance  
3. Provide a **data-driven recommendation** to Eniac’s leadership team  

Deliverable: **A presentation summarizing findings and recommendation**

---

## 🗂️ Dataset
Magist provided a snapshot of their e-commerce database, including multiple tables:  
- `orders` – order IDs, timestamps, delivery status  
- `order_items` – product, seller, and pricing details  
- `products` – category, type, and attributes  
- `sellers` – seller info and revenue  
- `customers` – buyer demographics and region  

---

## 🧑‍💻 SQL Skills Demonstrated
This project was designed to showcase **fundamental SQL knowledge**:
- Selecting and filtering data with `WHERE`, `GROUP BY`, `HAVING`  
- Joining multiple tables with `INNER JOIN`, `LEFT JOIN`  
- Aggregating values using `COUNT`, `SUM`, `AVG`  
- Using **CASE WHEN** for conditional classification  
- Calculating delivery performance with `DATEDIFF`  
- Translating business questions into SQL queries  

---

## 🔎 Business Questions & SQL Insights
### 1. Products
- What categories of **tech products** exist in Magist’s database?  
- How many tech products were sold, and what % of total sales do they represent?  
- What is the **average selling price**?  
- Are expensive tech products popular? *(using CASE WHEN logic)*  

### 2. Sellers
- How many **months of data** are covered?  
- Total sellers vs. tech sellers (% share)?  
- Revenue analysis:  
  - Total seller earnings  
  - Total tech seller earnings  
  - Average monthly income (all sellers vs. tech sellers)  

### 3. Delivery
- What’s the **average delivery time** (order → delivery)?  
- How many orders were **on time vs delayed**?  
- Are **larger products delayed more often**?  

---


