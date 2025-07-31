# Listro Productivity App (LPA)

**Listro** is a minimalist, full-stack productivity web app designed to help you organize your tasks, manage your time, and stay focused. Built with modern web technologies, Listro offers a clean and intuitive interface inspired by apps like Notion and Raycast.

---

## Features

- **Authentication**  
  Sign in securely with Google, Microsoft, or Email/Password using NextAuth.js and Firebase Authentication.

- **Task Management**  
  Easily create, update, and delete tasks synced in real-time via Firebase Firestore.

- **Pomodoro Timer**  
  Stay productive with a built-in Pomodoro timer that supports start, pause, and reset functions.

- **Calendar View**  
  Visualize tasks and deadlines with a calendar interface.

- **Dark & Light Theme**  
  Toggle between light and dark modes for comfortable usage at any time.

---

## Tech Stack

- **Frontend:** Next.js 14 (React 18), Tailwind CSS  
- **Backend:** Firebase (Firestore, Authentication)  
- **Auth:** NextAuth.js (Google, Microsoft, Email)  
- **Deployment:** Static export hosted on GitHub Pages or Vercel

---

## Getting Started

### 1. Prerequisites: Install Git

Listro uses Git for version control and collaboration. If you don't have Git installed, follow these instructions based on your operating system:

#### Windows

1. Download Git for Windows from [https://git-scm.com/download/win](https://git-scm.com/download/win)  
2. Run the installer and follow the prompts (default options are fine)  
3. After installation, open **Git Bash** from the Start menu to use Git commands

#### macOS

- Using Homebrew (recommended):

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install git
