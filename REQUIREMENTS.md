# Requirements

## 1.1
Given the API is running
When the `productsList` endpoint is hit with a `GET` request
Then the following product categories are returned in the list [`Tops`, `Tshirts`, `Dress`, `Tops & Shirts`, `Jeans`, `Saree`]

## 1.2
Given the API is running
When the `productsList` endpiont is hit with a `GET` request
Then the endpoint returns a `200` response code

Given the API is running
When the `brandsList` endpiont is hit with a `GET` request
Then the endpoint returns a `200` response code

Given the API is running
When the `getUserDetailByEmail` endpiont is hit with a `GET` request
And with the email `test@test.com`
Then the endpoint returns a `200` response code

## 1.3
Given a user navigates to `https://automationexercise.com/`
When the mens categories is viewed
Then the following product categories are viewable [`TShirts`, `Jeans`]

## 1.4
Given a user navigates to `https://automationexercise.com/`
When adds an item to the cart
Then product is added to the user's cart