# Customer Support & Sales Operations Dashboard
A Power BI project on the performance of a call center dataset.

![overview of dashboard](https://github.com/M0Data/Call-center-Dashboard/blob/main/call%20center.PNG?raw=true)

## Overview
This call center dashboard is designed to monitor and evaluate the performance of a call center, providing actionable insights into key metrics such as call volume, agent performance, customer satisfaction, and operational efficiency.

The dashboard equips managers and stakeholders with a clear view of daily operations, enabling data-driven decisions to enhance customer service quality and improve team performance.

---

## Key Features
The dashboard is divided into several key sections that focus on different aspects of call center operations:

### 1. **Overall Summary**
At the top, the dashboard displays key performance indicators (KPIs) for a high-level overview of the call center’s performance:
- **Total Calls:** The total number of calls the call centre handles (5K in this case).
- **Number of Agents:** The total number of active agents (8).
- **Average Speed of Answer:** The average time (in seconds) it takes for agents to answer calls (68 seconds).
- **Average Talk Duration:** The average length of calls (225 seconds).
- **Rate of Answered Calls:** The percentage of incoming calls answered by agents (81%).
- **Rate of Resolved Calls:** The percentage of calls resolved successfully during the interaction (73%).
- **Average Satisfaction Rate:** The average customer satisfaction score (on a scale of 1–5).

### 2. **Call Volume Analysis**
This section provides insights into the volume of calls received:
- **Call Volume by Date:** A line chart visualizing call volume trends over time, showing fluctuations such as reduced volumes in February and March.
- **Calls Made by Each Agent:** This is a bar chart comparing the number of calls handled by each agent. For example, Agent Jim managed the most calls (666), while Stewart handled the fewest (592).
- **Calls Based on Each Topic:** This is a breakdown of calls categorized by topics such as "Admin Support," "Payment Related," and "Streaming." Streaming and Payment-Related topics received the highest number of calls (1,032 and 1,021, respectively).

### 3. **Agent Performance Analysis**
This segment evaluates individual agent performance:
**Resolved Rate of Each Agent:** This chart Highlights resolution rates, with Joe and Stewart leading at 74% and Becky lags slightly at 72%.
- **Average Talk Duration of Each Agent:** Compares average call durations. Dan has the longest duration (281 seconds), while Jim has the shortest (219 seconds).
- **Average Speed of Answer of Each Agent:** Shows efficiency in response times, with Greg answering calls the fastest (63 seconds) and Martha the slowest (73 seconds).

### 4. **Call Handling Efficiency Analysis**
Focused on operational efficiency, this section includes:
- **Average Speed of Answer by Date:** Displays trends in answering speed, showing slight improvements over time.
- **Resolution Rate by Average Talk Duration:** Examines the relationship between talk duration and resolution rates, peaking at moderate durations (~250–300 seconds).
- **Rate of Unanswered Calls by Time Interval:** Highlights time intervals with the highest unanswered call rates, such as 6 AM–6 PM (19%).

### 5. **Topic-Based Analysis**
This section assesses performance based on specific topics:
- **Average Satisfaction Rate of Each Topic:** A bar chart showing satisfaction rates for topics like Admin Support and Payment Issues.
- **Resolution Rate of Each Topic:** Highlights topics with above-average resolution rates, such as Streaming and Contract Issues (74%).

---

## Insights Gained
From this dashboard, several key insights can be derived:
1. **Agent-Specific Recommendations:** Agents with lower resolution rates or slower answering times (e.g., Martha, Becky) could benefit from targeted coaching.
2. **Operational Adjustments:** Higher unanswered call rates during mornings and afternoons (19%) suggest the need for optimized staffing.
3. **Process Improvements:** Topics like Streaming and Payment-Related show slightly lower resolution rates (~72%), requiring targeted training.
4. **Customer Experience Focus:** Enhancing satisfaction rates for specific topics can lead to improved customer retention.

---

## Technical Details
- **Tool Used:** Power BI  
- **Data Sources:** Sample call center data, including metrics such as call timestamps, agent details, call topics, and customer feedback.  
- **Filters:** Interactive slicers allow users to filter data by:
  - **Topic:** Admin Support, Payment Related, Streaming, Technical Support, etc.
  - **Agent:** Specific agents such as Becky, Dan, Diane, etc.
  - **Time Interval:** Morning (6 AM–Noon), Afternoon (Noon–6 PM), and Evening (6 PM–Midnight).

---

## How to Use
1. **Clone the Repository:** Download the repository to access the Power BI file.  
2. **Open the Dashboard:** Use Power BI Desktop to open the `.pbix` file and explore the dashboard.  
3. **Customize Filters:** Use slicers to filter data by topic, agent, or time interval to analyze specific trends.  

---

## Future Enhancements
- **Predictive Analytics:** Add forecasting capabilities for call volumes and agent workload.  
- **Drill-Down Capabilities:** Enable granular views for agent performance and specific time intervals.  
- **Real-Time Data Integration:** Connect the dashboard to live data sources for real-time monitoring.  

---

## Conclusion
This Call Center Dashboard is a powerful tool for monitoring and optimizing call center operations. Providing detailed insights into key metrics empowers stakeholders to make informed decisions that improve efficiency and customer satisfaction.

Feel free to explore the repository and provide feedback. Collaboration and suggestions are always welcome!
