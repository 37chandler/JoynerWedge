
# Applied Data Analytics

## Wedge Project

<!-- I think the project was fair in difficulty. I would not have been able to complete it without the help of you in labs and classmate contributions. It would have been nice to have an example output for each sql statement for part 2 and 3. I am more of a visual person, so being able to see an example of what the output should look like would have been helpful--> 

### Task 1

* Files for this task: 
<!--  Step1.ipynb --> 

Loads all data into GBQ data set.

`Step1.ipynb`: 
Loads all of the data into GBQ. There is a manual upload way and a loop way of uploading. Both are on display. The Manual way of uploading is more time consuming as you have to change the file name each upload. The loop method does this for you.

<!--  Repeat for each file  --> 



### Task 2

* Files for this task: 
<!--  Step2.ipynb --> 

Retrieves all records from random sample of card-owners not including non-members.

`Step2.ipynb`: 
This file showcases how to get a random sample of card-owners in the first sql query. You will need to run that query in GBQ and then save the results as its own table. I couldn't find a way to do that all via code without repeating parts of step 1. After that, the next query takes a random sample of those card numbers and pulls all records in the dataset of that random sample. The code then writes those results to a txt file. I showcase two ways of doing this, one without pandas, one with. I reccomend the pandas method, as it does everything you need in a quicker and cleaner fashion.
 
	

### Task 3

* Files for this task: 
<!--  Step3.ipynb --> 

This code creates summary tables for the wedge dataset. 

`Step3.ipynb`: 
This code starts with three sql querys that we need to run to get our summary tables. It then creates a local sqlite database. Then pandas sends each query result to the database as its own table.
<!--  Repeat for each file  --> 


## Query Comparison Results

Fill in the following table with the results from the 
queries contained in `gbq_assessment_query.sql`. You only
need to fill in relative difference on the rows where it applies. 
When calculating relative difference, use the formula 
` (your_results - my_results)/my_results)`. 



|  Query  |  Your Results  |  My Results | Difference | Rel. Diff | 
|---|---|---|---|---|
| Total Rows  |85760139|85760139|0|   |
| January 2012 Rows  |1070907|1070907|0|   |
| October 2012 Rows  |1042287|1042287|0|   |
| Month with Fewest  |Feb|Feb|No| NA  |
| Num Rows in Month with Fewest  |6556770|6556770|0|   |
| Month with Most  |May|May|No| NA  |
| Num Rows in Month with Most  |7578372|7578372|0|   |
| Null_TS  |7123792|7123792|0|   |
| Null_DT  |0|0|0|   |
| Null_Local  |234843|234843|0|   |
| Null_CN  |0|0|0|   |
| Num 5 on High Volume Cards  |14987|14987|No| NA  |
|  Num Rows for Number 5 |460630|460630|0|   |
| Num Rows for 18736  |12153|12153|0|   |
| Product with Most Rows  |Banana Organic|Banana Organic|No| NA  |
| Num Rows for that Product  |908639|908639|   |   |
| Product with Fourth-Most Rows  |Avacado Hass Organic|Avacado Hass Organic|No| NA  |
| Num Rows for that Product  |456771|456771|0|   |
| Num Single Record Products  |2769|2769|0|   |
| Year with Highest Portion of Owner Rows  |2014|2014|No| NA |
| Fraction of Rows from Owners in that Year  |.7591|.7591|0|   |
| Year with Lowest Portion of Owner Rows  |2011|2011|No| NA |
| Fraction of Rows from Owners in that Year  |.7372|.7372|0|   |

## Reflections

<!-- If I were to do this project again, I probably would have slowed down and not get so jumpy. I mean that in I probably didn't need to waste about 48 hours of my time in uploading the data 4 times. If I would have just played it safe and done my due diligence with everything, I would have saved myself a couple of headaches. I enjoyed the project after all of the uploading issues dissipated. There were times where pandas felt like it was making my life way easier than it would have been with out it. Pandas is probably the only reason I am done at week 8.   --> 
