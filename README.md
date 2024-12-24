# Full Stack Group-chat-app
## :grey_question: what it does
group chat app is a real-time messaging platform built using Socket.io. It allows users to join chat rooms, send and receive messages instantly, and engage in group discussions. The backend is developed using Node.js and Express, while the frontend is created using HTML, CSS, and JavaScript. Socket.io enables bi-directional communication between the server and clients, ensuring real-time message delivery. The app also supports user authentication and displays a list of users currently active in the chat. With its seamless real-time communication, users can have interactive and immediate conversations.

![Screenshot 2024-11-18 220010](https://github.com/user-attachments/assets/cb79c382-93a5-4025-962e-3e744c9be3f1)


## :open_book: things i learned 
1. Implementing the MVC (Model-View-Controller) pattern
1. Creating dynamic routes
1. Using JWT for authentication
1. Integrating Brevo email service for password recovery
1. Hashing passwords with bcrypt
1. Working with Sequelize ORM
1. Real time connection using socket.io
1. How important pagination is 
1. Implementing transactions to maintain consistency in the database
1. Utilized AWS S3 for file storage

## :hammer_and_wrench: how to run
### Prerequisites
1. **Node version 18.x.x**
1. **generate JWT secret key**
1. **create razorpay account**
1. **create Brevo SMPT account**
1. **create AWS account and get s3**

### Cloning the repository
```shell
git clone 
```
### Setup .env file
```js
JWT_SECRET = 
DB_NAME = 
DB_USER = 
DB_PASS = 
DB_HOST = "localhost"
PORT = 
SMPT_API_KEY = 
AWS_BUCKET_NAME = 
AWS_ACCESS_KEY = 
AWS_SECRET_ACCESS_KEY = 
```
### Install packages

```shell
npm i
```
### Start the app

```shell
npm start
```
