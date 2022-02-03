# Twittor:

This is a small express server ready to run and serve the public folder on the web.
It saves information in an IndexDB in the moment when there is no good internet connection
so that once a good internet connection is established it synchronizes with our small server.

The node modules must be rebuilt with the command

```
npm install
```

Then, for production running
```
npm start
```

To run on development
```
npm run dev
```
