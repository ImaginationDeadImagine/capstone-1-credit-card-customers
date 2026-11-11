# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

## README.md

- **Dataset content:**	The dataset, 'Credit Card customers', was sourced from Kaggle.com.  It contained 10,127 rows, and 23 columns.  These were reduced to 21 columns during inital processing of the dataset.  Each row contained 23 items of data organised by columns in an identical manner.
  
- **Business requirements:**	The bank manager who initiated this analysis is concerned about credit card churn; more specifically about who churns and how to keep them as customers.

- **Hypotheses and how to validate:**
  - H1. Customers who have a transaction count lower than the median are more likely to churn than customers who have a transaction count at the median or above.  Tested with a **histogram**.

  - H2. Customers with more inactive months than the median are more likely to churn than customers who have inactive months at the median or below.  Tested with a **line chart**.

  - H3. Customers who contacted the bank more times than the median are more likely to churn than customers who contacted the bank the median number of times or below.  Tested with a **bar chart**.

  - H4. Customers who used their credit limit lower than the median are more likely to churn than customers who used their credit limit at the median or above.  Tested with a **violin plot**.

- **Project plan:**	 The raw data file was downloaded from Kaggle and undergoes an Extract, Transform, Load (ETL) process.  The resulting clean data file is used for a series of analytical steps, principally involving the creation of a number of visualisations.  The visualisations are used to draw analytical conclusions, principally about credit card churn.

- **Rationale for visualisations:**
| Chart | Business question / hypothesis | Why this chart type |
|---|---|---|
| Pie chart | What share of customers churn? | Shows parts of a whole; reveals that roughly 1 in 6 customers churn |
| Histogram | H1: Is low transaction count associated with churn? | Shows distributions.  Low transaction count is associated with churn.  Customers who churn and those who stay are distinct groups, although there is overlap between them. |
| Line chart | H2: Is account inactivity associated with churn? | Shows trends; there is a rising trend in churn for 1 to 4 months of account inactivity. |
| Bar chart | H3: Is more customer contact associated with churn? | Compares the churn rate for each number of contacts.  More contact is associated with increasing churn. |
| Violin plot | H4: Is low credit usage associated with churn? | Demonstrates the shape of distributions, showing where values cluster, and includes a mini-boxplot. |
| Heatmap | What are the stronegst correlations with churn? | Low total transaction count, declining transaction count, and low credit card usage all correlate with increased churn. Particularly supports H1 and H4.|

