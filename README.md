This is a new [**React Native**](https://reactnative.dev) project, bootstrapped using [`@react-native-community/cli`](https://github.com/react-native-community/cli).

// comandos git & react native
// crear proyecto en react native
npx react-native init <nombre>

// instalar dependencias de react
npm install @react-native-community/geolocation@3.1.0
npm install @react-navigation/bottom-tabs@6.5.14
npm install @react-navigation/native@6.1.12
npm install @react-navigation/native-stack@6.9.20
npm install @react-navigation/stack@6.3.23
npm install react@18.2.0
npm install react-native@0.73.4
npm install react-native-appearance@0.3.4
npm install react-native-geolocation-service@5.3.1
npm install react-native-maps@1.10.3
npm install react-native-safe-area-context@4.9.0
npm install react-native-screens@3.29.0
npm install react-navigation-stack@2.10.4


// ir al proyecto y ejecutarlo en emulador android o dispositivo
cd "C:\ruta\al\proyecto"
npx react-native run-android || npm run android

// iniciar repositorio en git es
git init // que no es necesario para iniciar el proyecto ya que al crear el proyecto en react se inicia un repositorio

// iniciar sesion en git desde la terminal
git config --global user.email "<correo en github>@ejemplo.com"
git config --global user.name "<usuario en github>"

// añadir cambios en todos los archivos a git para despues hacer el commit
git add .

// hacer un commit
git commit -m "<mensaje>"

// dirigirte a la rama (branch) main
git branch -M main

// añadir al repositorio el commit hecho anteriormente
git push -u origin main

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
