# Graph Project Proposol 

### Description
create a graph that represents the data that correlates across different categories.\
Project is based off this project *Savai: An app that helps users search beauty services around their area*\
&nbsp;&nbsp;&nbsp;&nbsp;[Website](https://savai.co/)\
&nbsp;&nbsp;&nbsp;&nbsp;[iOS Repo](https://github.com/SarinSwift/Savai)\
&nbsp;&nbsp;&nbsp;&nbsp;[Backend Repo](https://github.com/RinniSwift/BackendAPI)\
&nbsp;&nbsp;&nbsp;&nbsp;[Docsify](https://rinniswift.github.io/BackendAPI/#/)

**Data Hierarchy**
```
Service Location
---Macro Category
---Micro Category
---Service Category
---Services
```

**Object Info**:
```
Service Location:
   name: String
   hours: String
   service categories: [Service Category]
   micro categories: [Micro Category]
   macro categories: [Macro Category]
   services: [Service]

Macro Category:
   name: String
   micro categories: [Micro Category]

Micro Category:
   name: String
   services: [Service]

Service Category:
   name: String
   macro categories: [Macro Category]

Service:
   name: String
   description: String
   discounted: String
   original price: String
   discounted price: String
```


### Graph visualization

> Middle node is the database which connects to 5 other clusters.\
> Clusters represent the 5 different objects.

<img src="IMG_3094.JPG" width="900" height="600" />

### Graph visualization with data

> Easy visualization of backend database.

<img src="IMG_3099.JPG" width="900" height="600" />


### Solutions

1. Calculate the least amount of services a shop offers with bfs
2. Calculate all the services a shop offerd with dfs

