# Task 15: Customer Segmentation (RFM Analysis)

## 📌 Project Overview
This project performs **Customer Segmentation** using the **RFM (Recency, Frequency, Monetary)** technique on the Online Retail dataset. The goal is to categorize customers into distinct segments (e.g., Champions, Loyal Customers, At Risk) to enable targeted marketing strategies and improve customer retention.

## 📊 Visual Analysis
Below is the distribution of customer segments based on the RFM scores.


<img width="1000" height="600" alt="segment_chart" src="https://github.com/user-attachments/assets/c10e5eac-6723-4ca8-ab9d-f2a7401209e1" />



## 📂 Repository Structure
| File Name | Description |
|:---|:---|
| **`task15_rfm.ipynb`** | The Jupyter Notebook containing the Python code for data cleaning, RFM calculation, segmentation logic, and visualization. |
| **`rfm_segments.csv`** | The output dataset containing unique Customer IDs, their calculated RFM scores, and their assigned Segment labels. |
| **`segment_actions.txt`** | A text file outlining specific business strategies and action plans for key customer segments. |
| **`online_retail_II.csv`** | The raw transaction dataset used for this analysis. |

## 🛠️ Methodology: RFM Analysis
The customers were segmented based on three key metrics:
1.  **Recency (R):** Days since the customer's last purchase.
2.  **Frequency (F):** Total number of transactions.
3.  **Monetary (M):** Total money spent.

### Process:
1.  **Data Cleaning:** Removed rows with missing `CustomerID` and filtered cancelled orders.
2.  **Scoring:** Assigned scores from 1 to 4 using **Quantiles** to ensure equal distribution.
3.  **Segmentation:** Grouped customers into segments like **Champions** (High R, F, M) and **At Risk** (High F/M, Low R).

## 🚀 How to Run
1.  Clone this repository.
2.  Ensure `online_retail_II.csv` is in the directory.
3.  Run `task15_rfm.ipynb` in Jupyter Notebook or Google Colab.

---
*Task completed for Data Analyst Internship*
