# Airline Data Analysis

## Steps Included
- Understanding the Business Problem
- Importing Libraries
- Database connection to extract data
- Exploring tables present in the Database to identify key variables
- Analyzing the key variables
- Creating Report with all the results and analysis for the company.

## Skills
- Python
- PostgreSQL

## Database File
Download the dataset from 

## Business Problem
Our company operates a diverse fleet of aircraft ranging from small business jets to medium-sized machines. We have been providing high-quality air transportation services to our clients for several years, and our primary focus is to ensure a safe, comfortable, and convenient journey for our passengers. However, we are currently facing challenges due to several factors such as stricter environmental regulations, higher flight taxes, increased interest rates, rising fuel prices, and a tight labor market resulting in increased labor costs. As a result, the company's profitability is under pressure, and they are seeking ways to address this issue. To tackle this challenge, they are looking to conduct an analysis of their database to find ways to increase their occupancy rate, Revenue and Ticket Sales, Flight Performance, Popular Routes and Airports and Customer Segmentation.

## Main Challenges
1. Stricter environmental regulations: The demand on the airlines industry to reduce its carbon footprint is growing, resulting in more stringent environmental laws that increase operating costs and restrict expansion potential.
2. Higher flight taxes: To address environmental issues and generate revenue, governments worldwide are imposing heavier taxes on aircraft, raising the cost of flying and decreasing demand.
3. Tight labor market resulting in increased labor costs: The shortage of trained personnel in aviation has driven up labor costs and increased turnover rates.

## Objectives
1. Increase Occupancy Rates: By raising occupancy rates, we can enhance the average profit per seat and alleviate the impact of the challenges we're facing.
2. Improve Price Strategy: We need to formulate a pricing strategy that considers the evolving market conditions and customer preferences, aiming to attract and retain customers.
3. Enhance Customer Experience: Our focus should be on delivering a seamless and convenient experience for our customers, spanning from booking to arrival. This approach will differentiate us in a highly competitive industry and foster customer loyalty.

The end goal of this task would be:
1. To identify opportunities to increase the occupancy rate on low-performing flights, which can ultimately lead to increased profitability for the airline.
2. Which fare classes (Business, Economy) generate the most revenue? How do pricing strategies affect sales?
3. Analyze the frequency of flight delays or cancellations. Which airports or routes have the most disruptions?
4. Which routes or airports are most frequently used, and how does this impact operational efficiency?
5. Can we categorize passengers based on ticket purchases (e.g., frequent flyers, economy vs. business)?

## Basic Analysis
The initial data analysis provides insights into the number of large aircraft (over 100 seats), booking trends, revenue generation, and average fares. This information will aid in developing strategies to optimize occupancy rates and pricing for each aircraft type. Table 1 lists the large aircraft models and their corresponding seat capacities.

To analyze ticket booking trends and associated revenue, we employed a line chart. The chart revealed a steady increase in bookings from June 22nd to July 7th, followed by a relatively stable period until August. A significant peak in bookings was observed on a single day. Revenue closely correlated with ticket bookings, mirroring the same trend. Understanding the factors driving this peak could lead to strategies for boosting revenue and optimizing operations.

A bar graph comparing average fare costs for different classes (business, economy, comfort) on various aircraft is shown in Figure 3. The CN1 and CR2 offer only economy class, while the 773 provides all three. Business class fares consistently exceed economy class fares across all aircraft.

## Analyzing Occupancy Rate
Airlines must thoroughly analyze their revenue streams in order to maximize profitability. The overall income per year and average revenue per ticket for each aircraft are important metrics to consider. Airlines may use this information to determine which aircraft types and itineraries generate the most income and alter their operations appropriately. This research can also assist in identifying potential for pricing optimization and allocating resources to more profitable routes. The below Figure 4 shows the total revenue, total tickets, and average revenue made per ticket for each aircraft. The aircraft with the highest total revenue is SU9, and from Figure 3, it can be seen that the price of the business class and economy class is the lowest on this aircraft. This could be the reason that most people bought tickets for this aircraft as it costs less compared to others. The aircraft with the least total revenue is CN1, and the possible reason behind this is that it only offers economy class with a very low price. It might be because of its poor conditions or fewer facilities.

The average occupancy per aircraft is another critical metric to consider. Airlines may measure how successfully they fill their seats and discover opportunities to boost occupancy rates by using this metric. Higher occupancy rates can help airlines increase revenue and profitability while lowering operational expenses associated with vacant seats. Pricing strategy, airline schedules, and customer satisfaction are all factors that might influence occupancy rates. The below Figure 5 shows the average booked seats from the total number of seats for each aircraft. The occupancy rate is calculated by dividing the booked seats by the total number of seats. Higher occupancy rate means the aircraft seats are more booked and only few seats are left unbooked.

Airlines can assess how much their total yearly turnover could improve by providing all aircraft with a 10% higher occupancy rate to further examine the possible benefits of raising occupancy rates. This research can assist airlines in determining the financial impact of boosting occupancy rates by 10%, which results in a gradual increase. Therefore, airlines should focus more on pricing strategies.

## Revenue Sales Analysis of Flights and Tickets
From this analysis, you can identify which fare classes (e.g., Business or Economy) generate the most revenue. If a fare class (e.g., Business) generates lower revenue, you could suggest targeted marketing, discounts, or upsell strategies to improve sales in that segment.

## Flight Performance Analysis
The visualization will show which routes are the most problematic in terms of delays or cancellations. You can recommend revisiting flight schedules, adding buffer time between flights, or improving coordination with airports to minimize these issues.

## Popular Routes and Airports
This map provides a geographical overview of flight activity. From this, you can identify active regions and recommend route optimizations or airport upgrades to accommodate high traffic.

## Conclusions:
By performing these analyses, we can uncover key insights such as:

- Occupancy Rate: Identifying underperforming routes and improving occupancy via promotions or route changes.
- Revenue Optimization: Targeted strategies to boost sales in underperforming fare classes.
- Flight Performance: Addressing delays or cancellations by improving flight schedules or operations.
- Route Efficiency: Adjusting flight frequencies to balance demand and operational capacity.
- Geographical Trends: Optimizing routes based
