# Shikhar App

An Expo-based React Native application with Firebase integration, React Navigation, and various utility libraries.

## Prerequisites

- Node.js (v20 or higher)
- npm (v10 or higher)

## Installed Dependencies

### Core Libraries
- **expo** (~54.0.25) - The Expo framework
- **react** (19.1.0) - React library
- **react-native** (0.81.5) - React Native framework

### Firebase
- **firebase** (^12.6.0) - Firebase SDK for authentication, database, and other services

### Navigation
- **@react-navigation/native** (^7.1.21) - React Navigation core
- **@react-navigation/native-stack** (^7.7.0) - Stack navigator
- **@react-navigation/bottom-tabs** (^7.8.6) - Tab navigator
- **react-native-gesture-handler** (^2.29.1) - Gesture handling
- **react-native-reanimated** (^4.1.5) - Animations library
- **react-navigation** (^5.0.0) - Legacy navigation package

### UI & Forms
- **react-native-paper** (^5.14.5) - Material Design components
- **react-hook-form** (^7.66.1) - Form validation and handling
- **yup** (^1.7.1) - Schema validation

### Expo Utilities
- **expo-secure-store** (^15.0.7) - Secure storage for sensitive data
- **expo-notifications** (^0.32.13) - Push notifications
- **expo-image-manipulator** (^14.0.7) - Image manipulation
- **expo-file-system** (^19.0.19) - File system access
- **@react-native-async-storage/async-storage** (^1.24.0) - Async storage

### Monitoring (Optional)
- **@sentry/react-native** (^7.6.0) - Error tracking and monitoring

## Getting Started

### Install Dependencies

Dependencies are already installed. If you need to reinstall:

```bash
npm install
```

### Run the App

Start the development server:

```bash
npm start
```

Run on specific platforms:

```bash
# Android
npm run android

# iOS (requires macOS)
npm run ios

# Web
npm run web
```

## Project Structure

```
shikhar-app/
├── assets/          # Images, fonts, and other static assets
├── App.js           # Main application component
├── app.json         # Expo configuration
├── index.js         # Entry point
├── package.json     # Dependencies and scripts
└── README.md        # This file
```

## Development

- The app uses the blank Expo template
- The new React Native architecture is enabled
- Edit `App.js` to start building your application
- Use React Navigation for navigation between screens
- Use React Native Paper for UI components
- Integrate Firebase for backend services

## Learn More

- [Expo Documentation](https://docs.expo.dev/)
- [React Navigation](https://reactnavigation.org/)
- [React Native Paper](https://callstack.github.io/react-native-paper/)
- [Firebase Documentation](https://firebase.google.com/docs)
- [React Hook Form](https://react-hook-form.com/)
