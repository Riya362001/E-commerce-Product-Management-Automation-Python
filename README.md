# 🛍️ E-commerce Product Management System (CRUD Automation using Python)

## 📌 Overview
In the fast-paced world of e-commerce, managing large volumes of product information manually can be inefficient and error-prone. This project offers a robust Python-based solution to automate CRUD operations (Create, Read, Update, Delete) for product sales data, details, and descriptions.

## 🎯 Objective
To build a file-handling system that allows admin users to:
- Add, retrieve, update, and delete **product sales data** from CSV files
- Manage **product metadata** (brand, model, price, specs) in JSON files
- Store and update **product descriptions** in plain text files

## 🧰 Tools & Technologies
- Python 3
- File handling (`os`, `json`, `csv`)
- Pretty printing with `pprint`
- Directory navigation and modular programming

## 📂 Project Structure

## 🛠️ Features Implemented

- ✅ **Create:** Add new products (sales, details, description)  
- 🔍 **Read:** View data for a specific product using its SKU  
- ✏️ **Update:** Modify existing product records across all files  
- ❌ **Delete:** Remove all product info based on SKU  
- 🧩 All CRUD actions are orchestrated via a master `crud()` function  

## 🧪 Functional Modules
- `load_data()`: Load existing data from CSV, JSON, and TXT files  
- `add_sales_data()`, `add_product_details()`, `add_product_description()`  
- `display_sales_data()`, `display_product_details()`, `display_product_descriptions()`  
- `update_sales_data()`, `update_product_details()`, `update_product_descriptions()`  
- `delete()`: Cleanly removes all associated data by SKU  
- `crud()`: Central interface for all admin operations  

## 📈 Use Case
- 📦 Added and managed a new product – **Acer Aspire 3 Laptop**
- 📉 Updated sales trends, product info, and revised descriptions
- 🚫 Demonstrated deletion of the product after end-of-life  

## 🧠 Learning Outcomes
- Mastery of Python file I/O and data manipulation
- Implementation of modular, reusable functions
- Understanding of data flow in e-commerce platforms

## 🚀 How to Run
1. Clone or download the repository
2. Place your dataset in the correct folder structure
3. Run the notebook in **Jupyter Notebook** or **Google Colab**
4. Use the `crud()` function to execute operations

## 📎 License
For educational purposes only.

