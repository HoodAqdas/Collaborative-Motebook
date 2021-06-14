# Collaborative-Motebook
Node JS,  HTML, CSS with complete backend. An app similar to Google Docs.

## Functionalities

1. Sign Up
2. Login
3. Create new text files (You can also copy paste images/gifs/anything you want)
4. Format Text
5. Share files with other Journal users who can then make changes visible to all co authors
6. Authenticate your Google Drive account
7. Upload files to google drive
8. Edit/Download/Delete your files
9. How to run

The following modules are required:
* node
* session
* express
* nodemailer
* body-parser
* ajax
* mongodb
* express-session


Each module can be installed using npm. For example to install node, all you have to do is execute the following command
`npm install node`

Next, you have to change the connection string and database name for mongodb as well as mention the base path in the following file:
config/settings.js
There should be 3 collections in the database:

Clone the project, go to the project directory and run the following command:
`node main.js`

Then open the browser and go to `localhost:8888`
