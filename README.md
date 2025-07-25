# PowerBI-Tweet-Dashboard
**Task 1: Develop a chart that displays tweets with the highest engagement rates (top 10%). Include only those tweets that have received more than 50 likes and were posted on weekdays and this graph should work only between 3PM IST to 5 PM IST apart from that time we should not show this graph in dashboard itself as well as tweet character count should be below 30.**

Data Cleaning & Transformation**

**Description:**
Cleaned raw tweet data by removing invalid timestamps and null values.
Converted UTC timestamps to IST using a calculated column.
Created new columns like:
EngagementRate_Column (engagements ÷ impressions)
Word_Count (number of words in the tweet)
Post_Hour (hour of tweet in IST)
Is_Odd_Date (if tweet date is odd)
Classified tweets into High or Normal engagement using a 5% threshold.

# Filtered dataset for:
Replies > 10
Word Count > 50
Odd Date
Time between 6 PM – 11 PM IST

**✅ Task 2: Plot a scatter chart to analyse the relationship between media engagements and media views for tweets that received more than 10 replies. Highlight tweets with an engagement rate above 5% and this graph should work only between 6PM IST to 11 PM IST apart from that time we should not show this graph in dashboard itself and the tweet date should be odd number as well as tweet word count be above 50.**



**Description:**
Built a scatter chart to visualize the relationship between:
Media Views (X-axis)
Media Engagements (Y-axis)

Bubble size mapped to Engagement Rate
Added High_Engagement as legend
Enabled interaction filters to restrict chart visibility to:
High engagement tweets
Replies > 10
Post time between 6–11 PM IST
Word Count > 50
Odd-numbered dates

**✅ Task 3: Create a dual-axis chart that shows the number of media views and media engagements by the day of the week for the last quarter. Highlight days with significant spikes in media interactions. this graph should work only between 3PM IST to 5 PM IST and 7 AM to 11AM apart from that time we should not show this graph in dashboard itself and the tweet impression should be even number and tweet date should be odd number as well as tweet character count should be above 30 and need to remove tweet word which has letter 'H'.**

**Description:**
Designed a dark-themed Power BI dashboard with:
KPI Cards (Tweet Count, Media Views, Engagements, Replies, Word Count)

**Title: “Media Engagement vs Views (Filtered by High Engagement, Replies, Time & Word Count)”**

**Slicers for**: 1.Word Count
                 2.Post Hour
                3.Is_Odd_Date dropdown

Made dashboard fully interactive using visual slicers instead of static filters
Added formatting for tooltips (Engagement %, Replies).

