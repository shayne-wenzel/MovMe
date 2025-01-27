# MoviMe (API)

a backend using Node/Express.js to create a REST API. MongoDB serves as the database.

<br>

## Installation

Install dependencies with npm:

```bash
  git clone https://github.com/shayne-wenzel/MoviMe
  cd MoviMe
  npm install
  
```

<br>

## Dependencies
**For Development**
- Express Library
- Passport Library (for authentication)
- JSON Web Token and Bcrypt
- CORS
- Mongoose (Business Logic)

**For Non-Relational Database**
MongoDB / MongoDB Atlas

<br> 

### Local Developement
In order to locally work on this app, you have to connect it to the localhost.
To do so, uncomment the respective code block in `index.js` and comment out the connection to the remote databasee.

### Nodemon
Once working locally, you can use Nodemon as a tool to automatically save and generate a new node file.

Start the server
```bash
npx nodemon index.js
```
After every save it restarts the server

<br>

### Hosting
- Heroku
To sync local changes to hosted db, use
```bash
git push heroku main
```
