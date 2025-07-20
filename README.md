# 📚 Student Lecture Management App

A **React Native** mobile application designed to help university students manage their lectures efficiently. Students can view upcoming lectures, receive automated reminders, check daily schedules, and stay organized throughout the semester.

---

## 🚀 Features

- 📅 View upcoming lectures in a clean timeline
- ⏰ Set and receive lecture reminders/notifications
- 🗓️ See daily or weekly lecture schedules
- 🔔 Push notifications for lecture updates
- 📚 Access course details and lecture locations
- 🎯 User-friendly and responsive interface

---

## 🛠️ Tech Stack

| Technology      | Description                        |
|----------------|------------------------------------|
| React Native    | Cross-platform mobile development  |
| Expo / Bare RN  | App bootstrapping (choose one)     |
| Firebase / Backend API | For data storage & authentication |
| React Navigation| Navigation between screens         |
| AsyncStorage    | Store user preferences locally     |
| Push Notifications | Local/remote reminders           |

---

## 🧪 Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/student-lecture-manager.git
cd student-lecture-manager

npm install
# or
yarn install

npx expo start
# or, if using bare React Native
npx react-native run-android
npx react-native run-ios

src/
│
├── components/       # Reusable UI components
├── screens/          # App screens (Home, Schedule, Details)
├── services/         # Notification and API logic
├── navigation/       # React Navigation setup
├── config/           # Firebase or API config
└── utils/            # Helper functions
