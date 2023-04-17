# ICC-WORLD-CUP-2023

##Overview
As the World-cup 2023 is round the clock, so in our project we Scrapped data of Indian Cricketers who are in Indian Squad from different links. For GUI we created a website which contains all the details of each player. This Data can be viewed by the user in an interactive manner where he/she could compare each player against others in there respective formats. This website helps to pick a squad of 11 players, which can help India to win World-Cup 2023. This Website contains data of every player from the moment he started playiing international ODI cricket.

##Libraries Included
1) Pandas
2) matplotlib.pyplot
3) Express framework
4) Mongoose
5) BeautifulSoup
6) Bootstrap 5 framework
7) html5lib
8) requests

##Technology Used

###Concepts
1) BeautifulSoup: To scrape the data efficiently from the links by using its inbuilt functions.
2) Pandas: To create a dataframe and read the excel files
3) matplotlib.pyplot: To plot the graph out of the data created in dataframe and to save the graphs created and to save excel files.
4) Hbs: Its a template engine which is powerful than html and helps in creating the skeleton of the frontend.
5) CSS: Its basically used for styling the web page by using the different functions within it.
6) Js: its the main brain of the frontend of the websites which serves certain part on certain command by the client in the frontend.
7) Node.js: To create the back-end of Website
8) Express: its a framework of node.js which is used to serve files from the backend as response on request by the client.
9) Mongodb: Its the database where we stored all the necessary data of the players.
10) mongoose: it basically acts like a medium between node.js and mongodb which helps to get the data from the database i.e. mongodb

###Working
First we scraped the data of all the players using beautifulsoup and then we plotted line and bar graphs using pandas and matplotlib.pyplot and saved all the files. Then we created the frontend of the website using hbs, css and js then we created a file called app.js in src folder where we connected to the database i.e. mongodb using mongoose, in this file we set template engine as hbs i.e. handlebars in which all the files were coded. Then in routes folder we created a main.js file in which we are serving the files created in hbs to the client as per the request. Here we are fetching data from the database which is required while serving the file.
Further, index.hbs in views folder is the home page or landing page of our website where the user is given options to choose which player's statistics he/she wants to view or which player he/she wants to compare with.

##Usage Instructions
first download all the files from our repository, make sure that your local system has mongodb, mongoose and mongodbcompass installed. Also, make sure that your local system has nodemon,npm and all other frameworks mentioned in our package.json installed.
Just simply open command shell of your local system in Adminstrative mode and type the command "mongod" to start the server and then open mongodbcompass and then get connected to your server.
Now simply open the terminal and type "npm start" so you would get a text in terminal "server started listening on port::5556" after that open your favourite web browser and then type in the url section "localhost:5556". Done! you are now able to access the website.

##Team Members Info
1) Sri Surya Makkapati (IMT2022567)
2) G Sujit (IMT2022558)
