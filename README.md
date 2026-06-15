# CaptionCraft

AI-powered caption generator that creates engaging, creative, and context-aware captions from images or user prompts.

## Overview

CaptionCraft leverages modern AI models to generate high-quality captions for social media posts, blogs, marketing content, and personal use. Simply upload an image or provide a prompt, and the application generates relevant captions instantly.

Whether you're a content creator, marketer, student, or business owner, CaptionCraft helps you save time and improve engagement with AI-generated captions.

## Features

* AI-generated captions in seconds
* Image-to-caption generation
* Multiple caption styles and tones
* Clean and responsive user interface
* Fast and lightweight architecture
* Copy captions with one click
* Mobile-friendly design
* Real-time caption generation

## Tech Stack

### Frontend

* React.js
* Tailwind CSS
* JavaScript

### Backend

* Node.js
* Express.js

### AI Integration

* Gemini API / OpenAI API / Hugging Face Model

### Database

* MongoDB

## Screenshots

Add screenshots of your application here.

### Home Page

![Home Page](./screenshots/home.png)

### Generated Captions

![Captions](./screenshots/result.png)

## Installation

### Clone the Repository

```bash
git clone https://github.com/amandevspace/CaptionCraft.git
```

### Navigate to Project Directory

```bash
cd CaptionCraft
```

### Install Dependencies

Frontend

```bash
cd frontend
npm install
```

Backend

```bash
cd backend
npm install
```

### Configure Environment Variables

Create a `.env` file inside the backend folder.

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
API_KEY=your_ai_api_key
```

### Run the Application

Backend

```bash
npm run dev
```

Frontend

```bash
npm start
```

The application will be available at:

```text
http://localhost:3000
```

## Usage

1. Open the application.
2. Upload an image or enter a prompt.
3. Click Generate Caption.
4. Wait for the AI to process the input.
5. Copy and use the generated caption.

## Project Structure

```text
CaptionCraft
│
├── frontend
│   ├── src
│   ├── public
│   └── package.json
│
├── backend
│   ├── controllers
│   ├── routes
│   ├── models
│   ├── services
│   └── package.json
│
├── screenshots
├── .env
├── README.md
└── LICENSE
```

## Future Improvements

* Multi-language caption generation
* Hashtag recommendations
* AI-powered content optimization
* Social media platform-specific captions
* Caption history and favorites
* User authentication
* Voice-to-caption support


## Author

Aman Kumar

GitHub: https://github.com/amandevspace

---

If you find this project useful, consider giving it a star.
