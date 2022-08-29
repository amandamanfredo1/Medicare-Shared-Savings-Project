# Medicare-Shared-Savings-Project
Analysis of Medicare Shared Savings  Program 2016-2020

Healthcare costs have been steadily increasing for the last several decades
In the year 2000 , $1.4 trillion was spent on healthcare expenditures 
By the year 2020, that increased to $4.1 trillion
Health spending accounts for 19.7% of the nation’s Gross Domestic Product



What is MSSP and how does it work?
MSSP stands for Medicare Shared Savings Program
Started in 2012, with updated “tracks” available in 2016, 2018 and 2019
Ultimate purpose is to “reduce healthcare costs and reward you for making informed and cost-effective decisions about your healthcare.”
Works with ACO’s (Accountable Care Organizations) to provide financial incentives for decreasing costs while reaching quality goals

I used the “Performance_Year_Financial_and_Quality_Results” dataset from the CMS website
Contains financial data as well as quality data for each ACO
Financial data source: CMS calculations of performance year inputs
Individual Quality measures source: ACO submitted data through claims and other interfaces
Contains data from 2016 to 2020


As more risk is shifted to providers with MSSP, Risk Scores become a more important assessment
The more beneficiaries an ACO has, the more likely they are to have higher cost/risk beneficiaries
Especially since Medicare patients are more likely to have multiple conditions
Since ACO’s receive shared saving bonuses if they lower spending, this could lead to ACO’s avoiding beneficiaries that are more chronically or acutely ill, or even drop clinicians from the program who focus on more high-risk patients.  
If the risk scores lead to lack of shared saving bonuses, more ACO’s are likely to drop out of the program

Different tracks in the MSSP generally correlate to the level of risk and shared savings 
Current_BASIC_A and Current_BASIC_B are one-sided shared savings model or “upside risk” but must meet minimum quality performance standards
Up to 40% shared savings based on quality, and capped at 10% of shared expenditures
No shared losses
Current_BASIC_C,D,E and ENHANCED are two-sided shared savings models
Enhanced features up to 75% shared savings based on quality, and capped at 20% of shared expeditures
1 minus final sharing rate (40%-75%), up to 15% of shared expenditures

The Medicare Shared Spending Program’s focus on value based care is shifting focus to effective treatments to save money
The Track that an ACO is on influences the FinalShareRate and overall savings the most
“Winners” are those enrolled in a two-sided risk model due to higher average savings
In the future we can look at which preventative care measures influence savings

