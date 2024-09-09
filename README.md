# Sterling-E-Commerce-Performance-Analysis


![](commerce.jpg)


## Table of Contents
- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Project Objective](#project-objective)
- [Data Sources](#data-sources)
- [Data Handling](#data-handling)
- [Data Visualization](#Data-Visualization)
- [Key Insights](#key-insights)
- [Conclusion](#conclusion)
- [Recommendations](#recommendations)

## Project Overview
This project analyzes FutureTale Hotel bookings using Excel to address the rising issue of reservation cancellations. The data revealed a 22% increase in 
cancellations between July 2017 and October 2018, highlighting a significant shift in booking patterns. By leveraging Excel, key factors contributing to this 
trend were identified, offering insights to mitigate future cancellations and improve reservation stability.

## Problem Statement

![](hotel1.jpg)
- High number of cancellations and no-shows as a result of Current cancellation policy that allows free or low-cost cancellations.
- This policy benefits guests but negatively impacts the hotel’s revenue.

## Project Objective
The main objective of this project is to conduct a detailed analysis of hotel reservation data to uncover insights and address the challenges associated 
with rising cancellation rates.

## Data Sources
The dataset used in this project was provided by 10Alytics. The key features are Booking ID, number of adults and children, number of weekend and weeknights, 
meal plan type, car parking requirements, reserved room type, lead time, arrival year and month, market segment, repeated guest status, previous cancellations and bookings, 
booking status, and average price per room.

## Data Handling
Data compilation and cleansing were performed, with duplicate entries identified and removed. A new column, "sum of is_cancelled," was introduced using the 
"IF" function to assign a value of "1" for cancelled bookings and "0" for non-cancelled ones. The VLOOKUP function was applied to derive accurate arrival month names by referencing 
the table containing month numbers and paired them with their corresponding names, ensuring accurate reservation details for FutureTale Hotel.

## Dashboards

![](Dashboard1Sterl.jpg)

![](Dashboard2Serl.jpg)

## Conclusion
The examination of FutureTale Hotel booking data reveals critical insights into booking and cancellation trends. The significant rise in cancellation rates between 2017 and 2018 underscores the need 
for targeted strategies to enhance booking stability. By addressing key factors such as meal plans and room types that contribute to cancellations, FutureTale Hotel can implement data-driven improvements 
to optimize guest satisfaction and operational efficiency.

## Recommendation
- Package Deals: Create attractive package deals that include meal plans to enhance the overall value for guests. Offer a range of flexible meal plan options to meet diverse preferences.
- Promotional Campaigns: Initiate targeted promotional campaigns that emphasize the benefits of booking package deals with meal plans. Highlight the added value and convenience to entice more bookings.
- Review Room Type Policies: Reassess the cancellation policies for room types with higher cancellation rates. Adjust these policies to be more accommodating for guests, while maintaining operational viability.
- Dynamic Pricing: Adopt dynamic pricing strategies to adjust room rates based on factors such as demand, seasonality, and booking trends. Offering competitive rates during periods of historically lower cancellations 
  could boost reservations.
- Diversification: Seek opportunities to diversify the guest base by targeting segments with historically lower cancellation rates. Explore partnerships and collaborations to attract more stable clients.
  Tailored marketing and promotional strategies to address high-cancellation segments with personalized offers, loyalty programs, or exclusive deals.
