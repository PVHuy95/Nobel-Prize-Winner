# Hello! This is eProject group 1.

## Introduction

The **"Nobel Prize Winner"** website is a project dedicated to honoring **Marie Curie**, the first woman to win two Nobel Prizes. The site features a clean design that highlights key information about her life, groundbreaking research, and notable achievements. With interactive features such as color changes when users hover over content and a timeline that showcases significant milestones in her career, the website offers an engaging way to explore the legacy of Marie Curie.

## Technology Stack

- **React 18.3.1** - UI Library
- **Vite** - Build Tool & Dev Server (migrated from Create React App)
- **React Router DOM** - Client-side routing
- **Bootstrap 5** - CSS Framework
- **React Bootstrap** - Bootstrap components for React
- **Chart.js & Recharts** - Data visualization
- **Leaflet & React Leaflet** - Interactive maps
- **AOS** - Animations on scroll
- **Slick Carousel** - Image carousels
- **Material-UI** - Additional UI components

## Our Group Members

- **Đỗ Thanh Hùng** - Student1574909 (Leader)
- **Đặng Lê Phương Vân** - Student1571999
- **Lê Quốc Đạt** - Student1571990
- **Phù Vĩnh Huy** - Student1571989

## Project Resources

- **Documents reports**: [https://github.com/PVHuy95/Nobel-Prize-Winner/tree/main/Documents](https://github.com/PVHuy95/Nobel-Prize-Winner/tree/main/Documents)
- **Data Test**: [https://github.com/PVHuy95/Nobel-Prize-Winner/tree/main/src/Data](https://github.com/PVHuy95/Nobel-Prize-Winner/tree/main/src/Data)
- **Project demonstration video**: [https://www.youtube.com/watch?v=jXGXXkrxIqo](https://www.youtube.com/watch?v=jXGXXkrxIqo)
- **Live Website**: [https://PVHuy95.github.io/Nobel-Prize-Winner/](https://PVHuy95.github.io/Nobel-Prize-Winner/)

## 🚀 Run Locally

To run this project locally, follow these steps:

### 1. Clone the repository

```bash
git clone https://github.com/PVHuy95/Nobel-Prize-Winner.git
```

### 2. Navigate to the project directory

```bash
cd Nobel-Prize-Winner
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm run dev
```

### 5. Open your browser

Navigate to [http://localhost:3000](http://localhost:3000) to view the website.

## 📜 Available Scripts

In the project directory, you can run:

### `npm install`

Installs all the dependencies required for the project.

### `npm run dev`

Runs the app in development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any errors in the console.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

### `npm run preview`

Locally preview the production build. Run this after `npm run build`.

### `npm run deploy`

Deploys the built app to GitHub Pages.

## 🌐 Deployment

This project is deployed on **GitHub Pages**.

### Steps to Deploy

1. **Build the project:**
   ```bash
   npm run build
   ```

2. **Deploy to GitHub Pages:**
   ```bash
   npm run deploy
   ```

The site will be live at: [https://PVHuy95.github.io/Nobel-Prize-Winner/](https://PVHuy95.github.io/Nobel-Prize-Winner/)

## 📦 Migration from Create React App to Vite

This project was originally created with **Create React App** and has been successfully migrated to **Vite** for:

- ⚡ **Faster development server startup** - Near-instant server start
- 🔥 **Instant Hot Module Replacement (HMR)** - Lightning-fast updates without losing state
- 📦 **Smaller bundle sizes** - More efficient production builds
- 🚀 **Better build performance** - Faster build times using Rollup
- 🛠️ **Active maintenance** - Vite is actively developed, unlike CRA

### Key Changes Made During Migration

- Replaced `process.env.PUBLIC_URL` with `import.meta.env.BASE_URL`
- Converted `require()` statements to ES6 `import`
- Moved `index.html` from `public/` to project root
- Renamed `.js` files containing JSX to `.jsx` extensions
- Created `vite.config.js` for build configuration
- Updated scripts in `package.json`

## 🎨 Using Font Awesome Icons

To use Font Awesome icons in this project:

### Install packages

```bash
npm install @fortawesome/react-fontawesome
npm install --save-dev @fortawesome/fontawesome-free
```

### Import in your component

```javascript
import { FontAwesomeIcon } from '@fortawesome/react-fontawesome';
import { faHome, faSearch } from '@fortawesome/free-solid-svg-icons';
```

## Learn More

- **Vite Documentation**: [https://vitejs.dev/](https://vitejs.dev/)
- **React Documentation**: [https://reactjs.org/](https://reactjs.org/)
- **React Router**: [https://reactrouter.com/](https://reactrouter.com/)
- **Bootstrap**: [https://getbootstrap.com/](https://getbootstrap.com/)

## Acknowledgments

Special thanks to all contributors, instructors, and group members who made this project possible.

Special gratitude to **FPT Aptech Academy** and **eProject** who gave us the chance to be involved in a meaningful and realistic project.

---

**© 2024 Nobel Prize Winner - eProject Group 1**
