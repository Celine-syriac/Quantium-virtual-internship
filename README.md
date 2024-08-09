### Quantium Data Analytics Virtual Experience Program

This virtual experience program focuses on analyzing supermarket chip purchases to understand customer behavior and assess the success of a new store layout trial. The program consists of three tasks:

#### **Task 1: Data Preparation and Customer Analytics**
- **Objective:** Clean and analyze customer purchase behavior data.
- **Files:** `quantium_task1.ipynb` reads from `QVI_purchase_behaviour.csv` and `QVI_transaction_data.xlsx`.
- **Process:**
  - **Data Cleaning:** Converted dates from integer to datetime format, removed salsas and outliers.
  - **Analysis:** 
    - Examined customer segments based on `LIFESTAGE` and `MEMBER_TYPE`.
    - Focused on the purchasing habits of the Mainstream Young Singles/Couples segment, analyzing chip brand and packet size preferences.
- **Key Insights:**
  - Top three segments by total sales: Budget Older Families, Mainstream Young Singles/Couples, and Mainstream Retirees.
  - Older families purchase more packets on average, while the Mainstream Young Singles/Couples have the largest population.
  - Across most segments, Kettles chips and 175g packets are the most popular.
  - Mainstream Young Singles/Couples are more likely to purchase Tyrells chips and larger 270g packets, particularly Twisties.

#### **Task 2: Experimentation and Uplift Testing**
- **Objective:** Evaluate the impact of a new store layout on sales and customer numbers.
- **Files:** `quantium_Task2(1).ipynb` reads from `QVI_data.csv`.
- **Process:**
  - **Store Matching:** Paired trial stores with control stores based on combined metrics using Pearson correlations and magnitude distances.
  - **Hypothesis Testing:** Assessed whether differences in performance between control and trial stores were statistically significant.
- **Key Insights:**
  - Control and trial store pairs identified: 77 with 233, 86 with 155, 88 with 40.
  - Significant sales increases in stores 77 and 86, especially in March and April 2019.
  - Significant customer number increases in stores 77 and 86.
  - No significant performance change in store 88.

#### **Task 3: Analytics and Commercial Application**
- **Objective:** Summarize findings and provide commercial insights.
- **Output:** PowerPoint report using the Pyramid Principle to communicate key insights from Tasks 1 and 2.

### **Dependencies**
- **Language:** Python 3.8
- **Packages:** pandas, matplotlib, mlxtend, datetime, sklearn, scipy

### **Project Overview**
The goal was to analyze chip purchasing behavior, evaluate the impact of a new store layout, and provide actionable recommendations based on customer preferences and trial performance.
