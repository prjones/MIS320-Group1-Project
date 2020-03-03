# Documentation for Ryder Scooters

# MIS407-Team-1
## Repository for the Team 1 Group Project
### Team Members:
```
* Peter Jones - prjones@iastate.edu
* Bailey Teply - bmteply@iastate.edu
* Charlie Donaldson - charlesd@iastate.edu
* Troy Jones - tbjones@iastate.edu
* Joseph Yang - sims192@iastate.edu
```
## Project Idea
For our project, we decided to make a transportation system for college campuses. We want to allow college students to ride electric scooters around campus. To do this, we plan to build docking stations for the scooters. These docking stations not only charge the scooters but keep them safe from harm, such as the weather. Our web application allows users to Ride, Reserve and Pickup a reservation.

### Documentation

For our web application, there are two login methods. One login is for users, where they can access the Ride, Reserve, Pickup and Account View methods. Then there is the manager login where the managers can view the map of the stations and data analytics on the scooters and users.

## Web Application
> You can view our running web application at https://ryderscooters.herokuapp.com/

## To Use the User View
> Click the User Login on the side bar
> When prompted, enter a username and password that match up from the Users.csv file in the ryderscooters/CSVFiles folder on this github page. In this csv file, there are 500 users with their username, first name, last name, password, and other information. User the First and Fourth columns when logging in as a user. Take your pick of which user you would like to log in with.
>From here you can select Ride Now, Reserve or Pickup. 

### Ride Now
>To Ride Now, select Ride Now from the side bar. You will then be prompted to enter a Start Location and End Location. We currently have 7 docking station locations:
> * Maple Willow Larch
> * Frederiksen Court
> * Memorial Union
> * State Gym
> * Kildee Hall
> * Parks Library
> * Towers
> When you select the Start Location and End Location, make sure to enter the exact location you wish to start at and travel to.

### Reserve
> To Reserve a scooter, simply click the Reserve button on the side bar and enter the Reservation Location you wish to reserve a scooter at.

### Pickup
> To Pickup a scooter, you must first have a scooter reserved under your username. If you want to pickup a scooter, make sure you are signed in with the same user you reserved a scooter with.
> Once you click the Pickup button on the side bar, you can select the End Location of where you wish to travel.





## To Use the Manager View
> First click the Manager Login button from the side bar
> Once prompted, enter the manager login and password. Currently you may use:
> * Username: prjones
> * Password: password
> We can add a manager username and password for you if you wish.

### View Analytics
> To view analytics, simply select the Analysis button on the side bar. This shows you the rate at which the scooters lose charge over their time, which is helpful because it estimates the life expectancy of the scooter. We will discuss more on this in our presentation.

### View Map
> To view the map of the stations, simply click the Map button on the side bar. Feel free to drag it around and play with it.

### View User History
> To view User History's, simply click the User History button on the side bar. This history table view will show you all the users who have taken a ride and show you simple data on their rides.


### View Scooter History
> To view Scooter History's, simply click the Scooter History button on the side bar. This history table view will show you every single ride transaction that has taken place.

## Logout
> Remember to click the logout button to return to the home page of the application.

## Other
> Some other things to note are the Home, About and Contact pages on the intial web application screen. These link you back to a website that we have made through squarespace which gives you more information about our company. Enjoy!


## Project Guidelines

>The project...
>* must primarily in Python (SQL, HTML/CSS/Javascript "front-end" could > be included in the project)
>* use interfaces such as Web, GUI, "Chatbot" style (text interaction), > or Jupyter Notebook.
> * must provide business value (you'll be expected to articulate this > in your presentations)
>   * This could be a new service that a business could be built around > (and thus be monetized in some way)
>   * Or, it could be a system that would provides a tangible cost > savings/efficiencies for a company.



