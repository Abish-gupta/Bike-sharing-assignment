# Bike Sharing Assignment
> A bike-sharing system is a service designed to provide bicycles for short-term use, either for a fee or free of charge. These systems often employ a network of computer-controlled docking stations, where users can securely rent and return bikes. By entering payment details or a membership credential, users can unlock a bike from one location and return it to another dock within the same network, offering flexibility and convenience for urban transportation.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The company seeks to understand the key factors influencing the demand for shared bikes in the American market.
    - They are specifically interested in identifying the variables that significantly impact the prediction of bike demand.
    - Additionally, the company wants to evaluate how effectively these variables explain the fluctuations in bike demand.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - version 1.23.5
- pandas - version 1.5.2
- matplotlib - version 3.6.2
- seaborn - version 0.12.2
- scikit-learn - version 1.2.2
- statsmodels - version 0.13.5

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The linear regression model was able to predict bike demand precisely with an R2 Score of more than 80%.

- Final Equation

```cnt = yr*0.237132 + temp*0.388947 + windspeed*(-0.160217) + Jan*(-0.050699) + July*(-0.064112) + Oct*0.052266 + Sept*0.060748 + Sat*0.023058 + Cloudy*(-0.078506) + Light_snow_rain*(-0.290117) + spring*(-0.121727) + 0.297184```



## Contact
Created by [@Abish-gupta] - feel free to contact me!


