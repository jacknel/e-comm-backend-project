# e-comm-backend-project

The user must provide database name, MySQL username, and password in the environment variable file for connection.

Using Sequelize, the .env file will allow the user to connect to the database.

Upon entering schema and seed commands, the database will be created and populated with test data.

Running the start command will launch the server and sync the sequelize models with the MySQL database.

API GET routes in Insomnia for categories, products, and tags will display their respective data in JSON format.

Testing POST, PUT, and DELETE routes in Insomnia will perform the respective actions in the database.

Clicking the write icon will prompt a new empty note for starting the process again.