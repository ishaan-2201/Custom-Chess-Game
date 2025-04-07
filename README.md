# Real-Time Chess Game

A real-time chess game application built using Express.js, Socket.io, Chess.js, and EJS. The project allows two players to connect over the internet and play chess with live updates. The chess logic is handled by the chess.js library, and the user interface is rendered using an EJS template and styled with CSS (with Tailwind CSS assistance).

## Features

- **Real-time gameplay:** Uses Socket.io to emit and listen for moves between the client and server.
- **Chess logic:** Implements chess rules (e.g., valid moves, game state updates) using the chess.js library.
- **Responsive UI:** Uses EJS templates and CSS to render a dynamic chessboard interface.

## Game

<img width="929" alt="" src="https://github.com/ishaan-2201/Custom-Chess-Game/blob/main/Game-screenshot.png?raw=true">

## Technologies Used

- **Express.js:** For creating the web server and handling HTTP requests.
- **Socket.io:** For real-time, bi-directional communication between clients and the server.
- **Chess.js:** To handle chess game rules, valid moves, and board state updates.
- **EJS:** For templating and rendering the frontend.
- **CSS/Tailwind CSS:** For styling the chessboard and UI.

## Project Structure

- **app.js:** The backend logic and server setup using Express and Socket.io.
- **index.ejs:** The HTML template for the chess game UI.
- **index.css:** The stylesheet for the chessboard and UI elements.
- **chessgame.js:** The frontend JavaScript that connects with Socket.io, handles user interactions, and integrates chess.js.

## How to Play

- Open the application in your browser.
- Two players can connect (using two different browsers or devices).
- Moves are sent in real-time via Socket.io, and the chess.js library validates them.
- Enjoy playing a full game of chess online!
