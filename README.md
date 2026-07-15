# ReactJS Learning Projects

This repository contains two React-based applications built as part of a ReactJS learning and assignment journey. Together, they demonstrate practical front-end development concepts such as component-based design, state management, routing, API integration, and responsive UI implementation.

## Projects Included

### 1. Expense Tracker (TypeScript)
The Expense Tracker application helps users manage personal expenses in a simple and intuitive way. Users can add new expense entries, view a list of expenses, and see a summary of their spending.

Key features:
- Add new expense items
- Display expenses in a structured list
- Show a summary of totals
- Use a mock backend for data persistence

Technologies used:
- React
- TypeScript
- Bootstrap
- JSON Server

### 2. Movie Application
The Movie Application is a responsive movie browsing interface that allows users to explore different movie categories and view details for selected titles. It includes a navigation experience for browsing popular movie sections and managing favorites.

Key features:
- Browse movie categories such as coming soon, movies in theaters, and top-rated options
- View movie cards with essential information
- Open detailed movie views
- Add or remove movies from a favorites list

Technologies used:
- React
- React Router
- React Icons
- Toast notifications
- JSON Server

## Repository Structure

- expense-tracker-typeScript/
  - client/ - React frontend for the expense tracker
  - server/ - mock API server using JSON Server
- movie-application-reactjs/
  - client/ - React frontend for the movie application
  - server/ - mock API server using JSON Server

## Getting Started

### Prerequisites
Make sure you have the following installed on your machine:
- Node.js
- npm

### Run the Expense Tracker
1. Open a terminal and navigate to the server folder:
   - cd expense-tracker-typeScript/server
   - npm install
   - npm start
2. Open a second terminal and start the client:
   - cd expense-tracker-typeScript/client
   - npm install
   - npm start
3. The frontend should open in your browser, typically at http://localhost:3000.

### Run the Movie Application
1. Open a terminal and navigate to the server folder:
   - cd movie-application-reactjs/server
   - npm install
   - npm start
2. Open a second terminal and start the client:
   - cd movie-application-reactjs/client
   - npm install
   - npm start
3. The frontend should open in your browser, typically at http://localhost:3000.

## Notes
- Each project uses its own local mock server, so both the client and server need to be started separately.
- If port 3000 is already in use, React will prompt you to use another available port.

## Summary
This repository is a small collection of React applications that showcase practical UI development skills and modern front-end practices. It is suitable for learning, reviewing project structure, and understanding how React applications can be organized across separate client and server folders.
