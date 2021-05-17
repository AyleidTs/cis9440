# Project Name here
- author(s): Anastasios Avramidis
- date created: 05/16/2021
- class: CIS 9440

Project Objective: Follow the Kimball Lifecycle to design and develop a public, cloud-based Data Warehouse with a functioning BI Applications

Project Tools:
The tools used to build this Data Warehouse were: 
1. For data integration - Python
2. For data warehousing - Google BigQuery
3. For Business Intelligence - Tableau

## Kimball Lifecycle Project Stages

### Project Planning

Motivation for project:
Evaluate the parameters that contribute in a video being viral. Try to understand Youtube
algorithm and people preference

Description of the issues or opportunities the project will address:
Identify potential issues in non viral videos and address them to increase viewership of videos.
Get an edge over similar channels.

Project Business or Organization Value:
Generate more views, increase revenue.

Data Sources:
1. Trending Youtube Video Statistics (Kaggle)
2. Youtube Channels (Kaggle)
3. Recent video data scraped from Youtube 

### Business Requirements Definition

List of Data Warehouse KPI's:
1.Dislikes/Like Ratio
2.Total views per category
3.Total channels per category
4.Videos/Sub per Channel 
5.Ratings/Views Ratio

### Dimensional Model

This project's Dimensional Model consists of (x) Facts and (y) Dimensions

Use correct file path here to show picture of dimensional model...
![Alt text](/img/dimensional.png)

This project's Kimball Bus Matrix:

Use correct file path here to show picture of dimensional model...
![Alt text](/img/kimbalmatrix.png)

### Business Intelligence Design and Development

List of Visualizations for each KPI:
1. Bar Chart for like/dislikes Ratio
2. Bar Chart for total views per category
3. Bar Chart for total channels per category
4. Bar Chart for ratings/views Ratio
5. Bar Chart for videos/subs per channel
6. Treemap for total views/channels per category

BI Application Wireframe design:

Use correct file path here to show picture of Wireframe design...
![Alt text](/img/cis9440wireframe.jpg)

Picture of final Dashboard:

Use correct file path here to show picture of Dashboard...
![Alt text](/img/dashboard.PNG)

### Deployment

The project was deployed on Tableau Public: https://public.tableau.com/profile/tasos.avr.#!/vizhome/Cis9440/YoutubeStats?publish=yes