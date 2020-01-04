# Assignment Made by Rohit Lal- Front-end application which would let the users help list and browse all Characters of Rick and Morty Show.

## How to Start

In the project directory, first run `npm install` to install the dependencies. Then you can run:

### `npm start`

Runs the app in the development mode. Should automatically open
[http://localhost:3000](http://localhost:3000) for viewing in the browser.

Alternatively, you can follow the directions below to build and run a production-optimized version.

### `npm run build`

Builds the app for production to the `build` folder. It correctly bundles React in production mode
and optimizes the build for the best performance.

Once this is done, you can easily serve it with a static server by running `npx serve build`.

### Create React App & TypeScript

### API Wrapper

I built a [small wrapper around the API](src/lib/api.ts). It uses `axios` for network requests and
uses `node-cache` to cache API responses for 10 minutes.

It is also [tested using Jest](src/lib/api.test.ts). Note that the tests are set to skip by default
since they hit the live API.


