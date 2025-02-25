# Myntra Sales Analysis Project  - EXCEL

This project demonstrates data cleaning, preparation, analysis, and retrieval techniques on Myntra's sales dataset using **Microsoft Excel**. The goal is to derive actionable insights, streamline data, and showcase advanced Excel functionalities to solve real-world business problems.

## 📋 **Project Objectives**

### A. Data Cleaning and Preparation
- ✅ Removed duplicate entries from the dataset.
- ✅ Standardized the `DiscountOffer` column to ensure consistent formatting.
- ✅ Filled missing values:
  - `DiscountPrice`: Replaced null values with the category's average discount price.
  - `SizeOption`: Replaced null values with the text "Not Available."
  
### B. Data Analysis
- 📊 Calculated the **average original price** for products rated above 4.
- 📊 Counted:
  - Products offering a **discount greater than 50% OFF.**
  - Products available in size **"M".**
- 📊 Created a new column to label products as:
  - **High Discount**: Discount greater than 50%.
  - **Low Discount**: Discount 50% or below.

### C. Data Retrieval and Lookup
- 🔍 Used **VLOOKUP/XLOOKUP** to retrieve the brand, price, and rating for a product with `Product_id = 11226634`.
- 🔍 Applied **INDEX and MATCH** functions to find the `DiscountPrice` for the product with `Product_id = 6744434`.
- 🔍 Utilized **nested XLOOKUP** to fetch any product detail using its `Product_id`.

---

## 🛠 **Tech Stack**
- **Tools Used:** Microsoft Excel
- **Techniques:**  
  - Data Cleaning  
  - Data Analysis  
  - Advanced Excel Functions (VLOOKUP, XLOOKUP, INDEX-MATCH)  
  - Nested Lookups  

---

## 📊 **Key Insights**
- Identified pricing trends for highly-rated products.
- Analyzed promotional activity by determining the prevalence of high-discount items.
- Ensured inventory readiness by counting products available in popular sizes.

---

## 🗂 **Project Structure**
```plaintext
├── data/
│   └── myntra_sales_data.xlsx    # Raw dataset (not included for privacy)
├── notebooks/
│   └── analysis_steps.xlsx       # Excel file showcasing all steps
├── outputs/
│   └── myntra_analysis_summary.pdf  # Final presentation slides
└── README.md                    # Project documentation
