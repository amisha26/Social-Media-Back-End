### Social-Media New Back-End

* There were some issues with the old backend.
* To proply connect backend and front-end.
* Follow the below steps :-

<hr>

### For Backend Part :-

1. Make .env file and save the mongoDB server link there to connect with mongodb.
2. now start the server of backend by using 
```
npm start
```
3. Its shows port in use, use this command :-
```
sudo kill $(sudo lsof -t -i:x)
``` 
* Here x will be the port number ex:- ( 8080, 8000, 8800..etc ) 

4. If you are using this on local host wihtout the request url as ( http://localhost:8800 )
* Make sure to port the request to right port.

5. If you are using it on (http://localhost:8800/api/auth/register..)
* Make sure to use CORS


6. In app.js file or your main file which can also be ( server.js )

<hr>

### To use cors in your back-end

* Install CORS on root folder first
```
npm install cors
```

* Put it in App.js or Server.js of your set-up

```
const express = require('express')
const cors = require('cors')
const app = express()
app.use(cors())
```
<hr>


### For Frontend Part :-

1. Now the bcakend set-up is done.
2. Make sure you have all the dependecies are installed.
```
npm install
```
3. Now start the cliebt server
```
npm start
```

<hr>

#### Important :-

* Run both Back-End & Front-End in different port.
* Don't start the front-end server first  

### HAPPY CODING ✌️