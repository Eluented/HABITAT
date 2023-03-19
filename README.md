# HABITAT
LAP2 PROJECT 

## How to Run:
**bash _scripts/startDev.sh**
- api & db services
- runs db migrations
- seeds db for development
- serves client on localhost:8080
- serves api on localhost:3000

## How to teardown
**bash _scripts/teardown.sh**
- stop all running services
- removes containers
- removes volumes

## Habitat - Plant Habit Tracker
Habitat is a web application that allows users to track how many times they have watered their plants. Users can create an account and sign in to see their plants and add new plants to track. The application will keep track of the last time a plant was watered and notify users when it's time to water their plants.

## Tech Stack
* HTML for the front-end interface
* CSS for styling the interface
* JavaScript for client-side interactions
* SQL for the database management
* Express.js for server-side framework
* Node.js for backend programming

## Features
* User Registration: Users can create an account by providing their email address and password. The application will store the user's information in the database.

* User Authentication: Users can log in to their account by providing their email and password. The application will verify the user's information before allowing them access to their plants.

* Plant Management: Users can add new plants to track by providing the plant's name and species. The application will store the plant's information in the database and display it on the user's dashboard.

* Habit Tracking: Users can track the number of times they water their plants. The application will record the date and time of each watering and display it on the user's dashboard.
