# 📊 OSAS & OSEJI WHATSAPP GROUP CHAT INSIGHTS DASHBOARD (POWER BI)

---

## 📑 Table of Contents
- [👩‍💻 Author](#-Author)
- [📱 Introduction](#-Introduction)
- [🎯 Project Objectives](Project-Objectives)
- [📊 Dataset Overview](#-dataset-overview)
- [🖥️ Dashboard Features](#-dashboard-features)
- [📸 Dashboard Preview](#-dashboard-preview)  
- [🔍 Key Insights](#-key-insights)  
- [💡 Recommendations](#-Recommendations)
- [🚀 Future Improvements](#-future-improvements)
- [🧾 How to Use](#-how-to-use)   
- [📂 Repository Contents](#-repository-contents)  
- [🙏 Acknowledgments](#-acknowledgments)  
- [📚 Conclusion](#-Conclusion)  

---

## 👩‍💻 Author
*Augustine Glory Chinyere*  
Entry-Level Data Analyst | My Journey from Raw WhatsApp Chats to Insightful Dashboards 

I am a budding data analyst passionate about turning raw data into meaningful insights through visualization and storytelling.  
As I build my skills in Power BI and data analytics, I enjoy creating dashboards that support decision-making and help me grow into a well-rounded data professional.  

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:glorealaustine@gmail.com)  
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/GlorealAustine)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/glory-chinyere-augustine)

---

## 📱 Introduction

WhatsApp groups have become a vital tool for communication, collaboration, and community building. However, group engagement often varies significantly — with a few highly active members driving most conversations while others remain passive or inactive.  
Understanding these engagement patterns is essential for improving group interaction, fostering balanced participation, and ensuring important messages reach all members.  

This project leverages data analytics and Power BI to analyze WhatsApp group chat activity. By visualizing message trends, top contributors, and participation levels, the dashboard provides actionable insights to help group admins and decision-makers make data-driven improvements that enhance overall group communication and engagement.

---

## 🎯 Project Objectives
The main objectives of this project are to:

1. *Analyze Group Engagement*  
   Identify overall group activity levels and trends to understand how members interact over time.

2. *Identify Top Contributors*  
   Highlight the most active members and measure their contribution to total group messages.

3. *Classify Member Activity Levels*  
   Categorize members into groups such as active, In-active, and No-active based on message frequency.

4. *Visualize Peak Activity Periods*  
   Determine the most active days and times for strategic communication and announcements.

5. *Provide Actionable Insights*  
   Generate data-driven recommendations to help improve participation and balance engagement across the group.

---

## 📊 Dataset Overview (2022-2025)

- **Group:** OSAS & OSEJI  
- **Period Covered by Dataset:** 2022 – 2025  
- **Analysis Carried Out:** 22nd – 23rd July 2025  
- **Total Messages:** 1,768  
- **Total Users:** 19  

## Technical Details

The dataset was exported directly from a WhatsApp group chat using the built-in *Export Chat* feature. Media files were excluded to keep the size manageable. The raw `.txt` export was later transformed into an Excel `.xlsx` file for easier analysis in Power BI.

### *Source*
- **Platform:** WhatsApp  
- **Export Method:** Native export feature (without media)  
- **Format:** `.txt` → cleaned → `.xlsx`  

### *Structure*
After cleaning and transformation, the dataset was organized into a tabular format.

**Final columns include:**
- **Date** – Full date of the message (with weekday)  
- **Time** – Exact time the message was sent  
- **User** – Name of the sender  
- **Message** – Content of the message (text only)  
- **MessageHourFormatted** – Rounded time value in `hh:00:00` format  
- **Hour** – Hour extracted as integer  
- **Hour1** – Hour in time format  

### *Dataset Size*
- **Rows (Messages):** ~1,903  
- **Time Period Covered:** 2022 – 2025  


## 📊 Sample Preview

| Date                       | Time     | User        | Message                           | MessageHourFormatted  | Hour | Hour1    |
|----------------------------|----------|--------------|----------------------------------|-----------------------|------|----------|
| Monday, 7 November 2022    | 10:42:00 | Mr. Tosin OO | ‎Mr. Tosin OO was added           | 10:00:00              | 10   | 10:00:00 |
| Thursday, 10 November 2022 | 15:01:00 | Mr. Tosin OO | I dey tell you                   | 15:00:00              | 15   | 15:00:00 |
| Friday, 11 November 2022   | 12:01:00 | Mr. Tosin OO | No ma                            | 12:00:00              | 12   | 12:00:00 |
| Saturday, 12 November 2022 | 21:32:00 | Mr. Tosin OO | I dey tell you; mercy Jay change…| 21:00:00              | 21   | 21:00:00 |
| Wednesday, 16 November 2022| 07:08:00 | Mr. Tosin OO | Correct                          | 07:00:00              | 7    | 07:00:00 |

This structured dataset forms the foundation for modeling, visualization, and deriving actionable insights through the dashboard.

---

## 🖥️ Dashboard Features
This Power BI dashboard provides a clear picture of how members engaged in the Osas & Oseji WhatsApp Group** during the analysis period:

- **Total Messages by Users** → The dashboard highlights that a few members dominated the conversation. For instance, the top three users alone contributed over 68.37%% of all messages, while others had little to no activity.  
- **Total Messages by Month & Year** → The trend charts reveal seasonal spikes, such as a sharp peak in March with over 400 messages, compared to quieter months like May and September. This shows how group activity fluctuated over time.  
- **Most Active Day & Hour** → The group’s busiest day was **25th February 2023**, which coincided with Nigeria’s General Election — a key event that drove heightened conversations and engagement. The most active time was consistently around **9:00 PM**, reflecting
    when members were most likely to engage.
- **User Activity Levels** → Members are classified into **Active, Inactive, and No Activity** groups. Only a few users were consistently active (200+ messages), while many remained mostly inactive or contributed minimally.  
- **Treemap by Time** → The treemap provides a colorful breakdown of activity across hours of the day. It shows concentrated bursts of messages at specific times (notably evenings), giving a quick view of when conversations were most lively.

---

## 📸 Dashboard Preview
![dashboard_screenshot](https://github.com/user-attachments/assets/c61410e3-880a-4b1f-be3b-83e8858d1ca4)
*Interactive Power BI dashboard showing WhatsApp group chat insights.*

---

## 🔍 Key Insights (2022–2025)

- *Most Active User:* Mr. Tosin OO  
   Consistently engaged, driving most of the group conversations.

- *Most Active Day:* 25th February 2023  
  This day recorded an unusual spike in messages due to discussions surrounding the **2023 General Election.

- *Peak Activity Hour:* 9:00 AM  
   Majority of conversations happen early in the day, indicating morning engagement habits.

- *Top 3 Users' Contribution:* 69% of total messages  
   The top 3 users dominate group interactions out of 25 total members, showing highly concentrated participation.

---

## 💡 Recommendations

Based on the insights gathered from the *2022–2025 analysis*, the following actions are recommended to improve engagement and optimize group activity:

- *Increase Engagement During Low-Activity Periods:*  
   Schedule interactive sessions or discussions during quiet periods to boost participation.

- *Recognize Top Contributors:*  
   Acknowledge highly active members through appreciation messages or special mentions to encourage consistent engagement.

- *Encourage Balanced Participation:*  
   Motivate less active members to participate by introducing group polls, surveys, or targeted conversation topics.

- *Streamline Communication:*  
   Define clear discussion topics or categories to prevent clutter and make conversations more organized.

- *Monitor Trends Regularly:*  
   Continuously track group activity using the dashboard to quickly identify declines in engagement and respond proactively.

  ---

## 🚀 Future Improvements

To enhance the dashboard and provide deeper insights, the following improvements are suggested for future versions:

- *Real-Time Data Refresh:*  
   Integrate live data connections to keep the dashboard continuously updated with the latest activity.

- *Sentiment Analysis:*  
   Analyze message tone to understand whether group conversations are positive, neutral, or negative.

- *Advanced Time Analysis:*  
   Add custom filters for comparing activity across specific time ranges, such as monthly or quarterly trends.

- *Demographic Segmentation:*  
   Include demographic data (e.g., location, department) to uncover patterns across different member groups.

- *Automated Report Sharing:*  
   Set up scheduled report exports to share key insights with stakeholders via email or shared platforms.

- *Enhanced Data Model:*  
   Optimize relationships and calculations in the data model for faster performance and scalability.

  ---

## 🧾 How to Use
  
1. *Download the Project*  
   - Clone or download this repository to your local machine.

2. *Open the Dashboard File*  
   - Locate and open the [Osas & Oseji Whatsapp Group Chat_Insights.pbix](./Osas%20&%20Oseji%20Whatsapp%20Group%20Chat_Insights.pbix) file using *Power BI Desktop*.  
   - [Download Power BI Desktop here](https://powerbi.microsoft.com/desktop/).

3. *Explore the Interactive Dashboard*  
   - View *overall message trends* to understand group activity over time.  
   - Check *user activity levels* to identify active and inactive members.  
   - Discover *most active days and hours* to see when engagement peaks.  
   - Analyze *contributions of top users* for participation insights.

4. *Access the Cleaned Dataset*  
   - Open the [Osas & Oseji Whatsapp Group Chat_File.xlsx](./Osas%20&%20Oseji%20Whatsapp%20Group%20Chat_File.xlsx) file to view the prepared dataset used in the analysis.
  
 ---

## 📂 Repository Contents
  
- `Osas & Oseji Whatsapp Group Chat_File .xlsx` → Cleaned WhatsApp chat dataset  
- `Osas & Oseji Whatsapp Group Chat_Insights.pbix` → Power BI dashboard file  
- `dashboard_screenshot.png` → Dashboard preview

---

## 🙏 Acknowledgement

This project was created as part of my *learning journey in data analytics*, where I practiced cleaning data, performing analysis, and building interactive dashboards.

Special thanks to:
- *The Incubator Hub* – for providing the opportunity and resources to learn various data analytics skills, including Power BI, SQL, and Excel. The knowledge gained from their program laid the foundation for me to independently practice and develop this project.  
- *Microsoft Power BI* – for offering a powerful tool that made it possible to visualize and analyze the data effectively.

---

## 📚 Conclusion

This project provided valuable insights into group chat dynamics over the period *2022–2025*, helping to better understand user behavior and engagement patterns.

The analysis revealed:
- The top contributors driving the majority of conversations.
- Peak activity periods, including the most active day and hour.
- Opportunities to improve participation among less active members.

By implementing the *recommendations*, the group can foster stronger engagement, maintain balanced participation, and improve communication flow.  
With planned *future improvements*, such as real-time data updates and sentiment analysis, this dashboard can evolve into an even more powerful tool for monitoring and managing group interactions effectively.
