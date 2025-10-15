# Hotel-Cancellation-Analytics-Dashboard
I have developed a comprehensive project in Excel, creating dashboards and tables to analyze the data. This process involved several stages, including data collection, data preprocessing, data cleaning, and data visualization.

<h2>Hotel Booking Cancellation Analysis (Interactive Dashboard using MS Excel)</h2>

## 🎯 Project Objective

The **Hotel Booking Cancellation Analysis** project aims to analyze the booking data of City and Resort Hotels to understand the key factors influencing **booking cancellations**.  
The objective is to help hotel management identify patterns and trends that contribute to cancellations and take **data-driven decisions** to reduce them, optimize revenue, and improve customer satisfaction.  

This dashboard provides valuable insights into:
- Booking and cancellation trends over time  
- Most affected customer segments  
- Impact of market segments, room types, and lead time on cancellations  
- Relationship between hotel type, booking channels, and cancellation behavior  

By leveraging these insights, the hotel can formulate better **marketing strategies**, **pricing models**, and **customer engagement plans** to minimize cancellations and maximize confirmed bookings.

________________________________________
## Dataset Used:
Link: <a href="https://github.com/tusharpatel0701/Hotel-Cancellation-Analytics-Dashboard/blob/d7b99d6520b78823be62e41b772871bd5cf8cacd/Hotel%20Booking%20Dataset.xlsx">Dataset</a>
________________________________________
## Questions (KPIs):

1.	Compare the total bookings vs. total cancellations across all years.
2.	Analyze Desired vs. Un-Desired room bookings — which room category has higher cancellations?
3.	Identify the monthly trend of total bookings and cancellations — which months record the highest activity?
4.	Compare the cancellation rates between City Hotel and Resort Hotel.
5.	Determine which guest type (Couples, Family, Single) has the highest number of cancellations.
6.	How does guest type (Single, Couples, Family) relate to cancellation trends?
7.	Calculate the total number of bookings and total cancellations for the period 2015–2017.
8.	Observe how total guests vs. cancelled bookings vary by guest type.
9.	Provide insights into how hotel type and room preference influence cancellation behavior.
10.	Track booking performance using year-wise slicer filters for dynamic analysis.
________________________________________
## Process:

### 1. Data Cleaning and Preparation
- Verified the dataset for **missing values**, **duplicates**, and **inconsistent data types** (dates, room types, hotel names).
- Replaced or removed null values in columns like *children* and *country*.
- Standardized categorical fields such as **hotel**, **guest_type**, and **room_status** for uniform analysis.

### 2. Data Analysis Using Pivot Tables
- Created **Pivot Tables** to summarize total bookings and cancellations.
- Built separate pivot tables for:
  - *Desired vs. Un-Desired Rooms*
  - *Monthly Booking and Cancellation Trends*
  - *City Hotel vs. Resort Hotel Comparison*
  - *Guest Type (Couples, Family, Single) Analysis*
- Added **calculated fields** to compute total cancellations, total bookings, and cancellation percentages.

### 3. Dashboard Creation
- Combined all pivot charts into a single **interactive Excel dashboard**.
- Used **bar charts** for month-wise and guest-type analysis.
- Used **pie charts** to represent hotel-type distribution and cancellation share.
- Displayed **KPI cards** showing total bookings and total cancellations.
- Added **year-wise slicers** (2015–2017) for dynamic filtering.

### 4. Formatting and Design
- Applied a **professional blue theme** for visual consistency.
- Used **icons, labels, and color differentiation** (blue for total bookings, orange for cancellations).
- Ensured clear chart alignment and interactive slicers for a user-friendly dashboard experience.



Dashboard Interaction: <a href="https://github.com/tusharpatel0701/Hotel-Cancellation-Analytics-Dashboard/blob/d7b99d6520b78823be62e41b772871bd5cf8cacd/Dashboard.png">View Dashboard</a>
________________________________________
Dashboard:
<img width="1706" height="1052" alt="Dashboard" src="https://github.com/user-attachments/assets/4bd13f28-2850-48e1-a196-e4fbea12933f" />

________________________________________
## 💡 Project Insights

- The **City Hotel** received more bookings than the **Resort Hotel**, but also experienced a higher cancellation rate.  
- **Couples** made the majority of the bookings, accounting for nearly **60%** of total reservations.  
- **July to August** recorded the highest number of total bookings as well as cancellations, indicating peak season volatility.  
- Guests booking **Desired Rooms** had significantly fewer cancellations compared to **Un-Desired Room** bookings.  
- The **overall cancellation rate** was around **37%**, showing the need for better guest retention strategies.  
- Most cancellations occurred for bookings made **through Online Travel Agencies (OTAs)**, highlighting dependency on third-party platforms.  
- **Families and Group travelers** showed a lower cancellation ratio compared to single or couple guests.  
- **City Hotels** faced more last-minute cancellations, while **Resort Hotels** had more early cancellations.  
- Bookings made closer to the check-in date had **lower chances of cancellation**, whereas long lead-time bookings showed higher risk.  
- **Cancellation patterns** were influenced by **seasonal demand** and **room type availability**, which can guide dynamic pricing policies.

________________________________________
## ✅ Final Conclusion

After analyzing the **Hotel Booking Dataset**, it can be concluded that:

- The **City Hotel** consistently outperforms the **Resort Hotel** in terms of total bookings but suffers from a higher **cancellation rate**.  
- **Seasonal peaks** (especially in **summer months**) drive more bookings but also more cancellations — indicating the need for better **demand forecasting** and **flexible refund policies**.  
- **Couples** represent the largest customer segment, suggesting targeted marketing campaigns and loyalty programs could improve retention.  
- Ensuring that customers receive their **desired room type** can significantly reduce cancellations, as dissatisfaction with room allocation contributes heavily to booking drop-offs.  
- Introducing **incentives for confirmed bookings**, such as discounts or room upgrades for non-refundable reservations, can help control the overall cancellation percentage.  
- By focusing on **booking source optimization**, **dynamic pricing**, and **personalized offers**, hotels can reduce cancellations and increase overall profitability.

In summary, the data shows that by improving room allocation, optimizing seasonal strategies, and providing better customer engagement, hotels can achieve a **significant reduction in booking cancellations** while enhancing **guest satisfaction and revenue growth**.


