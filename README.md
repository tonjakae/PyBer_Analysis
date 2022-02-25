# PyBer_Analysis
## Deliverable 1: A ride-sharing summary DataFrame by city type
### Deliverable 1 Requirements
* The total number of rides for each city type is retrieved

![image](https://user-images.githubusercontent.com/87340105/155786417-16b87a60-4c7f-4aff-b673-7b327e4cb4a0.png)

* The total number of drivers for each city type is retrieved

![image](https://user-images.githubusercontent.com/87340105/155786490-4a7206f6-0f75-400f-8f46-5dd044bd2467.png)

* The sum of the fares for each city type is retrieved

![image](https://user-images.githubusercontent.com/87340105/155786569-cfd484d7-4749-441b-bdcf-9aa17c3c36f6.png)

* The average fare per ride for each city type is calculated

![image](https://user-images.githubusercontent.com/87340105/155786851-d2cc426a-0c52-4690-9229-7639d41729b2.png)

* The average fare per driver for each city type is calculated

![image](https://user-images.githubusercontent.com/87340105/155786952-92ad7c8f-39bd-4f71-9666-f61ed94d2ddb.png)

* A PyBer summary DataFrame is created

![image](https://user-images.githubusercontent.com/87340105/155787062-5fc8d4f3-9dfa-4e80-ac7e-0f99efccea23.png)
![image](https://user-images.githubusercontent.com/87340105/155787274-43d06134-ef41-4857-8d37-a5340c57616f.png)

* The PyBer summary DataFrame is formatted as shown in the example
![image](https://user-images.githubusercontent.com/87340105/155787845-c3b13913-5f21-4bc3-932b-0c1ed8cefe26.png)


## Deliverable 2: A multiple-line chart of total fares for each city type
### Deliverable 2 Requirements

* A DataFrame was created using the groupby() function on the "type" and "date" columns, and the sum() method is applied on the "fare" column to show the total fare amount for each date and time
* A DataFrame was created using the pivot() function where the index is the "date," the columns are the city "type," and the values are the "fare."
* A DataFrame was created using the loc method on the date range: 2019-01-01 through 2019-04-28
* A DataFrame was created using the resample() function in weekly bins and shows the sum of the fares for each week
* An annotated chart showing the total fares by city type is created and saved to the "analysis" folder

## Deliverable 3: A written report for the PyBer analysis
