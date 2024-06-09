# NPF-Crimes-Analysis-with-Python

**Abstract**
This report examines the distinct types of crimes that occurred and their changes over the years. Utilizing open police data sources, the analysis covered recorded crime data delivered in a yearly format. It explores the geographical distribution of crime types and compares the changes during and after the COVID-19 pandemic. The analysis, implemented using Apache Spark core, assesses crime density and the impact of lockdown measures, providing a benchmark of crime types in the region during the specified period.

**INTRODUCTION **
This report delves into an analysis of crimes reported within the Nottinghamshire Police Force from March 2019 to March 2021. Utilizing open data sourced from data.police.uk, the study focuses on identifying distinct crime types and tracking changes over the specified period. The data encompasses monthly records in CSV format, detailing crime occurrences with specific fields such as Crime Type, Location, Post Code, Latitude, and Longitude. With the advent of the COVID-19 pandemic, Nottinghamshire implemented new health protocols to mitigate the virus's spread, including lockdowns, self-isolation, and social distancing measures. These changes significantly impacted crime rates, leading to noticeable shifts in both domestic and non-domestic crime reports. By leveraging Apache Spark core, the analysis provides insights into crime density, geographical distribution, and the effects of pandemic-induced lockdown measures. The report aims to benchmark crime types before, during, and after the pandemic, highlighting patterns and anomalies in the data. This study is crucial for understanding how public health crises and associated restrictions can influence criminal activity, providing valuable information for future policy and law enforcement strategies in the region.

**Data Set**
The dataset for this report was extracted from the open dataset source on data.police.uk for the years 2019, 2020, and 2021. This data, made available by the police, serves as a central collection point for recorded crime information. It was downloaded in monthly CSV files, covering the period from March 2019 to March 2021. The onset of the COVID-19 pandemic brought about new health protocols in Nottinghamshire, including lockdowns, self-isolation, and social distancing measures aimed at curbing the virus's spread. These measures led to significant changes in crime rates, with both domestic and non-domestic crimes showing notable variations. Each CSV file includes detailed fields such as Crime Type, Location, Post Code, Latitude, and Longitude, enabling a comprehensive geographical visualization of crime incidents. Nottinghamshire, located in the East Midlands region of England, comprises eight districts under the jurisdiction of the Nottinghamshire Police Force. The dataset's geographical coordinates provide a clear depiction of crime distribution and types across these districts during the specified period. The report analyzes these changes, noting variations in crime types and their frequencies across different months, thus offering a thorough understanding of the impact of the pandemic on crime in the region.

**Data Column Field**
Crime ID| Month| Reported by| Falls Within| Longitude | Latitude| Location | LSOA Code |  LSOA Name | Crime Type | Last Outcome  Category | Context

**METHODOLOGY - DATA PREPARATION**







