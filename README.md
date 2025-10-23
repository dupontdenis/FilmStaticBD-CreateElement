# FilmStaticBD-CreateElement

A simple static web application that demonstrates dynamic HTML element creation using JavaScript ES6 modules. This project displays a collection of films with their details using different rendering methods.

## 📋 Overview

This project showcases how to dynamically create and populate HTML elements using JavaScript's `createElement` method and ES6 module imports. It includes a static film database with two different presentation views.

## 🎬 Features

- **Static Film Database**: Pre-defined collection of popular films with details (title, year, director, actors)
- **Actor Salary Data**: Sample salary information stored in a Map structure
- **Two Display Views**:
  - **Table View** (`filmListArray.html`): Displays films in a Bootstrap table format
  - **List View** (`filmListUl.html`): Displays films in an unordered list format
- **Dynamic DOM Manipulation**: Uses `document.createElement()` to build HTML elements programmatically
- **ES6 Modules**: Demonstrates modern JavaScript module system with `import/export`

## 📁 Project Structure

```
FilmStaticBD-CreateElement/
├── index.html           # Main landing page with navigation
├── filmListArray.html   # Table view of films
├── filmListUl.html      # List view of films
├── dataFilms.mjs        # ES6 module containing film data
└── README.md            # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (due to ES6 module CORS restrictions)

### Installation

1. Clone or download this repository:

   ```bash
   git clone https://github.com/dupontdenis/FilmStaticBD-CreateElement.git
   cd FilmStaticBD-CreateElement
   ```

2. Start a local web server. You can use any of these methods:

   **Using Python 3:**

   ```bash
   python -m http.server 8000
   ```

   **Using Node.js (http-server):**

   ```bash
   npx http-server -p 8000
   ```


3. Open your browser and navigate to:
   ```
   http://localhost:8000
   ```

## 💡 Usage

1. Open `index.html` in your browser (through a local server)
2. Choose one of the two viewing options:
   - **View Films**: Displays films in a table format with title and director
   - **View Film List**: Displays films in a list format with title and director

## 📚 Data Structure

### Films Array

Each film object contains:

- `title`: Film title (string)
- `year`: Release year (number)
- `director`: Director name (string)
- `actors`: Array of actor names (array of strings)

### Actor Salaries Map

A Map structure containing actor names as keys and their salaries as values (for demonstration purposes).

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS**: Bootstrap 4.5.2 for styling
- **JavaScript ES6**: Modern JavaScript features
  - ES6 Modules (import/export)
  - Template literals
  - Arrow functions
  - Array methods (forEach)
  - Map data structure

## 🎓 Learning Objectives

This project is ideal for learning:

- Dynamic DOM manipulation with `createElement()`
- ES6 module system
- Bootstrap integration
- Working with JavaScript data structures (Arrays and Maps)
- Modern JavaScript best practices
