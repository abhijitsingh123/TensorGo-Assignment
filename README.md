<h3>As for the privacy, the API keys and google auth ID and secret ID are kept not visible to the public</h3>

So, these are the steps to setup and run this web application:<br/>
<br/>
Setup<br/>
Put your GOOGLE_CLIENT_ID,
         GOOGLE_CLIENT_SECRET,
         GOOGLE_CALLBACK_URL,
         FRILL_API_KEY, MONGO_URI,
         SESSION_SECRET,
         PORT  in .env in the backend<br/>
<br/>
Steps to run:<br/>
In the terminal<br/>
1. cd frontend<br/>
2. npm i<br/>
3. npm start(will start the development server on the port 3000(default)<br/>
In another terminal<br/>
4. cd backend<br/>
5. install necessary libraries or packages like Axios, cors, express, express-session, passport, passport-google-oauth20 and nodemon in the command line<br/>
6. check for the scripts in the package.json file<br/>
7. run the command: npm run dev (will start the backend server using nodemon on the port 5000(default)<br/>
