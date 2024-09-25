# Mortgage_Analysis_OF_Real_Estate_Owner

**DESCRIPTION**

A banking institution requires actionable insights from the perspective of Mortgage-Backed Securities, Geographic Business Investment and Real Estate Analysis. 

The objective is to identify white spaces/potential business in the mortgage loan. The mortgage bank would like to identify potential monthly mortgage expenses for each of region based on factors which are primarily monthly family income in a region and rented value of the real estate. Some of the regions are growing rapidly and Competitor banks are selling mortgage loans to subprime customers at a lower interest rate. The bank is strategizing for better market penetration and targeting new customers. A statistical model needs to be created to predict the potential demand in dollars amount of loan for each of the region in the USA. Also, there is a need to create a dashboard which would refresh periodically post data retrieval from the agencies. This would help to monitor the key metrics and trends.

The dashboard must demonstrate relationships and trends for the key metrics as follows:  number of loans, average rental income, monthly mortgage and owner’s cost, family income vs mortgage cost comparison across different regions. The metrics are described not to limit the dashboard to these few only. 

**Dataset Description :**


**Variables**                                                   **Description**

**Second mortgage -**                                       Households with a second mortgage statistics

**Home equity   -**                                       Households with a home equity loan statistics

**Debt  -**                                               Households with any type of debt statistics

**Mortgage Costs  -**                                     Statistics regarding mortgage payments, home equity loans, utilities, and property taxes

**Home Owner Costs -**                                    Sum of utilities, and property taxes statistics

**Gross Rent  -**                                         Contract rent plus the estimated average monthly cost of utility features

**High school Graduation -**                               High school graduation statistics

**Population Demographics -**                             Population demographics statistics

**Age Demographics -**                                    Age demographic statistics

**Household Income -**                                   Total income of people residing in the household

**Family Income -**                                      Total income of people related to the householder



**Data Import and Preparation:**

1. Import data. 

2. Figure out the primary key and look for the requirement of indexing.
   
3. Gauge the fill rate of the variables and devise plans for missing value treatment. Please explain explicitly the reason for the treatment chosen for each variable.



**Exploratory Data Analysis (EDA):**

**a. Perform debt analysis. You may take the following steps:**

i) Explore the top 2,500 locations where the percentage of households with a second mortgage is the highest and percent ownership is above 10 percent. Visualize using geo-map. You may keep the upper limit for the percent of households with a second mortgage to 50 percent

ii) Use the following bad debt equation:

iii) Bad Debt = P (Second Mortgage ∩ Home Equity Loan)

iv) Bad Debt = second_mortgage + home_equity - home_equity_second_mortgage

v) Create pie charts  to show overall debt and bad debt

vi) Create a collated income distribution chart for family income, house hold income, and remaining income

**b) Perform EDA and come out with insights into population density and age. You may have to derive new fields (make sure to weight averages for accurate measurements):**

