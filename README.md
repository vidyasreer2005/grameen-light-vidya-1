# Grameen-Light Android Project Setup

This project has been generated as a **Complete Native Android Studio Project** using Kotlin and Jetpack Compose.

## 🚀 How to open in Android Studio

1. **Download the project** as a ZIP from AI Studio (Settings > Download ZIP).
2. **Extract the ZIP** to a folder on your computer.
3. Open **Android Studio**.
4. Select **File > Open** (or "Open an existing project").
5. Navigate to the extracted folder and select the **root directory** (the one containing `settings.gradle.kts`).
6. Wait for Android Studio to finish the **Gradle Sync**.

## 🛠️ Mandatory Configuration

Because this is a native app, you MUST provide your own Firebase and Google Maps configuration:

### 1. Firebase Setup
- Go to the [Firebase Console](https://console.firebase.google.com/).
- Create a new project (or use an existing one).
- Add an **Android App** with package name `com.village.streetlight`.
- Download the `google-services.json` file.
- Place it in the `app/` directory of this project.

### 2. Google Maps API Key
- Go to the [Google Cloud Console](https://console.cloud.google.com/).
- Enable the **Maps SDK for Android**.
- Create an API Key.
- Open `app/src/main/AndroidManifest.xml`.
- Replace `${MAPS_API_KEY}` with your real API Key.

## 📱 Running the App
1. Connect a physical Android device or start an **Android Emulator**.
2. Click the **Run** button (green play icon) in Android Studio.

## 📁 Project Structure
- `app/src/main/kotlin/com/village/streetlight/MainActivity.kt`: Entry point.
- `app/src/main/kotlin/com/village/streetlight/ui/screens/`: All UI screens (Compose).
- `app/src/main/kotlin/com/village/streetlight/viewmodels/`: Business logic and data sync.
- `app/src/main/kotlin/com/village/streetlight/data/models/`: Data definitions.
