# Works

# Loan Default & Overview - Power BI Project

An interactive, 3-page Power BI dashboard designed to analyze lending distributions, credit risk profiles, applicant demographics, and complex financial metrics across historical data (2013-2018).

## 📊 Dashboard Preview

### 1. Loan Default & Overview
![Loan Default Overview](<img width="100%" alt="Loan Default Overview" src="Screenshot 2026-06-23 142546.png" />)
*Key Focus:* High-level overview tracking loan volume by purpose, age distribution, and historical default rates. Unemployed applicants correlate with the highest default rates (3.39%), while historical defaults peaked in 2015-2016 at over 11.7%.

### 2. Applicant Demographics & Financial Profile
![Applicant Demographics](<img width="100%" alt="Applicant Demographics" src="Screenshot 2026-06-23 145408.png" />)

*Key Focus:* Breakdown of loan metrics across credit categories, marital statuses, educational backgrounds, and dependency statuses. Major volume drivers include applicants with medium/high credit scores and those holding a Bachelor's degree.

### 3. Financial Risk Metrics
![Financial Risk Metrics](img width="100%" alt="Financial Risk Metrics" src="Screenshot 2026-06-23 145417.png" />)
*Key Focus:* Advanced evaluation using dynamic tracking mechanisms. Displays Year-over-Year (YOY) loan fluctuations and paths total loan volumes ($32.58bn) across structural income brackets and employment types using Decomposition Trees.

---

## 🛠️ Features & Technical Stack
- **Data Visualization & Design:** Clean, analytical presentation with cohesive grid layouts using Power BI.
- **Data Engineering:** Cleaned, structured, and transformed multi-variable financial data using **Power Query**.
- **Advanced Calculations:** Developed custom **DAX metrics** to calculate multi-period Year-over-Year (YOY) and Year-to-Date (YTD) financial fluctuations.
- **Advanced Visual Interaction:** Utilized Sankey flows, donut-multi-group charts, and interactive decomposition paths to track $32.58bn in capital allocation.

## 📈 Key Insights Formulated
1. **Employment vs Risk:** A direct downward trajectory exists between stability of employment and default rates. Unemployed defaults rest at 3.39% while full-time employees drop to 2.36%.
2. **Portfolio Volume:** The bulk of loan applications are concentrated heavily within 'Medium' and 'High' credit score bands, representing over $9bn in combined total allocations.
3. **Historical Fluctuations:** Extreme volatility in Year-over-Year default changes occurred around 2014-2015, helping risk teams note critical operational inflection points.

## 🚀 How to View
1. Open the interactive dashboard directly on the [Power BI Service](https://app.powerbi.com/groups/d9b0f4f7-e141-4146-9789-c7e08c801dbb/reports/c6f9f70d-b3cc-436f-8a4b-53582ac3e14a/5a87436760915c2b5cd0?experience=power-bi).
2. Alternatively, clone this repository and open the local `.pbix` file using **Power BI Desktop**.
