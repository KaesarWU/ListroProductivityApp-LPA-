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
    ```

- Or download and install from [https://git-scm.com/download/mac](https://git-scm.com/download/mac)

## Verify installation with:

```bash
git --version
```

## Linux (Debian/Ubuntu)
```bash
Copy
Edit
sudo apt update
sudo apt install git
Verify installation:
```

```bash
Copy
Edit
git --version
```

2. Clone the Repository
Open your terminal or command prompt and run:

bash
Copy
Edit
git clone https://github.com/YOUR_USERNAME/listro.git
cd listro
3. Install Node.js and npm
Download the latest LTS version from https://nodejs.org/

Follow the installation instructions for your OS

Verify installation:

bash
Copy
Edit
node --version
npm --version
4. Install Project Dependencies
Inside the project folder, run:

bash
Copy
Edit
npm install
5. Setup Firebase Credentials
Go to https://console.firebase.google.com/

Create a new project and enable Firestore and Authentication

Create a web app inside the project and copy the Firebase config keys

In your project root, create a file .env.local and add:

env
Copy
Edit
NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
6. Run the Development Server
Start your app locally:

bash
Copy
Edit
npm run dev
Open http://localhost:3000 in your browser to see Listro in action.

7. Build and Export for Production
For GitHub Pages hosting (static export), run:

bash
Copy
Edit
npm run build
npm run export
This will generate an out/ folder with static files.

8. Deploy to GitHub Pages
Push your code to your GitHub repository

Go to GitHub → Settings → Pages

Set the source branch to main (or your default branch)

Choose the /docs folder (if you copy the out/ folder contents there) or configure your deployment to push out/ directly to GitHub Pages

Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

License
This project is licensed under the MIT License.

Contact
Created with ❤️ by YOUR_NAME
