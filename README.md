Hospitality Analysis Dashboard

A Power BI report on hotel booking performance: revenue, occupancy, RevPAR, ADR, and booking realization, broken down by city, room class, property, booking platform, and weekday vs. weekend.

Stack: Power BI, DAX, Power Query, Excel Data source: [State the source here, for example "Codebasics Resume Project Challenge dataset; hotel names changed to Tenet". Say what you built yourself versus what was provided.]

Data coverage
134,590 bookings across 25 properties in 4 cities (Delhi, Mumbai, Hyderabad, Bangalore)
Check-in dates from 1 May 2022 to 31 July 2022 (92 days)
Room classes: Standard, Elite, Premium, Presidential; property categories: Luxury and Business
Tables: bookings, Total Bookings (daily capacity and successful bookings), Hotels, Rooms, Date; Measures.xlsx documents the measures
Metric definitions (as implemented in DAX)
Metric	Definition
Revenue	Sum of revenue_realized
ADR	Revenue / total bookings (cancelled and no-show bookings are included in the count)
Occupancy %	Successful bookings / total capacity
RevPAR	Revenue / total capacity
Realisation %	1 - (cancellation % + no-show %), a booking-based measure, not a revenue-based one
DSRN	Total capacity / number of days
Key findings (May to July 2022)
Weekends outperform on occupancy, not price. Weekend occupancy was 62.6% vs. 56.0% on weekdays and RevPAR was 12% higher (7,972 vs. 7,101), while ADR was almost identical (12,725 vs. 12,683).
Luxury drives most revenue because it has more properties. Luxury accounted for 61.6% of revenue and has 16 of the 25 properties; Business properties had slightly higher RevPAR (7,498 vs. 7,256).
Realization is the same everywhere. All seven booking platforms fall between 69.8% and 70.6%, so no platform stands out.
Mumbai leads on price and revenue. ADR of 15,387 vs. 9,322 in Hyderabad, and about 39% of total revenue.
Overall: occupancy 57.9%, cancellation rate 24.8%, no-show rate 5.0%, realisation 70.2%.
Dashboard pages

Main overview with KPI cards and week-over-week changes, plus trend pages for Revenue, RevPAR, DSRN, Occupancy, ADR, and Realization.

Files
Hospitality_Analysis.pbix: report and data model
Source CSV files: bookings, total bookings, date, hotels, rooms
Measures.xlsx, Columns.xlsx: measure and column documentation
