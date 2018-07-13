# Following are the instructions to run the app:

## Pre-requisite
* Xcode 9
* Swift 4.0
* iOS 9.0+
* Cocoa pod 1.1 or later

## Pod install
* Open terminal and go to the project directory 
* run ‘pod install’ command on terminal

## Project architectutre
* MVC
* Model Layer
Model layer parse the result into application model
* Network Layer
Network layer is responsible for calling webservice
* Database Layer 
Database layer uses realm database and convert db data into application object and vice versa
## Third party libraries
* AFNetworking - to asynchronously download images from the web
* RealmSwift -  database framework for login and creating users
