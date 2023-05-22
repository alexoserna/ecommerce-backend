  # E-commerce Back End Starter Code
  ![MIT License](https://img.shields.io/badge/license-MIT-brightgreen "MIT License")

  ## Table of Contents

  - [Description](#description)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Questions](#questions)
  - [License](#license)

  ## Description
  This project is the backend for an ecommerce platform. It is made to handle everything from adding products, prices, categories, and tags to updating and deleting them aswell.

  ## Installation
  Clone the repository. Open up the terminal and input the command npm install, in order to install all necessary packages.

  ## Usage
  In order to use the application make sure to add and fill in a .env file. Then in the terminal run "mysql -u root -p". It will prompt you for your personal mysql password. After you are
  logged and in the mysql cli run "SOURCE db/schema.sql" in order to ensure that the database is set and ready to go. You can quit out of the mysql cli and proceed to the next step.
  Next run "npm run seed" in order to seed the database, and finally run "npm start" to boot up the server in order to run the api calls in insomnia. Using insomnia you can run any of the api
  calls to get any of the category, product, or tag information that is needed. Aswell as to create, update, and delete them. 
  
  ![image](https://github.com/alexoserna/ecommerce-backend/assets/118146045/0574eb44-462a-4e48-a3bf-727c6b035c8e)

  [Vide Demonstration](https://drive.google.com/file/d/1cpPno4T89sz15jGZowGMoRMIw0Pzot0_/view)
  
  ## Test
  To test all the routes you can open up insomnia and input the api routes when running locally. For example "http://localhost:3001/api/tags/".

   ## License
  This project is licensed under the [MIT License](https://opensource.org/license/mit/) - Click for more information

  ## Questions
  If you have any questions you can reach me here:
  Github: [alexoserna](https://github.com/alexoserna)
