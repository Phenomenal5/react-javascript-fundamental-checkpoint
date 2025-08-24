# React Bootstrap Component Project

A foundational React application built to practice core concepts and integrate the **React-Bootstrap** library.  
This project demonstrates the setup of a modern React environment and the implementation of key UI components like a navigation bar and cards.



---

## 📖 Table of Contents
- [About The Project](#-about-the-project)  
- [Built With](#%EF%B8%8F-built-with)  
- [Prerequisites](#-prerequisites)  
- [Installation & Setup](#-installation--setup)  
- [Project Structure](#-project-structure)  
- [Key Implementation Details](#-key-implementation-details)  
- [Resources](#-resources)  

---

## 🧐 About The Project
This project was created as a learning exercise to achieve the following objectives:

- Initialize a modern React application using **create-react-app**.  
- Integrate and utilize the **React-Bootstrap** component library to build a responsive UI.  
- Understand the structure of a React component, including the use of **React Fragments**.  
- Practice building common web elements: a navigation bar, a heading, and card components.  

The app serves as a template for future projects and a hands-on demonstration of basic React principles.

---

## ⚙️ Built With
This project was built with the following technologies and libraries:

- [React](https://react.dev/) – A JavaScript library for building user interfaces.  
- [Create React App](https://create-react-app.dev/) – Official way to bootstrap React apps.  
- [React-Bootstrap](https://react-bootstrap.github.io/) – Popular Bootstrap components rebuilt for React.  
- [Bootstrap](https://getbootstrap.com/) – Open-source front-end toolkit for responsive design.  

---

## ✅ Prerequisites
Before you begin, ensure you have the following installed on your machine:

- [Node.js](https://nodejs.org/) (v14 or higher)  
- npm (bundled with Node.js) or [Yarn](https://yarnpkg.com/)  
- A code editor like [Visual Studio Code](https://code.visualstudio.com/)  

---

## 💻 Installation & Setup
Follow these steps to get a local copy of this project up and running:

### 1. Clone the repository
```bash
git clone <your-repository-url>
cd <project-name>
```
### 2. Install dependencies
```
npm install
```
### 3. Start the development server
```
npm start
```

The app will automatically open in your browser at http://localhost:3000
. The page will reload automatically when you make changes.

## 📁 Project Structure

After setup, the src directory structure is minimal and focused:
```
src/
├── App.js             # Main App component with Navbar, Heading, and Cards
├── index.js           # Entry point of the application
└── reportWebVitals.js # Optional performance monitoring
```

## 📜 Key Implementation Details

- *App.js:* The main component uses a React Fragment (<>...</>) to avoid unnecessary wrapper DOM elements. Inside, a div with the class "App" contains all JSX.

- *Components:*

    - A responsive Navbar from React-Bootstrap.

    - A main Heading.

    - Three Card components, showcasing how to use props like title, text, and buttonText.
---
## 🔗 Resources

- React Documentation

- React-Bootstrap Documentation

- Bootstrap Documentation

- Create React App Documentation
