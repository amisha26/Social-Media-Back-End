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