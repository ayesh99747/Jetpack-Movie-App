# Jetpack-Movie-App

This Android application displays a list of movies and allows users to view detailed information about each movie, including its IMDB rating, producers, and more.  This app was developed following a course from O'Reilly ([link](https://learning.oreilly.com/videos/android-jetpack-compose/9781803237718/)).

## Key Features

* Displays a list of movies with titles and posters.
* Allows users to navigate to a detail view for selected movies.
* Detail view shows movie information including plot, director, actors, and rating.
* Displays multiple images for each movie.
* Uses Jetpack Compose for UI.
* Uses Coil for image loading.
* Uses Android Navigation component.


## Technologies Used

* Kotlin
* Jetpack Compose
* AndroidX
* Coil
* Android Navigation Component


## Prerequisites

* Android Studio (with Kotlin and Compose plugins installed)
* Android SDK API level 31 or higher
* JDK 8 or higher
*  Internet connection (for image loading)


## Installation

1. **Clone the repository:**

   ```bash
   git clone <repository_url>
   ```

2. **Open the project in Android Studio:**

   Open Android Studio and select "Open an existing Android Studio project". Navigate to the cloned repository and select the `Jetpack-Movie-App` folder.


3. **Sync the project:**

   Android Studio will automatically sync the project with Gradle.  If it doesn't, manually click the "Sync Project with Gradle Files" button (usually an elephant icon in the toolbar).


4. **Install dependencies:**

   The project uses Gradle to manage dependencies.  The necessary dependencies are declared in the `app/build.gradle.kts` file.  Android Studio should automatically download and resolve them during the sync process.


## Usage Examples

1. **Run the app:** After successful installation and sync, click the "Run" button in Android Studio to build and install the app on an emulator or connected Android device.

2. **Navigate through the app:** The app starts on the home screen displaying a list of movies. Click on a movie poster to navigate to the details screen.  From the details screen, you can use the back button to return to the home screen.


## Project Structure

The project follows a standard Android project structure:

* **app/:** Contains the main application code.
    * **src/:** Source code.
        * **main/:** Main source code, resources, and manifest.
        * **androidTest/:** Android instrumentation tests.
        * **test/:** Unit tests.
    * **build.gradle.kts:** Module-level Gradle build configuration.
    * **proguard-rules.pro:** ProGuard rules for release builds.
* **gradle/:** Gradle wrapper files.
* **gradlew, gradlew.bat:** Gradle wrapper scripts.
* **settings.gradle.kts:** Project-level Gradle build configuration.
* **gradle.properties:** Project-wide Gradle properties.
* **screenshots/:** Screenshots of the application.
* **README.md:** This file.


## Configuration

The `gradle.properties` file contains project-wide Gradle settings.  The most important setting is `org.gradle.jvmargs`, which specifies JVM arguments for the Gradle daemon. You can adjust the memory allocation (`-Xmx2048m`) as needed.

The `app/build.gradle.kts` file contains Android-specific build configurations, including dependencies, build types, and signing configurations (which are currently set to a debug configuration).


## Scripts

* **gradlew (gradlew.bat for Windows):** These are wrapper scripts for Gradle.  Use them to run Gradle tasks from the command line (e.g., `./gradlew build`, `gradlew.bat build`).  These tasks handle dependency resolution, compilation, and building of the APK file.

## License

### Disclaimer

This repository contains code created while following the course  
**"Android Jetpack Compose - Build Android Native UIs Fast"** by **Paulo Dichone**,  
available at: [O’Reilly Learning Platform](https://learning.oreilly.com/course/android-jetpack-compose/9781803237718/)

The content is intended for educational purposes only and closely follows the structure and lessons from the original course.

All rights to the course content and materials belong to **Paulo Dichone**.  
This repository is not affiliated with or endorsed by Paulo Dichone or O’Reilly.

If you are the content owner and would like this repository modified or removed, please contact me directly.

## Error Messages

Refer to the Android Studio error messages and logs for debugging help. If you encounter issues, ensure your environment is correctly setup, including Java, Android SDK, and Android Studio. Check the Gradle sync to confirm all dependencies are correctly resolved.

## Screenshots

<p align="center">
<img src="screenshots/Screenshot 1.png" width="300" height="550">
<br>
<em>Figure 1: Home screen of the app.</em>
</p>

<p align="center">
<img src="screenshots/Screenshot 2.png" width="300" height="550">
<br>
<em>Figure 2: Home screen of the app with tiles expanded.</em>
</p>

<p align="center">
<img src="screenshots/Screenshot 3.png" width="300" height="550">
<br>
<em>Figure 3: Screen showing movie details and images.</em>
</p>

<p align="center">
<img src="screenshots/Screenshot 4.png" width="300" height="550">
<br>
<em>Figure 4: Screen showing movie details and images - Expanded.</em>
</p>

<p align="center">
<img src="screenshots/Screenshot 5.png" width="300" height="550">
<br>
<em>Figure 5: Screen showing avatar movie details and images - Expanded.</em>
</p>

<p align="center">
<img src="screenshots/Screenshot 6.png" width="300" height="550">
<br>
<em>Figure 6: Screen showing the wolf of wall street movie details and images - Expanded.</em>
</p>

