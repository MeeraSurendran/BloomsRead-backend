## **Front End Repo**
https://github.com/maria-salman/wbdv-sp21-project-frontend

## **Instructions**
Our project is hosted remotely at: http://wbdv-sp21-finalproject.herokuapp.com/

If you wish to run this app locally, both the front end and back end repos must be used to run the application. Steps to run the front end can be found in the README in the front end repo listed above.

### **Steps**
1. Clone repo
2. Install Mongo
3. In the command line, run: ```npm install```
4. Create a folder in the project to store data locally. 
5. Run the command ```mongod --dbpath data``` (where data is the name of the data folder created in step 4.)
6. Run shell in another terminal window with command ```mongo```.
7. In .env file, define the following variable necessary to run the app

    ORIGIN_NAME = http://localhost:3000
8. Run the server by running command ```node server.js``` or adding a configuration in Intellij called "server" to run server.js.
