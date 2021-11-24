# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/modules/assignments/project-outline)


## Submission Instructions

### Overview

Have you ever been bored at home, wondering if there was anything going on around you? Well we have, and we want to create a solution. Our application will allow both locals and tourists to find events going on in their current locale. It will also allow vetted event planners to post their events, and give them a platform for their event to reach the public. As users search for events, they will be able to filter their searches by distance from them, certain location, key words, name, price, and whether or not an event is child-friendly, among other things. Their search results can be displayed on either a map or a list, and as users browse, they will be able to favorite events that interest them to have easy access at a later time. Once a user starts to interact with the site, they can choose to receive notifications about upcoming events that might interest them or are going on around them.

As an event planner, you will be able to display important information about your event, such as time, date, cost, location, name, description, etc. As your events are created, they will appear in searches and users will be allowed to favorite them. You also have the option to edit an event after posting it, in case your event information changes. Lastly you can keep track of the different events you've hosted on your profile, which will display any upcoming and past events you've planned or are planning.
### Features

Create Event - Users with specific authorization will be able to create events: Name, Date, Description, location, Cost

Edit Event - Users with specific authoriztion will be able to edit events

Search with Filter for Event - A search engine that allows for specific keywords or filters so a user can look for the vents that they are interested in. 

User login + Authorization - Users will be able to create accounts (event searchers or Event planners), and log in to their type of account. Each user will have a unique profile page with their saved events or events they have created.

Favorite Events - Event searchers will be able to save and view events on their profile. (notifications will pop up for user when events are coming up - see things we have to learn).

Display Events - The user will be able to view the events according to their specific search or location. Events will be displayed in different ways, either by an interactive map or a list of events.

### Technologies

Java, mySQL, Angular, SpringBoot, Hibernate, Thymeleaf

### What I'll Have to Learn
OAuth - allow users to login user other sites like google/facebook etc. A way to use OAuth through Spring security.

Interactive Mapping API - We are looking into Google Maps API or Yelp API so a user on our app can look for events in their area

Web scraper - We are looking into implementing a web scraper to pull

Event Authentication - We are working on a way for events to be authenticated as real events before being posted, possibly by only allowing those with the correct event authorization (event planners) to create/edit events.  We could have a mod system/administrator role in place to monitor events as they are posted.

Notifications - This would alert a user with a profile of upcoming events in their area. We will need to do more research in how to implement this. We would need to track date/location

### Project Tracker
http://trello.com/b/9BUbb2Ow/ateamliftoff
