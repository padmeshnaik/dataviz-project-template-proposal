# Data Visualization Project

## Data

The data I propose to visualize for my project is a detailed set of variables from the Montesinho natural park in Portugal, capturing the dynamic interplay between meteorological conditions and forest fires. This dataset includes geographic coordinates denoting fire locations, temporal indicators, critical Fire Weather Index (FWI) components such as the Fine Fuel Moisture Code (FFMC), Duff Moisture Code (DMC), Drought Code (DC), and Initial Spread Index (ISI), as well as key weather observations like temperature, relative humidity, wind speed, and rainfall.  

X	Y	month	day	FFMC	DMC	DC	ISI	temp	RH	wind	rain	area   
7	5	mar	fri	86.2	26.2	94.3	5.1	8.2	51	6.7	0	 0    
7	4	oct	tue	90.6	35.4	669.1	6.7	18	33	0.9	0	 0   
7	4	oct	sat	90.6	43.7	686.9	6.7	14.6	33	1.3	0 	0   
8	6	mar	fri	91.7	33.3	77.5	9	8.3	97	4	0.2	0   
8	6	mar	sun	89.3	51.3	102.2	9.6	11.4	99	1.8	0	0    
8	6	aug	sun	92.3	85.3	488	14.7	22.2	29	5.4	0	0    
8	6	aug	mon	92.3	88.9	495.6	8.5	24.1	27	3.1	0	0   
8	6	aug	mon	91.5	145.4	608.2	10.7	8	86	2.2	0	0    
8	6	sep	tue	91	129.5	692.6	7	13.1	63	5.4	0	0   

Dataset Link : https://archive.ics.uci.edu/static/public/162/forest+fires.zip


## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

  
1). Is there a correlation between temperature and relative humidity?    
    
2). Are there interesting spatial patterns in the occurrence of fires?  
  
3). How does the area burned vary across different months?  


## Sketches

![Rough Sketch of the interactive visualization](IMG_0713.jpg)

![image](img.png)

The initial map rendering of Montesinho Natural Park, leveraging GEOJSON data, is instrumental in identifying fire locations and understanding spatial distributions.

![Rendering the Montisenho Natural Park using GEOJSON](montisenho.png)

Additionally, the map embellished with grid lines offers an enhanced perspective of the park’s layout, potentially revealing spatial correlations with fire events.

![Rendering the Montisenho Natural Park with grid lines](graph3.png)



## Graphs

The subsequent scatter plot delineates the relationship between humidity and temperature, a crucial aspect in fire behavior analysis.

![image](graph1.png)

Another graph showcases the relationship between the area affected by fires and the month of occurrence, highlighting potential seasonal trends

![image](graph2.png)

## Open Questions

Integrating FWI components into the visualization remains a complex task. I aim to present these various components—differing in scale and relevance—intuitively, ensuring the information is digestible for users regardless of their background in fire science or meteorology.

## Milestones

Week 1: Data Preparation and Initial Visualization  
Week 2: Enhancing Scatter Plot and Spatial Pattern Analysis  
Week 3: Development of Temporal Analysis and Interaction  
Week 4: FWI Components vs. Meteorological Conditions  
Week 5: Integration and User Experience Improvements  
Week 6: Final Testing and Project Review
