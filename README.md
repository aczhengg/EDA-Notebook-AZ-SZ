# EDA-Notebook-AZ-SZ

This analysis is by Stella Zhang and Ali Zheng, seniors at Emory University studying Quantitative Sciences. 

## Project Objectives

This project studies the relationships and trends between US nursing home care quality, payment methods for nursing home care, population demographics, and participant income level. 

Objective 1: 
How do residents and family members perceive care quality at nursing homes?

Objective 2: 
How does financial support across facilities affect quality ratings?


## Methods Used
- Data Visualization (variety of graphs)
- Statistical Significance Testing (p-values)

## Technology Used
- GitHub
- RStudio

## Project Description
This project is based on significant and current health trends witnessed across the United States. With number of caregivers declining, life expectancy for older generations increasing, and prevalence of chronic diseases exacerbating, it's imperative to understand and analyze the various factors influencing US nursing home care quality. Nursing homes have long been a fundamental part of the US's healthcare landscape, in both preventive and diagnostic care. Given their importance, this study aims to identify key factors that influence resident and resident family's perceptions on nursing home care by analyzing demographics such as sex, race, income, and payment source. We placed an emphasis on analyzing payment source and income levels because of the known discrepancies between federally funded nursing homes and privately funded. Federally funded nursing homes tend to see more frequent management changes, lower quantity of qualified nurses and staff, and potentially different patterns in care quality compared to non-federally funded nursing homes. Individuals paying through private long term insurance are more likely to obtain better care quality by affording better facilities, a difference that may contribute to divergent perceptions among residents and their family. 

The data utilized in this study originated from a nationally administered Internet-based survey to individuals with nursing home experience within the last 6 months in 2017 and 2019. Participants were recruited from the Survey Sampling International (SSI) US online panel, a global research company that represents over 3.7 million households worldwide and holds access to online survey panels. Participants between the 2017 and 2019 cohorts are exclusive, so there is no participant in both cohorts. Each participant is asked to rank factors of care from 0 (extremely poor) to 10 (extremely high). This approach facilitated a quantitative evaluation of these factors so participant perspectives can be analyzed systematically and significant factors can be pinpointed as exerting the most substantial influence on resident satisfaction. 

In terms of visualizations, we created bar graphs in RStudio; these were especially utilized throughout our study to make statistical inferences and plot trends. Tests of significance are used to support these trends. These graphs were created through the _ggplot2_ and _tidyverse_ packages in RStudio. We decided on bar graphs as a means to best represent frequency, which was one of our main visualization goals, and to provide a clear depiction of categorical data comparisons. This approach not only facilitated a comprehensive understanding of distribution but also enabled a straightforward comparison of prevalent factors. 

Challenges we currently face involve questions about the generalizeability of our data, rooted in the data's nature as a voluntary survey, which could have introduced selection bias, and the lack of longevity of each cohort study. Next steps we would want to study include looking at pre-COVID19 and post-COVID19 data to understand the impact of global health policies as well as diving deeper into nursing home funding disparities; for instance, one direction we could be interested in is looking at how less financially stable, rural areas compare to more financially well off, urban areas in terms of their nursing home care quality. 

## Instructions for Getting Started
1. Clone this repository
2. Download both "37969-0001-Data.csv" and "37969-0002-Data.csv". These are the two datasets we used for this project; the first is 2017 data and the second is 2019 data. 
3. Download "EDA-Final.rmd" to view our analysis

