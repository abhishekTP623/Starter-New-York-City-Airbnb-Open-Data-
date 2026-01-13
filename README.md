# New York City Airbnb Open Data Analysis

This project performs exploratory data analysis (EDA) on the **New York City Airbnb Open Data (2019)** dataset obtained from Kaggle. The analysis focuses on understanding Airbnb listing patterns such as pricing, availability, room types, and neighborhood distribution across NYC.

---

## Dataset Details

- **Source:** Kaggle – New York City Airbnb Open Data  
- **Year:** 2019  
- **Rows:** 48,895  
- **Columns:** 16  
- **File:** `AB_NYC_2019.csv`

Each row represents a unique Airbnb listing in New York City.

---

## Dataset Columns

- `id` – Listing ID  
- `name` – Listing name  
- `host_id` – Host ID  
- `host_name` – Host name  
- `neighbourhood_group` – Borough  
- `neighbourhood` – Neighborhood  
- `latitude`, `longitude` – Location coordinates  
- `room_type` – Type of accommodation  
- `price` – Price per night  
- `minimum_nights` – Minimum nights required  
- `number_of_reviews` – Total reviews  
- `last_review` – Date of last review  
- `reviews_per_month` – Reviews per month  
- `calculated_host_listings_count` – Listings per host  
- `availability_365` – Days available per year  

---

## Analysis Performed

- Data loading and inspection  
- Distribution analysis using histograms and bar charts  
- Correlation matrix visualization  
- Scatter and density plots  
- Basic insights into pricing and availability trends  

---

## Tools Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  
- Jupyter / Kaggle Notebook  

---

## How to Run

```python
import pandas as pd
df = pd.read_csv("AB_NYC_2019.csv")
df.head()
