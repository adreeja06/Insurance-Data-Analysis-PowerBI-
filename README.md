# PRISM Insurance Pvt. Ltd. - Claims Analysis Dashboard

### Project Overview
An end-to-end Power BI project analyzing insurance claims data to provide actionable insights on performance, profitability, and customer feedback.

**Live Dashboard:** `[Link to your published Power BI Report]`

---

### Key Skills & Features Implemented

**1. Data Transformation (Power Query):**
* Cleaned and profiled raw data, handled errors, and corrected data types.
* Created conditional columns for new analytical categories like 'Age Groups'.

**2. Data Modeling:**
* Built a robust **Star Schema** with a central Fact table and multiple Dimension tables (Calendar, Location, etc.).
* Established correct relationships and cardinality for an optimized and scalable model.

**3. Advanced DAX Calculations:**
* Developed complex measures for KPIs like Claim Rate, Rejection Rate, and Profitability.
* Implemented **Time Intelligence** functions (`TOTALYTD`, `SAMEPERIODLASTYEAR`) for trend analysis.

**4. Sentiment Analysis (AI Insights):**
* Analyzed the unstructured 'Feedback' column using **Text Analytics** in Power Query (a Premium feature).
* Converted sentiment scores into "Positive," "Negative," and "Neutral" categories to quantify customer satisfaction.

**5. Row-Level Security (RLS):**
* Implemented RLS to restrict data access based on user roles (e.g., Regional Manager).
* Used DAX rules with `USERPRINCIPALNAME()` to dynamically filter data for each user after deployment.

**6. Interactive Visualization & Reporting:**
* Designed a user-friendly report with interactive visuals, slicers, and cross-filtering.
* Enhanced user experience with **Bookmarks** and custom button navigation to create an app-like feel.

---

### Author
* **Name:** `[Your Name]`
* **LinkedIn:** `[Your LinkedIn Profile URL]`
