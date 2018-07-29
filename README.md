# Installing dependencies
To install the project’s dependencies, run
> npm install
You’re now ready to run and see your app!

# Run the app in development mode
To run the app locally, run
> npm start
This will start a local server on port 8081. Open http://localhost:8081 to view your app in the browser. Note that this server can continue running as you’re making changes to your application, which you will see if you refresh the browser tab.
If the port is already taken on your computer, or if you need to change the default hostname (because you’re using a Docker container, for example), you can configure them using command line arguments:
> npm start -- --hostname 0.0.0.0 --port 4444

# Run the tests
Check out the Application testing page for more information about the tests. For a quick way to run the tests, run
> npm run test

# Available scripts
In the app’s root directory you can run:
> npm start
to run the application in development mode.
> npm run test
to run the application’s unit and integration tests (see the see the testing section for more details. To run just the unit or integration tests, both npm run test:unit and npm run test:integration are available.
> npm run build
to build your application for production (see the building and deploying section for more details).
> npm run serve:static
to serve the static built application
> npm run serve:prpl-server
to serve the prpl built application

The complete list of scripts can be found in the package.json file.
