# Bank Loan Data Analysis

## Problem Statement
To gain a comprehensive understanding of lending operations and monitor loan performance, this project aims to create a grid view report categorized by Loan Status. The analysis provides insights into key financial metrics, enabling data-driven decision-making and assessment of the loan portfolio's health.

## Key Performance Indicators (KPIs)
### General Loan Metrics:
1. **Total Loan Applications**
   - Calculate the total number of loan applications.
   - Monitor Month-to-Date (MTD) applications and track Month-over-Month (MoM) changes.
2. **Total Funded Amount**
   - Track the total funds disbursed as loans.
   - Monitor MTD funded amounts and analyze MoM trends.
3. **Total Amount Received**
   - Assess total repayments received from borrowers.
   - Analyze MTD received amounts and MoM fluctuations.
4. **Average Interest Rate**
   - Calculate the average interest rate across loans.
   - Monitor MTD interest rate trends and MoM variations.
5. **Average Debt-to-Income Ratio (DTI)**
   - Evaluate borrowers' financial health through average DTI.
   - Track MTD DTI values and MoM changes.

### Good Loans:
- Good Loan Application Percentage
- Good Loan Applications
- Good Loan Funded Amount
- Good Loan Total Received Amount

### Bad Loans:
- Bad Loan Application Percentage
- Bad Loan Applications
- Bad Loan Funded Amount
- Bad Loan Total Received Amount

## Data Analysis & Visualization
To provide a deeper understanding of loan data, the project includes various charts and visualizations:
1. **Monthly Trends by Issue Date (Line Chart)**
   - Identifies seasonality and long-term trends in lending activities.
2. **Regional Analysis by State (Geographical Map)**
   - Highlights significant lending activity across different states.
3. **Loan Term Analysis (Bar Chart)**
   - Displays the distribution of loans across various term lengths.
4. **Employment Length Analysis (Bar Chart)**
   - Shows lending metrics distribution among borrowers with different employment histories.
5. **Loan Purpose Breakdown (Pie Chart)**
   - Provides a visual representation of loans categorized by their stated purpose.
6. **Home Ownership Analysis (Hierarchical Chart)**
   - Illustrates the impact of home ownership on loan applications and disbursements.

## Dataset
The dataset `financial_loan.csv` contains:
- **Continuous Variables:** `annual_income`, `dti`, `installment`, `int_rate`, `loan_amount`, `total_payment`
- **Categorical Variables:** `address_state`, `application_type`, `grade`, `home_ownership`, `loan_status`, `purpose`, `sub_grade`, `term`, `verification_status`

## Requirements
To run the analysis, install the required dependencies:
```bash
pip install pandas numpy matplotlib seaborn
```

## Usage
1. **Load Dataset:**
   - Import and clean the data.
2. **Perform EDA & Visualization:**
   - Generate key statistical summaries and visualizations.
3. **Analyze KPIs:**
   - Compute relevant financial metrics and trends.
4. **Interpret Insights:**
   - Identify trends affecting loan approvals and repayment behavior.

## Future Work
- Enhance data exploration with interactive dashboards.
- Implement automated reporting for loan portfolio monitoring.
- Extend the analysis to include customer segmentation based on risk factors.



