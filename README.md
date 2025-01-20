# RicoTrade Backend

This repository contains the backend code for **RicoTrade**, a trading platform inspired by Zerodha. It serves as a bridge between the frontend and the MongoDB database, enabling seamless API calls and providing real-time, updated data for the platform.  

The backend is responsible for handling API requests from the frontend hosted on **[Traderico](https://traderico.onrender.com)** and ensures efficient communication with the **MongoDB** database.

---

## **Key Features**

- **API Integration**: Facilitates data retrieval and updates between the frontend and the MongoDB database.
- **MongoDB Connectivity**: Ensures seamless connection with MongoDB for storing and managing data.
- **Real-Time Updates**: Supports fetching updated data for a dynamic and responsive user experience.
- **Scalable Architecture**: Designed to handle multiple requests efficiently.

---

## **Technologies Used**

- **Node.js**: For building the backend server.
- **Express.js**: As the web application framework.
- **MongoDB**: For the database.
- **Mongoose**: For MongoDB object modeling.
- **Render**: For deploying the backend server.

---

## **Start the server:**

1. command:
   ```bash
   npm start

## **API Endpoints used in RicoTrade-Trade**

GET (https://backend4rt.onrender.com/allholdings)
Fetches the latest data about holdings from the MongoDB database used in Holdings.js.

GET (https://backend4rt.onrender.com/allpositions)
Fetches the latest data about positions from the MongoDB database used in Positions.js.

POST (https://backend4rt.onrender.com/newOrder)
Adds new data to the MongoDB database about the orders of users used in BuyActionWindow.js.
