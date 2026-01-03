#  Internet Usage Data Analysis

## Project Overview
This project involves the analysis of internet session logs to identify user behavior, network traffic patterns, and session stability. Using Python and the **Pandas** library, we transform raw CSV data into a comprehensive report with visual insights.

---
##  Key Features
* **Time Normalization**: Converts `HH:MM:SS:CC` string formats into total seconds for mathematical analysis.
* **User Aggregation**: Summarizes total upload, download, and active time per unique user.
* **Traffic Trending**: Identifies "Rush Hours" and "Quiet Hours" for the network.

---

##  Summary of Findings
Based on the analysis of `Internetusage_Beginnertask03.csv`:

* * * Top User**: **User 9** is the heaviest consumer with a total transfer of over **344,292 MB**. [Total internet usage Per user]("usage_by_user.png")
* * * Average Usage**: The average user spends approximately **18 hours and 57 minutes** online in total.
* * * Peak Traffic**: The busiest time for the network is **6:00 PM (18:00)**. [Peak traffic Graph]("hourly_traffic.png")
* * * Best Binge/Download Time**: For the fastest speeds and lowest congestion, the best time is **5:00 AM**.
* * * Disconnect Reasons**: The most frequent session break reason is **"Idle-Timeout"**, indicating that many users leave their devices connected while inactive.

---

##  Tech Stack & Requirements
This project is built using:
* **Python 3.x**
* **Pandas**: Data manipulation
* **Matplotlib**: Data visualization
