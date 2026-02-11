# Capacitor Project Setup and Documentation

## Introduction
This project utilizes Capacitor for building cross-platform mobile applications. Below are detailed setup instructions and documentation for the project.

## Prerequisites
Before you begin, ensure you have the following installed:
- Node.js (version 12 or later)
- npm (Node package manager)
- Capacitor CLI (install globally using `npm install -g @capacitor/cli`)
- A code editor such as Visual Studio Code

## Setting Up the Project
1. **Clone the Repository**  
   Clone the repository to your local machine:
   ```bash
   git clone https://github.com/Edisims/winmetrics.app.git
   cd winmetrics.app
   ```

2. **Install Dependencies**  
   Navigate to the project directory and install the dependencies:
   ```bash
   npm install
   ```

3. **Initialize Capacitor**  
   Initialize Capacitor with the following command:
   ```bash
   npx cap init [appName] [appId]
   ```
   Replace `[appName]` with your app's name and `[appId]` with a unique identifier (e.g., `com.example.app`).

4. **Add Platforms**  
   You can add Android and iOS platforms by running:
   ```bash
   npx cap add android
   npx cap add ios
   ```

5. **Build the Project**  
   Build the project for the platforms you have added:
   ```bash
   npm run build
   npx cap copy
   ```

6. **Open Platform IDE**  
   Open the project in Android Studio or Xcode to run the application:
   ```bash
   npx cap open android
   npx cap open ios
   ```

## Running the Application
To run the application in the respective environments:
- For Android, use Android Studio to launch on an emulator or device.
- For iOS, use Xcode to launch on an emulator or device.

## Documentation
For detailed documentation regarding Capacitor and its APIs, please refer to the [Capacitor Documentation](https://capacitorjs.com/docs).

## Troubleshooting
If you encounter any issues, please consult the following resources:
- [Capacitor Issues on GitHub](https://github.com/capacitor-community/issues)
- [Node.js Documentation](https://nodejs.org/en/docs/)

## Conclusion
You have successfully set up the Capacitor project. Happy coding!