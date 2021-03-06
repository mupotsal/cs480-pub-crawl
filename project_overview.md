# Pub-Crawler-App

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
Social media application for partier to coordinate partying activities. 
Written in Java using Android Studio.

To enhance the party-adventurers next night out with this charming and easy to use mobile experience. 

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Social App
- **Mobile:** The app is geared to be used "on the fly" as a group of friends organize and travel to different destinations across a city's night-life ecosystem. It uses real-time technology, such as maps, location info and recommendations, and user/friends status.
- **Story:** The app is used as a way to enhance every individual aspect of "going out on the town" and having a good time. Allows very straightforward ways of coordinating whats going down on the town and which friends are looking to have fun. Allows users feasible ways to capture their experience admist a night of fun and euphoria to later reminisce about. Incorporates a drink counter alert and ride sharing link so users can stay safe and worry less. Helps keep the night dynamic by alerting users to interesting events going on and keep the user on track if they have made an itinerary for the night.
- **Market:** The app is geared to be customizable towards a number of user experiences and issues associated with recreational event planning. Although, most of the market will be centered around younger generations experiencing either the big-city or college town nightlife.
- **Habit:** Its after 5, works done, its the weekend, etc, and the user is determined they are now in "party-mode" until they're tucked neatly into bed. They're looking for fun things to do and fun friends to do it with. Our app is geared as a companion to enhance that experience from beginning to end during this rush hour of fun seeking. It handles a number of issues associated with the experience that requires constant interaction with the user. The user is to associate this mode, mentality, and experience with our app. Anticipated the average user uses the app on a bi-weekly basis, each session across several hours at a time.
- **Scope:** The project will be divided up into Required and Optional stories. A majority of the Required stories will be implementing functions we've already covered in previous assignments and labs. These Required stories making up the "stripped-down version" of our app hopefully will be challenging but doable by the end of program. Nonetheless it will be interesting to build from start to finish.

I can affirm that if this app were completed and available on the Play Store, I and fellow friends would be using this app on a weekly basis minimum.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

A. Epic 1 - MapScreen -> Events and Friends Real Time Display

- [ ] As a person actively getting lit, I should be able to display my GPS location in real time so my friends can join me.

- [ ] As a user, I should be able to set permissions for who can view my location.

B. Epic 2 - Event Planner -> Allow users to plan out the night like an itinerary

- [ ] As a person planning to go out later, I should be able to make a schedule for where I want to be and when.

- [ ] As a person who is currently out on the town, I should receive notifications telling me when it's time to move to the next bar on my schedule.

- [ ] Timer feature to alert users when to move onto the next activity

- [ ] As a person who wants to stay in my location, I should be able to delay the timers on my schedule and edit timings, or cancel locations on my schedule.

- [ ] Can choose to skip or delay the timer incase users want to stay in one location.
 
C. Epic 3 -  Night tracker -> keeping track of what you and/or your friends are doing throughout the night

- [ ] As someone wanting to reminisce, I want to keep a copy of the itinerary that was updated throughout the night

- [ ] As someone who cares about my physical/financial health and As someone who spends too much money, drinks too much, or blacks out: I should be able to keep a tally of how much I've had to drink today, what I drank, and where; I should be able to view a record of what I drank on a certain date, and where

- [ ] Drink tracker -> keeping track of what you and/or your friends are consuming throughout the night -> keeps track of sobriety and track of experience for record keeping

D. Epic 4 - Bar, restaurant, kareoke, game-night, music venues -> college town type of events going on in town

- [ ] As a user, I should be able to see the locations of bars and other venues in my region

- [ ] As someone looking for social interaction, I should be able to see on the map which venue the most people are currently at, based on user data collected from the app.

E. Other Misc Required User Stories

- [ ] As a user ready to descend on the night-life scene, I want to see what events are playing and who is doing what or wants to do what
 
- [ ] As a user, I want to create a plan for me or my friends listing what I'd like to do or what I plan on doing

- [ ] As a user, I want to be able to record my night to share with other friends, for future reminiscing, or alert of my alcohol/drug use status for my safety

**Optional Nice-to-have Stories**

A. Epic 1 - MapScreen -> Events and Friends Real Time Display

*

B. Epic 2 - Event Planner -> Allow users to plan out the night like an itinerary

*

C. Epic 3 -  Night tracker -> keeping track of what you and/or your friends are doing throughout the night

- [ ] Link to ride sharing service ie uber to avoid drunk driving

- [ ] As a friend, I should be able to see and share my friends' records for how much they've had to drink so I can choose to join them or not.

- [ ] As a busy and probably not sober user, I should be able to interact with this feature on the main map screen for convenient use.

D. Epic 4 - Bar, restaurant, kareoke, game-night, music venues -> college town type of events going on in town

- [ ] As someone who likes to party, I should be able to filter the list of locations in my area to see attributes, like which places serve alcohol and which places are currently open.

E. Other Misc Optional User Stories

- [ ] Based on user information, can make event recommendations

### 2. Screen Archetypes

* Login Screen

  * logs in user OR refers user to the register screen

* Register Screen

  * registers user and immediately logins them in

* Profile Screen

  * As someone wanting to reminisce, I want to keep a copy of the itinerary that was updated throughout the night.

  * My Account info

* Settings Screen

* Map Screen

  * As someone looking for social interaction, I should be able to see on the map which venue the most people are currently at,       based on user data collected from the app.

  * As a user, I should be able to see the locations of bars and other venues in my region

  * real-time display of local events and friends
 
  * As a person actively getting lit, I should be able to display my GPS location in real time so my friends can join me.
 
  * As a user, I should be able to set permissions for who can view my location.
  
  * As a user, I should be able to see the locations of bars and other venues in my region

* Creation Screen

  * As a person planning to go out later, I should be able to make a schedule for where I want to be and when.

  * Event Planning Feature

* Stream/Detail Screen

  * As someone wanting to reminisce, I want to keep a copy of the itinerary that was updated throughout the night.

  * As someone who cares about my physical/financial health and As someone who spends too much money, drinks too much, or blacks out: I should be able to keep a tally of how much I've had to drink today, what I drank, and where; I should be able to view a record of what I drank on a certain date, and where

  * Details of Creation Screen
 
  * As a person planning to go out later, I should be able to make a schedule for where I want to be and when.
 
  * As a person who is currently out on the town, I should receive notifications telling me when it's time to move to the next bar on my schedule.
 
  * As a person who wants to stay in my location, I should be able to delay the timers on my schedule and edit timings, or cancel locations on my schedule.

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Home Feed/Stream Screen
* Map Screen
* Create Screen/Itinerary
* Profile Screen
* Settings Screen

**Flow Navigation** (Screen to Screen)

* [Login/Register]
   * [On Login -> Main Menu]
   * [On Sign Up -> Register]
* [Register]
   * [On Login -> Main Menu]
* [Main Menu]
   * [On Hamburger click -> open side app drawer]
   * [On Settings -> Settings]
   * [On Party Stream -> Party Stream]
   * [On Create Session -> Create session]
   * [On Profile -> Profile]
* [Party Stream]
   * [On Hamburger click -> open side app drawer]
   * [On Settings -> Settings]
   * [On Main Menu -> Main Menu]
   * [On Create Session -> Create session]
   * [On Profile -> Profile]
* [Create Session]
   * [On Create Session -> Party Stream (in session)]
   * [On Hamburger click -> open side app drawer]
   * [On Settings -> Settings]
   * [On Main Menu -> Main Menu]
   * [On Profile -> Profile]
* [Profile]
   * [On Hamburger click -> open side app drawer]
   * [On Settings -> Settings]
   * [On Main Menu -> Main Menu]
   * [On Create Session -> Create session]
* [Settings]
   * [On Hamburger click -> open side app drawer]
   * [On Main Menu -> Main Menu]
   * [On Create Session -> Create session]
   * [On Profile -> Profile]

## Wireframes
<img src="https://i.imgur.com/aoIki2C.jpg" width=600>
<img src="https://i.imgur.com/AnWOgsu.jpg" width=600>

### [BONUS] Digital Wireframes & Mockups
* https://www.figma.com/file/Ob60uh4zGWYOr7froocubG/PubC?node-id=0%3A1

### [BONUS] Interactive Prototype
* https://www.figma.com/file/Ob60uh4zGWYOr7froocubG/PubC?node-id=0%3A1

## Schema 
[This section will be completed in Unit 9]
### Models
Model: User 

| Property | Type | Description |
| --------- | ------| ------------- |
| objectId | String | unique ID for user |
| username | String | username for login |
| password | String | password for login | 
| email | String | user's email address | 
| name | String | user's name |

Model: Drink 

| Property | Type | Description | 
| ---------- | ---- | ------------- |
| user | Pointer <_User> | which user had the drink |
| type | String | what kind of drink (beer, wine, etc.) | 
| quantity | Number | how much of that drink was had | 
| location | GeoPoint | where that drink was had | 
| dateDrank | Date |  when the drink was had |

Model: Schedule 

| Property | Type | Description |
| ---------- | ---- | ------------- |
| location | GeoPoint | itinerary item: where to be |
| startTime | Date | when to be at that location | 
| endTime | Date | when to leave that location |

### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
