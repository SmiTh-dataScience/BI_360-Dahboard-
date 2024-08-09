# Business Insights for a computer hardware selling company.

## Problem Statement
AtliQ Hardware is a computer hardware selling company, whose business is in India and many more countries. The manager wants to know about the sales, stock present and many more insights but he has to look over too much excel files to get these insights. He want a visual report which help him in taking decisions regarding his business and regularly update of that let him know what is the current situation, also he wants to know the supply chain view so that he can efficiently move forward with his business.

## Solution Approach
I have been provided with two big sql files and many excel files(in src folder) to help me in creating this report. After that I have asked the relevant questions what basically the manager sir wants, the final outcome i received is that he wants a visual report wich not only for him but also for the other members of organization, like if they are from sales department they can see the sales view, if they are from supply chain then they have a look over it and same for marketing team as well. Manager sir is more interested in seeing the finance view. So, basically we need to cover up all the sectors of the organization. 

All started with checking the data using SQL. In this check, I have observed many error related to blank data, negative value of prices etc. So, after loading the data in Power BI I have removed those errors using Power Query Editor. Once the data is cleaned I have started creating measures based on the requiremnets of the company and the manager. After creating the relevant measures, I moved on with creating different dashboards and combining all of them. The first I have created the Finance View, then Sales View, Marketing View, then Supply Chain View and Executive View. After that I have ended up by creating the tool tips for more clear visualisation and then Home page and Support page through which on clicking on dedicated icon you can reach to each particular dashboard of the report. Then on the instructions from the manager I have also deployed it on Power BI services.  

## Tech Stack
Visualisation: Power BI

Dependencies: MS Excel , SQL queries for checking the errors present in the raw data and cross checking the measures. 

Performance Metrics: MS Excel , MySQL , DAX and M language, Measures in Power BI.


### Key Insights by View

**Finance View:**
- Analyzed crucial KPI indicators such as Net Sales, Gross Margin %, and Net Profit %.
- Created a comprehensive Profit & Loss Statement with Year-over-Year (YOY) growth analysis.

**Sales View:**
- Explored Customer Performance based on Net Sales and Gross Margin.
- Identified top-performing customers to drive sales strategies.

**Marketing View:**
- Enhanced Marketing insights with segment performance analysis and Net Profit metrics.
- Provided actionable insights to optimize marketing efforts.

**Supply Chain View:**
- Surveyed the variance between Actual Sales and Forecast accuracy.
- Improved supply chain efficiency by identifying key discrepancies.

**Executive View:**
- Examined Yearly Trends by Revenue, Gross Margin %, Net Profit %, and Market Share %.
- Listed the TOP 5 Customers & Products by Revenue Contribution to highlight key growth drivers.

## Data Sources
The dashboard seamlessly collects and utilizes data from two primary sources:

- **Excel/CSV Files**: Targets, Market Share data, and related information are sourced from Excel/CSV files.
- **MySQL Database**: Facts and Dimensions data are retrieved from a MySQL database.

## View the Project
You can view the full Power BI report [PROJECT_LINK](https://app.powerbi.com/view?r=eyJrIjoiZmY1NDQ5NDQtZWQ0Zi00NzNmLWIyYTctZDQyOTM4Yzg3ZTJhIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)
## Tools & Techniques
- Power BI for interactive data visualization
- Data modeling and DAX for advanced calculations
- Data integration from multiple sources

Would love to hear your thoughts and feedback. Let's connect and discuss more!
