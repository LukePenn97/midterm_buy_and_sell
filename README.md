### User Stories

- A _user story_ describes how users will interact with your application
- They have the form: As a ______, I want to ______, because ______.

BREAD

BROWSE - As a user, I want to be able to browse featured items, because I want to know what         is featured today.
As a user, I want to be able to search with parameters because I only like cats.

READ - As a user, I want to be able to look at a specific item to see its details.

EDIT - As an admin, I want to be able to edit previous posts because I might have new info or make a mistake.
As an admin, I want to be able to mark items as sold when they are sold because they are sold.

ADD - As an admin, I want to be able to add new listings.
As a user, I want to be able to favourite listings that i am interested in.
As a user or admin, I want to be able to message other users or admins to ask about listings, on site or on email/text.

DELETE As an admin, I want to be able to delete posts.


### User Scenarios
- A _user scenario_ is a syntactic alternative to user stories
- They have the form: Given _____, when ______, then ______.
- eg. Given _that I am logged in_, when _I click favourite on a post_, then _it is added to my favourites_.
- You can also chain on an _and_ to user stories/scenarios
- eg. Given _that I am logged in_, when _I click favourite on a post_, then _it is added to my favourites_ **and** _the save icon will change to indicate success_.

### ERD
- The user stories provide you with nouns (eg. user, posts, favourites)
- Use these nouns/entities to build out your database (ie. tables are the nouns from the stories)

### Routes
- Once you know the resources that you'll have, write out the routes that you'll need to perform BREAD operations on those resources
- Remember RESTful conventions (they make it much easier)

### MVP vs MVD
- There is a concept in development of an MVP, the Minimum Viable Product
- An MVP has just enough features to be useful to a user
- This concept helps streamline the development process and help keep the team on target
- For mid-terms, we want to focus on the MVD, the Minimum Viable Demo
- **If you aren't going to demo it, don't build it**

### Wireframes
- Draw out the structure of your web pages
- This will make it much easier to build out these pages later
- This is also a great opportunity to get input from all of the team members
- Design matters... however you are a developer, not a designer
- Get inspiration from websites you visit

### Tech Choices
- We have made all the tech choices for you
- Back End: Node and Express
- Front End: HTML, CSS, JS, jQuery, Bootstrap

### The Mid-term Skeleton
- Use the provided `node-skeleton` as a template for your project
- This will get you up and running quickly

### SPA vs Multi-page App
- These concepts are not mutually exclusive
- You can choose one or the other or both

### Git
- Use Git best practices (ask a mentor for clarification if you need it)
- Use branches

### DO NOT CODE ON MASTER
- I repeat, do not code on master

### Splitting up the Work
- Horizontally - whole team working on front-end or back-end at the same time
- Vertically - divide the work between front-end and back-end
- Pair Programming - working together on the same tasks

### Communication
- Make sure to communicate with your team members
- Use Slack, iMessage, Google Hangouts, whatever... just make sure that everyone is on the same page

### Deployment
- Decide if you want/need to deploy your application to the cloud
- Ask a mentor for assistance/advice if your team decides to deploy
