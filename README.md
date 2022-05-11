# House Price Prediction
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contact](#contact)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
We are required to build a regression model using regularisation (l1 norm & l2 norm) in order to predict the actual value of the prospective properties and decide whether to invest in them or not. We have to identify the following

- which features are significant in predicting the price of a house
- how well those features describe the price of a house
- optimal value of strength of penalty (λ) for ridge and lasso

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Highlights of the final model:
- We choose lasso as our final model over ridge
- Because lasso's predictive r2_score is 90% whereas for ridge it is 88%
- Most importantly lasso model is lighter as it uses only 161 features whereas ridge uses all 215

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy
- pandas
- matplotlib
- seaborn
- sklearn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@https://www.linkedin.com/in/fazil-mohammed-4062711b2/] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->