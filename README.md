# Chirp — Mini Social Media App

Chirp is a small social-media-style web application built with HTML, Tailwind CSS and Firebase Realtime Database.

> **Designed and Developed by Haritha Kongi**

## ✨ Features

- Simple registration flow
- Username/email-based demo login
- Create short posts up to 280 characters
- Real-time post feed
- Like posts
- Add comments
- Character counter
- Logout flow
- Firebase Realtime Database integration
- Responsive interface

## 🛠️ Tech Stack

- HTML5
- JavaScript
- Tailwind CSS
- Firebase Realtime Database
- Firebase JavaScript SDK

## 🏗️ How It Works

1. A user registers with a username and email.
2. User information is stored in Firebase Realtime Database.
3. The user can create short posts.
4. Posts are stored under the Firebase `posts` collection.
5. The feed updates in real time.
6. Users can like posts and add comments.

## 📁 Project Structure

```text
social-media-mini-app/
├── index.html
├── firebase.json
├── .firebaserc
├── .gitignore
└── README.md
```

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/HarithaKongi/social-media-mini-app.git
cd social-media-mini-app
```

The application is a single-page HTML project. Open `index.html` in a browser or serve the folder with a local web server.

## 🔐 Security Note

This project is an educational/demo application. It should **not** be treated as a production social platform.

The current implementation uses a lightweight username/email demo login rather than Firebase Authentication. Before production use, authentication and Firebase Realtime Database Security Rules should be strengthened and validated.

Firebase web configuration values are not a substitute for database authorization. Real secrets should never be committed to the repository.

## 👤 Author

**Haritha Kongi**

- GitHub: https://github.com/HarithaKongi

---

⭐ Built as a Firebase and frontend learning project.
