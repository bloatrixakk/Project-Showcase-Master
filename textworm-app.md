# TEXTWORM APP

## Features
   * ### In app translator ![status](https://img.shields.io/badge/status-down-red)
      * Translates the selected word into your desired language on tap
   * ### Texts in different languages reviewed by a real language teacher
      <img src="imgs/textworm-app-screenshots/photo_5809654759697354021_y.jpg" width="200">
      <img src="imgs/textworm-app-screenshots/photo_5809654759697354022_y.jpg" width="200">

   * ### Exercises for texts
      * Multiple choice
         <img src="imgs/textworm-app-screenshots/photo_5809654759697354018_y.jpg" width="200">
      * Fill in
         <img src="imgs/textworm-app-screenshots/photo_5809654759697354017_y.jpg" width="200">
      * True or false
      * Rearrange sentence
         <img src="imgs/textworm-app-screenshots/photo_5809654759697354016_y.jpg" width="200">
      * Odd one out
         <img src="imgs/textworm-app-screenshots/photo_5809654759697354013_y.jpg" width="200">
      * Fill the gaps
   * ### Account system
      * access tokens
      * login and password
      * creating a new account
      <img src="imgs/textworm-app-screenshots/photo_5809654759697354014_y.jpg" width="200">
      <img src="imgs/textworm-app-screenshots/photo_5809654759697354010_y.jpg" width="200">
      <img src="imgs/textworm-app-screenshots/photo_5809654759697354009_y.jpg" width="200">
      <img src="imgs/textworm-app-screenshots/photo_5809654759697354011_y.jpg" width="200">
      <img src="imgs/textworm-app-screenshots/photo_5809654759697354012_y.jpg" width="200">
      
## Backend
* ### AWS services is used as the cloud backend
* ### AWS S3:
   * config
      * stores the filters for the search of texts in app
   * exercises
      * stores the exercises for texts in json format
   * texts
      * stores texts in txt format
* ### AWS Lambda:
   * links the 
* ### AWS DynamoDB:
   * Refresh tokens
      * stores the refresh tokens for the users
   * texts
      * links the items in the bucket(text files) to the names, etc...
   * users
      * links the user data(name, etc...) to the json files in the bucket
* ### API Gateway
   * Used to link the lambda scripts to end points

## Frontend
* ### React native is the base for the mobile app
* ### Android is currently the only OS supported, but the code can be easily compiled for IOS
* ### A fun design