This is a new [**React Native**](https://reactnative.dev) project, bootstrapped using [`@react-native-community/cli`](https://github.com/react-native-community/cli).

# Getting Started

>**Note**: Make sure you have completed the [React Native - Environment Setup](https://reactnative.dev/docs/environment-setup) instructions till "Creating a new application" step, before proceeding.

## Step 1: Start the Metro Server

First, you will need to start **Metro**, the JavaScript _bundler_ that ships _with_ React Native.

To start Metro, run the following command from the _root_ of your React Native project:

```bash
# using npm
npm start

# OR using Yarn
yarn start
```

## Step 2: Start your Application

Let Metro Bundler run in its _own_ terminal. Open a _new_ terminal from the _root_ of your React Native project. Run the following command to start your _Android_ or _iOS_ app:

### For Android

```bash
# using npm
npm run android

# OR using Yarn
yarn android
```

### For iOS

```bash
# using npm
npm run ios

# OR using Yarn
yarn ios
```

If everything is set up _correctly_, you should see your new app running in your _Android Emulator_ or _iOS Simulator_ shortly provided you have set up your emulator/simulator correctly.

This is one way to run your app — you can also run it directly from within Android Studio and Xcode respectively.

## Step 3: Modifying your App

Now that you have successfully run the app, let's modify it.

1. Open `App.tsx` in your text editor of choice and edit some lines.
2. For **Android**: Press the <kbd>R</kbd> key twice or select **"Reload"** from the **Developer Menu** (<kbd>Ctrl</kbd> + <kbd>M</kbd> (on Window and Linux) or <kbd>Cmd ⌘</kbd> + <kbd>M</kbd> (on macOS)) to see your changes!

   For **iOS**: Hit <kbd>Cmd ⌘</kbd> + <kbd>R</kbd> in your iOS Simulator to reload the app and see your changes!

## Congratulations! :tada:

You've successfully run and modified your React Native App. :partying_face:

### Now what?

- If you want to add this new React Native code to an existing application, check out the [Integration guide](https://reactnative.dev/docs/integration-with-existing-apps).
- If you're curious to learn more about React Native, check out the [Introduction to React Native](https://reactnative.dev/docs/getting-started).

# Troubleshooting

If you can't get this to work, see the [Troubleshooting](https://reactnative.dev/docs/troubleshooting) page.

# Learn More

To learn more about React Native, take a look at the following resources:

- [React Native Website](https://reactnative.dev) - learn more about React Native.
- [Getting Started](https://reactnative.dev/docs/environment-setup) - an **overview** of React Native and how setup your environment.
- [Learn the Basics](https://reactnative.dev/docs/getting-started) - a **guided tour** of the React Native **basics**.
- [Blog](https://reactnative.dev/blog) - read the latest official React Native **Blog** posts.
- [`@facebook/react-native`](https://github.com/facebook/react-native) - the Open Source; GitHub **repository** for React Native.


# React Native Note App - RESTful API

## Introduction
[![React Native](https://img.shields.io/badge/React%20Native-0.60-blue.svg?style=rounded-square)](https://facebook.github.io/react-native/)
[![Node.js](https://img.shields.io/badge/Node.js-v.10.16-green.svg?style=rounded-square)](https://nodejs.org/)

Here is my new repository which builded with React Native Framework for making the User Interface in JavaScript syntax, see my previous repository about [RESTful API Note App with Express](https://github.com/aahmadhadi/RESTful-API-Note-App-with-Express) for the backend side and making API.

### What is React Native ?
React Native is an open-source mobile application framework created by Facebook. It is used to develop applications for Android, iOS and UWP by enabling developers to use React along with native platform capabilities. [[1]](https://en.wikipedia.org/wiki/React_Native)

### Why using React Native ?
6 main reason why me using React Native for make a mobile app :

1. It's got iOS and Android covered
2. Reusable components allow hybrid apps to render natively
3. Apply React Native UI component to an existing app's code-without any rewriting at all
4. It’s one of the top mobile JavaScript frameworks among developers—and growing
5. React Native is all about the UI
6. Native app development is much more efficient

### How React Native works ?
Short explanation about **How React Native Works**.

React Native invokes Objective-C APIs to render to iOS components, or Java APIs to render to Android components. This sets React Native apart from other cross-platform app development options, which often end up rendering web-based views.

## Requirements
1. npm (node package manager)
2. react-native-cli (from npm)

## How to run the app ?
1. Clone or download first this repository with 
```
git clone https://github.com/aahmadhadi/RESTful-API-Note-App-with-Express.git
```
2. Open the project in your favorite text editor
3. Open your terminal or cmd and type
```
npm install
```
4. Open *\src\Public\redux\actions\notes.js*  and edit the **IP url** according to your ip backend
5. And the last just type in your terminal or cmd
```
react-native run-android
```
be sure if you connected with a device on debugging mode or use the emulator on debugging mode too.

## Demonstration

<p>Home Screen</p>
    <img src='https://github.com/arnab-kundu/NoteApp/blob/master/src/Assets/DummyData/scrolling.gif?raw=true' width=150 />
<p>Sort Ascending / Descending</p>
    <img src='https://github.com/aarnab-kundu/NoteApp/blob/master/src/Assets/DummyData/sort.gif?raw=true' width=150 />
<p>Search</p>
    <img src='https://github.com/arnab-kundu/NoteApp/blob/master/src/Assets/DummyData/search.gif?raw=true' width=150 />
<p>Sort by Category</p>
    <img src='https://github.com/arnab-kundu/NoteApp/blob/master/src/Assets/DummyData/sortbycategory.gif?raw=true' width=150 />
<p>Insert Delete Note</p>
    <img src='https://github.com/arnab-kundu/NoteApp/blob/master/src/Assets/DummyData/insertdeletenote.gif?raw=true' width=150 />
<p>Update Note</p>
    <img src='https://github.com/arnab-kundu/NoteApp/blob/master/src/Assets/DummyData/updatenote.gif?raw=true' width=150 />
<p>Insert Delete Category</p>
    <img src='https://github.com/arnab-kundu/NoteApp/blob/master/src/Assets/DummyData/insertdeletecategory.gif?raw=true' width=150 />

