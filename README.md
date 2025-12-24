# Movie Application

<div>
    <img src="https://img.shields.io/badge/-React_JS-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="react.js" />
    <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=FD366E" alt="appwrite" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
</div>

A modern, feature-rich movie browsing application built with React.js, Appwrite, and TailwindCSS.

## 📋 Table of Contents

1. [Introduction](#introduction)
2. [Tech Stack](#tech-stack)
3. [Features](#features)
4. [Quick Start](#quick-start)
5. [Project Structure](#project-structure)
6. [Environment Setup](#environment-setup)
7. [Available Scripts](#available-scripts)

## 🤖 Introduction

This Movie Application is a personal project that lets you browse trending movies, search for specific titles, and explore content using the TMDB API. It features a responsive, modern design with a sleek user interface that works seamlessly across all devices.

## ⚙️ Tech Stack

- **[Appwrite](https://appwrite.io/)** - Open-source Backend-as-a-Service platform providing authentication, databases, storage, and more for secure, scalable applications.

- **[React.js](https://react.dev/reference/react)** - JavaScript library for building user interfaces with reusable components and efficient state management. Perfect for single-page applications with its virtual DOM optimization.

- **[React-use](https://github.com/streamich/react-use)** - Collection of essential React hooks that simplify state management, side effects, and lifecycle events for cleaner, more maintainable code.

- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS framework providing low-level utility classes for rapid, responsive UI development without writing custom CSS.

- **[Vite](https://vite.dev/)** - Modern build tool offering a fast development environment with hot module replacement (HMR) and optimized production builds.

## 🔋 Features

- **Browse All Movies** - Explore a wide range of movies available on the platform
- **Search Movies** - Easily search for specific movies using the search function
- **Trending Movies Algorithm** - Displays trending movies based on dynamic algorithms
- **Modern UI/UX** - Sleek and user-friendly interface designed for great user experience
- **Fully Responsive** - Works seamlessly across all devices and screen sizes
- **Clean Code Architecture** - Reusable components and well-organized project structure

## 🤸 Quick Start

### Prerequisites

Ensure you have the following installed:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

### Cloning the Repository

```bash
git clone https://github.com/AkhilBejjanki/react-movies.git
cd react-movies
```

### Installation

Install project dependencies:

```bash
npm install
```

### Environment Variables

Create a `.env.local` file in the project root with the following variables:

```env
VITE_TMDB_API_KEY=your_tmdb_api_key_here

VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
VITE_APPWRITE_DATABASE_ID=your_database_id
VITE_APPWRITE_COLLECTION_ID=your_collection_id
```

Get your credentials from:
- **TMDB API**: [TheMovieDatabase API](https://www.themoviedb.org/)
- **Appwrite**: [Appwrite Console](https://appwrite.io/)

### Running the Project

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser to view the application.

## 📁 Project Structure

```
react-movies/
├── src/
│   ├── components/
│   │   ├── Spinner.jsx
│   │   └── ...
│   ├── pages/
│   ├── hooks/
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── public/
├── .env.local
├── package.json
├── vite.config.js
└── README.md
```

## 🚀 Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build for production
- `npm run preview` - Preview the production build
- `npm run lint` - Run ESLint (if configured)

## 📝 Notes

This is a personal project showcasing modern web development practices with React, backend services, and responsive design. Feel free to customize and extend it based on your needs.
