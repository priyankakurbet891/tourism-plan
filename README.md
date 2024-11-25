# Tours App

A React-based application to display a list of travel tours with features like viewing detailed descriptions and removing tours.

## Features

- **Dynamic Tour Rendering**: Displays a list of tours fetched from a local dataset.
- **Read More/Show Less**: Toggle between viewing a full or truncated description of each tour.
- **Remove Tour**: Allows users to remove tours from the list.
- **Refresh Option**: When all tours are removed, a refresh button reloads the tour list.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/tours-app.git

## Navigate to the project directory:
bash
Copy code
cd tours-app

## Install dependencies:
bash
Copy code
npm install

## Usage
Start the development server:
bash
Copy code
npm start
Open the app in your browser at http://localhost:3000.

## Project Structure
bash
Copy code
src/
├── Component/
│   ├── Card.js         # Displays individual tour information
│   └── Tours.js        # Manages the list of tours
├── data.js             # Mock dataset for tours
├── App.js              # Main application logic
├── index.js            # Entry point of the app
└── styles.css          # CSS styles for the app

## Components
1. Card Component
Displays a single tour's image, price, name, and description.
Contains a button to remove the tour and a "read more" toggle for descriptions.
2. Tours Component
Renders a list of Card components.
Manages the removal of a tour using props passed from App.
3. App Component
Main component that handles state management for the list of tours.
Displays a refresh button when no tours are left.
Key Files
data.js: Mock data for the list of tours.
App.js: Contains the logic for rendering tours and removing them.

## Example Data Format
javascript
Copy code
const data = [
  {
    id: 1,
    name: "Tour Name",
    info: "Detailed description of the tour...",
    price: "$500",
    image: "image_url",
  },
  // More tour objects...
];
export default data;
License
This project is licensed under the MIT License.

**Happy Coding! 🎉**