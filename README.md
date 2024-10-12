# Chain Reaction Game

### Overview  
Chain Reaction is a **multiplayer strategy game** developed using **Python and Pygame**. The game involves players strategically placing orbs in cells on a grid-based board, triggering chain reactions through cell explosions. The objective is to **infect opponents' orbs** and dominate the board by managing chain reactions effectively.

### Table of Contents
- [Introduction](#introduction)  
- [Objectives](#objectives)  
- [Gameplay Mechanics](#gameplay-mechanics)  
- [AI Methods](#ai-methods)  
- [Installation](#installation)  
- [How to Play](#how-to-play)  
- [Video Demo](#video-demo)  
- [License](#license)  

---

## Introduction
The **Chain Reaction** game offers a highly engaging and competitive gameplay experience, challenging players' **strategic thinking**. Built as part of a university project, it utilizes **AI algorithms like Minimax, Alpha-Beta Pruning, Genetic Algorithms, and Fuzzy Logic** to enhance the decision-making process of the computer opponent.

---

## Objectives  
The primary objectives of the project are:  
- To develop an **interactive and engaging multiplayer game**.  
- To implement **strategic mechanics** involving the placement and infection of orbs.  
- To build a **visually appealing** and smooth interface using **Pygame**.  
- To provide **responsive controls and animations** for seamless gameplay.

---

## Gameplay Mechanics  
- **Grid Setup**: The game is played on a **5x5 grid**.
- **Turn-based Gameplay**: Players take turns placing orbs in empty cells or their own occupied cells.  
- **Cell Explosion**: A cell explodes when it reaches its critical mass (equal to its number of neighbors), sending orbs to adjacent cells.  
- **Chain Reaction**: Explosions in neighboring cells can cause **cascading chain reactions**, leading to further explosions.  
- **Winning Condition**: The game ends when **one player dominates the grid** or the opponent cannot make any more moves.

---

## AI Methods  
The computer opponent leverages the following advanced AI techniques:  
- **Minimax Algorithm**: Determines the optimal move by simulating possible outcomes.  
- **Alpha-Beta Pruning**: Optimizes Minimax by eliminating redundant branches.  
- **Genetic Algorithm**: Uses evolutionary principles to generate new strategies.  
- **Fuzzy Logic**: Enables nuanced decision-making by handling uncertainty and ambiguity.  

---
