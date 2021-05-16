# Plotly_Deploy
## Overview
A food start-up, Improbable Beef has partnered with a microbiology laboratory to search for an elusive bacterial species that provides perfect taste like beef. Lab’s biology researcher, Rosa's role is to discover and document the bacterial species that can synthesize proteins that taste like beef. Rosa hypothesizes that the ideal bacterial species to make synthetic beef may found in the human bellybutton. To test her hypothesis, Rosa has gathered navel samples from candidates across the country to identify bacterial species that colonize the bellybutton. To document the results, Rosa wants to build a dashboard on a website where both research participants and fellow researchers can access data. 

## Summary
The data collected from research participants are visually presented in a dashboard with the help of graphs. Individual participant data can be accessed by selecting the participant’s unique Id.

### 1. Horizontal Bar Chart
A horizontal bar chart is designed using JavaScript, Plotly, D3.js Upon selecting an individual Id from the dropdown menu on the webpage, a horizontal bar chart is displayed with the top 10 bacterial species (OTU’s) for that Id. Below are the specifications for the horizontal bar chart:

- X-axis: Sample values 
- Y-axis: OTU ids 
- Hover Text: OTU labels 

![image](https://user-images.githubusercontent.com/76491891/118402364-a43f4b00-b637-11eb-82ec-708f78a6723e.png)

### 2. Bubble Chart
A bubble bar chart is designed using JavaScript, Plotly, D3.js. Upon selecting an individual Id from the dropdown menu on the webpage, a bubble chart is displayed with bacteria cultures for that Id. Below are the specifications for the bubble chart:

- X-axis: OTU ids
- Y-axis: Sample values 
- Hover Text: OTU labels 
- Marker Size: Sample values
- Marker Colors: OTU ids

![image](https://user-images.githubusercontent.com/76491891/118402502-22035680-b638-11eb-98ea-322d26fccd5c.png)

### 3. Gauge Chart
A gauge chart is designed using JavaScript, Plotly, D3.js. Upon selecting an individual Id from the dropdown menu on the webpage, a gauge chart displays the weekly washing frequency value as a measure from 0- 10 on the progress bar for that id. Below are the specifications for the gauge chart:

- Values: Washing frequency 
- Range: 0 – 10

![image](https://user-images.githubusercontent.com/76491891/118402588-89b9a180-b638-11eb-829b-88e1c3ce23c2.png)

### 4. Enhancements to the Dashboard
Using HTML and Bootstrap, the below enhancements are done to improve the look and feel of the webpage:

- Added a background image to the Jumbotron
- Added background color to the webpage
- Changed the font color
- Aligned graphs on the webpage
