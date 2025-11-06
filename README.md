# Universal Query Generator
# 🌐 Universal Data Query Generator

A lightweight, single-file web utility that simplifies **data migration** and **bulk query generation** for multiple database systems.  
Easily convert CSV or tabular data into **multi-row INSERT** or **UPDATE** statements for SQL and NoSQL databases all in your browser.

---

## 🚀 Project Overview

The **Universal Data Query Generator** eliminates the need for manual query writing or formatting when dealing with large datasets.  
With just a few clicks, it transforms your CSV data into ready-to-execute database queries optimized for different ecosystems.

This tool is handy for:
- Data migration tasks  
- Bulk data updates or inserts  
- Cross-database format conversions  
- Quick query prototyping

---

## ✨ Key Features

✅ **Multi-Database Support**  
Generate queries for:
- **SQL Databases:** MySQL, PostgreSQL, Oracle  
- **NoSQL Databases:** MongoDB, AQL (ArangoDB)

✅ **Dynamic Operations**  
Choose between:
- **INSERT:** For creating new records  
- **UPDATE:** For modifying existing data

✅ **Intelligent CSV Import**  
- Automatically detects and uses CSV headers as field names.  
- Parses data types (numbers, booleans, JSON) intelligently.  
- Supports drag-and-drop or manual file browsing.

✅ **Primary Key Handling (for UPDATE)**  
- Define a primary key field (e.g., `id`) to auto-generate `WHERE` clauses for each record.

✅ **User-Friendly Interface**  
- Sticky table headers for better data visibility.  
- Instant preview of generated queries.

---

## 🛠️ How to Use

1. **Open the Tool**  
   Open `universal_query_generator.html` in any modern web browser (no installation required).

2. **Define Target (Step 1)**  
   - Select your **Target Database Type** (SQL, MongoDB, AQL).  
   - Choose the **Operation Type** (INSERT or UPDATE).  
   - For UPDATE operations, specify your **Primary Key** column name (e.g., `id`).

3. **Import Data (Step 2B)**  
   - Drag and drop your CSV file, or click **Browse File** to upload.  
   - Ensure your CSV includes headers in the first row.

4. **Review Data (Step 2A)**  
   - Inspect and edit imported data directly in the browser.  
   - Add or remove rows if needed.

5. **Generate Query (Step 3)**  
   - Click **Generate Query** to produce formatted multi-row statements.

6. **Copy & Execute (Step 4)**  
   - Copy the generated query and execute it in your target database.

---

## 🔧 Technical Details

- **Single-file build:** `aql_query_generator.html`  
- **Frontend:** HTML5 + Tailwind CSS  
- **Logic Layer:** Pure client-side JavaScript (no backend required)  
- **Compatibility:** Works on all modern browsers (Chrome, Edge, Firefox, Safari)

---

