<h2>A. Install necessary tools using CLI:</h2>

* Install React
  * npm -g install create-react-app

* Install Express
  * npm install -g express-generator
  
* Install CORS
  * npm install -g save cors
  
<h2>B. Create project folder  using CLI:</h2>

* Make Directory
  * mkdir git_fullstackapp

<h2>C. Create backend and frontend projects:</h2>

* Change Directory
  * cd git_fullstackapp
  
* Create Backend
  * express --view=pug backend
  
* Change Directory
  * cd backend
  
* Install dependencies
  * npm install
  
* Change Directory up one level
  * cd ..
  
* Create Frontend
  * npx create-react-app frontend

<h2>D. Checking backend and frontend projects:</h2>

* Change Directory
  * cd backend
  
 * Start Command
   * npm start
   
 * Open browser
   * http://localhost:3000/
   
 * Verify that you see:
 
   <b>Express</b>
   
   Welcome to Express
   
 * Stop Command
   * Ctrl+C
   
 * Change Directory
   * cd ../frontend
   
 * Start Command
   * npm start
   
 * Open browser
   * http://localhost:3000/
   
 * Verify that you see:
   * React welcome page and React Logo
   
 * Stop Command
   * Ctrl+C

<h2>E. Editing the backend:</h2>

* Replace "www" file in /backend/bin/
  * Use file from github repo
  
* Insert "mypage.js" file in /backend/routes/
  * Use file from github repo
  
* Replace app.js file in /backend/
  * Use file from github repo
  
* Install CORS locally in /backend/
  * npm install cors
  
* Start Command
  * npm start
  
 * Open browser
   * http://localhost:7000/mypage
   
 * Verify that you see:
   * I am sending this DATA from backend to frontend
   
 
