
## TweetEdu!
    The project is to stream the live tweets from twitter

#Dependencies <br>
    Twitter Developer account
    Twitter package(Nodejs)
    Express
    Socket.io

#To Run
     Clone or Download the repository and Run below command 

     `npm install`

   1.Create a account in Twiiter developer account and wait for the conformation
   2.After get conformation from Twitter developer community Go the developer account
   3.Create a app that will Give the
            > API key
            > API secret Key
            > Access Token Key
            > Access Token Secret
    4.After getting all the key replace the keys in tweet.js file as mentioned below

        consumer_key:'API key',
        consumer_secret: 'API secret Key',
        access_token_key:'Access Token Key',
        access_token_secret:'Access Token Secret'

 After replacing the move to server folder and Run the server by below commands

    `cd/src/server - This command is to move to the server folder (windown)`

After moving Start the server by below command

    `node server.js`
       
After that to Run the front end Run the below command

### `npm Run start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

You will also see any lint errors in the console.



This command for To test and deploy the appication this is not necessary to Run 

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](#running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!
