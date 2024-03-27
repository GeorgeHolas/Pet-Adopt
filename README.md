# Pet Adoption App

This app allows users to browse adoptable pets from an animal shelter and view details about each pet.

## Overview

This is a React app that allows users to:

- View a homepage with pet listings
- Search for pets
- View pet details pages
- Handle 404 pages for invalid pet IDs

## Technologies

- React 
- React Router DOM
- React Testing Library
- Jest
- Mock Service Worker for API mocking

## Folder Structure

- `src/` contains the React code
- `src/pages` contains React components for each page 
- `src/components` contains reusable React components
- `src/mocks` contains mocks for API responses

## Key Files

- `src/App.js` - Main App component that renders pages
- `src/index.js` - Entry point that renders App
- `src/mocks/handlers.js` - Mock API handlers
- `src/mocks/browser.js` - Configures Mock Service Worker

## Getting Started
- Install dependencies
 ```bash
 npm install
```
- Run the app
```bash
 npm start
 ```
- This will start the app at localhost:3000

- Deployed by netlify https://adoptdogrouting.netlify.app/
