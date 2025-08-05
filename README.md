# Sankalp 2.0 – Cross-Platform Productivity App

Sankalp 2.0 is a cross-platform productivity and habit-tracking application developed using **React Native (Expo)** with backend support via **Hostinger**. It was built as part of an internship project at SpectoV to improve personal and educational productivity through task management, reminders, and syncing features.

---

## 🚀 Features

- 🔐 **User Authentication** — Secure login and registration system
- 🔄 **Real-Time Sync** — Automatically sync tasks and updates across devices
- 📱 **Cross-Platform UI** — Built with React Native (Expo) for Android & iOS
- 🔔 **Push Notifications** — Stay on track with scheduled reminders
- 🧠 **User Dashboard** — Clean, intuitive interface for managing habits, goals, and progress
- 📡 **Backend Integration** — Using Hostinger for authentication, real-time database, and push services

---

## 🛠️ Tech Stack

| Frontend | Backend | Tools |
|----------|---------|-------|
| React Native (Expo) | Hostinger Realtime DB & Auth | Git, GitHub |
| JavaScript | Firebase-compatible services | Visual Studio Code |
| Styled Components / CSS | Push Notifications | Android Studio (optional) |

---

## 📦 Getting Started

### 1. Clone the Repository
``'
git clone https://github.com/Sathwik8888/Sankalp-2.0.git
cd Sankalp-2.0
2. Install Dependencies
bash
Copy
Edit
npm install
3. Start the Development Server
bash
Copy
Edit
npx expo start
You can now scan the QR code on your mobile device using the Expo Go app to view it live.

🔧 Configuration
If your app connects to a specific backend or requires Firebase/Hostinger keys, update the necessary .env or config files:

js
Copy
Edit
// Example config
export const FIREBASE_CONFIG = {
  apiKey: "YOUR_API_KEY",
  authDomain: "your-auth-domain",
  ...
};
📂 Project Structure
bash
Copy
Edit
Sankalp-2.0/
├── assets/                 # Images, fonts
├── components/             # Reusable UI components
├── screens/                # Login, Dashboard, Profile, etc.
├── services/               # Backend integration
├── navigation/             # React Navigation configs
├── App.js                  # Main entry point
└── README.md
👥 Contributors
Gangadhara Sathwik – Developer & Intern

SpectoV Team – Mentorship & Deployment Support

📝 License
This project is licensed under the MIT License.
Feel free to use and contribute!

🙌 Acknowledgements
Hostinger for backend tools

Expo for fast mobile development

React Native community and libraries
