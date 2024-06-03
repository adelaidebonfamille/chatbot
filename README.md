# Chatbot Application

This repository contains a simple chatbot application built using HTML, CSS, and JavaScript. The application allows users to interact with a chatbot that responds to predefined queries.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)


## Installation

To run this application, simply clone the repository and open the `index.php` file in your web browser.

```bash
git clone https://github.com/yourusername/chatbot.git
cd chatbot
```

Make sure you have a local server running, such as XAMPP or WAMP, to properly run PHP files.

## Usage

1. Open `index.php` in your web browser.
2. Type a message in the input box at the bottom of the chat window.
3. Click the send button or press the Enter key to send your message.
4. The chatbot will respond based on predefined responses in the `response.js` file.

## File Structure

```
chatbot/
├── index.php
├── app.js
├── response.js
├── style.css
├── images/
│   ├── bg.jpg
│   ├── mariearistocats3.jpg
│   └── send.png
└── README.md
```

### index.php

This is the main HTML file that structures the chatbot interface. It includes links to the stylesheet and JavaScript files.

### app.js

This JavaScript file contains the logic for handling user input and generating chatbot responses. Key functions include:

- `renderUserMessage()`: Renders the user's message in the chat window.
- `renderChatbotResponse()`: Renders the chatbot's response.
- `renderMessageEle()`: Creates and appends message elements to the chat body.
- `getChatbotResponse()`: Retrieves predefined responses based on user input.
- `setScrollPosition()`: Ensures the chat window scrolls to the latest message.

### response.js

This JavaScript file contains an object `responseObj` with predefined responses to specific user inputs. It also includes a deferred function to set the current time and date.

### style.css

This stylesheet defines the styles for the chatbot interface, including layout, colors, and responsiveness.

### images

This directory contains images used in the chatbot interface, such as the background image, logo, and send button.
