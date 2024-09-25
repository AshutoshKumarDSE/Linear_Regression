# Project Name
> Bike Sharing Case Study
> This case study is part of the requirement for Executive PG Diploma program of UpGrad in collaboration with IIIT Bangalore.
> It has a detailed Jupyter Notebook, answers to subjective questions as pdf and the data used for the study
 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 



- In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. 
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 
- The company wants to know:

    Which variables are significant in predicting the demand for shared bikes.
    How well those variables describe the bike demands
What is the business probem that your project is trying to solve?
- The dataset used is provided to us for two years on cnt along with few categorical and numerical features


## Conclusions
- For seasons the value 3(Fall) has the highest median cnt
- For yr 2019(which is coded as 1) has the highest median cnt
- Among months july seems to have the highest median
- median cnt is higher for non-holidays
- For weathersit the category 1(Clear, Few clouds, Partly cloudy, Partly cloudy) has the highest median cnt
- Working day seems to have the same impact as no working day on median cnt

- The correlation between cnt and temp along with correlaƟon between cnt and atemp is very high.
- yr, const, atemp, season_winter, weekday_sun, mnth_sep are the top five positive drivers to cnt
- mnth_nov, temp, season_spring, workingday, weathersit_cloudy are the top five negative drivers to cnt

the linear regression equation is below

cnt = 2831.0805*const + 3778.3653 * yr + 2018.3781 * atemp + 813.5149 * season_winter +445.2129 * weekday_sun +
    435.4007 * mnth_sep + 402.3615 * windspeed + 360.0866 * mnth_mar + 314.9842 * mnth_may +-469.9609 * weathersit_misty
    -479.9611 * mnth_dec -564.0854 * mnth_jul -648.2251 * mnth_nov -904.9624 * temp -1124.5386 * season_spring
    -1491.7928 * workingday -1841.5558 * weathersit_cloudy




## Technologies Used
- library - Pandas, NumPy, Scikit-learn
- library - Statsmodel
- library - Jupyter Notebook

## Acknowledgements
Give credit here.
- This project was inspired by the instructors at IIIT Bangalore and UpGrad
- [References if any...](https://www.kaggle.com/code/pythonafroz/pipeline-step-by-step-guide)
- This project was based on [this tutorial](https://scikit-learn.org/stable/).


## Contact
Created by @AshutoshKumarDSE - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
