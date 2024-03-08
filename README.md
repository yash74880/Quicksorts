# Quickshorts

Quickshorts is a social media application where you can create image posts,like posts,comment on posts, and add or remove friends.

## Features


1.  **API Authorization**: Quickshorts ensures secure access to its APIs through JWT (JSON Web Token) authorization. Only authorized users can interact with the application's APIs.
    
2.  **Session Management**: JWT is used for session management in Snapture. It helps maintain user sessions and provides secure access to different parts of the application.
    
 ## Technology Stack
![Screenshot 2024-02-04 at 11 33 27 AM (1)](https://github.com/yash7488/Quickshorts/assets/80100162/faa7f94a-5e53-4d7c-b266-d58ec300b9d5)

Quickshorts is built using the following technologies:

-   **Frontend**: React.js
-   **Backend**: Node.js with Express.js
-   **Database**: MongoDB
   


## Prerequisites

Before running Quickshorts, ensure that you have the following software installed:

-   Node.js: Make sure you have Node.js installed on your system. You can download it from the official Node.js website and follow the installation instructions for your operating system.
    
-   MongoDB: Install MongoDB and make sure it is running on your local machine or provide the connection details for a remote MongoDB database.

## Installation

To install and run QuickShorts locally, follow these steps:

1.  Clone the repository:
    ```sh    
       git clone https://github.com/yash7488/Quickshorts.git
    ```
    
2.  Navigate to the cloned repository:
     
    `cd _QuickShorts` 
    
3.  Install the dependencies for the frontend:
    
    ```sh    
    cd client
    npm install
    ``` 
    
4.  Install the dependencies for the backend:
        
    ```sh    
    cd ../server
    npm install
    ```
    
## Configuration

QuickShorts requires configuration for various services. Here are the steps to set up the required configuration:

### Backend Configuration

1.  Open the `server` directory.
    
2.  Create a `.env` file in this directory.
    
3.  Set the following environment variables in the `.env` file:
    
    -   `MONGO_URL`: The MongoDB connection string.
    
    -   `PORT` : 3001.
                
    -   `JWT_KEY`: A secret key used for JWT token generation and validation.
        
4.  Save the `.env` file.

## Running QuickShorts

After completing the configuration steps, you can now run Snapture locally.

1.  Start the backend server:
	```sh
	cd server 
	node index.js
	```
2. Start the frontend development server:
	```sh
	cd ../client
	npm start
	```
3. Access QuickShorts in your browser at `http://localhost:3001`.


