# to-do-fullstack
# TaskFlow — Modern To-Do Application

TaskFlow is a premium, feature-rich To-Do application designed for high productivity and a stunning visual experience. Built with a focus on modern aesthetics, it provides a seamless interface for managing tasks, tracking progress, and personalizing your workspace.

![TaskFlow Header](https://images.unsplash.com/photo-1484480974693-6ca0a78fb36b?q=80&w=2072&auto=format&fit=crop)

## ✨ Features

- **Premium UI/UX**: Vibrant colors, sleek dark mode, glassmorphism, and smooth animations using Syne & DM Sans typography.
- **Full Authentication**: Secure Login, Signup, and Password Recovery flows.
- **Task Management**:
  - Add, Edit, and Delete tasks with ease.
  - Set Priority levels (High, Medium, Low) to stay focused on what matters.
  - Interactive checkboxes for instant completion tracking.
- **Progress Tracking**: Real-time progress bar showing your completion percentage.
- **Advanced Filtering**: Filter tasks by status (Pending/Done) or Priority levels.
- **User Personalization**:
  - Customizable profile with bio, phone, and profile pictures (coming soon).
  - Theme customization: Choose from multiple accent colors.
  - Settings: Toggle notifications, sounds, dark mode, and auto-save.
- **Persistence**: All data is saved to LocalStorage, ensuring your tasks remain across browser sessions.

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, Safari).

### Installation
1. Clone or download this repository.
2. Navigate to the `frontend` folder.
3. Open `todo.html` in your browser.

## 🛠️ Technology Stack

- **Frontend**: HTML5, Vanilla CSS3 (Custom Variables & Keyframe Animations), Vanilla JavaScript (ES6+).
- **Backend (Under Development)**: Node.js, MongoDB, Mongoose (as seen in the `backend` folder structure).
- **Fonts**: Syne (Display), DM Sans (Body) via Google Fonts.

## 📂 Project Structure

```text
├── backend/            # Server-side logic and database models
├── frontend/           # Client-side application files
│   └── todo.html      # Main application file
├── README.md           # Project documentation
└── package.json        # Project dependencies
```

## 🔒 Session & Security Fixes

The application includes robust session handling:
- **Case-Insensitive Login**: Emails are handled case-insensitively to prevent login errors.
- **Reference Syncing**: Your session is synchronized with the master user list, ensuring profile updates and password changes persist correctly across tab reloads.

---

Built with ❤️ for productivity.

