# SuperStore Returns Project  


##  The purpose of this project is to analyze the root causes of returned orders at the Superstore, identify patterns and trends contributing to high return rates, and develop a data-driven dashboard to help the CEO monitor and reduce return volumes effectively.
Dashboard Drafts [here](https://docs.google.com/document/d/1iZRZ_1nbPAxjYgz1YAV-eIf3xWuYFIHJllyMFu_y9d8/edit?usp=sharing)  
Tableau [here](https://public.tableau.com/app/profile/alison.fritts/viz/Sprint5_17307441715190/ReturnsStory)  
Presentation [here](https://www.youtube.com/watch?v=ybKaJ3n_1DE)

- Joined the Returns table to the Orders table using a LEFT JOIN to ensure all order records were included, with returned orders marked as “Yes” and non-returns as “null.”
- Created a calculated field to convert “null” values to 0 and “Yes” values to 1, allowing the return rate to be measured as an average.
- Developed a scatterplot to analyze the correlation between total sales and total returns at the subcategory level to determine if higher sales led to more returns.
- Built a bar chart displaying the return rate by product category to identify product types with the highest return percentages.
- Filtered customer return data to focus on customers with multiple orders, identifying those more prone to making frequent returns.
- Mapped return rates by geographic location (state/city) to detect regions with disproportionately high return volumes.
- Analyzed return rates over time to identify seasonal trends in returned orders.
- Constructed composite charts combining multiple factors (date, geography, product category) to provide deeper insights into return trends.
- Designed three low-fidelity mock-ups of a dashboard using pen-and-paper sketches to visualize return trends effectively.
- Created a dashboard template in Tableau using empty containers to match the chosen mock-up layout.
- Populated the dashboard with relevant charts and interactive filters, ensuring clear visualization of return insights.
- Drafted a Tableau Story Arc outlining key findings, causes of returns, and how to interpret the dashboard for decision-making.
- Demonstrated how to use the dashboard to identify root causes of returns and take corrective actions.
- Prepared a presentation explaining the analysis, dashboard usage, and proposed recommendations for reducing return rates.
- Published the final dashboard on Tableau Public and compiled all project files into a ZIP archive for submission.


- I built an interactive Tableau dashboard to analyze customer return patterns at the Superstore. The dashboard helps identify key factors contributing to high return rates, such as product categories, geographic trends, customer behaviors, and seasonal effects. This allows the CEO to make data-driven decisions to reduce return volume and improve profitability. 
- The project addressed the issue of high product return rates by uncovering the root causes behind returned orders. It provided insights into which products, customers, regions, and time periods had the highest return rates, enabling the company to refine its sales strategy, improve product quality, and enhance customer satisfaction.
- The technologies used were Tableau for data visualization and dashboard creation, SQL (Left Join) for data preparation and merging tables, excel/CSV for raw data analysis and processing, and screen recording software for presentation documentation
- The project took approximately 3 weeks to complete, including data analysis, visualization development, dashboard design, and final presentation.
- I worked independently on this project. 
  
### Conclusions
In the analysis of returns for the company Super Store it was found that sales and return rate do have a positive correlation. Note most data was measured by return rate but when measured with sales the return totals were used. Overall the data shows when sales go up returns also go up. While looking at customer return rates it was found that two customers have 100% return rates. When looking at state return rates it shows Utah has the highest return rate followed by California, and Oregon. Categories appear to have similar return rate with tech having the highest return rate by about 2%. Then looking at months the second half of the year shows a trend of higher return rate which could be a result of seasonality, November does not follow this trend.


### Recommendations
Address High Return Rates in Key States, investigate reasons for high return rates in Utah, California, and Oregon (e.g., product quality, shipping issues, or regional preferences).
Implement targeted quality control measures or stricter return policies in these regions.
Improve customer support in these states to reduce unnecessary returns.
Improve Product Quality and Customer Expectations, analyze common return reasons for tech products, which have the highest return rate.
Enhance product descriptions, images, and specifications to set accurate customer expectations.
Implement stricter quality control to minimize defective product shipments.
Reduce Returns from High-Return Customers, identify patterns in customers with 100% return rates and implement strategies like:
Personalized recommendations to ensure they purchase the right products.
Restricting returns for habitual returners or implementing restocking fees.
Offering direct customer support before finalizing orders.
Address Seasonality in Returns, since return rates increase in the second half of the year, investigate whether this is due to:
Holiday purchases leading to buyer’s remorse.
More promotional sales increasing impulse buys and returns.
Adjust return policies during peak seasons, such as offering exchanges instead of refunds.
Improve customer education during high-sales months to ensure informed purchasing decisions.
Optimize Logistics and Return Policies, improve packaging and shipping processes to reduce damage-related returns.
Offer better warranty or repair options instead of direct returns.
Provide incentives for store credit instead of full refunds to retain revenue.
By implementing these recommendations, Super Store can reduce return rates while maintaining customer satisfaction and operational efficiency.
