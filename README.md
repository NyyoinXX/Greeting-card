
# Greeting Cards Application

## Overview
This is a simple React project built with **Vite** and styled using **Tailwind CSS**.

## Features
- **Header Component**: Displays a welcoming title.
- **GreetingCard Component**: Reusable card components that display different greeting messages.
- **Responsive Design**: The layout is fully responsive and adjusts to various screen sizes using Tailwind CSS.

## Technologies Used
- **React**: For building the user interface.
- **Vite**: For fast and modern development tooling.
- **Tailwind CSS**: For styling with a utility-first CSS framework.

## Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd greeting-cards
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

## Usage
1. Start the development server:
   ```bash
   npm run dev
   ```
2. Open your browser and visit:
   ```
   http://localhost:3000
   ```

## File Structure
```
greeting-cards/
├── public/
├── src/
│   ├── index.css        // Tailwind CSS directives and global styles
│   ├── main.jsx         // React entry point
│   ├── App.jsx          // Main application component
│   ├── Components/
│   │   ├── Header.jsx        // Header component
│   │   └── GreetingCard.jsx  // Greeting Card component
├── tailwind.config.js   // Tailwind configuration
├── package.json         // Project dependencies
├── vite.config.js       // Vite configuration
├── index.html           // Entry HTML file
```

## Components
### Header Component (`src/Components/Header.jsx`)
- Displays a center-aligned title with a background.
- Uses Tailwind CSS for styling.

### GreetingCard Component (`src/Components/GreetingCard.jsx`)
- A reusable card component.
- Accepts `title` and `message` as props.
- Styled using Tailwind CSS for a modern card appearance.

### App Component (`src/App.jsx`)
- Combines the `Header` and multiple `GreetingCard` components.
- Arranges the cards in a responsive flex layout.

## Author
- **Name**: Terence Anquandah
- **Role Number**: 10022200077

## License
This project is for educational purposes only.
