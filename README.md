# Data Cleaning Using Pandas
The data cleaning using pandas tasks are divided into two. Each task touches upon a variety of aspects of data cleaning in pandas. 
## TASK 1
A CSV file containing 29 rows and 7 columns namely: Index, Age, Salary, Rating, Location, Established and Easy Apply.
-	The columns contain null values, incorrect values and messy data that is cleaned step by step column-wise in the Jupyter Notebook file. 
-	Explanations of each task are added in the ipynb file as well. 
<br> <br>
### Challenges
As a beginner approaching data cleaning in pandas, there were some challenges in regards to a few columns. The Location column took an elaborate approach to clean up. Upon completion of the task, I realised that the column could have been cleaned more easily using the `.replace()` function. Therefore, my challenge in task 1 was to stick to the basics of data cleaning logic which is something to work towards continuously. 
## TASK 2
A TSV file containing chipotle order data with 4622 rows and 5 columns namely: Order Id, Quantity, Item Name, Choice Description and Item Price
-	While the data in the file was not as messy when compared to task 1, the text-heavy nature of the dataset introduced a new layer to data cleaning.
-	The steps and processes undertaken during the data cleaning process are explained in the Jupyter Notebook file for task 2. Some fundamental analysis was also conducted on the cleaned dataset.
-	Additionally, cleaned data summarising order_id and item details were also extracted along with the cleaned chipotle file.
<br> <br>
### Challenges
I faced a grave challenge when approaching the choice_description column. Ultimately, I settled on counting the number of choice descriptions. As detailed in the challenges of task 1, perhaps an answer to extracting individual items in choice_description was more straightforward but I could not reach to it. 
