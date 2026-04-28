#  Data Management App (Flutter)

##  Overview
This is a Flutter application developed as part of an internship assignment.  
It demonstrates **state management using setState** and **persistent local storage using SharedPreferences**.

The app contains two main modules:
-  Counter App
-  To-Do List App

---

##  Features

###  Counter App
- Increment and decrement counter value
- Uses `setState` for state management
- Saves data locally using `SharedPreferences`
- Restores last saved value on app restart

---

###  To-Do List App
- Add new tasks
- Delete tasks from list
- Displays tasks in a scrollable ListView
- Saves tasks locally using `SharedPreferences`
- Data persists even after app restart

---

##  Technologies Used
- Flutter
- Dart
- SharedPreferences (Local Storage)
- Material 3 UI

---

##  Local Storage Implementation
- Counter value stored with key: `counter`
- Task list stored as JSON string with key: `tasks`

---

##  Project Structure
lib/
├── main.dart
├── CounterPage
├── TodoPage

---

##  How to Run the Project

### 1. Install dependencies
```bash
flutter pub get
flutter run