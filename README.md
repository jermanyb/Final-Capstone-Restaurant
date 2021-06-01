![Screen Shot 2021-06-01 at 11 49 02 AM](https://user-images.githubusercontent.com/76081613/120353565-c25fa900-c2cf-11eb-9edc-d49948d97367.png)
![Screen Shot 2021-06-01 at 11 50 05 AM](https://user-images.githubusercontent.com/76081613/120353577-c4c20300-c2cf-11eb-8e46-5da25cb80361.png)
![Screen Shot 2021-06-01 at 11 49 45 AM](https://user-images.githubusercontent.com/76081613/120353585-c68bc680-c2cf-11eb-9c40-37f3ca31702f.png)
![Screen Shot 2021-06-01 at 11 49 34 AM](https://user-images.githubusercontent.com/76081613/120353593-c7bcf380-c2cf-11eb-9a9c-7110e5a90a63.png)
![Screen Shot 2021-06-01 at 11 49 23 AM](https://user-images.githubusercontent.com/76081613/120353599-c8ee2080-c2cf-11eb-8ab1-5fb7c9b82756.png)

<h1>Periodic Tables: Restaurant Reservation System</h1>

Welcome! Thanks for using our app. This app is designed to help users manage reservations for their customers.

Some features include:

View all reservations on the Dashboard. The reservations are listed by date, which the user is able to change. Create and edit reservations. Create tables for seating your reservations. Assign a table to a reservation upon arrival at the restaurant. Free a table when the reservation has finished dining and leaves. Search for a reservation by mobile number. Cancel a reservation.

<h3>Installation</h3>

1. Fork and clone this repository.
2. Run npm install to install project dependencies.
3. Craete .env file in the backend directory.
4. Modify .env with the following:
 DATABASEURL=_productionURL  DATABASEURL_DEVELOPMENT=_developmentURL  DATABASEURL_TEST=_testURL  DATABASEURL_PREVIEW=_previewURL  LOG_LEVEL=info
 
5. Replace "productionURL" with the URL to your production database.
6. Repeat step 5 for the remaining fields, but using the corresponding database URL.
7. Create a .env file in the frontend directory.
8. Modify .env with the following:
REACT_APP_API_BASE_URL=http://localhost:5000
9. From inside the backend directory, run npx knex migrate:latest.
10. Run npx knex seed:run.
11. Finally, go back to the root of the main directory and run npm run start:dev to run the application locally.





<h3>Technologies</h3>

The frontend was built using HTML5, CSS3, Javascript, Bootstrap, and React. For the backend, we used Nodejs, Express, and Knex.

