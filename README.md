# Social Network API

## Table of Contents 
- [Description](#description)
- [User Story](#user-story)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [APIs](#apis)
- [Visual Representation](#visual-representation)
- [Demo video](#demo-video)

## Description

A back-end social network database api that allows the user to create, update, and delete data from the database using Insomnia.

## User Story:
`AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data`

## Technologies Used

- MongoDB
- Mongoose
- Express
- Moment

## Usage

- Clone this repo
- Install Insomnia
- Install express
- Install mongoose
- Install moment
- From the social-network-api directory, run `npm start`
- Use Insomnia to test api

## APIs

### Users

GET /api/users - Gets all available users <br>
POST /api/users - Create new user <br>
GET /api/users/:userID - Get user by ID <br>
PUT /api/users/:userID - Update a user <br>
DELETE /api/users/:userID - Delete a user <br>

### Friends

PUT /api/users/:userID/friends/:friendID - Add a friend to user ID <br>
DELETE /api/users/:userID/friends/:friendID - Delete friend <br>

### Thoughts

GET /api/thoughts - Gets all thoughts <br>
POST /api/thoughts - Create new thought associated to User <br>
PUT /api/thoughts/:thoughtID - Update a thought by ID <br>
DELETE /api/thoughts/:thoughtID - Delete thought <br>

### Reactions

POST /api/thoughts/:thoughtID/reactions - Create new reaction to thought by ID <br>
DELETE /api/thoughts/:thoughtID/reactions/:reactionID - Delete reaction <br>


## Visual Representation:
![Alt text](assets/images/Screen%20Shot%202023-04-10%20at%206.53.01%20PM.png)
![Alt text](assets/images/Screen%20Shot%202023-04-10%20at%206.54.19%20PM.png)
![Alt text](assets/images/Screen%20Shot%202023-04-10%20at%206.54.59%20PM.png)
![Alt text](assets/images/Screen%20Shot%202023-04-10%20at%206.55.40%20PM.png)

## Demo Video
[Demo](https://drive.google.com/file/d/1pj2PvN6maE19_QxRJ4hgmLa_ZlPXVRqT/view)