Chippity – React Chat App
<p align="center"> A sleek, modern chat interface built using React, custom CSS, and a lightweight rule-based chatbot. </p> <p align="center"> <img src="https://img.shields.io/badge/Made%20with-React-blue" alt="Made with React"> </p>
Table of Contents
About the Project
Tech Stack
Features
Project Structure
How It Works
Usage
Screenshots
License
About the Project
Chippity is a stylish and interactive chat UI built with React and rendered directly in the browser using Babel. Featuring a dark, futuristic interface, smooth animations, and a simple rule-based chatbot engine, it demonstrates how to create a fully functional chat experience without heavy dependencies.
It’s perfect for beginners exploring React basics and for developers who want a minimal, clean chat UI for demos or prototypes.
Tech Stack
React.js – UI rendering and component architecture
ReactDOM – DOM management
Babel – In-browser JSX transpilation
Custom CSS – Complete styling and layout
Simple Rule-Based Chatbot (via supersimpledev/chatbot.js)
Features
🎨 Aesthetic UI: Dark gradient theme with glowing accents
💬 Two-sided Messaging: User and robot messages displayed with avatars
📜 Auto-Scroll Chat Window
⚡ Instant User Input + Delayed Bot Response
🎯 Reusable Components for input, messages, and layout
🖼️ Avatar Support for both sender types
📦 Zero Build Tools Required — runs in any browser
Project Structure
.
├── index.html
├── me.png             # Bot avatar
└── Screenshot.png     # User avatar
Everything runs inside a single HTML file using inline JSX.
How It Works
Chippity is built with three core components:
ChatInput
Handles user input, Enter key submission, and message dispatching.
ChatMessage
Renders individual chat bubbles with adaptive styling for user/robot roles.
ChatMessages
Displays the list of messages and auto-scrolls on new entries.
The chatbot response is generated with Chatbot.getResponse() provided by the external script:
https://unpkg.com/supersimpledev/chatbot.js
React manages state (messages) to update the UI dynamically.
Usage
Clone or Download the Project
Open the project folder and place your images:
me.png → bot
Screenshot.png → user
Simply open the index.html file in any browser — no build or setup needed.
Start chatting with Chippity 💬
Screenshots
(Add screenshots here if you want later.)
License
This project is open-source and licensed under the MIT License. Refer to the LICENSE file for details.
