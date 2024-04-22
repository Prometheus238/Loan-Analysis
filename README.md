**Project Description:**

I created a Power BI data model that utilizes DAX calculations to construct a loan model based on mortgage rates. Mortgages are typically paid off over various periods of time, with the 30-year loan being one of the most common, involving fixed interest rate payments each month for 30 years.

For my calculations, I sourced interest rates from the Federal Reserve Economic Data (FRED), including both 15-year and 30-year fixed mortgage rates. These rates serve as crucial inputs for my loan model, with the 15-year rate starting approximately two decades later than the 30-year rate and typically being lower due to the shorter loan duration.

Using Power BI, I established connections to these FRED data sources for both 15-year and 30-year fixed mortgage interest rates via the Power Query Editor. Throughout the project, I utilized the DAX language to build the Power BI model for these loan calculations. Additionally, I explored the dynamic visualization capabilities of Power BI to effectively communicate how the loan model operates to a broader business audience.

At a high level, a loan involves borrowing a specific amount of money at time zero and repaying it through regular payments over a predetermined period, such as five years in my case. These payments encompass both principal and interest, with interest rates derived from the 15-year and 30-year average rates.

Key calculations in the loan model include converting annual interest rates into monthly rates, determining the level payment amount, tracking the loan balance at each period, and calculating the interest and principal paid for each period. To ensure clarity and organization, I numbered the DAX formulas for individual tables within Model 1 and Model 2 and used a sequence to denote the order of measures calculated within each model as I progressed in building the loan models in Power BI.

**Dashboard:**

![image](https://github.com/Prometheus238/Loan-Analysis/assets/69340526/4528d557-7183-48d1-a472-4176ea0c849e)

**More Supporting Visualizations:**

![image](https://github.com/Prometheus238/Loan-Analysis/assets/69340526/6bd52849-9645-4d19-b48c-61ff5078a9ea)

![image](https://github.com/Prometheus238/Loan-Analysis/assets/69340526/6e8c9fcd-7df8-4ab4-b74f-37bf521adeb6)

![image](https://github.com/Prometheus238/Loan-Analysis/assets/69340526/7b9650ee-95f7-43a9-b239-fb2f5b8f550d)


