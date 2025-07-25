# 📊 SSRS Report: General Information About Employees

## 📌 Overview

This SSRS (SQL Server Reporting Services) project provides a structured and visual summary of employee data across various dimensions. It is designed to help HR departments, managers, and executives gain insight into the composition and trends of the workforce using clear charts and tabular data.

The report is built using Microsoft Report Builder and connects to the **AdventureWorksDW2016** data source. It uses fields from the `Employee` dataset to deliver multiple layers of analytical breakdowns.

---

## 📁 Report Name

**info of employees.rdl**

---

## 📊 Key Sections of the Report

### 1. Status of Employees
A breakdown of employees by their **current employment status**, summarized in a table and chart format to highlight the distribution of statuses across the organization.

### 2. Marital and Gender Composition
Displays a cross-analysis between **marital status** and **gender**, showing the number of employees in each category. This helps in understanding diversity and demographic trends within the workforce.

### 3. Employment by Start Year
Presents historical hiring data by **year of employment**, allowing stakeholders to observe trends in recruitment volume and workforce growth over time.

---

## 🧾 Dataset and Fields Used

The report utilizes the following key fields from the `Employee` dataset:

- `EmployeeKey`
- `Current_status`
- `MaritalStatus`
- `Gender`
- `StartDate_year`
- Other relevant employee details (e.g., `Title`, `BirthDate`, `HireDate`, etc.)

---

## 🛠️ Tools and Technologies

- Microsoft SQL Server Reporting Services (SSRS)
- Microsoft Report Builder
- SQL Server (AdventureWorksDW2016 Data Warehouse)

---

## 🚀 How to Use

1. Open `info of employees.rdl` in **Microsoft Report Builder** or **Visual Studio** with SSRS support.
2. Ensure the `AdventureWorksDW2016` data source is correctly configured.
3. Run the report to preview or deploy it to your SSRS server.
4. Modify expressions, filters, or groupings as needed for your organization’s requirements.

---

## 💼 Use Cases

- HR analytics and workforce planning
- Executive dashboards
- Diversity and inclusion monitoring
- Employment trend tracking

---
