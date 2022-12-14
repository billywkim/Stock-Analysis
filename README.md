# VBA of Wallstreet

## Overview of Project

The purpose of this project was to create a VBA code that will automatically calculate the yearly return of each stock so that someone can decide which stock is best to invest in. The purpose of this specific challenge was to recreate the original code on this workbook so it is more efficient and is processed faster. 

## Results

After running the script and looking at the results, one can clearly see that the stocks in 2017 were much more profitable than the following year. However, there are only 2 stocks that outstand the others by generating positive returns (ENPH and RUN). These stocks are clearly the best stocks to invest in for future returns. 

![Results 2017](https://user-images.githubusercontent.com/88448731/185767131-f926fabf-62a2-4351-9540-8951248b49c0.PNG) ![Results 2018](https://user-images.githubusercontent.com/88448731/185767135-8f5d1715-a81b-4148-a904-684019709938.PNG)

After refactoring the code, the script runs more efficient and uses less memory. Below, you can find the run time for the year 2017 before refactoring and after, respectively. Clearly, refactoring made a drastic difference in the run time of the code.

![Run time before Refactoring](https://user-images.githubusercontent.com/88448731/185767456-d22cd8a7-d812-4f9b-8995-73a2ec79953f.PNG) ![VBA_Challenge_2017](https://user-images.githubusercontent.com/88448731/185767460-bfdd2d53-f879-44b8-a7dd-a9db737433a2.PNG)

## Summary

### Advantages and disadvantages of refactoring code

When a code is refactored correctly, the advantages heavily outweigh its disadvatages for both, the programmers and its users. A refactored code is much cleaner and facilitates debugging and maintenance. The script would also run faster, which would provide less stress to the computer. However, some disadvantages of refactoring may include risk when the application is too big. If not processed correctly, refactoring may also add additional bugs and errors into the code and may take more time and money to fix.

### Application of pros and cons to the refactored VBA script

When refactoring was completed, the biggest advantage was its runtime. Before refactoring, the script for 2017 ran in 0.44 seconds and while it only took 0.07 seconds after (see images above). However, refactoring a code from its original script took a long time. Most of the time was spent debugging and figuring out what was causing the errors from running properly. 
