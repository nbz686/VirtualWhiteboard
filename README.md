# VirtualWhiteboard
Work in progress. Implementing a virtual whiteboard.
I used WSL2 to run the code, but should also work on other platforms. 

#Requirements
To run the code you need to have a python installation and pip installed. 
With pip you should install the following packages: 
 - bcrypt, 
 - flask, 
 - flask-sqlalchemy, 
 - flask-flask-login, 
 - passlib

Furthermore you need to have sqlite installed in order for the database part to work. 

#Credits where due: 
I used a lot of these two implemenations: 
 - https://codepen.io/dcode-software/pen/ExXzdVM
 - https://github.com/arpanneupane19/Python-Flask-Authentication-Tutorial

## How to run code
Navigate to the directory with the 'app.py' file. 
run 'flask shell' in your command line
Run the following commands in the shell: 
 - flask shell
  - from app import app
  - app.app_context()
  - from app import db
  - db.create_all()
  - exit()
Now run, in the command line: 
 - python3 app.py. 

## How to use the 'website':
Click on the link in your terminale and you will see a locally hosted version of a login page. 
 1. Register yourself as a user
 2. Navigate to the login page. 
 3. Enter the login details. 
 4. You should now see a new page with the possiblity of creating sticky notes. 
 5. You can create a new sticky note
 6. You can delete a sticky note by double cliking on an existing note. 

