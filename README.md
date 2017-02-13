# Ionic DreamHouse for PropertyWebBuilder

This is a fork of the Ionic DreamHouse sample application that demonstrates how to build mobile apps with Ionic 2. Read more about it here:  http://coenraets.org/blog/2016/11/new-and-improved-ionic-2-sample-application/

The reason for this fork is to adapt the code to work with PropertyWebBuilder as the backend API providor:

https://github.com/etewiah/property_web_builder/issues/6


## Installation Instructions

Follow these instructions to install the app and run it with the mock (in-memory) data services:

1. **Make sure you have the latest version of Cordova and Ionic:**
    ```
    npm install -g npm
    npm install -g cordova
    npm install -g ionic
    ```

1. Clone the repository:
    ```
    git clone https://github.com/dreamhouseapp/dreamhouse-mobile-ionic
    ```

1. Navigate to the `dreamhouse-mobile-ionic` directory :
    ```
    cd dreamhouse-mobile-ionic
    ```

1. Install the dependencies
    ```
    npm install
    ```
  
1. Run the app in the browser
    ```
    ionic serve
    ```

## Using REST Services (Currently under development)

Follow these instructions to run it with the REST data services:

1. Install the PropertyWebBuilder implementation of the REST services (see [this repository](https://github.com/etewiah/property_web_builder) for instructions), and run the Rails server.
 
1. Adjust the `SERVER_URL` in `providers/config.ts`. The default is http://localhost:5000.

1. Run the app in the browser
    ```
    ionic serve
    ```
