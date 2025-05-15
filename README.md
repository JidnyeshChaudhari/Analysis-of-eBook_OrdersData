# eBook Orders Analysis – Power BI Dashboard
Created a Power BI dashboard built to analyze eBook order data for an online bookstore.  
The goal of this project was to identify sales trends, customer buying patterns, and key performance indicators (KPIs) to support better business decisions.
## 🔍 Dataset Overview
- Order Date: The date when the order was placed.
- Hour: The hour of the day (1-24) when the order occurred.
- Orders Count: Number of eBook orders placed during a particular hour. 
- Books Count: Total number of eBooks purchased in that hour.
## 🧰 Tools Used
- **Power BI**
Various measures & calculated columns, such as total orders, total books, day type, and time slot segregation of hours, were created using DAX (Data Analysis Expressions).
For visualization, line charts, bar charts, and column charts were utilized to effectively represent data trends and patterns. 
- **Excel**
The original wide-format dataset with hourly columns was transformed into a long format by applying the Unpivot Columns operation. Unnecessary columns were removed, resulting in a structured dataset with four key fields: Date, Hour, Order, and Books.
## 🖼️ Dashboard Preview
![eBookOrder_Dashboard_1st_Page](https://github.com/user-attachments/assets/8c577560-ca27-4c99-b454-e3a7d71771dd)
![eBookOrder_Dashboard_2nd_Page](https://github.com/user-attachments/assets/47ecd459-d196-41b6-820a-d8da5c04fe25)
## 📁 Files
[eBookOrder_Dataset_SampleData.xlsx](https://github.com/user-attachments/files/20225926/eBookOrder_Dataset_SampleData.xlsx)
[Cleaned Dataset.xlsx](https://github.com/user-attachments/files/20225927/Cleaned.Dataset.xlsx)
