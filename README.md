# Toy Exchange Mobile Application

## Introduction
It is  a mobile application where the customers can buy and sell toys. There exists no system for exclusive trade of toys. This can be ideal for new parents or those whose children have grown past the age to use certain toys.
- Sellers need to upload the image of the toy along with title, description, the expected selling price of the same along with 
their contact number.
- Buyers can browse through several toy options, contact the sellers, negotiate with them one-on-one and then choose to 
purchase the toy.
- The conversations, bargaining, advances, transactions remain between the buyer and the seller, thus maintaining privacy.

## Tech Stack
- VSCode, Android Studio +Emulator
- React Native (front-end framework)
- Libraries include:
  - React Native Paper for overall styling of app components.
  - React Native Gesture Handler to navigate between different screens.
  - React Native Vector Icons to add relevant icons to add aesthetics and make the app user friendly.
- Firebase (back-end) and Firestore (cloud storage): Install packages to link with  React Native app. Eg. For authorisation, etc.

## Modular Design
- Login
- Sign Up 
- Toy Catalogue
- Creating Ad
- User Account
- 
## Functional requirements
- Login and Signup: Existing customers can access the application post logging in. New customers can sign up.
- Homepage/Toy Catalogue: This is shown on successful signing in. Images of the available toys along with the description, price and contact. It is juxtaposed with a bottom screen navigation bar. The bar contains relevant icons embedded in buttons to easily move between screens
- Creating new ad: Sellers can create an ad for their toy by providing the required details.
- Purchasing a product: Interested buyers can call the sellers directly through app to get further details (bargain, place of pick-up etc.). 
- Account details: User can view his/her ads posted and choose to log out


## Non functional requirements
- Safety requirements: The user should have an account and remember the email address and password. User must understand the terms and conditions of data collected via application.
- Security requirements: Verification of the email and contact information provided by the user
