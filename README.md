# COBOL RPT5000 – Sales Report Program

## Introduction
This COBOL program generates a detailed **Year-To-Date Sales Report** using customer data. It calculates both the **change in sales amount** and the **percentage change** between the current year and the previous year.

In addition to customer-level data, the program also produces:
- Sales Representative totals
- Branch totals
- Grand totals across all data

---

## Table of Contents
- [Authors](#-authors)
- [What does it do?](#-what-does-it-do)
- [Output Example](#️-output-example)
- [COBOL Concepts Used](#-cobol-concepts-used)

---

## Authors
  
**Hayden Schmidt**

- **GitHub**: [Haschm05](https://github.com/Haschm05)
  
- **Email**: [haschm05@wsc.edu]

---

## What does it do?

For each run, the program:

1. Reads customer sales data from an input file  
2. Calculates:
   - Sales difference (This Year - Last Year)
   - Percentage change in sales  
3. Outputs a formatted report including:
   - Branch Number  
   - Sales Representative Number  
   - Customer Number  
   - Customer Name  
   - Sales (This Year)  
   - Sales (Last Year)  
   - Change in Amount  
   - Change in Percentage  
4. Groups and summarizes data at multiple levels:
   - Sales Representative totals  
   - Branch totals  
   - Grand totals  



---

### Resources
- [GeeksForGeeks](https://www.geeksforgeeks.org/cobol/file-handling-in-cobol/?utm_source=chatgpt.com)
- Note: GeeksForGeeks is good for help when troubleshooting or getting broken code working.
  Stick to the textbooks when you can.
