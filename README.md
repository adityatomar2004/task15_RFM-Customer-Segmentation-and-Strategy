# Task 15: Customer Segmentation (RFM Analysis)

## 📌 Project Overview
This project performs **Customer Segmentation** using the **RFM (Recency, Frequency, Monetary)** technique on the Online Retail dataset. [cite_start]The goal is to categorize customers into distinct segments (e.g., Champions, Loyal Customers, At Risk) to enable targeted marketing strategies and improve customer retention[cite: 5, 26].

## 📊 Visual Analysis
Below is the distribution of customer segments based on the RFM scores.

![Customer Segmentation Chart](segment_chart.png)
<img width="1000" height="600" alt="segment_chart" src="https://github.com/user-attachments/assets/c10e5eac-6723-4ca8-ab9d-f2a7401209e1" />


## 📂 Repository Structure
| File Name | Description |
|:---|:---|
| **`task15_rfm.ipynb`** | [cite_start]The Jupyter Notebook containing the Python code for data cleaning, RFM calculation, segmentation logic, and visualization[cite: 24]. |
| **`rfm_segments.csv`** | [cite_start]The output dataset containing unique Customer IDs, their calculated RFM scores, and their assigned Segment labels[cite: 24]. |
| **`segment_actions.txt`** | [cite_start]A text file outlining specific business strategies and action plans for key customer segments[cite: 24]. |
| **`online_retail_II.csv`** | [cite_start]The raw transaction dataset used for this analysis[cite: 11]. |

## 🛠️ Methodology: RFM Analysis
[cite_start]The customers were segmented based on three key metrics[cite: 17, 28]:
1.  **Recency (R):** Days since the customer's last purchase.
2.  **Frequency (F):** Total number of transactions.
3.  **Monetary (M):** Total money spent.

### Process:
1.  [cite_start]**Data Cleaning:** Removed rows with missing `CustomerID` and filtered cancelled orders[cite: 15].
2.  [cite_start]**Scoring:** Assigned scores from 1 to 4 using **Quantiles** to ensure equal distribution[cite: 18, 30].
3.  [cite_start]**Segmentation:** Grouped customers into segments like **Champions** (High R, F, M) and **At Risk** (High F/M, Low R)[cite: 19].

## 🚀 How to Run
1.  [cite_start]Clone this repository[cite: 43].
2.  Ensure `online_retail_II.csv` is in the directory.
3.  [cite_start]Run `task15_rfm.ipynb` in Jupyter Notebook or Google Colab[cite: 7].

---
[cite_start]*Task completed for Data Analyst Internship* [cite: 2]
