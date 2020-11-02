## ConnecTeam
ConnecTeam is a site created for team notification. The project allows the user to enter in their team members with full CRUD functionality. The application also uses a Twilio API call to actually send messages to the team members.

The Single Page application uses a React Front end with a Node Express Server and a PostgreSQL database. The flexibility of the Node server is on display as Twilio had an install package ready for Node. The React application uses a switch and case method to render the screens. Finally, during the function call to send the text messages, records are written into the billing table so that billing can be viewed when the billing and teams tables are joined in the Billing Detail Screen. Follow this link to the live project: https://protected-shelf-61131.herokuapp.com/

##Technologies Used:
The application is a PERN stack (PostgreSQL, Express, React & Node).  With a react front end and an api built with Node/Express using a SQL database.  A third party API called twilio was used to make the sms(texting) possible.  

The page is styled with standard css using GRID.

The most interesting feature of the react is the Switch and Case method for controlling screens.

![ConnecTeam](connecteam.png)

The texting is turned off because the Twilio account is a test account and doesn't allow mass texting until the account is upgraded to production status.  


##Installation
If you fork the repo then you'll have to upgrade the .env file with your twilio codes because the ones there don't work.  

Ensure that you've updated the postgresql info to point to your database and then you should be able to use the sql primer file to create and load the tables required for the application.  

Start the server and the application should pull up on localhost:3000.
