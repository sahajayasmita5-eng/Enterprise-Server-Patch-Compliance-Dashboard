\# Enterprise Server Patch Compliance Dashboard



\## Overview



The \*\*Enterprise Server Patch Compliance Dashboard\*\* is an interactive Power BI project designed to monitor and analyze Linux server patch compliance across an enterprise infrastructure environment.



This dashboard enables infrastructure and operations teams to monitor patching status, identify compliance gaps, and analyze server distribution across multiple operational dimensions such as environments, data centers, applications, ownership, operating systems, and patch cycles.



The project was inspired by real enterprise infrastructure reporting scenarios and demonstrates how operational data can be transformed into actionable business insights.



\---



\# Problem Statement



Managing patch compliance across hundreds of enterprise servers is challenging due to the large number of environments, operating systems, applications, and exception categories.



Infrastructure teams need a centralized dashboard to answer questions such as:



\* How many servers are eligible for patching?

\* Which servers are End-of-Life (EOL)?

\* Which servers are restricted from patching?

\* How many exceptions exist?

\* Which environments contain the highest number of servers?

\* Which operating system versions are most common?

\* How many servers were patched during each monthly patch cycle?

\* What is the overall patch compliance percentage?



This dashboard provides a single source of truth for infrastructure monitoring and patch compliance reporting.



\---



\# Dashboard Features



\* Interactive KPI cards

\* Patch Compliance Percentage

\* Patch Month filtering

\* Environment filtering

\* Data Center filtering

\* Application filtering

\* Dynamic cross-filtering across visuals

\* Dark-themed enterprise dashboard design



\---



\# Key Performance Indicators (KPIs)



\* Servers in Selection

\* Eligible Servers

\* EOL Servers

\* Restricted Servers

\* Exceptions

\* Patch Compliance %



\---



\# Dashboard Visualizations



\### Patchable Distribution



Displays the distribution of servers based on their patch eligibility.



\### Environment Distribution



Shows server count across Production, Development, Testing, and Disaster Recovery environments.



\### Internal vs External Ownership



Compares internally managed and externally managed infrastructure.



\### OS Version Distribution



Displays the distribution of Linux operating system versions across servers.



\---



\# Technologies Used



\* Microsoft Power BI

\* Power Query

\* DAX

\* Data Modeling



\---



\# DAX Concepts Used



\* CALCULATE()

\* COUNTROWS()

\* DIVIDE()

\* IF()

\* FORMAT()

\* MONTH()

\* ISBLANK()



\---



\# Business Insights



The dashboard enables stakeholders to:



\* Monitor enterprise patch compliance

\* Identify infrastructure requiring patching

\* Track monthly patch deployment progress

\* Analyze server distribution across environments

\* Understand operating system adoption

\* Support infrastructure planning and compliance reporting



\---



\# Project Structure



```

Enterprise-Server-Patch-Compliance-Dashboard

│

├── Enterprise Server Patch Compliance Dashboard.pbix

├── dataset.xlsx

├── Dashboard Screenshot.png

├── README.md

```



\---



\# Future Enhancements



\* Historical compliance trend analysis

\* Executive summary page

\* Drill-through reports

\* Row-Level Security (RLS)

\* Scheduled data refresh

\* Power BI Service deployment



\---



\# About Me



I am an Infrastructure Engineer transitioning into Data Analytics. This project combines my Linux infrastructure domain knowledge with Power BI, DAX, and data visualization skills to solve a realistic enterprise reporting problem.



