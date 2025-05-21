# Submarine Cable Data Exploration

**Project Overview**
This project aims to analyze and visualize the growth of submarine cables built over the past 15 years (2010–2024) and their regional distribution. The goal was to retrieve data on the number of submarine cables becoming operational each year, analyze their geographic distribution, and visualize these findings using Datawrapper. This project serves as an entry point into deeper research on submarine cable ownership, distribution, and geopolitical implications.

**Tools & Packages Used**

- Python for data retrieval and processing
- Requests to fetch data from the API
- Pandas for data cleaning and manipulation
- Datawrapper for interactive visualizations
- HTML & CSS to build a basic website for presentation

**Data Collection**

- Annual Submarine Cable Construction
The primary data source was a hidden API powering the Submarine Cable Map. By directly querying API endpoints, I was able to extract cable data for each year, normalize it, and prepare it for visualization. This allowed me to track the dramatic rise in submarine cable construction, especially the acceleration since 2015.
- Regional Distribution Analysis
For the regional distribution analysis, I manually compiled data from two primary sources:
  - TeleGeography's Submarine Cable Map - Provided information on cable routes and landing points
  - ITU's Infrastructure Connectivity Map (BBmaps) - Supplemented with additional data on cable lengths

The regional dataset required manual processing to classify cables into regional categories (Trans-Atlantic, Trans-Pacific, Intra-Asia, Europe-Asia-Africa, Latin America & Caribbean, and Australia & Oceania) and calculate metrics like total cable length per region and the number of distinct cable systems.

**Visualizations**

- 15-Year Growth Chart
The column chart visualizes the number of new submarine cables deployed each year from 2010 to 2024. The visualization highlights the significant acceleration in deployment since 2015, coinciding with the rise of cloud computing and increasing global data demands.
- Regional Distribution Pie Chart
The pie chart shows the distribution of submarine cables by region, revealing which geographic areas have the greatest concentration of this critical infrastructure.

**Key Findings**

The analysis revealed several  patterns:
- There has been a dramatic increase in submarine cable construction since 2015, reflecting growing demand for global connectivity
- Regional distribution shows important disparities, with Trans-Pacific routes having the most extensive infrastructure by distance
- Intra-Asia has the highest number of individual cable systems, reflecting the region's population density and economic importance

**Future Development & Research**

Next steps for this project could look into the geopolitical, technological, and corporate implications of submarine cables. Future directions include:
- Exploring more hidden APIs for additional data retrieval
- Analyzing geographic distributions in greater detail
- Investigating ownership and control patterns
- Examining the relationship between cable infrastructure and digital sovereignty
- Studying the vulnerability of submarine cable networks to damage and disruption
