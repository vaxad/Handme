# Handme - Second-Hand Marketplace App

Handme is a second-hand marketplace designed to provide a secure and student-exclusive platform for buying and selling used goods. Developed using React Native and Expo, Handme offers features such as end-to-end encrypted messaging, friend connections, making it a reliable and community-focused solution for students. _This project was developed for a client based in the USA. As all rights to the project are owned by the client, the source code is proprietary and cannot be made public._

<img src="https://res.cloudinary.com/db670bhmc/image/upload/v1716962930/Screenshot_2024-05-29-10-16-15-67_e2470e577e7b8861c2b301eabc35adc8_zijpyf.jpg" style="display: none"/>
<img src="https://res.cloudinary.com/db670bhmc/image/upload/v1716962959/Screenshot_2024-05-29-10-16-26-05_e2470e577e7b8861c2b301eabc35adc8_pkg8bb.jpg" style="display: none"/>
<img src="https://res.cloudinary.com/db670bhmc/image/upload/v1716962989/Screenshot_2024-05-29-10-16-48-33_e2470e577e7b8861c2b301eabc35adc8_gv3g3s.jpg" style="display: none "/>

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
  - [User Features](#user-features)
  - [Admin Features](#admin-features)
- [Dependencies and Packages](#dependencies-and-packages)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the App](#running-the-app)
- [Screens](#screens)
  - [Onboarding](#onboarding)
  - [Home Page](#home-page)
  - [Explore Page](#explore-page)
  - [Listings Page](#listings-page)
  - [Product Page](#product-page)
  - [Posting Interface](#posting-interface)
  - [Messaging](#messaging)
  - [Profile Page](#profile-page)
- [Admin Dashboard](#admin-dashboard)
- [Security Considerations](#security-considerations)
- [Images](#images)

## Project Overview

Handme is designed to create a safe, student-only marketplace by requiring users to register with a .edu email address. This ensures a secure environment for transactions and fosters a sense of community among students.

### Why Handme?

- **Exclusivity and Credibility:** Requires a .edu email address for registration.
- **Community Building:** Allows users to add friends and build a network.
- **Safety and Reliability:** Focuses on creating a bot-free and scam-free platform.
- **Consumer Value:** Recognizes the unique consumer behavior of students.

## Features

### User Features

- **Onboarding:** Easy login and signup process with Google or email.
- **Home Page:** Personalized greeting, profile access, search bar, and curated listings.
- **Explore Page:** Type-ahead search, wishlists, and category-based product listings.
- **Listings Page:** Horizontal and vertical views, filters, and sorting options.
- **Product Page:** Detailed product information, image sliders, and seller profile.
- **Posting Interface:** Easy posting of products with tags, categories, and images.
- **Messaging:** Secure and organized chat system for buyers and sellers.
- **Profile Page:** Personal and other user profiles, editing options, and hotspot preferences.

## Dependencies and Packages

### Core Libraries

- **React Native:** Core library for building mobile applications.
- **Expo:** A framework and platform for universal React applications.

### UI and Navigation

- **React Native Elements (RNE):** Used for building UI components (`@rneui/base`, `@rneui/themed`).
- **React Native Animatable:** Used for animations and transitions.
- **React Navigation:** Used for managing navigation in the app.

### Forms and Storage

- **React Native Async Storage:** Used for storing data locally (`@react-native-async-storage/async-storage`).
- **React Native Picker:** Used for creating dropdown pickers (`@react-native-picker/picker`).

### Networking and Data Fetching

- **Axios:** Used for making HTTP requests.
- **Socket.IO Client:** Used for real-time communication (`socket.io-client`).

### Media and File Handling

- **Expo Image Picker:** Used for picking images from the device (`expo-image-picker`).
- **Expo Media Library:** Used for managing media files (`expo-media-library`).
- **Blob Util:** Used for handling binary large objects.
- **RN Fetch Blob:** Used for file handling and downloading (`rn-fetch-blob`).

### Authentication and Security

- **Expo Auth Session:** Used for handling authentication sessions (`expo-auth-session`).
- **UUID:** Used for generating unique identifiers.

### Styling

- **NativeWind:** Integration of Tailwind CSS for styling React Native components.
- **Lottie React Native:** Used for adding animations (`lottie-react-native`).

### Utilities

- **Fuse.js:** Used for fuzzy search functionality.
- **React Native Safe Area Context:** Used for handling safe area insets.

## Screens

### Onboarding

- **Login/Get Started:** Option to log in, sign up, or browse listings.
- **Sign up with Google/Email:** Collects user info and verifies email with OTP.
- **Additional Info:** Collects username, college standing, and preferences.

### Home Page

- **Greeting:** Displays user's name.
- **Profile Access:** Redirects to profile page.
- **Search Bar:** Redirects to explore page.
- **Curations:** Carousel of curated listings.
- **Wishlist Carousel:** Shows saved listings.
- **Seasonal Curations:** Listings based on seasonal popularity.
- **Friend Connections:** Prompts to connect with friends on Handme.

### Explore Page

- **Search Bar:** Type-ahead search for listings.
- **Category Panel:** Buttons for category-based listings.
- **Fact Cards:** Random facts displayed.


### Listings Page

- **Views:** Horizontal and vertical card views.
- **Filters and Sorting:** Options to filter and sort listings.
- **Product Cards:** Save and view detailed product information.

### Product Page

- **Product Details:** Title, tags, and save option.
- **Image Slider:** Up to 6 images.
- **Seller Profile:** Option to message and report the seller.

### Posting Interface

- **Camera Access:** Take pictures of listings.
- **Landlord/Student:** Different interfaces for landlords and students.
- **Tags and Categories:** Select appropriate tags and categories.
- **Price and Negotiability:** Enter the price and select if negotiable.
- **Confetti Animation:** Confirmation animation after posting.

### Messaging

- **Start Screens:** Suggested behavior screens.
- **Chat Organization:** Buying and selling chats organized by product.
- **Image Sharing:** Share images from the gallery.
- **Hotspot Highlighting:** Common hotspots highlighted in chat.

### Profile Page

- **Personal Profile:** Settings and edit options.
- **Other Profiles:** Message and connect options.
- **Hotspots:** Display preferred transaction locations.

## Security Considerations

- **Encryption:** Encrypt all passwords and secure data transmission.
- **Privacy:** Ensure user communications are private and secure.
- **Performance:** Optimize for smooth transitions and quick loading times.

## Images

![screens](https://res.cloudinary.com/db670bhmc/image/upload/v1716960261/lu419tr0fwx672k3alu8.png)
![screens](https://res.cloudinary.com/db670bhmc/image/upload/v1716960259/c4byd2pthyzbicbjhuqw.png)
![screens](https://res.cloudinary.com/db670bhmc/image/upload/v1716960259/kkvpegydkedbl4ha65jy.png)
![screens](https://res.cloudinary.com/db670bhmc/image/upload/v1716960259/tlby8we4ritdqklnoeom.png)
![screens](https://res.cloudinary.com/db670bhmc/image/upload/v1716960261/aj0mxtdc3ipt2b1pgckm.png)
![screens](https://res.cloudinary.com/db670bhmc/image/upload/v1716960259/atoatz4vguvd1ivatzmc.png)
![screens](https://res.cloudinary.com/db670bhmc/image/upload/v1716960259/c4ztkjuf2qriphu9j6ik.png)
![screens](https://res.cloudinary.com/db670bhmc/image/upload/v1716960259/p0nfpzxy6nxechbbywfa.png)
![screens](https://res.cloudinary.com/db670bhmc/image/upload/v1716960259/tr2iu1h3ljrz1xqwe92w.png)

## App Store

You can install the app on iOS devices via the [App Store](https://apps.apple.com/in/app/handme/id6480402318).
