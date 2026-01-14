# 🗄️ Applying Filters to SQL Queries

> Demonstrating the use of SQL filtering techniques to investigate security events and manage employee systems.

---

## 📖 Project Overview

This project demonstrates my experience using **SQL filters** to investigate potential security issues within a large organization. As a security professional, part of my responsibility is to analyze login activity and employee data to help maintain system security.

Using the organization’s `employees` and `log_in_attempts` tables, I applied SQL queries with filtering conditions to retrieve relevant records, investigate suspicious activity, and identify employee machines that require security updates. This project builds practical SQL skills that are commonly assessed during cybersecurity and analyst interviews.

---

## 🎯 Project Objectives

- Investigate suspicious login activity using SQL queries  
- Analyze login attempts based on time, date, and location  
- Retrieve employee information for targeted security updates  
- Demonstrate effective use of SQL filtering operators  
- Clearly explain query logic and results  

---

## 🧩 Scenario Summary

You are a security professional at a large organization responsible for investigating potential security incidents. Recently, suspicious login attempts and system update requirements were identified. To respond, SQL filters are used to query login and employee data to support investigation and remediation efforts.

---

## 🔍 SQL Filtering Techniques Demonstrated

### ⏰ Filtering After-Hours Failed Login Attempts
SQL filters are used to identify **failed login attempts that occurred after business hours**. This helps detect suspicious access attempts that may indicate unauthorized activity.

### 📅 Filtering Login Attempts by Date
Date-based filters are applied to review login activity on **specific dates**, allowing investigation of incidents tied to known events.

### 🌍 Filtering Login Attempts by Location
The `LIKE` operator and wildcards are used to identify login attempts that occurred **outside of a specific country**, helping detect unusual geographic activity.

### 🏢 Filtering Employees by Department and Location
Logical operators such as `AND` are used to retrieve employees from a **specific department and building**, supporting targeted system updates.

### 🔀 Filtering with AND / OR
The `AND` and `OR` operators are used to apply **multiple conditions** in a single query, ensuring precise data retrieval.

### 🚫 Filtering with NOT
The `NOT` operator is used to **exclude specific departments**, allowing identification of employees who still require security updates.

---

## 🧠 Key SQL Concepts Used

- `WHERE` clause for filtering records  
- `AND` and `OR` for multiple conditions  
- `NOT` for exclusion-based filtering  
- `LIKE` with `%` wildcard for pattern matching  
- Date and time filtering for security investigations  

---

## 📝 Summary

In this project, I used SQL filtering techniques to investigate login activity and retrieve employee information related to potential security incidents. By applying logical operators, pattern matching, and date/time filters, I was able to extract meaningful insights from multiple datasets. This activity demonstrates practical SQL skills that are directly applicable to cybersecurity analysis and incident investigation.

---

## 🚀 Key Skills Demonstrated

- SQL Query Writing  
- Data Filtering and Analysis  
- Security Event Investigation  
- Logical Reasoning with AND / OR / NOT  
- Pattern Matching with LIKE  
- Technical Documentation for Portfolios  

---

## 📎 Disclaimer

This project is based on a fictional scenario and is intended solely for **educational and cybersecurity portfolio demonstration purposes**.
