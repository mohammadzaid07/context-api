# 🧠 React Context API Demo

This is a simple React app demonstrating the use of **React Context API** to manage user authentication state globally. The app consists of two main components — `Login` and `Profile` — and uses context to share state between them.

## 🌐 Live Demo

🔗 [Click here to view the app](https://mohammadzaid07.github.io/Fruit-Slasher/context-api/)

## 🚀 Features

- ⚛️ Built with React + Vite
- 🔐 Global user state management using React Context API
- 🧾 Simple login form to set user data
- 🙋 Profile page that conditionally renders based on login state

## 🧩 Components

- **Login.jsx**: Accepts username and password, updates user state on submission.
- **Profile.jsx**: Displays welcome message if user is logged in; otherwise, asks to log in.
- **UserContext.js**: Context object for user state.
- **UserContextProvider.jsx**: Provides context with `user` and `setUser`.

## 🛠️ Tech Stack

- React
- Vite
- React Context API
- JavaScript

## 🧪 How It Works

1. The `UserContextProvider` wraps the entire app and provides a `user` object and a `setUser` function.
2. The `Login` component updates the context when a user submits the form.
3. The `Profile` component consumes the context and conditionally renders based on whether a user is logged in.
