# Water Access and Sanitation Conditions in Kakuma
Capstone Analysis Using Python & Tableau

## Project Title



Water Access and Sanitation Conditions in Kakuma Refugee Settlement


## Business Problem



Humanitarian organizations operating in Kakuma face challenges in ensuring equitable access to safe, adequate water and proper sanitation. Existing conditions—including long distances to water sources, low water supply per person, and sanitation infrastructure gaps—impact health, hygiene, and overall wellbeing of residents.
A data-driven approach is needed to identify priority zones and guide resource allocation.


## Business Understanding



The project aims to help humanitarian actors (UNHCR, NGOs, WASH clusters) answer key operational questions:

Which zones experience the longest distances to water?

Are households receiving the Sphere standard (20L/person/day)?

Which zones have the worst sanitation conditions?

How do water access indicators correlate with sanitation status?

Where should interventions be prioritized?

These insights support evidence-based planning and decision-making.


## Project Objectives



Analyze water access indicators, including average distance, collection time, and liters per person per day.

Evaluate compliance with the 20L humanitarian minimum water standard.

Assess sanitation conditions across Kakuma zones.

Identify geospatial patterns in water and sanitation disparities.




## Criterion for Success


Water access indicators (distance, liters/person/day, and time burden) are correctly analyzed, cleaned, and visualized, with clear comparisons across zones — showing, for example, that Kalobeyei and Kakuma 2 have the longest average distances (>1.3 km) and that the overall daily time burden averages 3 hours.

Household compliance with the 20L/person/day humanitarian water standard is accurately evaluated and clearly quantified, showing that 0% of households across all zones meet the Sphere water standard.

Sanitation conditions are correctly assessed, categorized, and mapped, with Kalobeyei, Kakuma 2, and Kakuma 1 highlighted as zones with inadequate sanitation, while all remaining zones display moderate to better sanitation conditions.

Geospatial and statistical patterns between water access and sanitation outcomes are clearly identified, demonstrating that zones with longer water collection distances and lower liters/person/day consistently overlap with zones having poor sanitation, confirming combined WASH vulnerabilities.


 ## Data Understanding

The dataset used in this analysis comes from field-level water and sanitation assessment records collected within the Kakuma Refugee Settlement for humanitarian monitoring and evaluation. It contains household-level data covering multiple zones within Kakuma and Kalobeyei.

Data Contents

The dataset includes key variables required to assess water access and sanitation conditions:

Distance to water source (km)

Daily time spent collecting water (hours)

Liters of water available per person per day

Type of water source (borehole, tap stand, trucked water, river, etc.)

Sanitation score and type of sanitation facility

Household size and geographical zone

These data points allow for detailed analysis of humanitarian service gaps and zone-level disparities.

Data Cleaning and Preparation

To ensure accuracy and consistency, the following preprocessing steps were applied:

Missing values handled appropriately:

Categorical → filled with "unknown"

Numerical → median imputation

Standardized zone names and sanitation categories

Feature engineering introduced:

Water sufficiency flag (≥ 20 L/person/day)

Distance bins for analysis

Removed inconsistencies and ensured format uniformity (text standardization, numeric corrections)

Dataset Purpose and Use

The dataset was provided specifically for this capstone analysis, enabling:

Evaluation of compliance with humanitarian water standards

Identification of zones with poor sanitation

Understanding relationships between water access and sanitation outcomes

Production of dashboards for humanitarian decision-making

Ethical Note

The dataset contains no personally identifiable information (PII).
All entries were anonymized and aggregated for safe and ethical analysis.


##Business Requirements (business_requirements.txt)

TOOLS

pandas
numpy
matplotlib
seaborn
plotly
jupyter
notebook
tableau

This analysis must satisfy the following:

Provide clear metrics on water availability and sanitation by zone.

Identify zones below humanitarian standards.

Visualize data using maps, charts, and summary tables.

Support resource prioritization for WASH partners.

Produce insights understandable by non-technical teams.

## ploratory Data Analysis (EDA) Summary
Water Access



Average collection distance: 1.2 km

Kalobeyei & Kakuma 2 have the longest distances (>1.3 km)

Average collection time: 3 hours per day

Water Sufficiency

0% of households meet the 20L per person per day Sphere standard

Lowest sufficiency detected in Kalobeyei and Kakuma 2

Sanitation Conditions

Severe disparities across zones

Some zones show high open defecation rates

Poor sanitation correlates with:

Higher household density

Longer distance to water

Fewer improved water sources

Water Source Distribution

Boreholes are most common

Tap stands & water trucking provide highest water volumes

Rivers/unimproved sources correlate with lowest sanitation scores

Key Correlation

Better water access is associated with better sanitation conditions, indicating the need for integrated interventions.

## Conclusions



Kakuma faces significant gaps in both water access and sanitation.

No households meet recommended water standards, highlighting a humanitarian emergency.

Zones such as Kalobeyei, Kakuma 1, and Kakuma 2 require immediate attention.

Poor sanitation and poor water access often occur together, worsening health risks.

## Recommendations



Expand boreholes, piped water systems, and tap stands in underserved zones.

Increase water trucking temporarily to bridge supply gaps.

Improve sanitation infrastructure, prioritizing latrine construction.

Implement hygiene education programs linked to improved water access.

Establish routine monitoring systems integrating water & sanitation indicators.

Conduct future analysis with:

Time-series datasets

Health outcome correlations

Seasonal supply variations

 ## Non-Technical Summary (Simple Language)

 

This project studied how people in Kakuma refugee camp get water and use sanitation facilities. The data showed:

People walk far distances to get water—over 1 km on average.

Nobody receives the minimum water amount recommended for daily needs.

Some areas have very poor toilets or none at all.

Areas with bad water access also tend to have bad sanitation.

In simple terms:
Kakuma needs more clean water sources and better toilets. Improving both together will help keep people healthier and reduce disease.

## Author

Ater Deng Mayen

Data Analyst | Python, Excel, Tableau

aterdeng88@gmail.com


