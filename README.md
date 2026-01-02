# RTC: Customer Shopping Data Analysis

## 📌 Project Overview
This project analyzes customer shopping behavior using Python (Pandas, Matplotlib, Seaborn) in Jupyter Notebook.  
The dataset includes invoices, customer demographics, product categories, prices, quantities, payment methods, and shopping mall details.  
The goal is to uncover insights into **sales trends, pricing patterns, and customer preferences**.

---

## 📂 Dataset Structure
The dataset contains the following columns:

- `invoice_no` → Unique invoice identifier  
- `customer_id` → Unique customer identifier  
- `gender` → Male / Female  
- `age` → Customer age  
- `category` → Product category (Clothing, Shoes, Technology, etc.)  
- `quantity` → Number of items purchased  
- `price` → Price per item  
- `payment_method` → Payment type (Cash, Credit Card, etc.)  
- `invoice_date` → Date of purchase  
- `shopping_mall` → Mall where purchase occurred  

---

## 📊 Key Analyses
1. **Total Sales by Category**  
   - Bar chart showing which product categories generate the most revenue.  
   - Clothing, Shoes, and Technology dominate sales.  

2. **Total Sales by Gender**  
   - Comparison of male vs female purchasing behavior.  
   - Female customers contribute higher total sales.  

3. **Total Sales by Payment Method**  
   - Identifies preferred payment channels.  

4. **Sales by Age Group**  
   - Groups customers into age bins (e.g., 20–29, 30–39).  
   - Reveals spending trends by age.  

5. **Sales by Category and Gender (Stacked Bar)**  
   - Shows gender contribution within each category.  
   - Totals displayed on top of each stacked bar.  

6. **Price Distribution**  
   - Histogram and boxplots to highlight common price ranges (e.g., 300, 600, 1200, 1500, 3000+).  

---

## 🛠️ Tools & Libraries
- **Python 3**  
- **Jupyter Notebook**  
- **Pandas** → Data manipulation  
- **Matplotlib / Seaborn** → Visualization  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Thrishaj2005/Customer-Shopping-Analysis.git
