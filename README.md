# Bike Sharing Assignment
> This assignment is a programming assignment wherein you have to build a multiple linear regression model for the prediction of demand for shared bikes. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
> Problem Statement
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share     > systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks  > it. This bike can then be returned to another dock belonging to the same system.
> 
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very > difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as   > the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
> 
> In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation   > due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other   > service providers and make huge profits.
> 
> They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the > factors affecting the demand for these shared bikes in the American market. The company wants to know:
> 
> Which variables are significant in predicting the demand for shared bikes.
> How well those variables describe the bike demands
> Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American     > market based on some factors. 
> 
> Business Goal:
> You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the   > demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations.       > Further, the model will be a good way for management to understand the demand dynamics of a new market. 
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
> As per our final Model, the top 3 predictor variables that influences the bike booking are:
> - Temperature (temp) - A coefficient value of ‘0.4486’ indicated that a unit increase in temp variable increases the bike hire numbers by 0.4486 units.
> - Weather Situation (Light_snowrain) - A coefficient value of ‘-0.2907’ indicated that, w.r.t Light snow rain, a unit increase in Light_snowrain variable decreases the bike hire numbers by 0.2907 units.
> - Year (yr) - A coefficient value of ‘0.2341’ indicated that a unit increase in yr variable increases the bike hire numbers by 0.2342 units.
> So, it's suggested to consider these variables utmost importance while planning, to achive maximum Booking

> The next best features that can also be considered are
> - Spring season: - A coefficient value of ‘-0.1117’ indicated that w.r.t spring season, a unit increase in spring variable decreases the bike hire numbers by -0.1117 units.
> -windspeed: - A coefficient value of ‘-0.1393’ indicated that, a unit increase in windspeed variable decreases the bike hire numbers by 0.1393 units.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - Datetime, pandas, numpy, pandas, seaborn, matplotlib.pyplot, sklearn, statsmodels.

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by [@[amit23114](https://github.com/amit23114)] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
