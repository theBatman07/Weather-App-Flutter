# #Flutter Weather App

Welcome to the Flutter Weather App project! This mobile application is designed to provide users with up-to-date weather information for the next 5 days. The app fetches weather data from a third-party API and displays it in a user-friendly interface.

<img src="https://drive.google.com/uc?id=1xhtxXGLdHCroA51US6LpAOwq3lZuq68i" alt="App Preview" width="400" height="auto">

## Features

- **Weather Information:** Get detailed weather information for the next 5 days, including temperature, humidity, wind speed, and more.
- **API Integration:** The app utilizes a weather API to fetch real-time data.
- **Error Handling:** Robust error handling is implemented to manage unsuccessful API requests or invalid responses.
- **Loading Indicator:** A loading indicator is displayed while fetching data to enhance the user experience.

## Getting Started

To get started with the Flutter Weather App, follow these steps:

1. **Clone the Repository:**

```bash
git clone https://github.com/theBatman07/Weather-App-Flutter.git
```

2. **Navigate to Project Directory:**

```bash
cd Weather-App-Flutter
```

3. **Install Dependencies:**

```bash
flutter pub get
```

4. **Run the App:**

```bash
flutter run
```

## Project Structure

The project structure follows the standard Flutter directory organization:

- `lib`: Contains the Dart code for the Flutter app.
- `android`: Contains the Android-specific files.
- `ios`: Contains the iOS-specific files.
- `pubspec.yaml`: Defines the project dependencies and metadata.

## Error Handling

The app includes error handling mechanisms to gracefully handle API request failures or unexpected responses. This ensures a smooth user experience even in less-than-ideal network conditions.

## Loading Indicator

To enhance the user experience, a loading indicator is displayed while the app is fetching weather data. This provides visual feedback to the user and indicates that the app is actively retrieving information.
