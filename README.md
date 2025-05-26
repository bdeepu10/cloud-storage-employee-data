# cloud-storage-employee-data
Cloud-based data storage and access using Google Drive with employee data
# Cloud-Based Data Storage and Access using Google Drive (Employee Dataset)

This project demonstrates how to store, access, and analyze an employee dataset using **Google Drive** as a cloud storage platform and **Python (Colab)** for processing and visualization.

## 📌 Project Overview

In today's data-driven world, cloud-based access to data is essential for flexibility and scalability. This project showcases:
- Uploading and mounting Google Drive within Google Colab
- Loading an employee dataset from the cloud
- Cleaning and exploring the data
- Visualizing employee performance metrics

## 📂 Dataset Details

- **Name**: `Employee.csv`  
- **Fields Included**:  
  - `Employee_ID`  
  - `Department`  
  - `Gender`  
  - `Age`  
  - `Job_Title`  
  - `Hire_Date`  
  - `Years_of_Service`  
  - `Performance_Score`  
- **Size**: ~1,000 records  
- **Source**: Simulated Employee Productivity Dataset (CSV format)

## 🛠️ Technologies Used

- **Google Colab**
- **Google Drive (Cloud Storage)**
- **Python**  
  - `pandas`  
  - `matplotlib`  
  - `seaborn`

## 📈 Key Steps Performed

1. **Mount Google Drive** to access stored CSV files.
2. **Read the dataset** using `pandas`.
3. **Handle missing values** with `.dropna()`.
4. **Verify column data types** and structure.
5. **Grouped analysis**:
   - Average performance scores by department.
   - Top 5 employees by performance.
6. **Visualization**:
   - Histogram of `Performance_Score` with `seaborn`.

## ✅ Outcome

- Demonstrated seamless cloud-based access to data using Google Drive.
- Performed quick yet effective EDA and visualized key metrics.
- Highlighted how cloud integration supports scalable analytics pipelines.

## 📎 How to Run

1. Open the notebook in **Google Colab**
2. Upload the dataset to your **Google Drive**
3. Adjust file path if needed:
   ```python
   file_path = '/content/drive/My Drive/DataProjects/Employee.csv'
