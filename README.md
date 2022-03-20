# VBA Challenge
## Overview of Project
The analysis was intended to give a user a clear picture of how 12 stocks performed over 2017 and 2018 taking into consideration beginning and ending values as well as the volume that each stock was traded in each year.

## Results
Based on the results its clear that in 2017 all stocks except for "TERP" gave a positive rate of return while in 2018 all stocks except for "ENPH" and "RUN" gave a negative rate of return. "DQ" which was of high interest by Steve and his parents had a return of 199.45% in 2017 and a negative return of 62.6% in 2018, suggesting that the stock is relatively volatile and more intrinsic data would be needed to confidently recommend whether this would be a good investment. It is also worth mentioning that after refactoring code to efficiently store values with arrays and redesigning the structure of the code I was able to reduce the run time of the program by a third 33%. The 2017 all stock analysis ran in 0.4375 seconds and the 2018 all stock analysis ran in 0.4453
![image](https://user-images.githubusercontent.com/99148657/159142260-a5711359-6b4e-4841-9e6a-425bd9a1600a.png) ![image](https://user-images.githubusercontent.com/99148657/159142272-edb4d52f-57ba-4006-86af-2921afc0e6fb.png)

![VBA_Challenge_2017](https://user-images.githubusercontent.com/99148657/159142324-69b3eaff-d5af-4d5b-ad3d-715dc69e2d3c.PNG)    ![VBA_Challenge_2018](https://user-images.githubusercontent.com/99148657/159142390-3e116a08-9470-4bfa-8b0e-478500375f09.PNG)

## Summary
1. What are the advantages or disadvantages of refactoring code?
    * Refactoring code is an important process when working with large datasets, limited computing power or complex programs. It is important to design the project in    such a way that the code runs as efficiently as it can when any one of these issues are present. Refactoring code is also useful for making the code more readable
    * On the other hand, if refactoring the code only changes the processing time bu a negligible rate, then the time that was invested in doing so would have been wasted, especially if that came with having to debug new errors. 


How do these pros and cons apply to refactoring the original VBA script?
   * Refactoring our original script helped to reduce the processing time by a significant rate. If the dataset were to be expanded the code would be easily adaptable and would also run more efficiently.
   * In real values, saving 2 tenths of a second would not be worth the time invested in refactoring this code if that was the main purpose of doing so. It is basically unnoticable, even if it were to be refined further.
