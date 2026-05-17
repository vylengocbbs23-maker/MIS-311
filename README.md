# MIS 311 - Used Car Price Analysis

## Introduction to Business Analytics

### Data Analysis and Insight

## Data Overview

**Source of data:**
Used car market dataset collected from online vehicle listings and automotive sales platforms.

**Number of rows:**
203 rows

**Number of columns:**
7 columns

**The context:**
The used car market is influenced by many factors such as manufacturing year, mileage, fuel type, and vehicle condition. This dataset provides information about different used cars and their selling prices. Analysing this data helps identify the factors that affect car prices and understand customer preferences in the used vehicle market. Such analysis is useful for buyers, sellers, and businesses because it supports pricing decisions and market evaluation.

---

## Data Cleaning

### Duplicate rows: 5 rows

Five duplicate rows were identified in the dataset. These duplicate records were removed because they do not provide additional information and may create statistical bias during analysis. Duplicate rows can affect descriptive statistics, reduce data reliability, and influence the accuracy of visualisations. Therefore, removing duplicate rows helps improve data consistency and analysis quality.

After removing duplicate rows, the dataset contained 198 rows.

### Missing values: 10 rows

Several missing values were identified in the dataset, mainly in variables such as Color, Type, Fuel, and Year. In addition, a small number of missing values were found in the Price column. These incomplete rows were removed because missing information may reduce the accuracy and reliability of statistical analysis and visualisations. The missing rows account for approximately 5.05% of the remaining 198 rows, which is considered acceptable for removal without significantly affecting the overall dataset.

After the cleaning process, the final dataset contained 188 rows and 7 columns, making the dataset cleaner and more suitable for further descriptive analysis and data visualisation.

## Descriptive Statistics

<p align="center">
  <img src="https://raw.githubusercontent.com/vylengocbbs23-maker/MIS-311/ad97bc77f54c8bb52d629763828317e84ab8efe0/Screenshot%202026-05-17%20224247.png" alt="Descriptive Statistics" width="80%">
</p>

Table 1 presents the descriptive statistics of the used car dataset, including the variables Year, Km/h, and Price. The average manufacturing year is approximately 2016, while the median year is 2017, indicating that most vehicles in the dataset are relatively modern used cars. The minimum and maximum values show that the cars were manufactured between 2009 and 2024, suggesting a wide range of vehicle ages and conditions in the market.

The mileage statistics reveal considerable variation among vehicles. The average mileage is approximately 119,158 km, while the maximum mileage reaches 500,000 km. In addition, the high standard deviation indicates that the driving distances vary significantly across vehicles, meaning the dataset includes both lightly used and heavily used cars.

The price variable also shows substantial variation. The average car price is approximately 1,037,487, while the median price is 750,000. Since the mean price is significantly higher than the median price, this suggests that several expensive vehicles increase the overall average price. Furthermore, the large standard deviation and positive skewness indicate that car prices are unevenly distributed, with a small number of high-priced vehicles influencing the dataset.

## Insights

**Insight 1: Manufacturing Year and Car Price**

<p align="center">
  <img src="https://raw.githubusercontent.com/vylengocbbs23-maker/MIS-311/2a65ddd059936eee73de26e8f12bc571ef2a8479/Screenshot%202026-05-17%20231410.png" alt="Average Price by Manufacturing Year" width="80%">
</p>

Figure 1 shows that newer cars generally have higher average prices compared to older vehicles. Cars manufactured from 2020 to 2024 have noticeably higher market values, while vehicles produced before 2015 tend to have lower average prices. This suggests that customers are willing to pay more for newer models because they often provide better technology, safety features, fuel efficiency, and overall vehicle condition.

**Insight 2: Mileage and Car Price**

<p align="center">
  <img src="https://raw.githubusercontent.com/vylengocbbs23-maker/MIS-311/f5b7b9c14b6fa956350201644cf0dae2f25bbea3/Screenshot%202026-05-17%20231616.png" alt="Mileage vs Car Price" width="80%">
</p>

Figure 2 indicates a negative relationship between mileage and car price. Vehicles with lower mileage are usually sold at higher prices, while cars with higher mileage tend to have lower market values. This pattern suggests that buyers may associate heavily used vehicles with greater maintenance costs, reduced reliability, and shorter remaining lifespan, causing the selling price to decrease as mileage increases.

## Conclusion

This analysis explored the characteristics of the used car dataset using descriptive statistics and data visualisation techniques. The results show that manufacturing year and mileage are important factors affecting used car prices. Newer vehicles generally have higher market values, while cars with higher mileage tend to have lower selling prices.

In addition, the dataset revealed a wide variation in both mileage and price, indicating differences in vehicle condition and market demand. Overall, descriptive statistics and visualisations helped provide a clearer understanding of pricing patterns in the used car market.
