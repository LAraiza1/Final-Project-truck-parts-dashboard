# Final Project: Truck Parts Dashboard

This repository contains a complete Shiny dashboard project for analyzing real-world truck part listings. The project was completed as part of the **DATA 824: Data Visualization and Acquisition** course.

---

## 📊 What the App Does

The interactive app allows users to:
- Filter truck part listings by item condition (New, Used, All)
- View a dynamic histogram of price distributions
- Explore listing volume over time
- Compare item conditions and pricing behavior
- Interact with a searchable data table

The goal is to support inventory analysis, price modeling, and market insights in a business context.

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `FinalProject.Daniel.Araiza.Rmd` | Main data analysis using R Markdown |
| `ShinyApp_Description.Rmd` | Flexdashboard Shiny app with filtering and plotting |
| `applications.csv` | Source dataset from UsableDatabases |
| `FinalProject.Daniel.Araiza.pptx` | Final presentation with speaker notes |
| `FinalProject.Daniel.Araiza.html` | (Optional) HTML version of R analysis |

---

## 📂 Dataset Information

**Source:**  
[UsableDatabases.com - U.S. Auto Parts Database](https://www.usabledatabases.com/database/us-auto-parts-database-by-year-make-model-engine-brand/)

The dataset contains over 95,000 part listings, including:
- `app_id`, `price_usd`, `item_condition`, `headline`
- `insert_date`, `category_id`, and more

---

## 💻 Tools Used

- **R / RStudio**
- **Shiny + Flexdashboard**
- **ggplot2, DT, dplyr**
- **Tableau Public**

---

## 🎯 Purpose

This project was designed as a business-facing tool that demonstrates visualization principles, storytelling with data, and real-world Shiny application design.
