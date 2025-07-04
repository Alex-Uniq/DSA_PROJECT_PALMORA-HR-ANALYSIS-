# 📊 Palmora Group HR Analytics Report

**Author:** Obiekezie Precious Chinaza  
**Role:** HR Data Analyst  
**Tools Used:** Excel (Mobile - WPS)  
**Focus Areas:** Gender Equality • Salary Structure • Regional Compliance • Bonus Allocation  

---

## 📈 Executive Summary

This report presents a detailed analysis of HR data for **Palmora Group**, focusing on gender-related issues, pay structure, performance ratings, and compliance across three operating regions: **Abuja, Kaduna, and Lagos**.

Key insights reveal:
- Evidence of a gender pay gap  
- Low compliance with the $90,000 minimum salary regulation  
- Imbalanced gender distributions across departments  

Visualizations and pivot tables were used to guide strategic recommendations for addressing inequalities and aligning compensation structures.

---

## 🔧 Data Cleaning Summary

- Replaced missing gender values with `"Undisclosed"`  
- Removed rows with missing salary values  
- Deleted rows where department was `"NULL"`  
- Renamed `"Location"` column to `"Region"`  
- Added calculated columns:
  - **Bonus %**
  - **Bonus Amount**
  - **Total Pay**
  - **Salary Band**

---

## 📊 Analysis by Case Questions

### 1. Gender Distribution (Overall, Region, and Department)

**Table: Gender Distribution – Company-wide**
- Female: 441  
- Male: 465  
- Undisclosed: 40  

**Table: Gender Distribution by Region**
- Balanced gender split in **Abuja**  
- **Kaduna** and **Lagos** slightly male-heavy  

**Table: Gender Distribution by Department**
- **Support, HR, and Services** are more balanced  
- **Legal** and **Engineering** show male dominance  

---

### 2. Performance Ratings by Gender

**Table: Performance Ratings by Gender**
- Rating distribution is relatively even  
- **Females** have higher counts in *Very Good* and *Good* ratings  

---

### 3. Gender Pay Gap Analysis

**Table: Average Salary by Gender**
- Female: `$72,136`  
- Male: `$74,790`  
- Undisclosed: `$78,368`  

**Table: Average Salary by Gender by Region**
- Gender pay gap in all regions (*Male > Female*)  
- **Abuja and Kaduna** show ~$2,500–$3,000 gaps  

**Table: Average Salary by Gender by Department**
- Gaps exist in most departments  
- Notable disparities in **Legal**, **Engineering**, and **Services**  

---

### 4. Compliance with $90,000 Minimum Salary Regulation

**Table: Salary Band Distribution**
- **654 of 946 employees** earn below $90k (~69%)  
- Only **31%** are compliant  

**Table: Salary Band by Region**
- **Lagos** has the highest number below $90k  
- **Abuja** slightly better, followed by **Kaduna**  

---

### 5. Bonus and Total Pay Calculation

**Bonus Rules Applied** (Based on Performance Rating):
- *Very Poor*: 0%  
- *Poor*: 5%  
- *Average*: 10%  
- *Good*: 15%  
- *Very Good*: 20%  

**Table: Bonus Amount by Region**
- **Kaduna**: `$825,912`  
- **Abuja**: `$801,144`  
- **Lagos**: `$567,054`  

**Table: Total Pay by Region**
- **Kaduna**: `$27.48M`  
- **Abuja**: `$24.92M`  
- **Lagos**: `$19.52M`  

**Table: Company-Wide Totals**
- **Total Bonus Paid**: `$2.19M`  
- **Total Salary + Bonus**: `$71.92M`  

---

## ✅ Final Recommendations – Palmora Group HR Analysis

1. **Address Gender Pay Gaps**
   - Prioritize salary audits in **Legal**, **Engineering**, and the **Lagos region**, where pay disparities are most pronounced.
   - Implement transparent salary bands and ensure **equal pay for equal roles** across genders.

2. **Enforce $90,000 Minimum Salary Policy**
   - With **~69% of employees earning below $90k**, focus remediation efforts on **Lagos** and **Support-related roles**.
   - Review compensation structures and **phase in salary adjustments** to meet regulatory standards.

3. **Maintain Fair Bonus Allocation**
   - Standardize bonus calculations based on performance ratings and ensure **uniform application** across all regions and departments.
   - Publish clear **internal bonus policies** to enhance trust and reduce bias.

4. **Improve Gender Representation**
   - Increase female hiring and retention in **technical and male-dominated departments** (e.g., Engineering).
   - Introduce **anonymous employee feedback systems** to monitor workplace fairness and equity.


---

## 👤 Analyst Profile

**Obiekezie Precious Chinaza**  
_First-Class Biochemistry Graduate_  
📧 Email: precious.obiekezie100@gmail.com
📍 Region: Nigeria  

> This analysis was developed entirely on **mobile (WPS Office)**, showcasing analytical excellence under technical constraints.

---# DSA_PROJECT_PALMORA-HR-ANALYSIS-
