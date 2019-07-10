# CANU
Validierung eines objektiven Messinstruments zur Erfassung von Kreativität

# createst

### To launch the application:

1. Install dependencies in server and client:
`cd server && npm install`
`cd client && npm install`

2. Start the Server:
`cd server && npm run start`

3. Start the Client:
`cd client && npm start`

App runs in development mode on http://localhost:3000, Server runs on http://localhost:5000

### To build the application on the server

1. Build the Client:
`cd client && npm run build`

2. Start the Server:
`cd server && npm run start`

The project is now hosted on the server and available via http://creativity.lfe.mw.tum.de

### Nginx
The Client is served on `port :80`
Everything with the url `.../api/...` is rerouted to `por t:3000`
