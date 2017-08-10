# my-microblog
A simple microblog made with NodeJs, Express and MongoDB, build user interface based on Bootstrap.  
Functions like signup, login, signout, publish blogs and delete blogs are included.

## Build  
first of all we are supposed to connect the database mongodb, and then use git bash to open the web page  
### connect database  
1.download and install MongoDB if you don't have it on your computer, else jump to next step  
2.open CMD and locate to folder 'mongodb' with 'cd' command  
3.create a new folder 'blog' with 'mkdir' command (or any other name you like)  
4.locate to folder 'bin'  
5.run 'mongod --dbpath ../blog', then the default 27017 port will be opened  
### git bash  
1.run 'npm install' to install the dependencies  
2.run 'node index.js'  
3.visit 'http://localhost:8000' to see the microblog hosted locally(make sure the port 8000 is not taken)  

you can sign up an account and log in to write some blogs. Just enjoy it!
