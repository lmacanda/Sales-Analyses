# 📊 Sales Analysis with Python — CRISP-DM

This project demonstrates an exploratory sales analysis using the **CRISP-DM** process. The analysis was developed in **Google Colab**, using **Pandas**, **Matplotlib**, and **Seaborn** for data manipulation, visualization, and insight extraction.

---

## 📌 Objectives

- Identify the best-selling products and categories
- Analyze customer purchase behavior by age group
- Investigate the impact of weekdays and holidays on sales
- Answer business questions 

---

## 🧠 CRISP-DM Steps

### 1. Business Understanding
- **Which product generated the most total revenue?**
- **Which category sold the most units?**

### 2. Data Understanding
- **What is the average ticket per customer?**
- **Which days of the week have the highest sales volume?**

### 3. Data Preparation
- Created a `customer_type` column:  
  → "Young" if age < 30, "Adult" otherwise
- Merged sales data with customer and calendar datasets
- Filtered sales made on holidays

### 4. Modeling (Exploratory Visualization)
- **Bar chart** showing revenue per category
- **Line plot** of daily sales with holidays highlighted


### 5. Evaluation
- **Are more expensive products also the top sellers?**  
  → Scatter plot: average price vs. quantity sold
- **Do younger customers spend more or less?**  
  → Boxplot: `valor_total` by customer type and age range


---

## 🛠 Technologies Used

- Python 3
- Pandas
- Matplotlib
- Seaborn
- Google Colab

---

## ✍️ Author

**[Laura Pantano]**  
[[LinkedIn: (https://www.linkedin.com/in/lauramacandapantano/)l]

---

## ✅ How to Use

1. Clone the repository:
```bash
git clone https://github.com/yourusername/your-repo.git
