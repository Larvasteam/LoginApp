# LoginApp

A clean and simple Android login application built with Java and XML layout, demonstrating standard form validation and Android UI design best practices.

## Features

- **Form Validation**: Real-time validation for missing username/password inputs.
- **Credential Verification**: Validates login details with custom error states and Toast feedback.
- **Android Best Practices**:
  - Externalized string resources ([strings.xml](app/src/main/res/values/strings.xml)).
  - Proper layout formatting and autofill hints (`autofillHints`) in [activity_main.xml](app/src/main/res/layout/activity_main.xml).
  - Clean lifecycle management in [MainActivity.java](app/src/main/java/com/example/loginapp/MainActivity.java).

## Demo Credentials

For testing login functionality:

| Field    | Value   |
| -------- | ------- |
| **Username** | `admin` |
| **Password** | `1234`  |

## Project Structure

```
LoginApp/
├── app/
│   └── src/
│       └── main/
│           ├── java/com/example/loginapp/
│           │   └── MainActivity.java       # Core login logic and validation
│           ├── res/
│           │   ├── layout/
│           │   │   └── activity_main.xml   # Login UI layout
│           │   └── values/
│           │       └── strings.xml         # String resources
│           └── AndroidManifest.xml
├── build.gradle.kts
└── settings.gradle.kts
```

## Getting Started

### Prerequisites

- [Android Studio](https://developer.android.com/studio) (2024.1 or newer recommended)
- JDK 17
- Android SDK API 34+

### Installation & Build

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Larvasteam/LoginApp.git
   cd LoginApp
   ```

2. **Build the project:**
   Using Gradle wrapper:
   ```bash
   ./gradlew assembleDebug
   ```

3. **Run on Device/Emulator:**
   Open the project in Android Studio and press **Run** (`Shift + F10`), or deploy via ADB.

## License

This project is open-source and available under the [MIT License](LICENSE).
