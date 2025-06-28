# PowerBI-Healthcare-Performance

# ProCare Solutions - Financial & Cost Performance Analysis (Power BI)
This repository contains the Power BI dashboards and supporting documentation for a case study conducted for ProCare Solutions, a UK company providing staff services to major hospitals worldwide. The project aimed to analyze key financial and cost performance metrics across various healthcare projects, providing actionable insights for data-driven decision-making to the management.

📝 Project Overview
As part of a team of Data Analysts hired by ProCare Solutions, our first task was to analyze revenue and cost data for three major US hospital clients (referred to as "projects"): Sacred Heart Hospital, Cleveland Clinic, and UCLA Medical Center, from 2020-2022. The management sought to understand project performance and validate their pricing policies and project management effectiveness.

This case study focuses on empowering ProCare Solutions with clear, centralized, and fast insights into their project performance. Our team developed interactive dashboards to systematically address critical business questions related to revenue, profit, and cost structures, highlighting areas for optimization.

🎯 Objectives
# The management asked us to prepare a Profit Report that answers the following key questions:

What are the profit margins (profit/revenues) for each project in the three-year period? Which one generated more profit margin?

During the period analysis, which one of the three projects performed worse? Did one project get worsening margins or did every project maintain relatively stable ones? Present the evolution of revenues and margin for each project.

Are yearly patients and revenues positively correlated? Historically speaking, does more patients mean more revenues we can charge?

Present the evolution of costs (also in relation to revenues) and provide a detailed analysis for financial statement items.

Which are the highest costs we need to monitor for future projects? Is there a cost that negatively impacts the performance of one of the projects? If yes, which one and for which project. Provide the evolution of cost margin (costs/revenues) for the analyzed period and for each project.

# Beyond answering these questions, the objectives also included:

To develop interactive Power BI dashboards for Revenue & Profit Analysis and Cost Analysis.

To explore key insights regarding project performance, profit margins, and revenue trends.

To analyze cost structures and efficiency across projects, identifying major cost drivers.

To provide clear and actionable insights to evaluate project performance and support data-driven decision-making for ProCare Solutions.

⚙️ Methodology
# Our team's approach involved the following steps:

Data Sourcing & Preparation: Gathering and preparing the provided case study data using Power BI's Power Query Editor. This included:

Costs.csv: Detailed cost data incurred by ProCare Solutions for services provided to the three hospitals from 2020 to 2022.

Date.csv: Daily dates from 2019 to 2024, formatted correctly (using UK date formats) to be readily workable in Power BI for time intelligence.

Patients.csv: Daily patient numbers for each hospital and their operating days, used to analyze the relationship between patient numbers and revenue.

Project_Detail.csv: Short list of information regarding the projects (hospital type, State, City), prepared to be matched with other variables using a common key.

Revenues.csv: All revenues realized by ProCare Solutions relative to the services offered to the three hospitals from 2020 to 2022.

All data was meticulously transformed to ensure correct formatting and proper pairing of revenues and costs with project and financial statement item definitions.

Data Modeling: Once the data was transformed, all necessary connections were created in Power BI's Model View. Each query was connected to Revenues and Costs (though Revenues and Costs were not directly connected to each other), ensuring a coherent data model.

KPI Generation & Analysis: Meaningful Measures were created in Power BI to answer the management's questions. This involved calculating and visualizing crucial KPIs such as profit margins (profit/revenues), cost margins (costs/revenues), and revenue per patient.

# Dashboard Development: Two core interactive dashboards were designed and built in Power BI's Report View:

Revenue & Profit Analysis: Focused on profit margins for each project, revenue trends, and the relationship between patient numbers and revenue.

Cost Analysis: Detailed analysis of cost evolution, cost efficiency, and identification of key cost components.

The report was developed with a personal theme (sheet header, title, color palette), ensuring consistency in colors, fonts, and dimensions across all elements. Visuals and measures were chosen for their meaning to the end-user and aesthetic appeal.

Insight Extraction & Reporting: Systematically deriving answers to key business questions based on the insights revealed by the dashboards, presented in both the Power BI report and a short accompanying document.

📈 Key Insights & Findings
# The dashboards revealed several critical insights:

Profitability: UCLA Medical Center was identified as the most profitable project due to stable and consistent profit margins across a three-year period, while Cleveland Clinic showed the worst performance by 2022.

Revenue Drivers: Patient numbers and revenues were found not to be strongly correlated; pricing strategies and service offerings played a larger role in driving revenue. For example, the lowest patient count in 2022 generated the highest revenue, influenced by pricing and service complexity.

Cost Efficiency: Costs increased disproportionately compared to revenues over the three years, especially in 2022, highlighting a need for stricter cost control measures.

Key Cost Categories: External service providers were consistently identified as the biggest cost in every clinic for every year, requiring close monitoring for future projects.

🛠️ Technologies & Tools
Power BI: Primary tool used for dashboard development, data modeling, and visualization.

Microsoft Excel (Implied): For initial data organization and calculations before Power BI import.

🏃 How to View the Project
Download: Clone this repository or download the .pbix file.

Power BI Desktop: Ensure you have Power BI Desktop installed on your computer.

Open File: Open the downloaded .pbix file directly with Power BI Desktop.

Interact: Explore the interactive dashboards, utilize filters, and navigate between the "Revenue & Profit Analysis" and "Cost Analysis" pages to discover insights.

📞 Contact
Feel free to connect with me for any questions or collaborations:

LinkedIn: https://www.linkedin.com/in/sametcan-kandemirt/

Email: kandemirsametcan99@gmail.com
