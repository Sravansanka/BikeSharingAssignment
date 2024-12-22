# Bike Sharing Assignment

> This project focuses on building a predictive model to forecast the demand for shared bikes in the American market. BoomBikes, a leading bike-sharing provider, aims to leverage data insights to overcome challenges posed by the pandemic and better align with shifting customer needs.

By analyzing historical bike usage data, this project identifies key factors like weather, temperature, day of the week, and season that influence bike demand. Using linear regression, it explores how these variables affect demand fluctuations and helps predict future trends. 

The ultimate goal is to enable BoomBikes to:
- Optimize operations
- Adjust fleet distribution
- Refine pricing strategies
- Tailor marketing efforts

This data-driven approach will help BoomBikes anticipate demand, enhance customer satisfaction, and improve operational efficiency, positioning it as a leader in the competitive bike-sharing market during economic recovery.

---

## Table of Contents
- [General Information](#general-information)
- [Conclusions](#conclusions)
- [Technologies Used](#technologies-used)
- [Author](#author)

---

## General Information
- **Objective**: Model and predict bike demand in the American market using factors like weather, temperature, and day of the week to help BoomBikes optimize its operations post-pandemic.
- **Business Challenge**: BoomBikes has faced revenue declines due to the COVID-19 pandemic. This project addresses the need to forecast bike demand as the economy recovers, ensuring the company meets customer needs effectively.
- **Problem Statement**: The project predicts shared bike demand in a post-pandemic market, helping BoomBikes adapt strategies, optimize operations, and increase profitability.
- **Dataset**: Daily bike demand data from the American market, influenced by factors like weather, temperature, and behavioral patterns.

---

## Conclusions

The following features significantly contribute to the prediction of bike demand (`cnt`):

### Top Features Influencing Bike Demand
1. **Temperature (`temp`)**  
   - A one-unit increase in `temp` leads to a **0.5044** increase in bike bookings.  
   - Warmer weather significantly drives bike demand.

2. **Year (`yr`)**  
   - A unit increase in `yr` (moving from 2018 to 2019) results in a **0.2328** increase in bike hirings.  
   - This indicates a rising trend in demand over time, showcasing business growth.

3. **Weather Condition (`snow/rain/thunderstorm`)**  
   - A unit increase in `snow/rain/thunderstorm` decreases bike bookings by **0.3004** units.  
   - Adverse weather conditions negatively impact bike demand.

### Additional Insights
- Factors such as **Sun**, **July**, **September**, **misty/cloudy**, **spring**, **summer**, and **winter** also influence bike demand but to a lesser extent.  
- Warmer temperatures and an increasing trend over the years are the primary positive drivers of demand, whereas adverse weather conditions significantly reduce bookings.

---

## Technologies Used
The following libraries were utilized to implement the predictive model:

- **pandas**: 2.2.2  
- **numpy**: 1.26.4  
- **matplotlib**: 3.8.0  
- **seaborn**: 0.13.2  
- **scikit-learn**: 1.5.2  
- **statsmodels**: 0.14.4  

---

## Author
Created by **Sravana Sanka**  

If you have any questions or feedback, feel free to reach out! 😊
