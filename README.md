# React Native Fashion App

This is a React Native application for a fashion store called "Open Fashion." The app allows users to view a list of available fashion items, add them to their cart, and view the cart to proceed with the checkout.

## Features

- View a list of fashion items.
- Add items to the cart.
- Remove items from the cart.
- View the cart with a summary of items and total price.
- Navigate between Home and Cart screens.
- Persistent cart storage using AsyncStorage.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/rn-assignment6-11004314.git
   cd rn-assignment6-11004314
2. Install the dependencies:
   ```bash
   npm install
3. Start the Metro Bundler:
   ```bash
   npm start
4. Run the app on an emulator or device:

For Android:
```bash
npm run android
```
For iOS:
```bash
npm run ios
```

## Screens

### Home Screen

- Displays a list of fashion items.
- Each item shows an image, name, description, and price.
- Users can add items to the cart.
- Includes navigation to the Cart screen.

### Cart Screen

- Displays a list of items added to the cart.
- Each item shows an image, name, quantity, and total price.
- Users can remove items from the cart.
- Shows the estimated total price for all items in the cart.
- Includes navigation back to the Home screen.

### File Structure
- App.js: Main entry point of the application.
- screens/HomeScreen.js: Home screen component.
- screens/CartScreen.js: Cart screen component.
- assets/: Contains all the image assets used in the app.
- styles/: Contains common styles used across components (if any).

## Design Choices

### UI Design

The UI is designed to provide a clean and modern look, with easy navigation and user-friendly interactions. The main components are styled to ensure consistency across different screens and devices.

### Data Storage

Cart data is stored locally on the device using AsyncStorage. This ensures that the cart persists even if the app is closed and reopened, providing a seamless user experience.

## Screenshots

### Home Screen

![202hw6 home](https://github.com/Brain500/rn-assignment6-11004314/assets/151630060/566e4f88-95ac-4af9-ab6b-a335c96aadaf)


### Cart Screen

![202h6 cartscreen](https://github.com/Brain500/rn-assignment6-11004314/assets/151630060/871ef028-5faa-4d17-9096-0e50fa21b51a)













