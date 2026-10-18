# StudyFlow - Assignment 02

StudyFlow is a React Native app built with Expo. This project extends the Assignment 01 app with a Progress screen, a fourth bottom tab, and StudyFlow-branded splash artwork.

## Run the app

```bash
npm ci
npm start
```

Use the Expo CLI prompts to open the app on a device or simulator. To run the web version:

```bash
npm run web
```

## Assignment 02 additions

- Added a themed Progress screen with weekly focus, daily study activity, subject breakdowns, and a study streak.
- Added the Progress tab to both native and web bottom-tab navigation.
- Kept the custom StudyFlow app icon and configured splash screen; updated the in-app launch animation to use the StudyFlow splash artwork.
- Built the new screen using the shared `ThemedView` and `ThemedText` components.

## Android APK

The `preview` EAS Build profile is configured to produce an installable APK:

```bash
npx eas-cli@latest build --platform android --profile preview
```

Sign in to Expo when prompted. The APK download link is provided by EAS after the cloud build finishes.
