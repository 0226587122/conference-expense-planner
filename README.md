# Conference Event Planner

A React application for planning conference events and managing expenses.

## Features

- Interactive event planning interface
- Budget management tools
- Venue selection functionality
- Responsive design

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
2. Navigate to the project directory:
   ```bash
   cd conference_event_planner
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

### Running the Application

To start the development server:
```bash
npm run dev
```

The application will run on `http://localhost:4137`.

### Project Structure

```
src/
├── App.jsx          # Main application component
├── App.css          # Main styling file
├── ConferenceEvent.jsx  # Event planning component
├── AboutUs.jsx      # About us section component
└── index.js         # Entry point
```

## Components

### App Component
The main application component that manages the overall state and renders other components.

### ConferenceEvent Component
Handles event planning functionality including:
- Venue selection
- Budget management
- Event details input

### AboutUs Component
Displays information about the company or service.

## Available Scripts

- `npm run dev` - Starts the development server
- `npm run lint` - Runs lint testing
- `npm run build` - Builds the production version
- `npm run preview` - Build and run the production version

## Deployment

The application can be deployed to any static hosting service that supports React applications.