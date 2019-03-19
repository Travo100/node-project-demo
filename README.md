# node-project-demo

To get this demo to work you will need to make a `.env` file at the root of your file directory for this project 

### Directory Structure  
<pre>
node-project-demo
 ┬  
 ├ .env 
 ├ .gitignore  
 ├ index.js 
 ├ package.json  
 ├ README.md 
</pre>

Inside of the .env provide the following:
```
SPOTIFY_CLIENT_ID = YOUR_SPOTIFY_CLIENT
SPOTIFY_SECRET_KEY = YOUR_SPOTIFY_SECRET
```

Then run `npm install dotenv node-spotify-api` to install the packages needed to get started with this demo

Then run `node index.js` to see the data from the `node-spotify-api` package.