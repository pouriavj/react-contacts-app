# React Contacts App

A simple React project demonstrating component-based architecture, props, mapping, and styling. This app renders a list of contact cards using reusable React components.

---

## Table of Contents

- [Demo](#demo)  
- [Features](#features)  
- [Project Structure](#project-structure)  
- [Technologies Used](#technologies-used)  
- [Getting Started](#getting-started)  
- [Usage](#usage)  
- [License](#license)  

---

## Demo



---

## Features

- Multiple reusable React components (`App`, `Card`, `Avatar`, `Detail`)  
- Passing data via **props**  
- Rendering lists with **map**  
- Component-based **styling** with CSS  
- Clean and responsive card design  

---

## Project Structure

react-contacts-app/
├─ public/
│ └─ styles.css
├─ src/
│ ├─ components/
│ │ ├─ App.jsx
│ │ ├─ Card.jsx
│ │ ├─ Avatar.jsx
│ │ └─ Detail.jsx
│ ├─ contacts.js
│ └─ index.jsx
├─ index.html
├─ vite.config.js
├─ package.json
├─ package-lock.json
├─ .gitignore
└─ README.md


- `App.jsx`: Main component rendering the list of contacts  
- `Card.jsx`: Displays each contact card  
- `Avatar.jsx`: Shows contact image  
- `Detail.jsx`: Shows contact details (phone, email)  
- `contacts.js`: Fictional contact data array  
- `styles.css`: Styling for cards and layout (inside `public`)  
- `index.html`: Entry HTML file  
- `index.jsx`: Entry point for React app  
- `vite.config.js`: Vite configuration  
- `package.json` & `package-lock.json`: Project metadata and dependencies  
- `.gitignore`: Files/folders to ignore in Git  
- `README.md`: Project documentation

