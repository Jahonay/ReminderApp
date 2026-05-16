# ReminderApp

## Basic push notification reminder app

- Add reminders via a floating + button — enter a title, optional message, pick a date and time
- Scheduled notifications fire exactly at the chosen time using AlarmManager (works even when the app is closed)
- Reminder list shows all upcoming reminders; past ones are visually dimmed with a ✓
- Delete any reminder (also cancels the scheduled alarm)

## Setup steps

1. Open Android Studio → "Open" → select the ReminderApp folder
2. Let Gradle sync finish
3. Run on a device or emulator (API 26+)

### Android 12+ note on exact alarms
On Android 12 (API 31+), users may need to grant "Alarms & Reminders" permission manually:

Settings → Apps → Reminders → Permissions → Alarms & Reminders → Allow
