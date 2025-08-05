# Air-Purifier-Product-Market-Fit
This dashboard explores the AQI (Air Quality Index), impact of EV's and health issues associated with poor AQI in Indian cities. The dashboard is part of a market research dashboard for a dummy company seeking to develop their own Air Purifiers in India. It aids in identifying top markets, key pollutants to target and which cities to start with

This dashboard was part of the Resume Project Challenge by Codebasics (https://codebasics.io/challenges/codebasics-resume-project-challenge/20). Data was provided by Dataful

# Project Overview
Pollution has become a global crisis and is leading to severe climate and health effects. One partiular country quoted for having the most polluted areas is India. This project analyses the state of India's Air Quality Index (AQI). An attempt is made to understand the AQI of different states or areas, the top pollutants, impact of e-vehciles and the diseases thsi may be leading to.

The goal is to understand the pollution crisis in India in order to recommend an air purifier for a company who seeks to set up in India

# Data sources
1. AQI, Vehicles and disease data obtained from Dataful
2. Search index for air purifier - Google Trends
3. Income and population densities - DataCommons (By Google)

# Dashboard and analysis
*Note: Only screenshots of the dashboard are provided below. Interactive dashboard can be accessed using the link below (Alongside data files):*
https://drive.google.com/drive/folders/1DDQbpYr_CdUB26uw5_D96eWQ17dIKa4-?usp=sharing

## 1. Page 1 - Overview
<img width="635" height="355" alt="Page 1 - Overview" src="https://github.com/user-attachments/assets/a7174c6d-8fd1-4256-a5cb-25964acf6841" />

**Key Insights**

•	AQI patterns are highly seasonal – Peaks occur in November/December attributable to the crop burning season by farmers which result in high levels of PM10 and PM2.5 pollutants.

•	This is further enhanced by the occurrence of Diwali. While the peak is November/December, the rise starts slightly earlier and this could be due to the fireworks pollution during October and November.

•	On average, air is cleanest (lowest AQI) on Mondays. This could be because of reduced car usage over the weekends and therefore there is a delayed impact on the AQI. Lower car usage on weekends results in less pollution and this means better AQI on Monday

•	Metropolitan cities of India have seen a significant worsening of AQI in 2025 with average AQI shooting up to 120.67 from just 104.33 in the previous year (Filtered to metropolitan cities)

•	PM10 and PM2.5 are the 2 most common pollutants in all states of India. This is followed by Carbon Monoxide (design of new air purifiers should be done with these pollutants in mind)

## 2. Page 2 - Vehicle Analysis
<img width="635" height="358" alt="Page 2- Vehicle Analysis" src="https://github.com/user-attachments/assets/baebe0d5-2060-48ef-a7e9-e3a31d2d9ef0" />

**Key Insights**

•	Although there is a rise in EV’s in India, the AQI has not seen a significant improvement.

•	Selecting the pure Electric class to highlight the number of electric vehicles across the ‘Vehicles by Class’ visual shows us that EV uptake is higher for motorcycles as opposed to cars which might be the reason for the lack of AQI improvement.

•	Larger states show much higher EV adoption but also have higher AQI’s. This shows that the EV adoption is more likely due to higher incomes and not necessarily pollution driven.

## 3. Page 3 - Disease Analysis
<img width="628" height="357" alt="Page 3 - Disease Analysis" src="https://github.com/user-attachments/assets/29868e75-2133-4d61-b3d3-6a8e2055f0a6" />

**Key Insights**

•	Food poisoning and Diarrhoea were seen as the main diseases across all states

•	Although not formally proven, Chickenpox, Measles and Dengue seem to be related with the quality of Air. A week before these diseases broke out, the areas where the disease broke out had recorded some of the highest/worst AQI values.

## 4. Page 4 - Market Analysis
<img width="634" height="358" alt="Page 4 - Market Analysis" src="https://github.com/user-attachments/assets/7c44ceba-63b0-4b6c-9ade-32488753fa22" />


**Key Insights**

•	Searches for air purifiers are concurrent with the AQI peaks in India (data for searches was sourced from Google Trends). This helps us identify times when key marketing content should be focused.

•	Byrnihat, Delhi, Greater Noida, Begusarai and Ganganagar show almost irreversible AQI degradation with the percentage of days recorded as bad exceeding 45% over 4 years. These become key target areas for selling the purifiers.

•	Population and AQI have no direct correlation – higher population does not always mean worse AQI. This means that it is not necessary for the government to only direct counter-pollution measures to populous cities.

•	Risk scores (AQI * Median Income * Population Density, all divided by 1000000) of Delhi is extremely critical, with Puducherry, Uttar Pradesh and Haryana being dangerously high as well. 

# Additional Market Analysis

1. It was reported that 90% of Indians know about AQI and air pollution but lack knowledge on its causes and effects, which might be the reason for poor AQI policy implementation (https://www.thehindu.com/news/cities/Delhi/90-citizens-aware-of-air-pollution-but-lack-awareness-of-causes-and-impact/article25528325.ece). This creates a unique opportunity to bundle air purifier ads with informative ads for greater engagement.
2. Top competitors include: Dyson, Phillips, Honeywell, Xiaomi. The Highest Selling type of Air filter is the type V which has HEPA + Carbon + Ionizer + UV Light + Electrostatic capabilities. Almost all Air Filters have HEPA filters which is the market expected to grow the most. However, HEPA filters are unable to work on Carbon Monoxide - the design of the new air purifier should incorporate this.
3. Key gaps with current purifiers include:

  a. They have app functionality but lack detection of pollutants features which leads to higher energy consumption. Adjusting operation strength or automatically switching between filters based on Air quality would be a unique feature to save energy.

  b. Most air filters produce Ozone, which is also one of the top 4 pollutants hence ineffective. An alternate to this has to be designed.

# Conclusions
1. AQI worsening has become an increasingly pressing concern to add
2. The market for Air purifiers is constantly growing. Although government policy in India is changing, some cities have seen irreversible changes that warrant the need for new purifiers (Also supported by an increase in cases of Diarrhoea and other related diseases)
3. The impact of EV's is not that prominent towards AQI improvement. This is because the majority of EV adoption is with motorbikes and not vehicles, where the carbon emmission impact is reduced.
4. Positioning as a small sized air purifier with 2 price ranges (Mid-range and high-range since low range is quite a saturated market) will be key. Must have features include HEPA filter, Carbon Monoxide filter, Cooling technology, Smart app technology (Since all competitors have this) and pollutant detection sensors.


