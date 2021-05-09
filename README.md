# Data Visualization Of Covid-19

# Introduction
Recent news stated that the COVID-19 cases showing a slowdown trend. After examining different charts and data, this doesn’t seem to be the case. The purpose of my Github page is to track the COVID-19 cases in the United States specifically. As a stock trader, I have always believed that the charts always tell the story and I never depend 100% on what people are saying about certain events. As users, you can see information regarding confirmed cases and total deaths in each State. The data that I used is constantly updated every day so the users can always come back and see the trend.

# Narrative Structure
The narrative visualization follows the drill-down story structure. For example, the first section gives an overview look at the COVID-19 situation in each State of the US. The 2nd section shows the COVID-19 trend while the 3rd section shows the total COVID-19 related deaths. Both 2nd and 3rd charts are correlated as one goes up the other one should go up as well.

# Visual Structure
The theme of my page is ‘simplicity’. The charts are pretty simple and easy to understand as the first chart follows a scatter plot while the last two charts follow simple line charts. The page follows a format that emphasizes the information displayed as the charts are the only parts of the page that’s colored and highlighted. 
Section IV. Scenes
There are 3 scenes in total. The first scene is the overview of COVID-19 cases per State. The 2nd scene shows the confirmed cases in the US while the 3rd scene shows the total deaths. 

# Annotation
The charts didn’t have follow any particular templates for the annotations. I feel like having them will not go well with the theme of my page.
Section VI. Parameters
The users can change the state of the page by clicking on the underline sections. They serve as indexes of the page. Mouse movement is another parameter as a particular data item is shown in a tooltip box at a particular mouse coordinate. 

# Triggers
When the user selects a bubble in the first chart, it triggers an event which shows the COVID-19 information regarding a particular State. The 2nd chart triggers the confirmed cases up to a particular date. The 3rd chart implements a rectangle which detects the mouse’s position and a circle on the line chart showing total deaths up to a particular date will follow the mouse. Once the mouse pauses or moves far away, this will trigger an event ‘stop’ and whatever information was last displayed will remain on the chart.

Author: Hoa Le
