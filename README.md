# Windows XP Portfolio

A personal portfolio website designed to replicate the nostalgic user interface of the Windows XP operating system.
This project showcases my professional experience, personal information, projects, and contact methods through
interactive desktop windows, custom-managed state applications, and real-time UI components.

---

## Live Website
[View Live Portfolio]

---

## Tech Stack

### Frontend & Architecture
* **Astro Framework** - Used for fast page loads, component-based structure, and optimized build delivery.
* **CSS** - Leveraged for precise, retro UI styling and responsive layouts.
* **TypeScript** - Implements strict type safety for interactive UI states, window manipulation algorithms, and navigation history stacks to prevent runtime errors.

---

## Key Features
* **Retro Window Management System:** Draggable, resizable, and minimizable application window that acts like a real folder system.
* **Functional Folder Management System:** Selecting folders navigates to desired information, displaying professional experience, about me, projects, and contact information.
* **Responsive Taskbar & Navigation:** Fully functional taskbar applet utility that tracks browser history states for fluid back and forward window navigation.

---

## Project Structure

```text
├── public/             # Static assets
├── src                     
│   ├── assets          # Images for folders
│   ├── components      # UI Components (Taskbar, Work Info, etc.)
│   ├── layouts         # Base HTML and metadata templates
│   └── pages           # Main Astro pages
└── package.json
```

---

## Setup & Installation
Follow these steps to clone the project:

### Prerequisites
Make sure you have [Node.js](https://nodejs.org/) installed (v18+).

### 1. Clone the Repository
```bash
git clone https://github.com/JesusCazares2/windows-xp-portfolio.git
cd windows-xp-portfolio
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Start the Development Server
```bash
npm run dev
```
