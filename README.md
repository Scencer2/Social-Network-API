# Social-Network-API

This is a backend API for a social media app. it Allows users to create accounts, post thoughts, add friends, and comment on other posts. This app uses Express.js, mongoDB, Mongoose, and Insomnia for testing.
![image](https://github.com/user-attachments/assets/b96182eb-854a-4c46-aff7-df9d85a43884)


## Installation
Clone the repo:
   git clone https://github.com/yourusername/social-network-api.git
   cd social-network-api
Install dependencies:
  npm install
Start the MonboDB server and run the app:
  npm run dev


## Usage
Test the API in Insomnia using the following routes:
  👤 Users
GET /api/users – Get all users
GET /api/users/:userId – Get a single user (with thoughts and friends)
POST /api/users – Create a new user
PUT /api/users/:userId – Update a user
DELETE /api/users/:userId – Delete a user and their thoughts
POST /api/users/:userId/friends/:friendId – Add a friend
DELETE /api/users/:userId/friends/:friendId – Remove a friend

💭 Thoughts
GET /api/thoughts – Get all thoughts
GET /api/thoughts/:thoughtId – Get a single thought
POST /api/thoughts – Create a new thought
PUT /api/thoughts/:thoughtId – Update a thought
DELETE /api/thoughts/:thoughtId – Delete a thought

🔁 Reactions
POST /api/thoughts/:thoughtId/reactions – Add a reaction to a thought
DELETE /api/thoughts/:thoughtId/reactions/:reactionId – Remove a reaction

## Questions
If you have any questions feel free to contact me at:
  GitHub: https://github.com/Scencer2
  Email: Scencer2@yahoo.com

## Walkthrough Video
https://drive.google.com/file/d/14wktFsf_wq4j1PeDRnr4RorF09Jtcw0d/view
