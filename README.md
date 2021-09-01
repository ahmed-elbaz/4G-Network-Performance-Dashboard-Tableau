# 4G-Network-Performance-Dashboard-Tableau

## Introduction

A typical 4G mobile network consists of several nodes connected to each other, where each node serves users in the surrounding area. While users are accessing network services, their mobile phones record Key Performance Indicators (KPIs) which can help network operators in assessing their quality of service.
There are many KPIs which evaluate different aspects of the network. For example, RSRP (Reference Signals Received Power) is a KPI which measures the network coverage in the user’s location. Traffic Volume is another KPI which measures how much data has been consumed by the user.

We have two crowdsourced datasets: RSRP and Traffic Volume captured for three operators(A,B and C). Each dataset has the corresponding KPI measurements collected from mobile phones of different users over a week. It also includes the user’s location, operator, phone model and other information. The detailed description of each field can be found in DataDescription.xlsx.

After preprocessing the above datasets a 4G network performance dashboard was created.

## Dashboard components

1. A time-lapse of a density map showing how users move during the hours of the day.
2. A heat map of user locations for a selected operator colored by RSRP value.
3. A bubble map showing the areas with high downlink traffic for each operator. Each bubble represents an area on the map.
4. A Bar chart of RSRP per device type per operator with an option to choose the aggregation method of RSRP (avg, min, max and 90th Percentile). A slider to control the minimum number of users of each device was added.

## Project contents

1. **DataDescription.xlsx** shows the detailed description of each field in the datasets.
2. **Data_preprocessing** notebook shows the preprocessing done in both datasets to prepare them for visualisation phase.
3. **4G Network Performance Dashboard** can be found in the below link  https://public.tableau.com/app/profile/ahmed.elbaz/viz/4GNetworkPerformance/4GPerformanceDashboard
