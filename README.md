# Task-Insights-and-Workload-Overview-Analysis-for-DEN

# About Our Project

The DASSA Hackathon 2024, organized by CU Boulder, challenges participants to solve real-world data problems. This year, Denver International Airport (DEN), one of the busiest and largest airports in the United States, provided a complex problem statement aimed at optimizing their data analytics process. [More about the DASSA Hackathon 2024](https://inquisitive-roast-b08.notion.site/DaSSA-Hackathon-2024-134e84f7d0ec80b38e9ecb637d5a4c96).

**Problem Statement**  
Handling millions of passengers and cargo efficiently requires robust data systems. DEN uses ServiceNow for enhancement requests and Azure DevOps (ADO) for development tracking. Our task was to create an integrated solution to provide real-time insights and improve communication between these systems. [View the problem statement here](https://inquisitive-roast-b08.notion.site/Challenge-1-134e84f7d0ec80e7bfeef0066ea5e643).

## Data Preparation and Cleaning
1. We combined the ServiceNow and Azure DevOps datasets using the common 'Status' values, merging relevant fields for analysis.
2. Redundant columns such as "Enhancement Number," "Azure DevOps ID," "Customer," and "Developer" were removed to simplify the data.
3. We created a new "Manager" column to assign tasks dynamically and used a function to compute due dates based on 'Level of Effort,' 'Priority,' and 'Updated Time.'
4. NLP techniques were applied to extract key phrases for the 'Short Description,' and missing values were filled strategically using logical imputation methods.
5. New columns like "Cross Team Dependency" and "Stakeholder Group" were added for deeper analysis and collaboration insights.

## PowerBI Data Visualizations

![PowerBI Dashboard for ServiceNow and Azure DevOps Integration](https://github.com/HarishNandhan/Task-Insights-and-Workload-Overview-Analysis-for-DEN/blob/main/Solution%20screenshots/Screenshot%202024-11-17%20214951.png)

1. **Workload Distribution**: Stacked bar charts and heatmaps displayed real-time workload distribution among developers, highlighting areas of potential overload.
2. **Level of Efforts Overview**: A categorical bar chart classified requests as Easy, Medium, or Hard, aiding in resource management and prioritization.
3. **Request Counts by Customers**: A clear view of demand patterns, identifying which customers submit the most requests, helping prioritize support.
4. **Project Timeline**: A combined line and bar chart visualized request trends over time, making it easy to track progress and anticipate upcoming work.

Our dashboard provides a comprehensive and interactive experience, ensuring stakeholders have the data-driven insights they need for strategic decision-making.

## Contributors

I'd like to acknowledge the valuable contributions of my team members:

- **[Rissi Kumar Prabhakaran](https://github.com/RISSIKUMARP/RISSIKUMARP)**
- **[Dnyaneshwari Rakshe](https://github.com/dnyaneshwari2502)**
- **[Pramod Kumar](https://github.com/pramodkumar26)**


Feel free to check out our GitHub profiles to see more of our projects and contributions!

