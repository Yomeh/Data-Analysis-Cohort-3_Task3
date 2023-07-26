# Task Three
The 3rd task assigned for the Data analysis training with **Promise Chinoso**

# Introduction
Advancing further into the data analysis cohort, I began to learn about advanced functions such as VLOOKUP, HLOOKUP, XLOOKUP, SUMIF, COUNTIF, etc. For this task, I used the previous sales dataset provided by the instructor which is made up of 12 columns and 701 rows. 

# Problem Statement
1. Calculate the average revenue generated from each sale of Paseo
2. Calculate the number of sales made in the Government and Midmarket segments.
3. Calculate the total revenue generated from the sales of Montana in Canada.
4. In which country, segment, and month was the highest unit sold
5. Calculate the total profit in December

# Skills Demonstrated
1. Data Manipulation
2. Use of the Sum function
3. Use of the Average function
4. Use of the Max function
5. Use of the VLOOKUP function
7. Use of the COUNTIF function

# Methodology

# Raw Data
![Screenshot (8)](https://github.com/Yomeh/Data-Analysis-Cohort-3_Task3/assets/140501792/d9f26ffa-4738-400f-ac3b-75476c1e72d5)
# Interpretation
![Screenshot (9)](https://github.com/Yomeh/Data-Analysis-Cohort-3_Task3/assets/140501792/3abc9a6f-3b83-4851-b8bb-396219eedb68)
#
# Average Revenue Generated from Paseo Sale
I used the *Averageif* function which calculates the average of a range when it meets a specified condition, to get the average revenue from paseo sales I specified that only the average from the product "paseo" should be calculated. The syntax is given as: **=AVERAGEIF(product range,"Paseo",Sales range)**

# Number of Sales Made in Government and Midmarket Segment
I used the *sumif* function which adds up the values for the specified condition met for Government and Midmarket. To get the number of sales made in the government and midmarket segment, the condition to be met was for the segment column to be government and midmarket. The syntax was as follows: **=COUNTIF(segment range, "Government")** vice versa for midmarket

# Total Revenue Generated From The Sales of Montana in Canada
I used the *sumifs* function which allows to specify multiple conditions to be met before adding up the values in the sum range. In this instance, the sum range was the sales range and the condition we specified to be met are: the country must be Canada and the product must be Montana. The syntax is: **=SUMIFS("sale_range,"product_range,"Montana","country_range,"Canada")**

# In Which Country, Segment, and Month was the highest unit sold
To get these values, I used the *VLOOKUP* function which allows you to look across the rows and columns of a table for a value. I inputted the MAX formula as the lookup value for these functions because we're looking for the highest amount of units sold from the country, segment, and month range.

# Total Profit in December
I used the *sumif* function to calculate the value of profits if they fall in the month of December.

Conclusion
This task required a lot of critical thinking and a firm knowledge of the advanced Excel functions. I was able to apply the knowledge from the training and practiced personally, so as to get familiar with these advanced functions.


