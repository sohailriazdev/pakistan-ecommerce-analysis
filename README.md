# Pakistan E-Commerce Sales Analysis

An end-to-end analysis of ~584,500 real orders from Pakistan's largest e-commerce platform, covering data cleaning, exploratory analysis, and an interactive dashboard.

🔗 **[View the Interactive Tableau Dashboard](https://public.tableau.com/app/profile/sohail.riaz/viz/Book1_17910955181110/Dashboard1)**

## 🎯 Objective
- What share of orders are completed, canceled, or refunded?
- Which product categories generate the most revenue?
- How has order volume and revenue trended over time?

## 🗂️ Dataset
[Pakistan Largest Ecommerce Dataset](https://www.kaggle.com/datasets/zusmani/pakistans-largest-ecommerce-dataset) (Kaggle) — ~1 million raw order rows, 2016-2018. *(Not included in this repo due to file size — download from the Kaggle link above to reproduce.)*

## 🛠️ Tools
Python (pandas, matplotlib) for cleaning & analysis · Tableau Public for the interactive dashboard

## 📁 Project Structure
```
pakistan-ecommerce-analysis/
├── README.md
└── pk_ecommerce.ipynb
```

## 📊 Key Findings
- **Fulfillment gap:** Only 40% of orders reach `complete` status; 46% end in cancellation, refund, or return.
- **Category concentration:** `Mobiles & Tablets` generates ~PKR 2.44B — more than the next two categories combined.
- **Seasonality:** Revenue spikes sharply every November (most dramatically Nov 2017, ~6-7x a typical month), pointing to a major annual sales event.
- **Data quality:** ~50% of the raw dataset consisted of fully empty rows, identified and removed during cleaning.

## ▶️ How to Run
1. Download the dataset from the Kaggle link above.
2. `pip install pandas matplotlib`
3. Run `pk_ecommerce.ipynb` top to bottom.
