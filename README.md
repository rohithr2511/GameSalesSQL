# 🎮 Analyzing Game Sales Across Regions and Platforms

## 📌 Project Overview
The gaming industry is highly competitive, and understanding **sales patterns across different regions and platforms** is crucial for developers and publishers. This project aims to analyze a **game sales dataset** to extract meaningful insights using **SQL operations** such as **aggregations, joins, inserts, updates, and deletions**.

## 🎯 Problem Statement
The objective of this project is to **analyze game sales data** to help developers and publishers **optimize their strategies**. By leveraging **SQL queries**, we will manipulate and explore data to understand the **sales performance of various games** across multiple platforms and regions.

## 🛠️ Technologies Used
- **Database:** MySQL
- **Querying Techniques:** Aggregations, Joins, Subqueries, CTEs, Data Manipulation
- **Tools:** SQL Workbench, MySQL CLI

---

## 📂 Dataset Information
### **1️⃣ Games.csv** (Game Details)
| Column Name    | Description                        |
|---------------|------------------------------------|
| **GameID**     | Unique identifier for the game    |
| **GameTitle**  | Title of the game                |
| **Genre**      | Genre category of the game       |
| **ReleaseDate** | Release date of the game        |
| **Developer**  | Developer of the game           |

### **2️⃣ Game Sales.csv** (Sales Data)
| Column Name    | Description                        |
|---------------|------------------------------------|
| **GameID**     | Unique identifier (Foreign Key)  |
| **Platform**   | Gaming platform (PlayStation, Xbox, etc.) |
| **SalesRegion** | Region where the game was sold |
| **UnitsSold**  | Number of units sold            |
| **Price**      | Sale price of the game          |

---

## 🚀 SQL Query Objectives

### **1️⃣ Insert a New Game Record**
Insert a new game with:
- **Title:** Future Racing
- **Genre:** Racing
- **Release Date:** 2024-10-01
- **Developer:** Speed Studios

### **2️⃣ Update Game Price**
Update the **price of the game with GameID 2** on the **PlayStation** platform to **60**.

### **3️⃣ Delete a Game Record**
Delete the **record of the game with GameID 5** from the **Game Sales** table.

### **4️⃣ Calculate Total Units Sold Per Game**
Retrieve the **total number of units sold for each game** across **all platforms and regions**.

### **5️⃣ Identify the Best-Selling Game in North America**
Find the **game with the highest number of units sold** in **North America**.

### **6️⃣ Retrieve Game Titles with Sales Details**
Get the **game titles, platforms, and sales regions** along with the **units sold for each game**.

### **7️⃣ Find All Games (Including Those Without Sales Data)**
Retrieve **all games**, even those that have **no sales data** in the **Game Sales** table.

### **8️⃣ Retrieve Sales Records Without Corresponding Game Details**
Find all **sales records where the game details are missing** in the **Games** table.

### **9️⃣ Retrieve Unique Sales Data for North America & Europe**
Get **game sales data for North America and Europe**, removing **duplicate records**.

### **🔟 Retrieve All Sales Data for North America & Europe (With Duplicates)**
Get all **game sales data from North America and Europe**, including **duplicate records**.



## 🚀 How to Use
1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/Game-Sales-Analysis.git
   ```
2. **Import the dataset** into **MySQL**.
3. **Run the SQL scripts** to execute queries and analyze game sales.
4. **Modify constraints and stored procedures** for custom insights.

---

## 📈 Expected Insights
- **Top-selling games & platforms**
- **Regional sales trends**
- **Game pricing insights**
- **Data validation & missing records identification**


📌 **Author:** P Rohith Raveendran  
🔗 [GitHub Profile](https://github.com/rohithr2511) | 🔗 [LinkedIn Profile](https://www.linkedin.com/in/p-rohith-raveendran-dataanalyst/)  

