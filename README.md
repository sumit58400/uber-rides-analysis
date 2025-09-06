# 🚖 Uber Ride Analysis  

This project performs **exploratory data analysis (EDA)** on Uber ride data to identify patterns in demand, trip categories, distance, and ride purposes. Using Python and Jupyter Notebook, the dataset is cleaned, transformed, and visualized to extract meaningful insights about Uber usage behavior.  

## 📊 Objectives  
- Clean and preprocess Uber ride dataset.  
- Analyze ride demand over time.  
- Understand categories (Business vs Personal).  
- Identify common ride purposes and locations.  
- Visualize mileage distribution and trip patterns.  

## 🛠️ Tech Stack  
- **Language:** Python  
- **Environment:** Jupyter Notebook  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  

## 📂 Dataset  
The dataset contains **1,156 records** with 7 columns:  
- `START_DATE`, `END_DATE`: Trip timestamps  
- `CATEGORY`: Business or Personal trip  
- `START`, `STOP`: Start and stop locations  
- `MILES`: Distance of trip  
- `PURPOSE`: Purpose of ride (Meeting, Errand, Customer Visit, etc.)  

Dataset Source: [Kaggle Uber Dataset](https://www.kaggle.com/fivethirtyeight/uber-pickups-in-new-york-city)  

## 🔑 Key Insights  
- **Business trips dominate** the dataset compared to personal rides.  
- Many rides have **short distances (<10 miles)**.  
- Peak activity is observed during **workdays and commute hours**.  
- Missing values in `PURPOSE` were handled by filling with "NOT".  

## 📸 Sample Visualizations  
*(Add screenshots of your graphs here for better presentation)*  

- Ride distribution by category  
- Mileage histogram  
- Purpose-wise trip frequency  

## 🚀 How to Run  
1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/uber-ride-analysis.git
   cd uber-ride-analysis
