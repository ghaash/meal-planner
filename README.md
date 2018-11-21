# Meal Planner

Meal Planner is a simple CRUD application that allows users to plan/track their meals.
This program was made as a group project for Oregon State University - CS 361 (Software Engineering I).

## Build the application

In the root directory, install dependencies

```bash
npm install
```

Install forever (CLI tool to ensure that a given script runs continuously)

```bash
npm install forever
```

Declare a port number to use in app.js

```javascript
/* in app.js */
app.set("port", 58188); // Set port number to 58188
```

Run the forever command

```bash
./node_modules/forever/bin/forever start app.js 58188
```

## Run the application

If you built the application on the OSU servers, make sure you are connected to the OSU VPN before accesing the URL below.
<flip3.engr.oregonstate.edu:58188>

Note: check which version of flip you build the application on, as the app could be running on any of the following 3 URLS:
<flip1.engr.oregonstate.edu:58188>
<flip2.engr.oregonstate.edu:58188>
<flip3.engr.oregonstate.edu:58188>
