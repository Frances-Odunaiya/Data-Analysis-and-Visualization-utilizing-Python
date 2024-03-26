# How Does a Bike-Share Navigate Speedy Success ?
### The real question is - How do annual members and casual riders use cyclistic bikes ?

## Table of contents

- [Clear Statement of the business task](#Clear-Statement-of-the-business-task)

    - [StakeHolders](#STAKEHOLDERS)

- [A description of all data sources used](#A-description-of-all-data-sources-used)

- [Documentation of any cleaning or manipulation of data](#Documentation-of-any-cleaning-or-manipulation-of-data)

- [A summary of my analysis](#-A-summary-of-my-analysis)

- [Supporting Visualizations and Key Findings](#Supporting-Visualizations-and-Key-Findings)

- [Recommendations](#RECOMMENDATIONS)

- [Conclusion](#IN-CONCLUSION)


## Clear Statement of the business task
The problem I am trying to solve revolves around maximizing the number of annual memberships at Cyclistic, a bike-share company in Chicago. The director of marketing believes that converting casual riders into annual members is crucial for the company's future success. Therefore, the business task is to design marketing strategies aimed at converting casual riders into annual members.

### STAKEHOLDERS
-	**Lily Moreno (Director of Marketing)**: Responsible for developing campaigns and initiatives to promote the bike-share program. Moreno is keen on increasing the number of annual memberships as a strategic growth driver.

-	**Cyclistic Marketing Analytics Team**: Responsible for collecting, analyzing, and reporting data to guide marketing strategy decisions. They will play a crucial role in providing insights and recommendations based on data analysis.

-	**Cyclistic Executive Team**: The decision-makers who will approve the recommended marketing program. They are interested in strategies that align with the company's growth objectives and profitability goals.


A **clear statement of the business task** is to design marketing strategies aimed at converting casual riders into annual members, with the ultimate goal of maximizing the number of annual memberships at Cyclistic.

## A description of all data sources used

- The primary data source for this analysis is the Cyclistic historical bike trip data, which includes information such as trip duration, start and end times, bike type, user type (annual member or casual rider), and station locations. This dataset spans multiple years and contains millions of trip records. 

- Financial analysts have also concluded that annual members are much more profitable than casual riders.

- The data has been made available by Motivate International Inc. under this [license](https://divvybikes.com/data-license-agreement)

## Documentation of any cleaning or manipulation of data

- **Removal of irrelevant columns**: I retained only the necessary columns for this analysis, including trip duration, user type, and bike type.

- **Handling missing or erroneous values**: I checked for missing or incorrect values in crucial fields and didn’t find any.

- **Conversion of data types**: I ensured that data types were appropriate for analysis, such as converting String Objects to datetime objects for easier manipulation.

- **Aggregation of data**: I aggregated the trip data to calculate key metrics such as average trip duration and frequency of bike usage for annual members and casual riders.

## A summary of my analysis

Through the analysis of Cyclistic bike trip data, I identified several differences in the usage patterns between annual members and casual riders:

Annual members tend to take shorter but more frequent trips compared to casual riders.

Casual riders often use bikes for leisure activities or occasional commuting, leading to longer trip durations on average.

There are distinct usage patterns based on the time of day and day of the week, with annual members showing more consistent usage throughout the week, including peak commuting hours.

Annual members are more likely to utilize the traditional bikes, while casual riders may opt for assistive options or cargo bikes, depending on their specific needs.

## Supporting Visualizations and Key Findings

**Average Trip Duration Comparison**: 
-	Key Finding: Annual members have shorter average trip durations compared to casual riders, indicating more frequent but shorter rides.
  <img src="/cyclicist_bike_share/Frequency of Bike Usage Comparison.png" alt="Average Trip Duration Comparison">

**Frequency of Bike Usage**: 
-	Key Finding: Annual members exhibit higher frequency in bike usage compared to casual riders, indicating more consistent and regular usage patterns.
  <img src="/cyclicist_bike_share/Frequency of Bike Usage Comparison.png" alt="Frequency of Bike Usage Comparison">

**Usage Patterns by Time of Day**: 
-	Key Finding: Annual members show more consistent usage throughout the day, with peaks during commuting hours, while casual riders exhibit more varied usage patterns.
  <img src="/cyclicist_bike_share/Usage Patterns by Time of day.png" alt="Usage Patterns by Time of day">
  
**Preferred Bike Types**: 
-	Key Finding: Annual members predominantly use traditional bikes, whereas casual riders may opt for alternative bike types based on their specific preferences and needs.
    <img src="/cyclicist_bike_share/Preferred Bike Type.png" alt="Preferred Bike Type">
    
These visualizations and findings provide valuable insights into the differences in bike usage between annual members and casual riders, laying the foundation for targeted marketing strategies aimed at converting casual riders into annual members.

## RECOMMENDATIONS

Based on the analysis of the differences in bike usage between annual members and casual riders, here are the top three recommendations for Cyclistic to convert casual riders into annual members:

### Tailored Membership Plans:

- **Recommendation**: Develop customized membership plans that align with the distinct usage patterns of annual members and casual riders.

- **Rationale**: Annual members prefer shorter but more frequent trips, indicating a need for plans that offer flexibility and value for regular use. Casual riders, on the other hand, may benefit from options that cater to occasional usage with longer trip durations or one-time passes for leisure activities.

- **Implementation**: Introduce tiered membership plans with varying pricing structures and benefits tailored to the specific needs and preferences of each user segment. Highlight the cost savings and convenience of annual memberships for frequent riders, while also offering flexible options for casual users.

### Targeted Promotions and Incentives:

- **Recommendation**: Launch targeted marketing campaigns and promotional offers to incentivize casual riders to upgrade to annual memberships.

- **Rationale**: Annual members demonstrate higher frequency and consistency in bike usage, indicating a strong commitment to the service. Offering exclusive promotions, discounts, or bonus incentives can encourage casual riders to make the switch by highlighting the long-term savings and benefits of annual memberships.

- **Implementation**: Utilize digital media channels to deliver personalized offers and targeted advertisements to casual riders based on their usage history and preferences. Leverage data analytics to identify segments with high conversion potential and tailor promotions accordingly, emphasizing the advantages of annual memberships.

### Enhanced User Experience and Engagement:

- **Recommendation**: Focus on improving the overall user experience and engagement to retain existing annual members and attract new ones.

- **Rationale**: Providing a seamless and enjoyable experience for users is essential for fostering loyalty and encouraging membership renewals. Enhancements such as user-friendly mobile apps, intuitive station navigation, and responsive customer support can contribute to a positive perception of the service and increase user satisfaction.

- **Implementation**: Invest in technology upgrades and infrastructure improvements to streamline the bike-sharing experience, from bike checkout to return. Implement user feedback mechanisms to gather insights and address pain points effectively. Additionally, foster a sense of community among members through social events, rewards programs, and interactive features to enhance engagement and promote retention.

By implementing these recommendations, Cyclistic can effectively capitalize on the differences in bike usage between annual members and casual riders, driving higher conversion rates and long-term growth in membership subscriptions.

# IN CONCLUSION
Understanding the distinct usage patterns of annual members and casual riders is essential for devising effective marketing strategies to promote annual memberships. By leveraging these insights, Cyclistic can tailor its marketing initiatives to better cater to the needs and preferences of both user segments, ultimately driving higher conversion rates and business growth.
