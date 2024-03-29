# Park Rangers - Back End Project 

This site was created to provide the user the ability to create a trip involving visits to National Parks in the United States. 

## Welcome Page

The user is brought first to the home page. 

![image](https://user-images.githubusercontent.com/78281930/117556953-dd722c80-b033-11eb-8bcd-8124b6f53365.png)

## Register Page

If the user clicks on the "Create A Trip" button, they will be brought to the login page. They can log in if they already have an account, or they can click on the link to register.

![image](https://user-images.githubusercontent.com/78281930/117556983-317d1100-b034-11eb-8f2b-41cb9eb0b7f8.png)

The user needs to enter all information in order to create an account. If the username is already in use, the page will inform the user. The user's password is hashed and added to the back end database, along with the rest of their data.

## Login Page

If the user is successful in creating an account, they will be brought to the login page to login with their new credentials. 

![image](https://user-images.githubusercontent.com/78281930/117557010-743ee900-b034-11eb-9f4d-395bfee5e5d9.png)

## Explore Page

Once the user logs in, they are brough to the Explore page where they can start planning their trip! They provide a trip name, region and state they'd like to explore, and dates of the trip. 

![image](https://user-images.githubusercontent.com/78281930/117557124-7786a480-b035-11eb-8648-18145ace23bc.png)

Once the user clicks "Explore" button, the parks in the region and state they selected are populated to the page. 

![image](https://user-images.githubusercontent.com/78281930/117557392-114f5100-b038-11eb-936a-c62145e8dcea.png)

The user can click "More Info" if they want more information on the park. If the user is interested in visiting that park during their trip, they can click "Add to Itinerary" to add the park to their trip! When the user goes to the "View Trips" page, they will be able to see their trips.

## View Trips

![image](https://user-images.githubusercontent.com/78281930/117557197-2a570280-b036-11eb-9bd0-fa64a65a4283.png)

On this page, users are able to edit their trip (name and dates), delete parks from the trip, or delete the trip entirely. If they want to go back to add more parks to a trip, they can go to the Explore page again and use the same trip name. 

## Back End

This project utilized Supabase for easy back end collaboration. The back end consists of 3 models: users, parks, and trips.

The users model holds user data. All passwords are hashed before being stored in the database. When a user adds a park to their trip, that park is added to the park table. Lastly, the trips table has a user's trip data. 

<u>Users</u>
  
![image](https://user-images.githubusercontent.com/78281930/118336289-fcab0700-b4d6-11eb-814d-4c47f0e99aa8.png)

<u>Parks</u>

![image](https://user-images.githubusercontent.com/78281930/118336503-79d67c00-b4d7-11eb-9d71-18f639e9150f.png)

<u>Trips</u>

![image](https://user-images.githubusercontent.com/78281930/118336781-fa957800-b4d7-11eb-81a0-71e785a53b4e.png)

## Project Features

### Back end:
* Node.js
* JavaScript
* PostgreSQL database (Supabase)
* RESTful API
* API reference: https://www.nps.gov/subjects/developer/api-documentation.htm
* Express package
* ES6 Templating
* Form validation
* Full C.R.U.D. functionality
* Bcrypt user authentication & validation

### Front end:
* HTML & CSS
* JavaScript
* Bootstrap elements
* Mobile responsiveness

*This site was originally built while working in a group in my bootcamp! I cloned the repo and added a few personal touches to it! If you'd like to see the original project, please visit [this page](https://github.com/mjbulostin/ParkRangers).*

