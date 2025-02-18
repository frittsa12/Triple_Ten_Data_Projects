# Zuber Project   


## The purpose of this project is to analyze ride-sharing data for Zuber in Chicago to identify passenger preferences, evaluate the impact of external factors such as weather on ride frequency and duration, and provide data-driven insights to optimize operations and improve customer experience.
Googlesheet [here](https://docs.google.com/document/d/1kVOoyWJdvvLIT0oByWqKDege903TqiXQIES55xTr6WQ/edit?usp=sharing)

- Analyzed taxi ride data from competitors to identify ride patterns for November 2017 and ranked companies based on trip volume.
- Filtered rides by company names containing "Yellow" or "Blue" to determine trip counts from November 1-7, 2017 for comparative analysis.
- Grouped taxi companies into categories, highlighting Flash Cab and Taxi Affiliation Services to quantify their trip volumes against other competitors in November 2017.
- Extracted neighborhood identifiers for O'Hare and the Loop to analyze trips specifically between these locations for targeted insights.
- Classified weather conditions as "Bad" or "Good" based on descriptions containing "rain" or "storm" for correlation with trip data.
- Joined weather records with trip data to associate ride durations with corresponding weather conditions for impact analysis.
- Filtered trips occurring on Saturdays between the Loop and O’Hare to evaluate ride duration differences under varying weather conditions.
- Compared ride durations under rainy and clear weather to determine if rain significantly affects trip times.
- Summarized findings and insights to provide recommendations on optimizing Zuber’s operations based on trip patterns and external influences.


- I built an analytical report that examines ride-sharing patterns in Chicago, focusing on competitor performance, passenger preferences, and the impact of weather on ride duration. The goal was to provide Zuber, a new ride-sharing company, with data-driven insights to optimize operations and enhance its competitive strategy.
- The project helped identify key factors influencing ride demand, such as peak-performing taxi companies, ride frequency trends, and how adverse weather conditions impact trip duration. This allows Zuber to make informed business decisions regarding fleet allocation, pricing strategies, and customer service improvements.
- The technologies used were SQL for querying and analyzing the database.   
- The project was completed in approximately 2 weeks, including data exploration, hypothesis testing, analysis, and report preparation.
- I worked independently on this porject.  
  
### Conclusions
The SQL queries analyzed focus on evaluating taxi trip patterns based on various factors such as weather conditions, company names, trip durations, and specific date ranges. Key insights include the classification of weather conditions as 'Good' or 'Bad', filtering trips by pickup and drop-off locations, analyzing company-specific trip counts, and determining the impact of external factors like weather and weekdays on trip durations. The findings suggest that adverse weather conditions may influence trip durations, and certain taxi companies dominate in specific time frames. These queries provide valuable insights for transportation management, service optimization, and predictive analysis, helping businesses make data-driven decisions.


### Recommendations
Optimize Taxi Availability in Bad Weather, since adverse weather conditions like rain and storms may impact trips, taxi companies should increase fleet availability during such conditions to meet potential demand surges.
Analyze Peak Times & Locations, by examining pickup and drop-off locations, companies can strategically position taxis in high-demand areas, improving customer wait times and service efficiency.
Company Performance Evaluation, the analysis of different taxi companies' trip counts highlights market leaders. Underperforming companies should review pricing strategies, driver availability, and service quality to remain competitive.
Improve Weekend Service, since one query specifically filters for trips on a Saturday (dow = 6), it suggests that weekend patterns should be further analyzed. Companies should adjust staffing and pricing models to accommodate peak weekend demand.
Data-Driven Decision Making, future analysis can integrate additional factors like traffic conditions, customer reviews, and fare pricing to develop a more comprehensive strategy for service improvement and efficiency.
By leveraging these recommendations, taxi companies can enhance their operational efficiency, customer satisfaction, and profitability while adapting to real-world demand patterns.
