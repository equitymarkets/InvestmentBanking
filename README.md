## Group Project #1

### Project Title: Analysis of Top 10 Investment Banks

### Team Members of Group 3: Derek P, Katie B, Cheryl Z, Kevin N, Ray H 

#### Project Description/Outline: 

Our project aims to perform a data analysis of the top 10 investment banks using various datasets and visualize the findings using Matplotlib. This project will be divided into multiple tasks, with each member focusing on a specific aspect of the project research. 

#### Questions to Answer:

1.	Who are the largest investment banks by market share and how did they trend during a five-year window?
2.	What is the size of the banks currently, based on total revenue and total assets and how do they compare to IB fees?
3.	How big of a percentage of these banks' non-interest income are IB fees?
4.	What do measures of central tendency and standard deviation tell us about the results?



#### Dataset to be Used:

The team will use publicly available financial data for the top 10 investment banks, such as annual reports, financial statements, and other relevant sources. The team will also use APIs to gather additional data, such as stock prices, news articles, and analyst ratings. 

#### Rough Breakdown of Tasks:

•	*Data Collection and Cleaning:* will be responsible for collecting and cleaning the data using Pandas. We will create a Jupyter Notebook to document the data exploration and cleanup process.

•	*Data Analysis:* will use Pandas to perform the data analysis and create visualizations using Matplotlib. We will create a Jupyter Notebook to illustrate the final data analysis.

•	*Visualization:* will create 6 to 8 visualizations of the data, at least 2 visualizations per research question, using Matplotlib. We will save PNG images of the visualizations to share with the class and instructional team.

•	*Write-up:* will contribute to writing a summary of the major findings, including headings, for each research question, as well as a short description of the findings and relevant plots.

•	*Bonus Task:* will use at least one API to gather additional data pertinent to the research questions.

#### Findings:

Where and how we found the data we used to answer these questions

To answer our questions, we obtained our data mainly from the 10-K annual reports filed with the SEC in EDGAR. The exception to this rule is for foreign banks that are not required to file such reports with the SEC. In those cases, we pulled the annual reports from their investor information pages after confirming the CIK# on EDGAR. We found the data by pulling the CIK#s to identify the correct 10-K reports for the corresponding banks over the past five years.

Explain your data exploration and clean-up process

Our data exploration and clean-up process posed a number of challenges. Since not all banks are located in the US, not all of them were required to submit 10-K reports to the SEC. Additionally, their Income Statement (IS) and Balance Sheet (BS) were in their local currency rather than USD, which prompted conversion involving the use of year-end spot rates. 
Moreover, not all of the banks filed their annual reports during the typical year-end business cycle, rather, they filed them in different months. The reports were also large and not in CSV/Excel format, requiring us to manually sift through the reports to locate the Consolidated IS and BS and extract the appropriate figures. The banks also used different names to describe similar activities within the IS and BS, in addition to formatting numbers differently (e.g., shortening them from thousands to millions), necessitating standardization to millions. 
Each bank had numerous legal entities, subsidiaries, and lines of business, making it challenging to ensure that we had the correct data which fed up with the parent company's consolidated statements. Furthermore, many of our group members were not familiar with financial account data, and some of the terms and concepts were difficult to understand.

What are the largest investment banks by market share and how did they trend during a five-year window?

The banks ranked by market share over the 5yr aggregate are as follows JPM, GS, MS, BAML, Citi, Barclays, Jefferies, DB, RBC, CS. Looking at the 5-year trends we can see that JPM was the top IB with GS as second until the most recent year where GS overtook JPM. We also found that the smallest investment banks are pretty variable with CS at the bottom in 2017, RBC in 2018, Jefferies in 2019, and now, back-to-back smallest IB bank until 2020-2021 DB. On to Kevin for number 2. 

What is the size of the banks currently, based on total revenue and total assets and how do they compare to IB fees?

The Income Statement and BS are the major financial statements used to analyze banks. We took the current Total Revenue (IS) and Total Assets (BS) to help us measure and compare the banks. As we learned from Derek’s explanation of question #1, GS overtook JPM in the most recent year for IB fees. JPM still holds #1 in Revenue and Assets with GS as #2. We can also See that even though DB has now been the smallest IB of the 10 for the last 2 years in regard to Revenue. They are 3rd from the bottom, in front of CS and Jefferies, as well as middle (5th) overall in assets in front of RBC, MS, CS, Jefferies. On to Cheryl for question 3.

How big of a portion of these banks non-interest income are IB fees?

Investment banking fees make up a portion of the non-interest income which, when combined with Net interest income make up our total revenue. When we look at IB fees as a percentage of total non-interest income over the 5yr period we see that pretty much for all of the banks that IB fees sit in the range of about (10-30%), whereas for Jefferies IB fees makes up about 40% to 80% of their non-interest income from Year to year. This makes sense as the majority of Jefferies income comes primarily from investment banking compared to the more diversified IS for our other banks. On to Katie for number 4.

What do measures of central tendency and other statistics tell us about the results?

Looking at our regression, we can see that total IB fees were increasing over the 5-year period, though not super significantly. This makes sense because when we look at overall bank size, income statement, and balance sheet for, these banks, they continue to increase over the 5-year period. In other words, we can visualize that IB fees are going up with the rest of the bank. 

Implications

The banks at the top of investment banking, for the past half decade, normally do not move much in overall market share, with more variability surrounding the lower market shares; although smaller investment bank income does not necessarily meaning a smaller income statement or balance sheet. 

