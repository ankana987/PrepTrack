# PrepTrack – Your Personalized Interview Preparation Tracker

**Turn your interview preparation into a structured, measurable, and consistent learning journey.**

PrepTrack is a personalized interview preparation platform that helps students organize coding questions, monitor their daily progress, and stay consistent while preparing for technical interviews.

Instead of managing coding questions through scattered notes, spreadsheets, or multiple platforms, PrepTrack provides a centralized dashboard to track preparation progress and identify what needs more attention.

---

## Problem Statement

Students preparing for technical interviews often solve coding problems across multiple platforms but struggle to maintain a proper record of their progress. They may forget which questions they have completed, which concepts need revision, and how consistently they are practicing.

Traditional tracking methods, such as spreadsheets and handwritten notes, can become difficult to maintain over time. Moreover, students often lack a clear visual representation of their preparation progress, making it harder to stay motivated and identify areas that need improvement.

**PrepTrack aims to solve this problem by providing a centralized, organized, and customizable platform for managing the entire interview preparation journey.**

## Our Solution

PrepTrack brings question management, progress visualization, and personalization together in one platform.

Users can organize coding questions based on their preparation status, monitor their daily achievements through visual analytics, and customize the website's appearance according to their preferences.

The goal is simple: **Prepare smarter, track consistently, and stay interview-ready.**

---

##  Key Features

### 1.  Interactive Dashboard
- Get an overview of your interview preparation.
- View total questions and their completion status.
- Monitor your preparation progress through visual charts.
- Track the number of questions completed each day.

### 2.  Question Management
Organize coding questions into three categories:

- **Completed:** Questions successfully solved.
- **In Review:** Questions that need revision or further practice.
- **Not Started:** Questions that are yet to be attempted.

Users can add, edit, delete, and manage their questions.

### 3.  Daily Progress Tracking
- Visualize your daily coding activity.
- Monitor your consistency over time.
- Understand your preparation progress through graphical insights.

### 4.  Personalized Theme Customization
- Customize the website's appearance.
- Change the background and theme colors.
- Create a workspace that matches your personal preferences.

### 5.  Organized Question Filtering
- Filter questions according to their current status.
- Find specific questions more easily.
- Keep your preparation organized.

### 6.  Data Persistence
- Save question data using browser Local Storage.
- Retain changes when the page is refreshed.

---

## Tech Stack

| Technology | Purpose |
|---|---|
| React.js | Frontend development |
| JavaScript | Application logic and interactivity |
| CSS | Styling and responsive UI |
| Recharts | Data visualization and progress graphs |
| Vite | Development server and build tool |
| Local Storage | Client-side data persistence |

**Planned backend expansion:** Node.js, Express.js, and MongoDB for authentication, cloud-based storage, and multi-user support.

---

## Getting Started

Follow these steps to run PrepTrack locally.

### Prerequisites

Make sure you have installed:

- Node.js
- npm
- Git

### 1. Clone the Repository

```bash
git clone <YOUR_REPOSITORY_URL>
```

### 2. Navigate to the Project Directory

```bash
cd PrepTrack
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Start the Development Server

```bash
npm run dev
```

### 5. Open in Browser

Open the local URL displayed in your terminal, usually:

```text
http://localhost:5173
```

---

## Project Architecture

The project follows a component-based React architecture.

The application is organized around reusable UI components, question management, dashboard analytics, and theme customization.

As the project expands, the architecture can be extended with:

- Authentication and protected routes.
- Backend APIs.
- MongoDB database integration.
- Individual user dashboards.
- Cloud-based progress synchronization.

---

##  Future Enhancements

PrepTrack is designed to grow beyond a basic question tracker.

Planned improvements include:

- [ ] User registration and login.
- [ ] Individual dashboards for multiple users.
- [ ] MongoDB integration for persistent cloud storage.
- [ ] Personalized preparation goals and daily targets.
- [ ] Topic-wise and difficulty-wise question tracking.
- [ ] Revision reminders for questions in review.
- [ ] Streak tracking to encourage consistency.
- [ ] More theme customization options.
- [ ] Progress reports and advanced analytics.

---

## Target Users

- College students preparing for campus placements.
- Students preparing for software engineering interviews.
- Beginners learning Data Structures and Algorithms.
- Developers who want to maintain a structured coding practice routine.

---

## What Makes PrepTrack Different?

PrepTrack is not just another coding question tracker. It combines **progress management, daily performance visualization, and user-driven customization** in a single workspace.

Rather than simply counting solved problems, it encourages students to understand their preparation patterns, identify questions that need revision, and build a consistent practice habit.

Its modular architecture also provides a foundation for expanding into a multi-user interview preparation platform.

---

##  Developed With

Built with ❤️ and a passion for making interview preparation more organized and productive.

**Project Name:** PrepTrack  
**Category:** Productivity / Education / Interview Preparation  
**Status:** Frontend Prototype – Under Development

---

*Your preparation. Your progress. Your pace.*