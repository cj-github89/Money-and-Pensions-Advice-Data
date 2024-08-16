**Money and Pensions Advice Dashboard**

**Original Data:**

https://maps.org.uk/en/publications/moneyhelper-pension-take-up-dashboard

**The Task:**

The practice task was to access the data on the Money and Pensions Advice Service (MaPS) public website and to prepare a 15-minute presentation on what I thought was noteworthy.

**Method:**

The original dashboard contains data regarding appointment volumes across the various services provided by MaPS in addition to self service tool usage figures and customer satisfaction scores.

The original data was held within a Power BI dashboard embedded within the website. Therefore, to get the data scraped and ready for use quickly, I utilised image to text converters to access the data. This meant taking screenshots, compiling PDFs of each table and then using an online converter to create csv files. I combined these into one Excel document with named tables then took these into Power BI.

I used Power Query to clean the data as best I could and then transform the data to the format needed to visualise. For the sake of this task, I did not spend time creating a data model as my objective was to do some rough exploratory analysis within limited time for a short presentation.

I was able to quickly build out 5 pages in Power BI and gather some observations to present. I then quickly assessed the remaining data in Excel to ascertain some points for further development.

**Observations:**

The data has low granularity as it is generally aggregated by quarter. There is seasonality evident within the data when looking at volumes. We can also see clear pre vs post covid behaviour patterns with a significant shift in appointment channel towards Telephony post pandemic.

I also noted the following:

•	Increased arranged appointment volumes but with a greater proportion being lost meaning that in some cases less appointments were attended than the same period the previous year<br>
•	Consistently high customer feedback for Telephony although there are no volumes to contextualise these scores<br>
•	Potential for big impact if efficiencies are found in helpline process as last year this accounted for 78% of customers helped totalling over 200,000 people<br>
•	Online tool completion rates down vs previous year<br>
•	Unusual change in Q3>Q4 feedback scores (Pension Guidance)

**Further Development:**

Ideas to improve this project include completing a more robust data scrape using a Python script together with Beautiful Soup to parse the html. Then using this to create a well-structured data model complete with date table, allowing for time series analysis.
In a real business scenario, it would be interesting to try and determine the root cause for some of these fluctuations by accessing some additional data with a higher level of detail. For example, trying to understand what factors give an appointment a high chance of being lost (cancelled/not attended).
