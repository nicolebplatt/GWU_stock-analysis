# Stock Analysis
Module 2 for BCS

## Overview of Project
The purpose of this project was to analyze 12 different stocks in 2017 and 2018 for Steve and his parents. Over the last week, I have been slowly building code to perform such an analysis. The main goal of this project is to refactor the code to better operationalize it and confirm whether refactoring the code made things run more efficiently.

## Results
### Stock Performance
Overall, the stocks analyzed in this project saw a much better year in 2017 than 2018, as you can see from the below images. In 2018, only two stocks saw positive returns, ENPH and RUN.

![2017 Stock Results](https://user-images.githubusercontent.com/99286327/156896839-c954e0c3-ba86-428d-a13d-2dbf9454ade2.png)
![2018 Stock Results](https://user-images.githubusercontent.com/99286327/156896841-b0b2c78c-d50d-4550-97d3-38abdf85c8ea.png)

Steve's parents were paying particular attention to the stock DAQO. While the stock performed well in 2017 with a return of almost 200% (the highest annual return of all the stocks in this analysis), DAQO had a negative return of 62.6% in 2018 (the lowest annual return of all the stocks in this analysis). These large swings indicate DAQO is a bit of a risky option.

### Code Execution Time
Before refactoring, my original code took 0.777 seconds to run 2017 data and 0.793 seconds to run 2018 data. 

![2017 Original Macro](https://user-images.githubusercontent.com/99286327/156896837-3a39f60d-dc87-4f1c-95e2-161a552402f8.png)
![2018 Original Macro](https://user-images.githubusercontent.com/99286327/156896840-31b131e8-3793-44e1-9141-ff2372f6ad73.png)


After refactoring, 2017 took 0.188 seconds and 2018 took 0.168 seconds. Clearly, refactoring improved run time.

>Note: The original script did not include formatting but the refactored code did. 


![VBA_Challenge_2017](https://user-images.githubusercontent.com/99286327/156896842-328c5538-abc6-4645-bb18-05c2bccf4a2b.png)
![VBA_Challenge_2018](https://user-images.githubusercontent.com/99286327/156896843-e3114cf0-50af-48ea-ae97-446a7e712184.png)

## Summary
Since the goal of this project pertained to refactoring code and determining usability, it's therefore important to review a few general advantages and disadvantages of refactoring code.

### Advantages
If successful, refactoring code aims to make code logic more seamless and reduce inefficiencies. This helps reduce memory in terms of storage and increases speed of execution.

### Disadvantages
Refactoring by nature does not add any new functionality or purpose, so it's not incredibly useful if you're looking to improve anything other than speed. Additionally, because refactoring is based on prior code, it can be cumbersome investigating someone else's code to determine if refactoring might be useful.

### This Refactor 
Personally, I found the refactoring to be incredibly time consuming. Modifying code that worked and transforming certain variables into arrays caused painfully long hours devoted to debugging and understanding errors. While I was able to improve run time by a fraction of a second, I do not believe the hours spent refactoring was worth it.


