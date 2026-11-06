# Counter History App <a name="about-project"></a>

A simple Android counter application built with Kotlin and Jetpack Compose. The app demonstrates modern Android development practices including MVVM architecture, ViewModel state management, reactive UI updates, and dynamic list rendering. Users can increment, decrement, reset the counter, and view a history of all previously reached values.

## 🛠️ Built With

- **Language:** Kotlin
- **UI Toolkit:** Jetpack Compose
- **Architecture:** MVVM (Model-View-ViewModel)
- **State Management:** ViewModel, Compose State (`mutableStateOf`, `mutableStateListOf`)
- **Lifecycle Management:** AndroidX ViewModel
- **Design System:** Material Design 3
- **Development Environment:** Android Studio
- **SDK:** Android SDK

---

### Key Features <a name="key-features"></a>

- ✅ Increment counter value
- ✅ Decrement counter value
- ✅ Reset counter to zero
- ✅ Track every visited counter value
- ✅ Display history in real time
- ✅ Automatic UI updates through Compose recomposition
- ✅ ViewModel-based state management
- ✅ Separation of UI and business logic
- ✅ State persistence across configuration changes
- ✅ Material Design 3 user interface
- ✅ Beginner-friendly MVVM implementation

---

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Prerequisites

Before running this project, make sure you have:

- Android Studio installed
- Android SDK configured
- Kotlin support enabled
- Android Emulator or physical Android device
- JDK 11 or later

### Setup

Clone this repository:

```sh
git clone https://github.com/AbigiyaTY/CounterHistoryApp.git
```

Navigate to the project directory:

```sh
cd CounterHistoryApp
```

### Install

Open the project in Android Studio:

```sh
File → Open → Select Project Folder
```

Allow Android Studio to synchronize and download all required Gradle dependencies.

### Dependencies

The project uses Android Lifecycle ViewModel for Compose:

```kotlin
implementation("androidx.lifecycle:lifecycle-viewmodel-compose:2.8.7")
```

Sync the project after adding dependencies.

### Usage

This project demonstrates:

- Jetpack Compose fundamentals
- MVVM architecture
- Android ViewModel
- Mutable state management
- State-driven UI rendering
- Compose recomposition
- Material Design 3 components
- Dynamic list rendering
- Configuration change handling


## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to fork this repository and submit a pull request.
