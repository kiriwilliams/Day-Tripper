# Day-Tripper
Day Tripper makes last minute plans a breeze, providing recommended activities based on location and weather.

## [Try it out!]()

## How it Works
First, users log in using Firebase's login functionality, and enter their zipcode.

Next they are directed to the homepage. Information from openweather is translated into suggestions such as whether you need a coat, and a list of possible activities as displayed based on liklihood of precipitation.

Once a user selects categories they're interested in, the app makes a call to yelp API and displays the results with relevant information. These can be saved into the user's personal list for convenience. 
