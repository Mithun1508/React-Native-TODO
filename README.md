## Building Your First React Native Application 

Some of the core components of React Native are:

1.View

2.Text

3.Image

4.ScrollView

5.StyleSheet

6.Touchables

## Setting up our development environment
First, in the terminal run the following command to install the Expo CLI globally
npm install -g expo-cli

We’ll be using the Expo mobile app(Available on both Android and iOS) to simulate our app on mobile.

## Creating a new Expo project
In a terminal, run the command
expo init <project name>

This will create a base project (just like create-react-app) that we can use to create our application. For now, we can just run the application to test our setup by following the instructions below.

Run cd todoapp to change the directory.

Run the application by executing

expo start

Once the app spins up, you should be able to access the expo menu through a local host.

From there, you can find a number of options to test your app, including:
Running it in a web browser

Running in an iOS or Android Simulator

Scanning the QR code from a device with the expo app installed

While there may be some delays depending on the way you do it, Expo is generally pretty seamless in allowing you to test your app.

## Creating our ToDo App
We will edit the App.js file and add additional components to build our app. The source code for App.js can be found below.

## The App.js contains:

1 Imports - To import the required libraries, native and custom components
2 Function - Our App function will contain the entire code.
3 Basic components - Basic React Native components such as View, ScrollView, and TouchableOpacity
4 Custom component - Just like React we can create our own custom components and use them inside the App.js by importing. We are using a single custom component called Task written inside Task.js. The source is located below.

States and Props - Just like React we will utilise useState and pass props to our Task component.




