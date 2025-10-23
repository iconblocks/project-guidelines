# Iconblocks Coding Standards

This document defines the **standard formats** to be used across all projects for consistency.  
All developers must follow these conventions when working with data, code, and database fields.

---

## 1. Date Format

- **UI / Display Format:** `MM/DD/YYYY`  
  *Example:* `09/29/2025`  
- **Database Format:** `YYYY-MM-DD` (ISO 8601)  
  *Example:* `2025-09-29`  
- **Time Format:** `hh:mm AM/PM` (12-hour U.S. format)  
  *Example:* `03:45 PM`

---

## 2. Employee

- **Employee Name Format:** `First Name, Last Name`  
  *Example:* `John, Doe`

---

## 3. Company & Store

- **Store/Company Name Format:** `Code - Name`  
  *Example:* `900901 - Manchester`  
- **Store Code:** Always 6 digits, zero-padded if needed.  
  *Example:* `000123`

---

## 4. Grid (Data Table) Formatting Standards – *U.S. Zone*

All application data grids must adhere to the following formatting and usability standards.

### 4.1 Column Naming
- Use **Title Case** for headers.  
  *Example:* `First Name`, `Hire Date`, `Total Sales`
- Avoid abbreviations unless industry standard (`ID`, `SKU`, `ZIP Code`).
- Column names must be **self-explanatory** and **localized for U.S. English**.

### 4.2 Data Alignment
- **Text:** Left-aligned  
- **Numbers & Currency:** Right-aligned  
- **Dates/Times:** Center-aligned  
- **Checkbox/Boolean Fields:** Center-aligned  

### 4.3 Numeric Format
- Use U.S. standard numbering: comma for thousands, dot for decimal.  
  *Example:* `12,345.67`  
- Decimal precision:
  - **Currency:** 2 decimal places (`$1,250.00`)
  - **Percentages:** 1 or 2 decimal places (`15.25%`)
- Negative values shown with a minus sign (no parentheses): `-125.50`

### 4.4 Currency
- **Currency Symbol:** `$` (U.S. Dollars)  
  *Example:* `$2,450.75`  
- Symbol should **precede** the number without space.  
- For multi-currency apps, display currency code in parentheses: `$2,450.75 (USD)`
