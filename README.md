# Topic： A peek at covid's impact on physical and mental health through digital footprints.

# Milestone 3

## [Data story](https://futureson.github.io/Covidpageviews/)
We are the group of **Wizards2122** for the Applied Data Analysis. Our data story is [here](https://futureson.github.io/Covidpageviews/). If you are interested how do we build that website, you can find all the information [here](https://github.com/futureson/Covidpageviews)

## Notebooks
The analysis are divided into 4 parts: 

- [Data Processing](https://github.com/epfl-ada/ada-2022-project-wizards2122/tree/main/notebooks/1.Data%20Processing)

- [Correlation of mobility and pageviews](https://github.com/epfl-ada/ada-2022-project-wizards2122/tree/main/notebooks/3.Correlation%20of%20moblity%20and%20pageviews)

- [Correlation of covid cases and pageviews](https://github.com/epfl-ada/ada-2022-project-wizards2122/tree/main/notebooks/2.Correlation%20of%20covid%20cases%20and%20pageviews)

- [Effects of intervention events](https://github.com/epfl-ada/ada-2022-project-wizards2122/tree/main/notebooks/4.Effects%20of%20intervention%20events)

# Abstract:
Views of Wikipedia articles about COVID-19 can reflect the major developments of people’s attention in the lifetime of this pandemic. Analyzing the pageviews of COVID-19-related articles can give us an insight into how people are using Wikipedia to share and find information during this unprecedented time. We are not only interested in the Wikipedia pageview of COVID-symptoms, but also non-COVID diseases (not brought by or not directly related to COVID-19), and mental illnesses. Via analyzing the digital footprints during the COVID-19 pandemic, our project aims to figure out the patterns between covid cases and people’s interests in these kinds of physical and mental health shown by Wikipedia pageview. In addition, people’s mobility during the pandemic will be taken into account for pattern analysis. 



# Research questions:
1. Is there any evidence showing that the trend of pageviews associated with COVID-19 is related to COVID infections? If it does, what’s their causality?  How about the noncovid decreases and mental issues?
2. The stringent policies implemented during the Coronavirus pandemic had reduced human movements. We wonder if there is a correlation between the Wiki pageviews and mobility change? If it does, what’s their causality and what can we infer from the data?
3. How attention to different Wiki topics affected by intervention events?


# Proposed additional dataset:
**AD1**: COVID-19 infection and death dataset: [WHO public data](https://covid19.who.int/data), integrated data for English/German/French using the same weighted average method as stated in the paper.

**AD2**: [Keyword dataset](https://github.com/epfl-ada/ada-2022-project-wizards2122/blob/main/data/key_words.csv): provides the range of pageview we are interested in, including keys about covid-symptoms, non-covid-symptoms and mental health.

# Methods:

**Step 1: Data collection, pre-processing and dataset construction.**

- Keyword collection: identify the keywords we are interested in (including covid, non-covid and mental health related keywords). 

- Wiki pageview data collection: According to keywords, we can extract pages from topic_linked.csv that provides, then using Wikimedia REST API to collect daily pageview data for each page. After that, we manually categorize each page to more refined categories.

- Covid dataset and mobility dataset processing: integrate data according to different languages, using weighted sum for English/German/French.

**Step 2: Correlation analysis: wiki pageview of health and covid cases.**

- Calculate the correlations between wiki pageview of health (covid, non-covid, and mental health) and covid cases (positive cases per day). 

**Step 3: Correlation analysis: wiki pageview of health and mobility.**

- Calculate the correlations between wiki pageview of health (covid, non-covid, and mental health) and mobility change data. 

**Step 4: Time series analysis.**

- Using regression analysis to qualify the effect of the events.

**Step 5: Datastory and website design.**


# Proposed timeline(Finished on time):

**18.11.22 Milestone 2**

18.11.22 - 02.12.22: Break from the project to work on Homework 2

**02.12.22: Homework 2 submission**

05.12.22: All data have been collected and processed

10.12.22: Correlation analysis and data visualisation 

15.12.22: Regression analysis

20.12.22: Analysis finished and start building our data story website

**23.12.2022: Project milestone P3 submission**

# Organization within the team:
The work is equally distributed among all the group members

**Hailin Liu**: Data correlation analysis and data story building

**Jiawei Chen**: Data collection and processing, correlation analysis and data story building  

**Qiming Sun**: Time series and regression analysis as well as website building

**Shushu Zhang**: Topic classification and data story building 



