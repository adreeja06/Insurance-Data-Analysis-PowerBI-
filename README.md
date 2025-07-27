PRISM Insurance Pvt. Ltd. - Insurance Analysis Dashboard
Project Overview
An end-to-end Power BI project analyzing insurance claims data to provide actionable insights on performance, profitability, and customer feedback. This dashboard serves as a business intelligence tool for stakeholders to monitor key performance indicators and make data-driven decisions.

📊 Dashboard Preview
Key Insights from the Dashboard
High Claim Rejection Rate: The dashboard reveals a significant number of rejected claims (4.4K) compared to settled ones (2.6K), indicating a potential need to review policy terms or the claims validation process.

Customer Retention Risk: Over half of all policies (51.88%) are inactive, highlighting a critical area for customer re-engagement and retention strategies.

High-Risk Demographics: Claim amounts are strongly correlated with age, with the "Older Adult" group accounting for the highest total claim amount (6M).

Policy Performance: Travel insurance is the highest-grossing policy type by premium (1.5M) but also carries the highest risk in terms of total claim amounts.

Key Skills & Features Implemented
1. Data Transformation (Power Query):

Cleaned and profiled raw data, handled errors, and corrected data types for accuracy.

Created conditional columns for new analytical categories like 'Age Groups' to enable deeper segmentation.

2. Data Modeling:

Built a robust Star Schema with a central Fact table (claims) and multiple Dimension tables (Calendar, Policy, Customer).

Established correct relationships and cardinality for an optimized and scalable data model, ensuring fast performance.

3. Advanced DAX Calculations:

Developed complex measures for KPIs like Claim Rate, Rejection Rate, and Profitability.

Implemented Time Intelligence functions (TOTALYTD, SAMEPERIODLASTYEAR) for powerful trend analysis over time.

4. Sentiment Analysis (AI Insights):

Analyzed the unstructured 'Feedback' column using Text Analytics in Power Query (a Premium feature).

Converted sentiment scores into "Positive," "Negative," and "Neutral" categories to quantify customer satisfaction and identify areas for improvement.

5. Row-Level Security (RLS):

Implemented RLS to restrict data access based on user roles (e.g., a Regional Manager can only see data for their region).

Used DAX rules with USERPRINCIPALNAME() to dynamically filter data for each user after the report is deployed to the Power BI service.

6. Interactive Visualization & Reporting:

Designed a user-friendly and aesthetically pleasing report with interactive visuals, slicers, and cross-filtering.

Enhanced user experience with Bookmarks and custom button navigation to create an intuitive, app-like feel for end-users.
