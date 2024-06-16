<h3>As for the privacy, the API keys and google auth ID and secret ID are kept not visible to the public</h3>


<h3>Clear instructions for setting up and running the application.</h3>
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

<h3>Demonstration</h3>
1. On the application homepage, you will see a Google login button.
2. Click the Google login button to initiate the OAuth authentication flow.
3. A Google login window will appear. Sign in with your Google credentials.
4. Upon successful login, you will be redirected back to the application, and your authentication token will be stored.
5. After logging in, the feedback form will be displayed.
6. Select a feedback category from the dropdown menu (e.g., Product Features, Product Pricing, Product Usability).
7. Enter a rating (e.g., 4 out of 5).
8. Provide any comments you have about the product.
9. Click the submit button to send your feedback.
10. Upon submission, the feedback data (category, rating, and comments) will be sent to the backend server.
11. The backend server will store the feedback in your local database (MongoDB).
12. Simultaneously, the feedback will be sent to Frill.co via their API for further management and visualization.
13. You can view aggregated feedback for each category by navigating to the appropriate endpoint.
14. The frontend can be enhanced to display this aggregated feedback in a user-friendly manner, such as charts or lists.
15. Ensure that the feedback you submitted is also reflected on Frill.co.
16. Log in to your Frill.co account and navigate to the feedback section to verify the feedback data.
17. Check for the feedback categories, ratings, and comments that match what was submitted through your platform.
