# 📱 ParentAlert – Mobile App

**ParentAlert** is a cross-platform mobile application designed to help parents monitor and get alerted about potentially harmful or suspicious activity their children may encounter online.

---

## 🔍 Overview

With increasing digital exposure among children, ParentAlert provides a modern toolset for parents to stay informed and involved — without invading privacy. The app notifies parents in real time when potential risks (keywords, messages, content patterns) are detected in a child’s online activity.

---

## 🎯 Key Features

- 🔔 **Real-time alerts** based on keyword triggers or suspicious behavior
- 👨‍👩‍👧 **Multiple child profiles** per parent account
- ⚙️ **Custom alert settings** per child or category (e.g., bullying, drugs, violence)
- 🔐 **Secure login & token-based authentication**
- 📊 **Activity history** & context previews
- 🌐 **Multilingual support** (planned)

---

## 🧱 Tech Stack

### Mobile App (this repo)
- **Flutter** (Dart) – cross-platform native UI
- **Firebase Cloud Messaging (FCM)** – push notifications
- **Provider / Riverpod** – state management
- **Dio** or `http` – HTTP client for backend communication

### Backend (separate repo)
- **NestJS** (Node.js framework)
- **PostgreSQL** – main database
- **JWT** – for authentication and authorization
- **Socket.IO** (optional) – real-time alert pushing

---

## 📦 Folder Structure

```
lib/
├── main.dart
├── core/
│   ├── config/
│   ├── services/
│   └── utils/
├── features/
│   ├── auth/
│   ├── alerts/
│   ├── child_profile/
│   └── settings/
├── shared/
│   ├── widgets/
│   └── styles/
```

---

## 🧪 Development & Environment

- Configurable via `.env` file (e.g., backend base URL, FCM keys)
- Environment switching (dev/staging/prod)
- Supports both Android and iOS builds

---

## 🚧 Roadmap

- [x] Basic login & JWT auth
- [x] Alert screen UI
- [ ] Child linking workflow
- [ ] Localization & language support
- [ ] Analytics dashboard for parents

---

## 📄 License

This project is under active development and is currently not open-sourced. For partnership or licensing inquiries, please contact the maintainer.

---

**Built with ❤️ to help protect kids in the digital world.**
