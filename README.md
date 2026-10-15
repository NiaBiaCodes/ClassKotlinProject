# BooksApp — Android Book Library

An Android book catalog application developed in **Kotlin** using **Jetpack Compose**. The app lets users browse sample books and view price statistics through a simple multi-screen interface.

## Features

- **Book list:** Displays a scrollable collection of books using Jetpack Compose `LazyColumn`.
- **Statistics:** Calculates the average price across books and the average price within a selected genre.
- **App information:** Dedicated screen with information about the application.
- **Screen navigation:** Moves between the book list, statistics, and app information screens using Navigation Compose.
- **Shared data:** A `BookRepository` holds the sample book collection and provides calculations used by screen-specific ViewModels.

## Technologies

- **Language:** Kotlin
- **UI:** Jetpack Compose, Material 3
- **Navigation:** AndroidX Navigation Compose
- **Architecture:** `Application` class, repository pattern, ViewModels
- **Build tools:** Gradle, Android Studio

## Project structure

```text
app/src/main/java/com/example/booksapp/
├── MainActivity.kt
├── BookApplication.kt
├── Book.kt
├── BookRepository.kt
├── BookListScreen.kt
├── BookListViewModel.kt
├── StatsScreen.kt
├── StatsViewModel.kt
├── AppInfoScreen.kt
└── AppInfoViewModel.kt
```

## Run locally

1. Clone this repository or download the source code.
2. Open the project folder in **Android Studio**.
3. Let Gradle sync and install any required Android SDK components.
4. Start an Android emulator or connect a compatible Android device.
5. Run the **app** configuration.

## About

Built as an Android programming course assignment to practice declarative UI development, lists, navigation, separating data logic from UI, and Kotlin programming.

**Note:** This app uses local sample book data; it does not require an external book API or database.
