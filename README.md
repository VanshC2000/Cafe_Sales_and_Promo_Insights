# Cafe_Sales_and_Promo_Insights

### Dashboard Images
##### Page 1: Performance Snapshot: A high-level overview of sales activity, customer spending patterns, and daily revenue trends.
![image](https://github.com/user-attachments/assets/66a972aa-6764-433c-9e36-9149dd20eac3)

##### Page 2: The Impact of Incentives: An overview of offer performance, with completion rates and engagement across customer segments.
![image](https://github.com/user-attachments/assets/e400c5e7-b2b7-4699-b469-76a14f4593bc)

##### Page 3: Channel Effectiveness: An analysis of how individual and combined marketing channels impacted offer engagement.
![image](https://github.com/user-attachments/assets/22bcba3e-83a0-4ae4-854e-064ef9ef3225)

---

### Project Objective and Overview
This Power BI dashboard presents a 30-day analysis of customer engagement with promotional offers at Maven Café. It explores how offers were delivered, viewed, and completed across different marketing channels, alongside general customer behaviour over the month, and trends in overall sales performance. The primary goal of this project is to help marketing and strategy teams at Maven Café understand which channels and offer types drive customer action, and how these campaigns align with broader transaction behavior. These insights can inform future campaign planning and can help improve offer targeting and general customer engagement.

---

### Description of the Dataset
The dataset was fictionalized and sourced from [Maven Analytics](https://mavenanalytics.io/challenges/maven-rewards-challenge/404c6060-60eb-400f-9bce-c3b9f97e9d5a). It captures an unknown 30-day period of customer activity. For the purpose of this analysis, the time frame has been assumed to be the month of April, 2025.
The dataset contains three tables:
- offers: Contains metadata for each promotional offer, including type (BOGO, discount, or informational), minimum spending requirement (difficulty), potential reward, offer duration, and the marketing channels through which it was sent.
- customers: Includes demographic information such as gender, age, income, and the date each customer became a member of Maven Café’s loyalty program.
- events: Tracks customer activity, including transactions and offer-related events (received, viewed, completed), along with timestamps and associated offer or transaction values.

The tables are connected through customer_id and offer_id. This allows for analysis of customer behavior, offer performance, and marketing channel impact throughout the campaign period.

---

### Key Findings
For a complete breakdown of all insights and recommendations, please refer to the detailed project report available in the repository files.
- Average daily revenue increased significantly over the month, with the 5-day moving average rising by 39% from the end of week one to the final day.
- Sales on Sundays and Mondays were consistently low during the first two weeks but showed strong improvement in the latter half of the month. This trend should be closely monitored.
- Offers were only distributed on Tuesdays and Fridays, and these days saw the highest offer engagement. To boost engagement, periodic offer reminders should be introduced to encourage action beyond the initial offer releases.
- Younger customers (<35) and lower-income customers (<$70K) show significantly lower offer-linked transaction rates.
- Channel combinations involving social media yielded the highest offer viewing rates, despite only 59.85% of total offers being distributed through this channel. Thus, there is a strong opportunity to expand social media use in future campaigns.

