# react-native-onboard

[![npm version](https://img.shields.io/npm/v/react-native-onboard)](https://www.npmjs.com/package/react-native-onboard)
[![npm version](https://github.com/FrigadeHQ/react-native-onboard/actions/workflows/tests.yml/badge.svg)](https://github.com/FrigadeHQ/react-native-onboard/actions/workflows/tests.yml)
[![npm license](https://img.shields.io/npm/l/react-native-onboard)](https://www.npmjs.com/package/react-native-onboard)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)

Delightful and fully customizable onboarding components for React Native.

<img src="static/react-native-onboard-demo-simple.gif" alt="drawing" width="150"/>

See [Live Demo](https://snack.expo.dev/@christian-frigade/react-native-onboard-simple-demo) on Expo Snack.

## Features

- 📱 Easily add welcome screens, product tours, and feature announcements to your app
- 🎨 Fully customizable components and config
- 🔧 Dynamically trigger the right onboarding for the right user
- 🚀 Works with Expo
- ✨ Beautiful default UI

## Installation

Install the package with either npm or yarn:

```bash
npm install react-native-onboard
```
or
```bash
yarn add react-native-onboard
```

## Quick start
Place the `OnboardFlow` component anywhere in your app. It will automatically take up the entire screen. To change the 
default behavior, see the [docs on supported props](https://docs.frigade.com/docs/components/highlevel).

```jsx
import { OnboardFlow } from 'react-native-onboard';

const App = () => {
  
  return (
    <OnboardFlow
      pages={[
        {
          title: 'Welcome to my app',
          subtitle: 'This is page 1',
          imageUri: 'https://frigade.com/img/example1.png',
        },
        {
          title: 'Page 2 header',
          subtitle: 'This is page 2',
          imageUri: 'https://frigade.com/img/example2.png',
        }
      ]}
    />
  );
};
```

## Docs
The official docs are available at [docs.frigade.com](https://docs.frigade.com/).

## Customization
`react-native-onboard` is designed to be headless and customizable. You can use the default UI or create your own by
implementing a series of provided interfaces. See the [Official Docs](https://docs.frigade.com/docs/intro) to learn more.

<img src="static/react-native-onboard-demo.gif" alt="drawing" width="150"/>

## Get in touch
Questions? Comments? Suggestions? Join the [Frigade Discord](https://discord.gg/3fujYupY).