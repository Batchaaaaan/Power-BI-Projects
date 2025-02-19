<div align="center">
<h1> DENGUE CASES ANALYSIS AND DASHBOARD </h1>
</div>
<div align="center"><img src="https://github.com/Batchaaaaan/Power-BI-Projects/blob/main/dengue-cases-analysis-and-dashboard/images/dashboard.png"></div>

## PROJECT OVERVIEW
Dengue fever is a major public health concern in the Philippines, with a high incidence rate and considerable effects on the population. In recent years, the country has faced several dengue outbreaks, leading to widespread illness and fatalities. This report utilizes Exploratory Data Analysis (EDA) to examine the trends and patterns of dengue cases in the Philippines. By analyzing the data, we aim to better understand the dynamics of dengue fever, identify possible risk factors, and provide insights that can support public health strategies to reduce the disease’s incidence.

<hr>

## DATA INFORMATION
### Data Source: https://www.kaggle.com/datasets/vincentgupo/dengue-cases-in-the-philippines
### About dataset
Data set contains the recorded number of dengue cases per region of the Philippines from year 2016 to 2020. It can be used to find trends about the disease as well as spatiotemporal analysis that can result into data-driven solution about the trends of the disease for the past 5 years.
### Feature
| Feature | Description|
|-|-|
| Month | Month of the year in text format |
| Year | Ranges from 2016-2020 in numerical format |
|	Region | Region in the Philippines |
|	Dengue_Cases | Number of Monthly Cases per region. The dengue deaths are also included in this feature |
|	Dengue_Deaths | Number of Monthly Deaths per region due to dengue |

<hr>

# EXPLORATORY DATA ANALYSIS
### Sample statistics and Visualizations
#### What is the Total Number of Cases and Total Number of Deaths from 2016 to 2020?
<div align="center"><img src="https://github.com/Batchaaaaan/Power-BI-Projects/blob/main/dengue-cases-analysis-and-dashboard/images/visual1.png"></div>

- On the span of five years, there have been ~1 million ( 1,147,425 ) total number of cases of Dengue fever and ~17K ( 16, 844 ) total number of Deaths. 

#### What region has the highest total number of cases for the year 2016-2020?
 <div align="center"><img src="https://github.com/Batchaaaaan/Power-BI-Projects/blob/main/dengue-cases-analysis-and-dashboard/images/visual2.png"></div>
 
 -  CALABARZON (Region IV-A) recorded the highest number of dengue cases, with approximately 163,000 cases (163,029). In contrast, BARMM (Bangsamoro Autonomous Region in Muslim Mindanao) reported the lowest number of cases, with around 12,000 (11,537).

#### What is the trend of the disease for the past 5 years? Is it going lower or higher?
  <div align="center"><img src="https://github.com/Batchaaaaan/Power-BI-Projects/blob/main/dengue-cases-analysis-and-dashboard/images/visual3.png"></div>
  
  - Despite the spike in cases in 2019, the latest trend shows a decline in dengue fever cases.
 
#### Which month have the highest Number of Dengue Cases and Deaths? 
 <div align="center"><img src="https://github.com/Batchaaaaan/Power-BI-Projects/blob/main/dengue-cases-analysis-and-dashboard/images/visual4.png"></div> 
 
- August and September reported the highest number of dengue fever cases, with approximately 188,000 and 178,000 cases, respectively. Although August had the highest case count, it recorded only about 1,000 deaths. In contrast, October and September had the highest death tolls, with around 7,000 and 6,000 deaths, respectively. 


#### Which Island has the Highest Death-to-Case Ratio in the Philippines?
 <div align="center"><img src="https://github.com/Batchaaaaan/Power-BI-Projects/blob/main/dengue-cases-analysis-and-dashboard/images/visual5.png"></div>

- The Death-to-Case Ratio represents the proportion of Total Deaths to Total Cases, providing a measure of the disease's severity. A high Death-to-Case Ratio indicates a greater likelihood of death for those infected. 
- Among the three main island groups in the Philippines, Mindanao has the highest Death-to-Case Ratio at 0.022, while, unexpectedly, Luzon has the lowest at 0.011. 

#### Which region have the highest Death-to-Case Ratio in the Philippines?
  <div align="center"><img src="https://github.com/Batchaaaaan/Power-BI-Projects/blob/main/dengue-cases-analysis-and-dashboard/images/visual6.png"></div>
  
- SOCCSKSARGEN (Region XII) has the highest Death-to-Case Ratio at 0.05. With a total of 59,802 reported cases, the region recorded 2,796 deaths. In contrast, Ilocos Region (Region I) has the lowest Death-  to-Case Ratio at 0.0027, recording 59,066 cases and only 157 deaths.

<hr>

## Conclusions

-	The analysis of dengue fever cases in the Philippines reveals significant regional and temporal variations. SOCCSKSARGEN (Region XII) recorded the highest Death-to-Case Ratio at 0.05, indicating a higher severity of dengue cases compared to other regions. Conversely, the Ilocos Region (Region I) had the lowest Death-to-Case Ratio at 0.0027, suggesting more effective management or less severe outbreaks in that area. 
-	Among the island groups, Mindanao reported the highest Death-to-Case Ratio, while Luzon had the lowest.
-	Seasonal patterns were also observed, with August and September experiencing the highest number of dengue cases. 
-	Following a significant spike in 2019, the overall trend in dengue cases shows a decline, suggesting potential improvements in prevention and control measures.
-	Regions such as Region IV-A, Region III, NCR, Region VI, and Region VII have each reported at least 100,000 dengue fever cases.
<hr>

## Recommendations
-	Increase monitoring and early warning systems in regions with high Death-to-Case Ratios, particularly in SOCCSKSARGEN and Mindanao, to enable prompt medical interventions.
-	Implement focused awareness and preventive measures during peak months (August to October) to minimize the impact of seasonal outbreaks.
-	Allocate more healthcare resources and strengthen medical facilities in high-risk regions to reduce mortality rates.
-	Investigate the underlying factors contributing to the high Death-to-Case Ratio in SOCCSKSARGEN and the lower ratio in Ilocos Region to identify effective practices that can be implemented nationwide.
-	Implement extensive public health awareness programs in regions with the highest number of dengue cases, including Region IV-A, Region III, NCR, Region VI, and Region VII, where cases exceed 100,000.

