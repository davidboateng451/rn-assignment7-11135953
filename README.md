# rn-assignment7-11135953

## Overview

This React Native project demonstrates a basic e-commerce application with the following features:
- A list of available products fetched from an external API.
- Detailed view of each product.
- Adding and removing products from a shopping cart.
- Persisting cart items using local storage.

## Features

### HomeScreen
- Displays a list of available products.
- Each product item includes an "Add to Cart" button.

### ProductDetailScreen
- Shows detailed information about a selected product.
- Includes an "Add to Cart" button.

### CartScreen
- Displays the list of products added to the cart.
- Each cart item includes a "Remove from Cart" button.

### Navigation
- A drawer component/navigation menu accessible through a swipe gesture or button, allowing navigation between screens.

## Implementation Details

### Fetching Data
- Data is fetched from an external API using the `fetch` method or `axios` library.
- Asynchronous operations are managed with `async/await` syntax to handle promises.

### Local Storage
- Selected items are stored locally on the device using AsyncStorage.
- This ensures that the cart persists even if the app is closed and reopened.

### Navigation
- React Navigation is used to handle navigation between screens.
- A drawer navigator provides easy access to different parts of the application.

## Screenshots
![HomeScreen](https://github.com/user-attachments/assets/fb94103c-c090-47de-84a9-277f0289b6b2)

![ProductDetailScreen](https://github.com/user-attachments/assets/898e576e-af07-4fc1-a2e6-67bb89356902)

![CartScreen](https://github.com/user-attachments/assets/0f9f0926-1002-4180-a9cc-9cb673ba35f0)



## Design Choices
- **UI Layout**: The design is kept simple and intuitive, following the provided UI mockup to ensure usability.
- **Local Storage**: AsyncStorage is used for its simplicity and integration with React Native.
- **Error Handling**: Basic error handling is implemented for API calls and local storage operations to enhance user experience.
