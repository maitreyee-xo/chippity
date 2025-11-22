<h1 align="center">Chippity – React Chat App</h1>

<p align="center">
  A sleek, modern chat interface built using React, custom CSS, and a lightweight rule-based chatbot.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Made%20with-React-blue" alt="Made with React">
</p>

## Table of Contents

- [About the Project](#about-the-project)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Project Structure](#project-structure)
- [How It Works](#how-it-works)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [License](#license)

## About the Project

Chippity is a stylish and interactive chat UI built with React and rendered directly in the browser using Babel. Featuring a dark, futuristic interface, smooth animations, and a simple rule-based chatbot engine, it demonstrates how to create a fully functional chat experience without heavy dependencies.

It’s perfect for beginners exploring React basics and for developers who want a minimal, clean chat UI for demos or prototypes.

## Tech Stack

- **React.js** – UI rendering and component architecture  
- **ReactDOM** – DOM management  
- **Babel** – In-browser JSX transpilation  
- **Custom CSS** – Complete styling and layout  
- **Simple Rule-Based Chatbot** (via `supersimpledev/chatbot.js`)  

## Features

- 🎨 **Aesthetic UI**: Dark gradient theme with glowing accents  
- 💬 **Two-sided Messaging**: User and robot messages with avatars  
- 📜 **Auto-Scroll Chat Window**  
- ⚡ **Instant User Input + Delayed Bot Response**  
- 🎯 **Clean & Modular Components**  
- 🖼️ **Avatar Support**  
- 📦 **Zero Build Tools Required** — runs in any browser  


## How It Works

Chippity is built with three core components:

- **ChatInput**  
  Handles user input, Enter key submission, and message dispatching.

- **ChatMessage**  
  Renders chat bubbles with styling based on sender type.

- **ChatMessages**  
  Displays all messages and auto-scrolls on updates.

The chatbot responses are generated using:

https://unpkg.com/supersimpledev/chatbot.js


React state (`messages`) dynamically updates the UI as conversations progress.

## Usage

1. **Clone or download the project**
2. Add your avatar images:
   - `me.png` → bot  
   - `Screenshot.png` → user
3. Open `index.html` directly in any browser.
4. Start chatting with Chippity 💬

## Screenshots

(Add screenshots here)

## License

This project is open-source and licensed under the **MIT License**. Refer to the LICENSE file for full details.

