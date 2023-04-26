## Spring Security OAuth - Authorization Code
A simple Angular client for Authorization Code Flow

## Run the Module
To run the application, first make sure both authorization and resource server are already running
Then, build the app using command line:
```
mvn clean install
```

Change directory to src/main/resources:
```
cd src/main/resources
```

Finally, run our app on port 8089:
```
npm start
```

--- 
[update]: Angular complains with 'error:0308010C:digital envelope routines::unsupported'

=> suppress error with
```
set NODE_OPTIONS=--openssl-legacy-provider
```
---

Hit the app: 
http://localhost:8089/