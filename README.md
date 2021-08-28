# Module 2 Challenge for UC Berkley Data Analytics Bootcamp - VBA of Wall Street

## Overview of Project

### Purpose

The purpose of this analysis is to use historical stock market data to determine price returns various stocks have generated historically and total trading volume. Steve would like to use the output in order to guide investment decision. 

The code is written to calculate returns and total trading volume for a dozen stocks but it works well for thousands of stocks as well.
 
## Results

### Stock Performance in 2017 and 2018
The two charts below show returns and total trading volume of a 12 renewable energy stocks in 2017 and 2018. In 2017, 11 out of 12 stocks posted positive returns. In 2018, only 2 out of 12 stocks posted positive returns.

![Stock Return in 2017](/Resources/VBA_Challenge_2017_Chart.png) 
 
![Stock Return in 2018](/Resources/VBA_Challenge_2018_Chart.png) 


### Execution times of scripts
This code refactors existing code in Module 2 solution code to loop through all the data one time in order to collect the same information we did in past exercise. This  reduced the amount of time it would take to execute the VBA code. As can be seen in the following two charts, refactoring code reduced the time to execute significantly. 

![Execution time 2017](/Resources/VBA_Challenge_2017.png)
 
![Execution time 2018](/Resources/VBA_Challenge_2018.png) 

## Summary
### What are the advantages and disadvantages of refactoring code?

Advantages of refactoring:

- Refactoring helps with executing the code faster and improve performance of software/analysis.
- - Refactoring improves the design of scripts and makes code easier to understand.

Disadvantages of refactoring code

- Refactoring is a time consuming process but may be worthwhile for large data sets and time consuming scripts. 

### How do these pros and cons apply to refactoring the original VBA script?
- Refactoring the existing code removed the key nested loop for displaying ticker, daily volume, and annual return to move to a single loop. This reduced the time to execute the script.
- Refactoring reduced the complexity of using conditionals statements inside Loops.  
