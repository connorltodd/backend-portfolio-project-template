##  Project Setup
Below are the steps to setup the backend and frontend of the project. Use the powerpoint slides to guide you to build all of the features for this app.

##  Backend Setup
```sh
cd backend
npm i
```

Then complete the following steps:

1. Install mySQL and setup the root user
2. Inject the init.sql into the mySQL terminal
3. Create a .env file and inject all of your sql credentials like the one below:

```sh
.env file 
DB_HOST='localhost'
DB_USER='root'
DB_PASSWORD='your_current_password'
DATABASE='fake_store_db_portfolio_project'
```

3. Import the postman collection from the backend folder into postman
4. Create some products using prior to starting
5. Backend setup should be complete

To run the app use npm start

You should see the following message in your terminal:

```sh
App is listening at 9000
Successfully connected to the database
```

If not contact an instructor for assistance


## Frontend Setup
```sh
cd frontend
npm i
npm start
```




Frontend Setup