# Identify-consumer-profiles-at-E-Commerce
**Primary Task:**

Segment users based on their consumer profiles.

# Project Background

1. Who's the customer? Product manager responsible for user experience
2. Who needs the information? Who is the intended user of the final result? The customers who asked for the analysis
3. What do they want to do? Make personalized offers for users
4. Are we interested in a particular time period, or are we investigating the entire period covered by the source data? The entire period
5. Is the presentation intended for the customer? If not, who will study it? For the customer
6. What made this research necessary? Why this kind of research in particular? Qualitative research isn't enough to make decisions; we need arguments based on data.
7. Has research of this kind been carried out before? No, this is new. Be as explicit as possible when describing how your solution works.

# Analysis Procedures

1. Prepare dataset
2. Data checking and cleansing
3. Exploratory Data Analysis :
    - Revenue trends
    - Average purchase value and its trends
    - Month-to-month trends in average revenue per user
4. Segment users based on their purchase history :
    - What segments tend to make seasonal purchases? Do these users tend to make repeat purchases?
    - What user segments tend to make several orders over a long period of time?
    - What user segments make many purchases over a short period of time?
    - What user segments make big orders? What can you say about their consumption patterns?
5. Formulate and test statistical hypotheses :
    - Formulate and test a hypothesis on differences in average order frequency and size for different user segments. 
        - H0 : average order frequency and size for different user segments are the same
        - H1 : average order frequency and size for different user segments are not the same
    - Formulate a statistical hypothesis regarding the data from the dataset and test it. 
        - H0 : income for different user segments are the same
        - H1 : income for different user segments are not the same
    - the level of significance used is 5% or 0.05
6. Create Presentation and Dashboards:
    - Presentation will include how to decide which segment, what's the difference, and the significance of this study to the stakeholders.
    - What should we do with the information? what's the next step after this? 
7. Conclusion

# Data Description

The dataset contains the transaction history of Everything Plus, an online store that sells household goods.

The file `ecommerce_dataset_us.csv` contains the following columns:
- `InvoiceNo` — order identifier
- `StockCode` — item identifier
- `Description` — item name
- `Quantity`
- `InvoiceDate` — order date
- `UnitPrice` — price per item
- `CustomerID`
