# Title : HOUSE RENT APP USING MERN


## Team ID : NM2024TMID02410

## Team Members

1. **[Dhivahar.V]** - **310121104025**
2. **[Balaji.V]** - **310121104012**
3. **[Jai Suriya.K]** - **310121104042**
4. **[Sankar.K]** - **310121104054**
5. **[Elanthirayan.E]** - **310121104030**

## Overview

The Home Rental Web App is a platform developed using the MERN stack (MongoDB, Express.js, React, and Node.js) to help users find, list, and manage rental properties. The application enables property owners to post rental listings and potential renters to search for properties that match their preferences. This web app streamlines the rental process by connecting landlords and renters in one platform, making it easy to find or advertise rental properties.

## Table of Contents

- [Team Members](#team-members)
- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Setup and Installation](#setup-and-installation)
- [License](#license)

## Features

- **User Authentication**: Secure login and registration for landlords and renters.
- **Property Listings**: Landlords can post new listings with details like property type, location, price, and photos.
- **Property Search**: Renters can search properties based on location, price range, and other filters.
- **Booking Requests**: Allows renters to submit booking requests directly through the app.
- **Favorites List**: Renters can save properties they’re interested in.
- **Responsive Design**: Ensures usability on both desktop and mobile devices.

## Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Styling**: CSS
- **Authentication**: JWT (JSON Web Tokens)

## Setup and Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-repo/home-rental.git
   cd home-rental
   ```

2. **Install dependencies**  
   Navigate to the backend and frontend directories to install dependencies:

   ```bash
   cd backend
   npm install
   cd ../frontend
   npm install
   ```

3. **Configure Environment Variables**  
   Set up the required environment variables in a `.env` file in the backend directory:

   ```plaintext
   PORT=5000
   MONGO_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   ```

4. **Run the Application**  
   Start both the backend and frontend servers:

   ```bash
   # In the backend directory
   npm start
   # In the frontend directory
   npm start
   ```

5. **Access the Application**  
   Visit `http://localhost:3000` to view the app in your browser.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
