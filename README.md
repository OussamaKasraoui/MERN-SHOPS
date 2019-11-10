# MERN-SHOPS
Evaluation Project for UnitedRemote


Hello Coders, this project is an assessment for my skills as a Javascript Full Stack developer , ( i hope i'm skilled enough  :D ) otherwise i welcome all your feedbacks, contributions, also if you have projects ( no matter What programming language is required i'm open to learn new topics ) i'd love to contribute in the development process.
you can reach me out through my email : kasraouioussama@gmail.com

Now let's dive a little bit in the explaination, in this project i used The MERN STACK( Mongo Express ReactJs NodeJs ) to build a Web application wich responds to the requirments listed in this link bellow :
https://github.com/hiddenfounders/web-coding-challenge/blob/master/coding-challenge.md


the project consists of two folders One for the server side scripts, and the seconde for the Client side scripts. besides some Envirenments Variables which must be declared first of all ( check MongoDB section ) :

SECRETORKEY="Your Secret Or Key "               [STRING]  // required by JWT      Library

APP_PORT="Application Port Number"              [INT]     // required by Express  Frameword

DB_USER="Username"                              [STRING]  // required by MongoDB  Library

DB_USER_PASS="Password"                         [STRING]  // required by MongoDB  Library

DB_URI="mongodb://localhost:${APP_PORT}/SHOPS"  [STRING]  // required by Mongoose Library


# BackEnd Folder
in this folders resides the server side dependencies, So make sure you have NODEJS and NPM installed first, then open your Commande Line :

1 - git clone https://github.com/OussamaKasraoui/MERN-SHOPS.git

2 - cd MERN-SHOPS/BackEnd

3 - npm install       // to install application's dependencies ( Only for the first Time )

4 - node app.js       


# frontend Folder
in this folders resides the client side dependencies, I suppose you had already cloned the project, so in your Commande Line make sure you are in MERN-SHOPS directory then:

1 - cd frontend

2 - npm install   // to install application's dependencies ( Only for the first Time )

3 - npm start

# MongoDB
wich will stand for a NoSQL database, holding our web application's data, specially the user's account credentials and shop's informations. so make sure you have MongoD service already installed and congured. also pay attention to make a file named ".env" then put all Envirenments VARIABLES listed above in that file.


# NB
Almost app related Logical Errors i faced, are handled otherwise check Console if you have your Own.
i would be greatfull if you share me the Output.
