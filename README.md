# App-Keeper-2

# Keeper App

A React-based application that simulates a notes-keeping app, allowing users to view a collection of pre-defined notes. This project demonstrates component-based architecture in React, using props to pass data and rendering multiple components with dynamic content from a dataset.

## Table of Contents

1. [Overview](#overview)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Features](#features)
5. [Technologies](#technologies)
6. [Scripts](#scripts)
7. [License](#license)

## Overview

This app utilizes React components to render a set of notes stored in an array. The data is mapped to dynamically generate individual `Note` components, each displaying a title and content. The project is designed to help users practice handling React props, mapping over arrays, and managing components.

## Installation

### Prerequisites

- Node.js (version 14 or above)
- npm (version 6 or above)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/jbolan12/App-Keeper-2.git

   Navigate to the project directory:

bash
cd your-repo

**Install the dependencies:**

bash
npm install

**Start the development server:**

bash
npm start
Open http://localhost:3000 in your browser to view the app.

## Usage
Data Structure
The notes.js file exports an array of note objects, each containing a key, title, and content.

**Example entry in notes.js:**

javascript

const notes = [
  {
    key: 1,
    title: "Delegation",
    content: "Q. How many programmers does it take to change a light bulb? A. None – It’s a hardware problem",
  },
  // More notes...
];
export default notes;

## Components
- App: The root component that renders Header, all Note components, and Footer.
- Header: Displays the title "Keeper" at the top of the app.
- Footer: Displays the current year.
- Note: Renders individual notes, receiving title and content as props.
- Rendering Notes
- The App component uses .map() to iterate over the notes data, passing title and content to each Note component.

## Features
- Reusable Components: Header, Footer, and Note components are designed to be reusable.
- Props Usage: Passes data to components using props to dynamically render content.
- JavaScript Array Methods: Utilizes .map() for creating lists of components from data.
- Styling with CSS: Basic styling in styles.css for a simple and clean UI.

## Technologies
React (v18.3.1)
React-Dom (v18.3.1)
React-Scripts(v5.0.1)
CSS for styling



## Scripts
start: Runs the app in development mode with react-scripts start.
build: Builds the app for production with react-scripts build.
test: Runs the test suite with react-scripts test --env=jsdom.
eject: Ejects the app from Create React App configuration.


## License
This project is licensed under the MIT License.


