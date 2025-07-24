# Walmart Data Analysis: End-to-End SQL + Python Project

## 📌 Project Overview
This project is an end-to-end data analysis solution designed to extract critical business insights from Walmart sales data. We utilize Python for data processing and analysis, SQL for advanced querying, and structured problem-solving techniques to solve key business questions.

---

## 🛠️ Project Steps

### 1. Set Up the Environment
**Tools Used:** Visual Studio Code (VS Code), Python, SQL (MySQL and PostgreSQL)  
**Goal:** Create a structured workspace within VS Code and organize project folders for smooth development and data handling.

### 2. Set Up Kaggle API

- **Kaggle Profile:** Visit [Kaggle's homepage](https://www.kaggle.com/) and log in or create an account.
- **API Setup:** Navigate to your Kaggle profile settings and scroll down to the **API section**. Click **"Create New API Token"** to download the `kaggle.json` file.
- **Configure Kaggle:**
  - Place the downloaded `kaggle.json` file in your local `.kaggle` folder (e.g., `C:\Users\<username>\.kaggle\`).
  - Use the command kaggle datasets download -d <dataset-path> to pull datasets directly into your project.
  - You can find the dataset on [Walmart 10k Sales Datasets | Kaggle](https://www.kaggle.com/datasets/najir0123/walmart-10k-sales-datasets)

- **Storage:** Save the downloaded data in the `data/` folder of your project for easy access and organization.

### 3. Download Walmart Sales Data
- **Data Source:** Kaggle API  
- **Dataset Link:** Walmart Sales Dataset  
- **Storage:** Save the data in the `data/` folder for easy reference and access.

### 4. Install Required Libraries and Load Data
- **Install Libraries:**
  pip install pandas numpy sqlalchemy mysql-connector-python psycopg2
- **Load Data:** Read the data into a Pandas DataFrame for initial analysis and transformations.

### 5. Explore the Data
- Use `.info()`, `.describe()`, and `.head()` to understand data distribution, column types, and potential issues.

### 6. Data Cleaning
- **Remove Duplicates**
- **Handle Missing Values**
- **Fix Data Types**
- **Currency Formatting:** Use `.replace()` to format currency values.
- **Validation:** Ensure consistency and verify cleaned data.

### 7. Feature Engineering
- **Create New Columns:** Calculate `Total Amount = unit_price * quantity`
- **Enhance Dataset:** Add calculated fields to streamline SQL analysis.

### 8. Load Data into MySQL and PostgreSQL
- **Connect using SQLAlchemy**
- **Automate Table Creation and Data Insertion**
- **Verify with SQL Queries**

### 9. SQL Analysis: Complex Queries and Business Problem Solving
- Revenue trends across branches and categories  
- Best-selling product categories  
- Sales performance by time, city, and payment method  
- Peak sales periods and customer buying patterns  
- Profit margin analysis by branch and category  
- **Documentation:** Keep notes on query objectives, approach, and results

### 10. Project Publishing and Documentation
- **Documentation:** Use Markdown or Jupyter Notebook  
- **Publish:** Include:
- `README.md`
- Jupyter Notebooks
- SQL query scripts
- Data files or access instructions

---

## 📦 Requirements
- Python 3.8+  
- SQL Databases: MySQL, PostgreSQL  
- Python Libraries:  
`pandas`, `numpy`, `sqlalchemy`, `mysql-connector-python`, `psycopg2`  
- Kaggle API Key

---

## 🚀 Getting Started
```bash
git clone <repo-url>
pip install -r requirements.txt
