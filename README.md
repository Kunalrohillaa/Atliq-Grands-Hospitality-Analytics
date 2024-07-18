# Atliq-Grands-Hospitality-Analytics
AtliQ Grands, a leading hospitality chain in India, faced challenges in market share and revenue for luxury/business hotels due to intense competition and suboptimal decision-making. To combat this, the managing director spearheaded a drive to fuse Business Intelligence with Data Analytics.

🏨 **Problem Statement:**
AtliQ Grands, a leading hospitality chain in India, faced challenges in market share and revenue for luxury/business hotels due to intense competition and suboptimal decision-making. To combat this, the managing director spearheaded a drive to fuse Business Intelligence with Data Analytics.

🛠 **Tools Used:**
Microsoft Power BI

🔍 **Operations Performed:**
- Data Gathering
- Data Cleaning
- Data Transformation
- Data Modeling
- DAX Implementation
- Data Visualization
- Insights Sharing

For this project, data was sourced from diverse Excel files and amalgamated in the Power Query editor using unpivot functions and parameter definitions. Following meticulous cleaning and transformation, the data was connected to Power BI, and a Star Schema Model with two fact tables was constructed for comprehensive analysis.

📊 **Data Modeling:**
- The table dim_hotels is linked to fact_bookings and fact_aggregate_bookings via the property_id.
- dim_rooms is associated with fact_bookings and fact_aggregate_bookings using room_category and room_id.
- dim_date is connected to fact_bookings and fact_aggregate_bookings through check_in_date and the date field.

⏩ **Key Metrics Utilized:**
- Revenue
- RevPAR
- ADR
- DBRN
- DSRN
- DURN
- Realization %
- Occupancy% and Cancellation %
- No Show%

🔑 **Key Insights:**
- Atliq Exotica, Mumbai, leads with the highest RevPAR of 10,640.
- Weekdays witness a significant footfall in hotels, averaging around 67%.
- Overall, AtliQ properties maintain an occupancy rate of approximately 57.87%, with AtliQ Blu boasting the highest occupancy.
- Week 29 emerged as the revenue peak.
- RT2 room category emerged as the top revenue generator at 0.55bn, followed by RT3, RT4, and RT1.

🚀 **Business Growth Recommendations:**
- Unveiled a correlation between occupancy (%) and average rating, suggesting a need to address underlying issues contributing to negative ratings.
- Identified a surge in occupancy levels during weekends, signaling an opportunity to maximize revenue during peak periods.
- ADR remains stable despite occupancy fluctuations, hinting at the potential of dynamic pricing strategies to capitalize on high occupancy rates and enhance revenue streams.

Special thanks to Codebasics for introducing me with this domain and sharing this dataset.

Excited to embark on this journey of data-driven transformation in the hospitality sector! 🌐 hashtag#PowerBI hashtag#DataAnalytics hashtag#HospitalityInsights
