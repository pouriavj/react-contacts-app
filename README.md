# React Contacts App

A simple React project demonstrating reusable components, props, mapping, and styling by rendering a list of fictional contact cards.

---

## Table of Contents

- [Demo](#demo)  
- [Features](#features)  
- [Project Structure](#project-structure)  
- [Technologies Used](#technologies-used)  
- [Getting Started](#getting-started)  
- [Usage](#usage)  


---

## Demo


---

## Features

- Multiple reusable React components (`App`, `Card`, `Avatar`, `Detail`)  
- Passing data via **props**  
- Rendering lists with **map**  
- Component-based **styling** with CSS  
- Clean card layout and responsive design  

---

## Project Structure


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

---

## Technologies Used

<table>
  <tr>
    <td><b>React 19</b></td>
    <td><b>Vite</b></td>
  </tr>
  <tr>
    <td><b>JavaScript (JSX)</b></td>
    <td><b>CSS</b></td>
  </tr>
  <tr>
    <td><b>HTML</b></td>
    <td><b>npm</b></td>
  </tr>
</table>


---

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/pouriavj/react-contacts-app
   cd react-contacts-app
   ```
2. **Install dependencies**
   ```bash
   npm install

   ```
3. **Run the development server**
   ```bash
   npm run dev

   ```
4. Open `http://localhost:5173`
 in your browser.

---

## Usage

- The app renders a list of contact cards from `contacts.js`.  
- Each card displays:
  - Contact name  
  - Avatar image  
  - Phone number and email  
- You can add, remove, or modify contacts in `contacts.js` to update the list dynamically.

   
