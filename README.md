# WeatherApp
I developed this app using Kotlin and Jetpack Compose, leverages the Open Meteo API to provide real-time weather data. 
With a clean and efficient MVI (Model-View-Intent) architecture, users can easily access and beautifully display 
accurate weather information on their Android devices.

## Features

- Real-time weather data: Utilizes the Open Meteo API to fetch up-to-date weather information.
- Clean architecture: Adheres to the MVI design pattern for a modular and maintainable codebase.
- JSON parsing: Efficiently parses the weather data retrieved from the API.
- Dependency injection: Employs Hilt and Dagger to manage dependencies throughout the app.
- Asynchronous programming: Utilizes Coroutines for seamless and responsive data fetching.
- ViewModel: Implements ViewModel to handle data persistence and state management.

## Permissions

Make sure to include the following permissions in your app's manifest file:

```xml
<uses-permission android:name="android.permission.INTERNET" />
<uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" />
<uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
```

## Configuration

Add the necessary configuration to your app:

- In the `AndroidManifest.xml` file, add the required permissions and application configuration.
- In the `build.gradle` file, ensure the proper dependencies are included, such as Jetpack Compose, Hilt, Retrofit, and more.

## Getting Started

To run the app on your Android device or emulator, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/open-weather-app.git`
2. Open the project in Android Studio.
3. Build and run the app.

## Requirements

- Android Studio 4.2 or later
- Android API level 21 or higher

## Dependencies

The app relies on the following libraries and dependencies:

- Jetpack Compose
- Open Meteo API
- Hilt and Dagger
- Coroutines
- ViewModel
- Retrofit

Refer to the `build.gradle` file for the complete list of dependencies and versions.

## Contributions

Contributions to the project are welcome. If you find a bug or want to add a new feature, please create an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
