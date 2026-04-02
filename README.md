# Global E-commerce & Logistics 360 Analysis

## 📌 Project Overview
This project provides a comprehensive 360-degree view of a global e-commerce business. By integrating 7 disparate data sources (Sales, Products, Regions, Resellers, Targets, etc.), this dashboard identifies bottlenecks in the supply chain and tracks sales performance against corporate targets.

## 🛠️ Phase 1: Data Engineering & Cleaning (Completed)
Before visualization, I performed a rigorous "Sanity Check" using **Power Query (M)**:
* **Data Integration:** Imported and modeled 7 relational tables into a Star Schema.
* **Data Profiling:** Utilized Column Quality and Distribution tools to ensure 100% data integrity.
* **Cleaning Steps:**
    * Handled missing values by replacing "NA" in the Color category with "Other" to preserve sales row integrity.
    * Standardized data types (Currency for Sales/Cost, Date for OrderDate).
    * Removed redundant filters to ensure a full dataset view.
* **Data Modeling:** Established One-to-Many relationships between Dimension and Fact tables.

## 🚀 Current Status
* [x] Phase 1: Data Cleaning & Modeling
* [ ] Phase 2: DAX Measure Development (In Progress)
* [ ] Phase 3: Dashboard Design & Visualization
* [ ] Phase 4: Insights & Recommendations
