## how to run
Google OAuth 2.0

Start server
```
node server.js
```
Start client
```
npm start
```

## env
Client env
```
REACT_APP_SERVER_URL = http://localhost:4000
REACT_APP_CLERK_PUBLISHABLE_KEY=
```
Server env
```
GOOGLE_CLIENT_ID=<the client ID you created earlier>  
GOOGLE_CLIENT_SECRET=<the client secret you created earlier>  
REDIRECT_URL=http://localhost:3000/auth/callback  
CLIENT_URL=http://localhost:3000  
TOKEN_SECRET=<any random string>  
CLERK_SECRET_KEY=
```

## credits
https://clerk.com/blog/oauth2-react-user-authorization
