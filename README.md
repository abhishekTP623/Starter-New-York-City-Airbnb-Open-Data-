# New York City Airbnb Open Data Analysis

This project uses the **New York City Airbnb Open Data (2019)** dataset from Kaggle to perform **exploratory data analysis (EDA)** and basic visualizations.  
The goal is to understand pricing, availability, room types, and location-based patterns of Airbnb listings across New York City.

---

## 📌 Dataset Information

- **Dataset Name:** New York City Airbnb Open Data  
- **Source:** Kaggle  
- **Year:** 2019  
- **Total Rows:** 48,895  
- **Total Columns:** 16  
- **File:** `AB_NYC_2019.csv`

Each row represents one Airbnb listing in New York City.

---

## 📂 Project Structure


---

## 📊 Dataset Columns

| Column Name | Description |
|------------|------------|
| `id` | Unique listing ID |
| `name` | Listing name |
| `host_id` | Host ID |
| `host_name` | Host name |
| `neighbourhood_group` | Borough (Manhattan, Brooklyn, etc.) |
| `neighbourhood` | Neighborhood name |
| `latitude` | Latitude of listing |
| `longitude` | Longitude of listing |
| `room_type` | Type of room |
| `price` | Price per night (USD) |
| `minimum_nights` | Minimum stay required |
| `number_of_reviews` | Total reviews |
| `last_review` | Date of last review |
| `reviews_per_month` | Average reviews per month |
| `calculated_host_listings_count` | Listings per host |
| `availability_365` | Available days in a year |

---

## 🧪 Analysis Performed

- Data loading and inspection  
- Distribution plots (histograms & bar charts)  
- Correlation matrix analysis  
- Scatter and density plots  
- Identification of pricing and availability patterns  

---

## 🛠️ Tools & Libraries Used

- Python 3  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook / Kaggle Notebook  

---

## 🚀 Getting Started

### Load the Dataset

```python
import pandas as pd

df = pd.read_csv("AB_NYC_2019.csv")
df.head()
