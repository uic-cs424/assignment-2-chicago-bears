## Introduction
Please download the Building [Violation dataset(csv)](https://data.cityofchicago.org/Buildings/Building-Violations/22u3-xenr) to your local first.

## Description
The "Building Violations" dataset is a comprehensive record comprising 1.88 million entries and 26 columns. Each entry corresponds to a specific violation, detailing both geographical coordinates (latitude and longitude) and categorical attributes such as violation code and inspection category. 

In this repository, we hone in on specific attributes such as 'latitude and longitude', 'violation code', and 'violation date'. Utilizing a suite of visualization techniques, we have crafted a total of 19 graphs. This includes a specialized graph for analyzing property numbers, additional queries to discern violation-type trends from 2018-2023, and two visualizations using alternative libraries. To ensure compliance with the specifications of Assignment 2, for every graph generated with an alternative library, a standard version is also provided. Our overarching objective is to deepen comprehension by meticulously cleaning and aggregating data, and effectively presenting them through these visualizations.


In the final graph of our series, we employ a scatter plot segmented by two intersecting lines, effectively dividing the visualization into four distinct quadrants. Each quadrant elucidates a unique relationship between building violations and their respective solutions:

**Quadrant 1:** High violation counts and high solution rates, pointing to **neutral effects**.  
**Quadrant 2:** High violation counts but low solution rates, pointing to **positive effects**.  
**Quadrant 3:** Low violation counts and low solution rates, pointing to **no  effects**.  
**Quadrant 4:** High violation counts with low solution rates, pointing to **negative effects**.  

The positioning on the plot is determined by the x-axis (more to the right signifies higher violation counts) and the y-axis (higher placement corresponds to increased solution rates). This approach allows for an insightful analysis of the correlation between building violations and their resolutions.

## Screenshots
<img src="./screenshots/1-1-1.png">
<img src="./screenshots/1-1-2.png">
<img src="./screenshots/1-1-3.png">
<img src="./screenshots/1-1-4.png">
<img src="./screenshots/folium_map.png">
<img src="./screenshots/1-2-1.png">
<img src="./screenshots/1-2-2.png">
<img src="./screenshots/2-1-1.png">
<img src="./screenshots/2-1-1(1).png">
<img src="./screenshots/2-2-1.png">
<img src="./screenshots/2-2-2.png">
<img src="./screenshots/2-3-2.png">
<img src="./screenshots/2-4-1.png">
<img src="./screenshots/2-4-1(1).png">
<img src="./screenshots/2-4-2(1).png">
<img src="./screenshots/3-1-1.png">
<img src="./screenshots/3-1-2.png">
<img src="./screenshots/4-1-1.png">
<img src="./screenshots/4-1-2.png">

## Data Source 
- [Building Violation](https://data.cityofchicago.org/Buildings/Building-Violations/22u3-xenr)
- [Crimes in 2023](https://data.cityofchicago.org/Public-Safety/Crimes-2023/xguy-4ndq)
- [Chicago Personal Income from 1970-2021](https://fred.stlouisfed.org/series/CHIC917PCPI)
- [Chicago Bundaries](https://fmiranda.me/courses/cs424-fall-2023/lab-1/boundaries-zipcode.geojson)
