---
title: Battle of the Locations
category: [blog, Data Science]
tags: [machine learning]
author_profile: true 
---


The consumer demand for child care, early education, and back-up care has grown in recent years in concert with the growing number of working family households. Many families continue to migrate to the suburbs of large metro areas given their proximity to work and consequently there's a significant demand for surrounding child daycare services. Determining the appropriate geography for daycare center expansion is a challenge that requires considering the landscape of today's household and its respective demographics as well as the competitive saturation in these areas.

## Business Problem: ##

A fast growing client is determined to expand to other large metro areas and after internally reviewing the demographics within a segment of the largest cities in the country, have chosen Chicago, Boston and Washington, DC for this review stage. Due to the growing populations and high percentage of two-parent household working families, these cities were selected for closer inspection. The data science team is tasked with analyzing the neighborhoods of these large hubs which have shown a successful level of market penetration. It is these neighborhoods that will presume not only a substantial customer base to grow with, but a high likelihood of available labor as well.  [Click here](https://gregjroberts-datascientist.github.io/_pages/2019_11_01_Battle_for_Daycare_v1.html) to view the python script.

## Problem Statement: ##

The data science team will provide data and insight on the more desirable neighborhoods to target by implementing the following data sets and techniques:

- Part 1:  Data summarizing the top 10 U.S. city demographics for labor population and household size.

Data source: The U.S. Census Bureau datasets were included using the Census.gov API. These datasets were used to explore which cities are potentially target rich environments for childcare services and warrant further inspection of its surrounding neighborhoods. The preliminary findings indicated that Chicago, Boston and Washington, DC satisfied our clients' requirements for a growing populous and contain demographics consistent with both parents in the workforce and have children below the age of 6. Further review of the surrounding neighborhoods should yield areas with higher levels of competitor saturation indicating sufficient opportunity for growth and potential labor.  

- Part 2:  Neighborhood demographics that will indicate favorable environments for deployment.

Data source: After circling these three cities for closer review, web scraping techniques were employed to create datasets from the respective neighborhoods as listed on the associated Wikipedia websites.   You can review the detail behind those datasets respectively for Chicago: [https://en.wikipedia.org/wiki/List_of_neighborhoods_in_Chicago](https://en.wikipedia.org/wiki/List_of_neighborhoods_in_Chicago), Boston: [https://en.wikipedia.org/wiki/Neighborhoods_in_Boston](https://en.wikipedia.org/wiki/Neighborhoods_in_Boston) and Washington, DC.:   [https://en.wikipedia.org/wiki/Neighborhoods_in_Washington,_D.C.](https://en.wikipedia.org/wiki/Neighborhoods_in_Washington,_D.C.)

## Recommendations: ##

Boston would be the preferred geographic location for expanding the clients' child daycare franchise given the following:
- The low percentage of preschoolers enrolled relative to the population and average family size could indicate an underlying unmet customer base.
- The second highest percentage of two-parent households in the work force reflects a favorable environment.
- Boston presently has a significantly lower number of daycare facilities available to the community (20% of Washington, DC; 10% of Chicago) relative to the potential demand.  


 
