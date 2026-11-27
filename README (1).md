# Insurance Data Analysis Dashboard | Power BI

## Project Overview
This project is an interactive **Insurance Data Analysis Dashboard** created using Microsoft Power BI. It explores insurance policy, customer, premium, coverage, and claims information to provide a consolidated view of the insurance portfolio.

## Dashboard Highlights
The report includes visual analysis of:

- **Premium Amount** – total premium amount and premium distribution.
- **Coverage Amount** – total insurance coverage.
- **Claim Amount** – claim amount analysis.
- **Customer Gender** – customer distribution by gender.
- **Age Group** – claim amount analysis across customer age groups.
- **Policy Type** – comparison of premium amounts across policy categories.
- **Claim Status** – distribution of claims by status (Settled, Pending, and Rejected).
- **Policy Type and Claim Status** – views that help compare coverage and claim information across categories.

The report also includes slicers for **Policy Type**, **Claim Status**, and **Age Group**, allowing users to interact with and filter the dashboard.

## Dataset
The dashboard uses `InsuranceData.csv`, which contains insurance-related fields such as:

| Column | Description |
|---|---|
| `PolicyNumber` | Unique policy identifier |
| `CustomerID` | Customer identifier |
| `Gender` | Customer gender |
| `Age` | Customer age |
| `PolicyType` | Insurance category (Auto, Travel, Health, Home, or Life) |
| `PolicyStartDate` | Policy start date |
| `PolicyEndDate` | Policy end date |
| `PremiumAmount` | Premium amount |
| `CoverageAmount` | Coverage amount |
| `ClaimNumber` | Claim identifier |
| `ClaimDate` | Claim date |
| `ClaimAmount` | Claim amount |
| `ClaimStatus` | Claim status |

The CSV contains approximately 10,000 rows. The source data includes `NULL` values in `ClaimDate` for some records.

## Tools Used
- **Microsoft Power BI Desktop** – data modelling, report building, and visualization
- **CSV** – source dataset

## Repository Contents
```text
Insurance-Data-Analysis/
├── Insurance_data_analysis.pbix
├── InsuranceData.csv
└── README.md
```

## How to Use
1. Clone or download this repository.
2. Open `Insurance_data_analysis.pbix` using **Power BI Desktop**.
3. If Power BI asks for the source file, select `InsuranceData.csv` from the downloaded repository folder.
4. Refresh the data if required.
5. Use the slicers to explore the dashboard by policy type, claim status, and age group.

## Project Objective
The objective of this project is to practice data analysis and dashboard development in Power BI, and to present insurance-related information in an interactive and easy-to-understand format.

## Author
**Omkar Jaulkar**

---

If you find this project useful, feel free to ⭐ the repository.
