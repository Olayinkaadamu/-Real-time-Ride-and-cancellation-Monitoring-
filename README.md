# Real-time Ride and cancellation Monitoring
Power BI | UBER Real-Time Ride |From Raw Data to Business Insights

### Table of content
- [Project Overview](#project.overview)
- [Tools and Technologies](#tools--technologies)
- [Dataset Overview](#dataset.overview)
- [Data Cleaning process](#data.cleaning.process)
- [Power BI Dashboard](#power.bi.dashboard)
- [Key Insights](#key.insights)
- [Recommendations](#recommendation)


### Project Overview
The goal of this dashboard is to track ride performance, customer behaviour, and operational efficiency in real time.
Using Power query for Data cleaning, Power BI for Data Visualization. This Project turns Raw transaction into Actionable Insights.

### Tools & Technology 
* Excel (Power query)
* Power BI

### Dataset Overview
Colums:
Date, Time, Booking ID, Booking Status, Customer ID, Vechicle Type,Pickup Location, Drop Location, Avg VTAT, Avg CTAT, Cancelled Rides by Customer, Reason for cancelling by Customer, Cancelled Rides by Driver, Driver Cancellation Reason, Incomplete Rides, Incomplete Rides, Incomplete Rides Reason, booking Value, Ride Distance, Driver Ratings, Customer Rating, Payment Method.

### Data Cleaning Process
* Convert Date and Time to proper Date and Time format
* Remove missing or invalid value
* Created new calculated Field:
* Total Booking value
* Total cancellations
* Cancellation Rate
* Total successful Booking
* Avg Rating

### Power BI Dashboard
The Power BI Dashboard includes the following Pages:
- Revenue
- Overall
- Vehicle Type
- Cancellation
- Rating
  ![Screenshot 2025-09-28 222003](https://github.com/user-attachments/assets/f6487e47-9740-479e-a24d-67c30dc0976a)


  ### 📊 Key Insights
- High Booking Value, and consistent monthly demand  
- Booking Done rate exceeds 65%, strong supplier reliability  
- Driver side cancellations dominate, a governance risk  
- Vehicle types show performance variation, opportunity for fleet optimization  
- Ratings are high but revenue varies, signals quality vs cost trade offs

### Recommendations
UPI is far the most popular payment method, followed by Cash, Uber wallets and cards lagging.
Daily rides hover around 80-85k, but there is noticeable dip towards the end of the month.
Customer ID CID26744107 has the highest booking value.
- Maintain current payment options. 
- Consider loyalty perks by method.  
- Log payment method per ride for refund traceability.

Booking Value: £52M  Strong overall performance  
- Booking Status:
  - 67.1% completed  
  - 17% cancelled by drivers  
  - 11.14% cancelled by customers  
- Monthly Bookings: Consistent across all months stable demand.
- Maintain current fleet and supplier mix due to stable monthly bookings.  
- Investigate driver side cancellations (17%) and log causes into scenario cards.  
- Monitor booking completion rate (67.1%) to ensure supplier reliability.  
- Use governance notes to track trends and guide supplier accountability.  
- Document refund triggers and dispatch delays for audit clarity.

Vehicle Type Performance
- Prioritize Go Sedan and Go Moto for expansion.  
- Reassess Go SUV’s pricing or route strategy.  
- Monitor cancellation ratings for high-performing vehicles.

 Booking & Cancellation
- Investigate high cancellation rate.  
- Log cancellation reasons into scenario cards.  
- Optimize dispatch and reallocate fleet during peak hours.

Ratings & Revenue
- Leverage high ratings to identify loyalty segments.  
- Explore upsell opportunities for low-revenue, high-rating rides.  
- Track supplier quality through rating-linked scenario cards.

### Excel file

(Download Data)(https://1drv.ms/x/c/0214e947ac267ad5/Ea9IZlFiMYlClpCC5HIR6tsBKl6-bsWf8dCqi7WoRPuMHA?e=jjOtc7)




  
  


 
