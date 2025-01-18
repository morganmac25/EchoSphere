# Top Spotify Artists
## Overview
Top Spotify Artists is a web application that allows Spotify users to discover and visualize their top artists 
through an intuitive, personalized interface. By leveraging the Spotify Web API, this program provides 
users with insights into their music listening habits.

## Features 
* Seamless Spotify Account Authentication
* Retrieve and Display Top Artists
* Elegant, Responsive Design
* Secure OAuth 2.0 Implementation

## Technologies Used 
* Node.js
* Express.js
* Spotify Web API
* Pug Templating Engine
* OAuth 2.0
* JavaScript
* CSS

## How To Use 
1. User logs in via Spotify
2. Application requests authorization
3. Retrieves top artists data
4. Displays artists in an elegant table format

# Setup and Installation 
## Prerequisites
* Node.js
* Spotify Account (Can be free account)

## Installation Steps
1. Clone the repository
2. Install dependencies: npm install
3. Create .env file with Spotify credentials
4. Run the application: npm run start
5. Open http://localhost:3000

## In The Works
* Artists will be numbered as well as listed
* List of user's top songs
* Dashboard to choose Short, Medium, or Long term statistics

# Acknowledgements
This project was inspired by and built upon the knowledge gained from the "Build your first 
Spotify App - Online Workshop" by Sasha Kaverina. The workshop can be viewed here: 
https://www.youtube.com/watch?v=9infxDJtDFM

The initial setup and structure of this project were based on the GitHub repository associated 
with the workshop: https://github.com/alnacle/spotify-api-workshop/tree/main

While the core setup using Express, Pug, and JavaScript remains similar, this project implements 
different functionality and utilizes alternative Spotify API endpoints. The focus here is on 
visualizing top artists rather than creating a recommendation engine as demonstrated in the original workshop.
