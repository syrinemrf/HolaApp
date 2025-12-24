# HolaApp

HolaApp is a modern chat and gamification platform built with a Node.js/Express backend and a React frontend. It offers real-time messaging, group chats, status updates, and fun games like Tic-Tac-Toe, all in a user-friendly interface.

---

## Features

- **User Authentication**: Secure sign up, login, password reset, and email verification.
- **Real-Time Chat**: One-to-one and group messaging with instant updates.
- **Status Updates**: Share and view statuses, similar to popular messaging apps.
- **Media Sharing**: Send images and media in chats.
- **Gamification**: Play games like Tic-Tac-Toe directly in the chat.
- **Admin Panel**: Manage users and monitor platform activity.
- **Integration**: Connects with OpenAI and Unsplash APIs for enhanced features.

---

## Technologies Used

- **Frontend**: React, CSS
- **Backend**: Node.js, Express
- **Database**: (Configured via environment variables)
- **APIs**: OpenAI, Unsplash

---

## Getting Started

### Prerequisites
- Node.js (v18+ recommended)
- npm or yarn
- A PostgreSQL database (or your preferred DB)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/syrinemrf/HolaApp.git
   cd HolaApp
   ```

2. **Backend Setup**
   ```bash
   cd backend
   npm install
   cp ../.env.example ../.env
   # Edit .env with your credentials
   npm start
   ```

3. **Frontend Setup**
   ```bash
   cd ../frontend
   npm install
   npm start
   ```

4. **Access the App**
   - Frontend: http://localhost:3000
   - Backend API: http://localhost:5000

---

## Environment Variables

Copy `.env.example` to `.env` and fill in your secrets:
- Database credentials
- JWT secret
- Email credentials
- API keys (OpenAI, Unsplash)
- Frontend/Backend URLs

---

## Project Structure

- `backend/` — Express server, routes, controllers, models, middleware
- `frontend/` — React app, components, pages, context

---

## Author

Developed and maintained by **syrinemrf**.

---

## License

This project is licensed under the MIT License.