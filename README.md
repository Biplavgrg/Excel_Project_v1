This is an excel project using international coffee data of UK Ireland and United States.

In this project, I have used the raw data of the internation Coffee data, which I show case my ability to work with raw data in order to clean, process, analyse and visualise the data by creating pivot tables in order to create an interactive dashboard.

- I start off by cleaning the data by checking for duplicate entries using basic filter tool.
- I then use XLOOKUP to find the data from the different worksheets in order to populate the main coffee_orders worksheet.
- I also use INDEX Match function to populate the 'Coffee Type' field.
- I decided to create a new 'Coffee Type Name' column, as the initial 'Coffee Type' column is a shorter abbreviation to ensure complete transparency for the reader. I have incorporated a multiple IF function to perform this. 
- I repeated this step for the new 'Roast Type Name', to give a full name for the type of roast of the coffee.
- Next I spend a little time formatting the data to ensure best practise for claritiy. For instance the 'Order Date' column was changed to a custom 'dd-mmm-yyy'. This gives the months in writter format so it is easyy to differentiate between the months and day as there are many different date formats according to the locale. 
- I also ensure to add number formats to each columns in need of units and/or currency. 
- Before moving on to the pivot table/chart for analysis and visualisation, I convert the range to a table for the convenience of updating the pivot table automatically following the addition or removal of columns. 
-
