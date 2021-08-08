# plotlydiploy

## Overview:
 - Using the sample.json data, the challenge is to create different types of charts to display the metadata and samples datasets. By selecting individual ids, the page will display the person's demographics information as well as three charts for the top 10 bacterial species (OTUs).

## Results:

When the dashboard is first opened in a browser, ID 940’s is displayed in the dashboard, and the three charts are working according to the selected ID from the dropdown menus as shown in the below images.

![Figure 1 Bar_Gauge Chart](https://user-images.githubusercontent.com/83877498/128647283-03616ca9-0af1-4981-9479-6959c8508ab4.PNG)

Figure 1: Dashboard with ID 940 that displays the demographic information, bar chart and gauge chart

![Figure 2 Bubble Chart](https://user-images.githubusercontent.com/83877498/128647301-65addaf8-2181-4a98-8bf9-11b25f394bf2.PNG)

Figure 1: Dashboard with ID 940 that displays the bubbble chart

## Summary: 
 
JSON file can only be called by running a static server, or python -m http.server that allows us to skirt this restriction. Python's HTTP server provides a web address for both the JSON and HTML files to avoid these security issues.

Once the dataset is available, I'm able to use the filter, map, slicing and sort methods to manipulate the data according to the requirements in this challenge.
The charts.js will hold the logic while index.html will have the html tags where the data will be displayed.
