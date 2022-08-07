### react-template
Creating a PWA reactapp
* In Terminal type **npx create-react-app react-template --template cra-template-pwa**

### Serving the PWA
The PWA will only be visible  when the build version of our application is available. Offline-first Progressive Web Apps are faster and more reliable than traditional web pages, and provide an engaging mobile experience:

* All static site assets that are a part of your webpack build are cached so that your page loads fast on subsequent visits, regardless of network connectivity (such as 2G or 3G). Updates are downloaded in the background.
* Your app will work regardless of network state, even if offline. This means your users will be able to use your app at 10,000 feet and on the subway.
* On mobile devices, your app can be added directly to the user's home screen, app icon and all. This eliminates the need for the app store.

##### Inside application directory, you can run several commands

* In Terminal type **npm start** and press return. Starts the development server.
* In Terminal type **npm run build** and press return. Bundles the app into static files for production.
* In Terminal type **npm test** and press return. Starts the test runner.
* In Terminal type **npm run eject** and press return. Removes this tool and copies build dependencies, configuration files and scripts into the app directory. If you do this, you can’t go back!

### Build and run the application

* In Terminal type **cd ~/git/react-template** and press return
* In Terminal type **npm start** and press return

##### Running PWA
* In Terminal type **cd ~/git/react-template** and press return
* In Terminal type **npm run build** and press return 
* In Terminal type **npm install --location=global server** and press return
* In Terminal type **serve -s build** and press return
