# -customer-trends-data-analysis-SQL-Python-PowerBI
End-to-end customer analytics project using Python, SQL, and Power BI to analyze shopping trends, generate insights, and visualize data through interactive dashboards.

# 📊 Customer Shopping Behavior Analysis

## 🔍 Overview
This project focuses on analyzing customer shopping behavior using transactional data. The goal is to extract meaningful insights related to customer segments, purchasing patterns, product preferences, and revenue drivers to support data-driven business decisions.

The workflow includes data processing in Python, SQL-based analysis, and visualization using Power BI.

---

## 📁 Dataset
- **Total Records:** 3,900 transactions  
- **Features:** 18 columns  

### Includes:
- Customer demographics (Age, Gender, Location, Subscription Status)
- Purchase details (Item, Category, Amount, Season, etc.)
- Behavioral data (Discount usage, purchase frequency, ratings, shipping type)

### Data Issues:
- Missing values in the *Review Rating* column handled using median imputation per category  

---

## 🛠️ Tools & Technologies
- **Programming:** Python (Pandas, NumPy, Matplotlib, Seaborn)
- **Database:** PostgreSQL / MySQL / SQL Server
- **Visualization:** Power BI
- **Reporting:** Gamma (PPT creation)
- **Others:** Jupyter Notebook, SQL

---

## ⚙️ Project Workflow

### 1. Data Loading & Exploration
- Imported dataset using Pandas  
- Performed initial analysis using `.info()` and `.describe()`  

### 2. Data Cleaning & Preparation
- Handled missing values  
- Renamed columns (snake_case)  
- Removed redundant features  
- Created new features:
  - Age groups  
  - Purchase frequency  

### 3. Database Integration
- Loaded cleaned dataset into SQL database  
- Enabled structured querying for business insights  

### 4. SQL Analysis
Performed multiple business-focused queries:
- Revenue by gender  
- High-spending discount users  
- Top-rated products  
- Shipping type comparison  
- Subscriber vs non-subscriber analysis  
- Customer segmentation (New, Returning, Loyal)  
- Revenue by age group  

---

## 📊 Dashboard
An interactive **Power BI dashboard** was built to visualize insights:
- Total customers and average purchase value  
- Revenue distribution by category and age group  
- Subscription analysis  
- Sales trends  

---

## 📈 Key Results & Insights
- Male customers generated higher total revenue compared to females  
- Discount users can still be high spenders  
- Certain products consistently receive higher ratings  
- Subscription does not always guarantee higher spending  
- Young adults contribute the highest revenue share  
- Loyal customers form the majority segment  

---

## 💡 Business Recommendations
- Promote subscription benefits to increase adoption  
- Introduce loyalty programs for repeat customers  
- Optimize discount strategies for profitability  
- Focus marketing on high-revenue age groups  
- Highlight top-performing products  

---

## ▶️ How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/iamdevanshmishra/-customer-trends-data-analysis-SQL-Python-PowerBI.git
cd -customer-trends-data-analysis-SQL-Python-PowerBI
