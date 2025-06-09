# MediTrack

MediTrack is a modern Android app to help you manage your daily medicines, built with Kotlin and SQLite.  
Easily schedule, track, and get notified about your medications—so you never miss a dose.

---

## 🚀 Features

- **Add & Delete Medicines:**  
  Add medicines with name, dose, time, and select the days of the week for reminders. Remove medicines when they're no longer needed.

- **Smart Reminders:**  
  Receive automatic notifications 30 minutes before your scheduled medicine time.

- **Daily Schedule:**  
  See only today’s scheduled medicines. If none, the app shows “No medicine scheduled for today”.

- **Checkbox Tracking:**  
  Mark each medicine as taken for the day with a simple checkbox. Status resets every day at midnight.

- **Clean UI:**  
  Simple, intuitive interface with orange, white, and black theme.

- **Time & Dose Selection:**  
  Easy time picker and dose dropdown for quick entry.

- **Local Database:**  
  All data is stored securely on your device using SQLite—no internet needed.

---

## 🛠️ How It Works

- **Add Medicine:**  
  Enter medicine name, select dose, time, and days. The app schedules a notification 30 minutes before the set time for each selected day.

- **Medicine List:**  
  The main screen shows only medicines scheduled for today. If there are none, it displays a friendly empty state.

- **Mark as Taken:**  
  Use the checkbox to mark a medicine as consumed. All checkboxes reset automatically at midnight.

- **Delete Medicine:**  
  Remove any medicine from your schedule instantly.

- **Notifications:**  
  The app uses `AlarmManager` and `BroadcastReceiver` to deliver notifications, even if the app is closed (subject to device battery/background settings).

---

## 🏷️ Tech Stack

- Kotlin
- Android SDK
- SQLite
- AlarmManager & Notifications
- RecyclerView

---

## 📝 Installation

1. **Clone this repo** or download the source.
2. Open in **Android Studio**.
3. Build and run on a device or emulator (minSdk 24+).
4. Grant notification and alarm permissions if prompted.

---

## ⚡ Upcoming Features

- Pill inventory & refill reminders
- Medication history and adherence reports
- Notification action: "Mark as Taken" directly from notification
- Custom alarm sound duration
- More UI/UX enhancements

---

