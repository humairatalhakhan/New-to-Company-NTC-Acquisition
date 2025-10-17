# New-to-Company-NTC-Acquisition
The objective of this project is to track **Onboarded corporates** and monitor key KPIs

  <img width="911" height="561" alt="New-to-Company-NTC-Acquisition Dashboard" src="https://github.com/user-attachments/assets/79c20014-ade1-483c-b5db-b968050e1c1c" />


## 📊 Project Overview
The objective of this project is to track **Onboarded corporates** and monitor key KPIs related to **new-to-company acquisitions**, **card issuance**, and **salary transfers**.  
This project simulates real business data to demonstrate the **data analytics life cycle**: business understanding → data preparation → analysis → visualization → insights.

---

## 📌 Table of Contents
1. Business Understanding  
2. Data Understanding  
3. Approach (Data Analysis Life Cycle)  
4. Technologies  
5. Setup  
6. Screenshots & Results  
7. Status  

---

## 1️⃣ Business Understanding
- The Manager requested a dashboard to monitor **Corporates onboarded in the last three months**.  
- KPIs to be tracked:
  - **New-to-Company Acquisition per RM** (budget = 32 per RM)  
  - **Card Issuance per RM** (budget = 750 cards)  
  - **Salary Transfer %** of employees (target = 80%)  
- Goal: Provide clear, visual insights into performance against set budgets/targets.  

---

## 2️⃣ Data Understanding
- **Data Source:** Simulated dataset (to protect confidentiality of real bank data).  
- **Data Features:**
  - Corporate ID / Name (anonymized)  
  - Onboarding Date  
  - RM (Relationship Manager)
  - No. of Cards Issued  
  - Salary Transfer %  
- **Data Volume:** Last 3 months onboarding records.  

---

## 3️⃣ Approach (Data Analysis Life Cycle)
- **Data Collection:** Used sample Excel data representing corporates onboarded.  
- **Data Preparation:**  
  - Cleaned and validated onboarding dates.  
  - Applied lookup formulas (VLOOKUP/XLOOKUP) to align KPIs.  
  - Standardized corporate and RM-level records.  
- **Data Analysis:**  
  - Calculated KPIs (NTC acquisition per RM, card issuance per RM, salary transfer %).  
  - Compared actual performance vs budgeted targets.  
- **Data Visualization:**  
  - Built an interactive Excel dashboard.  
  - First chart: A donut chart displaying Total Acquisition vs Budget, with the percentage achieved prominently shown in the center for quick insights.

      <img width="307" height="263" alt="First chart" src="https://github.com/user-attachments/assets/c2d0443c-aed9-42df-8db5-4d418147d564" />
    
  - Secong chart: A combination chart showing regional achievements for AUH, SHJ, and DXB.
  - Clustered bars represent budget vs actual acquisition for each region.
  - A line overlay indicates the percentage of budget achieved, providing a clear comparison of performance across regions.

      <img width="595" height="261" alt="Second Chart" src="https://github.com/user-attachments/assets/ce783d08-3aca-4a06-b975-cb7bfbb2ccca" />

- **Insights:**  
  - Highlighted performance gaps against targets at both overall and regional levels.
  - Added RM-level tracking with bar charts showing target vs achieved for each region, enabling better accountability and performance monitoring by Relationship Manager.
    
      <img width="909" height="239" alt="Insights" src="https://github.com/user-attachments/assets/338cefbe-db76-4b7a-a28e-3563fb8ff29f" />

---

## 4️⃣ Technologies
- **Excel** (Dashboard, Charts, KPIs)  
- **SQL** (SSR reports)  
- **Power BI / Tableau** (future enhancement for visualization)  

---

## 5️⃣ Setup
To run this project:  
1. Clone this repository.  
2. Download the Excel file with sample data.  
3. Open the dashboard sheet to view KPIs & charts.  

---

## 6️⃣ Screenshots & Results

     <img width="911" height="561" alt="New-to-Company-NTC-Acquisition Dashboard" src="https://github.com/user-attachments/assets/26a43408-eaec-44a5-a8b3-de0f6ed5a898" />




---

## 7️⃣ Status
- ✅ Initial Version Completed: Excel dashboard created using simulated data for corporates. Additional data and features will be added as the project progresses.
- 🔄 Future Work: Plan to expand the dashboard to Power BI for advanced, interactive visualizations.

---

## 📬 Connect with Me
- 💡 Contact me on [LinkedIn](www.linkedin.com/in/humairatalha)
  
## 📬 Sample Data

- Corporate / Segment	Budget	Actual	% Achieved
  
Tony	32	15	46.88%

Jeff	32	25	78.13%

Sara	32	21	65.63%

Donny	32	22	68.75%

**New-to-Company (NTC) Acquisition DXB** & SHJ	128	83	64.84%

Steve	32	30	93.75%

Tom	32	28	87.50%

**New-to-Company (NTC) Acquisition AUH**	64	58	90.63%
**New-to-Company (NTC) Acquisition Total**	192	141	73.44%

- Notes:

Individual corporates are listed with their Budget, Actual, and % Achieved.

Aggregated rows (NTC by region or total) are bolded for clarity.

% Achieved is calculated as (Actual / Budget) * 100.
