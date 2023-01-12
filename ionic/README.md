# Ionic app with React integrated with COU WL webview

## Contents of repo

-   Ionic app built using React
-   Android app built from Ionic using Capacitor
-   Android APK of the android app

## How to run Ionic app locally

### Install Ionic CLI

To begin, let's install the latest version of the Ionic CLI.

```shell
npm install -g @ionic/cli
```

### Install dependencies

```shell
npm install
```

### Run the app

```shell
ionic serve
```

## Build an andorid app from the Ionic app

Adding native functionality is easy. Add Capacitor to your project and make sure you have all required dependencies installed for running an Andorid app.

```shell
ionic integrations enable capacitor
```

Next, build the project, then add your platform of choice:

```shell
ionic build
ionic cap add android
```

This will create an `android` folder inside the same repo. Open this folder in Android Studio to develop this app natively.
