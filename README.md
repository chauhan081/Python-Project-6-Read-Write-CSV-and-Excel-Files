# Python Project 6: Read & Write CSV and Excel Files 📊📁  

## 📌 Problem Statement:  
Create a Python script that can read data from a CSV file and write it to an Excel file (and vice versa).

## 🧠 What You'll Learn:  
- Reading CSV using pandas  
- Writing Excel files using ExcelWriter  
- File handling and data manipulation  

## ✅ Python Code:  
``` 
import pandas as pd

Read data from CSV
csv_data = pd.read_csv("data.csv")
print("CSV Data:")
print(csv_data)

Write to Excel
csv_data.to_excel("data_output.xlsx", index=False)

Read back from Excel
excel_data = pd.read_excel("data_output.xlsx")
print("\nExcel Data:")
print(excel_data)
```

## 📥 How It Works:  
- Reads data.csv file  
- Converts and saves it as an Excel file  
- Reads the Excel file to confirm successful write

## 🔧 Try modifying:  
– Add filters or sorting  
– Select specific columns  
– Append new rows before saving  

## 💡 Use Cases:  
– Convert CSV sales reports to Excel  
– Clean and reformat exported data  
– Automate data handling tasks  
