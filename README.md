# JoynerWedge
A repository for my Wedge Project for ADA 2021
In this repository you will find 3 jupyter notebooks. 
Notebook 1: uploads all of the wedge data that is clean.
Notebook 2: Takes all of the clean data and gets a random sample of owners not including card_no 3. It then takes those card owners and pulls all of their records and writes that out to a csv file.
Notebook 3: Makes summary tables from the wedge files and then sends those tables to a local database created in the code.

Some notes on the code:
You will need the clean wedge files. In notebook 1, I had the clean files located in a folder called Clean-Files. I have not included that data in the repo.
In notebook 1, For the loop to run, I had 2 copies of the clean data, one in that folder and one in the working directory. 
You can get around this by just making the working directory be where you look for the data, just be careful as you might not only upload the clean files or get an error in the middle of your loop. 
You will also need to have a GBQ database set up and have access to that from python. 
There are times where I include multiple solutions to what we are doing. Either work, some are just more efficient (pandas).

If you have any questions, feel free to reach out!