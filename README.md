# TechCMS
  ![badmath](https://img.shields.io/github/license/QuaggWasTaken/TechCMS)
  
  ## Description 
  
  This project is a CMS designed to host blog-style entries about tech and related topics. It's designed using the MVC paradigm, with Handlebars for the Views, Sequelize for the Models, and Express.js for the Controllers. It also uses dotenv for environment variables, bcrypt for hashing of passwords, connect-session-sequelize for storing persisting session data for logged in users in the sequelize db, express-session for aquiring that session data, and mysql2 to host the MySql database. Finally, it's deployed on a Heroku server, with the JawsDB add-on to give us a database we can work from.
  
  
  ## Table of Contents (Optional)
  
  * [Installation](#installation)
  * [Usage](#usage)
  * [Contribting](#contributing)
  * [Tests](#tests)
  * [Credits](#credits)
  * [License](#license)
  * [Questions](#questions)
  
  
  ## Installation
  
  No need! Just visit [this link!](https://tech-cms.herokuapp.com/)
  
  
  ## Usage 
  
  Once you visit, you'll be taken to the homepage, which will display all existing posts, with the most recent at the top. Clicking on one, will open it up and allow you to see comments on the post, those sorted with the oldest at the top. clivking 'login' will take you to a page where you can either create an account, or if you have one, log in. Once logged in, you;ll be taken to the dashboard, where you can make your own posts, view all of your posts, and edit them if need be. Once you're logged in, if you view or edit a post, you'll be able to now add a comment or upvote the post. If you decide you don't want to have a certain post anymore, you can also delete your post from the edit page. Be careful though, this is permanent!
  
  
  ## Contributing

  Follow the standard Contributor Covenant guidelines at [this link](https://www.contributor-covenant.org/version/2/0/code_of_conduct/)
  
  
  ## Tests

  If you really need to, you can download it from the github here, set it up like a standard node project, and run `npm test`, this will run the suite of tests defined using Jest in the __tests__ folder.
  
   
  ## License
  
  None (For Now)


  ## Questions

  For additional questions, fing my github page [here](https://github.com/QuaggWasTaken/), or email me at <forrestfaulkner1@gmail.com>
  