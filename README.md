# React Data Fetching Application

This project is a simple React application that fetches data from an API and displays it dynamically based on the selected data type. The available data types are **users**, **posts**, and **comments**, fetched from `https://jsonplaceholder.typicode.com/`. 

## Features

- Fetch and display data based on the selected type (users, posts, comments).
- Dynamic button-based selection to toggle between different data types.
- Component-based architecture with reusable components for easy customization.

## Project Structure

```plaintext
src/
├── components/
│   ├── Form.js          # Form with buttons to select data type
│   ├── Button.js        # Button component for each data type
│   ├── List.js          # List component to display items
│   └── ListItem.js      # Individual list item component
├── App.js               # Main application component
├── index.js             # Application entry point
└── styles.css           # Basic styles
