# Infofinder
## Tampere University, Finland 
## TIE-13106 Project Work 2019
for: Cybercom Finland Oy  
by: Simply the bestest (G06)

### The project
The system provides a tool for event organizers to create events and mark the event’s services and points of interest on a map. 
The event participant can use app with the map to find the services and sends location data to the service. The participant can 
see the current heatmap of the event area. Participant can use this data for example to pick a less crowded toilet. The organizer 
can view the heatmaps for the entire duration of the event and use this data to optimize the locations of the services and give 
better guidance to participants.  

The system includes cloud-based backend solution, web-based client application and a mobile/hybrid application for the end users.
The backend will be serverless and created using Amazon Web Services. Users are managed with Cognito, data is stored in DynamoDB,
business logic with Lambda functions and API Gateway provides the mapping between Lambdas and REST API URLs.

Gitlab repository provided by TAU will be used for version control, backlog management and issue tracking. Telegram channel 
will be used for team's internal communication. Slack channel provided by the customer will be used to quickly communicate with 
the customer. All the team members have access to both channels.  

Documentation for the project is held in a shared OneDrive folder to enable easy access and editing for all the group members. 

### The team
Mikko Ollila, Project Manager  
Riina Pussinen, Product Owner  
Saku Lehtinen, QA Lead  
Jukka Ilmanen, UX Expert  
Otto Sahanen, Software Architect  
Jukka Pajulehto, Developer  
Monika Bohara, Developer  

### Burnup chart
<img src='https://github.com/wldchld/infofinder/blob/master/images/burnup.PNG'/>

### Hour log

Team member    |  37  |  38  |  39  |  40  |  41  |  42  |  43  |  SUM  |
|--------------|------|------|------|------|------|------|------|-------|
Jukka Ilmanen  |0     |8     |6     |5,5   |6,5   |6     |8     |40     |
Jukka Pajulehto|0     |7     |6     |2     |0     |5     |3     |23     |
Mikko Ollila   |0,5   |12    |16,25 |5,75  |5     |11    |7,5   |58     |
Monika Bohara  |0     |6     |7     |4     |2     |12    |      |31     |
Otto Sahanen   |      |10    |9     |5     |4,5   |9     |4     |41,5   |
Riina Pussinen |0     |7     |9     |3     |5     |14    |2     |40     |
Saku Lehtinen  |0     |7     |6     |2     |8     |8     |      |31     |
(Cumulative)   |0,5   |57    |59,25 |27,25 |31    |65    |24,5  |264,5  |


#### 2019-11-01