# Mortgage_Analysis_OF_Real_Estate_Owner

**DESCRIPTION**

A banking institution requires actionable insights from the perspective of Mortgage-Backed Securities, Geographic Business Investment and Real Estate Analysis. 

The objective is to identify white spaces/potential business in the mortgage loan. The mortgage bank would like to identify potential monthly mortgage expenses for each of region based on factors which are primarily monthly family income in a region and rented value of the real estate. Some of the regions are growing rapidly and Competitor banks are selling mortgage loans to subprime customers at a lower interest rate. The bank is strategizing for better market penetration and targeting new customers. A statistical model needs to be created to predict the potential demand in dollars amount of loan for each of the region in the USA. Also, there is a need to create a dashboard which would refresh periodically post data retrieval from the agencies. This would help to monitor the key metrics and trends.

The dashboard must demonstrate relationships and trends for the key metrics as follows:  number of loans, average rental income, monthly mortgage and owner’s cost, family income vs mortgage cost comparison across different regions. The metrics are described not to limit the dashboard to these few only. 

**Dataset Description :**


**Variables**                                                   **Description**

**i) Second mortgage -**                                       Households with a second mortgage statistics

**ii) Home equity   -**                                       Households with a home equity loan statistics

**iii) Debt  -**                                               Households with any type of debt statistics

**iv) Mortgage Costs  -**                                     Statistics regarding mortgage payments, home equity loans, utilities, and property taxes

**v) Home Owner Costs -**                                    Sum of utilities, and property taxes statistics

**vi) Gross Rent  -**                                         Contract rent plus the estimated average monthly cost of utility features

**vii) High school Graduation -**                               High school graduation statistics

**viii) Population Demographics -**                             Population demographics statistics

**ix) Age Demographics -**                                    Age demographic statistics

**x) Household Income -**                                   Total income of people residing in the household

**xi) Family Income -**                                      Total income of people related to the householder



**Data Import and Preparation:**

1. Import data. 

2. Figure out the primary key and look for the requirement of indexing.
   
3. Gauge the fill rate of the variables and devise plans for missing value treatment. Please explain explicitly the reason for the treatment chosen for each variable.



**Exploratory Data Analysis (EDA):**


**Perform debt analysis. You may take the following steps:**

a) Explore the top 2,500 locations where the percentage of households with a second mortgage is the highest and percent ownership is above 10 percent. Visualize using geo-map. You may keep the upper limit for the percent of households with a second mortgage to 50 percent

b) Use the following bad debt equation:

c) Bad Debt = P (Second Mortgage ∩ Home Equity Loan)

d) Bad Debt = second_mortgage + home_equity - home_equity_second_mortgage

e) Create pie charts  to show overall debt and bad debt

f) Create a collated income distribution chart for family income, house hold income, and remaining income


**Perform EDA and come out with insights into population density and age. You may have to derive new fields (make sure to weight averages for accurate measurements):**

a) Use pop and ALand variables to create a new field called population density

b) Use male_age_median, female_age_median, male_pop, and female_pop to create a new field called median age

c) Visualize the findings using appropriate chart type


**Create bins for population into a new variable by selecting appropriate class interval so that the number of categories don’t exceed 5 for the ease of analysis:**

a) Analyze the married, separated, and divorced population for these population brackets

b) Visualize using appropriate chart type


**Please detail your observations for rent as a percentage of income at an overall level, and for different states.**

**Perform correlation analysis for all the relevant variables by creating a heatmap. Describe your findings.**



**Project Task: Week 2**

**Data Pre-processing:**

1. The economic multivariate data has a significant number of measured variables. The goal is to find where the measured variables depend on a number of smaller unobserved common factors or latent variables.

2. Each variable is assumed to be dependent upon a linear combination of the common factors, and the coefficients are known as loadings. Each measured variable also includes a component due to independent random variability, known as “specific variance” because it is specific to one variable. Obtain the common factors and then plot the loadings. Use factor analysis to find latent variables in our dataset and gain insight into the linear relationships in the data.

**Following are the list of latent variables:**

a) Highschool graduation rates

b) Median population age

c) Second mortgage statistics

d)Percent own

e)Bad debt expense


**Data Modeling :**

a) Build a linear Regression model to predict the total monthly expenditure for home mortgages loan.

 Please refer **deplotment_RE.xlsx**. Column **hc_mortgage_mean** is predicted variable. This is the mean monthly mortgage and owner costs of specified geographical location.

 **Note:** Exclude loans from prediction model which have NaN (Not a Number) values for **hc_mortgage_mean**

  a) Run a model at a Nation level. If the accuracy levels and R square are not satisfactory proceed to below step.
  
  b) Run another model at State level. There are 52 states in USA.
  
  c) Keep below considerations while building a linear regression model:

i) Variables should have significant impact on predicting Monthly mortgage and owner costs

ii) Utilize all predictor variable to start with initial hypothesis

iii) R square of 60 percent and above should be achieved

iv) Ensure Multi-collinearity does not exist in dependent variables

v) Test if predicted variable is normally distributed


**Data Reporting:**

a) Create a dashboard in tableau by choosing appropriate chart types and metrics useful for the business. The dashboard must entail the following:

i) Box plot of distribution of average rent by type of place (village, urban, town, etc.).

ii) Pie charts to show overall debt and bad debt.

iii) Explore the top 2,500 locations where the percentage of households with a second mortgage is the highest and percent ownership is above 10 percent. Visualize using geo-map.

iv) Pie chart to show the population distribution across different types of places (village, urban, town etc.).



