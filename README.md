# Data Science
***
## Project 1: **[The Impact of the Progresa Program Using Causal Inference and Linear Regression Analysis](https://richdait.github.io/Causality_Regression_Progresa/)**
* Estimated the social impact of the government assistance program - Progresa - on the welfare of poor, rural households in Mexico.
* Performed a t-test to determine whether the difference between the treatment and control groups is statistical significant. Also obtained the associated p-value.
* Measured the effectiveness of subsidies had on school attendance using DiD (i.e., difference in trends for T and C groups) simple and muliple regression analysis in R.
* Data transformation/manipulation via dplyr:
  <ul> <li> Created new variables via the mutate function. </li>
  <li> Selected rows via filter() to equal desired conditions. </li>
  <li> Utilized the group_by function to compare the controlled and treated groups, before and after the program was implemented. </li>
  <li> Produced a new dataframe to summarize the average school attendance of the participants for both the treatment and control groups, before and after the implementation of the Progresa program.</li> </ul>
  
##### Check [respository](https://github.com/richdait/Causality_Regression_Progresa) for a detailed project description and associated files.

## Project 2: **[Report on Crime in Boston](https://richdait.github.io/Extra-Credit---Crime-in-Boston/)**
* Created a report via time series data with a minimum of 1000 observations for crime in Boston.
* Inserted R script with code into an R markdown document to display findings and analysis.
* Data wrangling functions via dplyr package:
  <ul> 1. Grouped by incident no. </ul>
  <ul> 2. Filtered the data frame to only include offense type "ARSON" </ul>
  <ul> 3. Selected 6 relevant columns for display. </ul>
* Data visualization via ggplot2:
  <ul> 1. Rendered a vertical bar chart displaying frequency (measured in days of the week), in which arson occurred. </ul>
  <ul> 2. Created a background of map tiles.</ul>
  <ul> 3. Added point data (Long, Lat) of locations where arson happened on the map.</ul>
* The project provided valuable insights into forecasting criminal activities, that may result in improving policies and BPD decision-making.

##### Check [respository](https://github.com/richdait/Extra-Credit---Crime-in-Boston) for a detailed project description and associated files.

## Project 3: **[Food Accessibility in Washington State: You Are What You Eat](https://richiea7uwinfo.shinyapps.io/Food_Accessibility/)**
* Investigated whether or not socio-economic factors such as income, distance and transportation have an impact on accessibility to fresh and nutritious food in Washington State.
* Extracted, manipulated and wrangled data from the United States Department of Agriculture Economic Research Service website.
* Identified direct and indirect stakeholders.
* Collaborated with 3 other members to conduct research, produce code in R and generate an interactive shiny web application.
* Data science processes and techniques:
  <ul><li>Data aggregation</li></ul>
  <ul><li>Data exploration</li></ul>
  <ul><li>Data wrangling</li></ul>
  <ul><li>Data visualization: My part - a responsive and interactive data table with annotation answering the question, what extent does low income and location
have an effect on access to fresh and nutritious food?</li></ul>

##### Check [repository](https://github.com/richdait/INFO-201-Final-Project) for a detailed project description and associated files.

# GIS Data Analysis and/or Spatial Statistics
***
## Project 4: **[Smart Dashboard Illustrating the Spatial Variation of Poverty in Seattle](https://richdait.github.io/Final_Project_Poverty/poverty)**
* Created an interactive digital application, illustrating a real-world problem and critically analyzing its implications on society.
* Users are able to interact with the dashboard by clicking on a census tract polygon, which displays an associated poverty percentage.
* Procured shapefile from Seattle Open Data Portal and converted it to GeoJSON via QGIS.
* Icons from Font Awesome direct users to relevant sites and clickable links provide readers further info regarding poverty.
* The final project not only allowed me to research a topic I am passionate about, but give me the platform to refine my programming and GIS skills.

##### Check [respository](https://github.com/richdait/Final_Project_Poverty) for a detailed project description and associated files.

## Project 5: **[The Geography and Seasonality of Crime in Seattle, WA](https://arcg.is/H0DL5)**
* Collaborated with two other geography researchers to conduct a spatial temporal analysis of crime in Seattle, WA.
* Utilized ArcGIS Pro to produce compelling optimized hot spot analysis maps.
* Published and narrated our findings using the flexible and easy-to-build features of ArcGIS StoryMaps.
* Our research revealed geographic variability and patterns of seasonality with slight fluctuations.
  <ul><li>West, southwest and especially north Seattle, experienced shifts in crime incidents and density.</li></ul>
  <ul><li>Based on data, summer appears to the season with the most activity.</li></ul>
  <ul><li>Regardless of season, downtown Seattle and its neighboring areas exhibit statistically significant hot spots throughout the year for all three crime types.</li></ul>
  <ul><li>"An Optimized Hot Spot Analysis is Worth A Thousand Words" section was my part of the project.</li></ul>
* This particular project demonstrated that I am able to work effectively and communicate well in a team environment, whether in person or remotely via Zoom. Another big takeaway is my ability to collect, analyze and interpret data, and ultimately relay the findings through a powerful story using GIS based technologies. Lastly, the demands of the final project, in conjunction with the challenges of taking four grueling courses during my final quarter as an undergraduate, proved that I am more than capable of overcoming any obstacle or adversity, through sustained, genuine effort, grit and resilience. Of course, the final project was not made possible without the equal contribution, diligence and creative inputs of my fellow geographers.


# Web Development and Design
***
## Project 6: **[Hangry in Seattle](https://richdait.github.io/)**
* Produced a fully-functional, responsive website using Github pages.
* Personalized the grayscale Bootstrap-based template to align with the aesthetic and theme - food photography.
* User interface (UI) design:
<ul> 1. Modified CSS and HTML lines of code to facilitate usability and improve site organization. </ul>
<ul> 2. Tabs allow the user quick and easy access to information and specific areas of the website. </ul>
<ul> 3. Social media icons at the bottom instantly direct users to relevant and helpful third-party sites. </ul>

* The project allowed me to re-familiarze myself with Github, hone my skills in markdown syntax, create a Bootstrap-based responsive website and most importantly, showcase the burgeoning food scene in Seattle.

##### Check [repository](https://github.com/richdait/richdait.github.io) for a detailed project description and associated files.

## Project 7: **[Web Design and Tile Generation](https://richdait.github.io/Socioeconomic_Index_and_Seahawks_Tile_Sets/index.html)**
* Created 4 tile sets using various basemaps illustrating a geographic phenomena and theme of choice.
* Basemap of Seattle was designed via MapBox Studio.
* Generated and read map tiles through QGIS.
* Users are able to interact with the site via 3 radio buttons of basemaps and 4 overlays.
* One thing I learned from this project is that something as simple as implementing UI controls, increases user engagement.
##### Check [respository](https://github.com/richdait/Socioeconomic_Index_and_Seahawks_Tile_Sets) for a detailed project description and associated files.
## Project 8: **[Interactive Web Application of the Number of Airports in the U.S.](https://richdait.github.io/lab4_WebMapApp/)**
* Created an interactive web map, depicting the number of airports within each state, according to pre-defined data intervals and whether the airport itself, contains an air traffic control tower.
* OpenStreetMap basemap was used and GeoJSON data loaded via the Leaflet ajax plugin.
* User is able click on airplane icons courtesy of Font Awesome to determine the abbreviated name of an air traffic control tower. 
* Fundamental cartographic elements such as a legend and scale are included.
* The project taught me that choosing the right color scheme is important as it brings to light, the highest and lowest values in the dataset. Additionally, it makes the map more appealing and raises possible questions with the user.

##### Check [repository](https://github.com/richdait/lab4_WebMapApp) for a detailed project description and associated files.
