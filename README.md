# EMBS


<img width="1200" alt="tsyp" src="https://github.com/user-attachments/assets/d865e595-c33f-47a2-a5a8-3e6fec16c64a">
<br/>
<br/>
<br/>
<br/>
<div align="center">
<img src="https://img.shields.io/badge/IEEE-SUP'COM%20Student%20Branch-00629B?style=for-the-badge&logo=ieee&logoColor=white"/>

  <br/>
  
</div>
</h1>

# VivaMente

## Project logo

<div align= "center">
  <img src="https://github.com/user-attachments/assets/17bf233b-dc1b-48f6-80d4-c841b2ca7526" style="width: 300px; height: auto;">
</div>


---

*VivaMente is an AI-powered platform designed to support bipolar patients by enhancing care and improving treatment outcomes. It streamlines communication between patients and doctors while providing tailored tools for effective management.

The VivaMente Dashboard empowers doctors with tools to efficiently manage patient records, monitor medication schedules, and oversee treatment plans. It also enables real-time video consultations, offering personalized care and improving the doctor-patient connection, all within a user-friendly interface.

📝 *Table of Contents*

- [Website Layout](#-website-Layout-)
- [Technologies used](#-Technologies-used-)
- [Functionalities:](#-Functionalities-)


---

## 📚 Website Layout <a name = "website_layout"></a>

<p align="center">
  <div style="display: inline-block; text-align: center; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/0b1faf96-3150-4984-aadd-076fc0783954" width="400" />
    <p>Dashboard</p>
  </div>
  <div style="display: inline-block; text-align: center; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/3ab91280-843a-4f6e-a122-240a7307e1df" width="400" />
    <p>Patients</p>
  </div>
  <div style="display: inline-block; text-align: center; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/7e34b157-59c6-4671-b587-98e73156f7a5" width="400" />
    <p>Patient</p>
  </div>
  <div style="display: inline-block; text-align: center; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/390e268a-fdc9-4642-8331-f6e6695cf88c" width="400" />
    <p>Add visitation</p>
  </div>
  <div style="display: inline-block; text-align: center; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/c67dd291-41c1-4127-a32a-5dc554c4a8cb" width="400" />
    <p>Video call</p>
  </div>
</p>
---

## 💻 System Design <a name = "System Design"></a>

The Chess Coach Robot is designed to operate in real-time, analyzing ongoing games and providing suggestions and feedback during the game. The system consists of:
- *AI Models*: Reinforcement Learning for move prediction and optimization, Deep Neural Networks for game analysis.
- *Chess Engine Integration*: The robot leverages a chess engine (like Stockfish) for move generation and evaluation.
- *User Interface*: A friendly interface for players to interact with, including move suggestions, coaching tips, and progress tracking.


  <img src="https://github.com/user-attachments/assets/2c77afc6-058b-4c17-bff7-cbd228ffbb9d" alt="Capture d'écran 2024-11-20 184744" style="width: 45%; height: 400px;">
  <img src="https://github.com/user-attachments/assets/5fb84114-ee74-4ff0-b1de-3acd115328b9" alt="Capture d'écran 2024-11-20 185627" style="width: 45%; height: 400px;">

---

## 🤖 AI Models <a name = "AI Models"></a>

The Chess Coach Robot uses several AI models to assist players:
- *Optimal move determining algorithm*: Trained to predict optimal moves based on previous games and the current board state.
- *Game state tracking model*: For detecting the position of the board and the pieces through the phone's camera .
- *Endgame state prediction model*: A model trained to determine the winner/draw of thes chess game given the moves of both players.
- *Chatbot Tutorial Assistant*:A RAG-powered chatbot tutorial that provides interactive guidance, real-time feedback, and error detection to help users build and refine chatbots efficiently.

These models are continually updated and refined based on player feedback and gameplay data to ensure accuracy and effectiveness.

---

## 🎮 Game Interface <a name = "Game Interface"></a>

The Chess Coach Robot interacts with a graphical chess board, offering real-time move suggestions, evaluations, and coaching feedback. Key features include:
- *Move Suggestions*: The robot provides the best possible moves in any given position.
- *Training Mode*: Players can practice specific scenarios or strategies, with the robot offering tailored coaching.
- *Game Analysis*: After each game, the robot provides a detailed breakdown of key moments, suggesting improvements for future games.

---

## 🏗️ Architecture and Infrastructure <a name = "Architecture and Infrastructure"></a>

The Chess Coach Robot's architecture is built on a modular, scalable system, which includes the following components:

- *Frontend*: A user-friendly interface, where players can view the board and interact with the robot’s suggestions.
- *Backend*: A server that processes game data, handles player inputs, and interacts with the AI models.
- *Chess Engine*: The robot integrates with a chess engine to generate moves and evaluate game positions.
- *AI Models Server*: A dedicated server running the trained AI models to generate move predictions and provide coaching feedback.
  <div style="text-align: center;">
  <img src="https://github.com/user-attachments/assets/d5f6fe5b-4125-4f6e-b62c-4b3498595837" alt="462570214_1547938229180262_3988160215688193654_n" style="width: auto; height: 400px;">
</div>
---

### Architecture Flow: <a name = "Architecture Flow"></a>
1. The player moves a piece on the board, which is sent to the backend server.
2. The server processes the move and sends the updated game state to the AI models server.
3. The AI models server evaluates the board and generates suggestions for the next move.
4. The suggestion is sent back to the frontend interface, where it is displayed to the player.
5. The system continues to provide coaching and analysis throughout the game.

---
## Chess coach robot features : <a name = "Chess coach robot features"></a>
- *Chess tutorial* : To make our chess learning platform more attractive, we integrated an AI-driven chat-
bot as a dynamic tutorial. Instead of using static text-based lessons, this interac-
tive approach adapts to user queries in real time.
- *Chess puzzles*: Learning through playing chess puzzles is an engaging and structured process that helps
players gradually improve their chess skills and broader cognitive abilities.
<br/>
These puzzels have specific goals such as check-mating in a certain number of moves , avoiding check-mate and gaining material.
---



---
## 🎥 Solution Demo

<div align="center">
  
   [<img src="https://img.shields.io/badge/Watch%20Demo%20Video-FF0000?style=for-the-badge&logo=youtube&logoColor=white"/>](https://drive.google.com/drive/folders/1zmqwx9dBeI5y70cL6vh-oSn7sQvfUN8z?fbclid=IwY2xjawGrQ9ZleHRuA2FlbQIxMAABHbkFiX1TmhQ9TrNX3wGc21LhJ39sAgIUbbC-evb8BcZxLqZxQUijK7kBZg_aem_OwUX2wH88aHbjLkP9w18TA)
  <br/>
  Watch our complete solution demonstration showcasing:
  - 🛡️ Real-time threat detection
  - 🤖 AI-driven analysis
  - 🔄 Automated response system
  - 📊 Live dashboard monitoring

  <i>Click the button above to view the full demonstration</i>
</div>





github.com
