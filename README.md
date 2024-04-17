# Bike Sharing Assignment
> build a `multiple linear regression model` for the `prediction` of demand for shared bikes.

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Python Libraries used in Multiple Linear Regression Model](#acknowledgements)
* [Acknowledgements](#acknowledgements)


## General Information
- Provide general information about your project here.
  To model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly 
  manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 
  
- What is the background of your project?
  A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.
  A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. So, it has decided to come up with a mindful business plan to be able to 
  accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

- What is the business probem that your project is trying to solve?
  To understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will 
  be a good way for management to understand the demand dynamics of a new market. 


- What is the dataset that is being used?
  `Bike Sharing dataset`

  
## Conclusions
- Our final multiple linear regression model aims to predict bike bookings based on a set of predictor variables. After thorough analysis, we have identified the impact of each variable on bike bookings.
- The top `three` predictor variables that significantly influence bike bookings are as follows: <br>
  `Year (yr)`: Focus on understanding and leveraging the increasing trend over the years.<br>
  `Temperature (temp)`: Consider the positive impact of temperature on bike bookings and plan activities accordingly.<br>
  `Windspeed`: Be mindful of the negative impact of windspeed on bike bookings and plan strategies to mitigate its effects.<br>

- Inference of categorical Variables<br>
	`Fall` season got more bookings than Summer, Winter, Spring. And ‘Spring’ season had minimum bookings amongst all.
	September was the best month with maximum bookings, followed by October. Bookings trend increasing starting from January till October and then it started decreasing as last month arrived.
	In ‘Clear weather’, people opted for more bookings and in ‘Light Rain Thunder’ people travelled less.
	‘Thursday, Friday, Saturday and Sunday have more number of bookings as compared to ‘Monday and Tuesday’.
	‘Sunday’ has least bookings, as people may want to spend time with family and for recreational activities.
	Bookings trend is almost similar on working day or week-off days.


## `Python Libraries` used in Multiple Linear Regression Model:
- statsmodels
- sci-kit learn
- numpy, pandas
- matplotlib, seaborn


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@Sourav-sharma9693] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
