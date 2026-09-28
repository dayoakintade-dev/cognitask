# Cognitask

Cognitask is a full-stack AI assistant built with HTML, CSS, JavaScript, Node.js, Express, and the Google Gemini API.

## Live Demo

[View Live Demo](https://cognitask-kj52.onrender.com/)

## Overview

Cognitask is a web-based AI assistant that allows users to communicate with an AI model through a responsive chat interface.

The application supports regular AI conversations as well as file-based requests, allowing users to attach files and ask the AI assistant to analyze them.

The project combines a browser-based frontend with a Node.js and Express backend that communicates securely with the Google Gemini API.

## Key Features

### AI Assistant

- Send messages to the AI assistant
- Receive AI-generated responses
- Ask general-purpose questions
- Start new conversations
- Continue previous conversations
- Manage recent conversations
- Delete conversations

### File Uploads

- Attach files to conversations
- Send uploaded files to the AI for analysis
- Support file uploads up to 20 MB
- Process files through the backend
- Automatically remove temporary uploaded files after processing

### Conversation Management

- Create new chats
- View recent chats
- Switch between conversations
- Delete conversations
- Maintain conversation history in the frontend

### User Interface

- Responsive AI chat interface
- Chat history sidebar
- New chat controls
- Message composer
- File attachment controls
- Attachment preview
- Loading and error states
- Mobile-friendly layout

## Technology Stack

- HTML
- CSS
- JavaScript
- Node.js
- Express.js
- Google Gemini API
- Multer
- dotenv
- Git & GitHub
- Render

## Frontend

The frontend is built with HTML, CSS, and JavaScript.

It provides:

- AI chat interface
- Conversation history
- New chat functionality
- Message input
- File attachment interface
- Attachment preview
- Responsive layout
- Client-side conversation management

## Backend

The backend is built with Node.js and Express.

The Express server handles:

- AI chat requests
- Communication with the Gemini API
- File uploads
- Uploaded file processing
- Request validation
- Error handling
- Temporary file cleanup

### Main AI Endpoint

```http
POST /api/chat
