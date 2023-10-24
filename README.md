Building Your First React Native Application with Expo
#
tutorial
#
react
#
reactnative
#
javascript
For all the talk of web apps being the future, mobile applications still are one the easiest ways to reach your users. But building and maintaining apps for iOS, Android, and the web can literally triple your workload.

React Native solves this by helping developers build cross-platform mobile applications, reducing the time and effort involved. As such, React Native is an extremely popular tool used by tons of companies to simplify their workflow. Let's see how React Native achieves this.

What is React Native?
React Native is based on the popular JavaScript framework React. Hence, people familiar with the basics of React (states/props) can easily transition to React Native.
Since it is cross-platform, React Native helps avoid separate code bases for different platforms. It provides components and APIs which act as building blocks for the mobile application.
Some of the core components of React Native are:

View
Text
Image
ScrollView
StyleSheet
Touchables
Developers working with React Native use these components on a regular basis.

It is recommended that developers who are new to mobile application development, use the Expo CLI to develop apps faster, easier, and more efficiently. Expo CLI is a framework built on top of React Native making it much easier to start developing mobile applications.

Let's see React Native in action along with Expo CLI. We’ll be building a basic Todo application for mobile. We will use an android emulator to test our application. To start with, let’s install all the required software and packages.

Setting up our development environment
First, in the terminal run the following command to install the Expo CLI globally
npm install -g expo-cli

We’ll be using the Expo mobile app(Available on both Android and iOS) to simulate our app on mobile.

Creating a new Expo project
In a terminal, run the command
expo init <project name>

This will create a base project (just like create-react-app) that we can use to create our application. For now, we can just run the application to test our setup by following the instructions below.

Run cd todoapp to change the directory.

Run the application by executing

expo start

Once the app spins up, you should be able to access the expo menu through a local host.

Image description

From there, you can find a number of options to test your app, including:

Running it in a web browser
Running in an iOS or Android Simulator
Scanning the QR code from a device with the expo app installed
While there may be some delays depending on the way you do it, Expo is generally pretty seamless in allowing you to test your app.

Creating our ToDo App
We will edit the App.js file and add additional components to build our app. The source code for App.js can be found below.


view rawApp.js hosted with ❤ by GitHub
The App.js contains:

Imports - To import the required libraries, native and custom components
Function - Our App function will contain the entire code.
Basic components - Basic React Native components such as View, ScrollView, and TouchableOpacity
Custom component - Just like React we can create our own custom components and use them inside the App.js by importing. We are using a single custom component called Task written inside Task.js. The source is located below.

States and Props - Just like React we will utilise useState and pass props to our Task component.
