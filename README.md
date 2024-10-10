Marketing A/B Testing Analysis
Overview

This project analyzes the effectiveness of advertising campaigns using A/B testing. Marketing companies often face complex decisions when running campaigns, and A/B testing provides a method to evaluate different strategies. By comparing the performance of an experimental group (exposed to ads) with a control group (exposed to Public Service Announcements), this analysis aims to determine the success of ad campaigns and attribute conversions to advertising efforts.
Objectives

The primary goals of this analysis are to answer the following questions:

    Would the campaign be successful?
    If successful, how much of that success can be attributed to the ads?

By addressing these questions, we can provide insights into the effectiveness of the advertising strategies employed.
Dataset

The dataset used for this analysis contains the following columns:

    Index: Row index
    user id: Unique identifier for each user
    test group: Indicates whether the user saw an advertisement (ad) or a Public Service Announcement (psa)
    converted: Indicates if the user made a purchase (True) or not (False)
    total ads: Number of ads viewed by the user
    most ads day: Day on which the user viewed the highest number of ads
    most ads hour: Hour of the day when the user saw the most ads

Analysis

The analysis involves the following steps:

    Data Exploration: Understand the dataset structure, missing values, and distributions.
    Statistical Testing: Perform chi-squared tests to determine if there are significant differences in conversion rates between the ad and psa groups.
    Impact Assessment: Estimate the financial impact of the ads based on conversion rates and total sales.
    Visualizations: Create graphs to illustrate key findings and trends in the data.

Tools and Libraries

This project utilizes the following tools and libraries:

    Python: The primary programming language for data analysis.
    Pandas: For data manipulation and analysis.
    NumPy: For numerical calculations.
    SciPy: For statistical testing.
    Matplotlib/Seaborn: For data visualization.
