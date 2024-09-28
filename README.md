# Dashboard-with-PowerBI
Issue No. 1: Data Reconciliation

Issue No. 2: Working at Scale

Issue No. 3: Cleaning up Your Data

Issue No. 4: Getting the Scope of the Data Under Control (A.K.A “The Classic”)

# What Does Business Intelligence Mean?

Business Intelligence (often shortened to BI) is a field of expertise that uses data to improve decision-making within organizations. Different tools, such as Power BI, are used to do this.

In practice, it can be used to do things like:

Analyze client behavior to build new offerings. 

Identify key factors that impact production times for a piece in the workshop to gain better understanding and control. 

Calculate the flight risk for top employees with a given salary band or seniority level. 

Measure the impact of projects on the company’s economic performance. 

# The Scope of Your Project With Jane

In summary, Jane has two goals:

To reduce the time it takes to decide whether to approve mortgage applications. 

To improve the quality of approved application files. 

She describes several people who play a role in the decision-making chain for mortgages:

In-branch advisors who do not currently have the necessary decision-making tools, and must rely on their experience.

Branch managers who can confirm or overrule a decision made by the advisors.

The central unit for examining mortgage applications. This unit has the final say but is overwhelmed with requests. 

Jane mentions that the root cause of the delay in decision-making is the amount of information about the borrower that needs to be examined in order to approve or refuse a mortgage:

1) Professional situation (socio-professional category, employment status, regularity of income, and amount).

2) Family circumstances (age, number of dependent children).

3) Down payment amount.

4) Debt currently held.

5) Savings capacity (cost of living).

# Apply Best Practices to Set Your Project Scope
Best Practice No. 1: Meet the End Users
Best Practice No. 2: Meet With Stakeholders
Best Practice No. 3: Create User Stories
Best Practice No. 4: Use examples to Help the Group Visualize
Best Practice No. 5: Prototype the Solution With a Wireframe
Best Practice No. 6: Organize Regular Progress Reports

# Pie Chart, Stacked Column Chart

The distribution of mortgage applications by year.
AND 

The distribution of the loan amount between those approved or rejected.

# What, Why, How
What: What data does your user want to visualize? 

Different types of visualizations work better for different types of data.

Why: Why does your user want to visualize this data? 

This question has a real impact on the visualization you’ll choose and the interaction that you should set up. Does your user want to identify a trend? Correlation between variables? Are they looking for a particular value?

How: Finally, ask yourself how you should present the data to your user. 

Do they want to see sorted or filtered data?

Do they want to see all data points, or do they want the information combined into groups of values? 

# Pros and Cons of Each Visualization 
Pie Charts
✅ Easy to use for representing a whole as the sum of its elements.

⚠️️ Hard for the eye to compare the size of the different slices of the pie. 

⚠️️ If divided into more than four parts, they become impossible to read. 

Line Charts
✅ Practical for showing how a numerical variable has changed. 

⚠️️ When too many lines are involved, you risk the “spaghetti effect”.

Column Charts
✅ The most effective graph for representing numerical values by category. 

⚠️ Data is often grouped together, which may impact the way your end user interprets it. 

⚠️️ If the data is not sorted, these can be hard to read. 

Treemaps
✅ The best use of space for presenting lots of information at the same time. 

⚠️️ If there is no variance in the data, these are not much use. 

Maps
✅ These let end users picture their environment. 

⚠️️ Illegible if there are too many bubbles. 

⚠️️ Maps are often colored in (to show sea, continents, etc.), so take care with managing your colors. 

# Transform Data Using Power Query Editor
Identify Anomalies
Correct Anomalies Before Importing
Save With M

# Connect Tables for Cross-Tab Analysis
Connect Your Data Tables
Understand the Star Schema

Fact tables store observations or events, which could be sales orders, stock balances, exchange rates, temperatures, etc.

Dimension tables describe business entities – the things you model. Entities can include products, people, places, and concepts including time itself. 

# Combine Queries Instead of Connecting Data Tables
Scenario 1: You Have Several Event Tables
Scenario 2: You’re Lacking Dimensions on Your Event Table 
Create Different Roles to Manage Data Confidentiality 

# Create New Information From Existing Data
Use DAX Formulas
Create a Measure

# The Pros and Cons of Data-Creation Methods
Using Measures
✅ For visualizing a value based on interactions with your dashboard. 

✅ Quick measures are simple to use.

✅ No need to store new data. 

⚠️ ️ The calculation happens in real time and can be slow (if complex and drawing on lots of data). 

Using Calculated Columns
✅ For visualizing different values independent of the active selection. 

✅ For reusing values as fields in a visualization. 

⚠️ ️ Can require large volumes of data storage: if you have a 100,000-line table, a single column can take up lots of room. 
