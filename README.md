NAME: GARV PUROHIT INTERNSHIP @ CODETECH IT SOLUTIONS DOMAIN: ANDROID DEVELOPMENT DURATION: 20th June 2025 to 20th July 2025
Overview of the Projects:
# Expense Tracker App

An Android application to help users track their daily expenses, categorize them, and view summaries through visual charts. Built as part of CodTech Internship Task-1.

## Features

- Add daily expenses with category, amount, and description
- View a list of all recorded expenses
- Categorize expenses for better analysis
- View summary of expenses using charts (Pie/Bar)
- Data persistence using Room (SQLite abstraction)

## Tech Stack

- Language: Kotlin
- Architecture: MVVM (Model-View-ViewModel)
- Database: Room (built on SQLite)
- UI: XML Layouts (or Jetpack Compose if preferred)
- Charting Library: MPAndroidChart
- IDE: Android Studio

## Project Structure


## How It Works

1. **Add Expense**  
   - User enters amount, selects category, and provides a description  
   - Data is stored in Room Database  

2. **View Expenses**  
   - Recent transactions displayed in a RecyclerView  
   - Filtered and sorted by date or category  

3. **Summary View**  
   - Displays total expenses by category  
   - Visualized using Pie and Bar charts  

## Requirements

- Android Studio Hedgehog or later
- Gradle 8.x
- Minimum SDK 21
- Internet permission (optional if syncing with cloud or APIs)

## Getting Started

1. Clone this repository
2. Open in Android Studio
3. Sync Gradle
4. Run the app on an emulator or physical device

## Libraries Used

- [Room](https://developer.android.com/jetpack/androidx/releases/room)
- [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart)
- [Jetpack ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel)
- [LiveData](https://developer.android.com/topic/libraries/architecture/livedata)

## Screenshots

*(Add relevant screenshots of your app UI here)*

## License

This project is open-source and free to use under the MIT License.

