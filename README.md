
**Welcome to the AyuCare Herbal E-Commerce Web Application - International Standards with Excellence*

## Features
* Sellers can add, update, and delete items
* Buyers can search, buy, and track orders
* Payment for items can be made using credit cards or payment integration services
* The system integrates with a third-party delivery service
* A commission is charged on each purchase as the main revenue source, which includes payment service fees
* Buyers can review and rate suppliers and individual products  

# Getting Started 🔥

Clone this repository to a preffered location.

## Frontend

1. To run the frontend you can run following commands in the `Frontend` folder
   ```
   npm i
   npm run dev
   ```

## Services

1.  Create `.env` file in each and every `service` folder inside the services folder and add following details.

    ```
    PORT=<YOUR_PORT_ID>
    HOST_NAME=<YOUR_IP_ADDRESS>
    MONGO_URI=<YOUR_MONGO_DB_URI> 
    ```
    **Note: The MONGO_URI variable should not be added to the apiGateway .env file.**


2.  To run the services you can run following commands in each service directory.

    ```
    npm i
    npm run dev
    ```
