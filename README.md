### Social-Media Back-End 

* Node.js
* MonogoDB 
* Socket.io

### To run this from clone
```
git clone
npm install
npm start
```
* Check the package.json start script before npm start
 
### To run as new project

```
npm init
```
```
npm add express mongoose dotenv helmet morgan nodemon
```
```
np start
```

#### Error you can face regarding port used :--

* solution

```
sudo kill $(sudo lsof -t -i:8080)
```
### For front-End Repo

[Font-End](https://github.com/amisha26/Social-Media-FrontEnd)


### To run this social-media app

1. Fiest make your mongoDB cluster-database.
2. Put your MONGO_URL in  ( .env )
3. Now start backend server using - ( npm start )
4. If its shows backend running you are good to go.%
5. Now start the client server ( fron-end ) using - ( npm start )

* Run both Back-End & Front-End in different port.
* Don't start the front-end server first  

### HAPPY CODING

