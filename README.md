# Bikes Case Study

### Problem Statement:
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Conclusions
R- Sqaured train: 0.84 Adj. R-Squared train: 0.838

R- Sqaured test : 0.82 Adj. R-Squared test : 0.81

Variable's Coefficents :

const:                             0.291  
yr:                                0.231  
workingday:                        0.052  
temp:                              0.479  
hum:                              -0.145  
windspeed:                        -0.176  
season_spring:                    -0.108  
season_winter:                     0.057  
mnth_July:                        -0.077  
mnth_September:                    0.057  
weekday_Sat:                       0.062  
weathersit_LightSnowLightRain:    -0.250  
weathersit_MistCloudy:            -0.059  



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
The equation of our best fitted line is:

𝑐𝑛𝑡=0.291+(0.231×𝑦𝑟)+(0.052×𝑤𝑜𝑟𝑘𝑖𝑛𝑔𝑑𝑎𝑦)+(0.479×𝑡𝑒𝑚𝑝)−(0.145×𝐻𝑢𝑚𝑖𝑑𝑖𝑡𝑦)−(0.176×𝑤𝑖𝑛𝑑𝑠𝑝𝑒𝑒𝑑)−(0.108×𝑠𝑒𝑎𝑠𝑜𝑛_𝑠𝑝𝑟𝑖𝑛𝑔)+(0.057×𝑠𝑒𝑎𝑠𝑜𝑛_𝑤𝑖𝑛𝑡𝑒𝑟)−(0.077×𝑚𝑛𝑡ℎ_𝐽𝑢𝑙𝑦)+(0.057×𝑚𝑛𝑡ℎ_𝑆𝑒𝑝𝑡𝑒𝑚𝑏𝑒𝑟)+(0.062×𝑤𝑒𝑒𝑘𝑑𝑎𝑦_𝑆𝑎𝑡)−(0.250×𝑤𝑒𝑎𝑡ℎ𝑒𝑟𝑠𝑖𝑡_𝐿𝑖𝑔ℎ𝑡𝑆𝑛𝑜𝑤𝐿𝑖𝑔ℎ𝑡𝑅𝑎𝑖𝑛)−(0.059×𝑤𝑒𝑎𝑡ℎ𝑒𝑟𝑠𝑖𝑡_𝑀𝑖𝑠𝑡𝐶𝑙𝑜𝑢𝑑𝑦)

## Technologies Used
- numpy version: 1.21.5
- pandas version: 1.4.2
- seaborn version: 0.11.2
- matplotlib version: 3.5.1
- Missingno Version : 0.4.2



## Acknowledgements
- This project was inspired by upGrad Course.
- References:
-  https://en.wikipedia.org/wiki/Anscombe%27s_quartet![image](https://user-images.githubusercontent.com/73323691/188327785-fcb598f8-9e2d-412c-a210-2266ff64df09.png) (To get the history and data for Anscombe's quartet datasets)

- This project was based on [upGrad_MSC_Course]


## Contact
Created by [@nadeem] - feel free to contact me!
