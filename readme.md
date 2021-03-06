##REST API Sample Using AngularJS, Ionic Framework and Parse

This sample shows how to use all of the HTTP verbs with the `$http` service available form angularjs to interact with a data set in [Parse.com](http://www.parse.com).

[See Documentation on $http Service in AngularJS](https://docs.angularjs.org/api/ng/service/$http)

----

####Configure Your Environment for Ionic Framework:
+ [See Ionic Getting Started For More Specific Details](https://www.ionicframework.com/getting-started/)
+ First, install Node.js. Then, install the latest Cordova and Ionic command-line tools. Follow the Android and iOS platform guides to install required platform dependencies.

+ _Note: iOS development requires Mac OS X. iOS simulator through the Ionic CLI requires the ios-sim npm package, which can be installed with the command sudo npm -g install ios-sim_

####For this sample to work you must do the following:

+ Create an account in [Parse](https://www.parse.com/apps)
+ Create a new application by clicking on "Create a new App" Button in the Dashboard
+ Create a user in that new application, set the username to `admin` and the password to `test`

    **Screen Shot: Creating a new user account in application**
![alt tag](screenshots/Screenshot-Add-A-User.png)
+ Create a new file in the `www\js` directory of the application called `credentials.js` 
+ Go to the Settings - Keys Section and copy appropriate keys and replace them in the `credentials.js` file you just created

    **Screen Shot: Locating authentcation keys for application**
![alt tag](screenshots/Screenshot-Show-App-Keys.png)

####credentials.js example format

    PARSE__HEADER_CREDENTIALS = {
        "x-parse-application-id": "YOUR-APPLICATION-ID",
        "x-parse-rest-api-key": "YOUR-REST-API-KEY"
    };
