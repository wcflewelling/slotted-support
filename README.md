# Slotted Support

Need help, found a bug, or have a feature request? Email
**[wyattflew@yahoo.com](mailto:wyattflew@yahoo.com)** and include your device
model, iOS version, and what happened.

- [Privacy Policy](./privacy.md)

---

Slotted is a SwiftUI iOS app that reads a user's calendar on-device, finds realistic open time slots, and recommends workouts, meals, supplements, stretching, wind-down time, and hydration habits around the day they already have.

## Features

- Calendar-aware daily recommendations for workouts, meals, supplements, stretching, and sleep wind-down.
- Configurable wake time, bedtime, workout duration, workout split rotation, hydration goal, and enabled activities.
- Today, schedule, and week views.
- Optional "Add to Calendar" support for writing recommended activities back to the user's selected calendar.
- Optional local notifications before scheduled activities.
- Local habit tracking for completions, streaks, and hydration.
- Friend profile sharing through QR codes and deep links using `slotted://friend`.
- Local leaderboard based on shared friend snapshots.
- Optional biometric app lock with Face ID, Touch ID, or device authentication.
- App switcher privacy shield that hides app contents when the app is inactive.
- One-time paid download: every feature included, no subscriptions or in-app purchases.

## Requirements

- Xcode 15 or newer recommended.
- iOS 16.0 or newer.
- SwiftUI, EventKit, VisionKit, UserNotifications, and LocalAuthentication.

## Permissions

Slotted asks for these permissions only when needed:

- Calendar access: reads calendar events to find available time slots and writes events when the user chooses "Add to Calendar".
- Notifications: schedules local reminders before recommended activities.
- Camera: scans a friend's QR code.
- Face ID or Touch ID: unlocks the optional app lock. Biometric data is handled by iOS and is never available to the app.

## Privacy

Slotted is designed to be local-first. Preferences, completions, hydration logs, your shareable profile, and friend snapshots are stored on your device. Calendar events are accessed through EventKit on the device. Local notification requests are managed through iOS notification APIs. The app is bought once through the App Store.

Slotted does not operate its own backend server and does not upload your calendar events, habits, hydration logs, friends list, or local preferences to a Slotted server.
