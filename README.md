# For Instructions 
Please refer to Project4_PropertY-hub_fa2301INSTRUCTIONS.pdf. 

# Objectives 
## Milestone 1: Home Page and User Registration 
 ### Home Page:
 Design a generic home page (similar to an "About" page) to include:

Project Description: Provide an overview of the platform.

### User Registration:
Define user roles: Buyers, Sellers, and Admin (to analyze business activities).
The portal must handle registration and login for all users.
Front-End (FE):
Create a signup page with form fields such as first name, last name, email, username, etc.
Ensure comprehensive form validations for accurate data collection.
Back-End (BE):
Design the database schema to store all user data.
Implement password encryption before storing credentials.
##  Milestone 2: User Login
Functionality:

After successful registration, redirect users to the login page.

Verify credentials, and upon success, redirect users based on their role:

Sellers → Seller Dashboard

Buyers → Buyer Dashboard

Admin → Admin Dashboard

Implementation:

Use sessions for user authentication:

Assign a unique session ID upon login.

Use cookies to manage the session and verify user identity on subsequent requests.

##  Milestone 3: Seller Dashboard

## Front-End (FE):

Upon login, the seller dashboard should display all properties listed by the user in card format. Each card should include:

Details: Location, age, floor plan, square footage, number of bedrooms, bathrooms, garden, parking, proximity to facilities, main roads, and property tax (7% of value).

Image: A visual representation of the property.

Interaction:

Clicking a card redirects to the detailed property view.

Sellers can update or delete properties.

If no properties are listed, display a “+” card prompting the seller to add a new property. Use visual cues to encourage interaction.

## Back-End (BE):

Save property details in the database, associating them with the seller via a foreign key.

Design the database schema to align with best practices and support the above functionality.

