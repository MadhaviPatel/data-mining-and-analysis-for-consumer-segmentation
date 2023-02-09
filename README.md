# data-mining-and-analysis-for-consumer-segmentation
Artificial Intelligence
• Python 3.7
• Jupyter notebook Steps to Implement
• numpy
• Pandas
• Datetime
• openpyxl
Steps to implement
• Create a new Environment
• Download Online retail.xlsx and give proper path
• Run the code cell by cell
Idea
We've given you the task of doing data mining and analysis to do consumer segmentation from given online retail data in this assignment. I divided customers by RFM score (Recency, Frequency, and Monetary Score) after performing Recency, Frequency, and Monetary analysis on the given data. Here's a quick rundown of what RFM is all about.
I applied below mention step in program
- Step 1
The data is read using the pandas read excel method, and I simply implemented openpyxl using pip to run it. I also get an overview of the data by using the info() method to get the column names, datatypes, and sizes of each column.
- Step 2
Remove null values and only look at data with a value greater than 0.
In this step, I checked for null values in the data and removed them from the dataframe to improve the results.
After removing null values
- Step 3
Make a total cost calculation.
I simply multiplied quantity by unit price to get the total price paid by the customer.
- Step 4
Locate the most recent purchase date and adjust the current date accordingly.
Because the dataset is too old, I find the most recent purchase date and use that to set the current date, ensuring that the result is unaffected.   
- Step 5
Dataframe segmentation and ranking based on recency, frequency, and monetary value  
- Step 6
After completing all of the steps above, I used the RFM Score to find the answers to the professor's questions.
   
    
