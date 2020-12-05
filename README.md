# PLUGMAN 🚀🚀🚀🚀

To Open the web app go to 
[plugman.netlify.app](https://plugman.netlify.app).

This project was created with React, Typescript and redux.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).



In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

## Folder structure
`/.github/workflows` contains workflows to auto buld and deploy to production

`/public` contains static files

`/src` contains the actual code

`/src/Providers` contains different providers, otherwise known as services

`/src/components` contains the different react components

`/src/store` contains the redux store configuration with different reducers  and actions


## Major take away

The `socket.service.ts` file in `/src/Providers` contains all the socket configuration, emitters and listeners

The `Collections.service.ts` file in `/src/Providers` contains all the Collections data including the requests structure and different objects to keep track of the active state of each requests and folders


