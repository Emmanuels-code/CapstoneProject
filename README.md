# Travel Itinerary Planner Capstone Project
## Overview

This capstone project is a full-stack web application designed to help users plan, explore, and manage their travel itineraries. The platform allows users to view suggested travel destinations, plan trips with personalized itineraries, and explore various locations for their next adventure.
Project Structure

### The project consists of two primary components:

- **Frontend**: Built using React, hosted on Netlify.
- **Backend**: Powered by Node.js/Express with MongoDB for data storage, hosted on Glitch.

## Live Links:

- **Frontend**: (https://emmanuels-travel-plan.netlify.app/) [https://emmanuels-travel-plan.netlify.app/]
- **Backend**: (https://glitch.com/edit/#!/youthful-wandering-veil) [https://glitch.com/edit/#!/youthful-wandering-veil]

## Features

1. User Authentication

    Users can sign up for an account and log in securely using JWT-based authentication.
    User credentials are encrypted and stored in the database.
    Users remain logged in across sessions via local storage tokens.

2. Itinerary Management

    View Trips: Users can view a list of their previously planned trips.
    Plan a New Trip: Allows users to explore available locations and plan a new itinerary.
    Edit & Update Itineraries: Users can add activities, update dates, and modify itineraries.
    Upcoming Trips Section: Displays users' upcoming travel plans.

3. Location Exploration

    Users can explore curated travel destinations across the globe.
    Recommended destinations are shown on the homepage.
    Users can browse through multiple locations and find inspiration for their next trip.

4. Animations

    Lottie Animation Integration: Engaging animations using Lottie are used throughout the site to enhance the user experience.

## Frontend

The frontend is built using React and features a responsive design to provide a seamless user experience across devices.

### Tech Stack:

- React for building UI components.
- Axios for making HTTP requests.
- React Router for handling navigation.
- TailwindCSS for styling.

## Backend

The backend is built using Node.js and Express and provides the API for managing users, itineraries, and locations. It interacts with MongoDB for persistent data storage.

### Key Routes:

- User Authentication

> POST /auth/signup:
*Registers a new user*

> POST /auth/login: 
*Authenticates a user and provides a JWT token.*

- Itinerary Management
> GET /itineraries: 
*Fetches all itineraries for an authenticated user.*

> POST /itineraries: 
*Allows a user to create a new itinerary.*

> PUT /itineraries/:id: 
*Updates an existing itinerary.*

> DELETE /itineraries/:id: 
*Deletes an itinerary.*

- Location Data
        
> GET /locations: 
*Returns a list of available locations.*

> GET /locations/:id: 
*Fetches detailed information about a specific location.*

**Tech Stack:**

- Node.js with Express for server-side logic and API creation.
- MongoDB for database storage.
- JWT for authentication.
- Mongoose for modeling MongoDB data.

**Setup Instructions**

Frontend

    Clone the repository:

```bash
git clone https://github.com/Emmanuels-code/travel-planner
```
Install dependencies:

```bash
npm install
```
### Run the development server:

```bash
    npm start
```
*Visit the app at http://localhost:3000.*

## Backend

Clone the backend repository:

```bash
git clone https://github.com/Emmanuels-code/capstone-server
```

### Install dependencies:

```bash
npm install
```

Start the backend server:

```bash
    npm start
```

### Future Improvements

- Notifications: Send reminders to users about upcoming trips.
- Social Sharing: Allow users to share their itineraries with friends.
- Real-time Collaboration: Enable multiple users to collaborate on a shared itinerary.
