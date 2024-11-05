Hotel Booking Cancellations Analysis
A large data set containing information on booking ws used to analyze the cancellation pattern and draw insights to reduce cancellation.
This analysis looks at why people cancel hotel bookings based on guest profiles, booking patterns, hotel facilities, and seasonal trends. As more people book hotels online, flexible cancellation policies make it easier for guests to cancel, which affects hotel revenue. This analysis finds out which groups are more likely to cancel and shows ways to reduce these cancellations.

#Key Findings
The study is in four parts.
1. Guest Profiles & Booking Behavior
   - Adults in Booking: Bookings with 2-3 adults have the highest cancellation rates.
   - Group Size: Bookings with larger groups (more than 3 people) have higher cancellation rates than single, double, or triple groups.
   - Parental Status: Parents are slightly more likely to cancel than non-parents.
   - Visitor Type: First-time guests cancel more often than repeat guests.
   - Previous Cancellations: Guests with past cancellations are more likely to cancel again.
   - Successful Bookings: Repeat guests without past cancellations usually keep their bookings.
2. Hotel Facilities & Room Preferences
   - Room Price: We categorized bookings based on room price ranges (e.g., Budget, Standard, Premium, Luxury) and assessed cancellation rates for each price segment.
     Luxury rooms have the highest cancellations, showing they may be too expensive for some guests.
   - Meal Plan: Guests who choose Meal Plan 2 are more likely to cancel.
   - Room Type: Room Type 6 has the highest cancellations compared to other room types.
   - Parking Space Requirement: Guests who don’t need parking are more likely to cancel.
   - Special Requests: Bookings with fewer than 3 special requests tend to cancel more often.

3. Booking Trends
   - Monthly Trends: Cancellations are highest in June and July, possibly due to holiday seasons and high room rent.
   - Lead Time:Lead times were divided into four equal-sized ranges  using SQL's NTILE() function for a fair comparison.
     Bookings made over 151 days in advance are more likely to be canceled.
   - Booking Days: Combined day bookings (covering weekdays and weekends) have slightly higher cancellations.
   - Market Segment: Online bookings have more cancellations than bookings made offline or through corporate channels.

4. Revenue Impact
   - Total Revenue (Without Cancellations): $3,187,934.61, representing revenue from bookings that were not canceled.
   - Projected Revenue with 15% Fewer Cancellations: $3,472,067, which would increase revenue if cancellations were reduced.

Summary of Insights
- Highest Cancellation Groups: Key groups with higher cancellation rates include first-time guests, those booking luxury rooms, guests who do not need parking, large groups, bookings in June and July, and bookings with a long lead time.
- Potential Revenue Growth: Reducing cancellations by 15% could improve revenue by about $284,132.39.

 SQL Queries
All SQL queries used to find these insights are included in the code file.
This report and the SQL queries give helpful information on why people cancel bookings. 
Focusing on high-risk groups and offering special policies may help hotels reduce cancellations and increase revenue.
