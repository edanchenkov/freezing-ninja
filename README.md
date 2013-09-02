#Installation
##Setup development enviroment
###Install Node.js

     sudo apt-get install nodejs

###Install MongoDB

     sudo apt-get install mongodb

##Install app

     git clone git@github.com:edanchenkov/freezing-ninja.git
     cd freezing-ninja
     npm install

If there are prolems with SSH and connection restriction, check this <a href="https://help.github.com/articles/generating-ssh-keys"> link </a> out. There is a test in the bottom of that page.

##Run app and db

###Run mongo

Run mongo manually

     mongod 

or as a service
 
     sudo service mongodb start

stop

     sudo service mongodb stop
     
restart 

     sudo service mongodb restart
     
###Run app

     nodemon app.js

or   

     npm start //this a shortcut which is defined in package.json.  

     
