![BrightCoders Logo](img/logo.png)

# Introducción a React Native
***

> [Antes de iniciar leer las instrucciones](./instructions.md)

## Table of Contents

* Description 
* Installation 
* Usage 
* Testing 
* Structure of Project
* Contributors
* Badges

## Description
React Native is an open-source UI software framework created by Meta Platforms, Inc. It is used to develop applications for Android:Android TV, iOS:macOS, tvOS,Web, Windows and UWP by enabling developers to use the React framework along with native platform capabilities.

## Installation

To get the project up and running, follow these steps:

Clone the repository: bash Copy code git clone https://github.com/BrightCoders-Institute/s1a2-introducci-n-a-react-native-Jherrera11.git Navigate to the project directory: bash Copy code cd your-repo Install dependencies: bash Copy code npm install Usage

## Usage

To use the project, follow these steps:
**Note**: Make sure you have completed the [React Native - Environment Setup](https://reactnative.dev/docs/environment-setup) instructions till "Creating a new application" step, before proceeding.

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


## Testing

This project does not have testing in this moment.

## Structure of Project

```
└── 📁s1a2-introducci-n-a-react-native-Jherrera11
    └── .github
    └── 📁AwesomeProject
        └── 📁ios
        └── 📁__tests__
        └── 📁.bundle
        └── 📁Android
        └── 📁ios
        └── 📁node_modules       
        └── app.json
        └── App.tsx
        └── babel.config.js
        └── Gemfile
        └── index.js
        └── jest.config.js
        └── metro.config.js
        └── package-lock.json
        └── package.json
        └── react-native.config.js
        └── README.md
        └── tsconfig.json
    └── 📁img
        └── logo.png
    └──   .gitignore
    └── instructions.md
    └── README.md
```

## Contributors

This project was developed by 
* Co-authored-by: Jherrera11 <jherrera11@ucol.mx>


## Badges
![ReactNative](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![AndroidStudio](https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)