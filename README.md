# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

## README.md

- **Dataset content:**	The dataset, 'Credit Card customers', was sourced from Kaggle.com.  It contained 10,127 rows, and 23 columns.  These were reduced to 21 columns during inital processing of the dataset.  Each row contained 23 items of data organised by columns in an identical manner.
  
- **Business requirements:**	The bank manager who initiated this analysis is concerned about credit card churn; more specifically about who churns and how to keep them as customers.

- **Hypotheses and how to validate:**
  - 1. Customers who have a transaction count lower than the median are more likely to churn than customers who have a transaction count at the median or above.  Tested with a **histogram**.

  - 2. Customers with more inactive months than the median are more likely to churn than customers who have inactive months at the median or below.  Tested with a **line chart**.

  - 3. Customers who contacted the bank more times than the median are more likely to churn than customers who contacted the bank the median number of times or below.  Tested with a **bar chart**.

  - 4. Customers who used their credit limit lower than the median are more likely to churn than customers who used their credit limit at the median or above.  Tested with a **violin plot**.

- **Project plan:**	 The raw data file was downloaded from Kaggle and undergoes an Extract, Transform, Load (ETL) process.  The resulting clean data file is used for a series of analytical steps, principally involving the creation of a number of visualisations.  The visualisations are used to draw analytical conclusions, principally about credit card churn.
