# Tic-Tac-Toe Game

A simple Tic-Tac-Toe game built with React.

## Project Overview

This project is an implementation of the classic Tic-Tac-Toe game where two players can take turns marking spaces in a 3x3 grid. The game declares a winner when one player gets three of their marks in a row (horizontally, vertically, or diagonally), or it ends in a draw if all spaces are filled without a winner.

## Features

-   Interactive 3x3 game board.
-   Players can click on squares to place their mark ('X' or 'O').
-   The game alternates turns between 'X' and 'O'.
-   Displays the current status: next player or winner.
-   A "Restart Game" button to reset the board and start a new game.


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

-   Node.js and npm (or yarn) installed on your machine. You can download Node.js from [https://nodejs.org/](https://nodejs.org/).

### Installation & Running the Project

1.  **Clone the repository (if applicable) or download the project files.**

2.  **Navigate to the project directory:**
    ```bash
    cd path/to/your/tic-tac-toe
    ```

3.  **Install dependencies:**
    Open your terminal in the project root directory (`tic-tac-toe`) and run:
    ```bash
    npm install
    ```
    This command will install all the necessary packages defined in `package.json`.

4.  **Start the development server:**
    After the installation is complete, you can start the development server by running:
    ```bash
    npm start
    ```
    This will open the application in your default web browser, usually at `http://localhost:3000`.

## Available Scripts

In the project directory, you can run:

-   `npm start`: Runs the app in development mode.
-   `npm test`: Launches the test runner in interactive watch mode.
-   `npm run build`: Builds the app for production to the `build` folder.
-   `npm run eject`: Removes this tool and copies build dependencies, configuration files, and scripts into the app directory. If you do this, you can’t go back!

## Built With

-   [React](https://reactjs.org/) - A JavaScript library for building user interfaces.
-   [Create React App](https://github.com/facebook/create-react-app) - Used to set up the development environment.