# Paos-Food-Mobile Installation Guide


## Introduction

Welcome to the Paos-Food-Mobile installation guide. This guide provides a quick and easy way to set up the Paos-Food mobile application on your Android device. Paos-Food-Mobile is designed for food delivery drivers working with Paos, a local fast-food restaurant. This guide assumes you have a basic understanding of Android development tools.

## Prerequisites

Before you begin, make sure you have the following prerequisites installed:

- Android Studio
- Java Development Kit (JDK)
- Node.js
- Ionic CLI
- Capacitor

## Installation Steps

Follow these steps to install Paos-Food-Mobile on your Android device:

1. Clone the Paos-Food-Mobile repository to your local machine:

   ```bash
   git clone [repository_url]
   ```

2. Navigate to the project directory:

   ```bash
   cd Paos-Food-Mobile
   ```

3. Install project dependencies:

   ```bash
   npm install
   ```

4. Initialize Capacitor with your app's name and ID:

   ```bash
   npx cap init [app_name] [app_id]
   ```

5. Add the Android platform to your project:

   ```bash
   npx cap add android
   ```

6. Build the app for production:

   ```bash
   ionic build --prod
   ```

7. Open Android Studio and select "Open an existing Android Studio project." Navigate to your project directory and select the "android" folder.

8. Connect your Android device to your computer using a USB cable and ensure USB debugging is enabled on your device.

9. Build and run the app on your Android device by clicking the "Run" button in Android Studio.

10. Follow the on-screen instructions to install the app on your device.

11. Once installed, you can launch Paos-Food-Mobile from your device's app drawer.

## Running Tests

To run tests for Paos-Food-Mobile, follow these steps:

1. Navigate to the project directory:

   ```bash
   cd Paos-Food-Mobile
   ```

2. Run the tests using the Ionic CLI:

   ```bash
   ionic test
   ```

3. The Ionic testing framework will launch, and you can select the specific tests you want to run.

![Screenshot 8](/img/console-karma.jpg)

## Usage

Paos-Food-Mobile is designed for delivery drivers working with Paos. Log in with your credentials to start managing and delivering orders.

## Troubleshooting

If you encounter any issues during the installation process, refer to the troubleshooting section in the full installation guide or contact our support team at [support_email].

For more detailed information on the installation process, please refer to the comprehensive installation guide.

Happy delivering with Paos-Food-Mobile!

## Screenshots

![Screenshot 1](/img/img1.JPG)
![Screenshot 2](img/img2.JPG)
![Screenshot 3](img/img3.JPG)
![Screenshot 4](img/img4.JPG)
![Screenshot 5](img/img5.JPG)
![Screenshot 6](img/img6.JPG)
![Screenshot 7](img/img7.JPG)
