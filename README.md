# Connect 4 - 3D Digital Edition
- A modern, web-based 3D Connect 4 game that brings the classic, competitive gameplay of Connect 4 to life with a visually stunning, physical-like interface.
- Designed with an interactive, 3D-inspired layout, it provides an immersive experience perfect for nostalgic players and new fans alike.

## 🎮 Game Overview
- Connect 4 is a classic two-player strategy game where players take turns dropping colored discs into a 6x7 grid.
- The objective is to be the first to connect four consecutive pieces vertically, horizontally, or diagonally.
- Our digital version captures the essence of the traditional game with a sleek 3D effect, rich colors, and dynamic animations.

## ✨ Features
- **3D Physical Look & Feel**: Experience a realistic Connect 4 game interface inspired by the physical board, with dynamic shading, depth effects, and smooth animations.
- **Interactive UI**: User-friendly, hover and click effects bring each piece to life as players make moves.
- **Winning Highlight Animation**: Winning pieces glow to indicate the victory, adding a celebratory touch.
- **Responsive Design**: Optimized to work seamlessly on desktops, tablets, and mobile devices, adapting the layout to suit any screen size.
- **Error Prevention**: Ensures smooth gameplay by handling invalid moves or clicks outside the play area.
- **Customizable Theme**: Change colors, animations, or sounds easily to personalize the gaming experience (expandable feature).
  
## 🛠️ Technologies Used
- **HTML5**: For creating the game’s core structure and components.
- **CSS3**: Implements the 3D visual styling, background gradients, hover effects, and overall dark theme.
- **JavaScript** (ES6+): Handles game logic, animations, and user interactions, ensuring a smooth and engaging experience.
  
## 📁 Project Structure
- **index.html**: The main HTML file that contains the layout and initial structure of the game board.
- **style.css**: CSS file that defines the appearance, including the 3D look, hover effects, and responsive adjustments.
- **script.js**: JavaScript file that manages game logic, player turns, win conditions, and error handling for invalid moves.

## 🎨 Game Design and Visuals
- **Board Design**: 
The board is designed to replicate the classic Connect 4 look, featuring circular slots and color-coded pieces for each player. The vibrant yellow and red discs create a visually compelling contrast, making it easy for players to distinguish their turns.

- **Piece Effects**: 
Each piece uses radial gradients to mimic real-life plastic discs, with hover effects that simulate the feel of dropping a piece into the board.

- **Winning Animation**: 
Winning pieces glow with a soft pulsating effect, creating a sense of excitement and accomplishment for the winning player.

## 📜 Game Logic and Rules
- **Objective**: Be the first player to connect four of your pieces in a row, column, or diagonal.
- **Turns**: Players alternate turns, with each dropping one piece into an empty column of their choice.
- **Win Condition**: The game checks for four consecutive pieces after every move and announces the winner with a special glow effect on the winning pieces.
- **Draw Condition**: If the board fills up without any player achieving a connect-four, the game declares a draw.
  
## 🤖 Error Handling and Edge Cases
- **Column Full**: If a player tries to drop a piece in a full column, an alert (or subtle visual feedback) will prevent the move.
- **Invalid Inputs**: Only allows valid moves within the grid’s boundaries.
- **Responsive Feedback**: Highlights potential moves with hover effects, guiding players and enhancing accessibility.
  
## 💡 Future Enhancements
- **Sound Effects**: Add satisfying click and drop sounds for a more immersive experience.
- **AI Mode**: Implement a single-player mode with AI for users who wish to play solo.
- **Customizable Themes**: Allow users to choose between different color schemes and themes.
- **Enhanced Animations**: Add animations for dropping pieces, resetting the board, and game-over screen transitions.
