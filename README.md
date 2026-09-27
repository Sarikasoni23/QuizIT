# QuizIT

A multi-platform quiz application built with **Flutter/Dart** and a **Node.js + Express + MongoDB** backend.

## Overview

QuizIT is structured as a client-server application. The Flutter client is organised into reusable features, models, providers, widgets, routing, and shared utilities. The backend uses Express, MongoDB through Mongoose, JSON Web Tokens, and bcrypt-based password handling.

## Tech Stack

- **Client:** Flutter, Dart
- **Backend:** Node.js, Express.js
- **Database:** MongoDB, Mongoose
- **Authentication:** JSON Web Tokens, bcryptjs
- **Development:** Nodemon, Git

## Project Structure

- `lib/` — Flutter application source
  - shared/common widgets
  - feature-specific screens, services, and widgets
  - models and providers
  - routing and application configuration
- `server/` — Node.js/Express backend
- `android/`, `ios/`, `web/`, `linux/`, `macos/` — Flutter platform targets
- `test/` — application tests

## Getting Started

### Prerequisites

Install:

- Flutter SDK
- Dart
- Node.js and npm
- Git
- Android Studio or another supported Flutter development environment

### Run the backend

```bash
cd server
npm install
npm run dev
```

### Run the Flutter app

Configure the backend host/IP in the application's global variables, then run:

```bash
flutter pub get
flutter run
```

## Key Engineering Areas

- Modular feature-based Flutter architecture
- API-driven client/server communication
- Authentication-ready backend dependencies
- MongoDB data persistence
- Reusable widgets, models, and provider-based state management

## Repository

GitHub: https://github.com/Sarikasoni23/QuizIT
