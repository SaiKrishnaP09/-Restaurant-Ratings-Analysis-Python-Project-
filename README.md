# 🍽️ Restaurant Ratings Analysis (Python Project)

This project aims to analyze restaurant data to identify the best city in India to launch a restaurant. It explores restaurant density, culinary trends, customer ratings, cost ranges, and the impact of services like table booking and online delivery.

---

## 📁 Project Components

- `Project_Code_File.ipynb` – Jupyter notebook with full code.
- `Restaurant__Sourcedata.xlsx` – Raw restaurant dataset.
- `PRESENTATION.pptx` – Summary presentation.

---

## 🧹 Data Cleaning Techniques

The raw dataset was preprocessed using the following techniques:

- **Missing Value Handling**:
  - Dropped rows with critical missing fields (e.g., `Rating`, `City`)
  - Filled missing values in categorical columns using mode

- **Duplicate Removal**:
  - Removed duplicate rows based on restaurant name and location

- **Outlier Detection & Removal**:
  - Removed cost values above a threshold (₹50,000+) using IQR method

- **Standardization**:
  - Normalized column names to lowercase
  - Cleaned `Cuisines` column by trimming extra whitespace

- **Data Type Conversion**:
  - Converted `Rating` column to float
  - Converted cost columns to integers (after removing symbols like ₹, commas)

- **Feature Engineering**:
  - Extracted city with most restaurants
  - Grouped restaurants by locality for density analysis

---

## 🔍 Key Insights

- 📍 **Best City to Launch**: New Delhi – highest number of restaurants
- 🍲 **Cuisine Strategy**: Indian-Chinese Fusion is most favored
- 💰 **Affordability Range**: ₹1000–₹2000 for 2 people
- ⭐ **Ratings Pattern**: Very few restaurants score above 4.5
- 🛵 **Customer Preference**:
  - Table Booking: avg rating = 3.48
  - Online Delivery: avg rating = 3.28
- ⏳ **Long-term Growth**: High ratings take ~5 years

---

## 🛠️ Technologies Used

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Excel (for raw data)
- PowerPoint (for presentation)

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/restaurant-ratings-analysis.git
   cd restaurant-ratings-analysis

