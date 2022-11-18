# Topic： A peek at covid's impact on physical and mental health through digital footprints.

# Abstract:
Views of Wikipedia articles about COVID-19 can reflect the major developments of people’s attention in the lifetime of this pandemic. Analyzing the pageviews of COVID-19-related articles can give us an insight into how people are using Wikipedia to share and find information during this unprecedented time. We are not only interested in the Wikipedia pageview of COVID-symptoms, but also non-COVID diseases (not brought by or not directly related to COVID-19), and mental illnesses. Via analyzing the digital footprints during the COVID-19 pandemic, our project aims to figure out the patterns between covid cases and people’s interests in these kinds of physical and mental health shown by Wikipedia pageview. In addition, people’s mobility during the pandemic will be taken into account for pattern analysis. 



# Research questions:


1. Is there any evidence showing that covid-symptoms pageviews are related to covid infections and covid death? If it does, what’s their causation?
2. How attention to mental illness has changed during the pandemic. Are these changes mainly due to social and psychological changes caused by the epidemic lockdown or due to people's panic about this new disease? We will draw conclusions by comparing the correlation between mental illness attention and COVID -19 cases, and the comparative research before and after the mobility change point.
3. Previously, people's concerns about the disease followed a fixed pattern, but the outbreak of COVID-19 changed all that. How did these common diseases, which are not clearly associated with COVID-19, change during the pandemic? Are they related to changes in cases of COVID-19.

# Hypotheses：
 

# Proposed additional dataset:
**AD1**: COVID-19 infection and death dataset: WHO public data, integrated data for English/German/French using the same weighted average method as stated in the paper.

**AD2**: Keyword dataset: provides the range of pageview we are interested in, including keys about covid-symptoms, non-covid-symptoms and mental health.

# Methods:

**Step 1: Data collection, pre-processing and dataset construction.**

- Keyword translation: translate keyword dictionary to language we are interested in. 

- Wiki pageview data collection: According to keywords, we can extract pages from topic_linked.csv that provides, then using Wikimedia REST API to collect daily pageview data for each page. 

- Covid dataset and mobility dataset processing: integrate data according to different languages, using weighted sum for English/German/French.

**Step 2: Correlation analysis: wiki pageview of health and covid cases.**

- Calculate the correlations between wiki pageview of health (covid, non-covid, and mental health) and covid cases (positive cases, and death cases per day). 

**Step 3: Correlation analysis: wiki pageview of health and mobility.**

- Calculate the correlations between wiki pageview of health (covid, non-covid, and mental health) and mobility data. 

**Step 4: Time series analysis.**

- Using regression analysis to qualify the relationship

**Step 5: Datastory and website design.**


# Proposed timeline:

**18.11.22 Milestone 2**

18.11.22 - 02.12.22: Break from the project to work on Homework 2

**02.12.22: Homework 2 submission**

05.12.22: All data have been collected and processed

10.12.22: Correlation analysis and data visualisation 

15.12.22: Regression analysis

20.12.22: Analysis finished and start building our data story website

**23.12.2022: Project milestone P3 submission**

# Organization within the team:

**Hailin Liu**: Data Processing and data story building 

**Jiawei Chen**: Data Processing and analysis, data story building  

**Qiming Sun**: Time series and regression analysis and website building

**ShuShu Zhang**: Data correlation analysis and data story building 

# Questions for TAs (optional): 

