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

- The dataset was **very compact and in a wide format**, which made it difficult to analyze directly. This project helped me understand the **importance of data cleaning and manipulation** as a foundational step in any analysis workflow.
- As part of the solution, I used **Excel's 'Unpivot Columns'** feature to restructure the dataset into a long format, which made it easier to import into Power BI and build effective visualizations.
- I faced difficulties in finding strong relationships between fields due to the **limited size and scope of the dataset**. This made developing meaningful visuals in Power BI more challenging. However, these constraints helped me **develop critical thinking and problem-solving abilities** by forcing me to think creatively about how to extract value from minimal data'
- By creating calculated columns in Power BI to extract monthly trends, by learning DAX functions like `MONTH()` and `FORMAT()` helps to visualize the data effectively
## 📁 Files
- [eBookOrder_Dataset_SampleData.xlsx](https://github.com/user-attachments/files/20225926/eBookOrder_Dataset_SampleData.xlsx)
- [Cleaned Dataset.xlsx](https://github.com/user-attachments/files/20225927/Cleaned.Dataset.xlsx)
## 📌 Author
Jidnyesh Chaudhari [Connect me on Linkedin](https://www.linkedin.com/in/jidnyesh-chaudhari-6b98201bb?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BX99BQGujQzCTS8BB63xKfQ%3D%3D)
