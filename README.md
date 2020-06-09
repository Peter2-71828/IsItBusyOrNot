# Is it Busy Or Not

With lock down easing but social distancing still being critical we wanted to create an app that allows users to be able to leave the house with the knowledge that the area they want to visit wont be too busy.

Is it Busy Or Not is a Single Page Web Application that allows the user to search for any area and see in real-time the number of tweets in the last hour within a kilometer radius of that point, this gives the user a good indication of how busy that area is.


## Table of Contents
* [Tech Stack](#tech-stack)
* [How to run](#how-to-run)
* [Contributers](#contributers)



## Tech Stack
* React
* Express
* Twitter API

## How to run
Head to the Twitter Devloper site and apply for a API key
Once you have recieved an API key and API secret key you will need to run the following in your terminal to generate a bearer token
```
curl -u '<API key>:<API secret key>' \
  --data 'grant_type=client_credentials' \
  'https://api.twitter.com/oauth2/token'
```
Following this, clone the repo
```
cd client
npm install
touch .env
```
add the following to your env file
```
REACT_APP_API_KEY=<key>
REACT_APP_API_SECRET_KEY=<secretkey>
REACT_APP_TWITTER_BEARER_TOKEN=<bearertoken>
```
then run
```
source .env
npm run server
npm start
```
visit local host 3000 in your browser of choice

## Contributers
Peter Dean
Peter Stevens
Karla Gardiner
Will Grace
James Oddy
Paulo Azoia
Arjun Roy


