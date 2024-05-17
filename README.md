# PARENTAL LEAVE ANALYSIS

## Table of Contents
- [Introduction](#introduction)
- [Skills Demonstrated](#skills-demonstrated)
- [Data Sourcing](#data-sourcing)
- [Data Transformation](#data-transformation)
- [Tools](#tools)
- [Report and Insights](#report-and-insights)
- [Recommendations](#recommendations)


![family-parent use](https://github.com/Hassanat36/Maven_powerbi_project/assets/138366531/90df790f-40ae-42f1-9302-b472ed38b941)



## Introduction

My journey into the world of parental leave policies, driven by data and brought to life with Power BI Desktop, has unveiled critical findings that illuminate the current landscape. Drawing from a comprehensive survey of 1,601 companies spanning 186 industries, I've transformed this data into a captivating visual narrative.


## Skills Demonstrated

-	Extract Transform and Load (ETL).
-	Data Analysis Expression (DAX).
- Data Visualization.

   ## Data Sourcing

   Data was gotten from Kaggle. [Click here](https://www.kaggle.com/datasets/shilongzhuang/things-we-do-for-family-some-bald-guy) 

   ## Data Transformation
 1. I imported my dataset to Power Query by using the format connector in PowerBI.
 2. I created new columns
    - Months for paid paternity leave ( DIVIDE('parental_leave edit'[Paid Paternity Leave],4))
    - Months for paid maternity leave ( DIVIDE('parental_leave edit'[Paid Maternity Leave],4))
3. I calculated percentage paid maternity and paternity leave.
4. I calculated Average paid, unpaid maternity and paternity leave

   ## Tools
- Excel for data cleaning
- PowerBI for creating reports

   ## Report and insights
  
![Report](Maven Parental Leave Reports)

![u0Wt27N - Imgur](https://github.com/Hassanat36/Maven_powerbi_project/assets/138366531/af3ca580-893f-425f-be41-7cc000a6530a)

### 1.  Averaging Parental Leave Duration: 
Globally, companies offer an average of 10.9 weeks of paid maternity leave and 7.3 weeks of paid paternity leave. These figures serve as a baseline for understanding the worldwide commitment to supporting working parents.
### 2. Unpaid Leave Averages: 
In addition to paid leave, the data shows that unpaid maternity leave averages around 6.6 weeks, while unpaid paternity leave averages slightly longer at 7.7 weeks. This diversity in policies highlights the various ways companies accommodate parents' needs.
### 3. Prevalence of Parental Leave Policies: 
An impressive 98.25% of the surveyed companies provide maternity leave, underscoring the widespread recognition of supporting new mothers. However, only 16.94% extend paternity leave benefits, indicating an opportunity for greater support to new fathers.
### 4. Impact by Company:
 The Grant Thornton, LAC- Group, Flatiron Health and Bill and Melinda Gates Foundation offers balanced paid parental leaves.
### 5. Top Industries for Parental Leave:
 Among various sectors, Healthcare, particularly in Telemedicine and Philanthropy, offers the most generous paid maternity and paternity leave, surpassing all others in supporting new parents.
### 6. Maximum Paid Maternity Leave:
 Interestingly, 1.25% of companies offer an extensive 52 weeks of paid maternity leave, showcasing the varying levels of support provided by different organizations.
 
## RECOMMENDATIONS
1. Extend Paternity Leave: Given the disparity between maternity and paternity leave, we recommend that more companies consider extending paternity leave benefits. This move can promote gender equality, encourage fathers' active involvement in childcare, and alleviate the burden on new mothers.
2. Benchmark Against Industry Leaders: Companies looking to enhance their parental leave policies should take cues from industry leaders, especially in the philanthropy sector. Benchmarking against organizations with generous policies can set competitive standards and attract top talent.
3. Offer Longer-Term Maternity Leave: While most companies offer maternity leave within the 0-3 months range, consider providing options for longer-term leave. This allows mothers to effectively balance career and family life.



  



  
