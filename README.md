# stock-analysis
# Analysis on stock market investments


## Overview of Project

The purpose of this project is to analyze stock market tendencies over few years based on provided data to determine the best investment opportunities. And refactor the code to make it more efficient.

## Results

Analysis of the performance of different stocks on the stock market ([Figure 1](https://github.com/xenia-e/stock-analysis/blob/main/Resourses/all_stocks_2017_table.png) and [Figure 2](https://github.com/xenia-e/stock-analysis/blob/main/Resourses/all_stocks_2018_table.png)) shows the overall crash of the market in 2018, with only two stocks that performed well (Enphase Energy (ticker ENPH) and Sunrun (ticker RUN)

![Figure 1 - Stock Performance Analysis in 2017](https://github.com/xenia-e/stock-analysis/blob/main/Resourses/all_stocks_2017_table.png)

>Figure 1 - Stock Performance Analysis in 2017


![Figure 2 - Stock Performance Analysis in 2018](https://github.com/xenia-e/stock-analysis/blob/main/Resourses/all_stocks_2018_table.png)

>Figure 1 - Stock Performance Analysis in 2018

### Refactoring

Refactoring the existing VBA code helped us improve execution time by almost twice. See figures 3 and 4.

![Figure 3 - Code execution time before refactoring](https://github.com/xenia-e/stock-analysis/blob/main/Resourses/VBA_Challenge_2018_before_ref.png)

>Figure 3 - Code execution time before refactoring


![Figure 3 - Refactored Code Execution Time](https://github.com/xenia-e/stock-analysis/blob/main/Resourses/VBA_Challenge_2018.png)

>Figure 4 - Refactored Code Execution Time

## Summary: 

1. Refactoring code is a big part of programmers' work. Code Refactoring makes the code more extensible, helps in increasing the flexibility of the code. It makes code more efficient, easier to understand or read, less complex, and easier to maintain. 

  1.1 In my opinion, the main **disadvantage of code refactoring** is that it is time-consuming and means expensive. It may introduce new bugs. 

2. Since **refactoring** is just to change the structure of the code base, not its behavior, the results of executing refactored code are still the same. Following the rule ***DRY*** we eliminated repeating in our code and boost performance, as the refactored code has fewer lines and is quick to respond because of its simplicity. Our code is short to introduce any errors. Still, it takes more attention and understanding of programming principles to understand what we are doing without adding comments. 
