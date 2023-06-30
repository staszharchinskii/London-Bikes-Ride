# London-Bikes-Ride
## Preparing and visualising cycling data in London with Tableau
For this project, I used data from Kaggle https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset. In the Jupyter file, I prepared the data for visualisation, using the pandas library. After that, I exported the data to .xlsx format and used the Excel file in Tableau. In Tableau, I created 5 sheets and 1 final dashboard.

### Average Moving Sheet.
Here I created a line graph to visualise the relationship between average rides and average period. I also added a function to filter selected values using min month and max month.
![image](https://github.com/staszharchinskii/London-Bikes-Ride/assets/116664392/c1c6fa48-e297-4e44-a421-6c9de2842e89)

### Total Rides Sheet.
In this worksheet, I have created a number that corresponds to the number of selected rides per time period in the graph. I created an 'in range' filter for this, in which
[Moving Average Period] >= [Min Month]
AND 
[Moving Avarage Period] <= [Max Month], 
![image](https://github.com/staszharchinskii/London-Bikes-Ride/assets/116664392/04f1baf0-b3a4-4320-8d50-e689edb59f1e)

### Heatmap(Temperature vs wind speed) Sheet.
Here I created a relationship between temperature and wind speed in the form of a heatmap. Here I also used a filter so that the values are provided depending on the selected data interval on the graph.
![image](https://github.com/staszharchinskii/London-Bikes-Ride/assets/116664392/4e6cee85-c126-4759-ac28-d4b0666d4cc4)

### Weather Sheet.
I created this worksheet as a tooltip, when you select a value on a graph or heatmap, information about the weather for that period appears.
For example:
![image](https://github.com/staszharchinskii/London-Bikes-Ride/assets/116664392/8bd6cb89-ce7e-47a6-b99b-e148acacd795)
![image](https://github.com/staszharchinskii/London-Bikes-Ride/assets/116664392/1ccfe0e1-3829-4426-8f7a-1dc081ad5eb8)

### Hour Sheet.
This is a similar sheet to the one with the weather, everything is the same, only the time information :)
![image](https://github.com/staszharchinskii/London-Bikes-Ride/assets/116664392/358ab5de-d5e2-43a1-aa91-2aa4a1b43707)
![image](https://github.com/staszharchinskii/London-Bikes-Ride/assets/116664392/66d7bafd-8d95-443c-b068-a7bfd04b72d4)

## Final Result.
![image](https://github.com/staszharchinskii/London-Bikes-Ride/assets/116664392/96e584d5-780c-4688-ae94-269ce11b8cde)


