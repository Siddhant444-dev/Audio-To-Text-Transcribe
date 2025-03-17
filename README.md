Audio Transcription System

Overview

This is an AI-powered Audio-to-Text Transcription System built with:

Backend: Spring Boot (Handles API requests, file processing, and OpenAI integration)

AI Model: OpenAI Whisper API (Used for speech-to-text conversion)

Frontend: React + Vite (For a fast and interactive user interface)

Features

Upload Audio Files: Users can upload MP3, WAV, and other formats.

Real-time Transcription: The system processes the file and converts it to text.

Multi-language Support: Works with multiple languages supported by OpenAI Whisper.

User-friendly Interface: Built with React and Vite for a smooth experience.

Download & Copy Transcriptions: Users can download or copy the generated text.

History & Search: Stores previous transcriptions for easy access.

Prerequisites

Before running the project, ensure you have:

Java 17+ (For Spring Boot Backend)

Node.js 18+ (For React Frontend)

PostgreSQL or MongoDB (For storing transcription records)

OpenAI API Key (Required for using Whisper API)

How to Get an OpenAI API Key

Go to OpenAI's website

Sign up or log in.

Navigate to API Keys

Click Create API Key and copy it.

Store it in your backend application as an environment variable.

Installation

Backend (Spring Boot)

Clone the repository:

git clone https://github.com/your-username/audio-transcribe.git
cd audio-transcribe/backend

Set up your OpenAI API Key in application.properties:

openai.api.key=your_api_key_here

Run the Spring Boot application:

mvn spring-boot:run

Frontend (React + Vite)

Navigate to the frontend folder:

cd ../frontend

Install dependencies:

npm install

Start the React app:

npm run dev

Usage

Open the frontend in your browser (default: http://localhost:5173).

Upload an audio file and wait for transcription.

Copy or download the text output.

Contribution

Feel free to fork this repository and submit pull requests for improvements!
