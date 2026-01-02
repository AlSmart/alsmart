# Impact of Covid-19 on Air Quality 

## 🧩 Business Context
During the COVID-19 pandemic, governments introduced unprecedented lockdown measures that dramatically altered human behavior, transportation, and economic activity. 
This created a rare opportunity for decision-makers to understand how policy interventions directly influence environmental outcomes.
This project investigates the relationship between COVID-19 lockdown measures and air quality, specifically focusing on Carbon Monoxide (CO) emissions. 
By integrating pandemic data with environmental metrics, our team analyzed how shifts in human activity influenced pollution levels across various U.S. states and counties between 2019 and 2023.

👥 The Team: Team Crimson

    Jewel Atuel – Project Manager 
    Aly Sangare – Data Engineer 
    Minnie Ngo – Power BI Developer

## 🎯 Objective
  To deliver a decision-support dashboard that allows stakeholders to:
  Compare air quality before, during, and after lockdowns
  Understand how different cities responded to policy changes
  Support future decisions around transportation, urban planning, and environmental regulation


## 🛠️ My Role & Contribution
  Business Intelligence Developer / Data Engineer
  
  I was responsible for:
  
    - Designing the data pipeline that transformed raw environmental and COVID datasets into analysis-ready data
    - Structuring a centralized data model to support consistent reporting
    - Enabling Power BI dashboards that allowed stakeholders to explore trends without technical expertise
    - Ensuring insights were accurate, reliable, and easy to interpret

    The data was processed through a multi-tier architecture:
    Import Tier: Raw .csv files were ingested into a SQL Server environment.
    Data Cleaning & Transformation: Utilized stored procedures (e.g., dbo.sp_DimDate, dbo.sp_FactCovid) to clean and structure the data into a Star Schema.
    Data Warehouse: Hosted on Azure, consisting of dedicated Fact and Dimension tables for countries, states, dates, CO levels, and COVID-19 statistics.

    A semantic model was built to enable deep-dive analysis:
    Star Schema: Fact tables (vFactCovid, vFactCarbone) linked to multiple dimensions (vDimDate, vDimStates, vDimCounty).
    Key Metrics: Calculated DAX measures for Year-Over-Year (YOY) changes in confirmed cases and deaths

    
## 📂 Data Used
  Carbon Monoxide (CO) Air Quality Index (AQI) data (2019–2023) from the *U.S. Environmental Protection Agency*
  
  COVID-19 case data to align air quality changes with pandemic phases: *Bing COVID-19 Dataset.*
  
  City-level data for major urban areas, including New York, Los Angeles, and Washington State
  

## 📈 Key Insights for Decision Makers
    The "Lockdown Effect" on Air Quality: 
        A clear, immediate improvement in air quality occurred at the pandemic's onset, specifically an improvement in CO AQI during March 2020.
    Regional Divergence: Environmental impact was not uniform across the U.S.:
        New York: Experienced a sharp initial decrease in CO, followed by a rise as activity resumed.
        California (Los Angeles) & Washington (King County): 
        Showed more sustained reductions in average CO emissions even as COVID-19 cases climbed throughout the year.
    Behavioral vs. Viral Correlation: Air quality gains were tied to human activity (lockdown restrictions) rather than the virus itself. 
    As restrictions loosened in 2021–2023, CO emissions returned to normal pre-pandemic levels despite COVID-19 cases remaining high or increasing.
    Sustainability Gap: 
    The data suggests that without permanent policy or behavioral shifts, the environmental benefits of reduced human activity are temporary and quickly reversible


## 🧭 Business Impact
    This project demonstrates that:
        Short-term policy interventions can improve environmental outcomes
        Temporary restrictions alone are not enough for long-term improvement
        Cities need structural changes (transportation, remote work, emissions controls) to sustain air quality gains

    For decision-makers, this provides evidence to:
        Evaluate the real environmental impact of large-scale policies
        Design smarter, targeted interventions rather than broad shutdowns
        Support data-backed urban and environmental planning strategies

## 📊 Reporting & Visualization (Dashboard preview)
To support executive decision-making, build interactive:

    The final Power BI dashboard includes:
    Executive Summary: High-level metrics for Median Daily AQI and total COVID-19 cases (reaching over 1.7 billion confirmed cases in the analyzed period).

    Comparative Analysis: Side-by-side trends of CO concentrations vs. COVID-19 infection waves.

    Drill-through Reports: Detailed table views for specific counties, such as Los Angeles, showing daily statistics and percentage of state impact.

Designed visuals to answer “What changed?” and “Why does it matter?” in seconds


## 🧠 Skills Demonstrated
    Business Intelligence Development

    Data Modeling for Analytics

    Decision-Oriented Dashboard Design

    Translating Data into Executive Insights

    Cross-Domain Analysis (Public Health & Environment)

<!--
**AlSmart/alsmart** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
