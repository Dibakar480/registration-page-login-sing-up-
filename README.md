# registration-page-login-sing-up-
Dibakar 
<h1 align="center">
    <b>User Registration & Login systems in<br> Node.js using MongoDB </b> 
<br>
</h1>


<p align="center">
  <a href="/LICENSE"><img src="https://img.shields.io/github/license/guruhariharaun/Registration-and-Login-Form-in-Nodejs-and-MongoDB.svg?style=flat-square"></a>
</p>


## What is this for?
Myself Dibakar ghosh I have been created Registration & Login systems .This is a Simple User Registration & Login systems app done with Node.js Framework using MongoDB(Atlas) as the data store, Express as the routing system, Body-parser as the parser for webpage, Express-session used  to track the user's session and of course Mongoose to make interacting with Mongo from Node easy.



### Deployment
This Project is **[Live](https://reg-login-using-nodejs-mongodb.herokuapp.com/)** on: 🌍 **https://reg-login-using-nodejs-mongodb.herokuapp.com/**

## Running the tests

### •Registration Form:
Allows the user to register their account by filling their Email, Username, Password.

![registration](https://user-images.githubusercontent.com/127974192/225374020-1763b345-6c1a-49a4-9415-c258c11617b6.PNG)

### •Login Form:
If the user has been registered on the app, can login by passing the credentials.

![data](https://user-images.githubusercontent.com/127974192/225373113-4c687c64-43c1-4c1b-9880-9e541c625ad2.PNG)

### •User's Profile:
After the user logged in, a simple profile with the user's username and password <br>displayed with a session Logout button.

![userdb](https://user-images.githubusercontent.com/127974192/225374185-0d09b94f-25bf-4d56-872e-9b57aab485b8.PNG)

### •Password Reset:
If the user forget his/her password, can reset by entering the registered Email id <br>and reset the password.

![forgetpass](https://user-images.githubusercontent.com/127974192/225373648-10b2b775-fc08-4dc8-a7b1-2f5000988fb5.PNG)

### DataBase:
Here we use **[MongoDB Atlas(Cloud)](https://www.mongodb.com/cloud/atlas)** as the database. Here we have two collection created, named as:
- users.
- sessions.

A Collection(**Users**) is populated with the user's credentials.

![sessiondb](https://user-images.githubusercontent.com/127974192/225374366-c6cb72ce-f645-4e85-ae1e-54e52500c510.PNG)

A Collection(**session**) is created which stores the users Logged session.

![userdb](https://user-images.githubusercontent.com/127974192/225374473-632d1ff8-83c5-4e38-8e17-117d9cebfed3.PNG)
<br>
<br>
<br>

## Prerequisites
Tools that we need to run this app:

- ***[Node.js](https://nodejs.org/en/)***
- ***[Node Package Manager](https://www.npmjs.com/get-npm)***
- ***[MongoDB (Atlas)](https://www.mongodb.com/cloud/atlas)***

## Installing
```
npm install
```
## Connection to DataBase Access
At line 11 on ```./server.js``` change ***```<DB_USERNAME>```*** with your DataBase UserName & ***```<DB_PASSWORD>```*** with your DataBase Password.

## To Run the App
```
node server.js
```

The server will start Running on
+ http://localhost:3000/


## Author

| Author                | 
| --------------------- | 
| **Dibakar ghosh**     | 


## Acknowledgments

I would like to express myself and efforts .  I am eternally grateful to you.

<br><br>
<div align="center">
<a href="https://www.buymeacoffee.com/YwGKcxa" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" style="height: 51px !important;width: 217px !important;" ></a></div>
<p align="center">
  Made with ❤️ by Dibakar Ghosh <br>
</p>

