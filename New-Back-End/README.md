### Social-Media New Back-End

* There were some issues with the old backend.
* To proply connect backend nad front-end.

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
here x will be the port number ex:- ( 8080, 8000, 8800..etc ) 
4. If you are using this on local host wihtout the request url as (http://localhost:8800)
- Then make sure to psot the request to right port.
5. If you are using it on (http://localhost:8800/api/auth/register..)
- make sure to use CORS

### To use cors in your back-end

```
npm install cors
```
```
const express = require('express')
const cors = require('cors')
const app = express()
app.use(cors())
```

6. In app.js file or your main file which can also be ( server.js )