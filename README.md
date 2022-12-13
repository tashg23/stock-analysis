# stock-analysis

## Objective: 
To analyze the performance of 12 stocks for the years 2017 and 2018 by calculating the volume and return of each stock. 

### Results: 
- Based on the 'Return' column, the stock market performed very well in 2017 and investors would have made a positive return on their investment, except for those that invested in the stock "TERP" 

![VBA_Challenge_2017_Results](https://user-images.githubusercontent.com/113721712/207429706-1c12b641-6768-4855-911e-67ad7d03c622.png)

- Alternatively, the stock market did not perform well at all in 2018 except for two stocks - "ENPH" and "RUN" 

![VBA_Challenge_2018_Results](https://user-images.githubusercontent.com/113721712/207429930-101934dc-9e34-4998-ac53-aee3b8ccd7a6.png)

### Summary: 
The advantages of refactoring code are: 
- Improvements in performance 
- Makes code easier to understand 

The disadvantages of refactoring: 
- Time consuming 

The advantages of the refactored code in comparison to the original is firstly that it can be used for any year of data based on user input. Also, no nested loops were used; instead 3 separate for loops were used which makes the code easier to read and understand. Due to the refactoring, the performance of the code improved. For 2017, the original code took 0.79 seconds to run (see image below). 

![VBA_Challenge_2017_original code](https://user-images.githubusercontent.com/113721712/207432175-2e6d87b0-6c6e-4484-99fb-662ade5edc1d.png)

However, the refactored code only took 0.063 seconds to run for the 2017 dataset. 

![VBA_Challenge_2017](https://user-images.githubusercontent.com/113721712/207432345-30e5bb68-625c-44e9-b4dc-11c64e033bd2.png)



