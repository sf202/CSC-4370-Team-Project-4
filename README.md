# For Instructions 
Please refer to Project4_PropertY-hub_fa2301INSTRUCTIONS.pdf. 


# Objectives
**Milestone**
-1: Home page and User Registration. Home Page: Design a generic home page describing: (same concept as an About page
- Description of your project. 
-. User Registration 1. Now as a team, you have discussed what kind of users your platform will be having. 
2. Users: Buyers and Sellers. You also wanted to add an Admin user to analyze your business
. 3. This Portal must handle the registrations and login of all the users. Front End (FE):
- Design a signup page with all the required form fields. For example first name, last name, email id, username, etc. Make sure you collect all the form data that is required from the users to run your business effectively. 
- Handle all the form validations. Back-End (BE): 
- Design your DB Schema. 
- Store the all the required data in the database 
- Make sure you are encrypting the passwords when you store them in the DB

**Milestone**
-2 User Login: Once the new user is registered successfully the user must be redirected automatically to the login page. FE + BE: 
- Design and develop your login page.
- If the user exits after verification of the password fetched from the DB you should redirect the user to his dashboard to officially sign in. Redirecting Rules: 
- If the user is a seller, redirect the user to the seller dashboard. 
- If the user is a buyer, redirect the buyer to the buyer dashboard. 
- If the user is an admin, redirect the admin to the admin dashboard. Make use of the session’s concepts for example in the general situation : 1. The session id is sent to the user when his session is created. 2. It will store a cookie (called, by default, PHPSESSID…etc…) 3. The cookie is sent by the browser to the server with each request 4. The server (PHP) uses that cookie, containing the session_id, to know which file corresponds to that user.

**Milestone**- 3 Seller Dashboard: FE : Once the seller logs into their account the dashboard should list all the properties details also called card(s) tied to that user. For example:
 1. The location and age 
2. The floor plan (including the site's square footage) 
3. The number of bedrooms 
4. Additional facilities (such as bathrooms) 
5. Presence of a garden
 6. Parking availability 
7. Proximity to nearby facilities (such as large towns, schools and colleges) 
8. Proximity to main roads 
9. Property tax records - calculate 7% of value If the user hasn’t registered any property previously there should be a card with a + Symbol suggesting to add the new property to the platform. Implement some logic to emphasized that they must click the + symbol 
- Fetch all the properties from DB.
- List them in the form of cards. Card: ○ Each card must have an image. The main details like the location, price, etc.
-  Once the user clicks on the card. The user must be redirected to the complete details of the property.
-   The user should be able to update the property details in the complete video of the property details page.
-  The user should be able to delete the listed property. BE: Once the seller adds a property to the platform, store all the details in the property table in the DB with the foreign key user owning the property.
-   Design your DB Schema as per your convenience but the above-mentioned point is just a suggestion and best practice.
