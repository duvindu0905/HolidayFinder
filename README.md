Holiday Finder Mobile Application

The Holiday Finder mobile application allows users to explore a wide range of holidays across the globe. Developed using Kotlin in the Android Studio environment, the app features a user-friendly interface and integrates multiple APIs to fetch and display holiday-related information.

Key Features
1. Fetching Data from Public API: Fetches holiday data for a selected country and year.
2. Country Selection: Populates all countries in a spinner using a public API endpoint.
3. Holiday List View: Displays a list of holidays in a RecyclerView.
4. Detailed Holiday Information: Allows users to view additional details about specific holidays.
5. UI Enhancements:
  - Splash screen with progress bar.
  - Smooth navigation between screens with animations.
  - Default location and device data auto-selection.

Tech Stack
1. Language: Kotlin
2. IDE: Android Studio
3. API: [Calendarific API](https://calendarific.com/)
4. Dependencies:
  - Material Design UI: `"com.google.android.material:material:1.9.0-alpha02"`
  - Volley HTTP Library: `"com.android.volley:volley:1.2.1"`

Permissions Used
1. Coarse Location: `android.permission.ACCESS_COARSE_LOCATION`
2. Fine Location: `android.permission.ACCESS_FINE_LOCATION`
3. Internet Access: `android.permission.INTERNET`
