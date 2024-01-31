# Predict Movie Rental Duration

A machine learning project to predict the number of days a customer will rent a DVD, assisting a DVD rental company in efficient inventory planning.

## Objective

The primary goal of this project is to build regression models capable of predicting the rental duration of DVDs based on various features. The company aims to deploy a model with a Mean Squared Error (MSE) of 3 or less on a test set, improving inventory management.

## Dataset

The dataset, sourced from 'rental_info.csv,' contains the following features:

- `rental_date`: Date and time of DVD rental.
- `return_date`: Date and time of DVD return.
- `amount`: Amount paid by the customer.
- `release_year`: Year of the movie release.
- `rental_rate`: Rate at which the DVD is rented.
- `length`: Length of the movie (in minutes).
- `replacement_cost`: Cost to replace the DVD.
- `special_features`: Additional features, such as trailers or deleted scenes.
- Dummy variables for movie ratings: `NC-17`, `PG`, `PG-13`, `R`.

