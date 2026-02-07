🏥 Historical Epidemiology Analysis: Stockholm Cholera Outbreak (1853)

📌 Project Overview
This project reconstructs and analyzes the tragic 1853 Cholera outbreak in Stockholm, Sweden. By examining a dataset of 248 documented deaths, I utilized Power BI to identify mortality patterns across gender, age, and profession. This analysis mirrors the famous work of John Snow, using data to visualize the devastating impact of the disease over a critical four-month period.

📊 Key Insights
Demographic Impact: The outbreak saw a slightly higher mortality rate among females (130 deaths, 52.4%) compared to males (118 deaths, 47.6%).

Age Sensitivity: The average age of death was 34, but the data shows extreme vulnerability at both ends of the spectrum, with victims ranging from infants (age 0) to the elderly (age 86).

Peak Crisis Period: September was the deadliest month by a significant margin, accounting for 183 of the 248 total deaths, followed by a sharp decline in October.

Socio-Economic Trends: Analysis of victims' professions shows a high concentration of deaths among Workers, Carpenters, and Maids, suggesting that living conditions and proximity to contaminated sources played a vital role in transmission.

🛠️ Technical Toolkit
Healthcare Data Visualization: Designed an intuitive dashboard in Power BI using high-contrast visuals to clearly distinguish between age categories (Children, Adults, Aged, Senior).

Advanced Visuals:

Waterfall Charts: Used to visualize the decrease in deaths from Q3 to Q4.

Donut Charts: For gender-based mortality distribution.

Area Charts: To show the "burn-out" phase of the epidemic over time.

Demographic Segmentation: Created custom age groups to better understand which life stages were most at risk.

Historical Data ETL: Cleaned and structured 19th-century death records into a modern star schema for efficient reporting.

📂 Repository Structure

├── .Report/                   # Power BI visual metadata

├── .SemanticModel/            # Data relationships and demographic DAX measures

├── Stockholm_1853_Data/       # Historical records in CSV format

├── Cholera-Outbreak-1853.pbip # Main Power BI Project file

└── README.md                  # Project documentation

<img width="656" height="368" alt="Cholera Outbreak, Stockholm, 1853 Analysis" src="https://github.com/user-attachments/assets/3b25674e-8664-4294-b588-f79e26f5e25e" />


