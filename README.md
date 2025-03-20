# 📊 Instagram User Analytics Report  

## 🚀 Project Overview  
This project analyzes Instagram user data using **SQL** to derive valuable insights for **marketing strategies**, **product improvements**, and **investor decisions**.  

By simulating a **data analyst’s role**, this project provides insights into **user engagement, content trends, and potential bot activity**, helping stakeholders make **data-driven decisions**.  

## 🏆 Key Objectives  
✔️ **Identify** user behavior patterns to enhance engagement strategies  
✔️ **Optimize** marketing campaigns through data-driven insights  
✔️ **Detect** potential fake/bot accounts for platform integrity  
✔️ **Provide** investors with metrics to evaluate platform growth  

---

## 🏛️ **Database Schema**  
The following **ER Diagram** represents the structure of the database used in this project.  

![ER Diagram](./assets/er_diagram.png)  

🔹 The dataset consists of tables such as **Users, Photos, Likes, Comments, and Tags**.  

### **Dataset Preview (Users Table)**  
| User ID | Username        | Created At  |  
|---------|---------------|------------|  
| 1       | Kenton_Kirlin  | 2017-02-16 |  
| 2       | Andre_Purdy85  | 2017-04-02 |  
| 3       | Harley_Lind18  | 2017-02-21 |  
| 4       | Arely_Bogan63  | 2016-08-13 |  
| 5       | Aniya_Hackett  | 2016-12-07 |  

---

## 🛠️ **Tech Stack**  
🔹 **SQL Tool**: MySQL Workbench  
🔹 **Database**: MySQL  
🔹 **Languages**: SQL  

---

## 🔍 **Approach**  
The project is divided into two major sections:  

### 📊 **Marketing Analysis**  
✔️ **Loyal User Reward** – Identify the five oldest users to reward them for platform loyalty  
✔️ **Inactive User Engagement** – Find users who have never posted and suggest strategies to engage them  
✔️ **Contest Winner Declaration** – Determine which user received the most likes on a single post  
✔️ **Hashtag Research** – Identify the top five trending hashtags to maximize marketing reach  
✔️ **Ad Campaign Optimization** – Find the most popular day for user registration to schedule ad launches  

### 💰 **Investor Metrics**  
✔️ **User Engagement** – Calculate average posts per user to measure platform activity  
✔️ **Bot & Fake Account Detection** – Identify users who have liked every single post, indicating possible bot activity  

---

## 📌 **SQL Queries & Results**  

### **1️⃣ Loyal User Reward**  
**Objective:** Find the five oldest Instagram users.  
```sql
SELECT * FROM Users ORDER BY created_at LIMIT 5;

## data set of users
- <a href="https://docs.google.com/document/d/1-WhNRX1iYJIz7e5l28DMPWgsPklpE_w6/edit?tab=t.0">dataset</a>
