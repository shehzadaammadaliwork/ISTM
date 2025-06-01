# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Learn more

This app streamlines the workflow for field agents and tour operators. It supports role-based logins, QR code scanning for instant data access, and digital slip generation for easy record-keeping.

✨ Features
🔐 Secure Login – Authenticates via backend API, with real-time validation and alerts.

🧠 Role-Based Access – Auto-redirects users based on roles like tour_operator, destination_agent.

📦 Form Validation – Ensures only valid data gets submitted.

⚙️ AsyncStorage – Stores tokens and user data securely.

📸 QR Code Scanner – Uses the device camera to read and process QR codes with JSON autofill support.

🧾 Generate Payment Slips – Auto-generate and save/share payment receipt views.

🖼️ Save as Image – Capture any screen component as an image using react-native-view-shot.

🌐 Cross-Platform – Runs on Android, iOS, and web using the same codebase.

🛠️ Built with Expo Router – Easy navigation with file-based routing.

🧪 Technologies Used
Tech/Library	Purpose
React Native (Expo)	Cross-platform mobile app development
Expo Router	File-based navigation
EAS (Expo Application Services)	Native builds and OTA updates
AsyncStorage	Local persistent storage
expo-camera / barcode-scanner	QR code scanning
react-native-view-shot	Capture screen components as images
ToastAndroid / Alert	Platform-specific feedback

📲 QR Code Scanning
QR codes are scanned using the device camera to:

Autofill payment or departure data in forms

Identify and route based on scanned content

Provide error handling for invalid formats

Works seamlessly with JSON-formatted QR payloads.

📦 Deployment with EAS
This project is EAS-ready for native builds and OTA updates.

🛠️ Project Structure
app/
├── index.tsx
├── login.tsx         # Login screen with validation
├── departures/       # Screen for tour_operator role
├── NavigationListing # Screen for destination_agent role
├── QrCardScreen.tsx  # Render card with QR
├── SlipScreen.tsx    # Render payment receipt
└── components/       # Shared UI components

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
