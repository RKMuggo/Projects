# Climate Change: Temperatures and Precipitation Analysis

## Project Overview

In this project, I explored the effects of climate change by analyzing historical data on temperatures and precipitation. Climate change refers to long-term alterations in average weather patterns, and it can have profound impacts on various aspects of the environment and human life. By examining trends in temperature and precipitation over the years, I aimed to identify significant patterns and changes that may indicate the influence of climate change.

The project involved loading and processing datasets containing temperature and precipitation records, performing data analysis to calculate annual averages and totals, and visualizing these trends to interpret the results. This analysis helps to understand how our climate is evolving and the potential consequences of these changes.

## Setup

First, I loaded the necessary libraries for data analysis and visualization.

## Temperatures

### Section 1: Cities

I analyzed a collection of historical daily temperature and precipitation measurements from weather stations in 210 U.S. cities. This dataset was compiled by Yuchuan Lai and David Dzombak [1]. A description of the data from the original authors and the dataset itself is available [here](https://kilthub.cmu.edu/articles/dataset/Compiled_daily_temperature_and_precipitation_data_for_the_U_S_cities/7890488).

[1] Lai, Yuchuan; Dzombak, David (2019): Compiled historical daily temperature and precipitation data for selected 210 U.S. cities. Carnegie Mellon University. Dataset.

### Section 2: Welcome to Phoenix, Arizona

For my analysis, I chose Phoenix, Arizona, due to its unique climate characteristics. Located on the upper edge of the Sonoran Desert, Phoenix experiences some of the most extreme temperatures in the United States, making it an interesting case study for examining the impacts of climate change on temperature and precipitation patterns.

### Temperature Analysis

By examining historical temperature data for Phoenix, I identified trends in average maximum and minimum temperatures over the years. The analysis revealed significant increases in temperatures for most months, supporting the hypothesis that climate change has led to warmer conditions in Phoenix. Specifically, the data showed that for the majority of months, the present-day temperatures were significantly higher than the historical averages, particularly during the warmer seasons.

### Key Findings

- **Temperature Trends:** There is a clear upward trend in both average maximum and minimum temperatures in Phoenix, particularly from the early 1960s onwards, indicating the effects of modern-day global warming.

### Conclusion from the Hypothesis Test

Since the precipitation p-value generated from my data is less than a cutoff of 5% (0.05), the data is statistically significant, and I can reject the null hypothesis that the drought years and other years have the same amounts of precipitation. This allows me to conclude that the data is more consistent with the alternative hypothesis and that drought years do indeed have lower amounts of precipitation compared to other years.

### Conclusion on the EPA's Statement on Drought

Based on the results of the hypothesis test, I can conclude that the EPA's statement on drought is supported by the data. The periods identified by the EPA as drought years (2002-2005 and 2012-2020) experienced significantly lower precipitation compared to other years. This indicates that these drought years are not just random occurrences but are statistically different from other years in terms of precipitation, aligning with the EPA's observation of persistent drought conditions in the Southwest region during these periods.

## Precipitation Analysis

For the precipitation analysis, I examined total annual precipitation data for 13 cities in the Southwest region from 1960 to 2021. The focus was on assessing the impact of drought conditions as identified by the EPA for the periods 2002-2005 and 2012-2020.

Using an A/B test, I compared the average annual precipitation during drought years to other years. The hypothesis test showed that drought years had significantly lower precipitation compared to other years, with a p-value less than 0.05, allowing me to reject the null hypothesis. This supported the EPA's statement that large portions of the Southwest experienced persistent drought conditions during the specified periods.

### Key Findings

- **Precipitation Trends:** The Southwest region experienced significantly lower precipitation during the EPA-identified drought periods (2002-2005 and 2012-2020) compared to other years, confirming the presence of drought conditions.

## What I Learned

Throughout this project, I gained a deeper understanding of how to analyze and interpret climate data. Here are some of the key learnings and insights I obtained:

1. **Data Analysis Techniques:** I learned how to process and analyze large datasets, calculate relevant statistics, and visualize trends over time using Python.
2. **Statistical Hypothesis Testing:** I applied statistical methods to test hypotheses about climate patterns, which helped me understand the significance of observed changes in temperature and precipitation.
3. **Impact of Climate Change:** The analysis highlighted the tangible impacts of climate change on both temperature and precipitation patterns, reinforcing the importance of addressing climate-related challenges.
4. **Interpretation of Results:** I developed skills in interpreting and presenting data-driven conclusions, which is crucial for communicating scientific findings effectively.

## Final Thoughts

The analysis conducted in this project highlights the tangible impacts of climate change on both temperature and precipitation patterns. The findings underscore the importance of continued monitoring and analysis of climate data to understand and mitigate the effects of climate change. By examining historical data and employing statistical methods, we can draw meaningful conclusions that inform policy and adaptation strategies for affected regions.
