# 📊 Retail Performance Dashboard — Power BI

## 🧠 Overview

This project rebuilds a business analytics dashboard into a proper Business Intelligence model using Power BI.

The dashboard analyzes the retail behavioral funnel:

* App Users
* Store Views
* Product Shares
* Orders
* Revenue

Instead of spreadsheet aggregation, the project implements a semantic data model, relationships, and DAX measures to produce scalable analytics.

---

## 🎯 Objective

To transform spreadsheet-based analytics into a BI data model that supports consistent metrics and reusable calculations.

This simulates how analytics evolves in real companies:

Excel Analysis → Data Model → BI Dashboard

---

## 🗂 Data Model

Multiple event tables are modeled into a star-schema structure.

### Fact Tables

* Orders
* Revenue
* App Activity

### Dimension Tables

* Date
* Store
* User

Relationships are built using keys such as User ID and Date.

---

## 📐 Measures (DAX)

Key business metrics are created using DAX:

* Weekly Active Users
* Unique Users
* Orders Count
* Revenue
* Conversion Funnel Metrics

The model separates:

* Events (activity count)
* Users (distinct count)

---

## 📊 Dashboard Features

* Weekly trend analysis
* Funnel behavior monitoring
* Cross-filtering across stores
* Interactive time filtering
* Consistent metric definitions

---

## 🔍 Business Insights

The dashboard identifies performance changes across the funnel:

Traffic ↓ → Orders ↓ → Revenue ↓
Indicating acquisition issue rather than transaction failure.

---

## 🛠 Tools Used

* Power BI
* Power Query (data transformation)
* DAX Measures
* Data Modeling (Star Schema)

---

## 🧩 Key Skills Demonstrated

* Data modeling
* Metric standardization
* DAX calculation logic
* Analytical thinking
* BI dashboard design

---

## 📁 Files

`Retail_Performance.pbix` — full interactive dashboard
