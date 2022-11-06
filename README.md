# runtracking with compose
This is an android application created with jetpack and jetpack compose, applying clean architecture and multi module

## Features

- Track your location route when you are walking/running or cycling
- List of all the previous tracked sessions
- Show details of every tracked session
- You can rate every tracked session with an emoji
- You can see weekly and monthly summary of tracked sessions (Distance, time, etc.)


## Tech

Dillinger uses a number of open source projects to work properly:

- [Framework Android]
- [Clean Architecture] To give the application a solid and easy to scale structure
- [Jetpack] - a set of libraries and tools that allow create robust applications
- [Jetpack Compose] - an UI library to create great User Interfaces
  - [Room] - Room is a persistence library that provides an abstraction layer over SQLite 
  - [LiveData] - Observable data holder class and lifecycle aware
  - [ViewModel] - To store UI related data
- [Retrofit] - awesome library to make http request
- [GSON] - Library to convert JSON to Objects.
- [Dagger Hilt] - A library to do dependency injection in our app


## Requirements

- [Git](https://git-scm.com/) - Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.
- [Java](https://www.java.com/en/) - Java is a programming language and computing platform first released by Sun Microsystems in 1995. Install Java 8 and Java 11.
- [Android Studio](https://developer.android.com/studio) - Android Studio provides the fastest tools for building apps on every type of Android device. Version Bumblebee | 2021.2.1 Patch 1.

## screenshots


## Installation

Clone the repository.

```bash
git clone https://github.com/NYK0de/runtracking_compose.git
git status
```

You have to install Java 8 and Java 11.

Install Android Studio and then open the project...
Only need to execute the run button and will build the project satisfactory.

Or if you want to build and install via terminal, this are steps:

> Note: Set `Java 11` is required for execute gradle tools.
> Note: The `Physical Device` have to have configure the [Developer Options, Debugging USB](https://developer.android.com/studio/debug/dev-options) and connected the device to laptop.

On Mac or Linux
```bash
./gradlew installDebug
```

On Windows
```bash
gradlew.bat installDebug
```
