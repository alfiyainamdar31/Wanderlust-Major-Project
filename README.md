# Wanderlust
<h4><a href="https://major-project-jk4e.onrender.com/listings">Visit the link to see the project</a></h4>

This project is a clone of the Airbnb website, built using Node.js and Express.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Environment Variables](#environment-variables)
- [Contributing](#contributing)
- [Technologies](#Technologies)

## Technologies

1. Node.js: JavaScript runtime environment.
2. Express: Web framework for Node.js.
3. EJS: Embedded JavaScript templating.
4. MongoDB: NoSQL database for data storage.
5. Mongoose: Object Data Modeling (ODM) library for MongoDB and Node.js.
6. Passport: Authentication middleware for Node.js.
7. Connect-Flash: Flash message middleware for Express.
8. Connect-Mongo: MongoDB session store for Express.
9. Cookie-Parser: Middleware to parse cookies.
10. Dotenv: Module to load environment variables from a .env file.
11. Multer: Middleware for handling multipart/form-data.
12. Cloudinary: Cloud service for image and video storage.
13. Mapbox SDK: Geolocation services.
14. Joi: Data validation library.
15. Method-Override: Middleware to use HTTP verbs such as PUT or DELETE.
16. Path: Utility module for working with file and directory paths.

## Installation

1. Clone the repository:

    ```bash
   https://github.com/alfiyainamdar31/Wanderlust-Major-Project.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Wanderlust Major Project
    ```

3. Install the dependencies:

    ```bash
    npm install
    ```

## Usage

1. Start the application:

    ```bash
    node app.js
    ```

2. Open your browser and go to `http://localhost:3000`

## Environment Variables

This project uses a `.env` file to manage environment variables. Make sure to create a `.env` file in the root directory of your project with the following variables:

```plaintext
CLOUD_NAME=your-cloud-name
CLOUD_API_KEY=your-cloud-api-key
CLOUD_API_SECRET=your-cloud-api-secret
MAP_TOKEN=your-map-token
ATLASDB_URL=atlas-url
SECRET=your-secret
```
<b>Note:</b> The .env file is not included in the repository for security reasons. Make sure to create it manually and add your own values.

## Contributing

1. Fork the repository
2. Create your feature branch (git checkout -b feature/your-feature)
3. Commit your changes (git commit -m 'Add some feature')
4. Push to the branch (git push origin feature/your-feature)
5. Create a new Pull Request
