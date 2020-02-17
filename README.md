# budgeting-app

#### Application Overview
- This application will be responsible for tracking a user's spending and saving habits.
- It will be able to provide a daily, weekly, and monthly view of their current cash inflows & outflows, as well as budget available left in the period.
- It should provide an easy and accessible way of entering every day expenses.
- Multiple users should be able to be linked to the same account. I.e. Husband & Wife, or co-workers/partners in a business should be able to see and manipulate the same account data.
- Should provide a rich statistical reporting interface to provide maximum context & clarity on financial inflows & outflows.

#### Stack Overview
##### Database
The application will utilize a Postgres DB. It is important that the application database is designed to support the infrastructure for:  
- Handling Google SSO fields, so a user may login to this application with their existing Google account.
- Handling multi-user managed accounts.  

##### Back-End
This application will use NodeJS as a back-end including relevant third party APIs and libraries.  
- Knex (third party) should be used for communication between the back-end code and the Postgres DB.
- ExpressJS (third party) should be used for cleanly defining RESTful end-points on the back-end.

##### Front-End
This application will use ReactJS as a front-end including relevant third party APIs and libraries.
- Axios (third party) will be used for fetching data from the back-end.
- Flex CSS will be used with CSS for styling pages & displays.

##### Mobile Integration
This application will use React Native for an App compatible on mobile devices.
