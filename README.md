1. **Navigate to the Server Directory**
   - Move to the server directory using the command: `cd server`

2. **Create a .env file**
   - Create a `.env` file in the server directory and add the following variables:
      i. `MONGODB_URL` = `database connection string`
      ii. `JWT_SECRET_KEY` = `your secret key`
      iii. `PORT` = `8800`
      v. `APP_URL` = `http://localhost:8800/api-v1`

3. **Install Dependencies**
   - Run `npm install` to install the required packages.
   
4. **Start the Server**
   - Run `npm start` to start the server on `http://localhost:8800`

### Frontend (Client)

1. **Install Dependencies**
   - Run `npm install` to install all client-side dependencies.

2. **Start the Client**
   - Run `npm start` to start the client on `http://localhost:3000`

Now you're all set!


