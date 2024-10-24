# Van Listing Practice App

## Overview

This project is a simple **van listing app** built for **practicing React routes**. The app displays a list of vans and allows users to filter vans by type. Some parts of the data and functionality are hardcoded, and the app is not dynamic. It is intended to help understand and practice the following concepts in React:
- **React Router** for managing navigation and routing between pages.
- **Component state management** with React hooks.
- **Conditional rendering** and simple filtering logic.

## Features

- **Van Listing**: Displays a static list of vans with some pre-defined properties like name, price, type, and image.
- **Van Details**: Users can click on any van to view more details.
- **Filtering**: Users can filter vans based on type (e.g., campervan, motorhome, etc.).
- **Basic Routing**: The app uses React Router for navigating between the van list, van details, and other pages.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/jumankaushik/van-app.git

2. Navigate to the project directory:
    ```bash
    cd van-app

3. Install dependencies:
    ```bash
    npm install

4. Start the development server:
    ```bash
    npm run dev

5. Open your browser and go to http://localhost:5173 to see the app in action.


### Key Additions:
1. **Installation steps**: Includes Vite-specific commands (`npm run dev`) to start the development server.
2. **React Router setup**: Shows how to install `react-router-dom` and set up basic routes in `main.jsx`.
3. **Build commands**: For generating production builds using Vite (`npm run build`).


