# Graph Project Proposol 

### Description
create a graph that represents the data that correlates across different categories.\
Project is based off this project:\
&nbsp;&nbsp;&nbsp;&nbsp;[Website](https://savai.co/)\
&nbsp;&nbsp;&nbsp;&nbsp;[Repo](https://github.com/SarinSwift/Savai)\
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



