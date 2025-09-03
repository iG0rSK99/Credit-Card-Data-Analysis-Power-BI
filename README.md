📊 Credit Card Analysis (Power BI)

This project explores **credit card transactions and customer behavior** using a combination of **SQL for data preparation** and **Power BI for visualization**.  
It provides actionable insights into **revenue growth, card performance, customer demographics, and defaulter risks**.  

---

⚙️ Data Workflow

1. **Data Upload**
   - Raw datasets (`credit_card_transactions.csv`, `credit_card_customers.csv`) were uploaded into a **MySQL database**.

2. **Data Cleaning & Preparation (SQL)**
   - Performed joins between customer and transaction datasets.  
   - Checked for duplicates and handled missing values.   

3. **Data Connection**
   - Connected **Power BI** to the MySQL database for direct data extraction.  
   - Ensured real-time queries and updates from SQL to Power BI.  

4. **Visualization**
   - Built **two dashboards** to summarize findings:  
     - **Credit Card Transaction Report**  
     - **Credit Card Customer Report**

---

📷 Dashboards

### 1. Credit Card Transaction Report
<img width="1231" height="691" alt="Screenshot 2025-09-03 172310" src="https://github.com/user-attachments/assets/de8d40ab-8972-419f-8181-2a34bed44c8e" />


### 2. Credit Card Customer Report
<img width="1233" height="697" alt="Screenshot 2025-09-03 172328" src="https://github.com/user-attachments/assets/ffc15d54-1d89-45b0-a967-c3adfadf8642" />


---

🔑 Key Insights

**Transaction Report**
- **Revenue & Transactions**
  - Total Revenue: **11M**, Transactions: **667K**, Volume: **45.5M**  
  - Peak revenue in **Q3 & Q4 (~2.8M each)**  
- **Card Performance**
  - **Blue Card** contributes **85% revenue** and **89% transactions**  
  - Silver contributes ~9%, while Gold & Platinum are minimal  
- **Expenditure**
  - Highest spend on **Bills (0.18M)** and **Entertainment (0.13M)**  
  - Lowest spend on **Travel (0.05M)**  
- **Usage Patterns**
  - **Swipe transactions (0.45M)** dominate over Chip and Online  

**Customer Report**
- **Customer Base**
  - Total Clients: **10.3K** | Defaulters: **624 (~6%)**  
- **Demographics**
  - **30–40 (45%)** and **40–50 (30%)** are the top contributing age groups  
  - **Businessmen (28%)** and **Self-employed** show higher default risk  
- **Defaulter Trends**
  - **40–50 age group** had the maximum defaulters (**308 clients**)  
- **Geographic Trends**
  - **California, Texas, and New York** lead in transactions  
  - **New Jersey lowest (49K transactions)**  
- **Gender Trends**
  - Male and Female transactions are **almost equally split**  

---

⚙️ Tools & Technologies
- **SQL (MySQL)** → Data cleaning, joining, and aggregation  
- **Power BI** → Interactive dashboards and visualization  
- **Excel/CSV** → Source datasets  

