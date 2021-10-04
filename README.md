# VBA_Challenge

## Overview of Project

Since VBA is often use on the financial industry a stock analysis was conducted based on the information given at module 2. 

Steve just graduated from finance, and wants to help his parents invest their money on the right stock. Using VBA and automated analysis was created it to filter differrente stock data. With the click of a buttom Steve was able to analyze and entire data set in seconds. 

![Captura de Pantalla 2021-10-03 a la(s) 9 49 29 p  m](https://user-images.githubusercontent.com/37987602/135790049-c8dd5dc4-a721-46c7-9760-c4e1a44aef1b.png)



Now he wants to expand the data set to include the entire stock market over the las few years. Undestand that VBA code workd well for a dozen stocks, but let see how well it perfomrs for thousands, keeping in mind that time is an important factor lets see how can we reduce the run time fot this sctipt. 

To acomplish this we must refactor the code in order to loop through all the data one time in order to colelect the same information collected on our first project. 

>Reefactoring makes code more efficient
> - by taking fewer steps, 
> - using less memory, 
> - or improving the logic of the code to make it easier for future users to read


## Results

### Stock performance between 2017 and 2018

![Refactor2017](https://user-images.githubusercontent.com/37987602/135791836-e6be01f8-1aed-4ab7-af58-21084d01b0e0.png)
![Refactor2018](https://user-images.githubusercontent.com/37987602/135791869-dc76ab45-ad0a-4891-ada3-bd40bb986f72.png)

### Code Analysis


### Execution times of the original script and the refactored script.

#### Original Scipt Run Time

![green_stocks_2017](https://user-images.githubusercontent.com/37987602/135791395-7dc152c1-335a-4ee8-b560-a04db6ec18d0.png)
![green_stocks_2018](https://user-images.githubusercontent.com/37987602/135791407-d4399ff4-49a0-49f1-a8b8-4d1832414cc8.png)

#### Refactored Scipt Run Time

![VBA_Challange_2017](https://user-images.githubusercontent.com/37987602/135791422-8bc52dbc-a1b1-4183-9158-751ca1e25da7.png)
![VBA_Challange_2018](https://user-images.githubusercontent.com/37987602/135791427-5c081f87-80eb-400f-ac8b-2205714439b0.png)

## Summary
![Summary](https://user-images.githubusercontent.com/37987602/135792060-a5b32f04-037c-464b-8f9c-2a6a980a17f0.png)

### What are the advantages or disadvantages of refactoring code?

Advantages 
 - Makes your code run faster, because less memory is used
 - Makes your code more simple, because fewer steps are taken

Disadvantages 
 - It might make code that works, NOT work anymore. Editing code is sometimes dangerous when you are tired(misspelling)
 - Its time consuming, and also if not done right it might just be in vane. 


### How do these pros and cons apply to refactoring the original VBA script?

Well, it did take me some time to understand the changes, a lot of trial and error. I did some things that worked on one script but not on the other. Kept on changing thinsg here and there to se what worked until finally it was done. I dont thing refactoring is very usefull on this code because is not that mucho of a long taskt, but i am sure it might be useful with hevier data sets. 



